<!-- Readme.md is generated from Readme.org. Please edit that file -->


# Data Description

This repository contains data used in

-   Hellenkamp K, et al. (2018) Echocardiographic Estimation of Mean Pulmonary Artery Pressure: A Comparison of Different Approaches to Assign the Likelihood of Pulmonary Hypertension. Journal of the American Society of Echocardiography : official publication of the American Society of Echocardiography 31 (1):89-98. <10.1016/j.echo.2017.09.009>
-   Leha A, et al. A machine learning approach for the prediction of pulmonary hypertension, under review

It comprises data for 90 patients with invasively measured PAP within
24 hours after echocardiographic assessment.

There are 4 baseline variables

-   age [years]
-   sex
-   BMI (body mass index) [kg/m²]
-   BSA (body surface area) [m²]

and 21 echocardiographic measurements

-   IVSd [mm]
-   LVEDD [mm]
-   PW [mm]
-   LAD [mm]
-   EF <code>[%]</code>
-   RVD1 [mm]
-   RVD2 [mm]
-   RVD3 [mm]
-   RVenlargement <code>[0/1]</code>
-   TAPSE [mm]
-   RAPestimated [mmHg]
-   RAP15 (RAP >= 15) <code>[0/1]</code>
-   AS [0/1/2/3]
-   AR [0/1/2/3]
-   MS [0/1/2/3]
-   MR [0/1/2/3]
-   TR [0/1/2/3]
-   TRVmax [m/s]
-   TRVm [m/s]
-   PVAT [ms]
-   TRPm [mmHg]

The gold-standard (invasively obtained) outcome is given in

-   PAPm<sub>invasive</sub>
-   PH<sub>invasive</sub> (binarized at 25)

For reference, the established estimation according to Aduen J, et
al., Accuracy and precision of three echocardiographic methods for
estimating mean pulmonary artery pressure, <10.1378/chest.10-0126>,
is available in column

-   aduen


# Data Formats

The data set is available as R object (`RDS.RData`) and Excel table
(`xlsx`).


## Example Usage

The data can be loaded easily via

```R
## read data
dat <- readRDS("PH24.RDS.RData")
```

<div class="markdown">
<!&#x2013;
Local Variables:
 mode: gfm
 markdown-command: "marked"
End:
&#x2013;>

</div>
