# Jæren korn & malt
measure environment at Jæren korn & malt

```
sudo apt update
sudo apt upgrade
sudo apt install python3-pip
sudo apt install influxdb-client

```


### Setup the 1-wire bus on raspberry Pi 3.
```
sudo raspi-config
```
Select “Interfacing Options” and enable 1-wire

```
sudo modprobe w1–gpio
sudo modprobe w1-therm
```
```
sudo vi /etc/modules
```
add modules to automatic load on start-up
```
# /etc/modules: kernel modules to load at boot time.
#
# This file contains the names of kernel modules that should be loaded
# at boot time, one per line. Lines beginning with "#" are ignored.

w1-gpio
w1-therm
```


### Setup InfluxDB



### Setup Grafana

https://grafana.com/grafana/download


### Script

pip is installed by default in Raspberry Pi OS Desktop images (but not Raspberry Pi OS Lite). You can install it with apt:

```
sudo apt install python3-pip
python3 -m pip install influxdb

```


ESP8266 (Lolin D1 Mini - https://www.aliexpress.com/item/32529101036.html?spm=a2g0o.productlist.0.0.569d25ceHzKUd8&algo_pvid=8910803e-937f-40a5-bae4-925ebbcc8df1&algo_exp_id=8910803e-937f-40a5-bae4-925ebbcc8df1-0 )

* DHT22 Sensor
* ESPHome Software
