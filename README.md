# LOSA_Corr_to_Higher_Spherical_Harmonic_Modes
In this repo, I will store the method and results of the LOSA correction to the leading (2, 2) and higher spherical harmonic modes (3, 3) , (4, 4) ..etc.

## Here I will check that higer modes can mimic LOSA using the follwoing strategy based on fitting factor:

|Model  | Signal| Outcome |
|-----------|-------------|----------|
|No HM + Non-zero LOSA| HM + Zero LOSA| Fitting-factor peaks for \|LOSA\| $\neq$ 0 |
|HM + Non-zero LOSA| HM + Zero LOSA| FF peaks for \|LOSA\| = 0|
|HM + Non-zero LOSA| HM + Non-zero LOSA| FF peaks for \|LOSA\| $\neq$ 0|


## PE runs pertaining to higher modes

|Injection  | Recovery | Expectation |
|-----------|-------------|----------|
|LOSA All Modes | 22 Mode + LOSA 22 Mode| Biased Parameters|
|LOSA All Modes| All Modes + LOSA 22 Mode| [Biased Parameters](https://github.com/avi-tiw/LOSA_HM/tree/main/IMRPhenomXPHM_LOSA_HM_results/GW_190814_like_injection/22_plus_33_injection_and_same_recovery/bias_check/inj_LOSA_cor_to_all_modes_individually_rec_only_22_LOSA_cor_to_all_modes/LOSA_5_minus_3)|
|LOSA All Modes| All Modes + LOSA All Modes| [No Bias](https://github.com/avi-tiw/LOSA_HM/tree/main/IMRPhenomXPHM_LOSA_HM_results/GW_190814_like_injection/22_plus_33_injection_and_same_recovery/Final_results/all_modes_phase_and_amp_cor_phase_marg_false_duration_16sec) |



