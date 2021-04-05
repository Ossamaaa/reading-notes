
three  types of lists useed in html :

● Ordered lists. start with number like (1.2.3...ect)

code used  : `` <ol> ``

● Unordered lists. start with dot(.) as this list !
 
 code used : `` <ul>``

● Definition lists.  used to contain the term 
being defined .

 code used : ``<dl>``


> each item must has ``<li> and </li>``  and the last codes be before and after !

example :
```
   <ol>
<li>you must has struggle </li>
<li> you must doing effort </li>
<li>you must has patience</li>

  </ol>


```

Nested Lists it's mean you can make a second list inside 
an`` <li>`` element to create a subliste  or we can called nested list !



**Box Dimensions**

when we talking about Box Dimensions that's mean " width and height"

* we can change them by pixels or it's percentage

Every box has three properties can be adjusted to control it :

- Border
- Margin
- Padding

*Border Width*
 you can select proprty of values by :

- thin
- medium
- thick
 **or** by pixele

 *example* :
```

p{
border-width: thick;}

```

**Padding**

property allows you to put speace as you want times !

*example*
```
p{
padding: 10px;}

```

> You can also control the borders, margin and padding 
for each box with CSS. 

*If elese statement*

*checks a condition if its true will block run if was fales go to secound elese* !

**SWITCH STATEMENTS** 

 starts with a variable called the switch value.

- You must have a default option that is run if did't match any case !
 - if a match is found, that code is run;

 *exampel*
```
var msg; 
 let level = 3; 

 switch (level) { 
case 1: 
msg = 'hi man ' ; 
break; 
case 2: 
msg = 'Bye man'; 
break; 
case defulte :
msg = 'try again'

 }
 console.log(msg);
 ```

 **loops**
have three types :

- for : run with specefic times !

the condtion has three statements inside:
1. initializtion
2. condtion
3. update 

- while : if you don't know how much times !


- do while : close to while .


