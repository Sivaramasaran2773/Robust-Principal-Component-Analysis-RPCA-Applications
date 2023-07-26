# Robust-Principal-Component-Analysis-RPCA-Applications
We have discussed two applications related to RPCA in this repository: one in the area of video surveillance, where our methodology allows for the detection of objects in a cluttered background, and another in the area of recovering corrupted images via low-rank representation learning.

## Recovering corrupted images via low-rank representation learning:

Reconstruct a corrupted image by applying RobustPCA to overlapping patches. The low-rank component represents the filled-in regions, while the sparse component captures the corrupted or missing parts. The final recovered image combines the reconstructed regions with the original corrupted areas.

![image](https://github.com/Sivaramasaran2773/Robust-Principal-Component-Analysis-RPCA-Applications/assets/96780921/c7901836-bdba-49b8-b150-ca5da673a634)


## Video decomposition: Separating foreground from background in the video:
Given a sequence of surveillance video frames, we need to identify activities that stand out from the background. We stack the video frames as columns of a matrix M, then the low-rank component L0 naturally corresponds to the stationary background and the sparse component S0 captures the moving objects in the foreground. 

https://github.com/Sivaramasaran2773/Robust-Principal-Component-Analysis-RPCA-Applications/assets/96780921/cf4d9020-b486-43de-b3e4-e0eb76bb8112

