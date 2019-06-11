#SASS

##Varibles
- It helpes in reusability.
- We can define varibles in one place and use thoughtout the whole stylesheet 
- You can store things like colors, font stacks, or any CSS value you think you'll want to reuse
- SASS uses the ```$```this symbol to make something varible.
- Example : ```$primary-color: #333;```

###Nesting 
- We can do nesting in SASS
- like: 

 ```
  header: {
    background: red;
    button: {
        color: yellow
    }} 
```
and 
``` 
header button {
    color:yellow
} 
```
both css blocks are working similar

### Import
- It uses to modularise the css code in multiple files
- We can just import the files sequencially in main scss file
- Syntax: ```@import fileName```;

### Mixins
- Mixins are similar like normal functions we already have in javascript.
- Instead of typing the same property over and over we write a mixin once then call that mixin anytime we want to use it.
- We can customize the value of property in mixin functions similar  we do with normal functions just by passing the parameters just by passing values in that function like this```@include flexCenter(row);```this will change this property for particular css block

- To declare a mixin we use ```@mixin functionName()```
- To include the mixin we use ```@include functionName()```

### Extend
- It is one of the most useful features that allows us to share a set of CSS properties from one selector to another.
- It is kind of inheritance to get all the parent properties in child selector.
- We can override the properties 
- Syntax: ```@extend selectorName```