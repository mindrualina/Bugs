# Bugs

Below are some Bugs Samples that I wrote working on previous projects.

---

**Title:** Website icon not displayed 

**Description:** The website of the Alba Iulia city hall is experiencing a 404 error related to the favicon.ico:1 resource. The website icon (favicon) is not displayed as expected. 

**Steps to reproduce:**
1. Go to https://apulum.ro/
2. Visually inspect the browser tab or address bar for the presence of the browser icon (favicon).

**Expected result:** The website icon (favicon) should be displayed in the browser tab, providing visual identification for the Alba Iulia City Hall website.

**Actual result:** The website icon (favicon) is not visible in the browser tab or address bar.


---

**Title:** No error handling for random characters in the URL bar

**Description:** The website is currently lacking proper error handling when random or invalid characters are entered into the browser's URL bar.

**Steps to reproduce:**
1. Go to https://juice-shop.herokuapp.com/#/
2. In the browser's URL bar, enter random or invalid characters after the website's domain.
3. Press Enter to submit the URL.

**Expected result:** The website should display a clear error message or provide appropriate feedback indicating that the entered URL is invalid or does not exist.

**Actual result:** No error message or response is displayed when random characters are entered into the URL bar. \
The website does not handle invalid URLs, potentially leading to confusion for users.

---

**Title:** Design bug - Text clipping issue on "iPhone SE" view

**Description:** When selecting the iPhone SE view on the website, there is a design bug resulting in incomplete visibility of text. This issue is particularly noticeable when compared to the desktop (laptop) view, where the text is displayed correctly. The text appears to be truncated or clipped, impacting the overall readability and user experience on the iPhone SE.

**Steps to reproduce:**
1. Go to https://www.demoblaze.com/ on an iPhone SE device or select on the website "iPhone SE" view
2. Select any product
3. Observe the appearance of text on the screen.

**Expected result:** Text should be fully visible and legible when using iPhone SE view

**Actual result:** Text is partially visible when using iPhone SE view.

---

**Title:** Design bug - Innapropriate size images

**Description:** The two images displayed are difficult to understand due to the wrong size.

**Steps to reproduce:**
1. Go to https://juice-shop.herokuapp.com/#/
2. Select "Apple Pomace"
3. Select button "sent back to us"

**Expected result:** The two pictures on the page should be the right size and clear.

**Actual result:** The pictures are too narrow, they are not the correct size.

---


Theoretical example

**Title:** Login is not working properly

**Description:** When trying to login with the correct credentials, nothing happens. The user is not logged in and no error message is displayed.

**Steps to reproduce:**
1. Go to www.website.com/login
2. Add a correct username/password

**Expected result:** User should be able to login and is taken to his profile page.

**Actual result:** User is not logged and no error appears.

**Test data:** User: alina & Password: 123456

---
