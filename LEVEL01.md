## Writing Your First Test

***Note:** Assuming you've successfully installed the Test Runner and opened the Cypress app, now it's time to write our first test. We're going to:

- Create a sample_spec.js file.
- Watch Cypress update our list of specs.
- Launch the Cypress Test Runner.

## Write your first test
Now it's time to write our first test. We're going to:

Write our first passing test.
Write our first failing test.
Watch Cypress reload in real time.
As we continue to save our new test file we'll see the browser auto reloading in real time.

Open up your favorite IDE and add the code below to our sample_spec.js test file.

    describe ('Jakasur First Test:', ()=>{
        it('Nothing simple test!',()=>{
            expect(true).to.equal(true)
        })
    })


## What are describe, it, and expect?

All of these functions come from Bundled Tools that Cypress bakes in.

describe and it come from Mocha
expect comes from Chai
Cypress builds on these popular tools and frameworks that you hopefully already have some familiarity and knowledge of. If not, that's okay too.


## Write a real test
Step 1: Visit a page
 Step 2: Query for an element
Step 3: Click an element


**Scnario to write test:**

    - Visit: https://example.cypress.io
    - Find the element with content: type
    - Click on it
    - Get the URL
    - Assert it includes: /commands/actions
    - Get the input with the .action-email class
    - Type fake@email.com into the input
    - Assert the input reflects the new value


Page Transitions

    Cypress automatically detects things like a page transition event and will automatically halt running commands until the next page has finished loading.

    Had the next page not finished its loading phase, Cypress would have ended the test and presented an error.