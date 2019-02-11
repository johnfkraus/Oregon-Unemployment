# Interactive Choropleth Map of Oregon Unemployment
Choropleth map of unemployment 2006 to 2015
<b>Key map features<b/>: 
    <ul>
    <li>slider bar for changing year
    <li>pop-up box when hovering over counties (box displays county name and unemployment rate), and legend year that updates based on the year chosen by the slider bar.</li>
<ul/>

<ul><ul/>
<ul>Load two external files, a GeoJSON and a CSV, at runtime.<ul/>
<ul/>Process these data, binding attribute data to geometries.<ul/>
<ul>Draw a classed choropleth map of unemployment rates for US counties using an appropriate classification method, e.g.,
ckmeans or quantile, or quartile and a sequential color scheme.<ul/>
<ul>Draw an accompanying legend with an appropriate legend title and class break labels.<ul/>
<ul>Display the map at 100% width and height of the browser window's viewport.<ul/>
<ul>Allow the user to zoom and pan.<ul/>
<ul>Provide a meaningful title for the map, placed upon the map.<ul/>
<ul>In addition to these requirements, your map should also provide the following UI enhancements for the user:<ul/>
<ul>A visual affordance when the user hovers over specific counties (e.g., making the stroke of the county yellow).<ul/>
<ul>A tooltip triggered when the user clicks on a specific county, which provides the name of the county and the specific
unemployment rate for the currently displayed year.<ul/>