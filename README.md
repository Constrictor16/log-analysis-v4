# Advanced Log Analysis Project (v4)

## Objective
Analyze log data to identify suspicious login activity, prioritize risk levels, and detect potential security threats.

## Tools Used
- Command Prompt (CMD)
- find command

## Log Data
The log file contains multiple login attempts, including failed and successful logins.

## Results
- Total failed login attempts: 11  
- Total successful logins: 2  

## IP Breakdown

**192.168.1.200**
- 1 failed attempt
- 1 successful login

**192.168.1.100**
- 3 failed attempts
- 1 successful login

**10.0.0.9**
- 6 failed attempts

**172.16.0.30**
- 1 failed attempt

## Analysis
IP 192.168.1.200 and 192.168.1.100 show failed attempts followed by successful logins, indicating potential account compromise (high risk).

IP 10.0.0.9 shows repeated failed attempts, suggesting a brute-force attack (medium risk).

IP 172.16.0.30 shows minimal failed activity (low risk).

## Conclusion
This analysis demonstrates how log monitoring can detect suspicious activity, prioritize threats, and support cybersecurity investigations.
