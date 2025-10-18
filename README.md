# My Hugo Site

A personal CV/resume website built with Hugo using the Almeida CV theme. This site showcases professional experience, skills, projects, and contact information in a clean, responsive design.

## Features

- **Responsive Design**: Optimized for desktop and mobile devices
- **CV/Resume Layout**: Professional presentation of personal information
- **Hugo Static Site Generator**: Fast, secure, and SEO-friendly
- **Almeida CV Theme**: Modern, customizable theme with multiple color schemes
- **Multi-language Support**: Support for multiple languages (currently English and Vietnamese)
- **Contact Integration**: Direct links to email, phone, and social profiles

## Quick Start

### Prerequisites

Before you begin, ensure you have the following installed:

- [Hugo](https://gohugo.io/getting-started/installing/) (Extended version recommended)
- [Git](https://git-scm.com/downloads)
- A code editor (VS Code recommended)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TrungQNdev20/my-hugo-site.git
   cd my-hugo-site
   ```

2. **Install Hugo (if not already installed):**
   - **Windows:** Download from [Hugo releases](https://github.com/gohugoio/hugo/releases) and add to PATH
   - **macOS:** `brew install hugo`
   - **Linux:** `sudo apt install hugo` or `sudo dnf install hugo`

3. **Run the development server:**
   ```bash
   hugo server
   ```

4. **Open your browser** and navigate to `http://localhost:1313`

## Project Structure

```
my-hugo-site/
├── archetypes/          # Content templates
├── assets/             # SCSS source files
├── content/            # Markdown content files
├── data/               # YAML data files (CV content)
├── layouts/            # Custom layout templates
├── public/             # Generated static site (after build)
├── static/             # Static assets (images, etc.)
├── themes/             # Hugo themes
├── config.toml         # Site configuration
└── hugo.toml          # Additional Hugo configuration
```

## Customization

### Personal Information

Edit `data/content.yaml` to update:
- Basic info (name, photo, contacts)
- Profile description
- Work experience
- Education
- Skills and technologies
- Projects
- Languages
- Interests

### Site Configuration

Modify `config.toml` for:
- Site title and base URL
- Theme settings
- Color scheme customization
- Language settings

### Colors and Styling

The theme supports extensive color customization. Key color variables in `config.toml`:

```toml
[params]
colorLight = "#fff"
colorDark = "#666"
colorPrimary = "#e3bfb8"
colorSecondary = "#aaa"
colorPageBackground = "#ddd"
# ... more color options
```

### Adding Content

1. **Images:** Place in `static/img/` directory
2. **New pages:** Create markdown files in `content/` directory
3. **Data updates:** Modify YAML files in `data/` directory

## Building for Production

1. **Build the site:**
   ```bash
   hugo
   ```

2. **Deploy the `public/` directory** to your web server or hosting platform

### Deployment Options

- **GitHub Pages:** Push the `public/` folder to a `gh-pages` branch
- **Netlify:** Connect your repository for automatic builds
- **Vercel:** Deploy directly from GitHub
- **Traditional hosting:** Upload `public/` contents to your server

## Development Commands

```bash
# Start development server with live reload
hugo server

# Build site for production
hugo

# Build with minification
hugo --minify

# Clean public directory
hugo --gc

# View help
hugo --help
```

## Theme Information

This site uses the [Almeida CV Hugo Theme](https://github.com/ines/hugo-theme-almeida-cv).

### Theme Features

- Clean, professional CV layout
- Responsive design
- Customizable color schemes
- Font Awesome icons
- Print-friendly styles
- SEO optimized

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

If you have questions or need help:
- Check the [Hugo documentation](https://gohugo.io/documentation/)
- Review the [Almeida CV theme documentation](https://github.com/ines/hugo-theme-almeida-cv)
- Open an issue on this repository

## Author

**Nguyễn Quốc Trung**
- Website: [quoc-trung.dev](https://quoc-trung.dev)
- Email: paulonguyen3@gmail.com
- GitHub: [@TrungQNdev20](https://github.com/TrungQNdev20)
