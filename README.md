 # owf-lib-viz-c3
Open Water Foundation visualization library based on C3

## Getting Started

A standard development folder structure is recommended. The website development files can be set up as follows (Windows is assumed, but Linux would be similar):

```
> C:
> cd \Users\user
> mkdir C3
> cd C3
> mkdir git-repos
> cd git-repos
> git clone (URL)
``` 
The repository contains multiple folders that include time series examples using different sets of data.
## Additional Documentation

See also:
* [C3 Documentation](http://c3js.org/gettingstarted.html)
* [C3 Examples](http://c3js.org/examples.html)
* [C3 Options](http://c3js.org/reference.html)

## Dataset Limitations

At around six years of data using four different series, approximately 8,760 data points, C3 becomes bogged down when using the subchart and when scrolling around the graph.
C3 seems to do extremely well with simple, small sets of data.

## What is a Timeseries Graph

Timeseries, also known as Line Graphs, are used to display quantitative value over a continuous interval or time span. It is most frequently used to show trends and relationships (when grouped with other lines). Line Graphs also help to give a "big picture" over an interval, to see how it has developed over that period.

Line Graphs are drawn by first plotting data points on a Cartesian coordinate grid, then connecting a line between these points. Typically, the y-axis has a quantitative value, while the x-axis has either a category or sequenced scale. Negative values can be displayed below the x-axis.

For more information refer to the links below:

* [Timeseries Graph](http://www.datavizcatalogue.com/methods/line_graph.html)
* [Timeseries Documenation](https://developers.google.com/chart/interactive/docs/gallery/linechart)