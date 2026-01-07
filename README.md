# Dual-boot-Windows-Linux-Seperate-M.2-drives
dual drive dual boot linux + windows 

step 0 : fresh install of windows 11 on first NVME and removed bloatware + OOBE\BYPASSNRO to have a local account 

setp 1 : in windows control panel - power options - what power buttons do untick fast startup *prevents WiFi driver lockouts when swapping drives*

step 1.1  : boot into bios and turned off secure boot and CSM off 

step 2 : removed the windows NVME and installed the empty one to ready for the linux install *best route without affecting EFI partitons*

step 2.1 : booted from the USB *chose Linux mint distro* and followed setup instructions 

step 3 : reinstall the windows NVME 

step 4 : boot to bios select your linux drive as the main boot 

step 5 : the linux grub menu will appear 

i did this mainly to seperate my work to linux and my gaming to windows due to compatablilty with certain games,  following this i found the grub menu slightly ugly and outdated looking, so i later installed refind to have a nice looking menul. 
to date no issues and working as intended!
