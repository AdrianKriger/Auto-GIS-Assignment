Assignment: Urban Indicators
========================

This will be a granular assessment. Suburb or neighborhood level. 

### Data

 - The data will mostly come from local South African sources:
 
    - [City of Cape Town Open Data](https://www.capetown.gov.za)
    - [Western Cape Government](https://www.westerncape.gov.za)
    - [Statistics South Africa (StatsSA)](http://www.statssa.gov.za)
    - [South African Police Service](https://www.saps.gov.za)
    - [Council for Scientific and Industrial Research (CSIR)](https://www.csir.co.za)
    
     
 - Although there is a strong possibility of using the:
 
     - Global Human Settlements (GHS) 250m Population layer as well.

### The tool will attempt to calculate several indicators about the selected area or areas:
*(this might not be a comparison but an assessment - The City of Cape Town has its own [ECAMP](https://web1.capetown.gov.za/web1/ecamp) evalutation. I don't know how it comes up with its numbers but it will give me a ground truth to gauge my results with)*

- Population distribution and demographics

    - Key statistics with graphs
    
    
- Population growth

    - Compare population from at least two different years
    - Visualize as graphs
    

- Accessibility:

     - Travel Times will focus on accessability to schools, health care and public transport. Also to one or more economic hubs (thus walking and driving).
     - Travel time calculation will be done through ```shortest paths``` on a road and along the local Integrated Bus-Rapid Transit network
     - Dominance areas will cull population numbers from the GHS layer.
     - Visualization through graphs and maps
     

- Green area index

     - Calculate the percentage of green areas.
     - Visualize the results.
     

- Street network metrics

    - Fetch street network data or use CoCT Open Data
    - Calculate street network metrics
    - Visualize the results
    

- Building density and Air Quality

    - Building polygons might be a challenge in South Africa and air quality might not be available for the area of interest. I'll look into it.
