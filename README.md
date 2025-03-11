# Alessandro Gentili - Personal Website

A minimalist, dark-mode personal website built for GitHub Pages.

## Overview

This is a static personal website with a dark-mode-first aesthetic, focusing on essential content and frictionless navigation. The site prioritizes simplicity, readability, and performance.

## Features

- **Minimalist Design**: Clean, dark-mode interface with focused content
- **Responsive Layout**: Mobile-first approach that works on all devices
- **Blog Ready**: Simple structure for adding blog posts
- **Fast Loading**: Minimal dependencies for optimal performance

## Structure

- `index.html` - Home page with brief introduction
- `about.html` - Detailed bio, current work, and future goals
- `blog.html` - List of blog posts
- `styles.css` - All styling for the website

## Setup & Deployment

### Local Development

1. Clone this repository:
   ```
   git clone https://github.com/alessandrogentili001/alessandrogentili001.github.io.git
   ```

2. Navigate to the project directory:
   ```
   cd alessandrogentili001.github.io
   ```

3. Open the files in your preferred code editor to make changes

4. View the site locally by opening any HTML file in your browser

### Deployment

This site is designed to be deployed on GitHub Pages:

1. Push changes to your GitHub repository:
   ```
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

2. GitHub Pages will automatically build and deploy your site

## Updating Content

### Adding Blog Posts

To add a new blog post:

1. In `blog.html`, add a new list item to the `post-list` section following this format:
   ```html
   <li class="post-item">
       <p class="post-date">Month DD, YYYY</p>
       <h3><a href="#">Your Blog Post Title</a></h3>
   </li>
   ```

2. For full blog posts, you can create individual HTML files in a `/posts` directory and link to them

### Updating Personal Information

- Edit `index.html` to update your introduction
- Edit `about.html` to update your bio, current work, and future goals

## Customization

- Colors can be modified in the `:root` section of `styles.css`
- Fonts can be changed by updating the Google Fonts import and font-family properties

## License

MIT License