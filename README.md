# Simple-Tuttle-Draw-Module-in-Roblox-Studio (PenTool)
A turtle-graphics style drawing system for Roblox.

Draw shapes by moving a "brush" that leaves parts behind.

---

## Demo

https://youtu.be/obObfvHoQpk

---

##  Features

- OOP-based
- Tween
- Customizable brush (size, color, material)
- Custom command support

---

##  Setup

```lua
local PenTool = require(game.ReplicatedStorage.PenTool)

local board = PenTool.new(
	Vector3.new(1, 1, 1),
	Color3.fromRGB(0, 229, 255),
	Enum.Material.Plastic,
	true,
	true
)
```

Instruction are inside the Notes script
