## Firmware Updates
This folder contains the original firmware updates, [originally available on
the Dell website](https://downloads.dell.com/published/pages/xps-15-9560-laptop.html).

The file checksums are from the corresponding download page for each firmware
revision. You can verify the checksums using `sha256sum` (`shasum -a 256` on
macOS):

    $ sha256sum -c SHA256SUMS
    XPS_15_9560_1.0.2.exe: OK
    XPS_15_9560_1.0.3.exe: OK
    XPS_15_9560_1.1.3.exe: OK
    XPS_15_9560_1.2.4.exe: OK
    XPS_15_9560_1.3.3.exe: OK
    XPS_15_9560_1.3.4.exe: OK
    XPS_15_9560_1.4.0.exe: OK
