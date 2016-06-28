# keep-USBHDD-awake
#
# Some USB drives without external power supply shut themselves off after a period of inactivity.
# Backup programs (e.g. TimeMachine) wake up, check if they can access the disk and then start
# doing their work. If the wait-time of the backup program is smaller then the spin-up time of
# the drive the programs exit. I don't like that.
#
#  run in background using 
#    $ keep-USBHDD-awake.sh <volume-name> &
