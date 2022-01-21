# Steps to to write HTML
1. Start with **\<html>** tag, followed by **\<head>** and **\<body>** tag. HTML always uses **forward** slash (not backward) for closing tag.
<img src="/Screenshots/Slash.png" width="40%" height="40%" >

```
<html>
    <head>
        <!- This is head ->
    </head>
    <body>
        <!- This is body ->
    </body>
</html>
```
2. Start with the **\<title>** tag and **\<body>** tag
```
<html>
    <head>
        <title>First page</title>
    </head>
    <body>
        This is first paage
    </body>
</html>
```
<img src="/Screenshots/head_title.png" width="40%" height="40%" >

3. Difference between **tag** , **element** and **attribute** in html

* **HTML Tags**: Tags are the starting and ending parts of an HTML element. They begin with < symbol and end with > symbol. Whatever written inside < and > are called tags. Example: ```<title> </title>```

* **HTML elements**: Elements enclose the contents in between the tags. They consist of some kind of structure or expression. It generally consists of a <u>start tag, content and an end tag </u>.
Example: ```<b>This is the element</b>```

* **HTML Attributes**: It is used to define the character of an HTML element. It always placed in the opening tag of an element. It generally provides additional styling (attribute) to the element.
Example: ```<p ```<u>```align="center"```</u>```>This is paragraph.</p>```

4. **\<meta>** tag 
* Metadata is data (information) about data.
* \<meta> tags always go __inside__ the \<head> element.
* Metadata will not be displayed on the page, but is machine readable.
* Metadata is used by browsers, search engines  and other web services.

Attribute |	Value |	Description
--- | --- | --- |
_charset_ | character_set |	Specifies the character encoding for the HTML document
_content_| text |	Specifies the value associated with the **http-equiv** or **name** attribute
_http-equiv_	| > content-security-policy <br/> > content-type <br /> > default-style <br /> > refresh	| Provides an HTTP header for the information/value of the content attribute
_name_ |>	application-name <br /> > author <br /> > description <br /> > generator <br /> > keywords <br/> > viewport<br /> |	Specifies a name for the metadata

* Define keywords for search engines:
```
<html>
    <head>
        <meta name="keywords" content="HTML, CSS, JavaScript"> 
    </head>
    <body>   
    </body>
</html>
```

* Define a description of your web page:
```
<html>
    <head>
        <meta name="description" content="Free Web tutorials for HTML and CSS">
    </head>
    <body>   
    </body>
</html>
```

* Define the author of a page:
```
<html>
    <head>
        <meta name="author" content="John Doe">
    </head>
    <body>   
    </body>
</html>
```
* Refresh document every 30 seconds:
```
<html>
    <head>
        <meta http-equiv="refresh" content="30">
    </head>
    <body>   
    </body>
</html>
```

