---
title: "Welcome to Fokker statistics!"
date: 2025-05-11T13:04:50+01:00
draft: false
Description: "Statistics from the Gameworld Fokker in AirlineSim"
---

This website shows the weekly statistics from the Private Gameworld Fokker from AirlineSim. [AirlineSim](https://www.airlinesim.aero/en) is a realistic airline simulation game that includes various aspects of flight planning such as fleet management, route evaluation and scheduling and maintaining connections at key hubs - all supported by real-world demand and real-time simulation. Fokker is a private server that hosts AirlineSim, visit us [here](https://www.fokker.airlinesim.aero/en).

## Visualization of last week's statistics

### Available seat kilometres (ASKM) vs Passengers carried
![Bubble Plot of ASKM vs Passengers carried](/fokker-statistics/images/askm_v_pax.png)
ASKM is the number of seats offered per flight multiplied by the flight distance and summed up over all flights. Your revenue depends on both the number of passengers transported and how far you have transported them. As such, ASKM is a better indicator of revenue compared to passengers carried.

The above plot of ASKM vs Passengers carried helps ascertain the average stage length of different airlines. For example, US based airlines have higher ASKM than their European counterparts as the average intra-european flight is much shorter than its US counterpart. Airlines make money when their planes are in the air. Hence, a plane deployed on a long-haul flight would make more money than a similar plane deployed on multiple short haul flights due to the impact of ground handling, with all other factors such as loads and profit margins being equal.

Note that the number of flights includes both passenger and cargo-only flights. Hence, ASKM is plotted against passengers carried (instead of the number of flights) for an unbiased picture of stage length. 

### Available freight kilometres (AFKM) vs Cargo carried
![Bubble Plot of AFKM vs Cargo carried](/fokker-statistics/images/afkm_v_cargo.png)
AFKM is the cargo equivalent of ASKM and the same logic applies here.

### Statistics
Here are the statistics from last week presented in a sortable format. Just click on the column header to sort:
{{< rawhtml >}}
{{< include-html "static/tables/statistics.html" >}}
{{< /rawhtml >}}
