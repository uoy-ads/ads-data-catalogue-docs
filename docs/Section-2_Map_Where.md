---
title: Where - The Map tool
description: The search options within the ADS Data Catalogue related to 'Where' the resource is located.
---

# Where - The Map tool

The Where tool uses an interactive map to display resource locations and allows you to refine your search results geographically. You can view results as heat spots, zoom into specific areas, or use drawing tools to define precise search boundaries.


| Where | Description |
| ----------- | ----------- |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Map of search results displayed as heat spots](../assets/04-Map.png) | The map on the Search results page displays the location of resources from your search results (where co-ordinates have been provided in the metadata). These appear as ‘heat spots’ on the map interface. <Br><Br>You can zoom in and out to a limited extent and change the map layers using the icons provided. See "Map filter options" below for more information.<Br><Br>By default, zooming in and out options will not change the defined area or the search results. |
| ![Map of search results with Search area option](../assets/55-Map_search_area.png) | You can use the map search to refine the results. After zooming in, a new option, “Search area”, will appear at the top of the map. Clicking this button  will update the search results to match what is currently shown by the map. Once you have zoomed in or when the number of resources is 500 or less, the heat map changes to show clusters and pins for more precise resource locations. Expanding the map area does not change the results again until you click the “Search area” option once more. <Br><Br>For more complex search areas and greater geographical precision, use the “Advanced search” option. |

## Advanced search

Clicking on ‘Advanced Search’ will open the Map filter page, where ou can refine your search results geographically by selecting specific areas on the map.

![Map with display options](../assets/05-Full-map-with-filters.png)
<p align=center><i>Map filter page with full set of filters (left) geographical tools (right)</i></p>

The map can be used alongside the other search filters displayed on the left side of the screen. They can be hidden by clicking on the "Hide filter" button to the right of the column. 

The default base map uses Open Street Map (OSM), which shows national borders with place names in native languages. 

## Map filter options

A series of icons in the bottom right hand corner of the map provide various options for filtering results using the map tool.

| Icon | Description |
| ----------- | ----------- |
| ![Layers icon for map display option](../assets/06-Layers-icon.png) | The Layers icon opens a sub-menu with six different base map display options, including Google Satellite and street map. All place names appear in English. |
| ![Zoom in and out icon for map display option](../assets/07-Zoom-icon.png) | The Zoom icons allows you to zoom in and out of geographic regions. You can also zoom using a touchpad or mouse wheel where enabled.|
| ![Set of drawing tool options - line. polygon and rectangle](../assets/08-Drawing-tool-icons.png) | The Drawing tools include:<Br><Br> Line tool - displays the distance between each point drawn. <p>Polygon tool - defines a multi-sided area on the map. <Br><Br> Rectangle tool - defines a rectangular area on the map between two opposite corners. <p>Results are updated to display only records located within the defined areas. Each of the drawing tools has options to complete, edit or cancel the operation. |


### Display as search result
Once you have defined an area of interest, you can view all related resources on the Results page by clicking the ‘Display as search result’ button in the top left corner of the screen. The number of resources within the curent view is shown above the button.

![Map in Google satellite mode showing resources](../assets/09-Map-in-Google-satellite-mode-showing-resources.png)
<p align=center><i>Map shown in Google Satellite mode showing both individual and clusters of resources</i></p>

## Representation of resources on the map
### Pin icons

<figure markdown="span">
  ![Pin icons used on the map to denote resource locations](../assets/10-Map-pins.png)
  <figcaption>Pin icons represent individual resources on the Map</figcaption>
</figure>
  
Different icons represent how resources appear on the map tool.

- **Geo point** - shows a single resource with exact co-ordinates. When multiple Geo point appear on the Map, the current resource is highlighted by an inner red ring. 
- **Geo shape** - indicates where a resource location is not precise. This occurs when the resource location is given as a geographical area (e.g. a town or region) or, where reports cover a large or multiple locations.
- **Approximate location icons** - shown when a resource location is considered sensitive, such as shipwrecks or sites where valuable metal artefacts have been found. Blue pins indicate an approximate point and red pins show an area. Individual record for red pin sites display a defined area (often rectangular) where the actual location is a random point within the shown area.

| Icons | Description |
| ----------- | ----------- |
| ![Red pins used on map](../assets/11-Red-pins-on-map.png) | In this example, the red outline defines the area where a gold finger ring was found and includes two other resources with nearby, imprecise locations. Additional resources with both with exact and imprecise locations are also visible within the larger area. |

### Cluster icons

![Cluster icons used to denote multiple icons at a map location](../assets/10a-Map-clusters.png)
<p><i>Cluster icons used to represent groups of resources on the Map</i></p>

Clusters icons denote locations where multiple resources can be found. The different colours indicate the total number of resources: blue = 1-10, yellow = 11-99 and red 100+ resources.

![Multiple pins (expanded view) on the map](../assets/12-Multiple-pins.png) 

Hovering your mouse over individual Geo points and Geo shapes will display the title of the associated resource. In the example below, the circular pattern of Geo shapes represents a cluster of resources that have been assigned the same approximate location. This pattern appears when you click the cluster icon - each individual pin can then be clicked to view the related resource record. 

Please note that the Map functions operate the same way on both the Map tool and the main Results page. Minor differences may appear on the individual Resource pages, specifically the display of an imprecise or approximate location for a resource. 
