[Return to the Table of Contents](README.md)

# Duckett HTML Book
 ## Chapter 7 Forms (p. 144-175)
  ### Why Forms?
  - The best known form on the web is probably the search box that sits right in the middle of Google's homepage.
  ### Form Controls
  - There are several types of form controls that you can use to collect information from visitors to your site.
  ### How Forms Work
  - A user fills in a form and then presses a button to submit the information to the server.
  - A form may have several form controls, each gathering different information.
  - The server needs to know which piece of inputted data corresponds with which form element.
  ### Form Structure
  - `<form>`
   - action
   - method
   - id
  ### Text Input
  - `<input>`
   - type="text"
   - name
   - size
   - maxlength 
  ### Password Input
   - `<input>`
   - name
   - size, maxlength
  ### Text Area
   - `<textarea>`
  ### Radio Button
   - `<input>`
   - type="radio"
   - name
   - value
   - checked
  ### Checkbox
   - `<input>`
   - type="checkbox"
   - name
   - value
   - checked
  ### Drop Down List Box
   - `<select>`
   - name
   - `<option>`
   - value
   - selected
  ### Multiple Select Box
   - `<select>`
   - size
   - multiple
  ### File Input Box
  - `<input>`
  - type="file"
  ### Submit Button
  - `<input>`
  - type="submit"
  - name
  - value
  ### Image Button
  - `<input>`
  - type="image"
  ### Button and Hidden Controls
  - `<button>`
  - `<input>`
  - type="hidden"
  ### Labelling Form Controls
  - `<label>`
  - for
  ### Grouping Form Elements
  - `<fieldset>`
  - `<legend>`
  ### HTML5: Form Validation
  - You have probably seen forms on the web that give users messages if the form control has not been filled in correctly.
  ### HTML5: Date Input
  - `<input>`
  - type="date"
  ### HTML5: Email and URL Input
  - `<input>`
  - type="email"
  - type="url"
  ### HTML5: Search Input
  - `<input>`
  - type="search"
  - placeholder
 ## Summary
  - Whenever you want to collect information from visitors you will need a form, which lives inside a `<form>` element.
  - Information from a form is sent in name/value pairs.
  - Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
  - HTML5 introduces new form elements which make it easier for visitors to fill in forms.

 ## Chapter 14 Lists, Tables and Forms (p.330-357)
  ### Summary
   - In addition to the CSS properties covered in other chapters which work with the contents of all elements, there are several otehrs that are specifically used to control the appearance of lists, tables, and forms.
   - List markers can be given different appearances using the `list-style-type` and `list-style image` properties.
   - Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
   - Forms are easier to use if the form controls are vertically aligned using CSS.
   - Forms benefit from styles that make them feel more interactive.


# Duckett JS Book
 ## Chapter 6 Events (p.243-292)
  ### Sumamary
  - Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
  - Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
  - When an event occurs on an element, it can trigger a JavaScript function.
  - When this function then changes the web page in some way, it feels interactive because it has responded to the user.
  - You can use event delegation to monitor for events that happen on all of the children of an element.
  - The most commonly used event are W3C DOM events, although there are others in the HTML5 specification as well as browser-specific events.