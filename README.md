# İstiklal Caddesi - Interactive Time Map

An interactive visualization of İstiklal Street and its surroundings in Istanbul, showing how the area changes throughout the day.

## Features

- **Interactive Map**: SVG-based map visualization with pan and zoom capabilities
- **Time Slider**: Switch between three time periods:
  - **Sabah (Morning)**: Yellow markers - quieter atmosphere with preparation activities
  - **Öğlen (Noon)**: Orange markers - moderate crowds with tourists and locals
  - **Akşam (Night)**: Blue markers - peak activity with nightlife and entertainment
- **Location Details**: Hover over numbered markers to see detailed information about each location
- **13 Locations**: Key points of interest including:
  - Taksim Meydanı (Taksim Square)
  - Atatürk Kültür Merkezi
  - Çiçek Pasajı
  - İstiklal Caddesi (main street)
  - Galatasaray Lisesi
  - Nevizade Sokak
  - St. Antuan Kilisesi
  - And more...

## How to Use

1. **Open the Map**: Simply open `index.html` in any modern web browser
2. **Navigate**: 
   - Click and drag to pan around the map
   - Use mouse wheel to zoom in/out
3. **Change Time Period**: Use the slider at the bottom to switch between morning, noon, and night
4. **View Details**: Hover over any numbered marker to see location information and descriptions

## Files

- `index.html` - Main interactive map interface
- `data.json` - Location data extracted from Excel spreadsheets
- `İstiklal Caddesi Sabah.xlsx` - Morning data
- `İstiklal Caddesi Öğlen.xlsx` - Noon data
- `İstiklal Caddesi Akşam.xlsx` - Night data

## Technical Details

- Pure HTML/CSS/JavaScript implementation (no external dependencies required)
- SVG-based rendering for smooth graphics
- Responsive design that works on desktop and mobile devices
- Data sourced from field documentation and sound walks

## Color Legend

- 🟡 **Yellow (#EBED58)** - Morning (Sabah)
- 🟠 **Orange (#DE9612)** - Noon (Öğlen)
- 🔵 **Blue (#3E87A3)** - Night (Akşam)

## Data Source

The data was collected through:
- Visual documentation
- Sound walks (Ses Yürüyüşü)
- Field observations at different times of day

Each location includes:
- Name and type
- Geographic coordinates (latitude/longitude)
- Time-specific descriptions of atmosphere and activity
- Asset classification

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

No internet connection required - all resources are embedded in the HTML file.
