Colours in culture
=====================


A pure javascript plugin to get the culture meanings for a color.

[Codepen demo](http://codepen.io/tfrere/pen/VpMWwv)


HOW TO USE
------------


```javascript

var ColoursInCulture = require("colours-in-culture");

var result = new ColoursInCulture.getCultureColorFeelings("#7c7b7a", "japanese");
console.log(JSON.stringify(result, null, 4));

/**
 * Outputs :
 *
 * {
 *   closestColor: {
 *     hex: "#7c7b7a",
 *     name: "grey"
 *   },
 *   cultureFeelings: [
 *      "staid,
 *      "intelligence",
 *      "reliability",
 *      "old age",
 *      "conservative",
 *      "modesty"
 *    ]
 *  }
 */


```


SOURCES
------------


This is based on the excellent [work](http://www.informationisbeautiful.net/visualizations/colours-in-cultures/) of David McCandless

* [The original data sheet](https://docs.google.com/spreadsheets/d/1kdEOmMxo-Shy2gGlUpPe_Low3s27ZXIw15hybMmtMDU/edit#gid=0) 

* [Pantone: Communicating With Colour](http://www.amazon.com/exec/obidos/ASIN/0966638328/titb-20/)
* [John Gage: Color and Meaning: Art, Science, and Symbolism](http://www.amazon.com/exec/obidos/ASIN/0520226119/titb-20/)
* [ColorMatters](http://www.colormatters.com/search.html)
* [BrandCurve](http://www.brandcurve.com/color-meanings-around-the-world/)
* [About](http://webdesign.about.com/od/color/a/bl_colorculture.htm)


CONTRIBUTE
---------------

If you want to add any additional information in the database, feel free to submit a pull request. 



Released under the MIT [License](https://github.com/tfrere/colours-in-culture/blob/master/LICENSE)
