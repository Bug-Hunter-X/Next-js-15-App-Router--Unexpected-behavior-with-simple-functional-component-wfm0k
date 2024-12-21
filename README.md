# Next.js 15 App Router Bug: Unexpected Behavior with Simple Functional Component

This repository demonstrates an unexpected behavior encountered when using a simple functional component within the `pages` directory of a Next.js 15 application using the App Router.

**Bug:**

The simple functional component, `pages/index.js`, does not render as expected.  Instead of displaying 'Hello World!', it might result in an error or unexpected behavior.

**Steps to Reproduce:**

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior in the browser.

**Expected Behavior:**

The page should display 'Hello World!'.

**Actual Behavior:**

The page displays an error or unexpected output.

**Possible Causes:**

This issue might be related to improper configuration of the App Router or unexpected interactions with the new routing system in Next.js 15.

**Solution (Provided in `bugSolution.js`):**

The solution involves adjusting file structure and/or the way the component is defined within the app directory.