## [deCONZ](https://phoscon.de) Helm Chart

### Add the chart using following command:
```
helm repo add rpi-helm-deconz https://0bu.github.io/rpi-helm-deconz
```

### Installation
```
helm install deconz rpi-helm-deconz/deconz \
--set host=pi4a \
--set loadBalancerIPs=192.168.1.26 \
--set device=/dev/ttyUSB0 \
--set vncPassword=deconz
```
