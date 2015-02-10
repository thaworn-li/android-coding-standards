# ustwo™ Android Coding Standards

## Table of contents

* [Code](#code)
    * [Style](#style)
    * [Indentation](#indentation)
    * [Line length](#line-length)
    * [Whitespace](#whitespace)
    * [Imports](#imports)
* [Documentation](#documentation)

## Code
### Style
Follow the official Android code style guidelines: [http://source.android.com/source/code-style.html](http://source.android.com/source/code-style.html)

### Indentation
We use spaces for indentation. Do not use tabs in your code. You should set your editor to emit spaces when you hit the tab key.

### Line Length
Stick within the 120 char line limit. Use line breaks to split up code according to the style guidelines.

### Whitespace
Code should not have any trailing whitespace to avoid creating unnecessary diff issues. Please setup your IDE to remove these as a save action.

### Imports
Please setup your IDE to remove all unused imports as a save action.

## Documentation
 * Any new classes that are committed must include a class descriptor Javadoc along with the '''@author name@address.com'''
 * Put inline comments on the line above the code your are commenting.
 * Use in-line commenting to help the next developer who might be editing your code, even if it seems obvious now.
 * Javadoc any methods that benefit. All library methods MUST have Javadoc
 * Javadoc any public methods, variables and constants.

