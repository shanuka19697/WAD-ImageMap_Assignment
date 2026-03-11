# Project Documentation

**Project Title**: HTML Image Map Based Faculty Navigation System  
**Index Number**: 2024t02212 , 2024t02189 , 2024t02213

## Description
This project implements an interactive HTML Image Map for a campus/faculty navigation system. Users can hover over specific markers on the campus map to view the location name and click on them to navigate to more detailed pages about each specific area (e.g., Main Gate, Administrator Building, Hostels, Canteen, Academic Building). The image map is made responsive using the `imageMapResize` script.

## Map Destinations and Paths

The interactive map links to specific pages for each location on the campus. Below is the mapping of each location to its destination path:

| Location (Identifier) | Location Name | Destination Path |
| :--- | :--- | :--- |
| Location 1 | Main Gate | `pages/main_gate.html` |
| Location 2 | Administrator Building | `/pages/admin.html` |
| Location 3 | Girls Hostel | `pages/girls.html` |
| Location 4 | Boys Hostel | `pages/boys.html` |
| Location 5 | Canteen | `pages/canteen.html` |
| Location 6 | Academic Building | `pages/academic.html` |

## Directory Structure and File Paths

### Root Files
- `index.html` : The main map interface containing the image map and navigation links.
- `style.css` : The main stylesheet containing styles for the application shell, location markers, and labels.
- `DOCUMENTATION.md` : This documentation file.

### Pages (`/pages`)
Contains individual HTML pages for various campus locations overviewed in the map.
- `pages/main_gate.html`
- `pages/admin.html`
- `pages/academic.html`
- `pages/boys.html`
- `pages/girls.html`
- `pages/canteen.html`
- `pages/security.html`
- `pages/admin_entr_02.html`
- `pages/admin_main_entra.html`

**Sub-pages (Admin Room Examples)**
- `pages/admin-ground/fg01.html`
- `pages/admin-ground/fg022.html`
- `pages/admin-ground/fg03.html`

**Sub-pages (Canteen Views)**
- `pages/canteen/catwalk.html`
- `pages/canteen/counter.html`
- `pages/canteen/dustbin1.html`
- `pages/canteen/dustbin2.html`
- `pages/canteen/notice-board.html`
- `pages/canteen/printing_shop.html`
- `pages/canteen/sink2.html`
- `pages/canteen/zink1.html`

### Images (`/images`)
Contains images used across the application to provide location contexts.
- `images/map.png` : Main campus map.
- `images/location.png` : Location marker icon used in the UI.
- `images/academic.jpeg`
- `images/admin.jpeg`
- `images/admin_ground.jpeg`
- `images/boys.jpeg`
- `images/canteen.jpeg`
- `images/entrance02.jpeg`
- `images/gate.jpeg`
- `images/girls.jpeg`
- `images/security.jpeg`

**Admin Detail Images**
- `images/admin/F-G01.jpeg`
- `images/admin/F-G02-2.jpeg`
- `images/admin/F-G03.jpeg`

**Canteen Detail Images**
- `images/canteen/cat_walt.jpeg`
- `images/canteen/counter.jpeg`
- `images/canteen/ductbin2.jpeg`
- `images/canteen/dustping1.jpeg`
- `images/canteen/notice_board.jpeg`
- `images/canteen/printing_shop.jpeg`
- `images/canteen/zink1.jpeg`
- `images/canteen/zink2.jpeg`

## Technical Details
- **Core Technologies**: HTML5, CSS3
- **Image Mapping**: Leverages interactive `<map>` and `<area>` tag geometries (`circle`, `poly`, `rect`).
- **Responsiveness**: Utilizes the external `image-map-resizer` package via CDN to scale coordinate metrics reliably on different window sizes or devices.