harumi
======

d2
dota_cheap_water 1
cl_globallight_shadow_mode 0
r_deferred_height_fog 0
r_deferred_simple_light 1
r_screenspace_aa 0
mat_vsync 0
dota_hud_healthbars 1
dota_enemy_color_r 0.8
dota_enemy_color_g 0.4
dota_enemy_color_b 0.4
dota_friendly_color_r 0.3
dota_friendly_color_g 0.7
dota_friendly_color_b 0.8
dota_minimap_misclick_time 0
dota_sf_hud_header_display_time 0
dota_sf_game_end_delay 0
con_enable "F11"
cl_cmdrate "60"
cl_updaterate "60"
rate "80000"
cl_interp "0"
cl_interp_ratio "1"
cl_smooth "1"
cl_smoothtime "0.01"
cl_lagcompensation "1"
cl_pred_optimize "2"
bind "F1" "dota_camera_set_lookatpos -2287 1817"
bind "F2" "dota_camera_set_lookatpos 2960 -2353"
dota_camera_disable_zoom "1"
dota_disable_range_finder 0
dota_minimap_hero_size 1100
dota_neutral_color_r 1.0
dota_neutral_color_g 1.0
dota_neutral_color_b 1.0
alias "tab1" "dota_cycle_selected;"
alias "poff1" "dota_ability_execute 1;"
alias "poff2" "dota_ability_execute 1; dota_ability_execute 1;"
alias "tab2" "tab1; "poff2;"
alias "imbapoff" "tab2; tab2; tab2; tab2; tab2; +dota_camera_follow;"
bind "x" "imbapoff"
alias "selectpoff1" "dota_ability_execute 1; +sixense_Left_click; -sixense_Left_click; tab1;"
alias "selectpoff2" "selectpoff1"
bind "z" "selectpoff2"
