# JS_StringBuilderTool
javascript StringBuilder plug-in

## Instruction

Concatenation, or joining strings, is an important facility within any programming language. 
It’s especially vital within web applications, since strings are regularly used to generate HTML output. 
Several languages offer fast string-handling classes such as StringBuilder in .NET and StringBuffer/StringBuilder in Java.

## Feature 

- Using string array and pushing it into array;

## Example

- plug-in the js file.
- new a stringBuilder() object;
- using append to add your char;
- using toString() to output your text;

```
var sb = new $SB.stringBuilder();
var text;
sb.append("a")
  .append("b")
  .append("c");

text = sb.toString();
```
