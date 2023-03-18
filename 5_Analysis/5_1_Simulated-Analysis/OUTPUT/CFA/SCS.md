lavaan 0.6.13 ended normally after 39 iterations

  Estimator                                         ML
  Optimization method                           NLMINB
  Number of model parameters                        30

  Number of observations                           400

Model Test User Model:
                                                      
  Test statistic                                77.756
  Degrees of freedom                                48
  P-value (Chi-square)                           0.004

Model Test Baseline Model:

  Test statistic                              2868.370
  Degrees of freedom                                66
  P-value                                        0.000

User Model versus Baseline Model:

  Comparative Fit Index (CFI)                    0.989
  Tucker-Lewis Index (TLI)                       0.985

Loglikelihood and Information Criteria:

  Loglikelihood user model (H0)              -6019.798
  Loglikelihood unrestricted model (H1)      -5980.920
                                                      
  Akaike (AIC)                               12099.596
  Bayesian (BIC)                             12219.340
  Sample-size adjusted Bayesian (SABIC)      12124.148

Root Mean Square Error of Approximation:

  RMSEA                                          0.039
  90 Percent confidence interval - lower         0.022
  90 Percent confidence interval - upper         0.055
  P-value H_0: RMSEA <= 0.050                    0.862
  P-value H_0: RMSEA >= 0.080                    0.000

Standardized Root Mean Square Residual:

  SRMR                                           0.023

Parameter Estimates:

  Standard errors                             Standard
  Information                                 Expected
  Information saturated (h1) model          Structured

Latent Variables:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  UI =~                                                                 
    UI1               1.000                               0.852    0.806
    UI2               0.926    0.054   17.020    0.000    0.789    0.783
    UI3               0.976    0.057   17.253    0.000    0.832    0.791
  UC =~                                                                 
    UC1               1.000                               1.081    0.866
    UC2               1.028    0.051   19.990    0.000    1.111    0.869
    UC3               0.947    0.051   18.745    0.000    1.024    0.809
  DI =~                                                                 
    DI1               1.000                               0.721    0.715
    DI2               1.173    0.079   14.772    0.000    0.846    0.784
    DI3               1.052    0.069   15.158    0.000    0.759    0.805
  DC =~                                                                 
    DC1               1.000                               1.104    0.871
    DC2               1.000    0.043   23.234    0.000    1.103    0.898
    DC3               0.984    0.044   22.318    0.000    1.086    0.867

Covariances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
  UI ~~                                                                 
    UC               -0.059    0.054   -1.105    0.269   -0.064   -0.064
    DI                0.603    0.059   10.296    0.000    0.981    0.981
    DC               -0.075    0.054   -1.384    0.166   -0.080   -0.080
  UC ~~                                                                 
    DI                0.023    0.046    0.506    0.613    0.030    0.030
    DC               -0.007    0.066   -0.108    0.914   -0.006   -0.006
  DI ~~                                                                 
    DC               -0.002    0.046   -0.047    0.962   -0.003   -0.003

Variances:
                   Estimate  Std.Err  z-value  P(>|z|)   Std.lv  Std.all
   .UI1               0.393    0.036   11.029    0.000    0.393    0.351
   .UI2               0.394    0.034   11.515    0.000    0.394    0.387
   .UI3               0.414    0.036   11.352    0.000    0.414    0.374
   .UC1               0.391    0.048    8.138    0.000    0.391    0.250
   .UC2               0.400    0.050    7.964    0.000    0.400    0.244
   .UC3               0.553    0.053   10.501    0.000    0.553    0.345
   .DI1               0.496    0.040   12.361    0.000    0.496    0.488
   .DI2               0.449    0.040   11.331    0.000    0.449    0.386
   .DI3               0.312    0.029   10.819    0.000    0.312    0.351
   .DC1               0.386    0.041    9.343    0.000    0.386    0.241
   .DC2               0.293    0.037    7.853    0.000    0.293    0.194
   .DC3               0.390    0.041    9.563    0.000    0.390    0.249
    UI                0.726    0.077    9.386    0.000    1.000    1.000
    UC                1.169    0.114   10.276    0.000    1.000    1.000
    DI                0.520    0.066    7.920    0.000    1.000    1.000
    DC                1.218    0.114   10.648    0.000    1.000    1.000

