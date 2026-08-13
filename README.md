# Kartu Digital Saya - Portfolio

A modern, professional personal portfolio website for Acharius Maximilanus Sumeisey.

## 🎯 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Scrolling** - Elegant transitions when navigating between sections
- **Interactive Elements** - Hover effects and smooth animations
- **Component-Based Architecture** - Modular HTML structure for easy maintenance
- **Modern Styling** - Clean, professional design with custom CSS
- **Profile Section** - Large, centered profile image with glowing border
- **Animated Background** - Floating gradient shapes in the hero section
- **Organized Sections**:
  - Hero introduction
  - About me
  - Skills & expertise
  - Featured projects
  - Contact information

## 📁 Project Structure

```
kartu-digital-saya/
├── index.html              # Main entry point
├── styles.css              # All styling
├── Foto.jpeg              # Profile picture
├── components/
│   ├── nav.html           # Navigation bar
│   ├── hero.html          # Hero section
│   ├── about.html         # About section
│   ├── skills.html        # Skills section
│   ├── projects.html      # Projects section
│   ├── contact.html       # Contact information
│   └── footer.html        # Footer
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code recommended)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AchariusM/kartu-digital-saya.git
cd kartu-digital-saya
```

2. Open with Live Server:
   - Install "Live Server" extension in VS Code
   - Right-click `index.html` → "Open with Live Server"
   - Browser opens with auto-reload on file changes

3. Or use Python's built-in server:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

## ✏️ Customization

### Edit Contact Information
- **Email**: Edit `components/contact.html`
- **LinkedIn**: Update the LinkedIn URL in `components/contact.html`
- **GitHub**: Add your GitHub link in `components/contact.html`

### Update Profile Picture
- Replace `Foto.jpeg` with your own image (same filename)
- Or update the image path in `components/hero.html`

### Modify Skills
- Edit `components/skills.html` to add/remove skills
- Add more skill cards by duplicating the existing ones

### Add Projects
- Edit `components/projects.html` to add your projects
- Update project titles, descriptions, and technologies

### Change Colors
- Edit `styles.css` and modify the CSS variables in `:root`:
```css
:root {
  --primary: #1a1a2e;
  --secondary: #0f3460;
  --accent: #00d4ff;
  --text: #eaeaea;
  --text-dark: #333;
  --bg: #f5f5f5;
}
```

## 📝 Sections

### Hero Section
Large profile picture on the left with introduction text and call-to-action buttons on the right.

### About Section
Personal information and biography describing your background and approach.

### Skills Section
Three skill cards showcasing your frontend, backend, and tools expertise.

### Projects Section
Featured projects with descriptions and technology tags.

### Contact Section
Email, GitHub, and LinkedIn contact information.

## 🎨 Design Highlights

- **Color Scheme**: Dark blue primary with cyan accents
- **Typography**: Clean sans-serif fonts
- **Animations**: Smooth transitions and hover effects
- **Layout**: Responsive grid system that adapts to screen size
- **Background**: Animated gradient shapes in hero section

## 📱 Responsive Breakpoint

The site is optimized for:
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (< 768px)

## 🔧 Technologies Used

- HTML5
- CSS3 (with CSS Grid & Flexbox)
- JavaScript (for component loading)
- Responsive Design

## 📤 Deployment

To deploy your portfolio:

1. **GitHub Pages** (Free):
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose `main` branch
   - Your site will be live at `https://AchariusM.github.io/kartu-digital-saya`

2. **Netlify** (Free):
   - Connect your GitHub repo
   - Deploy with one click

3. **Vercel** (Free):
   - Import your GitHub repo
   - Auto-deploy on push

## 📝 License

This portfolio is personal to Acharius Maximilanus Sumeisey.

## 📧 Contact

- **Email**: achariusm@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/acharius-maximilanus-sumeisey-8030503b6
- **GitHub**: https://github.com/AchariusM

---

Made with ❤️ by Acharius Maximilanus Sumeisey
