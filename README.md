Docker General
==============


### Volume Configuration File
```
vi /etc/docker/daemon.json
{                                                                                                                                                             
    "data-root": "/home/docker",
    "storage-driver": "devicemapper"
}

```


### CentOS - System CTL
```
systemctl start docker
systemctl stop docker
systemctl daemon-reload
systemctl restart docker
```

