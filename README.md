# React + TypeScript + Vite Project

This project is built with React, TypeScript, and Vite, and is configured for deployment to GitHub Pages.

## Getting Started

1. Clone this repository
2. Install dependencies: `npm install`
3. Start development server: `npm run dev`
4. Build for production: `npm run build`

## Deployment

This project is configured to automatically deploy to GitHub Pages when you push to the main branch.

### Manual Setup Steps:

1. **Create a new repository on GitHub**
2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Source", select "GitHub Actions"
3. **Push your code**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

The GitHub Action will automatically build and deploy your site to `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## Technologies Used

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Lucide React (for icons)