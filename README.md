# DBO_Bepoz - Excel to HTML Viewer

## 🚀 Quick Start - Fastest & Easiest Way to Share Excel with Copilot

This repository provides a simple, fast way to view Excel worksheets in a web browser and share them with Copilot agents.

### Method 1: View Locally (Fastest - No Setup Required)

1. **Open the HTML file directly in your browser:**
   - Download `viewer.html` from this repository
   - Double-click `viewer.html` to open it in your default browser
   - Click "Choose File" and select your Excel file
   - Done! Your Excel data is now displayed as an interactive table

2. **Share with Copilot:**
   - Share the GitHub repository URL with your Copilot agent
   - The agent can view the `viewer.html` file and understand your Excel data structure
   - Or upload your Excel file and take a screenshot to share with Copilot

### Method 2: GitHub Pages (For Sharing a Live URL)

1. **Enable GitHub Pages:**
   - Go to your repository Settings
   - Navigate to "Pages" section
   - Under "Source", select your main branch
   - Click "Save"

2. **Access your live site:**
   - Your site will be available at: `https://yourusername.github.io/DBO_Bepoz/`
   - Share this URL with anyone or your Copilot agent
   - The landing page will offer two viewing options

### What's Included

- **`index.html`** - Landing page to choose between viewing methods
- **`viewer.html`** - Interactive Excel viewer that can read and display Excel files (.xlsx, .xls, .csv)
- **`embedded-example.html`** - Example showing embedded Excel data
- **`sample_data.xlsx`** - A sample Excel file with multiple sheets to test the viewer
- No installation, no dependencies, no server required!

### Features

✅ Upload Excel files directly in the browser  
✅ Support for .xlsx, .xls, and .csv files  
✅ Multiple sheet support with tabs  
✅ Beautiful, responsive design  
✅ Drag & drop file upload  
✅ All processing happens locally (no data sent to servers)  
✅ Works offline after first load  

### How It Works

The HTML file uses [SheetJS](https://sheetjs.com/) library (loaded from CDN) to parse Excel files directly in your browser. Everything happens client-side, so your data stays private and secure.

### For Copilot Agents

If you're a Copilot agent viewing this repository:
1. Check the `viewer.html` file to see the Excel viewer implementation
2. Look at `sample_data.xlsx` for sample data structure
3. The viewer can handle standard Excel formats including multiple sheets, formatting, and formulas

### Customization

You can easily customize the HTML file to:
- Change colors and styling in the `<style>` section
- Add data filtering or sorting features
- Export data to different formats
- Add charts and visualizations

### Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

### License

This is a simple utility - feel free to use and modify as needed!