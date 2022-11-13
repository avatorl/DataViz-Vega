# Radar Charts for Krakow Bicycle Counters report

The charts (vega code) are almost identical, but one charts shows annual seasonality (by month), another chart shows weekly seasonality (by day of week).
The only difference between two charts are: different data sources (one with 'month' column, another with 'day_of_week' column) and corresponding column references, and different conditional formatting for the axis labels (to highlight either winter/summer months or Saturday/Sunday with different colors). I also removed the spider on the weekly chart.

A slicer on the bottom of the page allows to shitch data agregation level:
- all years and locations average (one line for the average, filled area to show range of annual variations)
- individual years (one line for each year)
- individual locations (one line for each location)
