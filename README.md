



# MytestOnJetsonXaviere

On my PC host developper (not the xaviere) :

If i get the procedure   from nvidia  and i get and  install sdk manager
 sdkmanager_1.0.1-5538_amd64.deb

![SDK Manager](Capture%20du%202020-04-02%2019-46-38.png)


Next boot of the system , i follow procedure 
cd NVIDIA directory and launch of the installer
next launch of ubuuntu 
add of the french keyboard

***** Go from 4 to 8 CPu heart *****
``` console
CArefull in the robot could be good to stay low consommation (15W)

nvidia@jetson-0420119097418:~$ sudo nvpmodel -q
[sudo] password for nvidia: 
NV Power Mode: MODE_15W
2
nvidia@jetson-0420119097418:~$ sudo nvpmodel -m 0
nvidia@jetson-0420119097418:~$ sudo nvpmodel -q
NV Power Mode: MAXN
0
******
```

Insipration :
https://www.jetsonhacks.com/2018/09/28/nvidia-jetson-agx-xavier-developer-kit/



