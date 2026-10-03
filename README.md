# Navee Flasher

Android sideload APK for flashing Navee ESC firmware over BLE.

**Not** on Play Store. **Not** affiliated with Navee.

## Download

Get the APK from **[Releases](https://github.com/scooterteam/navee-flasher/releases)**.

## Install

1. Allow install from unknown sources for your file manager / browser
2. Open the APK and install
3. Grant Bluetooth (+ location on older Android)

## MCU speed table in OTA

Whether stock ESC MCU OTAs embed an editable region speed-limit table (`yes` / `no` / `mixed` = some builds only). May be incomplete or wrong for some SKUs.

Layout / flasher quirks (`keys+limits` vs `keys+sbox`, T2416 multi-copy CNESDE, CRC Dual/ImgOnly): [docs/platform/navee_region_tables.md](../../../../docs/platform/navee_region_tables.md).

| Model | Model ID | Speed table |
|---|---|---|
| E20 | 4001 | mixed |
| EasyRide 20 | 4001 | mixed |
| E20 Lite | 10101 | yes |
| E25 | 4101 | mixed |
| EasyRide 25 Pro | 4101 | mixed |
| E25 Go | 9101 | yes |
| E45 Pro | 10001 | no |
| E45 Pro | 12801 | no |
| E60 Pro | 10301 | no |
| E60 Pro | 10601 | no |
| E60 Pro | 12901 | no |
| G5 | 5401 | no |
| G5 Max | 5701 | no |
| G5 Pro | 5601 | no |
| GT3 | 3501 | mixed |
| GT3 Max | 3601 | mixed |
| GT3 Pro | 3401 | mixed |
| GT3 Pro | 12601 | no |
| GT5 Max | 8501 | no |
| GT5 Pro | 8401 | no |
| K100 | 5201 | no |
| K100 Max | 5001 | no |
| K100 Pro | 5101 | no |
| N65I | 1101 | mixed |
| N65I II | 6001 | no |
| N65I II | 10701 | no |
| NT3 Max | 12701 | no |
| NT3 Pro | 12401 | no |
| NT5 Max | 9301 | no |
| NT5 Max | 9701 | no |
| NT5 Max+ | 9201 | no |
| NT5 Turbo | 9201 | no |
| NT5 Ultra | 9401 | no |
| NT5 Ultra X | 9501 | no |
| S2 | 9901 | yes |
| S40 | 1601 | mixed |
| S40 SLD25 SLS40 | 1601 | yes |
| S60 | 2501 | mixed |
| S65 | p2223 | no |
| S65C/D | t2214 | yes |
| ST3 | 3701 | mixed |
| ST3 Pro | 3801 | no |
| ST3 Pro | 12501 | no |
| ST5 Max | 7801 | no |
| ST5 Pro | 4901 | no |
| UT3 Max | 10501 | no |
| UT5 Max | 8901 | no |
| UT5 Ultra X | 9601 | no |
| V25 | 701 | mixed |
| V25i | 701 | mixed |
| V25I Pro II | 4301 | no |
| V3 Pro | 4201 | mixed |
| V40 | t2208 | yes |
| V40i | 1301 | mixed |
| V40i Pro | 1301 | mixed |
| V40I Pro II | 4401 | mixed |
| V45I | 10201 | no |
| V50 | t2211 | yes |
| V50I Pro | 1201 | mixed |
| V50I Pro | 1291 | mixed |
| V50I Pro II | 4501 | no |
| XT5 Max | 5901 | no |
| XT5 Pro | 5301 | no |
| XT5 Ultra | 5801 | no |

## License

[CC BY-NC-SA 4.0](LICENSE) — ScooterTeam community tool. Flash at your own risk.

Source is not published in this repository.
