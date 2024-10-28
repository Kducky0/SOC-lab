Configuration Guide

Windows VM Configuration
1. Disable Tamper Protection and other security features as described in the project.
2. Set Safe Boot options and modify registry keys to disable certain services.

LimaCharlie EDR Installation
1. Create a account on LimaCharlie.
2. After creating an organization, add a sensor for Windows and follow the installation instructions provided by LimaCharlie.
3. Configure Sysmon event logs for telemetry collection.

Setting Up the Attack System
1. SSH into the Linux VM and download Sliver C2 framework.
2. Generate C2 session payload and transfer it to the Windows VM using Python HTTP server.
