# wol-app
An Android App to send magic wake-on-lan packets to the local network. The goal is to create an all-in-one app to discover the devices on the network by hardware ID, IP, and hostname in order to allow the user to select which machines are configured to allow magic packets.

To Do:
- Relearn how to write java
- Enumerate the network for live IPs
- Enumerate IPs: reverse DNS and MAC
- Allow user to select which devices to retain / enable as wol targets
- Send a wol packet
- Let the user know when the host is live (ping)
- Make it pretty
- Make it multithreaded so multiple machines can be started simultaniously
- Create instructions to setup wake-on-lan
