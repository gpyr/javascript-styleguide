JavaScript Guidelines to be used in all Patt's Projects.

1. General
=====================

### Indentation ###

Tabs Democratically elected however the word on the street tells of a rebellion. Stay tuned.



### Spaces Between arguments and expressions ###

use Sparingly and spaces between operators:

    project.MyClass = function(arg1, arg2) {};


### Line Length ###

Recommended 80 characters (but no enforcement)



### Semicolons ###

Always use semicolons and don't rely in implicit insertion.



### Comments ###

YUI Doc Conventions.

[http://yui.github.io/yuidoc/](http://yui.github.io/yuidoc/)



### Quotes ###

Prefer ' over " .



### Globals ###

Avoid using globals.



### Variable declarations ###

Prefered one per line however not enforced.

    var foo = '';
    var bar = '';

if using multiples then go with line ending commas and formatting like:

    var foo = "",
      	bar = "",
      	quux;



### Braces ###

Use opening brace in same line: 

    function thisIsBlock(){
    }


### Whitespace ###

Use whitespace (empty lines) to separate logical bits of code. (2-3 lines and unix line endings) **No trailing whitespace**




2.	Naming
=====================


### Functions ###

Start first word lowercase and after that all words start with uppercase letter (camelCaps): 

Prefer longer and describing function names.

    function veryLongOperationName(){
	};


Use vocubular like is, set, get:

    function isReady(){};
    function setName(){};
    function getName(){};


### Arrays ###

Use plural forms and append description of type: 

    var documents = [];


### Objects and Class's ###

Lower case for instances/variables and uppercase for Class/Object Definitions

    var thisIsObject = new Date;
    var MyView = Backbone.View.extend({});


### File and Folder names ###

Use all-lower-hyphen-css-case for multiword filenames, config keys and folder names.

Use . notation for js files.  

    page.controller.js

General folder structure:

    /styles/
    /sass
    /scripts/
    	/libs/
    	/app
    config.rb
    
Alternatively /css and /js can be used.

