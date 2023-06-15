# Clean Energy Access Prioritiser 



## Introduction

Clean Energy Access Prioritiser (CEAP)  is an open-source decision-support tool designed to identify priority areas for clean energy interventions and investments.  The spatial planning tool allows users to evaluate clean energy projects with a multi-sectoral approach, including environmental, socio-economic, cultural and political aspects. 

This web-based multi-criteria tool identifies and analyses  the priority areas (hot and cold spots) in real-time based on custom priorities.  The automatic geo-processing capabilities encompass more than 30 variables, spanning energy demand, environmental conditions and social aspects.
The Clean Energy Access Prioritiser can be of interest to both institutional and private stakeholders in the energy sector, such as policymakers, international donors, governments, and philanthropic investors.

## Benefits of Utilising the Clean Energy Access Prioritiser
Using a web-based geospatial decision-support tool for prioritising areas for clean energy interventions and investments offers several advantages. 

First, the tool enables informed decision-making by integrating various geospatial datasets from multiple sources into a single spatial indicator. Decision-makers can gain a comprehensive understanding of the particular factors influencing clean energy investments in each area. The tool has the ability to extract raw data to provide insights into the influencing factors such as solar irradiation, wind speed, population density, electricity demand, and existing energy infrastructure.

Second, the tool offers easy access to spatial analysis, allowing users to compare normalised spatial variables across different areas. This helps decision-makers to effectively identify areas with the highest potential for clean energy generation, enabling them to optimise their investments and interventions for maximum impact.

Third, the tool allows users to assign different levels of importance to each criterion depending on the specific user's priorities. The tool has the ability to perform multi-criteria-weighted variables generating a composite index (or score) that compares the suitability of each area for clean energy investments in relation to the specific needs of the user.

Forth, the tool offers interactive and exportable outputs such as maps and charts underpinning the results of a selected planning scenario. These visual representations help to identify patterns and hotspots related to clean energy potential and other relevant factors. 

Lastly, the tool is accessible to a wide range of users through the internet, making it easier for stakeholders, policymakers, investors, and communities to access the tool. This accessibility promotes collaboration and engagement among different stakeholders involved in the decision-making processes. By sharing the tool online, decision-makers can gather input from various experts, local communities, and interested parties, fostering transparency and inclusivity.

## Potential Applications of the Clean Energy Access Prioritiser

* Design evidence-based energy planning scenarios: The tool enables users to design energy planning scenarios based on evidence and data-driven analysis. Decision-makers can explore different scenarios by adjusting parameters and inputs to understand the potential outcomes and implications for clean energy investments. This helps in making informed decisions and designing strategies that align with specific energy planning goals.

* Perform spatial suitability analysis: The tool allows users to conduct spatial suitability analysis by considering various factors such as renewable energy potential, environmental constraints, infrastructure availability, and socioeconomic indicators. Decision-makers can identify areas that are most suitable for clean energy investments based on these factors, ensuring optimal utilisation of resources and maximising the benefits of clean energy projects.

* Compare and map scenarios across projects: Users can compare and map different scenarios across multiple projects using the tool. This feature enables decision-makers to assess the impact of various scenarios and projects on clean energy investments. By visualising and comparing the spatial distribution of different scenarios, decision-makers can identify patterns, trends, and areas of overlap or divergence, aiding in the evaluation and selection of the most effective clean energy interventions.

* Access key spatial datasets: The tool provides access to key spatial datasets relevant to clean energy planning and decision-making. These datasets can include information on renewable energy potential, land use, topography, climate data, population density, and infrastructure. Access to such datasets helps decision-makers analyse and understand the spatial dynamics and potential of clean energy resources in a given area.

* Conduct gap analyses: Decision-makers can use the tool to conduct gap analyses, identifying areas or aspects where there is a shortfall or lack of clean energy interventions. By comparing the existing state with the desired goals or targets, decision-makers can identify gaps in clean energy infrastructure, and potential areas for improvement, and prioritise interventions accordingly.

* Understand trade-offs between objectives: The tool allows decision-makers to assess and understand the trade-offs between different objectives. For example, they can evaluate the trade-off between maximising clean energy generation and minimising environmental impacts. By considering and visualising these trade-offs, decision-makers can make more balanced and informed decisions, ensuring that clean energy investments align with broader sustainability objectives.

## How to use the Clean Energy Access Prioritiser
This section will walk you through four essential steps to effectively utilise the Clean Energy Access Prioritiser tool. Additionally, it will provide you with a detailed understanding of the crucial factors to consider when defining priorities for your planning scenario.

![CEAP Overall schema](/images/image10.png)

## Use case: Educational facilities without access to electricity

Hereby we illustrate a  use case to facilitate your understanding of the tool's full potential. Let's consider a practical scenario where you aim to identify suitable areas for the electrification of educational facilities based on the criteria of a specific programme. By following this use case, you will gain practical insights into leveraging the tool effectively.

### Select Variables

To streamline your decision-making process, you have the option to exclude those variables that are not relevant. You can exclude variables in two ways: either all at once or individually. To remove all variables in one go, simply click on the "Remove all variables" button. Alternatively, if you prefer a more selective approach, you can choose to exclude variables one by one. Next to each variable, you will find an "x" icon. Clicking on this icon will remove the respective variable from consideration. By utilising these exclusion options, you can customise your analysis to focus on the most relevant variables, providing you with a tailored decision-making process.
In this use case, you are primarily interested in areas where currently electricity access at remote schools is not guaranteed. Here's how you can approach the variable selection process based on four pillars:

__Market Supply__

