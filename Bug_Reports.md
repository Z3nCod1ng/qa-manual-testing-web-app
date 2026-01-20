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
