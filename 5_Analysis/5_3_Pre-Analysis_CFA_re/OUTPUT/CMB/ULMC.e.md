lavaan 0.6.16 ended normally after 221 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        51

  Number of observations                           221

Model Test User Model:
                                                      
  Test statistic                               302.466
  Degrees of freedom                               159
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              2664.443
  Degrees of freedom                               190
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.942
  Tucker-Lewis Index (TLI)                       0.931

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -7374.994
  Loglikelihood unrestricted model (H1)      -7223.761
                                                      
  Akaike (AIC)                               14851.987
  Bayesian (BIC)                             15025.293
  Sample-size adjusted Bayesian (SABIC)      14863.672

Root Mean Square Error of Approximation:

  RMSEA                                          0.064
  90 Percent confidence interval - lower         0.053
  90 Percent confidence interval - upper         0.075
  P-value H_0: RMSEA <= 0.050                    0.020
  P-value H_0: RMSEA >= 0.080                    0.007

Standardized Root Mean Square Residual:

  SRMR                                           0.051

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                              21.048   13.004
    ASC2              0.988    0.024   40.544    0.000   20.802   13.109
    ASC3              0.975    0.051   19.072    0.000   20.520   13.522
    ASC4              0.996    0.010  101.526    0.000   20.965   12.732
    ASC5              1.012    0.025   41.116    0.000   21.296   11.927
  OSC =~                                                                
    OSC1              1.000                              21.292   12.356
    OSC2              0.987    0.027   36.451    0.000   21.011   12.244
    OSC3              0.969    0.063   15.375    0.000   20.625   12.494
    OSC4              0.961    0.079   12.216    0.000   20.458   12.612
    OSC6              0.996    0.010  100.912    0.000   21.208   11.715
  RD =~                                                                 
    RD1               1.000                              20.835   12.498
    RD2               1.015    0.030   33.353    0.000   21.140   12.124
    RD3               1.029    0.059   17.512    0.000   21.430   11.677
    RD4               0.998    0.008  129.623    0.000   20.791   12.233
    RD5               1.015    0.031   33.095    0.000   21.142   12.154
  POS =~                                                                
    POS1              1.000                              21.477   12.415
    POS2              1.000    0.005  201.439    0.000   21.480   12.599
    POS3              0.977    0.046   21.101    0.000   20.978   13.796
    POS5              0.991    0.020   50.456    0.000   21.275   11.741
    POS6              0.966    0.067   14.532    0.000   20.757   13.951
  ULMC =~                                                               
    ASC1       (w)    1.000                              20.380   12.591
    ASC2       (w)    1.000                              20.380   12.844
    ASC3       (w)    1.000                              20.380   13.430
    ASC4       (w)    1.000                              20.380   12.377
    ASC5       (w)    1.000                              20.380   11.414
    OSC1       (w)    1.000                              20.380   11.827
    OSC2       (w)    1.000                              20.380   11.876
    OSC3       (w)    1.000                              20.380   12.345
    OSC4       (w)    1.000                              20.380   12.563
    OSC6       (w)    1.000                              20.380   11.258
    RD1        (w)    1.000                              20.380   12.225
    RD2        (w)    1.000                              20.380   11.688
    RD3        (w)    1.000                              20.380   11.105
    RD4        (w)    1.000                              20.380   11.991
    RD5        (w)    1.000                              20.380   11.716
    POS1       (w)    1.000                              20.380   11.780
    POS2       (w)    1.000                              20.380   11.953
    POS3       (w)    1.000                              20.380   13.403
    POS5       (w)    1.000                              20.380   11.247
    POS6       (w)    1.000                              20.380   13.697

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC ~~                                                                
    OSC             448.043 1804.940    0.248    0.804    1.000    1.000
    RD              437.935 1784.911    0.245    0.806    0.999    0.999
    POS             451.278 1812.453    0.249    0.803    0.998    0.998
    ULMC           -428.363 1765.695   -0.243    0.808   -0.999   -0.999
  OSC ~~                                                                
    RD              442.970 1795.248    0.247    0.805    0.999    0.999
    POS             456.469 1822.796    0.250    0.802    0.998    0.998
    ULMC           -433.310 1776.035   -0.244    0.807   -0.999   -0.999
  RD ~~                                                                 
    POS             446.387 1802.743    0.248    0.804    0.998    0.998
    ULMC           -423.965 1755.998   -0.241    0.809   -0.998   -0.998
  POS ~~                                                                
    ULMC           -437.221 1783.522   -0.245    0.806   -0.999   -0.999

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              0.990    0.111    8.952    0.000    0.990    0.378
   .ASC2              1.170    0.127    9.209    0.000    1.170    0.465
   .ASC3              1.129    0.133    8.492    0.000    1.129    0.491
   .ASC4              1.190    0.128    9.284    0.000    1.190    0.439
   .ASC5              1.151    0.133    8.620    0.000    1.151    0.361
   .OSC1              0.925    0.116    7.975    0.000    0.925    0.311
   .OSC2              1.349    0.145    9.302    0.000    1.349    0.458
   .OSC3              1.490    0.163    9.152    0.000    1.490    0.547
   .OSC4              1.460    0.168    8.669    0.000    1.460    0.555
   .OSC6              1.383    0.153    9.064    0.000    1.383    0.422
   .RD1               1.259    0.143    8.820    0.000    1.259    0.453
   .RD2               1.131    0.131    8.657    0.000    1.131    0.372
   .RD3               0.915    0.126    7.270    0.000    0.915    0.272
   .RD4               1.410    0.158    8.946    0.000    1.410    0.488
   .RD5               1.113    0.129    8.622    0.000    1.113    0.368
   .POS1              0.824    0.110    7.469    0.000    0.824    0.275
   .POS2              0.732    0.103    7.080    0.000    0.732    0.252
   .POS3              1.013    0.116    8.744    0.000    1.013    0.438
   .POS5              1.528    0.165    9.280    0.000    1.528    0.465
   .POS6              1.140    0.135    8.459    0.000    1.140    0.515
    ASC             443.023 1794.607    0.247    0.805    1.000    1.000
    OSC             453.331 1815.267    0.250    0.803    1.000    1.000
    RD              434.116 1775.261    0.245    0.807    1.000    1.000
    POS             461.278 1830.249    0.252    0.801    1.000    1.000
    ULMC            415.333 1736.780    0.239    0.811    1.000    1.000

