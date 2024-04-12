# SSH Brute-Forcer

This Python script performs SSH brute-force attacks on remote servers using a list of usernames and passwords.

## Features

- Utilizes Paramiko library for SSH connections.
- Offers an option to execute a command upon successful authentication.
- Displays a banner using PyFiglet library.

## Requirements

- Python 3.x
- Paramiko library (`pip install paramiko`)
- PyFiglet library (`pip install pyfiglet`)

## Usage

1. Clone the repository:

git clone https://github.com/yourusername/ssh-brute-forcer.git


2. Navigate to the directory:

cd ssh-brute-forcer


3. Run the script with the required arguments:

```bash
python ssh_brute_forcer.py --users /path/to/users.txt --passes /path/to/passwords.txt --host <remote_host_ip> --port <remote_host_port> --cmd "<command_to_execute>"

--users: Absolute path of the file containing usernames.
--passes: Absolute path of the file containing passwords.
--host (optional): IP address of the remote SSH server (default: localhost).
--port (optional): Port of the SSH server (default: 22).
--cmd (optional): Command to execute upon successful authentication.
```

Wait for the script to finish. If valid credentials are found, the script will display them and, if specified, execute the command.

# Disclaimer

This tool is intended for educational and testing purposes only. Unauthorized access to computer systems is illegal and unethical. Only use this tool on systems you have explicit permission to test.

# License

This project is licensed under the MIT License - see the LICENSE file for details.
