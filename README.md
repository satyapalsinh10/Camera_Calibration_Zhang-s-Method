# Camera Calibration by implementation Zhang's method 
Implementation of Zhang's camera calibration method from scratch to estimate the camera intrinsics and distortion parameters.


## Data
In order to estimate camera intrinsic parameters, the Zhang's method uses a checkerboard. The file checkerboard.pdf contains the calibration target that was utilized. The 'Calib_Img' folder contains 13 photos, which will be utilized for calibration.



### Reprojected corners

<img src="Results/Reprojected_corners/reprojected_corners1.png"  align="center" alt="Undistorted" length = "200" width="300"/>

## Results
                   
```
Distortion Coefficients:

[0.0125  -0.0125]

```

<div style="margin: 20px 0"></div>

```
Intrinsic matrix:                   

[[2464.4 0.3680 0763.8],             
 [  0    2441.1 1348.3],
 [  0      0       1  ]]
```


## Usage Guidelines:

Open the 'AutoCalib' directory on terminal and enter the commmand:

```
python3 Wrapper.py
```

Corners on original images and Reprojected images are stored in Results folder.

Please refer the report for details of the method followed and corresponding results.


## References

1. https://rbe549.github.io/fall2022/hw/hw1/
2. https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr98-71.pdf
