# Faith n Anime 🌟

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-green)](https://dennisison.github.io/faithnanime/)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.x-red)](https://jekyllrb.com/)
[![Minimal Mistakes](https://img.shields.io/badge/Theme-Minimal%20Mistakes-blue)](https://github.com/mmistakes/minimal-mistakes)

A faith-based anime review website providing thoughtful analysis of anime series and movies from a Christian perspective. Helping families make informed viewing decisions while exploring deeper themes and values in anime content.

## 🌐 Live Site

Visit the live site: **[https://dennisison.github.io/faithnanime/](https://dennisison.github.io/faithnanime/)**

## 📖 About

Faith & Anime offers:

- **Comprehensive Reviews** - In-depth analysis of anime series and movies
- **Content Considerations** - Family-friendly ratings and content warnings
- **Faith Perspective** - Exploring themes, values, and spiritual elements
- **Age Recommendations** - Helping parents find appropriate content
- **Character Analysis** - Discussion of moral lessons and character development

## 🛠️ Built With

- **[Jekyll](https://jekyllrb.com/)** - Static site generator
- **[Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)** - Jekyll theme
- **[GitHub Pages](https://pages.github.com/)** - Hosting platform
- **Markdown** - Content creation
- **SCSS/CSS** - Custom styling

## 🚀 Features

- ✅ Responsive design
- ✅ SEO optimized
- ✅ Fast loading times
- ✅ Mobile-friendly navigation
- ✅ Category and tag organization
- ✅ Social media integration
- ✅ Search functionality
- ✅ Comment system ready

## 📁 Site Structure

```
faithnanime/
├── _config.yml           # Site configuration
├── _data/
│   └── navigation.yml    # Site navigation menu
├── _posts/              # Blog posts (reviews)
├── _pages/              # Static pages (About, Contact, etc.)
├── _layouts/            # Custom page layouts
├── assets/
│   ├── css/
│   │   └── main.scss    # Custom styles
│   └── images/          # Site images and headers
├── index.html           # Homepage
└── README.md           # This file
```

## 🎯 Content Categories

- **Anime Series** - TV shows and long-form content
- **Anime Movies** - Feature films and OVAs
- **Family Friendly** - Content appropriate for all ages
- **Teen & Up** - Content with mature themes
- **Content Warnings** - Detailed breakdown of potentially concerning content

## 📝 Writing Reviews

Each review includes:

1. **Plot Summary** - Spoiler-free overview
2. **Faith & Values Analysis** - Themes, morals, and spiritual elements
3. **Content Considerations** - Violence, language, sexual content, etc.
4. **Age Recommendations** - Suggested viewing ages
5. **Final Verdict** - Overall rating and recommendation

## 🔧 Local Development

To run this site locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/dennisison/faithnanime.git
   cd faithnanime
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run Jekyll**
   ```bash
   bundle exec jekyll serve
   ```

4. **View locally**
   Open `http://localhost:4000/faithnanime/` in your browser

## 📋 Adding New Reviews

1. Create a new file in `_posts/` with the format: `YYYY-MM-DD-anime-title.md`
2. Use this front matter template:

```yaml
---
title: "Anime Title: Season X Review"
date: YYYY-MM-DDTHH:MM:SS-04:00
categories:
  - anime-reviews
tags:
  - genre1
  - genre2
  - age-rating
header:
  image: /assets/images/anime-header.jpg
  teaser: /assets/images/anime-teaser.jpg
excerpt: "Brief description and recommendation summary"
---
```

3. Write your review content in Markdown
4. Commit and push to GitHub
5. GitHub Pages will automatically build and deploy

## 🎨 Customization

### Colors & Styling
Edit `assets/css/main.scss` to customize:
- Color scheme
- Typography
- Layout spacing
- Header image sizing

### Navigation
Edit `_data/navigation.yml` to modify site menu

### Site Configuration
Edit `_config.yml` for:
- Site title and description
- Author information
- Social media links
- Plugin settings

## 🤝 Contributing

Interested in contributing? Here's how you can help:

1. **Suggest Anime** - Recommend series for review
2. **Report Issues** - Found a bug or broken link?
3. **Content Ideas** - Suggest new features or content types
4. **Share** - Help spread the word about the site

### Guidelines for Contributions
- Keep content family-friendly and faith-focused
- Provide balanced, honest reviews
- Include appropriate content warnings
- Follow the established format for consistency

## 📧 Contact

- **Email**: [your-email@example.com](mailto:your-email@example.com)
- **Website**: [https://dennisison.github.io/faithnanime/](https://dennisison.github.io/faithnanime/)
- **GitHub**: [@dennisison](https://github.com/dennisison)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **[Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)** by Michael Rose
- **[Jekyll](https://jekyllrb.com/)** static site generator
- **[GitHub Pages](https://pages.github.com/)** for free hosting
- The anime community for inspiration and discussion

---

**Faith & Anime** - Discovering deeper meaning in animated storytelling ✨

*Last updated: January 2025*
