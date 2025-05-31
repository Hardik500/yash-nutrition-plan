# Yashaswini's Nutritional Blueprint Explorer

An interactive web application that provides personalized South & North Indian dietary guidance based on lab results and nutritional analysis.

## Features

- **Health Snapshot**: Visual overview of key lab indicators
- **Lab Insights**: Detailed breakdown of lab values with interactive tables
- **Dietary Strategy**: Core principles and nutrient optimization strategies
- **Meal Plans**: Comprehensive South and North Indian meal planning
- **Lifestyle Guidance**: Complementary wellness strategies

## Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Chart.js for data visualization
- Vanilla JavaScript for interactivity

## Deployment

This application is automatically deployed to GitHub Pages using GitHub Actions.

### Setup Instructions

1. **Create a GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Nutritional Blueprint Explorer"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/yash-nutrition-plan.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to Settings → Pages
   - Under "Source", select "GitHub Actions"
   - The workflow will automatically deploy your site

3. **Access Your Deployed Site**
   - After the workflow completes, your site will be available at:
   - `https://YOUR_USERNAME.github.io/yash-nutrition-plan/`

### Manual Deployment

If you prefer to deploy manually:

```bash
# Add all files
git add .

# Commit changes
git commit -m "Update nutritional blueprint"

# Push to main branch (triggers automatic deployment)
git push origin main
```

## File Structure

```
.
├── index.html              # Main application file
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions workflow
└── README.md              # This file
```

## Features Overview

### Interactive Components
- **Charts**: Visual representation of lab values vs. reference ranges
- **Accordions**: Expandable sections for organized content navigation
- **Tables**: Sortable and interactive data presentation
- **Navigation**: Sticky navigation bar with smooth section switching

### Content Sections
1. **Snapshot**: Key health goals and lab indicators
2. **Lab Insights**: Detailed parameter analysis
3. **Diet Strategy**: Nutritional optimization principles
4. **South Indian Plan**: Traditional South Indian meal planning
5. **North Indian Plan**: Traditional North Indian meal planning
6. **Lifestyle**: Holistic wellness recommendations

## Development

To make changes to the application:

1. Edit the `index.html` file
2. Test locally by opening the file in a web browser
3. Commit and push your changes to trigger automatic deployment

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- Progressive enhancement for older browsers

## License

This project is for personal use and educational purposes.

## Disclaimer

This tool is for informational purposes and does not replace professional medical advice. Please consult healthcare providers for medical concerns. 