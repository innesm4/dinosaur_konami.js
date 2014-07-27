dinosaur_konami.js # [![Build Status](https://travis-ci.org/yeoman/yo.svg?branch=master)](https://travis-ci.org/yeoman/yo) ![](http://img.shields.io/badge/unicorn-approved-ff69b4.svg)

"Finally a Konami Code Plugin I can use"

## Installation

Requires jQuery 

```
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script src="dinosaur_konami.js"></script> 
```

Options
```
var species = $.extend({
                dino: "img/dino-head.png",
                height: "250",
                width: "250",
                top: "50%",
                left: "50%",
            }, trex),
```

Add to Page
```
var Dinosaur = {
	    init: function() {

	        $('body').dinosaur_konami();
	    
	    }
	};
Dinosaur.init();	
```

Enter the Konami Code
```
UP UP DOWN DOWN LEFT RIGHT LEFT RIGHT B A
```

Move Dino
```
UP DOWN LEFT RIGHT
```

## Changelog

1.0 - Initial Release

## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
