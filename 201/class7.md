# Class 7 Notes

### **Domain Modeling**

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

2. Model its attributes with a constructor function that defines and initializes properties.

3. Model its behaviors with small methods that focus on doing one job well.

4. Create instances using the **new** keyword followed by a call to a constructor function.

5. Store the newly created object in a variable so you can access its properties and methods from outside.

6. Use the **this** variable within methods so you can access the object's properties and methods from inside.
<br>
<br>
## **CSS Tables**
A table represents information in a grid format. Examples include financial reports, tv schedules, and sports results. 
- Grids allow us to understand complex refrencing information on two axes.
- Each lock in the grid is reffered to as a table cell. In HTML a table is written out row by row.

Basic table  structure
```html
<table>
  <tr>
    <td>15</td>
    <td>15</td>
    <td>30</td>
  </tr>
  <tr>
    <td>45</td>
    <td>55</td>
    <td>45</td>
  </tr>
  <tr>
    <td>41</td>
    <td>56</td>
    <td>43</td>
  </tr>
</table>
```

Table Headings
```html
<table>
  <tr>
    <th></th>
    <th scope="col">Saturday</th>
    <th scope="col">Sunday</th>
  </tr>
  <tr>
    <th scope="row">Tickets Sold</th>
    <td>321</td>
    <td>143</td>
  </tr>
  <tr>
    <th scope="row">Tickets Sales:</th>
    <td>321</td>
    <td>143</td>
  </tr>
</table>
```
