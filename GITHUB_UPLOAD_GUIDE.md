# Linquity GitHub Upload Guide

This guide will help you upload your Linquity project to GitHub.

## Pre-Upload Checklist

Your project already includes:
- Chrome extension files in `/chrome-extension/`
- GitHub Pages website in `/docs/`
- GitHub workflows in `/.github/workflows/`
- Documentation files (README.md, CONTRIBUTING.md)

## Upload Steps

### 1. Download Project Files
- Click the three dots (⋮) menu in the top-right corner of Replit
- Select "Download as zip"
- Save the zip file to your computer

### 2. Create GitHub Repository
- Go to https://github.com/BrezDuse/Linquity (or your preferred repository name)
- Click "Create repository" with:
  - Repository name: `Linquity`
  - Description: `AI-powered LinkedIn content editor`
  - Visibility: Public
  - Do NOT initialize with README, license, or .gitignore

### 3. Upload Files
After repository creation:
- Extract the zip file on your computer
- On GitHub, click "uploading an existing file"
- Drag and drop the extracted files or select them
- Add commit message: "Initial commit of Linquity project"
- Click "Commit changes"

### 4. Set Up GitHub Pages
- Go to repository Settings
- Scroll to "Pages" section
- Select "main" branch and "/docs" folder
- Click "Save"
- Your site will be published at https://brezduse.github.io/Linquity/

### 5. Create First Release
- Go to "Code" tab → "Releases" section → "Create a new release"
- Tag version: `v1.0.0`
- Target: `main`
- Title: `Initial Release`
- Description: Include key features and installation instructions
- Publish release

## After Upload

- Test GitHub Actions by checking the "Actions" tab
- Verify GitHub Pages is working by visiting your site URL
- Clone the repository to your local machine for future development

## Chrome Extension Testing

- Go to `chrome://extensions/` in Chrome
- Enable "Developer mode"
- Click "Load unpacked"
- Select the `chrome-extension` folder from your local files
- Test the extension on LinkedIn