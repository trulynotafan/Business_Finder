# Business Lead Finder

A web tool that helps freelancers and agencies find potential clients by identifying businesses without websites but with contact information using OpenStreetMap data.

## Features

- Search businesses within 200km radius
- Multi-select business categories  
- Progressive radius search (25km, 50km, 100km, 200km)
- Filter by contact method (email/phone)
- Real-time search statistics
- Interactive map integration
- Location autocomplete
- Mobile-responsive design

## Tech Stack

- HTML5, CSS3, JavaScript
- Leaflet for mapping
- OpenStreetMap & Overpass API
- Nominatim for geocoding

## Installation

```bash
git clone https://github.com/trulynotafan/Business_Finder.git
cd business-finder
npm install
node server.js
```

## Usage

1. Enter a location in the search box
2. Select business categories
3. Choose search radius (1-200km)
4. Select contact filters (email/phone)
5. Click "Search" to find leads

## How It Works

Uses chunked search approach:
1. Breaks large radius searches into smaller chunks
2. Queries each business category separately
3. Filters out businesses with existing websites
4. Identifies businesses with contact information
5. Removes duplicates and presents results

## Important Notes

- Respect API rate limits
- Use responsibly and ethically
- Consider privacy laws when collecting contact info
- Follow proper business outreach etiquette

## License

MIT License

---

**Author:** Afaan
