# Personal Portfolio 🚀

## Project Description 📝

> 🌟 Welcome to Shogofa Developer's Portfolio! 🌟

Embark on a journey through the realm of web development with me, Shogofa Developer. 🚀

As a diligent web development enthusiast, I've dedicated numerous hours to refining my skills in remote development. From crafting sleek landing pages to mastering various projects, I've immersed myself in a wide array of tasks. My portfolio showcases a range of projects, each crafted with passion and attention to detail.

Join me as I continue to pursue excellence in the dynamic world of web development! 💻✨

---

Featuring:

- **Home:** Explore my story and passion for web development.
- **About:** Learn more about my dedication and journey in the field.
- **Projects:** Dive into my portfolio, featuring projects like Tribute Pages, Technical Documentation, and Landing Pages.
- **Contact:** Interested in collaborating or need assistance with a project? Reach out, and let's make it happen!

---

Crafted with simplicity and practicality, this portfolio serves as a testament to my dedication and skills in web development. Happy exploring! 🚀

```html
<!-- Welcome to Shogofa Developer's Portfolio! -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Shogofa Developer's Portfolio</title>
    <!-- Include Boxicons CSS -->
    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"
    />
    <!-- Include custom CSS -->
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <!-- Header section -->
    <header class="header">
      <a href="#" class="logo">
        <img src="images/mylogoo-removebg-preview.png" alt="Logo" />
      </a>
      <!-- Navigation -->
      <nav class="navbar">
        <a href="#hom" class="ac" style="--i: 1">Home</a>
        <a href="#about" style="--i: 2">About</a>
        <a href="#proj" style="--i: 3">Projects</a>
        <a href="#contact" style="--i: 4">Contact</a>
      </nav>
    </header>

    <!-- Home section -->
    <section class="home" id="hom">
      <!-- Home content -->
    </section>

    <!-- About section -->
    <section class="about" id="about">
      <!-- About content -->
    </section>

    <!-- Projects section -->
    <section class="projects" id="proj">
      <!-- Projects content -->
    </section>

    <!-- Contact section -->
    <section class="contact" id="contact">
      <!-- Contact content -->
    </section>
  </body>
</html>
```

```css
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  scroll-behavior: smooth;
}

.header {
  position: fixed;
  top: 0;
  left: 0;
  background-color: black;
  display: flex;
  justify-content: space-between;
  width: 100%;
  padding: 0 10%;
  align-items: center;
  z-index: 100;
}

.logo img {
  width: 200px;
  height: 80px;
  opacity: 0;
  animation: SlideR 1s ease forwards, updown 3s ease-in-out infinite;
  animation-delay: 0, 4s;
}

.home-content h1 {
  font-size: 56px;
  line-height: 130%;
  background-image: linear-gradient(
    -225deg,
    #ee5ff3 0%,
    #28f4f8 29%,
    #f2a456 67%,
    #ed5504 100%
  );
  background-size: 200% auto;
  color: #fff;
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  opacity: 0;
  animation: SlideR 1s ease forwards;
  animation-delay: 1s;
}
```

## Demo 📸

![Project Gif](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3UxeGJ5NWR1MGxwNXdsejNodXcxbHNqcHhvM291ZzM2M3lzdG03aiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/WgwvFuNaUPcXjRJGuj/giphy.gif)

## Technologies Used 🛠️

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Installation 💻

To install and set up this project, simply follow these steps:

1. **Clone the repository:**
   ```bash
   git clone git@github.com:shogof/Technical-Documentation-page.git
   ```

🎉 Once you've cloned the repository, you're all set to start exploring and using the project! If you encounter any issues or have questions, feel free to reach out for assistance. 🚀

## Usage 🎯

To use this project, follow these steps:

1. **Installation:**
   If you haven't already, follow the installation instructions mentioned in the [Installation](#installation-) section to clone the repository.

2. **Navigate to project directory:**
   ```bash
   cd Technical-Documentation-page
   ```
3. **Open the HTML file:**
   Open the index.html file in your preferred web browser. You can do this by double-clicking the file or using a command-line tool like open (for macOS) or start (for Windows).

4. **Explore the documentation:**
   Once the HTML file is opened, you'll have access to the technical documentation page. Navigate through different sections using the sidebar navigation or scroll through the content to learn about various topics.

5. **Modify as needed:**
   If you'd like to customize the documentation page or add your own content, feel free to edit the HTML and CSS files in your text editor of choice.

6. **Share and contribute:**
   If you find this project helpful, consider sharing it with others. You can also contribute to the project by submitting bug reports, feature requests, or pull requests to improve it for everyone.

## Author 👩‍💻

- LinkedIn: [Shegofa Developer](www.linkedin.com/in/shegofa-developer-aa362030b)
- Email: (shogofadeveloper12@gmail.com)

## Contributing 🤝

Thank you for considering contributing to this project! Contributions from the community help improve the project for everyone.

### How to Contribute

If you'd like to contribute to this project, follow these steps:

1.  **Fork the repository:**
    Fork the repository to your own GitHub account.

2.  **Clone the repository:**
    Clone the repository to your local machine.

    ```bash
    git clone https://github.com/Shegofa/Technical-Documentation-page.git
    ```

3.  **Create a new branch:**
    Create a new branch with a descriptive name to work on your contribution.

    ```bash
    git checkout -b feature/new-feature

    ```

4.  **Make your changes:**
    Make your changes to the project in your local environment. Ensure that your changes are in line with the project's coding conventions and style guidelines.

5.  **Commit your changes:**
    Once you've made your changes, commit them to your branch with clear and descriptive commit messages.

    ```bash
    git commit -a m 'Add new feature'

    ```

6.  **Push your changes:**
    Push your changes to your forked repository on GitHub.

    ```bash
    git push origin feature/new-feature

    ```

7.  **Submit a pull request:**
    Go to the original repository on GitHub and submit a pull request with your changes.
