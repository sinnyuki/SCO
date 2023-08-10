lavaan 0.6.15 ended normally after 41 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        45

  Number of observations                           221

Model Test User Model:
                                                      
  Test statistic                               400.005
  Degrees of freedom                               165
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              2703.709
  Degrees of freedom                               190
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.907
  Tucker-Lewis Index (TLI)                       0.892

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -7425.220
  Loglikelihood unrestricted model (H1)      -7225.218
                                                      
  Akaike (AIC)                               14940.441
  Bayesian (BIC)                             15093.358
  Sample-size adjusted Bayesian (SABIC)      14950.751

Root Mean Square Error of Approximation:

  RMSEA                                          0.080
  90 Percent confidence interval - lower         0.070
  90 Percent confidence interval - upper         0.090
  P-value H_0: RMSEA <= 0.050                    0.000
  P-value H_0: RMSEA >= 0.080                    0.528

Standardized Root Mean Square Residual:

  SRMR                                           0.067

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                               1.282    0.787
    ASC2              0.835    0.077   10.807    0.000    1.070    0.695
    ASC3              0.696    0.075    9.325    0.000    0.892    0.613
    ASC4              0.959    0.081   11.839    0.000    1.229    0.750
    ASC5              1.220    0.090   13.584    0.000    1.564    0.837
  OSC =~                                                                
    OSC1              1.000                               1.391    0.817
    OSC2              0.931    0.076   12.193    0.000    1.294    0.746
    OSC3              0.720    0.076    9.432    0.000    1.002    0.608
    OSC4              0.704    0.078    9.061    0.000    0.979    0.588
    OSC6              0.967    0.079   12.317    0.000    1.345    0.752
  SCO =~                                                                
    ASC               1.000                               0.967    0.967
    OSC               1.102    0.102   10.785    0.000    0.982    0.982
  RD =~                                                                 
    RD1               1.000                               1.187    0.715
    RD2               1.116    0.103   10.823    0.000    1.325    0.777
    RD3               1.237    0.108   11.431    0.000    1.469    0.824
    RD4               1.056    0.106    9.940    0.000    1.254    0.711
    RD5               1.246    0.109   11.429    0.000    1.479    0.823
  POS =~                                                                
    POS1              1.000                               1.474    0.847
    POS2              1.027    0.066   15.442    0.000    1.513    0.874
    POS3              0.720    0.063   11.385    0.000    1.061    0.697
    POS4              0.713    0.071   10.102    0.000    1.051    0.635
    POS5              0.846    0.071   11.989    0.000    1.246    0.724

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  SCO ~~                                                                
    RD                0.949    0.153    6.190    0.000    0.645    0.645
    POS               0.973    0.167    5.820    0.000    0.532    0.532
  RD ~~                                                                 
    POS               0.788    0.155    5.088    0.000    0.450    0.450

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              1.009    0.114    8.827    0.000    1.009    0.380
   .ASC2              1.226    0.128    9.559    0.000    1.226    0.517
   .ASC3              1.326    0.134    9.904    0.000    1.326    0.625
   .ASC4              1.179    0.128    9.196    0.000    1.179    0.438
   .ASC5              1.042    0.129    8.050    0.000    1.042    0.299
   .OSC1              0.964    0.117    8.230    0.000    0.964    0.333
   .OSC2              1.333    0.146    9.123    0.000    1.333    0.443
   .OSC3              1.712    0.173    9.879    0.000    1.712    0.630
   .OSC4              1.815    0.183    9.943    0.000    1.815    0.655
   .OSC6              1.391    0.153    9.071    0.000    1.391    0.435
   .RD1               1.350    0.147    9.193    0.000    1.350    0.489
   .RD2               1.155    0.135    8.577    0.000    1.155    0.397
   .RD3               1.023    0.131    7.814    0.000    1.023    0.322
   .RD4               1.537    0.167    9.219    0.000    1.537    0.494
   .RD5               1.039    0.133    7.817    0.000    1.039    0.322
   .POS1              0.857    0.117    7.304    0.000    0.857    0.283
   .POS2              0.705    0.109    6.464    0.000    0.705    0.235
   .POS3              1.194    0.127    9.370    0.000    1.194    0.515
   .POS4              1.630    0.168    9.698    0.000    1.630    0.596
   .POS5              1.410    0.154    9.172    0.000    1.410    0.476
   .ASC               0.108    0.088    1.227    0.220    0.066    0.066
   .OSC               0.069    0.107    0.650    0.516    0.036    0.036
    SCO               1.536    0.245    6.262    0.000    1.000    1.000
    RD                1.410    0.240    5.879    0.000    1.000    1.000
    POS               2.172    0.289    7.517    0.000    1.000    1.000

