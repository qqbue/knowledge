<!--允许应用打开网络套接口 -->
<uses-permission android:name="android.permission.INTERNET" />

<uses-permission android:name="android.permission.MOUNT_UNMOUNT_FILESYSTEMS" />

<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.SET_WALLPAPER" />


<!-- 允许在登入数据库的时候读写其中的属性表，并上传改变的值 -->
<uses-permission android:name="android.permission.ACCESS_CHECKIN_PROPERTIES" />
 
<!--允许应用访问范围(如WIFI)性的定位 -->
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
 
<!-- 允许应用访问精确(如GPS)性的定位 -->
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
 
<!--允许应访问额外的提供定位的指令 -->
<uses-permission android:name="android.permission.ACCESS_LOCATION_EXTRA_COMMANDS" />
2
<!-- 允许应用创建用于测试的模拟定位提供者 -->
<uses-permission android:name="android.permission.ACCESS_MOCK_LOCATION" />
 
<!--允许应用访问网络上的信息 -->
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
 
<!--允许应用使用低版本视图的特征 -->
<uses-permission android:name="android.permission.ACCESS_SURFACE_FLINGER" />
 
<!--允许应用访问关羽Wi-Fi网络的信息 -->
<uses-permission android:name="android.permission.ACCESS_WIFI_STATE" />
 
<!--允许应用进入帐户认证 -->
<uses-permission android:name="android.permission.ACCOUNT_MANAGER" />
3
<!--允许应用为ACCOUNT_MANAGER扮演一个帐户认证系统 -->
<uses-permission android:name="android.permission.AUTHENTICATE_ACCOUNTS" />
 
<!--允许应用去统计电源信息 -->
<uses-permission android:name="android.permission.BATTERY_STATS" />
 
<!-- 允许应用告诉AppWidget哪个应用能够访问该AppWidget的数据 -->
<uses-permission android:name="android.permission.BIND_APPWIDGET" />
 
<!--必须通过关机接收者的请求来确保只有系统能够与之交互 -->
<uses-permission android:name="android.permission.BIND_DEVICE_ADMIN" />
 
<!-- 必须通过InputMethodService的请求来确保只有系统能够与之绑定 -->
<uses-permission android:name="android.permission.BIND_INPUT_METHOD" />
 
<!--必须通过WallpaperService的请求来确保只有系统能够与之绑定 -->
<uses-permission android:name="android.permission.BIND_WALLPAPER" />
4
<!-- 允许应用去连接蓝牙设备 -->
<uses-permission android:name="android.permission.BLUETOOTH" />
 
<!-- 允许应用找到与之连接的蓝牙设备 -->
<uses-permission android:name="android.permission.BLUETOOTH_ADMIN" />
 
<!--被请求废止设备(非常危险) -->
<uses-permission android:name="android.permission.BRICK" />
 
<!--允许应用发出一个程序包被移除的广播消息 -->
<uses-permission android:name="android.permission.BROADCAST_PACKAGE_REMOVED" />
 
<!-- 允许应用发出一个收到短信的消息 -->
<uses-permission android:name="android.permission.BROADCAST_SMS" />
 
<!--允许应用发出一个与intent相连的消息 -->
<uses-permission android:name="android.permission.BROADCAST_STICKY" />
 
<!--允许应用发出一个收到WAP PUSH的广播消息 -->
<uses-permission android:name="android.permission.BROADCAST_WAP_PUSH" />
5
<!--允许应用启动一个用户确认电话被拨打而不通过拨打电话的用户界面的的拨打程序 -->
<uses-permission android:name="android.permission.CALL_PHONE" />
 
<!--允许应用启动一个用户确认电话被拨打而不通过拨打电话的用户界面的的任意号码的拨打，包括紧急号码. -->
<uses-permission android:name="android.permission.CALL_PRIVILEGED" />
 
<!--能够启动照相机设备的请求 -->
<uses-permission android:name="android.permission.CAMERA" />
 
<!-- 允许应用去改变一个应用是否是激活状态 -->
<uses-permission android:name="android.permission.CHANGE_COMPONENT_ENABLED_STATE" />
 
