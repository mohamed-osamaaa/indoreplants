

https://github.com/user-attachments/assets/a471af90-24ed-4566-aae1-0ef1b1ae706f



https://github.com/user-attachments/assets/eb870b6a-ae5c-4107-b167-44e6acbcd577



https://github.com/user-attachments/assets/b2d49fe9-accc-471c-bf01-9c3e03721956


# Indoreplants

Indoreplants is a web project showcasing a beautifully designed website for promoting plants and their positive impact on the environment. Built with Tailwind CSS for styling and ScrollReveal.js for smooth animations, this project highlights the modern front-end development techniques and tools.

## Features

- **Responsive Design**: Optimized for different screen sizes using Tailwind CSS.
- **Interactive Animations**: Scroll-based animations implemented with ScrollReveal.js.
- **Dynamic Components**: Includes buttons, headers, and content sections with hover effects.
- **Social Media Integration**: Links to Facebook, X (formerly Twitter), and Instagram.
- **Custom Sections**: About Us, Services, Product Highlights, and Customer Reviews.

## Demo

Explore the live demo of the project: [Indoreplants](https://mohamed-osamaaa.github.io/indoreplants/)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mohamed-osamaaa/indoreplants.git
   ```
2. Navigate to the project directory:
   ```bash
   cd indoreplants
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start a local development server:
   ```bash
   npm run dev
   ```
5. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## Usage

### HTML Structure

- The HTML file (`index.html`) contains well-structured sections for the header, main content, and footer.
- Class names are defined according to Tailwind CSS conventions.
- Images, text, and icons are used for visual appeal.

### JavaScript Functionality

- The `main.js` file initializes ScrollReveal animations for elements with the class `animClass`:
  ```javascript
  const sr = ScrollReveal({
      origin: "top",
      distance: "60px",
      duration: 2500,
      delay: 300,
      reset: true,
  });
  sr.reveal(`.animClass`);
  ```

## Technologies Used

- **HTML5**: For the website structure.
- **CSS3 (Tailwind CSS)**: For modern styling and responsive design.
- **JavaScript (ScrollReveal.js)**: For interactive animations.
- **FontAwesome**: For social media and decorative icons.

## File Structure

```
indoreplants/
├── assets/
│   ├── img/
│   │   ├── home.png
│   │   ├── leaf-2.png
│   │   ├── leaf-3.png
│   │   ├── leaf-4.png
│   │   ├── plant-1.png
│   │   ├── plant-2.png
│   │   ├── cart-1.png
│   │   └── cart-2.png
├── index.html
├── main.js
├── output.css
└── README.md
```

## Customization

- Update the text and images in `index.html` as needed.
- Modify the Tailwind configuration to change the theme or add custom styles.
- Adjust the ScrollReveal settings in `main.js` for different animation effects.

