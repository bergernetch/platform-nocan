# NoCAN: OMZLO NoCAN CANZERO development platform for [PlatformIO](https://platformio.org)

The Omzlo CANZERO is an Arduino-compatible board with builtin CANbus networking and designed to be connected to a NoCAN network, enabling the creation of wired IoT applications.
Based on https://github.com/platformio/platform-atmelsam

* [Home](https://www.omzlo.com/articles/canzero)

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:


```ini
[env:canzero]
platform = https://github.com/bergernetch/platform-nocan.git # or install the platform via url and just use "platform = nocan" here
framework = arduino
board = nocan_canzero
upload_port = 1 # nocan node id
...
```

# Configuration

