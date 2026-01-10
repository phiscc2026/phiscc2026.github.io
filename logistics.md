---
layout: page
title: Logistics
feature_text: |
  # Workshop Logistics
use_amap: true
use_map: true
---

## Venue

The workshop will be held at the Kavli Institute for Astronomy and Astrophysics (KIAA), which locates in the campus of Peking University, No. 5 Yiheyuan Road, Haidian District, Beijing 100871, China. The campus is famous for its rich historical heritage and beautiful scenery, especially during the autumn season. 

<!-- <iframe src="https://www.google.com/maps/d/embed?mid=1SfXoK6FT8IUv4xy_kKtKixPyWWjwf2w&ehbc=2E312F&noprof=1" width="720" height="480"></iframe> -->

<!-- <div id="map" style="width:100%; height:500px;"></div>

<script>
window.initMap = function () {

  const map = new AMap.Map('map', {
    zoom: 13,
    center: [116.31115, 39.999266],  // KIAA
    lang: 'en'
  });

  const marker = new AMap.Marker({
  position: [116.31115, 39.999266],
  title: "KIAA",
  label: {
    content: "KIAA",
    direction: "top"
  }
});

  map.add(marker);
};
</script> -->

<div id="map" style="width:100%; height:500px;"></div>

<script>
const map = L.map('map').setView([39.90923, 116.397428], 13);

L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
  maxZoom: 19,
  attribution: '© OpenStreetMap'
}).addTo(map);

L.marker([39.90923, 116.397428])
  .addTo(map)
  .bindPopup('Tiananmen Square');
</script>


## Accommodation
The closest hotel to the venue is <a href="https://en.thelakeviewbeijing.cn"> The Lakeview Hotel Beijing (北京北大博雅国际酒店)</a>, which is about a 5-minute walk from KIAA. (reservation info TBD)

<!-- ## Conference dinner
TBD -->


## Travel to Beijing

Beijing is a major international hub, served by Beijing Capital International Airport (**PEK**) and Beijing Daxing International Airport (**PKX**). Transports between the airports and Peking University are offered by subway (PEK:¥30, PKX:¥40) and taxi (PEK:~¥120, PKX:~¥230). Typically 1.5 hours are needed to reach Peking University from either airport, depending on traffic conditions.

## Transport within Beijing

Subway is the most convenient way to travel within Beijing. The closest subway station to the campus is Peking University East Gate (Line 4). From there, it is about a 10-minute walk to KIAA. Taxis and ride-hailing services (e.g., Didi) are also widely available. Shared bikes are another popular option for short-distance travel.

<!-- ## Useful APPs for Travelling in China
TBD -->

For any additional information please contact the Local Organizing Committee at <a href="mailto:phiscc2026@126.com">phiscc2026@126.com</a>