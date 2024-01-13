# NTAG-I2C-Eval-Board

This is a small board built to use the NXP NTAG I2C _Plus_ 2K, with supporting hardware and a Class 4 PCB Antenna. 

This board is meant to test mobile smartphone applications for the NTAG I2C _Plus_ series.

![Schematic Image](https://cloud-din6btxn9-hack-club-bot.vercel.app/0image.png)

![PCB Render](https://cloud-3zj57agtd-hack-club-bot.vercel.app/0screenshot_2023-11-14_at_10.27.56_am.png)

Use the following command to initialize the board for flashing (configure CC bits): 

A2:03:E1:10:6D:00,A2:04:03:04:D8:00,A2:05:00:00:FE:00

Theoretically, this should provide up to 872 bytes of EEPROM out of the 1024 or 2048 onboard the chip. However, this isn't always achievable and lower sizes will work more reliably.

I used [this app](https://apps.apple.com/us/app/nfc-tools-for-desktop/id1392471092?mt=12) for iOS. Go into Other > Advanced NFC Commands. 

Depending on what app you're using to flash this, you'll likely need to go into Advanced Settings and find the option that allows you to flash this command directly. 

## BOM:
| Part Number        | Quantity | Distributor | Distributor #               |
|--------------------|----------|-------------|-----------------------------|
| XZCM2MOK54WA-1VF   | 1        | Digikey     | 1497-XZCM2MOK54WA-1VFCT-ND  |
| NT3H2211W0FT1X     | 1        | Digikey     | 568-12905-1-ND              |
| C0805C224K1REC7800 | 1        | Digikey     | 399-C0805C224K1REC7800CT-ND |
| RC0805FR-07100RL   | 1        | Digikey     | 311-100CRCT-ND              |
