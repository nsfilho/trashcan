# Trashcan Configs and Mods

## Introduction

At this repository, I will show some important stuffs of I learned about my little Eachine Trashcan.

## Betaflight

All configurations in this repo are made for Betaflight `4.2.8` version. My recommendation is to clear your configuration before use this.

The main goal of this configuration is to `simulate` (or approximately) trashcan to fly attitude of my 5 inch quad (drone).

**Important things:**

1. I'm using JESC Firmware at 48Khz;
2. I'm using XT30 connector (not ph connector);
3. I'm using a good Lipo Battery (2s Coddar HV 450mah XT30);
4. I removed the led strips bar;
5. I'm using FR-Sky at D8 (because of a very well documented problem about Crazybee F4 with D16);
6. With this configuration, I flew about 6 min;

### Files

-   [Diff all](BTFL_cli_TRASHCAN_20210403_164840.txt)
-   [Dump all](BTFL_cli_TRASHCAN_20210403_164853.txt)

### Re-binding or Binding

Using your betaflight 7.x (or higher), connect to your drone and write in CLI:

```
bind_rx
```
