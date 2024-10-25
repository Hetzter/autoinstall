## Data Source
Format a USB drive to FAT 32, name "CIDATA" and put "user-data" and "meta-data" in USB root.
mkfs.fat -I -F 32 -n 'CIDATA' /dev/sdX
