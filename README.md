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


# Projects
|Project number| Project description|
|----------|--------|
|1.| LOSA + Ecc (dominant 22 mode and dominat eccentric harmonic)|
|2. | LOSA (Quasi-circular) + Higher Modes|
|3.| Application of Project 2: GW190814|
|4.| LOSA + Ecc including all higher eccentric harmonics (dominant 22 mode)|
|5. | Application of Project 4: GW200105|
|6.| LVK-LOSA search with the method developed in Project 2|
|7.| Merger rate constraints|
|8.| Constraining detectebility of LOSA in various astrophysical env. with the developed LOSA + Ecc waveform|
|9.| Constructing a generic potential profile with LOSA + Ecc|
|10.| Statistical study of the evolution history of a binary |


