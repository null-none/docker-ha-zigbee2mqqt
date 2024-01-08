# docker-ha-zigbee2mqqt
Home assistant and Zigbee2MQTT in Docker

### Install environment

```bash
docker-compose up

$ sudo dmesg
…
usbcore: registered new interface driver ch341
usbserial: USB Serial support registered for ch341-uart
ch341 3–1:1.0: ch341-uart converter detected
usb 3–1: ch341-uart converter now attached to ttyUSB0

$ ls -l /dev/ttyUSB0
crw-rw — — 1 root dialout 188, May 16 19:15 /dev/ttyUSB0
```

