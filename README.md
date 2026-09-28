# Canadian Archival Maps (Gigapixel Tiles for StoryMapJS)

This repository hosts pre-sliced Zoomify tile pyramids for use with Knight Lab StoryMapJS.

## Usage in StoryMapJS

In StoryMapJS:
1. Open Options > set StoryMap Type to Gigapixel.
2. Enter the Base URL (including the trailing slash /) and the corresponding Width and Height.

| Map | Base URL | Max Width | Max Height |
| :--- | :--- | :--- | :--- |
| Toronto (1876) | https://<username>.github.io/gigapixel/toronto1876/ | 12746 | 8150 |
| Upper & Lower Canada (1815) | https://<username>.github.io/gigapixel/bouchette1815/ | 12096 | 7553 |
| Western British North America (1814) | https://<username>.github.io/gigapixel/thompson1814/ | 9146 | 5744 |
| Inhabited Part of Canada (1777) | https://<username>.github.io/gigapixel/french1777/ | 9552 | 6464 |

---

## Sources & Attributions

The original image files were obtained via Wikimedia Commons. Derivative Zoomify tile sets were generated using libvips (dzsave --layout zoomify) for educational display.

### 1. Bird’s-Eye View of Toronto (1876)
* Title: Bird’s-Eye View of Toronto (1876)
* Creator / Lithographer: Art by P.A. Gross3 lithographed by Copp, Clark & Co. Limited.
* Source: https://commons.wikimedia.org/wiki/File:Toronto_1876.jpg
 License: Public Domain

### 2. Map of Upper & Lower Canada (1815)
* Title: Map of the provinces of Upper & Lower Canada with the adjacent parts of the United States of America, &c. (1815)
* Creator / Cartographer: Joseph Bouchette, William Faden, J. Walker. Digital file via Digital Commonwealth.
* Source: https://commons.wikimedia.org/wiki/File:1815_Map_of_the_provinces_of_upper_&6_lower_Canada_with_the_adjacent_parts_of_the_United_States_of_America,_&c,_by_Joseph_Bouchette, William_Faden,_J._Walker,_from_the_Digital_Commonwealth_-_commonwealth_8049g898c.jpg
* License: Public Domain

### 3. Map of Western British North America (1813-1814)
* Title: Map of Western British North America (David Thompson, 1813-1814)
* Uploader / Attribution: Manitoba Historical Maps
* Source: https://commons.wikimedia.org/wiki/File:Map_of_Western_British_North_America_(David_Thompson_1813-1814).jpg
 License: Creative Commons Attribution 2.0 Generic (CC BY 2.0) -https://creativecommons.org/licenses/by/2.0/
* Note of Modification: Scaled and sliced into Zoomify pyramid web tiles via libvips.

### 4. A Map of the Inhabited Part of Canada from the French Surveys (1777)
* Title: A map of the inhabited part of Canada from the French surveys, with the frontiers of New York and New England (1777)
* Uploader / Attribution: http://maps.bpl.org (Norman B. Leventhal Map & Education Center at the Boston Public Library)
* Source: https://commons.wikimedia.org/wiki/File:A_map_of_the_inhabited_part_of_Canada_from_the_French_surveys,_with_the_frontiers_of_New_York_and_New_England_(4578688747).jpg
* License: Creative Commons Attribution 2.0 Generic (CC BY 2.0) -https://creativecommons.org/licenses/by/2.0/
* Note of Modification: Scaled and sliced into Zoomify pyramid web tiles via libvips.

---

## Citation Snippets for Student Projects

When referencing these base maps on your StoryMap title slide:

For Toronto (1876):
Base map: Bird’s-Eye View of Toronto (1876), art by P.A. Gross, Copp, Clark & Co. Lith., Public domain, via Wikimedia Commons.

For Upper & Lower Canada (1815):
Base map: Map of Upper & Lower Canada (1815), Joseph Bouchette, William Faden, J. Walker, Public domain, via Digital Commonwealth / Wikimedia Commons.

For Western British North America (1814):
Base map: Map of Western British North America (1813-1814), David Thompson; digital scan by Manitoba Historical Maps, licensed under CC BY 2.0 (https://creativecommons.org/licenses/by/2.0/), via Wikimedia Commons. Tiled for Zoomify.

For Inhabited Part of Canada (1777):
Base map: A map of the inhabited part of Canada from the French surveys (1777); digital scan courtesy of the Boston Public Library (http://maps.bpl.org), licensed under CC BY 2.0 (https://creativecommons.org/licenses/by/2.0/), via Wikimedia Commons. Tiled for Zoomify.
