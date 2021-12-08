# cypress-vs-playwright-puppeteer


- [VIDEO Introducing Playwright test runner](https://www.youtube.com/watch?v=JjhY2aFBTTk)
	- The team didnt want to create a new testing framework but they felt they had to. They tried Jest, mocha etc. Historically JS test frameworks are built around unit tests, playwright is built for E2E tests (see 2:56)
		- Cross browser
		- Parallelization
		- Isolation
		- Flexibility
		- TODO notes

Readings
- https://alisterbscott.com/2021/10/27/five-reasons-why-playwright-is-better-than-cypress/



Table
- 





Jackson from Rand Leadership slack (thread): https://rands-leadership.slack.com/archives/CCVT1RAP5/p1638969714187800
I’ve used both, and personally really like the playwright API.
At my current job we use Cypress. One issue with it is that Cypress can only test a single domain at once, so if the flow you’re testing involves a page redirect you’re kind of out of luck.  In their docs they do list visiting external sites as an anti pattern, and their arguments are pretty sound however in our case because the redirect was triggered by Stripe, there were no real workarounds using cy.request to simulate the flow.
Another thing which bugs me is maybe a little trivial, but it’s the fact that the Cypress API allows you to chain commands with .then() however it isn’t because the commands return a Promise. To me that’s just a confusing choice given how familiar Promise.prototype.then() would be to JS developers.
