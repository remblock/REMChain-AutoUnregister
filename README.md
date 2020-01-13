# REMChain-AutoUnregister

This script will unregister a block producer if they fail to produce blocks by a certain number of minutes.

Edit Config:

nano remblock/auto-failover/config

```
sudo wget https://github.com/remblock/REMChain-AutoUnregister/raw/master/producer-unregister && sudo chmod u+x producer-unregister && sudo ./producer-unregister
```
