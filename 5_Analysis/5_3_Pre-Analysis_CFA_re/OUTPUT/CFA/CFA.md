lavaan 0.6.16 ended normally after 39 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        47

  Number of observations                           221

Model Test User Model:
                                                      
  Test statistic                               418.656
  Degrees of freedom                               184
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              2772.376
  Degrees of freedom                               210
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.908
  Tucker-Lewis Index (TLI)                       0.895

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -7776.296
  Loglikelihood unrestricted model (H1)      -7566.968
                                                      
  Akaike (AIC)                               15646.592
  Bayesian (BIC)                             15806.305
  Sample-size adjusted Bayesian (SABIC)      15657.360

Root Mean Square Error of Approximation:

  RMSEA                                          0.076
  90 Percent confidence interval - lower         0.066
  90 Percent confidence interval - upper         0.086
  P-value H_0: RMSEA <= 0.050                    0.000
  P-value H_0: RMSEA >= 0.080                    0.252

Standardized Root Mean Square Residual:

  SRMR                                           0.065

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                               1.285    0.789
    ASC2              0.840    0.077   10.925    0.000    1.079    0.701
    ASC3              0.702    0.074    9.448    0.000    0.902    0.619
    ASC4              0.954    0.081   11.813    0.000    1.226    0.747
    ASC5              1.209    0.090   13.496    0.000    1.553    0.832
  OSC =~                                                                
    OSC1              1.000                               1.381    0.811
    OSC2              0.942    0.077   12.185    0.000    1.301    0.750
    OSC3              0.745    0.077    9.693    0.000    1.029    0.625
    OSC4              0.727    0.078    9.296    0.000    1.004    0.603
    OSC5              0.495    0.071    6.965    0.000    0.683    0.468
    OSC6              0.969    0.080   12.135    0.000    1.338    0.748
  SCO =~                                                                
    ASC               1.000                               0.973    0.973
    OSC               1.069    0.100   10.657    0.000    0.968    0.968
  RD =~                                                                 
    RD1               1.000                               1.192    0.718
    RD2               1.112    0.102   10.868    0.000    1.326    0.777
    RD3               1.226    0.107   11.427    0.000    1.461    0.819
    RD4               1.057    0.106   10.017    0.000    1.260    0.714
    RD5               1.241    0.108   11.484    0.000    1.480    0.824
  POS =~                                                                
    POS1              1.000                               1.497    0.860
    POS2              1.018    0.063   16.054    0.000    1.523    0.880
    POS3              0.732    0.060   12.102    0.000    1.095    0.719
    POS5              0.791    0.069   11.388    0.000    1.185    0.688
    POS6              0.637    0.062   10.217    0.000    0.953    0.634

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  SCO ~~                                                                
    RD                0.963    0.155    6.226    0.000    0.646    0.646
    POS               0.947    0.167    5.662    0.000    0.506    0.506
  RD ~~                                                                 
    POS               0.694    0.152    4.576    0.000    0.389    0.389

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              1.002    0.114    8.795    0.000    1.002    0.378
   .ASC2              1.207    0.127    9.520    0.000    1.207    0.509
   .ASC3              1.309    0.132    9.877    0.000    1.309    0.617
   .ASC4              1.188    0.129    9.204    0.000    1.188    0.442
   .ASC5              1.076    0.132    8.145    0.000    1.076    0.308
   .OSC1              0.990    0.119    8.338    0.000    0.990    0.342
   .OSC2              1.314    0.145    9.084    0.000    1.314    0.437
   .OSC3              1.656    0.169    9.816    0.000    1.656    0.610
   .OSC4              1.765    0.178    9.891    0.000    1.765    0.636
   .OSC5              1.664    0.163   10.209    0.000    1.664    0.781
   .OSC6              1.409    0.155    9.105    0.000    1.409    0.440
   .RD1               1.338    0.146    9.161    0.000    1.338    0.485
   .RD2               1.155    0.135    8.562    0.000    1.155    0.397
   .RD3               1.045    0.133    7.881    0.000    1.045    0.329
   .RD4               1.523    0.166    9.186    0.000    1.523    0.490
   .RD5               1.037    0.133    7.792    0.000    1.037    0.321
   .POS1              0.787    0.112    7.011    0.000    0.787    0.260
   .POS2              0.674    0.106    6.338    0.000    0.674    0.225
   .POS3              1.120    0.121    9.259    0.000    1.120    0.483
   .POS5              1.559    0.165    9.465    0.000    1.559    0.526
   .POS6              1.350    0.139    9.734    0.000    1.350    0.598
   .ASC               0.087    0.089    0.978    0.328    0.053    0.053
   .OSC               0.121    0.105    1.159    0.246    0.064    0.064
    SCO               1.563    0.248    6.308    0.000    1.000    1.000
    RD                1.421    0.241    5.909    0.000    1.000    1.000
    POS               2.241    0.291    7.715    0.000    1.000    1.000

