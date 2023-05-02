## Open questions for Bellingcat technical contributors

These are difficult, long-term projects that would contribute to open source investigations at Bellingcat and for other investigators around the world. If you are interested in working on these topics, Bellingcat can help connect you with technical resources.

Pull requests that add additional references, ideas, or explorations to the list below are very welcomed.

### Assisted or semi-automated terrain perspective match

From a photograph containing topographic features, can the location and view angle be determined?
* Topographic features could be traced from the image manually.
* An approximate geographic bounding box could be required to constrain the search space.
* Could make use of OSM data - triangulation/other techniques used on source image to describe a cluster of OSM features and their positions (e.g. bridge, building, way) which are then searched for in a given region. Descriptions would need to be semantic (e.g. relative placement of features, shape of roads) as that is more meaningful than assumed position. (For example it could be as simple as searching for 'large apartment block, gas station and river within 50m of each other', or as complex as 'railway line passing through forest with two buildings either side')


### Electrical network frequency analysis

Create an open source package for chrono-locating a audio/video source by matching electrical network frequency variations (from low frequency hums in source audio) with recorded variations in a grid frequency database (i.e. https://osf.io/m43tg/). This is theoretically possible (many IEEE articles about it) and reportedly in use by state-level justice entities, but is it practical for the OSINT hobbyist? To our knowledge, no one has publicly developed a public, non-academic proof-of-concept of this.

### Interferometric SAR imagery

Synthetic aperture radar imagery (as captured by, e.g., Sentinel-1) has certain advantages over optical imaging for open source investigation. It is unaffected by cloud cover and can even be used to detect radar installations, as has been previously documented. An additional advantage, little explored in the open source investigation community, is that these images are complex, that is, they contain both magnitude and phase information. While difficult to work with for several reasons (not accessible in Google Earth Engine, requires "unwrapping", etc.), it has some useful applications for computing topography or topographic changes. It is often used in academic research to visualize crust deformations following an earthquake or long-term land subsidence in agricultural areas. Could this phase data also be used for open source investigations, for example to see deforestation or bombing impacts?

### Resource lists for conventional Sentinel imagery

Curation of resources for convential Sentinel-2 imagery would be useful to open source investigators. There are many resources out there, but collecting them in one place would be useful. This could include Sentinel Hub scripts for visualizing certain types of Sentinel-2 products, such as water or fire detection. Bellingcat technical contributors have started collecting some references in the `conventional-sentinel-resources/` folder.
