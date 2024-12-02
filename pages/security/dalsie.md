<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 columns */
  gap: 20px; /* spacing between cards */
  padding: 20px; /* padding around the grid */
}
.card {
  background-color: #222; /* dark background for the card */
  color: #fff; /* white text */
  border-radius: 10px; /* rounded corners */
  padding: 15px; /* padding inside the card */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); /* subtle shadow */
  text-align: center; /* center-align content */
  display: flex;
  flex-direction: column;
  justify-content: flex-start; /* Align content to the top */
  align-items: center; /* Center horizontally */
  min-height: 200px; /* Ensure cards have a consistent base height */
}
.card img {
  width: 100%; /* full width of the card */
  border-radius: 10px 10px 0 0; /* round top corners */
  height: auto; /* Allow dynamic height for the image */
  max-height: 120px; /* Limit the maximum height of the image */
  object-fit: cover; /* Ensure the image fits well */
  margin-bottom: 10px; /* Add a small space between image and text */
}
.card p {
  font-size: 0.9em; /* Adjusted font size */
  margin: 0; /* Remove excessive margins */
  text-align: center; /* Center-align the text */
  line-height: 1.4; /* Slightly increase line spacing for readability */
}
</style>

# Ďaľšie užitočné rady

<div class="grid-container">
  <div class="card">
    <img src="/more/device.png" alt="Image 1">
    <p>Zamykajte zariadenia keď odnich odchádzate</p>
  </div>
  <div class="card">
    <img src="/more/omg-cable.avif" alt="Image 2">
    <p>Pozor čo si pripájate do zariadenia</p>
  </div>
  <div class="card">
    <img src="/more/screen-shield.png" alt="Image 3">
    <p>Screen shieldy sú tiež užitočné, ja si čítam v mhd čo si ľudia píšu</p>
  </div>
  <div class="card">
    <img src="/more/camera.png" alt="Image 4">
    <p>Rovnako ak je za vami kamera</p>
  </div>
  <div class="card">
    <img src="/more/usb-condom.avif" alt="Image 6">
    <p>Na verejných zásuvkách môžete využiť USB kondom</p>
  </div>
  <div class="card">
    <img src="/more/barcode.jpg" alt="Image 5">
    <p>Pozor na QR/barocode kt. skenujete</p>
  </div>
</div>
