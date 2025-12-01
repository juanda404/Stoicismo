# Memento Mori - Remember that you will die. Live better.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📖 Description

**Memento Mori** is a website inspired by Stoic philosophy that explores the meaning of the Latin phrase "Remember that you will die." This project aims to inspire clarity, purpose, and actions aligned with what truly matters in life.

The page features educational content about the historical origin of Memento Mori, practical examples for applying it in daily life, and inspirational quotes from Stoic philosophers like Marcus Aurelius.

## ✨ Features

- 🌓 **Dark/Light Mode**: Toggle between themes with a single click
- 📱 **Responsive Design**: Optimized for mobile devices, tablets, and desktop
- 🎨 **Minimalist Aesthetic**: Golden colors (#d4af37) on dark/light backgrounds
- ⚡ **Performance**: Fast loading with Tailwind CSS CDN
- ♿ **Accessibility**: HTML5 semantic tags and optimized meta tags
- 🔍 **SEO Optimized**: Meta description, keywords, and robots configured

## 🚀 Live Demo

You can see the page in action here: [View Demo](#) *https://stoicismo.netlify.app/*

## 🛠️ Technologies Used

- **HTML5**: Semantic site structure
- **Tailwind CSS 3**: CSS utility framework for styling
- **Vanilla JavaScript**: Theme toggle functionality
- **Google Fonts** *(Optional)*: Modern typography

## 📂 Project Structure

```
memento-mori/
│
├── index.html              # Main page
├── README.md               # This file
│
└── src/
    ├── assets/
    │   ├── apple-touch-icon.png
    │   ├── favicon-32x32.png
    │   ├── favicon-16x16.png
    │   └── site.webmanifest
    │
    └── output.css          # (Optional) Compiled Tailwind CSS
```

## 📦 Installation and Usage

### Option 1: Direct Use (Recommended)

1. Clone this repository:
```bash
git clone https://github.com/juanda404/memento-mori.git
cd memento-mori
```

2. Open `index.html` directly in your browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

### Option 2: Local Server

If you prefer to use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎨 Customization

### Change Colors

Main colors are defined in Tailwind classes:

```html
<!-- Primary golden color -->
text-[#d4af37]

<!-- Dark golden variant -->
text-[#c5a028]

<!-- Dark background -->
bg-[#111111]
```

You can modify these hex values in the HTML according to your preferred color palette.

### Modify Content

Edit sections directly in `index.html`:

```html
<section class="space-y-4">
  <h2 class="text-[#c5a028] text-3xl font-semibold">
    Your Title Here
  </h2>
  <p class="text-[#e5e5e5]">
    Your content here...
  </p>
</section>
```

## 🌐 Deployment

### GitHub Pages

1. Upload your repository to GitHub
2. Go to **Settings** → **Pages**
3. Select the `main` branch and `/root` folder
4. Save and wait a few minutes

### Netlify

1. Drag the project folder to [netlify.com/drop](https://app.netlify.com/drop)
2. Your site will be online instantly

### Vercel

```bash
npm i -g vercel
vercel --prod
```

## 🤝 Contributing

Contributions are welcome. If you want to improve this project:

1. Fork the repository
2. Create a branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Roadmap

- [ ] Add entrance animations (fade-in)
- [ ] Implement random quotes section
- [ ] Add days lived counter (calculator)
- [ ] Integrate daily Stoic phrases
- [ ] Multi-language version (ES/EN/FR)
- [ ] Stoic reflections blog

## 🐛 Known Issues

- Dark mode doesn't persist on reload (due to localStorage limitations in some environments)
- Favicons require manual path configuration

## 📄 License

This project is under the MIT License. See the `LICENSE` file for more details.

## 👨‍💻 Author

**Juan David Santamaría**

- GitHub: [@juanda404](https://github.com/juanda404)
- LinkedIn: [juandasantamaria](https://www.linkedin.com/in/juandasantamaria)
- Email: juandasantamaria404@gmail.com
- Location: Jamundí, Valle del Cauca, Colombia

## 🙏 Acknowledgments

- Stoic Philosophy and Marcus Aurelius for the inspiration
- Tailwind CSS community for the framework
- Design inspired by Japanese simplicity and minimalism

## 📚 References

- [Meditations by Marcus Aurelius](https://en.wikipedia.org/wiki/Meditations)
- [Stoicism on Wikipedia](https://en.wikipedia.org/wiki/Stoicism)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

---

⭐ If you found this project useful, consider giving it a star on GitHub

*"You could leave life right now. Let that determine what you do, say, and think." — Marcus Aurelius*
