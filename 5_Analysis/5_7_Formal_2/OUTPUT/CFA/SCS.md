lavaan 0.6.15 ended normally after 37 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        30

  Number of observations                           218

Model Test User Model:
                                                      
  Test statistic                                94.042
  Degrees of freedom                                48
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              1312.967
  Degrees of freedom                                66
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.963
  Tucker-Lewis Index (TLI)                       0.949

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -4209.904
  Loglikelihood unrestricted model (H1)      -4162.883
                                                      
  Akaike (AIC)                                8479.807
  Bayesian (BIC)                              8581.342
  Sample-size adjusted Bayesian (SABIC)       8486.274

Root Mean Square Error of Approximation:

  RMSEA                                          0.066
  90 Percent confidence interval - lower         0.046
  90 Percent confidence interval - upper         0.086
  P-value H_0: RMSEA <= 0.050                    0.087
  P-value H_0: RMSEA >= 0.080                    0.133

Standardized Root Mean Square Residual:

  SRMR                                           0.046

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  UI =~                                                                 
    UI1               1.000                               0.925    0.735
    UI2               1.264    0.117   10.812    0.000    1.170    0.864
    UI3               1.209    0.113   10.659    0.000    1.119    0.794
  UC =~                                                                 
    UC1               1.000                               1.128    0.727
    UC2               1.188    0.110   10.783    0.000    1.340    0.799
    UC3               1.294    0.116   11.125    0.000    1.459    0.872
  DI =~                                                                 
    DI1               1.000                               1.361    0.817
    DI2               1.117    0.074   15.187    0.000    1.521    0.897
    DI3               1.124    0.076   14.820    0.000    1.531    0.872
  DC =~                                                                 
    DC1               1.000                               1.028    0.726
    DC2               1.161    0.126    9.236    0.000    1.193    0.788
    DC3               1.046    0.115    9.090    0.000    1.075    0.743

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  UI ~~                                                                 
    UC               -0.229    0.087   -2.637    0.008   -0.219   -0.219
    DI               -0.113    0.098   -1.155    0.248   -0.090   -0.090
    DC                0.069    0.078    0.884    0.377    0.073    0.073
  UC ~~                                                                 
    DI                0.746    0.142    5.249    0.000    0.486    0.486
    DC                0.264    0.100    2.647    0.008    0.228    0.228
  DI ~~                                                                 
    DC                0.568    0.127    4.470    0.000    0.406    0.406

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .UI1               0.730    0.090    8.094    0.000    0.730    0.460
   .UI2               0.466    0.101    4.640    0.000    0.466    0.254
   .UI3               0.731    0.108    6.747    0.000    0.731    0.369
   .UC1               1.136    0.135    8.418    0.000    1.136    0.472
   .UC2               1.019    0.146    6.998    0.000    1.019    0.362
   .UC3               0.669    0.141    4.751    0.000    0.669    0.239
   .DI1               0.926    0.114    8.120    0.000    0.926    0.333
   .DI2               0.559    0.101    5.516    0.000    0.559    0.195
   .DI3               0.737    0.113    6.536    0.000    0.737    0.239
   .DC1               0.947    0.128    7.408    0.000    0.947    0.473
   .DC2               0.868    0.145    5.982    0.000    0.868    0.379
   .DC3               0.938    0.133    7.060    0.000    0.938    0.448
    UI                0.856    0.146    5.845    0.000    1.000    1.000
    UC                1.272    0.218    5.821    0.000    1.000    1.000
    DI                1.853    0.261    7.099    0.000    1.000    1.000
    DC                1.057    0.192    5.514    0.000    1.000    1.000

