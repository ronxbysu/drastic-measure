# Drastic Measure

- disable wi-fi switching off

```commandline
    allow-hotplug wlan0
    iface wlan0 inet manual
    // wpa-conf /etc/wpa_supplicant/wpa_supplicant.conf
    wireless-power off

    allow-hotplug wlan1
    iface wlan1 inet manual
    // wpa-conf /etc/wpa_supplicant/wpa_supplicant.conf
    wireless-power off
```

- install Java
```commandline
    sudo add-apt-repository ppa:webupd8team/java
    sudo apt-get update
    sudo apt-get install oracle-java8-installer
```
- install OH2

    https://www.openhab.org/docs/installation/linux.html#installation

- add openhab user to group
```commandline
    sudo adduser openhab dialout
```

- check system monitor
```commandline
    sudo armbianmonitor -m
```





