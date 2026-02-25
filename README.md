# upnphelper
This is probably my first actually useful tool, its simple, allows for port-forwarding through UPnP fast and easy.
### Documentation.
First of all, if you see anything other than UPnP device found, you cannot use this tool. Theres 2 codes, one where it doesnt find it and second is a program error. Also you need to be NOT blocked by CGNAT, and not only that, you need UPnP enabled on ur router.

Next, if you forward a port but its inaccessible or something happened, you probably have your windows firewall settings to default.

Press WIN + R and type "wf.msc". Press Windows Defender Firewall Properties and set Inbound connections to allow. At the top, you will see all sorts of profiles, do the same thing on each one.

If you used an online port checker and did the firewall configuration, you probably need something running on that port for it to get recognised. Run something like a CS server, or a minecraft server or even host a website and THEN try it.

The program uses Open.NAT to connect with UPnP. Well that's all, you can go download the tool from the Releases tab.
