# 2025 Awards Nomination Explorer

An interactive web application to explore and manage movie and TV awards nominations for 2025. This dashboard allows you to browse through various categories, add new nominees, remove entries, and get suggestions for alternatives.

## Features

- 📊 **Dashboard Overview**: Visual chart summarizing nominations across major categories
- 🎬 **27 Award Categories**: Including Hollywood movies, Indian cinema, series, and technical awards
- ➕ **Interactive Management**: Add, remove, and suggest alternatives for nominees
- 🎨 **Modern UI**: Clean, responsive design with Tailwind CSS
- 📱 **Mobile Friendly**: Works seamlessly on desktop and mobile devices

## Live Demo

Once deployed, your site will be available at:
```
https://[your-username].github.io/awards-nomination-explorer/
```

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `awards-nomination-explorer`
4. Choose "Public" visibility
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click "uploading an existing file"
2. Drag and drop the `index.html` file from the project folder
3. Commit the changes

**Option B: Using Git Command Line**
```bash
# Navigate to your project folder
cd c:\Users\VIDIT\Downloads\awards-nomination-explorer

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Awards Nomination Explorer"

# Add your GitHub repository as remote (replace YOUR-USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/awards-nomination-explorer.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top navigation)
3. Click "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select `main` and `/ (root)`
6. Click "Save"

Your site will be live in a few minutes at:
```
https://[your-username].github.io/awards-nomination-explorer/
```

## Project Structure

```
awards-nomination-explorer/
├── index.html          # Main application file
├── README.md          # This file
└── .gitignore         # Git ignore file
```

## Technologies Used

- **HTML5**: Structure and content
- **Tailwind CSS**: Styling and responsive design
- **Chart.js**: Data visualization
- **Vanilla JavaScript**: Interactivity and data management

## Categories Included

### Movies
- Best Hollywood Movies
- Best Indian Movies
- Best Comic Book/Superhero Movies
- Best Sci-Fi Movies
- Best Mass Masala Movies
- Best Horror Movies
- Best Animated Movies

### Series
- Best Comic Book/Superhero Series
- Best Animated Series
- Best International Series
- Best Indian Series

### Technical & Craft
- Best Adapted Content
- Best Cinematography
- Best Visual Effects (VFX)
- Best Sound Design
- Best Theatrical Experience

### Talent
- Best Director (Hollywood)
- Best Indian Director
- Best International Actor/Actress
- Best Indian Actor/Actress

### Special Categories
- Most Anticipated (Hollywood, Indian, Series)
- Wasted Potential
- Worst Projects

## Local Development

To run locally:
1. Simply open `index.html` in your web browser
2. No build process or dependencies required!

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

## Contributing

Feel free to fork this project and customize it for your own awards lists!

---

**Note**: All external dependencies (Tailwind CSS, Chart.js, Google Fonts) are loaded via CDN, so an internet connection is required for full functionality.
