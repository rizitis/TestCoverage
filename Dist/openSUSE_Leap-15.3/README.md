openSUSE Leap-15.3 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE_Leap-15.3/Desktop/README.md) and [notebooks](/Dist/openSUSE_Leap-15.3/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 197

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | PCx0Dx                      | Notebook    | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [e5b5f4792c](https://linux-hardware.org/?probe=e5b5f4792c) | Feb 19, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [c73a9b9ee2](https://linux-hardware.org/?probe=c73a9b9ee2) | Feb 19, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [a4b5bc192d](https://linux-hardware.org/?probe=a4b5bc192d) | Jan 06, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1212530d94](https://linux-hardware.org/?probe=1212530d94) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [19e8973a92](https://linux-hardware.org/?probe=19e8973a92) | Dec 18, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [780eecc5e8](https://linux-hardware.org/?probe=780eecc5e8) | Dec 12, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [57a9a5fbf8](https://linux-hardware.org/?probe=57a9a5fbf8) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [8b8ac358e4](https://linux-hardware.org/?probe=8b8ac358e4) | Nov 21, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [776a9bc0b6](https://linux-hardware.org/?probe=776a9bc0b6) | Nov 09, 2022 |
| Gateway       | NV54 Series                 | Notebook    | [88b57ed4e4](https://linux-hardware.org/?probe=88b57ed4e4) | Oct 09, 2022 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [7532844cd7](https://linux-hardware.org/?probe=7532844cd7) | Sep 11, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| Biostar       | H77MU3                      | Desktop     | [20ba4d44ed](https://linux-hardware.org/?probe=20ba4d44ed) | Sep 05, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [db3bc987b6](https://linux-hardware.org/?probe=db3bc987b6) | Aug 29, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [88ad38d9f7](https://linux-hardware.org/?probe=88ad38d9f7) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [73b611ea50](https://linux-hardware.org/?probe=73b611ea50) | Aug 17, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [d9fa82e283](https://linux-hardware.org/?probe=d9fa82e283) | Aug 15, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [56c2008bb6](https://linux-hardware.org/?probe=56c2008bb6) | Jul 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [9de0586493](https://linux-hardware.org/?probe=9de0586493) | Jul 01, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [8c7b7c1b45](https://linux-hardware.org/?probe=8c7b7c1b45) | Jul 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3b177fe0af](https://linux-hardware.org/?probe=3b177fe0af) | Jun 17, 2022 |
| HP            | Mini 210-1000               | Notebook    | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [325cde32e5](https://linux-hardware.org/?probe=325cde32e5) | Jun 06, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [6abee365c1](https://linux-hardware.org/?probe=6abee365c1) | Jun 06, 2022 |
| ASUSTek       | G771JW                      | Notebook    | [b6c03572a0](https://linux-hardware.org/?probe=b6c03572a0) | May 31, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7fe5175e37](https://linux-hardware.org/?probe=7fe5175e37) | May 30, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [66b453536a](https://linux-hardware.org/?probe=66b453536a) | May 24, 2022 |
| HP            | 2820h                       | Desktop     | [af311c3a41](https://linux-hardware.org/?probe=af311c3a41) | May 18, 2022 |
| HP            | 250 G3                      | Notebook    | [73dbcb9953](https://linux-hardware.org/?probe=73dbcb9953) | May 17, 2022 |
| HP            | 250 G3                      | Notebook    | [a12d6710cf](https://linux-hardware.org/?probe=a12d6710cf) | May 16, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b31c3ee2d6](https://linux-hardware.org/?probe=b31c3ee2d6) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | Notebook    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [4142d08db8](https://linux-hardware.org/?probe=4142d08db8) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [699a7ea54b](https://linux-hardware.org/?probe=699a7ea54b) | May 04, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [344c43c31a](https://linux-hardware.org/?probe=344c43c31a) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [e168087bf0](https://linux-hardware.org/?probe=e168087bf0) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [c258235d05](https://linux-hardware.org/?probe=c258235d05) | Apr 28, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [26727e92e4](https://linux-hardware.org/?probe=26727e92e4) | Apr 22, 2022 |
| HP            | Notebook                    | Notebook    | [65e86d0311](https://linux-hardware.org/?probe=65e86d0311) | Apr 21, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [aa67c47f23](https://linux-hardware.org/?probe=aa67c47f23) | Apr 13, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | Desktop     | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [05c0be34be](https://linux-hardware.org/?probe=05c0be34be) | Mar 18, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0d9c88498d](https://linux-hardware.org/?probe=0d9c88498d) | Mar 13, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | 2129                        | Desktop     | [a6b5f98b78](https://linux-hardware.org/?probe=a6b5f98b78) | Mar 02, 2022 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [362c220f2d](https://linux-hardware.org/?probe=362c220f2d) | Feb 20, 2022 |
| MSI           | CX600                       | Notebook    | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b3ff58ce92](https://linux-hardware.org/?probe=b3ff58ce92) | Feb 06, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [29ea90b598](https://linux-hardware.org/?probe=29ea90b598) | Feb 06, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2f03547791](https://linux-hardware.org/?probe=2f03547791) | Feb 05, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [20e910e73b](https://linux-hardware.org/?probe=20e910e73b) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [394132a26d](https://linux-hardware.org/?probe=394132a26d) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| Biostar       | H77MU3                      | Desktop     | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [2000988c8b](https://linux-hardware.org/?probe=2000988c8b) | Jan 10, 2022 |
| HP            | 2B29                        | Desktop     | [cfb166f99c](https://linux-hardware.org/?probe=cfb166f99c) | Jan 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [980348cf8f](https://linux-hardware.org/?probe=980348cf8f) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [87ffc81034](https://linux-hardware.org/?probe=87ffc81034) | Jan 08, 2022 |
| Toshiba       | AS 1301                     | Notebook    | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| Dell          | 0RY007                      | Desktop     | [d51d13fdd1](https://linux-hardware.org/?probe=d51d13fdd1) | Dec 31, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [559c6e472e](https://linux-hardware.org/?probe=559c6e472e) | Dec 30, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f6aeab7c1](https://linux-hardware.org/?probe=6f6aeab7c1) | Dec 20, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [c008e360e7](https://linux-hardware.org/?probe=c008e360e7) | Dec 19, 2021 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [1ff9d84c5f](https://linux-hardware.org/?probe=1ff9d84c5f) | Dec 17, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a5ddb2410e](https://linux-hardware.org/?probe=a5ddb2410e) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e744dbe03d](https://linux-hardware.org/?probe=e744dbe03d) | Dec 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [00a3ad4abc](https://linux-hardware.org/?probe=00a3ad4abc) | Dec 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Dell          | 03015M A09                  | Server      | [c685a0033b](https://linux-hardware.org/?probe=c685a0033b) | Nov 17, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [d50547de1f](https://linux-hardware.org/?probe=d50547de1f) | Nov 15, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [c863f2ca43](https://linux-hardware.org/?probe=c863f2ca43) | Nov 14, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| HP            | 844C                        | Desktop     | [2d709598d7](https://linux-hardware.org/?probe=2d709598d7) | Nov 12, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [aadca45789](https://linux-hardware.org/?probe=aadca45789) | Nov 01, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [d9a12dc22c](https://linux-hardware.org/?probe=d9a12dc22c) | Oct 19, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [34a55551e2](https://linux-hardware.org/?probe=34a55551e2) | Oct 19, 2021 |
| Medion        | E6436 MD61150               | Notebook    | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion        | E6436 MD61150               | Notebook    | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [ce4776505f](https://linux-hardware.org/?probe=ce4776505f) | Oct 03, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [556c37ba9b](https://linux-hardware.org/?probe=556c37ba9b) | Oct 03, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [3cec37b610](https://linux-hardware.org/?probe=3cec37b610) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| Dell          | Precision M6700             | Notebook    | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| VS Company    | G31T-M                      | Desktop     | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| MSI           | X370 GAMING PRO             | Desktop     | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| HP            | 8056                        | Desktop     | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [be3b65a81d](https://linux-hardware.org/?probe=be3b65a81d) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung       | 600B4B/600B5B               | Notebook    | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| Dell          | Precision M6700             | Notebook    | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 8895W9U        | Notebook    | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung       | 600B4B/600B5B               | Notebook    | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | Notebook    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [a22aa3c48c](https://linux-hardware.org/?probe=a22aa3c48c) | Aug 01, 2021 |
| MSI           | B85M-E45                    | Desktop     | [0e20d4cea9](https://linux-hardware.org/?probe=0e20d4cea9) | Jul 30, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [acbcbe74d7](https://linux-hardware.org/?probe=acbcbe74d7) | Jul 22, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| HP            | 8433 11                     | Desktop     | [b079ccb608](https://linux-hardware.org/?probe=b079ccb608) | Jul 15, 2021 |
| MSI           | D2415 S26361-D2415-A21      | Desktop     | [b49400f636](https://linux-hardware.org/?probe=b49400f636) | Jul 11, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | Notebook    | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | Notebook    | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [27a6ac997b](https://linux-hardware.org/?probe=27a6ac997b) | Jul 03, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| HP            | 0A68h                       | Desktop     | [36cfa6a366](https://linux-hardware.org/?probe=36cfa6a366) | Jun 27, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [dfc2f82575](https://linux-hardware.org/?probe=dfc2f82575) | Jun 26, 2021 |
| ASUSTek       | G771JW                      | Notebook    | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Sony          | VPCSB15GB                   | Notebook    | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| HP            | 2AA2                        | Desktop     | [65e7cd2d3e](https://linux-hardware.org/?probe=65e7cd2d3e) | Jun 02, 2021 |
| Sony          | VGN-Z570AN                  | Notebook    | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony          | VGN-Z570AN                  | Notebook    | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| MSI           | GS60 6QE                    | Notebook    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI           | GS60 6QE                    | Notebook    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| HP            | Pavilion dx6500             | Notebook    | [091cc2c616](https://linux-hardware.org/?probe=091cc2c616) | Apr 13, 2021 |
| HP            | Pavilion dx6500             | Notebook    | [6ad0d5c87f](https://linux-hardware.org/?probe=6ad0d5c87f) | Apr 13, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [97a7246099](https://linux-hardware.org/?probe=97a7246099) | Mar 01, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b1e186207c](https://linux-hardware.org/?probe=b1e186207c) | Feb 28, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [fca0fd3336](https://linux-hardware.org/?probe=fca0fd3336) | Jan 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.3.18-59.37-default         | 18        | 12.33%  |
| 5.3.18-59.27-default         | 13        | 8.9%    |
| 5.3.18-59.19-default         | 13        | 8.9%    |
| 5.3.18-57-default            | 8         | 5.48%   |
| 5.3.18-150300.59.49-default  | 8         | 5.48%   |
| 5.3.18-59.5-default          | 6         | 4.11%   |
| 5.3.18-59.24-default         | 6         | 4.11%   |
| 5.3.18-59.16-default         | 6         | 4.11%   |
| 5.3.18-150300.59.54-default  | 6         | 4.11%   |
| 5.3.18-59.10-default         | 5         | 3.42%   |
| 5.3.18-150300.59.63-default  | 5         | 3.42%   |
| 5.3.18-59.34-default         | 4         | 2.74%   |
| 5.3.18-150300.59.87-default  | 4         | 2.74%   |
| 5.3.18-150300.59.60-default  | 4         | 2.74%   |
| 5.3.18-150300.59.68-default  | 3         | 2.05%   |
| 5.3.18-150300.59.43-default  | 3         | 2.05%   |
| 5.3.18-59.27-preempt         | 2         | 1.37%   |
| 5.3.18-59.19-preempt         | 2         | 1.37%   |
| 5.3.18-59.13-default         | 2         | 1.37%   |
| 5.3.18-150300.59.93-default  | 2         | 1.37%   |
| 5.3.18-150300.59.90-default  | 2         | 1.37%   |
| 5.3.18-lp152.57-default      | 1         | 0.68%   |
| 5.3.18-59.37-preempt         | 1         | 0.68%   |
| 5.3.18-59.34-preempt         | 1         | 0.68%   |
| 5.3.18-59.24-preempt         | 1         | 0.68%   |
| 5.3.18-59.10-preempt         | 1         | 0.68%   |
| 5.3.18-57-preempt            | 1         | 0.68%   |
| 5.3.18-56-default            | 1         | 0.68%   |
| 5.3.18-52-default            | 1         | 0.68%   |
| 5.3.18-46-default            | 1         | 0.68%   |
| 5.3.18-150300.59.98-default  | 1         | 0.68%   |
| 5.3.18-150300.59.76-default  | 1         | 0.68%   |
| 5.3.18-150300.59.71-default  | 1         | 0.68%   |
| 5.3.18-150300.59.63-preempt  | 1         | 0.68%   |
| 5.3.18-150300.59.60-preempt  | 1         | 0.68%   |
| 5.3.18-150300.59.49-preempt  | 1         | 0.68%   |
| 5.3.18-150300.59.106-preempt | 1         | 0.68%   |
| 5.3.18-150300.59.106-default | 1         | 0.68%   |
| 5.3.18-150300.59.101-preempt | 1         | 0.68%   |
| 5.3.18-150300.59.101-default | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 129       | 96.27%  |
| 5.17.2  | 2         | 1.49%   |
| 5.16.0  | 1         | 0.75%   |
| 5.15.11 | 1         | 0.75%   |
| 4.12.14 | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 129       | 96.27%  |
| 5.17    | 2         | 1.49%   |
| 5.16    | 1         | 0.75%   |
| 5.15    | 1         | 0.75%   |
| 4.12    | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 133       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 65        | 47.1%   |
| GNOME      | 20        | 14.49%  |
| KDE        | 17        | 12.32%  |
| Unknown    | 16        | 11.59%  |
| XFCE       | 12        | 8.7%    |
| X-Cinnamon | 4         | 2.9%    |
| plasma5    | 1         | 0.72%   |
| MATE       | 1         | 0.72%   |
| LXDE       | 1         | 0.72%   |
| ICEWM      | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 112       | 82.96%  |
| Wayland | 13        | 9.63%   |
| Tty     | 10        | 7.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 67        | 48.91%  |
| SDDM    | 33        | 24.09%  |
| LightDM | 30        | 21.9%   |
| XDM     | 6         | 4.38%   |
| GDM     | 1         | 0.73%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 38        | 28.15%  |
| de_DE   | 32        | 23.7%   |
| POSIX   | 14        | 10.37%  |
| pt_BR   | 7         | 5.19%   |
| ru_RU   | 6         | 4.44%   |
| es_ES   | 5         | 3.7%    |
| Unknown | 5         | 3.7%    |
| fr_FR   | 4         | 2.96%   |
| en_GB   | 4         | 2.96%   |
| nl_NL   | 3         | 2.22%   |
| it_IT   | 2         | 1.48%   |
| zh_CN   | 1         | 0.74%   |
| tr_TR   | 1         | 0.74%   |
| sv_SE   | 1         | 0.74%   |
| sk_SK   | 1         | 0.74%   |
| pt_PT   | 1         | 0.74%   |
| pl_PL   | 1         | 0.74%   |
| nl_BE   | 1         | 0.74%   |
| hu_HU   | 1         | 0.74%   |
| hr_HR   | 1         | 0.74%   |
| fi_FI   | 1         | 0.74%   |
| es_MX   | 1         | 0.74%   |
| en_DE   | 1         | 0.74%   |
| en_AU   | 1         | 0.74%   |
| cs_CZ   | 1         | 0.74%   |
| ca_AD   | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 80        | 59.7%   |
| EFI  | 54        | 40.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 90        | 67.16%  |
| Ext4    | 38        | 28.36%  |
| Xfs     | 5         | 3.73%   |
| Overlay | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 67        | 49.26%  |
| Unknown | 57        | 41.91%  |
| MBR     | 12        | 8.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 82.22%  |
| Yes       | 24        | 17.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 93        | 69.92%  |
| Yes       | 40        | 30.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 22        | 16.54%  |
| Lenovo              | 19        | 14.29%  |
| Hewlett-Packard     | 18        | 13.53%  |
| MSI                 | 14        | 10.53%  |
| Gigabyte Technology | 12        | 9.02%   |
| Dell                | 12        | 9.02%   |
| ASRock              | 8         | 6.02%   |
| Acer                | 7         | 5.26%   |
| TUXEDO              | 3         | 2.26%   |
| Fujitsu             | 3         | 2.26%   |
| Sony                | 2         | 1.5%    |
| VS Company          | 1         | 0.75%   |
| Shuttle             | 1         | 0.75%   |
| Semp Toshiba        | 1         | 0.75%   |
| Samsung Electronics | 1         | 0.75%   |
| Notebook            | 1         | 0.75%   |
| Medion              | 1         | 0.75%   |
| Itautec             | 1         | 0.75%   |
| Intel               | 1         | 0.75%   |
| HUAWEI              | 1         | 0.75%   |
| Gateway             | 1         | 0.75%   |
| Biostar             | 1         | 0.75%   |
| Apple               | 1         | 0.75%   |
| Alienware           | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 3         | 2.26%   |
| TUXEDO Pulse 15 Gen1                       | 2         | 1.5%    |
| VS Company G31T-M                          | 1         | 0.75%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.75%   |
| Sony VPCSB15GB                             | 1         | 0.75%   |
| Sony VGN-Z570AN                            | 1         | 0.75%   |
| Shuttle XS35V4                             | 1         | 0.75%   |
| Semp Toshiba AS 1301                       | 1         | 0.75%   |
| Samsung 600B4B/600B5B                      | 1         | 0.75%   |
| Notebook PCx0Dx                            | 1         | 0.75%   |
| MSI MS-7D16                                | 1         | 0.75%   |
| MSI MS-7C34                                | 1         | 0.75%   |
| MSI MS-7C09                                | 1         | 0.75%   |
| MSI MS-7C02                                | 1         | 0.75%   |
| MSI MS-7B89                                | 1         | 0.75%   |
| MSI MS-7A38                                | 1         | 0.75%   |
| MSI MS-7A34                                | 1         | 0.75%   |
| MSI MS-7A33                                | 1         | 0.75%   |
| MSI MS-7817                                | 1         | 0.75%   |
| MSI Modern 15 A4M                          | 1         | 0.75%   |
| MSI GS60 6QE                               | 1         | 0.75%   |
| MSI GP63 Leopard 8RD                       | 1         | 0.75%   |
| MSI ESPRIMO P1510                          | 1         | 0.75%   |
| MSI CX600                                  | 1         | 0.75%   |
| Medion E6436 MD61150                       | 1         | 0.75%   |
| Lenovo Yoga 730-15IKB 81CU                 | 1         | 0.75%   |
| Lenovo V330-15IKB 81AX                     | 1         | 0.75%   |
| Lenovo ThinkStation P520 30BE008VGE        | 1         | 0.75%   |
| Lenovo ThinkStation P500 30A6S4JU00        | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC   | 1         | 0.75%   |
| Lenovo ThinkPad T61 8895W9U                | 1         | 0.75%   |
| Lenovo ThinkPad T490s 20NYS1XK00           | 1         | 0.75%   |
| Lenovo ThinkPad T470 20HES1RB06            | 1         | 0.75%   |
| Lenovo ThinkPad T460 20FMS75800            | 1         | 0.75%   |
| Lenovo ThinkPad T450s 20BWA06J00           | 1         | 0.75%   |
| Lenovo ThinkPad T450 20BUS0EW1F            | 1         | 0.75%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00       | 1         | 0.75%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000       | 1         | 0.75%   |
| Lenovo ThinkPad E580 20KS001RGE            | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 11        | 8.27%   |
| Dell Inspiron       | 5         | 3.76%   |
| Acer Aspire         | 5         | 3.76%   |
| HP Pavilion         | 3         | 2.26%   |
| ASUS ROG            | 3         | 2.26%   |
| ASUS All            | 3         | 2.26%   |
| TUXEDO Pulse        | 2         | 1.5%    |
| Lenovo ThinkStation | 2         | 1.5%    |
| HP ZBook            | 2         | 1.5%    |
| HP Laptop           | 2         | 1.5%    |
| Gigabyte B550       | 2         | 1.5%    |
| Fujitsu LIFEBOOK    | 2         | 1.5%    |
| Dell Latitude       | 2         | 1.5%    |
| ASUS TUF            | 2         | 1.5%    |
| ASUS PRIME          | 2         | 1.5%    |
| Acer Nitro          | 2         | 1.5%    |
| VS Company G31T-M   | 1         | 0.75%   |
| TUXEDO Aura         | 1         | 0.75%   |
| Sony VPCSB15GB      | 1         | 0.75%   |
| Sony VGN-Z570AN     | 1         | 0.75%   |
| Shuttle XS35V4      | 1         | 0.75%   |
| Semp Toshiba AS     | 1         | 0.75%   |
| Samsung 600B4B      | 1         | 0.75%   |
| Notebook PCx0Dx     | 1         | 0.75%   |
| MSI MS-7D16         | 1         | 0.75%   |
| MSI MS-7C34         | 1         | 0.75%   |
| MSI MS-7C09         | 1         | 0.75%   |
| MSI MS-7C02         | 1         | 0.75%   |
| MSI MS-7B89         | 1         | 0.75%   |
| MSI MS-7A38         | 1         | 0.75%   |
| MSI MS-7A34         | 1         | 0.75%   |
| MSI MS-7A33         | 1         | 0.75%   |
| MSI MS-7817         | 1         | 0.75%   |
| MSI Modern          | 1         | 0.75%   |
| MSI GS60            | 1         | 0.75%   |
| MSI GP63            | 1         | 0.75%   |
| MSI ESPRIMO         | 1         | 0.75%   |
| MSI CX600           | 1         | 0.75%   |
| Medion E6436        | 1         | 0.75%   |
| Lenovo Yoga         | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 18        | 13.53%  |
| 2020 | 14        | 10.53%  |
| 2019 | 13        | 9.77%   |
| 2012 | 13        | 9.77%   |
| 2014 | 11        | 8.27%   |
| 2021 | 9         | 6.77%   |
| 2017 | 9         | 6.77%   |
| 2015 | 8         | 6.02%   |
| 2011 | 7         | 5.26%   |
| 2013 | 6         | 4.51%   |
| 2010 | 6         | 4.51%   |
| 2016 | 5         | 3.76%   |
| 2009 | 5         | 3.76%   |
| 2008 | 4         | 3.01%   |
| 2007 | 4         | 3.01%   |
| 2006 | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 68        | 51.13%  |
| Notebook    | 59        | 44.36%  |
| Convertible | 3         | 2.26%   |
| All in one  | 2         | 1.5%    |
| Server      | 1         | 0.75%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 121       | 90.98%  |
| Enabled  | 12        | 9.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 133       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 38        | 28.57%  |
| 8.01-16.0   | 24        | 18.05%  |
| 4.01-8.0    | 23        | 17.29%  |
| 3.01-4.0    | 19        | 14.29%  |
| 32.01-64.0  | 12        | 9.02%   |
| 64.01-256.0 | 12        | 9.02%   |
| 24.01-32.0  | 2         | 1.5%    |
| 1.01-2.0    | 2         | 1.5%    |
| 2.01-3.0    | 1         | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 39        | 28.26%  |
| 1.01-2.0   | 38        | 27.54%  |
| 4.01-8.0   | 32        | 23.19%  |
| 3.01-4.0   | 16        | 11.59%  |
| 0.51-1.0   | 6         | 4.35%   |
| 8.01-16.0  | 4         | 2.9%    |
| 32.01-64.0 | 1         | 0.72%   |
| 24.01-32.0 | 1         | 0.72%   |
| 0.01-0.5   | 1         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 45.11%  |
| 2      | 44        | 33.08%  |
| 3      | 12        | 9.02%   |
| 4      | 8         | 6.02%   |
| 6      | 4         | 3.01%   |
| 5      | 3         | 2.26%   |
| 9      | 1         | 0.75%   |
| 7      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 51.13%  |
| No        | 65        | 48.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 92.48%  |
| No        | 10        | 7.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 73.13%  |
| No        | 36        | 26.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 58.09%  |
| No        | 57        | 41.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 35        | 26.32%  |
| USA         | 17        | 12.78%  |
| Brazil      | 12        | 9.02%   |
| Russia      | 7         | 5.26%   |
| France      | 6         | 4.51%   |
| Netherlands | 4         | 3.01%   |
| Australia   | 4         | 3.01%   |
| UK          | 3         | 2.26%   |
| Spain       | 3         | 2.26%   |
| Mexico      | 3         | 2.26%   |
| India       | 3         | 2.26%   |
| Switzerland | 2         | 1.5%    |
| Slovakia    | 2         | 1.5%    |
| Nicaragua   | 2         | 1.5%    |
| Japan       | 2         | 1.5%    |
| Italy       | 2         | 1.5%    |
| Hungary     | 2         | 1.5%    |
| Greece      | 2         | 1.5%    |
| Czechia     | 2         | 1.5%    |
| Belgium     | 2         | 1.5%    |
| Austria     | 2         | 1.5%    |
| Turkey      | 1         | 0.75%   |
| Thailand    | 1         | 0.75%   |
| Sweden      | 1         | 0.75%   |
| Sudan       | 1         | 0.75%   |
| Romania     | 1         | 0.75%   |
| Portugal    | 1         | 0.75%   |
| Poland      | 1         | 0.75%   |
| Peru        | 1         | 0.75%   |
| Luxembourg  | 1         | 0.75%   |
| Finland     | 1         | 0.75%   |
| Estonia     | 1         | 0.75%   |
| Croatia     | 1         | 0.75%   |
| China       | 1         | 0.75%   |
| Canada      | 1         | 0.75%   |
| Bulgaria    | 1         | 0.75%   |
| Andorra     | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 4         | 2.92%   |
| Halle                 | 4         | 2.92%   |
| Moscow                | 3         | 2.19%   |
| Wesel                 | 2         | 1.46%   |
| Tokyo                 | 2         | 1.46%   |
| Sydney                | 2         | 1.46%   |
| Stolk                 | 2         | 1.46%   |
| Managua               | 2         | 1.46%   |
| Lehrte                | 2         | 1.46%   |
| Chapecó              | 2         | 1.46%   |
| Berlin                | 2         | 1.46%   |
| Zurich                | 1         | 0.73%   |
| Zagreb                | 1         | 0.73%   |
| Weilheim              | 1         | 0.73%   |
| Waltham               | 1         | 0.73%   |
| Vijayawada            | 1         | 0.73%   |
| Vienna                | 1         | 0.73%   |
| Veresegyhaz           | 1         | 0.73%   |
| Vaennaes              | 1         | 0.73%   |
| Udine                 | 1         | 0.73%   |
| Três Lagoas          | 1         | 0.73%   |
| The Hague             | 1         | 0.73%   |
| Teresina              | 1         | 0.73%   |
| Tallinn               | 1         | 0.73%   |
| Tacna                 | 1         | 0.73%   |
| Sterling              | 1         | 0.73%   |
| Stargard              | 1         | 0.73%   |
| Southampton           | 1         | 0.73%   |
| Sofia                 | 1         | 0.73%   |
| Seclin                | 1         | 0.73%   |
| San Luis Potosí City | 1         | 0.73%   |
| Samorin               | 1         | 0.73%   |
| Saalfeld              | 1         | 0.73%   |
| Rotterdam             | 1         | 0.73%   |
| Rottenburg            | 1         | 0.73%   |
| Rockville             | 1         | 0.73%   |
| Rio de Janeiro        | 1         | 0.73%   |
| Rio Branco            | 1         | 0.73%   |
| Recife                | 1         | 0.73%   |
| Ratingen              | 1         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 66     | 19.64%  |
| Samsung Electronics | 41        | 67     | 18.3%   |
| Seagate             | 38        | 61     | 16.96%  |
| Kingston            | 20        | 24     | 8.93%   |
| Toshiba             | 11        | 12     | 4.91%   |
| SanDisk             | 11        | 12     | 4.91%   |
| Hitachi             | 8         | 11     | 3.57%   |
| Crucial             | 7         | 10     | 3.13%   |
| Unknown             | 5         | 5      | 2.23%   |
| SK hynix            | 5         | 5      | 2.23%   |
| Intel               | 4         | 4      | 1.79%   |
| HGST                | 4         | 6      | 1.79%   |
| A-DATA Technology   | 4         | 4      | 1.79%   |
| Micron Technology   | 3         | 4      | 1.34%   |
| Silicon Motion      | 2         | 2      | 0.89%   |
| Phison              | 2         | 2      | 0.89%   |
| Fujitsu             | 2         | 2      | 0.89%   |
| TO Exter            | 1         | 1      | 0.45%   |
| SSSTC               | 1         | 1      | 0.45%   |
| Plextor             | 1         | 2      | 0.45%   |
| LITEON              | 1         | 1      | 0.45%   |
| Lite-On             | 1         | 1      | 0.45%   |
| JMicron Technology  | 1         | 1      | 0.45%   |
| Intenso             | 1         | 1      | 0.45%   |
| Inateck             | 1         | 1      | 0.45%   |
| HGST HTS            | 1         | 1      | 0.45%   |
| Corsair             | 1         | 1      | 0.45%   |
| China               | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |
| Apacer              | 1         | 3      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 1.18%   |
| Samsung SSD 850 EVO 500GB             | 3         | 1.18%   |
| Samsung SSD 850 EVO 250GB             | 3         | 1.18%   |
| Kingston SA400S37480G 480GB SSD       | 3         | 1.18%   |
| WDC WDS500G1X0E-00AFY0 500GB          | 2         | 0.79%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 2         | 0.79%   |
| WDC WD5000AAKX-07U6AA0 500GB          | 2         | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 0.79%   |
| WDC WD10EZEX-00KUWA0 1TB              | 2         | 0.79%   |
| WDC WD10EAVS-22D7B0 1TB               | 2         | 0.79%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 0.79%   |
| Silicon Motion NVMe SSD Drive 512GB   | 2         | 0.79%   |
| Seagate ST3750528AS 752GB             | 2         | 0.79%   |
| Seagate ST3500418AS 500GB             | 2         | 0.79%   |
| Seagate ST3500413AS 500GB             | 2         | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 0.79%   |
| Seagate ST2000DM006-2DM164 2TB        | 2         | 0.79%   |
| Seagate ST2000DM001-9YN164 2TB        | 2         | 0.79%   |
| Seagate ST2000DM001-1ER164 2TB        | 2         | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 0.79%   |
| Seagate ST1000DM010-2EP102 1TB        | 2         | 0.79%   |
| Samsung SSD 980 PRO 1TB               | 2         | 0.79%   |
| Samsung SSD 970 EVO 1TB               | 2         | 0.79%   |
| Samsung SSD 870 QVO 1TB               | 2         | 0.79%   |
| Samsung SSD 860 EVO 500GB             | 2         | 0.79%   |
| Samsung SSD 860 EVO 250GB             | 2         | 0.79%   |
| Samsung SSD 860 EVO 1TB               | 2         | 0.79%   |
| Samsung NVMe SSD Drive 1TB            | 2         | 0.79%   |
| Samsung HD105SI 1TB                   | 2         | 0.79%   |
| Samsung HD103SI 1TB                   | 2         | 0.79%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 0.79%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 0.79%   |
| Kingston NVMe SSD Drive 500GB         | 2         | 0.79%   |
| Hitachi HDS5C3020ALA632 2TB           | 2         | 0.79%   |
| HGST HTS721010A9E630 1TB              | 2         | 0.79%   |
| Fujitsu MHW2120BH 120GB               | 2         | 0.79%   |
| Crucial CT1000MX500SSD1 1TB           | 2         | 0.79%   |
| Crucial CT1000BX500SSD1 1TB           | 2         | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 0.39%   |
| WDC WDS500G2B0A 500GB SSD             | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 60     | 37.25%  |
| WDC                 | 34        | 50     | 33.33%  |
| Hitachi             | 8         | 11     | 7.84%   |
| Toshiba             | 7         | 8      | 6.86%   |
| Samsung Electronics | 7         | 14     | 6.86%   |
| HGST                | 4         | 6      | 3.92%   |
| Fujitsu             | 2         | 2      | 1.96%   |
| Unknown             | 1         | 1      | 0.98%   |
| HGST HTS            | 1         | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 27     | 22.78%  |
| Kingston            | 15        | 19     | 18.99%  |
| SanDisk             | 11        | 12     | 13.92%  |
| WDC                 | 9         | 10     | 11.39%  |
| Crucial             | 4         | 5      | 5.06%   |
| A-DATA Technology   | 4         | 4      | 5.06%   |
| Toshiba             | 3         | 3      | 3.8%    |
| SK hynix            | 2         | 2      | 2.53%   |
| Intel               | 2         | 2      | 2.53%   |
| TO Exter            | 1         | 1      | 1.27%   |
| SSSTC               | 1         | 1      | 1.27%   |
| Plextor             | 1         | 2      | 1.27%   |
| Micron Technology   | 1         | 2      | 1.27%   |
| LITEON              | 1         | 1      | 1.27%   |
| JMicron Technology  | 1         | 1      | 1.27%   |
| Intenso             | 1         | 1      | 1.27%   |
| Inateck             | 1         | 1      | 1.27%   |
| China               | 1         | 1      | 1.27%   |
| Apple               | 1         | 1      | 1.27%   |
| Apacer              | 1         | 3      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 81        | 153    | 41.12%  |
| SSD     | 69        | 99     | 35.03%  |
| NVMe    | 42        | 56     | 21.32%  |
| MMC     | 4         | 4      | 2.03%   |
| Unknown | 1         | 1      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 109       | 244    | 67.7%   |
| NVMe | 42        | 56     | 26.09%  |
| SAS  | 6         | 9      | 3.73%   |
| MMC  | 4         | 4      | 2.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 76        | 118    | 46.91%  |
| 0.51-1.0   | 56        | 86     | 34.57%  |
| 1.01-2.0   | 20        | 31     | 12.35%  |
| 3.01-4.0   | 4         | 9      | 2.47%   |
| 2.01-3.0   | 3         | 3      | 1.85%   |
| 10.01-20.0 | 2         | 3      | 1.23%   |
| 4.01-10.0  | 1         | 2      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 36        | 26.47%  |
| 1001-2000      | 25        | 18.38%  |
| 501-1000       | 23        | 16.91%  |
| 2001-3000      | 19        | 13.97%  |
| 251-500        | 15        | 11.03%  |
| 101-250        | 5         | 3.68%   |
| Unknown        | 5         | 3.68%   |
| 51-100         | 4         | 2.94%   |
| 1-20           | 3         | 2.21%   |
| 21-50          | 1         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 19.01%  |
| 251-500        | 24        | 16.9%   |
| 501-1000       | 21        | 14.79%  |
| 51-100         | 18        | 12.68%  |
| 1001-2000      | 16        | 11.27%  |
| 1-20           | 12        | 8.45%   |
| 2001-3000      | 8         | 5.63%   |
| 21-50          | 6         | 4.23%   |
| More than 3000 | 5         | 3.52%   |
| Unknown        | 5         | 3.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 6.67%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 6.67%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 6.67%   |
| WDC WD10PURX-64E5EY0 1TB              | 1         | 1      | 6.67%   |
| Toshiba HDWD105 500GB                 | 1         | 1      | 6.67%   |
| SSSTC CVB-8D128-HP 128GB              | 1         | 1      | 6.67%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 6.67%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 6.67%   |
| Seagate ST3320620AS 320GB             | 1         | 1      | 6.67%   |
| Seagate ST2000LX001-1RG174 2TB        | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 6.67%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 6.67%   |
| Phison 311CD0512GB                    | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 6.67%   |
| Crucial CT1000P1SSD8 1TB              | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 5      | 33.33%  |
| WDC      | 4         | 4      | 26.67%  |
| Toshiba  | 1         | 1      | 6.67%   |
| SSSTC    | 1         | 1      | 6.67%   |
| SK hynix | 1         | 1      | 6.67%   |
| Phison   | 1         | 1      | 6.67%   |
| Kingston | 1         | 1      | 6.67%   |
| Crucial  | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 50%     |
| WDC     | 4         | 4      | 40%     |
| Toshiba | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 64.29%  |
| SSD  | 3         | 3      | 21.43%  |
| NVMe | 2         | 2      | 14.29%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 72        | 149    | 48.65%  |
| Detected | 62        | 149    | 41.89%  |
| Malfunc  | 14        | 15     | 9.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 84        | 46.41%  |
| AMD                              | 36        | 19.89%  |
| Samsung Electronics              | 19        | 10.5%   |
| SanDisk                          | 6         | 3.31%   |
| Kingston Technology Company      | 5         | 2.76%   |
| ASMedia Technology               | 5         | 2.76%   |
| Micron/Crucial Technology        | 4         | 2.21%   |
| Phison Electronics               | 3         | 1.66%   |
| Marvell Technology Group         | 3         | 1.66%   |
| SK hynix                         | 2         | 1.1%    |
| Silicon Motion                   | 2         | 1.1%    |
| Micron Technology                | 2         | 1.1%    |
| Lite-On Technology               | 2         | 1.1%    |
| Broadcom / LSI                   | 2         | 1.1%    |
| Toshiba America Info Systems     | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Silicon Image                    | 1         | 0.55%   |
| Seagate Technology               | 1         | 0.55%   |
| Nvidia                           | 1         | 0.55%   |
| JMicron Technology               | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 25        | 11.9%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 4.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 4.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 2.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 1.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 1.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.9%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3         | 1.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.43%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 0.95%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.95%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.95%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 0.95%   |
| Micron NVMe Storage Controller                                                          | 2         | 0.95%   |
| Kingston Company NVMe Controller                                                        | 2         | 0.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.95%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.95%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 0.95%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 0.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 104       | 58.76%  |
| NVMe | 42        | 23.73%  |
| IDE  | 21        | 11.86%  |
| RAID | 9         | 5.08%   |
| SAS  | 1         | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 91        | 68.42%  |
| AMD    | 42        | 31.58%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.26%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3         | 2.26%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 3         | 2.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.5%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.5%    |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.5%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 2         | 1.5%    |
| AMD Ryzen 7 3800X 8-Core Processor          | 2         | 1.5%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.5%    |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.5%    |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1         | 0.75%   |
| Intel Xeon W-2135 CPU @ 3.70GHz             | 1         | 0.75%   |
| Intel Xeon E-2286M CPU @ 2.40GHz            | 1         | 0.75%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.75%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz         | 1         | 0.75%   |
| Intel Xeon CPU E5-2470 v2 @ 2.40GHz         | 1         | 0.75%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 0.75%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1         | 0.75%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.75%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.75%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1         | 0.75%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.75%   |
| Intel Core i9-10900T CPU @ 1.90GHz          | 1         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.75%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.75%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.75%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.75%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.75%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.75%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 26.32%  |
| Intel Core i7           | 19        | 14.29%  |
| AMD Ryzen 7             | 13        | 9.77%   |
| Intel Xeon              | 8         | 6.02%   |
| Intel Core i3           | 7         | 5.26%   |
| AMD Ryzen 5             | 7         | 5.26%   |
| AMD Ryzen 9             | 6         | 4.51%   |
| Intel Core 2 Duo        | 5         | 3.76%   |
| Intel Celeron           | 4         | 3.01%   |
| Intel Pentium Dual-Core | 3         | 2.26%   |
| AMD Phenom II X4        | 3         | 2.26%   |
| Other                   | 2         | 1.5%    |
| Intel Core i9           | 2         | 1.5%    |
| Intel Core 2 Quad       | 2         | 1.5%    |
| AMD FX                  | 2         | 1.5%    |
| AMD A6                  | 2         | 1.5%    |
| Intel Pentium Silver    | 1         | 0.75%   |
| Intel Pentium Dual      | 1         | 0.75%   |
| Intel Pentium           | 1         | 0.75%   |
| Intel Core 2            | 1         | 0.75%   |
| AMD Sempron             | 1         | 0.75%   |
| AMD Ryzen 7 PRO         | 1         | 0.75%   |
| AMD Ryzen 3             | 1         | 0.75%   |
| AMD Phenom II X6        | 1         | 0.75%   |
| AMD Phenom II X2        | 1         | 0.75%   |
| AMD C-50                | 1         | 0.75%   |
| AMD Athlon              | 1         | 0.75%   |
| AMD A8                  | 1         | 0.75%   |
| AMD A10                 | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 48        | 36.09%  |
| 2      | 43        | 32.33%  |
| 8      | 19        | 14.29%  |
| 6      | 13        | 9.77%   |
| 16     | 4         | 3.01%   |
| 12     | 3         | 2.26%   |
| 20     | 1         | 0.75%   |
| 10     | 1         | 0.75%   |
| 3      | 1         | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 131       | 98.5%   |
| 2      | 2         | 1.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 85        | 63.91%  |
| 1      | 48        | 36.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 133       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 36.5%   |
| 0x206a7    | 7         | 5.11%   |
| 0x306c3    | 5         | 3.65%   |
| 0x306a9    | 5         | 3.65%   |
| 0x906ea    | 4         | 2.92%   |
| 0x806e9    | 4         | 2.92%   |
| 0x406e3    | 4         | 2.92%   |
| 0x6fd      | 3         | 2.19%   |
| 0x1067a    | 3         | 2.19%   |
| 0x08701021 | 3         | 2.19%   |
| 0x08600106 | 3         | 2.19%   |
| 0xa0653    | 2         | 1.46%   |
| 0x906e9    | 2         | 1.46%   |
| 0x806ea    | 2         | 1.46%   |
| 0x706a8    | 2         | 1.46%   |
| 0x506e3    | 2         | 1.46%   |
| 0x306d4    | 2         | 1.46%   |
| 0x0a201016 | 2         | 1.46%   |
| 0x0a201009 | 2         | 1.46%   |
| 0x08108109 | 2         | 1.46%   |
| 0x08001137 | 2         | 1.46%   |
| 0x07030105 | 2         | 1.46%   |
| 0x010000c8 | 2         | 1.46%   |
| 0xa0655    | 1         | 0.73%   |
| 0x906ed    | 1         | 0.73%   |
| 0x906ec    | 1         | 0.73%   |
| 0x806ec    | 1         | 0.73%   |
| 0x806d1    | 1         | 0.73%   |
| 0x806c1    | 1         | 0.73%   |
| 0x706a1    | 1         | 0.73%   |
| 0x50654    | 1         | 0.73%   |
| 0x306f2    | 1         | 0.73%   |
| 0x306e4    | 1         | 0.73%   |
| 0x30678    | 1         | 0.73%   |
| 0x20655    | 1         | 0.73%   |
| 0x10677    | 1         | 0.73%   |
| 0x10676    | 1         | 0.73%   |
| 0x0a50000c | 1         | 0.73%   |
| 0x0a201204 | 1         | 0.73%   |
| 0x08108102 | 1         | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 22        | 16.54%  |
| Haswell       | 13        | 9.77%   |
| Zen 2         | 11        | 8.27%   |
| Skylake       | 10        | 7.52%   |
| IvyBridge     | 10        | 7.52%   |
| SandyBridge   | 8         | 6.02%   |
| Zen 3         | 7         | 5.26%   |
| Penryn        | 7         | 5.26%   |
| Zen+          | 6         | 4.51%   |
| Zen           | 5         | 3.76%   |
| K10           | 5         | 3.76%   |
| Core          | 5         | 3.76%   |
| CometLake     | 4         | 3.01%   |
| Goldmont plus | 3         | 2.26%   |
| Westmere      | 2         | 1.5%    |
| Silvermont    | 2         | 1.5%    |
| Puma          | 2         | 1.5%    |
| Piledriver    | 2         | 1.5%    |
| Broadwell     | 2         | 1.5%    |
| TigerLake     | 1         | 0.75%   |
| Steamroller   | 1         | 0.75%   |
| Nehalem       | 1         | 0.75%   |
| K10 Llano     | 1         | 0.75%   |
| Jaguar        | 1         | 0.75%   |
| Icelake       | 1         | 0.75%   |
| Bobcat        | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 66        | 40.74%  |
| Nvidia            | 53        | 32.72%  |
| AMD               | 41        | 25.31%  |
| S3 Graphics       | 1         | 0.62%   |
| ASPEED Technology | 1         | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 3.64%   |
| AMD Renoir                                                                  | 6         | 3.64%   |
| Intel HD Graphics 620                                                       | 5         | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 3.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 2.42%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 2.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 2.42%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 1.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.82%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 3         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.82%   |
| Intel UHD Graphics 620                                                      | 3         | 1.82%   |
| Intel HD Graphics 630                                                       | 3         | 1.82%   |
| Intel HD Graphics 530                                                       | 3         | 1.82%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3         | 1.82%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.21%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.21%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2         | 1.21%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2         | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.21%   |
| Intel HD Graphics 5500                                                      | 2         | 1.21%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.21%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2         | 1.21%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2         | 1.21%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 2         | 1.21%   |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                     | 1         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.61%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.61%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.61%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 41        | 30.83%  |
| 1 x Nvidia      | 33        | 24.81%  |
| 1 x AMD         | 32        | 24.06%  |
| Intel + Nvidia  | 17        | 12.78%  |
| Intel + AMD     | 6         | 4.51%   |
| 2 x AMD         | 1         | 0.75%   |
| 1 x S3 Graphics | 1         | 0.75%   |
| Nvidia + ASPEED | 1         | 0.75%   |
| AMD + Nvidia    | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 100       | 74.63%  |
| Proprietary | 29        | 21.64%  |
| Unknown     | 5         | 3.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 60.58%  |
| 1.01-2.0   | 17        | 12.41%  |
| 3.01-4.0   | 9         | 6.57%   |
| 0.01-0.5   | 8         | 5.84%   |
| 7.01-8.0   | 6         | 4.38%   |
| 0.51-1.0   | 5         | 3.65%   |
| 5.01-6.0   | 3         | 2.19%   |
| 8.01-16.0  | 3         | 2.19%   |
| 16.01-24.0 | 2         | 1.46%   |
| 2.01-3.0   | 1         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Goldstar             | 18        | 11.69%  |
| Samsung Electronics  | 16        | 10.39%  |
| LG Display           | 16        | 10.39%  |
| Chimei Innolux       | 14        | 9.09%   |
| Dell                 | 12        | 7.79%   |
| AU Optronics         | 11        | 7.14%   |
| Hewlett-Packard      | 7         | 4.55%   |
| BOE                  | 7         | 4.55%   |
| Philips              | 6         | 3.9%    |
| BenQ                 | 6         | 3.9%    |
| Ancor Communications | 6         | 3.9%    |
| AOC                  | 4         | 2.6%    |
| Acer                 | 4         | 2.6%    |
| Lenovo               | 3         | 1.95%   |
| ViewSonic            | 2         | 1.3%    |
| Medion               | 2         | 1.3%    |
| LG Electronics       | 2         | 1.3%    |
| Iiyama               | 2         | 1.3%    |
| ASUSTek Computer     | 2         | 1.3%    |
| Vizio                | 1         | 0.65%   |
| TCL                  | 1         | 0.65%   |
| Sony                 | 1         | 0.65%   |
| Sharp                | 1         | 0.65%   |
| Sceptre Tech         | 1         | 0.65%   |
| LG Philips           | 1         | 0.65%   |
| InfoVision           | 1         | 0.65%   |
| Hitachi              | 1         | 0.65%   |
| Fujitsu Siemens      | 1         | 0.65%   |
| Denver               | 1         | 0.65%   |
| CSO                  | 1         | 0.65%   |
| CPT                  | 1         | 0.65%   |
| Apple                | 1         | 0.65%   |
| AGO                  | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic VX3211-2K VSCF634 2560x1440 700x390mm 31.5-inch              | 2         | 1.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 1.25%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch            | 2         | 1.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 2         | 1.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 1.25%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                 | 2         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 1.25%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                  | 2         | 1.25%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch           | 2         | 1.25%   |
| Vizio E55u-D2 VIZ1018 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.63%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                       | 1         | 0.63%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch   | 1         | 0.63%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.63%   |
| Sceptre Tech Sceptre E19 SPT07A8 1366x768 575x323mm 26.0-inch          | 1         | 0.63%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1         | 0.63%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1         | 0.63%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch      | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch   | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM00A2 1024x768 304x228mm 15.0-inch    | 1         | 0.63%   |
| Samsung Electronics SMS27A850T SAM0887 2560x1440 518x324mm 24.1-inch   | 1         | 0.63%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch   | 1         | 0.63%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 1         | 0.63%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch      | 1         | 0.63%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch      | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC324E 1600x900 309x174mm 14.0-inch   | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM08FC 1366x768                       | 1         | 0.63%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch                | 1         | 0.63%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch              | 1         | 0.63%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 1         | 0.63%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 0.63%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.63%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                      | 1         | 0.63%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                      | 1         | 0.63%   |
| Medion MD30999PE MED8928 1440x900 410x256mm 19.0-inch                  | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 46.43%  |
| 1366x768 (WXGA)    | 20        | 14.29%  |
| 3840x2160 (4K)     | 10        | 7.14%   |
| 2560x1440 (QHD)    | 9         | 6.43%   |
| 1600x900 (HD+)     | 6         | 4.29%   |
| 1920x1200 (WUXGA)  | 5         | 3.57%   |
| 2560x1080          | 4         | 2.86%   |
| 1680x1050 (WSXGA+) | 4         | 2.86%   |
| 1024x768 (XGA)     | 4         | 2.86%   |
| 3440x1440          | 3         | 2.14%   |
| 1440x900 (WXGA+)   | 3         | 2.14%   |
| 1280x1024 (SXGA)   | 3         | 2.14%   |
| 640x480            | 1         | 0.71%   |
| 3840x2400          | 1         | 0.71%   |
| 2160x1440          | 1         | 0.71%   |
| 1280x800 (WXGA)    | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 22.52%  |
| 27      | 17        | 11.26%  |
| 21      | 14        | 9.27%   |
| 24      | 12        | 7.95%   |
| 17      | 11        | 7.28%   |
| 14      | 11        | 7.28%   |
| 23      | 9         | 5.96%   |
| 13      | 7         | 4.64%   |
| 34      | 5         | 3.31%   |
| 22      | 4         | 2.65%   |
| 31      | 3         | 1.99%   |
| 19      | 3         | 1.99%   |
| 18      | 3         | 1.99%   |
| 11      | 3         | 1.99%   |
| Unknown | 3         | 1.99%   |
| 26      | 2         | 1.32%   |
| 25      | 2         | 1.32%   |
| 20      | 2         | 1.32%   |
| 84      | 1         | 0.66%   |
| 74      | 1         | 0.66%   |
| 42      | 1         | 0.66%   |
| 35      | 1         | 0.66%   |
| 32      | 1         | 0.66%   |
| 12      | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 32.21%  |
| 501-600     | 36        | 24.16%  |
| 401-500     | 26        | 17.45%  |
| 351-400     | 11        | 7.38%   |
| 201-300     | 9         | 6.04%   |
| 701-800     | 6         | 4.03%   |
| 601-700     | 6         | 4.03%   |
| Unknown     | 3         | 2.01%   |
| 1501-2000   | 2         | 1.34%   |
| 801-900     | 1         | 0.67%   |
| 901-1000    | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 102       | 76.12%  |
| 16/10   | 14        | 10.45%  |
| 21/9    | 6         | 4.48%   |
| 4/3     | 5         | 3.73%   |
| 5/4     | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| 3/2     | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 34        | 22.52%  |
| 101-110        | 34        | 22.52%  |
| 301-350        | 18        | 11.92%  |
| 81-90          | 14        | 9.27%   |
| 351-500        | 10        | 6.62%   |
| 121-130        | 9         | 5.96%   |
| 151-200        | 7         | 4.64%   |
| 251-300        | 6         | 3.97%   |
| 141-150        | 5         | 3.31%   |
| 71-80          | 4         | 2.65%   |
| 51-60          | 3         | 1.99%   |
| Unknown        | 3         | 1.99%   |
| More than 1000 | 2         | 1.32%   |
| 501-1000       | 1         | 0.66%   |
| 91-100         | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 56        | 38.36%  |
| 101-120       | 42        | 28.77%  |
| 121-160       | 37        | 25.34%  |
| 161-240       | 4         | 2.74%   |
| More than 240 | 3         | 2.05%   |
| Unknown       | 3         | 2.05%   |
| 1-50          | 1         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 103       | 76.3%   |
| 2     | 24        | 17.78%  |
| 0     | 5         | 3.7%    |
| 3     | 3         | 2.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 79        | 38.92%  |
| Intel                            | 67        | 33%     |
| Qualcomm Atheros                 | 19        | 9.36%   |
| Broadcom                         | 10        | 4.93%   |
| Ralink                           | 5         | 2.46%   |
| Broadcom Limited                 | 3         | 1.48%   |
| Samsung Electronics              | 2         | 0.99%   |
| Dell                             | 2         | 0.99%   |
| ASIX Electronics                 | 2         | 0.99%   |
| ZyXEL Communications             | 1         | 0.49%   |
| TP-Link                          | 1         | 0.49%   |
| TOMTOM                           | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Sierra Wireless                  | 1         | 0.49%   |
| Ralink Technology                | 1         | 0.49%   |
| NetXen Incorporated              | 1         | 0.49%   |
| MediaTek                         | 1         | 0.49%   |
| Manta                            | 1         | 0.49%   |
| Lenovo                           | 1         | 0.49%   |
| Edimax Technology                | 1         | 0.49%   |
| DisplayLink                      | 1         | 0.49%   |
| D-Link System                    | 1         | 0.49%   |
| AVM                              | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 23.97%  |
| Intel Wi-Fi 6 AX200                                               | 13        | 5.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.07%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.07%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.65%   |
| Intel Wireless 8260                                               | 4         | 1.65%   |
| Intel Wireless 7260                                               | 4         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.24%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.24%   |
| Intel Wireless 3165                                               | 3         | 1.24%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.24%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.83%   |
| Intel Wireless-AC 9260                                            | 2         | 0.83%   |
| Intel Wireless 7265                                               | 2         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.83%   |
| Intel Ethernet Connection (2) I218-LM                             | 2         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.83%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]      | 1         | 0.41%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.41%   |
| TOMTOM GO 60                                                      | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.41%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 0.41%   |
| Samsung Kiera                                                     | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 48.51%  |
| Realtek Semiconductor | 19        | 18.81%  |
| Qualcomm Atheros      | 12        | 11.88%  |
| Broadcom              | 6         | 5.94%   |
| Ralink                | 5         | 4.95%   |
| ZyXEL Communications  | 1         | 0.99%   |
| TP-Link               | 1         | 0.99%   |
| Sierra Wireless       | 1         | 0.99%   |
| Ralink Technology     | 1         | 0.99%   |
| MediaTek              | 1         | 0.99%   |
| Edimax Technology     | 1         | 0.99%   |
| Dell                  | 1         | 0.99%   |
| D-Link System         | 1         | 0.99%   |
| Broadcom Limited      | 1         | 0.99%   |
| AVM                   | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13        | 12.87%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.95%   |
| Intel Wireless 8265 / 8275                                     | 4         | 3.96%   |
| Intel Wireless 8260                                            | 4         | 3.96%   |
| Intel Wireless 7260                                            | 4         | 3.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.97%   |
| Intel Wireless 3165                                            | 3         | 2.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.98%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.98%   |
| Intel Wireless-AC 9260                                         | 2         | 1.98%   |
| Intel Wireless 7265                                            | 2         | 1.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.98%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1         | 0.99%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.99%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 0.99%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.99%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.99%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.99%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.99%   |
| Ralink RT3072 Wireless Adapter                                 | 1         | 0.99%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                           | 1         | 0.99%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 1         | 0.99%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.99%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.99%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 0.99%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 0.99%   |
| Intel WiFi Link 5100                                           | 1         | 0.99%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 72        | 53.73%  |
| Intel                            | 37        | 27.61%  |
| Qualcomm Atheros                 | 9         | 6.72%   |
| Broadcom                         | 5         | 3.73%   |
| Samsung Electronics              | 2         | 1.49%   |
| Broadcom Limited                 | 2         | 1.49%   |
| ASIX Electronics                 | 2         | 1.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |
| NetXen Incorporated              | 1         | 0.75%   |
| Lenovo                           | 1         | 0.75%   |
| DisplayLink                      | 1         | 0.75%   |
| Dell                             | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 58        | 41.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 5.04%   |
| Realtek RTL8125 2.5GbE Controller                                    | 5         | 3.6%    |
| Intel I211 Gigabit Network Connection                                | 5         | 3.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 2.16%   |
| Intel Ethernet Connection I217-V                                     | 3         | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 1.44%   |
| Intel I210 Gigabit Network Connection                                | 2         | 1.44%   |
| Intel Ethernet Connection I219-LM                                    | 2         | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                                | 2         | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                                | 2         | 1.44%   |
| Intel Ethernet Connection (2) I218-LM                                | 2         | 1.44%   |
| Intel 82579V Gigabit Network Connection                              | 2         | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.44%   |
| ASIX AX88179 Gigabit Ethernet                                        | 2         | 1.44%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 1         | 0.72%   |
| Samsung Kiera                                                        | 1         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1         | 0.72%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 0.72%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 0.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.72%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.72%   |
| Lenovo OneLink+ Giga                                                 | 1         | 0.72%   |
| Intel I350 Gigabit Network Connection                                | 1         | 0.72%   |
| Intel Ethernet Controller I225-V                                     | 1         | 0.72%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.72%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                 | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.72%   |
| Intel Ethernet Connection (11) I219-V                                | 1         | 0.72%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 123       | 55.16%  |
| WiFi     | 98        | 43.95%  |
| Unknown  | 2         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 53.15%  |
| WiFi     | 66        | 46.15%  |
| Unknown  | 1         | 0.7%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 79        | 59.4%   |
| 1     | 46        | 34.59%  |
| 3     | 6         | 4.51%   |
| 5     | 1         | 0.75%   |
| 4     | 1         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 99        | 73.33%  |
| Yes  | 36        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 41.25%  |
| Realtek Semiconductor           | 10        | 12.5%   |
| Cambridge Silicon Radio         | 9         | 11.25%  |
| Qualcomm Atheros Communications | 6         | 7.5%    |
| IMC Networks                    | 4         | 5%      |
| Foxconn / Hon Hai               | 3         | 3.75%   |
| Broadcom                        | 3         | 3.75%   |
| ASUSTek Computer                | 3         | 3.75%   |
| Lite-On Technology              | 2         | 2.5%    |
| Dell                            | 2         | 2.5%    |
| Realtek                         | 1         | 1.25%   |
| MediaTek                        | 1         | 1.25%   |
| Belkin Components               | 1         | 1.25%   |
| Apple                           | 1         | 1.25%   |
| Alps Electric                   | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 11        | 13.75%  |
| Intel AX200 Bluetooth                                                               | 11        | 13.75%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 11.25%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 6.25%   |
| Intel AX201 Bluetooth                                                               | 4         | 5%      |
| Realtek Bluetooth Radio                                                             | 3         | 3.75%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 3.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.5%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.5%    |
| IMC Networks Bluetooth Device                                                       | 2         | 2.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.25%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.25%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.25%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.25%   |
| MediaTek Wireless_Device                                                            | 1         | 1.25%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.25%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.25%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.25%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 1.25%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.25%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.25%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.25%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.25%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 1.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.25%   |
| ASUS Bluetooth Adapter                                                              | 1         | 1.25%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 1.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.25%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 86        | 42.79%  |
| AMD                              | 52        | 25.87%  |
| Nvidia                           | 41        | 20.4%   |
| C-Media Electronics              | 5         | 2.49%   |
| Creative Labs                    | 3         | 1.49%   |
| Texas Instruments                | 2         | 1%      |
| Logitech                         | 2         | 1%      |
| Lenovo                           | 2         | 1%      |
| Silicon Integrated Systems [SiS] | 1         | 0.5%    |
| M2Tech                           | 1         | 0.5%    |
| JMTek                            | 1         | 0.5%    |
| GN Netcom                        | 1         | 0.5%    |
| ESS Technology                   | 1         | 0.5%    |
| DSEA A/S                         | 1         | 0.5%    |
| BEHRINGER International          | 1         | 0.5%    |
| ASUSTek Computer                 | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.13%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 4.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 4.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 4.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 3.42%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.56%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 2.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.14%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 2.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.71%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 1.28%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 1.28%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.28%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.85%   |
| Logitech Headset H390                                                      | 2         | 0.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.85%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.85%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.85%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 21        | 21.65%  |
| SK hynix               | 14        | 14.43%  |
| Kingston               | 13        | 13.4%   |
| Unknown                | 10        | 10.31%  |
| G.Skill                | 7         | 7.22%   |
| Corsair                | 7         | 7.22%   |
| Crucial                | 6         | 6.19%   |
| Micron Technology      | 5         | 5.15%   |
| A-DATA Technology      | 3         | 3.09%   |
| Ramaxel Technology     | 2         | 2.06%   |
| Patriot                | 2         | 2.06%   |
| Unknown (000004B30000) | 1         | 1.03%   |
| Team                   | 1         | 1.03%   |
| Smart                  | 1         | 1.03%   |
| Goodram                | 1         | 1.03%   |
| GeIL                   | 1         | 1.03%   |
| Elpida                 | 1         | 1.03%   |
| AMD                    | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s      | 2         | 1.89%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 2         | 1.89%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s     | 2         | 1.89%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 2         | 1.89%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s         | 2         | 1.89%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1         | 0.94%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 1         | 0.94%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                 | 1         | 0.94%   |
| Unknown RAM Module 4096MB SODIMM DDR3                      | 1         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 1         | 0.94%   |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                  | 1         | 0.94%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1         | 0.94%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 0.94%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1         | 0.94%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 1         | 0.94%   |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                  | 1         | 0.94%   |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s         | 1         | 0.94%   |
| Unknown (000004B30000) RAM Module 32GB DIMM DDR3 1333MT/s  | 1         | 0.94%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s         | 1         | 0.94%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s      | 1         | 0.94%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.94%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s           | 1         | 0.94%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM SDRAM 2048MT/s | 1         | 0.94%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 0.94%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s  | 1         | 0.94%   |
| SK hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1         | 0.94%   |
| SK hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s       | 1         | 0.94%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.94%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 0.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 1         | 0.94%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s    | 1         | 0.94%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.94%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s     | 1         | 0.94%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s     | 1         | 0.94%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s | 1         | 0.94%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2400MT/s             | 1         | 0.94%   |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 4199MT/s        | 1         | 0.94%   |
| Samsung RAM M471B5673EH1-CH9 2048MB SODIMM DDR3 1334MT/s   | 1         | 0.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s      | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 45        | 52.94%  |
| DDR3    | 25        | 29.41%  |
| DDR2    | 5         | 5.88%   |
| LPDDR4  | 4         | 4.71%   |
| Unknown | 3         | 3.53%   |
| SDRAM   | 2         | 2.35%   |
| LPDDR3  | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 43        | 50.59%  |
| SODIMM       | 39        | 45.88%  |
| Row Of Chips | 2         | 2.35%   |
| Chip         | 1         | 1.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 37        | 38.54%  |
| 4096  | 21        | 21.88%  |
| 16384 | 17        | 17.71%  |
| 2048  | 11        | 11.46%  |
| 32768 | 6         | 6.25%   |
| 1024  | 4         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 18        | 18.95%  |
| 1600    | 18        | 18.95%  |
| 3200    | 10        | 10.53%  |
| 1333    | 9         | 9.47%   |
| 3600    | 5         | 5.26%   |
| 2133    | 5         | 5.26%   |
| 2400    | 3         | 3.16%   |
| 1867    | 3         | 3.16%   |
| 800     | 3         | 3.16%   |
| 667     | 3         | 3.16%   |
| 3800    | 2         | 2.11%   |
| 2666    | 2         | 2.11%   |
| 4267    | 1         | 1.05%   |
| 4266    | 1         | 1.05%   |
| 4199    | 1         | 1.05%   |
| 3866    | 1         | 1.05%   |
| 3733    | 1         | 1.05%   |
| 3466    | 1         | 1.05%   |
| 3400    | 1         | 1.05%   |
| 3007    | 1         | 1.05%   |
| 2934    | 1         | 1.05%   |
| 2048    | 1         | 1.05%   |
| 1334    | 1         | 1.05%   |
| 1067    | 1         | 1.05%   |
| 1066    | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 22.22%  |
| Canon               | 2         | 22.22%  |
| Brother Industries  | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |
| Prolific Technology | 1         | 11.11%  |
| Kyocera             | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-4200 series       | 1         | 11.11%  |
| Prolific PL2305 Parallel Port | 1         | 11.11%  |
| Kyocera FS-1030D printer      | 1         | 11.11%  |
| HP ENVY 4500 series           | 1         | 11.11%  |
| HP DeskJet 6940 series        | 1         | 11.11%  |
| Canon G3020 series            | 1         | 11.11%  |
| Canon CanoScan LiDE 300       | 1         | 11.11%  |
| Brother Printer               | 1         | 11.11%  |
| Brother HL-L3210CW series     | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Seiko Epson     | 1         | 20%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1         | 20%     |
| HP ScanJet 3970c                      | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30         | 1         | 20%     |
| Canon CanoScan LiDE 210               | 1         | 20%     |
| Canon CanoScan LiDE 110               | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 21.79%  |
| Logitech                               | 10        | 12.82%  |
| Acer                                   | 7         | 8.97%   |
| IMC Networks                           | 6         | 7.69%   |
| Sunplus Innovation Technology          | 5         | 6.41%   |
| Realtek Semiconductor                  | 5         | 6.41%   |
| Quanta                                 | 4         | 5.13%   |
| Microdia                               | 4         | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.13%   |
| Lite-On Technology                     | 2         | 2.56%   |
| Z-Star Microelectronics                | 1         | 1.28%   |
| Syntek                                 | 1         | 1.28%   |
| Suyin                                  | 1         | 1.28%   |
| Silicon Motion                         | 1         | 1.28%   |
| Ricoh                                  | 1         | 1.28%   |
| Microsoft                              | 1         | 1.28%   |
| Luxvisions Innotech Limited            | 1         | 1.28%   |
| Hewlett-Packard                        | 1         | 1.28%   |
| Genesys Logic                          | 1         | 1.28%   |
| Generalplus Technology                 | 1         | 1.28%   |
| Cubeternet                             | 1         | 1.28%   |
| Creative Technology                    | 1         | 1.28%   |
| Bison Electronics                      | 1         | 1.28%   |
| ALi                                    | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 6         | 7.5%    |
| Realtek Integrated_Webcam_HD                        | 3         | 3.75%   |
| Logitech Webcam C270                                | 3         | 3.75%   |
| Sunplus HD WebCam                                   | 2         | 2.5%    |
| Microdia Integrated_Webcam_HD                       | 2         | 2.5%    |
| Logitech HD Pro Webcam C920                         | 2         | 2.5%    |
| Logitech B525 HD Webcam                             | 2         | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.5%    |
| IMC Networks Integrated Camera                      | 2         | 2.5%    |
| Chicony Integrated IR Camera                        | 2         | 2.5%    |
| Acer HD Webcam                                      | 2         | 2.5%    |
| Acer BisonCam,NB Pro                                | 2         | 2.5%    |
| Acer BisonCam, NB Pro                               | 2         | 2.5%    |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.25%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.25%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.25%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.25%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.25%   |
| Sunplus 1.3M HD WebCam                              | 1         | 1.25%   |
| Silicon Motion WebCam SC-13HDN10939N                | 1         | 1.25%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.25%   |
| Realtek USB Camera                                  | 1         | 1.25%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.25%   |
| Realtek Laptop_Integrated_Webcam_HD                 | 1         | 1.25%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.25%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.25%   |
| Quanta HD Webcam                                    | 1         | 1.25%   |
| Quanta HD User Facing                               | 1         | 1.25%   |
| Microsoft LifeCam VX-700                            | 1         | 1.25%   |
| Microdia Webcam Vitade AF                           | 1         | 1.25%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.25%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.25%   |
| Logitech Webcam C250                                | 1         | 1.25%   |
| Logitech QuickCam Pro 4000                          | 1         | 1.25%   |
| Logitech HD Webcam C615                             | 1         | 1.25%   |
| Lite-On Integrated Camera                           | 1         | 1.25%   |
| Lite-On HP 5MP Camera                               | 1         | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.25%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.25%   |
| HP Webcam 3100                                      | 1         | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 43.75%  |
| Validity Sensors           | 5         | 31.25%  |
| Upek                       | 1         | 6.25%   |
| STMicroelectronics         | 1         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 12.5%   |
| Synaptics  WBDI                                        | 2         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                        | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| Synaptics WBDI                                         | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.25%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 6.25%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 6.25%   |
| Unknown                                                | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| O2 Micro              | 2         | 28.57%  |
| Broadcom              | 2         | 28.57%  |
| Alcor Micro           | 2         | 28.57%  |
| Gemalto (was Gemplus) | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader              | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader               | 2         | 28.57%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 14.29%  |
| Broadcom 5880                                     | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 90        | 66.18%  |
| 1     | 37        | 27.21%  |
| 2     | 9         | 6.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 29.63%  |
| Graphics card            | 11        | 20.37%  |
| Chipcard                 | 8         | 14.81%  |
| Net/wireless             | 6         | 11.11%  |
| Sound                    | 3         | 5.56%   |
| Multimedia controller    | 3         | 5.56%   |
| Unassigned class         | 2         | 3.7%    |
| Bluetooth                | 2         | 3.7%    |
| Net/ethernet             | 1         | 1.85%   |
| Communication controller | 1         | 1.85%   |
| Camera                   | 1         | 1.85%   |

