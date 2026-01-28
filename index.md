## **Welcome to my portfolio!**

#### Contact Information
**Email:** [nym.veach@gmail.com](mailto:nym.veach@gmail.com)  
**LinkedIn:** [www.linkedin.com/in/nym-veach](https://www.linkedin.com/in/nym-veach)  
**GitHub:** [github.com/nym-veach](https://github.com/nym-veach)

#### Professional & Educational Background
I’m currently a student in the Earth Data Analytics Graduate Certificate Program at CU Boulder, developing skills in geospatial analysis, data analytics, and data-driven approaches to address complex environmental challenges. My coursework involves processing and visualizing environmental data, using tools like Python and Jupyter Notebooks, and applying those technical skills to real-world projects. 

Previously, I worked as an Environmental Scientist at the North Dakota Department of Environmental Quality, overseeing regulatory compliance and data monitoring for safe drinking water, including disinfection byproducts, volatile organic compounds, pesticides, and inorganic chemicals. Additionally, I worked with the Dakota Resource Council, a grassroots environmental nonprofit, supporting community engagement on sustainable natural resource and land-use issues. I have a deep passion for water resources, but am curious about all sorts of environmental systems.

My interdisciplinary background spans environmental compliance, stakeholder engagement, policy, education, communications, research, and field/lab work. I graduated summa cum laude with a B.S. in Natural Resources Management, with an emphasis in physical and earth resources science.

#### About Me
Outside of work, I love writing, reading, hiking, meditation, travel, and spending time with my three cats.
*“Instructions for living a life. Pay attention. Be astonished. Tell about it.” -Mary Oliver*

#### Interest Areas
- Water Resources, Hydrology, & Hydrogeology
- Water Quality Monitoring
- Nonpoint Source Pollution
- Environmental Planning
- Geospatial Analysis (GIS)
- Time-Series Analysis of Environmental Data
- Applied Machine Learning for Environmental Data
- Environmental Chemistry & Chemical Contaminants (Drinking Water)
- Science-Based Policy
- Flood Risk Management & Mitigation
- Climate Change Impacts

## <u> Projects </u>


#### **Elwha Dam Removal**

#### **Elwha River Dam Removal: NDVI**

#### **Trumpeter Swan (Cygnus buccinator) Migration Analysis using Python**

**Following the Flight: Where Can You Find the Trumpeter Swan (Cygnus buccinator) Throughout the Year?**

Trumpeter Swans are a symbol of resilience, grace, and beauty. They also tell a story of successful conservation efforts to protect wetlands and threatened species. Following their migration on the map above, Trumpeter Swans spend the winter in inland areas such as the Midwest and along the U.S. coasts where waters remain ice-free. They then travel to remote regions such as Alaska, Canada, and the northwestern U.S. to breed in the spring and summer (Cornell Lab of Ornithology, n.d.).

Only about 10 % of trumpeter swans are long-distance migrants. Many others migrate a moderate distance, some a short distance, and a few populations are non-migratory, staying relatively local to their breeding grounds (BirdFact, 2023). There are three subpopulations of trumpeter swans: the Pacific, the Rocky Mountain, and the Interior. They fly in small family groups of 10 - 25 birds. Trumpeter Swans are sensitive to failed hatches due to human disturbance, which is one reason they need calm and undisturbed water habitat for successful breeding (U.S. National Park Service, 2025).

Some of the populations that are visible in certain regions year-round are from swan populations that were reintroduced due to conservation efforts in areas like Oregon and Yellowstone National Park. Some of these southern populations no longer migrate at all, as ice-free waters are available year-round close to their breeding grounds.

Recovering from near-extinction due to hunting, habitat loss, pollution, and human disturbance is not an easy feat. Trumpeter Swans have made a serious comeback, but the fight is far from over for birds that are impacted by humans and climate change. Trumpeter swans are an iconic and easily identifiable bird. They are an important indicator species for freshwater ecosystem health and water resources management more broadly. Using this species migration interactive map, you can follow them as they travel to find habitat with clean and calm waters.

This data analysis used Python to work with occurrence data from GBIF, spatially joined to WWF ecoregion polygons, to create the species migration map. The normalized mean occurrence was used to reduce spatial and temporal sampling variability. While this data analysis did not yet include wetland characteristics, water quality, or hydrologic data, it could provide a valuable foundation and direction for future environmental data science studies. By combining Trumpeter Swan migration patterns with wetland, hydrologic, or even climate data, researchers could investigate associations between swan occurrences and freshwater ecosystem health, detect environmental changes over time, and inform water resources management for data-driven decisions. [View the full data analysis]()

#### **Climate Change & Large Freshwater Lakes: Lake Superior’s Story Shows How Air Temperatures Alone Can Mislead**
<div style="width: 100%; max-width: 100%; overflow-x: auto;">
  <iframe 
    src="img/lake-superior-temp-interactive.html" 
    width="100%" 
    height="600" 
    style="border:none; min-width: 800px;">
  </iframe>
</div>

Lake Superior is the largest lake by surface area in the world, holding approximately 10% of the planet’s fresh surface water, and is among the fastest warming large lakes globally. At first glance, one might think the Lake Superior region isn’t being impacted by climate change, since near-shore air temperatures show a slight cooling trend (slope = –0.002 °C/year, R² = 0.02). This R² indicates that most of the temperature variation is natural and that the trend line explains very little of it.

Grand Marais, MN station along the shoreline was used as a land-based proxy to get near-shore lake air temperatures. This analysis highlights how air temperatures alone don’t tell the full story of climate change or explain complex air–land–water interactions. While local air temperatures appear stable or slightly cooling, broader regional and water temperature data reveal clear warming and climate change impacts such as increased precipitation, reduced ice cover, stronger storms, and changing habitats.

Large lakes like Lake Superior can modulate local air temperatures, acting as a thermal buffer by absorbing/storing heat, which can mask the full effects of climate change when examining air data alone. [View the full data analysis](https://nym-veach.github.io/portfolio_posts/01-lake-superior-shoreline-climate-change.html) for data cleaning, visualization, trend calculation, references, and further discussion.

Data Citation: Menne, M. J., Durre, I., Korzeniewski, B., McNeill, S., Thomas, K., Yin, X., Anthony, S., Ray, R., Vose, R. S., Gleason, B. E., & Houston, T. G. (2012). Global Historical Climatology Network – Daily (GHCN-Daily), Version 3: Grand Marais, MN (USC00213282), 1920–2020. NOAA National Centers for Environmental Information. https://doi.org/10.7289/V5D21VHZ [Accessed October 4, 2025]

#### **Map of Lake Metigoshe created with Python**
Lake Metigoshe is an transboundary waterway near where I grew up, on the international border between North Dakota and Canada. It is a glacial lake with unique hydrological properties in the Turtle Mountain region. It has sensitive water chemistry and has struggled with nutrient pollution, leading to harmful algal blooms in recent years. As a part of Lake Metigoshe State Park, the lake supports important wildlife habitat and recreation activities. I spent a lot of time here in my youth and a summer in 2017 serving as a naturalist and environmental educator, which deepened my personal connection and professional curiosity of the landscape.
<iframe 
  src="img/lakemetigoshe.html" 
  width="600" 
  height="600" 
  style="border:none;">
</iframe>
