# CodeCraft

CodeCraft is an online programming learning platform offering comprehensive tutorials for beginners to advanced developers. It provides structured learning paths, course modules, and PDF resources across a wide variety of programming languages and technologies.

## 🎨 Design System: Neo-Brutalism

The entire CodeCraft website is built using a custom **Neo-Brutalism** design system. This aesthetic emphasizes:
- High-contrast elements with bold, thick black borders (`4px solid`).
- Hard block drop shadows (`8px 8px 0px`) instead of soft, feathered shadows.
- Vibrant, punchy accent colors (Reds, Yellows, Teals, Purples).
- A distinctive radial-gradient grid background.
- A unified `.section` layout providing a consistent `100px auto` vertical rhythm across all pages.

## ✨ Features

- **Responsive Design**: Fully responsive layout that adapts gracefully from large desktop monitors down to mobile screens using CSS media queries.
- **Light/Dark Mode**: Integrated theme toggle that switches between light and dark neo-brutalist color palettes. The user's preference is saved locally using `localStorage` and persists seamlessly as you navigate between different course pages.
- **Scroll-to-Top**: A dynamic scroll-to-top button that appears as you navigate down the page, improving user experience on long curriculum pages.
- **Course Modules**: Clean, grid-based layouts (`display: grid`) to display course curriculums effectively.
- **PDF Downloads**: Dedicated sections for downloading comprehensive course materials for offline reading.

## 📚 Supported Courses & Tutorials

The platform includes dedicated, fully-styled tutorial pages for:
- HTML (`html.html`)
- CSS (`css.html`)
- JavaScript (`js.html`)
- Python (`python.html`)
- Java (`java.html`)
- C (`c.html`)
- C++ (`cpp.html`)
- SQL (`sql.html`)
- MongoDB (`mongodb.html`)
- Data Structures & Algorithms (DSA) (`dsa.html`)
- Database Management Systems (DBMS) (`dbms.html`)
- Full Stack Web Development (`fullstack.html`)

*(It also includes an `about.html` and standard `index.html` landing page)*

## 🛠️ Technology Stack

- **HTML5**: Semantic HTML structure.
- **Vanilla CSS**: Custom styling using CSS variables (`:root`) for easy theme management and dark-mode toggling, without relying on heavy external frameworks.
- **Vanilla JavaScript**: Lightweight scripts for theme toggling and scroll-to-top functionality.
- **Google Fonts**: Uses the **Poppins** font family (`wght@400;500;600;700;800;900`) for clean, modern, and bold typography suited for brutalism.
- **FontAwesome**: Utilizes FontAwesome 6.5.1 for UI icons (theme toggle moon/sun, social media icons, arrows).

## 🚀 Getting Started

To run the project locally, you don't need any complex build tools or servers.

1. Clone or download this repository.
2. Open `index.html` (or any of the course HTML files) in your favorite modern web browser (Chrome, Firefox, Safari, Edge).
3. Navigate through the site using the navigation bar or related course links at the bottom of the pages.

## 📂 Project Structure

All HTML files are standalone. The CSS variables, Neo-brutalism utility classes (`.neo-box`, `.neo-btn`), and JavaScript logic are embedded directly within each file. This architecture ensures each page is highly portable and loads its specific content instantly.

