## **HTML + CSS Homework – Sleek Card Component**

### General directions
1. Make a new folder called **`additional-hw-3`**.  
2. Inside it, create **one file**: `index.html`.  
3. Use Emmet (`!` ➜ *Enter*) to drop the standard HTML5 boilerplate.  
4. Test in a browser after each task.  
5. When done, upload one screenshot of your code **and** one screenshot of your rendered page to the Google Form.

---

### Task 1 – Page groundwork
| Step | What to do |
|------|------------|
| 1 | Set the `<title>` to **“Sleek Card Component”**. |
| 2 | Give the `<body>` a light-gray background `#f5f7fa`. |
| 3 | Reset the body’s default `margin` and `padding` to `0` using universal selector. |
| 4 | Add a default font: `'Inter', Arial, sans-serif`. |

---

### Task 2 – Build the card skeleton
Inside `<body>` add the following **in order**:

1. A parent `<div>` with the class **`sleek-card`**.  
2. An `<img>` with class **`sleek-card-image`** and the source  

https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=600&q=80

3. A child `<div>` with class **`sleek-card-content`** containing:  
- `<h2>` with class **`sleek-card-title`** and the text **“Minimal Portfolio”**.  
- `<p>` with class **`sleek-card-desc`** (write 2–3 lines about the card—your own words).  
- `<a>` with class **`sleek-card-btn`**, link `href="#"`, label **“View Project”**.

---

### Task 3 – Style the Card  
Inside your `<style>` tag, write rules so each selector below meets **every** design requirement.  
*(Tip : keep your CSS blocks short and tidy – one selector, several lines of properties.)*

| Selector | Design requirements you must reach — describe in your own CSS |
|----------|----------------------------------------------------------------|
| **`.sleek-card`** | • Give the card a fixed width of **340 px**.<br>• Fill it with a solid **white** background.<br>• Round **all four** corners by **18 px**.<br>• Outline it with a **1 px solid** border using the colour `rgba(0, 0, 0, 0.21)`. |
| **`.sleek-card-image`** | • Make the image exactly **340 px wide** and **160 px tall**.<br>• `object-fit: cover;`.<br>• Match the card’s curvature on the **top-left** and **top-right** corners (18 px each) with the help of border-radius property.<br>• Remove any space that might appear below the image.<br>• Make the display property to block. |
| **`.sleek-card-content`** | • Add generous interior padding: **26 px** on top & bottom, **24 px** on the left & right. |
| **`.sleek-card-title`** | • Increase the heading size to **20 px**.<br>• Make the text **bold** .<br>• Colour the text with the deep navy **`#181c2c`**.<br>• Remove default margins, then add a **12 px** gap **below** the heading only. |
| **`.sleek-card-desc`** | • Set the paragraph size to **16 px**.<br>• Use the muted grey **`#667`** for the text colour.<br>• Keep the top margin at **0**, but leave **22 px** of space beneath it. |
| **`.sleek-card-btn`** | • Create a comfortable click-area: **15 px** padding top/bottom and **28 px** left/right.<br>• Use a dark navy background **`#22243a`** with **white** text for strong contrast.<br>• Round the button edges by **10 px**.<br>• Match the paragraph font size (**16 px**) and make it **bold**.<br>• Remove default link underlines and borders.<br>• Change the cursor to a pointer when the user hovers. |

---


### Task 4 – Button hover
Add a hover state for `.sleek-card-btn` that darkens the background to **#1a1c30** (or any darker shade you prefer).

---

**Final output:**

![image1](../images/addional%203.png)