<!-- 允许应用修改当前的配置，如本地设置 -->
<uses-permission android:name="android.permission.CHANGE_CONFIGURATION" />
 
<!-- 允许应用改变网络的连接状态 -->
<uses-permission android:name="android.permission.CHANGE_NETWORK_STATE" />
 
6
<!-- 允许应用进入Wi-Fi的组播方式 -->
<uses-permission android:name="android.permission.CHANGE_WIFI_MULTICAST_STATE" />
 
<!--允许应用改变Wi-Fi的连接状态 -->
<uses-permission android:name="android.permission.CHANGE_WIFI_STATE" />
 
<!--允许应用清除所有安装在设备上的应用的缓存 -->
<uses-permission android:name="android.permission.CLEAR_APP_CACHE" />
 
<!--允许应用清除使用者的信息资料 -->
<uses-permission android:name="android.permission.CLEAR_APP_USER_DATA" />
 
<!--允许从广播设备来更新或不更新本地的消息 -->
<uses-permission android:name="android.permission.CONTROL_LOCATION_UPDATES" />
 
<!--允许应用删除掉缓存文件 -->
<uses-permission android:name="android.permission.DELETE_CACHE_FILES" />
 
<!--允许应用删除掉程序包 -->
<uses-permission android:name="android.permission.DELETE_PACKAGES" />
7
<!-- 允许低权限的访问电源管理项 -->
<uses-permission android:name="android.permission.DEVICE_POWER" />
 
<!--允许应用诊断程序资源 -->
<uses-permission android:name="android.permission.DIAGNOSTIC" />
 
<!--允许应用禁用键盘锁 -->
<uses-permission android:name="android.permission.DISABLE_KEYGUARD" />
 
<!--允许应用从系统服务中恢复转储的信息 -->
<uses-permission android:name="android.permission.DUMP" />
 
<!--允许应用扩大或缩小状态栏 -->
<uses-permission android:name="android.permission.EXPAND_STATUS_BAR" />
 
<!--如制造商测试的应用一样用终极权限用户运行 -->
<uses-permission android:name="android.permission.FACTORY_TEST" />
 
<!--允许访问手电筒 -->
<uses-permission android:name="android.permission.FLASHLIGHT" />
8
<!--允许应用强制的返回操作而不论是不是最终的activity -->
<uses-permission android:name="android.permission.FORCE_BACK" />
 
<!--允许应用访问账目服务中的统计清单 -->
<uses-permission android:name="android.permission.GET_ACCOUNTS" />
 
<!-- 允许应用查找出任何程序包使用的空间 -->
<uses-permission android:name="android.permission.GET_PACKAGE_SIZE" />
 
<!-- 允许应用找到关于当前或最近运行的任务和在哪些acitivities里运行 -->
<uses-permission android:name="android.permission.GET_TASKS" />
 
<!-- 这个权限可以被内容提供者用来允许使用全程搜索他们的数据 -->
<uses-permission android:name="android.permission.GLOBAL_SEARCH" />
 
<!-- 允许访问硬件及周边设备. -->
<uses-permission android:name="android.permission.HARDWARE_TEST" />
 
<!--允许应用注入用户事件（键盘、触摸）到事件中然后提供给任意的窗口 -->
<uses-permission android:name="android.permission.INJECT_EVENTS" />
9
<!--允许应用安装一个位置提供商到位置管理器中 -->
<uses-permission android:name="android.permission.INSTALL_LOCATION_PROVIDER" />
 
<!--允许应用安装程序包. -->
<uses-permission android:name="android.permission.INSTALL_PACKAGES" />
 
<!--允许应用打开被部分系统用户接口使用的窗口 -->
<uses-permission android:name="android.permission.INTERNAL_SYSTEM_WINDOW" />
 
<!--允许应用打开网络套接口 -->
<uses-permission android:name="android.permission.INTERNET" />
 
<!--允许应用去呼叫killBackgroundProcesses(String).方法 -->
<uses-permission android:name="android.permission.KILL_BACKGROUND_PROCESSES" />
 
