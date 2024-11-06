# inet4031 add user script

## Program Description

This program is a python script designed to automate the process of creating user accounts on an Ubuntu system.

## Program Operation

To run the script, you will need python on your Ubuntu system. The script also needs permissions to create user accounts, so it should be run with sudo.

### Steps to run the script

1. **Prepare the user list**: Create the input file for the script containing usernames and any other info needed.
2. **Run the script**: Execute the script using the command line, passing in the input file name as a parameter.
3. **Verify the users**: After the script is done, make suer the users were created (/etc/passwd)

**Example Command**

sudo ./create-users.py < create-users.input
