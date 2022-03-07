# DOM
## What is DOM?
DOM stands for Document Object Model. It is a programming interface for HTML and XML(Extensible markup language) documents that allows us to create, change, or remove elements from the document. It defines the logical structure of documents and the way a document is accessed and manipulated.

DOM is a way to represent the webpage in a structured hierarchical way so that it will become easier for programmers and users to glide through the document. With DOM, we can easily access and manipulate tags, IDs, classes, Attributes, or Elements using commands or methods provided by the Document object.

![](https://imgur.com/V6PsabZ.png)

Element node : It represent any element that exists in the DOM.

Root node : This is the top node in the tree, which in the case of HTML, is always the "HTML" node.

Child node: This is a node that is directly inside another node. For example,h2 is a child of body in the above example.

Descendant node: This is a node that exists anywhere in the hierarchy of another node. For example, h2 is a descendant of html in the above example.

Parent node: This is a node that has another node inside it. For example, body is the parent node of h2 in the above example.

Sibling nodes: The nodes which sit on the same level in the DOM tree. For example,h2 and p are siblings in the above example.

Text node: This is a node that contains a text string.

## How does it helps?
HTML is used to structure the web pages and Javascript is used to add behavior to our web pages. When an HTML file is loaded into the browser, the javascript can not understand the HTML document directly. So, a corresponding document is created(DOM). DOM is basically the representation of the same HTML document but in a different format with the use of objects. Javascript interprets DOM easily i.e javascript can not understand the tags(h1/h/h1) in HTML document but can understand object h1 in DOM. Now, Javascript can access each of the objects (h1, p, etc) by using different functions.

## How to access DOM?
To identify and access the DOM elements, JavaScript uses three ways:
•  Accessing elements By ID
•  Accessing elements By TagName
•  Accessing elements By className
#### Accessing a DOM element By ID:
JavaScript can find HTML elements in the DOM based on the "id" of the element. The document object provides a method "getElementById()" to accomplish this task.

Syntax:

document.getElementById(“IDName”);
![](https://imgur.com/vQmMrWR.png)

#### Accessing a DOM element By TagName:
Accessing a DOM element By TagName:
JavaScript can find the elements in the HTML based on the "tagName" and return an array of matching nodes. The inbuilt function, of document object, available for this is   getElementByTagName().

Syntax:

document.getElementByTagName(“tagName”);

![](https://imgur.com/C5HlQBc.png)

#### Accessing a DOM element By ClassName:
Accessing a DOM element By ClassName:
JavaScript can find the element in the HTML based on the className attribute of the element and returns an array of matching nodes. The inbuilt function available in this operation is getElementByClassName().

Syntax:

document.getElementByClassName(“ClassName”);
![](https://imgur.com/KAQwAVB.png)

## What are JS DOM helper methods?
