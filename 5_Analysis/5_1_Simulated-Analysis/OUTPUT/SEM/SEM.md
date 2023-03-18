lavaan 0.6.13 ended normally after 48 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        59

  Number of observations                           400

Model Test User Model:
                                                      
  Test statistic                               992.814
  Degrees of freedom                               292
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                             10460.352
  Degrees of freedom                               325
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.931
  Tucker-Lewis Index (TLI)                       0.923

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)             -11772.834
  Loglikelihood unrestricted model (H1)     -11276.427
                                                      
  Akaike (AIC)                               23663.668
  Bayesian (BIC)                             23899.165
  Sample-size adjusted Bayesian (SABIC)      23711.954

Root Mean Square Error of Approximation:

  RMSEA                                          0.077
  90 Percent confidence interval - lower         0.072
  90 Percent confidence interval - upper         0.083
  P-value H_0: RMSEA <= 0.050                    0.000
  P-value H_0: RMSEA >= 0.080                    0.219

Standardized Root Mean Square Residual:

  SRMR                                           0.143

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                               0.917    0.828
    ASC2              1.017    0.048   21.224    0.000    0.933    0.851
    ASC3              0.994    0.050   20.048    0.000    0.911    0.821
    ASC4              0.995    0.050   19.849    0.000    0.913    0.816
    ASC5              0.971    0.051   19.190    0.000    0.890    0.798
  OSC =~                                                                
    OSC1              1.000                               0.935    0.829
    OSC2              0.977    0.048   20.498    0.000    0.913    0.831
    OSC3              0.977    0.048   20.295    0.000    0.913    0.826
    OSC4              0.980    0.048   20.247    0.000    0.916    0.825
    OSC5              0.975    0.048   20.245    0.000    0.911    0.824
    OSC6              0.948    0.048   19.760    0.000    0.886    0.812
  SCO =~                                                                
    ASC               1.000                               0.989    0.989
    OSC               1.036    0.058   17.987    0.000    1.006    1.006
  RD =~                                                                 
    RD1               1.000                               1.081    0.846
    RD2               1.056    0.044   24.122    0.000    1.141    0.900
    RD3               0.995    0.044   22.749    0.000    1.076    0.871
    RD4               1.020    0.043   23.488    0.000    1.102    0.887
    RD5               1.026    0.044   23.207    0.000    1.109    0.881
  POS =~                                                                
    POS1              1.000                               1.072    0.844
    POS2              1.053    0.045   23.379    0.000    1.129    0.889
    POS3              1.048    0.045   23.280    0.000    1.123    0.886
    POS4              0.999    0.047   21.228    0.000    1.071    0.840
    POS5              1.022    0.044   23.086    0.000    1.096    0.882
  LS =~                                                                 
    LS1               1.000                               0.809    0.835
    LS2               0.962    0.055   17.520    0.000    0.778    0.774
    LS3               0.910    0.057   15.846    0.000    0.736    0.719
    LS4               0.980    0.055   17.782    0.000    0.792    0.782
    LS5               0.975    0.056   17.472    0.000    0.788    0.772
  RD =~                                                                 
    SCO               0.502    0.054    9.212    0.000    0.598    0.598
  POS =~                                                                
    SCO               0.541    0.054    9.946    0.000    0.639    0.639
  LS =~                                                                 
    RD               -0.878    0.070  -12.568    0.000   -0.657   -0.657
    POS               0.837    0.070   12.012    0.000    0.631    0.631
    SCO              -0.016    0.082   -0.200    0.842   -0.015   -0.015

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              0.387    0.031   12.667    0.000    0.387    0.315
   .ASC2              0.330    0.027   12.328    0.000    0.330    0.275
   .ASC3              0.401    0.031   12.740    0.000    0.401    0.326
   .ASC4              0.418    0.033   12.797    0.000    0.418    0.334
   .ASC5              0.451    0.035   12.966    0.000    0.451    0.363
   .OSC1              0.398    0.031   12.751    0.000    0.398    0.313
   .OSC2              0.373    0.029   12.727    0.000    0.373    0.309
   .OSC3              0.388    0.030   12.785    0.000    0.388    0.318
   .OSC4              0.395    0.031   12.798    0.000    0.395    0.320
   .OSC5              0.391    0.031   12.799    0.000    0.391    0.320
   .OSC6              0.406    0.031   12.924    0.000    0.406    0.341
   .RD1               0.466    0.038   12.166    0.000    0.466    0.285
   .RD2               0.306    0.028   10.761    0.000    0.306    0.190
   .RD3               0.367    0.032   11.652    0.000    0.367    0.241
   .RD4               0.330    0.029   11.221    0.000    0.330    0.214
   .RD5               0.355    0.031   11.397    0.000    0.355    0.224
   .POS1              0.464    0.039   12.049    0.000    0.464    0.288
   .POS2              0.340    0.031   10.946    0.000    0.340    0.210
   .POS3              0.344    0.031   11.018    0.000    0.344    0.214
   .POS4              0.477    0.039   12.110    0.000    0.477    0.294
   .POS5              0.342    0.031   11.152    0.000    0.342    0.222
   .LS1               0.283    0.027   10.525    0.000    0.283    0.302
   .LS2               0.405    0.034   11.805    0.000    0.405    0.401
   .LS3               0.506    0.041   12.479    0.000    0.506    0.483
   .LS4               0.398    0.034   11.673    0.000    0.398    0.388
   .LS5               0.420    0.035   11.829    0.000    0.420    0.403
   .ASC               0.018    0.023    0.782    0.434    0.021    0.021
   .OSC              -0.010    0.024   -0.420    0.674   -0.011   -0.011
   .SCO               0.453    0.049    9.202    0.000    0.551    0.551
   .RD                0.665    0.069    9.632    0.000    0.569    0.569
   .POS               0.691    0.071    9.670    0.000    0.602    0.602
    LS                0.654    0.066    9.954    0.000    1.000    1.000

