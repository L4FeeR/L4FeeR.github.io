## Setup Or Run Nethunter In `Termux` Instead Of `NH-Term`

* For this setup, you have to successfully install the nethunter (by root method).

* Now open termux, and enter below commands

> termux-setup-storage && su -c

* Now clone my nh-termux-runner tool from my git by running below code on termux : 

> curl -LO https://raw.githubusercontent.com/L4FeeR/My-Nethunter-files/main/nh

* Now Make The File As shortcut by running below command : 

> cp nh /usr/bin && chmod +x /usr/bin/nh

### Successfully Setup Complete.

## If you wanna run nh in termux , run nh command on termux ,it will up the nh chroot.
