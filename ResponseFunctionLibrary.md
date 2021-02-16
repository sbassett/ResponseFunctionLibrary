# ResponseFunctionLibrary
Models of suceptibility to wildfire for valued resources and assets.

## Template
| VRA      | FIL 1     | FIL 2     | FIL 3     | FIL 4     | FIL 5     | FIL 6     | FIL Desc | Source |
| :------------- | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :-----------: |
|  NAME | 0   | 0    | 0    | 0    | 0    | 0    | UNIT: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | Source    |

## Communications Infrastructure

| VRA      | FIL 1     | FIL 2     | FIL 3     | FIL 4     | FIL 5     | FIL 6     | FIL Desc | Source |
| :------------- | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :-----------: |
|  Comm Sites/Cell Towers | 0   | 0    | -10    | -20    | -30    | -30    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | [Rogue Basin Strategy v.2](https://www.conservationgateway.org/ConservationPractices/FireLandscapes/LANDFIRE/Documents/Rogue%20Basin%20Cohesive%20Strategy.pdf)    |
|  Communication Sites/Cell Towers | -10   | -30    | -60    | -80    | -100    | -100    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | Gilbertson-Day et al. 2018   |

## Electricity Distribution

| VRA      | FIL 1     | FIL 2     | FIL 3     | FIL 4     | FIL 5     | FIL 6     | FIL Desc | Source |
| :------------- | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :-----------: |
|  Electric Trans-Line/Sub | 0   | 0    | -20    | -20    | -20    | -20    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | [Rogue Basin Strategy v.2](https://www.conservationgateway.org/ConservationPractices/FireLandscapes/LANDFIRE/Documents/Rogue%20Basin%20Cohesive%20Strategy.pdf)    |
|  Trans-Line- High voltage | 10   | 0    | 0    | -10    | -50    | -70    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | Gilbertson-Day et al. 2018    |
|  Trans-Line- Low voltage | -10   | -20    | -50    | -70    | -80    | -90    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | Gilbertson-Day et al. 2018    |


## Buildings and Developed Areas
Some QRAs rely on building or residential density data, others rely on building footprints or other discrete features.

# Delineation

These density metrics can be very poor if the neightborhoods used to defined the area are inconsistently delineated. Census-derived metrics are relatively low quality because 

# Response Functions

Direct ignition vs firebrand/ember ignition?

Response functions differ depending on the delineation method. If the difference in response function between different density classes is due soleyely to the reduced likelyhood of fire impacting astructure so the probabilty of a fire encounter decreases as density decreases ("room for fire")? It could also change due to changes in building proximity and the increased suceptibility of buildings to radiatively ignite other nearby buildings?

It seems reasonable to assume that the response function for discrete building points or footprints would be the same as for the highest density class in the building density system. Community resilience to disasters could be modeled using the approach outlined Davies et al. 2018, and assigned to the building points within the census block group/tract.  

| VRA      | FIL 1     | FIL 2     | FIL 3     | FIL 4     | FIL 5     | FIL 6     | FIL Desc | Source |
| :------------- | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :-----------: |
|  Residential Density <1/40 acres | -10  | -20    | -40    | -80    | -100    | -100    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | [Rogue Basin Strategy v.2](https://www.conservationgateway.org/ConservationPractices/FireLandscapes/LANDFIRE/Documents/Rogue%20Basin%20Cohesive%20Strategy.pdf)     |
| ...|
|  Residential Density >3/1 acre | -20   | -60    | -80    | -100    | -100    | -100    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | [Rogue Basin Strategy v.2](https://www.conservationgateway.org/ConservationPractices/FireLandscapes/LANDFIRE/Documents/Rogue%20Basin%20Cohesive%20Strategy.pdf)     |

## Recreation Sites
| VRA      | FIL 1     | FIL 2     | FIL 3     | FIL 4     | FIL 5     | FIL 6     | FIL Desc | Source |
| :------------- | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: | :-----------: |
|  Ski Areas | 0   | -10    | -20    | -40    | -60    | -80    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | Gilbertson-Day et al. 2018    |
|  Developed Recreation Sites | -10   | -30    | -70    | -90    | -100    | -100    | Feet: 0–2, 2–4, 4–6, 6–8, 8–12, >12    | Gilbertson-Day et al. 2018    |

# References

Davies IP, Haugo RD, Robertson JC, Levin PS (2018) The unequal vulnerability of communities of color to wildfire. PLOS ONE 13(11): e0205825. https://doi.org/10.1371/journal.pone.0205825

Gilbertson-Day, J. W., J. H. Scott, K. C. Vogler, A. Brough, and R. D. Stratton. 2018. Pacific Northwest Quantitative Wildfire Risk Assessment: Methods and Results. :1–86.

[Rogue Basin Strategy v.2](https://www.conservationgateway.org/ConservationPractices/FireLandscapes/LANDFIRE/Documents/Rogue%20Basin%20Cohesive%20Strategy.pdf) 
