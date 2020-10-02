**7 day average new COVID-19 cases by US State - rate visualization**

This is a visualization that shows relative rate of increase in new COVID-19 cases by US State over the past 7 days.

View web page with visualization <a href="https://sitrucp.github.io/covid_rate_us/" target="_blank">here</a>.

Uses D3.js SVG to to retrieve csv file and process data, including filtering to most recent 7 days, group by location to get case count means, and create location SVG canvas, location SVG name text & counts, and circle shape elements, and transitions.

Data from <a href="https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36" target="_blank">US CDC</a>.