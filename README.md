# MattiaCode Chart.js Dashboard

An interactive dashboard built with Chart.js and Tailwind CSS showcasing various chart types for business data visualization.

## 🎯 Features

- **Responsive Design**: Optimized layout for desktop and mobile devices
- **5 Chart Types**: Line, Doughnut, Bar, Polar Area, and Radar charts
- **Smooth Animations**: Loading animations for cards and smooth transitions
- **Modern Styling**: Clean design with gradient backgrounds and card shadows
- **Italian Localization**: Interface and data localized in Italian

## 📊 Chart Types

### 1. Line Chart - Monthly Sales
Shows sales trends from January to September featuring:
- Smooth curved lines with area fill
- Interactive hover effects
- Custom point styling
- Formatted currency values

### 2. Doughnut Chart - Product Categories
Displays product category distribution with:
- 5 product categories (Electronics, Clothing, Home, Books, Sports)
- Custom color palette
- Bottom legend with dot indicators
- 60% cutout for modern look

### 3. Bar Chart - Weekly Performance
Compares sales and visits data with:
- Dual dataset visualization
- Rounded corner bars
- Custom legend indicators
- Weekly data (Monday to Sunday)

### 4. Polar Area Chart - Sales Regions
Visualizes regional sales distribution across:
- 5 Italian regions (Lombardia, Lazio, Campania, Sicilia, Veneto)
- Semi-transparent fills with colored borders
- Radial grid styling

### 5. Radar Chart - Performance Metrics
Multi-dimensional performance analysis showing:
- 6 key metrics (Sales, Marketing, Customers, Products, Support, Innovation)
- Comparison between Q3 performance and targets
- Dual dataset overlay
- 0-100 scale with 20-point intervals

## 🛠️ Technologies Used

- **Chart.js 3.9.1**: Modern charting library
- **Tailwind CSS**: Utility-first CSS framework
- **HTML5**: Semantic markup
- **JavaScript ES6**: Modern JavaScript features

## 🎨 Design System

### Color Palette
```css
Primary: #3b82f6 (Blue)
Secondary: #8b5cf6 (Purple) 
Accent: #06b6d4 (Cyan)
Success: #10b981 (Green)
Warning: #f59e0b (Amber)
Danger: #ef4444 (Red)
```

### Layout
- **Grid System**: CSS Grid with responsive breakpoints
- **Card Components**: White backgrounds with subtle shadows
- **Spacing**: Consistent 8px grid system
- **Typography**: Clean, modern font hierarchy

## 🚀 Quick Start

1. **Clone or download** the HTML file
2. **Open** `index.html` in your browser
3. **No build process required** - all dependencies loaded via CDN

## 📱 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 Customization

### Adding New Charts
1. Add a new canvas element in the HTML
2. Create chart configuration in the JavaScript section
3. Use the predefined `chartColors` object for consistency

### Modifying Data
Update the `data` arrays in each chart configuration to reflect your business metrics.

### Styling Changes
Modify the Tailwind configuration object or add custom CSS classes as needed.

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Created by MattiaCode** - Showcasing modern data visualization techniques