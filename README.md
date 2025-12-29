# Headphones

## Project Overview
Headphones is a responsive web page built from a Figma design provided by ALX.  
The project demonstrates accurate conversion of a UI design into clean HTML and CSS, with proper responsiveness and interactions.

## Figma Design
The design was provided as a downloadable Figma (.fig) file.  
To access the design:
1. Download the `.fig` file from the provided link  
2. Open [Figma](https://www.figma.com/files)  
3. Click **New → Import** or drag the file into Figma  
4. Click **“Duplicate to Drafts”** to inspect details  

🔗 **Design source:**  
https://savanna.alxafrica.com/rltoken/BzcwTuQuVymfPmk1ivgdeg

## Features
- Pixel-accurate implementation from Figma  
- Fully responsive layout  
- Mobile view activates at **screen width ≤ 480px**  
- Hover and active interactions for links and buttons  
- Centered content with a maximum width of **1000px**  
- Fonts: **Source Sans Pro** and **Spin Cycle OT**


## Responsiveness
```css
@media (max-width: 480px) {
    /* Mobile styles */
}

a:hover,
a:active {
    color: #FF6565;
}

Buttons

button:hover,
button:active {
    opacity: 0.9;
}

 Layout Constraint

All main content is centered and constrained to a maximum width of 1000px.

.container {
    max-width: 1000px;
    margin: 0 auto;
}

 Fonts Used

The following fonts are used in this project as specified in the Figma design:

Source Sans Pro

Spin Cycle OT

If these fonts are not available on your system, they should be installed to ensure accurate rendering.

🛠 Technologies Used

HTML5

CSS

Figma

📂 Project Structure
headphones/
│── index.html
│── styles.css
│── README.md

🚀 How to Run the Project

Clone this repository

Open index.html in your browser

Ensure required fonts are installed

Resize the browser window to test responsiveness

👤 Author
Dorcas Okeleji
Front-End Developer
ALX Software Engineering Program