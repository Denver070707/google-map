<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="initial-scale=1.0">
  <meta charset="utf-8">
  <style>
    #map {
      height: 100%;
    }
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
    }
  </style>
  <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAWQVZPx1PlYpr_ovXdSYm-DpneZ71M12g"></script>
  <script>
    function initMap() {
      var map = new google.maps.Map(document.getElementById('map'), {
        center: {lat: 52.51, lng: 13.4},
        zoom: 10
      });
    }
  </script>
</head>
<body onload="initMap()">
  <div id="map" style="height: 100%; width: 100%;"></div>
</body>
</html>
