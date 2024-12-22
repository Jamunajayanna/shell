To create a file in Ubuntu using shell scripting, follow these steps:

Steps:
1.Open a Terminal: Press Ctrl+Alt+T to open a terminal in Ubuntu.

2.Write the Script: Use a text editor like nano or vim to create your shell script. For example, to create a file named create_file.sh, use the following command:
nano create_file.sh
Add Script Content: Write the script to create a file. For example:
in 
#!/bin/bash

# Script to create a file
echo "Enter the name of the file to create:"
read filename

# Create the file
touch "$filename"

echo "File '$filename' has been created."

4. Save the Script: Save the file by pressing Ctrl+O, then Enter, and exit by pressing Ctrl+X.
5. Make the Script Executable: Run the following command to make the script executable:
chmod +x create_file.sh
6.Run the Script: Execute the script using:
./create_file.sh

