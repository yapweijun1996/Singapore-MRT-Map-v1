# Singapore MRT Map Demo

A simple, interactive demo showing Singapore MRT stations on a Leaflet map, with modern markers, clustering, and rich popups. Perfect for learning how to build and customize map-based front-ends.

---

## 🚀 Features

* **Markers & Clustering**: Displays stations as single points or clusters when zoomed out.
* **Custom Popups**: Show station image, description, facilities, and a “View Details” button.
* **Toast Notifications**: Feedback for tile load errors and button interactions.
* **Single-file Demo**: All HTML, CSS, and JS live in `index.html` for easy study.

---

## 🧰 Dependencies

This demo uses the following libraries loaded via CDN:

* **Leaflet** for interactive maps:

  ```html
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
  <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
  ```
* **Leaflet.markercluster** for marker clustering:

  ```html
  <link rel="stylesheet" href="https://unpkg.com/leaflet.markercluster@1.5.3/dist/MarkerCluster.css" />
  <script src="https://unpkg.com/leaflet.markercluster@1.5.3/dist/leaflet.markercluster.js"></script>
  ```

---

## 🔧 Customization Guide

* **Station Data**: Edit the `SG_MRT_STATIONS_SAMPLE` array in the `<script>` of `index.html`.
* **Marker Styles**: Tweak `.modern-single` and `.modern-cluster` in the `<style>` block.
* **Popup HTML**: Modify the template under `addMarkers()`.
* **Messages**: Update toast text in `CONFIG.messages.en`.

---

## Demo 

---

## 📄 License

This project is released under the MIT License. Feel free to use, modify, and share!
