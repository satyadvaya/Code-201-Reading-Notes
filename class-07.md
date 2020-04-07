# External Article
## _Domain Modeling_
- Domain modeling is the process of creating a conceptual model in code for a specific problem.
- A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain.
- An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
# HTML & CSS
## Chapter6: _Tables_
Basic 2x2 table structure
```
<table>
    <tr>
        <td>Row1Column1</td>
        <td>Row1Column2</td>
    </tr>
    <tr>
        <td>Row2Column1</td>
        <td>Row2Column2</td>
    </tr>
</table>
```
- The table heading `<th>` element represents the heading for either a column or a row.
- The colspan attribute can be applied to either a `<th>` or a `<td>` element.

Basic long table structure
```
<table>
    <thead>
        <tr>
            <th>
            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
            </td>
        </tr>
    </body>
    <tfoot>
        <tr>
            <td>
            </td>
        </tr>
    </tfoot>
</table>
```
# JavaScript & jQuery
## Chapter6: _Functions, Methods, & Objects_
The three groups of built-in objects are:
```
Browser Object Model
    - Creates a model of the browser tab or window;
Document Object Model
    - Creates a model of the current web page;
Global JavaScript Objects
    - A group of individual objects that don't form a single model.
```
- Within an object, variables are known as properties and functions are known as methods.
- Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
- JavaScript also has several built-in objects such as `String`, `Number`, `Math`, and `Date`.  Their properties and methods offer functionality that aid in the writing of scripts.
- Arrays and objects can be used to create complex data sets (and both can contain the other).