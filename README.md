## Description
sweep2sleep is a gesture that exists on some Android ROMs that makes your device sleep if you slide right-to-left or left-to-right on the bottom of your screen.

This module enables sweep2sleep rigt-to-left on ROMs that support this feature by running the following command in the "late_start" service:

```sh
echo "2" > sys/sweep2sleep/sweep2sleep
```

#### Current Version
1.0

#### Changelog

* 1.0 (25.07.2017) - Initial release

#### Magisk Template
v1400

#### NOTICE

* You should use latest Magisk Manager to install this module. If you meet any problem under installation from Magisk Manager, please try to install it from recovery.