# Internship_Research2
## Developing a Computer Vision Model for Forest Analysis


The paper  "Forest digital twin- A new tool for forest management practices based on Spatio-Temporal Data 3D simulation Engine and intelligent interactive environment " introduces the concept of digital twins and their applications in various fields. It highlights the lack of common approaches, standards, and guidelines for digital twins in forestry. The authors identify gaps in existing forest digitization studies, mainly:
- Lack of decision-making feedback
- Absence of virtual-real interaction synchronization
- Focus on one-way forest management practice visualization

### 1. Study Area and Data Collection:
- Two study areas: Huangfengqiao Forest Farm (Hunan Province) and Shanxia Experimental Forest Farm (Jiangxi Province), China
- Data collected includes individual tree attributes (coordinates, age, DBH, height, crown width, under living branch height)
- Texture information (1366 photos) of bark, branches, leaves, and surrounding environment

### 2. Methodology:
#### 2.1 Neighborhood Indices:
The paper discusses various stand spatial structure indices:
- Uniform angle index
- DBH dominance
- Openness
- Spatial density index
- Hegyi competition index
- Forest layer index

These indices are used to characterize the spatial distribution, advantage degree, crowding, competitiveness, and vertical distribution of trees in a stand.

#### 2.2 Tree Grading Growth Model:
- Introduces a comprehensive spatial structure grade index (FCGSS)
- Uses Richards growth equation as the basic model
- Incorporates Bayesian method and Particle Swarm Optimization (PSO) for parameter estimation
  ![image](https://github.com/fedy-culer/Internship_Research/assets/151845761/bb43cfbe-8587-4e44-bb4a-8684fd566ac8)


#### 2.3 Forest Digital Twin Construction:
- Utilizes Unreal Engine 4 for visualization
- Integrates tree model database, 3D terrain, and dynamic interaction
- Implements virtual-real synchronization and decision-making feedback
- Describes the process of thinning simulation and harvested tree selection
  ![image](https://github.com/fedy-culer/Internship_Research/assets/151845761/d1174458-616e-41cf-8f05-26f06cd02a34)


#### 2.4 Evaluation Methods:
- Virtual reality representativeness tests with human assessors
- Evaluation metrics for growth models (MAPE, R², Accuracy)
  ![image](https://github.com/fedy-culer/Internship_Research/assets/151845761/62d80915-1683-48fc-81e5-92d0f270a39f)


### 3. Results:
#### 3.1 Forest Digital Twin Representativeness:
- High success rate (91.3%) in matching real forest images with digital twin scenes
- System capable of handling up to 100,000 trees without rendering issues

#### 3.2 Dynamic Tree Growth Model:
- High prediction accuracy for DBH (94.7%), height (91.9%), crown width (89.9%), and under branch height (84.6%)
- The proposed model (TGGM) outperforms basic grading models and spatial structure unit-based models
  
#### 3.3 Dynamic Interactive Thinning Simulation:
- Compares thinning approaches: human assessor (ASS), forest digital twin (FDT), and their interaction (ASS-FDT)
- ASS-FDT interaction shows superior performance in optimizing stand spatial structure
- The multi-dimensional stand spatial structure index (F-index) increased by 22.82% after ASS-FDT thinning
![image](https://github.com/fedy-culer/Internship_Research/assets/151845761/217b108c-e92a-468e-90ff-5efa940a111b)

### 4. Discussion:
#### 4.1 Utilization of Forest Digital Twin:
- Highlights the importance of fidelity in visual representation
- Discusses the advantages of the proposed growth model
- Addresses limitations in the current implementation (e.g., limited tree species, simple growth parameter settings)

#### 4.2 Implications for Forest Management Practices:
- Emphasizes the potential of forest digital twins in resource monitoring, analysis, and natural scene reproduction
- Discusses the frequency of data updates based on growth stages and other factors
- Proposes key design principles for future, more complex forest digital twins
![image](https://github.com/fedy-culer/Internship_Research/assets/151845761/ee8bc58f-7ad5-4bfd-bd73-a9f7c3d746d4)

### 5. Conclusion:
The paper concludes that the proposed forest digital twin can effectively characterize real forest structures, predict tree growth with high accuracy, and optimize stand spatial structure through interactive thinning simulations. It acknowledges limitations and suggests future research directions, including integration of more ecological factors.
![image](https://github.com/fedy-culer/Internship_Research/assets/151845761/c5d063e8-5e01-4d10-bec6-519b43f41fa2)

This research provides a comprehensive framework for developing forest digital twins, combining various aspects of forestry, geospatial technology, and computer science. It offers valuable insights for your computer vision project, especially in areas of tree detection, attribute estimation, and species identification from imagery.
