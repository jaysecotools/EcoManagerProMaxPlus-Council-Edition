# 🌿 EcoManager Pro

**EcoManager Pro** is a comprehensive, browser-based ecosystem management system designed for local councils and environmental agencies. It provides a suite of tools to manage restoration projects, conduct ecological assessments, track species, schedule maintenance, and visualize key environmental data—all in one place.

Built as a single HTML/CSS/JS application, it requires no backend server and stores all data locally in the browser's `localStorage`, making it ideal for demonstrations, field trials, or small-team deployments.

![EcoManager Pro Dashboard](https://via.placeholder.com/800x400?text=EcoManager+Pro+Dashboard)

## ✨ Key Features

### Core Management
- **Project Management** – Create, edit, and track restoration projects with budgets, timelines, and geolocation.
- **Ecological Assessments** – Conduct standardized ecosystem health assessments with automatic health scoring (0–100).
- **Species Registry** – Catalog native and introduced species, filter by project, and track status.
- **Maintenance Scheduling** – Schedule, prioritize, and complete maintenance tasks with calendar and list views.

### Interactive & Visual
- **Interactive Maps** – Plot project locations using Leaflet maps; import GPX/KML boundaries.
- **Weather Integration** – Live or demo weather data via WeatherAPI.com, including forecasts and environmental alerts.
- **Rich Analytics** – Health trends, species distribution, maintenance activity charts, and monthly activity overviews.
- **Dashboard** – Key metrics, quick actions, recent activities, and upcoming maintenance.

### Data & Administration
- **Role-Based Access** – Viewer, Field Staff, Project Manager, and Admin roles with tailored permissions.
- **Data Import/Export** – Export data as JSON, PDF reports, or Excel spreadsheets; import JSON backups.
- **Document Management** – Upload and associate files (permits, photos, reports) with projects.
- **Audit Logging** – Track all create, update, delete actions per user.
- **Custom Forms** – Build custom monitoring forms per project via the built-in form builder.

### User Experience
- **Responsive Design** – Works on desktop, tablet, and mobile devices.
- **User Onboarding** – Guided tour for first-time users.
- **Dark Mode Support** – Respects system color scheme preferences.
- **Accessibility** – Keyboard navigation, high-contrast support, reduced motion options.

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- (Optional) A free API key from [WeatherAPI.com](https://www.weatherapi.com/) for live weather data

### Installation

1. **Download the Application**
   - Save the provided HTML file as `index.html` on your local computer or server.

2. **Open the Application**
   - Double-click the `index.html` file to open it in your web browser.
   - No web server is required; the application runs entirely client-side.

3. **Log In**
   - Use the demo password: `council123`
   - Select your role: Viewer, Staff, Manager, or Admin.

4. **Start Managing**
   - Follow the guided tour or explore the sidebar menus.

### Weather API Setup (Optional)

To enable live weather data:
1. Sign up for a free API key at [WeatherAPI.com](https://www.weatherapi.com/).
2. Navigate to the **Weather** section in EcoManager Pro.
3. Enter your API key and click **Save**.
4. Toggle off "Use demo data" to see live conditions.

## 📁 Data Storage

All data is stored in your browser's `localStorage`. This includes:
- Projects, assessments, species, maintenance tasks
- Uploaded document metadata (not the files themselves)
- User preferences and audit logs

**Note:** Clearing browser data will erase all saved information. Use the **Export Data** feature to create backups.

## 🗺️ Map & Location Features

- **Project Location** – Set latitude/longitude manually, use current device location, or click on the map.
- **Boundary Drawing** – Draw project boundaries on the map and calculate area in hectares.
- **GPX/KML Import** – Upload existing boundary files via the map toolbar.
- **Location Preview** – View project locations in a modal map from the Projects table.

## 📊 Ecosystem Health Scoring

Assessments calculate a health score (0–100) based on:
- Vegetation cover (30% weight)
- Weed cover (30% weight)
- Soil stability (20% weight)
- Species richness (20% weight)

Scores map to ratings: Excellent (80+), Good (60–79), Fair (40–59), Poor (20–39), Degraded (<20).

## 🔒 User Roles & Permissions

| Role | Key Permissions |
|------|----------------|
| Viewer | Read-only access to all sections |
| Field Staff | Create assessments, species, and maintenance; complete tasks |
| Project Manager | Create/edit projects, approve workflows, export data |
| Admin | Full system access, including user management |

## 📤 Export & Reporting

- **JSON Export** – Complete backup of all project data.
- **PDF Report** – Professional, multi-page report with executive summary, charts, and data tables.
- **Excel Export** – Spreadsheet format for further analysis.

## 🛠️ Troubleshooting

| Issue | Solution |
|-------|----------|
| Weather data not loading | Check API key or enable demo mode in Weather settings. |
| Map not displaying | Ensure internet connection for Leaflet CDN; check browser console for errors. |
| Data lost after browser clear | Use Export Data regularly; imports can restore backups. |
| Tables not scrolling | Refresh the page; the app automatically fixes layout issues. |

## 💻 Technology Stack

- **HTML5 / CSS3 / JavaScript (ES6)**
- **Bootstrap 5** – UI components and layout
- **Leaflet** – Interactive maps and drawing tools
- **Chart.js** – Data visualizations
- **FullCalendar** – Maintenance calendar view
- **jsPDF & html2canvas** – PDF report generation
- **SheetJS (XLSX)** – Excel export
- **Intro.js** – User onboarding tour

## 🤝 Contributing

This is a demonstration project. For custom modifications:
1. Fork the code or save a local copy.
2. Modify HTML, CSS, or JavaScript as needed.
3. Test thoroughly across browsers.

## 📄 License

This project is provided for **demonstration and educational purposes** only. It is not licensed for commercial redistribution without permission.

## 🙏 Acknowledgements

- Icons by [Bootstrap Icons](https://icons.getbootstrap.com/)
- Maps by [OpenStreetMap](https://www.openstreetmap.org/)
- Weather data by [WeatherAPI.com](https://www.weatherapi.com/)

---

**EcoManager Pro – Empowering Local Ecosystem Management**  
*Version 1.0 | Council Demo Mode*
