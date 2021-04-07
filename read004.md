# Writing Links
* you can link any page you want by `` <a> `` element and using href attribute !
*example*


 `` <a href="link here">this text appear to user</a> ``


 ## Email Links

 *and here we can link our email with our website !*

*example ;*

``<a href="my email">anything want appear to user</a>``

 ### if you want to open link in new window !

```
 <a href="my link" target="_blank">
any text want appear to user</a> (opens in new window)
```


- width : This sets the width of the  columns. 
- float : This positions the columns next to each other.
- margin : This creates a gap between the columns.

*example :*
```
.column1of2 {
float: left;
width: 620px;
margin: 10px;}

```

*Screen Sizes*

Different visitors to your site will have different sized screens that show 
different amounts of information, so your design needs to be able to all!


*The float*

> The float property moves content to the left or right 
of the page and can be used to create multi-column 
layouts

*Grids* set consistent proportions 
and spaces between items which 
helps to create a professional 
looking design. 

### CSS Frameworks

*CSS frameworks aim to make your life easier by providing the code for 
common tasks;such as creating layout grids, styling forms, creating 
printer-friendly versions of pages and so on.*

#### how to link multiple Style Sheets?

*example*
```
<!DOCTYPE html> 
<html> 
<head> 
 <title>Multiple Style Sheets - Link</title> 
 <link rel="stylesheet" type="text/css" 
 href="css/site.css" />
 <link rel="stylesheet" type="text/css" 
 href="css/tables.css" />
 <link rel="stylesheet" type="text/css"
 href="css/typography.css" /> 
</head>
<body>
 <!-- HTML page content here -->
</body>
</html>

```

> Pages can be fixed width or liquid (stretchy) layouts


## Declaring function

* creat a function
* give it name
* write the statement you want achive it 
* and taske inside curly braces 

*example* 

```
function sayBye() {

    document.writ('Bye'!);
}

```
> Functions can return more than one value using an array. 
