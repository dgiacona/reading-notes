# Class 6 Notes

### What is an Object?

Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions take on nre names.

**In an object**

- Variables become **properties**
- Functions become **methods**

### Document Object Model (DOM)

Specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

**The DOM is neither HTML or JavaScript it is a seperate set of rules representing two primary areas.**

- Making a model of the HTML page.
- Accessing and changing the HTML page.

## Steps of working with a DOM Tree
**Access the elements**
- Select an individual element node- getElementById(), querySelector()
- Select multiple elements (nodelist)- getElementByClassName(), getElementByTagName(), querySelectorA11()
- Traversing Between Element Mode- parentNode, previousSibling/nextSibling, firstChild/lastChild

**Work with those elements**
- Access/Update Text Nodes-nodeValue()
- Work with HTML Content- createElement(), createTextNode(), appendchild()/removeChild()
- Access or Update Attribute Values- hasAttribute(), getAttribute(), setAttribute(), removeAttribute()