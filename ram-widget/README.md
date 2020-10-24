# Ram widget

This widget shows the RAM usage. When clicked another widget appears with more detailed information:

![screenshot](./out.gif)

## Installation

```
local ram_widget = require("awesome-wm-widgets.ram-widget.ram-widget")
...
s.mytasklist, -- Middle widget
	{ -- Right widgets
    	layout = wibox.layout.fixed.horizontal,
		...
		ram_widget(),-- default
		...
```
Please refer to the [installation](https://github.com/streetturtle/awesome-wm-widgets#installation) section of the repo.
