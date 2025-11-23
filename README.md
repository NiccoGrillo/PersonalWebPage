# Niccolò Grillo - Personal Website

A modern, responsive personal website showcasing my background as an ML Researcher/Engineer.

## 🚀 Live Site

Once deployed to GitHub Pages, your site will be available at: `https://yourusername.github.io/personal_web_page`

## 📋 Setup Instructions for GitHub Pages

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `personal_web_page` (or any name you prefer)
3. Make it public (required for free GitHub Pages)
4. Don't initialize with README since we already have files

### 2. Push Your Files to GitHub

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Personal website"

# Add remote repository (replace 'yourusername' with your GitHub username)
git remote add origin https://github.com/yourusername/personal_web_page.git

# Push to GitHub
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

Your site will be live in a few minutes at `https://yourusername.github.io/personal_web_page`

## 🛠️ Customization

### Updating Content

- **Personal Info**: Edit the contact links and bio in `index.html`
- **Experience**: Add or modify job experiences in the experience section
- **Projects**: Update the projects section with your latest work
- **Skills**: Add new technologies to the skills section

### Styling

- **Colors**: Modify CSS variables in `styles.css` (`:root` section)
- **Fonts**: Change the font imports in the `<head>` of `index.html`
- **Layout**: Adjust grid layouts and spacing in `styles.css`

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Update the navigation if needed

## 📁 File Structure

```
personal_web_page/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── Niccolò_Grillo_CV.pdf  # Your CV (optional to include)
```

## 🎨 Features

- **Responsive Design**: Works on all devices
- **Modern UI**: Clean, professional styling
- **Smooth Animations**: Subtle hover and scroll effects
- **Fast Loading**: Optimized performance
- **SEO Friendly**: Proper meta tags and structure

## 🔧 Technologies Used

- **HTML5**: Semantic structure
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Interactive animations and effects
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

Feel free to fork this repository and adapt it for your own use!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).