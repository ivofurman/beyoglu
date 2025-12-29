# İstiklal Caddesi - Interactive Time Map

An interactive visualization of İstiklal Street and its surroundings in Istanbul, showing how the area changes throughout the day using Leaflet maps.

## Features

- **Interactive Leaflet Map**: Real OpenStreetMap tiles with full pan and zoom
- **Sidebar with Location Cards**: Click cards to fly to locations on the map
- **Time Slider**: Switch between three time periods:
  - **Sabah (Morning)**: Yellow markers - quieter atmosphere with preparation activities
  - **Öğlen (Noon)**: Orange markers - moderate crowds with tourists and locals
  - **Akşam (Night)**: Blue markers - peak activity with nightlife and entertainment
- **Interactive Popups**: Click markers to see detailed information about each location
- **13 Locations**: Key points of interest including:
  - Taksim Meydanı (Taksim Square)
  - Atatürk Kültür Merkezi
  - Çiçek Pasajı
  - İstiklal Caddesi (main street)
  - Galatasaray Lisesi
  - Nevizade Sokak
  - St. Antuan Kilisesi
  - Galata Kulesi
  - And more...

## How to Use

1. **Open the Map**: Simply open `index.html` in any modern web browser
   - **Requires internet connection** for Leaflet library and map tiles
   - Data is embedded in HTML, so no web server needed
2. **Change Time Period**: Use the slider in the sidebar to switch between morning, noon, and night
3. **View Location Details**: 
   - Click on location cards in the sidebar to fly to that location
   - Click on markers to see detailed popups
4. **Navigate the Map**:
   - Drag to pan
   - Scroll/pinch to zoom
   - Standard Leaflet map controls

**Note:** If the map doesn't load, check your internet connection. The Leaflet library and map tiles require internet access.

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- **Internet connection** (for Leaflet library and OpenStreetMap tiles)

## Files

- `index.html` - Main interactive map interface with Leaflet
- `data.json` - Location data extracted from Excel spreadsheets
- `İstiklal Caddesi Sabah.xlsx` - Morning data
- `İstiklal Caddesi Öğlen.xlsx` - Noon data  
- `İstiklal Caddesi Akşam.xlsx` - Night data

## Technical Details

- Built with [Leaflet](https://leafletjs.com/) 1.9.4
- OpenStreetMap tile layer
- Responsive design with sidebar layout
- Color-coded markers by time period
- Data sourced from field documentation and sound walks

## Design

The map interface is inspired by the [Istanbul Atlas](https://github.com/ivofurman/istanbul_atlas) project, featuring:
- Dark theme with elegant color scheme
- Sidebar with clickable location cards
- Smooth transitions when flying to locations
- Custom styled popups and markers

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

**Note**: Internet connection required for Leaflet library and map tiles.
