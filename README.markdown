# Cybersecurity Internship Task 5: Network Traffic Analysis

## Author

- **Name**: Neel Bhatt
- **Date**: June 30, 2025
- **Repository**: Cybersecurity-Task5

## Objective

Capture live network packets and identify basic protocols using Wireshark on Kali Linux.

## Tools Used

- **Wireshark**: A free packet analyzer for capturing and analyzing network traffic.

## Steps Performed

1. Installed Wireshark and launched it on an active network interface.
   
   ![image](https://github.com/user-attachments/assets/f5c4a168-8d8e-4f6f-ac5c-b9faeeb38b44)

2. Generated traffic by browsing a website and pinging a server.
   
   ![image](https://github.com/user-attachments/assets/00294179-faea-44ed-a571-2d232816e0b8)

3. Captured packets for \~1 minute and saved the file.
   
   ![image](https://github.com/user-attachments/assets/4cebe852-8dd7-47bd-80be-0e05f58708a5)

4. Filtered packets to identify HTTP, DNS, and TCP protocols.
   
   4.1. TCP
   
    ![image](https://github.com/user-attachments/assets/09bd4919-fd77-4a80-8d0e-d5f9b2268a58)
   
   4.2. HTTP
   
    ![image](https://github.com/user-attachments/assets/47a55d8a-d85f-44e7-84c4-4887df09ad14)
   
   4.3. DNS
   
    ![image](https://github.com/user-attachments/assets/92ea0f06-013e-485c-ac0b-48758f7d090e)

5. Documented findings in a report.

## Files Included

- `network_capture.pcapng`: The captured packet file for analysis.
- `analysis_report.txt`: Summary of identified protocols and packet details.

## Key Learnings

- Learned to use Wireshark for packet capture and filtering.
- Identified key protocols (HTTP, DNS, TCP) and their roles.
- Understood basic network traffic analysis techniques.

## Challenges

- Ensured sufficient traffic generation within the time limit.

## Acknowledgments

- **Elevate Cybersecurity Internship**: For this learning opportunity.
- **Neel Bhatt**: For completing the task efficiently.

This repository represents my work for Task 5, submitted with permission.
