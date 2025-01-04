Name = Rajdeep Naskar
Company = CODTECH IT SOLUTIONS
ID = CT6WDS2467
Domain = CYBER SECURITY AND ETHICAL HACKING
Duration = November to 10th january 2025
Topic = vulnerability scanning tool

OVERVIEW OF THE PROJECT:

Import necessary libraries:
  subprocess: For system commands.
  nmap: For network scanning.

scan_host(ip_address) function:
  Creates an nmap.PortScanner object.
  Scans the specified ip_address.
  Iterates through hosts, protocols, and ports to extract information like host name, IP address, protocol, port number, and state (open, closed,   filtered).
  Prints the collected information.
  Includes a try-except block to handle potential errors during scanning.
  
scan_network(network) function:
  Scans the specified network range.
  Creates a list of hosts and their status (up/down).
  Prints the list of hosts and their status.
  Includes a try-except block to handle potential errors during network scanning.

To use this tool:
  Install the nmap library:
    pip install python-nmap
  Save the code as a Python file (e.g., vulnerability_scanner.py).
  Run the script from your terminal:
    python vulnerability_scan.py
  Follow the on-screen instructions to select the scanning option and provide the necessary input.  
