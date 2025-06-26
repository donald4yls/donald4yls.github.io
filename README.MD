# Donald's Blog

![Node.js >= 20](https://img.shields.io/badge/node.js-%3E%3D20-brightgreen) 
![pnpm >= 9](https://img.shields.io/badge/pnpm-%3E%3D9-blue) 
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)](https://donald4yls.github.io)

A modern static blog built with [Astro](https://astro.build) and powered by the Fuwari theme. This repository hosts my personal blog where I record my life experiences and share my thoughts on technology, development, and beyond.

🌐 **Live Site**: [donald4yls.github.io](https://donald4yls.github.io)

## 📖 Introduction

Welcome to my digital space! This blog serves as a platform where I document my journey through technology, share insights from my development experiences, and reflect on various aspects of life. Built with modern web technologies, it offers a clean, responsive, and fast browsing experience.

## ✨ Features

- 🚀 **Built with Astro** - Lightning-fast static site generation
- 🎨 **Tailwind CSS** - Modern, responsive design
- 🌓 **Dark/Light Mode** - Automatic theme switching with user preference
- 🔍 **Full-text Search** - Powered by Pagefind for instant content discovery
- 📱 **Mobile Responsive** - Optimized for all device sizes
- 🏷️ **Categorization & Tags** - Organized content structure
- 📊 **Table of Contents** - Easy navigation within posts
- 🔗 **RSS Feed** - Stay updated with new content
- ⚡ **Smooth Animations** - Enhanced user experience with page transitions
- 🛠️ **Markdown Extended** - Rich content formatting with custom components
- 🌈 **Customizable Theme** - Personalized color schemes
- 📈 **SEO Optimized** - Search engine friendly

## 🚀 Quick Start

### Prerequisites

- Node.js >= 20
- pnpm >= 9

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/donald4yls/donald4yls.github.io.git
   cd donald4yls.github.io/my_blog
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

3. **Start development server**
   ```bash
   pnpm dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:4321` to see the blog in action.

## 📝 Content Creation

### Creating a New Post

Use the built-in script to create a new blog post:

```bash
pnpm new-post
```

This will generate a new markdown file in `src/content/posts/` with the proper frontmatter structure.

### Post Structure

Posts are located in `src/content/posts/` and use the following frontmatter:

```yaml
---
title: "Your Post Title"
published: 2025-06-26
description: "Brief description of your post"
image: "./cover-image.jpg"
tags: ["tag1", "tag2"]
category: "Category Name"
draft: false
---
```

## 🛠️ Available Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm preview` - Preview production build
- `pnpm new-post` - Create a new blog post
- `pnpm format` - Format code with Biome
- `pnpm lint` - Lint code with Biome
- `pnpm check` - Run Astro checks

## 📁 Project Structure

```
my_blog/
├── src/
│   ├── components/          # Reusable components
│   ├── content/            # Blog posts and configuration
│   ├── layouts/            # Page layouts
│   ├── pages/              # Route definitions
│   ├── styles/             # Global styles
│   ├── utils/              # Utility functions
│   └── config.ts           # Site configuration
├── public/                 # Static assets
├── scripts/                # Build and utility scripts
└── package.json           # Project dependencies
```

## ⚙️ Configuration

The blog is highly customizable through `src/config.ts`. Key configuration options include:

- **Site Information**: Title, subtitle, language
- **Theme Colors**: Customizable hue and color schemes
- **Navigation**: Menu items and external links
- **Social Media**: Profile links and contact information
- **Features**: Enable/disable various blog features

## 🎨 Customization

### Theme Colors

Adjust the theme color in `src/config.ts`:

```typescript
themeColor: {
  hue: 250, // 0-360, e.g., red: 0, teal: 200, cyan: 250
  fixed: false, // Allow visitors to change theme
}
```

### Adding Custom Components

Create new components in `src/components/` and import them in your markdown files or layouts.

## 🚀 Deployment

This blog is automatically deployed to GitHub Pages. Any push to the main branch triggers a new deployment.

### Manual Deployment

1. **Build the project**
   ```bash
   pnpm build
   ```

2. **Deploy to your preferred hosting service**
   The built files will be in the `dist/` directory.

## 🤝 Contributing

While this is a personal blog, I welcome suggestions and improvements! Feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built upon the [Fuwari](https://github.com/saicaca/fuwari) theme
- Powered by [Astro](https://astro.build)
- Search functionality by [Pagefind](https://pagefind.app)
- Styled with [Tailwind CSS](https://tailwindcss.com)

## 📧 Contact

Feel free to reach out if you have any questions or just want to connect!

- GitHub: [@donald4yls](https://github.com/donald4yls)
- Website: [donald4yls.github.io](https://donald4yls.github.io)

---

*This blog is a continuous work in progress, just like the journey it documents. Thanks for visiting! 🚀*