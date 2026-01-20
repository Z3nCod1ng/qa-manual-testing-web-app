# Test Cases

## Home Page

### TC-01: Home page loads successfully
**Steps:**
1. Open https://the-internet.herokuapp.com

**Expected Result:**  
Home page loads and displays the list of available examples.

**Actual Result:**  
Home page loads successfully and examples are displayed.

**Status:**  
Pass

---------------------------------------------------------------

## Broken Images

### TC-02: Verify images are displayed correctly
**Steps:**
1. Open the Broken Images page
2. Observe the displayed images

**Expected Result:**  
All images should load and display correctly.

**Actual Result:**  
Some images are broken and not displayed.

**Status:**  
Fail (BUG-01)

---------------------------------------------------------------

## Digest Authentication

### TC-03: Access Digest Authentication page
**Steps:**
1. Open the home page
2. Click on "Digest Authentication"

**Expected Result:**  
User should be prompted for digest authentication credentials.

**Actual Result:**  
Page returns HTTP 400 error.

**Status:**  
Fail (BUG-03)

---------------------------------------------------------------

## Disappearing Elements

### TC-04: Verify navigation menu behavior on page reload
**Steps:**
1. Open the Disappearing Elements page
2. Refresh the page multiple times

**Expected Result:**  
Navigation elements may appear or disappear based on page load.

**Actual Result:**  
Menu items appear and disappear randomly as expected.

**Status:**  
Pass

---------------------------------------------------------------

## Dynamic Controls

### TC-05: Remove and add checkbox
**Steps:**
1. Open the Dynamic Controls page
2. Click "Remove"
3. Wait for operation to complete
4. Click "Add"

**Expected Result:**  
Checkbox is removed and added correctly.

**Actual Result:**  
Checkbox is removed and added correctly.

**Status:**  
Pass

---------------------------------------------------------------

### TC-06: Verify loading animation behavior
**Steps:**
1. Open the Dynamic Controls page
2. Click "Enable"
3. Wait until loading completes
4. Click "Enable" again
5. Observe the loading animation

**Expected Result:**  
Loading animation appears once per action and disappears after completion.

**Actual Result:**  
Loading animation sometimes stacks up after completion.

**Status:**  
Fail (BUG-04)

---------------------------------------------------------------

## Floating Menu

### TC-07: Verify floating menu behavior on scroll
**Steps:**
1. Open the Floating Menu page
2. Scroll down the page

**Expected Result:**  
Navigation menu remains visible while scrolling.

**Actual Result:**  
Menu remains visible during scroll.

**Status:**  
Pass

---------------------------------------------------------------

### TC-08: Verify floating menu navigation links
**Steps:**
1. Click on menu links (Home, News, Contact, About)

**Expected Result:**  
Clicking links should navigate to corresponding sections or trigger page change.

**Actual Result:**  
Links do not trigger navigation or page change.

**Status:**  
Fail (BUG-05)

---------------------------------------------------------------

## Forgot Password

### TC-09: Submit email for password recovery
**Steps:**
1. Open the Forgot Password page
2. Enter a valid email address
3. Click "Retrieve password"

**Expected Result:**  
Confirmation message or success page is displayed.

**Actual Result:**  
Application returns an Internal Server Error.

**Status:**  
Fail (BUG-06)

---------------------------------------------------------------

## File Downloader

### TC-10: Download file successfully
**Steps:**
1. Open the File Downloader page
2. Click on any file link

**Expected Result:**  
File download starts successfully.

**Actual Result:**  
File is downloaded successfully.

**Status:**  
Pass

---------------------------------------------------------------

## A/B Testing

### TC-11: Verify page variation behavior
**Steps:**
1. Open the A/B Testing page
2. Refresh the page multiple times

**Expected Result:**  
Different page variations may be displayed.

**Actual Result:**  
Different variations are displayed as expected.

**Status:**  
Pass