<!-- 允许应用去管理帐户管理者中的重要清单 -->
<uses-permission android:name="android.permission.MANAGE_ACCOUNTS" />
10
<!--允许应用去管理(创建、销毁、顺序)在窗口管理者中的应用 -->
<uses-permission android:name="android.permission.MANAGE_APP_TOKENS" />
 
<uses-permission android:name="android.permission.MASTER_CLEAR" />
 
<!--允许应用修改全局音频设定 -->
<uses-permission android:name="android.permission.MODIFY_AUDIO_SETTINGS" />
 
<!--允许改变拨打电话的状态-电源等 -->
<uses-permission android:name="android.permission.MODIFY_PHONE_STATE" />
 
<!--允许格式化可移除的存储仓库的文件系统 -->
<uses-permission android:name="android.permission.MOUNT_FORMAT_FILESYSTEMS" />
 
<!--允许装备或解除可移除的存储仓库的文件系统 -->
<uses-permission android:name="android.permission.MOUNT_UNMOUNT_FILESYSTEMS" />
 
<!--允许应用使它的activities更持久稳固 -->
<uses-permission android:name="android.permission.PERSISTENT_ACTIVITY" />
11
<!--允许应用监督、限定或终止呼出的电话 -->
<uses-permission android:name="android.permission.PROCESS_OUTGOING_CALLS" />
 
<!--允许应用读取用户的日历数据 -->
<uses-permission android:name="android.permission.READ_CALENDAR" />
 
<!-- 允许应用读取用户的联系人数据 -->
<uses-permission android:name="android.permission.READ_CONTACTS" />
 
<!--允许应用抓取屏幕和更多可获得的缓冲数据 -->
<uses-permission android:name="android.permission.READ_FRAME_BUFFER" />
 
<!--允许应用去读取(非写)用户浏览历史和书签 -->
<uses-permission android:name="android.permission.READ_HISTORY_BOOKMARKS" />
 
<!-- 允许应用去的当前键盘和控制的状态 -->
<uses-permission android:name="android.permission.READ_INPUT_STATE" />
12
<!--允许应用读取低级别的系统日志文件 -->
<uses-permission android:name="android.permission.READ_LOGS" />
 
<!--允许应用读取所有者的数据 -->
<uses-permission android:name="android.permission.READ_OWNER_DATA" />
 
<!--允许读取电话的状态 -->
<uses-permission android:name="android.permission.READ_PHONE_STATE" />
 
<!--允许应用读取短信息. -->
<uses-permission android:name="android.permission.READ_SMS" />
 
<!--允许应用读取同步的设置 -->
<uses-permission android:name="android.permission.READ_SYNC_SETTINGS" />
 
<!--允许应用读取同步的统计数据 -->
<uses-permission android:name="android.permission.READ_SYNC_STATS" />
 
<!--重新启动设备的请求 -->
<uses-permission android:name="android.permission.REBOOT" />
13
<!--允许应用接收在系统完成启动后发出的ACTION_BOOT_COMPLETED广播信息 -->
<uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED" />
 
<!--允许应用去监听多媒体信息并记录和对起进行处理 -->
<uses-permission android:name="android.permission.RECEIVE_MMS" />
 
<!--允许应用去监听短消息并记录和对起进行处理 -->
<uses-permission android:name="android.permission.RECEIVE_SMS" />
 
<!--允许应用监听WAP push信息 -->
<uses-permission android:name="android.permission.RECEIVE_WAP_PUSH" />
 
<!--允许应用记录音频信息 -->
<uses-permission android:name="android.permission.RECORD_AUDIO" />
 
<!--允许应用改变任务的关系位置 -->
<uses-permission android:name="android.permission.REORDER_TASKS" />
 
<!--已废弃使用 -->
<uses-permission android:name="android.permission.RESTART_PACKAGES" />
 
14
<!--允许应用发送短消息. -->
<uses-permission android:name="android.permission.SEND_SMS" />
 
<!--允许应用查看和控制activities是怎样在系统中运行的 -->
<uses-permission android:name="android.permission.SET_ACTIVITY_WATCHER" />
 
