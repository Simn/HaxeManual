## 12.1.6 JavaScript target Metadata

This is the list of JavaScript specific metadata. For more information, see also the complete list of all [Haxe built-in metadata](cr-metadata.md).

##### JavaScript metadata
 
 Metadata  |  Description 
 --- | ---
@:expose _(?Name=Class path)_   |  Makes the class available on the <code>window</code> object or <code>exports</code> for node.js  
@:jsRequire   |  Generate javascript module require expression for given extern 
@:selfCall   |  Translates method calls into calling object directly
