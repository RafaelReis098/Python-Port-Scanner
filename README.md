# Python Port Scanner

This is a simple Python script that scans for open ports on a target system within a specified range. The script uses the `socket` library to check for open connections on each port.

## Table of Contents

- [Usage](#usage)
- [How It Works](#how-it-works)
- [Customization](#customization)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/python-port-scanner.git
2. Navigate to the project directory:
   ```bash
   cd python-port-scanner
3. Run the script:
   ```bash
   python port_scanner.py
4. Follow the prompts:
   ```bash
   Enter the target IP address.
   Enter the starting port number.
   Enter the ending port number.
How It Works
The script iterates over the specified range of ports and attempts to connect to each port using a socket. If the connection is successful, it prints that the port is open; otherwise, it prints that the port is closed.

Customization
You can customize the target IP address and port range by modifying the following variables in the script:
```bash
target_ip = "127.0.0.1"  # Replace with the target IP address
start_port = 1           # Replace with the starting port number
end_port = 1024          # Replace with the ending port number
```
Adjust the values based on your specific requirements.

Example:
```bash
Scan ports on the local machine (127.0.0.1) in the range 1 to 1024
scan_ports("127.0.0.1", 1, 1024)
```
Feel free to contribute to the project by improving the code or adding new features!

Contributing
1.Fork the repository.
2.Create a new branch (git checkout -b feature/your-feature-name).
3.Make your changes and commit them (git commit -am 'Add new feature').
4.Push the changes to your branch (git push origin feature/your-feature-name).
5.Create a pull request.

License
This project is licensed under the MIT License.
```bash

Replace "your-username" with your GitHub username or the organization name where you host the repository. Customize the content as needed for your specific project.
