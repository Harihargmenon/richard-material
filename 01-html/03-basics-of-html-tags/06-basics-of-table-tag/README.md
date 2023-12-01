---
title: "Basics Of HTML Tags"
---

# Understanding Table Tag

HTML tables are used to organize and display data in a structured grid format. Information is neatly arranged into rows and columns. Let's try to understand various parts of this table tag
<table> - Tag used to declare the table  
<tr> - Used to define a row in the table
<td> - Used to define table data in each row
<th> -  Used to define that table data which are the headers of a table. The headers can be both vertical and horizontal.
<caption> - Used to give a title to the table, 
border - A Table attribute used to give an outline to a table
Let’s create a table containing information about marks in mathematics. This table below has 3 columns: table headings<th>: Name, Section, and Marks in Maths. This is followed by marks of 3 students, each contained inside a <td> tag. The border helps us give an outline of width 1px.
<table border="1" >
<caption>Marks in Mathematics</caption>
  <tr>
    <th>Name</th>
    <th>Section</th>  
    <th>Marks In Maths</th>
  </tr>
  <tr>
    <td>Rajnikanth</td>
    <td>B</td>
    <td>40</td>
  </tr>
  <tr>
    <td>Shah Rukh Khan</td>
    <td>A</td>
    <td>10</td>
  </tr>
  <tr>
    <td>Nana Patekar</td>
    <td>C</td>
    <td>49</td>
  </tr>
</table>
Now that we understand, what each table tag means, let us understand the concept of colspan and rowspan. The colspan attribute is to merge different columns in a table and the rowspan attribute is to merge different rows of the table. Going forward, we’ll try to understand table tag in more depth.
