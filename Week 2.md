## **HTML Homework Assignment**

*(Week 2 – Links, Forms, & Tables)*

### **General Instructions**

1. Do all tasks inside your **Personal Portfolio** project folder.  
2. Test your page in a browser after every major edit.  
3. When finished, **take a screenshot of your code and the rendered pages**.  
4. **Upload the screenshot(s) in the provided Google Form**.

## **Task 1: “Find Me Online” section**

1. **Add a new heading** (level 2\) titled **“Find Me Online”** directly below your “My Daily Routine” section.  
2. Optionally include a one-sentence paragraph inviting visitors to connect.  
   (for example: “You can follow my work on these platforms: ”)  
3. Create two `<a>` elements, one linking to your **LinkedIn** profile, the other to your **GitHub** page.   
4. Inside each `<a>`, use an `<img>` tag (rather than text) to display the appropriate icon.  
   * **LinkedIn Image Link:**  
     data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9ImN1cnJlbnRDb2xvciIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiIGNsYXNzPSJsdWNpZGUgbHVjaWRlLWxpbmtlZGluLWljb24gbHVjaWRlLWxpbmtlZGluIj48cGF0aCBkPSJNMTYgOGE2IDYgMCAwIDEgNiA2djdoLTR2LTdhMiAyIDAgMCAwLTItMiAyIDIgMCAwIDAtMiAydjdoLTR2LTdhNiA2IDAgMCAxIDYtNnoiLz48cmVjdCB3aWR0aD0iNCIgaGVpZ2h0PSIxMiIgeD0iMiIgeT0iOSIvPjxjaXJjbGUgY3g9IjQiIGN5PSI0IiByPSIyIi8+PC9zdmc+  
   * **Github Image Link:**  
     data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9ImN1cnJlbnRDb2xvciIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiIGNsYXNzPSJsdWNpZGUgbHVjaWRlLWdpdGh1Yi1pY29uIGx1Y2lkZS1naXRodWIiPjxwYXRoIGQ9Ik0xNSAyMnYtNGE0LjggNC44IDAgMCAwLTEtMy41YzMgMCA2LTIgNi01LjUuMDgtMS4yNS0uMjctMi40OC0xLTMuNS4yOC0xLjE1LjI4LTIuMzUgMC0zLjUgMCAwLTEgMC0zIDEuNS0yLjY0LS41LTUuMzYtLjUtOCAwQzYgMiA1IDIgNSAyYy0uMyAxLjE1LS4zIDIuMzUgMCAzLjVBNS40MDMgNS40MDMgMCAwIDAgNCA5YzAgMy41IDMgNS41IDYgNS41LS4zOS40OS0uNjggMS4wNS0uODUgMS42NS0uMTcuNi0uMjIgMS4yMy0uMTUgMS44NXY0Ii8+PHBhdGggZD0iTTkgMThjLTQuNTEgMi01LTItNy0yIi8+PC9zdmc+  
5. Specify a `width` attribute of about 40 (or whatever you prefer) so that each icon displays at roughly **40 × 40** pixels.  
6. Add the **attribute** `target="_blank"` to each `<a>` element so that its link opens in a new browser tab.

## **Task 2: My Favorites Table**

1. An `<h1>` titled **“My Favorite \[Topic\]”** — for example:  
    `"My Favorite Books"` or `"Top 5 Games I Love"` or `"My Dream Cars"`  
   or *(Choose any topic you enjoy\!)*  
2. One `<p>` explaining what the table shows (use at least one `<b>` or `<i>` tag).  
3. A single `<table>` that meets **all** of the following:  
4. First row is a header row (`<th>`).  
   * Minimum **4 rows of data** (not counting the header).  
   * At least **3 columns**.  
   * Borders visible (use the `border` attribute).  
5. Below the table, add one `<img>` that represents **any one item** from your table.

## **Task 3: Internal Page Navigation**

1. Create a **new file named `contact.html`** in the same folder as your main `index.html`.  
2. Use Emmet (`! → Enter`) to generate the HTML5 boilerplate.  
3. Add an `<h1>` titled **“Contact Me”**  
4. At the top of the both pages (`index` and `contact`), add a `<nav>` tag with two links inside.  
5. One that directs the user to Home(`index.html`) and second to Contact(`contact.html`).

## **Task 4: Contact Me Page**

Under the h1 heading add a single `<form>` tag inside the `<form>` tag do the following:

* Add label and an input field of type text for **Name** (required).  
* Add label and an input field of type email  for **Email** (required).  
* Add label and a textarea field for **Message** (required).  
* One additional control of your choice: `<select>`, radio buttons, or a checkbox.  
* A submit button.