<!--允许应用去控制当activities被覆盖后是否是立即接触结束 -->
<uses-permission android:name="android.permission.SET_ALWAYS_FINISH" />
 
<!-- 改变动画的比例因子 -->
<uses-permission android:name="android.permission.SET_ANIMATION_SCALE" />
 
<!--设置一个应用为调试模式 -->
<uses-permission android:name="android.permission.SET_DEBUG_APP" />
 
<!--允许低级别的设置屏幕的方向 -->
<uses-permission android:name="android.permission.SET_ORIENTATION" />
 
<!--已废弃 -->
<uses-permission android:name="android.permission.SET_PREFERRED_APPLICATIONS" />
 
<!--允许应用设置可以运行的最大数的应用进程 -->
<uses-permission android:name="android.permission.SET_PROCESS_LIMIT" />
 
<!-- 允许应用设置系统时间 -->
<uses-permission android:name="android.permission.SET_TIME" />
15
<!-- 允许应用设置系统时区时间 -->
-->
<uses-permission android:name="android.permission.SET_TIME_ZONE" />
 
<!-- 允许应用设置壁纸 -->
<uses-permission android:name="android.permission.SET_WALLPAPER" />
 
<!--允许应用设置锁定的壁纸 -->
<uses-permission android:name="android.permission.SET_WALLPAPER_HINTS" />
 
<!--允许应用发出一个给所有稳定进程信号的请求 -->
<uses-permission android:name="android.permission.SIGNAL_PERSISTENT_PROCESSES" />
 
<!-- 允许应用打开、关闭或使状态栏或图标失去作用 -->
<uses-permission android:name="android.permission.STATUS_BAR" />
 
<!--允许应用访问内容提供者的签署认证 -->
<uses-permission android:name="android.permission.SUBSCRIBED_FEEDS_READ" />
 
<uses-permission android:name="android.permission.SUBSCRIBED_FEEDS_WRITE" />
 
<!-- 允许应用使用TYPE_SYSTEM_ALERT来打开窗口，并将窗口显示于其他应用的顶端 -->
<uses-permission android:name="android.permission.SYSTEM_ALERT_WINDOW" />
 
<!--允许应用更新设备资料信息 -->
<uses-permission android:name="android.permission.UPDATE_DEVICE_STATS" />
 
<!--允许应用从管理器得到授权请求 -->
<uses-permission android:name="android.permission.USE_CREDENTIALS" />
 
<!--允许应用访问震动器 -->
<uses-permission android:name="android.permission.VIBRATE" />
 
<!-- 允许使用电源锁定管理以使进程休眠或屏幕变暗 -->
<uses-permission android:name="android.permission.WAKE_LOCK" />
 
<!--允许应用去写入接入点设置 -->
<uses-permission android:name="android.permission.WRITE_APN_SETTINGS" />
 
<!--允许应用写（非读）用户的日历数据 -->
<uses-permission android:name="android.permission.WRITE_CALENDAR" />
 
<!--允许应用写（非读）用户的联系人数据 -->
<uses-permission android:name="android.permission.WRITE_CONTACTS" />
 
<!-- 允许应用写（非读）用户的外部存储器 -->
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
 
<!-- 允许应用修改Google服务地图 -->
<uses-permission android:name="android.permission.WRITE_GSERVICES" />
 
<!-- 允许应用写（非读）用户的浏览器历史和书签 -->
<uses-permission android:name="android.permission.WRITE_HISTORY_BOOKMARKS" />
 
<!--允许应用写（非读）用户的数据 -->
<uses-permission android:name="android.permission.WRITE_OWNER_DATA" />
 
16
<!--允许应用写或读当前系统设置 -->
<uses-permission android:name="android.permission.WRITE_SECURE_SETTINGS" />
 
<!-- 允许应用写或读系统设置 -->
<uses-permission android:name="android.permission.WRITE_SETTINGS" />
 
<!--允许应用写短消息信息 -->
<uses-permission android:name="android.permission.WRITE_SMS" />
<!-- 允许应用写同步设置 -->
<uses-permission android:name="android.permission.WRITE_SYNC_SETTINGS" />
