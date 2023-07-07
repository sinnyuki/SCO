lavaan 0.6.15 ended normally after 52 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        59

  Number of observations                           218

Model Test User Model:
                                                      
  Test statistic                              1113.403
  Degrees of freedom                               292
  P-value (Chi-square)                           0.000

Model Test Baseline Model:

  Test statistic                              3230.350
  Degrees of freedom                               325
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.717
  Tucker-Lewis Index (TLI)                       0.685

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -9604.733
  Loglikelihood unrestricted model (H1)      -9048.031
                                                      
  Akaike (AIC)                               19327.465
  Bayesian (BIC)                             19527.150
  Sample-size adjusted Bayesian (SABIC)      19340.184

Root Mean Square Error of Approximation:

  RMSEA                                          0.114
  90 Percent confidence interval - lower         0.107
  90 Percent confidence interval - upper         0.121
  P-value H_0: RMSEA <= 0.050                    0.000
  P-value H_0: RMSEA >= 0.080                    1.000

Standardized Root Mean Square Residual:

  SRMR                                           0.174

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  ASC =~                                                                
    ASC1              1.000                               1.135    0.710
    ASC2              1.028    0.094   10.909    0.000    1.167    0.804
    ASC3              0.851    0.094    9.094    0.000    0.966    0.663
    ASC4              0.997    0.100    9.981    0.000    1.131    0.730
    ASC5             -0.711    0.113   -6.275    0.000   -0.806   -0.454
  OSC =~                                                                
    OSC1              1.000                               1.013    0.657
    OSC2              0.708    0.115    6.142    0.000    0.718    0.468
    OSC3              0.984    0.118    8.320    0.000    0.997    0.661
    OSC4              1.022    0.125    8.188    0.000    1.035    0.649
    OSC5              0.705    0.097    7.237    0.000    0.715    0.562
    OSC6             -0.165    0.122   -1.352    0.176   -0.167   -0.099
  SCO =~                                                                
    ASC               1.000                               1.087    1.087
    OSC               0.724    0.121    5.964    0.000    0.882    0.882
  RD =~                                                                 
    RD1               1.000                               1.052    0.685
    RD2               0.152    0.118    1.282    0.200    0.160    0.097
    RD3               1.140    0.134    8.502    0.000    1.200    0.727
    RD4              -0.162    0.113   -1.435    0.151   -0.170   -0.109
    RD5               1.189    0.136    8.723    0.000    1.252    0.780
  POS =~                                                                
    POS1              1.000                               1.305    0.844
    POS2              1.059    0.073   14.493    0.000    1.383    0.858
    POS3              0.925    0.070   13.147    0.000    1.207    0.790
    POS4              0.582    0.086    6.745    0.000    0.759    0.458
    POS5              0.651    0.078    8.355    0.000    0.849    0.552
  LS =~                                                                 
    LS1               1.000                               1.252    0.818
    LS2               1.082    0.074   14.545    0.000    1.354    0.857
    LS3               1.069    0.079   13.518    0.000    1.338    0.811
    LS4               1.036    0.089   11.655    0.000    1.297    0.725
    LS5               1.093    0.088   12.368    0.000    1.368    0.759
  RD =~                                                                 
    SCO               0.529    0.109    4.843    0.000    0.451    0.451
  POS =~                                                                
    SCO               0.251    0.077    3.244    0.001    0.266    0.266
  LS =~                                                                 
    RD               -0.356    0.071   -5.013    0.000   -0.423   -0.423
    POS               0.531    0.078    6.832    0.000    0.509    0.509
    SCO               0.169    0.088    1.928    0.054    0.171    0.171

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .ASC1              1.266    0.140    9.033    0.000    1.266    0.496
   .ASC2              0.744    0.095    7.853    0.000    0.744    0.353
   .ASC3              1.190    0.127    9.364    0.000    1.190    0.561
   .ASC4              1.120    0.126    8.855    0.000    1.120    0.467
   .ASC5              2.504    0.248   10.089    0.000    2.504    0.794
   .OSC1              1.352    0.149    9.081    0.000    1.352    0.568
   .OSC2              1.836    0.184    9.963    0.000    1.836    0.781
   .OSC3              1.278    0.141    9.045    0.000    1.278    0.563
   .OSC4              1.473    0.161    9.143    0.000    1.473    0.579
   .OSC5              1.107    0.115    9.641    0.000    1.107    0.684
   .OSC6              2.846    0.273   10.424    0.000    2.846    0.990
   .RD1               1.249    0.156    7.991    0.000    1.249    0.530
   .RD2               2.669    0.256   10.416    0.000    2.669    0.991
   .RD3               1.283    0.176    7.282    0.000    1.283    0.471
   .RD4               2.411    0.232   10.409    0.000    2.411    0.988
   .RD5               1.007    0.164    6.122    0.000    1.007    0.391
   .POS1              0.689    0.099    6.991    0.000    0.689    0.288
   .POS2              0.684    0.104    6.564    0.000    0.684    0.264
   .POS3              0.876    0.107    8.167    0.000    0.876    0.376
   .POS4              2.171    0.215   10.093    0.000    2.171    0.790
   .POS5              1.643    0.167    9.863    0.000    1.643    0.695
   .LS1               0.774    0.095    8.183    0.000    0.774    0.331
   .LS2               0.665    0.090    7.359    0.000    0.665    0.266
   .LS3               0.934    0.112    8.304    0.000    0.934    0.343
   .LS4               1.518    0.165    9.221    0.000    1.518    0.474
   .LS5               1.380    0.154    8.942    0.000    1.380    0.424
   .ASC              -0.234    0.190   -1.227    0.220   -0.181   -0.181
   .OSC               0.228    0.119    1.918    0.055    0.222    0.222
   .SCO               1.167    0.270    4.322    0.000    0.767    0.767
   .RD                0.909    0.182    4.990    0.000    0.821    0.821
   .POS               1.261    0.180    7.017    0.000    0.740    0.740
    LS                1.567    0.220    7.135    0.000    1.000    1.000

