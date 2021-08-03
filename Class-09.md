# Read: 09 - Forms and Events

## ***HTML & CSS***
  **1. Forms**
    * Whenever you want to c XX ollect information from visitors you will need a form, which lives inside a form element.
    * Information from a form is sent in name/value pairs.
    * Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
    * HTML5 introduces new form elements which make it easier for visitors to fill in forms.
  **2. Lists, Tables & Forms**
    * In addition to the CSS properties covered in other chapters which work with the contents of all elements,there are several others that are specifically used to control the appearance of lists, tables, and forms.
    * List markers can be given different appearances using the list-style-type and list-style image properties.
    * Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
    * Forms are easier to use if the form controls are vertically aligned using CSS.
    * Forms benefit from styles that make them feel more interactive.
    
## ***JAVASCRIPT & JQUERY***
  **1. DOM**
   * The browser represents the page using a DOM tree. DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
   * You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. Whenever a DOM query can return more than one node, it will always return a Nadel i st.
   * From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques.
   * An element node can contain multiple text nodes and child elements that are siblings of each other.
   * In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
   * Browsers offer tools for viewing the DOM tree .
   **2. Events**
     * Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
     * Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
     * When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.
     * You can use event delegation to monitor for events that happen on all of the children of an element.
     * The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.