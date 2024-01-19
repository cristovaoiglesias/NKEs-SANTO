# NKEs-SANTO
It has been recently proven that joint estimation of states and unshared parameters with an extended Kalman filter (JEKF) fails with some common conditions present in biomanufacturing [1]. 
This recent finding raises questions about the effectiveness of the unscented and cubature Kalman filters under these challenging conditions since they can estimate the system state more accurately than extended Kalman filters. 
Therefore, In the present work, we assess the potential of Joint estimation of states and unshared parameters with an unscented Kalman filter (JUKF) and cubature Kalman Filter (JCKF) on the same conditions that cause the JEKF failure.
Our empirical evaluation using a synthetic dataset shows that JUKF and JCKF do not fail like JEKF but are inefficient in estimating the unshared parameters.
Their performance only improved after using specific initial conditions for state error covariance matrix (\textbf{P}). However, in one of the studied cases, it caused unconventional behavior in the Kalman gain values.

[1] Iglesias, C.F., Jr.; Bolic, M. How Not to Make the Joint Extended Kalman Filter Fail with Unstructured Mechanistic Models. Sensors 2024, 24, 653. https://doi.org/10.3390/s24020653


## Supplementary Material  
[Link]( https://github.com/cristovaoiglesias/NKEs-SANTO/blob/main/Supplementary_Material_SDS2024.pdf)



## Code and Dataset

[Link](https://github.com/cristovaoiglesias/NKEs-SANTO/tree/main/Experiment)
