# ubuntu psmouse suspend

Ubuntu 18.04 struggles with touchpad suspend for some reason, this is a
shell script that removes and loads the kernel module *psmouse* when
the computer suspends, unsuspends.

Place the script here:

    /lib/systemd/system-sleep/

