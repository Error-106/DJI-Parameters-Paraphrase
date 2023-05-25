# 参数值释义

## 杂项类

### battery_type

| 参数值 | 参数值意义       |
| ------ | ---------------- |
| 0      | 启用智能电池管理 |
| 1      | 禁用智能电池管理 |

### enable_new_smart_battery

### forearm_led_ctrl\|g_config.misc_cfg.forearm_lamp_ctrl

| 参数值 | 参数值意义     |
| ------ | -------------- |
| 0      | 完全关闭机臂灯 |
| 239    | 正常开启机臂灯 |

### g_config.diskcheck_topleft_check_disk

### g_config.flying_limit.avoid_ground_and_smart_landing_enable

### g_config.misc_cfg.follow_gimbal_yaw_en

### g_config.takeoff.auto_takeoff_height

### g_config_fdi_open_close_auto_stop_motor_check

### g_config_mode_sport_cfg_vert_acc_down

### min_hegiht_user

### sequence_start_en\|g_config.engine.sequence_start_en

### vert_vel_down_adding_max

## 挡位类

### 挡位参数

注:挡位主要的分别有 Normal(普通档) Sport(运动挡) Gentle(稳定挡)

#### g*config.mode*(挡位)_cfg.tors_gyro_range

#### g*config.mode*(挡位)*cfg_vert*(up/down)

#### mode*(挡位)\|_cfg_tilt_att_range/g_config.mode*(挡位)\|_cfg.tilt_atti_rang

### 挡位分配

#### fswitch_selection[空/1/2]\|g_config.control.control_mode[0-12]

| 参数值 | 参数意义                                                            |
| ------ | ------------------------------------------------------------------- |
| 0      | 手动挡-GPS 及姿态矫正均被禁用 \*谨慎启用                            |
| 1      | GPS 模式-同普通挡运作原理相同 \*未确认                              |
| 2      | GPS 模式-同普通挡运作原理相同 \*未确认                              |
| 3      | ATTI(姿态模式)-GPS 以及光流定位被禁用-倾斜角度上限为 60 °\*谨慎启用 |
| 4      | GPS 模式-同普通挡运作原理相同 \*未确认                              |
| 5      | GPS 模式-同普通挡运作原理相同 \*未确认                              |
| 6      | 工程模式-视机型不同用途不同 \*谨慎启用                              |
| 7      | 普通档                                                              |
| 8      | 运动挡                                                              |
| 9      | 农业模式-具有 RTH 定位的模式-同普通挡运作原理相同                   |
| 10     | GPS 模式-同普通挡运作原理相同                                       |
| 11     | GPS 模式-同普通挡运作原理相同 \*未确认                              |
| 12     | 三脚架/稳定档                                                       |
