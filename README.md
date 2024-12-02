# Firewall Configuration Project

## Description
This project demonstrates an attempt to block HTTP traffic from port 80, ensuring that users only access secure websites via HTTPS

## Objective
- Block insecure HTTP traffic on port 80 using a firewall

## Steps taken
1. Accessed the windows defender firewall with advanced security
2. Created an **Outbound rule** to block all connections through port 80
3. Created a complementary **inbound rule** for the same purpose
4. Tested the rule using http:// websites

## Screenshots
![fw-ss1](https://github.com/user-attachments/assets/3d38f28b-1dfc-4178-8852-583d620719b2)

![fw-ss2](https://github.com/user-attachments/assets/1b801ea0-c273-4143-b092-963462e7174c)

![fw-ss3](https://github.com/user-attachments/assets/d48208ab-ee69-43a2-88a0-89cd45aee934)

![image](https://github.com/user-attachments/assets/79e7ecb1-4dd3-4551-844d-bf495659d875)


## Challenges 
- The rule did not succesfully block all HTTP traffic as expected. Some potential reasons include:
    1. Cached DNS settings or browser cache
    2. Other network-level configurations
    3. Port 80 traffic bring routed through an alternate method

## Lessons learned
- Gained hands-on experience configuring Windoes defender firewall with advanced security
- Understood the limitations of relying solely on a single firewall rule for traffic blocking
- Realized the importance of testing configurations thoroughly
- Use 3rd party firewall solutions or proxies for better control
