在C:用户/用户名 文件夹中添加.wezterm.lua文件配置：

```lua
-- Pull in the wezterm API
local wezterm = require 'wezterm'

return {
	default_prog = {"C:\\Users\\32248\\AppData\\Local\\Microsoft\\WindowsApps\\Microsoft.PowerShell_8wekyb3d8bbwe\\pwsh.exe", "-NoLogo"},
	default_cwd = "C:\\Users\\dyzag\\Downloads",
}

```

