# pfSense-related
Configurations and Settings related to pfSense Firewall


### Cmd
```bash
pfctl -d
```

This is mandatory to allow pfSense access to WAN

If you want a permanent rule:

Go to Firewall > Rules > LAN in the Web UI (if you manage to access it later).

Add a rule:

Protocol: ANY

Source: Any

Destination: LAN IP / This Firewall

Action: Allow
