lavaan 0.6.16 ended normally after 40 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        36

  Number of observations                           409

Model Test User Model:
                                                      
  Test statistic                               448.045
  Degrees of freedom                               100
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              3731.835
  Degrees of freedom                               120
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.904
  Tucker-Lewis Index (TLI)                       0.884

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)             -10581.667
  Loglikelihood unrestricted model (H1)     -10357.644
                                                      
  Akaike (AIC)                               21235.333
  Bayesian (BIC)                             21379.827
  Sample-size adjusted Bayesian (SABIC)      21265.593

Root Mean Square Error of Approximation:

  RMSEA                                          0.092
  90 Percent confidence interval - lower         0.084
  90 Percent confidence interval - upper         0.101
  P-value H_0: RMSEA <= 0.050                    0.000
  P-value H_0: RMSEA >= 0.080                    0.990

Standardized Root Mean Square Residual:

  SRMR                                           0.070

Parameter Estimates:

  Standard errors                            Bootstrap
  Number of requested bootstrap draws             5000
  Number of successful bootstrap draws            5000

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  RD =~                                                                 
    RD1               1.000                               1.230    0.747
    RD2               0.974    0.066   14.689    0.000    1.198    0.717
    RD3               0.742    0.075    9.913    0.000    0.912    0.549
    RD4               1.214    0.070   17.316    0.000    1.492    0.848
    RD5               1.117    0.074   14.998    0.000    1.373    0.824
  POS =~                                                                
    POS1              1.000                               1.144    0.771
    POS2              1.007    0.051   19.709    0.000    1.151    0.785
    POS3              1.039    0.075   13.816    0.000    1.189    0.831
    POS5              0.672    0.068    9.854    0.000    0.769    0.538
    POS6              0.913    0.081   11.266    0.000    1.044    0.757
  LS =~                                                                 
    LS1               1.000                               1.217    0.800
    LS2               0.985    0.054   18.334    0.000    1.199    0.845
    LS3               1.096    0.058   18.907    0.000    1.334    0.853
    LS4               0.984    0.059   16.651    0.000    1.198    0.710
    LS5               0.906    0.068   13.276    0.000    1.103    0.641
  RD =~                                                                 
    SCD       (a1)    0.706    0.099    7.099    0.000    0.868    0.531
  POS =~                                                                
    SCD       (a2)   -0.247    0.115   -2.144    0.032   -0.282   -0.173
  LS =~                                                                 
    RD        (b1)   -0.723    0.060  -12.087    0.000   -0.716   -0.716
    POS       (b2)    0.662    0.055   11.952    0.000    0.705    0.705
    SCD        (c)    0.462    0.130    3.543    0.000    0.563    0.345

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .RD1               1.201    0.121    9.944    0.000    1.201    0.443
   .RD2               1.354    0.135   10.006    0.000    1.354    0.486
   .RD3               1.928    0.136   14.171    0.000    1.928    0.698
   .RD4               0.866    0.099    8.761    0.000    0.866    0.280
   .RD5               0.892    0.125    7.113    0.000    0.892    0.321
   .POS1              0.893    0.127    7.037    0.000    0.893    0.406
   .POS2              0.827    0.101    8.162    0.000    0.827    0.384
   .POS3              0.635    0.074    8.621    0.000    0.635    0.310
   .POS5              1.450    0.106   13.643    0.000    1.450    0.710
   .POS6              0.813    0.099    8.203    0.000    0.813    0.427
   .LS1               0.831    0.112    7.432    0.000    0.831    0.359
   .LS2               0.574    0.053   10.902    0.000    0.574    0.285
   .LS3               0.665    0.067    9.962    0.000    0.665    0.272
   .LS4               1.408    0.111   12.709    0.000    1.408    0.495
   .LS5               1.741    0.131   13.244    0.000    1.741    0.589
   .SCD               2.193    0.139   15.737    0.000    2.193    0.822
   .RD                0.738    0.122    6.044    0.000    0.488    0.488
   .POS               0.659    0.103    6.395    0.000    0.504    0.504
    LS                1.482    0.141   10.492    0.000    1.000    1.000

Defined Parameters:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
    IE_RD            -0.510    0.085   -6.007    0.000   -0.621   -0.380
    IE_POS           -0.163    0.079   -2.076    0.038   -0.199   -0.122

