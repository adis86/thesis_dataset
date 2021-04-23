## Introduction to the dataset

The ability of nodes of a low-power wireless sensor network (WSN) to reliably communicate is affected when co-located with other interfering wireless systems. Interference mitigation techniques found in the literature mostly focus on the interference sources. In this work, we take a different look at interference, specifically from a WSN node’s perspective and our experiments focus on characterising this interference in two different indoor environments. The dataset we provide consists of the timestamps of interference arrivals as perceived by a TMote Sky sensor node. 

The dataset we provide consists of traces from three measurement campaigns in two different indoor environments, OFFICE, an office building, and HOME, a shared apartment in a student dormitory. During the measurement campaigns, we collected timestamps of interference arrivals detected by the sensor nodes. Although the sensor node platform we used can be deemed obsolete, the measurements are valid for all contemporary radios as the Clear Channel Assessment (CCA) threshold was set to −77 dBm in the sensor node.

## We collected traces in three measurement campaigns: FIRST, SECOND and THIRD. 

Each file in the dataset is saved as a CSV file. The name of a sample file is in the format of "ENVIRONMENT_CAMPAIGN_SETTING_DATA.csv". For example, a sample file "OFFICE_FIRST_ch18 _timestamps.csv" means that this set of timestamps was collected in the OFFICE environment during the first campaign on IEEE 802.15.4 channel 18. 

### FIRST:

- 3 nodes
- OFFICE environment
- same location
- channels: 13, 18, 23
- duration: 24 hours

### SECOND: 

- 3 nodes
- OFFICE ENVIRONMENT	
- 3 different locations
- same channel 18
- duration: 24 hours

### THIRD:

- 1 node
- 2 different environments: OFFICE and HOME
- channel 18
- duration: 2 weeks


## What is included?

- timestamps of interference arrivals as perceived by TMote Sky sensor nodes. 

