**Make sure you have python installed**

# KiwiIRC-Start-Script-
KiwiIRC Start Script
I made this to start KiwiIRC on Reboots
Step 1: Download kiwistart1.0.py
Step 2: Run the command: chmod +x kiwistart1.0.py (make sure to edit kiwistart.py and replace the direcotires with the location of your kiwi execuatable)
Step 3: Add a cronjob. crontab -e, and add @reboot /home/username/KiwiIRC/kiwistart1.0.py
Step 4: Reboot and test
