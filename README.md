# nyc_subway_network
use NYC MTA Subway GTFS to build up network

1. Network</br>
  -- Prepare data for nodes and links.ipynb</br>
  -- network_construction_criticality.ipynb</br>
  -- network_setup</br>
      -- stop_times_cleaned</br>
      -- stop_train</br>
      nodes:</br>
      -- sub_node	</br>
      -- master_master_node</br>
      edges:</br>
      -- waiting</br>
      -- duration_7-10am_weekday</br>
      -- transfer</br>
     
2. Duration</br>
  -- whole_network_duration</br>
  -- whole_network_duration_shortest_path.csv</br>


3. Duration Difference</br>
  remove one node:</br>
  --remove_one_node_duration_diff.csv.gz</br>
  remove two nodes:</br>
  -- remove_two_nodes_duration_diff.csv.gz</br>

4. Demand</br>
  -- demand.csv.gz
  -- od_demand_distribution_v2.csv

5.Criticality computation</br>
  -- one node criticality calculation.ipynb
  -- network_runtwo_nodes_removal_duration.ipynb
  -- delay_multiply_demand_one_node_removal.csv
  -- delay_multiply_demand_two_nodes_removal.csv

