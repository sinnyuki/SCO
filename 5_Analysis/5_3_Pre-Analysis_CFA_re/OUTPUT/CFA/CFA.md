lavaan 0.6.16 ended normally after 39 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        49

  Number of observations                           221

Model Test User Model:
                                                      
  Test statistic                               501.187
  Degrees of freedom                               204
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              2951.762
  Degrees of freedom                               231
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.891
  Tucker-Lewis Index (TLI)                       0.876

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -8152.583
  Loglikelihood unrestricted model (H1)      -7901.990
                                                      
  Akaike (AIC)                               16403.166
  Bayesian (BIC)                             16569.676
  Sample-size adjusted Bayesian (SABIC)      16414.393

Root Mean Square Error of Approximation:

  RMSEA                                          0.081
  90 Percent confidence interval - lower         0.072
  90 Percent confidence interval - upper         0.090
  P-value H_0: RMSEA <= 0.050                    0.000
  P-value H_0: RMSEA >= 0.080                    0.595

Standardized Root Mean Square Residual:

  SRMR                                           0.071

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                               1.284    0.789
    ASC2              0.841    0.077   10.931    0.000    1.080    0.701
    ASC3              0.702    0.074    9.444    0.000    0.902    0.619
    ASC4              0.954    0.081   11.799    0.000    1.225    0.747
    ASC5              1.209    0.090   13.486    0.000    1.553    0.832
  OSC =~                                                                
    OSC1              1.000                               1.382    0.812
    OSC2              0.941    0.077   12.184    0.000    1.300    0.750
    OSC3              0.745    0.077    9.700    0.000    1.029    0.625
    OSC4              0.726    0.078    9.296    0.000    1.004    0.603
    OSC5              0.495    0.071    6.973    0.000    0.684    0.468
    OSC6              0.968    0.080   12.148    0.000    1.339    0.748
  SCO =~                                                                
    ASC               1.000                               0.970    0.970
    OSC               1.077    0.101   10.661    0.000    0.971    0.971
  RD =~                                                                 
    RD1               1.000                               1.190    0.716
    RD2               1.114    0.103   10.849    0.000    1.325    0.777
    RD3               1.230    0.108   11.428    0.000    1.464    0.821
    RD4               1.057    0.106    9.983    0.000    1.257    0.713
    RD5               1.244    0.108   11.466    0.000    1.480    0.824
  POS =~                                                                
    POS1              1.000                               1.470    0.845
    POS2              1.032    0.065   15.789    0.000    1.517    0.877
    POS3              0.737    0.063   11.791    0.000    1.084    0.712
    POS4              0.711    0.070   10.098    0.000    1.046    0.632
    POS5              0.839    0.070   11.899    0.000    1.233    0.716
    POS6              0.648    0.064   10.127    0.000    0.953    0.634

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  SCO ~~                                                                
    RD                0.958    0.154    6.212    0.000    0.646    0.646
    POS               0.955    0.166    5.759    0.000    0.521    0.521
  RD ~~                                                                 
    POS               0.742    0.152    4.883    0.000    0.424    0.424

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              1.003    0.114    8.792    0.000    1.003    0.378
   .ASC2              1.205    0.127    9.514    0.000    1.205    0.508
   .ASC3              1.308    0.133    9.875    0.000    1.308    0.617
   .ASC4              1.189    0.129    9.203    0.000    1.189    0.442
   .ASC5              1.075    0.132    8.137    0.000    1.075    0.308
   .OSC1              0.988    0.118    8.336    0.000    0.988    0.341
   .OSC2              1.316    0.145    9.094    0.000    1.316    0.438
   .OSC3              1.656    0.169    9.818    0.000    1.656    0.610
   .OSC4              1.766    0.178    9.894    0.000    1.766    0.637
   .OSC5              1.663    0.163   10.210    0.000    1.663    0.781
   .OSC6              1.409    0.155    9.109    0.000    1.409    0.440
   .RD1               1.343    0.146    9.175    0.000    1.343    0.487
   .RD2               1.155    0.135    8.570    0.000    1.155    0.397
   .RD3               1.037    0.132    7.858    0.000    1.037    0.326
   .RD4               1.529    0.166    9.202    0.000    1.529    0.492
   .RD5               1.036    0.133    7.797    0.000    1.036    0.321
   .POS1              0.867    0.114    7.634    0.000    0.867    0.286
   .POS2              0.693    0.103    6.719    0.000    0.693    0.231
   .POS3              1.145    0.122    9.363    0.000    1.145    0.494
   .POS4              1.640    0.168    9.772    0.000    1.640    0.600
   .POS5              1.442    0.155    9.331    0.000    1.442    0.487
   .POS6              1.351    0.138    9.766    0.000    1.351    0.598
   .ASC               0.098    0.089    1.097    0.273    0.059    0.059
   .OSC               0.109    0.105    1.043    0.297    0.057    0.057
    SCO               1.552    0.247    6.286    0.000    1.000    1.000
    RD                1.416    0.240    5.897    0.000    1.000    1.000
    POS               2.161    0.287    7.534    0.000    1.000    1.000

