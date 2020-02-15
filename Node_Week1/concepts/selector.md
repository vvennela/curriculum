# Selector

**Selectors** are used in CSS files to selects elements in the HTML file based on the element name to elaborate on them, such as changing the color of the text.

There are five simple seletors:

1. element selector

2. id selector

3. class selector

4. universal selector

5. grouping selector

   

The most basic element selector calls the HTML element's name and change all the design of it. For example, you have following codes in your HTML file,

```html
<html>
    <body>
        <p>this is a paragraph.</p>
        <p>this is another paragraph.</p>
    </body>
</html>
```

and you can change the color of the text into red by adding the following codes:

```html
<style>
    p{
        color:red;
    }
</style>
```

Note that by using selector "p" in the CSS file, you selects all <p> elements on the page, and both "this is a paragraph", and "this is another paragraph" would be in red now.



Another useful selector is called the **id selector**. The id selector can selects a specific HTML element by using "**#**" before the id name.

For example, suppose you have another HTML file here

```html
<html>
    <body>
        <p>this is a paragraph</p>
        <p id="p2">this is another paragraph</p>
    </body>
</html>
```

Then, by using ""#p2" selector between <style></style>, you can refer to the style of "this is another paragraph" specifically.

```html
<style>
    #p2 {
        color: red;
    }
</style>
```

Now, "this is a paragraph" remains as default style, while "this is another paragraph" changed into red.



The **class selector** selects a specific class attributes by using "." in front of the class name. 

Suppose you have a class called "hello" in your HTML file:

```html
<html>
    <body>
        <p>this is a paragraph</p>
        <p>this is another paragraph</p>
        <h class = "hello">hello</h>
        <p class = "hello">good morning</p>
    </body>
</html>
```

In order to make the HTML elements in the same class change to another style, we can use the class selector:

```html
<style>
    .hello {
        color: red;
    }
</style>
```

Note that `.hello` will change both lines "hello", and "good morning" into red, because it refers to the class `hello`. However, you can specifically change the style of "hello" by using `h.hello`, and similarly, to select "good morning" by using `p.hello`.



Note: Both the id name and class name cannot be started with a number!



Now, let's take a look at the **universal selector**. The 

`*` refers to the universal selector, which selects **all** the elements on the HTML page.

We simply use it as

```html
<style>
    * {
        color: red;
    }
</style>
```

and it will change all elements on the HTML page into red.



The last simple selector is the **grouping selector**. It groups the element selectors together, when you want to give these elements the same style definition.

For example, the HTML has different headings and paragraphs that named h1, h2, p1, and p2. Now you want to set all h1, h2 and p2 into red. Then, you can use a grouping selector as `h1, h2, p2 { color: red; }` instead of copying the code three times under three element selectors.



