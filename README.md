# Elvic Kongolo - Personal Website

A professional portfolio and blog website for Elvic Kongolo, operator turned investor.

## 🌐 Live Site

- **Production**: https://www.helenmin.com
- **Local Development**: http://localhost:8000

## 📁 Project Structure

```
www.helenmin.com/
├── assets/
│   ├── css/
│   │   └── header-improvements.css    # Custom header styling
│   └── images/
│       ├── elvic-kongolo-logo.png     # Site logo (800x115px)
│       ├── elvic-profile.jpg          # Profile image (640x800px, optimized)
│       └── *.png, *.jpg               # Other images
├── docs/
│   ├── Elvic Artikler/                # Article resources
│   ├── Elvic docs/                    # Documentation
│   └── Elvic Kongolo's Latest News & Updates.md
├── archive/
│   ├── blog@author=*.html             # Archived blog files
│   ├── blog?author=*.html             # Archived blog files
│   └── *.rss                          # RSS feeds
├── blog/                              # Blog post pages
├── index.html                         # Home page
├── about.html                         # News/Blog listing page
├── projects.html                      # Projects showcase
├── contact.html                       # Contact page
├── cart.html                          # Shopping cart
└── robots.txt                         # SEO configuration

```

## 🚀 Quick Start

### Prerequisites
- Python 3.x (for local development server)
- Modern web browser

### Running Locally

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd www.helenmin.com
   ```

2. **Start the development server**
   ```bash
   python3 -m http.server 8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

## 📄 Pages

| Page | File | Description |
|------|------|-------------|
| **Home** | `index.html` | Landing page with introduction |
| **News** | `about.html` | Blog articles and updates (11 articles) |
| **Projects** | `projects.html` | Portfolio of projects and investments |
| **Contact** | `contact.html` | Contact information and form |
| **Cart** | `cart.html` | Shopping cart functionality |

## 🎨 Design & Styling

### Custom CSS
- **File**: `assets/css/header-improvements.css`
- **Features**:
  - Compact header with optimized spacing
  - Responsive navigation (32px gap between items)
  - Active page indicator (black background, white text)
  - Mobile-friendly breakpoints

### Fonts
- **Work Sans**: Weights 100, 400, 700 (from Google Fonts)
- **Besley**: Weights 400, 700 (from Google Fonts)

### Color Scheme
- Active navigation: Black background (#000), white text
- Header border: Subtle bottom border for definition

## 🔧 Technical Details

- **Template**: Squarespace 7.1 (Template ID: 5c5a519771c10ba3470d8101)
- **Static Site**: Exported from Squarespace
- **No Backend**: Pure HTML/CSS/JS static site
- **External Assets**: Loaded from Squarespace CDN

## 📝 Content Management

### Adding Blog Articles
Blog articles are located in the `blog/` directory and listed on `about.html`.

### Updating Images
1. Place images in `assets/images/`
2. Reference using: `assets/images/filename.ext`
3. Optimize images before uploading (recommended)

### Navigation Structure
All pages share the same navigation:
- Home → `index.html`
- News → `about.html`
- Projects → `projects.html`
- Contact → `contact.html`

## 🗂️ Archive

Old and unused files are stored in the `archive/` directory:
- Legacy blog HTML files
- RSS feeds
- Deprecated scripts

## 📚 Documentation

Additional documentation and resources are in the `docs/` directory:
- Article content and drafts
- Project documentation
- News updates markdown file

## 🤝 Contributing

This is a personal website. For suggestions or issues, please contact Elvic Kongolo directly.

## 📧 Contact

- **LinkedIn**: [linkedin.com/in/helenmin](https://www.linkedin.com/in/helenmin/)
- **X (Twitter)**: [@helen_min](https://x.com/helen_min)

## 📜 License

© 2024 Elvic Kongolo. All rights reserved.

