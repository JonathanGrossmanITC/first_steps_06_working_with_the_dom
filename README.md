# Working With The DOM

Welcome to the sixth lesson! In this lesson, you learn about the Document Object Model, commonly known as **The DOM**. 

**ADD MORE INTRO**

At the end of this lesson, you see a live coding example. The live coding session reinforces what you learn in the lesson. This lesson also helps prepare you for making your personal portfolio site. The code from the session is included in this repository. You can use it however you like, but as with any code you get from someone else, make sure you understand it well enough to explain it to someone before putting it in your own projects.  

In this lesson, you learn:  

Hour 1: What is the DOM
Hour 2: JavaScript's Built-in Functions
Hour 3: Live Coding 

- Hour 1: [What is the DOM](#what-is-the-dom)     
- Hour 2: [JavaScript Builtin Functions](#javascript-builtin-functions)   
- Hour 3: [Live Coding](#live-coding)  

The topics below outline what you learn in the live session. After the live session, you can use this material as a resource for guided self-learning. This document will serve you as a roadmap for gaining repetition with the material that you learned during the live session.   

## [What is the DOM](#what-is-the-dom)    

- The [DOM](https://www.w3schools.com/js/js_htmldom.asp) is an object-oriented representation of an HTML document 
- When a webpage loads, the browser converts the HTML into a DOM  
- Every element in an HTML document is part of the document object model for that document. For instance: 
    -— The `document` itself  
    -- The `head` 
    -- The `body`  
    -- The elements inside the body, like `div`, `h1`, `p`  
- You saw a [visual representation of the DOM](https://css-tricks.com/dom/) when you looked at the Elements tab in the inspector  
- You can modify the DOM [using a scripting language such as JavaScript](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction#dom_and_javascript)  
- Modifying the DOM is modifying the HTML document  
- The DOM orgaizes into objects the properties, methods, and events available for modifying and creating HTML elements       
- By defining the HTML elements as objects, JavaScript can do things like:  
  -- Get an existing HTML element and read its attributes  
  -- Change an existing HTML element's attributes  
  -- Add a new HTML element and set its attributes   
  -- Remove an existing HTML element or any of its attributes  
  -- Create and execute new HTML events  
- You can access the DOM in your JavaScript code by creating a `script` inside your HTML document  
  -- It can be a `script` that links to an external JavaScript file or any other type of `script` 
  -- You can immediately begin accessing the DOM and modifying HTML elements
  -- As you learned in the variables lesson, once you access an HTML element, you can **save it as a variable** and **access its attributes**  
- The DOM has various [built-in data types](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction#important_data_types)  
  -- Pay special attention to the built-in [data type named `document`](https://developer.mozilla.org/en-US/docs/Web/API/Document)
  -- The `document` is an object that represents the HTML document as loaded in the browser
  -- It serves as an entry point for JavaScript into the web page's content  
  -- It provides [global functionality](https://developer.mozilla.org/en-US/docs/Web/API/Document#properties), like accessing the page's URL or adding new elements, through its built-in methods   
  -- An example using document's built-in method for getting an HTML element by its `id` attribute: `const submitButton = document.getElementById("submitButton")`
 
## [JavaScript Builtin Functions](#javascript-builtin-functions)    

### DOM Methods  

- A document object has many [properties and methods](https://www.w3schools.com/jsref/dom_obj_document.asp)  
- Commonly used methods for the *document* include:  
  -- [`getElementById`](https://www.w3schools.com/jsref/met_document_getelementbyid.asp)  
  -- [`createElement`](https://www.w3schools.com/jsref/met_document_createelement.asp)  
  -- [`getElementsByClassName`](https://www.w3schools.com/jsref/met_document_getelementsbyclassname.asp)  
  -- [`addEventListener`](https://www.w3schools.com/jsref/met_document_addeventlistener.asp)  
- Element objects also have [properties and methods](https://www.w3schools.com/jsref/dom_obj_all.asp)   
- Commonly used methods for *elements* include:  
  -- [`appendChild`](https://www.w3schools.com/jsref/met_node_appendchild.asp)  
  -- [`removeChild`](w3schools.com/jsref/met_node_removechild.asp)  
  -- [`addEventListener`](https://www.w3schools.com/jsref/met_element_addeventlistener.asp)  
  -- [`getElementsByTagName`](https://www.w3schools.com/jsref/met_element_getelementsbytagname.asp)  
- Commonly used properties for *elements* include:  
 -- [id](https://www.w3schools.com/jsref/prop_html_id.asp)  
 -- [classList](https://www.w3schools.com/jsref/prop_element_classlist.asp)  
 -- [textContent](https://www.w3schools.com/jsref/prop_node_textcontent.asp)  
 -- You will see online the use of `innerText` and `innerHTML` instead of `textContent` and you should know [the differences](https://developer.mozilla.org/en-US/docs/Web/API/Node/textContent)  

### DOM Events  

## [Live Coding](#live-coding)   

The live coding session continues working on the live code from the previous lessons. Here are the tasks:

1.  
