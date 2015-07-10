# elementIsVisible

Checks if an element is visible by recursing up the node tree until it finds either the body or an element that is hidden.
Returns a boolean.

Should work with all module loaders, I use it with require.js, I have not tested it with any of the other ones. 
I wrote this based on a stack overflow.. I did not like the answer and coudl not find a simple module to do this. 
http://stackoverflow.com/questions/178325/checking-if-an-element-is-hidden

It is used in the dom navigation library [magic-focus-finder](https://github.com/Solid-Interactive/magic-focus-finder)

install with bower:

```bash
bower install --save elementIsVisible
```
