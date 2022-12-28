# Handy Tips

## Lua (Roblox)
- print() --> prints a string (typically) and provides an output
- wait() --> creates a delay in a script, and helps with making sure the lines of code do not go very quickly
- warn() --> identical to print(), but displays in orange text
- game.[parent].[child].[property] to change a property
- [variable_name] = [""/#/boolean]
- variables can help minimise scripting time (e.g. `game.Workspace.MyPart` can be `mypart = game.Workspace.MyPart`, which can result in `mypart.Material = "Brick"` rather than `game.Workspace.MyPart.Material = "Brick"` )
- variables store data to help your code to be much more concise
- `Instance.new` is a helpful line of code that helps you create any object and you are also able to edit it like you would edit the existing object
- With a script in a part, the script can refer to the part as its parent because it is inside it, so the variable can be `part = script.Parent`
- Roblox uses Vector3 to determine an object's position, which is XYZ
- You can change the position of the object by using functions such as `part.Position = Vector3.new(X, Y, Z)`
- While loops are handy to make sure something keeps repeating until something has not been fulfilled