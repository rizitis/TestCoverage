Ubuntu Unity - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu Unity.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Unity/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Unity/Notebook/README.md).

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

Total: 1695

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ECS           | MCP61M-M3                   | Desktop     | [4a66244a0d](https://linux-hardware.org/?probe=4a66244a0d) | May 08, 2024 |
| Dell          | Inspiron N7010              | Notebook    | [538f6e2c91](https://linux-hardware.org/?probe=538f6e2c91) | May 06, 2024 |
| Dell          | Precision 5530              | Notebook    | [373556c210](https://linux-hardware.org/?probe=373556c210) | May 02, 2024 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [e442e79602](https://linux-hardware.org/?probe=e442e79602) | Apr 30, 2024 |
| ASUSTek       | ET2031I                     | Notebook    | [d27647c450](https://linux-hardware.org/?probe=d27647c450) | Apr 29, 2024 |
| HP            | ProBook 4510s               | Notebook    | [8de734fc37](https://linux-hardware.org/?probe=8de734fc37) | Apr 28, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [ef90289a1a](https://linux-hardware.org/?probe=ef90289a1a) | Apr 17, 2024 |
| Gigabyte      | AORUS 16X ASG               | Notebook    | [58a22b5fcc](https://linux-hardware.org/?probe=58a22b5fcc) | Apr 16, 2024 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [a00d0bb1b4](https://linux-hardware.org/?probe=a00d0bb1b4) | Apr 16, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [2cf9b070a4](https://linux-hardware.org/?probe=2cf9b070a4) | Apr 15, 2024 |
| Unknown       | Unknown                     | Soc         | [127faa9050](https://linux-hardware.org/?probe=127faa9050) | Apr 02, 2024 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [25d9669839](https://linux-hardware.org/?probe=25d9669839) | Mar 25, 2024 |
| Medion        | WIM2170                     | Notebook    | [190b555e0c](https://linux-hardware.org/?probe=190b555e0c) | Mar 23, 2024 |
| Dell          | 0PRR48 A01                  | Desktop     | [7c69b5e082](https://linux-hardware.org/?probe=7c69b5e082) | Mar 20, 2024 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [597b022119](https://linux-hardware.org/?probe=597b022119) | Feb 29, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d17f61dd3a](https://linux-hardware.org/?probe=d17f61dd3a) | Feb 24, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e990417791](https://linux-hardware.org/?probe=e990417791) | Feb 24, 2024 |
| Intel         | H61                         | Desktop     | [fc2cf214b0](https://linux-hardware.org/?probe=fc2cf214b0) | Feb 20, 2024 |
| Lenovo        | ThinkPad T520 42406BG       | Notebook    | [c2f80860e5](https://linux-hardware.org/?probe=c2f80860e5) | Feb 15, 2024 |
| Lenovo        | ThinkStation D30 4223AU4    | Desktop     | [bd10aa2839](https://linux-hardware.org/?probe=bd10aa2839) | Feb 13, 2024 |
| Exo           | Smart T                     | Notebook    | [6691435d42](https://linux-hardware.org/?probe=6691435d42) | Feb 10, 2024 |
| Samsung       | 730QED                      | Convertible | [eb61c8edf0](https://linux-hardware.org/?probe=eb61c8edf0) | Feb 07, 2024 |
| Positivo      | Q4128C-S                    | Notebook    | [8c01f80e79](https://linux-hardware.org/?probe=8c01f80e79) | Feb 06, 2024 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [78586dd263](https://linux-hardware.org/?probe=78586dd263) | Feb 06, 2024 |
| Dell          | Latitude D620               | Notebook    | [c0f28567a4](https://linux-hardware.org/?probe=c0f28567a4) | Jan 31, 2024 |
| ASRock        | X370 Professional Gaming    | Desktop     | [ddff1295a4](https://linux-hardware.org/?probe=ddff1295a4) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [1adb0efb30](https://linux-hardware.org/?probe=1adb0efb30) | Jan 27, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [040dbb275e](https://linux-hardware.org/?probe=040dbb275e) | Jan 26, 2024 |
| Gigabyte      | Z68X-UD4-B3                 | Desktop     | [e114381673](https://linux-hardware.org/?probe=e114381673) | Jan 25, 2024 |
| HP            | 3048h                       | Desktop     | [ed2d54328f](https://linux-hardware.org/?probe=ed2d54328f) | Jan 25, 2024 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [ed95c81dcc](https://linux-hardware.org/?probe=ed95c81dcc) | Jan 19, 2024 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [911ffd60a5](https://linux-hardware.org/?probe=911ffd60a5) | Jan 04, 2024 |
| Dell          | Latitude 5480               | Notebook    | [cf678e4c6d](https://linux-hardware.org/?probe=cf678e4c6d) | Dec 31, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a1bc8df9e4](https://linux-hardware.org/?probe=a1bc8df9e4) | Dec 30, 2023 |
| Lenovo        | ThinkPad T450 20BUS2VK00    | Notebook    | [15de64acfb](https://linux-hardware.org/?probe=15de64acfb) | Dec 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [b1342e1524](https://linux-hardware.org/?probe=b1342e1524) | Dec 23, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [d67a62b447](https://linux-hardware.org/?probe=d67a62b447) | Dec 21, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [b847e03f71](https://linux-hardware.org/?probe=b847e03f71) | Dec 21, 2023 |
| System76      | Adder WS                    | Notebook    | [d272c23e51](https://linux-hardware.org/?probe=d272c23e51) | Dec 21, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [2b49349cf8](https://linux-hardware.org/?probe=2b49349cf8) | Dec 19, 2023 |
| Toshiba       | NB505                       | Notebook    | [7aa351f4c3](https://linux-hardware.org/?probe=7aa351f4c3) | Dec 19, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [808c135dea](https://linux-hardware.org/?probe=808c135dea) | Dec 19, 2023 |
| Toshiba       | NB505                       | Notebook    | [9ed9ded2ea](https://linux-hardware.org/?probe=9ed9ded2ea) | Dec 19, 2023 |
| Apple         | Mac-F42787C8 PVT            | All in one  | [ef50f10d1f](https://linux-hardware.org/?probe=ef50f10d1f) | Dec 17, 2023 |
| HP            | Pavilion 15                 | Notebook    | [8041cb2da6](https://linux-hardware.org/?probe=8041cb2da6) | Dec 09, 2023 |
| Gigabyte      | 970A-DS3                    | Desktop     | [cad7bc7542](https://linux-hardware.org/?probe=cad7bc7542) | Dec 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [69fcc32b2c](https://linux-hardware.org/?probe=69fcc32b2c) | Dec 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [3919c76efa](https://linux-hardware.org/?probe=3919c76efa) | Dec 04, 2023 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [5ab684ace6](https://linux-hardware.org/?probe=5ab684ace6) | Nov 27, 2023 |
| Intel         | NUC6i3SYB H81132-502        | Mini pc     | [0238e68d82](https://linux-hardware.org/?probe=0238e68d82) | Nov 26, 2023 |
| Toshiba       | NB205                       | Notebook    | [a3f0bef4d4](https://linux-hardware.org/?probe=a3f0bef4d4) | Nov 15, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [527e45b73b](https://linux-hardware.org/?probe=527e45b73b) | Nov 15, 2023 |
| HP            | ZHAN 66 Pro G2 Notebook ... | Notebook    | [f93402c5f5](https://linux-hardware.org/?probe=f93402c5f5) | Nov 14, 2023 |
| ECS           | H81H3-M7                    | Desktop     | [d2afbe33c7](https://linux-hardware.org/?probe=d2afbe33c7) | Nov 09, 2023 |
| ECS           | H81H3-M7                    | Desktop     | [e5ea8b4820](https://linux-hardware.org/?probe=e5ea8b4820) | Nov 09, 2023 |
| HONOR         | GLO-GXXX                    | Notebook    | [a1519ee799](https://linux-hardware.org/?probe=a1519ee799) | Nov 09, 2023 |
| Dell          | Precision 3551              | Notebook    | [da2f2a5993](https://linux-hardware.org/?probe=da2f2a5993) | Nov 08, 2023 |
| ASUSTek       | GL702VMK                    | Notebook    | [4cb218a4f4](https://linux-hardware.org/?probe=4cb218a4f4) | Nov 08, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c2a37daf7d](https://linux-hardware.org/?probe=c2a37daf7d) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [1d56b84bdd](https://linux-hardware.org/?probe=1d56b84bdd) | Nov 05, 2023 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [71fd69724b](https://linux-hardware.org/?probe=71fd69724b) | Nov 03, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [0eba32de41](https://linux-hardware.org/?probe=0eba32de41) | Nov 01, 2023 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [bf7045fe69](https://linux-hardware.org/?probe=bf7045fe69) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [4bd69e46d1](https://linux-hardware.org/?probe=4bd69e46d1) | Oct 30, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6232ddb7f2](https://linux-hardware.org/?probe=6232ddb7f2) | Oct 28, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [6e2384b7ee](https://linux-hardware.org/?probe=6e2384b7ee) | Oct 27, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [bea4c3f8b4](https://linux-hardware.org/?probe=bea4c3f8b4) | Oct 26, 2023 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [0cbd6a255a](https://linux-hardware.org/?probe=0cbd6a255a) | Oct 25, 2023 |
| Dell          | Inspiron 6000               | Notebook    | [5ba1518578](https://linux-hardware.org/?probe=5ba1518578) | Oct 22, 2023 |
| Unknown       | SpringdalePE                | Desktop     | [e29427ba94](https://linux-hardware.org/?probe=e29427ba94) | Oct 10, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [358f4a0030](https://linux-hardware.org/?probe=358f4a0030) | Oct 08, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [887c13dff8](https://linux-hardware.org/?probe=887c13dff8) | Oct 06, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [5bd11bbd69](https://linux-hardware.org/?probe=5bd11bbd69) | Oct 06, 2023 |
| Notebook      | N150ZU                      | Notebook    | [cbaeef6994](https://linux-hardware.org/?probe=cbaeef6994) | Oct 05, 2023 |
| Notebook      | N150ZU                      | Notebook    | [3a555e095f](https://linux-hardware.org/?probe=3a555e095f) | Oct 05, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [48afb4262c](https://linux-hardware.org/?probe=48afb4262c) | Oct 04, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [eb48f40a27](https://linux-hardware.org/?probe=eb48f40a27) | Sep 29, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [451784974b](https://linux-hardware.org/?probe=451784974b) | Sep 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [11777b411d](https://linux-hardware.org/?probe=11777b411d) | Sep 20, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6861d58ee0](https://linux-hardware.org/?probe=6861d58ee0) | Sep 20, 2023 |
| Lenovo        | ThinkPad T460 20FN002VUS    | Notebook    | [46c6a66e5b](https://linux-hardware.org/?probe=46c6a66e5b) | Sep 19, 2023 |
| Toshiba       | Intel H81/Q87 PCH 32        | All in one  | [43275b430f](https://linux-hardware.org/?probe=43275b430f) | Sep 14, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [8d0117a5f3](https://linux-hardware.org/?probe=8d0117a5f3) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ecc13f9294](https://linux-hardware.org/?probe=ecc13f9294) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e1b135961f](https://linux-hardware.org/?probe=e1b135961f) | Sep 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [f08f8e5ce8](https://linux-hardware.org/?probe=f08f8e5ce8) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [fd7e472e9b](https://linux-hardware.org/?probe=fd7e472e9b) | Sep 07, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [d630819b59](https://linux-hardware.org/?probe=d630819b59) | Sep 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [6c5351c835](https://linux-hardware.org/?probe=6c5351c835) | Sep 01, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [04492867e2](https://linux-hardware.org/?probe=04492867e2) | Aug 31, 2023 |
| HP            | 8592                        | Desktop     | [667f4402e7](https://linux-hardware.org/?probe=667f4402e7) | Aug 31, 2023 |
| ASUSTek       | X553SA                      | Notebook    | [ca9ccf934d](https://linux-hardware.org/?probe=ca9ccf934d) | Aug 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [38fbd02f14](https://linux-hardware.org/?probe=38fbd02f14) | Aug 23, 2023 |
| Dell          | Inspiron 1200               | Notebook    | [2340dcab47](https://linux-hardware.org/?probe=2340dcab47) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [a3982248d3](https://linux-hardware.org/?probe=a3982248d3) | Aug 13, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [977c66cbc0](https://linux-hardware.org/?probe=977c66cbc0) | Aug 12, 2023 |
| Dell          | Latitude D630               | Notebook    | [a57bb7cde1](https://linux-hardware.org/?probe=a57bb7cde1) | Aug 08, 2023 |
| Acer          | Aspire 1825PTZ              | Notebook    | [553d2539fa](https://linux-hardware.org/?probe=553d2539fa) | Aug 07, 2023 |
| System76      | Thelio Major                | Desktop     | [eeea316849](https://linux-hardware.org/?probe=eeea316849) | Aug 04, 2023 |
| Dell          | G5 5587                     | Notebook    | [320fffbb49](https://linux-hardware.org/?probe=320fffbb49) | Aug 04, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [6ffb3ac7e7](https://linux-hardware.org/?probe=6ffb3ac7e7) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [e6d6527380](https://linux-hardware.org/?probe=e6d6527380) | Aug 01, 2023 |
| Panasonic     | CF-20-1                     | Notebook    | [0b59968d03](https://linux-hardware.org/?probe=0b59968d03) | Jul 29, 2023 |
| OEM           | Unknown                     | Notebook    | [d0d59fb363](https://linux-hardware.org/?probe=d0d59fb363) | Jul 24, 2023 |
| ASUSTek       | A_F_K20BF                   | Desktop     | [f2ae40130e](https://linux-hardware.org/?probe=f2ae40130e) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [f81b2bedb9](https://linux-hardware.org/?probe=f81b2bedb9) | Jul 18, 2023 |
| Dell          | 0C2425 A00                  | Desktop     | [130edcd2b5](https://linux-hardware.org/?probe=130edcd2b5) | Jul 06, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [157d424ec0](https://linux-hardware.org/?probe=157d424ec0) | Jun 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [46ae665800](https://linux-hardware.org/?probe=46ae665800) | Jun 18, 2023 |
| HP            | Pavilion 17                 | Notebook    | [f0e1e5aae8](https://linux-hardware.org/?probe=f0e1e5aae8) | Jun 18, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [8c47ad5e92](https://linux-hardware.org/?probe=8c47ad5e92) | Jun 16, 2023 |
| Dell          | 06NWYK A01                  | Desktop     | [c731dec189](https://linux-hardware.org/?probe=c731dec189) | Jun 14, 2023 |
| DJI           | MANIFOLD 2-C                | Desktop     | [44edfc848e](https://linux-hardware.org/?probe=44edfc848e) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [68af03eefe](https://linux-hardware.org/?probe=68af03eefe) | Jun 10, 2023 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [7411937d5b](https://linux-hardware.org/?probe=7411937d5b) | Jun 09, 2023 |
| Dell          | G15 5511                    | Notebook    | [ddee46cbfa](https://linux-hardware.org/?probe=ddee46cbfa) | Jun 07, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [5e1bb16065](https://linux-hardware.org/?probe=5e1bb16065) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [3067e6332a](https://linux-hardware.org/?probe=3067e6332a) | Jun 02, 2023 |
| HP            | 802E                        | Desktop     | [1837c96bfd](https://linux-hardware.org/?probe=1837c96bfd) | Jun 02, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [544fc521be](https://linux-hardware.org/?probe=544fc521be) | May 30, 2023 |
| Nvidia        | Tegra                       | Soc         | [06b49744e2](https://linux-hardware.org/?probe=06b49744e2) | May 28, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [ccc5d73179](https://linux-hardware.org/?probe=ccc5d73179) | May 28, 2023 |
| Intel         | X58M                        | Desktop     | [912addab98](https://linux-hardware.org/?probe=912addab98) | May 27, 2023 |
| Biostar       | N61PB-M2S                   | Desktop     | [e4669affdb](https://linux-hardware.org/?probe=e4669affdb) | May 24, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [00b64b43b5](https://linux-hardware.org/?probe=00b64b43b5) | May 22, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [ebe8b24fd2](https://linux-hardware.org/?probe=ebe8b24fd2) | May 20, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [bb5b5bd73c](https://linux-hardware.org/?probe=bb5b5bd73c) | May 19, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [af1e17cc95](https://linux-hardware.org/?probe=af1e17cc95) | May 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [e77f91338e](https://linux-hardware.org/?probe=e77f91338e) | May 16, 2023 |
| Samsung       | 950XED                      | Notebook    | [8d4e3bcb94](https://linux-hardware.org/?probe=8d4e3bcb94) | May 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [100534a570](https://linux-hardware.org/?probe=100534a570) | May 08, 2023 |
| Unknown       | AG958                       | Notebook    | [70aa4b6cf2](https://linux-hardware.org/?probe=70aa4b6cf2) | May 08, 2023 |
| Toshiba       | TECRA A11                   | Notebook    | [456421ff37](https://linux-hardware.org/?probe=456421ff37) | May 07, 2023 |
| Acer          | Aspire 7530G                | Notebook    | [5c19c9f6e4](https://linux-hardware.org/?probe=5c19c9f6e4) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [2016e42226](https://linux-hardware.org/?probe=2016e42226) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [d8256a8177](https://linux-hardware.org/?probe=d8256a8177) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [d4019e13f1](https://linux-hardware.org/?probe=d4019e13f1) | May 03, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | Notebook    | [4a6eed684e](https://linux-hardware.org/?probe=4a6eed684e) | Apr 26, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9425800303](https://linux-hardware.org/?probe=9425800303) | Apr 25, 2023 |
| ASUSTek       | X45C                        | Notebook    | [759ed58d76](https://linux-hardware.org/?probe=759ed58d76) | Apr 23, 2023 |
| ELSKY         | M219F-6C                    | Desktop     | [5f41223856](https://linux-hardware.org/?probe=5f41223856) | Apr 21, 2023 |
| ASUSTek       | P4C800-E                    | Desktop     | [4521f2b9b4](https://linux-hardware.org/?probe=4521f2b9b4) | Apr 17, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [9a85729d53](https://linux-hardware.org/?probe=9a85729d53) | Apr 12, 2023 |
| HP            | 3396                        | Desktop     | [25eac72561](https://linux-hardware.org/?probe=25eac72561) | Apr 12, 2023 |
| HP            | 1497                        | Desktop     | [94c6f8a63a](https://linux-hardware.org/?probe=94c6f8a63a) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [85a8b8b452](https://linux-hardware.org/?probe=85a8b8b452) | Mar 26, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [8e9a11831c](https://linux-hardware.org/?probe=8e9a11831c) | Mar 24, 2023 |
| Alienware     | m17 R3                      | Notebook    | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d45d6dce3b](https://linux-hardware.org/?probe=d45d6dce3b) | Mar 15, 2023 |
| Lenovo        | 313A SDK0L77767 WIN 3423... | Desktop     | [869582f7a7](https://linux-hardware.org/?probe=869582f7a7) | Mar 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [daf758d941](https://linux-hardware.org/?probe=daf758d941) | Mar 08, 2023 |
| Dell          | Latitude 7480               | Notebook    | [c4e5e8923c](https://linux-hardware.org/?probe=c4e5e8923c) | Mar 05, 2023 |
| DIEBOLD       | H55H-CM                     | Desktop     | [fadb939dd7](https://linux-hardware.org/?probe=fadb939dd7) | Mar 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [f9213f29ca](https://linux-hardware.org/?probe=f9213f29ca) | Mar 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [e1733fa8c9](https://linux-hardware.org/?probe=e1733fa8c9) | Mar 01, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8fb68b4ad6](https://linux-hardware.org/?probe=8fb68b4ad6) | Feb 26, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [d205de771a](https://linux-hardware.org/?probe=d205de771a) | Feb 26, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [b57e519074](https://linux-hardware.org/?probe=b57e519074) | Feb 25, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [bf3c4ff51d](https://linux-hardware.org/?probe=bf3c4ff51d) | Feb 25, 2023 |
| Nvidia        | Tegra                       | Soc         | [5a0d032110](https://linux-hardware.org/?probe=5a0d032110) | Feb 23, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [a28282663a](https://linux-hardware.org/?probe=a28282663a) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [524153d219](https://linux-hardware.org/?probe=524153d219) | Feb 22, 2023 |
| Dell          | Latitude 7330               | Notebook    | [caf4a2b3ac](https://linux-hardware.org/?probe=caf4a2b3ac) | Feb 16, 2023 |
| HP            | 1497                        | Desktop     | [b27560d384](https://linux-hardware.org/?probe=b27560d384) | Feb 14, 2023 |
| HP            | Mini 210-1000               | Notebook    | [a97b152ab2](https://linux-hardware.org/?probe=a97b152ab2) | Feb 09, 2023 |
| HP            | Mini 210-1000               | Notebook    | [1546202e50](https://linux-hardware.org/?probe=1546202e50) | Feb 08, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [cc92542e21](https://linux-hardware.org/?probe=cc92542e21) | Feb 08, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [190d8c3b40](https://linux-hardware.org/?probe=190d8c3b40) | Feb 08, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [04f7bc268b](https://linux-hardware.org/?probe=04f7bc268b) | Feb 07, 2023 |
| ASUSTek       | 1101HA                      | Notebook    | [28cb433eb0](https://linux-hardware.org/?probe=28cb433eb0) | Feb 03, 2023 |
| AZW           | S5 V1.0                     | Mini pc     | [213d0d1a6a](https://linux-hardware.org/?probe=213d0d1a6a) | Feb 01, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [d84840d5c9](https://linux-hardware.org/?probe=d84840d5c9) | Jan 29, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| ASRock        | Z97 Extreme6                | Desktop     | [4ffae2148d](https://linux-hardware.org/?probe=4ffae2148d) | Jan 26, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [f75ac14e70](https://linux-hardware.org/?probe=f75ac14e70) | Jan 23, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [7189416b97](https://linux-hardware.org/?probe=7189416b97) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | Notebook    | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [c2dd87db86](https://linux-hardware.org/?probe=c2dd87db86) | Jan 17, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [674f3e9cae](https://linux-hardware.org/?probe=674f3e9cae) | Jan 17, 2023 |
| Acer          | Aspire V5-122P              | Notebook    | [c5d70f195f](https://linux-hardware.org/?probe=c5d70f195f) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4d89e9dec4](https://linux-hardware.org/?probe=4d89e9dec4) | Jan 14, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [6a129c6fde](https://linux-hardware.org/?probe=6a129c6fde) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [1318c97f67](https://linux-hardware.org/?probe=1318c97f67) | Jan 13, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [79cb54f05f](https://linux-hardware.org/?probe=79cb54f05f) | Jan 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b9eb9f78d2](https://linux-hardware.org/?probe=b9eb9f78d2) | Jan 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [182a43f2b4](https://linux-hardware.org/?probe=182a43f2b4) | Jan 08, 2023 |
| HP            | 3397                        | Desktop     | [ef794d730d](https://linux-hardware.org/?probe=ef794d730d) | Jan 05, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fd8b340292](https://linux-hardware.org/?probe=fd8b340292) | Jan 05, 2023 |
| Dell          | 0MTFWP A00                  | Desktop     | [1bec4602bb](https://linux-hardware.org/?probe=1bec4602bb) | Jan 05, 2023 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [f9833c6d79](https://linux-hardware.org/?probe=f9833c6d79) | Jan 03, 2023 |
| Dell          | 0P99M4 A01                  | Desktop     | [0b6a911c16](https://linux-hardware.org/?probe=0b6a911c16) | Jan 03, 2023 |
| ASUSTek       | G71GX                       | Notebook    | [7650c66520](https://linux-hardware.org/?probe=7650c66520) | Jan 01, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [def123de2d](https://linux-hardware.org/?probe=def123de2d) | Dec 31, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [6d0b6881ac](https://linux-hardware.org/?probe=6d0b6881ac) | Dec 30, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [33c4b80d0a](https://linux-hardware.org/?probe=33c4b80d0a) | Dec 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [ef194165fc](https://linux-hardware.org/?probe=ef194165fc) | Dec 24, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| Acer          | ERC410M                     | Desktop     | [e25233896a](https://linux-hardware.org/?probe=e25233896a) | Dec 21, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [7fe5232b14](https://linux-hardware.org/?probe=7fe5232b14) | Dec 20, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [0f360efa8f](https://linux-hardware.org/?probe=0f360efa8f) | Dec 20, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Irbis         | NB264                       | Notebook    | [4bb5935a41](https://linux-hardware.org/?probe=4bb5935a41) | Dec 19, 2022 |
| Irbis         | NB264                       | Notebook    | [1209e6c899](https://linux-hardware.org/?probe=1209e6c899) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [a5f6a25d72](https://linux-hardware.org/?probe=a5f6a25d72) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [2b955ca3b3](https://linux-hardware.org/?probe=2b955ca3b3) | Dec 19, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| Dell          | 0MTFWP A00                  | Desktop     | [b701f65ffc](https://linux-hardware.org/?probe=b701f65ffc) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [00c328990f](https://linux-hardware.org/?probe=00c328990f) | Dec 16, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [3d5598a5eb](https://linux-hardware.org/?probe=3d5598a5eb) | Dec 16, 2022 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [02067db7ad](https://linux-hardware.org/?probe=02067db7ad) | Dec 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Sony          | VGN-NS220TH                 | Notebook    | [29e1373be4](https://linux-hardware.org/?probe=29e1373be4) | Dec 11, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [50ccab1267](https://linux-hardware.org/?probe=50ccab1267) | Dec 10, 2022 |
| Dell          | 0593VH A00                  | Desktop     | [1cbf8ccc4a](https://linux-hardware.org/?probe=1cbf8ccc4a) | Dec 07, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [6c6d0525fc](https://linux-hardware.org/?probe=6c6d0525fc) | Dec 01, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [9f1ad78301](https://linux-hardware.org/?probe=9f1ad78301) | Nov 29, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [4aba048a46](https://linux-hardware.org/?probe=4aba048a46) | Nov 28, 2022 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [2042d30c8b](https://linux-hardware.org/?probe=2042d30c8b) | Nov 28, 2022 |
| ASUSTek       | 1225B                       | Notebook    | [87f1b143de](https://linux-hardware.org/?probe=87f1b143de) | Nov 27, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [f0e76c8866](https://linux-hardware.org/?probe=f0e76c8866) | Nov 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QTS0... | Notebook    | [37d3dc95f1](https://linux-hardware.org/?probe=37d3dc95f1) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [97ede0876f](https://linux-hardware.org/?probe=97ede0876f) | Nov 25, 2022 |
| Nvidia        | Tegra                       | Soc         | [770c4e4092](https://linux-hardware.org/?probe=770c4e4092) | Nov 21, 2022 |
| Acer          | E946GZ                      | Desktop     | [f084e099d5](https://linux-hardware.org/?probe=f084e099d5) | Nov 17, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [b7ff70b9b2](https://linux-hardware.org/?probe=b7ff70b9b2) | Nov 14, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f6bfbc00ba](https://linux-hardware.org/?probe=f6bfbc00ba) | Nov 14, 2022 |
| HP            | ZBook 14                    | Notebook    | [27b57aad86](https://linux-hardware.org/?probe=27b57aad86) | Nov 12, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [227f62cdb9](https://linux-hardware.org/?probe=227f62cdb9) | Nov 11, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [19000343fd](https://linux-hardware.org/?probe=19000343fd) | Nov 08, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [bdca860f08](https://linux-hardware.org/?probe=bdca860f08) | Nov 06, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [f4ef4d30b0](https://linux-hardware.org/?probe=f4ef4d30b0) | Nov 06, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [73ba8f75b7](https://linux-hardware.org/?probe=73ba8f75b7) | Nov 04, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [e941d01470](https://linux-hardware.org/?probe=e941d01470) | Nov 02, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [49e1be474a](https://linux-hardware.org/?probe=49e1be474a) | Nov 01, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [60ca16eaff](https://linux-hardware.org/?probe=60ca16eaff) | Oct 30, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [ded0ce1d3e](https://linux-hardware.org/?probe=ded0ce1d3e) | Oct 29, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [73f4952d74](https://linux-hardware.org/?probe=73f4952d74) | Oct 29, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [1b93a2f7df](https://linux-hardware.org/?probe=1b93a2f7df) | Oct 28, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [9a01d62b1e](https://linux-hardware.org/?probe=9a01d62b1e) | Oct 28, 2022 |
| ASUSTek       | U50Vg                       | Notebook    | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | G60                         | Notebook    | [e9af8a9e61](https://linux-hardware.org/?probe=e9af8a9e61) | Oct 28, 2022 |
| Toshiba       | STI 005492G                 | Desktop     | [e7fccc3a84](https://linux-hardware.org/?probe=e7fccc3a84) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c9393d50b5](https://linux-hardware.org/?probe=c9393d50b5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [5199be5418](https://linux-hardware.org/?probe=5199be5418) | Oct 24, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [64030c9ba3](https://linux-hardware.org/?probe=64030c9ba3) | Oct 24, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d135b32e8b](https://linux-hardware.org/?probe=d135b32e8b) | Oct 21, 2022 |
| Acer          | Aspire E5-551               | Notebook    | [0e72f3b2e8](https://linux-hardware.org/?probe=0e72f3b2e8) | Oct 21, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [108583577e](https://linux-hardware.org/?probe=108583577e) | Oct 21, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [ec9a97a15d](https://linux-hardware.org/?probe=ec9a97a15d) | Oct 20, 2022 |
| Lenovo        | ThinkPad T470 20HD002TCD    | Notebook    | [0b0ca5a5f6](https://linux-hardware.org/?probe=0b0ca5a5f6) | Oct 20, 2022 |
| Lenovo        | G580 2689H2G                | Notebook    | [1d81a2fb3b](https://linux-hardware.org/?probe=1d81a2fb3b) | Oct 18, 2022 |
| Notebook      | N15_17RD,RD2                | Notebook    | [50713b916b](https://linux-hardware.org/?probe=50713b916b) | Oct 18, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [8a3de9dbf2](https://linux-hardware.org/?probe=8a3de9dbf2) | Oct 18, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [3dd30d87be](https://linux-hardware.org/?probe=3dd30d87be) | Oct 18, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [17c133e933](https://linux-hardware.org/?probe=17c133e933) | Oct 15, 2022 |
| HP            | Presario C300 (RM500EA#A... | Notebook    | [c35d7b0ee3](https://linux-hardware.org/?probe=c35d7b0ee3) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| Dell          | Precision M3800             | Notebook    | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| IBM           | ThinkPad R51 1836Q4U        | Notebook    | [f77e633009](https://linux-hardware.org/?probe=f77e633009) | Oct 11, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [1f2485fab4](https://linux-hardware.org/?probe=1f2485fab4) | Oct 08, 2022 |
| Dell          | 0UW457 A03                  | Desktop     | [e9b6d4e613](https://linux-hardware.org/?probe=e9b6d4e613) | Oct 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [fc558ece05](https://linux-hardware.org/?probe=fc558ece05) | Oct 02, 2022 |
| HP            | 1497                        | Desktop     | [86ab60b437](https://linux-hardware.org/?probe=86ab60b437) | Sep 30, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [8272a6655b](https://linux-hardware.org/?probe=8272a6655b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [be9d7b3e42](https://linux-hardware.org/?probe=be9d7b3e42) | Sep 28, 2022 |
| Acer          | AO532h                      | Notebook    | [383ce70d97](https://linux-hardware.org/?probe=383ce70d97) | Sep 25, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | Notebook    | [fef4bc54eb](https://linux-hardware.org/?probe=fef4bc54eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | Notebook    | [db6bdb0dbd](https://linux-hardware.org/?probe=db6bdb0dbd) | Sep 20, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [0408dbc0cc](https://linux-hardware.org/?probe=0408dbc0cc) | Sep 19, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [55497ec8a3](https://linux-hardware.org/?probe=55497ec8a3) | Sep 19, 2022 |
| Dell          | System XPS L702X            | Notebook    | [6f7b318b6d](https://linux-hardware.org/?probe=6f7b318b6d) | Sep 17, 2022 |
| Dell          | System XPS L702X            | Notebook    | [4b812d3653](https://linux-hardware.org/?probe=4b812d3653) | Sep 17, 2022 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [3b63a75571](https://linux-hardware.org/?probe=3b63a75571) | Sep 16, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [9e4267bcc6](https://linux-hardware.org/?probe=9e4267bcc6) | Sep 15, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [bd9b94b7f8](https://linux-hardware.org/?probe=bd9b94b7f8) | Sep 15, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [575e8f5f81](https://linux-hardware.org/?probe=575e8f5f81) | Sep 14, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f90bed17e2](https://linux-hardware.org/?probe=f90bed17e2) | Sep 13, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [55ee4f593c](https://linux-hardware.org/?probe=55ee4f593c) | Sep 12, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [e5067297e8](https://linux-hardware.org/?probe=e5067297e8) | Sep 07, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [1d387a1216](https://linux-hardware.org/?probe=1d387a1216) | Sep 07, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | Notebook    | [bceac5a658](https://linux-hardware.org/?probe=bceac5a658) | Aug 30, 2022 |
| Dell          | Latitude E6500              | Notebook    | [defd0003bc](https://linux-hardware.org/?probe=defd0003bc) | Aug 22, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [552d907afc](https://linux-hardware.org/?probe=552d907afc) | Aug 20, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Dell          | 0MWYPT A00                  | Desktop     | [9b33533a8d](https://linux-hardware.org/?probe=9b33533a8d) | Aug 09, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [06422a72b8](https://linux-hardware.org/?probe=06422a72b8) | Aug 08, 2022 |
| Lenovo        | ThinkPad Edge 030244U       | Notebook    | [b8b2ea30e1](https://linux-hardware.org/?probe=b8b2ea30e1) | Aug 08, 2022 |
| ASUSTek       | 1015PX                      | Notebook    | [af43595e7b](https://linux-hardware.org/?probe=af43595e7b) | Aug 08, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [2d4b30ec72](https://linux-hardware.org/?probe=2d4b30ec72) | Aug 07, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [0ebff09d2b](https://linux-hardware.org/?probe=0ebff09d2b) | Aug 07, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [bc4cf926f2](https://linux-hardware.org/?probe=bc4cf926f2) | Aug 06, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [93794bf0b1](https://linux-hardware.org/?probe=93794bf0b1) | Aug 01, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [b0b9ddad28](https://linux-hardware.org/?probe=b0b9ddad28) | Jul 30, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [2de6d95c80](https://linux-hardware.org/?probe=2de6d95c80) | Jul 28, 2022 |
| Gigabyte      | Z590 D                      | Desktop     | [fe718899cb](https://linux-hardware.org/?probe=fe718899cb) | Jul 26, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2ba1ac3ec9](https://linux-hardware.org/?probe=2ba1ac3ec9) | Jul 23, 2022 |
| Toshiba       | EQUIUM A110                 | Notebook    | [4b6ace9122](https://linux-hardware.org/?probe=4b6ace9122) | Jul 22, 2022 |
| Huanan        | X79 VAA1                    | Desktop     | [9069c6e2ad](https://linux-hardware.org/?probe=9069c6e2ad) | Jul 19, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [f653a494f3](https://linux-hardware.org/?probe=f653a494f3) | Jul 18, 2022 |
| HP            | Presario V2000 (EC158UA#... | Notebook    | [d46bb41a18](https://linux-hardware.org/?probe=d46bb41a18) | Jul 08, 2022 |
| HP            | Presario V2000 (EC158UA#... | Notebook    | [c55a6d7cca](https://linux-hardware.org/?probe=c55a6d7cca) | Jul 08, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [c09a3e0c24](https://linux-hardware.org/?probe=c09a3e0c24) | Jul 08, 2022 |
| MSI           | MS-AA71                     | All in one  | [4e7d1d05d6](https://linux-hardware.org/?probe=4e7d1d05d6) | Jul 06, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e400d050db](https://linux-hardware.org/?probe=e400d050db) | Jul 05, 2022 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [cc62a478ac](https://linux-hardware.org/?probe=cc62a478ac) | Jul 01, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [3bbee83307](https://linux-hardware.org/?probe=3bbee83307) | Jun 30, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [0b299bea1b](https://linux-hardware.org/?probe=0b299bea1b) | Jun 30, 2022 |
| Biostar       | H510MH/E                    | Desktop     | [7b28198a82](https://linux-hardware.org/?probe=7b28198a82) | Jun 30, 2022 |
| Nvidia        | Tegra                       | Soc         | [cfeb6fb78f](https://linux-hardware.org/?probe=cfeb6fb78f) | Jun 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [d08060fb50](https://linux-hardware.org/?probe=d08060fb50) | Jun 23, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [672749ef0e](https://linux-hardware.org/?probe=672749ef0e) | Jun 22, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [bbfd4f7b68](https://linux-hardware.org/?probe=bbfd4f7b68) | Jun 22, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [f395d01890](https://linux-hardware.org/?probe=f395d01890) | Jun 21, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | Notebook    | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| Nvidia        | Tegra                       | Soc         | [4d32910c65](https://linux-hardware.org/?probe=4d32910c65) | Jun 16, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [ba10f6ee4f](https://linux-hardware.org/?probe=ba10f6ee4f) | Jun 14, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [5ad081e335](https://linux-hardware.org/?probe=5ad081e335) | Jun 13, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [73f3d67b14](https://linux-hardware.org/?probe=73f3d67b14) | Jun 13, 2022 |
| HP            | 3398                        | Desktop     | [fe4629c354](https://linux-hardware.org/?probe=fe4629c354) | Jun 05, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [4f9d7a297e](https://linux-hardware.org/?probe=4f9d7a297e) | Jun 05, 2022 |
| HP            | 09E8h                       | Desktop     | [9c75a338fc](https://linux-hardware.org/?probe=9c75a338fc) | May 31, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3fbca187e7](https://linux-hardware.org/?probe=3fbca187e7) | May 31, 2022 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [55e99cb697](https://linux-hardware.org/?probe=55e99cb697) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | Notebook    | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [e054e02eba](https://linux-hardware.org/?probe=e054e02eba) | May 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [dd39f18241](https://linux-hardware.org/?probe=dd39f18241) | May 25, 2022 |
| Shuttle       | FH170                       | Desktop     | [2645369ebc](https://linux-hardware.org/?probe=2645369ebc) | May 24, 2022 |
| HP            | Compaq 6720s                | Notebook    | [b7ea743814](https://linux-hardware.org/?probe=b7ea743814) | May 22, 2022 |
| HP            | Compaq 6720s                | Notebook    | [c0b723e185](https://linux-hardware.org/?probe=c0b723e185) | May 22, 2022 |
| HP            | 3398                        | Desktop     | [d7e6c0c903](https://linux-hardware.org/?probe=d7e6c0c903) | May 22, 2022 |
| HP            | Mini 210-1000               | Notebook    | [f4d6735690](https://linux-hardware.org/?probe=f4d6735690) | May 20, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [0a25740096](https://linux-hardware.org/?probe=0a25740096) | May 18, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [952fd1b0ac](https://linux-hardware.org/?probe=952fd1b0ac) | May 13, 2022 |
| Shuttle       | FH170                       | Desktop     | [9a5b55b35c](https://linux-hardware.org/?probe=9a5b55b35c) | May 13, 2022 |
| ASRock        | AM1B-ITX                    | Desktop     | [622db6a0da](https://linux-hardware.org/?probe=622db6a0da) | May 12, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [a940d31b37](https://linux-hardware.org/?probe=a940d31b37) | May 10, 2022 |
| HP            | Mini 110-1000               | Notebook    | [e1a5afc203](https://linux-hardware.org/?probe=e1a5afc203) | May 06, 2022 |
| HP            | Compaq 6830s (FR883LA#AB... | Notebook    | [a3eb29c75d](https://linux-hardware.org/?probe=a3eb29c75d) | May 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [329673fcbf](https://linux-hardware.org/?probe=329673fcbf) | May 03, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f639c7c8f5](https://linux-hardware.org/?probe=f639c7c8f5) | Apr 29, 2022 |
| Gigabyte      | H170-HD3 DDR3-CF            | Desktop     | [b23594dfa0](https://linux-hardware.org/?probe=b23594dfa0) | Apr 29, 2022 |
| Acer          | TM4750                      | Notebook    | [8254e2b47d](https://linux-hardware.org/?probe=8254e2b47d) | Apr 27, 2022 |
| HP            | 3646h                       | Desktop     | [131d2ef893](https://linux-hardware.org/?probe=131d2ef893) | Apr 23, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [75dc6c44e5](https://linux-hardware.org/?probe=75dc6c44e5) | Apr 23, 2022 |
| HP            | 3646h                       | Desktop     | [e232464dd6](https://linux-hardware.org/?probe=e232464dd6) | Apr 22, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [e0729e8375](https://linux-hardware.org/?probe=e0729e8375) | Apr 22, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0150424029](https://linux-hardware.org/?probe=0150424029) | Apr 22, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [8ef18c7ea4](https://linux-hardware.org/?probe=8ef18c7ea4) | Apr 21, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [15bba912da](https://linux-hardware.org/?probe=15bba912da) | Apr 21, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [242592fee5](https://linux-hardware.org/?probe=242592fee5) | Apr 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [7ef3e515d9](https://linux-hardware.org/?probe=7ef3e515d9) | Apr 15, 2022 |
| Dell          | 0N867P A01                  | Desktop     | [749dc04756](https://linux-hardware.org/?probe=749dc04756) | Apr 12, 2022 |
| Dell          | Latitude D630               | Notebook    | [6c715d7619](https://linux-hardware.org/?probe=6c715d7619) | Apr 09, 2022 |
| Unknown       | Unknown                     | Soc         | [99029e9661](https://linux-hardware.org/?probe=99029e9661) | Apr 08, 2022 |
| Timi          | TM1701                      | Notebook    | [e2930f3884](https://linux-hardware.org/?probe=e2930f3884) | Apr 06, 2022 |
| Lenovo        | ThinkPad P70 20ESS04S00     | Notebook    | [18bcdf72db](https://linux-hardware.org/?probe=18bcdf72db) | Apr 05, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [e7d599e001](https://linux-hardware.org/?probe=e7d599e001) | Apr 01, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [52d7f90956](https://linux-hardware.org/?probe=52d7f90956) | Apr 01, 2022 |
| HP            | ProBook 6550b               | Notebook    | [d337221af6](https://linux-hardware.org/?probe=d337221af6) | Apr 01, 2022 |
| HP            | 0A54h                       | Desktop     | [0efed10555](https://linux-hardware.org/?probe=0efed10555) | Mar 29, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [60b0ea7dd1](https://linux-hardware.org/?probe=60b0ea7dd1) | Mar 26, 2022 |
| eMachines     | eM350                       | Notebook    | [19b0ed12cc](https://linux-hardware.org/?probe=19b0ed12cc) | Mar 26, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [f758ccfcbe](https://linux-hardware.org/?probe=f758ccfcbe) | Mar 25, 2022 |
| Panasonic     | CF-19AHUDX1M                | Notebook    | [638470e61d](https://linux-hardware.org/?probe=638470e61d) | Mar 25, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [4add06ac06](https://linux-hardware.org/?probe=4add06ac06) | Mar 17, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [1f948586ca](https://linux-hardware.org/?probe=1f948586ca) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [737a2d4c61](https://linux-hardware.org/?probe=737a2d4c61) | Mar 14, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [be2c2c791c](https://linux-hardware.org/?probe=be2c2c791c) | Mar 09, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [6563e94c95](https://linux-hardware.org/?probe=6563e94c95) | Mar 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [33ce116b8a](https://linux-hardware.org/?probe=33ce116b8a) | Mar 08, 2022 |
| Dell          | System XPS L322X            | Notebook    | [2aa0c05f64](https://linux-hardware.org/?probe=2aa0c05f64) | Mar 06, 2022 |
| Dell          | Precision WorkStation 53... | Desktop     | [0969471740](https://linux-hardware.org/?probe=0969471740) | Mar 05, 2022 |
| Nvidia        | Tegra                       | Soc         | [904f2d4f21](https://linux-hardware.org/?probe=904f2d4f21) | Feb 28, 2022 |
| Acer          | Aspire X3950                | Desktop     | [29e02ae274](https://linux-hardware.org/?probe=29e02ae274) | Feb 27, 2022 |
| Toshiba       | Satellite Pro A40-C         | Notebook    | [49766126e1](https://linux-hardware.org/?probe=49766126e1) | Feb 27, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [95b1251334](https://linux-hardware.org/?probe=95b1251334) | Feb 23, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [38511163be](https://linux-hardware.org/?probe=38511163be) | Feb 22, 2022 |
| HP            | 1494                        | Desktop     | [f2b67d46d0](https://linux-hardware.org/?probe=f2b67d46d0) | Feb 19, 2022 |
| MSI           | MS-AAA71 100                | Desktop     | [cf1a921cae](https://linux-hardware.org/?probe=cf1a921cae) | Feb 19, 2022 |
| Nvidia        | Tegra                       | Soc         | [7cde4a4d40](https://linux-hardware.org/?probe=7cde4a4d40) | Feb 19, 2022 |
| Dell          | Inspiron 1011               | Notebook    | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [16b6deff57](https://linux-hardware.org/?probe=16b6deff57) | Feb 19, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [7814d1e2f8](https://linux-hardware.org/?probe=7814d1e2f8) | Feb 18, 2022 |
| MSI           | EX620                       | Notebook    | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [ee8d1e4b48](https://linux-hardware.org/?probe=ee8d1e4b48) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [7a511b44b6](https://linux-hardware.org/?probe=7a511b44b6) | Feb 12, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [a45da375c0](https://linux-hardware.org/?probe=a45da375c0) | Feb 11, 2022 |
| ASRock        | X99M Extreme4               | Desktop     | [c07bb42ff3](https://linux-hardware.org/?probe=c07bb42ff3) | Feb 08, 2022 |
| ASRock        | X99M Extreme4               | Desktop     | [eeb38fc01d](https://linux-hardware.org/?probe=eeb38fc01d) | Feb 07, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [5a471683f7](https://linux-hardware.org/?probe=5a471683f7) | Feb 05, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c55769f459](https://linux-hardware.org/?probe=c55769f459) | Feb 02, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [b685151ac1](https://linux-hardware.org/?probe=b685151ac1) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [712c420215](https://linux-hardware.org/?probe=712c420215) | Jan 31, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [0c05019294](https://linux-hardware.org/?probe=0c05019294) | Jan 31, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [190a99dd63](https://linux-hardware.org/?probe=190a99dd63) | Jan 31, 2022 |
| Acer          | Aspire X3950                | Desktop     | [c3e1066388](https://linux-hardware.org/?probe=c3e1066388) | Jan 30, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [0cb832f85f](https://linux-hardware.org/?probe=0cb832f85f) | Jan 27, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [16d9024680](https://linux-hardware.org/?probe=16d9024680) | Jan 26, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e9752ad35d](https://linux-hardware.org/?probe=e9752ad35d) | Jan 24, 2022 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [5aa25aeeeb](https://linux-hardware.org/?probe=5aa25aeeeb) | Jan 21, 2022 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [90b4523b21](https://linux-hardware.org/?probe=90b4523b21) | Jan 19, 2022 |
| MSI           | H310M-S03                   | Desktop     | [8c009a1259](https://linux-hardware.org/?probe=8c009a1259) | Jan 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [d43bc9ead0](https://linux-hardware.org/?probe=d43bc9ead0) | Jan 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [5cabde7162](https://linux-hardware.org/?probe=5cabde7162) | Jan 08, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [753fcd1661](https://linux-hardware.org/?probe=753fcd1661) | Jan 08, 2022 |
| MSI           | B150 GAMING M3              | Desktop     | [3514e82b43](https://linux-hardware.org/?probe=3514e82b43) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [c3a0a425f9](https://linux-hardware.org/?probe=c3a0a425f9) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [ea4bdf8279](https://linux-hardware.org/?probe=ea4bdf8279) | Jan 06, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [bc75234559](https://linux-hardware.org/?probe=bc75234559) | Jan 06, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [3d44173eda](https://linux-hardware.org/?probe=3d44173eda) | Jan 05, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [759f405820](https://linux-hardware.org/?probe=759f405820) | Jan 05, 2022 |
| Dell          | 0MM599                      | Desktop     | [82532cb19f](https://linux-hardware.org/?probe=82532cb19f) | Jan 03, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [8834da8d25](https://linux-hardware.org/?probe=8834da8d25) | Jan 02, 2022 |
| Lenovo        | ThinkPad T430 23426FU       | Notebook    | [53e2109383](https://linux-hardware.org/?probe=53e2109383) | Dec 30, 2021 |
| Gigabyte      | M61PME-S2                   | Desktop     | [f7fd55088e](https://linux-hardware.org/?probe=f7fd55088e) | Dec 27, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [9fb08ebeb4](https://linux-hardware.org/?probe=9fb08ebeb4) | Dec 26, 2021 |
| Dell          | 0NDYHG A01                  | Desktop     | [093e7e5784](https://linux-hardware.org/?probe=093e7e5784) | Dec 20, 2021 |
| MSI           | GS66 Stealth 11UE           | Notebook    | [ab09d4463d](https://linux-hardware.org/?probe=ab09d4463d) | Dec 20, 2021 |
| Nvidia        | Tegra                       | Soc         | [30c09e0585](https://linux-hardware.org/?probe=30c09e0585) | Dec 17, 2021 |
| Toshiba       | Satellite C600              | Notebook    | [dd417ecb87](https://linux-hardware.org/?probe=dd417ecb87) | Dec 15, 2021 |
| Sony          | VGN-NR430E                  | Notebook    | [305865a785](https://linux-hardware.org/?probe=305865a785) | Dec 12, 2021 |
| Sony          | VGN-NR430E                  | Notebook    | [3ca106703d](https://linux-hardware.org/?probe=3ca106703d) | Dec 11, 2021 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [cd0e6354c3](https://linux-hardware.org/?probe=cd0e6354c3) | Dec 11, 2021 |
| Dell          | Latitude 3410               | Notebook    | [4b84ebe353](https://linux-hardware.org/?probe=4b84ebe353) | Dec 08, 2021 |
| Dell          | Latitude 3410               | Notebook    | [c2a6a9ad6b](https://linux-hardware.org/?probe=c2a6a9ad6b) | Dec 08, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [5b7f08a29b](https://linux-hardware.org/?probe=5b7f08a29b) | Dec 08, 2021 |
| ASRockRack    | E3C232D4U-V1L               | Desktop     | [139a75e689](https://linux-hardware.org/?probe=139a75e689) | Dec 07, 2021 |
| Nvidia        | Tegra                       | Soc         | [87cf7f053c](https://linux-hardware.org/?probe=87cf7f053c) | Dec 06, 2021 |
| Nvidia        | Tegra                       | Soc         | [b62c884aec](https://linux-hardware.org/?probe=b62c884aec) | Dec 05, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [a700683a6f](https://linux-hardware.org/?probe=a700683a6f) | Dec 05, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [ad91050095](https://linux-hardware.org/?probe=ad91050095) | Dec 03, 2021 |
| Lenovo        | ThinkPad R61 89337HG        | Notebook    | [670c02b990](https://linux-hardware.org/?probe=670c02b990) | Dec 02, 2021 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [a9ef047f21](https://linux-hardware.org/?probe=a9ef047f21) | Dec 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [c9ed75dd92](https://linux-hardware.org/?probe=c9ed75dd92) | Dec 02, 2021 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [09fd8a63b7](https://linux-hardware.org/?probe=09fd8a63b7) | Nov 30, 2021 |
| Sony          | VGN-FE31B                   | Notebook    | [9c79f90f8d](https://linux-hardware.org/?probe=9c79f90f8d) | Nov 27, 2021 |
| HP            | Pavilion 17                 | Notebook    | [b5f54d657a](https://linux-hardware.org/?probe=b5f54d657a) | Nov 27, 2021 |
| Acer          | Aspire 6920                 | Notebook    | [ecd71d1bde](https://linux-hardware.org/?probe=ecd71d1bde) | Nov 26, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [1dc5d193a3](https://linux-hardware.org/?probe=1dc5d193a3) | Nov 24, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7045bece2c](https://linux-hardware.org/?probe=7045bece2c) | Nov 23, 2021 |
| Packard Be... | EasyNote TJ75               | Notebook    | [76b8b98ec9](https://linux-hardware.org/?probe=76b8b98ec9) | Nov 21, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [dc3ffc2288](https://linux-hardware.org/?probe=dc3ffc2288) | Nov 20, 2021 |
| MSI           | Boston                      | Desktop     | [6e0d850a8e](https://linux-hardware.org/?probe=6e0d850a8e) | Nov 17, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [1f5deb0f31](https://linux-hardware.org/?probe=1f5deb0f31) | Nov 16, 2021 |
| Lenovo        | IdeaPad Z460 0913           | Notebook    | [0bb3eea006](https://linux-hardware.org/?probe=0bb3eea006) | Nov 16, 2021 |
| Acer          | One S1003                   | Tablet      | [e88252db3f](https://linux-hardware.org/?probe=e88252db3f) | Nov 13, 2021 |
| Lenovo        | G580 26897JJ                | Notebook    | [dc2120663a](https://linux-hardware.org/?probe=dc2120663a) | Nov 10, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [a9cf3f2b5b](https://linux-hardware.org/?probe=a9cf3f2b5b) | Nov 08, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [85d8ecd997](https://linux-hardware.org/?probe=85d8ecd997) | Nov 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [0c99cea4ba](https://linux-hardware.org/?probe=0c99cea4ba) | Nov 07, 2021 |
| Notebook      | NP50DE_DB                   | Notebook    | [6ecc612580](https://linux-hardware.org/?probe=6ecc612580) | Nov 07, 2021 |
| Dell          | Latitude 7490               | Notebook    | [43eeb8d632](https://linux-hardware.org/?probe=43eeb8d632) | Nov 06, 2021 |
| Dell          | Latitude 7490               | Notebook    | [209cc4c51e](https://linux-hardware.org/?probe=209cc4c51e) | Nov 06, 2021 |
| Dell          | 0MTFWP A00                  | Desktop     | [46f1aaf23a](https://linux-hardware.org/?probe=46f1aaf23a) | Nov 03, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [042607d7f1](https://linux-hardware.org/?probe=042607d7f1) | Oct 31, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [11527ae3f9](https://linux-hardware.org/?probe=11527ae3f9) | Oct 31, 2021 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [5f0bcd4c39](https://linux-hardware.org/?probe=5f0bcd4c39) | Oct 30, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [e4aa5740c5](https://linux-hardware.org/?probe=e4aa5740c5) | Oct 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [338ddd258e](https://linux-hardware.org/?probe=338ddd258e) | Oct 24, 2021 |
| Dell          | Precision 3520              | Notebook    | [cf720e50db](https://linux-hardware.org/?probe=cf720e50db) | Oct 24, 2021 |
| Dell          | Latitude D620               | Notebook    | [19049fd2bd](https://linux-hardware.org/?probe=19049fd2bd) | Oct 23, 2021 |
| Dell          | Latitude D620               | Notebook    | [08fd9efc01](https://linux-hardware.org/?probe=08fd9efc01) | Oct 23, 2021 |
| Dell          | 0KWVT8 A03                  | Desktop     | [ec418886cd](https://linux-hardware.org/?probe=ec418886cd) | Oct 22, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [17baa8dc0e](https://linux-hardware.org/?probe=17baa8dc0e) | Oct 19, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [dd8ce106ae](https://linux-hardware.org/?probe=dd8ce106ae) | Oct 17, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bf52ab65ff](https://linux-hardware.org/?probe=bf52ab65ff) | Oct 17, 2021 |
| Dell          | 040DDP A00                  | Desktop     | [95249e56f5](https://linux-hardware.org/?probe=95249e56f5) | Oct 15, 2021 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [19bdd9712d](https://linux-hardware.org/?probe=19bdd9712d) | Oct 09, 2021 |
| Acer          | Aspire E5-432               | Notebook    | [ff1a22fdc4](https://linux-hardware.org/?probe=ff1a22fdc4) | Oct 08, 2021 |
| Toshiba       | dynabook R634/K             | Notebook    | [f0e385cbfb](https://linux-hardware.org/?probe=f0e385cbfb) | Oct 08, 2021 |
| Intel         | NUC6i3SYB H81132-503        | Mini pc     | [38571fcfb9](https://linux-hardware.org/?probe=38571fcfb9) | Oct 04, 2021 |
| Lenovo        | ThinkPad E15 20RD001CGE     | Notebook    | [f7d150a85c](https://linux-hardware.org/?probe=f7d150a85c) | Oct 04, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | Notebook    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [f1420c5af0](https://linux-hardware.org/?probe=f1420c5af0) | Sep 29, 2021 |
| Dell          | 0GXM1W A00                  | Desktop     | [57b3b27a47](https://linux-hardware.org/?probe=57b3b27a47) | Sep 28, 2021 |
| eMachines     | EL1352                      | Desktop     | [2d5f9a7733](https://linux-hardware.org/?probe=2d5f9a7733) | Sep 27, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [31e1740325](https://linux-hardware.org/?probe=31e1740325) | Sep 24, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [5b046ba6ee](https://linux-hardware.org/?probe=5b046ba6ee) | Sep 24, 2021 |
| Acer          | Aspire one 1-431            | Notebook    | [3ff4be2b55](https://linux-hardware.org/?probe=3ff4be2b55) | Sep 21, 2021 |
| Dell          | 0XCR8D A00                  | Desktop     | [a2d02a9a2d](https://linux-hardware.org/?probe=a2d02a9a2d) | Sep 20, 2021 |
| Acer          | AO751h                      | Notebook    | [d217a1c6b7](https://linux-hardware.org/?probe=d217a1c6b7) | Sep 18, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [96463d6903](https://linux-hardware.org/?probe=96463d6903) | Sep 16, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [aa3f685f0a](https://linux-hardware.org/?probe=aa3f685f0a) | Sep 15, 2021 |
| Acer          | Acadia V1.45                | Notebook    | [cd630332c7](https://linux-hardware.org/?probe=cd630332c7) | Sep 15, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [1a39f562b3](https://linux-hardware.org/?probe=1a39f562b3) | Sep 13, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [271309ac53](https://linux-hardware.org/?probe=271309ac53) | Sep 12, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [db2503f46f](https://linux-hardware.org/?probe=db2503f46f) | Sep 07, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [b5b00e8498](https://linux-hardware.org/?probe=b5b00e8498) | Sep 06, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [0d3b75782b](https://linux-hardware.org/?probe=0d3b75782b) | Sep 03, 2021 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [ee76fbd8e5](https://linux-hardware.org/?probe=ee76fbd8e5) | Sep 03, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [5bdbb1445f](https://linux-hardware.org/?probe=5bdbb1445f) | Sep 03, 2021 |
| Panasonic     | CF-20-1                     | Notebook    | [6f921aa428](https://linux-hardware.org/?probe=6f921aa428) | Sep 02, 2021 |
| HP            | 3032h                       | Desktop     | [7d94cc3baa](https://linux-hardware.org/?probe=7d94cc3baa) | Sep 01, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6c149c6405](https://linux-hardware.org/?probe=6c149c6405) | Aug 31, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [27b23ba02b](https://linux-hardware.org/?probe=27b23ba02b) | Aug 29, 2021 |
| ARCELIK       | GNB 15xx B1 Serisi          | Notebook    | [8537b57efa](https://linux-hardware.org/?probe=8537b57efa) | Aug 24, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [781fc26452](https://linux-hardware.org/?probe=781fc26452) | Aug 23, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [f0a640519a](https://linux-hardware.org/?probe=f0a640519a) | Aug 17, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [87d045fa9c](https://linux-hardware.org/?probe=87d045fa9c) | Aug 16, 2021 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [874eaab0bb](https://linux-hardware.org/?probe=874eaab0bb) | Aug 15, 2021 |
| ASUSTek       | Z9PG-D16 Series             | Server      | [c31fdfca91](https://linux-hardware.org/?probe=c31fdfca91) | Aug 15, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [feaabd09c8](https://linux-hardware.org/?probe=feaabd09c8) | Aug 10, 2021 |
| Dell          | Latitude E7450              | Notebook    | [5e94ad6881](https://linux-hardware.org/?probe=5e94ad6881) | Aug 10, 2021 |
| Dell          | Latitude E7450              | Notebook    | [110fc3ebef](https://linux-hardware.org/?probe=110fc3ebef) | Aug 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [8227b4305d](https://linux-hardware.org/?probe=8227b4305d) | Aug 09, 2021 |
| Acer          | AO531h                      | Notebook    | [f677e6e910](https://linux-hardware.org/?probe=f677e6e910) | Aug 09, 2021 |
| Acer          | AO531h                      | Notebook    | [42bc030846](https://linux-hardware.org/?probe=42bc030846) | Aug 09, 2021 |
| Acer          | AO531h                      | Notebook    | [3475d2f343](https://linux-hardware.org/?probe=3475d2f343) | Aug 09, 2021 |
| HP            | ENVY 17                     | Notebook    | [1d6dd8440c](https://linux-hardware.org/?probe=1d6dd8440c) | Aug 05, 2021 |
| Dell          | Studio 1737                 | Notebook    | [b4f16960c4](https://linux-hardware.org/?probe=b4f16960c4) | Aug 05, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [8de53a9490](https://linux-hardware.org/?probe=8de53a9490) | Aug 04, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [ec6ce0a80c](https://linux-hardware.org/?probe=ec6ce0a80c) | Aug 04, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [955d3e4330](https://linux-hardware.org/?probe=955d3e4330) | Aug 02, 2021 |
| ASRock        | Z170 OC Formula             | Desktop     | [0d1ca849b8](https://linux-hardware.org/?probe=0d1ca849b8) | Jul 29, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [b7fec1807a](https://linux-hardware.org/?probe=b7fec1807a) | Jul 29, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [48b32724e2](https://linux-hardware.org/?probe=48b32724e2) | Jul 27, 2021 |
| Teclast       | F6 Pro                      | Notebook    | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [d7369d7eb4](https://linux-hardware.org/?probe=d7369d7eb4) | Jul 26, 2021 |
| HP            | 1494                        | Desktop     | [fe57b848c7](https://linux-hardware.org/?probe=fe57b848c7) | Jul 22, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [8bf86066a5](https://linux-hardware.org/?probe=8bf86066a5) | Jul 22, 2021 |
| Dell          | 0MTFWP A00                  | Desktop     | [bde85c8a04](https://linux-hardware.org/?probe=bde85c8a04) | Jul 21, 2021 |
| Nvidia        | Tegra                       | Soc         | [ecddedcfb7](https://linux-hardware.org/?probe=ecddedcfb7) | Jul 20, 2021 |
| HP            | 1494                        | Desktop     | [2c30dc2cf3](https://linux-hardware.org/?probe=2c30dc2cf3) | Jul 19, 2021 |
| Gateway       | NE570                       | Notebook    | [f9ccf3665f](https://linux-hardware.org/?probe=f9ccf3665f) | Jul 19, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [b221cbc463](https://linux-hardware.org/?probe=b221cbc463) | Jul 17, 2021 |
| Pegatron      | EVE                         | Desktop     | [a8fb12adae](https://linux-hardware.org/?probe=a8fb12adae) | Jul 16, 2021 |
| Timi          | A35S                        | Notebook    | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [7908947c9f](https://linux-hardware.org/?probe=7908947c9f) | Jul 14, 2021 |
| HP            | Pavilion dv6                | Notebook    | [aee9cfed82](https://linux-hardware.org/?probe=aee9cfed82) | Jul 11, 2021 |
| Acer          | Aspire 7740                 | Notebook    | [d8694dd629](https://linux-hardware.org/?probe=d8694dd629) | Jul 09, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [2e203beafd](https://linux-hardware.org/?probe=2e203beafd) | Jul 08, 2021 |
| MSI           | J1900I                      | Desktop     | [31b65c37c9](https://linux-hardware.org/?probe=31b65c37c9) | Jul 07, 2021 |
| Dell          | Latitude 5511               | Notebook    | [cac1bff4a1](https://linux-hardware.org/?probe=cac1bff4a1) | Jul 06, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [6130e48df9](https://linux-hardware.org/?probe=6130e48df9) | Jul 05, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [8fcf62f37c](https://linux-hardware.org/?probe=8fcf62f37c) | Jul 05, 2021 |
| Dell          | 0HY9JP A00                  | Desktop     | [300272bb79](https://linux-hardware.org/?probe=300272bb79) | Jul 03, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [222b34dd03](https://linux-hardware.org/?probe=222b34dd03) | Jul 01, 2021 |
| HP            | Pavilion g4                 | Notebook    | [fa58b1dd24](https://linux-hardware.org/?probe=fa58b1dd24) | Jun 30, 2021 |
| Dell          | Precision 7550              | Notebook    | [79a56a6b22](https://linux-hardware.org/?probe=79a56a6b22) | Jun 30, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [4fd63df257](https://linux-hardware.org/?probe=4fd63df257) | Jun 30, 2021 |
| Gigabyte      | G31M-S2L                    | Desktop     | [ab620ec059](https://linux-hardware.org/?probe=ab620ec059) | Jun 29, 2021 |
| Gigabyte      | P110-D3-CF                  | Desktop     | [37aab1ae76](https://linux-hardware.org/?probe=37aab1ae76) | Jun 29, 2021 |
| HP            | 18E7                        | Desktop     | [5f0e216922](https://linux-hardware.org/?probe=5f0e216922) | Jun 28, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ada772c932](https://linux-hardware.org/?probe=ada772c932) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7MM0... | Notebook    | [4e01561e2d](https://linux-hardware.org/?probe=4e01561e2d) | Jun 25, 2021 |
| Dell          | Latitude 5591               | Notebook    | [0a888c201f](https://linux-hardware.org/?probe=0a888c201f) | Jun 25, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7MM0... | Notebook    | [424e9fe919](https://linux-hardware.org/?probe=424e9fe919) | Jun 24, 2021 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [1f4ef21a29](https://linux-hardware.org/?probe=1f4ef21a29) | Jun 24, 2021 |
| Dell          | Precision 5550              | Notebook    | [7b9e5a1b30](https://linux-hardware.org/?probe=7b9e5a1b30) | Jun 23, 2021 |
| Dell          | Latitude 5511               | Notebook    | [6625368d80](https://linux-hardware.org/?probe=6625368d80) | Jun 21, 2021 |
| Nvidia        | Tegra                       | Soc         | [7616b8f6b7](https://linux-hardware.org/?probe=7616b8f6b7) | Jun 21, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7ddb9a5ab7](https://linux-hardware.org/?probe=7ddb9a5ab7) | Jun 20, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [7026c20c97](https://linux-hardware.org/?probe=7026c20c97) | Jun 20, 2021 |
| Dell          | Latitude 5511               | Notebook    | [3b8bd7756c](https://linux-hardware.org/?probe=3b8bd7756c) | Jun 20, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [f34a1bbe5a](https://linux-hardware.org/?probe=f34a1bbe5a) | Jun 20, 2021 |
| HP            | ProBook 6550b               | Notebook    | [262ede4645](https://linux-hardware.org/?probe=262ede4645) | Jun 16, 2021 |
| MSI           | 870A-G54                    | Desktop     | [b1b8e74ea3](https://linux-hardware.org/?probe=b1b8e74ea3) | Jun 16, 2021 |
| Intel         | S3000AHLX D40858-208        | Desktop     | [ab61e363eb](https://linux-hardware.org/?probe=ab61e363eb) | Jun 12, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [9814f75415](https://linux-hardware.org/?probe=9814f75415) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [3d0b697005](https://linux-hardware.org/?probe=3d0b697005) | Jun 09, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [977558100f](https://linux-hardware.org/?probe=977558100f) | Jun 09, 2021 |
| Lenovo        | 30C1                        | Desktop     | [e6fcdd8be6](https://linux-hardware.org/?probe=e6fcdd8be6) | Jun 08, 2021 |
| HP            | Notebook                    | Notebook    | [aa603459f8](https://linux-hardware.org/?probe=aa603459f8) | Jun 06, 2021 |
| Toshiba       | Satellite Pro A40-C         | Notebook    | [a467cae210](https://linux-hardware.org/?probe=a467cae210) | Jun 03, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [6018f18645](https://linux-hardware.org/?probe=6018f18645) | Jun 02, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [03b8f35b44](https://linux-hardware.org/?probe=03b8f35b44) | Jun 02, 2021 |
| Acer          | Aspire 4830TG               | Notebook    | [0233ed2211](https://linux-hardware.org/?probe=0233ed2211) | May 31, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5f8bfd5fbf](https://linux-hardware.org/?probe=5f8bfd5fbf) | May 30, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Lenovo        | ThinkPad T530 24291H4       | Notebook    | [9ecbb7a946](https://linux-hardware.org/?probe=9ecbb7a946) | May 28, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [d7e0be00c1](https://linux-hardware.org/?probe=d7e0be00c1) | May 27, 2021 |
| Hometech      | N1401A                      | Notebook    | [421dcf0a2f](https://linux-hardware.org/?probe=421dcf0a2f) | May 27, 2021 |
| ASUSTek       | P4S800-MX SE                | Desktop     | [7a323363ef](https://linux-hardware.org/?probe=7a323363ef) | May 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [4ea4310ddc](https://linux-hardware.org/?probe=4ea4310ddc) | May 22, 2021 |
| ECS           | A780GM-A                    | Desktop     | [03853132a4](https://linux-hardware.org/?probe=03853132a4) | May 20, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9b05fb9e1f](https://linux-hardware.org/?probe=9b05fb9e1f) | May 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [0d397cf104](https://linux-hardware.org/?probe=0d397cf104) | May 16, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [b5c18575bf](https://linux-hardware.org/?probe=b5c18575bf) | May 15, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [df4d80f1f9](https://linux-hardware.org/?probe=df4d80f1f9) | May 14, 2021 |
| Acer          | LuganoII                    | Notebook    | [c26e330dae](https://linux-hardware.org/?probe=c26e330dae) | May 13, 2021 |
| Nvidia        | Tegra                       | Soc         | [742be0320c](https://linux-hardware.org/?probe=742be0320c) | May 12, 2021 |
| Acer          | AOA150                      | Notebook    | [21647e22ba](https://linux-hardware.org/?probe=21647e22ba) | May 12, 2021 |
| Acer          | LuganoII                    | Notebook    | [3a87a5cef9](https://linux-hardware.org/?probe=3a87a5cef9) | May 12, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [98ad000dc7](https://linux-hardware.org/?probe=98ad000dc7) | May 11, 2021 |
| Dell          | 0DXYK6 A01                  | Desktop     | [a3183357c9](https://linux-hardware.org/?probe=a3183357c9) | May 10, 2021 |
| Lenovo        | M5400 20281                 | Notebook    | [b0b95cd759](https://linux-hardware.org/?probe=b0b95cd759) | May 09, 2021 |
| HP            | Pavilion dv6                | Notebook    | [dce60f14e1](https://linux-hardware.org/?probe=dce60f14e1) | May 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [ab1c7d5eab](https://linux-hardware.org/?probe=ab1c7d5eab) | May 08, 2021 |
| HP            | 3029h                       | Desktop     | [dfcd82490e](https://linux-hardware.org/?probe=dfcd82490e) | May 08, 2021 |
| HP            | 3029h                       | Desktop     | [f54bf8eeb9](https://linux-hardware.org/?probe=f54bf8eeb9) | May 08, 2021 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [a2ec86f284](https://linux-hardware.org/?probe=a2ec86f284) | May 08, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| Biostar       | IH61MF-Q5                   | Desktop     | [21134da958](https://linux-hardware.org/?probe=21134da958) | May 06, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [22cfe5b72a](https://linux-hardware.org/?probe=22cfe5b72a) | May 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [522b86dc40](https://linux-hardware.org/?probe=522b86dc40) | May 03, 2021 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [0ff4565a31](https://linux-hardware.org/?probe=0ff4565a31) | May 02, 2021 |
| Dell          | Latitude E5440              | Notebook    | [ea59351ece](https://linux-hardware.org/?probe=ea59351ece) | May 01, 2021 |
| Dell          | Latitude 7480               | Notebook    | [6b9e1797c6](https://linux-hardware.org/?probe=6b9e1797c6) | Apr 29, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [ae9a58ea22](https://linux-hardware.org/?probe=ae9a58ea22) | Apr 27, 2021 |
| Nvidia        | Tegra                       | Soc         | [6adca880a0](https://linux-hardware.org/?probe=6adca880a0) | Apr 27, 2021 |
| Nvidia        | Tegra                       | Soc         | [b7b0ca04bc](https://linux-hardware.org/?probe=b7b0ca04bc) | Apr 27, 2021 |
| ASUSTek       | Amberine M                  | Desktop     | [9eeaeb53fc](https://linux-hardware.org/?probe=9eeaeb53fc) | Apr 26, 2021 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [34ab0fd5ed](https://linux-hardware.org/?probe=34ab0fd5ed) | Apr 24, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [bd53dff836](https://linux-hardware.org/?probe=bd53dff836) | Apr 23, 2021 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [daf737a5ba](https://linux-hardware.org/?probe=daf737a5ba) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [1e2ec488ee](https://linux-hardware.org/?probe=1e2ec488ee) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [171825e444](https://linux-hardware.org/?probe=171825e444) | Apr 21, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1bcff94731](https://linux-hardware.org/?probe=1bcff94731) | Apr 20, 2021 |
| ASRock        | B550 Steel Legend           | Desktop     | [d8db6d8577](https://linux-hardware.org/?probe=d8db6d8577) | Apr 18, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [c75019619f](https://linux-hardware.org/?probe=c75019619f) | Apr 17, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [2070ae5e60](https://linux-hardware.org/?probe=2070ae5e60) | Apr 11, 2021 |
| ASRock        | X370 Gaming X               | Desktop     | [ec2915656d](https://linux-hardware.org/?probe=ec2915656d) | Apr 09, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [b5253eecf6](https://linux-hardware.org/?probe=b5253eecf6) | Apr 05, 2021 |
| Nvidia        | Tegra                       | Soc         | [3eef74187f](https://linux-hardware.org/?probe=3eef74187f) | Apr 04, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [a7a9af4a65](https://linux-hardware.org/?probe=a7a9af4a65) | Apr 04, 2021 |
| Acer          | TravelMate 5530             | Notebook    | [6b6df6431c](https://linux-hardware.org/?probe=6b6df6431c) | Apr 02, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [bc3cceab26](https://linux-hardware.org/?probe=bc3cceab26) | Mar 28, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [981ef499d5](https://linux-hardware.org/?probe=981ef499d5) | Mar 28, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [f5335bcba5](https://linux-hardware.org/?probe=f5335bcba5) | Mar 28, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [92223923ad](https://linux-hardware.org/?probe=92223923ad) | Mar 28, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [ed77da0a7f](https://linux-hardware.org/?probe=ed77da0a7f) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| ASRock        | Z87 Extreme3                | Desktop     | [702e348746](https://linux-hardware.org/?probe=702e348746) | Mar 25, 2021 |
| Acer          | ERC410M                     | Desktop     | [de264500c8](https://linux-hardware.org/?probe=de264500c8) | Mar 24, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [2c8acbf86c](https://linux-hardware.org/?probe=2c8acbf86c) | Mar 21, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [27f1098177](https://linux-hardware.org/?probe=27f1098177) | Mar 20, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [290838c751](https://linux-hardware.org/?probe=290838c751) | Mar 19, 2021 |
| Dell          | Latitude 5591               | Notebook    | [440c09d385](https://linux-hardware.org/?probe=440c09d385) | Mar 19, 2021 |
| MSI           | EX620                       | Notebook    | [92223bedbf](https://linux-hardware.org/?probe=92223bedbf) | Mar 18, 2021 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [daf57d1fe4](https://linux-hardware.org/?probe=daf57d1fe4) | Mar 17, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ef2bfba994](https://linux-hardware.org/?probe=ef2bfba994) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [39fb7fbfdd](https://linux-hardware.org/?probe=39fb7fbfdd) | Mar 17, 2021 |
| IDEALMAX      | H34                         | Notebook    | [3a80074655](https://linux-hardware.org/?probe=3a80074655) | Mar 17, 2021 |
| MSI           | Z270 GAMING M7              | Desktop     | [b72439b299](https://linux-hardware.org/?probe=b72439b299) | Mar 17, 2021 |
| Acer          | B350AM4-M                   | Desktop     | [277bbc0e9e](https://linux-hardware.org/?probe=277bbc0e9e) | Mar 16, 2021 |
| Sony          | VPCEB2M1E                   | Notebook    | [b66618f38f](https://linux-hardware.org/?probe=b66618f38f) | Mar 16, 2021 |
| Positivo      | Mobile                      | Notebook    | [b6bf80e4a0](https://linux-hardware.org/?probe=b6bf80e4a0) | Mar 15, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [35db155267](https://linux-hardware.org/?probe=35db155267) | Mar 15, 2021 |
| Medion        | H61H2-LM3 V1.0              | Desktop     | [baec6f54e0](https://linux-hardware.org/?probe=baec6f54e0) | Mar 14, 2021 |
| Uniwill       | 255KI / 259KI Series        | Desktop     | [e9bc9b3c8a](https://linux-hardware.org/?probe=e9bc9b3c8a) | Mar 13, 2021 |
| Dell          | 0GM819                      | Desktop     | [8c4895a06b](https://linux-hardware.org/?probe=8c4895a06b) | Mar 13, 2021 |
| Dell          | Latitude E5250              | Notebook    | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [f4de81ccba](https://linux-hardware.org/?probe=f4de81ccba) | Mar 11, 2021 |
| Lenovo        | ThinkPad X250 20CLS0LJ04    | Notebook    | [3ea7e7e0eb](https://linux-hardware.org/?probe=3ea7e7e0eb) | Mar 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS0LJ04    | Notebook    | [fbc708f40b](https://linux-hardware.org/?probe=fbc708f40b) | Mar 10, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [d55c9ab43d](https://linux-hardware.org/?probe=d55c9ab43d) | Mar 09, 2021 |
| Dell          | Latitude E5250              | Notebook    | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Toshiba       | Satellite U405D             | Notebook    | [c39fbac2a3](https://linux-hardware.org/?probe=c39fbac2a3) | Mar 07, 2021 |
| MSI           | MS-7369                     | Desktop     | [6b76ab1b0c](https://linux-hardware.org/?probe=6b76ab1b0c) | Mar 06, 2021 |
| MSI           | MS-7369                     | Desktop     | [c26816dad0](https://linux-hardware.org/?probe=c26816dad0) | Mar 06, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [e7550259a4](https://linux-hardware.org/?probe=e7550259a4) | Mar 06, 2021 |
| Nvidia        | Tegra                       | Soc         | [3c7d66229b](https://linux-hardware.org/?probe=3c7d66229b) | Mar 06, 2021 |
| Nvidia        | Tegra                       | Soc         | [8efa588967](https://linux-hardware.org/?probe=8efa588967) | Mar 05, 2021 |
| ASRock        | QC5000-ITX/PH               | Desktop     | [025e863d24](https://linux-hardware.org/?probe=025e863d24) | Mar 05, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [4451a45c7f](https://linux-hardware.org/?probe=4451a45c7f) | Mar 03, 2021 |
| Dell          | Precision M3800             | Notebook    | [946b253122](https://linux-hardware.org/?probe=946b253122) | Mar 03, 2021 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [f9edf81d02](https://linux-hardware.org/?probe=f9edf81d02) | Mar 02, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [11e6858209](https://linux-hardware.org/?probe=11e6858209) | Feb 28, 2021 |
| MSI           | H61M-P22                    | Desktop     | [2b1f47c25e](https://linux-hardware.org/?probe=2b1f47c25e) | Feb 28, 2021 |
| Dell          | 0XFWHV A00                  | Desktop     | [439e40ec4f](https://linux-hardware.org/?probe=439e40ec4f) | Feb 25, 2021 |
| Toshiba       | Satellite Pro A100          | Notebook    | [403755cbe6](https://linux-hardware.org/?probe=403755cbe6) | Feb 25, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [adbd82e6f8](https://linux-hardware.org/?probe=adbd82e6f8) | Feb 23, 2021 |
| Intel         | DH55PJ AAE93812-302         | Desktop     | [b255f21865](https://linux-hardware.org/?probe=b255f21865) | Feb 22, 2021 |
| Dell          | 03CPWF A00                  | Desktop     | [126a2e8974](https://linux-hardware.org/?probe=126a2e8974) | Feb 22, 2021 |
| Dell          | Latitude 7280               | Notebook    | [07efc65c6a](https://linux-hardware.org/?probe=07efc65c6a) | Feb 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a4096f684a](https://linux-hardware.org/?probe=a4096f684a) | Feb 21, 2021 |
| Toshiba       | IS-1522                     | Notebook    | [6e0892a006](https://linux-hardware.org/?probe=6e0892a006) | Feb 19, 2021 |
| Acer          | Aspire 5610                 | Notebook    | [c5681a4097](https://linux-hardware.org/?probe=c5681a4097) | Feb 17, 2021 |
| Toshiba       | Satellite C50D-B            | Notebook    | [4114652578](https://linux-hardware.org/?probe=4114652578) | Feb 16, 2021 |
| Toshiba       | Satellite C50D-B            | Notebook    | [63a04a0d52](https://linux-hardware.org/?probe=63a04a0d52) | Feb 16, 2021 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [5e5e5b2190](https://linux-hardware.org/?probe=5e5e5b2190) | Feb 15, 2021 |
| Nvidia        | Tegra                       | Soc         | [be96bbe4f4](https://linux-hardware.org/?probe=be96bbe4f4) | Feb 15, 2021 |
| Dell          | Latitude E4310              | Notebook    | [37a49f8182](https://linux-hardware.org/?probe=37a49f8182) | Feb 15, 2021 |
| Dell          | Latitude 7480               | Notebook    | [92f5ef8b15](https://linux-hardware.org/?probe=92f5ef8b15) | Feb 14, 2021 |
| Dell          | Latitude 7480               | Notebook    | [7fc96867c5](https://linux-hardware.org/?probe=7fc96867c5) | Feb 14, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | Notebook    | [ea78db0716](https://linux-hardware.org/?probe=ea78db0716) | Feb 14, 2021 |
| Nvidia        | Tegra                       | Soc         | [b49723230a](https://linux-hardware.org/?probe=b49723230a) | Feb 13, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [26169a65ed](https://linux-hardware.org/?probe=26169a65ed) | Feb 13, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [f4b9bbaa28](https://linux-hardware.org/?probe=f4b9bbaa28) | Feb 13, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [dfe8b342e5](https://linux-hardware.org/?probe=dfe8b342e5) | Feb 13, 2021 |
| ASUSTek       | X55U                        | Notebook    | [aea7a001db](https://linux-hardware.org/?probe=aea7a001db) | Feb 13, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [8ec8f1ce75](https://linux-hardware.org/?probe=8ec8f1ce75) | Feb 11, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [4b2cd43abc](https://linux-hardware.org/?probe=4b2cd43abc) | Feb 10, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [e5b3c2f659](https://linux-hardware.org/?probe=e5b3c2f659) | Feb 10, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [8e6c1aadd3](https://linux-hardware.org/?probe=8e6c1aadd3) | Feb 10, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [2589d166ca](https://linux-hardware.org/?probe=2589d166ca) | Feb 10, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [e04f044ed6](https://linux-hardware.org/?probe=e04f044ed6) | Feb 08, 2021 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [62247a6f15](https://linux-hardware.org/?probe=62247a6f15) | Feb 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [93004b8e8f](https://linux-hardware.org/?probe=93004b8e8f) | Feb 07, 2021 |
| Nvidia        | Tegra                       | Soc         | [ed22dcb6c2](https://linux-hardware.org/?probe=ed22dcb6c2) | Feb 07, 2021 |
| ASRock        | C226 WS                     | Desktop     | [ea5438d5ff](https://linux-hardware.org/?probe=ea5438d5ff) | Feb 06, 2021 |
| Dell          | G3 3779                     | Notebook    | [363e754d51](https://linux-hardware.org/?probe=363e754d51) | Feb 06, 2021 |
| Compal        | PBL10                       | Notebook    | [5cf67578d7](https://linux-hardware.org/?probe=5cf67578d7) | Feb 04, 2021 |
| Compal        | PBL10                       | Notebook    | [a20e9d9588](https://linux-hardware.org/?probe=a20e9d9588) | Feb 04, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [3271c9fcf1](https://linux-hardware.org/?probe=3271c9fcf1) | Feb 04, 2021 |
| MSI           | B350M MORTAR                | Desktop     | [6b0f675fd7](https://linux-hardware.org/?probe=6b0f675fd7) | Feb 04, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [d629981b18](https://linux-hardware.org/?probe=d629981b18) | Feb 03, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [59683af6d8](https://linux-hardware.org/?probe=59683af6d8) | Feb 03, 2021 |
| Gigabyte      | H310M H                     | Desktop     | [0ab01adfd8](https://linux-hardware.org/?probe=0ab01adfd8) | Feb 02, 2021 |
| HP            | ProBook 6550b               | Notebook    | [b41bf411ae](https://linux-hardware.org/?probe=b41bf411ae) | Jan 31, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [002dbe9174](https://linux-hardware.org/?probe=002dbe9174) | Jan 30, 2021 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [e58a22a75a](https://linux-hardware.org/?probe=e58a22a75a) | Jan 30, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [b3c1b54fb7](https://linux-hardware.org/?probe=b3c1b54fb7) | Jan 30, 2021 |
| HP            | ProBook 4510s               | Notebook    | [90108b85c2](https://linux-hardware.org/?probe=90108b85c2) | Jan 28, 2021 |
| Lenovo        | ThinkPad T420s 41732AU      | Notebook    | [0f7cf25542](https://linux-hardware.org/?probe=0f7cf25542) | Jan 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | Notebook    | [407c5fa547](https://linux-hardware.org/?probe=407c5fa547) | Jan 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | Notebook    | [76ed8917b5](https://linux-hardware.org/?probe=76ed8917b5) | Jan 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [90cc726402](https://linux-hardware.org/?probe=90cc726402) | Jan 27, 2021 |
| Dell          | 0GM819                      | Desktop     | [a58974e595](https://linux-hardware.org/?probe=a58974e595) | Jan 24, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [b45017b059](https://linux-hardware.org/?probe=b45017b059) | Jan 24, 2021 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF       | Desktop     | [f8fdb6f4b3](https://linux-hardware.org/?probe=f8fdb6f4b3) | Jan 24, 2021 |
| Intel         | DX48BT2 AAE26191-206        | Desktop     | [fd2f76fd1e](https://linux-hardware.org/?probe=fd2f76fd1e) | Jan 22, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [bdfeee2839](https://linux-hardware.org/?probe=bdfeee2839) | Jan 21, 2021 |
| HP            | ProBook 4510s               | Notebook    | [249c4254b8](https://linux-hardware.org/?probe=249c4254b8) | Jan 20, 2021 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [5b01cff11a](https://linux-hardware.org/?probe=5b01cff11a) | Jan 20, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [4b06224bf0](https://linux-hardware.org/?probe=4b06224bf0) | Jan 19, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a69186697c](https://linux-hardware.org/?probe=a69186697c) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [f34a9b325b](https://linux-hardware.org/?probe=f34a9b325b) | Jan 18, 2021 |
| Dell          | Latitude D420               | Notebook    | [8cea54aabf](https://linux-hardware.org/?probe=8cea54aabf) | Jan 17, 2021 |
| HP            | 0984h                       | Desktop     | [5bb1bf036f](https://linux-hardware.org/?probe=5bb1bf036f) | Jan 16, 2021 |
| Intel         | S3000AHLX D40858-208        | Desktop     | [8508696f16](https://linux-hardware.org/?probe=8508696f16) | Jan 16, 2021 |
| Itautec       | Infoway w7430               | Notebook    | [de4a2289ae](https://linux-hardware.org/?probe=de4a2289ae) | Jan 14, 2021 |
| Lenovo        | ThinkPad E14 20RAS0BY00     | Notebook    | [0178b6f04d](https://linux-hardware.org/?probe=0178b6f04d) | Jan 13, 2021 |
| Lenovo        | ThinkPad R400 7440CL2       | Notebook    | [d9662809ae](https://linux-hardware.org/?probe=d9662809ae) | Jan 13, 2021 |
| Lenovo        | ThinkPad R400 7440CL2       | Notebook    | [2b357b7a62](https://linux-hardware.org/?probe=2b357b7a62) | Jan 13, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6b9e20079b](https://linux-hardware.org/?probe=6b9e20079b) | Jan 13, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [cbbb4ea83c](https://linux-hardware.org/?probe=cbbb4ea83c) | Jan 13, 2021 |
| HP            | ProBook 4520s               | Notebook    | [46240490b5](https://linux-hardware.org/?probe=46240490b5) | Jan 12, 2021 |
| ECS           | Nettle2                     | Desktop     | [53d1c62d82](https://linux-hardware.org/?probe=53d1c62d82) | Jan 10, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a8eaaf47b0](https://linux-hardware.org/?probe=a8eaaf47b0) | Jan 10, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [601e76c662](https://linux-hardware.org/?probe=601e76c662) | Jan 09, 2021 |
| Dell          | Inspiron N5030              | Notebook    | [e7b2580e2b](https://linux-hardware.org/?probe=e7b2580e2b) | Jan 09, 2021 |
| HP            | ProBook 6550b               | Notebook    | [af743262a6](https://linux-hardware.org/?probe=af743262a6) | Jan 09, 2021 |
| Dell          | Inspiron N5030              | Notebook    | [299420cc02](https://linux-hardware.org/?probe=299420cc02) | Jan 09, 2021 |
| HP            | 510 Notebook PC (RU964AA... | Notebook    | [fe8a07348f](https://linux-hardware.org/?probe=fe8a07348f) | Jan 08, 2021 |
| Lenovo        | ThinkCentre M58p 6137B28    | Desktop     | [62fa506663](https://linux-hardware.org/?probe=62fa506663) | Jan 08, 2021 |
| HP            | 510 Notebook PC (RU964AA... | Notebook    | [86ef2cddd1](https://linux-hardware.org/?probe=86ef2cddd1) | Jan 08, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [7e08feac35](https://linux-hardware.org/?probe=7e08feac35) | Jan 07, 2021 |
| ASRock        | C226 WS                     | Desktop     | [476dfd5e9b](https://linux-hardware.org/?probe=476dfd5e9b) | Jan 05, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c7b7c0f082](https://linux-hardware.org/?probe=c7b7c0f082) | Jan 04, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [31844373c2](https://linux-hardware.org/?probe=31844373c2) | Jan 03, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [ad1bd88f4e](https://linux-hardware.org/?probe=ad1bd88f4e) | Jan 03, 2021 |
| Packard Be... | EasyNote TK36               | Notebook    | [d5aeb5be31](https://linux-hardware.org/?probe=d5aeb5be31) | Jan 02, 2021 |
| IBM           | 8114W15                     | Desktop     | [a0b58efd51](https://linux-hardware.org/?probe=a0b58efd51) | Jan 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [cec4fcbdea](https://linux-hardware.org/?probe=cec4fcbdea) | Jan 02, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [da33e577bf](https://linux-hardware.org/?probe=da33e577bf) | Jan 02, 2021 |
| Packard Be... | EasyNote TK36               | Notebook    | [43b59e2a0c](https://linux-hardware.org/?probe=43b59e2a0c) | Jan 02, 2021 |
| NEC Comput... | Packard Bell EasyNote       | Notebook    | [c0b37bc3c3](https://linux-hardware.org/?probe=c0b37bc3c3) | Jan 02, 2021 |
| NEC Comput... | Packard Bell EasyNote       | Notebook    | [953e9fbfda](https://linux-hardware.org/?probe=953e9fbfda) | Jan 02, 2021 |
| Nvidia        | Tegra                       | Soc         | [df9a0f37eb](https://linux-hardware.org/?probe=df9a0f37eb) | Jan 01, 2021 |
| Nvidia        | Tegra                       | Soc         | [fb4f881e78](https://linux-hardware.org/?probe=fb4f881e78) | Jan 01, 2021 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [a7fc4110ab](https://linux-hardware.org/?probe=a7fc4110ab) | Jan 01, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [3ccf619144](https://linux-hardware.org/?probe=3ccf619144) | Dec 31, 2020 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [d7fd1a7a8d](https://linux-hardware.org/?probe=d7fd1a7a8d) | Dec 31, 2020 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [dee2ede561](https://linux-hardware.org/?probe=dee2ede561) | Dec 31, 2020 |
| ASRock        | Z390 Taichi                 | Desktop     | [9b2f7341f2](https://linux-hardware.org/?probe=9b2f7341f2) | Dec 30, 2020 |
| Sony          | VGN-Z21MN_B                 | Notebook    | [db832121d8](https://linux-hardware.org/?probe=db832121d8) | Dec 30, 2020 |
| Acer          | Swift SF314-55G             | Notebook    | [6f94a2e40c](https://linux-hardware.org/?probe=6f94a2e40c) | Dec 30, 2020 |
| ASUSTek       | K53U                        | Notebook    | [92d200393a](https://linux-hardware.org/?probe=92d200393a) | Dec 29, 2020 |
| ASUSTek       | K53U                        | Notebook    | [99610b1976](https://linux-hardware.org/?probe=99610b1976) | Dec 29, 2020 |
| ASUSTek       | P5N73-AM                    | Desktop     | [47d2381c33](https://linux-hardware.org/?probe=47d2381c33) | Dec 29, 2020 |
| Advent        | Verona                      | Notebook    | [3cb47bf21d](https://linux-hardware.org/?probe=3cb47bf21d) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [c3f9fc25d4](https://linux-hardware.org/?probe=c3f9fc25d4) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [dbc2669fc0](https://linux-hardware.org/?probe=dbc2669fc0) | Dec 28, 2020 |
| ASUSTek       | P8Z68-V                     | Desktop     | [3a553168b5](https://linux-hardware.org/?probe=3a553168b5) | Dec 27, 2020 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [cd038bd21f](https://linux-hardware.org/?probe=cd038bd21f) | Dec 26, 2020 |
| Lenovo        | ThinkPad L450 20DT001DUS    | Notebook    | [dd815dfd6a](https://linux-hardware.org/?probe=dd815dfd6a) | Dec 25, 2020 |
| HP            | ProLiant DL360p Gen8        | Server      | [3f6ebb3247](https://linux-hardware.org/?probe=3f6ebb3247) | Dec 23, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [4a85297f60](https://linux-hardware.org/?probe=4a85297f60) | Dec 23, 2020 |
| Samsung       | R530/R730                   | Notebook    | [397b075add](https://linux-hardware.org/?probe=397b075add) | Dec 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [e99e06a590](https://linux-hardware.org/?probe=e99e06a590) | Dec 23, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [bb04468cdd](https://linux-hardware.org/?probe=bb04468cdd) | Dec 22, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [2d64eaea6f](https://linux-hardware.org/?probe=2d64eaea6f) | Dec 22, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [f9cf955187](https://linux-hardware.org/?probe=f9cf955187) | Dec 22, 2020 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [b82c30b180](https://linux-hardware.org/?probe=b82c30b180) | Dec 21, 2020 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [289dc71948](https://linux-hardware.org/?probe=289dc71948) | Dec 21, 2020 |
| MSI           | 870A-G54                    | Desktop     | [479ee62f9f](https://linux-hardware.org/?probe=479ee62f9f) | Dec 21, 2020 |
| Dell          | 0TP412                      | Desktop     | [30196a7c77](https://linux-hardware.org/?probe=30196a7c77) | Dec 21, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [57a12f2fb0](https://linux-hardware.org/?probe=57a12f2fb0) | Dec 21, 2020 |
| ASUSTek       | UX305FA                     | Notebook    | [01059cbee4](https://linux-hardware.org/?probe=01059cbee4) | Dec 20, 2020 |
| Dell          | 0N867P A01                  | Desktop     | [1975eb324e](https://linux-hardware.org/?probe=1975eb324e) | Dec 19, 2020 |
| Dell          | Precision 5540              | Notebook    | [eea500d1e4](https://linux-hardware.org/?probe=eea500d1e4) | Dec 18, 2020 |
| Dell          | Precision 5540              | Notebook    | [0e06bc0dae](https://linux-hardware.org/?probe=0e06bc0dae) | Dec 18, 2020 |
| Dell          | Inspiron 910                | Notebook    | [87ff58828e](https://linux-hardware.org/?probe=87ff58828e) | Dec 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [73fa61c233](https://linux-hardware.org/?probe=73fa61c233) | Dec 15, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [5a179cb315](https://linux-hardware.org/?probe=5a179cb315) | Dec 14, 2020 |
| Dell          | 0N867P A01                  | Desktop     | [b8d37533eb](https://linux-hardware.org/?probe=b8d37533eb) | Dec 14, 2020 |
| Lenovo        | ThinkPad X301 4057W3A       | Notebook    | [ca140372c9](https://linux-hardware.org/?probe=ca140372c9) | Dec 13, 2020 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [d942ed05b5](https://linux-hardware.org/?probe=d942ed05b5) | Dec 13, 2020 |
| Dell          | 0TP412                      | Desktop     | [9b3c5cdcaa](https://linux-hardware.org/?probe=9b3c5cdcaa) | Dec 13, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [941a457fa1](https://linux-hardware.org/?probe=941a457fa1) | Dec 12, 2020 |
| Dell          | 0TP412                      | Desktop     | [d3683dc02c](https://linux-hardware.org/?probe=d3683dc02c) | Dec 12, 2020 |
| Gigabyte      | EX58-UD5                    | Desktop     | [846fea1d93](https://linux-hardware.org/?probe=846fea1d93) | Dec 11, 2020 |
| Toshiba       | Portable PC                 | Notebook    | [9aec36b4b9](https://linux-hardware.org/?probe=9aec36b4b9) | Dec 11, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fb4783aeba](https://linux-hardware.org/?probe=fb4783aeba) | Dec 10, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [1bd7a01295](https://linux-hardware.org/?probe=1bd7a01295) | Dec 09, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [59bb1dc077](https://linux-hardware.org/?probe=59bb1dc077) | Dec 09, 2020 |
| Lenovo        | ThinkPad T410 2522A92       | Notebook    | [dd93682c3c](https://linux-hardware.org/?probe=dd93682c3c) | Dec 09, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [d9258de65c](https://linux-hardware.org/?probe=d9258de65c) | Dec 09, 2020 |
| Acer          | Extensa 2519                | Notebook    | [b2ccfa56ae](https://linux-hardware.org/?probe=b2ccfa56ae) | Dec 08, 2020 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [910a8c0514](https://linux-hardware.org/?probe=910a8c0514) | Dec 08, 2020 |
| Acer          | Extensa 2519                | Notebook    | [2e71470fef](https://linux-hardware.org/?probe=2e71470fef) | Dec 08, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [d08e11665d](https://linux-hardware.org/?probe=d08e11665d) | Dec 07, 2020 |
| Dell          | OptiPlex 3010               | Desktop     | [41dabae1fc](https://linux-hardware.org/?probe=41dabae1fc) | Dec 07, 2020 |
| Dell          | 0TP412                      | Desktop     | [9fcc10bab8](https://linux-hardware.org/?probe=9fcc10bab8) | Dec 06, 2020 |
| Acer          | TravelMate 5530             | Notebook    | [0e494e91b0](https://linux-hardware.org/?probe=0e494e91b0) | Dec 06, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [2a527149d7](https://linux-hardware.org/?probe=2a527149d7) | Dec 03, 2020 |
| ASUSTek       | EMERY                       | Desktop     | [1b9cd9a176](https://linux-hardware.org/?probe=1b9cd9a176) | Dec 03, 2020 |
| Dell          | Latitude 7480               | Notebook    | [a04feb1736](https://linux-hardware.org/?probe=a04feb1736) | Dec 01, 2020 |
| Acer          | Aspire VN7-591G             | Notebook    | [a30c2da246](https://linux-hardware.org/?probe=a30c2da246) | Nov 26, 2020 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [7f7531aadb](https://linux-hardware.org/?probe=7f7531aadb) | Nov 25, 2020 |
| Positivo      | P5VD2-MX                    | Desktop     | [b2a60399bd](https://linux-hardware.org/?probe=b2a60399bd) | Nov 25, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | Notebook    | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [9464486b83](https://linux-hardware.org/?probe=9464486b83) | Nov 22, 2020 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [dd831ee6ef](https://linux-hardware.org/?probe=dd831ee6ef) | Nov 22, 2020 |
| ASUSTek       | M4A785-M                    | Desktop     | [a245d69e45](https://linux-hardware.org/?probe=a245d69e45) | Nov 22, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [1817281db6](https://linux-hardware.org/?probe=1817281db6) | Nov 21, 2020 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [2b39f0d95c](https://linux-hardware.org/?probe=2b39f0d95c) | Nov 20, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [23269890ea](https://linux-hardware.org/?probe=23269890ea) | Nov 20, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [3ca88d3de2](https://linux-hardware.org/?probe=3ca88d3de2) | Nov 19, 2020 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [cc2deb2f07](https://linux-hardware.org/?probe=cc2deb2f07) | Nov 19, 2020 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2385da6b14](https://linux-hardware.org/?probe=2385da6b14) | Nov 18, 2020 |
| Dell          | 0PU052                      | Desktop     | [17818ae6d5](https://linux-hardware.org/?probe=17818ae6d5) | Nov 18, 2020 |
| HP            | Pavilion dv6                | Notebook    | [ee09691432](https://linux-hardware.org/?probe=ee09691432) | Nov 18, 2020 |
| Nvidia        | Tegra                       | Soc         | [d03c207bf2](https://linux-hardware.org/?probe=d03c207bf2) | Nov 18, 2020 |
| Nvidia        | Tegra                       | Soc         | [df2ccd3ed4](https://linux-hardware.org/?probe=df2ccd3ed4) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Timi          | TM1701                      | Notebook    | [ee53272b88](https://linux-hardware.org/?probe=ee53272b88) | Nov 14, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [7867789c72](https://linux-hardware.org/?probe=7867789c72) | Nov 13, 2020 |
| HP            | ENVY 15                     | Notebook    | [fb33289aed](https://linux-hardware.org/?probe=fb33289aed) | Nov 13, 2020 |
| ASUSTek       | UL30VT                      | Notebook    | [d5921db40a](https://linux-hardware.org/?probe=d5921db40a) | Nov 12, 2020 |
| ASUSTek       | N76VB                       | Notebook    | [be1a7a1846](https://linux-hardware.org/?probe=be1a7a1846) | Nov 11, 2020 |
| Dell          | 00TD00 A00                  | All in one  | [e311c8e66c](https://linux-hardware.org/?probe=e311c8e66c) | Nov 11, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b86dbcfe65](https://linux-hardware.org/?probe=b86dbcfe65) | Nov 11, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5ccb6559a1](https://linux-hardware.org/?probe=5ccb6559a1) | Nov 11, 2020 |
| HP            | ZBook 17 G3                 | Notebook    | [6edcc11c0e](https://linux-hardware.org/?probe=6edcc11c0e) | Nov 11, 2020 |
| ASRock        | 880GM-LE FX                 | Desktop     | [c16ef7ddf0](https://linux-hardware.org/?probe=c16ef7ddf0) | Nov 09, 2020 |
| HP            | ProBook 640 G2              | Notebook    | [239d1a4663](https://linux-hardware.org/?probe=239d1a4663) | Nov 09, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [78c640d460](https://linux-hardware.org/?probe=78c640d460) | Nov 09, 2020 |
| ASUSTek       | H110M-K D3                  | Desktop     | [114c634725](https://linux-hardware.org/?probe=114c634725) | Nov 09, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [35d9993cdc](https://linux-hardware.org/?probe=35d9993cdc) | Nov 08, 2020 |
| Dell          | Latitude XT2                | Notebook    | [8fba8f46db](https://linux-hardware.org/?probe=8fba8f46db) | Nov 08, 2020 |
| MSI           | 870A-G54                    | Desktop     | [d14df17124](https://linux-hardware.org/?probe=d14df17124) | Nov 08, 2020 |
| MSI           | H81M-E33                    | Desktop     | [bb70f807c6](https://linux-hardware.org/?probe=bb70f807c6) | Nov 08, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [e349021135](https://linux-hardware.org/?probe=e349021135) | Nov 08, 2020 |
| ASUSTek       | P5G41-M                     | Desktop     | [7bdeab772b](https://linux-hardware.org/?probe=7bdeab772b) | Nov 08, 2020 |
| Toshiba       | Satellite A505              | Notebook    | [d76aa15e2c](https://linux-hardware.org/?probe=d76aa15e2c) | Nov 07, 2020 |
| Dell          | 0PU052                      | Desktop     | [3179b2018f](https://linux-hardware.org/?probe=3179b2018f) | Nov 04, 2020 |
| Lenovo        | ThinkPad X301 4057AL1       | Notebook    | [b52207277d](https://linux-hardware.org/?probe=b52207277d) | Nov 04, 2020 |
| ASUSTek       | X453SA                      | Notebook    | [1bb7c5cfe5](https://linux-hardware.org/?probe=1bb7c5cfe5) | Nov 03, 2020 |
| Lenovo        | ThinkPad T60 1951AH4        | Notebook    | [f23ac90595](https://linux-hardware.org/?probe=f23ac90595) | Nov 03, 2020 |
| Lenovo        | ThinkPad T60 1951AH4        | Notebook    | [52d6742358](https://linux-hardware.org/?probe=52d6742358) | Nov 03, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [cdc24d2269](https://linux-hardware.org/?probe=cdc24d2269) | Nov 02, 2020 |
| ASUSTek       | T101MT                      | Notebook    | [5842dd654b](https://linux-hardware.org/?probe=5842dd654b) | Nov 01, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [16e2be9f0f](https://linux-hardware.org/?probe=16e2be9f0f) | Nov 01, 2020 |
| Acer          | Aspire XC-704               | Desktop     | [b4b6521607](https://linux-hardware.org/?probe=b4b6521607) | Nov 01, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [f8fa4c9c31](https://linux-hardware.org/?probe=f8fa4c9c31) | Nov 01, 2020 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [941da7c937](https://linux-hardware.org/?probe=941da7c937) | Oct 30, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [a4caa7de36](https://linux-hardware.org/?probe=a4caa7de36) | Oct 30, 2020 |
| Biostar       | J1800MH2                    | Desktop     | [96c321390a](https://linux-hardware.org/?probe=96c321390a) | Oct 30, 2020 |
| ASRock        | B150M-DVS R2.0              | Desktop     | [fe0d972e21](https://linux-hardware.org/?probe=fe0d972e21) | Oct 29, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [7184b7e890](https://linux-hardware.org/?probe=7184b7e890) | Oct 29, 2020 |
| Positivo      | POS-PIH81DI                 | Desktop     | [92e06f833e](https://linux-hardware.org/?probe=92e06f833e) | Oct 28, 2020 |
| Dell          | Vostro 1000                 | Notebook    | [05849c4d22](https://linux-hardware.org/?probe=05849c4d22) | Oct 28, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [8ed7fab224](https://linux-hardware.org/?probe=8ed7fab224) | Oct 27, 2020 |
| Unknown       | Unknown                     | Desktop     | [01e13eca3a](https://linux-hardware.org/?probe=01e13eca3a) | Oct 27, 2020 |
| Dell          | Vostro 1000                 | Notebook    | [f55377552a](https://linux-hardware.org/?probe=f55377552a) | Oct 27, 2020 |
| Dell          | Vostro 1400                 | Notebook    | [e27c854a39](https://linux-hardware.org/?probe=e27c854a39) | Oct 27, 2020 |
| Dell          | Vostro 1400                 | Notebook    | [102eafaf81](https://linux-hardware.org/?probe=102eafaf81) | Oct 27, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [28db491892](https://linux-hardware.org/?probe=28db491892) | Oct 26, 2020 |
| HUAWEI        | KPL-W0X                     | Notebook    | [cf48a4f7b0](https://linux-hardware.org/?probe=cf48a4f7b0) | Oct 26, 2020 |
| Lenovo        | ThinkPad T570 20H9CTO1WW    | Notebook    | [c8f0e5e6fa](https://linux-hardware.org/?probe=c8f0e5e6fa) | Oct 26, 2020 |
| Gigabyte      | P35-DS3R                    | Desktop     | [1c154e0968](https://linux-hardware.org/?probe=1c154e0968) | Oct 24, 2020 |
| Gigabyte      | P35-DS3R                    | Desktop     | [a8d7e7913f](https://linux-hardware.org/?probe=a8d7e7913f) | Oct 24, 2020 |
| Intel         | D915GAV AAC64134-400        | Desktop     | [73b829201a](https://linux-hardware.org/?probe=73b829201a) | Oct 24, 2020 |
| Intel         | D915GAV AAC64134-400        | Desktop     | [5df08a35e8](https://linux-hardware.org/?probe=5df08a35e8) | Oct 24, 2020 |
| ASUSTek       | K55VJ                       | Notebook    | [53e73c71d1](https://linux-hardware.org/?probe=53e73c71d1) | Oct 23, 2020 |
| ASUSTek       | K55VJ                       | Notebook    | [5351f3ac0f](https://linux-hardware.org/?probe=5351f3ac0f) | Oct 23, 2020 |
| Apple         | MacBookPro1,1               | Notebook    | [2a6c327452](https://linux-hardware.org/?probe=2a6c327452) | Oct 23, 2020 |
| Nvidia        | Tegra                       | Soc         | [ef24e8c128](https://linux-hardware.org/?probe=ef24e8c128) | Oct 23, 2020 |
| Intel         | B75                         | Desktop     | [c593a50d39](https://linux-hardware.org/?probe=c593a50d39) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3a4ce2fd2](https://linux-hardware.org/?probe=d3a4ce2fd2) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3bdc7437e](https://linux-hardware.org/?probe=d3bdc7437e) | Oct 22, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [0ea98ac7d2](https://linux-hardware.org/?probe=0ea98ac7d2) | Oct 22, 2020 |
| Dell          | XPS 13 9310                 | Notebook    | [ca9da289db](https://linux-hardware.org/?probe=ca9da289db) | Oct 19, 2020 |
| Lenovo        | ThinkPad T60 1952EB4        | Notebook    | [62681b5680](https://linux-hardware.org/?probe=62681b5680) | Oct 19, 2020 |
| Intel         | JV10_CS                     | Notebook    | [8c95378d1f](https://linux-hardware.org/?probe=8c95378d1f) | Oct 18, 2020 |
| ASUSTek       | K53SJ                       | Notebook    | [5635f2d532](https://linux-hardware.org/?probe=5635f2d532) | Oct 16, 2020 |
| Nvidia        | Tegra                       | Soc         | [9b157b83a5](https://linux-hardware.org/?probe=9b157b83a5) | Oct 15, 2020 |
| LG Electro... | P430-K.BE48P1               | Notebook    | [366bd09248](https://linux-hardware.org/?probe=366bd09248) | Oct 15, 2020 |
| Acer          | Aspire A515-51              | Notebook    | [a92208292e](https://linux-hardware.org/?probe=a92208292e) | Oct 13, 2020 |
| Lenovo        | Z710 20250                  | Notebook    | [c864fda22e](https://linux-hardware.org/?probe=c864fda22e) | Oct 13, 2020 |
| Acer          | Swift SF514-53T             | Notebook    | [cfac356307](https://linux-hardware.org/?probe=cfac356307) | Oct 13, 2020 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [08ebefc47e](https://linux-hardware.org/?probe=08ebefc47e) | Oct 12, 2020 |
| Nvidia        | Tegra                       | Soc         | [0a8ada10b5](https://linux-hardware.org/?probe=0a8ada10b5) | Oct 12, 2020 |
| HP            | 3029h                       | Desktop     | [5156424aad](https://linux-hardware.org/?probe=5156424aad) | Oct 11, 2020 |
| ASUSTek       | G11CB                       | Desktop     | [9fafa60d0b](https://linux-hardware.org/?probe=9fafa60d0b) | Oct 11, 2020 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [2971e5263a](https://linux-hardware.org/?probe=2971e5263a) | Oct 10, 2020 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [1500397c93](https://linux-hardware.org/?probe=1500397c93) | Oct 10, 2020 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a5dff2c638](https://linux-hardware.org/?probe=a5dff2c638) | Oct 10, 2020 |
| Dell          | 0DT031 A00                  | Desktop     | [2b5dd78a1d](https://linux-hardware.org/?probe=2b5dd78a1d) | Oct 09, 2020 |
| HP            | Compaq Presario A900        | Notebook    | [352f29d57c](https://linux-hardware.org/?probe=352f29d57c) | Oct 08, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [b8d157004d](https://linux-hardware.org/?probe=b8d157004d) | Oct 08, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [615c1db3f0](https://linux-hardware.org/?probe=615c1db3f0) | Oct 08, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [80f6028032](https://linux-hardware.org/?probe=80f6028032) | Oct 07, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a9c5c82482](https://linux-hardware.org/?probe=a9c5c82482) | Oct 07, 2020 |
| Apple         | MacBookPro1,1               | Notebook    | [03e2d99987](https://linux-hardware.org/?probe=03e2d99987) | Oct 07, 2020 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [2914e9b28e](https://linux-hardware.org/?probe=2914e9b28e) | Oct 06, 2020 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [e6221b2a9c](https://linux-hardware.org/?probe=e6221b2a9c) | Oct 06, 2020 |
| Toshiba       | Satellite A135              | Notebook    | [872e375f7d](https://linux-hardware.org/?probe=872e375f7d) | Oct 06, 2020 |
| Toshiba       | Satellite A135              | Notebook    | [51279c1662](https://linux-hardware.org/?probe=51279c1662) | Oct 06, 2020 |
| Dell          | G5 5590                     | Notebook    | [30d1a3f785](https://linux-hardware.org/?probe=30d1a3f785) | Oct 05, 2020 |
| HP            | Mini 210-1000               | Notebook    | [ad7e5e722f](https://linux-hardware.org/?probe=ad7e5e722f) | Oct 05, 2020 |
| Dell          | Studio 1537                 | Notebook    | [fb2730ecf5](https://linux-hardware.org/?probe=fb2730ecf5) | Oct 05, 2020 |
| ASUSTek       | P5VD2-VM SE                 | Desktop     | [0316df3f18](https://linux-hardware.org/?probe=0316df3f18) | Oct 04, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | Notebook    | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| Dell          | 00FKMJ A00                  | Desktop     | [516d723c41](https://linux-hardware.org/?probe=516d723c41) | Oct 04, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [fe2c088ea6](https://linux-hardware.org/?probe=fe2c088ea6) | Oct 03, 2020 |
| ASUSTek       | P5VD2-VM SE                 | Desktop     | [c4db0a9703](https://linux-hardware.org/?probe=c4db0a9703) | Oct 03, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [e4175eb759](https://linux-hardware.org/?probe=e4175eb759) | Oct 03, 2020 |
| LG Electro... | X120-H.CSVPG                | Notebook    | [548d6618e3](https://linux-hardware.org/?probe=548d6618e3) | Oct 02, 2020 |
| LG Electro... | X120-H.CSVPG                | Notebook    | [4853246cce](https://linux-hardware.org/?probe=4853246cce) | Oct 02, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [2b417363dd](https://linux-hardware.org/?probe=2b417363dd) | Oct 02, 2020 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [0f4425d89a](https://linux-hardware.org/?probe=0f4425d89a) | Oct 02, 2020 |
| ASRock        | N68-S                       | Desktop     | [e867c049a3](https://linux-hardware.org/?probe=e867c049a3) | Sep 30, 2020 |
| ASRock        | N68-S                       | Desktop     | [5e39fce3e2](https://linux-hardware.org/?probe=5e39fce3e2) | Sep 30, 2020 |
| HP            | 3048h                       | Desktop     | [038b6a6740](https://linux-hardware.org/?probe=038b6a6740) | Sep 30, 2020 |
| HP            | ENVY TS m7                  | Notebook    | [1e21fdd484](https://linux-hardware.org/?probe=1e21fdd484) | Sep 30, 2020 |
| Dell          | Latitude E7450              | Notebook    | [7df34be11f](https://linux-hardware.org/?probe=7df34be11f) | Sep 29, 2020 |
| Dell          | Latitude E7450              | Notebook    | [8149a50311](https://linux-hardware.org/?probe=8149a50311) | Sep 29, 2020 |
| Samsung       | R610                        | Notebook    | [6d82e49339](https://linux-hardware.org/?probe=6d82e49339) | Sep 29, 2020 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [8616e28654](https://linux-hardware.org/?probe=8616e28654) | Sep 29, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [cb88d55f32](https://linux-hardware.org/?probe=cb88d55f32) | Sep 29, 2020 |
| Penguin Co... | Altus 1800i                 | Desktop     | [2d9133376a](https://linux-hardware.org/?probe=2d9133376a) | Sep 28, 2020 |
| Samsung       | R610                        | Notebook    | [e8416ebd86](https://linux-hardware.org/?probe=e8416ebd86) | Sep 28, 2020 |
| Dell          | XPS 13 9343                 | Notebook    | [98a248903d](https://linux-hardware.org/?probe=98a248903d) | Sep 28, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [2a0e9530f3](https://linux-hardware.org/?probe=2a0e9530f3) | Sep 28, 2020 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [a039ec6724](https://linux-hardware.org/?probe=a039ec6724) | Sep 28, 2020 |
| Apple         | MacBook2,1                  | Notebook    | [a11af3313e](https://linux-hardware.org/?probe=a11af3313e) | Sep 28, 2020 |
| Itautec       | Infoway                     | Notebook    | [7208bdf264](https://linux-hardware.org/?probe=7208bdf264) | Sep 28, 2020 |
| Dell          | Inspiron 7560               | Notebook    | [e5c43c8206](https://linux-hardware.org/?probe=e5c43c8206) | Sep 28, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [32556e96bf](https://linux-hardware.org/?probe=32556e96bf) | Sep 27, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [7176092b12](https://linux-hardware.org/?probe=7176092b12) | Sep 27, 2020 |
| Toshiba       | Satellite L755              | Notebook    | [32e663a3d9](https://linux-hardware.org/?probe=32e663a3d9) | Sep 27, 2020 |
| Dell          | 0JC474                      | Desktop     | [e26ccdd878](https://linux-hardware.org/?probe=e26ccdd878) | Sep 26, 2020 |
| HP            | EliteBook 755 G5            | Notebook    | [48467304f0](https://linux-hardware.org/?probe=48467304f0) | Sep 26, 2020 |
| HP            | EliteBook 755 G5            | Notebook    | [cee814d244](https://linux-hardware.org/?probe=cee814d244) | Sep 26, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [a9c8f7c921](https://linux-hardware.org/?probe=a9c8f7c921) | Sep 26, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | Notebook    | [cc52f7719c](https://linux-hardware.org/?probe=cc52f7719c) | Sep 26, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | Notebook    | [48212a4f99](https://linux-hardware.org/?probe=48212a4f99) | Sep 26, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [6790f8d26f](https://linux-hardware.org/?probe=6790f8d26f) | Sep 24, 2020 |
| Dell          | G3 3500                     | Notebook    | [387113ea62](https://linux-hardware.org/?probe=387113ea62) | Sep 24, 2020 |
| MSI           | Creator 15M A10SD           | Notebook    | [9d39878ae6](https://linux-hardware.org/?probe=9d39878ae6) | Sep 23, 2020 |
| MSI           | MS-7204                     | Desktop     | [56ffd4a54c](https://linux-hardware.org/?probe=56ffd4a54c) | Sep 23, 2020 |
| Dell          | Precision 3520              | Notebook    | [62f622c78a](https://linux-hardware.org/?probe=62f622c78a) | Sep 23, 2020 |
| Dell          | G3 3500                     | Notebook    | [9c5bcc318d](https://linux-hardware.org/?probe=9c5bcc318d) | Sep 22, 2020 |
| Dell          | G3 3500                     | Notebook    | [a2e67cdcc9](https://linux-hardware.org/?probe=a2e67cdcc9) | Sep 22, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [bab729c6d0](https://linux-hardware.org/?probe=bab729c6d0) | Sep 22, 2020 |
| Lenovo        | ThinkPad R61e 7650E8G       | Notebook    | [900df41d5f](https://linux-hardware.org/?probe=900df41d5f) | Sep 21, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [009f06d707](https://linux-hardware.org/?probe=009f06d707) | Sep 20, 2020 |
| HP            | ProBook 6470b               | Notebook    | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| ASUSTek       | F7F                         | Notebook    | [0ffb1837f3](https://linux-hardware.org/?probe=0ffb1837f3) | Sep 20, 2020 |
| Positivo      | Mobile                      | Notebook    | [c6539534cd](https://linux-hardware.org/?probe=c6539534cd) | Sep 19, 2020 |
| HP            | Pavilion ZV6000 (PZ987EA... | Notebook    | [1b21bd3742](https://linux-hardware.org/?probe=1b21bd3742) | Sep 17, 2020 |
| Toshiba       | Satellite L755              | Notebook    | [e702908245](https://linux-hardware.org/?probe=e702908245) | Sep 17, 2020 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [27dd15deec](https://linux-hardware.org/?probe=27dd15deec) | Sep 17, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [6261260ac9](https://linux-hardware.org/?probe=6261260ac9) | Sep 17, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [cfbf78b903](https://linux-hardware.org/?probe=cfbf78b903) | Sep 17, 2020 |
| Acer          | Aspire M3-481               | Notebook    | [55949e4f33](https://linux-hardware.org/?probe=55949e4f33) | Sep 17, 2020 |
| Unknown       | Unknown                     | Desktop     | [67ad062e28](https://linux-hardware.org/?probe=67ad062e28) | Sep 17, 2020 |
| Unknown       | Unknown                     | Desktop     | [0bc4949d0e](https://linux-hardware.org/?probe=0bc4949d0e) | Sep 17, 2020 |
| ASRock        | A55M-HVS                    | Desktop     | [dd77b0b202](https://linux-hardware.org/?probe=dd77b0b202) | Sep 16, 2020 |
| Dell          | Inspiron 3583               | Notebook    | [906a07309d](https://linux-hardware.org/?probe=906a07309d) | Sep 16, 2020 |
| Dell          | 0GXM1W A02                  | Desktop     | [228bbe0e9b](https://linux-hardware.org/?probe=228bbe0e9b) | Sep 16, 2020 |
| Acer          | Aspire 8735                 | Notebook    | [a2a7136928](https://linux-hardware.org/?probe=a2a7136928) | Sep 16, 2020 |
| Acer          | Aspire 8735                 | Notebook    | [7b66b4dc9f](https://linux-hardware.org/?probe=7b66b4dc9f) | Sep 16, 2020 |
| HP            | 304Ah                       | Desktop     | [5acd57b9db](https://linux-hardware.org/?probe=5acd57b9db) | Sep 15, 2020 |
| Fujitsu Si... | P5LD2-FM-DH-VP              | Desktop     | [dae3374f32](https://linux-hardware.org/?probe=dae3374f32) | Sep 14, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [d84e4c8838](https://linux-hardware.org/?probe=d84e4c8838) | Sep 13, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [290aad9d0d](https://linux-hardware.org/?probe=290aad9d0d) | Sep 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [798495635e](https://linux-hardware.org/?probe=798495635e) | Sep 11, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_Unity/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu Unity 16.04 | 589       | 47.89%  |
| Ubuntu Unity 20.04 | 245       | 19.92%  |
| Ubuntu Unity 18.04 | 232       | 18.86%  |
| Ubuntu Unity 22.04 | 79        | 6.42%   |
| Ubuntu Unity 22.10 | 16        | 1.3%    |
| Ubuntu Unity 19.10 | 13        | 1.06%   |
| Ubuntu Unity 23.04 | 11        | 0.89%   |
| Ubuntu Unity 21.10 | 10        | 0.81%   |
| Ubuntu Unity 21.04 | 9         | 0.73%   |
| Ubuntu Unity 23.10 | 8         | 0.65%   |
| Ubuntu Unity 20.10 | 8         | 0.65%   |
| Ubuntu Unity 14.04 | 6         | 0.49%   |
| Ubuntu Unity 17.04 | 2         | 0.16%   |
| Ubuntu Unity 19.04 | 1         | 0.08%   |
| Ubuntu Unity 18.10 | 1         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu Unity | 1216      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 4.15.0-142-generic | 94        | 7.13%   |
| 4.15.0-112-generic | 44        | 3.34%   |
| 4.4.0-210-generic  | 41        | 3.11%   |
| 4.15.0-99-generic  | 34        | 2.58%   |
| 4.15.0-45-generic  | 34        | 2.58%   |
| 4.15.0-91-generic  | 31        | 2.35%   |
| 4.15.0-96-generic  | 28        | 2.12%   |
| 4.15.0-88-generic  | 26        | 1.97%   |
| 4.15.0-72-generic  | 25        | 1.9%    |
| 5.4.0-42-generic   | 20        | 1.52%   |
| 4.9.140-tegra      | 20        | 1.52%   |
| 5.4.0-48-generic   | 19        | 1.44%   |
| 4.15.0-118-generic | 18        | 1.36%   |
| 4.15.0-101-generic | 18        | 1.36%   |
| 5.4.0-52-generic   | 15        | 1.14%   |
| 4.4.0-177-generic  | 15        | 1.14%   |
| 4.15.0-128-generic | 15        | 1.14%   |
| 5.4.0-58-generic   | 14        | 1.06%   |
| 4.15.0-122-generic | 14        | 1.06%   |
| 4.15.0-74-generic  | 13        | 0.99%   |
| 4.15.0-117-generic | 13        | 0.99%   |
| 4.15.0-76-generic  | 12        | 0.91%   |
| 4.15.0-106-generic | 12        | 0.91%   |
| 4.4.0-184-generic  | 11        | 0.83%   |
| 4.15.0-107-generic | 11        | 0.83%   |
| 5.4.0-65-generic   | 10        | 0.76%   |
| 5.15.0-56-generic  | 10        | 0.76%   |
| 4.15.0-70-generic  | 9         | 0.68%   |
| 5.4.0-66-generic   | 8         | 0.61%   |
| 5.4.0-47-generic   | 8         | 0.61%   |
| 4.9.201-tegra      | 8         | 0.61%   |
| 4.4.0-176-generic  | 8         | 0.61%   |
| 4.15.0-213-generic | 8         | 0.61%   |
| 4.15.0-133-generic | 8         | 0.61%   |
| 4.4.0-186-generic  | 7         | 0.53%   |
| 4.4.0-178-generic  | 7         | 0.53%   |
| 4.4.0-174-generic  | 7         | 0.53%   |
| 4.4.0-173-generic  | 7         | 0.53%   |
| 4.4.0-148-generic  | 7         | 0.53%   |
| 5.4.0-37-generic   | 6         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 553       | 44.74%  |
| 5.4.0   | 201       | 16.26%  |
| 4.4.0   | 183       | 14.81%  |
| 5.15.0  | 57        | 4.61%   |
| 5.19.0  | 32        | 2.59%   |
| 5.8.0   | 28        | 2.27%   |
| 5.3.0   | 25        | 2.02%   |
| 4.9.140 | 21        | 1.7%    |
| 5.13.0  | 20        | 1.62%   |
| 5.11.0  | 18        | 1.46%   |
| 6.2.0   | 17        | 1.38%   |
| 6.5.0   | 16        | 1.29%   |
| 5.0.0   | 8         | 0.65%   |
| 4.9.201 | 8         | 0.65%   |
| 4.9.253 | 6         | 0.49%   |
| 4.13.0  | 6         | 0.49%   |
| 4.8.0   | 4         | 0.32%   |
| 3.13.0  | 4         | 0.32%   |
| 5.14.0  | 2         | 0.16%   |
| 4.18.0  | 2         | 0.16%   |
| 4.10.0  | 2         | 0.16%   |
| 6.2.11  | 1         | 0.08%   |
| 6.0.0   | 1         | 0.08%   |
| 5.9.6   | 1         | 0.08%   |
| 5.7.2   | 1         | 0.08%   |
| 5.7.19  | 1         | 0.08%   |
| 5.7.10  | 1         | 0.08%   |
| 5.7.1   | 1         | 0.08%   |
| 5.5.11  | 1         | 0.08%   |
| 5.4.14  | 1         | 0.08%   |
| 5.3.14  | 1         | 0.08%   |
| 5.17.6  | 1         | 0.08%   |
| 5.17.0  | 1         | 0.08%   |
| 5.16.8  | 1         | 0.08%   |
| 5.16.4  | 1         | 0.08%   |
| 5.16.0  | 1         | 0.08%   |
| 5.13.6  | 1         | 0.08%   |
| 5.12.1  | 1         | 0.08%   |
| 5.12.0  | 1         | 0.08%   |
| 5.0.7   | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15    | 554       | 44.86%  |
| 5.4     | 202       | 16.36%  |
| 4.4     | 183       | 14.82%  |
| 5.15    | 57        | 4.62%   |
| 4.9     | 35        | 2.83%   |
| 5.19    | 32        | 2.59%   |
| 5.8     | 28        | 2.27%   |
| 5.3     | 26        | 2.11%   |
| 5.13    | 21        | 1.7%    |
| 6.2     | 18        | 1.46%   |
| 5.11    | 18        | 1.46%   |
| 6.5     | 16        | 1.3%    |
| 5.0     | 9         | 0.73%   |
| 4.13    | 6         | 0.49%   |
| 5.7     | 4         | 0.32%   |
| 4.8     | 4         | 0.32%   |
| 3.13    | 4         | 0.32%   |
| 5.16    | 3         | 0.24%   |
| 5.17    | 2         | 0.16%   |
| 5.14    | 2         | 0.16%   |
| 5.12    | 2         | 0.16%   |
| 4.19    | 2         | 0.16%   |
| 4.18    | 2         | 0.16%   |
| 4.10    | 2         | 0.16%   |
| 6.0     | 1         | 0.08%   |
| 5.9     | 1         | 0.08%   |
| 5.5     | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 861       | 70.69%  |
| i686    | 320       | 26.27%  |
| aarch64 | 37        | 3.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Unity    | 1200      | 98.6%   |
| GNOME    | 15        | 1.23%   |
| KDE5     | 1         | 0.08%   |
| Cinnamon | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1120      | 91.88%  |
| Wayland | 88        | 7.22%   |
| Tty     | 11        | 0.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 688       | 55.66%  |
| LightDM | 301       | 24.35%  |
| GDM     | 182       | 14.72%  |
| GDM3    | 64        | 5.18%   |
| SDDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 442       | 36.26%  |
| de_DE   | 116       | 9.52%   |
| fr_FR   | 76        | 6.23%   |
| pt_BR   | 72        | 5.91%   |
| en_IN   | 58        | 4.76%   |
| en_GB   | 58        | 4.76%   |
| ru_RU   | 42        | 3.45%   |
| it_IT   | 39        | 3.2%    |
| es_ES   | 33        | 2.71%   |
| en_CA   | 26        | 2.13%   |
| Unknown | 26        | 2.13%   |
| pl_PL   | 18        | 1.48%   |
| en_AU   | 15        | 1.23%   |
| nl_NL   | 14        | 1.15%   |
| hu_HU   | 14        | 1.15%   |
| es_AR   | 11        | 0.9%    |
| pt_PT   | 10        | 0.82%   |
| es_MX   | 9         | 0.74%   |
| en_ZA   | 9         | 0.74%   |
| zh_CN   | 8         | 0.66%   |
| tr_TR   | 7         | 0.57%   |
| cs_CZ   | 7         | 0.57%   |
| C       | 7         | 0.57%   |
| el_GR   | 6         | 0.49%   |
| ja_JP   | 5         | 0.41%   |
| en_PH   | 5         | 0.41%   |
| zh_TW   | 4         | 0.33%   |
| ru_UA   | 4         | 0.33%   |
| nl_BE   | 4         | 0.33%   |
| es_CO   | 4         | 0.33%   |
| en_NZ   | 4         | 0.33%   |
| en_IE   | 4         | 0.33%   |
| de_CH   | 4         | 0.33%   |
| da_DK   | 4         | 0.33%   |
| sv_SE   | 3         | 0.25%   |
| sl_SI   | 3         | 0.25%   |
| sk_SK   | 3         | 0.25%   |
| ro_RO   | 3         | 0.25%   |
| fi_FI   | 3         | 0.25%   |
| es_GT   | 3         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 837       | 68.49%  |
| EFI  | 385       | 31.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1152      | 94.5%   |
| Tmpfs    | 42        | 3.45%   |
| Ext3     | 6         | 0.49%   |
| Zfs      | 5         | 0.41%   |
| Overlay  | 3         | 0.25%   |
| Ext2     | 3         | 0.25%   |
| Btrfs    | 3         | 0.25%   |
| Aufs     | 3         | 0.25%   |
| SquasXfs | 1         | 0.08%   |
| Jfs      | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 839       | 68.27%  |
| GPT     | 265       | 21.56%  |
| MBR     | 125       | 10.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1078      | 87.86%  |
| Yes       | 149       | 12.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 807       | 65.77%  |
| Yes       | 420       | 34.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 190       | 15.63%  |
| Hewlett-Packard     | 167       | 13.73%  |
| ASUSTek Computer    | 155       | 12.75%  |
| Lenovo              | 134       | 11.02%  |
| Gigabyte Technology | 91        | 7.48%   |
| Acer                | 66        | 5.43%   |
| MSI                 | 46        | 3.78%   |
| Toshiba             | 37        | 3.04%   |
| Nvidia              | 34        | 2.8%    |
| ASRock              | 32        | 2.63%   |
| Intel               | 28        | 2.3%    |
| Apple               | 26        | 2.14%   |
| Unknown             | 17        | 1.4%    |
| Fujitsu Siemens     | 15        | 1.23%   |
| Fujitsu             | 12        | 0.99%   |
| Sony                | 11        | 0.9%    |
| Samsung Electronics | 11        | 0.9%    |
| Positivo            | 11        | 0.9%    |
| ECS                 | 8         | 0.66%   |
| Pegatron            | 7         | 0.58%   |
| Medion              | 7         | 0.58%   |
| HUAWEI              | 6         | 0.49%   |
| Notebook            | 5         | 0.41%   |
| Itautec             | 5         | 0.41%   |
| Biostar             | 5         | 0.41%   |
| Timi                | 4         | 0.33%   |
| Packard Bell        | 4         | 0.33%   |
| IBM                 | 4         | 0.33%   |
| Foxconn             | 4         | 0.33%   |
| LG Electronics      | 3         | 0.25%   |
| eMachines           | 3         | 0.25%   |
| Chuwi               | 3         | 0.25%   |
| Alienware           | 3         | 0.25%   |
| System76            | 2         | 0.16%   |
| Semp Toshiba        | 2         | 0.16%   |
| PCWare              | 2         | 0.16%   |
| Panasonic           | 2         | 0.16%   |
| OEM                 | 2         | 0.16%   |
| NEC Computers       | 2         | 0.16%   |
| Lex BayTrail        | 2         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Nvidia Tegra                  | 34        | 2.8%    |
| Unknown                       | 21        | 1.73%   |
| ASUS All Series               | 13        | 1.07%   |
| HP Pavilion dv6               | 7         | 0.58%   |
| Dell OptiPlex 755             | 6         | 0.49%   |
| HP ProBook 6550b              | 4         | 0.33%   |
| HP Mini 210-1000              | 4         | 0.33%   |
| Dell OptiPlex 9020            | 4         | 0.33%   |
| Dell OptiPlex 7010            | 4         | 0.33%   |
| Dell Latitude 7480            | 4         | 0.33%   |
| Toshiba Satellite L300        | 3         | 0.25%   |
| Positivo Mobile               | 3         | 0.25%   |
| Itautec Infoway               | 3         | 0.25%   |
| HP Z400 Workstation           | 3         | 0.25%   |
| HP Notebook                   | 3         | 0.25%   |
| Gigabyte GA-78LMT-USB3 6.0    | 3         | 0.25%   |
| Gigabyte G31M-ES2L            | 3         | 0.25%   |
| Dell XPS 13 9370              | 3         | 0.25%   |
| Dell Latitude D630            | 3         | 0.25%   |
| Dell Latitude D620            | 3         | 0.25%   |
| Dell Inspiron 5570            | 3         | 0.25%   |
| Dell Inspiron 3521            | 3         | 0.25%   |
| Dell Inspiron 1545            | 3         | 0.25%   |
| ASUS P4C800-E                 | 3         | 0.25%   |
| ASUS 1005HA                   | 3         | 0.25%   |
| Toshiba Portable PC           | 2         | 0.16%   |
| Toshiba NB505                 | 2         | 0.16%   |
| Timi TM1701                   | 2         | 0.16%   |
| Samsung R530/R730             | 2         | 0.16%   |
| Positivo N1103                | 2         | 0.16%   |
| MSI MS-7B86                   | 2         | 0.16%   |
| MSI MS-7996                   | 2         | 0.16%   |
| Medion Akoya THE TOUCH 10     | 2         | 0.16%   |
| Lenovo V145-15AST 81MT        | 2         | 0.16%   |
| Lenovo IdeaPad 3 15IIL05 81WE | 2         | 0.16%   |
| Lenovo G50-70 20351           | 2         | 0.16%   |
| Intel X79 V2.72A              | 2         | 0.16%   |
| HP ZBook 17 G3                | 2         | 0.16%   |
| HP ProBook 455 G1             | 2         | 0.16%   |
| HP ProBook 4510s              | 2         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 60        | 4.93%   |
| Dell Inspiron            | 56        | 4.61%   |
| Acer Aspire              | 41        | 3.37%   |
| HP Compaq                | 38        | 3.13%   |
| Dell Latitude            | 37        | 3.04%   |
| HP Pavilion              | 36        | 2.96%   |
| Nvidia Tegra             | 34        | 2.8%    |
| Dell OptiPlex            | 33        | 2.71%   |
| Toshiba Satellite        | 25        | 2.06%   |
| Unknown                  | 21        | 1.73%   |
| Dell XPS                 | 20        | 1.64%   |
| HP ProBook               | 19        | 1.56%   |
| Dell Precision           | 18        | 1.48%   |
| Lenovo IdeaPad           | 17        | 1.4%    |
| HP EliteBook             | 14        | 1.15%   |
| ASUS PRIME               | 13        | 1.07%   |
| ASUS All                 | 13        | 1.07%   |
| Dell Vostro              | 12        | 0.99%   |
| ASUS ROG                 | 9         | 0.74%   |
| HP ZBook                 | 8         | 0.66%   |
| HP ENVY                  | 7         | 0.58%   |
| HP Mini                  | 6         | 0.49%   |
| Lenovo Yoga              | 5         | 0.41%   |
| Lenovo ThinkCentre       | 5         | 0.41%   |
| Itautec Infoway          | 5         | 0.41%   |
| Fujitsu LIFEBOOK         | 5         | 0.41%   |
| ASUS M5A78L-M            | 5         | 0.41%   |
| Medion Akoya             | 4         | 0.33%   |
| Lenovo Legion            | 4         | 0.33%   |
| HP Presario              | 4         | 0.33%   |
| HP Laptop                | 4         | 0.33%   |
| Fujitsu Siemens LIFEBOOK | 4         | 0.33%   |
| Fujitsu Siemens ESPRIMO  | 4         | 0.33%   |
| Fujitsu ESPRIMO          | 4         | 0.33%   |
| ASUS VivoBook            | 4         | 0.33%   |
| ASUS TUF                 | 4         | 0.33%   |
| Acer TravelMate          | 4         | 0.33%   |
| Acer Extensa             | 4         | 0.33%   |
| Positivo Mobile          | 3         | 0.25%   |
| Lenovo G580              | 3         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 95        | 7.81%   |
| 2009    | 92        | 7.57%   |
| 2012    | 90        | 7.4%    |
| 2007    | 83        | 6.83%   |
| 2011    | 78        | 6.41%   |
| 2010    | 76        | 6.25%   |
| 2018    | 75        | 6.17%   |
| 2017    | 75        | 6.17%   |
| 2013    | 72        | 5.92%   |
| 2015    | 65        | 5.35%   |
| 2016    | 63        | 5.18%   |
| 2014    | 61        | 5.02%   |
| 2019    | 56        | 4.61%   |
| 2006    | 52        | 4.28%   |
| 2020    | 50        | 4.11%   |
| Unknown | 39        | 3.21%   |
| 2021    | 29        | 2.38%   |
| 2005    | 27        | 2.22%   |
| 2022    | 18        | 1.48%   |
| 2004    | 8         | 0.66%   |
| 2003    | 6         | 0.49%   |
| 2023    | 3         | 0.25%   |
| 2002    | 2         | 0.16%   |
| 2024    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 654       | 53.78%  |
| Desktop        | 478       | 39.31%  |
| System on chip | 37        | 3.04%   |
| Mini pc        | 13        | 1.07%   |
| All in one     | 13        | 1.07%   |
| Convertible    | 12        | 0.99%   |
| Server         | 5         | 0.41%   |
| Tablet         | 4         | 0.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1155      | 94.98%  |
| Enabled  | 61        | 5.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1216      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 264       | 21.48%  |
| 4.01-8.0    | 237       | 19.28%  |
| 16.01-24.0  | 190       | 15.46%  |
| 8.01-16.0   | 170       | 13.83%  |
| 1.01-2.0    | 145       | 11.8%   |
| 32.01-64.0  | 75        | 6.1%    |
| 2.01-3.0    | 64        | 5.21%   |
| 0.51-1.0    | 51        | 4.15%   |
| 64.01-256.0 | 18        | 1.46%   |
| 24.01-32.0  | 13        | 1.06%   |
| 0.01-0.5    | 2         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 497       | 38.95%  |
| 2.01-3.0    | 233       | 18.26%  |
| 0.51-1.0    | 192       | 15.05%  |
| 4.01-8.0    | 149       | 11.68%  |
| 3.01-4.0    | 128       | 10.03%  |
| 8.01-16.0   | 50        | 3.92%   |
| 0.01-0.5    | 11        | 0.86%   |
| 16.01-24.0  | 7         | 0.55%   |
| Unknown     | 4         | 0.31%   |
| 32.01-64.0  | 2         | 0.16%   |
| 24.01-32.0  | 2         | 0.16%   |
| 64.01-256.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 821       | 66.48%  |
| 2      | 272       | 22.02%  |
| 3      | 72        | 5.83%   |
| 4      | 32        | 2.59%   |
| 6      | 10        | 0.81%   |
| 5      | 10        | 0.81%   |
| 0      | 10        | 0.81%   |
| 9      | 3         | 0.24%   |
| 7      | 3         | 0.24%   |
| 11     | 1         | 0.08%   |
| 10     | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 637       | 52.26%  |
| No        | 582       | 47.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1115      | 91.47%  |
| No        | 104       | 8.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 904       | 74.1%   |
| No        | 316       | 25.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 704       | 57.47%  |
| Yes       | 521       | 42.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 202       | 16.57%  |
| Germany      | 124       | 10.17%  |
| Brazil       | 91        | 7.47%   |
| France       | 79        | 6.48%   |
| India        | 61        | 5%      |
| Russia       | 54        | 4.43%   |
| UK           | 53        | 4.35%   |
| Italy        | 46        | 3.77%   |
| Spain        | 40        | 3.28%   |
| Canada       | 29        | 2.38%   |
| Netherlands  | 24        | 1.97%   |
| Poland       | 22        | 1.8%    |
| Belgium      | 18        | 1.48%   |
| Turkey       | 15        | 1.23%   |
| Romania      | 15        | 1.23%   |
| Hungary      | 15        | 1.23%   |
| Australia    | 15        | 1.23%   |
| Ukraine      | 14        | 1.15%   |
| Greece       | 13        | 1.07%   |
| China        | 13        | 1.07%   |
| Argentina    | 13        | 1.07%   |
| Mexico       | 12        | 0.98%   |
| Bulgaria     | 12        | 0.98%   |
| Colombia     | 11        | 0.9%    |
| South Africa | 10        | 0.82%   |
| Portugal     | 10        | 0.82%   |
| Japan        | 10        | 0.82%   |
| Czechia      | 10        | 0.82%   |
| Switzerland  | 9         | 0.74%   |
| Indonesia    | 9         | 0.74%   |
| Austria      | 9         | 0.74%   |
| Vietnam      | 8         | 0.66%   |
| Sweden       | 8         | 0.66%   |
| Morocco      | 6         | 0.49%   |
| Denmark      | 6         | 0.49%   |
| South Korea  | 5         | 0.41%   |
| Slovakia     | 5         | 0.41%   |
| Philippines  | 5         | 0.41%   |
| New Zealand  | 5         | 0.41%   |
| Ireland      | 5         | 0.41%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 20        | 1.59%   |
| Moscow            | 14        | 1.11%   |
| Sao Paulo         | 13        | 1.04%   |
| Paris             | 11        | 0.88%   |
| Rome              | 8         | 0.64%   |
| Hamburg           | 8         | 0.64%   |
| Athens            | 8         | 0.64%   |
| Warsaw            | 7         | 0.56%   |
| Rio de Janeiro    | 7         | 0.56%   |
| Milan             | 7         | 0.56%   |
| Budapest          | 7         | 0.56%   |
| Bengaluru         | 7         | 0.56%   |
| Barcelona         | 7         | 0.56%   |
| Sydney            | 6         | 0.48%   |
| Pune              | 6         | 0.48%   |
| Munich            | 6         | 0.48%   |
| Montreal          | 6         | 0.48%   |
| Istanbul          | 6         | 0.48%   |
| Hyderabad         | 6         | 0.48%   |
| Frankfurt am Main | 6         | 0.48%   |
| Brasília         | 6         | 0.48%   |
| Bogotá           | 6         | 0.48%   |
| St Petersburg     | 5         | 0.4%    |
| Denver            | 5         | 0.4%    |
| Amsterdam         | 5         | 0.4%    |
| Yekaterinburg     | 4         | 0.32%   |
| Wuppertal         | 4         | 0.32%   |
| Vienna            | 4         | 0.32%   |
| Toronto           | 4         | 0.32%   |
| Stuttgart         | 4         | 0.32%   |
| Nizhniy Novgorod  | 4         | 0.32%   |
| New Delhi         | 4         | 0.32%   |
| Mumbai            | 4         | 0.32%   |
| Madrid            | 4         | 0.32%   |
| Lviv              | 4         | 0.32%   |
| Lisbon            | 4         | 0.32%   |
| Hanoi             | 4         | 0.32%   |
| Dublin            | 4         | 0.32%   |
| Cologne           | 4         | 0.32%   |
| Buenos Aires      | 4         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 293       | 388    | 18.11%  |
| WDC                       | 289       | 385    | 17.86%  |
| Samsung Electronics       | 212       | 274    | 13.1%   |
| Toshiba                   | 149       | 171    | 9.21%   |
| Hitachi                   | 95        | 104    | 5.87%   |
| Kingston                  | 74        | 87     | 4.57%   |
| Unknown                   | 72        | 81     | 4.45%   |
| SanDisk                   | 58        | 69     | 3.58%   |
| Crucial                   | 44        | 54     | 2.72%   |
| HGST                      | 42        | 55     | 2.6%    |
| Intel                     | 27        | 30     | 1.67%   |
| Micron Technology         | 23        | 29     | 1.42%   |
| Fujitsu                   | 17        | 17     | 1.05%   |
| A-DATA Technology         | 15        | 15     | 0.93%   |
| SK hynix                  | 14        | 14     | 0.87%   |
| Maxtor                    | 14        | 14     | 0.87%   |
| PNY                       | 11        | 16     | 0.68%   |
| LITEON                    | 11        | 14     | 0.68%   |
| Intenso                   | 11        | 14     | 0.68%   |
| OCZ                       | 10        | 11     | 0.62%   |
| Transcend                 | 9         | 9      | 0.56%   |
| Patriot                   | 9         | 10     | 0.56%   |
| KIOXIA                    | 8         | 8      | 0.49%   |
| Apple                     | 7         | 10     | 0.43%   |
| SPCC                      | 6         | 8      | 0.37%   |
| LITEONIT                  | 6         | 10     | 0.37%   |
| China                     | 6         | 6      | 0.37%   |
| Verbatim                  | 4         | 4      | 0.25%   |
| Phison                    | 4         | 5      | 0.25%   |
| Lenovo                    | 4         | 4      | 0.25%   |
| Corsair                   | 4         | 4      | 0.25%   |
| XPG                       | 3         | 4      | 0.19%   |
| Micron/Crucial Technology | 3         | 3      | 0.19%   |
| Hewlett-Packard           | 3         | 4      | 0.19%   |
| Apacer                    | 3         | 3      | 0.19%   |
| XrayDisk                  | 2         | 2      | 0.12%   |
| Team                      | 2         | 4      | 0.12%   |
| StoreJet                  | 2         | 2      | 0.12%   |
| Silicon Motion            | 2         | 2      | 0.12%   |
| SABRENT                   | 2         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 18        | 1.02%   |
| Unknown MMC Card  32GB              | 17        | 0.97%   |
| Seagate ST500DM002-1BD142 500GB     | 15        | 0.85%   |
| Kingston SA400S37240G 240GB SSD     | 15        | 0.85%   |
| Unknown MMC Card  128GB             | 14        | 0.8%    |
| Seagate ST1000DM010-2EP102 1TB      | 13        | 0.74%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 11        | 0.63%   |
| Samsung SSD 850 EVO 250GB           | 11        | 0.63%   |
| Kingston SV300S37A120G 120GB SSD    | 10        | 0.57%   |
| HGST HTS545050A7E680 500GB          | 10        | 0.57%   |
| Toshiba DT01ACA100 1TB              | 9         | 0.51%   |
| Samsung SSD 860 EVO 250GB           | 9         | 0.51%   |
| Unknown MMC Card  64GB              | 8         | 0.45%   |
| Samsung NVMe SSD Drive 512GB        | 8         | 0.45%   |
| HGST HTS721010A9E630 1TB            | 8         | 0.45%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 0.4%    |
| Samsung SSD 860 EVO 500GB           | 7         | 0.4%    |
| Kingston SA400S37120G 120GB SSD     | 7         | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB            | 6         | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB            | 6         | 0.34%   |
| Toshiba MQ01ACF050 500GB            | 6         | 0.34%   |
| Toshiba MQ01ABD100 1TB              | 6         | 0.34%   |
| Seagate ST380815AS 80GB             | 6         | 0.34%   |
| Seagate ST2000DM001-1ER164 2TB      | 6         | 0.34%   |
| Seagate ST1000DM003-1SB102 1TB      | 6         | 0.34%   |
| Samsung SSD 840 EVO 250GB           | 6         | 0.34%   |
| Kingston SUV400S37240G 240GB SSD    | 6         | 0.34%   |
| Kingston SA400S37480G 480GB SSD     | 6         | 0.34%   |
| Hitachi HTS545032B9A300 320GB       | 6         | 0.34%   |
| HGST HTS725050A7E630 500GB          | 6         | 0.34%   |
| Crucial CT240BX500SSD1 240GB        | 6         | 0.34%   |
| Crucial CT1000MX500SSD1 1TB         | 6         | 0.34%   |
| WDC WD5000AAKX-001CA0 500GB         | 5         | 0.28%   |
| WDC WD10EZEX-60WN4A0 1TB            | 5         | 0.28%   |
| Toshiba MQ01ABD075 752GB            | 5         | 0.28%   |
| Toshiba DT01ACA050 500GB            | 5         | 0.28%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 0.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 0.28%   |
| Seagate ST3500418AS 500GB           | 5         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 291       | 383    | 31.56%  |
| WDC                 | 261       | 351    | 28.31%  |
| Toshiba             | 120       | 136    | 13.02%  |
| Hitachi             | 95        | 104    | 10.3%   |
| Samsung Electronics | 58        | 69     | 6.29%   |
| HGST                | 42        | 55     | 4.56%   |
| Fujitsu             | 17        | 17     | 1.84%   |
| Maxtor              | 14        | 14     | 1.52%   |
| Apple               | 5         | 6      | 0.54%   |
| Unknown             | 4         | 3      | 0.43%   |
| SABRENT             | 2         | 2      | 0.22%   |
| JMicron Technology  | 2         | 2      | 0.22%   |
| Intenso             | 2         | 2      | 0.22%   |
| IBM/Hitachi         | 2         | 2      | 0.22%   |
| Hewlett-Packard     | 2         | 3      | 0.22%   |
| XrayDisk            | 1         | 1      | 0.11%   |
| USB                 | 1         | 2      | 0.11%   |
| StoreJet            | 1         | 1      | 0.11%   |
| STEC                | 1         | 1      | 0.11%   |
| Lenovo              | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 96        | 130    | 22.97%  |
| Kingston            | 61        | 72     | 14.59%  |
| SanDisk             | 42        | 49     | 10.05%  |
| Crucial             | 42        | 52     | 10.05%  |
| Micron Technology   | 17        | 22     | 4.07%   |
| WDC                 | 15        | 16     | 3.59%   |
| Intel               | 15        | 16     | 3.59%   |
| A-DATA Technology   | 12        | 12     | 2.87%   |
| Toshiba             | 11        | 13     | 2.63%   |
| PNY                 | 11        | 16     | 2.63%   |
| OCZ                 | 10        | 11     | 2.39%   |
| LITEON              | 9         | 12     | 2.15%   |
| Patriot             | 8         | 9      | 1.91%   |
| Transcend           | 6         | 6      | 1.44%   |
| LITEONIT            | 6         | 10     | 1.44%   |
| Intenso             | 6         | 7      | 1.44%   |
| China               | 6         | 6      | 1.44%   |
| Verbatim            | 4         | 4      | 0.96%   |
| SPCC                | 4         | 5      | 0.96%   |
| SK hynix            | 4         | 4      | 0.96%   |
| Team                | 2         | 4      | 0.48%   |
| KingDian            | 2         | 2      | 0.48%   |
| Apacer              | 2         | 2      | 0.48%   |
| XrayDisk            | 1         | 1      | 0.24%   |
| Vaseky              | 1         | 1      | 0.24%   |
| USB3.0              | 1         | 1      | 0.24%   |
| SUNEAST             | 1         | 1      | 0.24%   |
| StoreJet            | 1         | 1      | 0.24%   |
| SSK                 | 1         | 1      | 0.24%   |
| Smartbuy            | 1         | 1      | 0.24%   |
| Seagate             | 1         | 1      | 0.24%   |
| Plextor             | 1         | 1      | 0.24%   |
| NGFF                | 1         | 1      | 0.24%   |
| Mushkin             | 1         | 1      | 0.24%   |
| MidasForce          | 1         | 1      | 0.24%   |
| Lexar               | 1         | 1      | 0.24%   |
| KingSpec            | 1         | 2      | 0.24%   |
| Innodisk            | 1         | 1      | 0.24%   |
| Hikvision           | 1         | 2      | 0.24%   |
| GOODRAM             | 1         | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 809       | 1155   | 55.53%  |
| SSD     | 367       | 509    | 25.19%  |
| NVMe    | 198       | 239    | 13.59%  |
| MMC     | 63        | 70     | 4.32%   |
| Unknown | 20        | 25     | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1027      | 1627   | 76.87%  |
| NVMe | 198       | 238    | 14.82%  |
| MMC  | 63        | 70     | 4.72%   |
| SAS  | 48        | 63     | 3.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 825       | 1092   | 65.95%  |
| 0.51-1.0   | 286       | 354    | 22.86%  |
| 1.01-2.0   | 73        | 97     | 5.84%   |
| 2.01-3.0   | 26        | 39     | 2.08%   |
| 3.01-4.0   | 24        | 47     | 1.92%   |
| 4.01-10.0  | 13        | 27     | 1.04%   |
| 10.01-20.0 | 4         | 8      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 409       | 32.93%  |
| 251-500        | 292       | 23.51%  |
| 501-1000       | 151       | 12.16%  |
| 51-100         | 134       | 10.79%  |
| 1001-2000      | 80        | 6.44%   |
| 21-50          | 67        | 5.39%   |
| More than 3000 | 47        | 3.78%   |
| 2001-3000      | 32        | 2.58%   |
| 1-20           | 27        | 2.17%   |
| Unknown        | 3         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 510       | 40.48%  |
| 21-50          | 178       | 14.13%  |
| 101-250        | 167       | 13.25%  |
| 51-100         | 162       | 12.86%  |
| 251-500        | 92        | 7.3%    |
| 501-1000       | 79        | 6.27%   |
| 1001-2000      | 33        | 2.62%   |
| More than 3000 | 21        | 1.67%   |
| 2001-3000      | 15        | 1.19%   |
| Unknown        | 3         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB                            | 2         | 2      | 3.28%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 3.28%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 2      | 3.28%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 3      | 3.28%   |
| Seagate ST3320620AS 320GB                           | 2         | 2      | 3.28%   |
| HGST HTS545050A7E680 500GB                          | 2         | 2      | 3.28%   |
| WDC WD5001AALS-00LWTA0 500GB                        | 1         | 1      | 1.64%   |
| WDC WD5000AAKX-001CA0 500GB                         | 1         | 1      | 1.64%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 1         | 1      | 1.64%   |
| WDC WD20EARS-22MVWB0 2TB                            | 1         | 1      | 1.64%   |
| WDC WD10PURX-64D85Y0 1TB                            | 1         | 1      | 1.64%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 1.64%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 1      | 1.64%   |
| WDC WD10EADX-22TDHB0 1TB                            | 1         | 1      | 1.64%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD100M 1TB                             | 1         | 1      | 1.64%   |
| Toshiba MK6465GSX 640GB                             | 1         | 1      | 1.64%   |
| Toshiba MK3261GSYN 320GB                            | 1         | 1      | 1.64%   |
| Toshiba MK3252GSX 320GB                             | 1         | 2      | 1.64%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 1.64%   |
| Seagate ST500DM002-1SB10A 500GB                     | 1         | 1      | 1.64%   |
| Seagate ST3750330NS 752GB                           | 1         | 1      | 1.64%   |
| Seagate ST3500630AS 500GB                           | 1         | 1      | 1.64%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 1.64%   |
| Seagate ST32000542AS 2TB                            | 1         | 1      | 1.64%   |
| Seagate ST3160815AS 160GB                           | 1         | 1      | 1.64%   |
| Seagate ST31000524NS 1TB                            | 1         | 1      | 1.64%   |
| Seagate ST3000DM001-1CH166 3TB                      | 1         | 2      | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 1.64%   |
| Seagate ST1000LM 035-1RK172 1TB                     | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 850 EVO 250GB               | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 840 PRO Series 256GB        | 1         | 1      | 1.64%   |
| Samsung Electronics HM320II 320GB                   | 1         | 1      | 1.64%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 1.64%   |
| Samsung Electronics HD161HJ 160GB                   | 1         | 1      | 1.64%   |
| Samsung Electronics HD080HJ 80GB                    | 1         | 1      | 1.64%   |
| Patriot P210 1024GB SSD                             | 1         | 1      | 1.64%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 1.64%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 1         | 1      | 1.64%   |
| Kingston SH100S3240G 240GB SSD                      | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 31.67%  |
| WDC                 | 8         | 8      | 13.33%  |
| Toshiba             | 7         | 8      | 11.67%  |
| Samsung Electronics | 6         | 6      | 10%     |
| Hitachi             | 4         | 4      | 6.67%   |
| HGST                | 4         | 5      | 6.67%   |
| Crucial             | 3         | 3      | 5%      |
| Micron Technology   | 2         | 2      | 3.33%   |
| Kingston            | 2         | 3      | 3.33%   |
| Apple               | 2         | 2      | 3.33%   |
| Patriot             | 1         | 1      | 1.67%   |
| China               | 1         | 1      | 1.67%   |
| A-DATA Technology   | 1         | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 40.43%  |
| WDC                 | 8         | 8      | 17.02%  |
| Toshiba             | 7         | 8      | 14.89%  |
| Samsung Electronics | 4         | 4      | 8.51%   |
| Hitachi             | 4         | 4      | 8.51%   |
| HGST                | 4         | 5      | 8.51%   |
| Apple               | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 51     | 77.19%  |
| SSD  | 13        | 14     | 22.81%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 893       | 1421   | 70.37%  |
| Works    | 320       | 511    | 25.22%  |
| Malfunc  | 55        | 65     | 4.33%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 891       | 64.24%  |
| AMD                              | 155       | 11.18%  |
| Samsung Electronics              | 68        | 4.9%    |
| Nvidia                           | 42        | 3.03%   |
| SanDisk                          | 32        | 2.31%   |
| JMicron Technology               | 22        | 1.59%   |
| Toshiba America Info Systems     | 18        | 1.3%    |
| Marvell Technology Group         | 18        | 1.3%    |
| ASMedia Technology               | 16        | 1.15%   |
| VIA Technologies                 | 15        | 1.08%   |
| Kingston Technology Company      | 15        | 1.08%   |
| Silicon Integrated Systems [SiS] | 12        | 0.87%   |
| Silicon Motion                   | 11        | 0.79%   |
| SK hynix                         | 10        | 0.72%   |
| Phison Electronics               | 10        | 0.72%   |
| KIOXIA                           | 9         | 0.65%   |
| Micron Technology                | 6         | 0.43%   |
| ADATA Technology                 | 6         | 0.43%   |
| Silicon Image                    | 5         | 0.36%   |
| Micron/Crucial Technology        | 4         | 0.29%   |
| Realtek Semiconductor            | 3         | 0.22%   |
| Promise Technology               | 3         | 0.22%   |
| LSI Logic / Symbios Logic        | 3         | 0.22%   |
| Lite-On Technology               | 2         | 0.14%   |
| Lenovo                           | 2         | 0.14%   |
| Apple                            | 2         | 0.14%   |
| Union Memory (Shenzhen)          | 1         | 0.07%   |
| ULi Electronics                  | 1         | 0.07%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| Shenzhen Longsys Electronics     | 1         | 0.07%   |
| Seagate Technology               | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 87        | 5.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 71        | 4.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 56        | 3.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 52        | 3.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 50        | 2.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 43        | 2.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 41        | 2.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 34        | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 34        | 1.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 32        | 1.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 29        | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 28        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 27        | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 26        | 1.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 25        | 1.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 25        | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 25        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25        | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 24        | 1.4%    |
| Nvidia MCP61 SATA Controller                                                   | 22        | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 1.28%   |
| Intel SATA Controller [RAID mode]                                              | 21        | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 21        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 21        | 1.23%   |
| Nvidia MCP61 IDE                                                               | 20        | 1.17%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 20        | 1.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 19        | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 19        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 16        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 15        | 0.88%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 14        | 0.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 14        | 0.82%   |
| JMicron JMB363 SATA/IDE Controller                                             | 14        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 14        | 0.82%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 14        | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 14        | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 0.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 13        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 789       | 54.23%  |
| IDE  | 385       | 26.46%  |
| NVMe | 198       | 13.61%  |
| RAID | 77        | 5.29%   |
| SAS  | 4         | 0.27%   |
| SCSI | 2         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 974       | 80.1%   |
| AMD          | 202       | 16.61%  |
| ARM          | 25        | 2.06%   |
| Unknown      | 11        | 0.9%    |
| CentaurHauls | 3         | 0.25%   |
| Qualcomm     | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ARM Processor                               | 25        | 2.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 16        | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 14        | 1.15%   |
| Intel Pentium 4 CPU 3.00GHz                 | 13        | 1.07%   |
| Intel Atom CPU N270 @ 1.60GHz               | 13        | 1.07%   |
|                                             | 11        | 0.9%    |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 9         | 0.74%   |
| Intel Pentium M processor 1.73GHz           | 8         | 0.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 8         | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 8         | 0.66%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 7         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 7         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 7         | 0.58%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7         | 0.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 7         | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.58%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 7         | 0.58%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 7         | 0.58%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 7         | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 6         | 0.49%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6         | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 6         | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6         | 0.49%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 6         | 0.49%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 6         | 0.49%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 6         | 0.49%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 6         | 0.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 6         | 0.49%   |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 0.49%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6         | 0.49%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 5         | 0.41%   |
| Intel Pentium D CPU 2.80GHz                 | 5         | 0.41%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 5         | 0.41%   |
| Intel Pentium 4 CPU 3.20GHz                 | 5         | 0.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 5         | 0.41%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 5         | 0.41%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 5         | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 5         | 0.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 5         | 0.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 193       | 15.87%  |
| Intel Core i7                  | 189       | 15.54%  |
| Intel Core 2 Duo               | 102       | 8.39%   |
| Intel Core i3                  | 92        | 7.57%   |
| Other                          | 71        | 5.84%   |
| Intel Celeron                  | 54        | 4.44%   |
| Intel Atom                     | 49        | 4.03%   |
| Intel Pentium                  | 40        | 3.29%   |
| Intel Pentium Dual-Core        | 34        | 2.8%    |
| AMD Ryzen 5                    | 32        | 2.63%   |
| Intel Xeon                     | 30        | 2.47%   |
| Intel Genuine                  | 28        | 2.3%    |
| Intel Pentium 4                | 26        | 2.14%   |
| Intel Core 2                   | 19        | 1.56%   |
| AMD FX                         | 17        | 1.4%    |
| Intel Pentium Dual             | 16        | 1.32%   |
| Intel Pentium M                | 14        | 1.15%   |
| Intel Celeron M                | 13        | 1.07%   |
| AMD Ryzen 7                    | 13        | 1.07%   |
| AMD Athlon 64 X2               | 12        | 0.99%   |
| AMD Phenom II X4               | 10        | 0.82%   |
| AMD A4                         | 10        | 0.82%   |
| Intel Pentium D                | 9         | 0.74%   |
| Intel Core 2 Quad              | 9         | 0.74%   |
| Intel Core i9                  | 8         | 0.66%   |
| AMD Athlon II X2               | 8         | 0.66%   |
| AMD A10                        | 8         | 0.66%   |
| AMD Ryzen 9                    | 7         | 0.58%   |
| AMD Ryzen 3                    | 7         | 0.58%   |
| AMD A8                         | 7         | 0.58%   |
| Intel Core Duo                 | 5         | 0.41%   |
| AMD Athlon Dual Core           | 5         | 0.41%   |
| AMD A6                         | 5         | 0.41%   |
| Intel Pentium Silver           | 4         | 0.33%   |
| AMD Sempron                    | 4         | 0.33%   |
| AMD Phenom                     | 4         | 0.33%   |
| CentaurHauls VIA C7            | 3         | 0.25%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.25%   |
| AMD Ryzen 7 PRO                | 3         | 0.25%   |
| AMD Phenom II X6               | 3         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 596       | 48.97%  |
| 4       | 344       | 28.27%  |
| 1       | 121       | 9.94%   |
| 6       | 85        | 6.98%   |
| 8       | 36        | 2.96%   |
| 3       | 9         | 0.74%   |
| 12      | 8         | 0.66%   |
| 16      | 7         | 0.58%   |
| 10      | 4         | 0.33%   |
| 24      | 3         | 0.25%   |
| 14      | 2         | 0.16%   |
| 44      | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1192      | 98.03%  |
| 2       | 15        | 1.23%   |
| 3       | 6         | 0.49%   |
| 4       | 2         | 0.16%   |
| Unknown | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 612       | 50.25%  |
| 1       | 605       | 49.67%  |
| Unknown | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1086      | 89.31%  |
| 32-bit         | 95        | 7.81%   |
| Unknown        | 34        | 2.8%    |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 210       | 17.06%  |
| 0x1067a    | 82        | 6.66%   |
| 0x206a7    | 64        | 5.2%    |
| 0x306a9    | 63        | 5.12%   |
| 0x306c3    | 48        | 3.9%    |
| 0x6fd      | 38        | 3.09%   |
| 0x906ea    | 35        | 2.84%   |
| 0x506e3    | 32        | 2.6%    |
| 0x806e9    | 31        | 2.52%   |
| 0x20655    | 25        | 2.03%   |
| 0x10676    | 25        | 2.03%   |
| 0x806ea    | 23        | 1.87%   |
| 0x6e8      | 20        | 1.62%   |
| 0x40651    | 19        | 1.54%   |
| 0x106ca    | 19        | 1.54%   |
| 0x106c2    | 19        | 1.54%   |
| 0x906e9    | 18        | 1.46%   |
| 0x306d4    | 18        | 1.46%   |
| 0x806ec    | 17        | 1.38%   |
| 0x406e3    | 17        | 1.38%   |
| 0x6fb      | 16        | 1.3%    |
| 0x6d8      | 16        | 1.3%    |
| 0x010000c8 | 16        | 1.3%    |
| 0x6f6      | 14        | 1.14%   |
| 0x6ec      | 14        | 1.14%   |
| 0x30678    | 14        | 1.14%   |
| 0x06000852 | 13        | 1.06%   |
| 0x20652    | 12        | 0.97%   |
| 0x406c4    | 11        | 0.89%   |
| 0x6f2      | 9         | 0.73%   |
| 0x406c3    | 9         | 0.73%   |
| 0x06001119 | 9         | 0.73%   |
| 0xa0652    | 8         | 0.65%   |
| 0x806c1    | 8         | 0.65%   |
| 0x0700010f | 8         | 0.65%   |
| 0x206d7    | 7         | 0.57%   |
| 0x106e5    | 7         | 0.57%   |
| 0x10661    | 7         | 0.57%   |
| 0x08108109 | 7         | 0.57%   |
| 0x05000119 | 7         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 156       | 12.83%  |
| Penryn           | 115       | 9.46%   |
| Core             | 89        | 7.32%   |
| SandyBridge      | 83        | 6.83%   |
| Haswell          | 75        | 6.17%   |
| IvyBridge        | 73        | 6%      |
| Skylake          | 60        | 4.93%   |
| P6               | 53        | 4.36%   |
| Unknown          | 49        | 4.03%   |
| Westmere         | 44        | 3.62%   |
| Bonnell          | 41        | 3.37%   |
| Silvermont       | 40        | 3.29%   |
| NetBurst         | 38        | 3.13%   |
| K10              | 38        | 3.13%   |
| Broadwell        | 26        | 2.14%   |
| Piledriver       | 25        | 2.06%   |
| K8 Hammer        | 25        | 2.06%   |
| CometLake        | 21        | 1.73%   |
| Zen 2            | 20        | 1.64%   |
| Zen+             | 16        | 1.32%   |
| Zen              | 16        | 1.32%   |
| TigerLake        | 11        | 0.9%    |
| Alderlake Hybrid | 11        | 0.9%    |
| Nehalem          | 10        | 0.82%   |
| Excavator        | 10        | 0.82%   |
| Zen 3            | 8         | 0.66%   |
| Jaguar           | 8         | 0.66%   |
| IceLake          | 8         | 0.66%   |
| Goldmont plus    | 8         | 0.66%   |
| Bobcat           | 8         | 0.66%   |
| Steamroller      | 6         | 0.49%   |
| K8 & K10 hybrid  | 6         | 0.49%   |
| Puma             | 5         | 0.41%   |
| Goldmont         | 5         | 0.41%   |
| K10 Llano        | 4         | 0.33%   |
| K6               | 3         | 0.25%   |
| Tremont          | 1         | 0.08%   |
| Bulldozer        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 731       | 54.15%  |
| Nvidia                           | 337       | 24.96%  |
| AMD                              | 255       | 18.89%  |
| Silicon Integrated Systems [SiS] | 11        | 0.81%   |
| VIA Technologies                 | 8         | 0.59%   |
| ASPEED Technology                | 4         | 0.3%    |
| Silicon Motion                   | 2         | 0.15%   |
| Matrox Electronics Systems       | 2         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 58        | 4.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 44        | 3.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 44        | 3.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 39        | 2.7%    |
| Intel HD Graphics 620                                                                    | 31        | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 2.15%   |
| Intel HD Graphics 530                                                                    | 28        | 1.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 27        | 1.87%   |
| Intel UHD Graphics 620                                                                   | 25        | 1.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 22        | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 22        | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 21        | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 21        | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 1.32%   |
| Intel HD Graphics 5500                                                                   | 19        | 1.32%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 19        | 1.32%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 19        | 1.32%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 17        | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16        | 1.11%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 15        | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 0.9%    |
| Intel HD Graphics 630                                                                    | 12        | 0.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.69%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 10        | 0.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 0.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 0.69%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 9         | 0.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 0.62%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 9         | 0.62%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 9         | 0.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 0.62%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 8         | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 570       | 46.76%  |
| 1 x Nvidia         | 213       | 17.47%  |
| 1 x AMD            | 199       | 16.32%  |
| Intel + Nvidia     | 113       | 9.27%   |
| Other              | 38        | 3.12%   |
| Intel + AMD        | 29        | 2.38%   |
| 2 x AMD            | 20        | 1.64%   |
| 1 x SiS            | 11        | 0.9%    |
| 1 x VIA            | 8         | 0.66%   |
| 2 x Nvidia         | 5         | 0.41%   |
| AMD + Nvidia       | 5         | 0.41%   |
| 1 x Silicon Motion | 2         | 0.16%   |
| 1 x Matrox         | 2         | 0.16%   |
| 1 x ASPEED         | 2         | 0.16%   |
| Nvidia + ASPEED    | 1         | 0.08%   |
| AMD + ASPEED       | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 959       | 78.8%   |
| Proprietary | 151       | 12.41%  |
| Unknown     | 107       | 8.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 372       | 30.19%  |
| 0.01-0.5   | 307       | 24.92%  |
| 1.01-2.0   | 278       | 22.56%  |
| 3.01-4.0   | 136       | 11.04%  |
| 0.51-1.0   | 88        | 7.14%   |
| 7.01-8.0   | 25        | 2.03%   |
| 5.01-6.0   | 14        | 1.14%   |
| 2.01-3.0   | 6         | 0.49%   |
| 8.01-16.0  | 5         | 0.41%   |
| 4.01-5.0   | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 168       | 13.79%  |
| AU Optronics            | 133       | 10.92%  |
| LG Display              | 98        | 8.05%   |
| Chimei Innolux          | 68        | 5.58%   |
| Dell                    | 67        | 5.5%    |
| BOE                     | 67        | 5.5%    |
| Goldstar                | 57        | 4.68%   |
| Acer                    | 48        | 3.94%   |
| Hewlett-Packard         | 40        | 3.28%   |
| Ancor Communications    | 35        | 2.87%   |
| Lenovo                  | 30        | 2.46%   |
| Chi Mei Optoelectronics | 29        | 2.38%   |
| AOC                     | 28        | 2.3%    |
| Apple                   | 27        | 2.22%   |
| Philips                 | 26        | 2.13%   |
| Sharp                   | 25        | 2.05%   |
| BenQ                    | 25        | 2.05%   |
| LG Philips              | 18        | 1.48%   |
| LG Electronics          | 15        | 1.23%   |
| HannStar                | 14        | 1.15%   |
| Iiyama                  | 13        | 1.07%   |
| Unknown                 | 11        | 0.9%    |
| Sony                    | 9         | 0.74%   |
| InnoLux Display         | 7         | 0.57%   |
| ViewSonic               | 6         | 0.49%   |
| Vestel Elektronik       | 6         | 0.49%   |
| InfoVision              | 6         | 0.49%   |
| Fujitsu Siemens         | 6         | 0.49%   |
| ASUSTek Computer        | 6         | 0.49%   |
| Seiko/Epson             | 5         | 0.41%   |
| Quanta Display          | 5         | 0.41%   |
| Medion                  | 5         | 0.41%   |
| CPT                     | 5         | 0.41%   |
| Toshiba                 | 4         | 0.33%   |
| PANDA                   | 4         | 0.33%   |
| Panasonic               | 4         | 0.33%   |
| NEC Computers           | 4         | 0.33%   |
| IBM                     | 4         | 0.33%   |
| KTC                     | 3         | 0.25%   |
| KDC                     | 3         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 9         | 0.72%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 6         | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.4%    |
| Seiko/Epson LCD Monitor 1366x768                                         | 4         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.32%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 3         | 0.24%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 3         | 0.24%   |
| Samsung Electronics LCD Monitor U28E570                                  | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SyncMaster                               | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.24%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.24%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 3         | 0.24%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                    | 3         | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 3         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 3         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 3         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO0209 1024x600 195x113mm 8.9-inch  | 3         | 0.24%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 0.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.24%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 3         | 0.24%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 3         | 0.24%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 3         | 0.24%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.24%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 3         | 0.24%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                         | 3         | 0.24%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch         | 3         | 0.24%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch   | 3         | 0.24%   |
| Unknown                                                                  | 3         | 0.24%   |
| ___ LCDTV16 ___9000 1360x768                                             | 2         | 0.16%   |
| Unknown LCD Monitor SAMSUNG                                              | 2         | 0.16%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 2         | 0.16%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                  | 2         | 0.16%   |
| Sharp LCD Monitor SHP13CA 1280x800 331x207mm 15.4-inch                   | 2         | 0.16%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch     | 2         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 371       | 31.28%  |
| 1366x768 (WXGA)    | 240       | 20.24%  |
| 1280x800 (WXGA)    | 63        | 5.31%   |
| 1280x1024 (SXGA)   | 57        | 4.81%   |
| 3840x2160 (4K)     | 55        | 4.64%   |
| 1600x900 (HD+)     | 54        | 4.55%   |
| 1680x1050 (WSXGA+) | 51        | 4.3%    |
| Unknown            | 48        | 4.05%   |
| 1440x900 (WXGA+)   | 43        | 3.63%   |
| 2560x1440 (QHD)    | 38        | 3.2%    |
| 1024x600           | 30        | 2.53%   |
| 1920x1200 (WUXGA)  | 21        | 1.77%   |
| 1024x768 (XGA)     | 20        | 1.69%   |
| 1360x768           | 19        | 1.6%    |
| 2560x1080          | 9         | 0.76%   |
| 3440x1440          | 8         | 0.67%   |
| 3200x1800 (QHD+)   | 6         | 0.51%   |
| 1280x720 (HD)      | 6         | 0.51%   |
| 2560x1600          | 5         | 0.42%   |
| 2160x1440          | 5         | 0.42%   |
| 1920x540           | 5         | 0.42%   |
| 1600x1200          | 4         | 0.34%   |
| 3840x2400          | 2         | 0.17%   |
| 3840x1200          | 2         | 0.17%   |
| 3840x1080          | 2         | 0.17%   |
| 3072x1920          | 2         | 0.17%   |
| 2880x1800          | 2         | 0.17%   |
| 1680x945           | 2         | 0.17%   |
| 1280x960           | 2         | 0.17%   |
| 7120x1080          | 1         | 0.08%   |
| 3840x1303          | 1         | 0.08%   |
| 3456x2160          | 1         | 0.08%   |
| 3360x1080          | 1         | 0.08%   |
| 3286x1080          | 1         | 0.08%   |
| 3200x1200          | 1         | 0.08%   |
| 3200x1080          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2732x768           | 1         | 0.08%   |
| 2520x1680          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 294       | 24.34%  |
| 14      | 102       | 8.44%   |
| Unknown | 101       | 8.36%   |
| 13      | 86        | 7.12%   |
| 17      | 70        | 5.79%   |
| 24      | 69        | 5.71%   |
| 21      | 64        | 5.3%    |
| 23      | 59        | 4.88%   |
| 27      | 58        | 4.8%    |
| 19      | 43        | 3.56%   |
| 20      | 35        | 2.9%    |
| 10      | 34        | 2.81%   |
| 18      | 29        | 2.4%    |
| 22      | 26        | 2.15%   |
| 31      | 17        | 1.41%   |
| 12      | 15        | 1.24%   |
| 34      | 13        | 1.08%   |
| 11      | 12        | 0.99%   |
| 16      | 10        | 0.83%   |
| 84      | 9         | 0.75%   |
| 32      | 9         | 0.75%   |
| 72      | 7         | 0.58%   |
| 25      | 7         | 0.58%   |
| 54      | 6         | 0.5%    |
| 40      | 5         | 0.41%   |
| 26      | 4         | 0.33%   |
| 52      | 3         | 0.25%   |
| 28      | 3         | 0.25%   |
| 8       | 3         | 0.25%   |
| 42      | 2         | 0.17%   |
| 30      | 2         | 0.17%   |
| 86      | 1         | 0.08%   |
| 70      | 1         | 0.08%   |
| 64      | 1         | 0.08%   |
| 60      | 1         | 0.08%   |
| 50      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 44      | 1         | 0.08%   |
| 39      | 1         | 0.08%   |
| 35      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 454       | 37.96%  |
| 501-600     | 182       | 15.22%  |
| 401-500     | 171       | 14.3%   |
| 201-300     | 111       | 9.28%   |
| Unknown     | 101       | 8.44%   |
| 351-400     | 82        | 6.86%   |
| 601-700     | 28        | 2.34%   |
| 701-800     | 22        | 1.84%   |
| 1501-2000   | 17        | 1.42%   |
| 1001-1500   | 14        | 1.17%   |
| 801-900     | 7         | 0.59%   |
| 101-200     | 4         | 0.33%   |
| 901-1000    | 3         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 739       | 65.75%  |
| 16/10   | 176       | 15.66%  |
| Unknown | 90        | 8.01%   |
| 5/4     | 54        | 4.8%    |
| 4/3     | 35        | 3.11%   |
| 21/9    | 15        | 1.33%   |
| 3/2     | 11        | 0.98%   |
| 32/9    | 2         | 0.18%   |
| 6/5     | 1         | 0.09%   |
| 0.56    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 293       | 24.4%   |
| 201-250        | 184       | 15.32%  |
| 81-90          | 145       | 12.07%  |
| Unknown        | 101       | 8.41%   |
| 151-200        | 91        | 7.58%   |
| 301-350        | 61        | 5.08%   |
| 141-150        | 55        | 4.58%   |
| 351-500        | 42        | 3.5%    |
| 71-80          | 37        | 3.08%   |
| 41-50          | 34        | 2.83%   |
| 121-130        | 31        | 2.58%   |
| More than 1000 | 30        | 2.5%    |
| 251-300        | 27        | 2.25%   |
| 61-70          | 13        | 1.08%   |
| 131-140        | 13        | 1.08%   |
| 51-60          | 12        | 1%      |
| 501-1000       | 11        | 0.92%   |
| 111-120        | 9         | 0.75%   |
| 91-100         | 8         | 0.67%   |
| 1-40           | 4         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 437       | 36.97%  |
| 101-120       | 339       | 28.68%  |
| 121-160       | 203       | 17.17%  |
| Unknown       | 101       | 8.54%   |
| 161-240       | 46        | 3.89%   |
| 1-50          | 32        | 2.71%   |
| More than 240 | 24        | 2.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1014      | 82.51%  |
| 2     | 128       | 10.41%  |
| 0     | 69        | 5.61%   |
| 3     | 15        | 1.22%   |
| 4     | 2         | 0.16%   |
| 6     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 631       | 33.44%  |
| Intel                             | 485       | 25.7%   |
| Qualcomm Atheros                  | 255       | 13.51%  |
| Broadcom                          | 132       | 7%      |
| Marvell Technology Group          | 55        | 2.91%   |
| Broadcom Limited                  | 45        | 2.38%   |
| Nvidia                            | 33        | 1.75%   |
| Ralink                            | 32        | 1.7%    |
| Ralink Technology                 | 28        | 1.48%   |
| TP-Link                           | 22        | 1.17%   |
| VIA Technologies                  | 12        | 0.64%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.64%   |
| NetGear                           | 12        | 0.64%   |
| MediaTek                          | 11        | 0.58%   |
| Samsung Electronics               | 10        | 0.53%   |
| ASIX Electronics                  | 8         | 0.42%   |
| Qualcomm Atheros Communications   | 7         | 0.37%   |
| Xiaomi                            | 6         | 0.32%   |
| Ericsson Business Mobile Networks | 6         | 0.32%   |
| D-Link System                     | 6         | 0.32%   |
| D-Link                            | 6         | 0.32%   |
| Qualcomm                          | 4         | 0.21%   |
| Huawei Technologies               | 4         | 0.21%   |
| 3Com                              | 4         | 0.21%   |
| Sierra Wireless                   | 3         | 0.16%   |
| JMicron Technology                | 3         | 0.16%   |
| Dell                              | 3         | 0.16%   |
| ASUSTek Computer                  | 3         | 0.16%   |
| Aquantia                          | 3         | 0.16%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.11%   |
| Sitecom Europe                    | 2         | 0.11%   |
| Motorola PCS                      | 2         | 0.11%   |
| Motorola                          | 2         | 0.11%   |
| Linksys                           | 2         | 0.11%   |
| Lenovo                            | 2         | 0.11%   |
| ICS Advent                        | 2         | 0.11%   |
| FIBOCOM                           | 2         | 0.11%   |
| DisplayLink                       | 2         | 0.11%   |
| AVM                               | 2         | 0.11%   |
| ZyDAS                             | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 398       | 18.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 111       | 5.08%   |
| Intel Wireless 8265 / 8275                                              | 39        | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 38        | 1.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 34        | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 25        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 21        | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 19        | 0.87%   |
| Nvidia MCP61 Ethernet                                                   | 18        | 0.82%   |
| Intel Wireless 7265                                                     | 18        | 0.82%   |
| Intel Wireless 8260                                                     | 17        | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 0.69%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 14        | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 0.6%    |
| Intel I211 Gigabit Network Connection                                   | 13        | 0.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 0.6%    |
| Intel Centrino Advanced-N 6200                                          | 13        | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 0.6%    |
| Intel 82567LM Gigabit Network Connection                                | 13        | 0.6%    |
| Intel Wireless 3165                                                     | 12        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 0.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 11        | 0.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                                   | 11        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                   | 11        | 0.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                                | 11        | 0.5%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 11        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 334       | 35.46%  |
| Qualcomm Atheros                      | 199       | 21.13%  |
| Realtek Semiconductor                 | 160       | 16.99%  |
| Broadcom                              | 80        | 8.49%   |
| Ralink                                | 32        | 3.4%    |
| Ralink Technology                     | 28        | 2.97%   |
| Broadcom Limited                      | 26        | 2.76%   |
| TP-Link                               | 21        | 2.23%   |
| NetGear                               | 12        | 1.27%   |
| MediaTek                              | 10        | 1.06%   |
| Qualcomm Atheros Communications       | 7         | 0.74%   |
| D-Link                                | 6         | 0.64%   |
| Sierra Wireless                       | 3         | 0.32%   |
| ASUSTek Computer                      | 3         | 0.32%   |
| Sitecom Europe                        | 2         | 0.21%   |
| Marvell Technology Group              | 2         | 0.21%   |
| Linksys                               | 2         | 0.21%   |
| FIBOCOM                               | 2         | 0.21%   |
| Dell                                  | 2         | 0.21%   |
| D-Link System                         | 2         | 0.21%   |
| AVM                                   | 2         | 0.21%   |
| ZyDAS                                 | 1         | 0.11%   |
| PLANEX                                | 1         | 0.11%   |
| Microsoft                             | 1         | 0.11%   |
| Mercucys                              | 1         | 0.11%   |
| Intersil                              | 1         | 0.11%   |
| Edimax Technology                     | 1         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 39        | 4.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 38        | 4.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 3.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 2.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 2.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 19        | 2.01%   |
| Intel Wireless 7265                                                     | 18        | 1.9%    |
| Intel Wireless 8260                                                     | 17        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 15        | 1.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 1.59%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 1.37%   |
| Intel Centrino Advanced-N 6200                                          | 13        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.37%   |
| Intel Wireless 3165                                                     | 12        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.16%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 11        | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 1.06%   |
| Intel Wireless 7260                                                     | 10        | 1.06%   |
| Ralink MT7601U Wireless Adapter                                         | 9         | 0.95%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 0.95%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 9         | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 8         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.85%   |
| Realtek 802.11ac NIC                                                    | 8         | 0.85%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 0.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 8         | 0.85%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 8         | 0.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 569       | 48.22%  |
| Intel                            | 277       | 23.47%  |
| Qualcomm Atheros                 | 78        | 6.61%   |
| Broadcom                         | 64        | 5.42%   |
| Marvell Technology Group         | 53        | 4.49%   |
| Nvidia                           | 33        | 2.8%    |
| Broadcom Limited                 | 19        | 1.61%   |
| VIA Technologies                 | 12        | 1.02%   |
| Silicon Integrated Systems [SiS] | 12        | 1.02%   |
| Samsung Electronics              | 10        | 0.85%   |
| ASIX Electronics                 | 8         | 0.68%   |
| Xiaomi                           | 6         | 0.51%   |
| Qualcomm                         | 4         | 0.34%   |
| D-Link System                    | 4         | 0.34%   |
| 3Com                             | 4         | 0.34%   |
| JMicron Technology               | 3         | 0.25%   |
| Huawei Technologies              | 3         | 0.25%   |
| Aquantia                         | 3         | 0.25%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.17%   |
| Lenovo                           | 2         | 0.17%   |
| ICS Advent                       | 2         | 0.17%   |
| DisplayLink                      | 2         | 0.17%   |
| vivo                             | 1         | 0.08%   |
| TP-Link                          | 1         | 0.08%   |
| Standard Microsystems [SMC]      | 1         | 0.08%   |
| Standard Microsystems            | 1         | 0.08%   |
| Spreadtrum Communications        | 1         | 0.08%   |
| Motorola PCS                     | 1         | 0.08%   |
| MediaTek                         | 1         | 0.08%   |
| HMD Global                       | 1         | 0.08%   |
| Attansic Technology              | 1         | 0.08%   |
| Archos                           | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 398       | 33.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 111       | 9.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 34        | 2.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 25        | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 21        | 1.75%   |
| Nvidia MCP61 Ethernet                                                  | 18        | 1.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 14        | 1.17%   |
| Intel I211 Gigabit Network Connection                                  | 13        | 1.09%   |
| Intel 82567LM Gigabit Network Connection                               | 13        | 1.09%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 11        | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                  | 11        | 0.92%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 0.92%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 10        | 0.84%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 10        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                   | 10        | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9         | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 9         | 0.75%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 0.75%   |
| Intel 82579V Gigabit Network Connection                                | 9         | 0.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 8         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 7         | 0.58%   |
| Intel PRO/100 VE Network Connection                                    | 7         | 0.58%   |
| Intel I210 Gigabit Network Connection                                  | 7         | 0.58%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 7         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 6         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 6         | 0.5%    |
| Intel Ethernet Connection I217-V                                       | 6         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 6         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 6         | 0.5%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 6         | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 6         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1112      | 54.14%  |
| WiFi     | 901       | 43.87%  |
| Modem    | 39        | 1.9%    |
| Unknown  | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 693       | 55.04%  |
| Ethernet | 566       | 44.96%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 688       | 56.39%  |
| 1     | 484       | 39.67%  |
| 0     | 25        | 2.05%   |
| 3     | 17        | 1.39%   |
| 4     | 3         | 0.25%   |
| 5     | 2         | 0.16%   |
| 7     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1085      | 88%     |
| Yes  | 148       | 12%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 207       | 39.2%   |
| Qualcomm Atheros Communications | 49        | 9.28%   |
| Realtek Semiconductor           | 43        | 8.14%   |
| Cambridge Silicon Radio         | 43        | 8.14%   |
| Broadcom                        | 41        | 7.77%   |
| IMC Networks                    | 25        | 4.73%   |
| Apple                           | 25        | 4.73%   |
| Foxconn / Hon Hai               | 18        | 3.41%   |
| Lite-On Technology              | 12        | 2.27%   |
| Hewlett-Packard                 | 12        | 2.27%   |
| Ralink                          | 9         | 1.7%    |
| ASUSTek Computer                | 7         | 1.33%   |
| Toshiba                         | 6         | 1.14%   |
| Dell                            | 6         | 1.14%   |
| MediaTek                        | 5         | 0.95%   |
| Alps Electric                   | 3         | 0.57%   |
| TP-Link                         | 2         | 0.38%   |
| Taiyo Yuden                     | 2         | 0.38%   |
| Realtek                         | 2         | 0.38%   |
| Foxconn International           | 2         | 0.38%   |
| Smart Modular Technologies      | 1         | 0.19%   |
| Qcom                            | 1         | 0.19%   |
| Micro Star International        | 1         | 0.19%   |
| Integrated System Solution      | 1         | 0.19%   |
| Dynex                           | 1         | 0.19%   |
| D-Link System                   | 1         | 0.19%   |
| Conwise Technology              | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |
| Askey Computer                  | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 51        | 9.66%   |
| Intel Bluetooth wireless interface                  | 49        | 9.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 43        | 8.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 6.06%   |
| Intel AX201 Bluetooth                               | 27        | 5.11%   |
| Realtek Bluetooth Radio                             | 26        | 4.92%   |
| Qualcomm Atheros  Bluetooth Device                  | 25        | 4.73%   |
| Intel AX200 Bluetooth                               | 15        | 2.84%   |
| Apple Bluetooth HCI                                 | 13        | 2.46%   |
| IMC Networks Bluetooth Radio                        | 12        | 2.27%   |
| Ralink RT3290 Bluetooth                             | 9         | 1.7%    |
| Intel AX211 Bluetooth                               | 8         | 1.52%   |
| Apple Bluetooth Host Controller                     | 8         | 1.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 1.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 6         | 1.14%   |
| IMC Networks Bluetooth Device                       | 6         | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.95%   |
| MediaTek Wireless_Device                            | 5         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 5         | 0.95%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 0.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.76%   |
| Intel AX210 Bluetooth                               | 4         | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.76%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.76%   |
| Toshiba Bluetooth Device                            | 3         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.57%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 3         | 0.57%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.57%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.57%   |
| Broadcom BCM2045 Bluetooth                          | 3         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 916       | 61.56%  |
| AMD                              | 222       | 14.92%  |
| Nvidia                           | 216       | 14.52%  |
| VIA Technologies                 | 17        | 1.14%   |
| C-Media Electronics              | 16        | 1.08%   |
| Silicon Integrated Systems [SiS] | 12        | 0.81%   |
| Logitech                         | 9         | 0.6%    |
| GN Netcom                        | 7         | 0.47%   |
| Creative Labs                    | 7         | 0.47%   |
| Realtek Semiconductor            | 5         | 0.34%   |
| Plantronics                      | 4         | 0.27%   |
| JMTek                            | 4         | 0.27%   |
| Generalplus Technology           | 3         | 0.2%    |
| Ensoniq                          | 3         | 0.2%    |
| ASUSTek Computer                 | 3         | 0.2%    |
| Texas Instruments                | 2         | 0.13%   |
| Syntek                           | 2         | 0.13%   |
| SteelSeries ApS                  | 2         | 0.13%   |
| Sennheiser Communications        | 2         | 0.13%   |
| Lenovo                           | 2         | 0.13%   |
| KORG                             | 2         | 0.13%   |
| Kingston Technology              | 2         | 0.13%   |
| DSEA A/S                         | 2         | 0.13%   |
| Creative Technology              | 2         | 0.13%   |
| Corsair                          | 2         | 0.13%   |
| Blue Microphones                 | 2         | 0.13%   |
| BEHRINGER International          | 2         | 0.13%   |
| Apple                            | 2         | 0.13%   |
| ZOOM                             | 1         | 0.07%   |
| Yamaha                           | 1         | 0.07%   |
| ULi Electronics                  | 1         | 0.07%   |
| TerraTec Electronic              | 1         | 0.07%   |
| Tenx Technology                  | 1         | 0.07%   |
| SAVITECH                         | 1         | 0.07%   |
| Samson Technologies              | 1         | 0.07%   |
| Razer USA                        | 1         | 0.07%   |
| Pioneer DJ                       | 1         | 0.07%   |
| Novra/IDC/Wegener                | 1         | 0.07%   |
| Nordic Semiconductor ASA         | 1         | 0.07%   |
| JOUNIVO                          | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 128       | 7.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 83        | 4.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 80        | 4.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 75        | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 70        | 4.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 50        | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 46        | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 46        | 2.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 39        | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 37        | 2.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 37        | 2.17%   |
| AMD FCH Azalia Controller                                                                         | 37        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 36        | 2.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 36        | 2.11%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 1.41%   |
| Nvidia High Definition Audio Controller                                                           | 23        | 1.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 1.23%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 1.23%   |
| Nvidia MCP61 High Definition Audio                                                                | 19        | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 17        | 1%      |
| Nvidia GP106 High Definition Audio Controller                                                     | 16        | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 16        | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 0.88%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 15        | 0.88%   |
| Intel 200 Series PCH HD Audio                                                                     | 15        | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 15        | 0.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 14        | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 0.76%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13        | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 13        | 0.76%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 0.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 13        | 0.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 12        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 107       | 18.84%  |
| SK hynix                     | 98        | 17.25%  |
| Kingston                     | 79        | 13.91%  |
| Unknown                      | 74        | 13.03%  |
| Micron Technology            | 51        | 8.98%   |
| Crucial                      | 28        | 4.93%   |
| Corsair                      | 25        | 4.4%    |
| G.Skill                      | 20        | 3.52%   |
| Ramaxel Technology           | 16        | 2.82%   |
| Smart                        | 11        | 1.94%   |
| Nanya Technology             | 7         | 1.23%   |
| Elpida                       | 7         | 1.23%   |
| A-DATA Technology            | 7         | 1.23%   |
| Transcend                    | 6         | 1.06%   |
| Patriot                      | 4         | 0.7%    |
| Unknown (ABCD)               | 3         | 0.53%   |
| Silicon Power                | 2         | 0.35%   |
| Goldkey                      | 2         | 0.35%   |
| Walton Chaintech             | 1         | 0.18%   |
| Unknown (89F7)               | 1         | 0.18%   |
| Unknown (0x7C00000000000000) | 1         | 0.18%   |
| Unknown (0x0080)             | 1         | 0.18%   |
| Unknown (07FB)               | 1         | 0.18%   |
| Unifosa                      | 1         | 0.18%   |
| Timetec                      | 1         | 0.18%   |
| Team                         | 1         | 0.18%   |
| SHARETRONIC                  | 1         | 0.18%   |
| Qumo                         | 1         | 0.18%   |
| PUSKILL                      | 1         | 0.18%   |
| PNY                          | 1         | 0.18%   |
| Netlist                      | 1         | 0.18%   |
| High Bridge                  | 1         | 0.18%   |
| Hewlett-Packard              | 1         | 0.18%   |
| Exceleram                    | 1         | 0.18%   |
| ASint Technology             | 1         | 0.18%   |
| Apacer                       | 1         | 0.18%   |
| Ankowall                     | 1         | 0.18%   |
| A Force                      | 1         | 0.18%   |
| Unknown                      | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.31%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.82%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s              | 5         | 0.82%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 4         | 0.65%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 4         | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.65%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.65%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB Row Of Chips DDR4 3200MT/s   | 4         | 0.65%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 3         | 0.49%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.49%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 3         | 0.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.49%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.49%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 3         | 0.49%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 3         | 0.49%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.49%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 3         | 0.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 2         | 0.33%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 2         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.33%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.33%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                           | 2         | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.33%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 2         | 0.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.33%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 0.33%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.33%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.33%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 188       | 38.06%  |
| DDR3    | 186       | 37.65%  |
| DDR2    | 38        | 7.69%   |
| Unknown | 21        | 4.25%   |
| LPDDR4  | 15        | 3.04%   |
| SDRAM   | 14        | 2.83%   |
| LPDDR3  | 14        | 2.83%   |
| DDR5    | 9         | 1.82%   |
| DDR     | 5         | 1.01%   |
| LPDDR5  | 2         | 0.4%    |
| DRAM    | 2         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 277       | 55.62%  |
| DIMM         | 182       | 36.55%  |
| Row Of Chips | 35        | 7.03%   |
| Chip         | 3         | 0.6%    |
| FB-DIMM      | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 200       | 36.56%  |
| 4096  | 141       | 25.78%  |
| 16384 | 83        | 15.17%  |
| 2048  | 76        | 13.89%  |
| 1024  | 30        | 5.48%   |
| 32768 | 11        | 2.01%   |
| 512   | 5         | 0.91%   |
| 256   | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 115       | 21.46%  |
| 2667    | 78        | 14.55%  |
| 3200    | 59        | 11.01%  |
| 1333    | 49        | 9.14%   |
| 2133    | 41        | 7.65%   |
| 2400    | 29        | 5.41%   |
| 667     | 21        | 3.92%   |
| Unknown | 21        | 3.92%   |
| 1334    | 19        | 3.54%   |
| 800     | 14        | 2.61%   |
| 1867    | 8         | 1.49%   |
| 4800    | 7         | 1.31%   |
| 1067    | 6         | 1.12%   |
| 1066    | 6         | 1.12%   |
| 3600    | 5         | 0.93%   |
| 533     | 5         | 0.93%   |
| 4267    | 4         | 0.75%   |
| 3000    | 4         | 0.75%   |
| 2666    | 4         | 0.75%   |
| 1866    | 4         | 0.75%   |
| 8400    | 3         | 0.56%   |
| 6400    | 3         | 0.56%   |
| 3400    | 3         | 0.56%   |
| 3266    | 3         | 0.56%   |
| 400     | 3         | 0.56%   |
| 4266    | 2         | 0.37%   |
| 4199    | 2         | 0.37%   |
| 3866    | 2         | 0.37%   |
| 2200    | 2         | 0.37%   |
| 2048    | 2         | 0.37%   |
| 1800    | 2         | 0.37%   |
| 5600    | 1         | 0.19%   |
| 3733    | 1         | 0.19%   |
| 3100    | 1         | 0.19%   |
| 2934    | 1         | 0.19%   |
| 2733    | 1         | 0.19%   |
| 2473    | 1         | 0.19%   |
| 2187    | 1         | 0.19%   |
| 2000    | 1         | 0.19%   |
| 1639    | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 24        | 48.98%  |
| Canon                    | 9         | 18.37%  |
| Samsung Electronics      | 5         | 10.2%   |
| Brother Industries       | 3         | 6.12%   |
| Seiko Epson              | 2         | 4.08%   |
| Zhuhai Poskey Technology | 1         | 2.04%   |
| Xerox                    | 1         | 2.04%   |
| Ricoh                    | 1         | 2.04%   |
| QinHeng Electronics      | 1         | 2.04%   |
| Lexmark International    | 1         | 2.04%   |
| Kyocera                  | 1         | 2.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP OfficeJet 3830 series             | 2         | 4%      |
| HP LaserJet 1018                     | 2         | 4%      |
| Zhuhai Poskey Printer                | 1         | 2%      |
| Xerox Phaser 6130N                   | 1         | 2%      |
| Seiko Epson L375 Series              | 1         | 2%      |
| Seiko Epson L365 Series              | 1         | 2%      |
| Samsung SCX-472x Series              | 1         | 2%      |
| Samsung SCX-3200 Series              | 1         | 2%      |
| Samsung ML-1640 Series Laser Printer | 1         | 2%      |
| Samsung M267x 287x Series            | 1         | 2%      |
| Samsung CLX-3180 Series              | 1         | 2%      |
| Ricoh SP 150SUw                      | 1         | 2%      |
| QinHeng CH340S                       | 1         | 2%      |
| Lexmark International CS727de        | 1         | 2%      |
| Kyocera FS-1020D Printer             | 1         | 2%      |
| HP Officejet 4500 G510g-m            | 1         | 2%      |
| HP LaserJet P2055 series             | 1         | 2%      |
| HP LaserJet M101-M106                | 1         | 2%      |
| HP LaserJet 1020                     | 1         | 2%      |
| HP HP LaserJet M14-M17               | 1         | 2%      |
| HP EWS UPD                           | 1         | 2%      |
| HP ENVY Photo 7800 series            | 1         | 2%      |
| HP ENVY Photo 6200 series            | 1         | 2%      |
| HP ENVY 4500 series                  | 1         | 2%      |
| HP Deskjet F4500 series              | 1         | 2%      |
| HP DeskJet F2100 Printer series      | 1         | 2%      |
| HP DeskJet 930c                      | 1         | 2%      |
| HP DeskJet 5650c                     | 1         | 2%      |
| HP DeskJet 2700 series               | 1         | 2%      |
| HP DeskJet 2600 series               | 1         | 2%      |
| HP Deskjet 2540 series               | 1         | 2%      |
| HP DeskJet 2130 series               | 1         | 2%      |
| HP Deskjet 1050 J410                 | 1         | 2%      |
| HP ColorLaserJet M253-M254           | 1         | 2%      |
| HP Color LaserJet 2605               | 1         | 2%      |
| Canon TR8500 series                  | 1         | 2%      |
| Canon PIXMA MX920 Series             | 1         | 2%      |
| Canon PIXMA MX720 Series             | 1         | 2%      |
| Canon PIXMA MX370 Series             | 1         | 2%      |
| Canon PIXMA MP250                    | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 37.5%   |
| Hewlett-Packard | 2         | 25%     |
| Seiko Epson     | 1         | 12.5%   |
| Mustek Systems  | 1         | 12.5%   |
| AGFA-Gevaert NV | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 2         | 25%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 12.5%   |
| Mustek Systems ScanExpress 1200 CU Plus       | 1         | 12.5%   |
| HP ScanJet 5200c                              | 1         | 12.5%   |
| HP ScanJet 3570c                              | 1         | 12.5%   |
| Canon CanoScan LiDE 220                       | 1         | 12.5%   |
| AGFA-Gevaert NV Snapscan e40                  | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 125       | 19.75%  |
| Microdia                               | 65        | 10.27%  |
| Realtek Semiconductor                  | 62        | 9.79%   |
| IMC Networks                           | 43        | 6.79%   |
| Suyin                                  | 36        | 5.69%   |
| Logitech                               | 33        | 5.21%   |
| Sunplus Innovation Technology          | 30        | 4.74%   |
| Bison Electronics                      | 27        | 4.27%   |
| Apple                                  | 27        | 4.27%   |
| Cheng Uei Precision Industry (Foxlink) | 21        | 3.32%   |
| Quanta                                 | 18        | 2.84%   |
| Acer                                   | 17        | 2.69%   |
| Syntek                                 | 13        | 2.05%   |
| Lite-On Technology                     | 13        | 2.05%   |
| Lenovo                                 | 10        | 1.58%   |
| Silicon Motion                         | 9         | 1.42%   |
| Samsung Electronics                    | 8         | 1.26%   |
| Microsoft                              | 8         | 1.26%   |
| Importek                               | 6         | 0.95%   |
| Alcor Micro                            | 6         | 0.95%   |
| Z-Star Microelectronics                | 4         | 0.63%   |
| Luxvisions Innotech Limited            | 4         | 0.63%   |
| GEMBIRD                                | 4         | 0.63%   |
| Intel                                  | 3         | 0.47%   |
| Generalplus Technology                 | 3         | 0.47%   |
| SunplusIT                              | 2         | 0.32%   |
| Ricoh                                  | 2         | 0.32%   |
| Primax Electronics                     | 2         | 0.32%   |
| Philips (or NXP)                       | 2         | 0.32%   |
| Hewlett-Packard                        | 2         | 0.32%   |
| eMPIA Technology                       | 2         | 0.32%   |
| DigiTech                               | 2         | 0.32%   |
| Cubeternet                             | 2         | 0.32%   |
| ALi                                    | 2         | 0.32%   |
| YGTek                                  | 1         | 0.16%   |
| USB3.0 HD Audio Capture                | 1         | 0.16%   |
| USB Camera CS                          | 1         | 0.16%   |
| Trust                                  | 1         | 0.16%   |
| STEREOLABS                             | 1         | 0.16%   |
| Sonix Technology                       | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD             | 23        | 3.63%   |
| Microdia Integrated_Webcam_HD            | 23        | 3.63%   |
| Chicony Integrated Camera                | 11        | 1.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 10        | 1.58%   |
| Sunplus Integrated_Webcam_HD             | 9         | 1.42%   |
| Logitech Webcam C270                     | 9         | 1.42%   |
| IMC Networks Integrated Camera           | 9         | 1.42%   |
| Chicony HP HD Camera                     | 9         | 1.42%   |
| Samsung Galaxy series, misc. (MTP mode)  | 7         | 1.1%    |
| Realtek USB Camera                       | 7         | 1.1%    |
| Apple Built-in iSight                    | 7         | 1.1%    |
| Syntek Integrated Camera                 | 6         | 0.95%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 6         | 0.95%   |
| Lite-On Integrated Camera                | 6         | 0.95%   |
| Lenovo Integrated Webcam [R5U877]        | 6         | 0.95%   |
| Chicony Lenovo EasyCamera                | 6         | 0.95%   |
| Sunplus Asus Webcam                      | 5         | 0.79%   |
| Realtek Integrated Webcam HD             | 5         | 0.79%   |
| Realtek Integrated Webcam                | 5         | 0.79%   |
| Microdia Webcam Vitade AF                | 5         | 0.79%   |
| IMC Networks USB2.0 HD UVC WebCam        | 5         | 0.79%   |
| Chicony USB 2.0 Camera                   | 5         | 0.79%   |
| Chicony Camera                           | 5         | 0.79%   |
| Suyin HP Truevision HD                   | 4         | 0.63%   |
| Sunplus HD WebCam                        | 4         | 0.63%   |
| Realtek USB2.0 HD UVC WebCam             | 4         | 0.63%   |
| Microsoft LifeCam HD-3000                | 4         | 0.63%   |
| Microdia Sonix USB 2.0 Camera            | 4         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD     | 4         | 0.63%   |
| Logitech HD Webcam C615                  | 4         | 0.63%   |
| Logitech HD Pro Webcam C920              | 4         | 0.63%   |
| IMC Networks USB 2.0 Camera              | 4         | 0.63%   |
| IMC Networks Lenovo EasyCamera           | 4         | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam            | 4         | 0.63%   |
| Chicony HP Wide Vision HD Camera         | 4         | 0.63%   |
| Chicony FJ Camera                        | 4         | 0.63%   |
| Bison Lenovo Integrated Webcam           | 4         | 0.63%   |
| Apple Built-in iSight [Micron]           | 4         | 0.63%   |
| Syntek Lenovo EasyCamera                 | 3         | 0.47%   |
| Suyin Integrated_Webcam_HD               | 3         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 55        | 42.64%  |
| Synaptics                          | 22        | 17.05%  |
| AuthenTec                          | 17        | 13.18%  |
| Shenzhen Goodix Technology         | 11        | 8.53%   |
| Upek                               | 9         | 6.98%   |
| STMicroelectronics                 | 5         | 3.88%   |
| LighTuning Technology              | 4         | 3.1%    |
| Elan Microelectronics              | 4         | 3.1%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.78%   |
| DigitalPersona                     | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 8.53%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 6.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 5.43%   |
| AuthenTec AES2810                                                          | 6         | 4.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 3.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 3.88%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 3.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 3.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 3.1%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.1%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.1%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.1%    |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 3.1%    |
| Shenzhen Goodix FingerPrint                                                | 4         | 3.1%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 3.1%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.33%   |
| Validity Sensors VFS491                                                    | 3         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.33%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.33%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.33%   |
| AuthenTec AES1600                                                          | 3         | 2.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 1.55%   |
| Synaptics UWP WBDI                                                         | 2         | 1.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.55%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.55%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.55%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.78%   |
| Synaptics WBDI                                                             | 1         | 0.78%   |
| Synaptics TouchPad                                                         | 1         | 0.78%   |
| Synaptics  WBDI                                                            | 1         | 0.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.78%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.78%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.78%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 18        | 40.91%  |
| O2 Micro         | 11        | 25%     |
| Alcor Micro      | 8         | 18.18%  |
| SCM Microsystems | 3         | 6.82%   |
| Lenovo           | 3         | 6.82%   |
| Yubico.com       | 1         | 2.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 17.78%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 15.56%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 13.33%  |
| Broadcom 5880                                                                | 5         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 8.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 8.89%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.67%   |
| Broadcom 58200                                                               | 3         | 6.67%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.22%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 2.22%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 2.22%   |
| SCM Microsystems Elektra331-USB SmartCard Reader                             | 1         | 2.22%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 2.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 830       | 67.7%   |
| 1     | 307       | 25.04%  |
| 2     | 64        | 5.22%   |
| 3     | 12        | 0.98%   |
| 4     | 8         | 0.65%   |
| 5     | 3         | 0.24%   |
| 7     | 1         | 0.08%   |
| 6     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 157       | 30.19%  |
| Fingerprint reader       | 127       | 24.42%  |
| Net/wireless             | 61        | 11.73%  |
| Chipcard                 | 43        | 8.27%   |
| Communication controller | 35        | 6.73%   |
| Modem                    | 20        | 3.85%   |
| Multimedia controller    | 16        | 3.08%   |
| Bluetooth                | 13        | 2.5%    |
| Storage                  | 12        | 2.31%   |
| Sound                    | 12        | 2.31%   |
| Camera                   | 9         | 1.73%   |
| Unassigned class         | 4         | 0.77%   |
| Card reader              | 3         | 0.58%   |
| Flash memory             | 2         | 0.38%   |
| Dvb card                 | 2         | 0.38%   |
| Tv card                  | 1         | 0.19%   |
| Storage/raid             | 1         | 0.19%   |
| Storage/nvme             | 1         | 0.19%   |
| Net/ethernet             | 1         | 0.19%   |

