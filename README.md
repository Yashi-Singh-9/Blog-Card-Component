# Blog Card Component

A visually appealing and responsive **Blog Card Component** designed to showcase blog posts with essential information such as title, category, author details, and more. This project was completed as part of a challenge on the FrontendPro platform.

## 🛠️ Technologies Used

- **HTML5**: Semantic and accessible structure for the component.
- **SCSS**: Modern styling with reusable variables and mixins for maintainable and modular CSS.
- **Bootstrap 5**: For layout and responsive utilities.
- **Google Fonts**: Open Sans for elegant typography.

## 🎨 Features

- **Responsive Design**: The card adapts seamlessly to various screen sizes using SCSS media queries and Bootstrap utilities.
- **Dynamic Styling**: Hover effects and transitions for interactive elements such as the category badge.
- **Clean UI/UX**: Simple yet functional layout with an emphasis on readability and aesthetic appeal.

## 📂 Folder Structure

```
.
├── design/                 # Assets such as images and icons
│   ├── icon.svg
│   ├── office-setup.jpg
│   └── user-image.png
├── index.html              # Main HTML file
├── styles.css              # Compiled CSS from SCSS
├── styles.css.map          # Source Map file   
├── styles.scss             # SCSS source file
└── README.md               # Project documentation
```

## 🚀 Live Demo

Check out the live demo of the component here: [Blog Card Component](https://yashi-singh-9.github.io/Blog-Card-Component/)

## 🖼️ Preview

**Desktop Design**
![Blog Card Component](design/Desktop-Design.png)  

**Mobile Design**

<img src="design/Mobile-Design.png" height="850">

*A clean and modern blog card component with responsive features.*

## 🔧 Installation and SCSS Compilation

Follow these steps to set up the project and compile SCSS:

### 1. Clone the Repository

Clone the project repository from GitHub:

```bash
git clone https://github.com/Yashi-Singh-9/Blog-Card-Component.git
```

### 2. Install SCSS Compiler (if not already installed)

To compile SCSS into CSS, you need to install a SCSS compiler. The recommended tool is `Sass`. Install it globally using npm:

```bash
npm install -g sass
```

### 3. Compile SCSS to CSS

Navigate to the project folder and run the following command to compile the SCSS file into CSS:

```bash
sass styles.scss styles.css
```

This will generate the `styles.css` file in the root directory.

### 4. Watch for SCSS Changes (Optional)

To automatically recompile SCSS whenever you make changes, use the `--watch` flag:

```bash
sass --watch styles.scss:styles.css
```

This will monitor the `styles.scss` file for changes and regenerate `styles.css` on every save.

### 5. Open the Project

After compiling the SCSS, open the `index.html` file in your browser to view the blog card component.

---

## 🌟 Challenge Details

This project was completed as part of a FrontendPro platform challenge. The goal was to build a responsive blog card component with the following requirements:
- Include an image, title, category badge, description, and author details.
- Style it with SCSS and incorporate responsive design principles.
- Use a professional font and minimalistic design.

## ✨ Improvements Made

- Enhanced responsiveness with SCSS media queries.
- Added hover effects for interactivity.
- Optimized layout with Bootstrap utilities for quick and clean alignment.

## 🤝 Contributing

Contributions are welcome! If you find a bug or have an idea to improve the component, feel free to open an issue or submit a pull request. For Contribution Steps please visit [Contributing File](CONTRIBUTING.md)

## 📄 License

This project is open source and available under the MIT License. Feel free to use and adapt it as needed.