
# Small Worlds

A research investigation into the database of the Brazilian aviation network.

## Loom Video
- [:camera: Loom Video with the study's main findings]()

## Notebook 
- [:file_folder: Jupyter notebook with brazilian air network investigation](./Project_U2P1.ipynb)

## Main Findings
- The Brazilian network exhibits a significant level of connectivity.
- The Southeast region demonstrates the highest degree of interconnectivity, while the Northeast region exhibits the lowest.
- Only five airports remain unconnected to the national network.
- The assortativity is low, indicating a tendency for regions to connect with one another rather than within themselves.


## Requirements:
- **Requirement 1**: Perform a study on the assortativity of the network, considering the REGION where the airport is located as an attribute. Generate both statically and interactive graph similar to the ones used in the classroom, taking into account the REGION of the airport.
    - [x] Assortativty by region
    - [x] Static plot
    - [x] Interactive plot
    
- **Requirement 2**: Carry out a bivariate analysis between the vertex degree and the average number of neighbors. Create a similar graph considering the Brazilian network and all its Regions (North, Northeast, South, Southeast, and Central-West). Report your main findings.
    - [x] Bivariate analysis
    - [x] Plot graph
    
- **Requirement 3**: Determine how many connected components exist in the Brazilian air network. Characterize each component: quantity, percentage by region.
    - [x] Connected components
    - [x] Characterization of each component
    
- **Requirement 4**: Create a simulated scenario where a trip with the following route is desired:
    1. City 1 (North) to City 2 (South)
    2. City 2 (South) to City 3 (Northeast)
    3. City 3 (Northeast) to City 4 (Central-West)
    4. City 4 (Central-West) to City 5 (Southeast)
   
    Using the concept of the shortest path, describe the journey taken and the number of routes used. Provide a cost estimate for this trip, including a simulation with dates and the airline company, ensuring that the period from the first trip to the last does not exceed 30 days.
    - [ ] Imaginary trip
    - [ ] Number of routes
    - [ ] Cost estimate
    
- **Requirement 5**: Conduct a study on the Clustering Coefficient considering the National Air Network, as well as the individual air sub-networks of each Region (North, Northeast, Central-West, South, and Southeast).
    - [x] Clustering coefficient Network
    - [x] Clustering coefficient for each region


