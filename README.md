**OLA trigger config to control Yeelight Candela Light with DMX (Art-Net, sACN or via DMX input)**

**Requirements**

* [OLA](https://www.openlighting.org/ola)
* [Candelabrum](https://github.com/MikeWent/candelabrum)
* [Yeelight Candela Light](https://www.yeelight.com/en_US/product/gingko)

**Installation**
  
* Download the [yeelight-candela-light.conf](yeelight-candela-light.conf) file and edit the configuration section

[OLA trigger documentation](https://www.openlighting.org/ola/advanced-topics/ola-dmx-trigger/)

**Usage** 

* Before running ola_trigger, make sure that olad is running and the universe has been configured with a DMX512 source.  
The config file is provided on the command line:

`ola_trigger yeelight-candela-light.conf`
