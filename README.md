# Goal

This script gets the gateway IP information taken from the dhcp logs, and adds a notice.log entry if the gateway address is identified

# Example 

This command

```bro -C -i wlp3s0 zeek-package-log-gateway-IP```

Will result in the following entry in ```notice.log``` if the IP address is identified

![notice.log]( https://raw.githubusercontent.com/stratosphereips/zeek-package-log-gateway-IP/main/images/notice.png )

