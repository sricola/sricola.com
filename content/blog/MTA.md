---
title: "NYC MTA Ridership over COVID-19"
date: 2020-03-21
draft: false
show_reading_time: true
tags: [MTA,NYC,COVID-19,travel]
categories: [MTA,NYC,COVID-19,travel]
description: "NYC MTA Ridership over COVID-19"
---
The New York City Transit Authority (MTA) releases weekly data on the number of entries and exits at each of its subway stations. This analysis is based on the data retrieved from the following weeks
 * Week of January 19 - "normal week" before the outbreak, used as a control
 * Week of March 8 - week before NYC placed various restrictions
 * Week of March 15


## What data is being analysed?
The data is based on entries into the specified stations, during the timeframe noted. 

## What does the data tell us?
Infer what you may, but at the very least this tells us that New Yorkers are heeding health directives by avoiding the Subway system. Since the NYC subway is the lifeline of this city and the primary way to get around, this also suggests that New Yorkers are potentially staying home and distancing themselves.

## TL;DR?
While it is impossible to graph data of all stations in the subway system (472 stations), **the general trend is that ridership is much lower than normal**, by a factor of multiple. This is good as we all battle to #flattenthecurve.

# Select hotspots in NYC
The week of March 8 saw a small dropoff at these hotspots (highest usage stations). Encouragingly, the week of March 16 saw a huge drop. A lot of offices are around these stations.

{{< chartjs-weekly >}}

# Select stations with highest drop off

{{< chartjs-most >}}

# Select stations with least drop off
This isn't necessarily bad, its just the least percentage difference.
{{< chartjs-least >}}



## FAQs
### How can I help?
Please stay home, and #flattenthecurve
### Where is this Data From?
Provided by the MTA, the data is free to download from: https://bit.ly/mta_turnstile
### What is this data?
Its the number of entries, using turnstile data at various Subway stations across New York.
### How reliable is this data?
This data is officially published by the MTA. Apart from their guarantees, I make no additional guarantees about the data or its accuracy. Read more: https://bit.ly/mta_turnstile
  