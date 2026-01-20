# Bug Reports

## BUG-01: Images are not displayed on "Broken Images" page

**Page:** Broken Images  
**URL:** https://the-internet.herokuapp.com/broken_images

### Steps to Reproduce
1. Open the Broken Images page
2. Observe the displayed images

### Expected Result
All images should be displayed correctly.

### Actual Result
Some images are broken and not displayed.

### Severity
Medium

### Priority
Medium
---------------------------------------------------------------------

## BUG-02: Page elements have unstable or non-descriptive identifiers on "Challenging DOM" page

### Bug Type
Testability / Design limitation
**Page:** Challenging DOM  
**URL:** https://the-internet.herokuapp.com/challenging_dom

### Steps to Reproduce
1. Open the Challenging DOM page
2. Refresh the page multiple times
3. Observe the buttons, table elements, and displayed answer

### Expected Result
Page elements should have stable and descriptive identifiers to support reliable testing.

### Actual Result
Buttons and table elements use unstable or non-descriptive identifiers, and the displayed answer changes dynamically on each page load.

### Severity
Low

### Priority
Low
---------------------------------------------------------------------
## BUG-03: "Digest Authentication" page returns HTTP 400 error

**Page:** Digest Authentication  
**URL:** https://the-internet.herokuapp.com/digest_auth

### Steps to Reproduce
1. Open the home page
2. Click on "Digest Authentication"
3. Observe the page behavior

### Expected Result
User should be prompted for digest authentication credentials or see a proper authentication dialog.

### Actual Result
The page fails to load and displays an HTTP 400 error message.

### Severity
High

### Priority
High
---------------------------------------------------------------------
## BUG-04: "Wait for it..." loading animation stacks up after completion on Dynamic Controls page

**Page:** Dynamic Controls  
**URL:** https://the-internet.herokuapp.com/dynamic_controls

### Steps to Reproduce
1. Open the Dynamic Controls page
2. Click the "Enable" button under the Enable/disable section
3. Wait until the loading animation completes
4. Click the "Enable" button again
5. Observe the loading animation behavior

### Expected Result
The loading animation ("Wait for it...") should appear once per action and be removed after the process
---------------------------------------------------------------------
## BUG-05: Floating Menu links do not navigate or trigger any page change

**Page:** Floating Menu  
**URL:** https://the-internet.herokuapp.com/floating_menu

### Steps to Reproduce
1. Open the Floating Menu page
2. Click on "Home"
3. Click on "News"
4. Click on "Contact"
5. Click on "About"
6. Observe the page behavior

### Expected Result
Clicking menu links should navigate to the corresponding page or section (e.g., change URL or scroll to the target content).

### Actual Result
Clicking menu links does not change the page or navigate to any section.

### Severity
Low

### Priority
Low
---------------------------------------------------------------------
## BUG-06: "Forgot Password" returns Internal Server Error after submitting email

**Page:** Forgot Password  
**URL:** https://the-internet.herokuapp.com/forgot_password

### Steps to Reproduce
1. Open the Forgot Password page
2. Enter a valid email address (e.g., ig.borisavljevic@gmail.com)
3. Click the "Retrieve password" button
4. Observe the result

### Expected Result
A confirmation message should be displayed (e.g., instructions sent to the provided email) or a success page should load without errors.

### Actual Result
The request fails and the application returns an Internal Server Error.

### Severity
High

### Priority
High

