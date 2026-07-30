# AI-Based Flood Prediction and Digital Twin Visualization System

## Overview
This project focuses on flood prediction and Digital Twin visualization using Python and CesiumJS.

## Objectives
- Predict flood risk
- Estimate flood intensity
- Visualize flood-prone regions in 3D
- Support disaster preparedness

## Technologies
- Python
- CesiumJS
- Node.js

## Week 1–2 Progress
- Literature review completed
- Status report prepared
- Presentation completed
- Initial project planning completed
## Week 5–6 Progress

### Activities Completed

* Investigated and evaluated potential datasets required for flood prediction.
* Explored data sources related to rainfall, water levels, and environmental conditions.
* Conducted initial testing to understand how the selected datasets can be processed and utilized within the proposed system.
* Performed preliminary implementation and execution of the data-processing workflow.

### Challenges Encountered

* Several errors and inconsistencies were identified during data processing and system testing.
* Issues related to data formatting, integration, and execution were observed and documented for further investigation.

### Next Steps

* Resolve the identified errors and improve data handling procedures.
* Continue testing the datasets to ensure reliable operation of the flood prediction system.
* Refine the implementation based on the findings from the initial experiments.
* Prepare a detailed progress report for the next project milestone.
---

# Week 7–8 Progress

## Activities Completed
The primary focus during Weeks 7–8 was the implementation and testing of the Python backend for the flood prediction system.

### Backend Development
- Implemented live data ingestion for retrieving environmental data.
- Developed data fault filtering to remove invalid or inconsistent data.
- Implemented decoupled output to support future integration with the CesiumJS frontend.

## Testing and Validation
- Successfully tested the backend implementation multiple times.
- Identified and corrected several errors to improve system stability and reliability.

## Challenges Encountered
The following issues were encountered during development:

1. Package name configuration errors.
2. Trailing directory causing HTTP 404 errors.
3. Loop processing latency.
4. Server bot-block restrictions during live data retrieval.

## Next Development Phase
- Develop the CesiumJS frontend.
- Integrate the Python backend with CesiumJS.
- Develop the 3D Digital Twin visualization.
# Week 9–10 Progress

## Activities Completed

The primary focus during Weeks 9–10 was the development of the front-end component using **CesiumJS** for the Digital Twin visualization platform.

### Front-End Development

- Continued the implementation of the CesiumJS web platform.
- Modified and refined the source code through multiple iterations to achieve the required 3D globe visualization for the project.
- Performed repeated testing to evaluate the functionality and performance of the front-end application.
- Updated the implementation based on testing results to improve the visualization and overall system behaviour.

## Testing and Validation

Multiple rounds of testing were carried out throughout the development process. Several unsuccessful attempts were encountered during testing, requiring different coding approaches and further refinement of the implementation before achieving the expected behaviour.

## Challenges Encountered

The following issues were identified during the development and testing phase:

1. Blank pages displayed on the CesiumJS web application.
2. Server request rejection during data retrieval.
3. Specific name of the cities were not displayed correctly on the 3D globe.
4. Multiple code iterations were required to resolve front-end implementation issues.

## Next Development Phase

The next stage of development will focus on improving the CesiumJS front-end to provide a more refined and structured 3D Digital Twin visualization. Planned enhancements include:

- Displaying specific name of the cities.
- Showing real-time water level information.
- Displaying the predicted probability of future flooding.
- Improving the overall visualization and user interaction of the Digital Twin environment.
# Week 11–12 Progress

## Activities Completed

The primary focus during Weeks 11–12 was the continued development and refinement of the CesiumJS frontend for the Digital Twin visualization platform.

### Front-End Development

- Developed a structured CesiumJS application to display a 3D interactive globe.
- Implemented visualization of specific cities along with their current water level information.
- Integrated flood prediction by considering multiple environmental factors, including:
  - Water level
  - Probability of rainfall
  - Rainfall intensity
  - Additional environmental parameters affecting flood occurrence
- Expanded the prediction model by incorporating factors commonly considered by meteorologists, including:
  - Wind speed
  - Drainage rate
  - Soil water absorption capacity
- Improved the frontend to provide a more informative visualization of flood risk based on the changing environmental conditions.

## Testing and Validation

- Conducted regular testing at different time intervals to verify the dynamic behaviour of the system.
- Confirmed that flood risk values change automatically whenever the environmental parameters are updated.
- Observed that increases or decreases in water level and other influencing factors directly affect the predicted flood risk.
- Successfully verified that the frontend correctly reflects changing environmental conditions through multiple test iterations.

## Challenges Encountered

The following issues were encountered during development:

1. Coding errors while integrating the CesiumJS 3D globe.
2. Frontend rendering inconsistencies during implementation.
3. Integration issues while combining multiple environmental parameters into the visualization.

These issues were investigated and successfully resolved through debugging and code refinement.

## Next Development Phase

- Incorporate additional environmental factors to improve flood prediction accuracy.
- Enhance the flood intensity prediction model by refining the weighting of influencing parameters.
- Continue improving the CesiumJS interface to provide a more detailed and realistic Digital Twin visualization.
- Improve the accuracy of the predicted flood probability percentage through further testing and optimisation.
