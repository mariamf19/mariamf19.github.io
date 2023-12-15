---
title: "Assignment 3: Spatial Data"
categories:
  - Blog
tags:
  - Post Formats
  - readability
  - standard
---

## Spatial Data Assignment

Analyzing Healthcare Facilities in Chennai, India

## Introduction

For this spatial data assignment, I chose to analyze a dataset of 50 hospitals and medical facilities in Chennai, India that included the name, address, and contact information for each location. My goal was to map out these healthcare resources against Chennai's population density data to determine if hospital locations properly serve the healthcare needs of the local communities based on where residents are concentrated around the city.

![](/assets/images/c1.png)

![](/assets/images/c2.png)

I first collected the hospital names and addresses by manually compiling listings found online. After geocoding this spatial data to assign geographic latitude and longitude coordinates, I visualized the points on a map of Chennai using Kepler.gl. I then compared this to a separate map showing Chennai's population density distribution. My analysis looked at the alignment and discrepancies between population levels and access to medical facilities across neighborhoods.

## Data Extraction and Enrichment

The core dataset for this assignment was compiled from online listings of hospitals and medical facilities in Chennai. For each entry, I gathered the facility name, street address, and phone number. Plotting the addresses on a map required geocoding the location data - converting text-based addresses to geographic coordinates. I uploaded the dataset to Awesome Table and used their Geocoding tool to append columns for the latitude and longitude associated with each address.


![](/assets/images/g1.png)

![](/assets/images/g2.png)

With the geocoded data, I now had the key information needed to map out my list of facilities. But mapping points alone would not fully convey if certain areas were under-resourced. For deeper analysis, I needed to also examine the population levels across Chennai. I obtained a separate map showing the population density distribution based on census data. Comparing this with my hospital locations would make it possible to analyze if neighborhoods with more residents also had adequate medical facilities access.

## Data Visualization and Analysis

I uploaded my geocoded hospital data file to Kepler.gl to generate interactive map visualizations. I first plotted the list of facilities as points on a map of Chennai, styling the markers based on categories like hospital vs clinic. I generated a heatmap visualization to show the intensity of locations based on proximity between neighboring points. 


![](/assets/images/kepler.png)

![](/assets/images/pd.png)


The Kepler map revealed clusters and concentrations of medical facilities across Chennai. I could see a large massing of locations stretched along a central corridor spanning from Egmore down to Meenambakkam. Comparing my map against the population density data told a compelling story. The hospital points aligned strongly with the areas colored dark red on the population map, indicating neighborhoods with the highest levels of residents per square mile.

However, the population map also showed that densities remain moderately high extending outside Chennai's core downtown. Yet the medical facilities are rather sparse in certain peripheral areas. This suggests discrepancies in aligning healthcare access with population levels across all districts. While the downtown area caters to local needs, outlying neighborhoods may face gaps in medical coverage despite also being densely inhabited.

### Insights

Central Chennai High-Density Areas: The population density map showed areas of very high density, particularly in central Chennai. The hospital locations map shows a cluster of hospitals in this region. This concentration of healthcare facilities in the most densely populated part of the city suggests an alignment of healthcare resources with the large residential and working population.

Outskirts and Lower Density Areas: The population density map showed lighter areas on the outskirts of the city, such as around Avadi, indicating lower population densities. The hospital locations map shows fewer hospitals in these peripheral areas. This could point to potential gaps in healthcare coverage in less densely populated parts of the metropolitan area.

Distribution and Accessibility: While central Chennai seems well-served, the hospital map indicates that even in areas of lower population density, there are still some hospitals present, though more sparsely distributed. This suggests an effort to provide accessible healthcare across the city, though the capacity and services available may vary.

Potential Overload in High-Density Areas: High-density areas may have many hospitals, but these facilities could be experiencing high patient loads. This could lead to longer waiting times and potentially overstretched resources.

Urban Development Influence: There seems to be a correlation between the urban development (as seen by the road network on the hospital locations map) and the presence of hospitals. This correlation suggests that hospitals are more prevalent along major roads and in more developed areas.

Potential for Improved Coverage: There are pockets within high-density areas that appear underserved by hospitals on the map. These gaps could be opportunities for healthcare development, ensuring that the growing population has adequate access to healthcare.

Through spatial analysis, I was able to identify the strong correlation between population density factors and the presence of nearby healthcare facilities. This demonstrates that resource levels adapt to serve the largest groups of people concentrated in Chennai's urban core and surrounds. Yet there also appear to be opportunities to expand medical access and coverage to lower density areas outside this central corridor as the metro continues to grow.

## Conclusion

Mapping the locations of hospitals and clinics provided visibility into the alignment between healthcare facilities and population levels across neighborhoods in Chennai. Concentrations of medical access serve the downtown region effectively. However, more peripheral areas show gaps in coverage despite moderate density levels. As the population increases, additional healthcare centers may be needed outside the urban core communities. This spatial exercise enabled analysis that would inform needs assessment for improving equitable distribution in healthcare resourcing as Chennai evolves. The visualized data tells a compelling story to support strategic decision-making around community medical infrastructure development.

Mapping the locations of hospitals and clinics provided visibility into the alignment between healthcare facilities and population levels across neighborhoods in Chennai. Concentrations of medical access serve the downtown region effectively. However, more peripheral areas show gaps in coverage despite moderate density levels. As the population increases, additional healthcare centers may be needed outside the urban core communities.
This spatial analysis exercise enabled deeper inquiry into the balance of hospital locations throughout the city. The resulting map visualizations and comparative examination of population data facilitates assessment of where increased healthcare resources and facilities may be required in the near future.


By combining geospatial mapping capabilities with dataset exploration of population density factors, this assignment highlights potential areas for improvement in more equitably distributing access to ensure quality medical care across Chennai's boroughs and neighborhoods as the city continues to evolve demographically. The observed incongruities in hospital locations against resident levels outside the densely populated city center signal priority zones for enhanced investment in healthcare infrastructure realignment.


This multi-layered data story of overlapping population statistics and current medical establishment distribution patterns tells a compelling narrative around strategic planning imperatives to alleviate proportional imbalances through targeted location site selection for proposed future healthcare centers expansion.



