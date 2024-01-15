lavaan 0.6.16 ended normally after 46 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        60

  Number of observations                           303

Model Test User Model:
                                              Standard      Scaled
  Test Statistic                               824.508     710.065
  Degrees of freedom                               291         291
  P-value (Chi-square)                           0.000       0.000
  Scaling correction factor                                  1.161
    Yuan-Bentler correction (Mplus variant)                       

Model Test Baseline Model:

  Test statistic                              5349.336    4500.123
  Degrees of freedom                               325         325
  P-value                                        0.000       0.000
  Scaling correction factor                                  1.189

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.894       0.900
  Tucker-Lewis Index (TLI)                       0.881       0.888
                                                                  
  Robust Comparative Fit Index (CFI)                         0.902
  Robust Tucker-Lewis Index (TLI)                            0.890

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)             -12402.092  -12402.092
  Scaling correction factor                                  1.108
      for the MLR correction                                      
  Loglikelihood unrestricted model (H1)     -11989.838  -11989.838
  Scaling correction factor                                  1.152
      for the MLR correction                                      
                                                                  
  Akaike (AIC)                               24924.183   24924.183
  Bayesian (BIC)                             25147.007   25147.007
  Sample-size adjusted Bayesian (SABIC)      24956.719   24956.719

Root Mean Square Error of Approximation:

  RMSEA                                          0.078       0.069
  90 Percent confidence interval - lower         0.072       0.063
  90 Percent confidence interval - upper         0.084       0.075
  P-value H_0: RMSEA <= 0.050                    0.000       0.000
  P-value H_0: RMSEA >= 0.080                    0.286       0.001
                                                                  
  Robust RMSEA                                               0.074
  90 Percent confidence interval - lower                     0.067
  90 Percent confidence interval - upper                     0.081
  P-value H_0: Robust RMSEA <= 0.050                         0.000
  P-value H_0: Robust RMSEA >= 0.080                         0.089

Standardized Root Mean Square Residual:

  SRMR                                           0.073       0.073

Parameter Estimates:

  Standard errors                             Sandwich
  Information bread                           Observed
  Observed information based on                Hessian

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                               1.080    0.718
    ASC2              0.920    0.079   11.708    0.000    0.994    0.693
    ASC3              0.731    0.077    9.434    0.000    0.790    0.604
    ASC4              1.199    0.091   13.242    0.000    1.295    0.798
    ASC5              1.434    0.095   15.036    0.000    1.549    0.868
  OSC =~                                                                
    OSC1              1.000                               1.313    0.846
    OSC2              0.847    0.051   16.612    0.000    1.112    0.721
    OSC3              0.759    0.069   10.996    0.000    0.997    0.655
    OSC4              0.655    0.072    9.110    0.000    0.860    0.558
    OSC6              0.777    0.066   11.698    0.000    1.020    0.639
    OSC7              1.007    0.058   17.301    0.000    1.322    0.791
  SCO =~                                                                
    ASC               1.000                               0.968    0.968
    OSC               1.244    0.115   10.821    0.000    0.990    0.990
  RD =~                                                                 
    RD1               1.000                               1.189    0.739
    RD2               1.042    0.069   15.146    0.000    1.239    0.776
    RD3               0.906    0.075   12.074    0.000    1.077    0.714
    RD4               1.192    0.084   14.141    0.000    1.417    0.804
    RD5               1.177    0.080   14.641    0.000    1.398    0.827
  POS =~                                                                
    POS1              1.000                               1.025    0.741
    POS2              1.140    0.060   18.901    0.000    1.168    0.749
    POS3              1.136    0.088   12.869    0.000    1.164    0.862
    POS5              0.608    0.078    7.797    0.000    0.623    0.471
    POS6              1.143    0.086   13.261    0.000    1.171    0.813
  LS =~                                                                 
    LS1               1.000                               1.407    0.870
    LS2               0.889    0.047   18.889    0.000    1.251    0.849
    LS3               1.075    0.044   24.407    0.000    1.512    0.895
    LS4               0.935    0.054   17.364    0.000    1.316    0.754
    LS5               0.806    0.062   12.991    0.000    1.134    0.629

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  SCO ~~                                                                
    RD                0.312    0.095    3.286    0.001    0.251    0.251
    POS               0.326    0.090    3.637    0.000    0.304    0.304
    LS                0.220    0.104    2.114    0.035    0.149    0.149
  RD ~~                                                                 
    POS              -0.651    0.090   -7.203    0.000   -0.535   -0.535
    LS               -1.151    0.112  -10.312    0.000   -0.688   -0.688
  POS ~~                                                                
    LS                1.164    0.113   10.294    0.000    0.808    0.808

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              1.099    0.137    8.010    0.000    1.099    0.485
   .ASC2              1.068    0.109    9.784    0.000    1.068    0.520
   .ASC3              1.084    0.102   10.596    0.000    1.084    0.635
   .ASC4              0.954    0.101    9.451    0.000    0.954    0.363
   .ASC5              0.788    0.091    8.666    0.000    0.788    0.247
   .OSC1              0.685    0.080    8.610    0.000    0.685    0.284
   .OSC2              1.142    0.123    9.297    0.000    1.142    0.480
   .OSC3              1.324    0.136    9.761    0.000    1.324    0.571
   .OSC4              1.636    0.168    9.757    0.000    1.636    0.689
   .OSC6              1.511    0.144   10.476    0.000    1.511    0.592
   .OSC7              1.048    0.126    8.342    0.000    1.048    0.375
   .RD1               1.176    0.131    8.962    0.000    1.176    0.454
   .RD2               1.016    0.108    9.384    0.000    1.016    0.398
   .RD3               1.115    0.105   10.589    0.000    1.115    0.490
   .RD4               1.098    0.128    8.576    0.000    1.098    0.354
   .RD5               0.902    0.134    6.715    0.000    0.902    0.316
   .POS1              0.863    0.113    7.661    0.000    0.863    0.451
   .POS2              1.066    0.119    8.956    0.000    1.066    0.439
   .POS3              0.468    0.069    6.797    0.000    0.468    0.257
   .POS5              1.362    0.118   11.561    0.000    1.362    0.778
   .POS6              0.701    0.086    8.138    0.000    0.701    0.338
   .LS1               0.633    0.076    8.291    0.000    0.633    0.242
   .LS2               0.603    0.069    8.804    0.000    0.603    0.278
   .LS3               0.571    0.067    8.562    0.000    0.571    0.200
   .LS4               1.315    0.152    8.624    0.000    1.315    0.432
   .LS5               1.966    0.160   12.274    0.000    1.966    0.605
   .ASC               0.074    0.072    1.032    0.302    0.063    0.063
   .OSC               0.034    0.112    0.301    0.763    0.020    0.020
    SCO               1.093    0.163    6.711    0.000    1.000    1.000
    RD                1.413    0.169    8.342    0.000    1.000    1.000
    POS               1.050    0.139    7.528    0.000    1.000    1.000
    LS                1.979    0.166   11.947    0.000    1.000    1.000

