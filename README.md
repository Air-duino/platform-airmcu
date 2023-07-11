# platform-airmcu
AIRM2M MCU: development platform for PlatformIO 


- 2023/7/11: Preliminary platfrom.json & /boards/air001.json completed

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = air001
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/Air-duino/platform-airmcu.git
board = ...
...
```


# Configuration

Please navigate to [documentation](https://docs.platformio.org/page/platforms/air001.html).
