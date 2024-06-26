Linux in Vietnam - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Vietnam.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Vietnam/Desktop/README.md) and [notebooks](/Location/Vietnam/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 820

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MASSCOM VI... | L133                        | Notebook    | [12b6c6b515](https://linux-hardware.org/?probe=12b6c6b515) | May 06, 2024 |
| Acer          | Aspire A715-41G             | Notebook    | [b24efb4449](https://linux-hardware.org/?probe=b24efb4449) | May 06, 2024 |
| Acer          | Aspire A715-41G             | Notebook    | [aa9c440102](https://linux-hardware.org/?probe=aa9c440102) | May 01, 2024 |
| Dell          | G7 7588                     | Notebook    | [9745a22fe0](https://linux-hardware.org/?probe=9745a22fe0) | Apr 28, 2024 |
| Dell          | Latitude E5450              | Notebook    | [575668e003](https://linux-hardware.org/?probe=575668e003) | Apr 26, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [3e1d481314](https://linux-hardware.org/?probe=3e1d481314) | Apr 26, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [81b0d669d9](https://linux-hardware.org/?probe=81b0d669d9) | Apr 26, 2024 |
| HP            | Compaq 6520s                | Notebook    | [235863713b](https://linux-hardware.org/?probe=235863713b) | Apr 25, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [cf3db9398d](https://linux-hardware.org/?probe=cf3db9398d) | Apr 22, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [6eeb53e317](https://linux-hardware.org/?probe=6eeb53e317) | Apr 22, 2024 |
| AZW           | MINI S 10                   | Desktop     | [ae2d077638](https://linux-hardware.org/?probe=ae2d077638) | Apr 22, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [50f7cbb79a](https://linux-hardware.org/?probe=50f7cbb79a) | Apr 19, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [09c22645d8](https://linux-hardware.org/?probe=09c22645d8) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [a2fb569143](https://linux-hardware.org/?probe=a2fb569143) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [b70a3e9c9f](https://linux-hardware.org/?probe=b70a3e9c9f) | Apr 19, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [5357679252](https://linux-hardware.org/?probe=5357679252) | Apr 18, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [13af7544f2](https://linux-hardware.org/?probe=13af7544f2) | Apr 17, 2024 |
| Dell          | G7 7588                     | Notebook    | [06f5f64e59](https://linux-hardware.org/?probe=06f5f64e59) | Apr 14, 2024 |
| Dell          | Latitude E5570              | Notebook    | [91db6ada79](https://linux-hardware.org/?probe=91db6ada79) | Apr 13, 2024 |
| Dell          | 0D28YY A03                  | Desktop     | [894b628494](https://linux-hardware.org/?probe=894b628494) | Apr 12, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [1c61456dc2](https://linux-hardware.org/?probe=1c61456dc2) | Apr 11, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [c595905fcb](https://linux-hardware.org/?probe=c595905fcb) | Apr 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [05372f86e5](https://linux-hardware.org/?probe=05372f86e5) | Apr 10, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [8b430e632f](https://linux-hardware.org/?probe=8b430e632f) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [bf43ad7ffe](https://linux-hardware.org/?probe=bf43ad7ffe) | Apr 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [25dc9ad19d](https://linux-hardware.org/?probe=25dc9ad19d) | Apr 08, 2024 |
| Dell          | G7 7588                     | Notebook    | [8753ea1302](https://linux-hardware.org/?probe=8753ea1302) | Apr 05, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [bbb0e8daf4](https://linux-hardware.org/?probe=bbb0e8daf4) | Apr 02, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [d60c1ed904](https://linux-hardware.org/?probe=d60c1ed904) | Apr 02, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [5d12c5c26e](https://linux-hardware.org/?probe=5d12c5c26e) | Mar 31, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [142a42435b](https://linux-hardware.org/?probe=142a42435b) | Mar 30, 2024 |
| Lenovo        | Legion Pro 5 16IRX9 83DF    | Notebook    | [5457b4ef4c](https://linux-hardware.org/?probe=5457b4ef4c) | Mar 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S0HG00    | Notebook    | [f80e544ce6](https://linux-hardware.org/?probe=f80e544ce6) | Mar 22, 2024 |
| BBEN          | Cherry Trail CR             | Mini pc     | [ee5a042182](https://linux-hardware.org/?probe=ee5a042182) | Mar 19, 2024 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [99e78f54fd](https://linux-hardware.org/?probe=99e78f54fd) | Mar 18, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [a13b1aaa4d](https://linux-hardware.org/?probe=a13b1aaa4d) | Mar 18, 2024 |
| Lenovo        | XiaoXinPro 14 AHP9 83D3     | Notebook    | [468b8047e4](https://linux-hardware.org/?probe=468b8047e4) | Mar 15, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [af8cc61afe](https://linux-hardware.org/?probe=af8cc61afe) | Mar 14, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ba3ec85a8c](https://linux-hardware.org/?probe=ba3ec85a8c) | Mar 14, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [7cddb85911](https://linux-hardware.org/?probe=7cddb85911) | Mar 14, 2024 |
| Gigabyte      | G5 GD                       | Notebook    | [58ac2082b9](https://linux-hardware.org/?probe=58ac2082b9) | Mar 11, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [22f1633f40](https://linux-hardware.org/?probe=22f1633f40) | Mar 09, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [17ef9e97c9](https://linux-hardware.org/?probe=17ef9e97c9) | Mar 06, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [b68f17fbdf](https://linux-hardware.org/?probe=b68f17fbdf) | Mar 02, 2024 |
| MSI           | Modern 14 B11SBU            | Notebook    | [5a5e7d82d7](https://linux-hardware.org/?probe=5a5e7d82d7) | Feb 29, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [565e6c2d46](https://linux-hardware.org/?probe=565e6c2d46) | Feb 29, 2024 |
| Apple         | MacBookPro13,3              | Notebook    | [f6a0a37d75](https://linux-hardware.org/?probe=f6a0a37d75) | Feb 20, 2024 |
| Gigabyte      | G5 KD                       | Notebook    | [0743c222ba](https://linux-hardware.org/?probe=0743c222ba) | Feb 20, 2024 |
| ASUSTek       | PRIME H510M-F               | Desktop     | [21e4b5ffeb](https://linux-hardware.org/?probe=21e4b5ffeb) | Feb 20, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [ae67d4e82a](https://linux-hardware.org/?probe=ae67d4e82a) | Feb 19, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [ba02f5d2ae](https://linux-hardware.org/?probe=ba02f5d2ae) | Feb 18, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [efd4bd356f](https://linux-hardware.org/?probe=efd4bd356f) | Feb 17, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [111c375a02](https://linux-hardware.org/?probe=111c375a02) | Feb 17, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [2fc996bace](https://linux-hardware.org/?probe=2fc996bace) | Feb 17, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [5b9d9efd21](https://linux-hardware.org/?probe=5b9d9efd21) | Feb 17, 2024 |
| Dell          | Inspiron 3576               | Notebook    | [740a10ea1f](https://linux-hardware.org/?probe=740a10ea1f) | Feb 15, 2024 |
| OrangePi      | NEO-01                      | Notebook    | [9999d229d6](https://linux-hardware.org/?probe=9999d229d6) | Feb 09, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [8dbe3ddfaa](https://linux-hardware.org/?probe=8dbe3ddfaa) | Feb 08, 2024 |
| MSI           | GF63 Thin 10SC              | Notebook    | [0e9a586cf0](https://linux-hardware.org/?probe=0e9a586cf0) | Feb 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [5cbf6ef1b5](https://linux-hardware.org/?probe=5cbf6ef1b5) | Feb 06, 2024 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [33ad82eafa](https://linux-hardware.org/?probe=33ad82eafa) | Feb 05, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [e591b9e544](https://linux-hardware.org/?probe=e591b9e544) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6acefbaadc](https://linux-hardware.org/?probe=6acefbaadc) | Feb 01, 2024 |
| MSI           | Creator M16 A12UC           | Notebook    | [804a70b7f5](https://linux-hardware.org/?probe=804a70b7f5) | Jan 31, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [ed474939eb](https://linux-hardware.org/?probe=ed474939eb) | Jan 31, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [021f108e72](https://linux-hardware.org/?probe=021f108e72) | Jan 31, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ac9d05a0b5](https://linux-hardware.org/?probe=ac9d05a0b5) | Jan 30, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [61d19fb0bc](https://linux-hardware.org/?probe=61d19fb0bc) | Jan 29, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [41cff556c1](https://linux-hardware.org/?probe=41cff556c1) | Jan 29, 2024 |
| Google        | Elemi                       | Notebook    | [f767c4fdbb](https://linux-hardware.org/?probe=f767c4fdbb) | Jan 28, 2024 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [a2c3ceeb83](https://linux-hardware.org/?probe=a2c3ceeb83) | Jan 25, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0996781568](https://linux-hardware.org/?probe=0996781568) | Jan 21, 2024 |
| COM1          | NBINF-O5-4R7R6              | Notebook    | [95df5c3aa3](https://linux-hardware.org/?probe=95df5c3aa3) | Jan 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1284a92c36](https://linux-hardware.org/?probe=1284a92c36) | Jan 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [052a070a11](https://linux-hardware.org/?probe=052a070a11) | Jan 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1291da44c0](https://linux-hardware.org/?probe=1291da44c0) | Jan 14, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a7a7b48aa9](https://linux-hardware.org/?probe=a7a7b48aa9) | Jan 13, 2024 |
| Supermicro    | X10DRL-i                    | Desktop     | [874482c96c](https://linux-hardware.org/?probe=874482c96c) | Jan 10, 2024 |
| Supermicro    | X10DRL-i                    | Desktop     | [d51207de50](https://linux-hardware.org/?probe=d51207de50) | Jan 09, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [bde414f757](https://linux-hardware.org/?probe=bde414f757) | Jan 09, 2024 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [f23bf42f04](https://linux-hardware.org/?probe=f23bf42f04) | Jan 08, 2024 |
| Google        | Jinlon                      | Notebook    | [1d3ce76cf8](https://linux-hardware.org/?probe=1d3ce76cf8) | Jan 08, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [cd2d137285](https://linux-hardware.org/?probe=cd2d137285) | Jan 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [3274a6e444](https://linux-hardware.org/?probe=3274a6e444) | Jan 05, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [764d37dd86](https://linux-hardware.org/?probe=764d37dd86) | Jan 05, 2024 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [4254a865ee](https://linux-hardware.org/?probe=4254a865ee) | Jan 04, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [04de30dc4d](https://linux-hardware.org/?probe=04de30dc4d) | Jan 03, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | Notebook    | [389ae3afc8](https://linux-hardware.org/?probe=389ae3afc8) | Jan 02, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [939fe5ab0c](https://linux-hardware.org/?probe=939fe5ab0c) | Jan 02, 2024 |
| Gigabyte      | Z490 UD                     | Desktop     | [e0aa5cc2d1](https://linux-hardware.org/?probe=e0aa5cc2d1) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [a97c12a4c8](https://linux-hardware.org/?probe=a97c12a4c8) | Dec 28, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [555b9489dd](https://linux-hardware.org/?probe=555b9489dd) | Dec 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [27856e6bb2](https://linux-hardware.org/?probe=27856e6bb2) | Dec 27, 2023 |
| Supermicro    | X11DAi-N                    | Server      | [6e0a7e9f92](https://linux-hardware.org/?probe=6e0a7e9f92) | Dec 27, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [9440079733](https://linux-hardware.org/?probe=9440079733) | Dec 27, 2023 |
| HP            | 86E9 A                      | Desktop     | [e373d2be5d](https://linux-hardware.org/?probe=e373d2be5d) | Dec 27, 2023 |
| Supermicro    | X11DAi-N                    | Server      | [9a681db276](https://linux-hardware.org/?probe=9a681db276) | Dec 27, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [c179cdb6dc](https://linux-hardware.org/?probe=c179cdb6dc) | Dec 27, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [c7a5f771ce](https://linux-hardware.org/?probe=c7a5f771ce) | Dec 26, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [23577ab5f1](https://linux-hardware.org/?probe=23577ab5f1) | Dec 26, 2023 |
| HP            | 86E9 A                      | Desktop     | [c13adc0c5e](https://linux-hardware.org/?probe=c13adc0c5e) | Dec 26, 2023 |
| Gigabyte      | Z490 UD                     | Desktop     | [09813a10ac](https://linux-hardware.org/?probe=09813a10ac) | Dec 26, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [9eff3f535e](https://linux-hardware.org/?probe=9eff3f535e) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a4efec2a2c](https://linux-hardware.org/?probe=a4efec2a2c) | Dec 19, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [74cbcabaa1](https://linux-hardware.org/?probe=74cbcabaa1) | Dec 17, 2023 |
| AYANEO        | 2                           | Tablet      | [78a21ff7fb](https://linux-hardware.org/?probe=78a21ff7fb) | Dec 16, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| ASUSTek       | K45VD                       | Notebook    | [527a669776](https://linux-hardware.org/?probe=527a669776) | Dec 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5a7d45a007](https://linux-hardware.org/?probe=5a7d45a007) | Dec 05, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2d6eaf642b](https://linux-hardware.org/?probe=2d6eaf642b) | Dec 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [52374a1dea](https://linux-hardware.org/?probe=52374a1dea) | Dec 03, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [34df3b2497](https://linux-hardware.org/?probe=34df3b2497) | Dec 02, 2023 |
| Dell          | Inspiron 1440               | Notebook    | [08b87da5fd](https://linux-hardware.org/?probe=08b87da5fd) | Nov 30, 2023 |
| Dell          | Inspiron 1440               | Notebook    | [7c28444086](https://linux-hardware.org/?probe=7c28444086) | Nov 29, 2023 |
| Gigabyte      | H310M DS2                   | Desktop     | [14a8656c8b](https://linux-hardware.org/?probe=14a8656c8b) | Nov 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [30bce064eb](https://linux-hardware.org/?probe=30bce064eb) | Nov 27, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [42271c5724](https://linux-hardware.org/?probe=42271c5724) | Nov 26, 2023 |
| HP            | 212B                        | Desktop     | [90bc0d4d2d](https://linux-hardware.org/?probe=90bc0d4d2d) | Nov 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [95b888d2b1](https://linux-hardware.org/?probe=95b888d2b1) | Nov 24, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [dbbf51e4c5](https://linux-hardware.org/?probe=dbbf51e4c5) | Nov 18, 2023 |
| Samsung       | 730QDA                      | Convertible | [3167fd276f](https://linux-hardware.org/?probe=3167fd276f) | Nov 17, 2023 |
| Samsung       | 730QDA                      | Convertible | [33aae4cfd4](https://linux-hardware.org/?probe=33aae4cfd4) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [95a4f9ff42](https://linux-hardware.org/?probe=95a4f9ff42) | Nov 14, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [dfbaeb29c5](https://linux-hardware.org/?probe=dfbaeb29c5) | Nov 11, 2023 |
| Google        | Phaser360                   | Notebook    | [dbd0db9b7e](https://linux-hardware.org/?probe=dbd0db9b7e) | Nov 05, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [21b415bccc](https://linux-hardware.org/?probe=21b415bccc) | Nov 05, 2023 |
| Intel         | X99                         | Desktop     | [cb3515efba](https://linux-hardware.org/?probe=cb3515efba) | Nov 03, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [e87403e608](https://linux-hardware.org/?probe=e87403e608) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [664191098d](https://linux-hardware.org/?probe=664191098d) | Nov 02, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [3e5415671f](https://linux-hardware.org/?probe=3e5415671f) | Nov 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [63fa5e90b2](https://linux-hardware.org/?probe=63fa5e90b2) | Nov 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [64e3601d4c](https://linux-hardware.org/?probe=64e3601d4c) | Oct 29, 2023 |
| Dell          | Latitude E5450              | Notebook    | [aebf2cd9fb](https://linux-hardware.org/?probe=aebf2cd9fb) | Oct 29, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [dcd6988b7a](https://linux-hardware.org/?probe=dcd6988b7a) | Oct 28, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [681e404df8](https://linux-hardware.org/?probe=681e404df8) | Oct 28, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [9854f25018](https://linux-hardware.org/?probe=9854f25018) | Oct 26, 2023 |
| BBEN          | Cherry Trail CR             | Mini pc     | [a37982a5e5](https://linux-hardware.org/?probe=a37982a5e5) | Oct 25, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [824215ab50](https://linux-hardware.org/?probe=824215ab50) | Oct 25, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8764daeeab](https://linux-hardware.org/?probe=8764daeeab) | Oct 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4f06b99b2e](https://linux-hardware.org/?probe=4f06b99b2e) | Oct 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [62ca63bc89](https://linux-hardware.org/?probe=62ca63bc89) | Oct 23, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2b88710042](https://linux-hardware.org/?probe=2b88710042) | Oct 22, 2023 |
| Dell          | Latitude E6440              | Notebook    | [9db156fcaf](https://linux-hardware.org/?probe=9db156fcaf) | Oct 22, 2023 |
| HP            | Compaq 6520s                | Notebook    | [d010b05039](https://linux-hardware.org/?probe=d010b05039) | Oct 22, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [f77f7c8a16](https://linux-hardware.org/?probe=f77f7c8a16) | Oct 22, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a7f899353b](https://linux-hardware.org/?probe=a7f899353b) | Oct 21, 2023 |
| HP            | 15                          | Notebook    | [c85c40dbc8](https://linux-hardware.org/?probe=c85c40dbc8) | Oct 21, 2023 |
| HP            | 15                          | Notebook    | [95e8953601](https://linux-hardware.org/?probe=95e8953601) | Oct 21, 2023 |
| MSI           | Crosshair 15 B12UEZ         | Notebook    | [746189a3d8](https://linux-hardware.org/?probe=746189a3d8) | Oct 20, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [0875e69e22](https://linux-hardware.org/?probe=0875e69e22) | Oct 17, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [9240952796](https://linux-hardware.org/?probe=9240952796) | Oct 16, 2023 |
| Dell          | Latitude 7330               | Notebook    | [8632b84be8](https://linux-hardware.org/?probe=8632b84be8) | Oct 14, 2023 |
| HP            | Notebook                    | Notebook    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [b1ff58e369](https://linux-hardware.org/?probe=b1ff58e369) | Oct 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [47ba0bddd0](https://linux-hardware.org/?probe=47ba0bddd0) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [29c7192a14](https://linux-hardware.org/?probe=29c7192a14) | Oct 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08bbfa9e1](https://linux-hardware.org/?probe=a08bbfa9e1) | Oct 07, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [171a2ad768](https://linux-hardware.org/?probe=171a2ad768) | Oct 04, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [65ae20098f](https://linux-hardware.org/?probe=65ae20098f) | Oct 03, 2023 |
| Samsung       | 940XGK                      | Notebook    | [63aededb0c](https://linux-hardware.org/?probe=63aededb0c) | Oct 03, 2023 |
| Samsung       | 940XGK                      | Notebook    | [805cef3023](https://linux-hardware.org/?probe=805cef3023) | Oct 03, 2023 |
| Dell          | Inspiron 5583               | Notebook    | [c16bd909f3](https://linux-hardware.org/?probe=c16bd909f3) | Oct 02, 2023 |
| Sony          | SVF1421PSGB                 | Notebook    | [11d6cad851](https://linux-hardware.org/?probe=11d6cad851) | Oct 02, 2023 |
| Sony          | SVF1421PSGB                 | Notebook    | [84a0c8ea9b](https://linux-hardware.org/?probe=84a0c8ea9b) | Oct 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [76401b3ca2](https://linux-hardware.org/?probe=76401b3ca2) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [3e29eb1d63](https://linux-hardware.org/?probe=3e29eb1d63) | Sep 26, 2023 |
| ASRock        | A320M-HDV                   | Desktop     | [2beb623746](https://linux-hardware.org/?probe=2beb623746) | Sep 26, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [b063bf9f1e](https://linux-hardware.org/?probe=b063bf9f1e) | Sep 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2d1e14cb66](https://linux-hardware.org/?probe=2d1e14cb66) | Sep 23, 2023 |
| Dell          | Precision 7520              | Notebook    | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [4bf05e9eae](https://linux-hardware.org/?probe=4bf05e9eae) | Sep 17, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [b7c1a0a0a0](https://linux-hardware.org/?probe=b7c1a0a0a0) | Sep 16, 2023 |
| ASUSTek       | UX305FA                     | Notebook    | [e4ade39a1c](https://linux-hardware.org/?probe=e4ade39a1c) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [d1d5edf95c](https://linux-hardware.org/?probe=d1d5edf95c) | Sep 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [75ca1d0c52](https://linux-hardware.org/?probe=75ca1d0c52) | Sep 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [043d6c8d65](https://linux-hardware.org/?probe=043d6c8d65) | Sep 08, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [5b22cd283b](https://linux-hardware.org/?probe=5b22cd283b) | Sep 08, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [155023d91f](https://linux-hardware.org/?probe=155023d91f) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [b652970974](https://linux-hardware.org/?probe=b652970974) | Sep 01, 2023 |
| ASUSTek       | EX-H110M-V3                 | Desktop     | [c38af5d04d](https://linux-hardware.org/?probe=c38af5d04d) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | Desktop     | [e2b97e4436](https://linux-hardware.org/?probe=e2b97e4436) | Aug 31, 2023 |
| Dell          | Vostro 1450                 | Notebook    | [1aad0f5aa3](https://linux-hardware.org/?probe=1aad0f5aa3) | Aug 26, 2023 |
| GuoGuang      | IC2M1028N                   | Desktop     | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Dell          | Latitude 7480               | Notebook    | [50bcada7d4](https://linux-hardware.org/?probe=50bcada7d4) | Aug 23, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [e00521ec88](https://linux-hardware.org/?probe=e00521ec88) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [882234a7b8](https://linux-hardware.org/?probe=882234a7b8) | Aug 22, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [d6df464cc7](https://linux-hardware.org/?probe=d6df464cc7) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [471f5f6132](https://linux-hardware.org/?probe=471f5f6132) | Aug 20, 2023 |
| HP            | 2000                        | Notebook    | [650a9a885c](https://linux-hardware.org/?probe=650a9a885c) | Aug 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [f52ceb7ab6](https://linux-hardware.org/?probe=f52ceb7ab6) | Aug 15, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| Acer          | Aspire V5-471G              | Notebook    | [1955354749](https://linux-hardware.org/?probe=1955354749) | Aug 11, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [b065632006](https://linux-hardware.org/?probe=b065632006) | Aug 08, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6dbeaa5f27](https://linux-hardware.org/?probe=6dbeaa5f27) | Aug 04, 2023 |
| Dell          | System XPS L322X            | Notebook    | [dbe168d1a1](https://linux-hardware.org/?probe=dbe168d1a1) | Aug 02, 2023 |
| Alienware     | 13 R3                       | Notebook    | [845dfcc74f](https://linux-hardware.org/?probe=845dfcc74f) | Jul 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [ece0a7a538](https://linux-hardware.org/?probe=ece0a7a538) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad T420 4180EP2       | Notebook    | [298fe52a60](https://linux-hardware.org/?probe=298fe52a60) | Jul 25, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [ae23c3b0d3](https://linux-hardware.org/?probe=ae23c3b0d3) | Jul 24, 2023 |
| Lenovo        | ThinkPad T420 4180EP2       | Notebook    | [4ec1a5c6fe](https://linux-hardware.org/?probe=4ec1a5c6fe) | Jul 22, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [fe9e1671cc](https://linux-hardware.org/?probe=fe9e1671cc) | Jul 20, 2023 |
| Dell          | Latitude 5580               | Notebook    | [6efcf73621](https://linux-hardware.org/?probe=6efcf73621) | Jul 19, 2023 |
| Dell          | Latitude 5580               | Notebook    | [16f62b67d3](https://linux-hardware.org/?probe=16f62b67d3) | Jul 17, 2023 |
| itel Mobil... | SPIRIT 1                    | Notebook    | [36c3d3f6a8](https://linux-hardware.org/?probe=36c3d3f6a8) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [a01053a59a](https://linux-hardware.org/?probe=a01053a59a) | Jul 15, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [d8310de68b](https://linux-hardware.org/?probe=d8310de68b) | Jul 12, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [851a3a00cf](https://linux-hardware.org/?probe=851a3a00cf) | Jul 05, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [0ffe35561e](https://linux-hardware.org/?probe=0ffe35561e) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7aaa5d2eec](https://linux-hardware.org/?probe=7aaa5d2eec) | Jul 03, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [2cd1962ee4](https://linux-hardware.org/?probe=2cd1962ee4) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ef49f25cf8](https://linux-hardware.org/?probe=ef49f25cf8) | Jun 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6cc649e9ba](https://linux-hardware.org/?probe=6cc649e9ba) | Jun 29, 2023 |
| Lenovo        | ThinkPad T15g Gen1 20URC... | Notebook    | [e4c7449911](https://linux-hardware.org/?probe=e4c7449911) | Jun 27, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8454119675](https://linux-hardware.org/?probe=8454119675) | Jun 22, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ebedbde736](https://linux-hardware.org/?probe=ebedbde736) | Jun 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2754ddde7f](https://linux-hardware.org/?probe=2754ddde7f) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [d704e4a5d3](https://linux-hardware.org/?probe=d704e4a5d3) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bf2fc7d3b7](https://linux-hardware.org/?probe=bf2fc7d3b7) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [1b491bcfeb](https://linux-hardware.org/?probe=1b491bcfeb) | Jun 07, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [f1060e2b5d](https://linux-hardware.org/?probe=f1060e2b5d) | Jun 07, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [da21766a5c](https://linux-hardware.org/?probe=da21766a5c) | Jun 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | Notebook    | [8c16cec2e8](https://linux-hardware.org/?probe=8c16cec2e8) | Jun 01, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [d0a6a8e29e](https://linux-hardware.org/?probe=d0a6a8e29e) | May 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9c98caaf4](https://linux-hardware.org/?probe=b9c98caaf4) | May 13, 2023 |
| Dell          | G15 5520                    | Notebook    | [81024f3df4](https://linux-hardware.org/?probe=81024f3df4) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Supermicro    | X8DTL                       | Server      | [4d6836803f](https://linux-hardware.org/?probe=4d6836803f) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [7a7021d420](https://linux-hardware.org/?probe=7a7021d420) | May 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [ed0486cda1](https://linux-hardware.org/?probe=ed0486cda1) | May 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [e26aee893f](https://linux-hardware.org/?probe=e26aee893f) | May 01, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [21d008c7d8](https://linux-hardware.org/?probe=21d008c7d8) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [49557b8214](https://linux-hardware.org/?probe=49557b8214) | Apr 29, 2023 |
| Dell          | Latitude 7390               | Notebook    | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [b53354af62](https://linux-hardware.org/?probe=b53354af62) | Apr 25, 2023 |
| Intel         | H81                         | Desktop     | [fbc2766f35](https://linux-hardware.org/?probe=fbc2766f35) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [af72838c03](https://linux-hardware.org/?probe=af72838c03) | Apr 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85fa6bf3d5](https://linux-hardware.org/?probe=85fa6bf3d5) | Apr 21, 2023 |
| HP            | 1825                        | Desktop     | [e586a2657b](https://linux-hardware.org/?probe=e586a2657b) | Apr 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [82931a3c45](https://linux-hardware.org/?probe=82931a3c45) | Apr 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | Notebook    | [6406153cbf](https://linux-hardware.org/?probe=6406153cbf) | Apr 12, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [ae048d3165](https://linux-hardware.org/?probe=ae048d3165) | Apr 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [c67c78ba10](https://linux-hardware.org/?probe=c67c78ba10) | Apr 11, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c56952417d](https://linux-hardware.org/?probe=c56952417d) | Apr 11, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [b67954cc59](https://linux-hardware.org/?probe=b67954cc59) | Apr 10, 2023 |
| Dell          | Latitude E6440              | Notebook    | [8153a28710](https://linux-hardware.org/?probe=8153a28710) | Apr 09, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [320195c782](https://linux-hardware.org/?probe=320195c782) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [3d59062866](https://linux-hardware.org/?probe=3d59062866) | Apr 06, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [81400b8912](https://linux-hardware.org/?probe=81400b8912) | Apr 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [6844d471e4](https://linux-hardware.org/?probe=6844d471e4) | Apr 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ea39081b01](https://linux-hardware.org/?probe=ea39081b01) | Apr 01, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [e09dc41124](https://linux-hardware.org/?probe=e09dc41124) | Mar 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Dell          | Latitude 7290               | Notebook    | [576b8aa32a](https://linux-hardware.org/?probe=576b8aa32a) | Mar 13, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [315750ea63](https://linux-hardware.org/?probe=315750ea63) | Mar 11, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [c45a0f2220](https://linux-hardware.org/?probe=c45a0f2220) | Mar 11, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [dee1b60a0d](https://linux-hardware.org/?probe=dee1b60a0d) | Mar 07, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [3cec8a7abc](https://linux-hardware.org/?probe=3cec8a7abc) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [219f16372b](https://linux-hardware.org/?probe=219f16372b) | Mar 03, 2023 |
| Samsung       | 930XDA                      | Notebook    | [684b448b3a](https://linux-hardware.org/?probe=684b448b3a) | Mar 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [4ead3fc236](https://linux-hardware.org/?probe=4ead3fc236) | Mar 03, 2023 |
| Dell          | Latitude 3400               | Notebook    | [2936e7f368](https://linux-hardware.org/?probe=2936e7f368) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [373f4f8123](https://linux-hardware.org/?probe=373f4f8123) | Feb 27, 2023 |
| Dell          | Precision M4600             | Notebook    | [901a8de667](https://linux-hardware.org/?probe=901a8de667) | Feb 24, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5fb951a350](https://linux-hardware.org/?probe=5fb951a350) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| Dell          | Precision M4600             | Notebook    | [2bdbf753b0](https://linux-hardware.org/?probe=2bdbf753b0) | Feb 21, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [12bb4f91ae](https://linux-hardware.org/?probe=12bb4f91ae) | Feb 20, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [a4404180b7](https://linux-hardware.org/?probe=a4404180b7) | Feb 20, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| MSI           | H410M PRO-VH                | Desktop     | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [420ccdfca6](https://linux-hardware.org/?probe=420ccdfca6) | Feb 07, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [cfcea0a331](https://linux-hardware.org/?probe=cfcea0a331) | Feb 05, 2023 |
| MSI           | Modern 14 B11SBU            | Notebook    | [50538fe8fd](https://linux-hardware.org/?probe=50538fe8fd) | Feb 05, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [8da4ffdd5c](https://linux-hardware.org/?probe=8da4ffdd5c) | Feb 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b660fd4859](https://linux-hardware.org/?probe=b660fd4859) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a7eba3e52d](https://linux-hardware.org/?probe=a7eba3e52d) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [a169951063](https://linux-hardware.org/?probe=a169951063) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [45890fca78](https://linux-hardware.org/?probe=45890fca78) | Feb 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S3PV00    | Notebook    | [08f4e80cb9](https://linux-hardware.org/?probe=08f4e80cb9) | Feb 02, 2023 |
| HP            | 81B4                        | Desktop     | [01229ad5ec](https://linux-hardware.org/?probe=01229ad5ec) | Jan 29, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [b7971f413f](https://linux-hardware.org/?probe=b7971f413f) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0015U... | Notebook    | [1ece644fe1](https://linux-hardware.org/?probe=1ece644fe1) | Jan 04, 2023 |
| Dell          | Precision 3560              | Notebook    | [8cb8a3f5cf](https://linux-hardware.org/?probe=8cb8a3f5cf) | Jan 04, 2023 |
| Anbernic      | Win600                      | Notebook    | [db576ded28](https://linux-hardware.org/?probe=db576ded28) | Dec 29, 2022 |
| HP            | 158A                        | Desktop     | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c82ebf8b80](https://linux-hardware.org/?probe=c82ebf8b80) | Dec 26, 2022 |
| Anbernic      | Win600                      | Notebook    | [f7759a13d8](https://linux-hardware.org/?probe=f7759a13d8) | Dec 25, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b6ac9ce59](https://linux-hardware.org/?probe=3b6ac9ce59) | Dec 19, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470s 20HF0015U... | Notebook    | [3fd30db5e1](https://linux-hardware.org/?probe=3fd30db5e1) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [f82368713d](https://linux-hardware.org/?probe=f82368713d) | Dec 17, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [66635e6315](https://linux-hardware.org/?probe=66635e6315) | Dec 16, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| HP            | 350 G1                      | Notebook    | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Dell          | Latitude 7390               | Notebook    | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [324b5a49e4](https://linux-hardware.org/?probe=324b5a49e4) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [33113bb27d](https://linux-hardware.org/?probe=33113bb27d) | Nov 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [b19387a8f3](https://linux-hardware.org/?probe=b19387a8f3) | Nov 16, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [91268b9919](https://linux-hardware.org/?probe=91268b9919) | Nov 16, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [4adf740f59](https://linux-hardware.org/?probe=4adf740f59) | Nov 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [4b0ce24e6e](https://linux-hardware.org/?probe=4b0ce24e6e) | Nov 11, 2022 |
| Google        | Drallion                    | Notebook    | [7cb5922896](https://linux-hardware.org/?probe=7cb5922896) | Nov 10, 2022 |
| Dell          | G15 5511                    | Notebook    | [8a3246caed](https://linux-hardware.org/?probe=8a3246caed) | Nov 10, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [86f71fb0e6](https://linux-hardware.org/?probe=86f71fb0e6) | Nov 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| HP            | 212B                        | Desktop     | [adf4c58f4c](https://linux-hardware.org/?probe=adf4c58f4c) | Oct 22, 2022 |
| Gigabyte      | B360M DS3H                  | Desktop     | [ca57bb441c](https://linux-hardware.org/?probe=ca57bb441c) | Oct 18, 2022 |
| HP            | 158A                        | Desktop     | [6b1d53174a](https://linux-hardware.org/?probe=6b1d53174a) | Oct 12, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4... | Desktop     | [080242408d](https://linux-hardware.org/?probe=080242408d) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [1bff176b39](https://linux-hardware.org/?probe=1bff176b39) | Oct 05, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [403aa5af3e](https://linux-hardware.org/?probe=403aa5af3e) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| HP            | 158A                        | Desktop     | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Lenovo        | ThinkPad T450s 20BX005GU... | Notebook    | [5c41d03119](https://linux-hardware.org/?probe=5c41d03119) | Sep 15, 2022 |
| Intel         | S1200SP H57533-350          | Server      | [6e17cb41c9](https://linux-hardware.org/?probe=6e17cb41c9) | Sep 15, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [c07c5b31f6](https://linux-hardware.org/?probe=c07c5b31f6) | Sep 13, 2022 |
| HP            | Elite x2 1013 G3            | Tablet      | [25b64af3e9](https://linux-hardware.org/?probe=25b64af3e9) | Sep 13, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [7e840fc9d0](https://linux-hardware.org/?probe=7e840fc9d0) | Sep 12, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [4b728bc447](https://linux-hardware.org/?probe=4b728bc447) | Sep 12, 2022 |
| Dell          | 0VNM11 A00                  | Desktop     | [9ae0ae5ac4](https://linux-hardware.org/?probe=9ae0ae5ac4) | Sep 10, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [ecc2f4c975](https://linux-hardware.org/?probe=ecc2f4c975) | Sep 06, 2022 |
| MSI           | H410M PRO                   | Desktop     | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| HP            | 18E7                        | Desktop     | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [46c6096b6e](https://linux-hardware.org/?probe=46c6096b6e) | Aug 23, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [a3d9fca7aa](https://linux-hardware.org/?probe=a3d9fca7aa) | Aug 16, 2022 |
| HP            | 2AE2                        | Desktop     | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| ASUSTek       | GL552VX                     | Notebook    | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Lenovo        | ThinkPad P50 20EQS4QM00     | Notebook    | [9779cc7396](https://linux-hardware.org/?probe=9779cc7396) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| ASUSTek       | K55A                        | Notebook    | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Dell          | G3 3500                     | Notebook    | [69f594bb80](https://linux-hardware.org/?probe=69f594bb80) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| Toshiba       | dynabook Satellite B35/R    | Notebook    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| HP            | 8455                        | Desktop     | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| TENKU         | SB14                        | Notebook    | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6eb841aab1](https://linux-hardware.org/?probe=6eb841aab1) | Jun 21, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [58b312c382](https://linux-hardware.org/?probe=58b312c382) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [a8c7fc9c3a](https://linux-hardware.org/?probe=a8c7fc9c3a) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [63bc3a2ce5](https://linux-hardware.org/?probe=63bc3a2ce5) | May 27, 2022 |
| Acer          | Aspire A315-57G             | Notebook    | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [09ba129a3b](https://linux-hardware.org/?probe=09ba129a3b) | May 25, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [9df127ec26](https://linux-hardware.org/?probe=9df127ec26) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb2ffeb78a](https://linux-hardware.org/?probe=bb2ffeb78a) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb73f6aa37](https://linux-hardware.org/?probe=bb73f6aa37) | May 04, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [51625474b7](https://linux-hardware.org/?probe=51625474b7) | Apr 30, 2022 |
| Foxconn       | H61MD/H61MD-V               | Desktop     | [25b52955ee](https://linux-hardware.org/?probe=25b52955ee) | Apr 29, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [7499dbd303](https://linux-hardware.org/?probe=7499dbd303) | Apr 15, 2022 |
| Foxconn       | H61MD/H61MD-V               | Desktop     | [7bb124e322](https://linux-hardware.org/?probe=7bb124e322) | Apr 06, 2022 |
| Dell          | System Vostro 3450          | Notebook    | [78750d86f5](https://linux-hardware.org/?probe=78750d86f5) | Mar 19, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [5dcc8e2cee](https://linux-hardware.org/?probe=5dcc8e2cee) | Mar 14, 2022 |
| ASUSTek       | ET2013I                     | All in one  | [b20d7593ce](https://linux-hardware.org/?probe=b20d7593ce) | Mar 09, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| Dell          | System XPS L702X            | Notebook    | [e1d4821ec2](https://linux-hardware.org/?probe=e1d4821ec2) | Feb 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [64f5921b5b](https://linux-hardware.org/?probe=64f5921b5b) | Feb 13, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [0619812e27](https://linux-hardware.org/?probe=0619812e27) | Feb 11, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [4834a3fe2e](https://linux-hardware.org/?probe=4834a3fe2e) | Feb 09, 2022 |
| Dell          | G3 3500                     | Notebook    | [9001ccacbc](https://linux-hardware.org/?probe=9001ccacbc) | Feb 09, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [2621c151ec](https://linux-hardware.org/?probe=2621c151ec) | Feb 01, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [a95dfa8bc8](https://linux-hardware.org/?probe=a95dfa8bc8) | Jan 26, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | Notebook    | [872bc057f0](https://linux-hardware.org/?probe=872bc057f0) | Jan 10, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [5588a84fcf](https://linux-hardware.org/?probe=5588a84fcf) | Jan 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [d65648c445](https://linux-hardware.org/?probe=d65648c445) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [3b97b65258](https://linux-hardware.org/?probe=3b97b65258) | Jan 08, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [be7876abf4](https://linux-hardware.org/?probe=be7876abf4) | Jan 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [65c9a87d51](https://linux-hardware.org/?probe=65c9a87d51) | Jan 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [48cfc7d185](https://linux-hardware.org/?probe=48cfc7d185) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b64750f465](https://linux-hardware.org/?probe=b64750f465) | Dec 26, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [cee5f081e3](https://linux-hardware.org/?probe=cee5f081e3) | Dec 19, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [297d964b96](https://linux-hardware.org/?probe=297d964b96) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [717b9f1dd0](https://linux-hardware.org/?probe=717b9f1dd0) | Dec 16, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [bd72de2067](https://linux-hardware.org/?probe=bd72de2067) | Dec 12, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [412accf186](https://linux-hardware.org/?probe=412accf186) | Dec 09, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [21d85302a2](https://linux-hardware.org/?probe=21d85302a2) | Dec 05, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [70c63b2fb6](https://linux-hardware.org/?probe=70c63b2fb6) | Dec 02, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [c5d4bf5c62](https://linux-hardware.org/?probe=c5d4bf5c62) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| Timi          | A35S                        | Notebook    | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [fa62ac7a45](https://linux-hardware.org/?probe=fa62ac7a45) | Nov 23, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [10455f4980](https://linux-hardware.org/?probe=10455f4980) | Nov 23, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [17781cb457](https://linux-hardware.org/?probe=17781cb457) | Nov 20, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [f4a646d1f8](https://linux-hardware.org/?probe=f4a646d1f8) | Nov 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [5471ce2e2f](https://linux-hardware.org/?probe=5471ce2e2f) | Nov 16, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a471ac5d59](https://linux-hardware.org/?probe=a471ac5d59) | Nov 07, 2021 |
| Dell          | Vostro 3478                 | Notebook    | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | Notebook    | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Dell          | Precision 7510              | Notebook    | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [042607d7f1](https://linux-hardware.org/?probe=042607d7f1) | Oct 31, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [11527ae3f9](https://linux-hardware.org/?probe=11527ae3f9) | Oct 31, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [370ad865cf](https://linux-hardware.org/?probe=370ad865cf) | Oct 31, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [f316c0a82e](https://linux-hardware.org/?probe=f316c0a82e) | Oct 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| Gigabyte      | EP43T-S3L                   | Desktop     | [8a1adefcb3](https://linux-hardware.org/?probe=8a1adefcb3) | Oct 20, 2021 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [603ccdfb84](https://linux-hardware.org/?probe=603ccdfb84) | Oct 19, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [7459a9ed47](https://linux-hardware.org/?probe=7459a9ed47) | Oct 18, 2021 |
| Dell          | Precision 7510              | Notebook    | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| HP            | Notebook                    | Notebook    | [6ac2c09585](https://linux-hardware.org/?probe=6ac2c09585) | Oct 09, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [c9fd6887d4](https://linux-hardware.org/?probe=c9fd6887d4) | Oct 06, 2021 |
| Acer          | Predator PH315-51           | Notebook    | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b1fb3d4e88](https://linux-hardware.org/?probe=b1fb3d4e88) | Oct 04, 2021 |
| Dell          | Latitude E7440              | Notebook    | [fe4153e816](https://linux-hardware.org/?probe=fe4153e816) | Oct 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8b3b2655bb](https://linux-hardware.org/?probe=8b3b2655bb) | Oct 03, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [52fe5aa259](https://linux-hardware.org/?probe=52fe5aa259) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [d8cde7951e](https://linux-hardware.org/?probe=d8cde7951e) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [db7c214214](https://linux-hardware.org/?probe=db7c214214) | Sep 28, 2021 |
| Dell          | Latitude 3520               | Notebook    | [2fb41f5f08](https://linux-hardware.org/?probe=2fb41f5f08) | Sep 24, 2021 |
| HP            | 15                          | Notebook    | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Sony          | SVE14A15FGW                 | Notebook    | [f1049f7db1](https://linux-hardware.org/?probe=f1049f7db1) | Sep 21, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [d474bc1b91](https://linux-hardware.org/?probe=d474bc1b91) | Sep 03, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [bee71431a0](https://linux-hardware.org/?probe=bee71431a0) | Sep 03, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | GF62 7RD                    | Notebook    | [5a35b145a9](https://linux-hardware.org/?probe=5a35b145a9) | Aug 19, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [df3d4bfff1](https://linux-hardware.org/?probe=df3d4bfff1) | Aug 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [dde539e1b1](https://linux-hardware.org/?probe=dde539e1b1) | Aug 18, 2021 |
| HP            | ProBook 4430s               | Notebook    | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f77c5c4c48](https://linux-hardware.org/?probe=f77c5c4c48) | Aug 10, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [886b00678b](https://linux-hardware.org/?probe=886b00678b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [57bf64ac4b](https://linux-hardware.org/?probe=57bf64ac4b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [76e0c19c46](https://linux-hardware.org/?probe=76e0c19c46) | Aug 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ce35fd4a1a](https://linux-hardware.org/?probe=ce35fd4a1a) | Jul 23, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [10c0149671](https://linux-hardware.org/?probe=10c0149671) | Jul 17, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | Notebook    | [e6cb486cfd](https://linux-hardware.org/?probe=e6cb486cfd) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | Notebook    | [58ad5d25b9](https://linux-hardware.org/?probe=58ad5d25b9) | Jul 07, 2021 |
| Dell          | Latitude E6410              | Notebook    | [9a4002aa3d](https://linux-hardware.org/?probe=9a4002aa3d) | Jul 07, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [894db66628](https://linux-hardware.org/?probe=894db66628) | Jul 05, 2021 |
| HP            | Compaq 510                  | Notebook    | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Gigabyte      | P110-D3-CF                  | Desktop     | [37aab1ae76](https://linux-hardware.org/?probe=37aab1ae76) | Jun 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| Colorful T... | C.A68M-BTC YV14             | Desktop     | [9b6c7d9e82](https://linux-hardware.org/?probe=9b6c7d9e82) | Jun 23, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [85b912e99c](https://linux-hardware.org/?probe=85b912e99c) | Jun 22, 2021 |
| Huanan        | X79 249PC V2.1              | Desktop     | [b6fd95e48e](https://linux-hardware.org/?probe=b6fd95e48e) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | Notebook    | [ac56c24f68](https://linux-hardware.org/?probe=ac56c24f68) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | Notebook    | [4527ee70c7](https://linux-hardware.org/?probe=4527ee70c7) | Jun 13, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [ea30bb632e](https://linux-hardware.org/?probe=ea30bb632e) | Jun 10, 2021 |
| Lenovo        | ThinkPad L520 5015A76       | Notebook    | [84b62cbde9](https://linux-hardware.org/?probe=84b62cbde9) | Jun 10, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [851f20cb74](https://linux-hardware.org/?probe=851f20cb74) | Jun 09, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [428cb5bb99](https://linux-hardware.org/?probe=428cb5bb99) | Jun 05, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [de3596a9a3](https://linux-hardware.org/?probe=de3596a9a3) | Jun 05, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [38acf36fce](https://linux-hardware.org/?probe=38acf36fce) | Jun 05, 2021 |
| Dell          | Latitude 7420               | Notebook    | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [4401c591ee](https://linux-hardware.org/?probe=4401c591ee) | Jun 01, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [f1d33c68f6](https://linux-hardware.org/?probe=f1d33c68f6) | Jun 01, 2021 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [8995f3c1ad](https://linux-hardware.org/?probe=8995f3c1ad) | Jun 01, 2021 |
| Lenovo        | Z40-70 20366                | Notebook    | [b1b8196f26](https://linux-hardware.org/?probe=b1b8196f26) | May 31, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [35c74e640b](https://linux-hardware.org/?probe=35c74e640b) | May 31, 2021 |
| Lenovo        | ThinkPad X250 20CLCTO1WW    | Notebook    | [a5d677976f](https://linux-hardware.org/?probe=a5d677976f) | May 29, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [b70a62225d](https://linux-hardware.org/?probe=b70a62225d) | May 22, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [ddfb904938](https://linux-hardware.org/?probe=ddfb904938) | May 19, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [35324d2388](https://linux-hardware.org/?probe=35324d2388) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1abefab68f](https://linux-hardware.org/?probe=1abefab68f) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c4ea8f1bab](https://linux-hardware.org/?probe=c4ea8f1bab) | May 19, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2ce7106efb](https://linux-hardware.org/?probe=2ce7106efb) | May 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [c84fc5c646](https://linux-hardware.org/?probe=c84fc5c646) | May 12, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [ef73590627](https://linux-hardware.org/?probe=ef73590627) | May 09, 2021 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [63effde8c3](https://linux-hardware.org/?probe=63effde8c3) | May 08, 2021 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [99ac06d5e2](https://linux-hardware.org/?probe=99ac06d5e2) | May 08, 2021 |
| Acer          | Predator G9-793             | Notebook    | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [2fabbbebb9](https://linux-hardware.org/?probe=2fabbbebb9) | Apr 29, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [23cc5c25c3](https://linux-hardware.org/?probe=23cc5c25c3) | Apr 29, 2021 |
| HP            | Pavilion 15                 | Notebook    | [1ddb966308](https://linux-hardware.org/?probe=1ddb966308) | Apr 28, 2021 |
| Sony          | VPCCW13FX                   | Notebook    | [82e9a1f82a](https://linux-hardware.org/?probe=82e9a1f82a) | Apr 25, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [599315872a](https://linux-hardware.org/?probe=599315872a) | Apr 24, 2021 |
| Dell          | Precision 3520              | Notebook    | [fc2d295c0e](https://linux-hardware.org/?probe=fc2d295c0e) | Apr 24, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [76defcf2f7](https://linux-hardware.org/?probe=76defcf2f7) | Apr 22, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [c941a697c2](https://linux-hardware.org/?probe=c941a697c2) | Apr 22, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e55472cf5f](https://linux-hardware.org/?probe=e55472cf5f) | Apr 18, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [007ae7cca0](https://linux-hardware.org/?probe=007ae7cca0) | Apr 18, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [07736896f9](https://linux-hardware.org/?probe=07736896f9) | Apr 18, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [abf17f0c92](https://linux-hardware.org/?probe=abf17f0c92) | Apr 17, 2021 |
| HP            | Unknown                     | Notebook    | [2465109965](https://linux-hardware.org/?probe=2465109965) | Apr 13, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [698d0ca8cc](https://linux-hardware.org/?probe=698d0ca8cc) | Apr 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [d5d191947e](https://linux-hardware.org/?probe=d5d191947e) | Apr 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [07fd740efe](https://linux-hardware.org/?probe=07fd740efe) | Apr 06, 2021 |
| Chuwi         | LapBook SE                  | Notebook    | [0e9a03cc48](https://linux-hardware.org/?probe=0e9a03cc48) | Apr 06, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [d20d2b755f](https://linux-hardware.org/?probe=d20d2b755f) | Apr 04, 2021 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [cdfb323202](https://linux-hardware.org/?probe=cdfb323202) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [e8c59a070a](https://linux-hardware.org/?probe=e8c59a070a) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [b9324b1b4d](https://linux-hardware.org/?probe=b9324b1b4d) | Apr 04, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| MSI           | GS40 6QE Phantom            | Notebook    | [adbf080ab7](https://linux-hardware.org/?probe=adbf080ab7) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [43f33bc8e0](https://linux-hardware.org/?probe=43f33bc8e0) | Mar 21, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [c377f57ac8](https://linux-hardware.org/?probe=c377f57ac8) | Mar 21, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| Dell          | 04Y8V0 A02                  | Desktop     | [241289046a](https://linux-hardware.org/?probe=241289046a) | Mar 16, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [5bada8b921](https://linux-hardware.org/?probe=5bada8b921) | Mar 13, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [a8e1128b26](https://linux-hardware.org/?probe=a8e1128b26) | Mar 13, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [d56654c11c](https://linux-hardware.org/?probe=d56654c11c) | Mar 12, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [d1bd158872](https://linux-hardware.org/?probe=d1bd158872) | Mar 10, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| ASUSTek       | X202E                       | Notebook    | [cc089d4ddb](https://linux-hardware.org/?probe=cc089d4ddb) | Mar 08, 2021 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [3acc3e5a05](https://linux-hardware.org/?probe=3acc3e5a05) | Mar 06, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [647b5fbb43](https://linux-hardware.org/?probe=647b5fbb43) | Mar 06, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [9e8527b842](https://linux-hardware.org/?probe=9e8527b842) | Mar 05, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [96fd52e1f2](https://linux-hardware.org/?probe=96fd52e1f2) | Mar 02, 2021 |
| Acer          | Aspire A515-53              | Notebook    | [637c3ebf75](https://linux-hardware.org/?probe=637c3ebf75) | Feb 28, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [05ad71d3d8](https://linux-hardware.org/?probe=05ad71d3d8) | Feb 24, 2021 |
| Gateway       | LT40                        | Notebook    | [90ae93da93](https://linux-hardware.org/?probe=90ae93da93) | Feb 24, 2021 |
| Gateway       | LT40                        | Notebook    | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [4a441fe0c9](https://linux-hardware.org/?probe=4a441fe0c9) | Feb 21, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [bfb791c2fb](https://linux-hardware.org/?probe=bfb791c2fb) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | Notebook    | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | Notebook    | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [bb980a20ea](https://linux-hardware.org/?probe=bb980a20ea) | Feb 18, 2021 |
| ASUSTek       | EB1036                      | Desktop     | [d77c773bc7](https://linux-hardware.org/?probe=d77c773bc7) | Feb 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a79c837a9b](https://linux-hardware.org/?probe=a79c837a9b) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5cb0f77327](https://linux-hardware.org/?probe=5cb0f77327) | Feb 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0c70deaac1](https://linux-hardware.org/?probe=0c70deaac1) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0441228ba8](https://linux-hardware.org/?probe=0441228ba8) | Feb 07, 2021 |
| Dell          | Latitude E7450              | Notebook    | [94b0fc1fc8](https://linux-hardware.org/?probe=94b0fc1fc8) | Feb 06, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [b2b00b4390](https://linux-hardware.org/?probe=b2b00b4390) | Jan 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [d7f2ee4a81](https://linux-hardware.org/?probe=d7f2ee4a81) | Jan 25, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [568c3e9797](https://linux-hardware.org/?probe=568c3e9797) | Jan 21, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [82f5ebd486](https://linux-hardware.org/?probe=82f5ebd486) | Jan 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [e9acf54209](https://linux-hardware.org/?probe=e9acf54209) | Jan 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [d462b4ca25](https://linux-hardware.org/?probe=d462b4ca25) | Jan 12, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [8ae2ef5b3b](https://linux-hardware.org/?probe=8ae2ef5b3b) | Jan 07, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [4a11009c6f](https://linux-hardware.org/?probe=4a11009c6f) | Jan 06, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [cf3d073aae](https://linux-hardware.org/?probe=cf3d073aae) | Jan 06, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [8b549321e4](https://linux-hardware.org/?probe=8b549321e4) | Dec 31, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [540115f336](https://linux-hardware.org/?probe=540115f336) | Dec 28, 2020 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [2e581b986a](https://linux-hardware.org/?probe=2e581b986a) | Dec 28, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [cd0b939f13](https://linux-hardware.org/?probe=cd0b939f13) | Dec 27, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [6eaddc8157](https://linux-hardware.org/?probe=6eaddc8157) | Dec 21, 2020 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [fb16534a29](https://linux-hardware.org/?probe=fb16534a29) | Dec 17, 2020 |
| Sony          | VGN-NW270F                  | Notebook    | [d8989e5c40](https://linux-hardware.org/?probe=d8989e5c40) | Dec 16, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [e880800d6f](https://linux-hardware.org/?probe=e880800d6f) | Dec 13, 2020 |
| Dell          | G3 3579                     | Notebook    | [99724b8bd6](https://linux-hardware.org/?probe=99724b8bd6) | Dec 12, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fa10ea29e8](https://linux-hardware.org/?probe=fa10ea29e8) | Dec 11, 2020 |
| HP            | 158A                        | Desktop     | [9c309002d1](https://linux-hardware.org/?probe=9c309002d1) | Dec 10, 2020 |
| Acer          | Predator PH315-51           | Notebook    | [c9539f5932](https://linux-hardware.org/?probe=c9539f5932) | Dec 09, 2020 |
| HP            | 2B2C                        | Desktop     | [ffd83f6d60](https://linux-hardware.org/?probe=ffd83f6d60) | Dec 08, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [ea2bf23a76](https://linux-hardware.org/?probe=ea2bf23a76) | Dec 03, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [2a4ce919e5](https://linux-hardware.org/?probe=2a4ce919e5) | Dec 03, 2020 |
| Acer          | Aspire V5-431P              | Notebook    | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| HP            | 158A                        | Desktop     | [eaab601c40](https://linux-hardware.org/?probe=eaab601c40) | Dec 02, 2020 |
| HP            | 158A                        | Desktop     | [64320f7764](https://linux-hardware.org/?probe=64320f7764) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [4e39668b71](https://linux-hardware.org/?probe=4e39668b71) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [dbff453f7e](https://linux-hardware.org/?probe=dbff453f7e) | Dec 02, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [80f3a03fc2](https://linux-hardware.org/?probe=80f3a03fc2) | Nov 22, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [471b375bb8](https://linux-hardware.org/?probe=471b375bb8) | Nov 22, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [7fb140838e](https://linux-hardware.org/?probe=7fb140838e) | Nov 12, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [ac263c6ad6](https://linux-hardware.org/?probe=ac263c6ad6) | Nov 10, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [3b2d445938](https://linux-hardware.org/?probe=3b2d445938) | Nov 07, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [f2a745943a](https://linux-hardware.org/?probe=f2a745943a) | Nov 04, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [bfa10fd887](https://linux-hardware.org/?probe=bfa10fd887) | Nov 04, 2020 |
| Dell          | Latitude 7490               | Notebook    | [8f0ec25c05](https://linux-hardware.org/?probe=8f0ec25c05) | Oct 29, 2020 |
| Dell          | Latitude E6530              | Notebook    | [1a16aeb4dd](https://linux-hardware.org/?probe=1a16aeb4dd) | Oct 28, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [318f172f36](https://linux-hardware.org/?probe=318f172f36) | Oct 27, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [070dae158a](https://linux-hardware.org/?probe=070dae158a) | Oct 24, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | Notebook    | [fa061b6d7e](https://linux-hardware.org/?probe=fa061b6d7e) | Oct 13, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | Notebook    | [dc9b667685](https://linux-hardware.org/?probe=dc9b667685) | Oct 13, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [bcc1019568](https://linux-hardware.org/?probe=bcc1019568) | Oct 07, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [125dd87b84](https://linux-hardware.org/?probe=125dd87b84) | Oct 03, 2020 |
| Dell          | 0215PR A02                  | Desktop     | [a37475889b](https://linux-hardware.org/?probe=a37475889b) | Oct 03, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Lenovo        | ThinkPad T420 4236C95       | Notebook    | [8cf52f76c0](https://linux-hardware.org/?probe=8cf52f76c0) | Oct 02, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [6753d2054d](https://linux-hardware.org/?probe=6753d2054d) | Oct 01, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [6c568247ff](https://linux-hardware.org/?probe=6c568247ff) | Oct 01, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [15bcec7549](https://linux-hardware.org/?probe=15bcec7549) | Sep 28, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [5ff5b89d5e](https://linux-hardware.org/?probe=5ff5b89d5e) | Sep 22, 2020 |
| Koloe         | X58                         | Desktop     | [81d474ab62](https://linux-hardware.org/?probe=81d474ab62) | Sep 20, 2020 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [55e8990643](https://linux-hardware.org/?probe=55e8990643) | Sep 17, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [3a8b43fc2f](https://linux-hardware.org/?probe=3a8b43fc2f) | Sep 16, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [8adea7b2b3](https://linux-hardware.org/?probe=8adea7b2b3) | Sep 15, 2020 |
| Dell          | Vostro 1450                 | Notebook    | [444ddb1aa9](https://linux-hardware.org/?probe=444ddb1aa9) | Sep 15, 2020 |
| Dell          | Precision 3520              | Notebook    | [e8f520c4fa](https://linux-hardware.org/?probe=e8f520c4fa) | Sep 09, 2020 |
| MASSCOM VI... | L133                        | Notebook    | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [11a8a7e166](https://linux-hardware.org/?probe=11a8a7e166) | Sep 07, 2020 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [42cdde5346](https://linux-hardware.org/?probe=42cdde5346) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [6b4eeecb26](https://linux-hardware.org/?probe=6b4eeecb26) | Sep 04, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [190c1e6486](https://linux-hardware.org/?probe=190c1e6486) | Aug 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [a9ced30680](https://linux-hardware.org/?probe=a9ced30680) | Aug 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [17c4f51c75](https://linux-hardware.org/?probe=17c4f51c75) | Aug 29, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [08d8dc8d6e](https://linux-hardware.org/?probe=08d8dc8d6e) | Aug 28, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [889530c9b1](https://linux-hardware.org/?probe=889530c9b1) | Aug 28, 2020 |
| Lenovo        | ThinkPad L430 2465CTO       | Notebook    | [e5371d9b58](https://linux-hardware.org/?probe=e5371d9b58) | Aug 26, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [01f13cc1c7](https://linux-hardware.org/?probe=01f13cc1c7) | Aug 25, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [dc862d439b](https://linux-hardware.org/?probe=dc862d439b) | Aug 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ff005e6d9](https://linux-hardware.org/?probe=4ff005e6d9) | Aug 21, 2020 |
| Lenovo        | ThinkPad T580 20L9001MUS    | Notebook    | [92c940e8c2](https://linux-hardware.org/?probe=92c940e8c2) | Aug 21, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [e7702e2ce8](https://linux-hardware.org/?probe=e7702e2ce8) | Aug 20, 2020 |
| Dell          | G3 3579                     | Notebook    | [8e341b94ae](https://linux-hardware.org/?probe=8e341b94ae) | Aug 18, 2020 |
| Dell          | G3 3579                     | Notebook    | [9a1078144d](https://linux-hardware.org/?probe=9a1078144d) | Aug 18, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [d9fe6d88cd](https://linux-hardware.org/?probe=d9fe6d88cd) | Aug 14, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [52f08d8242](https://linux-hardware.org/?probe=52f08d8242) | Aug 12, 2020 |
| Lenovo        | ThinkPad E480 20KN005GVA    | Notebook    | [f77c6858ad](https://linux-hardware.org/?probe=f77c6858ad) | Jul 24, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [a58d188243](https://linux-hardware.org/?probe=a58d188243) | Jul 19, 2020 |
| HP            | 2B2C                        | Desktop     | [ed031034e8](https://linux-hardware.org/?probe=ed031034e8) | Jul 18, 2020 |
| HP            | 2B2C                        | Desktop     | [dd85e7a5e1](https://linux-hardware.org/?probe=dd85e7a5e1) | Jul 18, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [ab4eff4438](https://linux-hardware.org/?probe=ab4eff4438) | Jul 16, 2020 |
| Dell          | Latitude E5470              | Notebook    | [777b8955c3](https://linux-hardware.org/?probe=777b8955c3) | Jul 12, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [d0dff5e971](https://linux-hardware.org/?probe=d0dff5e971) | Jul 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [7300218f1f](https://linux-hardware.org/?probe=7300218f1f) | Jul 09, 2020 |
| Dell          | Vostro 3590                 | Notebook    | [4f8fb0d621](https://linux-hardware.org/?probe=4f8fb0d621) | Jul 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [dba2423eba](https://linux-hardware.org/?probe=dba2423eba) | Jul 08, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [601726ae15](https://linux-hardware.org/?probe=601726ae15) | Jul 01, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [4e1f771d23](https://linux-hardware.org/?probe=4e1f771d23) | Jun 29, 2020 |
| Dell          | Vostro 3460                 | Notebook    | [2338ae0fde](https://linux-hardware.org/?probe=2338ae0fde) | Jun 28, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [a3b890c7f1](https://linux-hardware.org/?probe=a3b890c7f1) | Jun 26, 2020 |
| ASUSTek       | A68HM-K                     | Desktop     | [7fc608d8c2](https://linux-hardware.org/?probe=7fc608d8c2) | Jun 21, 2020 |
| HP            | ZBook 17 G2                 | Notebook    | [467e55d0db](https://linux-hardware.org/?probe=467e55d0db) | Jun 20, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [f223bc5b5e](https://linux-hardware.org/?probe=f223bc5b5e) | Jun 19, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [27d008955f](https://linux-hardware.org/?probe=27d008955f) | Jun 19, 2020 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [ce4a203e0f](https://linux-hardware.org/?probe=ce4a203e0f) | Jun 19, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [652d0e5648](https://linux-hardware.org/?probe=652d0e5648) | Jun 18, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [3b5f86f3d4](https://linux-hardware.org/?probe=3b5f86f3d4) | Jun 18, 2020 |
| Dell          | Inspiron 5548               | Notebook    | [60a6140ac2](https://linux-hardware.org/?probe=60a6140ac2) | Jun 14, 2020 |
| Dell          | Inspiron 5548               | Notebook    | [ac70aa8a8d](https://linux-hardware.org/?probe=ac70aa8a8d) | Jun 14, 2020 |
| Dell          | Vostro 3590                 | Notebook    | [faca1b4063](https://linux-hardware.org/?probe=faca1b4063) | Jun 14, 2020 |
| HP            | ZBook Studio G3             | Notebook    | [91a0ff7707](https://linux-hardware.org/?probe=91a0ff7707) | Jun 10, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [7b0270fb87](https://linux-hardware.org/?probe=7b0270fb87) | Jun 04, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [be05348be2](https://linux-hardware.org/?probe=be05348be2) | May 29, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [945550a204](https://linux-hardware.org/?probe=945550a204) | May 29, 2020 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [b0f5fc9b10](https://linux-hardware.org/?probe=b0f5fc9b10) | May 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [26b5908778](https://linux-hardware.org/?probe=26b5908778) | May 20, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [849bf107d8](https://linux-hardware.org/?probe=849bf107d8) | May 18, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [5a938c4186](https://linux-hardware.org/?probe=5a938c4186) | May 17, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [f400730782](https://linux-hardware.org/?probe=f400730782) | May 15, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [ffb18f222a](https://linux-hardware.org/?probe=ffb18f222a) | May 15, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [272430b55d](https://linux-hardware.org/?probe=272430b55d) | May 12, 2020 |
| Toshiba       | PORTEGE T110                | Notebook    | [8c8ec8db54](https://linux-hardware.org/?probe=8c8ec8db54) | May 10, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [7e7b980d96](https://linux-hardware.org/?probe=7e7b980d96) | May 09, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [a4ec49073e](https://linux-hardware.org/?probe=a4ec49073e) | May 02, 2020 |
| ASRock        | AOD790GX/128M               | Desktop     | [8ba6b55d11](https://linux-hardware.org/?probe=8ba6b55d11) | Apr 28, 2020 |
| Dell          | Vostro 14-5480              | Notebook    | [3edae78003](https://linux-hardware.org/?probe=3edae78003) | Apr 28, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [8e17ac8b14](https://linux-hardware.org/?probe=8e17ac8b14) | Apr 27, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1aa80c5f94](https://linux-hardware.org/?probe=1aa80c5f94) | Apr 26, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [a41dc8c7b3](https://linux-hardware.org/?probe=a41dc8c7b3) | Apr 24, 2020 |
| Dell          | Vostro 3478                 | Notebook    | [65a16b0f00](https://linux-hardware.org/?probe=65a16b0f00) | Apr 22, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [985dd25740](https://linux-hardware.org/?probe=985dd25740) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [8b6c1d10a4](https://linux-hardware.org/?probe=8b6c1d10a4) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [9cb006b675](https://linux-hardware.org/?probe=9cb006b675) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [e670bd004a](https://linux-hardware.org/?probe=e670bd004a) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [ed1d4fbd62](https://linux-hardware.org/?probe=ed1d4fbd62) | Apr 19, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [c51238bbe1](https://linux-hardware.org/?probe=c51238bbe1) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [e421f3a586](https://linux-hardware.org/?probe=e421f3a586) | Apr 10, 2020 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [45b9a81a90](https://linux-hardware.org/?probe=45b9a81a90) | Apr 08, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Dell          | Precision 5530              | Notebook    | [805db6810c](https://linux-hardware.org/?probe=805db6810c) | Mar 31, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [6093f50362](https://linux-hardware.org/?probe=6093f50362) | Mar 30, 2020 |
| Sony          | VPCEB42EG                   | Notebook    | [d2586cdd17](https://linux-hardware.org/?probe=d2586cdd17) | Mar 25, 2020 |
| Sony          | VPCEB42EG                   | Notebook    | [424402e2b1](https://linux-hardware.org/?probe=424402e2b1) | Mar 25, 2020 |
| ASUSTek       | GL553VE                     | Notebook    | [1238bea224](https://linux-hardware.org/?probe=1238bea224) | Mar 21, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [72a39494c1](https://linux-hardware.org/?probe=72a39494c1) | Mar 18, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [7dddec34d1](https://linux-hardware.org/?probe=7dddec34d1) | Mar 02, 2020 |
| Intel         | S5520HC E26045-457          | Server      | [49d0f0d68c](https://linux-hardware.org/?probe=49d0f0d68c) | Mar 01, 2020 |
| Intel         | S5520HC E26045-457          | Server      | [359532fc26](https://linux-hardware.org/?probe=359532fc26) | Mar 01, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [f1e468eec0](https://linux-hardware.org/?probe=f1e468eec0) | Feb 29, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [3740504388](https://linux-hardware.org/?probe=3740504388) | Feb 28, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [284484a6b6](https://linux-hardware.org/?probe=284484a6b6) | Feb 15, 2020 |
| Koompi        | Unknown                     | Notebook    | [46e5e1375d](https://linux-hardware.org/?probe=46e5e1375d) | Feb 12, 2020 |
| Shuttle       | FS81                        | Desktop     | [93c00d64e6](https://linux-hardware.org/?probe=93c00d64e6) | Feb 07, 2020 |
| MSI           | GF63 8RD                    | Notebook    | [6eae1d7ba9](https://linux-hardware.org/?probe=6eae1d7ba9) | Feb 01, 2020 |
| MSI           | GF63 8RD                    | Notebook    | [b7087b6ba5](https://linux-hardware.org/?probe=b7087b6ba5) | Jan 31, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [e3cbb2da5f](https://linux-hardware.org/?probe=e3cbb2da5f) | Jan 24, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [46c0e495c1](https://linux-hardware.org/?probe=46c0e495c1) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b2bc63b818](https://linux-hardware.org/?probe=b2bc63b818) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4ea2e33944](https://linux-hardware.org/?probe=4ea2e33944) | Jan 07, 2020 |
| AMI           | Cherry Trail FFD            | Notebook    | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| ASUSTek       | P9X79 WS                    | Desktop     | [7a8ccfd558](https://linux-hardware.org/?probe=7a8ccfd558) | Nov 21, 2019 |
| Jumper        | EZpad                       | Notebook    | [6dfb4e2274](https://linux-hardware.org/?probe=6dfb4e2274) | Oct 31, 2019 |
| Dell          | System Vostro 3450          | Notebook    | [2017fd9a25](https://linux-hardware.org/?probe=2017fd9a25) | Oct 29, 2019 |
| Dell          | System Vostro 3450          | Notebook    | [90391fe6fe](https://linux-hardware.org/?probe=90391fe6fe) | Sep 19, 2019 |
| Samsung       | NC208/NC108                 | Notebook    | [a99fe6de20](https://linux-hardware.org/?probe=a99fe6de20) | Sep 16, 2019 |
| Dell          | 0CU409                      | Desktop     | [a5aabfdba4](https://linux-hardware.org/?probe=a5aabfdba4) | Sep 09, 2019 |
| Dell          | 0CU409                      | Desktop     | [8efe3a4b92](https://linux-hardware.org/?probe=8efe3a4b92) | Sep 08, 2019 |
| Dell          | Inspiron 3421               | Notebook    | [46a7955491](https://linux-hardware.org/?probe=46a7955491) | Sep 04, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | Notebook    | [35dfb93d51](https://linux-hardware.org/?probe=35dfb93d51) | Sep 02, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | Notebook    | [635d10113c](https://linux-hardware.org/?probe=635d10113c) | Sep 02, 2019 |
| Gigabyte      | B360 M AORUS PRO-CF         | Desktop     | [657b0b4115](https://linux-hardware.org/?probe=657b0b4115) | Aug 28, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [f9ed638fe3](https://linux-hardware.org/?probe=f9ed638fe3) | Aug 27, 2019 |
| Dell          | System Inspiron N4110       | Notebook    | [1923c8603b](https://linux-hardware.org/?probe=1923c8603b) | Aug 13, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [6a22791c51](https://linux-hardware.org/?probe=6a22791c51) | Aug 02, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [9394c6057f](https://linux-hardware.org/?probe=9394c6057f) | Aug 01, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [6cf789df63](https://linux-hardware.org/?probe=6cf789df63) | Jul 26, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [a6040fd25f](https://linux-hardware.org/?probe=a6040fd25f) | Jul 21, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [e4ad262a5d](https://linux-hardware.org/?probe=e4ad262a5d) | Jul 18, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [c52b084692](https://linux-hardware.org/?probe=c52b084692) | Jul 08, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [06efccb71d](https://linux-hardware.org/?probe=06efccb71d) | Jul 07, 2019 |
| Wistron       | JIH55Y                      | Desktop     | [75d7b2909e](https://linux-hardware.org/?probe=75d7b2909e) | Jul 07, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [ab1717a7d5](https://linux-hardware.org/?probe=ab1717a7d5) | Jul 05, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [32eed13a8c](https://linux-hardware.org/?probe=32eed13a8c) | Jul 05, 2019 |
| Dell          | Inspiron 3537               | Notebook    | [96b08c73b2](https://linux-hardware.org/?probe=96b08c73b2) | Jul 03, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [9662a59bb6](https://linux-hardware.org/?probe=9662a59bb6) | Jun 19, 2019 |
| ASUSTek       | K46CM                       | Notebook    | [f695a76e03](https://linux-hardware.org/?probe=f695a76e03) | Jun 16, 2019 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [e3cbad71df](https://linux-hardware.org/?probe=e3cbad71df) | Jun 06, 2019 |
| Dell          | Precision M4800             | Notebook    | [87cd78dbb8](https://linux-hardware.org/?probe=87cd78dbb8) | Jun 06, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [2b022f3e6e](https://linux-hardware.org/?probe=2b022f3e6e) | Jun 06, 2019 |
| HP            | Unknown                     | Notebook    | [5a84e64836](https://linux-hardware.org/?probe=5a84e64836) | Jun 05, 2019 |
| Lenovo        | Unknown                     | Notebook    | [bb521ffe81](https://linux-hardware.org/?probe=bb521ffe81) | May 29, 2019 |
| Lenovo        | Unknown                     | Notebook    | [ded7e33a30](https://linux-hardware.org/?probe=ded7e33a30) | May 29, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [0142c9d319](https://linux-hardware.org/?probe=0142c9d319) | May 08, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [eab65462c8](https://linux-hardware.org/?probe=eab65462c8) | May 08, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | Notebook    | [11b1a757e3](https://linux-hardware.org/?probe=11b1a757e3) | May 07, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | Notebook    | [48a1bab21b](https://linux-hardware.org/?probe=48a1bab21b) | May 06, 2019 |
| Dell          | Inspiron 3420               | Notebook    | [97669e6bac](https://linux-hardware.org/?probe=97669e6bac) | Apr 28, 2019 |
| Lenovo        | ThinkPad X240 20AMA01LVA    | Notebook    | [60e3dddb8e](https://linux-hardware.org/?probe=60e3dddb8e) | Apr 18, 2019 |
| Lenovo        | ThinkPad X230 2325VEN       | Notebook    | [7de9f34ff3](https://linux-hardware.org/?probe=7de9f34ff3) | Apr 08, 2019 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [f98ce96fd7](https://linux-hardware.org/?probe=f98ce96fd7) | Dec 14, 2018 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [3b2f20eb21](https://linux-hardware.org/?probe=3b2f20eb21) | Dec 14, 2018 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [eb181d9db4](https://linux-hardware.org/?probe=eb181d9db4) | Nov 17, 2018 |
| Gigabyte      | H61M-DS2                    | Desktop     | [6c2f44420a](https://linux-hardware.org/?probe=6c2f44420a) | Nov 09, 2018 |
| Gigabyte      | H61M-DS2                    | Desktop     | [795142797e](https://linux-hardware.org/?probe=795142797e) | Nov 09, 2018 |
| MSI           | GP62 6QE                    | Notebook    | [0befde2891](https://linux-hardware.org/?probe=0befde2891) | Oct 29, 2018 |
| MSI           | GP62 6QE                    | Notebook    | [6d5cda0177](https://linux-hardware.org/?probe=6d5cda0177) | Oct 29, 2018 |
| ASUSTek       | FX503VM                     | Notebook    | [c3eafeed41](https://linux-hardware.org/?probe=c3eafeed41) | May 23, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [b73b24ff47](https://linux-hardware.org/?probe=b73b24ff47) | May 16, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [4ced3a8a3c](https://linux-hardware.org/?probe=4ced3a8a3c) | Feb 04, 2018 |
| HP            | Notebook                    | Notebook    | [8f94426008](https://linux-hardware.org/?probe=8f94426008) | Dec 21, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [96a6c5cbab](https://linux-hardware.org/?probe=96a6c5cbab) | Dec 17, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [f59b817feb](https://linux-hardware.org/?probe=f59b817feb) | Dec 12, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [06a39a2c60](https://linux-hardware.org/?probe=06a39a2c60) | Dec 12, 2017 |
| Lenovo        | ThinkCentre M55e 9389AN1    | Desktop     | [850f4b963c](https://linux-hardware.org/?probe=850f4b963c) | Dec 08, 2017 |
| Dell          | Precision M4600             | Notebook    | [dbbeb2486e](https://linux-hardware.org/?probe=dbbeb2486e) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [7ee7ca743b](https://linux-hardware.org/?probe=7ee7ca743b) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [28ae3d12b8](https://linux-hardware.org/?probe=28ae3d12b8) | Dec 03, 2017 |
| Lenovo        | ThinkCentre M55e 9389AN1    | Desktop     | [e764602f25](https://linux-hardware.org/?probe=e764602f25) | Dec 02, 2017 |
| ASUSTek       | GL552JX                     | Notebook    | [c3e4792075](https://linux-hardware.org/?probe=c3e4792075) | Dec 10, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Vietnam/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 95        | 15.37%  |
| Ubuntu 22.04                 | 53        | 8.58%   |
| Arch Rolling                 | 38        | 6.15%   |
| Ubuntu 18.04                 | 36        | 5.83%   |
| Arch                         | 17        | 2.75%   |
| ArcoLinux Rolling            | 14        | 2.27%   |
| Fedora 37                    | 12        | 1.94%   |
| Fedora 38                    | 11        | 1.78%   |
| Debian 12                    | 10        | 1.62%   |
| Pop!_OS 22.04                | 9         | 1.46%   |
| Manjaro                      | 9         | 1.46%   |
| EndeavourOS Rolling          | 8         | 1.29%   |
| Debian 10                    | 8         | 1.29%   |
| Zorin 16                     | 7         | 1.13%   |
| Ubuntu 23.10                 | 7         | 1.13%   |
| Pop!_OS 20.04                | 7         | 1.13%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 1.13%   |
| Debian 11                    | 7         | 1.13%   |
| Xero Rolling                 | 6         | 0.97%   |
| Ubuntu 21.04                 | 6         | 0.97%   |
| OpenMandriva 23.03           | 6         | 0.97%   |
| KDE neon 20.04               | 6         | 0.97%   |
| Fedora 39                    | 6         | 0.97%   |
| Ubuntu 21.10                 | 5         | 0.81%   |
| Ubuntu 19.10                 | 5         | 0.81%   |
| Ubuntu 16.04                 | 5         | 0.81%   |
| OpenMandriva 4.2             | 5         | 0.81%   |
| Manjaro 20.2                 | 5         | 0.81%   |
| Linux Mint 21.2              | 5         | 0.81%   |
| Ubuntu Unity 16.04           | 4         | 0.65%   |
| Ubuntu 23.04                 | 4         | 0.65%   |
| Ubuntu 20.10                 | 4         | 0.65%   |
| Ubuntu 19.04                 | 4         | 0.65%   |
| Pop!_OS 21.04                | 4         | 0.65%   |
| Pop!_OS 20.10                | 4         | 0.65%   |
| OpenMandriva 4.3             | 4         | 0.65%   |
| Linux Mint 21.1              | 4         | 0.65%   |
| Linux Mint 20.3              | 4         | 0.65%   |
| Kubuntu 22.04                | 4         | 0.65%   |
| Fedora 34                    | 4         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 225       | 37.31%  |
| Arch             | 55        | 9.12%   |
| Fedora           | 42        | 6.97%   |
| Pop!_OS          | 26        | 4.31%   |
| Linux Mint       | 25        | 4.15%   |
| Debian           | 25        | 4.15%   |
| OpenMandriva     | 23        | 3.81%   |
| Manjaro          | 23        | 3.81%   |
| ArcoLinux        | 15        | 2.49%   |
| Kubuntu          | 11        | 1.82%   |
| Zorin            | 10        | 1.66%   |
| openSUSE         | 10        | 1.66%   |
| Ubuntu Unity     | 8         | 1.33%   |
| EndeavourOS      | 8         | 1.33%   |
| KDE neon         | 7         | 1.16%   |
| Kali             | 7         | 1.16%   |
| Endless          | 7         | 1.16%   |
| Xubuntu          | 6         | 1%      |
| Xero             | 6         | 1%      |
| Elementary       | 6         | 1%      |
| Lubuntu          | 5         | 0.83%   |
| Gentoo           | 5         | 0.83%   |
| Clear Linux      | 5         | 0.83%   |
| ChimeraOS        | 4         | 0.66%   |
| Ubuntu MATE      | 3         | 0.5%    |
| SteamOS          | 3         | 0.5%    |
| Nobara           | 3         | 0.5%    |
| CentOS           | 3         | 0.5%    |
| Void Linux       | 2         | 0.33%   |
| ROSA             | 2         | 0.33%   |
| Parrot           | 2         | 0.33%   |
| Oracle Linux     | 2         | 0.33%   |
| MX               | 2         | 0.33%   |
| LMDE             | 2         | 0.33%   |
| Garuda Linux     | 2         | 0.33%   |
| Artix            | 2         | 0.33%   |
| Ultramarine      | 1         | 0.17%   |
| Solus            | 1         | 0.17%   |
| RHEL             | 1         | 0.17%   |
| org.kde.Platform | 1         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 9         | 1.36%   |
| 5.4.0-37-generic         | 8         | 1.2%    |
| 5.4.0-52-generic         | 7         | 1.05%   |
| 5.4.0-48-generic         | 7         | 1.05%   |
| 6.2.6-desktop-1omv2390   | 6         | 0.9%    |
| 5.4.0-58-generic         | 6         | 0.9%    |
| 5.4.0-40-generic         | 6         | 0.9%    |
| 6.5.8-arch1-1            | 5         | 0.75%   |
| 6.2.0-34-generic         | 5         | 0.75%   |
| 5.8.0-55-generic         | 5         | 0.75%   |
| 5.8.0-53-generic         | 5         | 0.75%   |
| 5.15.0-91-generic        | 5         | 0.75%   |
| 5.15.0-56-generic        | 5         | 0.75%   |
| 5.15.0-52-generic        | 5         | 0.75%   |
| 5.11.0-41-generic        | 5         | 0.75%   |
| 5.11.0-38-generic        | 5         | 0.75%   |
| 5.11.0-37-generic        | 5         | 0.75%   |
| 5.10.14-desktop-1omv4002 | 5         | 0.75%   |
| 6.5.0-15-generic         | 4         | 0.6%    |
| 6.5.0-14-generic         | 4         | 0.6%    |
| 6.2.9-300.fc38.x86_64    | 4         | 0.6%    |
| 6.2.0-36-generic         | 4         | 0.6%    |
| 5.8.0-7642-generic       | 4         | 0.6%    |
| 5.8.0-50-generic         | 4         | 0.6%    |
| 5.8.0-43-generic         | 4         | 0.6%    |
| 5.4.0-47-generic         | 4         | 0.6%    |
| 5.4.0-26-generic         | 4         | 0.6%    |
| 5.15.0-48-generic        | 4         | 0.6%    |
| 5.15.0-47-generic        | 4         | 0.6%    |
| 5.0.0-23-generic         | 4         | 0.6%    |
| 4.10.0-28-generic        | 4         | 0.6%    |
| 6.8.1-arch1-1            | 3         | 0.45%   |
| 6.2.0-76060200-generic   | 3         | 0.45%   |
| 6.2.0-32-generic         | 3         | 0.45%   |
| 6.1.8-200.fc37.x86_64    | 3         | 0.45%   |
| 6.1.0-18-amd64           | 3         | 0.45%   |
| 6.1.0-13-amd64           | 3         | 0.45%   |
| 5.8.0-48-generic         | 3         | 0.45%   |
| 5.8.0-44-generic         | 3         | 0.45%   |
| 5.4.0-72-generic         | 3         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 76        | 11.97%  |
| 5.15.0  | 58        | 9.13%   |
| 5.8.0   | 37        | 5.83%   |
| 5.11.0  | 31        | 4.88%   |
| 6.2.0   | 24        | 3.78%   |
| 6.5.0   | 18        | 2.83%   |
| 5.13.0  | 15        | 2.36%   |
| 4.15.0  | 15        | 2.36%   |
| 5.19.0  | 13        | 2.05%   |
| 5.0.0   | 13        | 2.05%   |
| 6.1.0   | 12        | 1.89%   |
| 5.3.0   | 12        | 1.89%   |
| 5.10.0  | 10        | 1.57%   |
| 6.2.6   | 9         | 1.42%   |
| 4.18.0  | 9         | 1.42%   |
| 6.2.9   | 8         | 1.26%   |
| 4.19.0  | 6         | 0.94%   |
| 6.5.8   | 5         | 0.79%   |
| 6.5.6   | 5         | 0.79%   |
| 6.5.5   | 5         | 0.79%   |
| 5.10.14 | 5         | 0.79%   |
| 4.10.0  | 5         | 0.79%   |
| 6.3.9   | 4         | 0.63%   |
| 6.3.5   | 4         | 0.63%   |
| 5.16.7  | 4         | 0.63%   |
| 6.8.1   | 3         | 0.47%   |
| 6.7.4   | 3         | 0.47%   |
| 6.6.9   | 3         | 0.47%   |
| 6.4.11  | 3         | 0.47%   |
| 6.1.8   | 3         | 0.47%   |
| 6.1.11  | 3         | 0.47%   |
| 6.1.1   | 3         | 0.47%   |
| 6.0.8   | 3         | 0.47%   |
| 6.0.12  | 3         | 0.47%   |
| 5.9.0   | 3         | 0.47%   |
| 5.19.12 | 3         | 0.47%   |
| 5.15.60 | 3         | 0.47%   |
| 5.14.0  | 3         | 0.47%   |
| 6.8.6   | 2         | 0.31%   |
| 6.8.0   | 2         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 85        | 13.56%  |
| 5.15    | 72        | 11.48%  |
| 6.2     | 49        | 7.81%   |
| 6.5     | 40        | 6.38%   |
| 5.8     | 40        | 6.38%   |
| 6.1     | 36        | 5.74%   |
| 5.11    | 33        | 5.26%   |
| 5.10    | 23        | 3.67%   |
| 5.19    | 22        | 3.51%   |
| 5.13    | 21        | 3.35%   |
| 6.6     | 18        | 2.87%   |
| 5.0     | 16        | 2.55%   |
| 4.15    | 16        | 2.55%   |
| 6.4     | 14        | 2.23%   |
| 6.0     | 13        | 2.07%   |
| 5.3     | 12        | 1.91%   |
| 6.7     | 11        | 1.75%   |
| 6.3     | 11        | 1.75%   |
| 5.9     | 11        | 1.75%   |
| 6.8     | 10        | 1.59%   |
| 5.18    | 9         | 1.44%   |
| 5.12    | 9         | 1.44%   |
| 4.18    | 9         | 1.44%   |
| 5.16    | 8         | 1.28%   |
| 5.14    | 8         | 1.28%   |
| 4.19    | 8         | 1.28%   |
| 5.17    | 5         | 0.8%    |
| 4.10    | 5         | 0.8%    |
| 5.7     | 3         | 0.48%   |
| 5.6     | 2         | 0.32%   |
| 5.5     | 2         | 0.32%   |
| 4.13    | 2         | 0.32%   |
| 4.4     | 1         | 0.16%   |
| 4.12    | 1         | 0.16%   |
| 4.1     | 1         | 0.16%   |
| 3.10    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 579       | 99.31%  |
| i686    | 2         | 0.34%   |
| aarch64 | 2         | 0.34%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 301       | 49.92%  |
| KDE5             | 92        | 15.26%  |
| Unknown          | 73        | 12.11%  |
| XFCE             | 40        | 6.63%   |
| X-Cinnamon       | 20        | 3.32%   |
| KDE              | 13        | 2.16%   |
| Unity            | 8         | 1.33%   |
| MATE             | 7         | 1.16%   |
| LXQt             | 7         | 1.16%   |
| Pantheon         | 6         | 1%      |
| i3               | 5         | 0.83%   |
| Hyprland         | 5         | 0.83%   |
| Cinnamon         | 4         | 0.66%   |
| KDE6             | 3         | 0.5%    |
| bspwm            | 3         | 0.5%    |
| Openbox          | 2         | 0.33%   |
| LXDE             | 2         | 0.33%   |
| Deepin           | 2         | 0.33%   |
| awesome          | 2         | 0.33%   |
| X-Generic        | 1         | 0.17%   |
| sway             | 1         | 0.17%   |
| qtile            | 1         | 0.17%   |
| lightdm-xsession | 1         | 0.17%   |
| LeftWM           | 1         | 0.17%   |
| KDE4             | 1         | 0.17%   |
| fluxbox          | 1         | 0.17%   |
| Budgie           | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 411       | 68.16%  |
| Wayland | 142       | 23.55%  |
| Unknown | 37        | 6.14%   |
| Tty     | 13        | 2.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 263       | 43.69%  |
| GDM     | 92        | 15.28%  |
| SDDM    | 86        | 14.29%  |
| GDM3    | 73        | 12.13%  |
| LightDM | 64        | 10.63%  |
| TDM     | 16        | 2.66%   |
| XDM     | 2         | 0.33%   |
| SLiM    | 2         | 0.33%   |
| LY-DM   | 2         | 0.33%   |
| KDM     | 1         | 0.17%   |
| GREETD  | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 450       | 76.53%  |
| Unknown     | 62        | 10.54%  |
| vi_VN       | 35        | 5.95%   |
| C           | 18        | 3.06%   |
| en_GB       | 7         | 1.19%   |
| ru_RU       | 5         | 0.85%   |
| en_AU       | 4         | 0.68%   |
| ko_KR       | 1         | 0.17%   |
| ja_JP       | 1         | 0.17%   |
| fr_FR       | 1         | 0.17%   |
| en_US.UTF=8 | 1         | 0.17%   |
| en_BW       | 1         | 0.17%   |
| de_DE       | 1         | 0.17%   |
| de          | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 381       | 64.03%  |
| BIOS | 214       | 35.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 437       | 73.2%   |
| Btrfs    | 77        | 12.9%   |
| Overlay  | 34        | 5.7%    |
| Tmpfs    | 17        | 2.85%   |
| Unknown  | 14        | 2.35%   |
| Zfs      | 8         | 1.34%   |
| Xfs      | 6         | 1.01%   |
| F2fs     | 2         | 0.34%   |
| Reiserfs | 1         | 0.17%   |
| Ext3     | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 309       | 52.46%  |
| Unknown | 240       | 40.75%  |
| MBR     | 40        | 6.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 507       | 85.5%   |
| Yes       | 86        | 14.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 343       | 57.36%  |
| Yes       | 255       | 42.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 112       | 19.21%  |
| ASUSTek Computer               | 98        | 16.81%  |
| Lenovo                         | 93        | 15.95%  |
| Hewlett-Packard                | 68        | 11.66%  |
| Gigabyte Technology            | 49        | 8.4%    |
| MSI                            | 37        | 6.35%   |
| Acer                           | 31        | 5.32%   |
| Apple                          | 11        | 1.89%   |
| Samsung Electronics            | 6         | 1.03%   |
| Intel                          | 6         | 1.03%   |
| Toshiba                        | 5         | 0.86%   |
| Sony                           | 5         | 0.86%   |
| ASRock                         | 5         | 0.86%   |
| Supermicro                     | 4         | 0.69%   |
| HUAWEI                         | 4         | 0.69%   |
| Google                         | 4         | 0.69%   |
| Chuwi                          | 4         | 0.69%   |
| ZOTAC                          | 3         | 0.51%   |
| GuoGuang                       | 3         | 0.51%   |
| Unknown                        | 3         | 0.51%   |
| Wistron                        | 2         | 0.34%   |
| Timi                           | 2         | 0.34%   |
| MASSCOM VIETNAM                | 2         | 0.34%   |
| Foxconn                        | 2         | 0.34%   |
| Valve                          | 1         | 0.17%   |
| TENKU                          | 1         | 0.17%   |
| T-bao                          | 1         | 0.17%   |
| Shuttle                        | 1         | 0.17%   |
| Shenzhen Amediatech Technology | 1         | 0.17%   |
| Raspberry Pi Foundation        | 1         | 0.17%   |
| Panasonic                      | 1         | 0.17%   |
| OrangePi                       | 1         | 0.17%   |
| Microsoft                      | 1         | 0.17%   |
| LG Electronics                 | 1         | 0.17%   |
| Koompi                         | 1         | 0.17%   |
| Koloe                          | 1         | 0.17%   |
| Jumper                         | 1         | 0.17%   |
| itel Mobile Limited            | 1         | 0.17%   |
| Huanan                         | 1         | 0.17%   |
| Gateway                        | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 9         | 1.54%   |
| Gigabyte H61M-DS2                        | 6         | 1.03%   |
| ASUS All Series                          | 5         | 0.86%   |
| Lenovo Legion 5 15ARH05 82B5             | 4         | 0.69%   |
| Dell Inspiron 3537                       | 4         | 0.69%   |
| MSI MS-7B98                              | 3         | 0.51%   |
| MSI MS-7B89                              | 3         | 0.51%   |
| Lenovo ThinkPad E14 20RAS0KX00           | 3         | 0.51%   |
| HP Notebook                              | 3         | 0.51%   |
| ASUS X411UA                              | 3         | 0.51%   |
| Toshiba Satellite L840                   | 2         | 0.34%   |
| Supermicro SYS-7039A-I                   | 2         | 0.34%   |
| MSI MS-7C89                              | 2         | 0.34%   |
| MSI MS-7823                              | 2         | 0.34%   |
| MSI Modern 14 B5M                        | 2         | 0.34%   |
| MSI GF63 8RD                             | 2         | 0.34%   |
| MASSCOM VIETNAM L133                     | 2         | 0.34%   |
| Lenovo ThinkPad W530 2447EJ9             | 2         | 0.34%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0         | 2         | 0.34%   |
| Lenovo Legion 5 15ACH6H 82JU             | 2         | 0.34%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 2         | 0.34%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 2         | 0.34%   |
| Lenovo IdeaPad 5 14ITL05 82FE            | 2         | 0.34%   |
| HUAWEI BOM-WXX9                          | 2         | 0.34%   |
| HP Z440 Workstation                      | 2         | 0.34%   |
| HP Victus by Laptop 16-e0xxx             | 2         | 0.34%   |
| HP ProBook 450 G1                        | 2         | 0.34%   |
| HP ProBook 440 G7                        | 2         | 0.34%   |
| HP Laptop 14-bs0xx                       | 2         | 0.34%   |
| HP EliteBook 8470p                       | 2         | 0.34%   |
| HP EliteBook 845 14 inch G10 Notebook PC | 2         | 0.34%   |
| HP EliteBook 840 G2                      | 2         | 0.34%   |
| HP 15                                    | 2         | 0.34%   |
| GuoGuang IC2M1028V-J                     | 2         | 0.34%   |
| Gigabyte H81M-DS2                        | 2         | 0.34%   |
| Gigabyte G41M-ES2L                       | 2         | 0.34%   |
| Gigabyte B75M-D3H                        | 2         | 0.34%   |
| Gigabyte B450M GAMING                    | 2         | 0.34%   |
| Gigabyte B360M-D3H                       | 2         | 0.34%   |
| Dell XPS 15 9570                         | 2         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 42        | 7.2%    |
| Dell Latitude      | 27        | 4.63%   |
| Dell Inspiron      | 25        | 4.29%   |
| Dell Vostro        | 19        | 3.26%   |
| ASUS ROG           | 19        | 3.26%   |
| Lenovo IdeaPad     | 18        | 3.09%   |
| Acer Aspire        | 18        | 3.09%   |
| HP EliteBook       | 14        | 2.4%    |
| ASUS VivoBook      | 12        | 2.06%   |
| Lenovo Legion      | 11        | 1.89%   |
| Dell Precision     | 10        | 1.72%   |
| ASUS PRIME         | 10        | 1.72%   |
| Lenovo ThinkBook   | 9         | 1.54%   |
| HP ProBook         | 9         | 1.54%   |
| Dell XPS           | 9         | 1.54%   |
| Dell OptiPlex      | 9         | 1.54%   |
| Unknown            | 9         | 1.54%   |
| ASUS ASUS          | 7         | 1.2%    |
| Acer Nitro         | 7         | 1.2%    |
| HP Laptop          | 6         | 1.03%   |
| Gigabyte H61M-DS2  | 6         | 1.03%   |
| Dell System        | 5         | 0.86%   |
| ASUS All           | 5         | 0.86%   |
| MSI Modern         | 4         | 0.69%   |
| MSI GF63           | 4         | 0.69%   |
| HP ZBook           | 4         | 0.69%   |
| HP Pavilion        | 4         | 0.69%   |
| Dell G3            | 4         | 0.69%   |
| Toshiba Satellite  | 3         | 0.51%   |
| MSI MS-7B98        | 3         | 0.51%   |
| MSI MS-7B89        | 3         | 0.51%   |
| Lenovo ThinkCentre | 3         | 0.51%   |
| HP Notebook        | 3         | 0.51%   |
| HP Compaq          | 3         | 0.51%   |
| ASUS X411UA        | 3         | 0.51%   |
| ASUS TUF           | 3         | 0.51%   |
| ASUS P8H61-MX      | 3         | 0.51%   |
| Apple MacBookPro11 | 3         | 0.51%   |
| Acer Swift         | 3         | 0.51%   |
| Acer Predator      | 3         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 79        | 13.55%  |
| 2020    | 62        | 10.63%  |
| 2021    | 53        | 9.09%   |
| 2019    | 51        | 8.75%   |
| 2012    | 44        | 7.55%   |
| 2013    | 41        | 7.03%   |
| 2017    | 36        | 6.17%   |
| 2014    | 36        | 6.17%   |
| 2022    | 32        | 5.49%   |
| 2015    | 31        | 5.32%   |
| 2016    | 30        | 5.15%   |
| 2011    | 26        | 4.46%   |
| 2023    | 20        | 3.43%   |
| 2010    | 14        | 2.4%    |
| 2009    | 14        | 2.4%    |
| 2008    | 5         | 0.86%   |
| 2007    | 4         | 0.69%   |
| 2024    | 2         | 0.34%   |
| Unknown | 2         | 0.34%   |
| 2006    | 1         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 400       | 68.61%  |
| Desktop        | 155       | 26.59%  |
| Tablet         | 7         | 1.2%    |
| Convertible    | 7         | 1.2%    |
| Mini pc        | 5         | 0.86%   |
| Server         | 5         | 0.86%   |
| System on chip | 2         | 0.34%   |
| All in one     | 2         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 539       | 91.51%  |
| Enabled  | 50        | 8.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 579       | 99.31%  |
| Yes  | 4         | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 148       | 25.08%  |
| 16.01-24.0  | 131       | 22.2%   |
| 8.01-16.0   | 111       | 18.81%  |
| 3.01-4.0    | 81        | 13.73%  |
| 32.01-64.0  | 64        | 10.85%  |
| 24.01-32.0  | 25        | 4.24%   |
| 1.01-2.0    | 16        | 2.71%   |
| 64.01-256.0 | 9         | 1.53%   |
| 2.01-3.0    | 4         | 0.68%   |
| 0.51-1.0    | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 201       | 31.85%  |
| 4.01-8.0   | 132       | 20.92%  |
| 1.01-2.0   | 132       | 20.92%  |
| 3.01-4.0   | 97        | 15.37%  |
| 8.01-16.0  | 42        | 6.66%   |
| 0.51-1.0   | 14        | 2.22%   |
| 16.01-24.0 | 9         | 1.43%   |
| 24.01-32.0 | 2         | 0.32%   |
| 0.01-0.5   | 2         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 338       | 56.81%  |
| 2      | 198       | 33.28%  |
| 3      | 43        | 7.23%   |
| 4      | 10        | 1.68%   |
| 5      | 3         | 0.5%    |
| 0      | 2         | 0.34%   |
| 9      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 487       | 83.39%  |
| Yes       | 97        | 16.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 489       | 83.02%  |
| No        | 100       | 16.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 489       | 83.45%  |
| No        | 97        | 16.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 430       | 73.25%  |
| No        | 157       | 26.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Vietnam | 583       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Ho Chi Minh City | 268       | 44.15%  |
| Hanoi            | 200       | 32.95%  |
| Da Nang          | 15        | 2.47%   |
| Can Tho          | 10        | 1.65%   |
| Bien Hoa         | 7         | 1.15%   |
| Bac Giang        | 7         | 1.15%   |
| Nha Trang        | 6         | 0.99%   |
| Vũng Tàu       | 4         | 0.66%   |
| Thai Nguyen      | 4         | 0.66%   |
| Tay Ninh         | 4         | 0.66%   |
| Nam Định      | 4         | 0.66%   |
| Huế            | 4         | 0.66%   |
| Tua Chua         | 3         | 0.49%   |
| Thuan An         | 3         | 0.49%   |
| Thu Duc          | 3         | 0.49%   |
| Quảng Ngai     | 3         | 0.49%   |
| Nga Bay          | 3         | 0.49%   |
| Hai Duong        | 3         | 0.49%   |
| Dien Ban         | 3         | 0.49%   |
| Buon Ma Thuot    | 3         | 0.49%   |
| Đông Hà       | 2         | 0.33%   |
| Vinh Phuc        | 2         | 0.33%   |
| Vinh             | 2         | 0.33%   |
| Viet Tri         | 2         | 0.33%   |
| Tinh Binh Duong  | 2         | 0.33%   |
| Hung Yen         | 2         | 0.33%   |
| Haiphong         | 2         | 0.33%   |
| Binh Hoa         | 2         | 0.33%   |
| Binh Duong       | 2         | 0.33%   |
| Bến Tre        | 2         | 0.33%   |
| Bao Loc          | 2         | 0.33%   |
| Vi Thanh         | 1         | 0.16%   |
| Tra Vinh         | 1         | 0.16%   |
| Tinh Quang Binh  | 1         | 0.16%   |
| Tinh GJong Nai   | 1         | 0.16%   |
| Thon Dien Ha     | 1         | 0.16%   |
| Thanh Hóa       | 1         | 0.16%   |
| Tan An           | 1         | 0.16%   |
| Qui Nhon         | 1         | 0.16%   |
| Quang Trung      | 1         | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 131       | 172    | 15.25%  |
| WDC                         | 129       | 166    | 15.02%  |
| Seagate                     | 78        | 92     | 9.08%   |
| Toshiba                     | 53        | 70     | 6.17%   |
| SK hynix                    | 44        | 51     | 5.12%   |
| Kingston                    | 41        | 53     | 4.77%   |
| SanDisk                     | 33        | 40     | 3.84%   |
| Micron Technology           | 33        | 37     | 3.84%   |
| Unknown                     | 31        | 37     | 3.61%   |
| Intel                       | 30        | 32     | 3.49%   |
| HGST                        | 30        | 32     | 3.49%   |
| Hitachi                     | 16        | 21     | 1.86%   |
| Crucial                     | 16        | 19     | 1.86%   |
| KIOXIA                      | 11        | 14     | 1.28%   |
| Plextor                     | 10        | 10     | 1.16%   |
| Lexar                       | 8         | 8      | 0.93%   |
| Apple                       | 8         | 10     | 0.93%   |
| OSCOO                       | 7         | 8      | 0.81%   |
| Transcend                   | 6         | 6      | 0.7%    |
| TO Exter                    | 6         | 9      | 0.7%    |
| MAXIO Technology (Hangzhou) | 6         | 6      | 0.7%    |
| KingSpec                    | 6         | 6      | 0.7%    |
| Colorful                    | 6         | 6      | 0.7%    |
| Netac                       | 5         | 6      | 0.58%   |
| China                       | 5         | 5      | 0.58%   |
| XSTAR                       | 4         | 4      | 0.47%   |
| Kingmax                     | 4         | 4      | 0.47%   |
| Gigabyte Technology         | 4         | 4      | 0.47%   |
| Unknown                     | 4         | 4      | 0.47%   |
| SPCC                        | 3         | 3      | 0.35%   |
| OCZ                         | 3         | 3      | 0.35%   |
| LITEON                      | 3         | 3      | 0.35%   |
| JMicron Technology          | 3         | 3      | 0.35%   |
| Fujitsu                     | 3         | 4      | 0.35%   |
| FORESEE                     | 3         | 3      | 0.35%   |
| Apacer                      | 3         | 3      | 0.35%   |
| ZOTAC                       | 2         | 2      | 0.23%   |
| UMIS                        | 2         | 2      | 0.23%   |
| SSSTC                       | 2         | 2      | 0.23%   |
| Silicon Motion              | 2         | 4      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 12        | 1.32%   |
| HGST HTS721010A9E630 1TB                           | 12        | 1.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 11        | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB                     | 11        | 1.21%   |
| Samsung SSD 860 EVO 250GB                          | 10        | 1.1%    |
| Kingston SA400S37240G 240GB SSD                    | 8         | 0.88%   |
| Toshiba MQ01ABF050 500GB                           | 7         | 0.77%   |
| Samsung SSD 980 1TB                                | 7         | 0.77%   |
| Samsung SSD 860 EVO 500GB                          | 7         | 0.77%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 7         | 0.77%   |
| Unknown MMC Card  32GB                             | 6         | 0.66%   |
| TO Exter nal USB 3.0 500GB                         | 6         | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 6         | 0.66%   |
| Samsung NVMe SSD Drive 512GB                       | 6         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 6         | 0.66%   |
| Kingston OM8PCP3512F-AI1 512GB                     | 6         | 0.66%   |
| HGST HTS545050A7E680 500GB                         | 6         | 0.66%   |
| WDC WD5000AAKX-00ERMA0 500GB                       | 5         | 0.55%   |
| Toshiba MQ04ABF100 1TB                             | 5         | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 5         | 0.55%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB | 5         | 0.55%   |
| Kingston SA400S37480G 480GB SSD                    | 5         | 0.55%   |
| Kingston SA400S37120G 120GB SSD                    | 5         | 0.55%   |
| Crucial CT240BX500SSD1 240GB                       | 5         | 0.55%   |
| XSTAR SSD 128GB                                    | 4         | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                   | 4         | 0.44%   |
| WDC WD5000LPLX-60ZNTT1 500GB                       | 4         | 0.44%   |
| WDC WD2500AAKX-00ERMA0 250GB                       | 4         | 0.44%   |
| Unknown SD/MMC/MS PRO 128GB                        | 4         | 0.44%   |
| Toshiba MQ01ABD100 1TB                             | 4         | 0.44%   |
| SK hynix NVMe SSD Drive 256GB                      | 4         | 0.44%   |
| Seagate ST500DM002-1BD142 500GB                    | 4         | 0.44%   |
| Seagate ST1000LM049-2GH172 1TB                     | 4         | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB                     | 4         | 0.44%   |
| Samsung SSD 870 EVO 500GB                          | 4         | 0.44%   |
| Samsung MZALQ512HBLU-00BL2 512GB                   | 4         | 0.44%   |
| Micron 2210_MTFDHBA512QFD 512GB                    | 4         | 0.44%   |
| Lexar 128GB SSD                                    | 4         | 0.44%   |
| Unknown                                            | 4         | 0.44%   |
| WDC WD5000LPLX-66ZNTT1 500GB                       | 3         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 90        | 120    | 33.96%  |
| Seagate  | 78        | 91     | 29.43%  |
| Toshiba  | 37        | 45     | 13.96%  |
| HGST     | 30        | 32     | 11.32%  |
| Hitachi  | 16        | 21     | 6.04%   |
| TO Exter | 6         | 9      | 2.26%   |
| Unknown  | 4         | 4      | 1.51%   |
| Fujitsu  | 3         | 4      | 1.13%   |
| CSD      | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 62     | 17.82%  |
| Kingston            | 26        | 34     | 9.45%   |
| WDC                 | 24        | 24     | 8.73%   |
| SanDisk             | 16        | 20     | 5.82%   |
| Crucial             | 15        | 16     | 5.45%   |
| Intel               | 13        | 14     | 4.73%   |
| Plextor             | 10        | 10     | 3.64%   |
| Lexar               | 8         | 8      | 2.91%   |
| Transcend           | 6         | 6      | 2.18%   |
| SK hynix            | 6         | 6      | 2.18%   |
| KingSpec            | 6         | 6      | 2.18%   |
| Apple               | 6         | 8      | 2.18%   |
| Toshiba             | 5         | 6      | 1.82%   |
| OSCOO               | 5         | 5      | 1.82%   |
| Netac               | 5         | 6      | 1.82%   |
| Colorful            | 5         | 5      | 1.82%   |
| China               | 5         | 5      | 1.82%   |
| XSTAR               | 4         | 4      | 1.45%   |
| Micron Technology   | 4         | 4      | 1.45%   |
| LITEON              | 3         | 3      | 1.09%   |
| Kingmax             | 3         | 3      | 1.09%   |
| Gigabyte Technology | 3         | 3      | 1.09%   |
| FORESEE             | 3         | 3      | 1.09%   |
| Apacer              | 3         | 3      | 1.09%   |
| ZOTAC               | 2         | 2      | 0.73%   |
| SPCC                | 2         | 2      | 0.73%   |
| OCZ                 | 2         | 2      | 0.73%   |
| Maxtor              | 2         | 4      | 0.73%   |
| LITEONIT            | 2         | 2      | 0.73%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.73%   |
| KingDian            | 2         | 3      | 0.73%   |
| Hikvision           | 2         | 2      | 0.73%   |
| External            | 2         | 2      | 0.73%   |
| W800S               | 1         | 1      | 0.36%   |
| VSP-128G            | 1         | 1      | 0.36%   |
| VSP                 | 1         | 1      | 0.36%   |
| Vaseky              | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |
| Team                | 1         | 1      | 0.36%   |
| SAM                 | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 267       | 354    | 33.84%  |
| SSD     | 248       | 311    | 31.43%  |
| HDD     | 231       | 327    | 29.28%  |
| MMC     | 25        | 31     | 3.17%   |
| Unknown | 18        | 18     | 2.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 371       | 624    | 53.77%  |
| NVMe | 267       | 352    | 38.7%   |
| SAS  | 27        | 34     | 3.91%   |
| MMC  | 25        | 31     | 3.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 322       | 459    | 69.85%  |
| 0.51-1.0   | 107       | 130    | 23.21%  |
| 1.01-2.0   | 16        | 23     | 3.47%   |
| 3.01-4.0   | 7         | 8      | 1.52%   |
| 4.01-10.0  | 7         | 16     | 1.52%   |
| 2.01-3.0   | 2         | 2      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 203       | 32.79%  |
| 251-500        | 143       | 23.1%   |
| 501-1000       | 69        | 11.15%  |
| 51-100         | 48        | 7.75%   |
| Unknown        | 35        | 5.65%   |
| 1001-2000      | 32        | 5.17%   |
| 21-50          | 31        | 5.01%   |
| 1-20           | 29        | 4.68%   |
| More than 3000 | 15        | 2.42%   |
| 2001-3000      | 14        | 2.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 232       | 37.36%  |
| 21-50          | 115       | 18.52%  |
| 51-100         | 77        | 12.4%   |
| 101-250        | 76        | 12.24%  |
| 251-500        | 45        | 7.25%   |
| Unknown        | 35        | 5.64%   |
| 501-1000       | 23        | 3.7%    |
| More than 3000 | 7         | 1.13%   |
| 1001-2000      | 7         | 1.13%   |
| 2001-3000      | 4         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD             | 3         | 3      | 4.69%   |
| HGST HTS545050A7E680 500GB                   | 3         | 4      | 4.69%   |
| WDC WD3200AAKX-001CA0 320GB                  | 2         | 2      | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 3.13%   |
| Kingston SA400S37240G 240GB SSD              | 2         | 2      | 3.13%   |
| HGST HTS725050A7E630 500GB                   | 2         | 2      | 3.13%   |
| WDC WD60PURZ-85ZUFY1 6TB                     | 1         | 3      | 1.56%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 1.56%   |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 1.56%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.56%   |
| WDC WD3200AAJS-00L7A0 320GB                  | 1         | 1      | 1.56%   |
| WDC WD32 00BEVT-24A23 320GB                  | 1         | 1      | 1.56%   |
| WDC WD2500BEVT-75ZCT2 250GB                  | 1         | 1      | 1.56%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 1.56%   |
| WDC WD10EZRX-00A3KB0 1TB                     | 1         | 1      | 1.56%   |
| WDC WD10EARS-00Y5B1 1TB                      | 1         | 1      | 1.56%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1         | 1      | 1.56%   |
| Unknown Bamba-240GB SSD                      | 1         | 1      | 1.56%   |
| Transcend TS256GSSD230S 256GB                | 1         | 1      | 1.56%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 1.56%   |
| Toshiba MK8046GSX 80GB                       | 1         | 1      | 1.56%   |
| Toshiba MK3275GSX 320GB                      | 1         | 1      | 1.56%   |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 1.56%   |
| Toshiba HDWK105 500GB                        | 1         | 1      | 1.56%   |
| SK hynix HFS032G34MNC-2200A 32GB SSD         | 1         | 1      | 1.56%   |
| SK hynix BC711 HFM256GD3JX013N 256GB         | 1         | 1      | 1.56%   |
| Seagate ST9640423AS 640GB                    | 1         | 1      | 1.56%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.56%   |
| Seagate ST9320320AS 320GB                    | 1         | 1      | 1.56%   |
| Seagate ST9250410AS 250GB                    | 1         | 1      | 1.56%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 1.56%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 1.56%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 1.56%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 980 1TB              | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 870 EVO 1TB          | 1         | 1      | 1.56%   |
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 1.56%   |
| LITEON LCH-256V2S 256GB SSD                  | 1         | 1      | 1.56%   |
| Kingston SKC600512G 512GB SSD                | 1         | 3      | 1.56%   |
| Kingmax SSD 120GB                            | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 18     | 25%     |
| Seagate             | 10        | 10     | 15.63%  |
| HGST                | 9         | 10     | 14.06%  |
| Hitachi             | 6         | 7      | 9.38%   |
| Toshiba             | 5         | 5      | 7.81%   |
| Samsung Electronics | 3         | 3      | 4.69%   |
| Kingston            | 3         | 5      | 4.69%   |
| SK hynix            | 2         | 2      | 3.13%   |
| Unknown             | 1         | 1      | 1.56%   |
| Transcend           | 1         | 1      | 1.56%   |
| LITEON              | 1         | 1      | 1.56%   |
| Kingmax             | 1         | 1      | 1.56%   |
| KingFast            | 1         | 1      | 1.56%   |
| Intel               | 1         | 1      | 1.56%   |
| Fujitsu             | 1         | 1      | 1.56%   |
| CSD                 | 1         | 1      | 1.56%   |
| Crucial             | 1         | 1      | 1.56%   |
| China               | 1         | 1      | 1.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 15     | 28.89%  |
| Seagate | 10        | 10     | 22.22%  |
| HGST    | 9         | 10     | 20%     |
| Hitachi | 6         | 7      | 13.33%  |
| Toshiba | 5         | 5      | 11.11%  |
| Fujitsu | 1         | 1      | 2.22%   |
| CSD     | 1         | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 49     | 70.97%  |
| SSD  | 15        | 18     | 24.19%  |
| NVMe | 3         | 3      | 4.84%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 298       | 481    | 45.85%  |
| Works    | 293       | 489    | 45.08%  |
| Malfunc  | 58        | 70     | 8.92%   |
| Failed   | 1         | 1      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 418       | 54.08%  |
| Samsung Electronics            | 96        | 12.42%  |
| AMD                            | 65        | 8.41%   |
| SK hynix                       | 38        | 4.92%   |
| SanDisk                        | 36        | 4.66%   |
| Micron Technology              | 29        | 3.75%   |
| Kingston Technology Company    | 16        | 2.07%   |
| Toshiba America Info Systems   | 14        | 1.81%   |
| KIOXIA                         | 11        | 1.42%   |
| Phison Electronics             | 8         | 1.03%   |
| MAXIO Technology (Hangzhou)    | 7         | 0.91%   |
| Silicon Motion                 | 6         | 0.78%   |
| Solid State Storage Technology | 5         | 0.65%   |
| ASMedia Technology             | 4         | 0.52%   |
| Micron/Crucial Technology      | 3         | 0.39%   |
| Union Memory (Shenzhen)        | 2         | 0.26%   |
| Marvell Technology Group       | 2         | 0.26%   |
| Lite-On Technology             | 2         | 0.26%   |
| Lenovo                         | 2         | 0.26%   |
| ADATA Technology               | 2         | 0.26%   |
| Shenzhen Longsys Electronics   | 1         | 0.13%   |
| Realtek Semiconductor          | 1         | 0.13%   |
| OCZ Technology Group           | 1         | 0.13%   |
| O2 Micro                       | 1         | 0.13%   |
| LSI Logic / Symbios Logic      | 1         | 0.13%   |
| JMicron Technology             | 1         | 0.13%   |
| Broadcom / LSI                 | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 56        | 6.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 38        | 4.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 35        | 4.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 32        | 3.8%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 32        | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 27        | 3.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 19        | 2.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 18        | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 18        | 2.14%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 16        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16        | 1.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 16        | 1.9%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 15        | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 15        | 1.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 14        | 1.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 14        | 1.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 14        | 1.66%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 14        | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 12        | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12        | 1.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12        | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 1.31%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 11        | 1.31%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 11        | 1.31%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 10        | 1.19%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 1.19%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 9         | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 0.95%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 7         | 0.83%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 7         | 0.83%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 7         | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 0.83%   |
| Micron 3400 NVMe SSD [Hendrix]                                                          | 6         | 0.71%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 6         | 0.71%   |
| Intel Tiger Lake SATA AHCI Controller                                                   | 6         | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 418       | 54.57%  |
| NVMe | 268       | 34.99%  |
| RAID | 46        | 6.01%   |
| IDE  | 33        | 4.31%   |
| SAS  | 1         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 474       | 81.3%   |
| AMD    | 107       | 18.35%  |
| ARM    | 2         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 2.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 2.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 1.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 1.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 1.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 1.2%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 1.2%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 6         | 1.03%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 1.03%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 1.03%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 0.86%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.86%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.86%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.86%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.86%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 4         | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.68%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 4         | 0.68%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.68%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 0.68%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 0.68%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 4         | 0.68%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.51%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.51%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 0.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 174       | 29.85%  |
| Intel Core i7           | 97        | 16.64%  |
| Other                   | 59        | 10.12%  |
| Intel Core i3           | 59        | 10.12%  |
| AMD Ryzen 5             | 48        | 8.23%   |
| AMD Ryzen 7             | 32        | 5.49%   |
| Intel Celeron           | 21        | 3.6%    |
| Intel Xeon              | 18        | 3.09%   |
| Intel Core 2 Duo        | 15        | 2.57%   |
| Intel Atom              | 9         | 1.54%   |
| Intel Pentium           | 8         | 1.37%   |
| Intel Core i9           | 5         | 0.86%   |
| AMD Ryzen 9             | 5         | 0.86%   |
| AMD Ryzen 7 PRO         | 5         | 0.86%   |
| AMD Ryzen 3             | 5         | 0.86%   |
| Intel Genuine           | 3         | 0.51%   |
| Intel Xeon Silver       | 2         | 0.34%   |
| Intel Core M            | 2         | 0.34%   |
| AMD Ryzen 5 PRO         | 2         | 0.34%   |
| AMD Athlon              | 2         | 0.34%   |
| AMD A8                  | 2         | 0.34%   |
| AMD A10                 | 2         | 0.34%   |
| Intel Pentium Silver    | 1         | 0.17%   |
| Intel Pentium Gold      | 1         | 0.17%   |
| Intel Pentium Dual-Core | 1         | 0.17%   |
| Intel Pentium Dual      | 1         | 0.17%   |
| Intel Core 2 Quad       | 1         | 0.17%   |
| AMD Phenom II X4        | 1         | 0.17%   |
| AMD E                   | 1         | 0.17%   |
| AMD Athlon II X2        | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 214       | 36.64%  |
| 2       | 202       | 34.59%  |
| 6       | 80        | 13.7%   |
| 8       | 50        | 8.56%   |
| 12      | 10        | 1.71%   |
| 16      | 6         | 1.03%   |
| 14      | 6         | 1.03%   |
| 10      | 6         | 1.03%   |
| 24      | 3         | 0.51%   |
| 1       | 3         | 0.51%   |
| 36      | 1         | 0.17%   |
| 28      | 1         | 0.17%   |
| 11      | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 575       | 98.46%  |
| 2       | 7         | 1.2%    |
| 11      | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 462       | 78.97%  |
| 1       | 122       | 20.85%  |
| Unknown | 1         | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 576       | 98.63%  |
| Unknown        | 7         | 1.2%    |
| 64-bit         | 1         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 208       | 34.49%  |
| 0x306a9    | 36        | 5.97%   |
| 0x806ea    | 25        | 4.15%   |
| 0x206a7    | 22        | 3.65%   |
| 0x306c3    | 19        | 3.15%   |
| 0x906ea    | 17        | 2.82%   |
| 0x806ec    | 17        | 2.82%   |
| 0x40651    | 16        | 2.65%   |
| 0x806c1    | 15        | 2.49%   |
| 0x806e9    | 14        | 2.32%   |
| 0x306d4    | 14        | 2.32%   |
| 0x906e9    | 12        | 1.99%   |
| 0x1067a    | 11        | 1.82%   |
| 0x08600106 | 10        | 1.66%   |
| 0x506e3    | 9         | 1.49%   |
| 0x406e3    | 8         | 1.33%   |
| 0x08608103 | 8         | 1.33%   |
| 0x0a50000d | 7         | 1.16%   |
| 0x0a50000c | 7         | 1.16%   |
| 0xa0652    | 5         | 0.83%   |
| 0x906a3    | 5         | 0.83%   |
| 0x806d1    | 5         | 0.83%   |
| 0x6fd      | 5         | 0.83%   |
| 0x20655    | 5         | 0.83%   |
| 0x0a404102 | 5         | 0.83%   |
| 0xa0653    | 4         | 0.66%   |
| 0x906ed    | 4         | 0.66%   |
| 0x706e5    | 4         | 0.66%   |
| 0x706a1    | 4         | 0.66%   |
| 0x406c4    | 4         | 0.66%   |
| 0x08600104 | 4         | 0.66%   |
| 0x08108109 | 4         | 0.66%   |
| 0x08108102 | 4         | 0.66%   |
| 0x906eb    | 3         | 0.5%    |
| 0x906c0    | 3         | 0.5%    |
| 0x206d7    | 3         | 0.5%    |
| 0x0a201016 | 3         | 0.5%    |
| 0x08600103 | 3         | 0.5%    |
| 0x0810100b | 3         | 0.5%    |
| 0x90675    | 2         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 132       | 22.64%  |
| Haswell          | 58        | 9.95%   |
| IvyBridge        | 51        | 8.75%   |
| Unknown          | 42        | 7.2%    |
| Skylake          | 34        | 5.83%   |
| SandyBridge      | 31        | 5.32%   |
| Zen 2            | 27        | 4.63%   |
| Zen 3            | 26        | 4.46%   |
| TigerLake        | 24        | 4.12%   |
| Broadwell        | 24        | 4.12%   |
| CometLake        | 17        | 2.92%   |
| Alderlake Hybrid | 15        | 2.57%   |
| Zen+             | 14        | 2.4%    |
| Penryn           | 14        | 2.4%    |
| Icelake          | 12        | 2.06%   |
| Silvermont       | 11        | 1.89%   |
| Westmere         | 10        | 1.72%   |
| Goldmont plus    | 7         | 1.2%    |
| Core             | 7         | 1.2%    |
| Zen              | 6         | 1.03%   |
| Bonnell          | 5         | 0.86%   |
| Tremont          | 3         | 0.51%   |
| Steamroller      | 2         | 0.34%   |
| Nehalem          | 2         | 0.34%   |
| K10              | 2         | 0.34%   |
| Gracemont        | 2         | 0.34%   |
| Goldmont         | 2         | 0.34%   |
| Puma             | 1         | 0.17%   |
| Piledriver       | 1         | 0.17%   |
| Bobcat           | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 394       | 52.32%  |
| Nvidia                     | 221       | 29.35%  |
| AMD                        | 135       | 17.93%  |
| ASPEED Technology          | 2         | 0.27%   |
| Matrox Electronics Systems | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 4.32%   |
| Intel UHD Graphics 620                                                                   | 31        | 4.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 3.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 3.01%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 22        | 2.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.62%   |
| Intel HD Graphics 5500                                                                   | 16        | 2.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 16        | 2.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 1.83%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 14        | 1.83%   |
| Intel HD Graphics 620                                                                    | 14        | 1.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.57%   |
| Intel HD Graphics 630                                                                    | 12        | 1.57%   |
| Intel HD Graphics 530                                                                    | 12        | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.31%   |
| AMD Lucienne                                                                             | 10        | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 9         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.18%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.18%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 9         | 1.18%   |
| AMD Rembrandt [Radeon 680M]                                                              | 9         | 1.18%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.18%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 8         | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 254       | 43.42%  |
| Intel + Nvidia  | 114       | 19.49%  |
| 1 x AMD         | 81        | 13.85%  |
| 1 x Nvidia      | 76        | 12.99%  |
| AMD + Nvidia    | 27        | 4.62%   |
| Intel + AMD     | 23        | 3.93%   |
| 2 x AMD         | 4         | 0.68%   |
| Other           | 3         | 0.51%   |
| Nvidia + ASPEED | 2         | 0.34%   |
| 1 x Matrox      | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 428       | 72.3%   |
| Proprietary | 152       | 25.68%  |
| Unknown     | 12        | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 366       | 61.41%  |
| 1.01-2.0   | 67        | 11.24%  |
| 3.01-4.0   | 52        | 8.72%   |
| 0.01-0.5   | 40        | 6.71%   |
| 0.51-1.0   | 27        | 4.53%   |
| 7.01-8.0   | 14        | 2.35%   |
| 5.01-6.0   | 13        | 2.18%   |
| 8.01-16.0  | 13        | 2.18%   |
| 2.01-3.0   | 3         | 0.5%    |
| 16.01-24.0 | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 93        | 14.93%  |
| Chimei Innolux          | 75        | 12.04%  |
| AU Optronics            | 71        | 11.4%   |
| Samsung Electronics     | 64        | 10.27%  |
| Dell                    | 64        | 10.27%  |
| LG Display              | 55        | 8.83%   |
| Goldstar                | 29        | 4.65%   |
| PANDA                   | 16        | 2.57%   |
| Sharp                   | 15        | 2.41%   |
| ViewSonic               | 10        | 1.61%   |
| Apple                   | 10        | 1.61%   |
| AOC                     | 10        | 1.61%   |
| Hewlett-Packard         | 9         | 1.44%   |
| Lenovo                  | 8         | 1.28%   |
| ASUSTek Computer        | 8         | 1.28%   |
| Acer                    | 7         | 1.12%   |
| InfoVision              | 6         | 0.96%   |
| LGD                     | 5         | 0.8%    |
| Chi Mei Optoelectronics | 5         | 0.8%    |
| CSO                     | 4         | 0.64%   |
| Ancor Communications    | 4         | 0.64%   |
| Sony                    | 3         | 0.48%   |
| RTK                     | 3         | 0.48%   |
| Panasonic               | 3         | 0.48%   |
| Mi                      | 3         | 0.48%   |
| HKC                     | 3         | 0.48%   |
| BenQ                    | 3         | 0.48%   |
| Unknown                 | 3         | 0.48%   |
| TMX                     | 2         | 0.32%   |
| Philips                 | 2         | 0.32%   |
| MStar                   | 2         | 0.32%   |
| Gigabyte Technology     | 2         | 0.32%   |
| Fujitsu                 | 2         | 0.32%   |
| FPT                     | 2         | 0.32%   |
| XYM                     | 1         | 0.16%   |
| VSP                     | 1         | 0.16%   |
| VIE                     | 1         | 0.16%   |
| Valve                   | 1         | 0.16%   |
| Unknown (ADA)           | 1         | 0.16%   |
| TMK                     | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 8         | 1.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 8         | 1.27%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 6         | 0.95%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.95%   |
| LGD LCD Monitor 1920x1080                                             | 5         | 0.79%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.79%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 4         | 0.63%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.63%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 4         | 0.63%   |
| Dell SE198WFP DELF004 1440x900 410x260mm 19.1-inch                    | 4         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.63%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch   | 3         | 0.48%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 293x165mm 13.2-inch  | 3         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.48%   |
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                     | 3         | 0.48%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                | 3         | 0.48%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 3         | 0.48%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.48%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.48%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.48%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 3         | 0.48%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.48%   |
| AOC G2460PG AOC2460 1920x1080 531x299mm 24.0-inch                     | 3         | 0.48%   |
| Unknown                                                               | 3         | 0.48%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch      | 2         | 0.32%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 2         | 0.32%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 527x296mm 23.8-inch   | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch  | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.32%   |
| RTK 7911D RTK2A3B 720x1280 720x1280mm 57.8-inch                       | 2         | 0.32%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 2         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 306       | 51.6%   |
| 1366x768 (WXGA)   | 117       | 19.73%  |
| 2560x1440 (QHD)   | 30        | 5.06%   |
| 3840x2160 (4K)    | 28        | 4.72%   |
| 1600x900 (HD+)    | 18        | 3.04%   |
| 1920x1200 (WUXGA) | 12        | 2.02%   |
| 1280x1024 (SXGA)  | 12        | 2.02%   |
| 2880x1800         | 11        | 1.85%   |
| 2560x1600         | 11        | 1.85%   |
| 1440x900 (WXGA+)  | 10        | 1.69%   |
| 1280x800 (WXGA)   | 8         | 1.35%   |
| Unknown           | 5         | 0.84%   |
| 2160x1440         | 4         | 0.67%   |
| 2560x1080         | 3         | 0.51%   |
| 3440x1440         | 2         | 0.34%   |
| 3200x1800 (QHD+)  | 2         | 0.34%   |
| 1920x1280         | 2         | 0.34%   |
| 1360x768          | 2         | 0.34%   |
| 800x1280          | 1         | 0.17%   |
| 3840x2400         | 1         | 0.17%   |
| 3840x1080         | 1         | 0.17%   |
| 3456x2160         | 1         | 0.17%   |
| 3286x1080         | 1         | 0.17%   |
| 3200x2000         | 1         | 0.17%   |
| 3000x2000         | 1         | 0.17%   |
| 2736x1824         | 1         | 0.17%   |
| 1200x1920         | 1         | 0.17%   |
| 1024x600          | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 177       | 28.46%  |
| 14      | 89        | 14.31%  |
| 13      | 81        | 13.02%  |
| 21      | 39        | 6.27%   |
| 24      | 36        | 5.79%   |
| Unknown | 30        | 4.82%   |
| 27      | 29        | 4.66%   |
| 23      | 28        | 4.5%    |
| 17      | 18        | 2.89%   |
| 19      | 13        | 2.09%   |
| 18      | 13        | 2.09%   |
| 12      | 12        | 1.93%   |
| 31      | 9         | 1.45%   |
| 16      | 9         | 1.45%   |
| 20      | 8         | 1.29%   |
| 84      | 4         | 0.64%   |
| 34      | 4         | 0.64%   |
| 25      | 4         | 0.64%   |
| 11      | 4         | 0.64%   |
| 57      | 2         | 0.32%   |
| 54      | 2         | 0.32%   |
| 40      | 2         | 0.32%   |
| 7       | 2         | 0.32%   |
| 86      | 1         | 0.16%   |
| 72      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 43      | 1         | 0.16%   |
| 42      | 1         | 0.16%   |
| 28      | 1         | 0.16%   |
| 10      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 326       | 52.84%  |
| 501-600     | 92        | 14.91%  |
| 401-500     | 69        | 11.18%  |
| 201-300     | 49        | 7.94%   |
| Unknown     | 30        | 4.86%   |
| 351-400     | 18        | 2.92%   |
| 601-700     | 12        | 1.94%   |
| 701-800     | 6         | 0.97%   |
| 1501-2000   | 6         | 0.97%   |
| 1001-1500   | 3         | 0.49%   |
| 801-900     | 2         | 0.32%   |
| 901-1000    | 2         | 0.32%   |
| 101-200     | 1         | 0.16%   |
| 1-100       | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 449       | 80.04%  |
| 16/10   | 56        | 9.98%   |
| Unknown | 28        | 4.99%   |
| 5/4     | 10        | 1.78%   |
| 3/2     | 9         | 1.6%    |
| 21/9    | 5         | 0.89%   |
| 0.56    | 2         | 0.36%   |
| 0.67    | 1         | 0.18%   |
| 0.62    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 177       | 28.46%  |
| 81-90          | 146       | 23.47%  |
| 201-250        | 85        | 13.67%  |
| 151-200        | 31        | 4.98%   |
| Unknown        | 30        | 4.82%   |
| 301-350        | 29        | 4.66%   |
| 71-80          | 24        | 3.86%   |
| 141-150        | 19        | 3.05%   |
| 251-300        | 14        | 2.25%   |
| 351-500        | 13        | 2.09%   |
| More than 1000 | 11        | 1.77%   |
| 61-70          | 11        | 1.77%   |
| 121-130        | 10        | 1.61%   |
| 111-120        | 8         | 1.29%   |
| 51-60          | 4         | 0.64%   |
| 501-1000       | 4         | 0.64%   |
| 1-40           | 2         | 0.32%   |
| 91-100         | 2         | 0.32%   |
| 41-50          | 1         | 0.16%   |
| 131-140        | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 221       | 36.11%  |
| 101-120       | 148       | 24.18%  |
| 51-100        | 137       | 22.39%  |
| 161-240       | 48        | 7.84%   |
| Unknown       | 30        | 4.9%    |
| More than 240 | 20        | 3.27%   |
| 1-50          | 8         | 1.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 490       | 82.21%  |
| 2     | 74        | 12.42%  |
| 0     | 27        | 4.53%   |
| 3     | 5         | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 336       | 37.54%  |
| Intel                                  | 312       | 34.86%  |
| Qualcomm Atheros                       | 86        | 9.61%   |
| Broadcom                               | 39        | 4.36%   |
| MediaTek                               | 29        | 3.24%   |
| Broadcom Limited                       | 16        | 1.79%   |
| TP-Link                                | 11        | 1.23%   |
| Ralink Technology                      | 11        | 1.23%   |
| ASIX Electronics                       | 10        | 1.12%   |
| Samsung Electronics                    | 6         | 0.67%   |
| Marvell Technology Group               | 6         | 0.67%   |
| Xiaomi                                 | 5         | 0.56%   |
| Ralink                                 | 4         | 0.45%   |
| Hewlett-Packard                        | 3         | 0.34%   |
| D-Link                                 | 3         | 0.34%   |
| DisplayLink                            | 2         | 0.22%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |
| Sierra Wireless                        | 1         | 0.11%   |
| SEGGER                                 | 1         | 0.11%   |
| Qualcomm Atheros Communications        | 1         | 0.11%   |
| Qualcomm                               | 1         | 0.11%   |
| Novatel Wireless                       | 1         | 0.11%   |
| ICS Advent                             | 1         | 0.11%   |
| Huawei Technologies                    | 1         | 0.11%   |
| Foxconn / Hon Hai                      | 1         | 0.11%   |
| Ericsson Business Mobile Networks      | 1         | 0.11%   |
| Edimax Technology                      | 1         | 0.11%   |
| Dell                                   | 1         | 0.11%   |
| ASUSTek Computer                       | 1         | 0.11%   |
| Arduino SA                             | 1         | 0.11%   |
| Aquantia                               | 1         | 0.11%   |
| Unknown                                | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 238       | 22.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 37        | 3.56%   |
| Intel Wi-Fi 6 AX200                                                    | 27        | 2.6%    |
| Intel Wireless 8265 / 8275                                             | 24        | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 20        | 1.92%   |
| Intel Wireless 3165                                                    | 20        | 1.92%   |
| Intel Wi-Fi 6 AX201                                                    | 20        | 1.92%   |
| Intel Wireless 7265                                                    | 17        | 1.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 15        | 1.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 14        | 1.35%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 14        | 1.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 1.25%   |
| Intel Wireless 7260                                                    | 13        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 13        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 12        | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 12        | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                          | 12        | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 11        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 0.96%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 9         | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 0.87%   |
| Intel Wireless 8260                                                    | 9         | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                   | 9         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 9         | 0.87%   |
| Realtek Killer E2600 GbE Controller                                    | 8         | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 8         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 0.77%   |
| Intel Centrino Ultimate-N 6300                                         | 8         | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 7         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7         | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 7         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 0.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 6         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 253       | 50.1%   |
| Qualcomm Atheros                | 71        | 14.06%  |
| Realtek Semiconductor           | 68        | 13.47%  |
| Broadcom                        | 33        | 6.53%   |
| MediaTek                        | 28        | 5.54%   |
| Broadcom Limited                | 16        | 3.17%   |
| TP-Link                         | 11        | 2.18%   |
| Ralink Technology               | 11        | 2.18%   |
| Ralink                          | 4         | 0.79%   |
| D-Link                          | 3         | 0.59%   |
| Xiaomi                          | 1         | 0.2%    |
| Sierra Wireless                 | 1         | 0.2%    |
| Qualcomm Atheros Communications | 1         | 0.2%    |
| Marvell Technology Group        | 1         | 0.2%    |
| Edimax Technology               | 1         | 0.2%    |
| Dell                            | 1         | 0.2%    |
| ASUSTek Computer                | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 27        | 5.3%    |
| Intel Wireless 8265 / 8275                                     | 24        | 4.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 20        | 3.93%   |
| Intel Wireless 3165                                            | 20        | 3.93%   |
| Intel Wi-Fi 6 AX201                                            | 20        | 3.93%   |
| Intel Wireless 7265                                            | 17        | 3.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 2.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 14        | 2.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 14        | 2.75%   |
| Intel Wireless 7260                                            | 13        | 2.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 2.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 12        | 2.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 2.36%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 9         | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.77%   |
| Intel Wireless 8260                                            | 9         | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 8         | 1.57%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 1.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 1.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 1.18%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 1.18%   |
| Intel Wireless 3160                                            | 6         | 1.18%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 6         | 1.18%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 1.18%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 5         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 0.79%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 4         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 313       | 60.78%  |
| Intel                                  | 135       | 26.21%  |
| Qualcomm Atheros                       | 22        | 4.27%   |
| ASIX Electronics                       | 10        | 1.94%   |
| Broadcom                               | 8         | 1.55%   |
| Samsung Electronics                    | 6         | 1.17%   |
| Marvell Technology Group               | 5         | 0.97%   |
| Xiaomi                                 | 4         | 0.78%   |
| MediaTek                               | 2         | 0.39%   |
| Hewlett-Packard                        | 2         | 0.39%   |
| DisplayLink                            | 2         | 0.39%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.19%   |
| Qualcomm                               | 1         | 0.19%   |
| ICS Advent                             | 1         | 0.19%   |
| Huawei Technologies                    | 1         | 0.19%   |
| Foxconn / Hon Hai                      | 1         | 0.19%   |
| Aquantia                               | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 238       | 45.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 37        | 7.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 24        | 4.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 2.48%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 2.29%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 1.9%    |
| Intel Ethernet Connection (7) I219-V                                   | 9         | 1.71%   |
| Realtek Killer E2600 GbE Controller                                    | 8         | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 1.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 6         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 0.95%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 0.95%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.95%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.76%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.76%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 0.76%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.57%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.57%   |
| ASIX AX88772A Fast Ethernet                                            | 3         | 0.57%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 2         | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.38%   |
| MediaTek Infinix NOTE 30 VIP                                           | 2         | 0.38%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2         | 0.38%   |
| Intel Ethernet Connection X722 for 1GbE                                | 2         | 0.38%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.38%   |
| Intel Ethernet Connection (2) I218-LM                                  | 2         | 0.38%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 489       | 49.75%  |
| WiFi     | 488       | 49.64%  |
| Modem    | 5         | 0.51%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 408       | 67.66%  |
| Ethernet | 194       | 32.17%  |
| Modem    | 1         | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 352       | 60.07%  |
| 1     | 217       | 37.03%  |
| 3     | 12        | 2.05%   |
| 0     | 4         | 0.68%   |
| 4     | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 435       | 72.99%  |
| Yes  | 161       | 27.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 220       | 50.69%  |
| Realtek Semiconductor           | 40        | 9.22%   |
| Qualcomm Atheros Communications | 39        | 8.99%   |
| Broadcom                        | 25        | 5.76%   |
| IMC Networks                    | 24        | 5.53%   |
| Cambridge Silicon Radio         | 20        | 4.61%   |
| Lite-On Technology              | 17        | 3.92%   |
| Foxconn / Hon Hai               | 16        | 3.69%   |
| Apple                           | 11        | 2.53%   |
| Hewlett-Packard                 | 4         | 0.92%   |
| Dell                            | 4         | 0.92%   |
| Realtek                         | 3         | 0.69%   |
| MediaTek                        | 3         | 0.69%   |
| Ralink                          | 2         | 0.46%   |
| TP-Link                         | 1         | 0.23%   |
| Toshiba                         | 1         | 0.23%   |
| Opticis                         | 1         | 0.23%   |
| Marvell Semiconductor           | 1         | 0.23%   |
| Conwise Technology              | 1         | 0.23%   |
| Alps Electric                   | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 51        | 11.7%   |
| Intel AX201 Bluetooth                               | 50        | 11.47%  |
| Intel Bluetooth Device                              | 30        | 6.88%   |
| Realtek Bluetooth Radio                             | 29        | 6.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 6.42%   |
| Intel AX200 Bluetooth                               | 27        | 6.19%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 4.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 4.59%   |
| Intel AX210 Bluetooth                               | 14        | 3.21%   |
| IMC Networks Wireless_Device                        | 11        | 2.52%   |
| Intel AX211 Bluetooth                               | 9         | 2.06%   |
| Apple Bluetooth Host Controller                     | 8         | 1.83%   |
| IMC Networks Bluetooth Radio                        | 7         | 1.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 1.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 1.15%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.15%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.92%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.92%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.92%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.92%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.92%   |
| Realtek Bluetooth Radio                             | 3         | 0.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.69%   |
| MediaTek Wireless_Device                            | 3         | 0.69%   |
| Lite-On Bluetooth Radio                             | 3         | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.69%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.69%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 0.69%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.69%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.46%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 2         | 0.46%   |
| Lite-On Wireless_Device                             | 2         | 0.46%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 466       | 58.18%  |
| Nvidia                    | 157       | 19.6%   |
| AMD                       | 123       | 15.36%  |
| Generalplus Technology    | 9         | 1.12%   |
| C-Media Electronics       | 6         | 0.75%   |
| Logitech                  | 4         | 0.5%    |
| Realtek Semiconductor     | 3         | 0.37%   |
| JMTek                     | 3         | 0.37%   |
| Creative Labs             | 3         | 0.37%   |
| Audient                   | 3         | 0.37%   |
| Texas Instruments         | 2         | 0.25%   |
| FIFINE Microphones        | 2         | 0.25%   |
| ASUSTek Computer          | 2         | 0.25%   |
| Apple                     | 2         | 0.25%   |
| TX                        | 1         | 0.12%   |
| Shenzhen Rapoo Technology | 1         | 0.12%   |
| Plantronics               | 1         | 0.12%   |
| OPPO Electronics          | 1         | 0.12%   |
| Nordic Semiconductor ASA  | 1         | 0.12%   |
| Micro Star International  | 1         | 0.12%   |
| Kingston Technology       | 1         | 0.12%   |
| GYROCOM C&C               | 1         | 0.12%   |
| GN Netcom                 | 1         | 0.12%   |
| Elgato Systems            | 1         | 0.12%   |
| Creative Technology       | 1         | 0.12%   |
| Conexant Systems          | 1         | 0.12%   |
| BR25                      | 1         | 0.12%   |
| AudioQuest                | 1         | 0.12%   |
| AGPTek                    | 1         | 0.12%   |
| Unknown                   | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 78        | 8.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 61        | 6.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 44        | 4.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 44        | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 34        | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 33        | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 31        | 3.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 24        | 2.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 2.31%   |
| Intel Broadwell-U Audio Controller                                         | 21        | 2.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 2.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 20        | 2.1%    |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 2.1%    |
| Intel 8 Series HD Audio Controller                                         | 20        | 2.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 17        | 1.79%   |
| Nvidia Audio device                                                        | 15        | 1.58%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 1.58%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 15        | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                              | 12        | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12        | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 1.26%   |
| Intel Comet Lake PCH cAVS                                                  | 12        | 1.26%   |
| Intel CM238 HD Audio Controller                                            | 12        | 1.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 1.26%   |
| Intel 200 Series PCH HD Audio                                              | 12        | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 0.95%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 0.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 0.95%   |
| Generalplus Technology USB Audio Device                                    | 9         | 0.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9         | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 109       | 23.85%  |
| SK hynix                                | 82        | 17.94%  |
| Kingston                                | 79        | 17.29%  |
| Micron Technology                       | 60        | 13.13%  |
| G.Skill                                 | 25        | 5.47%   |
| Corsair                                 | 21        | 4.6%    |
| Unknown                                 | 16        | 3.5%    |
| Crucial                                 | 13        | 2.84%   |
| Ramaxel Technology                      | 9         | 1.97%   |
| A-DATA Technology                       | 9         | 1.97%   |
| Kingmax                                 | 8         | 1.75%   |
| Team                                    | 4         | 0.88%   |
| Elpida                                  | 4         | 0.88%   |
| Apacer                                  | 4         | 0.88%   |
| Kingmax Semiconductor                   | 2         | 0.44%   |
| Unknown                                 | 2         | 0.44%   |
| Unknown (ABCD)                          | 1         | 0.22%   |
| Unknown (7FE0)                          | 1         | 0.22%   |
| Silicon Power Computer & Communications | 1         | 0.22%   |
| PUSKILL                                 | 1         | 0.22%   |
| PNY                                     | 1         | 0.22%   |
| Patriot                                 | 1         | 0.22%   |
| Nanya Technology                        | 1         | 0.22%   |
| Lexar Co Limited                        | 1         | 0.22%   |
| AVEXIR                                  | 1         | 0.22%   |
| ASint Technology                        | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 7         | 1.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 6         | 1.2%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 1%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 5         | 1%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 5         | 1%      |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 5         | 1%      |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 5         | 1%      |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3066MT/s         | 5         | 1%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 0.8%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 4         | 0.8%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 4         | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4         | 0.8%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 4         | 0.8%    |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 3         | 0.6%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 3         | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 3         | 0.6%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 3         | 0.6%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 3         | 0.6%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 3         | 0.6%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 3         | 0.6%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 3         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 3         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 3         | 0.6%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s         | 3         | 0.6%    |
| Kingston RAM 9905700-122.A00G 16GB SODIMM DDR4 3200MT/s      | 3         | 0.6%    |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s        | 3         | 0.6%    |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 2         | 0.4%    |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s     | 2         | 0.4%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 2         | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.4%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s    | 2         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 216       | 58.54%  |
| DDR3    | 101       | 27.37%  |
| LPDDR4  | 14        | 3.79%   |
| DDR5    | 12        | 3.25%   |
| LPDDR3  | 9         | 2.44%   |
| LPDDR5  | 6         | 1.63%   |
| DDR2    | 5         | 1.36%   |
| DRAM    | 2         | 0.54%   |
| Unknown | 2         | 0.54%   |
| SDRAM   | 1         | 0.27%   |
| DDR     | 1         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 240       | 64.86%  |
| DIMM         | 96        | 25.95%  |
| Row Of Chips | 33        | 8.92%   |
| Unknown      | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 180       | 44.55%  |
| 4096  | 112       | 27.72%  |
| 16384 | 73        | 18.07%  |
| 2048  | 20        | 4.95%   |
| 32768 | 12        | 2.97%   |
| 1024  | 7         | 1.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 96        | 23.3%   |
| 1600    | 75        | 18.2%   |
| 2667    | 74        | 17.96%  |
| 2400    | 35        | 8.5%    |
| 1333    | 18        | 4.37%   |
| 2133    | 15        | 3.64%   |
| 1334    | 7         | 1.7%    |
| 4800    | 6         | 1.46%   |
| 4267    | 6         | 1.46%   |
| 1867    | 6         | 1.46%   |
| 6400    | 5         | 1.21%   |
| 3066    | 5         | 1.21%   |
| 5600    | 4         | 0.97%   |
| 3733    | 4         | 0.97%   |
| 3600    | 4         | 0.97%   |
| 3000    | 4         | 0.97%   |
| 800     | 4         | 0.97%   |
| 8400    | 3         | 0.73%   |
| 3666    | 3         | 0.73%   |
| 2933    | 3         | 0.73%   |
| 2666    | 3         | 0.73%   |
| 1067    | 3         | 0.73%   |
| 1066    | 3         | 0.73%   |
| 3466    | 2         | 0.49%   |
| 3400    | 2         | 0.49%   |
| 2800    | 2         | 0.49%   |
| 1866    | 2         | 0.49%   |
| 667     | 2         | 0.49%   |
| Unknown | 2         | 0.49%   |
| 7500    | 1         | 0.24%   |
| 7467    | 1         | 0.24%   |
| 5200    | 1         | 0.24%   |
| 4266    | 1         | 0.24%   |
| 4199    | 1         | 0.24%   |
| 3334    | 1         | 0.24%   |
| 3266    | 1         | 0.24%   |
| 3007    | 1         | 0.24%   |
| 2448    | 1         | 0.24%   |
| 1800    | 1         | 0.24%   |
| 1648    | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 28.57%  |
| Ricoh                 | 1         | 14.29%  |
| MIIIW                 | 1         | 14.29%  |
| Intermec Technologies | 1         | 14.29%  |
| Canon                 | 1         | 14.29%  |
| Brother Industries    | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Ricoh Printing Support     | 1         | 14.29%  |
| MIIIW MW Keyboard Air Mini | 1         | 14.29%  |
| Intermec PC43t             | 1         | 14.29%  |
| HP LaserJet P3010 Series   | 1         | 14.29%  |
| HP LaserJet P1102          | 1         | 14.29%  |
| Canon LBP6030w/6018w       | 1         | 14.29%  |
| Brother HL-L2360D series   | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 73        | 19.01%  |
| IMC Networks                           | 54        | 14.06%  |
| Microdia                               | 48        | 12.5%   |
| Realtek Semiconductor                  | 33        | 8.59%   |
| Sunplus Innovation Technology          | 31        | 8.07%   |
| Bison Electronics                      | 24        | 6.25%   |
| Quanta                                 | 20        | 5.21%   |
| Syntek                                 | 14        | 3.65%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.86%   |
| Luxvisions Innotech Limited            | 10        | 2.6%    |
| Logitech                               | 9         | 2.34%   |
| Apple                                  | 9         | 2.34%   |
| Lite-On Technology                     | 8         | 2.08%   |
| Suyin                                  | 7         | 1.82%   |
| Acer                                   | 5         | 1.3%    |
| Samsung Electronics                    | 4         | 1.04%   |
| Sonix Technology                       | 3         | 0.78%   |
| Ricoh                                  | 3         | 0.78%   |
| Alcor Micro                            | 3         | 0.78%   |
| Silicon Motion                         | 2         | 0.52%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.52%   |
| Denron                                 | 2         | 0.52%   |
| Lenovo                                 | 1         | 0.26%   |
| KYE Systems (Mouse Systems)            | 1         | 0.26%   |
| Intel                                  | 1         | 0.26%   |
| IDS Imaging Development Systems        | 1         | 0.26%   |
| Hewlett-Packard                        | 1         | 0.26%   |
| Aveo Technology                        | 1         | 0.26%   |
| Alpha Imaging Technology               | 1         | 0.26%   |
| ALi                                    | 1         | 0.26%   |
| 04004000_P040200_SN0002                | 1         | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 23        | 5.94%   |
| Chicony Integrated Camera                     | 23        | 5.94%   |
| IMC Networks USB2.0 HD UVC WebCam             | 19        | 4.91%   |
| Sunplus Integrated_Webcam_HD                  | 17        | 4.39%   |
| IMC Networks Integrated Camera                | 13        | 3.36%   |
| Realtek Integrated_Webcam_HD                  | 11        | 2.84%   |
| Syntek Integrated Camera                      | 10        | 2.58%   |
| Chicony HD Webcam                             | 8         | 2.07%   |
| Bison HD Webcam                               | 8         | 2.07%   |
| Microdia Laptop_Integrated_Webcam_HD          | 7         | 1.81%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 7         | 1.81%   |
| Chicony HP TrueVision HD Camera               | 6         | 1.55%   |
| Realtek Integrated Webcam                     | 5         | 1.29%   |
| Quanta HD User Facing                         | 5         | 1.29%   |
| Microdia Integrated Webcam                    | 5         | 1.29%   |
| Luxvisions Innotech Limited Integrated Camera | 5         | 1.29%   |
| Chicony HP HD Camera                          | 5         | 1.29%   |
| Bison SunplusIT Integrated Camera             | 5         | 1.29%   |
| Bison Integrated Camera                       | 5         | 1.29%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 5         | 1.29%   |
| Acer Integrated Camera                        | 5         | 1.29%   |
| Samsung Galaxy series, misc. (MTP mode)       | 4         | 1.03%   |
| Realtek USB Camera                            | 4         | 1.03%   |
| Realtek Integrated Webcam HD                  | 4         | 1.03%   |
| Quanta HP TrueVision HD Camera                | 4         | 1.03%   |
| Logitech Webcam C270                          | 4         | 1.03%   |
| Chicony HD User Facing                        | 4         | 1.03%   |
| Bison ThinkPad Integrated Camera              | 4         | 1.03%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 3         | 0.78%   |
| Quanta VGA WebCam                             | 3         | 0.78%   |
| Lite-On Integrated Camera                     | 3         | 0.78%   |
| IMC Networks VGA UVC WebCam                   | 3         | 0.78%   |
| IMC Networks USB2.0 UVC HD Webcam             | 3         | 0.78%   |
| Chicony Integrated HP HD Webcam               | 3         | 0.78%   |
| Chicony HP HD Webcam                          | 3         | 0.78%   |
| Syntek Lenovo EasyCamera                      | 2         | 0.52%   |
| Suyin Laptop_Integrated_Webcam_HD             | 2         | 0.52%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 2         | 0.52%   |
| Sunplus Asus Webcam                           | 2         | 0.52%   |
| Sonix USB2.0 HD UVC WebCam                    | 2         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 36        | 44.44%  |
| Synaptics                  | 18        | 22.22%  |
| Shenzhen Goodix Technology | 18        | 22.22%  |
| Samsung Electronics        | 3         | 3.7%    |
| LighTuning Technology      | 2         | 2.47%   |
| Elan Microelectronics      | 2         | 2.47%   |
| Upek                       | 1         | 1.23%   |
| STMicroelectronics         | 1         | 1.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 13        | 16.05%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 8.64%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 8.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 7.41%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 6.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 4.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 4.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 4.94%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 3.7%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 3.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.47%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.47%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.47%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.23%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.23%   |
| Synaptics UWP WBDI                                                         | 1         | 1.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.23%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.23%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.23%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 17        | 77.27%  |
| Alcor Micro | 3         | 13.64%  |
| Upek        | 1         | 4.55%   |
| Lenovo      | 1         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 31.82%  |
| Broadcom 5880                                                                | 6         | 27.27%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 13.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 9.09%   |
| Broadcom 58200                                                               | 2         | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.55%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 402       | 67.34%  |
| 1     | 162       | 27.14%  |
| 2     | 26        | 4.36%   |
| 3     | 4         | 0.67%   |
| 4     | 2         | 0.34%   |
| 5     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 79        | 34.65%  |
| Graphics card            | 46        | 20.18%  |
| Net/wireless             | 21        | 9.21%   |
| Chipcard                 | 21        | 9.21%   |
| Multimedia controller    | 15        | 6.58%   |
| Communication controller | 11        | 4.82%   |
| Camera                   | 11        | 4.82%   |
| Unassigned class         | 8         | 3.51%   |
| Bluetooth                | 6         | 2.63%   |
| Net/ethernet             | 5         | 2.19%   |
| Storage                  | 2         | 0.88%   |
| Card reader              | 2         | 0.88%   |
| Sound                    | 1         | 0.44%   |

