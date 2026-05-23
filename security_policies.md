Do security groups support both "allow" and "deny" rules? Explain how they handle traffic filtering.
Security groups operate only using "allow" rules; they cannot be used to explicitly deny traffic.

Describe what happens to all inbound traffic by default, and explain what happens to all outbound traffic by default if left unrestricted.
By default, all inbound traffic is blocked, while all outbound traffic is allowed.

Are EC2 instances internally aware of the security groups applied to them, or are they applied externally? Can one security group be reused across multiple instances?
Security groups are applied externally, meaning EC2 instances themselves are not aware of them.
A single security group can be associated with multiple EC2 instances.

| Port | Protocol | Purpose |
|------|-----------|----------|
| 22 | SSH (Secure Shell) | Secure remote access and command-line management of servers |
| 21 | FTP (File Transfer Protocol) | Transfers files between computers over a network |
| 80 | HTTP (HyperText Transfer Protocol) | Delivers standard web traffic for websites |
| 443 | HTTPS (HyperText Transfer Protocol Secure) | Delivers encrypted and secure web traffic using SSL/TLS |
| 3389 | RDP (Remote Desktop Protocol) | Remote graphical desktop access to Windows systems |