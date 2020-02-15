# Attributes

HTML **attributes** are extra information added on the HTML tags (placed inside the opening tag). It is used to define the characteristics of a HTML element. The form of an attribute is `name = "value"`.

The **name** is the property you want set. For example,  `align` as a name of an attribute can be used to indicate the alignment of a paragraph on the page.

The **value** is what you want the value of the property to be, and it is usually between the double quotation mark. In the above example, we can set the value of the property `align` as "left", "right", or "center".

```html
<p align = "center">
    this paragraph is centered.
</p>
```



Some basic attributes:

1. href attribute:

   ​		It specifies a link's address to the HTML link. With `<p href="www.google.com">whassup</p>`, we can go to "www.google.com" by clicking on "whassup" on the page.

2. style attribute:

   ​		By using `style` in the opening tag, we can modify the interface of the contents. For example, `<p style = "color: red;">hello</p>` change the message "hello" into red. You can also set specific font-family, font-size, and so on.

3. id attribute:

   ​		It makes the element carries a unique identifier, where we could use it to distinguish between elements with the same name and specifically associate it with a style sheet later on. The value of the id can be whatever you want, but it cannot be starting with a number.

4. class attribute:

   ​		It is similar to the id attribute, in which we could modify the style of all the elments in a specific calss. The value of a class can be a list of 1 or more classnames separated by a space. For example, `class = "time date month"`denoted the element is in all of the three "time", "date", and "month" classes.

5. src attribute:

   ​		It is assigned the filename of the image source for a HTML image (`<img>`). For example, `<img src = "the_eiffel_tower.jpg">`adds the image of the Eiffel Tower to the page.

6. width and height attributes:

   ​		They are attributes that specifically apply on an image to decide the width and height of the picture by `<img src = "the_eiffel_tower.jpg" width ="500" height="600">` (the unit is in pixel), which are separated by a space.

7. alt attributes:

   ​		It provides an alternative text to be shown if the image cannot be loaded. Use it as `<img src = "the_eiffel_tower.jpg" alt="cannot load">`.

