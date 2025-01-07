<<<<<<< HEAD
=======
# Pr.-Windows-Firewall
>>>>>>> afc073825ecad161b788130e871aaca0d4441a04
This project was completed legally on the TryHackMe platform, which provides a safe environment for learning cybersecurity and performing practical exercises. All actions described in the project were carried out within the framework of educational tasks using the provided virtual machines and resources in accordance with the platform’s rules.

In this project, I worked with the Windows Defender Firewall — the built-in firewall of the Windows operating system. My task was to create rules to block incoming and outgoing traffic, as well as set up custom rules to restrict access to certain services.

First, I started the virtual machine with Windows using the provided credentials and connected to it via RDP. Then, I opened the Windows Defender Firewall interface to familiarize myself with its main functions and settings, such as network profiles and security configurations for different types of networks (e.g., home and public networks).

I created several custom rules to block traffic on ports 80 (HTTP) and 443 (HTTPS), which allowed me to limit access to websites and test the effectiveness of these settings. To do this, I used the "Advanced Settings" section in the firewall’s control panel, where I created rules for outbound traffic by configuring the protocols and ports that needed to be blocked.

After creating these rules, I tested the firewall’s functionality by trying to visit the site located at http://10.10.10.10. As a result, with the blocking rules activated, I received an error message, confirming that the firewall settings were correctly applied.

This project helped me gain a better understanding of how firewalls work, how to configure them, and the importance of creating proper security rules to protect network infrastructure.
