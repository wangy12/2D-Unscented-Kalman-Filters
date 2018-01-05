# Unscented Kalman Filter Project 

In this project utilize an Unscented Kalman Filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. Passing the project requires obtaining RMSE values that are lower that the tolerance outlined in the project rubric. 

[//]: # (Image References)
[image1]: ./results/data1.png 
[image2]: ./results/data2.png 

## Results

### Dataset 1

![alt text][image1]

### Dataset 2

![alt text][image2]

The px, py, vx, and vy RMSE are less than to the values [.09, .10, .40, .30].

## Compare with EKF (Dataset 1)

EKF: The RMSE values for one Monte Carlo run are RMSE[px, py, vx, vy] = [0.13, 0.73, 0.71, 1.83].
UKF: The RMSE values for one Monte Carlo run are RMSE[px, py, vx, vy] = [0.07, 0.08, 0.33, 0.22].
Therefore, UKF outperforms EKF in tracking performance (accuracy/RMSE) in this scenario.

## NIS

By analysing the output radar NIS, the NIS of radar measurements are between 0.35 and 7.81 in at least 80% of all radar update steps.


