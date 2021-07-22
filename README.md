# tg_ripples

### workflow

1. start with basic ephys_tools data standards (https://github.com/ryanharvey1/ephys_tools)
2. make_session_df.ipynb (gets list of valid sessions to run)
3. fix_lfp_ts.m (will make lfp_ts.npy file for each session if there are time stamp issues)
4. detect_swr_with_ripple_detection.py (detects sharp wave ripples)
5. classify_pyr_int.m
6. save_spikes_npy.ipynb
7. classify_pyr_int.ipynb
8. detect_mua_events.ipynb
9. compare_mua_swr.ipynb
10. group_compar_plots.ipynb