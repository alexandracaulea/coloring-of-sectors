# Coloring of sectors

[![Netlify Status](https://api.netlify.com/api/v1/badges/46cd5d45-2e4a-4af5-a07f-346924aa545d/deploy-status)](https://app.netlify.com/sites/pensive-allen-40f285/deploys)

I've integrated an interactive map to highlight the sectors of Bucharest using Google Maps API.

In order to avoid wasting bandwidth of the user that accesses the page and to avoid making the page load slower, I've decided to lazy load Google Maps with the IntersectionObserver API.

Check out the project here: https://pensive-allen-40f285.netlify.app/

## Installation

1. Clone the repository: `git clone https://github.com/alexandracaulea/coloring-of-sectors`.
2. `cd coloring-of-sectors`.
3. Install project dependencies by running: `npm install`.
4. Get your own API key by following the steps from the [Google Maps Platform](https://developers.google.com/maps/documentation/embed/get-api-key).
5. Create a file and name it `.env` by running: `touch .env` and add the following:

```js
API_KEY=YOUR-API-KEY
API_URL=https://maps.googleapis.com/maps/api/js
```

6. To run: `npm run dev`.
7. To build: `npm run build`.
8. Restrict your API Key by following the steps from [Google Maps Platform](https://developers.google.com/maps/documentation/embed/get-api-key#restrict_key).
