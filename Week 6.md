## **CSS Homework Assignment**

*(Week 6 – CSS Flexbox)*

### **General Instructions**

1. Do all tasks inside your **Personal Portfolio** project folder.  
2. Test your page in a browser after every major edit.  
3. When finished, **take a screenshot of your code** and the **rendered pages**.  
4. Upload the screenshot(s) in the provided Google Form.

### **Task 1: Center Your Profile Image**

1. Open your `index.html` file.  
2. Wrap the `<img class="profile-img" …>` tag in a new `<div>` with the class name `profile-img-container`.  
    *(Place this new container directly below the `<h1>` element.)*  
3. Open your `index.css` file.  
4. Add a new style rule for `.profile-img-container`:  
   * Turn the `<div>` container into a Flexbox.  
   * Make the image appear on the screen centered **horizontally**.

### **Task 2: Showcase Your Tech Stack with Flexbox**

Follow these steps to add a new, neatly spaced row of tech-stack cards beneath your “Find Me Online” section:

1. **HTML structure**  
   * In `index.html`, add an `<h2>` titled **“My Tech Stack.”**  
   * Directly below that heading, insert a container `<div>` with the class **`tech-stack`**.  
   * Inside this container, create **four** child `<div>` elements, each with the class **`tech-stack-card`**.  
   * For every card, place the matching icon image and a short label inside `<p>` tag, like so:  
     * HTML: https://img.icons8.com/?size=100\&id=20909\&format=png\&color=000000  
     * CSS: https://img.icons8.com/?size=100\&id=21278\&format=png\&color=000000  
     * Bootstrap: https://img.icons8.com/?size=100\&id=PndQWK6M1Hjo\&format=png\&color=000000  
     * JavaScript: https://img.icons8.com/?size=100\&id=108784\&format=png\&color=000000  
2. **Layout with Flexbox**  
   * Open `index.css` and add a rule for `.tech-stack`.  
   * Turn the container into a Flexbox, keep the flex item centred on the page, and have a gap of 16px between the cards.  
3. **Card styling**  
   * Give each `.tech-stack-card` a simple border so the four blocks feel distinct.  
   * Center the caption text `<p>` under each icon for a tidy look.  
     (HINT: Use the descendant selector to select the `<p>` in `tech-stack-card`)  
4. Lastly, make the text centered in the `<h2>.`

### **Task 3: Arrange “Find Me Online” and “My Tech Stack” Side‑by‑Side**

You’ll now bring two separate sections together inside one Flexbox wrapper so they sit neatly next to each other.

1. **Group the sections in HTML**  
   * Inside the `index.html`:   
   * Immediately above the **“Find Me Online”** heading, insert a new container `<div>` with the class `flex-wrapper`.  
   * Now wrap each of the section \- **“Find Me Online”** and **“My Tech Stack”** inside a `<div>`.  
   * And move these two `<div>`‘s inside the `info-wrapper`.  
   * When you’re done, the `flex-wrapper` `<div>` should contain exactly two child `<div>`: one for “Find Me Online,” the other for “My Tech Stack.”  
2. **Convert the wrapper into a row layout**  
   * Open `index.css`.  
   * Add a rule for `.flex-wrapper` that turns the container into a Flexbox layout.  
   * Ensure the two child blocks share the **horizontal space evenly**, have margin of 50px top and bottom and `flex-wrap: wrap;` property.

### **Task 4: Display “My Top 3 Hobbies” and “My Daily Routine” Side‑by‑Side**

You’ll reuse the **`flex-wrapper`** class to place your two list sections in a single horizontal row. This shows how one Flexbox utility class can serve multiple layout needs.

1. Locate the existing “My Top 3 Hobbies” heading and its `<ul>`, and the “My Daily Routine” heading with its `<ol>`.  
2. Insert a new container `<div>` directly **above** the first heading and give it the class `flex-wrapper`.  
3. Wrap **each** list section (its `<h2>` plus the list) inside its own inner `<div>`.  
4. Move these two inner `<div>` elements so they sit inside the new `flex-wrapper`.  
5. Confirm that `flex-wrapper` now has exactly two direct children.