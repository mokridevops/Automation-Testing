 # Playwright

Playwright - Open-source tool by Microsoft for automating web browser testing, end-to-end testing.
Playwright also offers dedicated API for testing and interacting with Web API's.

Playwright is an open-source Node.js Library.

Node.js is an open-source cross-platform JavaScript runtime environment, that executes javascript code outside of a web browser.

Features:

Cross browser: Works with Chromium (Chrome, Edge), Firefox, WebKit (Safari).  ---> Chromium is the engine for Chrome and Ege, Webkit is the engine for Safari.

Cross-platform: runs on Windows, Mac, and Linux
Cross-Language: You can write tests in JavaScript, TypeScript, Java, Python, or C#.


Test Mobile Web: mobile testing for chrome (android) and safari (ios)
API Testing: Playwright includes built in API testing, allowing you to test backend API's together

Automatic Waiting(Auto-wait): Playwright waits for elements to be ready before performing actions, reducing test flakiness. 

flakiness - means - one time the testcase passes, another time the testcase fails

Handles Complex Elements:  Easily interacts with shadow DOM elements, which are tricky for other tools. 
Parallel Execution: Supports runing tests simultaneously in multiple browser instances for faster execution.


Built-in Reporters: Provides various report formats like HTML, JSON, JUnit, and more.  Supports third-party reporting tools like Allure reports.


1) Inspector: Helps debug tests by showing click points and verifying locators in real time.
2) Code Generation (Code Gen) The Codegen tool records your actions and converts them int o test scripts in any supported language.
3) Tracing (Trace Viewer): Captures screenshots, records videos, retries flaky tests, and logs steps automatically.
   Capture all the information to investigate the test failure.


JavaScript ---> Dynamically typed language

let age = 30
let name = "John"

age = "thirty"


TypeScript ---> Statically typed language

let age:number = 30
let name:string = "John"

age = "thirty"

why TypeScript
---------------
JavaScript (ES3, ES4, ES5, ES6)

ECMAScript - ECMAScript(ES) - is the standard to which all JavaScript code must comply.

TypeScript  --- Superset of JavaScript
-----------
A vendor such as Microsoft cannot add features to the JavaScript language without breaking ECMAScript compliance.
In contrast, with TypeScript, Microsoft can add any new features it wants, so long as the generated JavaScript is ECMAScript-compliant.
That gives Microsoft all the freedeom in the world to make TypeScript as feature-full as any other programming language.




   
