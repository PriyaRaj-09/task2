# task2
 # Linux File Permission Task

## Task Description
Create a file named `demo.txt` inside the `/home` directory and set its permissions so that:
- Owner can read, write, and execute.
- Group can read and write.
- Others can only read.

## Steps

1. Create the file:
   ```bash
   sudo touch /home/demo.txt
   
Check current permissions:
ls -l /home/demo.txt

Change permissions:
sudo chmod 764 /home/demo.txt

Verify the permissions:
ls -l /home/demo.txt

