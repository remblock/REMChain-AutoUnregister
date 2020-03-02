# REMChain-Automated-Unregprod

#### This script will unregister a block producer if they fail to produce blocks within a specified time frame. The time frame can be adjusted according to the block producers tolerance/preference.

***

### Setup REMChain-Unregprod:

```
sudo wget https://github.com/remblock/REMChain-Automated-Unregprod/raw/master/remchain-unregprod && sudo chmod u+x remchain-unregprod && sudo ./remchain-unregprod
```

***

### Setup Testchain-Unregprod:

```
sudo wget https://github.com/remblock/REMChain-Automated-Unregprod/raw/master/testchain-unregprod && sudo chmod u+x testchain-unregprod && sudo ./testchain-unregprod
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

#### Edit file to "on" to enable and "off" to disable
