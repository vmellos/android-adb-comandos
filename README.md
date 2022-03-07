# android-adb-comandos
Commands of android device debuguer (adb)

# install adb on linux
`$ sudo apt install android-tools-adb android-tools-fastboot`

# enable developer mode and active usb debugging

`$ adb devices`

`$ adb -s device_id shell`

`$ sudo adb kill-server`

`$ sudo adb start-server`

# list packages
`$ pm list packages -f | grep target_name`

# disable package
`$ pm disable-user -–user 0 com.samsung.android.game.gos`

# enable package
`$ pm enable -–user 0 com.samsung.android.game.gos`

# remove package Samsung Game Optimizing Service
`$ pm uninstall -k --user 0 com.samsung.android.game.gos`

# remove SIM toolkit
`$ pm uninstall -k --user 0 com.android.stk`

`$ pm uninstall -k --user 0 com.android.stk2`
