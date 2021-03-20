[Return to the Table of Contents](README.md)

# Click on the Link: [The Past, Present & Future of Local Storage for Web Applications](http://diveinto.html5doctor.com/storage.html)
## Diving In
- Historically, web applications have had none of these luxuries.
- Cookies were invented early in the web's history, and indeed they can be used for presistent local storage of small amounts of data.
- But they have three potentially dealbreaking downsides:
  1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.
  2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
  3. Cookies are limited to about 4KB  of data -- enough to slow down applicaion (see above), but not enough to be terribly useful.
## A Brief History of Local Store Hacks before HTML5
- Microsoft created Internet Explorer and DHTML Behaviors, and one of these behaviors was called userData.
- userData allos web pages to store up to 64KB of data per domain, in a hierarchical XML-based structure.
- Google launched Gears in 2007, an open source broswer plugin aimed at providing additional capabilities in browsers.
## Introducing HTML5 Storage
- HTML Storage Support:
  - IE 8.0+
  - Firefox 3.5+
  - Safari 4.0+
  - Chrome 4.0+
  - Opera 10.5+
  - iPhone 2.0+
  - Android 2.0+
## Using HTML5 Storage
- Tracking Changes to the HTML5 Storage Area
- StorageEvent Object
- Limitations in Current Browsers
## HTML5 Storage in Action
## Beyond Named Key-Value Pairs: Completing Visions