## WHAT IS AN OBJECT?

**You have already learned that JavaScript variables are containers for data values. You have already learned that JavaScript variables are containers for data values.**
**JavaScript objects are containers for named values called properties or methods.**
**Literal notation is the easiest and most popular way to creat objects**

#### The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes:

- THE DOCUMENT NODE
- ELEMENT NODES
- ATTRIBUTE NODES
- TEXT NODES

**Accessing and updating the DOM tree involves two steps:**

- STEP 1: ACCESS THE ELEMENTS
- STEP 2: WORK W ITH THOSE ELEMENTS Here
  **DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.**
  **Get element By i d ()**
  **allows you to select a single element node by specifying the value of its id attribute**

#### What ways should I have to select an element from a Nodelist:

1. THE tern {) METHOD
2. array syntax

**_Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them. In general, these are convenient characteristics; but if these features are not desirable for your particular use, you might consider using typed arrays._**

### LOOPING THROUGH A NODELIST

_If you want to apply the same code to numerous elements, looping through a Nodelist is a powerful technique_
_When you select a text node, you can retrieve or amend the content of it using the node Va 1 ue property._
_Using the inner HTML property, you can access and amend the contents of an element, including any child elements._

#### ADDING ELEMENTS USING DOM MANIPULATION:

- CREATE THE ELEMENT create el element ()
- GIVE IT CONTENT create Text Node()
- ADD IT TO THE DOM append Child ()

#### DOM manipulation can be used to remove elements from the DOM tree.

- STORE THE ELEMENT TO BE REMOVED IN A VARIABLE
- STORE THE PARENT OF THAT ELEMENT IN A VARIABLE
- REMOVE THE ELEMENT FROM ITS CONTA INING ELEMENT

#### What is attribute node?

_It is a node which holds an attribute value of the all the matched attributes_
_Whenever a DOM query can return more than one node, it will always return a Nadel i st_
