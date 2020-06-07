# Occupancy Grid Mapping Algorithm

a robot equipped with eight sonar rangefinder sensors circulates in an environment to map it. This robot is provided with its exact poses at each timestamp. The code structure is as follows:

# Data Files

1. measurement.txt: The measurements from the sonar rangefinder sensors attached to the robot at each time stamp recorded over a period of 413 seconds. (timestamp, measurement 1:8).

2. poses.txt: The exact robot poses at each timestamp recorded over a period of 413 seconds. (timestamp, x, y, ϴ).

# Global Functions

1. inverseSensorModel(): The inverse sensor model for sonar rangefinder sensors.

2. occupancyGridMapping(): Implements Occupancy Grid Algorithm.


# Main Function

1. File Scan: Scanning both the measurement and poses files to retrieve the values. At each time stamp, the values are passed to the occupancy grid mapping function.

2. Display Map: After processing all the measurements and poses, the map is displayed.

# Final Result

![Final Result](Images/Map.png)
