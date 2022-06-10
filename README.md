# Synology-Bridging

## Enable vSwitch bridging between two Ethernet ports on Synology NAS

This script enables you to create a network bridge between two Ethernet ports on
your Synology NAS.

## Prerequisites

- DSM >= 6.1
- A Synology NAS with at least two Ethernet ports
- Administrator account on DSM

## Instructions

- Upload the script to an arbitrary folder (preferably one that only
  Administrators can change)
- Launch Control Panel on DSM and go to Task Scheduler
- Click the “Create” button on the top. Select “Triggered Task” → ”User-defined
  script”
- Type any title you wish
- Choose the “Enable Task” box
- Move to “Task Setting” tab
- Type into the text box:

```
bash /path/to/vswitch_bridge
```

- Click the “OK” button
- Reboot if you want to
