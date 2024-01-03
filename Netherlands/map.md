<div>
  <iframe srcdoc='
    <html>
      <head>
        <title>Hotel Map</title>
        <script async defer src="https://maps.googleapis.com/maps/api/js?key=AIzaSyC-ydg2K3qBfpRIVF88pRgSp89UDex1qk0&callback=initMap"></script>
        <script>
          function initMap() {
            var map = new google.maps.Map(document.getElementById("map"), {
              zoom: 2,
              center: { lat: 0, lng: 0 },
            });
            var marker0 = new google.maps.Marker({
              position: { lat: 52.3730701, lng: 4.8926473 },
              map: map,
            });
            var marker1 = new google.maps.Marker({
              position: { lat: 52.3730701, lng: 4.8926473 },
              map: map,
            });
            var marker2 = new google.maps.Marker({
              position: { lat: 52.3730701, lng: 4.8926473 },
              map: map,
            });
            var marker3 = new google.maps.Marker({
              position: { lat: 52.3730701, lng: 4.8926473 },
              map: map,
            });
            var marker4 = new google.maps.Marker({
              position: { lat: 52.3752182, lng: 4.8839765 },
              map: map,
            });
            var marker5 = new google.maps.Marker({
              position: { lat: 52.3580757, lng: 4.8812053 },
              map: map,
            });
          }
        </script>
      </head>
      <body>
        <div id="map" style="height: 500px; width: 100%;"></div>
      </body>
    </html>'
    width="100%"
    height="500px"
    frameborder="0"
    allowfullscreen>
  </iframe>
</div>
