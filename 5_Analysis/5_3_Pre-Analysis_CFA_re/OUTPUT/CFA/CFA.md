lavaan 0.6.16 ended normally after 39 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        47

  Number of observations                           221

Model Test User Model:
                                                      
  Test statistic                               396.875
  Degrees of freedom                               184
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              2795.889
  Degrees of freedom                               210
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.918
  Tucker-Lewis Index (TLI)                       0.906

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -7787.304
  Loglikelihood unrestricted model (H1)      -7588.866
                                                      
  Akaike (AIC)                               15668.608
  Bayesian (BIC)                             15828.321
  Sample-size adjusted Bayesian (SABIC)      15679.376

Root Mean Square Error of Approximation:

  RMSEA                                          0.072
  90 Percent confidence interval - lower         0.063
  90 Percent confidence interval - upper         0.082
  P-value H_0: RMSEA <= 0.050                    0.000
  P-value H_0: RMSEA >= 0.080                    0.101

Standardized Root Mean Square Residual:

  SRMR                                           0.062

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                               1.281    0.786
    ASC2              0.835    0.077   10.779    0.000    1.070    0.695
    ASC3              0.698    0.075    9.337    0.000    0.895    0.614
    ASC4              0.962    0.081   11.848    0.000    1.232    0.751
    ASC5              1.219    0.090   13.528    0.000    1.562    0.836
  OSC =~                                                                
    OSC1              1.000                               1.370    0.805
    OSC2              0.946    0.078   12.060    0.000    1.297    0.748
    OSC3              0.742    0.078    9.531    0.000    1.017    0.617
    OSC4              0.726    0.079    9.164    0.000    0.994    0.597
    OSC6              1.003    0.080   12.488    0.000    1.375    0.768
    OSC6_re           0.770    0.080    9.584    0.000    1.054    0.620
  SCO =~                                                                
    ASC               1.000                               0.964    0.964
    OSC               1.078    0.102   10.578    0.000    0.972    0.972
  RD =~                                                                 
    RD1               1.000                               1.192    0.717
    RD2               1.113    0.102   10.869    0.000    1.326    0.777
    RD3               1.226    0.107   11.427    0.000    1.462    0.820
    RD4               1.056    0.106   10.004    0.000    1.259    0.714
    RD5               1.242    0.108   11.485    0.000    1.481    0.824
  POS =~                                                                
    POS1              1.000                               1.498    0.861
    POS2              1.017    0.063   16.068    0.000    1.523    0.880
    POS3              0.732    0.060   12.112    0.000    1.096    0.719
    POS5              0.791    0.069   11.388    0.000    1.184    0.688
    POS6              0.636    0.062   10.213    0.000    0.953    0.634

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  SCO ~~                                                                
    RD                0.957    0.154    6.215    0.000    0.650    0.650
    POS               0.950    0.167    5.701    0.000    0.514    0.514
  RD ~~                                                                 
    POS               0.694    0.152    4.577    0.000    0.389    0.389

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              1.012    0.115    8.817    0.000    1.012    0.381
   .ASC2              1.228    0.129    9.551    0.000    1.228    0.518
   .ASC3              1.322    0.134    9.892    0.000    1.322    0.623
   .ASC4              1.172    0.128    9.167    0.000    1.172    0.436
   .ASC5              1.048    0.130    8.046    0.000    1.048    0.301
   .OSC1              1.020    0.120    8.521    0.000    1.020    0.352
   .OSC2              1.325    0.145    9.158    0.000    1.325    0.441
   .OSC3              1.680    0.170    9.864    0.000    1.680    0.619
   .OSC4              1.784    0.180    9.930    0.000    1.784    0.643
   .OSC6              1.311    0.146    8.967    0.000    1.311    0.410
   .OSC6_re           1.777    0.180    9.854    0.000    1.777    0.615
   .RD1               1.339    0.146    9.164    0.000    1.339    0.485
   .RD2               1.154    0.135    8.562    0.000    1.154    0.396
   .RD3               1.044    0.133    7.882    0.000    1.044    0.328
   .RD4               1.526    0.166    9.194    0.000    1.526    0.491
   .RD5               1.035    0.133    7.789    0.000    1.035    0.321
   .POS1              0.785    0.112    7.005    0.000    0.785    0.259
   .POS2              0.675    0.106    6.352    0.000    0.675    0.225
   .POS3              1.119    0.121    9.260    0.000    1.119    0.482
   .POS5              1.560    0.165    9.468    0.000    1.560    0.527
   .POS6              1.351    0.139    9.737    0.000    1.351    0.598
   .ASC               0.115    0.088    1.309    0.191    0.070    0.070
   .OSC               0.103    0.101    1.024    0.306    0.055    0.055
    SCO               1.526    0.244    6.244    0.000    1.000    1.000
    RD                1.420    0.240    5.908    0.000    1.000    1.000
    POS               2.243    0.291    7.721    0.000    1.000    1.000

