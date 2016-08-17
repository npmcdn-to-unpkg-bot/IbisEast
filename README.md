# IbisEast
<html><head>
	<title>200m</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
	<link rel="shortcut icon" href="favicon.ico">
	<link rel="icon" href="favicon.ico">
	<link rel="apple-touch-icon" href="200m_60.png">
	<link rel="apple-touch-icon" sizes="76x76" href="200m_76.png">
	<link rel="apple-touch-icon" sizes="120x120" href="200m_120.png">
	<link rel="apple-touch-icon" sizes="152x152" href="200m_152.png">
	<meta name="apple-mobile-web-app-capable" content="yes">

	<meta property="og:title" content="200ｍ radius circles">
	<meta property="og:description" content="Double-tap to draw 200m radius circle for catching Pokemon. Long-tap to clear existing circles.">
	<meta property="og:type" content="website">
	<meta property="og:url" content="https://IbisEaston.github.io/200m/">
	<meta property="og:image" content="https://IbisEaston.github.io/200m/200m_ss.png">
	<meta property="fb:app_id" content="1659170097660873"> 

	<meta name="twitter:card" content="summary_large_image">
	<meta name="twitter:image" content="https://IbisEaston.github.io/200m/200m_ss.png">
	<meta name="twitter:title" content="200m radius circles for Pokemon GO">
	<meta name="twitter:description" content="Double-tap to draw 200m radius circle for catching Pokemon. Long-tap to clear existing circles.">
	<meta name="twitter:site" content="@Ibis">





	<link rel="stylesheet" href="https://npmcdn.com/leaflet@1.0.0-rc.3/dist/leaflet.css">
	<script src="https://npmcdn.com/leaflet@1.0.0-rc.3/dist/leaflet.js"></script>

	<style>
		body {
			padding: 0;
			margin: 0;
		}
		html, body, #map {
			height: 100%;
		}
	</style>
