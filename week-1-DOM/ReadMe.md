# The Week 1

- This week is going to be mainly focused on DOM. We are going re-learn about DOM.

# Breif about topics we learned each day

## Day-1

- What is DOM?
DOM(Document object Model) is a represtation of data in a web page. It is more likely a interface and we can change the document of the web page, basically the structure, stylee and content. Each element refers as a node and objects in DOM.

- What is getElementByID?
getElementByID is a method in Document interface returns an element, representing element whose "id" property matches the specified string. IDs are unique so getElementByID is useful way to get access to an element who a matching id. getElementByID("id").
Return => Element object

- What is querySelector?
querySelector is a method in Document which returns an Element obejct representing document that matches with a CSS or a group of CSS, if none is found then it returns null.
querySelector(".className/selectors"), we can also have multiple classes. Examples: document.querySelector(".myclass"); document.querySelector("div.user-panel.main input[name='login']");
Return => Element object, NOTE: "?" is not allowed is CSS identifires.

- What is textContent?
textContent is a property of the node iterface represents the text content of the element/node and its descendants. IMPORTANT NOTE: textContent remove the whole inside of an element, for instance if we have an element h1 and inside it we have multiple elements like p and span, and if we use textContent then on h1 then it will remove the child elements of the h1 and replace it with raw text if specified any.

- What is innerHTML?
innderHTML is a property of the node/Document interface gets or sets the HTML or XML markup contained within the elements. But also if we use innerHTML there is a security risk, we might need to use libraby to sanitize. when setting element content using innerHTML, the HTML string is parsed into DOM elements that do not contain shadow roots.


## Note: I have started JS again just re-learn we will utilize 1 hour daily, and each week we will new topics.
