# scs_osio
OpenSensors.io - device, organisation, topic and schema management tools for South Coast Science  air quality
monitoring projects.

**Required libraries:** 

* Third party: paho-mqtt
* SCS root: scs_core
* SCS host: scs_host_bbe, scs_host_posix or scs_host_rpi



**Typical PYTHONPATH:**

**Raspberry Pi, in /home/pi/.bashrc:**

export \\
PYTHONPATH=$HOME/SCS/scs_analysis:$HOME/SCS/scs_dev:$HOME/SCS/scs_osio:$HOME/SCS/scs_mfr:$HOME/SCS/scs_dfe_eng:$HOME/SCS/scs_host_rpi:$HOME/SCS/scs_core:$PYTHONPATH


**Beaglebone, in /root/.bashrc:**

export \\
PYTHONPATH=/home/debian/SCS/scs_dev:/home/debian/SCS/scs_osio:/home/debian/SCS/scs_mfr:/home/debian/SCS/scs_psu:/home/debian/SCS/scs_comms_ge910:/home/debian/SCS/scs_dfe_eng:/home/debian/SCS/scs_host_bbe:/home/debian/SCS/scs_core:$PYTHONPATH


**Beaglebone, in /home/debian/.bashrc:**

export \\
PYTHONPATH=\~/SCS/scs_dev:\~/SCS/scs_osio:\~/SCS/scs_mfr:\~/SCS/scs_psu:\~/SCS/scs_comms_ge910:\~/SCS/scs_dfe_eng:\~/SCS/scs_host_bbe:\~/SCS/scs_core:$PYTHONPATH
