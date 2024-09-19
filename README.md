
# SimpliCSS

![SimpliCSS Logo](https://raw.githubusercontent.com/baidou5/SimpliCSS/main/bgs.jpg)

Created by Abdellah Baidou  
Contact: +212 661-176711  
Email: baidou.abd@gmail.com

**SimpliCSS** is a lightweight, utility-first CSS framework designed to simplify the development of modern, responsive websites. It aims to be an easy-to-use alternative to more complex frameworks, offering a streamlined and intuitive approach to styling. While inspired by popular frameworks, SimpliCSS focuses on simplicity, efficiency, and flexibility.

 
## Key Features

- **Utility-First Design**: Embrace a utility-first approach with a comprehensive set of utility classes that enable rapid development without writing custom CSS. Build layouts and styles efficiently using pre-defined classes.

- **Minimalist Syntax**: SimpliCSS offers a simplified class naming convention that prioritizes ease of use and memorability. This design choice enhances productivity by reducing the cognitive load associated with more complex class names.

- **Responsive Utilities**: Leverage built-in responsive utilities to ensure your designs adapt seamlessly across various screen sizes. With SimpliCSS, you can manage responsive behaviors with minimal effort and maintain a consistent user experience on all devices.

- **Lightweight and Performance-Focused**: The framework is intentionally lightweight, including only essential features to keep your projects lean and fast. Avoid unnecessary bloat and enjoy a streamlined development experience with SimpliCSS.

- **Customizable and Extendable**: Easily tailor the framework to meet your specific needs. The `SimpliCSS.css` file is designed for straightforward customization, allowing you to modify existing utilities or add new ones to fit your project's requirements.

- **Flexbox and Grid Layouts**: Utilize modern layout techniques with built-in Flexbox and Grid utilities. Simplify complex layout designs and achieve flexible, responsive layouts without the need for additional CSS.

- **Consistent Design Language**: Achieve a cohesive look and feel throughout your project with a consistent design language. SimpliCSS provides a unified set of utilities that ensure visual harmony and reduce inconsistencies in styling.

- **Easy Integration**: Seamlessly integrate SimpliCSS into your projects with minimal setup. Whether using the CDN or local installation, getting started with SimpliCSS is straightforward and hassle-free.

- **Optimized for Modern Development**: Designed with modern web development practices in mind, SimpliCSS ensures compatibility with contemporary design standards and browser requirements.

 
## Installation

### Using the CDN

To include SimpliCSS via CDN, add the following link to your HTML's `<head>` section:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/baidou5/SimpliCSS@main/SimpliCSS/SimpliCSS.css">
```

### Local Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/baidou5/SimpliCSS.git
   ```

2. Navigate into the project directory:

   ```bash
   cd SimpliCSS
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Build the CSS:

   ```bash
   npm run build:css
   ```

5. Include the `SimpliCSS.css` file in your project:

   ```html
   <link rel="stylesheet" href="node_modules/simpli-css/dist/SimpliCSS.css">
   ```
or  Include SimpliCSS in Your Project:
   You can include SimpliCSS in your project by importing it into your CSS file:
   ```html
   @import 'node_modules/simpli-css/dist/SimpliCSS.css';
   ```



## Usage

SimpliCSS utilizes simple utility classes to style your elements. Apply these classes to your HTML elements to quickly create layouts and style your content.

### Example Usage

```html
<div class="bg-blue text-white p-2 rounded-md shadow-md">
  This is a simple card component!
</div>
```

### Responsive Classes

SimpliCSS includes responsive utilities to control how elements behave on different screen sizes. For example:

```html
<div class="bg-light md:bg-dark lg:bg-black">
  Responsive background color change!
</div>
```

Here, the background color changes based on the screen size (`md` for medium screens and `lg` for large screens).

## Example Code

Here's a basic example of a webpage using SimpliCSS:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SimpliCSS Example</title>
  <link rel="stylesheet" href="path/to/SimpliCSS.css">
</head>
<body>
  <div class="flex justify-center items-center h-screen bg-light">
    <div class="bg-blue text-white p-3 rounded-lg shadow-lg">
      Welcome to SimpliCSS!
    </div>
  </div>
</body>
</html>
```

This creates a simple centered message with a blue background and a white text box.

## Customization

SimpliCSS is designed with simplicity in mind but is also fully customizable. To modify the framework:

1. Open `SimpliCSS.css` in your preferred code editor.
2. Adjust the styles, breakpoints, or add your own custom utility classes.
3. Save your changes and rebuild the CSS:

   ```bash
   npm run build:css
   ```

## Roadmap

Here are some planned features and improvements for SimpliCSS:

- **Component Support**: Include ready-made UI components (like buttons, cards, etc.) for even faster development.
- **Dark Mode Support**: Add utilities for dark mode styling.
- **Advanced Animations**: Include a utility-based animation system for adding transitions and effects.
- **More Flexibility**: Continue simplifying the customization process, allowing users to build their own version of SimpliCSS with ease.

## Contributing

Contributions are welcome! If you’d like to help improve SimpliCSS:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some amazing feature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Thank you for using SimpliCSS! We hope it helps you build amazing projects.
```

Feel free to adjust any sections to better fit your framework's features and capabilities!
