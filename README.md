# data_visualization

## Summary
    A map plot use circle size that summarizes rate of delay flights and rate of Cancelled or Deiverted Flight in each US airport between 2006 and 2016. Data from the [RITA](http://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp) filter year between 2006 and 2016. Viewers are able to zoom in to see individual airport information by year.

## Desgin
    Chart type: map (proportional symbol map)
    The data being presented on a US map, radius of circle is presenting how serious the delay or not arrived situation in each airport. Each year is displayed separately in order to allow the viewer to know the change. The number of circles changing by year, the viewer is able to recognize airports’ location. 

## Feedback
    1.  Map color issue (updated)
    2.  Year buttons should not use color – orange, it conflicts with the “delay circle” color. (updated)
    3.  Add a slider bar for the years. (updated)

## Resources
    * [D3 API](https://github.com/d3/d3/blob/master/API.md)
    * [mousewheel-zoom + click-to-center](https://bl.ocks.org/mbostock/2206340)
    * [rangeslider.js](http://rangeslider.js.org/)
    