# Cisco-2960-basics
My Cisco 2960 home lab — console setup, management IP, and basic configuration
# What This Is
Setting up my Cisco Catalyst 2960 switch from scratch — console connection, hostname, management IP, and basic configuration.
#Equipment
- Cisco Catalyst WS-C2960-48TT-L Switch
- USB-to-RJ45 Console Cable
- PuTTY Serial Console Client
# Steps Completed:

# 1. Console Connection
- Connected via USB-to-RJ45 cable → PuTTY → COM port
- Settings: 9600 baud, 8 data bits, No parity, 1 stop bit

#2. Basic Setup
- Set hostname to: `Anthonia_homelab`

#3. Management IP
- Set Vlan1 IP: `192.168.1.200 /24`

4.Security Best Practices
- Enabled `service password-encryption` to protect configuration
- Created user account for management access
- Sensitive credentials redacted for security

#5. Save Configuration
- Ran `copy running-config startup-config` — saved successfully ✅
# screenshots 
- `show ip interface brief` — Management IP configured
- `show running-config` — Full configuration (credentials redacted)
- show vlan brief 
#Notes
- Management interface shows 'up/down' — waiting for USB-to-Ethernet adapter
- Console access always available as backup





