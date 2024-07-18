---
title: 
publish: false
cssclasses: 
date: 2024-06-13 15:39
type: note
book: 
page: 
tags:
---
##### Back: [[Plugins]] 



|Option|Description|Default|
|---|---|---|
|[id](app://obsidian.md/index.html#map-ids)|Unique identifier (can be anything). **Required.**||
|[image](app://obsidian.md/index.html#image-maps)|Direct URL/file path to an image file to be used as the map layer.|OpenStreetMap map|
|[tileServer](app://obsidian.md/index.html#real-world-maps)|Add additional tile servers as different layers||
|[tileSubdomains](app://obsidian.md/index.html#tile-subdomains)|Add Available subdomains for additional tile servers concurrent requests. Spilt by ',', etc. 'a,b,c'|a,b,c|
|[tileOverlay](app://obsidian.md/index.html#real-world-maps)|Add additional tile servers an overlay over the base map.||
|[osmLayer](app://obsidian.md/index.html#real-world-maps)|Turn off the OpenStreetMap layer (only usable if additional Tile Servers have been provided)||
|[lat](app://obsidian.md/index.html#initial-coordinates)|Default latitude to display when rendering.|50% (image) / 39.983334 (open street map)|
|[long](app://obsidian.md/index.html#initial-coordinates)|Default longitude to display when rendering.|50% (image) / -82.983330 (open street map)|
|height|Height of the map element. Can be provided in pixels or percentage of note height.|500px|
|width|Width of the map element. Can be provided in pixels or percentage of note width.|100%|
|[minZoom](app://obsidian.md/index.html#initial-zoom-level)|Minimum allowable zoom level of the map.|1|
|[maxZoom](app://obsidian.md/index.html#initial-zoom-level)|Maximum allowable zoom level of the map.|10|
|[defaultZoom](app://obsidian.md/index.html#initial-zoom-level)|Map will load zoomed to this level.|5|
|[zoomDelta](app://obsidian.md/index.html#initial-zoom-level)|Zoom level will change by this amount when zooming.|1|
|zoomFeatures|The map will automatically fit all [GeoJSON](app://obsidian.md/index.html#geojson) and [GPX](app://obsidian.md/index.html#gpx) features||
|[unit](app://obsidian.md/index.html#unit-and-scale)|Unit to display distances in|meters|
|[scale](app://obsidian.md/index.html#unit-and-scale)|Scale factor for image map distance calculation.|1|
|[marker](app://obsidian.md/index.html#markers)|Create immutable markers on the map||
|[commandMarker](app://obsidian.md/index.html#defined-in-code-block)|Create immutable markers that execute commands||
|[markerFile](app://obsidian.md/index.html#marker-file)|Create immutable marker from a note's frontmatter||
|[markerFolder](app://obsidian.md/index.html#marker-folders)|Create immutable markers from _all_ of the notes in the given Paths (relative or absolute to the Vault-Root). Limit Depth by appending one '/' per Folder-Level||
|[markerTag*](app://obsidian.md/index.html#marker-tags)|Create immutable markers from _all_ of the notes with the given tags.||
|[filterTag*](app://obsidian.md/index.html#filter-tag)|Filter what files are used to create markers. Only markers that match the tags will be used.||
|[linksTo*](app://obsidian.md/index.html#links)|Create immutable markers from _all_ of the notes linking **TO** a note||
|[linksFrom*](app://obsidian.md/index.html#links)|Create immutable markers from _all_ of the notes linking **FROM** a note||
|[darkMode](app://obsidian.md/index.html#dark-mode)|Invert map colors|false|
|[overlay](app://obsidian.md/index.html#overlays)|Add a circle overlay to the map||
|[overlayTag](app://obsidian.md/index.html#overlay-tag)|Define a YAML tag to search for in specified marker notes||
|[overlayColor](app://obsidian.md/index.html#overlay-color)|Change default overlay color|blue|
|[bounds](app://obsidian.md/index.html#bounds)|Set image map bounds to specified coordinates instead of default||
|[coordinates](app://obsidian.md/index.html#initial-coordinates)|Read location data from a note and use it as initial coordinates||
|[zoomTag](app://obsidian.md/index.html#initial-zoom-level)|Read distance-to-zoom data from a note and use it as default initial zoom||
|[geojson](app://obsidian.md/index.html#geojson)|Load multiple *.GeoJSON file-Paths in Json or YAML Syntax into this map. Relative Paths to the current doc start with `.` (dot).||
|[geojsonColor](app://obsidian.md/index.html#styles-and-color)|Change the default color of the GeoJSON features.|[#3388ff](app://obsidian.md/index.html#3388ff)|
|geojsonFolder|Search in multiple folders (Json or YAML Syntax) for `*.geojson` or `*.json` files to load into this map. Relative Paths start with `.` (Dot). Limit Subfolder Depth by appending one Slash per Folder-Level||
|[gpx](app://obsidian.md/index.html#gpx)|Load GPX files onto maps.||
|[gpxMarkers](app://obsidian.md/index.html#gpx-markers)|Set default start, stop and waypoint markers||
|gpxColor|Control default GPX color|[#3388ff](app://obsidian.md/index.html#3388ff)|
|gpxFolder|Parse a folder for `.gpx` files to load to the map.||
|[imageOverlay](app://obsidian.md/index.html#image-overlays)|Add an image overlay to the map.||
|[draw](app://obsidian.md/index.html#enable-draw-mode-by-default)|Enable the draw controller on the map.|true|
|drawColor|Default color that new shapes will be drawn with|[#3388ff](app://obsidian.md/index.html#3388ff)|
|showAllMarkers|Map will open showing all markers.|false|
|preserveAspect|If the note pane the map is in is resized, the map will resize itself to maintain its initial aspect ratio.|false|
|noUI|No controls will be added to the map.|false|
|lock|Control whether the map will start locked or unlocked|false|
|recenter|Forces map to stay re-center itself after panning.|false|
|noScrollZoom|Turns off scrollwheel zooming.|false|