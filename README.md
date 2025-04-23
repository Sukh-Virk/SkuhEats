# SukhEATS

Welcome to **SukhEATS**, an interactive web application built with **HTML**, **CSS**, and **JavaScript** that leverages **OpenStreetMap**, **Leaflet**, **OpenCage Geocoding**, and the **Overpass API** to help users discover restaurants and cafés across British Columbia, Canada.

---

## Overview

- **Search & Explore**: Enter a postal code or city name to find nearby restaurants, cafés, and fast-food spots.
- **Advanced Filtering**: Refine results by maximum distance, minimum rating, and price level.
- **Random & Fancy Picks**: Get a spontaneous suggestion or opt for a “Feeling Fancy” recommendation, complete with vibe tags.
- **Interactive Map**: View and interact with map markers, see detailed popups, and pan/zoom to explore.

---

## Motivation & Passion for Data

As someone who’s recently fallen in love with **data science**, I believe that **data is everywhere**—even in the simple act of choosing what to eat. This project was my playground to:

- **Fetch**: Retrieve geospatial and venue data via APIs.
- **Process**: Filter, sort, and transform raw JSON into meaningful information.
- **Visualize**: Present data through an intuitive map interface and dynamic controls.

Building SukhEATS has deepened my appreciation for how data drives decisions, uncovers patterns, and enhances user experiences. It’s my first step into the fascinating world of data science!

---

## Features

1. **Geocoding & Autocomplete**  
   • Nominatim & OpenCage for fuzzy address lookup and formatted results.
2. **Restaurant Discovery**  
   • Overpass API queries for `amenity=restaurant`, `fast_food`, and `cafe` within a radius.
3. **Advanced Filters**  
   • Range sliders for distance and rating, checkboxes for price tiers.
4. **Randomized Suggestions**  
   • "Get Random Pick" & "Feeling Fancy" modes with vibe tags (e.g., Romantic, Trendy).
5. **Responsive Design**  
   • Mobile-friendly layout, adaptable across screen sizes.

---

## Tech Stack

- **HTML5** & **CSS3** (Flexbox, responsive media queries)
- **JavaScript (ES6+)**
- **[Leaflet](https://leafletjs.com/)** for map rendering
- **[OpenStreetMap](https://www.openstreetmap.org/)** tiles
- **[OpenCage Geocoding API](https://opencagedata.com/)** for geocoding
- **Overpass API** for querying venue data

---

## Installation & Usage

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/sukheats.git
   cd sukheats
   ```

2. **Obtain API Keys**  
   - Sign up for an [OpenCage](https://opencagedata.com/) account and get your API key.  
   - Replace the placeholder in `index.html`:
     ```js
     const OC_KEY = "YOUR_OPENCAGE_API_KEY_HERE";
     ```

3. **Open in Browser**  
   - Simply open `index.html` in your favorite browser.

4. **Explore**  
   - Enter any BC postal code (e.g., `V6B 1H1`) or city name (e.g., `Victoria`) and click **Find Restaurants**.

---

## Future Improvements

- Integrate real user ratings & reviews from external APIs (e.g., Yelp).
- Add caching & rate-limit handling for Overpass and OpenCage requests.
- Expand to other provinces & countries.
- Implement server-side support for secure API key storage.

---

## About the Author

- **Sukhman Virk**

## Link To Website
https://sukheats.netlify.app/


![image](https://github.com/user-attachments/assets/f0cd2a85-2696-41cc-934b-fc923ffd8755)

