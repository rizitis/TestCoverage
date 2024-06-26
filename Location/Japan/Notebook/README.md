Linux in Japan - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Japan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 1002

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron N5040              | [5fae884a07](https://linux-hardware.org/?probe=5fae884a07) | May 08, 2024 |
| Intel         | STCK1A32WFC H67490-302      | [51c75f3848](https://linux-hardware.org/?probe=51c75f3848) | May 08, 2024 |
| Apple         | MacBookPro11,2              | [0ff911f7ac](https://linux-hardware.org/?probe=0ff911f7ac) | May 08, 2024 |
| Fujitsu       | FMVNR1PE                    | [95504ca73e](https://linux-hardware.org/?probe=95504ca73e) | May 08, 2024 |
| NEC Comput... | PC-LS350SSB                 | [530b3713dd](https://linux-hardware.org/?probe=530b3713dd) | May 08, 2024 |
| Apple         | MacBookPro16,2              | [fe05b165fb](https://linux-hardware.org/?probe=fe05b165fb) | May 04, 2024 |
| Google        | Elemi                       | [a6ea033cf0](https://linux-hardware.org/?probe=a6ea033cf0) | May 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [8cd1bfd7aa](https://linux-hardware.org/?probe=8cd1bfd7aa) | Apr 30, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [29f2579a02](https://linux-hardware.org/?probe=29f2579a02) | Apr 27, 2024 |
| NEC Comput... | PC-LS350SSW                 | [a0abb6c6a6](https://linux-hardware.org/?probe=a0abb6c6a6) | Apr 24, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [334a6f0385](https://linux-hardware.org/?probe=334a6f0385) | Apr 24, 2024 |
| Fujitsu       | FMVA40B1RJ                  | [b0d3f0b365](https://linux-hardware.org/?probe=b0d3f0b365) | Apr 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [59aceeb367](https://linux-hardware.org/?probe=59aceeb367) | Apr 18, 2024 |
| Dell          | Latitude E5470              | [f286256e09](https://linux-hardware.org/?probe=f286256e09) | Apr 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8d0c1cd8eb](https://linux-hardware.org/?probe=8d0c1cd8eb) | Apr 12, 2024 |
| Lenovo        | G510 20238                  | [db4d2ebd4f](https://linux-hardware.org/?probe=db4d2ebd4f) | Apr 12, 2024 |
| Apple         | MacBookPro11,5              | [d48fd50ca7](https://linux-hardware.org/?probe=d48fd50ca7) | Apr 11, 2024 |
| Dell          | Latitude 3190               | [4f2b2351b3](https://linux-hardware.org/?probe=4f2b2351b3) | Apr 09, 2024 |
| Toshiba       | dynabook T554/45LB          | [da72e21681](https://linux-hardware.org/?probe=da72e21681) | Apr 07, 2024 |
| MSI           | Prestige 16 AI Studio B1... | [03e388324a](https://linux-hardware.org/?probe=03e388324a) | Apr 07, 2024 |
| HP            | Notebook                    | [7ed4d5435b](https://linux-hardware.org/?probe=7ed4d5435b) | Apr 03, 2024 |
| HP            | Notebook                    | [cefd396a65](https://linux-hardware.org/?probe=cefd396a65) | Apr 02, 2024 |
| ASUSTek       | K53TA                       | [d27da7dcab](https://linux-hardware.org/?probe=d27da7dcab) | Apr 01, 2024 |
| Toshiba       | dynabook R63/F              | [953540775e](https://linux-hardware.org/?probe=953540775e) | Mar 29, 2024 |
| Apple         | MacBookPro9,2               | [fdfc1584b0](https://linux-hardware.org/?probe=fdfc1584b0) | Mar 23, 2024 |
| NEC Comput... | PC-LE150C2                  | [3cbfa07c97](https://linux-hardware.org/?probe=3cbfa07c97) | Mar 21, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [fe203f4b3c](https://linux-hardware.org/?probe=fe203f4b3c) | Mar 20, 2024 |
| HUAWEI        | CREM-WXX9                   | [38269c9b67](https://linux-hardware.org/?probe=38269c9b67) | Mar 20, 2024 |
| HP            | ProBook 430 G7              | [05be2ac277](https://linux-hardware.org/?probe=05be2ac277) | Mar 17, 2024 |
| NEC Comput... | PC-VK23LBZDU                | [24b87183b2](https://linux-hardware.org/?probe=24b87183b2) | Mar 16, 2024 |
| Fujitsu       | FARQ10003                   | [85d8b675fc](https://linux-hardware.org/?probe=85d8b675fc) | Mar 14, 2024 |
| Toshiba       | dynabook T552/36GB          | [9da00148f4](https://linux-hardware.org/?probe=9da00148f4) | Mar 14, 2024 |
| Fujitsu       | FARQ10003                   | [c65688098c](https://linux-hardware.org/?probe=c65688098c) | Mar 13, 2024 |
| Lenovo        | ThinkPad L540 20AVA05CJP    | [ac69dd4e65](https://linux-hardware.org/?probe=ac69dd4e65) | Mar 12, 2024 |
| Panasonic ... | FZ55-3                      | [f26a0e6fd3](https://linux-hardware.org/?probe=f26a0e6fd3) | Mar 12, 2024 |
| Lenovo        | ThinkPad L540 20AVA05CJP    | [b38dfb0116](https://linux-hardware.org/?probe=b38dfb0116) | Mar 11, 2024 |
| HP            | 2133                        | [262c68f9a7](https://linux-hardware.org/?probe=262c68f9a7) | Mar 08, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [599ee90001](https://linux-hardware.org/?probe=599ee90001) | Mar 01, 2024 |
| NEC Comput... | PC-VK19SGZDF                | [ac1b71e600](https://linux-hardware.org/?probe=ac1b71e600) | Feb 24, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [65fb12c93f](https://linux-hardware.org/?probe=65fb12c93f) | Feb 22, 2024 |
| MouseCompu... | IStNX3-15HP038              | [84f30f4e97](https://linux-hardware.org/?probe=84f30f4e97) | Feb 17, 2024 |
| ASUSTek       | K95VJ                       | [c82a491d01](https://linux-hardware.org/?probe=c82a491d01) | Feb 16, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [32f752641f](https://linux-hardware.org/?probe=32f752641f) | Feb 14, 2024 |
| Toshiba       | dynabook EX/45CW            | [15397b8cd4](https://linux-hardware.org/?probe=15397b8cd4) | Feb 14, 2024 |
| Toshiba       | dynabook R730/B             | [5de02dedf5](https://linux-hardware.org/?probe=5de02dedf5) | Feb 12, 2024 |
| Lenovo        | ThinkBook 14 G6 ABP 21KJ    | [09aed6b1df](https://linux-hardware.org/?probe=09aed6b1df) | Feb 12, 2024 |
| Google        | Lindar                      | [e3a071ae43](https://linux-hardware.org/?probe=e3a071ae43) | Feb 10, 2024 |
| Sony          | VPCEB38FJ                   | [25e917a912](https://linux-hardware.org/?probe=25e917a912) | Feb 07, 2024 |
| Apple         | MacBookAir9,1               | [8aec869c33](https://linux-hardware.org/?probe=8aec869c33) | Feb 05, 2024 |
| Fujitsu       | FMVMG70WNV                  | [0b1aa48770](https://linux-hardware.org/?probe=0b1aa48770) | Feb 04, 2024 |
| Apple         | MacBookAir4,2               | [2952e00ccb](https://linux-hardware.org/?probe=2952e00ccb) | Feb 02, 2024 |
| Apple         | MacBookAir4,2               | [3173c9ba14](https://linux-hardware.org/?probe=3173c9ba14) | Feb 02, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [8689e993e3](https://linux-hardware.org/?probe=8689e993e3) | Feb 01, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [01332b7a24](https://linux-hardware.org/?probe=01332b7a24) | Feb 01, 2024 |
| Toshiba       | dynabook Satellite B552/... | [9c1f52e62f](https://linux-hardware.org/?probe=9c1f52e62f) | Jan 29, 2024 |
| Fujitsu       | FMVWG2U47                   | [3d23440c14](https://linux-hardware.org/?probe=3d23440c14) | Jan 23, 2024 |
| Lenovo        | ThinkPad T430 2347A81       | [7209687602](https://linux-hardware.org/?probe=7209687602) | Jan 22, 2024 |
| HP            | ProBook 4340s               | [45354af236](https://linux-hardware.org/?probe=45354af236) | Jan 14, 2024 |
| HP            | ProBook 4340s               | [aea3678636](https://linux-hardware.org/?probe=aea3678636) | Jan 14, 2024 |
| Valve         | Jupiter                     | [4b71896940](https://linux-hardware.org/?probe=4b71896940) | Jan 13, 2024 |
| Sony          | VPCS12AFJ                   | [b46e630517](https://linux-hardware.org/?probe=b46e630517) | Jan 05, 2024 |
| Dell          | Inspiron 5583               | [1c3475390d](https://linux-hardware.org/?probe=1c3475390d) | Jan 04, 2024 |
| NEC Comput... | PC-VK26TXZCJ                | [3e752c1012](https://linux-hardware.org/?probe=3e752c1012) | Jan 04, 2024 |
| NEC Comput... | PC-VY10ACZ75                | [0a50a9d9ad](https://linux-hardware.org/?probe=0a50a9d9ad) | Jan 03, 2024 |
| MouseCompu... | EGPN711R307                 | [fc34633537](https://linux-hardware.org/?probe=fc34633537) | Jan 02, 2024 |
| Apple         | MacBookAir9,1               | [5a511e238e](https://linux-hardware.org/?probe=5a511e238e) | Jan 01, 2024 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [b66d7c38c1](https://linux-hardware.org/?probe=b66d7c38c1) | Dec 31, 2023 |
| Thirdwave     | Prime Series                | [dc3d167b01](https://linux-hardware.org/?probe=dc3d167b01) | Dec 31, 2023 |
| NEC Comput... | PC-VK19SGZDF                | [aa9f420488](https://linux-hardware.org/?probe=aa9f420488) | Dec 31, 2023 |
| Chuwi         | GemiBook Plus               | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| Toshiba       | dynabook Satellite B552/... | [544ae58a40](https://linux-hardware.org/?probe=544ae58a40) | Dec 27, 2023 |
| Panasonic     | CFSZ5-3                     | [73265b056e](https://linux-hardware.org/?probe=73265b056e) | Dec 19, 2023 |
| Fujitsu       | FMVNF70W                    | [cbeca4d4e8](https://linux-hardware.org/?probe=cbeca4d4e8) | Dec 19, 2023 |
| Dell          | Inspiron 3580               | [1daafa6278](https://linux-hardware.org/?probe=1daafa6278) | Dec 17, 2023 |
| Lenovo        | Legion Y7000 81FW           | [71c27a1bf6](https://linux-hardware.org/?probe=71c27a1bf6) | Dec 17, 2023 |
| Apple         | MacBookAir9,1               | [73f451cbe0](https://linux-hardware.org/?probe=73f451cbe0) | Dec 17, 2023 |
| Dell          | Inspiron 3580               | [16097eb9c4](https://linux-hardware.org/?probe=16097eb9c4) | Dec 17, 2023 |
| Lenovo        | ThinkPad X260 20F5A0XWJP    | [7aede5c549](https://linux-hardware.org/?probe=7aede5c549) | Dec 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e7ca2f3a6e](https://linux-hardware.org/?probe=e7ca2f3a6e) | Dec 14, 2023 |
| Dell          | Inspiron 1501               | [c4103f9e5c](https://linux-hardware.org/?probe=c4103f9e5c) | Dec 13, 2023 |
| Dell          | Inspiron 3580               | [47f1e44c7d](https://linux-hardware.org/?probe=47f1e44c7d) | Dec 09, 2023 |
| ASUSTek       | B121                        | [25eda5a74a](https://linux-hardware.org/?probe=25eda5a74a) | Dec 04, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [3316107191](https://linux-hardware.org/?probe=3316107191) | Dec 02, 2023 |
| Sony          | VJS153C11N                  | [eb8f061cb3](https://linux-hardware.org/?probe=eb8f061cb3) | Dec 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [20ad6cbe8e](https://linux-hardware.org/?probe=20ad6cbe8e) | Dec 01, 2023 |
| NEC Comput... | PC-LS150BS6R                | [ffb64219bf](https://linux-hardware.org/?probe=ffb64219bf) | Dec 01, 2023 |
| Toshiba       | dynabook T552/36HR          | [1e3171aa0a](https://linux-hardware.org/?probe=1e3171aa0a) | Nov 30, 2023 |
| Fujitsu       | FMVNS6HE                    | [df459431eb](https://linux-hardware.org/?probe=df459431eb) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [c37b719fb5](https://linux-hardware.org/?probe=c37b719fb5) | Nov 27, 2023 |
| NEC Comput... | PC-NS100C1W-P2              | [10175626ab](https://linux-hardware.org/?probe=10175626ab) | Nov 23, 2023 |
| HP            | ENVY dv6                    | [f86a52da6d](https://linux-hardware.org/?probe=f86a52da6d) | Nov 14, 2023 |
| Acer          | Aspire 5740                 | [7deb21f5d9](https://linux-hardware.org/?probe=7deb21f5d9) | Nov 13, 2023 |
| NEC Comput... | PC-NS100C1W-P2              | [3f3c22657c](https://linux-hardware.org/?probe=3f3c22657c) | Nov 12, 2023 |
| NEC Comput... | PC-NS100C1W-P2              | [d1ccec297d](https://linux-hardware.org/?probe=d1ccec297d) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [594257aca2](https://linux-hardware.org/?probe=594257aca2) | Nov 03, 2023 |
| Toshiba       | dynabook T350/56ARK         | [802dacc8cc](https://linux-hardware.org/?probe=802dacc8cc) | Oct 27, 2023 |
| HP            | Pavilion dv7                | [15526c62b8](https://linux-hardware.org/?probe=15526c62b8) | Oct 26, 2023 |
| NEC Comput... | PC-VJ22LFWZHSRF             | [b229c83a28](https://linux-hardware.org/?probe=b229c83a28) | Oct 25, 2023 |
| Dell          | Inspiron 15 3511            | [8d2894b3d1](https://linux-hardware.org/?probe=8d2894b3d1) | Oct 24, 2023 |
| Acer          | Aspire 5740                 | [78702b9deb](https://linux-hardware.org/?probe=78702b9deb) | Oct 23, 2023 |
| Panasonic     | CFSZ5-3                     | [a70e21055d](https://linux-hardware.org/?probe=a70e21055d) | Oct 23, 2023 |
| Dell          | G15 5515                    | [16754901cb](https://linux-hardware.org/?probe=16754901cb) | Oct 23, 2023 |
| NEC Comput... | PC-VK26TLNZ39ZJ             | [86f3d9bdbe](https://linux-hardware.org/?probe=86f3d9bdbe) | Oct 19, 2023 |
| GMKtec        | NucBox5                     | [4b4319490d](https://linux-hardware.org/?probe=4b4319490d) | Oct 17, 2023 |
| MouseCompu... | GTN83G15H19C                | [39e86c5be4](https://linux-hardware.org/?probe=39e86c5be4) | Oct 17, 2023 |
| NEC Comput... | PC-VK27MDZDN                | [052e2dbcc2](https://linux-hardware.org/?probe=052e2dbcc2) | Oct 16, 2023 |
| GLM           | 14-Z8350-C                  | [2db6571799](https://linux-hardware.org/?probe=2db6571799) | Oct 15, 2023 |
| Dynabook      | B65/ER                      | [2bda5e79a4](https://linux-hardware.org/?probe=2bda5e79a4) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | [4bc1c4e1b6](https://linux-hardware.org/?probe=4bc1c4e1b6) | Oct 14, 2023 |
| Fujitsu       | FMVNS7HE                    | [2408a69be7](https://linux-hardware.org/?probe=2408a69be7) | Oct 13, 2023 |
| Toshiba       | dynabook B452/22F           | [61777cd92a](https://linux-hardware.org/?probe=61777cd92a) | Oct 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d739639932](https://linux-hardware.org/?probe=d739639932) | Oct 09, 2023 |
| Dell          | System Vostro 3750          | [1cbdc082a8](https://linux-hardware.org/?probe=1cbdc082a8) | Oct 08, 2023 |
| Fujitsu       | FMVA05007                   | [265b66f904](https://linux-hardware.org/?probe=265b66f904) | Oct 05, 2023 |
| Timi          | A30                         | [36d352fb7f](https://linux-hardware.org/?probe=36d352fb7f) | Oct 04, 2023 |
| Panasonic     | CFSZ5-3                     | [9d0b849593](https://linux-hardware.org/?probe=9d0b849593) | Oct 01, 2023 |
| Panasonic     | CFSZ5-3                     | [f2c369cb00](https://linux-hardware.org/?probe=f2c369cb00) | Oct 01, 2023 |
| Dell          | Latitude 7390               | [93e22b6fc4](https://linux-hardware.org/?probe=93e22b6fc4) | Sep 27, 2023 |
| Dell          | Latitude 7390               | [a7bfa2e285](https://linux-hardware.org/?probe=a7bfa2e285) | Sep 27, 2023 |
| Fujitsu       | FMVA42CW                    | [48a8e36d5f](https://linux-hardware.org/?probe=48a8e36d5f) | Sep 25, 2023 |
| Fujitsu       | FMVA42CW                    | [8427efde7d](https://linux-hardware.org/?probe=8427efde7d) | Sep 25, 2023 |
| Toshiba       | dynabook Satellite B552/... | [7aea90703a](https://linux-hardware.org/?probe=7aea90703a) | Sep 24, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [be07169f5c](https://linux-hardware.org/?probe=be07169f5c) | Sep 22, 2023 |
| ASUSTek       | X551CAP                     | [b90045e0f9](https://linux-hardware.org/?probe=b90045e0f9) | Sep 22, 2023 |
| ASUSTek       | TP550LAB                    | [3e07304aa5](https://linux-hardware.org/?probe=3e07304aa5) | Sep 20, 2023 |
| Dell          | Latitude 3540               | [3f1c99de44](https://linux-hardware.org/?probe=3f1c99de44) | Sep 20, 2023 |
| Lenovo        | ThinkPad X240 20AMA1S702    | [5be3b8fc11](https://linux-hardware.org/?probe=5be3b8fc11) | Sep 19, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c26fb8a8da](https://linux-hardware.org/?probe=c26fb8a8da) | Sep 18, 2023 |
| Acer          | Aspire E5-575G              | [0f0607d7e4](https://linux-hardware.org/?probe=0f0607d7e4) | Sep 18, 2023 |
| Apple         | MacBookAir4,2               | [1e61961aef](https://linux-hardware.org/?probe=1e61961aef) | Sep 17, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [1a5acc2c10](https://linux-hardware.org/?probe=1a5acc2c10) | Sep 17, 2023 |
| NEC Comput... | PC-VK15EBZDG                | [83d74c1e9d](https://linux-hardware.org/?probe=83d74c1e9d) | Sep 17, 2023 |
| HP            | Pavilion dv2                | [ee227b3d35](https://linux-hardware.org/?probe=ee227b3d35) | Sep 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8c529cfaa8](https://linux-hardware.org/?probe=8c529cfaa8) | Sep 11, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [586c1fab43](https://linux-hardware.org/?probe=586c1fab43) | Sep 06, 2023 |
| ASUSTek       | K53TA                       | [b173b156f9](https://linux-hardware.org/?probe=b173b156f9) | Sep 04, 2023 |
| Dynabook      | G83/HS                      | [9db149b715](https://linux-hardware.org/?probe=9db149b715) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1211fca3e2](https://linux-hardware.org/?probe=1211fca3e2) | Sep 03, 2023 |
| Toshiba       | dynabook R73/J              | [c63c97e4a8](https://linux-hardware.org/?probe=c63c97e4a8) | Sep 03, 2023 |
| Dell          | Inspiron 3585               | [a8bdd5bcca](https://linux-hardware.org/?probe=a8bdd5bcca) | Sep 02, 2023 |
| Lenovo        | G570 4334                   | [60c351e038](https://linux-hardware.org/?probe=60c351e038) | Sep 01, 2023 |
| Lenovo        | ThinkPad X61 76753BJ        | [f90ed18892](https://linux-hardware.org/?probe=f90ed18892) | Sep 01, 2023 |
| Lenovo        | G550 2958                   | [033a5ccf76](https://linux-hardware.org/?probe=033a5ccf76) | Sep 01, 2023 |
| System76      | Lemur Pro                   | [c04af9751f](https://linux-hardware.org/?probe=c04af9751f) | Aug 31, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [fab320d1d5](https://linux-hardware.org/?probe=fab320d1d5) | Aug 31, 2023 |
| Intel Clie... | LAPAC71H                    | [67d6ffca34](https://linux-hardware.org/?probe=67d6ffca34) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | [e5a008be38](https://linux-hardware.org/?probe=e5a008be38) | Aug 30, 2023 |
| Apple         | MacBookPro15,2              | [3bee4c1b45](https://linux-hardware.org/?probe=3bee4c1b45) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Inspiron 3580               | [0cda85fdd1](https://linux-hardware.org/?probe=0cda85fdd1) | Aug 28, 2023 |
| Timi          | A35                         | [50e380e876](https://linux-hardware.org/?probe=50e380e876) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| Dell          | Inspiron 5559               | [310e1f561c](https://linux-hardware.org/?probe=310e1f561c) | Aug 22, 2023 |
| Toshiba       | dynabook B350/22A           | [80ad4cd1ff](https://linux-hardware.org/?probe=80ad4cd1ff) | Aug 21, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | [5ed6b3612a](https://linux-hardware.org/?probe=5ed6b3612a) | Aug 17, 2023 |
| MSI           | Stealth 14Studio A13VG      | [a8035775f2](https://linux-hardware.org/?probe=a8035775f2) | Aug 14, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [9a680df78d](https://linux-hardware.org/?probe=9a680df78d) | Aug 14, 2023 |
| Fujitsu       | FMVA42CW                    | [453329dbff](https://linux-hardware.org/?probe=453329dbff) | Aug 12, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [8abafe1b65](https://linux-hardware.org/?probe=8abafe1b65) | Aug 12, 2023 |
| Gateway       | MD7309U                     | [18dbacfdab](https://linux-hardware.org/?probe=18dbacfdab) | Aug 10, 2023 |
| Fujitsu       | FMVA42CW                    | [ffb5c4343b](https://linux-hardware.org/?probe=ffb5c4343b) | Aug 10, 2023 |
| NEC Comput... | PC-GN246W3A5                | [2f37664ebd](https://linux-hardware.org/?probe=2f37664ebd) | Aug 10, 2023 |
| Sony          | VJF151                      | [b2768a0abf](https://linux-hardware.org/?probe=b2768a0abf) | Aug 09, 2023 |
| Fujitsu       | FMVA42CW                    | [83d5950b7a](https://linux-hardware.org/?probe=83d5950b7a) | Aug 08, 2023 |
| Lenovo        | ThinkPad X230 2324BV7       | [e1f092d38b](https://linux-hardware.org/?probe=e1f092d38b) | Aug 08, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [4bd753037a](https://linux-hardware.org/?probe=4bd753037a) | Aug 06, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b4cc5c436c](https://linux-hardware.org/?probe=b4cc5c436c) | Aug 06, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [4d0d3b78e7](https://linux-hardware.org/?probe=4d0d3b78e7) | Aug 02, 2023 |
| Apple         | MacBookAir9,1               | [2e59618067](https://linux-hardware.org/?probe=2e59618067) | Aug 01, 2023 |
| NEC Comput... | PC-VY22GXZCA                | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Dell          | XPS 15 9500                 | [151b7d8d31](https://linux-hardware.org/?probe=151b7d8d31) | Jul 29, 2023 |
| Dell          | Inspiron 15-3565            | [3d41743a5d](https://linux-hardware.org/?probe=3d41743a5d) | Jul 23, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21EXC... | [5777fd52c6](https://linux-hardware.org/?probe=5777fd52c6) | Jul 22, 2023 |
| Sony          | VPCEB48FJ                   | [95cab43ae1](https://linux-hardware.org/?probe=95cab43ae1) | Jul 21, 2023 |
| Panasonic     | CFSZ5-3                     | [9eb560d292](https://linux-hardware.org/?probe=9eb560d292) | Jul 20, 2023 |
| HP            | Laptop 14s-dk0xxx           | [3cf00d1f89](https://linux-hardware.org/?probe=3cf00d1f89) | Jul 16, 2023 |
| Dell          | Inspiron 3580               | [e46543841d](https://linux-hardware.org/?probe=e46543841d) | Jul 16, 2023 |
| Lenovo        | G50-70 20351                | [46a3598028](https://linux-hardware.org/?probe=46a3598028) | Jul 16, 2023 |
| Apple         | MacBookPro15,1              | [cf0f0d0820](https://linux-hardware.org/?probe=cf0f0d0820) | Jul 15, 2023 |
| Lenovo        | ThinkPad Edge E535 3260C... | [9ff1a61e2a](https://linux-hardware.org/?probe=9ff1a61e2a) | Jul 14, 2023 |
| MSI           | GF63 Thin 9SCSR             | [835e924f6d](https://linux-hardware.org/?probe=835e924f6d) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | [7bf81133fc](https://linux-hardware.org/?probe=7bf81133fc) | Jul 12, 2023 |
| Apple         | MacBookAir9,1               | [c952cab7d7](https://linux-hardware.org/?probe=c952cab7d7) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| Apple         | MacBookAir9,1               | [703f4fd012](https://linux-hardware.org/?probe=703f4fd012) | Jul 10, 2023 |
| Lenovo        | G50-70 20351                | [2349cf550c](https://linux-hardware.org/?probe=2349cf550c) | Jul 08, 2023 |
| Lenovo        | G50-70 20351                | [a5267b5818](https://linux-hardware.org/?probe=a5267b5818) | Jul 08, 2023 |
| Toshiba       | dynabook R73/Y              | [37e3897f65](https://linux-hardware.org/?probe=37e3897f65) | Jul 08, 2023 |
| Toshiba       | dynabook Satellite B552/... | [f459621198](https://linux-hardware.org/?probe=f459621198) | Jul 06, 2023 |
| Dell          | Inspiron 15-3565            | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| Gigabyte      | AERO 16 OLED BSF            | [1148bd3952](https://linux-hardware.org/?probe=1148bd3952) | Jul 04, 2023 |
| Lenovo        | ThinkPad L520 5015A12       | [0cb85712d9](https://linux-hardware.org/?probe=0cb85712d9) | Jul 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [b025249305](https://linux-hardware.org/?probe=b025249305) | Jul 03, 2023 |
| Dynabook      | B65/ER                      | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a77c825995](https://linux-hardware.org/?probe=a77c825995) | Jun 29, 2023 |
| Lenovo        | ThinkPad L520 50153CJ       | [1793064ee5](https://linux-hardware.org/?probe=1793064ee5) | Jun 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7497c404d4](https://linux-hardware.org/?probe=7497c404d4) | Jun 27, 2023 |
| Sony          | VGN-AR74DB                  | [c51cc05c0a](https://linux-hardware.org/?probe=c51cc05c0a) | Jun 25, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| Fujitsu       | FMVA42CW                    | [673cf6831d](https://linux-hardware.org/?probe=673cf6831d) | Jun 16, 2023 |
| Acer          | Aspire V3-571               | [75c2da2c37](https://linux-hardware.org/?probe=75c2da2c37) | Jun 15, 2023 |
| Dell          | Inspiron 15-3565            | [32069bc39d](https://linux-hardware.org/?probe=32069bc39d) | Jun 13, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Toshiba       | dynabook Satellite B552/... | [46c70e6e33](https://linux-hardware.org/?probe=46c70e6e33) | Jun 10, 2023 |
| Apple         | MacBookAir9,1               | [de1d4d9d23](https://linux-hardware.org/?probe=de1d4d9d23) | Jun 05, 2023 |
| Valve         | Jupiter                     | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [2bcfc48199](https://linux-hardware.org/?probe=2bcfc48199) | Jun 02, 2023 |
| Apple         | MacBookAir9,1               | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8002face48](https://linux-hardware.org/?probe=8002face48) | May 30, 2023 |
| Apple         | MacBookAir8,1               | [47b2ee3c0d](https://linux-hardware.org/?probe=47b2ee3c0d) | May 28, 2023 |
| Samsung       | 270E5G/270E5U               | [affdf49716](https://linux-hardware.org/?probe=affdf49716) | May 27, 2023 |
| Samsung       | 270E5G/270E5U               | [106bd355da](https://linux-hardware.org/?probe=106bd355da) | May 27, 2023 |
| Fujitsu       | FMVA42ERKS                  | [91fa73184c](https://linux-hardware.org/?probe=91fa73184c) | May 26, 2023 |
| Intel Clie... | LAPBC510                    | [fe45f8ba3c](https://linux-hardware.org/?probe=fe45f8ba3c) | May 26, 2023 |
| HUAWEI        | BOHB-WAX9                   | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| Lenovo        | YangTian V340-15-IML 81V... | [cedb6136dc](https://linux-hardware.org/?probe=cedb6136dc) | May 12, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| Fujitsu       | FMVA0500TP                  | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Apple         | MacBookPro11,4              | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Apple         | MacBookAir9,1               | [a0073c6ff3](https://linux-hardware.org/?probe=a0073c6ff3) | May 08, 2023 |
| ASUSTek       | X202E                       | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| Fujitsu       | FMVA42CW                    | [893d6b37e8](https://linux-hardware.org/?probe=893d6b37e8) | May 05, 2023 |
| Fujitsu       | FMVA705ABS                  | [99cb877cba](https://linux-hardware.org/?probe=99cb877cba) | May 04, 2023 |
| Toshiba       | dynabook SS M42 210E/3W     | [ad7f7da4e4](https://linux-hardware.org/?probe=ad7f7da4e4) | May 04, 2023 |
| Lenovo        | 4068AGJ                     | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| NEC Comput... | PC-LE150C2                  | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Fujitsu       | FMVA05004                   | [c494a8453d](https://linux-hardware.org/?probe=c494a8453d) | Apr 26, 2023 |
| Toshiba       | dynabook TV/68KBL           | [19c59e3701](https://linux-hardware.org/?probe=19c59e3701) | Apr 26, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Toshiba       | dynabook BX/67TG            | [5349d462cd](https://linux-hardware.org/?probe=5349d462cd) | Apr 23, 2023 |
| Fujitsu       | FMVA42CW                    | [4fb1ab7ab8](https://linux-hardware.org/?probe=4fb1ab7ab8) | Apr 22, 2023 |
| HP            | Pavilion dv6                | [b3613186fa](https://linux-hardware.org/?probe=b3613186fa) | Apr 21, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [da51714544](https://linux-hardware.org/?probe=da51714544) | Apr 21, 2023 |
| Toshiba       | dynabook T451/46EW          | [e45702b9aa](https://linux-hardware.org/?probe=e45702b9aa) | Apr 20, 2023 |
| Apple         | MacBookPro8,1               | [4e95dc284c](https://linux-hardware.org/?probe=4e95dc284c) | Apr 19, 2023 |
| Fujitsu       | FMVNA6HE                    | [609572e6f7](https://linux-hardware.org/?probe=609572e6f7) | Apr 18, 2023 |
| LG Electro... | P530-KE6BK                  | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| HP            | Laptop 15s-eq3xxx           | [3455570853](https://linux-hardware.org/?probe=3455570853) | Apr 16, 2023 |
| MSI           | Stealth 14Studio A13VF      | [b6cd64a19b](https://linux-hardware.org/?probe=b6cd64a19b) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Dell          | G7 7700                     | [9552c2ecc0](https://linux-hardware.org/?probe=9552c2ecc0) | Apr 09, 2023 |
| Toshiba       | dynabook R732/H             | [ff99abe105](https://linux-hardware.org/?probe=ff99abe105) | Apr 08, 2023 |
| Lenovo        | 3000 N200 0769DQJ           | [db1539e64a](https://linux-hardware.org/?probe=db1539e64a) | Apr 06, 2023 |
| MSI           | Delta 15 A5EFK              | [d3066bb3d4](https://linux-hardware.org/?probe=d3066bb3d4) | Apr 06, 2023 |
| Fujitsu       | FMVA45MRP2                  | [80b1f5983b](https://linux-hardware.org/?probe=80b1f5983b) | Apr 05, 2023 |
| Lenovo        | G500 20236                  | [4bbe18183a](https://linux-hardware.org/?probe=4bbe18183a) | Apr 04, 2023 |
| Toshiba       | dynabook T653/46JR          | [7f0e2d07b5](https://linux-hardware.org/?probe=7f0e2d07b5) | Apr 01, 2023 |
| Dell          | Vostro 15 3515              | [eea311b1bb](https://linux-hardware.org/?probe=eea311b1bb) | Apr 01, 2023 |
| Acer          | Aspire 1410                 | [58be80ea51](https://linux-hardware.org/?probe=58be80ea51) | Mar 31, 2023 |
| Toshiba       | dynabook T653/46JR          | [94a37d865e](https://linux-hardware.org/?probe=94a37d865e) | Mar 30, 2023 |
| MSI           | GT70 2PE                    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Apple         | MacBookPro16,2              | [cf7ab8adb4](https://linux-hardware.org/?probe=cf7ab8adb4) | Mar 26, 2023 |
| Lenovo        | ThinkPad X230 2306A44       | [e948a25ef6](https://linux-hardware.org/?probe=e948a25ef6) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | [f8fc6c74da](https://linux-hardware.org/?probe=f8fc6c74da) | Mar 25, 2023 |
| MSI           | Alpha 15 B5EEK              | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| Dell          | Inspiron 3442               | [33137a049e](https://linux-hardware.org/?probe=33137a049e) | Mar 20, 2023 |
| HUAWEI        | FRD-WX9                     | [b5a517c552](https://linux-hardware.org/?probe=b5a517c552) | Mar 20, 2023 |
| ASUSTek       | X55U                        | [b06bd51348](https://linux-hardware.org/?probe=b06bd51348) | Mar 11, 2023 |
| Google        | Bobba                       | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Dell          | Inspiron 14 5420            | [cb6ec54195](https://linux-hardware.org/?probe=cb6ec54195) | Mar 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Dell          | XPS 15 9500                 | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| Dell          | Latitude 5300               | [a77b29e10d](https://linux-hardware.org/?probe=a77b29e10d) | Mar 04, 2023 |
| Toshiba       | dynabook R73/BN             | [1d81bb5f08](https://linux-hardware.org/?probe=1d81bb5f08) | Mar 03, 2023 |
| HP            | EliteBook 2740p             | [dee37a9bd9](https://linux-hardware.org/?probe=dee37a9bd9) | Mar 01, 2023 |
| Acer          | Aspire 5740                 | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| Lenovo        | G500 20236                  | [93f09b28d6](https://linux-hardware.org/?probe=93f09b28d6) | Feb 26, 2023 |
| Lenovo        | G500 20236                  | [51bd5c9f21](https://linux-hardware.org/?probe=51bd5c9f21) | Feb 26, 2023 |
| Toshiba       | dynabook T653/46JR          | [ac156d2c80](https://linux-hardware.org/?probe=ac156d2c80) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [5d62c279d2](https://linux-hardware.org/?probe=5d62c279d2) | Feb 21, 2023 |
| HUAWEI        | KPR-WX9                     | [1f44fd5a86](https://linux-hardware.org/?probe=1f44fd5a86) | Feb 18, 2023 |
| Dell          | Latitude 5300               | [371d693177](https://linux-hardware.org/?probe=371d693177) | Feb 17, 2023 |
| Dell          | Latitude 5300               | [323f21bb1e](https://linux-hardware.org/?probe=323f21bb1e) | Feb 17, 2023 |
| Dell          | Latitude 5300               | [ca02606bea](https://linux-hardware.org/?probe=ca02606bea) | Feb 17, 2023 |
| Toshiba       | dynabook R73/BN             | [df7e69c5c4](https://linux-hardware.org/?probe=df7e69c5c4) | Feb 16, 2023 |
| EPSON DIRE... | Endeavor NY2200S            | [2be0a1a8a0](https://linux-hardware.org/?probe=2be0a1a8a0) | Feb 14, 2023 |
| EPSON DIRE... | Endeavor NY2200S            | [29b669f143](https://linux-hardware.org/?probe=29b669f143) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | [7fc3c03910](https://linux-hardware.org/?probe=7fc3c03910) | Feb 13, 2023 |
| Compaq        | 420                         | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| Lenovo        | ThinkPad L512 4444PV3       | [8965eee02f](https://linux-hardware.org/?probe=8965eee02f) | Feb 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWA1MDJ... | [cc5f5375d2](https://linux-hardware.org/?probe=cc5f5375d2) | Feb 09, 2023 |
| Toshiba       | dynabook T653/46JR          | [2422c70d2e](https://linux-hardware.org/?probe=2422c70d2e) | Feb 09, 2023 |
| HP            | Notebook                    | [7d4a89adea](https://linux-hardware.org/?probe=7d4a89adea) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c5bdedaf17](https://linux-hardware.org/?probe=c5bdedaf17) | Feb 04, 2023 |
| Toshiba       | dynabook T653/46JR          | [6c1119bb00](https://linux-hardware.org/?probe=6c1119bb00) | Feb 04, 2023 |
| Unknown       | Unknown                     | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Dell          | Inspiron 14 5420            | [deec906907](https://linux-hardware.org/?probe=deec906907) | Feb 02, 2023 |
| Fujitsu       | LIFEBOOK E744               | [b048f7d3e1](https://linux-hardware.org/?probe=b048f7d3e1) | Feb 01, 2023 |
| Unknown       | Unknown                     | [d780984cf9](https://linux-hardware.org/?probe=d780984cf9) | Jan 30, 2023 |
| Valve         | Jupiter                     | [935a50bce1](https://linux-hardware.org/?probe=935a50bce1) | Jan 30, 2023 |
| Google        | Helios                      | [c8b5d0660b](https://linux-hardware.org/?probe=c8b5d0660b) | Jan 28, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f20e47b9d7](https://linux-hardware.org/?probe=f20e47b9d7) | Jan 28, 2023 |
| NEC Comput... | PC-NS350AAR-KS              | [c4aa0da6f4](https://linux-hardware.org/?probe=c4aa0da6f4) | Jan 27, 2023 |
| HP            | ProBook 440 G5              | [af59cf3cd3](https://linux-hardware.org/?probe=af59cf3cd3) | Jan 26, 2023 |
| Toshiba       | dynabook T653/46JR          | [00cabfbb97](https://linux-hardware.org/?probe=00cabfbb97) | Jan 24, 2023 |
| Purism        | Librem 15 v3                | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| Toshiba       | dynabook T653/46JR          | [1acfabc208](https://linux-hardware.org/?probe=1acfabc208) | Jan 22, 2023 |
| Dell          | Inspiron 3585               | [9790dcdef4](https://linux-hardware.org/?probe=9790dcdef4) | Jan 19, 2023 |
| Lenovo        | G550 2958                   | [7b255b7fe7](https://linux-hardware.org/?probe=7b255b7fe7) | Jan 18, 2023 |
| Dell          | XPS 9320                    | [bd7346b7c2](https://linux-hardware.org/?probe=bd7346b7c2) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Latitude 3540               | [01688be251](https://linux-hardware.org/?probe=01688be251) | Jan 15, 2023 |
| Acer          | Aspire 5349                 | [c52d3b2b2f](https://linux-hardware.org/?probe=c52d3b2b2f) | Jan 15, 2023 |
| Fujitsu       | FMVNF70YX                   | [2817102c87](https://linux-hardware.org/?probe=2817102c87) | Jan 14, 2023 |
| HONOR         | HLYL-WXX9                   | [e5b02d94cd](https://linux-hardware.org/?probe=e5b02d94cd) | Jan 14, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [fa1ebc0951](https://linux-hardware.org/?probe=fa1ebc0951) | Jan 14, 2023 |
| Apple         | MacBookPro9,2               | [4d89e9dec4](https://linux-hardware.org/?probe=4d89e9dec4) | Jan 14, 2023 |
| Panasonic     | CFSZ6-2                     | [7a9f534294](https://linux-hardware.org/?probe=7a9f534294) | Jan 13, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | [b2965791cb](https://linux-hardware.org/?probe=b2965791cb) | Jan 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | [093e5ffc06](https://linux-hardware.org/?probe=093e5ffc06) | Jan 13, 2023 |
| ASUSTek       | E200HA                      | [4d9f4512a6](https://linux-hardware.org/?probe=4d9f4512a6) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| Dell          | Inspiron 1545               | [20bc38b554](https://linux-hardware.org/?probe=20bc38b554) | Jan 11, 2023 |
| HP            | Pavilion dv6                | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| Dell          | Inspiron 14 5420            | [9aaef76c2c](https://linux-hardware.org/?probe=9aaef76c2c) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [1d0cd9b040](https://linux-hardware.org/?probe=1d0cd9b040) | Jan 09, 2023 |
| HP            | ZHAN 66 Pro G1              | [76e588ab0a](https://linux-hardware.org/?probe=76e588ab0a) | Jan 08, 2023 |
| Valve         | Jupiter                     | [73e8740cb9](https://linux-hardware.org/?probe=73e8740cb9) | Jan 08, 2023 |
| Toshiba       | dynabook T653/46JR          | [8fe8187a9e](https://linux-hardware.org/?probe=8fe8187a9e) | Jan 08, 2023 |
| Valve         | Jupiter                     | [75cabfba4d](https://linux-hardware.org/?probe=75cabfba4d) | Jan 03, 2023 |
| Valve         | Jupiter                     | [70b2e771b7](https://linux-hardware.org/?probe=70b2e771b7) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| ASUSTek       | ZenBook UX333FN_U3300FN     | [750a40a3cc](https://linux-hardware.org/?probe=750a40a3cc) | Jan 02, 2023 |
| Toshiba       | dynabook T653/46JR          | [cac689a705](https://linux-hardware.org/?probe=cac689a705) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| Dell          | XPS 9320                    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| Unknown       | Unknown                     | [86dcc5a2ff](https://linux-hardware.org/?probe=86dcc5a2ff) | Dec 30, 2022 |
| Toshiba       | dynabook T653/46JR          | [a1f59f6ff9](https://linux-hardware.org/?probe=a1f59f6ff9) | Dec 29, 2022 |
| Apple         | MacBookPro15,2              | [e5a7b5b5be](https://linux-hardware.org/?probe=e5a7b5b5be) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| Dell          | Inspiron 5370               | [e08cfee8e8](https://linux-hardware.org/?probe=e08cfee8e8) | Dec 27, 2022 |
| Dell          | Inspiron 5370               | [071ff79fc2](https://linux-hardware.org/?probe=071ff79fc2) | Dec 27, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [0069729ebe](https://linux-hardware.org/?probe=0069729ebe) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [985e965dec](https://linux-hardware.org/?probe=985e965dec) | Dec 25, 2022 |
| Apple         | MacBookPro9,2               | [ef194165fc](https://linux-hardware.org/?probe=ef194165fc) | Dec 24, 2022 |
| Toshiba       | dynabook T653/46JR          | [1f10cd2a64](https://linux-hardware.org/?probe=1f10cd2a64) | Dec 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [4a1e660e7d](https://linux-hardware.org/?probe=4a1e660e7d) | Dec 21, 2022 |
| Sony          | VJZ13A                      | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Toshiba       | dynabook T653/46JR          | [5a05dc8c43](https://linux-hardware.org/?probe=5a05dc8c43) | Dec 17, 2022 |
| Fujitsu       | FMVNS6C3                    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Fujitsu       | FMVNS6C3                    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| Unknown       | Unknown                     | [2a7d6d1541](https://linux-hardware.org/?probe=2a7d6d1541) | Dec 08, 2022 |
| Fujitsu       | FMVNS6C3                    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| HP            | Laptop 15-bs0xx             | [81576caeb1](https://linux-hardware.org/?probe=81576caeb1) | Dec 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [601575b385](https://linux-hardware.org/?probe=601575b385) | Dec 03, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| HP            | Laptop 17-by0xxx            | [4d903aa73b](https://linux-hardware.org/?probe=4d903aa73b) | Nov 21, 2022 |
| Fujitsu       | FMVNQL7PM                   | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| NEC Comput... | PC-VK27MCZDM                | [fce4afe996](https://linux-hardware.org/?probe=fce4afe996) | Nov 19, 2022 |
| KOUZIRO       | KOUZIRONB                   | [5802e3e5d6](https://linux-hardware.org/?probe=5802e3e5d6) | Nov 17, 2022 |
| NEC Comput... | NEC VERSA M160              | [a49b4b95b9](https://linux-hardware.org/?probe=a49b4b95b9) | Nov 17, 2022 |
| Toshiba       | dynabook T653/46JR          | [09569f3154](https://linux-hardware.org/?probe=09569f3154) | Nov 17, 2022 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [69f54ed610](https://linux-hardware.org/?probe=69f54ed610) | Nov 16, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | [96db8793b2](https://linux-hardware.org/?probe=96db8793b2) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | [c576805c81](https://linux-hardware.org/?probe=c576805c81) | Nov 15, 2022 |
| HP            | Laptop 17-by0xxx            | [ecdad4661a](https://linux-hardware.org/?probe=ecdad4661a) | Nov 15, 2022 |
| Toshiba       | dynabook T653/46JR          | [69d4f912f9](https://linux-hardware.org/?probe=69d4f912f9) | Nov 15, 2022 |
| KOUZIRO       | KOUZIRONB                   | [16bf4c059c](https://linux-hardware.org/?probe=16bf4c059c) | Nov 11, 2022 |
| Toshiba       | dynabook T653/46JR          | [dfa4a8aa7f](https://linux-hardware.org/?probe=dfa4a8aa7f) | Nov 10, 2022 |
| Fujitsu       | FMVXN4MN2Z                  | [7a08a94b1e](https://linux-hardware.org/?probe=7a08a94b1e) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [972094820e](https://linux-hardware.org/?probe=972094820e) | Nov 07, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [d87e75abbf](https://linux-hardware.org/?probe=d87e75abbf) | Nov 04, 2022 |
| Dell          | Vostro 2520                 | [16239dbee4](https://linux-hardware.org/?probe=16239dbee4) | Oct 17, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| Lenovo        | ThinkPad X220 42873LJ       | [b96b26c09b](https://linux-hardware.org/?probe=b96b26c09b) | Oct 11, 2022 |
| Toshiba       | dynabook T653/46JR          | [d5f7a80d34](https://linux-hardware.org/?probe=d5f7a80d34) | Oct 06, 2022 |
| GPU Compan... | GWTC116-2                   | [68a9782e38](https://linux-hardware.org/?probe=68a9782e38) | Oct 06, 2022 |
| GPU Compan... | GWTC116-2                   | [53516b2a9d](https://linux-hardware.org/?probe=53516b2a9d) | Oct 06, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [be11beaedd](https://linux-hardware.org/?probe=be11beaedd) | Oct 02, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Dell          | Inspiron 11-3162            | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| NEC Comput... | PC-VRL21FB6S3R7             | [2001e2e28e](https://linux-hardware.org/?probe=2001e2e28e) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [d1b6a74f84](https://linux-hardware.org/?probe=d1b6a74f84) | Sep 29, 2022 |
| Toshiba       | dynabook T653/46JR          | [9a613eaf66](https://linux-hardware.org/?probe=9a613eaf66) | Sep 28, 2022 |
| Fujitsu       | FMVA1200G                   | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Toshiba       | dynabook T653/46JR          | [ee93820bdf](https://linux-hardware.org/?probe=ee93820bdf) | Sep 21, 2022 |
| NEC Comput... | PC-VK26MXZCE                | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| Toshiba       | dynabook T653/46JR          | [7f9cf09305](https://linux-hardware.org/?probe=7f9cf09305) | Sep 17, 2022 |
| EPSON DIRE... | Endeavor NJ3100E            | [47cb342ecf](https://linux-hardware.org/?probe=47cb342ecf) | Sep 16, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Dell          | Latitude 7420               | [211c7ab44c](https://linux-hardware.org/?probe=211c7ab44c) | Sep 12, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ba1f911067](https://linux-hardware.org/?probe=ba1f911067) | Sep 10, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [c34e343671](https://linux-hardware.org/?probe=c34e343671) | Sep 05, 2022 |
| Panasonic     | CFSV9-1                     | [c21f59dee9](https://linux-hardware.org/?probe=c21f59dee9) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [adfeeb4193](https://linux-hardware.org/?probe=adfeeb4193) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [b97366daa0](https://linux-hardware.org/?probe=b97366daa0) | Aug 27, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | [a7c9d17455](https://linux-hardware.org/?probe=a7c9d17455) | Aug 25, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Fujitsu       | FMVA42CW                    | [f50babde6a](https://linux-hardware.org/?probe=f50babde6a) | Aug 23, 2022 |
| Toshiba       | dynabook T653/46JR          | [decfecaa20](https://linux-hardware.org/?probe=decfecaa20) | Aug 18, 2022 |
| MSI           | Delta 15 A5EFK              | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| Toshiba       | dynabook T75/RW             | [ff35aa835d](https://linux-hardware.org/?probe=ff35aa835d) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| System76      | Oryx Pro                    | [87b38f5a99](https://linux-hardware.org/?probe=87b38f5a99) | Aug 12, 2022 |
| Dell          | XPS 15 9500                 | [d8486d3371](https://linux-hardware.org/?probe=d8486d3371) | Aug 07, 2022 |
| Toshiba       | dynabook R732/G             | [82ef8736b3](https://linux-hardware.org/?probe=82ef8736b3) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7151e1746a](https://linux-hardware.org/?probe=7151e1746a) | Aug 05, 2022 |
| Toshiba       | dynabook T653/46JR          | [ea8bb6486b](https://linux-hardware.org/?probe=ea8bb6486b) | Jul 30, 2022 |
| Toshiba       | dynabook B350/22A           | [7a5344db19](https://linux-hardware.org/?probe=7a5344db19) | Jul 28, 2022 |
| Toshiba       | dynabook R734/K             | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| NEC Comput... | U2                          | [22314f4475](https://linux-hardware.org/?probe=22314f4475) | Jul 25, 2022 |
| Dell          | Latitude 7320               | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Apple         | MacBookAir9,1               | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| Alienware     | m17                         | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| NEC Comput... | PC-VJ24LLZCB                | [9b0955cfe2](https://linux-hardware.org/?probe=9b0955cfe2) | Jul 23, 2022 |
| Apple         | MacBookPro9,2               | [2ba1ac3ec9](https://linux-hardware.org/?probe=2ba1ac3ec9) | Jul 23, 2022 |
| MouseCompu... | L140MU                      | [5206d679a2](https://linux-hardware.org/?probe=5206d679a2) | Jul 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| Panasonic     | CF-S10EYADR                 | [1990cd2a08](https://linux-hardware.org/?probe=1990cd2a08) | Jul 13, 2022 |
| Apple         | MacBookPro15,1              | [42d81e0803](https://linux-hardware.org/?probe=42d81e0803) | Jul 13, 2022 |
| Lenovo        | G575 4383                   | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| Apple         | MacBookPro14,1              | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [fc3e083086](https://linux-hardware.org/?probe=fc3e083086) | Jun 26, 2022 |
| Panasonic     | CFSV9-1                     | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| ASUSTek       | T100HAN                     | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [cbf5603095](https://linux-hardware.org/?probe=cbf5603095) | Jun 13, 2022 |
| Dell          | XPS 15 9500                 | [197482fd83](https://linux-hardware.org/?probe=197482fd83) | Jun 13, 2022 |
| ASUSTek       | T100HAN                     | [9a5b9400a1](https://linux-hardware.org/?probe=9a5b9400a1) | Jun 12, 2022 |
| Sony          | VGN-Z71JB                   | [95a370d4e4](https://linux-hardware.org/?probe=95a370d4e4) | Jun 08, 2022 |
| Alienware     | 13 R3                       | [1431b0b659](https://linux-hardware.org/?probe=1431b0b659) | Jun 06, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| MSI           | Delta 15 A5EFK              | [1679888c2c](https://linux-hardware.org/?probe=1679888c2c) | May 29, 2022 |
| ASUSTek       | 900                         | [e50c30c38d](https://linux-hardware.org/?probe=e50c30c38d) | May 28, 2022 |
| ASUSTek       | 900                         | [dfd6af657c](https://linux-hardware.org/?probe=dfd6af657c) | May 28, 2022 |
| Gateway       | NV57H                       | [75c484ec74](https://linux-hardware.org/?probe=75c484ec74) | May 26, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| MouseCompu... | B5-R5RENASW11               | [35eae81eca](https://linux-hardware.org/?probe=35eae81eca) | May 25, 2022 |
| ASUSTek       | 900                         | [082b51aa29](https://linux-hardware.org/?probe=082b51aa29) | May 21, 2022 |
| HP            | ProBook 430 G7              | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | G550 2958                   | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Dell          | XPS 15 9500                 | [671279f960](https://linux-hardware.org/?probe=671279f960) | May 18, 2022 |
| TUXEDO        | P95_HR                      | [05d8136964](https://linux-hardware.org/?probe=05d8136964) | May 15, 2022 |
| Dell          | Inspiron 11-3162            | [d1e811474c](https://linux-hardware.org/?probe=d1e811474c) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Alienware     | 17                          | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| Toshiba       | PORTEGE Z930                | [fff817aea6](https://linux-hardware.org/?probe=fff817aea6) | May 10, 2022 |
| Thirdwave     | DX-T7                       | [b90ec1bf3a](https://linux-hardware.org/?probe=b90ec1bf3a) | May 10, 2022 |
| Fujitsu       | FMVNTCAKB                   | [66083f4e27](https://linux-hardware.org/?probe=66083f4e27) | May 09, 2022 |
| HP            | EliteBook 840 G3            | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| ASUSTek       | 900                         | [a4dc643c13](https://linux-hardware.org/?probe=a4dc643c13) | May 08, 2022 |
| ASUSTek       | 900                         | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Toshiba       | dynabook R731/37EK          | [10ed6c8741](https://linux-hardware.org/?probe=10ed6c8741) | May 06, 2022 |
| Acer          | Aspire 5740                 | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| ASUSTek       | 900                         | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Acer          | Aspire 5740                 | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Acer          | Aspire 5740                 | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | Inspiron 15-3565            | [a26578c0fc](https://linux-hardware.org/?probe=a26578c0fc) | Apr 30, 2022 |
| Dell          | Inspiron 15-3565            | [66d159169f](https://linux-hardware.org/?probe=66d159169f) | Apr 28, 2022 |
| Purism        | Librem 15 v3                | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| MouseCompu... | NH55Dx                      | [0a397dd5e7](https://linux-hardware.org/?probe=0a397dd5e7) | Apr 25, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [9edf97b766](https://linux-hardware.org/?probe=9edf97b766) | Apr 24, 2022 |
| Panasonic     | CF-S10EYADR                 | [efd3e5ce84](https://linux-hardware.org/?probe=efd3e5ce84) | Apr 18, 2022 |
| TUXEDO        | P95_HR                      | [a3996b5033](https://linux-hardware.org/?probe=a3996b5033) | Apr 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c6f1d1b99b](https://linux-hardware.org/?probe=c6f1d1b99b) | Apr 16, 2022 |
| Thirdwave     | DX-T7                       | [b03707283b](https://linux-hardware.org/?probe=b03707283b) | Apr 16, 2022 |
| Dell          | Vostro 2520                 | [fd8d5ab56a](https://linux-hardware.org/?probe=fd8d5ab56a) | Apr 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [29c02b0294](https://linux-hardware.org/?probe=29c02b0294) | Apr 12, 2022 |
| Acer          | Swift SF314-54              | [c40cfcc7fe](https://linux-hardware.org/?probe=c40cfcc7fe) | Apr 12, 2022 |
| MSI           | GP76 Leopard 11UG           | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [5a344e20d6](https://linux-hardware.org/?probe=5a344e20d6) | Apr 06, 2022 |
| Toshiba       | dynabook R73/BN             | [af1ad57286](https://linux-hardware.org/?probe=af1ad57286) | Apr 06, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | [188a7794dd](https://linux-hardware.org/?probe=188a7794dd) | Apr 04, 2022 |
| TUXEDO        | P95_HR                      | [41cd5e79c8](https://linux-hardware.org/?probe=41cd5e79c8) | Apr 03, 2022 |
| MouseCompu... | MB-J370                     | [2c72ea9b17](https://linux-hardware.org/?probe=2c72ea9b17) | Apr 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [d17d5e5310](https://linux-hardware.org/?probe=d17d5e5310) | Apr 01, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Apple         | MacBookPro15,1              | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| System76      | Lemur Pro                   | [cd847b5e6a](https://linux-hardware.org/?probe=cd847b5e6a) | Mar 23, 2022 |
| Apple         | MacBookPro5,5               | [0e17f0194f](https://linux-hardware.org/?probe=0e17f0194f) | Mar 22, 2022 |
| Fujitsu       | FMVA05003                   | [d61a791168](https://linux-hardware.org/?probe=d61a791168) | Mar 19, 2022 |
| HP            | EliteBook 830 G6            | [46f513206b](https://linux-hardware.org/?probe=46f513206b) | Mar 18, 2022 |
| Dell          | G3 3500                     | [9ca3e10f43](https://linux-hardware.org/?probe=9ca3e10f43) | Mar 14, 2022 |
| R.W.C         | RM-A107-SR                  | [ab4bef6a90](https://linux-hardware.org/?probe=ab4bef6a90) | Mar 13, 2022 |
| Dell          | Latitude E5470              | [7fcd9d2c98](https://linux-hardware.org/?probe=7fcd9d2c98) | Mar 11, 2022 |
| Acer          | Aspire 4750                 | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [2f2d99c83f](https://linux-hardware.org/?probe=2f2d99c83f) | Mar 03, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [0d0a2bab7a](https://linux-hardware.org/?probe=0d0a2bab7a) | Mar 03, 2022 |
| HP            | Notebook                    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| Fujitsu       | FMVA05007                   | [21c7863329](https://linux-hardware.org/?probe=21c7863329) | Feb 27, 2022 |
| Fujitsu       | FMVA33LB2                   | [2dc30249b7](https://linux-hardware.org/?probe=2dc30249b7) | Feb 26, 2022 |
| Lenovo        | ThinkPad X220 4290LG4       | [bfb13999b0](https://linux-hardware.org/?probe=bfb13999b0) | Feb 26, 2022 |
| Fujitsu       | FMVA42CW                    | [ec10edeb39](https://linux-hardware.org/?probe=ec10edeb39) | Feb 22, 2022 |
| Panasonic     | CFSV9-1                     | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| Dell          | Vostro 3405                 | [f869338cb0](https://linux-hardware.org/?probe=f869338cb0) | Feb 20, 2022 |
| Apple         | MacBookAir3,2               | [2e812a8de9](https://linux-hardware.org/?probe=2e812a8de9) | Feb 17, 2022 |
| Fujitsu       | FARQ02010                   | [04fbabcfd2](https://linux-hardware.org/?probe=04fbabcfd2) | Feb 15, 2022 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [681aa0b345](https://linux-hardware.org/?probe=681aa0b345) | Feb 13, 2022 |
| Lenovo        | G570 4334                   | [f5cef9fe9b](https://linux-hardware.org/?probe=f5cef9fe9b) | Feb 13, 2022 |
| ASUSTek       | U24A                        | [47e8fc096a](https://linux-hardware.org/?probe=47e8fc096a) | Feb 10, 2022 |
| Dell          | XPS L401X                   | [1db7a71e79](https://linux-hardware.org/?probe=1db7a71e79) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [76a7934681](https://linux-hardware.org/?probe=76a7934681) | Feb 09, 2022 |
| Lenovo        | G505 20240                  | [ed806edbbb](https://linux-hardware.org/?probe=ed806edbbb) | Feb 09, 2022 |
| Lenovo        | ThinkPad X240 20ALCTO1WW    | [1620a85467](https://linux-hardware.org/?probe=1620a85467) | Feb 08, 2022 |
| ASUSTek       | X541SA                      | [afafec99f9](https://linux-hardware.org/?probe=afafec99f9) | Feb 08, 2022 |
| Toshiba       | dynabook Satellite B453/... | [279ff9b0f0](https://linux-hardware.org/?probe=279ff9b0f0) | Feb 08, 2022 |
| ASUSTek       | S101                        | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| ASUSTek       | U24A                        | [c49e4b9513](https://linux-hardware.org/?probe=c49e4b9513) | Jan 31, 2022 |
| AMI           | Intel                       | [33011a4745](https://linux-hardware.org/?probe=33011a4745) | Jan 31, 2022 |
| AMI           | Intel                       | [f749123fdd](https://linux-hardware.org/?probe=f749123fdd) | Jan 31, 2022 |
| ASUSTek       | U24A                        | [cc19cff1a9](https://linux-hardware.org/?probe=cc19cff1a9) | Jan 30, 2022 |
| Fujitsu       | FMVA42CW                    | [ee9b2f44e9](https://linux-hardware.org/?probe=ee9b2f44e9) | Jan 29, 2022 |
| ASUSTek       | UX303LA                     | [b5e498daf0](https://linux-hardware.org/?probe=b5e498daf0) | Jan 28, 2022 |
| Acer          | Aspire V3-571               | [3d4087dc2a](https://linux-hardware.org/?probe=3d4087dc2a) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Fujitsu       | FMVA42CW                    | [4ba92ab5ea](https://linux-hardware.org/?probe=4ba92ab5ea) | Jan 23, 2022 |
| Dell          | Latitude 3540               | [28339307b2](https://linux-hardware.org/?probe=28339307b2) | Jan 21, 2022 |
| ASUSTek       | 1000H                       | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| KOUZIRO       | KOUZIRONB                   | [56b639daeb](https://linux-hardware.org/?probe=56b639daeb) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [8f0b1342b0](https://linux-hardware.org/?probe=8f0b1342b0) | Jan 10, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [73ff2bcb33](https://linux-hardware.org/?probe=73ff2bcb33) | Jan 10, 2022 |
| Acer          | Predator PH315-53           | [7f928f794b](https://linux-hardware.org/?probe=7f928f794b) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| Dell          | Inspiron 5557               | [53d769eaf7](https://linux-hardware.org/?probe=53d769eaf7) | Dec 31, 2021 |
| System76      | Lemur Pro                   | [287aa601fe](https://linux-hardware.org/?probe=287aa601fe) | Dec 29, 2021 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [0b20db823c](https://linux-hardware.org/?probe=0b20db823c) | Dec 29, 2021 |
| Dell          | Latitude 12 Rugged Table... | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| MSI           | Delta 15 A5EFK              | [68010a3af5](https://linux-hardware.org/?probe=68010a3af5) | Dec 23, 2021 |
| MSI           | Delta 15 A5EFK              | [2d4a0a1823](https://linux-hardware.org/?probe=2d4a0a1823) | Dec 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ded54cb08c](https://linux-hardware.org/?probe=ded54cb08c) | Dec 19, 2021 |
| Dell          | Inspiron 13 5310            | [bdad2f1618](https://linux-hardware.org/?probe=bdad2f1618) | Dec 14, 2021 |
| ASUSTek       | X510UQ                      | [1b14f17a6e](https://linux-hardware.org/?probe=1b14f17a6e) | Dec 11, 2021 |
| Apple         | MacBookPro12,1              | [a6e257304d](https://linux-hardware.org/?probe=a6e257304d) | Dec 05, 2021 |
| Toshiba       | dynabook Satellite B552/... | [b3c78d548b](https://linux-hardware.org/?probe=b3c78d548b) | Dec 03, 2021 |
| Apple         | MacBookPro13,2              | [d5c66e036d](https://linux-hardware.org/?probe=d5c66e036d) | Dec 02, 2021 |
| Notebook      | N13_N140ZU                  | [d63f7874c8](https://linux-hardware.org/?probe=d63f7874c8) | Nov 29, 2021 |
| Dell          | G3 3779                     | [cd6dace549](https://linux-hardware.org/?probe=cd6dace549) | Nov 26, 2021 |
| Notebook      | N13_N140ZU                  | [dca6d021bb](https://linux-hardware.org/?probe=dca6d021bb) | Nov 23, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [fdb480d5f4](https://linux-hardware.org/?probe=fdb480d5f4) | Nov 12, 2021 |
| Lenovo        | G580 26897JJ                | [dc2120663a](https://linux-hardware.org/?probe=dc2120663a) | Nov 10, 2021 |
| Dell          | Inspiron M5110              | [4a6d42444c](https://linux-hardware.org/?probe=4a6d42444c) | Nov 10, 2021 |
| System76      | Lemur Pro                   | [92a5e9c183](https://linux-hardware.org/?probe=92a5e9c183) | Nov 09, 2021 |
| Dell          | Inspiron 16 7610            | [34e330ff50](https://linux-hardware.org/?probe=34e330ff50) | Nov 07, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [0193f0b7a0](https://linux-hardware.org/?probe=0193f0b7a0) | Nov 06, 2021 |
| Timi          | RedmiBook Pro 14S           | [470204d924](https://linux-hardware.org/?probe=470204d924) | Nov 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [f7309ef31a](https://linux-hardware.org/?probe=f7309ef31a) | Oct 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [26adc81160](https://linux-hardware.org/?probe=26adc81160) | Oct 30, 2021 |
| Toshiba       | PORTEGE Z20t-C              | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Dell          | G5 5500                     | [cf10cd5b99](https://linux-hardware.org/?probe=cf10cd5b99) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | [1f26867986](https://linux-hardware.org/?probe=1f26867986) | Oct 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6aa4ae0da5](https://linux-hardware.org/?probe=6aa4ae0da5) | Oct 23, 2021 |
| HP            | ProBook 6550b               | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Dell          | G3 3779                     | [a84248c5d5](https://linux-hardware.org/?probe=a84248c5d5) | Oct 21, 2021 |
| Jumper        | Ezbook X3                   | [fe510b821a](https://linux-hardware.org/?probe=fe510b821a) | Oct 17, 2021 |
| UNITCOM       | W55xEU                      | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| NEC Comput... | PC-LL550VG6R                | [5879ce1d61](https://linux-hardware.org/?probe=5879ce1d61) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| Toshiba       | dynabook R634/K             | [f0e385cbfb](https://linux-hardware.org/?probe=f0e385cbfb) | Oct 08, 2021 |
| Acer          | Nitro AN515-45              | [6918b927d0](https://linux-hardware.org/?probe=6918b927d0) | Oct 07, 2021 |
| Dell          | XPS 13 9380                 | [0b768f6fac](https://linux-hardware.org/?probe=0b768f6fac) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c920ce007](https://linux-hardware.org/?probe=1c920ce007) | Oct 03, 2021 |
| Fujitsu       | U9311                       | [a76f2fbbe3](https://linux-hardware.org/?probe=a76f2fbbe3) | Sep 30, 2021 |
| Panasonic     | CFSV9-2                     | [05b8edc925](https://linux-hardware.org/?probe=05b8edc925) | Sep 29, 2021 |
| NEC Comput... | PC-GN15B79AA                | [a1046b626e](https://linux-hardware.org/?probe=a1046b626e) | Sep 23, 2021 |
| NEC Comput... | PC-GN15B79AA                | [a1b9f1dc30](https://linux-hardware.org/?probe=a1b9f1dc30) | Sep 23, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [b0289ef67d](https://linux-hardware.org/?probe=b0289ef67d) | Sep 22, 2021 |
| Apple         | MacBook7,1                  | [5164ba24f6](https://linux-hardware.org/?probe=5164ba24f6) | Sep 21, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6f52a2ebed](https://linux-hardware.org/?probe=6f52a2ebed) | Sep 18, 2021 |
| Apple         | MacBookPro5,5               | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Panasonic     | CF-S10EYTDR                 | [a90d037dcf](https://linux-hardware.org/?probe=a90d037dcf) | Sep 10, 2021 |
| ASUSTek       | G551JM                      | [9f323164cd](https://linux-hardware.org/?probe=9f323164cd) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| TUXEDO        | P95_HR                      | [f5d32061ec](https://linux-hardware.org/?probe=f5d32061ec) | Sep 08, 2021 |
| Toshiba       | dynabook T55/PW             | [1ce1b25ad5](https://linux-hardware.org/?probe=1ce1b25ad5) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 2306A44       | [8f97e284a7](https://linux-hardware.org/?probe=8f97e284a7) | Sep 03, 2021 |
| Toshiba       | dynabook R73/A              | [deb0351e19](https://linux-hardware.org/?probe=deb0351e19) | Sep 03, 2021 |
| Acer          | Aspire V5-571G              | [919b7c1304](https://linux-hardware.org/?probe=919b7c1304) | Sep 01, 2021 |
| Acer          | Aspire V5-471               | [469dc0f2ef](https://linux-hardware.org/?probe=469dc0f2ef) | Aug 31, 2021 |
| Acer          | Aspire V5-471               | [47f44e561f](https://linux-hardware.org/?probe=47f44e561f) | Aug 31, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Sony          | VGN-S55B_S                  | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| HP            | Laptop 15s-eq1xxx           | [90446b95e6](https://linux-hardware.org/?probe=90446b95e6) | Aug 21, 2021 |
| HP            | ProBook 6470b               | [4d338e7f16](https://linux-hardware.org/?probe=4d338e7f16) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [9b9cd9a995](https://linux-hardware.org/?probe=9b9cd9a995) | Aug 10, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | [32e6ec699f](https://linux-hardware.org/?probe=32e6ec699f) | Aug 09, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | [7facd0568b](https://linux-hardware.org/?probe=7facd0568b) | Aug 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS8E700    | [467f177df6](https://linux-hardware.org/?probe=467f177df6) | Aug 09, 2021 |
| NEC Comput... | PC-GN246W3A5                | [dfc05750e3](https://linux-hardware.org/?probe=dfc05750e3) | Aug 09, 2021 |
| Panasonic     | CF-S10EYTDR                 | [b965812f09](https://linux-hardware.org/?probe=b965812f09) | Aug 06, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [ff5bee5ff8](https://linux-hardware.org/?probe=ff5bee5ff8) | Aug 01, 2021 |
| Chuwi         | GemiBook Pro                | [a4ecebc31b](https://linux-hardware.org/?probe=a4ecebc31b) | Jul 27, 2021 |
| Chuwi         | GemiBook Pro                | [63b014e84e](https://linux-hardware.org/?probe=63b014e84e) | Jul 26, 2021 |
| Chuwi         | GemiBook Pro                | [478d06f2df](https://linux-hardware.org/?probe=478d06f2df) | Jul 26, 2021 |
| Acer          | Nitro AN515-45              | [fbf1f240f4](https://linux-hardware.org/?probe=fbf1f240f4) | Jul 24, 2021 |
| Fujitsu       | FMVS03004                   | [0182178989](https://linux-hardware.org/?probe=0182178989) | Jul 24, 2021 |
| HP            | 14                          | [29af89c91b](https://linux-hardware.org/?probe=29af89c91b) | Jul 23, 2021 |
| HP            | 14                          | [345be169ae](https://linux-hardware.org/?probe=345be169ae) | Jul 20, 2021 |
| Fujitsu       | FMVS54CD1                   | [7e6aa1f514](https://linux-hardware.org/?probe=7e6aa1f514) | Jul 18, 2021 |
| Dell          | Inspiron N5110              | [80b10e8187](https://linux-hardware.org/?probe=80b10e8187) | Jul 18, 2021 |
| Fujitsu       | FMVS54CD1                   | [ad9e144c6a](https://linux-hardware.org/?probe=ad9e144c6a) | Jul 15, 2021 |
| Dell          | Latitude E5510              | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| Toshiba       | dynabook T954/89L           | [176e4906db](https://linux-hardware.org/?probe=176e4906db) | Jul 12, 2021 |
| Dell          | Inspiron 1526               | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Google        | Helios                      | [644f9f9062](https://linux-hardware.org/?probe=644f9f9062) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | [db7536f5a7](https://linux-hardware.org/?probe=db7536f5a7) | Jun 29, 2021 |
| Dell          | Inspiron 5583               | [a1f0396c8e](https://linux-hardware.org/?probe=a1f0396c8e) | Jun 29, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| Toshiba       | dynabook T954/89L           | [c4b1b8aabb](https://linux-hardware.org/?probe=c4b1b8aabb) | Jun 21, 2021 |
| Toshiba       | dynabook T954/89L           | [b6a5d80f8a](https://linux-hardware.org/?probe=b6a5d80f8a) | Jun 21, 2021 |
| Lenovo        | S10-3                       | [eb48df4717](https://linux-hardware.org/?probe=eb48df4717) | Jun 20, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [2da9390d91](https://linux-hardware.org/?probe=2da9390d91) | Jun 11, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [c33921449f](https://linux-hardware.org/?probe=c33921449f) | Jun 10, 2021 |
| Toshiba       | dynabook R73/BN             | [c9cdf2bc57](https://linux-hardware.org/?probe=c9cdf2bc57) | Jun 06, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [0860242147](https://linux-hardware.org/?probe=0860242147) | Jun 04, 2021 |
| Lenovo        | ThinkPad T420s 4170CTO      | [74057c8385](https://linux-hardware.org/?probe=74057c8385) | May 30, 2021 |
| Lenovo        | S10-3                       | [8dfadf5edb](https://linux-hardware.org/?probe=8dfadf5edb) | May 27, 2021 |
| NEC Comput... | PC-LL730TG                  | [e4172892e9](https://linux-hardware.org/?probe=e4172892e9) | May 26, 2021 |
| Notebook      | N13_N140ZU                  | [4d1d4e61c3](https://linux-hardware.org/?probe=4d1d4e61c3) | May 25, 2021 |
| NEC Comput... | PC-VK22TGGCN                | [b6a2893c7e](https://linux-hardware.org/?probe=b6a2893c7e) | May 25, 2021 |
| Dell          | Latitude E6420              | [4ef6253092](https://linux-hardware.org/?probe=4ef6253092) | May 22, 2021 |
| Dell          | XPS 13 9360                 | [4ea4747cbf](https://linux-hardware.org/?probe=4ea4747cbf) | May 18, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [5d215fafdd](https://linux-hardware.org/?probe=5d215fafdd) | May 15, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [fdc8841fca](https://linux-hardware.org/?probe=fdc8841fca) | May 14, 2021 |
| Fujitsu       | FMVWE3AB11                  | [6c767dc0df](https://linux-hardware.org/?probe=6c767dc0df) | May 13, 2021 |
| Fujitsu       | FMVWE3AB11                  | [5ed8fb5a9f](https://linux-hardware.org/?probe=5ed8fb5a9f) | May 13, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | [02280704ba](https://linux-hardware.org/?probe=02280704ba) | May 11, 2021 |
| Dell          | Inspiron 1545               | [c796c57372](https://linux-hardware.org/?probe=c796c57372) | May 10, 2021 |
| Fujitsu       | FMVWE3AB11                  | [e7238c107c](https://linux-hardware.org/?probe=e7238c107c) | May 09, 2021 |
| Fujitsu       | FMVNF40UK                   | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| MouseCompu... | W150ERQ                     | [1ccfec5c8f](https://linux-hardware.org/?probe=1ccfec5c8f) | May 07, 2021 |
| Dell          | XPS 13 9360                 | [f001bddea6](https://linux-hardware.org/?probe=f001bddea6) | May 04, 2021 |
| Fujitsu       | FMVWE3AB11                  | [65dce9cf99](https://linux-hardware.org/?probe=65dce9cf99) | May 03, 2021 |
| Dynabook      | P1-T6NP-EG                  | [887c9157d0](https://linux-hardware.org/?probe=887c9157d0) | May 03, 2021 |
| Toshiba       | dynabook Satellite J61 1... | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Maibenben     | S431                        | [a4db49a83f](https://linux-hardware.org/?probe=a4db49a83f) | Apr 29, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| KOUZIRO       | KOUZIRONB                   | [c64bf46d8b](https://linux-hardware.org/?probe=c64bf46d8b) | Apr 24, 2021 |
| HP            | Laptop 15-db0xxx            | [7a4d236e06](https://linux-hardware.org/?probe=7a4d236e06) | Apr 24, 2021 |
| Dell          | XPS 13 9360                 | [dae1fdda5f](https://linux-hardware.org/?probe=dae1fdda5f) | Apr 23, 2021 |
| Lenovo        | ThinkBook 15p 20V3          | [fff82cb538](https://linux-hardware.org/?probe=fff82cb538) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| TUXEDO        | P95_HR                      | [4afc76cdbe](https://linux-hardware.org/?probe=4afc76cdbe) | Apr 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Dell          | Precision M4800             | [7a2924ab2a](https://linux-hardware.org/?probe=7a2924ab2a) | Apr 13, 2021 |
| HP            | Pavilion dv4                | [c5ed691eb7](https://linux-hardware.org/?probe=c5ed691eb7) | Apr 13, 2021 |
| KOUZIRO       | KOUZIRONB                   | [18adf344fe](https://linux-hardware.org/?probe=18adf344fe) | Apr 11, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | [122641cd7e](https://linux-hardware.org/?probe=122641cd7e) | Apr 08, 2021 |
| NEC Comput... | PC-VK25TXZCE                | [e6acc84298](https://linux-hardware.org/?probe=e6acc84298) | Apr 07, 2021 |
| Toshiba       | dynabook BX/33M             | [06580ff422](https://linux-hardware.org/?probe=06580ff422) | Apr 06, 2021 |
| Lenovo        | ThinkPad X230 23245Y1       | [83430b3adf](https://linux-hardware.org/?probe=83430b3adf) | Apr 06, 2021 |
| Dynabook      | P1-T6NP-EG                  | [3f0b2d7c1d](https://linux-hardware.org/?probe=3f0b2d7c1d) | Apr 05, 2021 |
| Toshiba       | dynabook CX/48F             | [d32bf9dced](https://linux-hardware.org/?probe=d32bf9dced) | Apr 02, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [a82050e3ae](https://linux-hardware.org/?probe=a82050e3ae) | Apr 01, 2021 |
| Toshiba       | dynabook Satellite B552/... | [0a547ba59a](https://linux-hardware.org/?probe=0a547ba59a) | Mar 31, 2021 |
| Dell          | Latitude E6320              | [2c01829c5b](https://linux-hardware.org/?probe=2c01829c5b) | Mar 28, 2021 |
| Dell          | G3 3500                     | [83f2a24875](https://linux-hardware.org/?probe=83f2a24875) | Mar 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [22b865b40a](https://linux-hardware.org/?probe=22b865b40a) | Mar 26, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [43c49d259d](https://linux-hardware.org/?probe=43c49d259d) | Mar 26, 2021 |
| HP            | G60                         | [a97ca105eb](https://linux-hardware.org/?probe=a97ca105eb) | Mar 25, 2021 |
| HP            | G60                         | [e8cc7247c7](https://linux-hardware.org/?probe=e8cc7247c7) | Mar 23, 2021 |
| TUXEDO        | P95_HR                      | [22b092fe80](https://linux-hardware.org/?probe=22b092fe80) | Mar 23, 2021 |
| Unknown       | Unknown                     | [a4b57558c3](https://linux-hardware.org/?probe=a4b57558c3) | Mar 22, 2021 |
| HP            | ProBook 430 G7              | [fbf317133b](https://linux-hardware.org/?probe=fbf317133b) | Mar 21, 2021 |
| Toshiba       | dynabook Satellite B552/... | [56a39af725](https://linux-hardware.org/?probe=56a39af725) | Mar 20, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [2d9b9381bd](https://linux-hardware.org/?probe=2d9b9381bd) | Mar 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Fujitsu       | FMVA05007                   | [707f6a3ea5](https://linux-hardware.org/?probe=707f6a3ea5) | Mar 14, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T3C... | [7cda624782](https://linux-hardware.org/?probe=7cda624782) | Mar 12, 2021 |
| Dynabook      | GCX83/PLE                   | [2ef2ac3448](https://linux-hardware.org/?probe=2ef2ac3448) | Mar 12, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Inspiron N5110              | [3feff6616d](https://linux-hardware.org/?probe=3feff6616d) | Mar 07, 2021 |
| Dell          | Latitude 7280               | [64e390d0d6](https://linux-hardware.org/?probe=64e390d0d6) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [24088afc25](https://linux-hardware.org/?probe=24088afc25) | Mar 06, 2021 |
| Timi          | RedmiBook 16                | [7139d19a98](https://linux-hardware.org/?probe=7139d19a98) | Mar 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e840817785](https://linux-hardware.org/?probe=e840817785) | Mar 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5f5d47e737](https://linux-hardware.org/?probe=5f5d47e737) | Feb 26, 2021 |
| Lenovo        | Yoga 3 14 80JH              | [b1a878b7d0](https://linux-hardware.org/?probe=b1a878b7d0) | Feb 26, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Apple         | MacBookPro9,2               | [3e009dec2f](https://linux-hardware.org/?probe=3e009dec2f) | Feb 23, 2021 |
| NEC Comput... | PC-LL750FS6R                | [2708ba9972](https://linux-hardware.org/?probe=2708ba9972) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | [fa1eb2a97a](https://linux-hardware.org/?probe=fa1eb2a97a) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | [cf754cecc4](https://linux-hardware.org/?probe=cf754cecc4) | Feb 23, 2021 |
| Toshiba       | dynabook Satellite TXW/6... | [51128d9716](https://linux-hardware.org/?probe=51128d9716) | Feb 19, 2021 |
| Toshiba       | dynabook EX/35KWH           | [c52a95f06c](https://linux-hardware.org/?probe=c52a95f06c) | Feb 18, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [e8e114704d](https://linux-hardware.org/?probe=e8e114704d) | Feb 16, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [977e293baa](https://linux-hardware.org/?probe=977e293baa) | Feb 16, 2021 |
| Fujitsu       | FMVNFB40J                   | [8a3d6bcc89](https://linux-hardware.org/?probe=8a3d6bcc89) | Feb 15, 2021 |
| Fujitsu       | FMVA05002                   | [a758e3201d](https://linux-hardware.org/?probe=a758e3201d) | Feb 14, 2021 |
| Lenovo        | ThinkPad T61 7659D92        | [8d9f56460d](https://linux-hardware.org/?probe=8d9f56460d) | Feb 13, 2021 |
| Fujitsu       | FMVA56GBX                   | [bdc337bd04](https://linux-hardware.org/?probe=bdc337bd04) | Feb 13, 2021 |
| HP            | Pavilion g6                 | [a45a89930f](https://linux-hardware.org/?probe=a45a89930f) | Feb 13, 2021 |
| Fujitsu       | FMVA05002                   | [db95456803](https://linux-hardware.org/?probe=db95456803) | Feb 12, 2021 |
| Panasonic     | CF-SX3EDHCS                 | [3f7a156241](https://linux-hardware.org/?probe=3f7a156241) | Feb 11, 2021 |
| NEC Comput... | PC-VK19SGZDF                | [624a2eee47](https://linux-hardware.org/?probe=624a2eee47) | Feb 10, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [e507fdbcf5](https://linux-hardware.org/?probe=e507fdbcf5) | Feb 08, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| Unknown       | Unknown                     | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| NEC Comput... | PC-LL750SG6R                | [7c9081a73a](https://linux-hardware.org/?probe=7c9081a73a) | Jan 16, 2021 |
| Sony          | VGN-TZ73B                   | [735d00e026](https://linux-hardware.org/?probe=735d00e026) | Jan 13, 2021 |
| Sony          | VGN-TZ73B                   | [5df5433a1c](https://linux-hardware.org/?probe=5df5433a1c) | Jan 13, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [1d6691dffe](https://linux-hardware.org/?probe=1d6691dffe) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [d033697e79](https://linux-hardware.org/?probe=d033697e79) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [6173e9c6e9](https://linux-hardware.org/?probe=6173e9c6e9) | Jan 12, 2021 |
| UNITCOM       | W55xEU                      | [8c2793a502](https://linux-hardware.org/?probe=8c2793a502) | Jan 10, 2021 |
| UNITCOM       | W55xEU                      | [44b1f16e92](https://linux-hardware.org/?probe=44b1f16e92) | Jan 10, 2021 |
| HUAWEI        | MRC-WX0                     | [f650998a3d](https://linux-hardware.org/?probe=f650998a3d) | Jan 02, 2021 |
| Fujitsu       | FMVLCE50B                   | [03569af3cb](https://linux-hardware.org/?probe=03569af3cb) | Dec 31, 2020 |
| MSI           | Modern 14 B4MW              | [ec110ae347](https://linux-hardware.org/?probe=ec110ae347) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | [fbc4b89320](https://linux-hardware.org/?probe=fbc4b89320) | Dec 28, 2020 |
| Dell          | Inspiron 5490               | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | [84b2b1cba7](https://linux-hardware.org/?probe=84b2b1cba7) | Dec 26, 2020 |
| Thirdwave     | Diginnos PC                 | [4573bf9eeb](https://linux-hardware.org/?probe=4573bf9eeb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | [f4fe782260](https://linux-hardware.org/?probe=f4fe782260) | Dec 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [fcc97d1fdb](https://linux-hardware.org/?probe=fcc97d1fdb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | [21e571b40f](https://linux-hardware.org/?probe=21e571b40f) | Dec 25, 2020 |
| Dynabook      | P1-T6NP-EG                  | [9f6b496aaf](https://linux-hardware.org/?probe=9f6b496aaf) | Dec 25, 2020 |
| Fujitsu       | FMVNFA50                    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| Dell          | Inspiron 13-5378            | [d236c778e1](https://linux-hardware.org/?probe=d236c778e1) | Dec 21, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | [6a74695399](https://linux-hardware.org/?probe=6a74695399) | Dec 21, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| Dell          | Latitude E6230              | [c0f67befa0](https://linux-hardware.org/?probe=c0f67befa0) | Dec 18, 2020 |
| Dell          | Latitude E6230              | [9dd587de7a](https://linux-hardware.org/?probe=9dd587de7a) | Dec 18, 2020 |
| Dell          | Inspiron 13-5378            | [52b0b77ef7](https://linux-hardware.org/?probe=52b0b77ef7) | Dec 17, 2020 |
| NEC Comput... | PC-LL750SG6R                | [867c1b37b1](https://linux-hardware.org/?probe=867c1b37b1) | Dec 14, 2020 |
| Dell          | Inspiron 5370               | [9cf5fbfe60](https://linux-hardware.org/?probe=9cf5fbfe60) | Dec 09, 2020 |
| Toshiba       | dynabook Satellite B552/... | [575c848b52](https://linux-hardware.org/?probe=575c848b52) | Dec 07, 2020 |
| Toshiba       | dynabook Satellite B552/... | [58cf889053](https://linux-hardware.org/?probe=58cf889053) | Dec 07, 2020 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [1190e2392c](https://linux-hardware.org/?probe=1190e2392c) | Dec 02, 2020 |
| HP            | G7000                       | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | [e8e9e6770b](https://linux-hardware.org/?probe=e8e9e6770b) | Nov 29, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [5fd1f62125](https://linux-hardware.org/?probe=5fd1f62125) | Nov 21, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [593013a504](https://linux-hardware.org/?probe=593013a504) | Nov 20, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | [f34c508c5a](https://linux-hardware.org/?probe=f34c508c5a) | Nov 19, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [8d4468ec71](https://linux-hardware.org/?probe=8d4468ec71) | Nov 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | [f827ecc142](https://linux-hardware.org/?probe=f827ecc142) | Nov 16, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [adbf017e43](https://linux-hardware.org/?probe=adbf017e43) | Nov 13, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [3d8a88a6dd](https://linux-hardware.org/?probe=3d8a88a6dd) | Nov 08, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [d746af6cfd](https://linux-hardware.org/?probe=d746af6cfd) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | [32a742ccd5](https://linux-hardware.org/?probe=32a742ccd5) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | [497c61e3d1](https://linux-hardware.org/?probe=497c61e3d1) | Nov 07, 2020 |
| Panasonic     | CF-SX1GDHYS                 | [e8f3a6867e](https://linux-hardware.org/?probe=e8f3a6867e) | Nov 06, 2020 |
| Fujitsu       | FMVNF70W                    | [aedfc24e7e](https://linux-hardware.org/?probe=aedfc24e7e) | Nov 05, 2020 |
| Fujitsu       | FMVNF70W                    | [6039056d5c](https://linux-hardware.org/?probe=6039056d5c) | Nov 05, 2020 |
| Apple         | MacBookAir6,1               | [102aa409db](https://linux-hardware.org/?probe=102aa409db) | Nov 03, 2020 |
| MSI           | GS66 Stealth 10SF           | [c885924d12](https://linux-hardware.org/?probe=c885924d12) | Nov 02, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | [51449a174d](https://linux-hardware.org/?probe=51449a174d) | Nov 01, 2020 |
| HUAWEI        | MRC-WX0                     | [57608acdc4](https://linux-hardware.org/?probe=57608acdc4) | Oct 31, 2020 |
| Dell          | Vostro 2520                 | [196d3c6a8d](https://linux-hardware.org/?probe=196d3c6a8d) | Oct 30, 2020 |
| HP            | ENVY 15                     | [7e0fd3abbc](https://linux-hardware.org/?probe=7e0fd3abbc) | Oct 28, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [d4b681e245](https://linux-hardware.org/?probe=d4b681e245) | Oct 28, 2020 |
| Dell          | Vostro 2520                 | [b660b39908](https://linux-hardware.org/?probe=b660b39908) | Oct 25, 2020 |
| HP            | ProBook 4525s               | [157a86205d](https://linux-hardware.org/?probe=157a86205d) | Oct 24, 2020 |
| Unknown       | Unknown                     | [046bfed81f](https://linux-hardware.org/?probe=046bfed81f) | Oct 23, 2020 |
| Sony          | VPCEB49FJ                   | [a7b30aea08](https://linux-hardware.org/?probe=a7b30aea08) | Oct 21, 2020 |
| EPSON DIRE... | Endeavor NJ7000E            | [fd0992fec0](https://linux-hardware.org/?probe=fd0992fec0) | Oct 21, 2020 |
| MouseCompu... | NG-N-i5730                  | [7748ae5522](https://linux-hardware.org/?probe=7748ae5522) | Oct 19, 2020 |
| ASUSTek       | E200HA                      | [01f02e3868](https://linux-hardware.org/?probe=01f02e3868) | Oct 19, 2020 |
| Fujitsu       | FMVNF70W                    | [af9ba22806](https://linux-hardware.org/?probe=af9ba22806) | Oct 17, 2020 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [d7c4496b69](https://linux-hardware.org/?probe=d7c4496b69) | Oct 17, 2020 |
| HP            | ProBook 4525s               | [67efc6e80a](https://linux-hardware.org/?probe=67efc6e80a) | Oct 16, 2020 |
| UNITCOM       | W35_37ET                    | [13ddafa560](https://linux-hardware.org/?probe=13ddafa560) | Oct 16, 2020 |
| NEC Comput... | PC-LL750F26C                | [7b9dc13b94](https://linux-hardware.org/?probe=7b9dc13b94) | Oct 10, 2020 |
| NEC Comput... | PC-LL750F26C                | [eb148db6e7](https://linux-hardware.org/?probe=eb148db6e7) | Oct 09, 2020 |
| Sony          | VPCS129FJ                   | [ababc3caff](https://linux-hardware.org/?probe=ababc3caff) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [e4b06fc3af](https://linux-hardware.org/?probe=e4b06fc3af) | Oct 07, 2020 |
| HP            | ENVY 15                     | [096683ec03](https://linux-hardware.org/?probe=096683ec03) | Oct 06, 2020 |
| Fujitsu       | FMVWW11W                    | [e1a03b47aa](https://linux-hardware.org/?probe=e1a03b47aa) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [ebe29c2e8c](https://linux-hardware.org/?probe=ebe29c2e8c) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [4c90a49a16](https://linux-hardware.org/?probe=4c90a49a16) | Oct 05, 2020 |
| HP            | ProBook 6560b               | [4f60a7aca9](https://linux-hardware.org/?probe=4f60a7aca9) | Oct 05, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [117567ed8a](https://linux-hardware.org/?probe=117567ed8a) | Oct 02, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [c1729c7402](https://linux-hardware.org/?probe=c1729c7402) | Oct 02, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [51fb8f3cad](https://linux-hardware.org/?probe=51fb8f3cad) | Oct 02, 2020 |
| Lenovo        | M4450 20302                 | [0614174763](https://linux-hardware.org/?probe=0614174763) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [84913584dc](https://linux-hardware.org/?probe=84913584dc) | Sep 27, 2020 |
| Sharp         | PC-WE/WT Series             | [91e9663e3a](https://linux-hardware.org/?probe=91e9663e3a) | Sep 22, 2020 |
| HP            | ProBook 6550b               | [58aeb4c973](https://linux-hardware.org/?probe=58aeb4c973) | Sep 19, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [087fa4f531](https://linux-hardware.org/?probe=087fa4f531) | Sep 17, 2020 |
| HP            | ProBook 6570b               | [db08cfd499](https://linux-hardware.org/?probe=db08cfd499) | Sep 17, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | [d58a689a0b](https://linux-hardware.org/?probe=d58a689a0b) | Sep 13, 2020 |
| Sony          | VGN-NW50JB                  | [f5115778c1](https://linux-hardware.org/?probe=f5115778c1) | Sep 11, 2020 |
| HP            | EliteBook 820 G2            | [37e43e92e5](https://linux-hardware.org/?probe=37e43e92e5) | Sep 07, 2020 |
| HP            | ENVY Notebook               | [4da75a6d49](https://linux-hardware.org/?probe=4da75a6d49) | Sep 07, 2020 |
| Toshiba       | dynabook T554/56KW          | [03f3e6b816](https://linux-hardware.org/?probe=03f3e6b816) | Sep 04, 2020 |
| Samsung       | 940X3G/930X3G               | [d63abb12ee](https://linux-hardware.org/?probe=d63abb12ee) | Sep 03, 2020 |
| Toshiba       | dynabook SS MX/25AE         | [8d195475bf](https://linux-hardware.org/?probe=8d195475bf) | Sep 02, 2020 |
| Fujitsu       | FMVNF70W                    | [b782fe1564](https://linux-hardware.org/?probe=b782fe1564) | Aug 31, 2020 |
| Fujitsu       | FMVNF70W                    | [7451d691b9](https://linux-hardware.org/?probe=7451d691b9) | Aug 31, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | [efd7cd5751](https://linux-hardware.org/?probe=efd7cd5751) | Aug 29, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a2c94f7fdd](https://linux-hardware.org/?probe=a2c94f7fdd) | Aug 29, 2020 |
| Acer          | Aspire V3-571               | [8b32c068dc](https://linux-hardware.org/?probe=8b32c068dc) | Aug 24, 2020 |
| UNITCOM       | W35_37ET                    | [221322a11d](https://linux-hardware.org/?probe=221322a11d) | Aug 18, 2020 |
| Lenovo        | G500 20236                  | [28aacac404](https://linux-hardware.org/?probe=28aacac404) | Aug 16, 2020 |
| Fujitsu       | FMVNF70W                    | [ea2752e5b3](https://linux-hardware.org/?probe=ea2752e5b3) | Aug 14, 2020 |
| Sony          | SVE14A18FJW                 | [0868a90d93](https://linux-hardware.org/?probe=0868a90d93) | Aug 11, 2020 |
| Sony          | SVE14A18FJW                 | [dcd00b5fdc](https://linux-hardware.org/?probe=dcd00b5fdc) | Aug 11, 2020 |
| Lenovo        | ThinkPad T400 6475F99       | [83366b7e92](https://linux-hardware.org/?probe=83366b7e92) | Aug 10, 2020 |
| Dell          | XPS 15 9570                 | [7b17868903](https://linux-hardware.org/?probe=7b17868903) | Aug 07, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1ae67d880c](https://linux-hardware.org/?probe=1ae67d880c) | Aug 02, 2020 |
| Thirdwave     | Diginnos PC                 | [edad55d12d](https://linux-hardware.org/?probe=edad55d12d) | Aug 02, 2020 |
| Thirdwave     | Diginnos PC                 | [e1fd71a4b1](https://linux-hardware.org/?probe=e1fd71a4b1) | Aug 02, 2020 |
| Panasonic     | CF-N9LYDKDS                 | [8f3337d6ad](https://linux-hardware.org/?probe=8f3337d6ad) | Jul 31, 2020 |
| Fujitsu       | FMVU2400AD                  | [3353544fa3](https://linux-hardware.org/?probe=3353544fa3) | Jul 31, 2020 |
| HP            | ProBook 430 G3              | [7d3e5091ef](https://linux-hardware.org/?probe=7d3e5091ef) | Jul 29, 2020 |
| Sony          | VGN-S55B_S                  | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| Toshiba       | dynabook T554/56KW          | [a6edb6db3c](https://linux-hardware.org/?probe=a6edb6db3c) | Jul 23, 2020 |
| Lenovo        | ThinkPad E520 1143RD9       | [8947a114a1](https://linux-hardware.org/?probe=8947a114a1) | Jul 20, 2020 |
| NEC Comput... | PC-GN246W3A5                | [b95df976ea](https://linux-hardware.org/?probe=b95df976ea) | Jul 19, 2020 |
| Fujitsu       | FMVA705BW                   | [0985e32752](https://linux-hardware.org/?probe=0985e32752) | Jul 18, 2020 |
| Toshiba       | dynabook EX/66MRD           | [e3a6da6bcc](https://linux-hardware.org/?probe=e3a6da6bcc) | Jul 16, 2020 |
| ASUSTek       | TUF Gaming FA506IU_TUF50... | [51c975b932](https://linux-hardware.org/?probe=51c975b932) | Jul 12, 2020 |
| NEC Comput... | PC-VJ19SGHDWLTF             | [b99df50393](https://linux-hardware.org/?probe=b99df50393) | Jul 12, 2020 |
| Acer          | Aspire 3810T                | [bc217e9435](https://linux-hardware.org/?probe=bc217e9435) | Jul 12, 2020 |
| Acer          | Aspire 3810T                | [9b2e49ccd8](https://linux-hardware.org/?probe=9b2e49ccd8) | Jul 12, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [7cf0424b3b](https://linux-hardware.org/?probe=7cf0424b3b) | Jul 10, 2020 |
| Lenovo        | ThinkPad T450 20BUS0G500    | [439f2ff831](https://linux-hardware.org/?probe=439f2ff831) | Jul 07, 2020 |
| Lenovo        | ThinkPad T450 20BUS0G500    | [770f2f3b0b](https://linux-hardware.org/?probe=770f2f3b0b) | Jul 07, 2020 |
| HP            | ProBook 470 G1              | [7e2ba71d87](https://linux-hardware.org/?probe=7e2ba71d87) | Jul 06, 2020 |
| Fujitsu       | FMVNF70W                    | [5b28cc735f](https://linux-hardware.org/?probe=5b28cc735f) | Jul 02, 2020 |
| Fujitsu       | FMVNF70W                    | [28307d3d6c](https://linux-hardware.org/?probe=28307d3d6c) | Jul 02, 2020 |
| ASUSTek       | K53SK                       | [2003676ccf](https://linux-hardware.org/?probe=2003676ccf) | Jul 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [6457099b06](https://linux-hardware.org/?probe=6457099b06) | Jun 27, 2020 |
| Apple         | MacBookPro11,1              | [8754b0ae46](https://linux-hardware.org/?probe=8754b0ae46) | Jun 27, 2020 |
| MSI           | GS63 7RE                    | [31dfc658d7](https://linux-hardware.org/?probe=31dfc658d7) | Jun 26, 2020 |
| Apple         | MacBookPro11,1              | [2a32b846c5](https://linux-hardware.org/?probe=2a32b846c5) | Jun 24, 2020 |
| Lenovo        | ThinkPad T500 208843J       | [a12d551827](https://linux-hardware.org/?probe=a12d551827) | Jun 21, 2020 |
| Sony          | VGN-S55B_S                  | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| Lenovo        | IdeaPad U300s 1080          | [dca0b5baa2](https://linux-hardware.org/?probe=dca0b5baa2) | Jun 21, 2020 |
| Lenovo        | IdeaPad U300s 1080          | [198cec29f3](https://linux-hardware.org/?probe=198cec29f3) | Jun 21, 2020 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [acbdac722c](https://linux-hardware.org/?probe=acbdac722c) | Jun 19, 2020 |
| Dell          | Inspiron 15-3565            | [696dea86af](https://linux-hardware.org/?probe=696dea86af) | Jun 15, 2020 |
| Apple         | MacBookPro16,1              | [8b4c1f4506](https://linux-hardware.org/?probe=8b4c1f4506) | Jun 15, 2020 |
| Apple         | MacBookPro9,2               | [5cedae8b83](https://linux-hardware.org/?probe=5cedae8b83) | Jun 12, 2020 |
| Gateway       | NE56R                       | [45934f9b2c](https://linux-hardware.org/?probe=45934f9b2c) | Jun 12, 2020 |
| ASUSTek       | K53SK                       | [ec6ff61a8c](https://linux-hardware.org/?probe=ec6ff61a8c) | Jun 12, 2020 |
| Fujitsu       | FMVNFG60TC                  | [b6bad717fa](https://linux-hardware.org/?probe=b6bad717fa) | Jun 10, 2020 |
| Fujitsu       | FMVNFG60TC                  | [1b3a040711](https://linux-hardware.org/?probe=1b3a040711) | Jun 10, 2020 |
| Fujitsu       | FMVA77JW                    | [ce5b1dbbcb](https://linux-hardware.org/?probe=ce5b1dbbcb) | Jun 10, 2020 |
| Dell          | Inspiron 15-3565            | [91540b6b55](https://linux-hardware.org/?probe=91540b6b55) | Jun 10, 2020 |
| Lenovo        | ThinkPad X230 232425J       | [2ebe6149b7](https://linux-hardware.org/?probe=2ebe6149b7) | Jun 06, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [c4d2595650](https://linux-hardware.org/?probe=c4d2595650) | Jun 04, 2020 |
| HUAWEI        | HN-WX9X                     | [7c56c01092](https://linux-hardware.org/?probe=7c56c01092) | May 30, 2020 |
| Dell          | Inspiron 7590               | [18895b4469](https://linux-hardware.org/?probe=18895b4469) | May 27, 2020 |
| Panasonic     | CF-195W1ACS                 | [5ee3c1d71e](https://linux-hardware.org/?probe=5ee3c1d71e) | May 27, 2020 |
| Dell          | Inspiron 7590               | [e219e1df90](https://linux-hardware.org/?probe=e219e1df90) | May 25, 2020 |
| Dell          | Inspiron 7590               | [46683fd696](https://linux-hardware.org/?probe=46683fd696) | May 25, 2020 |
| Dell          | Inspiron 7590               | [208561b660](https://linux-hardware.org/?probe=208561b660) | May 25, 2020 |
| Lenovo        | Z51-70 80K6                 | [7b25fce04c](https://linux-hardware.org/?probe=7b25fce04c) | May 24, 2020 |
| Acer          | Aspire 8940G                | [186821b722](https://linux-hardware.org/?probe=186821b722) | May 23, 2020 |
| Unknown       | Unknown                     | [d163d86dcb](https://linux-hardware.org/?probe=d163d86dcb) | May 19, 2020 |
| Toshiba       | dynabook T45/VRS            | [ddae801625](https://linux-hardware.org/?probe=ddae801625) | May 18, 2020 |
| Toshiba       | dynabook T45/VRS            | [efafbf544b](https://linux-hardware.org/?probe=efafbf544b) | May 18, 2020 |
| Panasonic     | CFSX4-1L                    | [54b56291de](https://linux-hardware.org/?probe=54b56291de) | May 18, 2020 |
| HP            | ProBook 6560b               | [72808d19a6](https://linux-hardware.org/?probe=72808d19a6) | May 15, 2020 |
| HP            | ProBook 6560b               | [f88ec1bc1d](https://linux-hardware.org/?probe=f88ec1bc1d) | May 15, 2020 |
| Lenovo        | G570 4334                   | [54ff12939f](https://linux-hardware.org/?probe=54ff12939f) | May 11, 2020 |
| Toshiba       | dynabook CX/45J             | [98a1bae5fd](https://linux-hardware.org/?probe=98a1bae5fd) | May 06, 2020 |
| HP            | Pavilion dv4                | [ea93ee2d08](https://linux-hardware.org/?probe=ea93ee2d08) | May 06, 2020 |
| Apple         | MacBookPro9,2               | [593c0984df](https://linux-hardware.org/?probe=593c0984df) | May 05, 2020 |
| Apple         | MacBookPro9,2               | [02d47ceb31](https://linux-hardware.org/?probe=02d47ceb31) | May 05, 2020 |
| Gateway       | NE56R                       | [6d4a0dd1b6](https://linux-hardware.org/?probe=6d4a0dd1b6) | May 04, 2020 |
| Gateway       | NE56R                       | [2910284c56](https://linux-hardware.org/?probe=2910284c56) | May 03, 2020 |
| Notebook      | N15_17RF                    | [3ec814dabd](https://linux-hardware.org/?probe=3ec814dabd) | May 01, 2020 |
| Toshiba       | dynabook Satellite B551/... | [b0ec3775c4](https://linux-hardware.org/?probe=b0ec3775c4) | Apr 29, 2020 |
| Lenovo        | ThinkPad Edge E130 3358C... | [2bc6ee441e](https://linux-hardware.org/?probe=2bc6ee441e) | Apr 29, 2020 |
| HP            | EliteBook 2570p             | [8481b529ee](https://linux-hardware.org/?probe=8481b529ee) | Apr 28, 2020 |
| HP            | Pavilion dv7                | [12f72e240a](https://linux-hardware.org/?probe=12f72e240a) | Apr 28, 2020 |
| Toshiba       | dynabook BX/571KW           | [9ba95d923c](https://linux-hardware.org/?probe=9ba95d923c) | Apr 22, 2020 |
| ASUSTek       | X45U                        | [0ce069357c](https://linux-hardware.org/?probe=0ce069357c) | Apr 18, 2020 |
| Acer          | Aspire A515-43              | [4eda844896](https://linux-hardware.org/?probe=4eda844896) | Apr 15, 2020 |
| Toshiba       | dynabook BX/571KW           | [b8dba9c83d](https://linux-hardware.org/?probe=b8dba9c83d) | Apr 13, 2020 |
| Intel         | CAPELL VALLEY CRB           | [2d21b4d154](https://linux-hardware.org/?probe=2d21b4d154) | Apr 12, 2020 |
| Dell          | Inspiron 3541               | [a1569c7977](https://linux-hardware.org/?probe=a1569c7977) | Apr 09, 2020 |
| Dell          | Inspiron 3541               | [6c900e8ddf](https://linux-hardware.org/?probe=6c900e8ddf) | Apr 09, 2020 |
| NEC Comput... | PC-LL550KG6GN               | [bc1a12a76f](https://linux-hardware.org/?probe=bc1a12a76f) | Mar 26, 2020 |
| Fujitsu       | FARQ06012Z                  | [6d19311f7e](https://linux-hardware.org/?probe=6d19311f7e) | Mar 23, 2020 |
| Lenovo        | ThinkPad T500 208843J       | [f221fcd053](https://linux-hardware.org/?probe=f221fcd053) | Mar 19, 2020 |
| Dell          | Inspiron 1545               | [cd22cce33d](https://linux-hardware.org/?probe=cd22cce33d) | Mar 12, 2020 |
| Dell          | Inspiron 1545               | [1cd8601a1e](https://linux-hardware.org/?probe=1cd8601a1e) | Mar 12, 2020 |
| HP            | ProBook 4320s               | [92478c20d5](https://linux-hardware.org/?probe=92478c20d5) | Mar 11, 2020 |
| Acer          | Aspire V3-571               | [82955eaaa3](https://linux-hardware.org/?probe=82955eaaa3) | Mar 10, 2020 |
| HP            | ProBook 4320s               | [96b40c5d0e](https://linux-hardware.org/?probe=96b40c5d0e) | Mar 05, 2020 |
| Acer          | Aspire V3-571               | [218d6c9bea](https://linux-hardware.org/?probe=218d6c9bea) | Mar 04, 2020 |
| HP            | Pavilion dv4                | [1e248b227a](https://linux-hardware.org/?probe=1e248b227a) | Feb 24, 2020 |
| Dell          | Inspiron 7380               | [2f37de4f3d](https://linux-hardware.org/?probe=2f37de4f3d) | Feb 23, 2020 |
| Dell          | Inspiron 7380               | [82f783a4d6](https://linux-hardware.org/?probe=82f783a4d6) | Feb 23, 2020 |
| ASUSTek       | 1005HA                      | [f668a6c2b8](https://linux-hardware.org/?probe=f668a6c2b8) | Feb 23, 2020 |
| Dell          | Inspiron 7380               | [a82beef9a1](https://linux-hardware.org/?probe=a82beef9a1) | Feb 23, 2020 |
| ASUSTek       | UX301LAA                    | [e994e96768](https://linux-hardware.org/?probe=e994e96768) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [4babc87322](https://linux-hardware.org/?probe=4babc87322) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | [da5b70c7c6](https://linux-hardware.org/?probe=da5b70c7c6) | Feb 21, 2020 |
| HP            | Pavilion dv4                | [45555d85c3](https://linux-hardware.org/?probe=45555d85c3) | Feb 20, 2020 |
| Toshiba       | dynabook EX/55LWH           | [8da363dbd2](https://linux-hardware.org/?probe=8da363dbd2) | Feb 20, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [d19eb25691](https://linux-hardware.org/?probe=d19eb25691) | Feb 15, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [87e4d3dd9a](https://linux-hardware.org/?probe=87e4d3dd9a) | Feb 14, 2020 |
| Sharp         | PC-WE/WT Series             | [6d4ad9101d](https://linux-hardware.org/?probe=6d4ad9101d) | Feb 11, 2020 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1ca6b6f436](https://linux-hardware.org/?probe=1ca6b6f436) | Jan 20, 2020 |
| Dell          | Inspiron 5485               | [fe8b986757](https://linux-hardware.org/?probe=fe8b986757) | Jan 19, 2020 |
| Dell          | XPS 13 7390                 | [b7f175312b](https://linux-hardware.org/?probe=b7f175312b) | Jan 15, 2020 |
| Dell          | XPS 13 7390                 | [430e5271de](https://linux-hardware.org/?probe=430e5271de) | Jan 15, 2020 |
| Toshiba       | dynabook CX/47H             | [f9cf94b130](https://linux-hardware.org/?probe=f9cf94b130) | Jan 14, 2020 |
| Toshiba       | dynabook CX/47H             | [15ce1a1178](https://linux-hardware.org/?probe=15ce1a1178) | Jan 14, 2020 |
| MSI           | GF72 8RE                    | [11ba6c28b8](https://linux-hardware.org/?probe=11ba6c28b8) | Jan 13, 2020 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [1a78f67963](https://linux-hardware.org/?probe=1a78f67963) | Jan 05, 2020 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [d8e43b34cc](https://linux-hardware.org/?probe=d8e43b34cc) | Jan 01, 2020 |
| Sony          | SVP1121A1J                  | [588b4f5ea9](https://linux-hardware.org/?probe=588b4f5ea9) | Dec 31, 2019 |
| Fujitsu       | FMVNFB40J                   | [0bfe715962](https://linux-hardware.org/?probe=0bfe715962) | Dec 30, 2019 |
| Dell          | Inspiron MM061              | [ab555162c8](https://linux-hardware.org/?probe=ab555162c8) | Dec 22, 2019 |
| NEC Comput... | PC-VY25AACZ9                | [67db0cd3e1](https://linux-hardware.org/?probe=67db0cd3e1) | Dec 12, 2019 |
| HP            | ProBook 6570b               | [567e5e5444](https://linux-hardware.org/?probe=567e5e5444) | Dec 06, 2019 |
| HP            | ProBook 6570b               | [12e166c17a](https://linux-hardware.org/?probe=12e166c17a) | Dec 06, 2019 |
| HP            | ProBook 4310s               | [d67761b5c2](https://linux-hardware.org/?probe=d67761b5c2) | Dec 04, 2019 |
| Novastar      | KL55                        | [277007d50c](https://linux-hardware.org/?probe=277007d50c) | Dec 03, 2019 |
| Novastar      | KL55                        | [d390f7576c](https://linux-hardware.org/?probe=d390f7576c) | Nov 20, 2019 |
| Novastar      | KL55                        | [9d09caf5c5](https://linux-hardware.org/?probe=9d09caf5c5) | Nov 19, 2019 |
| Novastar      | KL55                        | [3a8b42421b](https://linux-hardware.org/?probe=3a8b42421b) | Nov 18, 2019 |
| Novastar      | KL55                        | [e293c143c1](https://linux-hardware.org/?probe=e293c143c1) | Nov 18, 2019 |
| ASUSTek       | E203NA                      | [103ca8741c](https://linux-hardware.org/?probe=103ca8741c) | Nov 03, 2019 |
| HP            | ProBook 4530s               | [d6f9cecdc5](https://linux-hardware.org/?probe=d6f9cecdc5) | Nov 03, 2019 |
| Clevo         | W240HU/W250HUQ              | [c38e15b8e9](https://linux-hardware.org/?probe=c38e15b8e9) | Oct 15, 2019 |
| ASUSTek       | E203NA                      | [1e18143757](https://linux-hardware.org/?probe=1e18143757) | Oct 07, 2019 |
| ASUSTek       | X200MA                      | [d41d8e1f91](https://linux-hardware.org/?probe=d41d8e1f91) | Oct 07, 2019 |
| HASEE Comp... | P65xRP                      | [343291949a](https://linux-hardware.org/?probe=343291949a) | Oct 03, 2019 |
| Panasonic     | CF-J10YYBHR                 | [e00043a374](https://linux-hardware.org/?probe=e00043a374) | Sep 27, 2019 |
| Dell          | Inspiron 15-3565            | [6ebeac4bcd](https://linux-hardware.org/?probe=6ebeac4bcd) | Sep 27, 2019 |
| Dell          | Inspiron 15-3565            | [55ae5ff063](https://linux-hardware.org/?probe=55ae5ff063) | Sep 25, 2019 |
| Dell          | Inspiron 15-3565            | [90d49c8abd](https://linux-hardware.org/?probe=90d49c8abd) | Sep 25, 2019 |
| Lenovo        | G570 4334                   | [eefedc7e75](https://linux-hardware.org/?probe=eefedc7e75) | Sep 06, 2019 |
| Lenovo        | G570 4334                   | [66750ab32f](https://linux-hardware.org/?probe=66750ab32f) | Sep 04, 2019 |
| Lenovo        | G570 4334                   | [4a4a5fe410](https://linux-hardware.org/?probe=4a4a5fe410) | Sep 04, 2019 |
| ASUSTek       | X200MA                      | [aec3d01ee9](https://linux-hardware.org/?probe=aec3d01ee9) | Aug 28, 2019 |
| ASUSTek       | E203NA                      | [187729d926](https://linux-hardware.org/?probe=187729d926) | Aug 27, 2019 |
| Panasonic     | CF-J10YYBHR                 | [0005e1a411](https://linux-hardware.org/?probe=0005e1a411) | Aug 21, 2019 |
| ASUSTek       | E203NA                      | [eb4b2d2e3e](https://linux-hardware.org/?probe=eb4b2d2e3e) | Aug 15, 2019 |
| Dell          | Latitude E6500              | [cb9f268650](https://linux-hardware.org/?probe=cb9f268650) | Aug 12, 2019 |
| Fujitsu       | FMVNC6BE3                   | [24f8a2b045](https://linux-hardware.org/?probe=24f8a2b045) | Aug 10, 2019 |
| Fujitsu       | FMVNC6BE3                   | [b2a7c69d92](https://linux-hardware.org/?probe=b2a7c69d92) | Jul 25, 2019 |
| Lenovo        | ThinkPad X121e 30456FJ      | [974cf0c5c6](https://linux-hardware.org/?probe=974cf0c5c6) | Jul 24, 2019 |
| Dell          | Inspiron 15-3552            | [ce847df44a](https://linux-hardware.org/?probe=ce847df44a) | Jul 21, 2019 |
| HP            | Compaq 6720s                | [48ee31d6e9](https://linux-hardware.org/?probe=48ee31d6e9) | Jul 16, 2019 |
| Dell          | Latitude E6320              | [a45c07429f](https://linux-hardware.org/?probe=a45c07429f) | Jun 24, 2019 |
| Toshiba       | dynabook Satellite B552/... | [5d0ae356dd](https://linux-hardware.org/?probe=5d0ae356dd) | Jun 17, 2019 |
| SLIMBOOK      | PRO                         | [741aadd99e](https://linux-hardware.org/?probe=741aadd99e) | Jun 12, 2019 |
| Alienware     | 17 R5                       | [8b270d4228](https://linux-hardware.org/?probe=8b270d4228) | May 30, 2019 |
| Lenovo        | ThinkPad Edge E530 32599... | [23f78cf853](https://linux-hardware.org/?probe=23f78cf853) | May 28, 2019 |
| Acer          | Swift SF314-54              | [e682a05a1f](https://linux-hardware.org/?probe=e682a05a1f) | May 27, 2019 |
| Acer          | Swift SF314-54              | [167c038742](https://linux-hardware.org/?probe=167c038742) | May 27, 2019 |
| Fujitsu       | FMVWW11W                    | [2462f0f0bb](https://linux-hardware.org/?probe=2462f0f0bb) | May 25, 2019 |
| Toshiba       | Satellite A135              | [bc24647b76](https://linux-hardware.org/?probe=bc24647b76) | May 18, 2019 |
| Toshiba       | Satellite A135              | [fa5218ef36](https://linux-hardware.org/?probe=fa5218ef36) | May 16, 2019 |
| Apple         | MacBookPro9,2               | [e4d60349c2](https://linux-hardware.org/?probe=e4d60349c2) | May 01, 2019 |
| Lenovo        | 41872PU                     | [61cd8222cf](https://linux-hardware.org/?probe=61cd8222cf) | Apr 15, 2019 |
| Apple         | MacBookPro9,2               | [0c238b6751](https://linux-hardware.org/?probe=0c238b6751) | Apr 07, 2019 |
| Dell          | Inspiron 1210               | [7d4473a4a5](https://linux-hardware.org/?probe=7d4473a4a5) | Apr 07, 2019 |
| Dell          | G7 7588                     | [d38fee8e21](https://linux-hardware.org/?probe=d38fee8e21) | Mar 29, 2019 |
| HP            | Mini 5103                   | [266d78e723](https://linux-hardware.org/?probe=266d78e723) | Mar 25, 2019 |
| HP            | Laptop 15-db0xxx            | [c5c58d8655](https://linux-hardware.org/?probe=c5c58d8655) | Mar 23, 2019 |
| HP            | Laptop 15-db0xxx            | [c4d37bac1a](https://linux-hardware.org/?probe=c4d37bac1a) | Mar 17, 2019 |
| HP            | Laptop 15-db0xxx            | [3159028860](https://linux-hardware.org/?probe=3159028860) | Mar 17, 2019 |
| Teclast       | F6 Pro                      | [afaad4db96](https://linux-hardware.org/?probe=afaad4db96) | Mar 15, 2019 |
| Lenovo        | ThinkPad SL410 2842CTO      | [f577d3875e](https://linux-hardware.org/?probe=f577d3875e) | Mar 04, 2019 |
| NEC Comput... | PC-LL750RG                  | [f3208d8466](https://linux-hardware.org/?probe=f3208d8466) | Mar 03, 2019 |
| Dell          | Latitude E6320              | [04f301dc20](https://linux-hardware.org/?probe=04f301dc20) | Feb 27, 2019 |
| Panasonic     | CF-S9JWECPS                 | [fd3dd464f1](https://linux-hardware.org/?probe=fd3dd464f1) | Feb 11, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | [deac2364d1](https://linux-hardware.org/?probe=deac2364d1) | Jan 30, 2019 |
| Fujitsu       | FMVU93B3BZ                  | [974550aea3](https://linux-hardware.org/?probe=974550aea3) | Jan 30, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | [1629601591](https://linux-hardware.org/?probe=1629601591) | Jan 30, 2019 |
| Acer          | TravelMate 5730             | [3f204613cc](https://linux-hardware.org/?probe=3f204613cc) | Jan 13, 2019 |
| Fujitsu       | FMVNE4N1E                   | [8e2c99692b](https://linux-hardware.org/?probe=8e2c99692b) | Dec 29, 2018 |
| HP            | Notebook                    | [b73435f113](https://linux-hardware.org/?probe=b73435f113) | Dec 24, 2018 |
| HP            | Notebook                    | [5f943855ce](https://linux-hardware.org/?probe=5f943855ce) | Dec 24, 2018 |
| NEC Comput... | PC-LL550LG1K                | [004a3c19de](https://linux-hardware.org/?probe=004a3c19de) | Dec 09, 2018 |
| NEC Comput... | PC-LL550LG1K                | [80d5cca3f0](https://linux-hardware.org/?probe=80d5cca3f0) | Dec 09, 2018 |
| Sony          | VGN-FT31B                   | [7f0bb0cc92](https://linux-hardware.org/?probe=7f0bb0cc92) | Dec 06, 2018 |
| Sony          | VGN-N50HB                   | [8938dd9a9e](https://linux-hardware.org/?probe=8938dd9a9e) | Nov 11, 2018 |
| ASUSTek       | X551MA                      | [5806ab1f9f](https://linux-hardware.org/?probe=5806ab1f9f) | Oct 24, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Japan/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 91        | 12.36%  |
| Ubuntu 18.04                 | 47        | 6.39%   |
| Ubuntu 22.04                 | 39        | 5.3%    |
| OpenMandriva 23.03           | 31        | 4.21%   |
| OpenMandriva 4.3             | 29        | 3.94%   |
| OpenMandriva 4.90            | 26        | 3.53%   |
| OpenMandriva 4.2             | 20        | 2.72%   |
| Arch Rolling                 | 18        | 2.45%   |
| Debian 11                    | 15        | 2.04%   |
| Zorin 16                     | 14        | 1.9%    |
| OpenMandriva 23.01           | 14        | 1.9%    |
| OpenMandriva 23.08           | 12        | 1.63%   |
| Manjaro                      | 12        | 1.63%   |
| BlackPanther 18.1            | 11        | 1.49%   |
| Arch                         | 11        | 1.49%   |
| OpenMandriva 5.0             | 10        | 1.36%   |
| Zorin 15                     | 8         | 1.09%   |
| Xubuntu 20.04                | 8         | 1.09%   |
| Fedora 37                    | 8         | 1.09%   |
| Xubuntu 18.04                | 7         | 0.95%   |
| Ubuntu 23.04                 | 7         | 0.95%   |
| Ubuntu 21.04                 | 7         | 0.95%   |
| Pop!_OS 22.04                | 7         | 0.95%   |
| Pop!_OS 20.10                | 7         | 0.95%   |
| Linux Mint 19.3              | 7         | 0.95%   |
| Fedora 39                    | 7         | 0.95%   |
| Fedora 38                    | 7         | 0.95%   |
| Fedora 35                    | 7         | 0.95%   |
| Xubuntu 22.04                | 6         | 0.82%   |
| Ubuntu 19.10                 | 5         | 0.68%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 0.68%   |
| OpenMandriva 4.50            | 5         | 0.68%   |
| Linux Mint 21.2              | 5         | 0.68%   |
| Linux Mint 21.1              | 5         | 0.68%   |
| Linux Mint 20.2              | 5         | 0.68%   |
| Fedora 36                    | 5         | 0.68%   |
| Fedora 32                    | 5         | 0.68%   |
| Zorin 17                     | 4         | 0.54%   |
| Ubuntu Unity 16.04           | 4         | 0.54%   |
| Ubuntu 21.10                 | 4         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 215       | 30.5%   |
| OpenMandriva  | 149       | 21.13%  |
| Fedora        | 43        | 6.1%    |
| Linux Mint    | 31        | 4.4%    |
| Arch          | 29        | 4.11%   |
| Debian        | 27        | 3.83%   |
| Zorin         | 26        | 3.69%   |
| Pop!_OS       | 21        | 2.98%   |
| Xubuntu       | 20        | 2.84%   |
| Manjaro       | 18        | 2.55%   |
| BlackPanther  | 11        | 1.56%   |
| Kali          | 10        | 1.42%   |
| Kubuntu       | 8         | 1.13%   |
| Ubuntu Unity  | 7         | 0.99%   |
| openSUSE      | 7         | 0.99%   |
| Gentoo        | 7         | 0.99%   |
| Lubuntu       | 6         | 0.85%   |
| SteamOS       | 5         | 0.71%   |
| Slackware     | 5         | 0.71%   |
| NixOS         | 5         | 0.71%   |
| LMDE          | 4         | 0.57%   |
| KDE neon      | 4         | 0.57%   |
| ArcoLinux     | 4         | 0.57%   |
| Ubuntu MATE   | 3         | 0.43%   |
| Ubuntu Budgie | 3         | 0.43%   |
| ROSA          | 3         | 0.43%   |
| Peppermint    | 3         | 0.43%   |
| Guix          | 3         | 0.43%   |
| Deepin        | 3         | 0.43%   |
| antiX         | 3         | 0.43%   |
| RHEL          | 2         | 0.28%   |
| MX            | 2         | 0.28%   |
| Garuda Linux  | 2         | 0.28%   |
| Endless       | 2         | 0.28%   |
| Elementary    | 2         | 0.28%   |
| CentOS        | 2         | 0.28%   |
| SystemRescue  | 1         | 0.14%   |
| Sparky        | 1         | 0.14%   |
| SolydXK       | 1         | 0.14%   |
| Solus         | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 6.2.6-desktop-1omv2390       | 30        | 3.7%    |
| 5.16.7-desktop-1omv4003      | 27        | 3.33%   |
| 5.10.14-desktop-1omv4002     | 19        | 2.34%   |
| 6.1.1-desktop-1omv2290       | 15        | 1.85%   |
| 6.0.2-desktop-1omv4090       | 14        | 1.73%   |
| 5.4.0-42-generic             | 13        | 1.6%    |
| 6.6.2-desktop-1omv2390       | 12        | 1.48%   |
| 6.4.11-desktop-1omv2390      | 11        | 1.36%   |
| 5.4.0-52-generic             | 11        | 1.36%   |
| 5.4.0-58-generic             | 8         | 0.99%   |
| 4.18.16-desktop-1bP          | 8         | 0.99%   |
| 5.4.0-48-generic             | 7         | 0.86%   |
| 5.15.0-58-generic            | 6         | 0.74%   |
| 5.0.0-37-generic             | 6         | 0.74%   |
| 5.8.0-7642-generic           | 5         | 0.62%   |
| 5.8.0-50-generic             | 5         | 0.62%   |
| 5.8.0-48-generic             | 5         | 0.62%   |
| 5.8.0-43-generic             | 5         | 0.62%   |
| 5.3.0-40-generic             | 5         | 0.62%   |
| 5.19.1-desktop-1omv4090      | 5         | 0.62%   |
| 5.13.0-27-generic            | 5         | 0.62%   |
| 6.2.0-33-generic             | 4         | 0.49%   |
| 5.6.14-desktop-2bP           | 4         | 0.49%   |
| 5.4.0-40-generic             | 4         | 0.49%   |
| 5.18.12-desktop-3omv4090     | 4         | 0.49%   |
| 5.16.13-desktop-1omv4003     | 4         | 0.49%   |
| 5.15.0-56-generic            | 4         | 0.49%   |
| 5.12.4-desktop-1omv4050      | 4         | 0.49%   |
| 5.11.0-37-generic            | 4         | 0.49%   |
| 5.11.0-27-generic            | 4         | 0.49%   |
| 5.10.0-21-amd64              | 4         | 0.49%   |
| 4.18.0-25-generic            | 4         | 0.49%   |
| 6.5.0-28-generic             | 3         | 0.37%   |
| 6.4.12-arch1-1               | 3         | 0.37%   |
| 6.4.0-desktop-0.rc3.1omv2390 | 3         | 0.37%   |
| 6.2.0-26-generic             | 3         | 0.37%   |
| 6.0.12-76060006-generic      | 3         | 0.37%   |
| 5.8.0-45-generic             | 3         | 0.37%   |
| 5.4.0-65-generic             | 3         | 0.37%   |
| 5.4.0-51-generic             | 3         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 95        | 12.29%  |
| 5.15.0  | 43        | 5.56%   |
| 4.15.0  | 36        | 4.66%   |
| 5.8.0   | 34        | 4.4%    |
| 6.2.6   | 31        | 4.01%   |
| 5.16.7  | 28        | 3.62%   |
| 5.13.0  | 27        | 3.49%   |
| 5.11.0  | 27        | 3.49%   |
| 5.10.0  | 22        | 2.85%   |
| 6.5.0   | 20        | 2.59%   |
| 5.3.0   | 20        | 2.59%   |
| 5.10.14 | 19        | 2.46%   |
| 6.2.0   | 18        | 2.33%   |
| 5.19.0  | 18        | 2.33%   |
| 5.0.0   | 17        | 2.2%    |
| 6.1.1   | 16        | 2.07%   |
| 6.0.2   | 14        | 1.81%   |
| 6.6.2   | 12        | 1.55%   |
| 6.4.11  | 12        | 1.55%   |
| 6.1.0   | 10        | 1.29%   |
| 4.18.0  | 9         | 1.16%   |
| 4.18.16 | 8         | 1.03%   |
| 5.19.1  | 6         | 0.78%   |
| 4.4.0   | 5         | 0.65%   |
| 6.4.12  | 4         | 0.52%   |
| 6.4.0   | 4         | 0.52%   |
| 6.0.12  | 4         | 0.52%   |
| 6.0.0   | 4         | 0.52%   |
| 5.6.14  | 4         | 0.52%   |
| 5.19.11 | 4         | 0.52%   |
| 5.18.12 | 4         | 0.52%   |
| 5.16.13 | 4         | 0.52%   |
| 5.16.11 | 4         | 0.52%   |
| 5.12.4  | 4         | 0.52%   |
| 4.19.0  | 4         | 0.52%   |
| 6.6.8   | 3         | 0.39%   |
| 6.5.5   | 3         | 0.39%   |
| 6.3.5   | 3         | 0.39%   |
| 6.3.0   | 3         | 0.39%   |
| 5.8.13  | 3         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 102       | 13.37%  |
| 6.2     | 55        | 7.21%   |
| 5.15    | 52        | 6.82%   |
| 5.10    | 50        | 6.55%   |
| 5.8     | 41        | 5.37%   |
| 5.16    | 40        | 5.24%   |
| 6.1     | 38        | 4.98%   |
| 4.15    | 36        | 4.72%   |
| 5.19    | 35        | 4.59%   |
| 5.13    | 34        | 4.46%   |
| 5.11    | 30        | 3.93%   |
| 6.5     | 29        | 3.8%    |
| 6.0     | 26        | 3.41%   |
| 6.4     | 24        | 3.15%   |
| 6.6     | 21        | 2.75%   |
| 5.3     | 21        | 2.75%   |
| 5.0     | 18        | 2.36%   |
| 5.18    | 17        | 2.23%   |
| 4.18    | 17        | 2.23%   |
| 6.3     | 12        | 1.57%   |
| 5.14    | 11        | 1.44%   |
| 5.6     | 8         | 1.05%   |
| 5.12    | 8         | 1.05%   |
| 6.8     | 6         | 0.79%   |
| 6.7     | 6         | 0.79%   |
| 5.17    | 5         | 0.66%   |
| 4.4     | 5         | 0.66%   |
| 4.19    | 5         | 0.66%   |
| 5.9     | 4         | 0.52%   |
| 4.9     | 4         | 0.52%   |
| 5.7     | 2         | 0.26%   |
| 3.10    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 655       | 95.76%  |
| i686   | 29        | 4.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 283       | 40.49%  |
| KDE5          | 189       | 27.04%  |
| Unknown       | 62        | 8.87%   |
| XFCE          | 59        | 8.44%   |
| X-Cinnamon    | 23        | 3.29%   |
| LXQt          | 13        | 1.86%   |
| MATE          | 12        | 1.72%   |
| Unity         | 7         | 1%      |
| sway          | 6         | 0.86%   |
| LXDE          | 6         | 0.86%   |
| KDE           | 6         | 0.86%   |
| Cinnamon      | 6         | 0.86%   |
| i3            | 5         | 0.72%   |
| Budgie        | 4         | 0.57%   |
| Deepin        | 3         | 0.43%   |
| Pantheon      | 2         | 0.29%   |
| icewm         | 2         | 0.29%   |
| Hyprland      | 2         | 0.29%   |
| awesome       | 2         | 0.29%   |
| XSession      | 1         | 0.14%   |
| xmonad        | 1         | 0.14%   |
| KDE6          | 1         | 0.14%   |
| KDE4          | 1         | 0.14%   |
| JWM           | 1         | 0.14%   |
| GNOME Classic | 1         | 0.14%   |
| dwm           | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 500       | 71.12%  |
| Wayland | 159       | 22.62%  |
| Unknown | 30        | 4.27%   |
| Tty     | 14        | 1.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 277       | 39.24%  |
| SDDM    | 192       | 27.2%   |
| GDM3    | 80        | 11.33%  |
| GDM     | 80        | 11.33%  |
| LightDM | 53        | 7.51%   |
| TDM     | 14        | 1.98%   |
| XDM     | 5         | 0.71%   |
| LXDM    | 2         | 0.28%   |
| KDM     | 1         | 0.14%   |
| GREETD  | 1         | 0.14%   |
| EMPTTY  | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 290       | 41.19%  |
| ja_JP      | 248       | 35.23%  |
| Unknown    | 62        | 8.81%   |
| zh_CN      | 21        | 2.98%   |
| en_GB      | 19        | 2.7%    |
| pt_BR      | 15        | 2.13%   |
| C          | 12        | 1.7%    |
| fr_FR      | 10        | 1.42%   |
| es_ES      | 3         | 0.43%   |
| zh_TW      | 2         | 0.28%   |
| UTF-8      | 2         | 0.28%   |
| ru_RU      | 2         | 0.28%   |
| en_AU      | 2         | 0.28%   |
| sv_SE      | 1         | 0.14%   |
| sr_RS      | 1         | 0.14%   |
| sk_SK      | 1         | 0.14%   |
| pl_PL      | 1         | 0.14%   |
| nb_NO      | 1         | 0.14%   |
| ja_JP.UTF8 | 1         | 0.14%   |
| fi_FI      | 1         | 0.14%   |
| es_GT      | 1         | 0.14%   |
| en_SG      | 1         | 0.14%   |
| en_PH      | 1         | 0.14%   |
| en_NL      | 1         | 0.14%   |
| en_IN      | 1         | 0.14%   |
| en_DK      | 1         | 0.14%   |
| en_CA      | 1         | 0.14%   |
| en_AG      | 1         | 0.14%   |
| el_GR      | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 368       | 52.8%   |
| BIOS | 329       | 47.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 507       | 72.12%  |
| Overlay | 80        | 11.38%  |
| Btrfs   | 69        | 9.82%   |
| Tmpfs   | 24        | 3.41%   |
| Unknown | 9         | 1.28%   |
| Xfs     | 7         | 1%      |
| Zfs     | 3         | 0.43%   |
| F2fs    | 2         | 0.28%   |
| Ntfs    | 1         | 0.14%   |
| Ext2    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 342       | 48.24%  |
| Unknown | 288       | 40.62%  |
| MBR     | 79        | 11.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 548       | 78.06%  |
| Yes       | 154       | 21.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 499       | 72.01%  |
| Yes       | 194       | 27.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 129       | 18.86%  |
| Toshiba              | 78        | 11.4%   |
| Dell                 | 75        | 10.96%  |
| Hewlett-Packard      | 61        | 8.92%   |
| ASUSTek Computer     | 48        | 7.02%   |
| Fujitsu              | 47        | 6.87%   |
| Apple                | 39        | 5.7%    |
| NEC Computers        | 38        | 5.56%   |
| Sony                 | 17        | 2.49%   |
| Panasonic            | 17        | 2.49%   |
| Acer                 | 17        | 2.49%   |
| MSI                  | 11        | 1.61%   |
| MouseComputer        | 10        | 1.46%   |
| HUAWEI               | 10        | 1.46%   |
| Unknown              | 7         | 1.02%   |
| Valve                | 5         | 0.73%   |
| Dynabook             | 5         | 0.73%   |
| Alienware            | 5         | 0.73%   |
| Timi                 | 4         | 0.58%   |
| Novastar             | 4         | 0.58%   |
| Google               | 4         | 0.58%   |
| Gateway              | 4         | 0.58%   |
| Thirdwave            | 3         | 0.44%   |
| System76             | 3         | 0.44%   |
| Samsung Electronics  | 3         | 0.44%   |
| Notebook             | 3         | 0.44%   |
| EPSON DIRECT         | 3         | 0.44%   |
| UNITCOM              | 2         | 0.29%   |
| SLIMBOOK             | 2         | 0.29%   |
| KOUZIRO              | 2         | 0.29%   |
| Intel Client Systems | 2         | 0.29%   |
| Intel                | 2         | 0.29%   |
| Hampoo               | 2         | 0.29%   |
| Chuwi                | 2         | 0.29%   |
| TUXEDO               | 1         | 0.15%   |
| Teclast              | 1         | 0.15%   |
| Sharp                | 1         | 0.15%   |
| Razer                | 1         | 0.15%   |
| R.W.C                | 1         | 0.15%   |
| Purism               | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba dynabook T653/46JR          | 24        | 3.51%   |
| Apple MacBookAir9,1                 | 8         | 1.17%   |
| Unknown                             | 7         | 1.02%   |
| Valve Jupiter                       | 5         | 0.73%   |
| Toshiba dynabook Satellite B552/G   | 5         | 0.73%   |
| Apple MacBookPro9,2                 | 5         | 0.73%   |
| Novastar KL55                       | 4         | 0.58%   |
| Lenovo G570 4334                    | 4         | 0.58%   |
| Toshiba dynabook Satellite B552/H   | 3         | 0.44%   |
| Lenovo G550 2958                    | 3         | 0.44%   |
| HP Notebook                         | 3         | 0.44%   |
| Dell Inspiron 1545                  | 3         | 0.44%   |
| Apple MacBookPro15,1                | 3         | 0.44%   |
| Apple MacBookPro11,5                | 3         | 0.44%   |
| Toshiba dynabook R73/BN             | 2         | 0.29%   |
| System76 Lemur Pro                  | 2         | 0.29%   |
| Panasonic CFSZ5-3                   | 2         | 0.29%   |
| Panasonic CF-S10EYADR               | 2         | 0.29%   |
| Lenovo ThinkPad X230 2325SSF        | 2         | 0.29%   |
| Lenovo IdeaPad 300-15IBR 80M3       | 2         | 0.29%   |
| Lenovo G500 20236                   | 2         | 0.29%   |
| Lenovo G50-70 20351                 | 2         | 0.29%   |
| KOUZIRO KOUZIRONB                   | 2         | 0.29%   |
| HP ProBook 6570b                    | 2         | 0.29%   |
| HP ProBook 6560b                    | 2         | 0.29%   |
| HP ProBook 6550b                    | 2         | 0.29%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 2         | 0.29%   |
| HP Pavilion dv7                     | 2         | 0.29%   |
| HP Pavilion dv6                     | 2         | 0.29%   |
| HP Pavilion dv4                     | 2         | 0.29%   |
| HP Laptop 15-db0xxx                 | 2         | 0.29%   |
| Hampoo C3W6_AP108_4GB               | 2         | 0.29%   |
| Gateway NE56R                       | 2         | 0.29%   |
| Fujitsu FARQ02010                   | 2         | 0.29%   |
| Dell XPS 9320                       | 2         | 0.29%   |
| Dell XPS 15 9500                    | 2         | 0.29%   |
| Dell XPS 13 9360                    | 2         | 0.29%   |
| Dell Latitude E6320                 | 2         | 0.29%   |
| Dell Latitude 3540                  | 2         | 0.29%   |
| Dell Inspiron N5110                 | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 86        | 12.57%  |
| Toshiba dynabook      | 75        | 10.96%  |
| Dell Inspiron         | 36        | 5.26%   |
| HP ProBook            | 16        | 2.34%   |
| Dell Latitude         | 16        | 2.34%   |
| HP Pavilion           | 13        | 1.9%    |
| Acer Aspire           | 12        | 1.75%   |
| Dell XPS              | 11        | 1.61%   |
| Lenovo IdeaPad        | 9         | 1.32%   |
| ASUS VivoBook         | 9         | 1.32%   |
| HP Laptop             | 8         | 1.17%   |
| Apple MacBookAir9     | 8         | 1.17%   |
| HP EliteBook          | 7         | 1.02%   |
| Unknown               | 7         | 1.02%   |
| Lenovo ThinkBook      | 6         | 0.88%   |
| ASUS ROG              | 6         | 0.88%   |
| Apple MacBookPro11    | 6         | 0.88%   |
| Valve Jupiter         | 5         | 0.73%   |
| Apple MacBookPro9     | 5         | 0.73%   |
| Apple MacBookPro15    | 5         | 0.73%   |
| Novastar KL55         | 4         | 0.58%   |
| Lenovo G570           | 4         | 0.58%   |
| HP ENVY               | 4         | 0.58%   |
| ASUS ASUS             | 4         | 0.58%   |
| Lenovo Legion         | 3         | 0.44%   |
| Lenovo G550           | 3         | 0.44%   |
| HP Notebook           | 3         | 0.44%   |
| EPSON DIRECT Endeavor | 3         | 0.44%   |
| Dell Vostro           | 3         | 0.44%   |
| Dell G3               | 3         | 0.44%   |
| ASUS ZenBook          | 3         | 0.44%   |
| Apple MacBookPro16    | 3         | 0.44%   |
| Alienware 17          | 3         | 0.44%   |
| Toshiba PORTEGE       | 2         | 0.29%   |
| Timi RedmiBook        | 2         | 0.29%   |
| System76 Lemur        | 2         | 0.29%   |
| Panasonic CFSZ5-3     | 2         | 0.29%   |
| Panasonic CF-S10EYADR | 2         | 0.29%   |
| MSI Stealth           | 2         | 0.29%   |
| Lenovo Yoga           | 2         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 66        | 9.65%   |
| 2018    | 63        | 9.21%   |
| 2021    | 58        | 8.48%   |
| 2012    | 58        | 8.48%   |
| 2011    | 56        | 8.19%   |
| 2020    | 46        | 6.73%   |
| 2019    | 44        | 6.43%   |
| 2008    | 38        | 5.56%   |
| 2010    | 37        | 5.41%   |
| 2016    | 31        | 4.53%   |
| 2015    | 30        | 4.39%   |
| 2009    | 28        | 4.09%   |
| 2017    | 27        | 3.95%   |
| 2007    | 27        | 3.95%   |
| 2022    | 22        | 3.22%   |
| 2014    | 22        | 3.22%   |
| 2023    | 19        | 2.78%   |
| 2006    | 8         | 1.17%   |
| 2024    | 1         | 0.15%   |
| 2005    | 1         | 0.15%   |
| 2004    | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 684       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 625       | 90.06%  |
| Enabled  | 69        | 9.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 676       | 98.83%  |
| Yes  | 8         | 1.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 192       | 27.79%  |
| 3.01-4.0    | 179       | 25.9%   |
| 8.01-16.0   | 105       | 15.2%   |
| 16.01-24.0  | 95        | 13.75%  |
| 32.01-64.0  | 41        | 5.93%   |
| 1.01-2.0    | 37        | 5.35%   |
| 64.01-256.0 | 13        | 1.88%   |
| 24.01-32.0  | 12        | 1.74%   |
| 2.01-3.0    | 11        | 1.59%   |
| 0.51-1.0    | 6         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 312       | 41.99%  |
| 2.01-3.0   | 166       | 22.34%  |
| 3.01-4.0   | 80        | 10.77%  |
| 4.01-8.0   | 79        | 10.63%  |
| 0.51-1.0   | 74        | 9.96%   |
| 8.01-16.0  | 19        | 2.56%   |
| 0.01-0.5   | 10        | 1.35%   |
| 16.01-24.0 | 3         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 518       | 73.89%  |
| 2      | 160       | 22.82%  |
| 3      | 13        | 1.85%   |
| 0      | 7         | 1%      |
| 4      | 3         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 392       | 56.98%  |
| Yes       | 296       | 43.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 552       | 80.58%  |
| No        | 133       | 19.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 663       | 96.93%  |
| No        | 21        | 3.07%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 439       | 63.53%  |
| No        | 252       | 36.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Japan   | 684       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Tokyo       | 106       | 14.21%  |
| Yokohama    | 43        | 5.76%   |
| Osaka       | 34        | 4.56%   |
| Minato-ku   | 20        | 2.68%   |
| Chiyoda     | 17        | 2.28%   |
| Niigata     | 14        | 1.88%   |
| Nagoya      | 14        | 1.88%   |
| Shinjuku    | 12        | 1.61%   |
| Saitama     | 12        | 1.61%   |
| Shibuya     | 11        | 1.47%   |
| Setagaya-ku | 11        | 1.47%   |
| Kyoto       | 11        | 1.47%   |
| Honcho      | 10        | 1.34%   |
| Shinagawa   | 8         | 1.07%   |
| Sapporo     | 7         | 0.94%   |
| Adachi      | 7         | 0.94%   |
| Miura       | 6         | 0.8%    |
| Kobe        | 6         | 0.8%    |
| Takamatsu   | 5         | 0.67%   |
| Ōtsu       | 5         | 0.67%   |
| Nakano      | 5         | 0.67%   |
| Kagoshima   | 5         | 0.67%   |
| Ichikawa    | 5         | 0.67%   |
| Tsukuba     | 4         | 0.54%   |
| Shizuoka    | 4         | 0.54%   |
| Nagasaki    | 4         | 0.54%   |
| Mito        | 4         | 0.54%   |
| Machiya     | 4         | 0.54%   |
| Kitakyushu  | 4         | 0.54%   |
| Kawaguchi   | 4         | 0.54%   |
| Hitachi     | 4         | 0.54%   |
| Hiratsuka   | 4         | 0.54%   |
| Himeji      | 4         | 0.54%   |
| Chiyoda-ku  | 4         | 0.54%   |
| Bunkyo-ku   | 4         | 0.54%   |
| Yamanashi   | 3         | 0.4%    |
| Utsunomiya  | 3         | 0.4%    |
| Ube         | 3         | 0.4%    |
| Tomisato    | 3         | 0.4%    |
| Takasago    | 3         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 106       | 143    | 12.68%  |
| Toshiba                   | 105       | 117    | 12.56%  |
| WDC                       | 81        | 91     | 9.69%   |
| Unknown                   | 54        | 69     | 6.46%   |
| Seagate                   | 53        | 74     | 6.34%   |
| SanDisk                   | 43        | 54     | 5.14%   |
| Crucial                   | 36        | 45     | 4.31%   |
| Hitachi                   | 32        | 35     | 3.83%   |
| Apple                     | 29        | 32     | 3.47%   |
| SK hynix                  | 24        | 26     | 2.87%   |
| Micron Technology         | 24        | 38     | 2.87%   |
| Kingston                  | 23        | 25     | 2.75%   |
| Intel                     | 17        | 19     | 2.03%   |
| A-DATA Technology         | 16        | 21     | 1.91%   |
| SPCC                      | 15        | 19     | 1.79%   |
| HGST                      | 15        | 16     | 1.79%   |
| KIOXIA                    | 12        | 14     | 1.44%   |
| Fujitsu                   | 9         | 10     | 1.08%   |
| Transcend                 | 8         | 11     | 0.96%   |
| Unknown                   | 8         | 9      | 0.96%   |
| SUNEAST                   | 7         | 8      | 0.84%   |
| Plextor                   | 6         | 8      | 0.72%   |
| Micron/Crucial Technology | 6         | 6      | 0.72%   |
| JMicron Technology        | 5         | 5      | 0.6%    |
| China                     | 5         | 9      | 0.6%    |
| Zheino                    | 4         | 5      | 0.48%   |
| Teclast                   | 4         | 4      | 0.48%   |
| BUFFALO                   | 4         | 4      | 0.48%   |
| Silicon Motion            | 3         | 3      | 0.36%   |
| PNY                       | 3         | 3      | 0.36%   |
| Phison Electronics        | 3         | 4      | 0.36%   |
| Phison                    | 3         | 3      | 0.36%   |
| KIOXIA-EXCERIA            | 3         | 4      | 0.36%   |
| Green House               | 3         | 5      | 0.36%   |
| Team                      | 2         | 3      | 0.24%   |
| SSSTC                     | 2         | 2      | 0.24%   |
| SSK                       | 2         | 2      | 0.24%   |
| Ramaxel Technology        | 2         | 2      | 0.24%   |
| QC-FT-D                   | 2         | 2      | 0.24%   |
| Patriot                   | 2         | 3      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD075 752GB                           | 25        | 2.88%   |
| Unknown MMC Card  64GB                             | 14        | 1.61%   |
| Crucial CT500MX500SSD1 500GB                       | 10        | 1.15%   |
| Toshiba MQ01ABF050 500GB                           | 8         | 0.92%   |
| Toshiba MQ01ABD100 1TB                             | 8         | 0.92%   |
| Apple SSD AP0256N 256GB                            | 8         | 0.92%   |
| Unknown                                            | 8         | 0.92%   |
| Unknown MMC Card  128GB                            | 7         | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB                     | 7         | 0.81%   |
| SPCC Solid State Disk 256GB                        | 5         | 0.58%   |
| Seagate ST9500325AS 500GB                          | 5         | 0.58%   |
| Seagate ST500LT012-1DG142 500GB                    | 5         | 0.58%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 5         | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 5         | 0.58%   |
| Crucial CT240BX500SSD1 240GB                       | 5         | 0.58%   |
| Unknown SD/MMC/MS PRO 128GB                        | 4         | 0.46%   |
| Unknown MMC Card  32GB                             | 4         | 0.46%   |
| Samsung SSD 860 EVO 500GB                          | 4         | 0.46%   |
| Samsung NVMe SSD Drive 1TB                         | 4         | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 4         | 0.46%   |
| Kingston RBUSNS4180S3256GJ 256GB SSD               | 4         | 0.46%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                   | 3         | 0.35%   |
| WDC WD5000LPVX-08V0TT5 500GB                       | 3         | 0.35%   |
| WDC WD1600BEVT-22ZCT0 160GB                        | 3         | 0.35%   |
| Unknown NVMe SSD Drive 512GB                       | 3         | 0.35%   |
| Unknown ASP550SS7-240GM-MI-B 240GB SSD             | 3         | 0.35%   |
| Toshiba THNSNJ128GCSU 128GB SSD                    | 3         | 0.35%   |
| Toshiba MQ01ABD100H 1TB                            | 3         | 0.35%   |
| Toshiba MQ01ABD050 500GB                           | 3         | 0.35%   |
| SUNEAST SSD SE800 512GB                            | 3         | 0.35%   |
| SPCC Solid State Disk 128GB                        | 3         | 0.35%   |
| SK hynix HFM001TD3JX013N 1024GB                    | 3         | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 3         | 0.35%   |
| Seagate ST320LT012-1DG14C 320GB                    | 3         | 0.35%   |
| SanDisk NVMe SSD Drive 256GB                       | 3         | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                         | 3         | 0.35%   |
| SanDisk Extreme SSD 1TB                            | 3         | 0.35%   |
| Samsung SSD 860 QVO 1TB                            | 3         | 0.35%   |
| Samsung MZVLQ512HALU-00000 512GB                   | 3         | 0.35%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD               | 3         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 80        | 85     | 31.37%  |
| WDC                 | 57        | 63     | 22.35%  |
| Seagate             | 51        | 72     | 20%     |
| Hitachi             | 30        | 33     | 11.76%  |
| HGST                | 15        | 16     | 5.88%   |
| Fujitsu             | 9         | 10     | 3.53%   |
| Unknown             | 4         | 5      | 1.57%   |
| JMicron Technology  | 3         | 3      | 1.18%   |
| QC-FT-D             | 2         | 2      | 0.78%   |
| Samsung Electronics | 1         | 3      | 0.39%   |
| SABRENT             | 1         | 1      | 0.39%   |
| MARSHAL             | 1         | 2      | 0.39%   |
| Apple               | 1         | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 61     | 14.24%  |
| Crucial             | 35        | 44     | 11.59%  |
| SanDisk             | 22        | 29     | 7.28%   |
| WDC                 | 16        | 18     | 5.3%    |
| Toshiba             | 15        | 19     | 4.97%   |
| Kingston            | 15        | 16     | 4.97%   |
| A-DATA Technology   | 15        | 20     | 4.97%   |
| SPCC                | 13        | 16     | 4.3%    |
| Apple               | 10        | 10     | 3.31%   |
| Micron Technology   | 8         | 10     | 2.65%   |
| Intel               | 8         | 8      | 2.65%   |
| Transcend           | 7         | 10     | 2.32%   |
| SUNEAST             | 7         | 8      | 2.32%   |
| Plextor             | 6         | 8      | 1.99%   |
| Unknown             | 5         | 5      | 1.66%   |
| China               | 5         | 9      | 1.66%   |
| SK hynix            | 4         | 4      | 1.32%   |
| BUFFALO             | 4         | 4      | 1.32%   |
| Unknown             | 4         | 4      | 1.32%   |
| Teclast             | 3         | 3      | 0.99%   |
| PNY                 | 3         | 3      | 0.99%   |
| Green House         | 3         | 5      | 0.99%   |
| Zheino              | 2         | 2      | 0.66%   |
| Team                | 2         | 3      | 0.66%   |
| SSK                 | 2         | 2      | 0.66%   |
| Seagate             | 2         | 2      | 0.66%   |
| Patriot             | 2         | 3      | 0.66%   |
| OCZ                 | 2         | 2      | 0.66%   |
| Netac               | 2         | 2      | 0.66%   |
| Lexar               | 2         | 3      | 0.66%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.66%   |
| Hitachi             | 2         | 2      | 0.66%   |
| Apacer              | 2         | 4      | 0.66%   |
| USB                 | 1         | 1      | 0.33%   |
| TCSUNBOW            | 1         | 1      | 0.33%   |
| StoreJet            | 1         | 1      | 0.33%   |
| SC-M280             | 1         | 1      | 0.33%   |
| RX7                 | 1         | 1      | 0.33%   |
| Ramaxel Technology  | 1         | 1      | 0.33%   |
| OASDX               | 1         | 2      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 272       | 377    | 34.96%  |
| HDD     | 245       | 296    | 31.49%  |
| NVMe    | 201       | 269    | 25.84%  |
| MMC     | 47        | 64     | 6.04%   |
| Unknown | 13        | 13     | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 477       | 640    | 62.11%  |
| NVMe | 201       | 266    | 26.17%  |
| MMC  | 47        | 64     | 6.12%   |
| SAS  | 43        | 49     | 5.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 381       | 510    | 74.85%  |
| 0.51-1.0   | 114       | 147    | 22.4%   |
| 1.01-2.0   | 12        | 14     | 2.36%   |
| 3.01-4.0   | 1         | 1      | 0.2%    |
| 10.01-20.0 | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 252       | 34.76%  |
| 251-500        | 134       | 18.48%  |
| 501-1000       | 85        | 11.72%  |
| 1-20           | 71        | 9.79%   |
| 51-100         | 68        | 9.38%   |
| 21-50          | 37        | 5.1%    |
| 1001-2000      | 32        | 4.41%   |
| Unknown        | 25        | 3.45%   |
| 2001-3000      | 13        | 1.79%   |
| More than 3000 | 8         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 365       | 49.26%  |
| 21-50          | 125       | 16.87%  |
| 51-100         | 72        | 9.72%   |
| 101-250        | 71        | 9.58%   |
| 251-500        | 46        | 6.21%   |
| 501-1000       | 28        | 3.78%   |
| Unknown        | 25        | 3.37%   |
| 1001-2000      | 5         | 0.67%   |
| 2001-3000      | 3         | 0.4%    |
| More than 3000 | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB                         | 24        | 24     | 35.82%  |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 4.48%   |
| Seagate ST9160314AS 160GB                        | 2         | 2      | 2.99%   |
| HGST HTS541075A9E680 752GB                       | 2         | 2      | 2.99%   |
| WDC WD5000BEVT-55A0RT0 500GB                     | 1         | 1      | 1.49%   |
| WDC WD3200BEVT-08A23T1 320GB                     | 1         | 1      | 1.49%   |
| WDC WD1600BEVS-26RST0 160GB                      | 1         | 1      | 1.49%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 1.49%   |
| Toshiba MK2555GSX 250GB                          | 1         | 1      | 1.49%   |
| Toshiba MK2552GSX 250GB                          | 1         | 1      | 1.49%   |
| Toshiba MK1652GSX 160GB                          | 1         | 1      | 1.49%   |
| Toshiba MK1255GSX H 120GB                        | 1         | 1      | 1.49%   |
| Teclast 240GB SSD                                | 1         | 1      | 1.49%   |
| Teclast 128GB SSD                                | 1         | 1      | 1.49%   |
| SSSTC CL1-4D128 128GB                            | 1         | 1      | 1.49%   |
| Seagate ST9120817AS 120GB                        | 1         | 1      | 1.49%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 1.49%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 1.49%   |
| SanDisk SSD PLUS 1000GB                          | 1         | 2      | 1.49%   |
| SanDisk SSD P4 64GB                              | 1         | 1      | 1.49%   |
| SanDisk SSD P4 32GB                              | 1         | 1      | 1.49%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.49%   |
| Samsung Electronics HM641JI 640GB                | 1         | 2      | 1.49%   |
| Netac SSD 240GB                                  | 1         | 1      | 1.49%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD    | 1         | 1      | 1.49%   |
| MARSHAL MAL2020SA 80 20GB                        | 1         | 1      | 1.49%   |
| LITEON CV8-8E128-HP 128GB SSD                    | 1         | 4      | 1.49%   |
| Lite-On PH3-CE240 240GB SSD                      | 1         | 1      | 1.49%   |
| Intel SSDSA1M160G2HP 160GB                       | 1         | 1      | 1.49%   |
| Hitachi HTS723232L9A360 320GB                    | 1         | 1      | 1.49%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 1.49%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 1      | 1.49%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 1.49%   |
| Hitachi HTS545025B9SA02 250GB                    | 1         | 1      | 1.49%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 1.49%   |
| Crucial CT480BX500SSD1 480GB                     | 1         | 1      | 1.49%   |
| Crucial CT275MX300SSD1 275GB                     | 1         | 1      | 1.49%   |
| Crucial C300-CTFDDAC064MAG 64GB SSD              | 1         | 3      | 1.49%   |
| A-DATA Technology AXM21S3-24GM-B 24GB SSD        | 1         | 1      | 1.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 29        | 29     | 43.28%  |
| Seagate             | 9         | 9      | 13.43%  |
| Hitachi             | 5         | 5      | 7.46%   |
| WDC                 | 3         | 3      | 4.48%   |
| SanDisk             | 3         | 4      | 4.48%   |
| HGST                | 3         | 3      | 4.48%   |
| Crucial             | 3         | 5      | 4.48%   |
| Teclast             | 2         | 2      | 2.99%   |
| Samsung Electronics | 2         | 3      | 2.99%   |
| SSSTC               | 1         | 1      | 1.49%   |
| Netac               | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| MARSHAL             | 1         | 1      | 1.49%   |
| LITEON              | 1         | 4      | 1.49%   |
| Lite-On             | 1         | 1      | 1.49%   |
| Intel               | 1         | 1      | 1.49%   |
| A-DATA Technology   | 1         | 1      | 1.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 29        | 29     | 56.86%  |
| Seagate             | 9         | 9      | 17.65%  |
| Hitachi             | 5         | 5      | 9.8%    |
| WDC                 | 3         | 3      | 5.88%   |
| HGST                | 3         | 3      | 5.88%   |
| Samsung Electronics | 1         | 2      | 1.96%   |
| MARSHAL             | 1         | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 52     | 76.12%  |
| SSD  | 15        | 21     | 22.39%  |
| NVMe | 1         | 1      | 1.49%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 365       | 532    | 49.53%  |
| Works    | 305       | 412    | 41.38%  |
| Malfunc  | 66        | 74     | 8.96%   |
| Failed   | 1         | 1      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 480       | 62.91%  |
| Samsung Electronics            | 72        | 9.44%   |
| AMD                            | 61        | 7.99%   |
| SanDisk                        | 26        | 3.41%   |
| SK hynix                       | 21        | 2.75%   |
| Apple                          | 18        | 2.36%   |
| Micron Technology              | 17        | 2.23%   |
| KIOXIA                         | 14        | 1.83%   |
| Toshiba America Info Systems   | 9         | 1.18%   |
| Kingston Technology Company    | 9         | 1.18%   |
| Phison Electronics             | 8         | 1.05%   |
| Silicon Motion                 | 7         | 0.92%   |
| Micron/Crucial Technology      | 6         | 0.79%   |
| Nvidia                         | 4         | 0.52%   |
| Solid State Storage Technology | 3         | 0.39%   |
| ADATA Technology               | 3         | 0.39%   |
| Yangtze Memory Technologies    | 1         | 0.13%   |
| VIA Technologies               | 1         | 0.13%   |
| O2 Micro                       | 1         | 0.13%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.13%   |
| Unknown                        | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 98        | 11.94%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 51        | 6.21%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 47        | 5.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 45        | 5.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 32        | 3.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 29        | 3.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 26        | 3.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 25        | 3.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 23        | 2.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 19        | 2.31%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 18        | 2.19%   |
| Apple ANS2 NVMe Controller                                                       | 17        | 2.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 1.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 1.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 14        | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 1.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 13        | 1.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 13        | 1.58%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 11        | 1.34%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 10        | 1.22%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 10        | 1.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 0.85%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 6         | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 5         | 0.61%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 5         | 0.61%   |
| Intel SSD 660P Series                                                            | 5         | 0.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 0.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 0.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 0.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 0.61%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 5         | 0.61%   |
| AMD SB600 IDE                                                                    | 5         | 0.61%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.49%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 480       | 61.3%   |
| NVMe | 202       | 25.8%   |
| IDE  | 60        | 7.66%   |
| RAID | 41        | 5.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 583       | 85.23%  |
| AMD          | 100       | 14.62%  |
| CentaurHauls | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz         | 24        | 3.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 16        | 2.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 10        | 1.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 1.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 9         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 1.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 9         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 8         | 1.17%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 1.17%   |
| Intel Core i3-1000NG4 CPU @ 1.10GHz     | 8         | 1.17%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 8         | 1.17%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 8         | 1.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 8         | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 7         | 1.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 7         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 7         | 1.02%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 7         | 1.02%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 7         | 1.02%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 6         | 0.88%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 6         | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 6         | 0.88%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 6         | 0.88%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 6         | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 5         | 0.73%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 5         | 0.73%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 0.73%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 5         | 0.73%   |
| Intel Core i3-4000M CPU @ 2.40GHz       | 5         | 0.73%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 5         | 0.73%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 5         | 0.73%   |
| Intel Atom CPU N270 @ 1.60GHz           | 5         | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 5         | 0.73%   |
| AMD Custom APU 0405                     | 5         | 0.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 4         | 0.58%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 4         | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 194       | 28.36%  |
| Intel Core i7           | 115       | 16.81%  |
| Intel Celeron           | 78        | 11.4%   |
| Intel Core i3           | 56        | 8.19%   |
| Other                   | 47        | 6.87%   |
| Intel Core 2 Duo        | 42        | 6.14%   |
| AMD Ryzen 7             | 23        | 3.36%   |
| AMD Ryzen 5             | 22        | 3.22%   |
| Intel Atom              | 19        | 2.78%   |
| Intel Core 2            | 7         | 1.02%   |
| Intel Pentium           | 6         | 0.88%   |
| AMD Ryzen 7 PRO         | 6         | 0.88%   |
| AMD Ryzen 3             | 6         | 0.88%   |
| Intel Celeron M         | 5         | 0.73%   |
| AMD E2                  | 5         | 0.73%   |
| Intel Celeron Dual-Core | 4         | 0.58%   |
| AMD A6                  | 4         | 0.58%   |
| Intel Genuine           | 3         | 0.44%   |
| Intel Core i9           | 3         | 0.44%   |
| AMD Ryzen 9             | 3         | 0.44%   |
| AMD E1                  | 3         | 0.44%   |
| AMD Athlon              | 3         | 0.44%   |
| Intel Pentium M         | 2         | 0.29%   |
| Intel Pentium Dual-Core | 2         | 0.29%   |
| Intel Core M            | 2         | 0.29%   |
| AMD Turion 64 X2 Mobile | 2         | 0.29%   |
| AMD Ryzen 5 PRO         | 2         | 0.29%   |
| AMD Mobile Sempron      | 2         | 0.29%   |
| Intel Core m5           | 1         | 0.15%   |
| Intel Core m3           | 1         | 0.15%   |
| Intel Core 2 Extreme    | 1         | 0.15%   |
| Intel Core              | 1         | 0.15%   |
| CentaurHauls VIA C7     | 1         | 0.15%   |
| AMD V140                | 1         | 0.15%   |
| AMD V120                | 1         | 0.15%   |
| AMD Turion Neo X2       | 1         | 0.15%   |
| AMD Sempron             | 1         | 0.15%   |
| AMD Ryzen 3 PRO         | 1         | 0.15%   |
| AMD Quad-Core           | 1         | 0.15%   |
| AMD E                   | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 403       | 58.92%  |
| 4      | 156       | 22.81%  |
| 6      | 44        | 6.43%   |
| 8      | 38        | 5.56%   |
| 1      | 26        | 3.8%    |
| 14     | 9         | 1.32%   |
| 12     | 4         | 0.58%   |
| 10     | 3         | 0.44%   |
| 16     | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 684       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 481       | 70.32%  |
| 1      | 203       | 29.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 662       | 96.78%  |
| 32-bit         | 16        | 2.34%   |
| Unknown        | 6         | 0.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 231       | 32.49%  |
| 0x206a7    | 67        | 9.42%   |
| 0x306a9    | 51        | 7.17%   |
| 0x1067a    | 25        | 3.52%   |
| 0x306d4    | 21        | 2.95%   |
| 0x806ec    | 19        | 2.67%   |
| 0x20655    | 19        | 2.67%   |
| 0x806ea    | 15        | 2.11%   |
| 0x306c3    | 15        | 2.11%   |
| 0x806e9    | 13        | 1.83%   |
| 0x40651    | 13        | 1.83%   |
| 0xa0652    | 11        | 1.55%   |
| 0x0a50000c | 11        | 1.55%   |
| 0x806c1    | 10        | 1.41%   |
| 0x406e3    | 10        | 1.41%   |
| 0x20652    | 10        | 1.41%   |
| 0x10676    | 9         | 1.27%   |
| 0x906ea    | 7         | 0.98%   |
| 0x806eb    | 7         | 0.98%   |
| 0x406c4    | 7         | 0.98%   |
| 0x106c2    | 7         | 0.98%   |
| 0x08600106 | 7         | 0.98%   |
| 0x08108102 | 7         | 0.98%   |
| 0x906a3    | 6         | 0.84%   |
| 0x6f6      | 6         | 0.84%   |
| 0x08108109 | 6         | 0.84%   |
| 0x506c9    | 5         | 0.7%    |
| 0x406c3    | 5         | 0.7%    |
| 0x30678    | 5         | 0.7%    |
| 0x08608103 | 5         | 0.7%    |
| 0x6fd      | 4         | 0.56%   |
| 0x6e8      | 4         | 0.56%   |
| 0x506e3    | 4         | 0.56%   |
| 0x0a50000d | 4         | 0.56%   |
| 0x906e9    | 3         | 0.42%   |
| 0x706a8    | 3         | 0.42%   |
| 0x6d8      | 3         | 0.42%   |
| 0x40661    | 3         | 0.42%   |
| 0x010000c8 | 3         | 0.42%   |
| 0xb06a2    | 2         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 101       | 14.77%  |
| SandyBridge       | 88        | 12.87%  |
| IvyBridge         | 69        | 10.09%  |
| Haswell           | 49        | 7.16%   |
| Penryn            | 44        | 6.43%   |
| Westmere          | 39        | 5.7%    |
| Skylake           | 26        | 3.8%    |
| Broadwell         | 26        | 3.8%    |
| Zen 3             | 22        | 3.22%   |
| Silvermont        | 22        | 3.22%   |
| Unknown           | 22        | 3.22%   |
| TigerLake         | 19        | 2.78%   |
| Core              | 18        | 2.63%   |
| Zen+              | 16        | 2.34%   |
| CometLake         | 16        | 2.34%   |
| Zen 2             | 14        | 2.05%   |
| Icelake           | 14        | 2.05%   |
| Alderlake Hybrid  | 14        | 2.05%   |
| Bonnell           | 9         | 1.32%   |
| P6                | 8         | 1.17%   |
| K8 Hammer         | 6         | 0.88%   |
| Goldmont plus     | 6         | 0.88%   |
| Goldmont          | 6         | 0.88%   |
| Puma              | 5         | 0.73%   |
| Zen               | 4         | 0.58%   |
| K10               | 3         | 0.44%   |
| Jaguar            | 3         | 0.44%   |
| Bobcat            | 3         | 0.44%   |
| Piledriver        | 2         | 0.29%   |
| Nehalem           | 2         | 0.29%   |
| K8 & K10 hybrid   | 2         | 0.29%   |
| K10 Llano         | 2         | 0.29%   |
| Excavator         | 2         | 0.29%   |
| Meteorlake Hybrid | 1         | 0.15%   |
| Gracemont         | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 560       | 71.7%   |
| AMD              | 121       | 15.49%  |
| Nvidia           | 99        | 12.68%  |
| VIA Technologies | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 87        | 10.61%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 69        | 8.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 38        | 4.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 34        | 4.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 21        | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 2.56%   |
| Intel UHD Graphics 620                                                                   | 20        | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 2.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 18        | 2.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 2.07%   |
| Intel HD Graphics 5500                                                                   | 17        | 2.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 2.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 2.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.95%   |
| Intel HD Graphics 620                                                                    | 15        | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.59%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 13        | 1.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 12        | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 1.1%    |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 8         | 0.98%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 0.85%   |
| AMD Lucienne                                                                             | 7         | 0.85%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 6         | 0.73%   |
| Intel HD Graphics 500                                                                    | 6         | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.73%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.61%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 0.61%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 5         | 0.61%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 5         | 0.61%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.61%   |
| AMD Barcelo                                                                              | 5         | 0.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 464       | 67.54%  |
| 1 x AMD        | 91        | 13.25%  |
| Intel + Nvidia | 72        | 10.48%  |
| 1 x Nvidia     | 17        | 2.47%   |
| Intel + AMD    | 12        | 1.75%   |
| 2 x Intel      | 11        | 1.6%    |
| AMD + Nvidia   | 10        | 1.46%   |
| 2 x AMD        | 7         | 1.02%   |
| Other          | 2         | 0.29%   |
| 1 x VIA        | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 615       | 89.78%  |
| Proprietary | 53        | 7.74%   |
| Unknown     | 17        | 2.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 519       | 74.89%  |
| 0.01-0.5   | 64        | 9.24%   |
| 1.01-2.0   | 53        | 7.65%   |
| 3.01-4.0   | 21        | 3.03%   |
| 0.51-1.0   | 20        | 2.89%   |
| 5.01-6.0   | 7         | 1.01%   |
| 7.01-8.0   | 6         | 0.87%   |
| 8.01-16.0  | 3         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 140       | 20.86%  |
| AU Optronics            | 106       | 15.8%   |
| Samsung Electronics     | 64        | 9.54%   |
| BOE                     | 63        | 9.39%   |
| Chimei Innolux          | 61        | 9.09%   |
| Apple                   | 36        | 5.37%   |
| Sharp                   | 34        | 5.07%   |
| Chi Mei Optoelectronics | 25        | 3.73%   |
| Lenovo                  | 18        | 2.68%   |
| PANDA                   | 11        | 1.64%   |
| Dell                    | 10        | 1.49%   |
| Panasonic               | 8         | 1.19%   |
| Goldstar                | 8         | 1.19%   |
| InfoVision              | 7         | 1.04%   |
| Valve                   | 5         | 0.75%   |
| CPT                     | 5         | 0.75%   |
| Acer                    | 5         | 0.75%   |
| Toshiba                 | 4         | 0.6%    |
| Philips                 | 4         | 0.6%    |
| NOV                     | 4         | 0.6%    |
| CSO                     | 4         | 0.6%    |
| BenQ                    | 4         | 0.6%    |
| Sony                    | 3         | 0.45%   |
| Mitsubishi              | 3         | 0.45%   |
| LG Philips              | 3         | 0.45%   |
| Hewlett-Packard         | 3         | 0.45%   |
| ASUSTek Computer        | 3         | 0.45%   |
| Ancor Communications    | 3         | 0.45%   |
| IOD                     | 2         | 0.3%    |
| Iiyama                  | 2         | 0.3%    |
| AOC                     | 2         | 0.3%    |
| Unknown                 | 2         | 0.3%    |
| Yamaha                  | 1         | 0.15%   |
| SLD                     | 1         | 0.15%   |
| Sceptre Tech            | 1         | 0.15%   |
| SAC                     | 1         | 0.15%   |
| RTK                     | 1         | 0.15%   |
| Roku                    | 1         | 0.15%   |
| Quanta Display          | 1         | 0.15%   |
| Orion                   | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 24        | 3.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 1.18%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 8         | 1.18%   |
| Apple Color LCD APPA041 2560x1600 286x179mm 13.3-inch                    | 8         | 1.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.88%   |
| Apple Cinema HD APP9223 1920x1200 495x310mm 23.0-inch                    | 6         | 0.88%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 5         | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.59%   |
| NOV NOVA HD CARD NOV0405 1920x1080 459x296mm 21.5-inch                   | 4         | 0.59%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 4         | 0.59%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.59%   |
| LG Display LCD Monitor LGD02CB 1366x768 344x194mm 15.5-inch              | 4         | 0.59%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch              | 4         | 0.59%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.59%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                    | 4         | 0.59%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch             | 3         | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1364 1366x768 293x164mm 13.2-inch          | 3         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 3         | 0.44%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 3         | 0.44%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                     | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO1068 1920x1200 264x166mm 12.3-inch           | 3         | 0.44%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                    | 3         | 0.44%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                        | 2         | 0.29%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.29%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                  | 2         | 0.29%   |
| Sharp LCD Monitor SHP14D5 1920x1080 294x165mm 13.3-inch                  | 2         | 0.29%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 2         | 0.29%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.29%   |
| Sharp HDMI SHP0FDB 1360x768 820x460mm 37.0-inch                          | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5033 1280x800 331x207mm 15.4-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 237       | 35.91%  |
| 1920x1080 (FHD)    | 212       | 32.12%  |
| 1280x800 (WXGA)    | 33        | 5%      |
| 3840x2160 (4K)     | 29        | 4.39%   |
| 1920x1200 (WUXGA)  | 25        | 3.79%   |
| 2560x1600          | 19        | 2.88%   |
| 1600x900 (HD+)     | 18        | 2.73%   |
| 2880x1800          | 12        | 1.82%   |
| 2560x1440 (QHD)    | 12        | 1.82%   |
| 1440x900 (WXGA+)   | 10        | 1.52%   |
| 3840x2400          | 6         | 0.91%   |
| 800x1280           | 5         | 0.76%   |
| 1920x540           | 5         | 0.76%   |
| 1280x1024 (SXGA)   | 4         | 0.61%   |
| 3200x1800 (QHD+)   | 3         | 0.45%   |
| 2560x1080          | 3         | 0.45%   |
| 2160x1440          | 3         | 0.45%   |
| 1024x768 (XGA)     | 3         | 0.45%   |
| 1024x600           | 3         | 0.45%   |
| 3456x2160          | 2         | 0.3%    |
| 3072x1920          | 2         | 0.3%    |
| 2880x1620          | 2         | 0.3%    |
| 1680x1050 (WSXGA+) | 2         | 0.3%    |
| 1360x768           | 2         | 0.3%    |
| 1024x576           | 2         | 0.3%    |
| 3000x2000          | 1         | 0.15%   |
| 2520x1680          | 1         | 0.15%   |
| 2256x1504          | 1         | 0.15%   |
| 2240x1400          | 1         | 0.15%   |
| 1920x1280          | 1         | 0.15%   |
| 1400x1050          | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 283       | 41.8%   |
| 13      | 126       | 18.61%  |
| 14      | 61        | 9.01%   |
| 12      | 41        | 6.06%   |
| 17      | 27        | 3.99%   |
| 23      | 17        | 2.51%   |
| 11      | 17        | 2.51%   |
| 24      | 13        | 1.92%   |
| 21      | 13        | 1.92%   |
| 16      | 12        | 1.77%   |
| 31      | 10        | 1.48%   |
| 10      | 9         | 1.33%   |
| 27      | 8         | 1.18%   |
| Unknown | 6         | 0.89%   |
| 72      | 5         | 0.74%   |
| 18      | 5         | 0.74%   |
| 7       | 5         | 0.74%   |
| 37      | 3         | 0.44%   |
| 32      | 3         | 0.44%   |
| 19      | 3         | 0.44%   |
| 34      | 2         | 0.3%    |
| 84      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
| 39      | 1         | 0.15%   |
| 38      | 1         | 0.15%   |
| 29      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |
| 25      | 1         | 0.15%   |
| 20      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 374       | 55.57%  |
| 201-300     | 163       | 24.22%  |
| 351-400     | 37        | 5.5%    |
| 501-600     | 34        | 5.05%   |
| 401-500     | 26        | 3.86%   |
| 601-700     | 11        | 1.63%   |
| 1501-2000   | 6         | 0.89%   |
| Unknown     | 6         | 0.89%   |
| 801-900     | 5         | 0.74%   |
| 701-800     | 5         | 0.74%   |
| 1-100       | 5         | 0.74%   |
| 1001-1500   | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 484       | 78.06%  |
| 16/10   | 106       | 17.1%   |
| 3/2     | 10        | 1.61%   |
| 0.67    | 5         | 0.81%   |
| 5/4     | 4         | 0.65%   |
| Unknown | 4         | 0.65%   |
| 4/3     | 3         | 0.48%   |
| 21/9    | 3         | 0.48%   |
| 32/9    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 284       | 41.95%  |
| 81-90          | 106       | 15.66%  |
| 71-80          | 81        | 11.96%  |
| 61-70          | 40        | 5.91%   |
| 201-250        | 39        | 5.76%   |
| 121-130        | 22        | 3.25%   |
| 51-60          | 17        | 2.51%   |
| 351-500        | 15        | 2.22%   |
| 301-350        | 10        | 1.48%   |
| 111-120        | 10        | 1.48%   |
| 41-50          | 9         | 1.33%   |
| 151-200        | 8         | 1.18%   |
| More than 1000 | 7         | 1.03%   |
| 141-150        | 7         | 1.03%   |
| Unknown        | 6         | 0.89%   |
| 1-40           | 5         | 0.74%   |
| 501-1000       | 5         | 0.74%   |
| 251-300        | 2         | 0.3%    |
| 131-140        | 2         | 0.3%    |
| 91-100         | 2         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 203       | 30.48%  |
| 101-120       | 182       | 27.33%  |
| 51-100        | 131       | 19.67%  |
| 161-240       | 106       | 15.92%  |
| More than 240 | 30        | 4.5%    |
| 1-50          | 8         | 1.2%    |
| Unknown       | 6         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 589       | 85.36%  |
| 2     | 74        | 10.72%  |
| 0     | 24        | 3.48%   |
| 3     | 3         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 355       | 33.3%   |
| Realtek Semiconductor                  | 283       | 26.55%  |
| Qualcomm Atheros                       | 180       | 16.89%  |
| Broadcom                               | 94        | 8.82%   |
| Marvell Technology Group               | 24        | 2.25%   |
| ASIX Electronics                       | 18        | 1.69%   |
| MediaTek                               | 16        | 1.5%    |
| Broadcom Limited                       | 16        | 1.5%    |
| Apple                                  | 9         | 0.84%   |
| Ralink                                 | 8         | 0.75%   |
| TP-Link                                | 6         | 0.56%   |
| BUFFALO                                | 6         | 0.56%   |
| Sierra Wireless                        | 4         | 0.38%   |
| PLANEX                                 | 4         | 0.38%   |
| Huawei Technologies                    | 4         | 0.38%   |
| Ralink Technology                      | 3         | 0.28%   |
| Qualcomm                               | 3         | 0.28%   |
| Nvidia                                 | 3         | 0.28%   |
| Lenovo                                 | 3         | 0.28%   |
| Elecom                                 | 3         | 0.28%   |
| U-Blox                                 | 2         | 0.19%   |
| Qualcomm Atheros Communications        | 2         | 0.19%   |
| Google                                 | 2         | 0.19%   |
| DisplayLink                            | 2         | 0.19%   |
| D-Link                                 | 2         | 0.19%   |
| Xiaomi                                 | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Samsung Electronics                    | 1         | 0.09%   |
| QNAP System                            | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| NetGear                                | 1         | 0.09%   |
| NEC Computers                          | 1         | 0.09%   |
| Logitec                                | 1         | 0.09%   |
| JMicron Technology                     | 1         | 0.09%   |
| ICS Advent                             | 1         | 0.09%   |
| I-O Data Device                        | 1         | 0.09%   |
| Gemtek                                 | 1         | 0.09%   |
| Dell                                   | 1         | 0.09%   |
| Aquantia                               | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 155       | 11.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 42        | 3.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 33        | 2.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 30        | 2.29%   |
| Intel Wireless 7265                                                     | 23        | 1.75%   |
| Intel Wi-Fi 6 AX200                                                     | 22        | 1.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 1.68%   |
| Intel 82579V Gigabit Network Connection                                 | 22        | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 1.6%    |
| Intel Wireless 8265 / 8275                                              | 21        | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 20        | 1.52%   |
| Intel Wireless 7260                                                     | 20        | 1.52%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 1.22%   |
| ASIX AX88179 Gigabit Ethernet                                           | 16        | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.07%   |
| Intel Wireless 8260                                                     | 14        | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 0.99%   |
| Intel Wireless 3165                                                     | 13        | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 0.91%   |
| Intel Wireless 3160                                                     | 12        | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 11        | 0.84%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 11        | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 0.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 0.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 9         | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.69%   |
| Apple iBridge                                                           | 9         | 0.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 8         | 0.61%   |
| Intel WiMAX Connection 2400m                                            | 8         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                    | 8         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 316       | 45.27%  |
| Qualcomm Atheros                | 146       | 20.92%  |
| Realtek Semiconductor           | 94        | 13.47%  |
| Broadcom                        | 70        | 10.03%  |
| MediaTek                        | 16        | 2.29%   |
| Broadcom Limited                | 11        | 1.58%   |
| Ralink                          | 8         | 1.15%   |
| TP-Link                         | 6         | 0.86%   |
| BUFFALO                         | 6         | 0.86%   |
| Sierra Wireless                 | 4         | 0.57%   |
| PLANEX                          | 4         | 0.57%   |
| Ralink Technology               | 3         | 0.43%   |
| Qualcomm                        | 3         | 0.43%   |
| Elecom                          | 3         | 0.43%   |
| Qualcomm Atheros Communications | 2         | 0.29%   |
| D-Link                          | 2         | 0.29%   |
| NetGear                         | 1         | 0.14%   |
| Logitec                         | 1         | 0.14%   |
| I-O Data Device                 | 1         | 0.14%   |
| Dell                            | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 4.7%    |
| Intel Wireless 7265                                                     | 23        | 3.28%   |
| Intel Wi-Fi 6 AX200                                                     | 22        | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 2.99%   |
| Intel Wireless 8265 / 8275                                              | 21        | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 2.85%   |
| Intel Wireless 7260                                                     | 20        | 2.85%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 2.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.99%   |
| Intel Wireless 8260                                                     | 14        | 1.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 1.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 1.85%   |
| Intel Wireless 3165                                                     | 13        | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 1.71%   |
| Intel Wireless 3160                                                     | 12        | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 11        | 1.57%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 11        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.42%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.42%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 9         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.28%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 8         | 1.14%   |
| Broadcom BCM4377b Wireless Network Adapter                              | 8         | 1.14%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 8         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 7         | 1%      |
| Intel WiFi Link 5100                                                    | 7         | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 1%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 232       | 39.52%  |
| Intel                                  | 169       | 28.79%  |
| Qualcomm Atheros                       | 71        | 12.1%   |
| Broadcom                               | 36        | 6.13%   |
| Marvell Technology Group               | 24        | 4.09%   |
| ASIX Electronics                       | 18        | 3.07%   |
| Apple                                  | 9         | 1.53%   |
| Broadcom Limited                       | 5         | 0.85%   |
| Huawei Technologies                    | 4         | 0.68%   |
| Nvidia                                 | 3         | 0.51%   |
| Lenovo                                 | 3         | 0.51%   |
| Google                                 | 2         | 0.34%   |
| DisplayLink                            | 2         | 0.34%   |
| Xiaomi                                 | 1         | 0.17%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.17%   |
| Samsung Electronics                    | 1         | 0.17%   |
| QNAP System                            | 1         | 0.17%   |
| OPPO Electronics                       | 1         | 0.17%   |
| JMicron Technology                     | 1         | 0.17%   |
| ICS Advent                             | 1         | 0.17%   |
| Gemtek                                 | 1         | 0.17%   |
| Aquantia                               | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 155       | 25.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 42        | 7.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 33        | 5.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 30        | 5.02%   |
| Intel 82579V Gigabit Network Connection                                        | 22        | 3.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 20        | 3.34%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 16        | 2.68%   |
| Apple iBridge                                                                  | 9         | 1.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 8         | 1.34%   |
| Intel WiMAX Connection 2400m                                                   | 8         | 1.34%   |
| Intel Ethernet Connection (4) I219-V                                           | 8         | 1.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 7         | 1.17%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 1.17%   |
| Intel Ethernet Connection (10) I219-V                                          | 7         | 1.17%   |
| Intel 82577LC Gigabit Network Connection                                       | 7         | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 1%      |
| Intel Ethernet Connection I219-V                                               | 6         | 1%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 1%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 1%      |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 0.84%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.84%   |
| Intel Ethernet Connection I217-V                                               | 5         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 0.84%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 0.84%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 5         | 0.84%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 5         | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 4         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 0.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.67%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                          | 4         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 0.67%   |
| Huawei E353/E3131                                                              | 4         | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 665       | 54.07%  |
| Ethernet | 553       | 44.96%  |
| Unknown  | 9         | 0.73%   |
| Modem    | 3         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 498       | 69.07%  |
| Ethernet | 223       | 30.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 495       | 72.26%  |
| 1     | 175       | 25.55%  |
| 0     | 11        | 1.61%   |
| 3     | 4         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 509       | 72.51%  |
| Yes  | 193       | 27.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 222       | 49.89%  |
| Realtek Semiconductor           | 33        | 7.42%   |
| Qualcomm Atheros Communications | 30        | 6.74%   |
| Broadcom                        | 30        | 6.74%   |
| IMC Networks                    | 28        | 6.29%   |
| Apple                           | 20        | 4.49%   |
| Foxconn / Hon Hai               | 17        | 3.82%   |
| Cambridge Silicon Radio         | 17        | 3.82%   |
| Fujitsu                         | 8         | 1.8%    |
| Alps Electric                   | 7         | 1.57%   |
| Realtek                         | 6         | 1.35%   |
| Lite-On Technology              | 4         | 0.9%    |
| Hewlett-Packard                 | 4         | 0.9%    |
| ASUSTek Computer                | 4         | 0.9%    |
| Toshiba                         | 3         | 0.67%   |
| USI                             | 2         | 0.45%   |
| Ralink                          | 2         | 0.45%   |
| TP-Link                         | 1         | 0.22%   |
| Taiyo Yuden                     | 1         | 0.22%   |
| Ralink Technology               | 1         | 0.22%   |
| Opticis                         | 1         | 0.22%   |
| MediaTek                        | 1         | 0.22%   |
| Dell                            | 1         | 0.22%   |
| Askey Computer                  | 1         | 0.22%   |
| 8BitDo                          | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 66        | 14.83%  |
| Intel AX201 Bluetooth                                                               | 41        | 9.21%   |
| Intel Bluetooth Device                                                              | 33        | 7.42%   |
| Realtek Bluetooth Radio                                                             | 24        | 5.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 23        | 5.17%   |
| Intel AX200 Bluetooth                                                               | 22        | 4.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 17        | 3.82%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 2.7%    |
| Intel AX211 Bluetooth                                                               | 12        | 2.7%    |
| IMC Networks Bluetooth Radio                                                        | 11        | 2.47%   |
| Apple Bluetooth Host Controller                                                     | 11        | 2.47%   |
| Intel AX210 Bluetooth                                                               | 10        | 2.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 9         | 2.02%   |
| IMC Networks Wireless_Device                                                        | 8         | 1.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.57%   |
| Fujitsu Bluetooth Device                                                            | 7         | 1.57%   |
| Apple Bluetooth USB Host Controller                                                 | 7         | 1.57%   |
| Realtek Bluetooth Radio                                                             | 6         | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 1.35%   |
| IMC Networks Bluetooth Device                                                       | 6         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 0.9%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.9%    |
| Toshiba Atheros AR3012 Bluetooth                                                    | 3         | 0.67%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.67%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.67%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 0.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 0.67%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.67%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 3         | 0.67%   |
| USI Bluetooth Device                                                                | 2         | 0.45%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 0.45%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 563       | 70.82%  |
| AMD                                          | 113       | 14.21%  |
| Nvidia                                       | 63        | 7.92%   |
| Apple                                        | 17        | 2.14%   |
| C-Media Electronics                          | 10        | 1.26%   |
| Creative Technology                          | 4         | 0.5%    |
| Lenovo                                       | 3         | 0.38%   |
| Yamaha                                       | 2         | 0.25%   |
| VIA Technologies                             | 2         | 0.25%   |
| Elitegroup Computer Systems (ECS)            | 2         | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.13%   |
| Xiaomi                                       | 1         | 0.13%   |
| Sony                                         | 1         | 0.13%   |
| Roland                                       | 1         | 0.13%   |
| Realtek Semiconductor                        | 1         | 0.13%   |
| M2Tech                                       | 1         | 0.13%   |
| M-Audio                                      | 1         | 0.13%   |
| JMTek                                        | 1         | 0.13%   |
| JAVS                                         | 1         | 0.13%   |
| iCreate Technologies                         | 1         | 0.13%   |
| Corsair                                      | 1         | 0.13%   |
| CMX Systems                                  | 1         | 0.13%   |
| Cambridge Silicon Radio                      | 1         | 0.13%   |
| BY EDIFIER                                   | 1         | 0.13%   |
| Arturia                                      | 1         | 0.13%   |
| Unknown                                      | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 103       | 10.85%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 67        | 7.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 62        | 6.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 54        | 5.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 41        | 4.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 38        | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 34        | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 28        | 2.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 26        | 2.74%   |
| Intel Broadwell-U Audio Controller                                                                | 26        | 2.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21        | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 2.11%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 2.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 2%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 2%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 1.9%    |
| Apple Audio Device                                                                                | 17        | 1.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 1.58%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 1.58%   |
| AMD FCH Azalia Controller                                                                         | 14        | 1.48%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.26%   |
| Nvidia Audio device                                                                               | 12        | 1.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 11        | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.16%   |
| Intel Smart Sound Technology Audio Controller                                                     | 10        | 1.05%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 10        | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 6         | 0.63%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 6         | 0.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.63%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 6         | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.42%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 148       | 31.09%  |
| SK hynix            | 95        | 19.96%  |
| Micron Technology   | 65        | 13.66%  |
| Unknown             | 50        | 10.5%   |
| Kingston            | 19        | 3.99%   |
| Crucial             | 15        | 3.15%   |
| Elpida              | 11        | 2.31%   |
| Nanya Technology    | 8         | 1.68%   |
| Ramaxel Technology  | 7         | 1.47%   |
| A-DATA Technology   | 7         | 1.47%   |
| Unknown (ABCD)      | 6         | 1.26%   |
| Unknown             | 6         | 1.26%   |
| SanMax              | 5         | 1.05%   |
| Team                | 4         | 0.84%   |
| Silicon Power       | 4         | 0.84%   |
| Transcend           | 3         | 0.63%   |
| Toshiba             | 2         | 0.42%   |
| Patriot             | 2         | 0.42%   |
| Corsair             | 2         | 0.42%   |
| CFD                 | 2         | 0.42%   |
| ASint Technology    | 2         | 0.42%   |
| Unknown (0xD306)    | 1         | 0.21%   |
| Unknown (08C8)      | 1         | 0.21%   |
| SHARETRONIC         | 1         | 0.21%   |
| Neo Forza           | 1         | 0.21%   |
| Melco               | 1         | 0.21%   |
| Lexar               | 1         | 0.21%   |
| KLEVV               | 1         | 0.21%   |
| Goldkey             | 1         | 0.21%   |
| G.Skill             | 1         | 0.21%   |
| EUDAR               | 1         | 0.21%   |
| Essencore           | 1         | 0.21%   |
| ChangXin Memory     | 1         | 0.21%   |
| Advantech           | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 25        | 4.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.58%   |
| Micron RAM MT53E512M64D4NW-053 4GB Row Of Chips LPDDR4 3733MT/s  | 8         | 1.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.18%   |
| Unknown                                                          | 6         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 5         | 0.99%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 4         | 0.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.79%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 4         | 0.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.79%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.79%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                       | 3         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 3         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.59%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.59%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.59%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 0.59%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s         | 3         | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.59%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 3         | 0.59%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.59%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 3         | 0.59%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.39%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 2         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.39%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 2         | 0.39%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s             | 2         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 169       | 40.92%  |
| DDR4    | 131       | 31.72%  |
| LPDDR4  | 26        | 6.3%    |
| LPDDR3  | 26        | 6.3%    |
| DDR2    | 26        | 6.3%    |
| SDRAM   | 11        | 2.66%   |
| LPDDR5  | 10        | 2.42%   |
| DDR5    | 7         | 1.69%   |
| Unknown | 5         | 1.21%   |
| DRAM    | 1         | 0.24%   |
| DDR     | 1         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 348       | 84.26%  |
| Row Of Chips | 52        | 12.59%  |
| Unknown      | 5         | 1.21%   |
| DIMM         | 4         | 0.97%   |
| Chip         | 4         | 0.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 165       | 37%     |
| 8192  | 141       | 31.61%  |
| 2048  | 68        | 15.25%  |
| 16384 | 45        | 10.09%  |
| 1024  | 13        | 2.91%   |
| 32768 | 12        | 2.69%   |
| 512   | 1         | 0.22%   |
| 256   | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 131       | 29.71%  |
| 3200    | 62        | 14.06%  |
| 2667    | 53        | 12.02%  |
| 2400    | 28        | 6.35%   |
| 1334    | 26        | 5.9%    |
| 2133    | 23        | 5.22%   |
| 1067    | 14        | 3.17%   |
| 4199    | 10        | 2.27%   |
| 3733    | 10        | 2.27%   |
| 1333    | 10        | 2.27%   |
| 6400    | 9         | 2.04%   |
| 667     | 8         | 1.81%   |
| Unknown | 8         | 1.81%   |
| 1066    | 7         | 1.59%   |
| 4800    | 6         | 1.36%   |
| 4267    | 6         | 1.36%   |
| 1867    | 5         | 1.13%   |
| 975     | 3         | 0.68%   |
| 800     | 3         | 0.68%   |
| 533     | 3         | 0.68%   |
| 333     | 3         | 0.68%   |
| 5600    | 2         | 0.45%   |
| 3266    | 2         | 0.45%   |
| 1866    | 2         | 0.45%   |
| 400     | 2         | 0.45%   |
| 7500    | 1         | 0.23%   |
| 4266    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 266     | 1         | 0.23%   |
| 100     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 25%     |
| Samsung Electronics | 1         | 25%     |
| Canon               | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson WF-2010 Series | 1         | 25%     |
| Samsung SCX-3200 Series    | 1         | 25%     |
| Canon PIXMA MG3600 Series  | 1         | 25%     |
| Brother HL-2130 series     | 1         | 25%     |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 116       | 25.72%  |
| IMC Networks                           | 46        | 10.2%   |
| Microdia                               | 37        | 8.2%    |
| Bison Electronics                      | 29        | 6.43%   |
| Sunplus Innovation Technology          | 27        | 5.99%   |
| Realtek Semiconductor                  | 27        | 5.99%   |
| Acer                                   | 25        | 5.54%   |
| Apple                                  | 22        | 4.88%   |
| Quanta                                 | 18        | 3.99%   |
| Suyin                                  | 15        | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 3.1%    |
| Syntek                                 | 9         | 2%      |
| Luxvisions Innotech Limited            | 8         | 1.77%   |
| Alcor Micro                            | 7         | 1.55%   |
| Ricoh                                  | 6         | 1.33%   |
| Importek                               | 6         | 1.33%   |
| Silicon Motion                         | 5         | 1.11%   |
| Lite-On Technology                     | 5         | 1.11%   |
| BUFFALO                                | 5         | 1.11%   |
| Sonix Technology                       | 4         | 0.89%   |
| Logitech                               | 3         | 0.67%   |
| Genesys Logic                          | 3         | 0.67%   |
| Samsung Electronics                    | 2         | 0.44%   |
| Lenovo                                 | 2         | 0.44%   |
| Z-Star Microelectronics                | 1         | 0.22%   |
| SunplusIT                              | 1         | 0.22%   |
| Sunplus Technology                     | 1         | 0.22%   |
| Primax Electronics                     | 1         | 0.22%   |
| Omnivision                             | 1         | 0.22%   |
| Oculus VR                              | 1         | 0.22%   |
| Intel                                  | 1         | 0.22%   |
| Etron Technology                       | 1         | 0.22%   |
| Cubeternet                             | 1         | 0.22%   |
| 2M UVC CAMERA                          | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 20        | 4.42%   |
| Microdia Integrated_Webcam_HD                           | 18        | 3.97%   |
| IMC Networks Integrated Camera                          | 17        | 3.75%   |
| Chicony FJ Camera                                       | 14        | 3.09%   |
| Realtek Integrated_Webcam_HD                            | 13        | 2.87%   |
| Apple FaceTime HD Camera (Built-in)                     | 9         | 1.99%   |
| Chicony USB2.0 Camera                                   | 8         | 1.77%   |
| Chicony TOSHIBA Web Camera - HD                         | 7         | 1.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 6         | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 6         | 1.32%   |
| Apple FaceTime HD Camera                                | 6         | 1.32%   |
| Acer USB HD Webcam                                      | 6         | 1.32%   |
| BUFFALO USB 2.0 Camera                                  | 5         | 1.1%    |
| Bison Integrated Camera                                 | 5         | 1.1%    |
| Acer Integrated Camera                                  | 5         | 1.1%    |
| Sunplus Integrated_Webcam_HD                            | 4         | 0.88%   |
| Sunplus HD WebCam                                       | 4         | 0.88%   |
| Quanta HD User Facing                                   | 4         | 0.88%   |
| Microdia USB 2.0 Camera                                 | 4         | 0.88%   |
| Lite-On Integrated Camera                               | 4         | 0.88%   |
| IMC Networks ov9734_azurewave_camera                    | 4         | 0.88%   |
| Chicony Lenovo EasyCamera                               | 4         | 0.88%   |
| Chicony HP HD Camera                                    | 4         | 0.88%   |
| Chicony HD WebCam                                       | 4         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 4         | 0.88%   |
| Bison ThinkPad Integrated Camera                        | 4         | 0.88%   |
| Bison HD Webcam                                         | 4         | 0.88%   |
| Acer Lenovo EasyCamera                                  | 4         | 0.88%   |
| Syntek Lenovo EasyCamera                                | 3         | 0.66%   |
| Syntek Integrated Camera                                | 3         | 0.66%   |
| Suyin HP Webcam                                         | 3         | 0.66%   |
| Sunplus Integrated_Webcam_FHD                           | 3         | 0.66%   |
| Sunplus Dell HD Webcam                                  | 3         | 0.66%   |
| Realtek Lenovo EasyCamera                               | 3         | 0.66%   |
| Quanta HP TrueVision HD Camera                          | 3         | 0.66%   |
| Microdia Integrated Webcam HD                           | 3         | 0.66%   |
| Luxvisions Innotech Limited Integrated Camera           | 3         | 0.66%   |
| Importek TOSHIBA Web Camera - HD                        | 3         | 0.66%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 0.66%   |
| Chicony TOSHIBA Web Camera - FHD                        | 3         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 35        | 28.93%  |
| Synaptics                          | 21        | 17.36%  |
| Shenzhen Goodix Technology         | 18        | 14.88%  |
| AuthenTec                          | 18        | 14.88%  |
| Upek                               | 10        | 8.26%   |
| Elan Microelectronics              | 6         | 4.96%   |
| STMicroelectronics                 | 5         | 4.13%   |
| LighTuning Technology              | 5         | 4.13%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.65%   |
| Focal-systems.Corp                 | 1         | 0.83%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 11        | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                             | 9         | 7.44%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 7         | 5.79%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 7         | 5.79%   |
| Shenzhen Goodix Fingerprint Reader                              | 7         | 5.79%   |
| AuthenTec Fingerprint Sensor                                    | 6         | 4.96%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 4.13%   |
| STMicroelectronics Fingerprint Reader                           | 5         | 4.13%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 4         | 3.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 4         | 3.31%   |
| Elan ELAN:ARM-M4                                                | 4         | 3.31%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 4         | 3.31%   |
| Validity Sensors VFS491                                         | 3         | 2.48%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 2.48%   |
| Upek TCS5B Fingerprint sensor                                   | 3         | 2.48%   |
| AuthenTec AES2810                                               | 3         | 2.48%   |
| AuthenTec AES1600                                               | 3         | 2.48%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 2         | 1.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 1.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 1.65%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 1.65%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 1.65%   |
| Synaptics UWP WBDI Device                                       | 2         | 1.65%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 1.65%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 1.65%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 1.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 2         | 1.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 1.65%   |
| Elan ELAN:Fingerprint                                           | 2         | 1.65%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 0.83%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 0.83%   |
| Validity Sensors Fingerprint scanner                            | 1         | 0.83%   |
| Synaptics WBDI Device                                           | 1         | 0.83%   |
| LighTuning Fingerprint Reader                                   | 1         | 0.83%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 0.83%   |
| AuthenTec AES2660 Fingerprint Sensor                            | 1         | 0.83%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 0.83%   |
| Unknown                                                         | 1         | 0.83%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 34.48%  |
| Upek        | 9         | 31.03%  |
| Alcor Micro | 6         | 20.69%  |
| O2 Micro    | 4         | 13.79%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 31.03%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 20.69%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 13.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 13.79%  |
| Broadcom 58200                                                               | 3         | 10.34%  |
| Broadcom 5880                                                                | 2         | 6.9%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 439       | 62.89%  |
| 1     | 217       | 31.09%  |
| 2     | 32        | 4.58%   |
| 3     | 8         | 1.15%   |
| 6     | 2         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 119       | 38.51%  |
| Graphics card            | 54        | 17.48%  |
| Chipcard                 | 28        | 9.06%   |
| Net/wireless             | 27        | 8.74%   |
| Multimedia controller    | 24        | 7.77%   |
| Storage                  | 16        | 5.18%   |
| Communication controller | 9         | 2.91%   |
| Sound                    | 8         | 2.59%   |
| Camera                   | 7         | 2.27%   |
| Bluetooth                | 7         | 2.27%   |
| Network                  | 3         | 0.97%   |
| Storage/ata              | 2         | 0.65%   |
| Net/ethernet             | 2         | 0.65%   |
| Modem                    | 2         | 0.65%   |
| Tv card                  | 1         | 0.32%   |

