lavaan 0.6.16 ended normally after 37 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        33

  Number of observations                           409

Model Test User Model:
                                              Standard      Scaled
  Test Statistic                               388.866     336.012
  Degrees of freedom                                87          87
  P-value (Chi-square)                           0.000       0.000
  Scaling correction factor                                  1.157
    Yuan-Bentler correction (Mplus variant)                       

Model Test Baseline Model:

  Test statistic                              3614.901    2924.342
  Degrees of freedom                               105         105
  P-value                                        0.000       0.000
  Scaling correction factor                                  1.236

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.914       0.912
  Tucker-Lewis Index (TLI)                       0.896       0.893
                                                                  
  Robust Comparative Fit Index (CFI)                         0.917
  Robust Tucker-Lewis Index (TLI)                            0.900

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -9828.024   -9828.024
  Scaling correction factor                                  1.181
      for the MLR correction                                      
  Loglikelihood unrestricted model (H1)      -9633.591   -9633.591
  Scaling correction factor                                  1.164
      for the MLR correction                                      
                                                                  
  Akaike (AIC)                               19722.049   19722.049
  Bayesian (BIC)                             19854.501   19854.501
  Sample-size adjusted Bayesian (SABIC)      19749.787   19749.787

Root Mean Square Error of Approximation:

  RMSEA                                          0.092       0.084
  90 Percent confidence interval - lower         0.083       0.075
  90 Percent confidence interval - upper         0.102       0.093
  P-value H_0: RMSEA <= 0.050                    0.000       0.000
  P-value H_0: RMSEA >= 0.080                    0.984       0.761
                                                                  
  Robust RMSEA                                               0.090
  90 Percent confidence interval - lower                     0.080
  90 Percent confidence interval - upper                     0.100
  P-value H_0: Robust RMSEA <= 0.050                         0.000
  P-value H_0: Robust RMSEA >= 0.080                         0.949

Standardized Root Mean Square Residual:

  SRMR                                           0.070       0.070

Parameter Estimates:

  Standard errors                             Sandwich
  Information bread                           Observed
  Observed information based on                Hessian

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  RD =~                                                                 
    RD1               1.000                               1.205    0.732
    RD2               0.988    0.067   14.773    0.000    1.190    0.713
    RD3               0.767    0.076   10.126    0.000    0.924    0.556
    RD4               1.241    0.070   17.804    0.000    1.495    0.850
    RD5               1.150    0.075   15.346    0.000    1.386    0.832
  POS =~                                                                
    POS1              1.000                               1.139    0.768
    POS2              1.004    0.049   20.457    0.000    1.143    0.779
    POS3              1.049    0.077   13.685    0.000    1.194    0.835
    POS5              0.671    0.066   10.155    0.000    0.764    0.535
    POS6              0.922    0.083   11.098    0.000    1.050    0.761
  LS =~                                                                 
    LS1               1.000                               1.217    0.801
    LS2               0.986    0.053   18.630    0.000    1.201    0.847
    LS3               1.097    0.056   19.498    0.000    1.336    0.855
    LS4               0.989    0.059   16.712    0.000    1.204    0.714
    LS5               0.906    0.067   13.493    0.000    1.103    0.642

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  RD ~~                                                                 
    POS              -0.795    0.096   -8.263    0.000   -0.579   -0.579
    LS               -1.038    0.101  -10.308    0.000   -0.707   -0.707
  POS ~~                                                                
    LS                0.964    0.094   10.302    0.000    0.695    0.695

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .RD1               1.260    0.121   10.413    0.000    1.260    0.465
   .RD2               1.371    0.140    9.811    0.000    1.371    0.492
   .RD3               1.905    0.139   13.715    0.000    1.905    0.690
   .RD4               0.857    0.098    8.716    0.000    0.857    0.277
   .RD5               0.855    0.127    6.737    0.000    0.855    0.308
   .POS1              0.904    0.131    6.905    0.000    0.904    0.411
   .POS2              0.846    0.105    8.063    0.000    0.846    0.393
   .POS3              0.621    0.072    8.601    0.000    0.621    0.304
   .POS5              1.457    0.106   13.722    0.000    1.457    0.714
   .POS6              0.800    0.100    7.963    0.000    0.800    0.420
   .LS1               0.831    0.111    7.482    0.000    0.831    0.359
   .LS2               0.570    0.053   10.656    0.000    0.570    0.283
   .LS3               0.659    0.066    9.955    0.000    0.659    0.270
   .LS4               1.393    0.110   12.677    0.000    1.393    0.490
   .LS5               1.740    0.133   13.120    0.000    1.740    0.588
    RD                1.452    0.164    8.876    0.000    1.000    1.000
    POS               1.297    0.148    8.738    0.000    1.000    1.000
    LS                1.482    0.142   10.433    0.000    1.000    1.000

