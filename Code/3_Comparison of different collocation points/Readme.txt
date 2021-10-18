In this study, we find that the concentration gradient of both the electrolyte and particle surface is increased when approaching the cathode(anode)/separator interface. Therefore, it is reasonable to set more collocation nodes near the cathode/separator interface and the anode/separator interface by adjusting the value of α/β.
In this code, the battery is discharged using 10C constant current. You can choose different types of collocation nodes by setting the value of ‘setalpha’ (i.e., α) and ‘setbeta’ (i.e., β).
In ‘Supplementary Note 2. Determining the optimal value of α and β’, we give the RMSE of voltage under different types of collocation points in table S2 and S3.
Using this code, you can get the similar results in table S3.
If you want to get the RMSE of voltage using Chebyshev collocation nodes, set setalpha=0.5 and setbeta=0.5. 
If you want to get the RMSE of voltage using α(β)=1 collocation nodes, set setalpha=1 and setbeta=0.