Since your goal is to provide electricity where there is currently no access,  you may select variables relevant to your objective such as existing energy infrastructure and energy potentials.  In this case an important variable is to select areas far away from the existing electric grid (i.e. following the national criteria of 5 km away from grid) and then exclude the variable of presence of electric grid.  On top of this, you might be interested in data that indicate the presence of power plants. Furthermore, you might consider the potential of  energy sources  such as solar, wind and hydropower, as they enable clean energy supply. Finally, since focusing on hard-to-reach places would be extremely demanding, you may want to know what is the level of accessibility to prioritise the electrification of schools by decentralised technologies in areas with difficult accessibility . 

__Market Demand__

Your priority is to identify areas with a high prevalence of educational facilities lacking electricity.  Exclude variables that do not directly relate to this objective. However, do consider the variable concerning the distribution and density of population.  This variable helps ensure that your intervention will impact as many children as possible. 

__Environmental Factors__

Environmental factors that relate to the preservation of ecosystems and biodiversity such as Protected and Conserved Areas are essential to be considered when planning clean energy areas to avoid selecting environmentally sensitive territories for large infrastructures and promote decentralised energies when there are energy needs inside the protected areas.. By considering these factors you can minimise the disruption of habitats, protect biodiversity, and maintain the ecological balance. Furthermore, this pillar helps assess the resilience and adaptability of clean energy systems. By considering climate-related factors such as drought risks you can select areas that are less vulnerable to environmental hazards. Prioritising resilient clean energy areas enhances the longevity and reliability of energy infrastructure, reducing the potential for disruptions in educational facilities.

__Socio-Political Aspects__

Socio-political aspects play a crucial role and help ensure the equitable distribution of clean energy access. You may want to consider how planning units score as regards food security and connectivity, such as  internet accessibility and network performance. Additionally, it may be relevant for you to address whether educational facilities are exposed to political violence and protest events.

 <sub>_Please note that the selection of variables can be further expanded based on specific user requirements. The list of information gathered and processed to assess the performance and usability of the tool is a preliminary one and can be enhanced._ </sub> 

### Define Priorities

Once you have identified the variables that are relevant to your analysis, you can assign a specific weight to each of them based on their importance influencing the final result.

To assign weights, consider the following example:
- [x] Energy Potential (High  Weight: 9): Assign a weight of 9 to variables related to the renewable energy resource potential (for solar, wind, or hydropower). This indicates that these factors are highly important in your analysis.
- [x] Presence of Power Plants (Medium Weight: 5): Assign a weight of 5 to variables related to the presence of power plants. This indicates that this  variable is moderately important in your analysis.
- [x] Farthest from the Electricity Grid (High Weight: 8): Assign a weight of 8 to the variable representing the distance from the existing grid (furthest to the grid).
- [x] Accessibility of the Territory (Lowest Weight: 1): Assign a weight of 1 to the variable representing the accessibility of the territory (Most accessible Areas). This suggests that accessibility is the least important factor in your decision-making process.
- [x] Presence of Non-Electrified Schools (Highest Weight: 10): Assign a weight of 10 to the variable representing the presence of non-electrified schools. This indicates that this factor carries the most significant weight in your analysis.
- [x] Other Market Demands and Socio-Political Aspects (Low Weight: 1 or 2): Assign a weight of 1 or 2 to other market demands and socio-political aspects. This implies that these factors are considered as secondary elements in your analysis.

After completing the weighting, you can also exclude “No-Go Areas” from the analysis, which encompass strict nature reserves, wilderness  areas, national parks and monuments, species management areas, protected landscapes, and areas for sustainable use of natural resources. This can be done by ticking the “No-Go Areas” box.

The next step will be to click on “Compute scores”. The resulting map will display the planning units according to a colour scheme spanning from red, which represents the lowest priority areas,  to green,  which represents the highest priority areas.  The algorithms make it therefore possible to identify the areas most in need of intervention for the specific user needs.

Please use the following link to use the CEAP with presets as presented above: [CEAP](https://lucageo.github.io/cep_preset/cep.html?iso3=BEN&distance=1&distance_inv=0&powerplant=5&solar=5&wind=5&hydro=5&acces=3&acces_inv=0&grid=0&industrial=0&population=3&health=0&education=0&education_no_el=10&irrigation=0&gw_irrigation=0&livestock=0&elevation=0&slope=0&natural=0&int_forest=0&pca=0&temp_ano=0&drought=0&food_sec=2&conflicts=2&refugee=2&connectivity=3#6.8/9.334/2.313
)

### Perform Local Analysis

Based on the selection above,  the Northern part of Benin has the highest scores, as shown on the map down below. Specific hotspots with high scores can be found in the North and in the North-West side of the Country.
To further select top-ranking areas, you may use the slider placed in the top-left corner. This will allow you to highlight a specific percentage of the highest-scoring planning units.  
You can further isolate the portion of lands you wish to focus on by using the square or polygon symbols: these tools allow you to draw a polygon on the map  and select the planning units of your interest.

###  Explore and Export Data

After selecting the polygon, an orange box will appear in the top right-hand corner. Here, you will be able to visualise:
- [x] The size of the selected area (in square km);
- [x] A column chart with the scores obtained by the selected variables weighted according to the assigned priority. The columns represent the average value of the scores assigned to each planning unit included in the selected area;
- [x] A radar plot displaying which variables are the most prominent in the area selected. The weights of the selected variables are represented in orange, while the scores of the selected variables are displayed in blue.  This visualisation allows for detecting synergies and trade-offs as well as interlinkages between the variables that cover the area selected. 


____________
### Authors: 
Luca Battistella, Anna Bertelli, Magda Moner-Girona



