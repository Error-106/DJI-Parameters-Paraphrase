已知的大疆无人机参数表
==
杂项类
--
|                                                             |                             |
| ----------------------------------------------------------- | --------------------------- |
| battery_type                                                | 电池模式                    |
| enable_new_smart_battery                                    | 强制降落                    |
| forearm_led_ctrl/g_config.misc_cfg.forearm_lamp_ctrl        | 灯光控制                    |
| g_config.diskcheck_topleft_check_disk                       | 飞行器内存检查 \*仅部分机型 |
| g_config.flying_limit.avoid_ground_and_smart_landing_enable | 降落保护                    |
| g_config.misc_cfg.follow_gimbal_yaw_en                      | 旋转平滑过渡                |
| g_config.takeoff.auto_takeoff_height                        | 自动起飞悬停高度            |
| g_config_fdi_open_close_auto_stop_motor_check               | 无人机倾覆检查              |
| g_config_mode_sport_cfg_vert_acc_down                       | 最大下降速度 \*仅部分机型   |
| min_hegiht_user                                             | 未授权最大起飞高度          |
| sequence_start_en/g_config.engine.sequence_start_en         | 电机逐个启动                |
| vert_vel_down_adding_max                                    | 最大下降速度 \*限制值       |

挡位类
--
|                                                                          |               |
| ------------------------------------------------------------------------ | ------------- |
| g*config.mode*(挡位)\_cfg.tors_gyro_range                                 | 左右旋转速度  |
| g*config.mode*(挡位)_cfg_vert_(up/down)                                   | 上升/下降速度 |
| mode*(挡位)\_cfg_tilt_att_range/g_config.mode*(挡位)\_cfg.tilt_atti_rang  | 倾斜角度      |
| 注:挡位主要的分别有 Normal(普通档) Sport(运动挡) Gentle(稳定挡)              |              |

挡位分配
| fswitch_selection[ ]\|g_config.control.control_mode[0-12] 挡位分配 |

|     |                                                                     |
| --- | ------------------------------------------------------------------- |
| 0   | 手动挡-GPS 及姿态矫正均被禁用 \*谨慎启用                             |
| 1   | GPS 模式-同普通挡运作原理相同 \*未确认                               | 
| 2   | GPS 模式-同普通挡运作原理相同 \*未确认                               |
| 3   | ATTI(姿态模式)-GPS 以及光流定位被禁用-倾斜角度上限为 60 °\*谨慎启用    |
| 4   | GPS 模式-同普通挡运作原理相同 \*未确认                               |
| 5   | GPS 模式-同普通挡运作原理相同 \*未确认                               |
| 6   | 工程模式-视机型不同用途不同 \*谨慎启用                               |
| 7   | 普通档                                                             |
| 8   | 运动挡                                                             |
| 9   | 农业模式-具有 RTH 定位的模式-同普通挡运作原理相同                     |
| 10  | GPS 模式-同普通挡运作原理相同                                       |
| 11  | GPS 模式-同普通挡运作原理相同 \*未确认                               |
| 12  | 三脚架/稳定档               


