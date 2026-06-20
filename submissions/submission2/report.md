## exp-01 2026-06-20

**Author:** Mateo 

**Model:** xgboost, 5 folds averaged

### Changes
Added particle filter

### Features
['MD', 'X', 'Y', 'Z', 'GR', 'row_index', 'n_rows', 'prediction_start_index', 'last_known_tvt', 'known_tvt_min', 'known_tvt_max', 'known_tvt_range', 'known_tvt_mean', 'known_tvt_std', 'known_gr_mean', 'known_gr_std', 'known_gr_min', 'known_gr_max', 'last_known_gr', 'slope_tvt_md_all', 'slope_tvt_md_recent', 'slope_tvt_z_recent', 'row_from_ps', 'row_frac', 'md_from_ps', 'x_from_ps', 'y_from_ps', 'z_from_ps', 'xy_dist_from_ps', 'xyz_dist_from_ps', 'baseline_tvt_all_slope', 'baseline_tvt_recent_slope', 'baseline_tvt', 'gr_missing', 'gr_roll_mean_11', 'gr_roll_std_11', 'gr_roll_mean_51', 'gr_roll_std_51', 'gr_roll_mean_151', 'gr_roll_std_151', 'gr_diff_1', 'gr_diff_10', 'gr_minus_last_known', 'typewell_tvt_min', 'typewell_tvt_max', 'typewell_tvt_range', 'typewell_gr_mean', 'typewell_gr_std', 'typewell_gr_min', 'typewell_gr_max', 'tw_gr_at_last_known_tvt', 'tw_gr_at_baseline_tvt', 'tw_gr_at_baseline_all_slope', 'gr_minus_tw_baseline', 'gr_minus_tw_last_known', 'pf_scale_3_delta', 'pf_scale_5_delta', 'pf_scale_8_delta', 'pf_scale_12_delta', 'pf_mean_delta', 'pf_std']

### Scores
| CV       |  Public LB | 
| ----     |  ----      |
| 13.69534 |  13.036    |

### Hyperparameters
n_particles=10


### Notes


**Status:** `submitted`