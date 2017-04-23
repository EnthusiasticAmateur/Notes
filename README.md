# Notes

[Mount](#Mount)




## Mount
sudo fdisk -l   //List disks and their details

mkdir /media/2tb

sudo mount -o ro,noload /dev/sda1 /media/2tb     //noload optional to prevent system write attempt error, note that noload may lead to error if file system wasn't unmounted cleanly previously.