</head>
<body>
	<div id="map" class="leaflet-container leaflet-fade-anim leaflet-grab leaflet-touch-drag" tabindex="0" style="position: relative; outline: none;"><div class="leaflet-pane leaflet-map-pane" style="transform: translate3d(-279px, 0px, 0px);"><div class="leaflet-pane leaflet-tile-pane"><div class="leaflet-layer " style="z-index: 1; opacity: 1;"><div class="leaflet-tile-container leaflet-zoom-animated" style="z-index: 18; transform: translate3d(0px, 0px, 0px) scale(1);"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58234/25810.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(645px, 419px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58234/25809.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(645px, 163px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58235/25810.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(901px, 419px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58233/25809.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(389px, 163px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58235/25809.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(901px, 163px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58233/25810.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(389px, 419px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58234/25808.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(645px, -93px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58234/25811.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(645px, 675px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58233/25808.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(389px, -93px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58235/25808.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(901px, -93px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58235/25811.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(901px, 675px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58233/25811.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(389px, 675px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58236/25809.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(1157px, 163px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58232/25809.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(133px, 163px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58232/25810.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(133px, 419px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58236/25810.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(1157px, 419px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58232/25808.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(133px, -93px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58236/25811.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(1157px, 675px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58236/25808.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(1157px, -93px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58232/25811.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(133px, 675px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58237/25810.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(1413px, 419px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58237/25809.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(1413px, 163px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58231/25809.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-123px, 163px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58231/25810.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-123px, 419px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58231/25811.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-123px, 675px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58231/25808.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-123px, -93px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58237/25808.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(1413px, -93px, 0px); opacity: 1;"><img alt="" src="https://api.tiles.mapbox.com/v4/mapbox.streets/16/58237/25811.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(1413px, 675px, 0px); opacity: 1;"></div></div></div><div class="leaflet-pane leaflet-shadow-pane"><img src="https://npmcdn.com/leaflet@1.0.0-rc.3/dist/images/marker-shadow.png" class="leaflet-marker-shadow leaflet-zoom-animated" style="margin-left: -12px; margin-top: -41px; width: 41px; height: 41px; transform: translate3d(800px, 401px, 0px);"></div><div class="leaflet-pane leaflet-overlay-pane"><svg pointer-events="none" class="leaflet-zoom-animated" width="1250" height="959" viewBox="175 -80 1250 959" style="transform: translate3d(175px, -80px, 0px);"><g><path class="leaflet-interactive" stroke="pink" stroke-opacity="1" stroke-width="4" stroke-linecap="round" stroke-linejoin="round" fill="#ffcccc" fill-opacity="0.2" fill-rule="evenodd" d="M779.3190092779696,401.1049762070179a21,21 0 1,0 42,0 a21,21 0 1,0 -42,0 "></path><path class="leaflet-interactive" stroke="#00cc00" stroke-opacity="1" stroke-width="4" stroke-linecap="round" stroke-linejoin="round" fill="#88cc88" fill-opacity="0.2" fill-rule="evenodd" d="M699.7237435709685,397.7653120569885a103,103 0 1,0 206,0 a103,103 0 1,0 -206,0 "></path></g></svg></div><div class="leaflet-pane leaflet-marker-pane"><img src="https://npmcdn.com/leaflet@1.0.0-rc.3/dist/images/marker-icon.png" class="leaflet-marker-icon leaflet-zoom-animated leaflet-interactive" tabindex="0" style="margin-left: -12px; margin-top: -41px; width: 25px; height: 41px; transform: translate3d(800px, 401px, 0px); z-index: 401;"></div><div class="leaflet-pane leaflet-tooltip-pane"></div><div class="leaflet-pane leaflet-popup-pane"></div><div class="leaflet-proxy leaflet-zoom-animated" style="transform: translate3d(1.49081e+07px, 6.60734e+06px, 0px) scale(32768);"></div></div><div class="leaflet-control-container"><div class="leaflet-top leaflet-left"><div class="leaflet-control-zoom leaflet-bar leaflet-control"><a class="leaflet-control-zoom-in" href="#" title="Zoom in">+</a><a class="leaflet-control-zoom-out" href="#" title="Zoom out">-</a></div></div><div class="leaflet-top leaflet-right"></div><div class="leaflet-bottom leaflet-left"></div><div class="leaflet-bottom leaflet-right"><div class="leaflet-control-attribution leaflet-control"><a href="http://leafletjs.com" title="A JS library for interactive maps">Leaflet</a> | Map data © <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, <a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="http://mapbox.com">Mapbox</a></div></div></div></div>

	<script>
		var latestLocation = null;
		var latestCircleLatLng = null;
		
		var centerCircle = null;
		var centerPin = null;
		var centerCircleRadius = 40;

		var searchCircleRadius = 100;
	/*
		var searchCircleStyle = {
			weight: 1,
			color: '#0000ff',
			fillColor: '#ccccff',
			fillOpacity: 0.1
		};
	*/
		var searchCircleCount = 0;
		var searchCircleStyle = function(){
			var searchCircleColor;
			if(searchCircleCount == 0){
				searchCircleColor = '#00cc00';
				searchFillColor = '#88cc88';
				searchFillOpacity = '0.2';
			}
			else if(searchCircleCount == 1){
				searchCircleColor = '#ffcc00';
				searchFillColor = '#ffcc00';
				searchFillOpacity = '0.0';
			}
			else if(searchCircleCount == 2){
				searchCircleColor = '#ff4400';
				searchFillColor = '#ff4400';
				searchFillOpacity = '0.0';
			}
			else if(searchCircleCount == 3){
				searchCircleColor = '#0044ff';
				searchFillColor = '#0044ff';
				searchFillOpacity = '0.0';
			}
			else{
				searchCircleColor = '#444444';
				searchFillColor = '#444444';
				searchFillOpacity = '0.0';
			}
			return {
				weight: 4,
				color: searchCircleColor,
				fillColor: searchFillColor,
				fillOpacity: searchFillOpacity
			};
		}

		var map = L.map('map');
		L.tileLayer('https://api.tiles.mapbox.com/v4/{id}/{z}/{x}/{y}.png?access_token=pk.eyJ1IjoiaW51cm8iLCJhIjoiY2lycXdrZHllMGdzeXQybmsyc2JmaHlqcCJ9.fFTwIuK3ERkV5_WwQWL2vw', {
			maxZoom: 18,
			attribution: 'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, ' +
				'<a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, ' +
				'Imagery © <a href="http://mapbox.com">Mapbox</a>',
			id: 'mapbox.streets'
		}).addTo(map);



		//location event handler
		function onLocationFound(e) {
			//after 1st location found, disable setView
			if(!latestLocation){
				map.setView(e.latlng, 16);
			}

			//prevent same location
			if(latestLocation == e.latlng){
				return;
			}

			latestLocation = e.latlng;
		//	var locationRadius = e.accuracy / 2;

			if(!centerCircle){
				centerCircle = L.circle(latestLocation, centerCircleRadius, {
					weight: 4,
					color: 'pink',
					fillColor: '#ffcccc',
					fillOpacity: 0.2
				});
				centerCircle.addTo(map);
			}
			centerCircle.setLatLng(latestLocation);
		//	centerCircle.setRadius(locationRadius);

			if(!centerPin){
				centerPin = L.marker(e.latlng).addTo(map);
			}
			centerPin.setLatLng(latestLocation);
			centerPin.bindPopup(latestLocation.toString());
		}

		function onLocationError(e) {
			console.log(e);
			alert(e.message);
		}

		var circles = [];
		var KEY_CIRCLES = 'circles';
		function addCircle(latlng, radius, options) {
			var circle = L.circle(latlng, radius, options);
			circle.addTo(map);
			circles.push(circle);
			latestCircleLatLng = latlng;
			searchCircleCount++;

			// Update circles data in localStorage
			var data = [];
			circles.forEach(function (circle) {
				data.push([circle.getLatLng(), circle.getRadius(), circle.options]);
			});
			localStorage.setItem(KEY_CIRCLES, JSON.stringify(data));
		}

		function onMapDblclick(e){
			if(latestCircleLatLng != latestLocation){
				addCircle(latestLocation, searchCircleRadius, searchCircleStyle());
			}
		}

		function onMapTapHold() {
			circles.forEach(function (circle) {
				circle.removeFrom(map);
			});
			circles = [];
			searchCircleCount = 0;
			localStorage.removeItem(KEY_CIRCLES);
			latestCircleLatLng = null;
		}

		var timerId;
		function clearTimer() {
			clearTimeout(timerId);
		}
		map.on('mouseup', clearTimer);
		map.on('dragstart', clearTimer);
		map.on('zoomstart', clearTimer);

		map.on('mousedown', function () {
			timerId = setTimeout(onMapTapHold, 1000);
		});

		//continuous watching location
	//	map.on('locationfound', onLocationFound);
	//	map.on('locationerror', onLocationError);
		map.locate({
			setView: false, 
			watch: true, 
			enableHighAccuracy: true,
			maximumAge: 0, 
			timeout: 3000000
		})
		map.on('locationfound', onLocationFound);
		map.on('locationerror', onLocationError);
		map.doubleClickZoom.disable();
		map.on('dblclick', onMapDblclick);

		function initialize() {
			// Initialize circles by localStorage data
			var circles = JSON.parse(localStorage.getItem(KEY_CIRCLES));
			if (circles === null) return;

			circles.forEach(function (circle) {
				addCircle.apply(this, circle);
			});
		}
		map.on('load', initialize);
	</script>



</body></html>
