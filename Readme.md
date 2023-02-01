Developing equations for the Extended Kalman Filter(EKF) to find the unknown constant a


$$ x_{k+1} = ax_k + \psi_k $$




$$ y_k =  \sqrt{x^2_k+1}+v_k $$




$\psi_k \sim N(0,1)$

$v_k \sim N(0,1/2)$

$x_0 \sim N(1,2)$ (Initial estimate)


#Results
![download (1)](https://user-images.githubusercontent.com/89912646/216061740-b621e3ef-6fe5-4647-b014-92f2c37dd895.png)
