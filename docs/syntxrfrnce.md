# Syntax Refernce

##Graphic Commands

* `Palette(Color 1, Color 2,...)` - Up to 36 colors. [Color codes](https://dcs.cemetech.net/images/rgbhlpalette.png)
* `Background(Color)`
* `Render(Sprite Number,X,Y)`
* `Rect(x,y,width,height,color)`
* `Map{Sprite Width, Sprite Height, Sprite Number,Row,Column}` - Have all sprites have the same width and height
* `Text(x,y,color,background color,width,height,string)`

## Logic Commands

* `Start` - Starts a new program. Note - After `Start` is declared, all sprites will be loaded. 
* `Stop` - Ends the program safely
* `Number in Variable` - Variables:`A`-`Z` and `θ`
* `For()` 
* `While` - Runs a loop of code if the expression is true , must be ended by an `End`
* `Repeat` - Runs a loop of code until the expression is false, must be ended by am `End`
* `_` - Negative symbol. Note - You CANNOT write a `-` symbol as a negative symbol or it will throw a syntax error
* `getKey` - Gets the current [key code](https://github.com/StarWarsPanda/BitCreate/blob/master/KeyCodes.pdf) and sends it to variable `K`
* `Label` - Defines a jump point. Can be defined with one or two letters (Including theta)
* `Goto` - Jumps to any defined label, creates an error when trying to jump to an undefiend label
* `Pause()` - Wait until any key is pressed, with a time limit (leave blank for no time limit)
* `Wait()` - Wait a certain amount of seconds
* `%comment` - Comments