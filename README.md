# CPU Hot-plugging shell script for LG G4

A .sh script (acts as a linux deamon/service), that saves precious battery juice by shutting down inactive processor cores. 

Orginal LG G4 (H815; other variants probably too) does not use cpu hot-plugging feature. 

U can use it with orginal kernel, so only rooted device is needed (no need to unlock bootloader).


# Requirements

* root
* installed busybox, terminal emulator


# Usage

1) download all files and place it on internal memory using some explorer app (for example - "root browser"), best to folder /data/cpu_hotplug_meneves/ )

2) run terminal emulator and navigate to downloaded folder (cd /data/cpu_hotplug_meneves/)

3) execute "su" and then:

4) give all .sh script permission to execute (chmod 744 *.sh (give it chmod 777 *.sh if does not work))

5) make sure you use "interactive" governor (default) or cafactive (some custom kernels may have it, like Imperial Kernel)

6) and then:

  * start service by calling ./start.sh
  * stop service by calling ./stop.sh


# Screenshots

* see https://github.com/meneves/lg_g4_cpu_hotplug/tree/master/screenshots


# Support thread

* http://forum.xda-developers.com/g4/general/mod-lg-g4-cpu-hot-plugging-shell-sh-t3194702 (english)
* http://forum.android.com.pl/topic/246463-root-battery-saver-lg-g4-cpu-hot-plugging-shell-sh-script-gov-tweaks/ (polish)

