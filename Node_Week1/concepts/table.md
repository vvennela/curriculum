# Table

In HTML, a **table** is a way to arrange data set. It is made up of rows and columns. Each of the small container in a table is called a **cell**. We can arrange data into these cells and indicate some kinds of relationship among the  data. 

The name for each row and column is called **headers**. With these **headers**, we could interpret the data easily and efficiently.

To define a table in HTML, we use the <table> </table> tag. Within it, we could define each row with <tr></tr>, and add a row header between <th></th>.  By default, the headers are bold and centered. To add data into each cell, we put the data between <td></td>.

For example,

```html
<table>
    <tr>
        <th>Name</th>
        <th>Year</th>
        <th>Major</th>
    </tr>
    <tr>
        <td>Kathy</td>
        <td>Second</td>
        <td>Computer Science</td>
    </tr>
</table>
```

The code here creates a html table with 2 rows and 3 columns named "Name", "Year", and "Major", and with a second row of a sample data of a student under each header.



