<h1>Port Scanner</h1>
<h2>Description</h2>
Created a Python multithreaded TCP port scanner designed to identify open ports on a target system.

<h2>The program works by:</h2>

Prompting a user to enter:
  - A target IP address
  - A startign port number
  - An ending port number
- Iterating through the specified range of ports
- Attempting to establish a TCP connection to each port using the socket module
- Using ThreadPoolExecutor to scan multiple ports simultaneously for faster performance
- This identifies open ports based on successful connection attempts (connect_ex() returns 0)
- It also display's real-time scanning progress in the terminal
- Lastly, it outputs a final list of all open ports discovered on the target system

<br />

<h2>Key features the program has and what it's intended to do is:</h2>

- Multithreaded scanning for improved speed
- User-defined IP and port range
- Real-time progress updates
- Detection and reporting of open ports
- Input validation for port ranges
 
<h2>Pictures:</h2>

