lavaan 0.6.16 ended normally after 44 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        59

  Number of observations                           303

Model Test User Model:
                                                      
  Test statistic                               824.835
  Degrees of freedom                               292
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              5349.336
  Degrees of freedom                               325
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.894
  Tucker-Lewis Index (TLI)                       0.882

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)             -12402.255
  Loglikelihood unrestricted model (H1)     -11989.838
                                                      
  Akaike (AIC)                               24922.511
  Bayesian (BIC)                             25141.621
  Sample-size adjusted Bayesian (SABIC)      24954.504

Root Mean Square Error of Approximation:

  RMSEA                                          0.078
  90 Percent confidence interval - lower         0.071
  90 Percent confidence interval - upper         0.084
  P-value H_0: RMSEA <= 0.050                    0.000
  P-value H_0: RMSEA >= 0.080                    0.269

Standardized Root Mean Square Residual:

  SRMR                                           0.074

Parameter Estimates:

  Standard errors                            Bootstrap
  Number of requested bootstrap draws             5000
  Number of successful bootstrap draws            5000

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                               1.077    0.717
    ASC2              0.920    0.081   11.416    0.000    0.991    0.692
    ASC3              0.731    0.078    9.317    0.000    0.787    0.603
    ASC4              1.199    0.094   12.807    0.000    1.291    0.797
    ASC5              1.434    0.098   14.644    0.000    1.545    0.867
  OSC =~                                                                
    OSC1              1.000                               1.309    0.845
    OSC2              0.847    0.052   16.152    0.000    1.109    0.720
    OSC3              0.759    0.069   10.923    0.000    0.994    0.654
    OSC4              0.655    0.073    8.983    0.000    0.857    0.557
    OSC6              0.777    0.068   11.486    0.000    1.017    0.638
    OSC7              1.007    0.059   17.097    0.000    1.318    0.790
  SCO =~                                                                
    ASC               1.000                               0.968    0.968
    OSC               1.244    0.119   10.466    0.000    0.990    0.990
  RD =~                                                                 
    RD1               1.000                               1.189    0.739
    RD2               1.040    0.068   15.230    0.000    1.237    0.775
    RD3               0.904    0.076   11.891    0.000    1.075    0.713
    RD4               1.192    0.086   13.934    0.000    1.418    0.805
    RD5               1.177    0.081   14.538    0.000    1.400    0.828
  POS =~                                                                
    POS1              1.000                               1.022    0.739
    POS2              1.139    0.060   18.884    0.000    1.165    0.747
    POS3              1.141    0.086   13.197    0.000    1.166    0.864
    POS5              0.607    0.078    7.767    0.000    0.621    0.469
    POS6              1.145    0.087   13.116    0.000    1.171    0.814
  LS =~                                                                 
    LS1               1.000                               1.408    0.871
    LS2               0.888    0.048   18.595    0.000    1.250    0.849
    LS3               1.075    0.045   24.055    0.000    1.513    0.895
    LS4               0.935    0.055   17.033    0.000    1.316    0.754
    LS5               0.805    0.063   12.703    0.000    1.134    0.629
  RD =~                                                                 
    SCO       (a1)    0.577    0.083    6.925    0.000    0.659    0.659
  POS =~                                                                
    SCO       (a2)    0.508    0.156    3.263    0.001    0.498    0.498
  LS =~                                                                 
    RD        (b1)   -0.579    0.055  -10.540    0.000   -0.686   -0.686
    POS       (b2)    0.586    0.044   13.190    0.000    0.806    0.806
    SCO        (c)    0.149    0.120    1.239    0.215    0.201    0.201

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              1.099    0.139    7.911    0.000    1.099    0.487
   .ASC2              1.068    0.109    9.815    0.000    1.068    0.521
   .ASC3              1.084    0.103   10.497    0.000    1.084    0.636
   .ASC4              0.954    0.101    9.472    0.000    0.954    0.364
   .ASC5              0.788    0.092    8.541    0.000    0.788    0.248
   .OSC1              0.685    0.080    8.601    0.000    0.685    0.285
   .OSC2              1.142    0.124    9.232    0.000    1.142    0.482
   .OSC3              1.324    0.137    9.669    0.000    1.324    0.573
   .OSC4              1.636    0.168    9.740    0.000    1.636    0.690
   .OSC6              1.511    0.144   10.498    0.000    1.511    0.594
   .OSC7              1.048    0.127    8.275    0.000    1.048    0.376
   .RD1               1.175    0.133    8.829    0.000    1.175    0.454
   .RD2               1.021    0.108    9.425    0.000    1.021    0.400
   .RD3               1.118    0.106   10.600    0.000    1.118    0.492
   .RD4               1.095    0.128    8.542    0.000    1.095    0.353
   .RD5               0.897    0.134    6.719    0.000    0.897    0.314
   .POS1              0.867    0.109    7.973    0.000    0.867    0.454
   .POS2              1.073    0.115    9.319    0.000    1.073    0.442
   .POS3              0.462    0.065    7.155    0.000    0.462    0.254
   .POS5              1.365    0.116   11.714    0.000    1.365    0.780
   .POS6              0.701    0.087    8.059    0.000    0.701    0.338
   .LS1               0.629    0.075    8.361    0.000    0.629    0.241
   .LS2               0.605    0.068    8.859    0.000    0.605    0.279
   .LS3               0.570    0.066    8.629    0.000    0.570    0.199
   .LS4               1.313    0.152    8.642    0.000    1.313    0.431
   .LS5               1.965    0.161   12.223    0.000    1.965    0.605
   .ASC               0.074    0.074    0.994    0.320    0.064    0.064
   .OSC               0.034    0.116    0.290    0.772    0.020    0.020
   .SCO               0.718    0.118    6.066    0.000    0.661    0.661
   .RD                0.749    0.121    6.181    0.000    0.530    0.530
   .POS               0.366    0.073    5.005    0.000    0.350    0.350
    LS                1.982    0.170   11.643    0.000    1.000    1.000

Defined Parameters:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
    IE_RD            -0.334    0.059   -5.636    0.000   -0.452   -0.452
    IE_POS            0.297    0.092    3.232    0.001    0.402    0.402

