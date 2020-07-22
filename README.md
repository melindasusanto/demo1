
<param ve-config
       title="Title of Your Narrative"
       banner="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Cherry20190331105300.jpg/1024px-Cherry20190331105300.jpg"
       layout="vtl"
       num-maps="x"
       num-specimens="x"
       num-images="x"
       num-primary-sources="x"
       author="Names of Authors">

<param title="Beatrix Farrand" eid="Q437714">
<param title="cherry blossom" eid="Q871991">

## Subtitle
Code to add a location with a custom marker on a map for every paragraph in this section.
<param title="Sulawesi" eid="Q3812" fill="#FF0000" marker-symbol="landmark">

Paragraph text-Paste the text for the first paragraph in your narrative here. Below is the code for adding a simple image. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-image
title="Tidal basin cherry blossom" url="https://upload.wikimedia.org/wikipedia/commons/2/2a/Tidal_basin_cherry_blossom_closeup.JPG"
       fit="cover"
       attribution="Wikimedia Commons">
       
Below is the code for adding a map. The center of the map can be set with longitude and latitude, or with a relevant Wikidata QID. This map also uses a pre-made geojson overlay through Wikidata. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="Q3812" zoom="10" basemap="Esri_WorldPhysical">

Below is the code for adding a map with premade Geojson overlays. The center of the map can be set with longitude and latitude, or with a relevant Wikidata QID. This map also uses a pre-made geojson overlay through Wikidata. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map prefer-geojson center="Q3812" zoom="5" basemap="Esri_WorldPhysical">
<param title="Sulawesi" eid="Q3812">

The code below is an example of how to add a custom geojson overlay. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-map center="1.8479, 120.5279" zoom="6">
<param ve-map-layer geojson url="map.json" title="Sulawesi" fill="#FF0000" marker-symbol="landmark" active>

Below is the code for adding an IIIF annotated image created through Storiiies. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
<param ve-storiiies id="861e9">
