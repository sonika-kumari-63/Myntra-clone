<h1>Myntra Clone - README</h1>  
This project is a **frontend-only Myntra Clone** built using **HTML** and **CSS**. It replicates the visual layout and design of the popular e-commerce platform Myntra, featuring a responsive navbar, offer sections, category-based product display, and footer.

<h2>This clone is suitable for learning:</h2>
* Website layout structuring
* CSS styling and page organization
* Responsive design using media queries
* Using images to replicate UI sections


## Technologies Used

### **1. HTML5**

Used to create the overall structure of the webpage including:

* Navbar
* Banner section
* Category/Deals sections
* Footer

### **2. CSS3**

Used for:

* Custom styling
* Flexbox-based layout
* Responsive design
* Button/hover effects
* Shadows, spacing, typography

---

## 📁 Project Structure

```
Myntra-Clone/
│
├── index.html        # Main webpage
├── style.css         # Stylesheet for UI
├── images/           # Folder containing UI images/screenshots
│   ├── images.png
│   ├── offer-banner.png
│   ├── category1.png
│   └── ... more images
```

> Note: In your actual project, replace screenshot file names with the correct image names.

---

## 📄 File Descriptions

### **1. index.html**

This file contains the structure of the entire Myntra clone:

* **Navbar** with logo, links, search bar, and icons
* **Banner/Offers** section displaying promotional banners
* **Deal Cards & Category Listings** arranged using Flexbox
* **Footer** with three information sections

### **2. style.css**

This file manages the look and feel of the webpage:

* Reset styling using `* { margin: 0; padding: 0; }`
* Navbar design (sticky, shadow, alignment)
* Offer cards styling (shadow, hover effects, alignment)
* Category grid styling
* Footer styling
* Media queries for mobile responsiveness

---

## ⭐ Key Features

### **1. Fully Styled Navbar**

* Sticky at the top
* Contains brand logo, navigation links, search bar, profile/wishlist/bag icons

### **2. Deals & Category Sections**

* Multiple horizontally aligned Flexbox sections
* Each contains a product image, discount details, and CTA text

### **3. Responsive Layout**

* Media queries adjust layout at **750px** and **600px** breakpoints
* Mobile users see stacked sections

### **4. Clean UI with Shadows & Colors**

* Modern card-based design
* Soft shadows for depth
* Highlighted offer/info backgrounds

---

## 📱 Responsive Design Details

### **Breakpoints Used**:

* **750px:**

  * Navbar stacks vertically
  * Smaller search bar
  * Footer becomes centered

* **600px:**

  * Category sections wrap into vertical layout

> Note: There is a typo in the code → `@meadia` should be `@media`. Fixing it will ensure correct responsiveness.

---

## 🚀 How to Run the Project

1. **Download/Clone the project**
2. Place all image files inside an `/images` folder
3. Open `index.html` in any browser (Chrome, Edge, Firefox)
4. No dependencies or frameworks required

---

## 🛠️ Customization Guide

### **To change images:**

Replace `<img src="...">` with your desired image path.

### **To modify deals or categories:**

Edit the content inside:

```html
<div class="offer-card"> ... </div>
```

### **To add new categories:**

Copy & paste an existing `offer-card` block inside any `.category-section`.

---

## ⚠️ Known Issues & Fixes

### **1. Typo in media query**

```css
@meadia (max-width: 400px)  ❌ WRONG
```

Should be:

```css
@media (max-width: 400px) ✔️ CORRECT
```

### **2. Hard‑coded image sizes**

Some images are stretched. You can adjust using:

```css
object-fit: contain;
```

### **3. Too many repeated CSS values**

You can optimize by grouping card styles.

---

## 📸 Screenshots (Optional)

You can include UI screenshots here for project documentation.

---

## 📚 Learning Outcomes

After building this Myntra clone, you will learn:

* HTML structuring for large web pages
* Working with Flexbox to create grid-like layouts
* Styling reusable card components
* Improving UI/UX with spacing & shadows
* Making web pages responsive

---

## 📌 Future Improvements (Optional Enhancements)

You can expand the project with:

* JavaScript‑based search functionality
* Product detail page
* Login/signup page
* Add to cart / wishlist features
* Backend integration (Node.js / Firebase)

---

## 🏁 Final Notes

This project is perfect for beginners practicing front‑end development. You can use it as part of your portfolio or as the foundation for a fully functional e‑commerce website.

If you want, I can help you:

* Add JavaScript functionality
* Make the page fully responsive
* Convert it into a React project
* Optimize folder structure
