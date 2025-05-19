# Lenovo Unlocker : [https://alien.raaz.info.np/server/unlock/lenovo/](https://alien.raaz.info.np/server/unlock/lenovo/)
 
## Description
Lenovo Unlocker Coded By Hackeraj. It has capability to unlock including EC 1KB / 128KB / 256KB, and Wireless Unlocking.

## Features
* [x] Password ROM bypass (2012 and older)
      - Most ThinkPads from 2012 and older (3rd gen Intel and older) use a 24-series dedicated password ROM. It can often be bypassed during boot by shorting the SDA and SCL pins together. Other times, flashing the ROM may be required.
* [ ] DXE password bypass driver injection (2012-2018)
      - For newer machines (2012-2018, 4th to 8th gen Intel), the password itself is stored in the EC. BIOS must be modified and re-flashed to insert a special driver that will allow bypassing the BIOS password. Refer to https://www.badcaps.net/forum/showthread.php?t=87588 and https://www.badcaps.net/forum/showthread.php?t=81573
* [ ] Flashing EC (SMSC MEC, 2019-*)
      - On the latest generations of ThinkPads, the security issue that allowed to inject the DXE driver and bypass the password does not exist anymore. The password is still stored inside the EC, in a write-only region.
However, it appears that dumping the EC with a dedicated programmer, erasing it and flashing back can actually clear the password. See: https://www.badcaps.net/forum/showth...t=95736&page=5
https://www.badcaps.net/forum/showthread.php?t=111439
* [x] EC BIOS
    * [x] 1KB
         - starting_offset: 300
         - ending_offset: 380
         - Fill By 00 
    * [x] 128KB - Flashing EC (ENE KB9012)
         - starting_offset: 200
         - ending_offset: 022F
         - Fill By 00
    * [x] 256KB - Flashing EC (Nuvoton NPCE288 NPCE388)
         - Starting_offset: 36010
         - Ending_offset: 36CE0
         - Fill by 00
* [ ] Wireless Unlocking

# :octocat: Developer
1. [Hackeraj](https://www.facebook.com/HackerajOfficial/)
2. [Dibya Joshi](https://www.facebook.com/dibya.joshi.99)
3. [Umesh Gupta](https://www.facebook.com/umeshkumarguptanp/)

## Lenovo Unlocker Related Tutorials


## References
- [https://www.badcaps.net/forum/showthread.php?t=111439](https://www.badcaps.net/forum/showthread.php?t=111439)
- [https://www.badcaps.net/forum/showpost.php?p=1062024&postcount=19](https://www.badcaps.net/forum/showpost.php?p=1062024&postcount=19)
- [https://www.badcaps.net/forum/showthread.php?t=117284](https://www.badcaps.net/forum/showthread.php?t=117284)

[Facebook](https://www.facebook.com/HackerajOfficial/)
[Instagram](https://www.instagram.com/hackeraj/)
[Youtube](https://www.youtube.com/Hackeraj/)
[Github](https://www.github.com/HackerajOfficial/)
