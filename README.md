# Module: Word Clock
This Magic Mirror module displays a Word Clock written in the Swiss German dialect of Nidwalden.

## Installing the module
- cd MagicMirror/modules
- git clone https://github.com/Tsavorit52/MMM-nidwaldenwordclock.git

## Using the module

To use this module, add it to the modules array in the `config/config.js` file:
````javascript
modules: [
    {
		module: 'MMM-bernwordclock',
		position: 'bottom_left',
	},
]
````
You can change the size of the module by changing the "font-size" in "MagicMirror/modules/MMM-nidwaldenwordclock/bernwordclock.css"

## Screenshot 

![](wordclock.png)