* Setting the viewport to make your website look good on all devices. This is a method to let web designers take control over the viewport (the user's visible area of a web page), through the \<meta> tag:
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>   
    </body>
</html>
```


<img src="/Screenshots/viewport.png" width="50%" height="50%" >



<br/>


5. **\<br/>** - Line Breaking tag. This comes under the group od ___self-enclosing tag___ .  Notice that for the self closing tags, the forward slash comes after the tag name
```
<html>
    <head>
        <title>First page</title>
       
    </head>
    <body>
        O’er all the hilltops<br>
        Is quiet now,<br>
        In all the treetops<br>
        Hearest thou<br>
        Hardly a breath;<br>
        The birds are asleep in the trees:<br>
        Wait, soon like these<br>
        Thou too shalt rest.
    </body>
</html>
```
<img src="/Screenshots/break.png" width="40%" height="40%" >

5. **\<label>** - The \<label> tag defines a label (usually text) for several elements - <u> *\<input>,\<select>,\<textarea>* </u>
* The ***for*** attribute of \<label> must be equal to the ***id*** attribute of the related element to bind them together. 
* A label can also be bound to an element by placing the <u> element inside the \<label> element</u>. 

6. **\<input>** - Specifies an input field where the user can enter data. 
* **required** attribute : This is a boolean attribute. Boolean means it doesn not take value. It means that the particular input cannot be left blank.
```
<input type="text" id="point1" name="vehicle1" value="Dad," required>
<label for="point1"> I need a bike2</label><br>
```
```
<html>
    <head>
        <title>First page</title>
    </head>
    <body>  
          My country is <input> . My <input> is Hindi.
    </body>
</html>
```
<img src="/Screenshots/input.png" width="50%" height="50%" >

* **required** attribute : This is a boolean attribute. Boolean means it doesn not take value. It means that the particular input cannot be left blank.
```
<input type="text" id="point1" name="vehicle1" value="Dad," required>
<label for="point1"> I need a bike2</label><br>
```
<img src="/Screenshots/required.png" width="50%" height="50%" >
The different input types are as follows:


* ```<input type="button">```       <input type="button">
* ```<input type="checkbox">```     <input type="checkbox">
* ```<input type="color">```    <input type="color">
* ```<input type="date">```     <input type="date">
* ```<input type="datetime-local">```   <input type="datetime-local">
* ```<input type="email">```    <input type="email">
* ```<input type="file">```     <input type="file">
* ```<input type="hidden">```   <input type="hidden">
* ```<input type="image">```    <input type="image">
* ```<input type="month">```    <input type="month">
* ```<input type="number">```   <input type="number">
* ```<input type="password">```     <input type="password">
* ```<input type="radio">```        <input type="radio">
* ```<input type="range">```    <input type="range">
* ```<input type="reset">```    <input type="reset">
* ```<input type="search">```   <input type="search">
* ```<input type="submit">```   <input type="submit">
* ```<input type="tel">```      <input type="tel">
* ```<input type="text"> (default value)```     <input type="text">
* ```<input type="time">```     <input type="time">
* ```<input type="url">```      <input type="url">
* ```<input type="week">```     <input type="week">




7. **value** attribute - It specifies the value of an \<input> element. It is used differently for different input types:
* For **button**, **reset**, and **submit** - it defines the text on the button
* For **text**, **password**, and **hidden** - it defines the initial (default) value of the input field
* For **checkbox**, **radio**, **image** - it defines the value associated with the input (this is also the value that is sent on submit)
* <u>Relationship between input and label attributes</u> : Refer the template below
    * type : define the type of input that is expected from user
    * id : Associate a unique id to each input. **\<input> id attribute should be same as \<label> for attribute** so that each label can recognise which input to associate with. 
    * name : Consider this as the name of the variable. The value of the variable will be input by the user.
    * value : This is the default or initial value of the variable (*name* attribute). After the user input the value, the value will be replace with user value.

    ```
    <input type="text" id="ID_input_label" name="variable_name" value="default_value">
    <label for="ID_input_label"> I need a bike2</label><br>
    ```
    <input type="text" id="ID_input_label" name="variable_name" value="Default_value">
    <label for="ID_input_label"> I need a bike2</label><br>


* Form Submit URL : 
    * If method **GET** is used - Form variables are **passed** in the URL. This is **unsafe** method. Can lead to leakage of sensitive private data. 
        ```
        <form action="/action_page.php" method="get">
            <input type="text" id="point1" name="vehicle1" value="Dad,">
        <label for="point1"> I need a bike</label><br>
        </form>
        ```
        GET url :
        ```
        http://127.0.0.1:5500/action_page.php?vehicle1=Dad%2C&vehicle2=Hey+Frozen%2C&bikeNumber=race12&bikeNumber=Rush73&Car_Bike=Car&Car_Bike=Bike&Profession=Thief&RelativeWife=Wife&RelativeChild=Child
        ```
    * If method **POST** is used - Form variables are **not passed** in the URL. This is **safe** method.
        ```
        <form action="/action_page.php" method="post">
            <input type="text" id="point1" name="vehicle1" value="Dad,">
        <label for="point1"> I need a bike</label><br>
        </form>
        ```
        POST url :
        ```
        http://127.0.0.1:5500/action_page.php
        ```
* Form attribute :
    * name : unique name of the form
    * action : Determines what action to be taken after the form is submitted. For example: In below case, after the form is submitted, action_page.php will be loaded
    ```
    <form name="form_1" action="/action_page.php" method="post">    
    ```
    * novalidate : This is a boolean attribute. It means all the input in the form will not be validated. For example :
        * Without novalidate : On Submitting, input will be validated with the input type.
        ```
        <!DOCTYPE html>
        <html>
        <body>

        <h1>The form novalidate attribute</h1>

        <form action="/action_page.php" >
        <label for="email">Enter your email:</label>
        <input type="email" id="email" name="email"><br><br>
        <input type="submit">
        </form>
        </body>
        </html>
        ``` 
        <img src="/Screenshots/novalidate1.png" width="50%" height="50%" >

        * With novalidate : On Submitting, input will not be validated with the input type.
        ```
        <!DOCTYPE html>
        <html>
        <body>

        <h1>The form novalidate attribute</h1>

        <form action="/action_page.php" novalidate>
        <label for="email">Enter your email:</label>
        <input type="email" id="email" name="email"><br><br>
        <input type="submit">
        </form>
        </body>
        </html>
        ``` 
        <img src="/Screenshots/novalidate2.png" width="50%" height="50%" >

    
    * size : This attribute specifies the visible width, in characters. Default is 20
    * autofocus : Boolean attribute. Focus on a particular element automatically when page loads
    * maxlength : set the max length of input
    * minlength : set the min length of input 
        ```
        <label for="phone">Enter a phone number:</label><br><br>
        <input type="tel" id="phone" name="phone" minlength=5 maxlength=10 autofocus><br><br>
        <small>Format: 123-45-678</small><br><br>
        <input type="submit">
        </form>
        ```
        <label for="phone">Enter a phone number:</label><br><br>
        <input type="tel" id="phone" name="phone" minlength=5 maxlength=10 autofocus><br><br>
        <small>Format: 123-45-678</small><br><br>
        <input type="submit">
        </form>
    * pattern : specifies the pattern of input
    * placeholder : displays text in background in input
        ```
        <form action="/action_page.php">
        <label for="phone">Enter a phone number:</label><br><br>
        <input type="tel" id="phone" name="phone" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"><br><br>
        <small>Format: 123-45-678</small><br><br>
        <input type="submit">
        </form>
        ```
        <label for="phone">Enter a phone number:</label><br><br>
        <input type="tel" id="phone" name="phone" placeholder="123-45-678" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"><br><br>
        <small>Format: 123-45-678</small><br><br>
        <input type="submit">
        </form>
    * step : specifies legal number of steps
        ```
        <form action="/action_page.php">
            <label for="points">Points:</label>
            <input type="number" id="points" name="points" value="pt" step="3">
            <input type="submit">
        </form>
        ```
        <form action="/action_page.php">
        <label for="points">Points:</label>
        <input type="number" id="points" name="points" value="pt" step="3">
        <input type="submit">
        </form>

    ```
    <!DOCTYPE html>
    <html>
    <body>

    <h1>Form with checkboxes</h1>

    <form action="/action_page.php" method="get">
    <input type="text" id="point1" name="vehicle1" value="Dad,">
    <label for="point1"> I need a bike</label><br>
    
    <input type="text" id="point2" name="vehicle2" value="Hey Frozen," size=40>
    <label for="point2"> I have a bike</label><br>
    
    <input type="password" id="point3" name="bikeNumber" value="race12" size=20>
    <label for="point3"> Enter your bike number</label><br>
    
    <input type="hidden" id="point4" name="bikeNumber" value="Rush73">
    <label for="point4"> Enter your bike number</label><br>
    
    <input type="checkbox" id="point5" name="Car_Bike" value="Car" >
    <label for="point5"> I have a boat</label><br><br>
    
    <input type="checkbox" id="point6" name="Car_Bike" value="Bike" >
    <label for="point6"> I have a car</label><br><br>
    
    <input type="radio" id="point7" name="Profession" value="Thief" >
    <label for="point7"> I am a thief</label><br><br>
    
    <input type="radio" id="point8" name="Profession" value="Police" >
    <label for="point8"> I am a police</label><br><br>
    
    <input type="radio" id="point9" name="RelativeWife" value="Wife" >
    <label for="point9"> I have a wife</label><br><br>
    
    <input type="radio" id="point10" name="RelativeChild" value="Child" >
    <label for="point10"> I have a child</label><br><br>
    
    <input type="submit" value="Submit Now">
    <input type="reset" value="Reset Now">
    <input type="button" value="Buttoned">
    </form>

    </body>
    </html>
    ```

    <!DOCTYPE html>
    <html>
    <body>

    <h1>Form with checkboxes</h1>

    <form action="/action_page.php" method="get">
    <input type="text" id="point1" name="vehicle1" value="Dad,">
    <label for="point1"> I need a bike</label><br>
    
    <input type="text" id="point2" name="vehicle2" value="Hey Frozen," size=40>
    <label for="point2"> I have a bike</label><br>
    
    <input type="password" id="point3" name="bikeNumber" value="race12" size=20>
    <label for="point3"> Enter your bike number</label><br>
    
    <input type="hidden" id="point4" name="bikeNumber" value="Rush73">
    <label for="point4"> Enter your bike number</label><br>
    
    <input type="checkbox" id="point5" name="Car_Bike" value="Car" >
    <label for="point5"> I have a boat</label><br><br>
    
    <input type="checkbox" id="point6" name="Car_Bike" value="Bike" >
    <label for="point6"> I have a car</label><br><br>
    
    <input type="radio" id="point7" name="Profession" value="Thief" >
    <label for="point7"> I am a thief</label><br><br>
    
    <input type="radio" id="point8" name="Profession" value="Police" >
    <label for="point8"> I am a police</label><br><br>
    
    <input type="radio" id="point9" name="RelativeWife" value="Wife" >
    <label for="point9"> I have a wife</label><br><br>
    
    <input type="radio" id="point10" name="RelativeChild" value="Child" >
    <label for="point10"> I have a child</label><br><br>
    
    <input type="submit" value="Submit Now">
    <input type="reset" value="Reset Now">
    <input type="button" value="Buttoned">
    </form>

    </body>
    </html>

8. \<datalist>
* The \<datalist> tag specifies a list of pre-defined options for an \<input> element.

* The \<datalist> tag is used to provide an "autocomplete" feature for \<input> elements. Users will see a drop-down list of pre-defined options as they input data.
* Not compulsory that input should match the option


9. \<div> vs \<span> :
    * **HTML \<div> tag**: The div tag is known as Division tag. The div tag is used in HTML to make divisions of content on the web page like (text, images, header, footer, navigation bar, etc). Div tag has both opening(\<div>) and closing (\</div>) tags and it is mandatory to close the tag. As we know Div tag is a block-level tag. In this example, the div tag contains the entire width. It will be displayed div tag each time on a new line, not on the same line

        ```
        <html>
    
        <head>
            <title>Div tag</title>
        </head>
        
        <body>
            <div> div tag </div>
            <div> div tag </div>
            <div> div tag </div>
            <div> div tag </div>
        </body>
        
        </html>
        ```
        <html>
  
        <head>
            <title>Div tag</title>
        </head>
        
        <body>
            <div> div tag </div>
            <div> div tag </div>
            <div> div tag </div>
            <div> div tag </div>
        </body>
        
        </html>
    * **HTML \<span> tag**: The HTML span element is a generic inline container for inline elements and content. It used to group elements for styling purposes (by using the class or id attributes). A better way to use it when no other semantic element is available. The span tag is very similar to the div tag, but div is a block-level tag and span is an inline tag.
    ```
    <html> 
    <head>
        <title>span tag</title>
    </head>
    
    <body>
        <h2>Welcome To GFG</h2>
        <p><span style="background-color:lightgreen"> 
            GeeksforGeeks</span> is A Computer Science Portal 
            where you can<span style="color:blue;"> 
            Publish</span> your own <span 
            style="background-color:lightblue;">articles</span>
            and share your knowledge with the world!!
        </p>
        </body>
        
    </html>
    ```
    <html> 
    <head>
        <title>span tag</title>
    </head>
    
    <body>
        <h2>Welcome To GFG</h2>
        <p><span style="background-color:lightgreen"> 
            GeeksforGeeks</span> is A Computer Science Portal 
            where you can<span style="color:blue;"> 
            Publish</span> your own <span 
            style="background-color:lightblue;">articles</span>
            and share your knowledge with the world!!
        </p>
        </body>
        
    </html>