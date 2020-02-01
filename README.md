# mt7601u-4.15

Install instructions:

Check in terminal results for mokutil --sb-state as Secure Boot needs to be disabled, then in terminal do

sudo apt install git build-essential dkms

git clone https://github.com/jeremyb31/mt7601u-4.15.git

sudo dkms add ./mt7601u-4.15

sudo dkms install mt7601u/1.0


Then you can reboot, this will fix some vendor request issues with the mt7601u in the 4.15 kernel
