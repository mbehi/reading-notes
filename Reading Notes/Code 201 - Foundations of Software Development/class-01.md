[Return to the Table of Contents](README.md)

# Duckett HTML Book
 ## Introduction
  ### The Structure of This Book
        1. HTML
        2. CSS
        3. Practical
    - How People Access the Web
        1. Browsers
        2. Web Servers
        3. Devices
        4. Screen Readers
    - How Websites are Created
        1. What You See
        2. How It Is Created
        3. HTML5 and CSS3
    - How the Web Works
        1. When you connect to the web, you do so via an Internet Service Provider. You will type a domain name or web address into your browser to visit a site; for example: google.com, bbc.co.uk, microsoft.com.
        2. Your computer contacts a network of servers called Domain Name System servers. These act like phone books; they tell your computer the IP address associated with the requested domain name. An IP address is a number of up to 12 digits separated by periods/full stops. Every device connected to the web has a unique iP address; it is like the phone number for that computer.
        3. The unique number that the DNS server returns to your computer allows your browser to contact the web server that hosts the website you requested. A web server is a computer that is constantly connected to the web, and is set up especially to send web pages to users.
        4. The web server then sends the page you requested back to your web browser.
 ## HTML Chapter 1 Structure
    - HTML pages are text documents.
    - HTML uses tag (characters that sit inside angled brackets) to give the information they surround special meaning.
    - Tags are often referred to as elements.
    - Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes the end.
    - Opening tags can carry attributes, which tell us more about the content of that element.
    - Attributes require a name and a value.
    - To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.
 ## HTML Chapter 8 Extra Markup
    - DOCTYPES tell browsers which version of HTML you are using.
    - You can add comments to your code between the '<!-- and -->' markers. 
    - The 'id' and 'class' attributes allow you to identify particular elements.
    - The '<div>' and '<span>' elements allow you to group block-level and inline elements together.
    - '<iframes>' cut windows into your web pages through which other pages can be displayed.
    - The '<meta>' tag allows you to supply all kinds of information about your web page.
    - Escape characters are used to include special characters in your pages such as '<','>', and '©'. 
 ## HTML Chapter 17 HTML5 Layout    
    - The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
    - The new elements provide clearer code '(compared with using '<div>' elements).
    - Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
    - To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.
 ## HTML Chapter 18 Process and Design
    - It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
    - Site maps allow you to plan the structure of a site.
    - Wireframes allow you to organize the information that will need to go on each page.
    - Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
    - You can differentiate between pieces of information using size, color, and style.
    - You can use grouping and similiarity to help simplify the information you present.
# Duckett JS Book
 ## Introduction
  - How JavaScript makes web pages more interactive
        1. Access Content
        2. Modify Content
        3. Program Rules
        4. React to Events
  - Examples of JavaScript in the Browser
  - The Structure of this Book
 ## JS Chapter 1 The ABC of Programming
   - What is a script and how do I create one? 
        1. A script is a series of instructions that the computer can follow in order to achieve a goal.
        2. Each time the script runs, it might only use a subset of all the instructions.
        3. Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task programmatically.
        4. To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).
    - How do computers fit in with the world around them?
        1. Computers create models of the world using data.
        2. The models use objects to represent physical things. Objects can have: properties that tell us about the object; methods that perform tasks using the properties of the object; events which are triggered when a user interacts with the computer.
        3. Programmers can write code to say "When this event occurs, run that code."
        4. Web browsers use HTML markup to create a model of the web page. Each elemtn creates its own node (which is a kind of object).
        5. To make web pages interactive, you write code that uses the browser's model of the web page.
    - How do I write a script for a web page?
        1. It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension.
        2. The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file).
        3. If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.