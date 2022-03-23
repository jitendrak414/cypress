# cypress

## What is?
 1. Cypress is a next generation front end testing tool built for the modern web. We address the key pain points developers and QA engineers face when testing modern applications.

2. Cypress can test anything that runs in a browser.

3. This enables you to write faster, easier and more reliable tests.


We make it **possible to**:

- Set up tests
- Write tests
- Run tests
- Debug Tests


*Note: Cypress is most often compared to Selenium; however Cypress is both fundamentally and architecturally different. Cypress is not constrained by the same restrictions as Selenium.

## Features
Cypress comes fully baked, batteries included. Here is a list of things it can do that no other testing framework can:

- **Time Travel:** Cypress takes snapshots as your tests run. Hover over commands in the Command Log to see exactly what happened at each step.
- **Debuggability:** Stop guessing why your tests are failing. Debug directly from familiar tools like Developer Tools. Our readable errors and stack traces make debugging lightning fast.
- **Automatic Waiting:** Never add waits or sleeps to your tests. Cypress automatically waits for commands and assertions before moving on. No more async hell.
- **Spies, Stubs, and Clocks:** Verify and control the behavior of functions, server responses, or timers. The same functionality you love from unit testing is right at your fingertips.
- **Network Traffic Control:** Easily control, stub, and test edge cases without involving your server. You can stub network traffic however you like.
- **Consistent Results:** Our architecture doesn’t use Selenium or WebDriver. Say hello to fast, consistent and reliable tests that are flake-free.
- **Screenshots and Videos:** View screenshots taken automatically on failure, or videos of your entire test suite when run from the CLI.
  
- **Cross browser Testing:** Run tests within Firefox and Chrome-family browsers (including Edge and Electron) locally and optimally in a Continuous Integration pipeline.

----------



## Who uses Cypress?

Typically developers or QA engineers building web applications using modern JavaScript frameworks.

**Cypress enables you to write all types of tests:**

- End-to-end tests
- Integration tests
- Unit tests

------------------

## Cypress ecosystem
Cypress consists of a **free**, **open source**, **locally installed** **Test Runner** and a **Dashboard Service** for recording your tests.

- First: Cypress helps you set up and start writing tests every day while you build your application locally. TDD at its best!
- Later: After building up a suite of tests and integrating Cypress with your CI Provider, our Dashboard Service can record your test runs. You'll never have to wonder: Why did this fail?

--------****
## Setting up tests

There are no servers, drivers, or any other dependencies to install or configure.

Start project

    npm init -y

Install cypress

    npm install cypress --save-dev

Execute will open a dialog

    .\node_module\.bin\cypress open
    $(npm bin)/cypress open
    npx cypress open

To verify the cypress
***node_modules\cypress\lib\tasks\verify.js***

    npx cypress verify



Finally, through a large number of official and 3rd party plugins you can write Cypress a11y, visual, email and other types of tests.

Cypress makes it quick and easy to start testing, and as you begin to test your app, you'll often wonder if you're using best practices or scalable strategies.

To guide the way, the Cypress team has created the  Real World App (RWA), a full stack example application that demonstrates testing with Cypress in practical and realistic scenarios.

The RWA achieves full code-coverage with end-to-end tests across multiple browsers and device sizes, but also includes visual regression tests, API tests, unit tests, and runs them all in an efficient CI pipeline. Use the RWA to learn, experiment, tinker, and practice web application testing with Cypress.

The app is bundled with everything you need, just clone the repository and start testing.

---------

## Key Difference 
https://docs.cypress.io/guides/overview/key-differences#Debuggability

------------

### Switching browsers

## Adding npm scripts
In package.json

    {
        "scripts":{
            ....
            "cypress:open": "cypress open"
        }
    }
Now you can invoke the command from your project root like so:

    npm run cypress:open

----------
-----
Donate now on phone pay **9319821922@ybl** to buy hardware

----
