# carCalibration

## Table of Contents
1. Offline Table
  - Throttle Model
  - Brake Model
  
2. Online Model
  - Throttle Model
  - Brake Model
  
## Description
_carCalibration_ will show you how to build a data-driven longitudinal control system by machine-learning. 
  
## Dependency
- numpy >= 1.15.4
- pandas >= 0.22.0
- scipy >= 1.2.0
- tensorflow >= 1.7.0
- keras >= 2.1.6
- python3

###### if you wish to use matplotlib or plotly then you should use
- matplotlib >= 2.2.2
- plotly >= 2.5.1

## Usage

### Input CSV 
| %time | accel | brake | speed | steer | leftWheelSpeed | rightWheelSpeed | 
----- | ----- | ----- | ----- | ----- | -----| ----- |

- Prepare your csv File
- copy csv file under the data directory
- run the following command
`python src/main.py`

###### Output will be in the result directory

## References
https://arxiv.org/abs/1808.10134
