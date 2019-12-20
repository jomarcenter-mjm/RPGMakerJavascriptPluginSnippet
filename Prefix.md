# rmmvpluginsnippet List of Prefixes

All snippet always start with "!rmmv" and @type

## Content

This list all the content so you can easily start making the plugin
### Initial set
!rmmvStart - This create the body of the plugin
!rmmvStructContent - This create the initial Struct (please put this at the bottom)

## parameters
this is the list of parameters you can use in MV Plugin

### Numeric
@type float - adds a float parameters
@type limitFloat - adds a limited float parameters
@type int - adds a int parameters
@type limitint - adds a limited int parameters

### Condition
@type bool - This creates a bool parameters

### Text
@type note - This create a note parameters
@type text - This create the text parameters

### Files
@type file - This creates a generic file parameters
@type audio - this creates a audio file parameters
@type image - this creates a image file parameters

### Struct
@type struct - This create the struct parameters, if you making the struct please use !rmmvStructContent first.

### Objects
@type class - creates a class parameters parameters
@type weapon - creates a weapon class parameters
@type actor - creates a actor class parameters
@type animation - create a animation class parameters
@type skill - create a skill class parameters
@type item - create a item class parameters
@type armor - create a armor class parameters
@type enemy - create a enemy class parameters
@type troop - create a troop class parameters
@type state - create a state parameters
@type variable - create a variable object parameters

### Lists
@type ListsString - create a "string[]" parameters
@type ListFile - create a "file[]" parameters
@type ListString - create a "string[]" parameters
@type ListsText - create a "Struct<struct>[]"parameters

### Misc
@parent - This create "@parent" parameters, why it is separate, well you tell me
@text - creates a "@text" parameter, why it is separate, well you tell me
