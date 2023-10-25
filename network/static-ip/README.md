# Static IP with nmtui

## Step 1

Start `nmtui` as with root privileges:

```
sudo nmtui
```

Select entry `Edit a connection`:

![](nm-step1.png)

## Step 2


Select button `Add`:

![](nm-step2.png)

## Step 3

Select `Ethernet` as type:

![](nm-step3.png)

## Step 4

Enter a name for the connection (eg. `Plant network`), choose a device (eg. `eth0` for the first interface) and select `Manual` as `IPv4 CONFIGURATION` mode. 

Enter IP address with prefix (eg `/24` for a `255.255.255.0` netmask) and fill in gateway and nameservers as necessary.

![](nm-step4.png)

Save the configuration by selecting `OK`. Exting `nmtui` and reboot the RevPi.