BHP Net Tool

The "BHP Net Tool" is a Python script designed for network interaction and exploration. It leverages the capabilities of the socket library to facilitate communication between networked machines. This tool provides functionalities such as creating a command shell, executing commands on remote machines, uploading files, and managing network connections.

Features:

Command Shell: Establish a remote command shell on a target machine, allowing direct interaction and execution of commands.
Command Execution: Run specified commands on the remote machine and receive the output.
File Upload: Upload files to the remote machine's file system from the local machine.
Network Communication: Communicate between client and server using sockets.
Threading: Utilize multithreading to handle multiple client connections simultaneously.
Usage:
The tool's functionality is controlled through command-line arguments:

-c or --command: Enter command shell mode on the target machine.
-e or --execute: Execute a specific command on the target machine.
-l or --listen: Listen for incoming connections.
-p or --port: Specify the port for communication (default is 5555).
-t or --target: Specify the target IP address.
-u or --upload: Upload a file to the target machine.
Examples:

Run in command shell mode: python script.py -c -t 192.168.1.100
Execute a command: python script.py -e "ls -l" -t 192.168.1.100
Listen for incoming connections: python script.py -l -p 8080
Upload a file: python script.py -u myfile.txt -t 192.168.1.100
Please note that this tool is intended for educational purposes and network exploration. Ensure that you have the necessary permissions before using it in any network environment
