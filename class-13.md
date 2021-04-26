# What is HTML Web Storage?
With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

HTML Web Storage Objects
HTML web storage provides two objects for storing data on the client:

window.localStorage - stores data with no expiration date
window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)

**The localStorage Object**
The localStorage object stores the data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.
Example
// Store
localStorage.setItem("lastname", "Smith");

// Retrieve
document.getElementById("result").innerHTML = localStorage.getItem("lastname");

Create a localStorage name/value pair with name="lastname" and value="Smith"
Retrieve the value of "lastname" and insert it into the element with id="result"

# HTML5 localStorage for Offline Web Applications
Since the introduction of HTML5, the technology is making an equal impact in the desktop and mobile space. It has completely changed what is possible with a Web interface. The new features are so powerful they bring Web pages closer to Apps. The new features include a plugin-free paradigm, with the introduction of tags like <video>, semantic markup like <header>, new form elements like email, and client-side storage. There is a constant drive to make browser-specific incompatibilities disappear.

The code snippet below checks if the browser supports localStorage. The code in this article has been tested on Google Chrome 17.0.963.56 and Firefox 11.0. There is a small difference in behaviour when the code below is executed in IE: if the HTML file is opened locally (file:///C:/Web/mylocaltodo.html), IE throws an error — but if the same file is hosted on a server (even localhost), it just works!

In the following code, localStorage is an object under window and can be referenced via the window object, or directly as localStorage.

function browserCheck() {
  if (typeof(localStorage) == 'undefined' ) {
    alert('Your browser does not support HTML5 localStorage. Try upgrading.');
  }
}