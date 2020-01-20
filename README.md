# REMChain-Automated-Unregprod

#### This script will unregister a block producer if they fail to produce blocks within a specified time frame. The time frame can be adjusted according to the block producers tolerance/preference.

***

### Setup Automated-Unregprod:

```
sudo wget https://github.com/remblock/REMChain-Automated-Unregprod/raw/master/remchain-unregprod && sudo chmod u+x remchain-unregprod && sudo ./remchain-unregprod
```

***

### Edit Automated-Unregprod Config:

```
nano remblock/remchain-unregprod/config
```

### Edit Automated-Unregprod (Enable/Disable):

```
nano /root/check_unregprod
```

#### Edit file to "true" to enable and "false" to disable
