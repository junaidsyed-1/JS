# The Week 1

- This week is going to be mainly focused on DOM. We are going re-learn about DOM.

## Topics covered this week
- Day-1
  - DOM BASICS
  - getElementByID
  - querySelector
  - textContent
  - innerHTML
- Day-2
  - addEventListener
  - Input Event
  - Click Event
- Day-3
  - createElemet
  - appendChild
  - removeChild
- Day-4
  - preventDefault
  - Form validation
- Day-5
  - setTimeout
  - setInterval
  - clearInterval

# Breif about topics we learn each day

## Day-1

- What is DOM?
  - DOM(Document object Model) is a represtation of data in a web page. It is more likely an interface and we can change the document of the web page, basically the structure, style and content. Each element refers as a node and objects in DOM.

- What is getElementByID?
  - getElementByID is a method in Document interface returns an element, representing element whose "id" property matches the specified string. IDs are unique so getElementByID is useful way to get access to an element who a matching id. getElementByID("id").
Return => Element object

- What is querySelector?
  - querySelector is a method in Document which returns an Element obejct representing document that matches with a CSS or a group of CSS, if none is found then it returns null.
querySelector(".className/selectors"), we can also have multiple classes. Examples: document.querySelector(".myclass"); document.querySelector("div.user-panel.main input[name='login']");
Return => Element object, NOTE: "?" is not allowed is CSS identifires.

- What is textContent?
  - textContent is a property of the node iterface represents the text content of the element/node and its descendants. IMPORTANT NOTE: textContent remove the whole inside of an element, for instance if we have an element h1 and inside it we have multiple elements like p and span, and if we use textContent then on h1 then it will remove the child elements of the h1 and replace it with raw text if specified any.

- What is innerHTML?
  - innderHTML is a property of the node/Document interface gets or sets the HTML or XML markup contained within the elements. But also if we use innerHTML there is a security risk, we might need to use libraby to sanitize. when setting element content using innerHTML, the HTML string is parsed into DOM elements that do not contain shadow roots.

## Day 2

- What is addEventListener?
  - addEventListener is a method of the EventTarget interface sets up a function which can be called whenever the event is delivered to the target. Common Targets and 'element' and its children, Document, Window and any other object that supports the events.
  Syntax => addEventListener(type, listener, options/useCapture)

- What is input event?
  - Input Event fires when the "value" of the "input" changes or the value of "<select>", "<textarea>" element changes as a direct result of a user action.
    - For <textarea> and <input> elements that accept text input the interface is "InputEvent" for others the interface is Event.
    - The input event is fired every time the value changes of the element, unlike the "change" event, which only fires when the value is committed, such as by pressing enter of submitting.
    - Syntax: addEventListener("input", function(e)).

  - What is click event?
  - Click event fires as soon as there is a activity which invloves any click on the screen:
    - It could be a pointing-device button is pressed and released while the pointer is located inside the element which has the event.
    - Any User interaction that is equivalent to a click, such as pressing the space key or Enter Key.

## Day 3

- What is createElemet?
  - createElemet is a document method which creates a HTML element.
  Syntax => createElemet(localName)

- What is appendChild?
  - appendChild is a method of Node interface which adds a node to the end of the list of children of a specified parent node.
  Syntax => appendChild(aChild)

- What is removeChild?
  - removeChild is a method of Node interface which removes a node from the DOM and returns the removed node.
  Syntax => removeChild(child)

- BONUS: Difference between Node and Document:
  - Node: Node is the base class interface for many DOM API objects. Every kind of DOM node (like elements, text, comments, etc.) is represented by an interface based on Node.
  - Document: Document is a specific type of Node that represents the entire HTML or XML document. It is the root node from which all other nodes (elements, text, etc.) descend.

## Day 4

- What is preventDefault?
  - preventDefault is a method of the Event interface to block the default actions of the event. But if we pass preventDefault to a non-cancellable event then it will not stop that event. 
  Syntax => preventDefault(), Return Value => None(undefined)

- Basic Form validation

## Day 5

- What is setTimeout?
  - setTimeout is a method of the "window" interface which sets a timer, it executes the function or a piece of code as soon as the timer expires.
  Syntax => setTimeout(code/function, delay)
  - Return Value => The setTimeout return a postitive integer(within the range of 1 to 2billion), that uniquely identifies the timer created, hence it is often referred as timeout ID.
  - Timeouts are cancellabe usign window.clearTimeout().
  - setTimeout is called with "delay", but for instance if the value of the delay is not a number but a string like this: "1000" then JS does implicit type coercion and that string will be coerced into a number.
  - setTimeout is a asynchronous function which implies that the function will not block the main thread and it will actaully go to the event loop and inside CallBack queue and will wait until the call stack is empty.

- What is setInterval?
  - setInterval is a method of the window which call the function or a piece of code repeatedly after the delay, which is fixed in the interval.
  Syntax => setInterval(code/function, delay)
  - Same as timeout setInterval returns a positive integer within the same range as setTimeout, and is also known as interval ID.

- what is clearInterval/clearTimeout?
  - They both are a method of window iterface which cancels the timer, which was established by a setTimeout/setInterval.
  Syntax => clearInterval(timerID)/ clearTimeout(timerID)

## Note: I have started JS again just to re-learn, We will utilize 1 hour daily, and each week we will learn new topics.
