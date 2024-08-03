# Reshaping the Digital Twin Construct with Levels of Digital Twinning (LoDT)

## Overview

The paper titled "Reshaping the Digital Twin Construct with Levels of Digital Twinning (LoDT)" addresses the lack of harmonization in the interpretation and definition of digital twins and proposes a conceptual approach to the digital twinning of engineering physical assets.

## Background

Research on digital twins has often focused narrowly on specific applications or IoT frameworks, lacking a unified approach for strategic development. Sectors like Architecture, Engineering, and Construction (AEC) have shown resistance to digital transformation, citing barriers such as return on investment uncertainties, interoperability issues, and technology comprehension gaps.

## Functional Architecture of Digital Twinning

### Terms and Definitions

Digital twinning, introduced by Michael Grieves in 2002, involves replicating physical objects and processes through digital technologies. The concept of digital twinning harmonizes discussions on DTs by emphasizing that mirroring physical assets digitally can manifest in multiple dimensions. 
![Gemini_Principles](https://github.com/maram77/Summer_Internship_2024/assets/85744265/a5d0c6fe-9581-43e8-b9b2-c16294ecdad7)


### Structural Elements

- **Physical entity**: Represents physical assets or processes.
- **Data**: Synchronizes physical and digital spaces.
- **Digital models**: Represent physical entities with varying fidelity.
- **Decision making**: Supports decision-making processes.

### The Architecture

The proposed architecture builds upon Grieves' foundational elements, emphasizing the physical and virtual spaces' integration and effective data management.

1. **Physical Space**: Includes physical assets generating data.
2. **Virtual Space**: Composed of:
   - **Data Management**: Integrates and processes data.
   - **Perception Generation**: Analyzes data to generate insights.
   - **Decision Making**: Uses insights for decision support.be automated or involve human intervention, depending on the purpose and structure defined for the physical asset.
![Architecture](https://github.com/maram77/Summer_Internship_2024/assets/85744265/fd572022-47f6-43f5-b74d-c565a86cd0fd)

The **Information Value Chain** (Bolton et al., 2018) is present throughout the three layers of the virtual space. As data progresses through these layers, its volume decreases while its meaning and value increase, aligning with the DIKW hierarchy (data–information–knowledge–wisdom). In this transformation process, data collected from physical assets becomes digital assets, considered cognitive assets because they are necessary for converting individual knowledge into organizational knowledge and ensuring coordinated actions.

#### Creation

Data collection in the creation phase involves parameters for assessing physical asset performance, using sensors and manual or automated methods. Managing data as information assets considers risks and security enhancements.

Key considerations:
- Parameters to measure
- Types of sensors
- Data acquisition frequency
- Instrumentation cost
- Installation and replacement accessibility
- External agent exposure
- Preventing data acquisition distortions (e.g., aliasing effect)
- Optimizing acquisition frequency to balance value and costs

#### Communication

Secure, real-time data transmission between physical and digital spaces uses technologies like Wi-Fi, 4G/5G, and encryption. Data can be aggregated post-inspection for decision support.

#### Integration

Data integration into repositories (data lakes) involves cleansing, normalization, and combining with organizational data for analysis. Tasks include detecting/removing incorrect data, converting categorical values, and normalizing variables.

#### Analysis

Data analytics serves three types of data services:
- **Monitoring**: Descriptive (performance focus) or diagnostic (root cause analysis)
- **Prediction and Simulation**: Predict future behavior based on historical data
- **Optimization**: Prescriptive (performance improvement recommendations) or cognitive (autonomous AI-driven improvements)

#### Perception

Insights from data analysis are presented in various forms depending on their objectives, using compatible representations (2D, 3D, BIM, GIS) and interactive environments (virtual reality, augmented reality, dashboards).

####  Decision

Decisions consider DT information and existing criteria, constrained by factors like physical limitations, budgets, and timelines. The process may involve reviewing input data to improve decision-supporting information quality.

#### Action

This phase ensures that insights and decisions from the DT are implemented, impacting asset management and performance. Actions can include controlling physical assets, updating back-end systems, or creating action plans with human involvement.

## Digital Twinning throughout the Life Cycle of Physical Assets

Digital twinning spans four key phases in the life cycle of physical assets: 

**Planning and Design:**
- Assets start as ideas, evolving into detailed blueprints and potentially physical prototypes.
- Digital models and simulations reduce errors and risks, facilitating design optimizations and efficient permitting.
- Advanced tools like machine learning can optimize modular construction designs.

**Construction:**
- Transition from virtual to physical, where monitoring equipment and processes enhance safety, productivity, and quality.
- Digital modeling aids in site planning, progress tracking, and communication among stakeholders.
- Embedded sensors and initiatives like PointCloud4BIM improve quality verification and streamline invoicing.

**Use:**
- Focus on operation and maintenance, leveraging sensors for preventative decision-making and quicker responses.
- External data tools, like satellites and drones, optimize operations and expand knowledge of asset behavior.
- Automated processes enhance resource efficiency and reduce risks.

**End of Life:**
- Assets may undergo renovation, replacement, deactivation, or dismantling, with a focus on optimizing replacement timing and integrating dispersed information.
- Some assets retain value through historical significance or material reuse, improving economic performance and reducing environmental impact.
- Accurate material information and updated BIM models are crucial for efficient and safe end-of-life activities.

## Assessing the Level of Digital Twinning (LoDT)

Various models have been proposed to assess the maturity and complexity of digital twins, focusing on aspects like connectivity, collaboration, and hierarchical levels. However, existing models often lack clarity and comprehensiveness.

### UNI-TWIN—The Unified Digital Twinning Assessment Model

The proposed UNI-TWIN model for assessing the level of digital twinning of physical assets comprises nine dimensions: 
Each dimension has its own level of complexity, ranging from "1" (least complex) to "5+" (most complex).

![LoDT_Dimensions](https://github.com/maram77/Summer_Internship_2024/assets/85744265/0372450c-4082-4d2b-9c15-17ce7d98c3d9)

### Digital Twinning Dimensions

**Hierarchy:**
Hierarchy refers to the hierarchical level of the physical assets, from specific components to systems of systems, like city or national-level DT projects.

**Connection:**
Connection varies from no connection to fully automatic bidirectional connections between physical and digital spaces.

**Synchronization:**
Synchronization reflects the frequency of data updates in the digital space, ranging from single updates to continuous real-time updates.

**Geometric Representation:**
Geometric representation includes geometric information (shape, appearance) and non-geometric information (asset type, design specifications). 

**Non-Geometric Representation:**
Non-geometric information should meet the needs defined by the application's purpose. Agile access to data and mapping information requirements are crucial.

**Intelligence:**
Intelligence ranges from descriptive (what happened) to cognitive analysis (simulating human reasoning with AI), representing increasing complexity in data analysis.

**Interface:**
Interface levels range from no user interaction to multisensory interaction, enhancing decision-making quality.

**Accessibility:**
Accessibility ranges from single-user access to multiple users across various stakeholders, ensuring collaborative decision-making.

**Autonomy:**
Autonomy assesses the system's independence from human intervention, from no autonomy to high autonomy with limited human intervention.

**Connectivity:**
Connectivity between DTs allows for greater value by extracting more and better information. 


## Conclusion

The Levels of Digital Twinning (LoDT) framework offers a structured approach to understanding and implementing digital twins across various industries. By defining dimensions, the LoDT model provides a comprehensive assessment tool for evaluating digital twin maturity and complexity.


