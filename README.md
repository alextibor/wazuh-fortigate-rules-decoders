# wazuh-fortigate-rules-decoders

This project provides a robust set of decoders and rules designed to integrate Fortigate logs with Wazuh, developed based on the Fortigate Log Reference for versions 7.0.14, 7.2.7, 7.2.8, and 7.4.3. 

I am working hard on that to improve and expand the functionalities. Leave a star and follow this repo for updates.

## Features

- **738 Decoders**: For decoding and analyzing Fortigate logs.
- **1387 Rules**: For categorizing specific logs, facilitating monitoring and event analysis.

## Installation

1. **Copy the decoders and rules to your Wazuh Manager**

   - Copy `0100-fortigate_decoders.xml` to `/var/ossec/etc/decoders/`
   - Copy `0391-fortigate_rules.xml` to `/var/ossec/etc/rules/`

2. **Restart the Wazuh Manager**

   ```bash
   systemctl restart wazuh-manager
   ```


