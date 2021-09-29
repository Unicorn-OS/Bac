# Bac
When drives don't show up:
- Step 1. Make a Qcow2 the same size as the disk!
- Step 2. Use Macrium in a vm to restore Backup to Qcow2.
- Step 3. Make an image with Clonezilla! or similar linux tool.
- Step 4. Restore Image to Physical Disk with Clonezilla. ;

code: https://www.google.com/search?q=ubuntu+clone+physical+drive+to+qcow2

`sudo lsblk --bytes`
