# FHS Directory

A modern, single-page documentation site explaining the Filesystem Hierarchy Standard (FHS) for UNIX-like operating systems. Built with Astro and deployed to GitHub Pages.

## 🌐 Live Site

Visit [fhs.directory](https://fhs.directory) to view the live documentation.

## 🚀 Features

- Clean, modern design with responsive layout
- Comprehensive FHS documentation
- Fast loading with Astro's static site generation
- Automatic deployment via GitHub Actions
- Custom domain support

## 🛠️ Tech Stack

- [Astro](https://astro.build) - Static Site Generator
- GitHub Pages - Hosting
- GitHub Actions - CI/CD

## 📦 Local Development

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/fhs-directory.git
   cd fhs-directory
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## 🏗️ Project Structure

```
fhs-directory/
├── src/
│   ├── layouts/
│   │   └── Layout.astro    # Base layout component
│   └── pages/
│       └── index.astro     # Main documentation page
├── public/
│   └── favicon.svg         # Site favicon
├── .github/
│   └── workflows/          # GitHub Actions workflows
├── astro.config.mjs        # Astro configuration
└── package.json           # Project dependencies
```

## 🔄 Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch. The deployment process is handled by GitHub Actions.

### Custom Domain Setup

1. Add your custom domain in GitHub repository settings
2. Configure your DNS provider to point to GitHub Pages
3. Wait for DNS propagation (can take up to 24 hours)

## 📝 License

MIT License - feel free to use this project as a template for your own documentation sites.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
