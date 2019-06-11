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