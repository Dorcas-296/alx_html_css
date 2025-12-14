Headphones
📌 Project Overview

Headphones is a responsive web page built from a Figma design provided by ALX. The goal of this project is to accurately convert a professional UI design into clean, semantic HTML and modern CSS while respecting responsiveness, interactions, and layout constraints.

The project demonstrates attention to detail, proper use of CSS, and the ability to translate design specifications into functional code.

🎨 Figma Design

The design for this project was provided as a downloadable Figma (.fig) file.

To access the design:

Download the .fig file from the provided link

Open https://www.figma.com/files

Click New → Import, or drag and drop the .fig file into Figma

Click “Duplicate to Drafts” to inspect all design details

🔗 Design Source:
https://savanna.alxafrica.com/rltoken/BzcwTuQuVymfPmk1ivgdeg

✨ Features

Pixel-accurate implementation from Figma

Fully responsive layout

Mobile view activates at screen width ≤ 480px

Hover and active interactions for links and buttons

Centered content with a maximum width of 1000px

Custom fonts as specified in the design

📱 Responsiveness

The layout switches to a mobile version when the screen width is 480px or less using CSS media queries.

@media (max-width: 480px) {
    /* Mobile styles */
}

🎯 Interactions
Links
a:hover,
a:active {
    color: #FF6565;
}

Buttons
button:hover,
button:active {
    opacity: 0.9;
}

🧱 Layout Constraint

All main content is centered and constrained to a maximum width of 1000px.

.container {
    max-width: 1000px;
    margin: 0 auto;
}

🔤 Fonts Used

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