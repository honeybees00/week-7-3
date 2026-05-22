# week-7-3
security groups serve as virtual firewalls, and how to configure rule settings based on the principle of least privilege.

Do security groups support both "allow" and "deny" rules? Explain how they handle traffic filtering. Security groups work as gatekeepers; only the ports that match the rules get through, yes . depends on the port and SSH.

Describe what happens to all inbound traffic by default, and explain what happens to all outbound traffic by default if left unrestricted.
The protocol is that any IP can connect from any source, and all outbound is allowed by default unless it is restricted. All inbound are blocked by default 
Are EC2 instances internally aware of the security groups applied to them, or are they applied externally? Can one security group be reused across multiple instances?
No, they are not aware of each other.

Step 3: Core Port Mapping Matrix


In your security_policies.md file, build a reference table mapping the standard networking ports described in the class. Match each port number with its precise protocol name and purpose:

Port 22-linux

Port 21- ftp tranfers to the shared folder
Port 80  HTTP access without SSL
Port 443 website with SSL encryption
Port 3389 RDP remote to Windows access
 
