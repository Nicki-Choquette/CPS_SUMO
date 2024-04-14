All time-based TLS currently assume cars are going 30 mph (Note: this needs to be fixed based on actual speed limits in simulation)

# 3-way (T and Y intersections)

# 4-ways (crossroads and X-intersection)

Total cycle time = 4 * speed limit in mph

Yellow light phase = 1 second for every 10 mph of the speed limit

Vehicle priorities: allows ~10 seconds before yellow light where pedestrians are not allowed to walk. 

Pedestrian priorities: allows for ~10 second leading pedestrian interval (LPI) that gives pedestrians the opportunity to enter the crosswalk at an intersection before vehicles are given a green indication (currently allows cars to go straight, as it does not interfere with pedestrian path)

# 5-way