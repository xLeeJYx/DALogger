# How to use this node module
1. Install the node module using `npm i dalogger --save`
2. Go fancy

# Methods
Color is optional. If not inputted, default value will be used

### status(text, color)
> [HH:MM:SS] Status: Text

Text is what you want it to output  
Color is the color you want `Status: ` in.  
Default: Green

### trade(text, color)
> [HH:MM:SS] Trade: Text

Text is what you want it to output  
Color is the color you want `Trade: ` in.  
Default: Magenta

### alert(text, color)
> [HH:MM:SS] Alert: Text

Text is what you want it to output  
Color is the color you want `Alert: ` in.  
Default: Yellow

### confirm(text, color)
> [HH:MM:SS] Confirmation: Text

Text is what you want it to output  
Color is the color you want `Confirmation: ` in.  
Default: Cyan

### error(text, color)
> [HH:MM:SS] Error: Text

Text is what you want it to output  
Color is the color you want `Error: ` in.  
Default: Red

### item(text, color)
> (Text)

Text is what you want it to output  
Color is the color you want `( )` in.  
Default: Green

### warn(text, color1, color2)
> [HH:MM:SS] Warn: Text

Text is what you want it to output  
Color1 is the color you want `Warn: ` in.  
Color2 is the color you want `Text` in.  
Default: Yellow, Red

### time()
> [HH:MM:SS]

Returns current time for your own use