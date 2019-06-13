# JColor | Simple Javascript Color Plugin

Jcolor is a simple vanilla JavaScript color plugin with no dependencies. Simply download the jcolor.js file, include the script in your project, and you're good to go!

## Syntax

color(arg1, arg2, arg3);

* arg1: html element to trigger color picker and to color by default
* (optional) arg2: html element to color
* (optional) arg3: array of custom colors to be used( hex values)
* (optional) arg4: callback function to retrieve the color code

## Demo

Check out a demo of the color plugin [here](https://hkataya.github.io/JColor/) 

## Usage

just include the script file in your html file and call the color() function with an event handler. Simple!

```
 <script src="jcolor.js"> </script>
 <button  onclick="color(this)"  > Click Me </button>
```

Picking Color for a specific element

```
<script src="jcolor.js"> </script>
<div id="division"> this is a simple div tag </div>
<button  onclick="color(this, document.getElementById('division'))"  > Click Me </button>
```

Picking Color for a specific element

```
<script src="jcolor.js"> </script>
<h4 > Color Code: </h4>
<h3 id="colorCode">  </h3>
<button  onclick="color(this,this, undefined , function(code){document.getElementById('colorCode').innerHTML=code} )"  > Click Me </button>

```



## Built With

No dependencies - No jQuery - Javascript only. The file size is 1.97kb!

## Authors

**Hasan Kataya** 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



