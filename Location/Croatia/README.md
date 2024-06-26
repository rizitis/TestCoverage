Linux in Croatia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Croatia/Desktop/README.md) and [notebooks](/Location/Croatia/Notebook/README.md).

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

Total: 846

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [ed064c4025](https://linux-hardware.org/?probe=ed064c4025) | May 08, 2024 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [5b40331b05](https://linux-hardware.org/?probe=5b40331b05) | May 03, 2024 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [440bf944f3](https://linux-hardware.org/?probe=440bf944f3) | May 03, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [23c1b45346](https://linux-hardware.org/?probe=23c1b45346) | May 02, 2024 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fcd6ae5579](https://linux-hardware.org/?probe=fcd6ae5579) | May 02, 2024 |
| HP            | 1496                        | Desktop     | [64f726b9c5](https://linux-hardware.org/?probe=64f726b9c5) | Apr 30, 2024 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [886328abc3](https://linux-hardware.org/?probe=886328abc3) | Apr 25, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [0b8cd1192f](https://linux-hardware.org/?probe=0b8cd1192f) | Apr 24, 2024 |
| HP            | 8876 11                     | Desktop     | [b15b96ee62](https://linux-hardware.org/?probe=b15b96ee62) | Apr 23, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [3ac4d133b8](https://linux-hardware.org/?probe=3ac4d133b8) | Apr 23, 2024 |
| Tactus        | GeoBook 140                 | Notebook    | [aa4d027e01](https://linux-hardware.org/?probe=aa4d027e01) | Apr 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f7ab9249b4](https://linux-hardware.org/?probe=f7ab9249b4) | Apr 11, 2024 |
| Dell          | 06JWJY A01                  | Desktop     | [824cb2807f](https://linux-hardware.org/?probe=824cb2807f) | Apr 11, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [1d9ef42930](https://linux-hardware.org/?probe=1d9ef42930) | Apr 11, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [ee70d25db0](https://linux-hardware.org/?probe=ee70d25db0) | Apr 04, 2024 |
| HP            | 1495                        | Desktop     | [7bb71cc6c8](https://linux-hardware.org/?probe=7bb71cc6c8) | Apr 03, 2024 |
| HP            | 1495                        | Desktop     | [369904b953](https://linux-hardware.org/?probe=369904b953) | Apr 03, 2024 |
| Tactus        | GeoBook 140                 | Notebook    | [9e26c5ce44](https://linux-hardware.org/?probe=9e26c5ce44) | Apr 02, 2024 |
| HP            | Notebook                    | Notebook    | [af4830976e](https://linux-hardware.org/?probe=af4830976e) | Apr 01, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [f1a4abd6dc](https://linux-hardware.org/?probe=f1a4abd6dc) | Mar 31, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [000b3bdea6](https://linux-hardware.org/?probe=000b3bdea6) | Mar 29, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [d3533da3cc](https://linux-hardware.org/?probe=d3533da3cc) | Mar 25, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | Desktop     | [74e95f0015](https://linux-hardware.org/?probe=74e95f0015) | Mar 24, 2024 |
| HP            | ZBook 17                    | Notebook    | [02d8d9dcf1](https://linux-hardware.org/?probe=02d8d9dcf1) | Mar 23, 2024 |
| HP            | 83EF                        | Desktop     | [34c1c23a84](https://linux-hardware.org/?probe=34c1c23a84) | Mar 23, 2024 |
| Acer          | Aspire A515-47              | Notebook    | [e23d4b05d8](https://linux-hardware.org/?probe=e23d4b05d8) | Mar 19, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [74a0af3ace](https://linux-hardware.org/?probe=74a0af3ace) | Mar 19, 2024 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [fac66be915](https://linux-hardware.org/?probe=fac66be915) | Mar 19, 2024 |
| HP            | ProBook 470 G3              | Notebook    | [7acbeb9e50](https://linux-hardware.org/?probe=7acbeb9e50) | Mar 12, 2024 |
| Dell          | System XPS L702X            | Notebook    | [09313dcc56](https://linux-hardware.org/?probe=09313dcc56) | Mar 11, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [67978c3e25](https://linux-hardware.org/?probe=67978c3e25) | Mar 10, 2024 |
| HP            | ZBook 17                    | Notebook    | [9535fdaf2b](https://linux-hardware.org/?probe=9535fdaf2b) | Mar 10, 2024 |
| HP            | Laptop 17-bs0xx             | Notebook    | [019d8a8d68](https://linux-hardware.org/?probe=019d8a8d68) | Mar 01, 2024 |
| HP            | ProLiant DL165 G7           | Server      | [8850a77792](https://linux-hardware.org/?probe=8850a77792) | Feb 27, 2024 |
| Lenovo        | ThinkPad T530 2429AL0       | Notebook    | [6040b9b7e2](https://linux-hardware.org/?probe=6040b9b7e2) | Feb 24, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [8173a2268e](https://linux-hardware.org/?probe=8173a2268e) | Feb 24, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [d91a07c2e1](https://linux-hardware.org/?probe=d91a07c2e1) | Feb 22, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [4e64450aa5](https://linux-hardware.org/?probe=4e64450aa5) | Feb 21, 2024 |
| Dell          | Latitude D530               | Notebook    | [0885268edd](https://linux-hardware.org/?probe=0885268edd) | Feb 20, 2024 |
| Dell          | Latitude D530               | Notebook    | [e4d1a73b6e](https://linux-hardware.org/?probe=e4d1a73b6e) | Feb 20, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [91f2211c0c](https://linux-hardware.org/?probe=91f2211c0c) | Feb 14, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [1982f26149](https://linux-hardware.org/?probe=1982f26149) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d83aac3c35](https://linux-hardware.org/?probe=d83aac3c35) | Feb 11, 2024 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | Notebook    | [f1ffdd8987](https://linux-hardware.org/?probe=f1ffdd8987) | Feb 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [d916f30fdc](https://linux-hardware.org/?probe=d916f30fdc) | Feb 10, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [5c94c6fba5](https://linux-hardware.org/?probe=5c94c6fba5) | Feb 07, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [bf2ce0efeb](https://linux-hardware.org/?probe=bf2ce0efeb) | Jan 15, 2024 |
| Acer          | Swift SFG14-42              | Notebook    | [15da646623](https://linux-hardware.org/?probe=15da646623) | Jan 11, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [80799f979c](https://linux-hardware.org/?probe=80799f979c) | Jan 10, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [7013d64a90](https://linux-hardware.org/?probe=7013d64a90) | Jan 09, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [2b8bf09bd1](https://linux-hardware.org/?probe=2b8bf09bd1) | Jan 08, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [2a29a6c24b](https://linux-hardware.org/?probe=2a29a6c24b) | Jan 08, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [810f81c66e](https://linux-hardware.org/?probe=810f81c66e) | Jan 06, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ff9686f03c](https://linux-hardware.org/?probe=ff9686f03c) | Jan 06, 2024 |
| Dynabook      | Satellite Pro C40-G-109     | Notebook    | [0247395541](https://linux-hardware.org/?probe=0247395541) | Jan 05, 2024 |
| Unknown       | Apple MacBook Air (13-in... | Notebook    | [834855dcac](https://linux-hardware.org/?probe=834855dcac) | Jan 01, 2024 |
| HP            | Pavilion dv7                | Notebook    | [4b1ea284d3](https://linux-hardware.org/?probe=4b1ea284d3) | Dec 28, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [7a9ff71d9b](https://linux-hardware.org/?probe=7a9ff71d9b) | Dec 28, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [58bbd67a73](https://linux-hardware.org/?probe=58bbd67a73) | Dec 23, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [d9850a7566](https://linux-hardware.org/?probe=d9850a7566) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [656732b40e](https://linux-hardware.org/?probe=656732b40e) | Dec 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [367489ed4f](https://linux-hardware.org/?probe=367489ed4f) | Dec 10, 2023 |
| eMachines     | ET1850                      | Desktop     | [b433ca3cfa](https://linux-hardware.org/?probe=b433ca3cfa) | Dec 02, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| eMachines     | E725 V1.03                  | Notebook    | [bd5b32a320](https://linux-hardware.org/?probe=bd5b32a320) | Nov 20, 2023 |
| eMachines     | E725 V1.03                  | Notebook    | [bd29f2ff41](https://linux-hardware.org/?probe=bd29f2ff41) | Nov 19, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [2a9ba6fc77](https://linux-hardware.org/?probe=2a9ba6fc77) | Nov 17, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [9b2d42ff24](https://linux-hardware.org/?probe=9b2d42ff24) | Nov 15, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [f5413c3dd5](https://linux-hardware.org/?probe=f5413c3dd5) | Nov 15, 2023 |
| HP            | 18E4                        | Desktop     | [fb73ea4228](https://linux-hardware.org/?probe=fb73ea4228) | Nov 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [982139b13a](https://linux-hardware.org/?probe=982139b13a) | Nov 11, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [4fd542edf2](https://linux-hardware.org/?probe=4fd542edf2) | Nov 11, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c019f410aa](https://linux-hardware.org/?probe=c019f410aa) | Nov 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [4bfe797838](https://linux-hardware.org/?probe=4bfe797838) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [4b04b9ef25](https://linux-hardware.org/?probe=4b04b9ef25) | Nov 02, 2023 |
| Acer          | AOD270                      | Notebook    | [83c4a5920f](https://linux-hardware.org/?probe=83c4a5920f) | Oct 29, 2023 |
| Lenovo        | ThinkPad T450s 20BWS58K0... | Notebook    | [11b2f76301](https://linux-hardware.org/?probe=11b2f76301) | Oct 29, 2023 |
| HP            | Presario CQ57               | Notebook    | [f35a975672](https://linux-hardware.org/?probe=f35a975672) | Oct 29, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [bd82dd57be](https://linux-hardware.org/?probe=bd82dd57be) | Oct 27, 2023 |
| Intel         | NUC7i7BNB J31145-303        | Mini pc     | [8b6a0fb21d](https://linux-hardware.org/?probe=8b6a0fb21d) | Oct 25, 2023 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [24304767eb](https://linux-hardware.org/?probe=24304767eb) | Oct 21, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [deeaf6af5b](https://linux-hardware.org/?probe=deeaf6af5b) | Oct 19, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [c8f55c449a](https://linux-hardware.org/?probe=c8f55c449a) | Oct 19, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [0e6cc9fc48](https://linux-hardware.org/?probe=0e6cc9fc48) | Oct 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [6c49286a6c](https://linux-hardware.org/?probe=6c49286a6c) | Oct 14, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bf88efbfff](https://linux-hardware.org/?probe=bf88efbfff) | Oct 05, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [e0158c541c](https://linux-hardware.org/?probe=e0158c541c) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [7975260826](https://linux-hardware.org/?probe=7975260826) | Sep 29, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [fac9ee2e6e](https://linux-hardware.org/?probe=fac9ee2e6e) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0e32901b18](https://linux-hardware.org/?probe=0e32901b18) | Sep 27, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [bd389fb2a0](https://linux-hardware.org/?probe=bd389fb2a0) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | Desktop     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [c833e40c97](https://linux-hardware.org/?probe=c833e40c97) | Sep 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ba837274bd](https://linux-hardware.org/?probe=ba837274bd) | Sep 01, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [294343383a](https://linux-hardware.org/?probe=294343383a) | Aug 30, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [adba295596](https://linux-hardware.org/?probe=adba295596) | Aug 30, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4bc3ed94ce](https://linux-hardware.org/?probe=4bc3ed94ce) | Aug 28, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| ASRock        | B560 Steel Legend           | Desktop     | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1f6e4f9676](https://linux-hardware.org/?probe=1f6e4f9676) | Aug 21, 2023 |
| Lenovo        | ThinkPad T495s 20QJ001MG... | Notebook    | [3ac30cf2d0](https://linux-hardware.org/?probe=3ac30cf2d0) | Aug 16, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [73b7fc1fc9](https://linux-hardware.org/?probe=73b7fc1fc9) | Aug 11, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [c7724d9c7c](https://linux-hardware.org/?probe=c7724d9c7c) | Aug 02, 2023 |
| HP            | 2B47                        | Desktop     | [06373794be](https://linux-hardware.org/?probe=06373794be) | Aug 01, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| Dell          | Latitude 5520               | Notebook    | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [043258de54](https://linux-hardware.org/?probe=043258de54) | Jul 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Dell          | OptiPlex 9020               | Notebook    | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Timi          | TM1701                      | Notebook    | [5dee3c6b81](https://linux-hardware.org/?probe=5dee3c6b81) | Jul 01, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8f6d75c75e](https://linux-hardware.org/?probe=8f6d75c75e) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [289d9fe165](https://linux-hardware.org/?probe=289d9fe165) | Jun 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [18e80281cc](https://linux-hardware.org/?probe=18e80281cc) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [f7bd03dbb9](https://linux-hardware.org/?probe=f7bd03dbb9) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [bf403bb6d8](https://linux-hardware.org/?probe=bf403bb6d8) | Jun 06, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [3272ba5e49](https://linux-hardware.org/?probe=3272ba5e49) | May 19, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [cd65f81693](https://linux-hardware.org/?probe=cd65f81693) | May 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [5312325c90](https://linux-hardware.org/?probe=5312325c90) | May 10, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | Notebook    | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| HPE           | ProLiant ML30 Gen10 Plus    | Desktop     | [3a75fa5c03](https://linux-hardware.org/?probe=3a75fa5c03) | May 07, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [efb597952f](https://linux-hardware.org/?probe=efb597952f) | May 07, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1c98821416](https://linux-hardware.org/?probe=1c98821416) | May 03, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [e74d115d0d](https://linux-hardware.org/?probe=e74d115d0d) | Apr 29, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [5cb9fe1ae9](https://linux-hardware.org/?probe=5cb9fe1ae9) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [3669ef1de9](https://linux-hardware.org/?probe=3669ef1de9) | Apr 28, 2023 |
| Lenovo        | 3000 N200 0769A97           | Notebook    | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [0db2c54b2a](https://linux-hardware.org/?probe=0db2c54b2a) | Apr 24, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [b3c9b78fec](https://linux-hardware.org/?probe=b3c9b78fec) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [64f96c6fde](https://linux-hardware.org/?probe=64f96c6fde) | Apr 07, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [171e39cdb6](https://linux-hardware.org/?probe=171e39cdb6) | Apr 05, 2023 |
| Dell          | Latitude 5530               | Notebook    | [802248e232](https://linux-hardware.org/?probe=802248e232) | Apr 03, 2023 |
| Intel         | NUC11PABi3 M68269-400       | Mini pc     | [7c7fdc5950](https://linux-hardware.org/?probe=7c7fdc5950) | Apr 02, 2023 |
| Dell          | Latitude 5530               | Notebook    | [e4688e2ef8](https://linux-hardware.org/?probe=e4688e2ef8) | Apr 01, 2023 |
| HP            | 82DC 1100                   | All in one  | [4c1c2f908b](https://linux-hardware.org/?probe=4c1c2f908b) | Mar 30, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [b8e3d627b5](https://linux-hardware.org/?probe=b8e3d627b5) | Mar 27, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [5efd6f0674](https://linux-hardware.org/?probe=5efd6f0674) | Mar 20, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| Supermicro    | X8DTU                       | Server      | [6012de6351](https://linux-hardware.org/?probe=6012de6351) | Mar 10, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [2409dc15b4](https://linux-hardware.org/?probe=2409dc15b4) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | Notebook    | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| Dell          | OptiPlex 9020               | Notebook    | [dda13d9c8e](https://linux-hardware.org/?probe=dda13d9c8e) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [e2f06dcb4a](https://linux-hardware.org/?probe=e2f06dcb4a) | Feb 24, 2023 |
| Dell          | System XPS L702X            | Notebook    | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [1d5a0bc43f](https://linux-hardware.org/?probe=1d5a0bc43f) | Feb 14, 2023 |
| Lenovo        | ThinkPad T540p 20BFA183A... | Notebook    | [2705e3d0c5](https://linux-hardware.org/?probe=2705e3d0c5) | Feb 12, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e574477cb6](https://linux-hardware.org/?probe=e574477cb6) | Feb 07, 2023 |
| MSI           | 0A90                        | Desktop     | [9210981559](https://linux-hardware.org/?probe=9210981559) | Feb 06, 2023 |
| MSI           | 0A90                        | Desktop     | [aedd414dbf](https://linux-hardware.org/?probe=aedd414dbf) | Feb 06, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9f76193ccc](https://linux-hardware.org/?probe=9f76193ccc) | Jan 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [76689345ef](https://linux-hardware.org/?probe=76689345ef) | Jan 19, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [478f5dc5cb](https://linux-hardware.org/?probe=478f5dc5cb) | Jan 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [29ff669f2c](https://linux-hardware.org/?probe=29ff669f2c) | Jan 14, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [2b04043ef0](https://linux-hardware.org/?probe=2b04043ef0) | Jan 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ef10fbe492](https://linux-hardware.org/?probe=ef10fbe492) | Jan 09, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| Samsung       | SBB-DA                      | Notebook    | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [800f20e309](https://linux-hardware.org/?probe=800f20e309) | Jan 07, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [066ab1d6a3](https://linux-hardware.org/?probe=066ab1d6a3) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [f6de50a76b](https://linux-hardware.org/?probe=f6de50a76b) | Jan 04, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e703dd0215](https://linux-hardware.org/?probe=e703dd0215) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [3ba1d0e689](https://linux-hardware.org/?probe=3ba1d0e689) | Jan 03, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d88df3fcee](https://linux-hardware.org/?probe=d88df3fcee) | Jan 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [b2b93008c3](https://linux-hardware.org/?probe=b2b93008c3) | Dec 17, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [b73060ce38](https://linux-hardware.org/?probe=b73060ce38) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [d632edc927](https://linux-hardware.org/?probe=d632edc927) | Dec 05, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [412bffea3b](https://linux-hardware.org/?probe=412bffea3b) | Dec 05, 2022 |
| ASRock        | K10N78D                     | Desktop     | [b5e2e7a024](https://linux-hardware.org/?probe=b5e2e7a024) | Dec 02, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [e904ef7a24](https://linux-hardware.org/?probe=e904ef7a24) | Nov 26, 2022 |
| ASUSTek       | X550LB                      | Notebook    | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | Notebook    | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | Notebook    | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [01381d41de](https://linux-hardware.org/?probe=01381d41de) | Nov 03, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [b3cac9f8b8](https://linux-hardware.org/?probe=b3cac9f8b8) | Nov 02, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [41a93c4dfa](https://linux-hardware.org/?probe=41a93c4dfa) | Nov 02, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| Dell          | Studio 1735                 | Notebook    | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [24b035a7a4](https://linux-hardware.org/?probe=24b035a7a4) | Oct 25, 2022 |
| Dell          | Studio 1735                 | Notebook    | [21959a7db7](https://linux-hardware.org/?probe=21959a7db7) | Oct 24, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d178c463df](https://linux-hardware.org/?probe=d178c463df) | Oct 24, 2022 |
| Dell          | Studio 1735                 | Notebook    | [4385640990](https://linux-hardware.org/?probe=4385640990) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [04fed978ae](https://linux-hardware.org/?probe=04fed978ae) | Oct 18, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | Notebook    | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| Acer          | Aspire A317-53              | Notebook    | [dadf436fd1](https://linux-hardware.org/?probe=dadf436fd1) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [3f2cdff8d4](https://linux-hardware.org/?probe=3f2cdff8d4) | Oct 05, 2022 |
| Toshiba       | Encore                      | Notebook    | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [0dca3e500c](https://linux-hardware.org/?probe=0dca3e500c) | Sep 22, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [64dc493d4d](https://linux-hardware.org/?probe=64dc493d4d) | Sep 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [581356206a](https://linux-hardware.org/?probe=581356206a) | Sep 17, 2022 |
| Dell          | Latitude 5420               | Notebook    | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [583489891f](https://linux-hardware.org/?probe=583489891f) | Sep 06, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [9543920c45](https://linux-hardware.org/?probe=9543920c45) | Sep 04, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [b6d4d6bca2](https://linux-hardware.org/?probe=b6d4d6bca2) | Sep 04, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0e4eab04c0](https://linux-hardware.org/?probe=0e4eab04c0) | Aug 27, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [65e832cb2f](https://linux-hardware.org/?probe=65e832cb2f) | Aug 27, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5ddb15f201](https://linux-hardware.org/?probe=5ddb15f201) | Aug 07, 2022 |
| Acer          | Aspire A515-56G             | Notebook    | [3df2b6b19b](https://linux-hardware.org/?probe=3df2b6b19b) | Aug 05, 2022 |
| HP            | 1825                        | Desktop     | [4a21a02ae4](https://linux-hardware.org/?probe=4a21a02ae4) | Jul 29, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [3c665fb25f](https://linux-hardware.org/?probe=3c665fb25f) | Jul 28, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | Notebook    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [6886cd26f5](https://linux-hardware.org/?probe=6886cd26f5) | Jul 20, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [17cdd0291e](https://linux-hardware.org/?probe=17cdd0291e) | Jul 12, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4de601fe45](https://linux-hardware.org/?probe=4de601fe45) | Jul 12, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [4bd18943fb](https://linux-hardware.org/?probe=4bd18943fb) | Jul 09, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [3da162d001](https://linux-hardware.org/?probe=3da162d001) | Jul 09, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [36305f7936](https://linux-hardware.org/?probe=36305f7936) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | Notebook    | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6d9101e2d2](https://linux-hardware.org/?probe=6d9101e2d2) | Jul 08, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [36c7cff92d](https://linux-hardware.org/?probe=36c7cff92d) | Jul 07, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| ASRock        | K10N78D                     | Desktop     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [bfe2aed3aa](https://linux-hardware.org/?probe=bfe2aed3aa) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| WinFast       | NF-MCP55 FAB1.0             | Desktop     | [bb066cc2da](https://linux-hardware.org/?probe=bb066cc2da) | Jul 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82ca4386ae](https://linux-hardware.org/?probe=82ca4386ae) | Jun 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [42462e221b](https://linux-hardware.org/?probe=42462e221b) | Jun 29, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [160062e69a](https://linux-hardware.org/?probe=160062e69a) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [45c9b081c5](https://linux-hardware.org/?probe=45c9b081c5) | Jun 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [96c4f21509](https://linux-hardware.org/?probe=96c4f21509) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ba5ab976e2](https://linux-hardware.org/?probe=ba5ab976e2) | Jun 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [d2b608c230](https://linux-hardware.org/?probe=d2b608c230) | Jun 16, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0d4266a0f3](https://linux-hardware.org/?probe=0d4266a0f3) | Jun 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [1f92039342](https://linux-hardware.org/?probe=1f92039342) | Jun 02, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [dbbe7457ff](https://linux-hardware.org/?probe=dbbe7457ff) | May 31, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [a9c593dd0b](https://linux-hardware.org/?probe=a9c593dd0b) | May 31, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [987ef7b2e7](https://linux-hardware.org/?probe=987ef7b2e7) | May 26, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [9dff398fa9](https://linux-hardware.org/?probe=9dff398fa9) | May 24, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| eMachines     | E525                        | Notebook    | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | Notebook    | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [2953148fae](https://linux-hardware.org/?probe=2953148fae) | May 16, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| Dell          | 0J37VM A01                  | Desktop     | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
| Lenovo        | 3746 No DPK                 | All in one  | [910612b856](https://linux-hardware.org/?probe=910612b856) | May 07, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X540UA                      | Notebook    | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [bc333fe437](https://linux-hardware.org/?probe=bc333fe437) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Intel         | H61M-S2PV                   | Desktop     | [caa602b556](https://linux-hardware.org/?probe=caa602b556) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Razer         | Blade                       | Notebook    | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | Desktop     | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [84978cfba3](https://linux-hardware.org/?probe=84978cfba3) | Apr 17, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [e970f67c93](https://linux-hardware.org/?probe=e970f67c93) | Apr 13, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| Dell          | OptiPlex 9020               | Notebook    | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [d7d4ac2b9a](https://linux-hardware.org/?probe=d7d4ac2b9a) | Apr 04, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [f9ab989993](https://linux-hardware.org/?probe=f9ab989993) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | Notebook    | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | Notebook    | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| HP            | ProBook 4530s               | Notebook    | [061de41ec5](https://linux-hardware.org/?probe=061de41ec5) | Mar 13, 2022 |
| Toshiba       | Satellite C850-1GD          | Notebook    | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| ASRock        | B360 Gaming K4              | Desktop     | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ed3d7239af](https://linux-hardware.org/?probe=ed3d7239af) | Mar 09, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [d0ee45a4b1](https://linux-hardware.org/?probe=d0ee45a4b1) | Feb 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a93fdb0cc8](https://linux-hardware.org/?probe=a93fdb0cc8) | Feb 25, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [37c0889ae6](https://linux-hardware.org/?probe=37c0889ae6) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [57a0f33a96](https://linux-hardware.org/?probe=57a0f33a96) | Feb 23, 2022 |
| HP            | 2140                        | Notebook    | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | Notebook    | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | Notebook    | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                    | Desktop     | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [980b14c09a](https://linux-hardware.org/?probe=980b14c09a) | Feb 11, 2022 |
| Acer          | Aspire 7739G                | Notebook    | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| HP            | 82DC 1100                   | All in one  | [e3a85b9aaf](https://linux-hardware.org/?probe=e3a85b9aaf) | Feb 09, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [98d6451ac1](https://linux-hardware.org/?probe=98d6451ac1) | Feb 07, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| ASRock        | Z97M Pro4                   | Desktop     | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [4b3b067330](https://linux-hardware.org/?probe=4b3b067330) | Jan 21, 2022 |
| ASRock        | Z590 Pro4                   | Desktop     | [a89877d9de](https://linux-hardware.org/?probe=a89877d9de) | Jan 16, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [45b3c5b85a](https://linux-hardware.org/?probe=45b3c5b85a) | Jan 16, 2022 |
| ASRock        | Z590 Pro4                   | Desktop     | [7a2453280a](https://linux-hardware.org/?probe=7a2453280a) | Jan 14, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| MSI           | H81M-P33                    | Desktop     | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Gigabyte      | 965P-DS3                    | Desktop     | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| ECS           | H61H2-M2                    | Desktop     | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [967a9b3a38](https://linux-hardware.org/?probe=967a9b3a38) | Dec 27, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [d9c0087822](https://linux-hardware.org/?probe=d9c0087822) | Dec 26, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [9f3a7c27d9](https://linux-hardware.org/?probe=9f3a7c27d9) | Dec 24, 2021 |
| ASRock        | 870 Extreme3                | Desktop     | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [f258cd6bb3](https://linux-hardware.org/?probe=f258cd6bb3) | Dec 12, 2021 |
| Acer          | Aspire A314-22              | Notebook    | [655c34690e](https://linux-hardware.org/?probe=655c34690e) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | Notebook    | [fe88e1083a](https://linux-hardware.org/?probe=fe88e1083a) | Dec 11, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [422733b9df](https://linux-hardware.org/?probe=422733b9df) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [d0cf0cc443](https://linux-hardware.org/?probe=d0cf0cc443) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                       | Desktop     | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| Foxconn       | 2A8Ch                       | Desktop     | [1f650ebd72](https://linux-hardware.org/?probe=1f650ebd72) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [323825e995](https://linux-hardware.org/?probe=323825e995) | Nov 24, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [659ed4999d](https://linux-hardware.org/?probe=659ed4999d) | Nov 24, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [b0b04002be](https://linux-hardware.org/?probe=b0b04002be) | Nov 24, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [515899572d](https://linux-hardware.org/?probe=515899572d) | Nov 22, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [9ae3647f81](https://linux-hardware.org/?probe=9ae3647f81) | Nov 22, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [8a1a3f0661](https://linux-hardware.org/?probe=8a1a3f0661) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [eace5e1302](https://linux-hardware.org/?probe=eace5e1302) | Nov 19, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c77e499435](https://linux-hardware.org/?probe=c77e499435) | Nov 13, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [93e710085b](https://linux-hardware.org/?probe=93e710085b) | Nov 12, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [aa49529b6c](https://linux-hardware.org/?probe=aa49529b6c) | Nov 09, 2021 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [3af4c85553](https://linux-hardware.org/?probe=3af4c85553) | Nov 04, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [df4871ce19](https://linux-hardware.org/?probe=df4871ce19) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | Notebook    | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7f7df5e24](https://linux-hardware.org/?probe=c7f7df5e24) | Nov 01, 2021 |
| MSI           | P55-CD53                    | Desktop     | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [532a1d3d01](https://linux-hardware.org/?probe=532a1d3d01) | Oct 29, 2021 |
| MSI           | P55-CD53                    | Desktop     | [12bf811a5c](https://linux-hardware.org/?probe=12bf811a5c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | Desktop     | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2d80988ddc](https://linux-hardware.org/?probe=2d80988ddc) | Oct 22, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [d891006b52](https://linux-hardware.org/?probe=d891006b52) | Oct 14, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [afbb6f50c8](https://linux-hardware.org/?probe=afbb6f50c8) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [d5199453f5](https://linux-hardware.org/?probe=d5199453f5) | Oct 04, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [068d8ff3b0](https://linux-hardware.org/?probe=068d8ff3b0) | Oct 04, 2021 |
| ASUSTek       | A58M-K                      | Desktop     | [2ca6ce79db](https://linux-hardware.org/?probe=2ca6ce79db) | Oct 03, 2021 |
| Toshiba       | Satellite P200              | Notebook    | [df46118ac3](https://linux-hardware.org/?probe=df46118ac3) | Oct 02, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e5508ac7ab](https://linux-hardware.org/?probe=e5508ac7ab) | Sep 27, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [8803020fce](https://linux-hardware.org/?probe=8803020fce) | Sep 11, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [104bd9a2a0](https://linux-hardware.org/?probe=104bd9a2a0) | Sep 09, 2021 |
| Lenovo        | ThinkPad E590 20NB006MSC    | Notebook    | [73c87242b9](https://linux-hardware.org/?probe=73c87242b9) | Sep 09, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [aa6b5ca915](https://linux-hardware.org/?probe=aa6b5ca915) | Sep 08, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [8b503ffd8a](https://linux-hardware.org/?probe=8b503ffd8a) | Sep 07, 2021 |
| Dell          | Latitude 5580               | Notebook    | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [44e5a5c02e](https://linux-hardware.org/?probe=44e5a5c02e) | Aug 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [06981db89b](https://linux-hardware.org/?probe=06981db89b) | Aug 20, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [3c4fba3670](https://linux-hardware.org/?probe=3c4fba3670) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [149504315f](https://linux-hardware.org/?probe=149504315f) | Aug 10, 2021 |
| HP            | 2000                        | Notebook    | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [7d693f5628](https://linux-hardware.org/?probe=7d693f5628) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| Lenovo        | ThinkPad T430 2349AK2       | Notebook    | [c51aebd74f](https://linux-hardware.org/?probe=c51aebd74f) | Aug 04, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [0283581712](https://linux-hardware.org/?probe=0283581712) | Jul 31, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8297a49138](https://linux-hardware.org/?probe=8297a49138) | Jul 28, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [f60a7a3f63](https://linux-hardware.org/?probe=f60a7a3f63) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4759f3249f](https://linux-hardware.org/?probe=4759f3249f) | Jul 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| ASUSTek       | X540SAA                     | Notebook    | [34bb1d000b](https://linux-hardware.org/?probe=34bb1d000b) | Jul 24, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [9a9f7c5e69](https://linux-hardware.org/?probe=9a9f7c5e69) | Jul 20, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [45694711ff](https://linux-hardware.org/?probe=45694711ff) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | Notebook    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [0c5f910d8b](https://linux-hardware.org/?probe=0c5f910d8b) | Jun 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| Lenovo        | ThinkPad P53 20QNZ4RBUS     | Notebook    | [3f5925d0f5](https://linux-hardware.org/?probe=3f5925d0f5) | Jun 07, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [83b3cc659a](https://linux-hardware.org/?probe=83b3cc659a) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Lenovo        | ThinkPad P1 20MES1T700      | Notebook    | [be5bc5605b](https://linux-hardware.org/?probe=be5bc5605b) | Jun 01, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [2ec41d1cf8](https://linux-hardware.org/?probe=2ec41d1cf8) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| Dell          | 06CV2N A01                  | Desktop     | [35a0afd617](https://linux-hardware.org/?probe=35a0afd617) | May 25, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bfb71f53ec](https://linux-hardware.org/?probe=bfb71f53ec) | May 03, 2021 |
| Lenovo        | CRESCENTBAY 31900058 WIN... | All in one  | [84248bb07c](https://linux-hardware.org/?probe=84248bb07c) | May 03, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [6ab7b315e3](https://linux-hardware.org/?probe=6ab7b315e3) | Apr 24, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [7e0d6ec835](https://linux-hardware.org/?probe=7e0d6ec835) | Apr 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fbc2a66e2b](https://linux-hardware.org/?probe=fbc2a66e2b) | Apr 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [eabbb41fea](https://linux-hardware.org/?probe=eabbb41fea) | Apr 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [86927ce44d](https://linux-hardware.org/?probe=86927ce44d) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | Notebook    | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| ASRock        | P45DE                       | Desktop     | [2f6b602e36](https://linux-hardware.org/?probe=2f6b602e36) | Apr 18, 2021 |
| HP            | Compaq 6710b (KL509AV)      | Notebook    | [735870e390](https://linux-hardware.org/?probe=735870e390) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [24cd2670f3](https://linux-hardware.org/?probe=24cd2670f3) | Apr 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [60ef5cf4f2](https://linux-hardware.org/?probe=60ef5cf4f2) | Apr 15, 2021 |
| HP            | Compaq 6710b (KL509AV)      | Notebook    | [565cd80547](https://linux-hardware.org/?probe=565cd80547) | Apr 15, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [78550034b4](https://linux-hardware.org/?probe=78550034b4) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [43b989fae1](https://linux-hardware.org/?probe=43b989fae1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | Notebook    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [7ad77d82ba](https://linux-hardware.org/?probe=7ad77d82ba) | Apr 03, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [be7b667e75](https://linux-hardware.org/?probe=be7b667e75) | Mar 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [45e4f9d242](https://linux-hardware.org/?probe=45e4f9d242) | Mar 24, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ba238dbe29](https://linux-hardware.org/?probe=ba238dbe29) | Mar 21, 2021 |
| Dell          | Inspiron 5551               | Notebook    | [3b91b6e49f](https://linux-hardware.org/?probe=3b91b6e49f) | Mar 20, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6e5e0c9ef4](https://linux-hardware.org/?probe=6e5e0c9ef4) | Mar 19, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [12566ee726](https://linux-hardware.org/?probe=12566ee726) | Mar 10, 2021 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [24a672b8ac](https://linux-hardware.org/?probe=24a672b8ac) | Feb 25, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [8f0d10afce](https://linux-hardware.org/?probe=8f0d10afce) | Feb 24, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [ffdabc425b](https://linux-hardware.org/?probe=ffdabc425b) | Feb 16, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [69f9ebe58b](https://linux-hardware.org/?probe=69f9ebe58b) | Feb 11, 2021 |
| Acer          | Aspire ES1-532G             | Notebook    | [f01b666f99](https://linux-hardware.org/?probe=f01b666f99) | Feb 09, 2021 |
| Dell          | 0NNGP2 A00                  | Desktop     | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [d0648fe1f7](https://linux-hardware.org/?probe=d0648fe1f7) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [eee7c1f592](https://linux-hardware.org/?probe=eee7c1f592) | Feb 03, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a541bcd390](https://linux-hardware.org/?probe=a541bcd390) | Feb 02, 2021 |
| ASRock        | ConRoe1333-D667             | Desktop     | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [28cb4726bb](https://linux-hardware.org/?probe=28cb4726bb) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [0b4b751863](https://linux-hardware.org/?probe=0b4b751863) | Jan 31, 2021 |
| ASUSTek       | F5N                         | Notebook    | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [9cd91004ab](https://linux-hardware.org/?probe=9cd91004ab) | Jan 24, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [9afb5c207a](https://linux-hardware.org/?probe=9afb5c207a) | Jan 23, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [482bc5334f](https://linux-hardware.org/?probe=482bc5334f) | Jan 22, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [df34a7d718](https://linux-hardware.org/?probe=df34a7d718) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [0d8e905a30](https://linux-hardware.org/?probe=0d8e905a30) | Jan 16, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [17f2fe84cb](https://linux-hardware.org/?probe=17f2fe84cb) | Jan 14, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [9b72f3a82b](https://linux-hardware.org/?probe=9b72f3a82b) | Jan 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [939c4dbad4](https://linux-hardware.org/?probe=939c4dbad4) | Jan 10, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [1f95699c20](https://linux-hardware.org/?probe=1f95699c20) | Jan 09, 2021 |
| Lenovo        | ThinkPad T61 6458AU9        | Notebook    | [5350b0523f](https://linux-hardware.org/?probe=5350b0523f) | Jan 08, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [9b176fb8e5](https://linux-hardware.org/?probe=9b176fb8e5) | Jan 04, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [db68ccb5de](https://linux-hardware.org/?probe=db68ccb5de) | Jan 04, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| HP            | 18EA                        | Desktop     | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| ASRock        | Z370 Pro4                   | Desktop     | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| Acer          | Aspire 7739G                | Notebook    | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | Notebook    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | Notebook    | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [eed4ff0229](https://linux-hardware.org/?probe=eed4ff0229) | Nov 19, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9c165b5f59](https://linux-hardware.org/?probe=9c165b5f59) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [50ddfd361b](https://linux-hardware.org/?probe=50ddfd361b) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7e3892e9b1](https://linux-hardware.org/?probe=7e3892e9b1) | Nov 09, 2020 |
| Acer          | Aspire E5-771G              | Notebook    | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [b75cfae4a3](https://linux-hardware.org/?probe=b75cfae4a3) | Nov 01, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [e6cd5153b1](https://linux-hardware.org/?probe=e6cd5153b1) | Oct 31, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [c3c04c52ab](https://linux-hardware.org/?probe=c3c04c52ab) | Oct 26, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [57db732909](https://linux-hardware.org/?probe=57db732909) | Oct 25, 2020 |
| Nvidia        | Tegra                       | Soc         | [ef24e8c128](https://linux-hardware.org/?probe=ef24e8c128) | Oct 23, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3a4ce2fd2](https://linux-hardware.org/?probe=d3a4ce2fd2) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3bdc7437e](https://linux-hardware.org/?probe=d3bdc7437e) | Oct 22, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [38c87efbca](https://linux-hardware.org/?probe=38c87efbca) | Oct 16, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [ff7ecd0641](https://linux-hardware.org/?probe=ff7ecd0641) | Oct 15, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [65c065a968](https://linux-hardware.org/?probe=65c065a968) | Oct 09, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [0d11552658](https://linux-hardware.org/?probe=0d11552658) | Oct 07, 2020 |
| Pegatron      | 2A94h                       | Desktop     | [668c4bbb8b](https://linux-hardware.org/?probe=668c4bbb8b) | Oct 06, 2020 |
| Toshiba       | Satellite C55-A-1M7         | Notebook    | [174d6c4c6d](https://linux-hardware.org/?probe=174d6c4c6d) | Oct 06, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [7904981ea3](https://linux-hardware.org/?probe=7904981ea3) | Oct 05, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [b098cfc85e](https://linux-hardware.org/?probe=b098cfc85e) | Sep 30, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [dacb39a2ba](https://linux-hardware.org/?probe=dacb39a2ba) | Sep 30, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [df11954c4f](https://linux-hardware.org/?probe=df11954c4f) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [b4807eff1e](https://linux-hardware.org/?probe=b4807eff1e) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [9cc971b2e7](https://linux-hardware.org/?probe=9cc971b2e7) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [8220732bda](https://linux-hardware.org/?probe=8220732bda) | Sep 28, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [7f4940b41c](https://linux-hardware.org/?probe=7f4940b41c) | Sep 28, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [062f436dfa](https://linux-hardware.org/?probe=062f436dfa) | Sep 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [181e06ec2e](https://linux-hardware.org/?probe=181e06ec2e) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d7391de736](https://linux-hardware.org/?probe=d7391de736) | Sep 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [ea8e216968](https://linux-hardware.org/?probe=ea8e216968) | Sep 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [d93882e0b2](https://linux-hardware.org/?probe=d93882e0b2) | Sep 20, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [42ed26b195](https://linux-hardware.org/?probe=42ed26b195) | Sep 19, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [fa0ec4aeae](https://linux-hardware.org/?probe=fa0ec4aeae) | Sep 17, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | Notebook    | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | Notebook    | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Dell          | Latitude 7390               | Notebook    | [b8019896d0](https://linux-hardware.org/?probe=b8019896d0) | Sep 10, 2020 |
| ASUSTek       | M4A77                       | Desktop     | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [b80f12df10](https://linux-hardware.org/?probe=b80f12df10) | Sep 07, 2020 |
| ASRock        | Z87E-ITX                    | Desktop     | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [a2d99d11fc](https://linux-hardware.org/?probe=a2d99d11fc) | Aug 30, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [1c2eaa2346](https://linux-hardware.org/?probe=1c2eaa2346) | Aug 23, 2020 |
| HP            | 2129                        | Desktop     | [d1eda00971](https://linux-hardware.org/?probe=d1eda00971) | Aug 20, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [4458c2267f](https://linux-hardware.org/?probe=4458c2267f) | Aug 17, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [3a826b3414](https://linux-hardware.org/?probe=3a826b3414) | Aug 13, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [e28ccfa01e](https://linux-hardware.org/?probe=e28ccfa01e) | Aug 11, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9bf9387073](https://linux-hardware.org/?probe=9bf9387073) | Aug 05, 2020 |
| ASUSTek       | GL752VW                     | Notebook    | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c670b35249](https://linux-hardware.org/?probe=c670b35249) | Jul 29, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [842efe3170](https://linux-hardware.org/?probe=842efe3170) | Jul 28, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [743f8b4f98](https://linux-hardware.org/?probe=743f8b4f98) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [34213d655c](https://linux-hardware.org/?probe=34213d655c) | Jul 24, 2020 |
| Lenovo        | IdeaCentre Stick 300-01I... | Stick pc    | [28b902c9b7](https://linux-hardware.org/?probe=28b902c9b7) | Jul 21, 2020 |
| Dell          | Precision 5530              | Notebook    | [30c2f2561e](https://linux-hardware.org/?probe=30c2f2561e) | Jul 20, 2020 |
| ASUSTek       | X751NV                      | Notebook    | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | Notebook    | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
| Gigabyte      | G41M-Combo                  | Desktop     | [2f3657530f](https://linux-hardware.org/?probe=2f3657530f) | Jun 29, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ac52acb928](https://linux-hardware.org/?probe=ac52acb928) | Jun 24, 2020 |
| Notebook      | MAM2080                     | Notebook    | [7464ed3c9d](https://linux-hardware.org/?probe=7464ed3c9d) | Jun 23, 2020 |
| ASUSTek       | X751NV                      | Notebook    | [08c5775f88](https://linux-hardware.org/?probe=08c5775f88) | Jun 22, 2020 |
| Notebook      | MAM2080                     | Notebook    | [7321ecab2d](https://linux-hardware.org/?probe=7321ecab2d) | Jun 21, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [31f3732dc9](https://linux-hardware.org/?probe=31f3732dc9) | Jun 19, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | Notebook    | [c0c727bcb0](https://linux-hardware.org/?probe=c0c727bcb0) | Jun 18, 2020 |
| ASUSTek       | X540UA                      | Notebook    | [7f0afeb60e](https://linux-hardware.org/?probe=7f0afeb60e) | Jun 16, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [639b8bd2bc](https://linux-hardware.org/?probe=639b8bd2bc) | Jun 14, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [77e3ae41d8](https://linux-hardware.org/?probe=77e3ae41d8) | Jun 10, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [2c0b3072ac](https://linux-hardware.org/?probe=2c0b3072ac) | Jun 09, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [fa00080df2](https://linux-hardware.org/?probe=fa00080df2) | Jun 06, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [eff12f397f](https://linux-hardware.org/?probe=eff12f397f) | Jun 06, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [7da6752573](https://linux-hardware.org/?probe=7da6752573) | May 31, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d77566be76](https://linux-hardware.org/?probe=d77566be76) | May 31, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [5472c53dca](https://linux-hardware.org/?probe=5472c53dca) | May 31, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [06f88752e5](https://linux-hardware.org/?probe=06f88752e5) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [15cf043276](https://linux-hardware.org/?probe=15cf043276) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [89935abc60](https://linux-hardware.org/?probe=89935abc60) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [bbb1f5819f](https://linux-hardware.org/?probe=bbb1f5819f) | May 31, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [26a9c7f62c](https://linux-hardware.org/?probe=26a9c7f62c) | May 30, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [689825038f](https://linux-hardware.org/?probe=689825038f) | May 25, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [e3042f4583](https://linux-hardware.org/?probe=e3042f4583) | May 24, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [3ae92d178c](https://linux-hardware.org/?probe=3ae92d178c) | May 21, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e6f20d976d](https://linux-hardware.org/?probe=e6f20d976d) | May 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9e3950795e](https://linux-hardware.org/?probe=9e3950795e) | May 17, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [0a7ccd88d0](https://linux-hardware.org/?probe=0a7ccd88d0) | May 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [951378d6d8](https://linux-hardware.org/?probe=951378d6d8) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Acer          | Aspire ES1-571              | Notebook    | [77ee42e92e](https://linux-hardware.org/?probe=77ee42e92e) | May 12, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [abfb95a938](https://linux-hardware.org/?probe=abfb95a938) | May 11, 2020 |
| Gigabyte      | 965P-DS3                    | Desktop     | [e59e1593d5](https://linux-hardware.org/?probe=e59e1593d5) | May 11, 2020 |
| MSI           | MS-7360                     | Desktop     | [ab94189bcf](https://linux-hardware.org/?probe=ab94189bcf) | May 07, 2020 |
| eMachines     | G725                        | Notebook    | [7edfa3ee85](https://linux-hardware.org/?probe=7edfa3ee85) | May 04, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [c5c02e1984](https://linux-hardware.org/?probe=c5c02e1984) | May 03, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [5f8f6e1f17](https://linux-hardware.org/?probe=5f8f6e1f17) | May 02, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [72ece5cb6b](https://linux-hardware.org/?probe=72ece5cb6b) | Apr 23, 2020 |
| Lenovo        | B590 627439G                | Notebook    | [59e71f4410](https://linux-hardware.org/?probe=59e71f4410) | Apr 16, 2020 |
| Dell          | Vostro 3584                 | Notebook    | [37bd21052a](https://linux-hardware.org/?probe=37bd21052a) | Apr 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ca750eb568](https://linux-hardware.org/?probe=ca750eb568) | Apr 14, 2020 |
| HP            | 3031h                       | Desktop     | [b4638888cb](https://linux-hardware.org/?probe=b4638888cb) | Apr 14, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [1562c544a6](https://linux-hardware.org/?probe=1562c544a6) | Apr 14, 2020 |
| ASRock        | H61M-DGS                    | Desktop     | [0a090881ae](https://linux-hardware.org/?probe=0a090881ae) | Apr 12, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [72c0b81b89](https://linux-hardware.org/?probe=72c0b81b89) | Mar 27, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [1a2c3269a9](https://linux-hardware.org/?probe=1a2c3269a9) | Mar 25, 2020 |
| ASUSTek       | A8V-MQ                      | Desktop     | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| Medion        | P6618                       | Notebook    | [cd6a2e684b](https://linux-hardware.org/?probe=cd6a2e684b) | Mar 20, 2020 |
| ASRock        | H61M-VS                     | Desktop     | [799e1670fd](https://linux-hardware.org/?probe=799e1670fd) | Mar 18, 2020 |
| HP            | 212B                        | Desktop     | [6058dd53b1](https://linux-hardware.org/?probe=6058dd53b1) | Mar 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [958514b01d](https://linux-hardware.org/?probe=958514b01d) | Mar 06, 2020 |
| HP            | Presario CQ57               | Notebook    | [09b5945399](https://linux-hardware.org/?probe=09b5945399) | Mar 02, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [26545c7add](https://linux-hardware.org/?probe=26545c7add) | Feb 24, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [1693523c61](https://linux-hardware.org/?probe=1693523c61) | Feb 21, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [bdebb9000c](https://linux-hardware.org/?probe=bdebb9000c) | Feb 21, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [65c38da632](https://linux-hardware.org/?probe=65c38da632) | Feb 20, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [b0e9895bef](https://linux-hardware.org/?probe=b0e9895bef) | Feb 16, 2020 |
| HP            | Pavilion g6                 | Notebook    | [5965dbf803](https://linux-hardware.org/?probe=5965dbf803) | Feb 08, 2020 |
| ASRock        | B150M-HDV                   | Desktop     | [c08c6d0574](https://linux-hardware.org/?probe=c08c6d0574) | Feb 08, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [ed2e18e22a](https://linux-hardware.org/?probe=ed2e18e22a) | Jan 31, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [fc460d19de](https://linux-hardware.org/?probe=fc460d19de) | Jan 29, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ad283e347b](https://linux-hardware.org/?probe=ad283e347b) | Jan 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [fe5311a7e7](https://linux-hardware.org/?probe=fe5311a7e7) | Jan 28, 2020 |
| HP            | 18E7                        | Desktop     | [de846e5f4f](https://linux-hardware.org/?probe=de846e5f4f) | Jan 22, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [9ed2076b0d](https://linux-hardware.org/?probe=9ed2076b0d) | Jan 18, 2020 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [dc121e5512](https://linux-hardware.org/?probe=dc121e5512) | Jan 18, 2020 |
| Acer          | Veriton S680G               | Desktop     | [277889b2ff](https://linux-hardware.org/?probe=277889b2ff) | Jan 15, 2020 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [3317c231ea](https://linux-hardware.org/?probe=3317c231ea) | Jan 08, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [0af8fff870](https://linux-hardware.org/?probe=0af8fff870) | Jan 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [cd7fe65e36](https://linux-hardware.org/?probe=cd7fe65e36) | Jan 02, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [d8301b28b6](https://linux-hardware.org/?probe=d8301b28b6) | Dec 31, 2019 |
| HP            | ProBook 4730s               | Notebook    | [a56d8d1c28](https://linux-hardware.org/?probe=a56d8d1c28) | Dec 26, 2019 |
| HP            | ProBook 4730s               | Notebook    | [fc266328ed](https://linux-hardware.org/?probe=fc266328ed) | Dec 26, 2019 |
| HP            | ProBook 4730s               | Notebook    | [581fd252a9](https://linux-hardware.org/?probe=581fd252a9) | Dec 26, 2019 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [e097415087](https://linux-hardware.org/?probe=e097415087) | Dec 26, 2019 |
| ASRock        | N68-S3 UCC                  | Desktop     | [9cbd6c2e0e](https://linux-hardware.org/?probe=9cbd6c2e0e) | Dec 25, 2019 |
| ASRock        | 990FX Extreme3              | Desktop     | [107280e5a9](https://linux-hardware.org/?probe=107280e5a9) | Dec 23, 2019 |
| ASRock        | 990FX Extreme3              | Desktop     | [66a084d547](https://linux-hardware.org/?probe=66a084d547) | Dec 11, 2019 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | Notebook    | [059788b6b9](https://linux-hardware.org/?probe=059788b6b9) | Dec 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| ASRock        | H97 Killer                  | Desktop     | [8538b88e3d](https://linux-hardware.org/?probe=8538b88e3d) | Nov 27, 2019 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [73c6829ffb](https://linux-hardware.org/?probe=73c6829ffb) | Nov 27, 2019 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [c3973966c4](https://linux-hardware.org/?probe=c3973966c4) | Nov 21, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [dfc4334b0c](https://linux-hardware.org/?probe=dfc4334b0c) | Nov 15, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6334709a9e](https://linux-hardware.org/?probe=6334709a9e) | Nov 15, 2019 |
| HP            | EliteBook 850 G6            | Notebook    | [d1a89b5c7b](https://linux-hardware.org/?probe=d1a89b5c7b) | Nov 13, 2019 |
| HP            | 18EA                        | Desktop     | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [9bd874bab4](https://linux-hardware.org/?probe=9bd874bab4) | Nov 05, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [ae95cd5f3d](https://linux-hardware.org/?probe=ae95cd5f3d) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | Notebook    | [38c98d0bfa](https://linux-hardware.org/?probe=38c98d0bfa) | Oct 12, 2019 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [d3d79c2a8d](https://linux-hardware.org/?probe=d3d79c2a8d) | Sep 16, 2019 |
| ASUSTek       | G750JZ                      | Notebook    | [f6f8595b70](https://linux-hardware.org/?probe=f6f8595b70) | Sep 14, 2019 |
| Acer          | Aspire A315-21              | Notebook    | [b29e405bdc](https://linux-hardware.org/?probe=b29e405bdc) | Sep 13, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a35aea421b](https://linux-hardware.org/?probe=a35aea421b) | Sep 09, 2019 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [349ef8982a](https://linux-hardware.org/?probe=349ef8982a) | Sep 09, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [59782a89ea](https://linux-hardware.org/?probe=59782a89ea) | Sep 06, 2019 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b4ef0f5499](https://linux-hardware.org/?probe=b4ef0f5499) | Sep 05, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [458c9ffc20](https://linux-hardware.org/?probe=458c9ffc20) | Sep 02, 2019 |
| Dell          | G3 3779                     | Notebook    | [46c53c54c1](https://linux-hardware.org/?probe=46c53c54c1) | Aug 28, 2019 |
| Lenovo        | ThinkPad X240 20AMS30A01    | Notebook    | [a808bddfca](https://linux-hardware.org/?probe=a808bddfca) | Aug 22, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [be3a07802c](https://linux-hardware.org/?probe=be3a07802c) | Aug 13, 2019 |
| ASRock        | FM2A55M-DGS R2.0            | Desktop     | [9cdd546881](https://linux-hardware.org/?probe=9cdd546881) | Jul 29, 2019 |
| ASRock        | A300M-STX                   | Desktop     | [edf300f175](https://linux-hardware.org/?probe=edf300f175) | Jul 29, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [aad0551e27](https://linux-hardware.org/?probe=aad0551e27) | Jul 25, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [57c89febd9](https://linux-hardware.org/?probe=57c89febd9) | Jul 22, 2019 |
| Dell          | Vostro 3480                 | Notebook    | [142a1d632e](https://linux-hardware.org/?probe=142a1d632e) | Jul 12, 2019 |
| Dell          | Vostro 3480                 | Notebook    | [5c7cd324e3](https://linux-hardware.org/?probe=5c7cd324e3) | Jul 12, 2019 |
| ASUSTek       | E35M1-M                     | Desktop     | [1b78cc518f](https://linux-hardware.org/?probe=1b78cc518f) | Jul 08, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [542c9cbc52](https://linux-hardware.org/?probe=542c9cbc52) | Jun 23, 2019 |
| ASUSTek       | E35M1-M                     | Desktop     | [1f5e6b026b](https://linux-hardware.org/?probe=1f5e6b026b) | Jun 23, 2019 |
| Acer          | Aspire A515-51G             | Notebook    | [43a15b2717](https://linux-hardware.org/?probe=43a15b2717) | Jun 22, 2019 |
| Acer          | Extensa 5630                | Notebook    | [ac0c824624](https://linux-hardware.org/?probe=ac0c824624) | Jun 16, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f8c4365b6c](https://linux-hardware.org/?probe=f8c4365b6c) | Jun 07, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3968b06d9c](https://linux-hardware.org/?probe=3968b06d9c) | Jun 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [edcc2f0a4e](https://linux-hardware.org/?probe=edcc2f0a4e) | Jun 06, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8195d1d516](https://linux-hardware.org/?probe=8195d1d516) | Jun 06, 2019 |
| Dell          | Latitude E6440              | Notebook    | [6c61ba4580](https://linux-hardware.org/?probe=6c61ba4580) | Jun 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6ce5e7dbb1](https://linux-hardware.org/?probe=6ce5e7dbb1) | May 24, 2019 |
| HP            | 250 G6 Notebook PC          | Notebook    | [da7e75ebe8](https://linux-hardware.org/?probe=da7e75ebe8) | May 19, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [d78a5346f7](https://linux-hardware.org/?probe=d78a5346f7) | May 13, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [6465c1b176](https://linux-hardware.org/?probe=6465c1b176) | May 11, 2019 |
| HP            | 83ED                        | Desktop     | [532b72754e](https://linux-hardware.org/?probe=532b72754e) | May 06, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [93859ddac7](https://linux-hardware.org/?probe=93859ddac7) | May 05, 2019 |
| HP            | Notebook                    | Notebook    | [75f8121579](https://linux-hardware.org/?probe=75f8121579) | May 03, 2019 |
| HP            | Notebook                    | Notebook    | [55d7e86f13](https://linux-hardware.org/?probe=55d7e86f13) | May 03, 2019 |
| HP            | Notebook                    | Notebook    | [17fa8aef52](https://linux-hardware.org/?probe=17fa8aef52) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [09c192ce30](https://linux-hardware.org/?probe=09c192ce30) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [f4deeacc7c](https://linux-hardware.org/?probe=f4deeacc7c) | May 03, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5d410980c0](https://linux-hardware.org/?probe=5d410980c0) | May 01, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [89f0da0254](https://linux-hardware.org/?probe=89f0da0254) | Apr 30, 2019 |
| ASUSTek       | X550JX                      | Notebook    | [341ce6f2fb](https://linux-hardware.org/?probe=341ce6f2fb) | Apr 14, 2019 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e7259783d1](https://linux-hardware.org/?probe=e7259783d1) | Apr 13, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3b3d563f34](https://linux-hardware.org/?probe=3b3d563f34) | Apr 12, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8046c09d71](https://linux-hardware.org/?probe=8046c09d71) | Apr 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [54f04aad99](https://linux-hardware.org/?probe=54f04aad99) | Mar 22, 2019 |
| Dell          | 00X7CK A02                  | Server      | [5b9ec879fc](https://linux-hardware.org/?probe=5b9ec879fc) | Mar 11, 2019 |
| Pegatron      | 2A99                        | Desktop     | [196712630c](https://linux-hardware.org/?probe=196712630c) | Feb 26, 2019 |
| HP            | Unknown                     | Notebook    | [37702d4223](https://linux-hardware.org/?probe=37702d4223) | Feb 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [01e34dc2d8](https://linux-hardware.org/?probe=01e34dc2d8) | Feb 19, 2019 |
| ASUSTek       | B150M-C                     | Desktop     | [88898f6797](https://linux-hardware.org/?probe=88898f6797) | Feb 10, 2019 |
| ECS           | A770M-A                     | Desktop     | [feacfccf11](https://linux-hardware.org/?probe=feacfccf11) | Feb 05, 2019 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [bf1298d356](https://linux-hardware.org/?probe=bf1298d356) | Jan 29, 2019 |
| ABIT          | IP35-E                      | Desktop     | [87b22d6a66](https://linux-hardware.org/?probe=87b22d6a66) | Jan 26, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [42572b9771](https://linux-hardware.org/?probe=42572b9771) | Jan 05, 2019 |
| ASUSTek       | X540UA                      | Notebook    | [867a1fdda8](https://linux-hardware.org/?probe=867a1fdda8) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | Notebook    | [ae2b9d2b8f](https://linux-hardware.org/?probe=ae2b9d2b8f) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | Notebook    | [567e365e34](https://linux-hardware.org/?probe=567e365e34) | Dec 14, 2018 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc26ed35a0](https://linux-hardware.org/?probe=bc26ed35a0) | Dec 08, 2018 |
| Acer          | Aspire 5715Z                | Notebook    | [abecd9bff0](https://linux-hardware.org/?probe=abecd9bff0) | Nov 30, 2018 |
| Acer          | Aspire 5715Z                | Notebook    | [fd1d18122b](https://linux-hardware.org/?probe=fd1d18122b) | Nov 30, 2018 |
| HP            | 2000                        | Notebook    | [b24b2b9082](https://linux-hardware.org/?probe=b24b2b9082) | Nov 26, 2018 |
| Unknown       | Grantsdale                  | Desktop     | [65da6a461b](https://linux-hardware.org/?probe=65da6a461b) | Nov 21, 2018 |
| HP            | ProBook 450 G4              | Notebook    | [415307639f](https://linux-hardware.org/?probe=415307639f) | Nov 21, 2018 |
| Pegatron      | 2AB6                        | Desktop     | [00a8407210](https://linux-hardware.org/?probe=00a8407210) | Oct 31, 2018 |
| HP            | EliteBook 2540p             | Notebook    | [88e983ac45](https://linux-hardware.org/?probe=88e983ac45) | Oct 28, 2018 |
| ASUSTek       | X705UDR                     | Notebook    | [0a1cf851c7](https://linux-hardware.org/?probe=0a1cf851c7) | Jun 20, 2018 |
| Samsung       | N150/N210/N220              | Notebook    | [bab6da27ab](https://linux-hardware.org/?probe=bab6da27ab) | Apr 30, 2017 |
| Dell          | Vostro 1700                 | Notebook    | [6167c4bd5d](https://linux-hardware.org/?probe=6167c4bd5d) | Mar 17, 2017 |
| Dell          | Inspiron 3737               | Notebook    | [fba4632269](https://linux-hardware.org/?probe=fba4632269) | Dec 22, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Croatia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 72        | 11.45%  |
| Ubuntu 22.04                 | 38        | 6.04%   |
| Ubuntu 18.04                 | 33        | 5.25%   |
| Debian 11                    | 22        | 3.5%    |
| OpenMandriva 4.3             | 14        | 2.23%   |
| Zorin 16                     | 13        | 2.07%   |
| Arch Rolling                 | 13        | 2.07%   |
| Linux Mint 20.2              | 11        | 1.75%   |
| Pop!_OS 22.04                | 10        | 1.59%   |
| Linux Mint 20.3              | 10        | 1.59%   |
| Fedora 39                    | 10        | 1.59%   |
| Fedora 38                    | 10        | 1.59%   |
| Ubuntu 18.10                 | 9         | 1.43%   |
| Pop!_OS 21.04                | 9         | 1.43%   |
| ArcoLinux Rolling            | 9         | 1.43%   |
| Debian 12                    | 8         | 1.27%   |
| Ubuntu 21.04                 | 7         | 1.11%   |
| Pop!_OS 20.04                | 7         | 1.11%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 1.11%   |
| OpenMandriva 4.2             | 7         | 1.11%   |
| Manjaro                      | 7         | 1.11%   |
| Fedora 36                    | 7         | 1.11%   |
| Ubuntu 19.10                 | 6         | 0.95%   |
| Pop!_OS 21.10                | 6         | 0.95%   |
| Pop!_OS 20.10                | 6         | 0.95%   |
| Linux Mint 21.1              | 6         | 0.95%   |
| KDE neon 22.04               | 6         | 0.95%   |
| KDE neon 20.04               | 6         | 0.95%   |
| Debian 10                    | 6         | 0.95%   |
| Ubuntu 19.04                 | 5         | 0.79%   |
| Fedora 35                    | 5         | 0.79%   |
| Endless 3.7.8                | 5         | 0.79%   |
| EndeavourOS Rolling          | 5         | 0.79%   |
| Arch                         | 5         | 0.79%   |
| Zorin 17                     | 4         | 0.64%   |
| Zorin 15                     | 4         | 0.64%   |
| Ubuntu 20.10                 | 4         | 0.64%   |
| OpenMandriva 4.50            | 4         | 0.64%   |
| OpenMandriva 23.08           | 4         | 0.64%   |
| Linux Mint 20                | 4         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu             | 173       | 30.03%  |
| Linux Mint         | 44        | 7.64%   |
| Fedora             | 40        | 6.94%   |
| Pop!_OS            | 38        | 6.6%    |
| OpenMandriva       | 36        | 6.25%   |
| Debian             | 35        | 6.08%   |
| Manjaro            | 27        | 4.69%   |
| Endless            | 24        | 4.17%   |
| Zorin              | 21        | 3.65%   |
| Arch               | 17        | 2.95%   |
| Kubuntu            | 15        | 2.6%    |
| openSUSE           | 11        | 1.91%   |
| KDE neon           | 11        | 1.91%   |
| ArcoLinux          | 10        | 1.74%   |
| ROSA               | 9         | 1.56%   |
| Ubuntu MATE        | 6         | 1.04%   |
| Elementary         | 6         | 1.04%   |
| Kali               | 5         | 0.87%   |
| EndeavourOS        | 5         | 0.87%   |
| Xubuntu            | 4         | 0.69%   |
| Ubuntu Budgie      | 4         | 0.69%   |
| LMDE               | 4         | 0.69%   |
| Ubuntu Unity       | 3         | 0.52%   |
| Nobara             | 3         | 0.52%   |
| Gentoo             | 3         | 0.52%   |
| Raspbian           | 2         | 0.35%   |
| Q4OS               | 2         | 0.35%   |
| MX                 | 2         | 0.35%   |
| Lubuntu            | 2         | 0.35%   |
| LinuxFX            | 2         | 0.35%   |
| Xero               | 1         | 0.17%   |
| SteamOS            | 1         | 0.17%   |
| Rocky Linux        | 1         | 0.17%   |
| Parrot             | 1         | 0.17%   |
| Garuda Linux       | 1         | 0.17%   |
| Fedora-asahi-remix | 1         | 0.17%   |
| Dts-distro         | 1         | 0.17%   |
| Clear Linux        | 1         | 0.17%   |
| CentOS             | 1         | 0.17%   |
| BlackPanther       | 1         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 14        | 2.04%   |
| 5.4.0-42-generic         | 8         | 1.17%   |
| 5.11.0-38-generic        | 8         | 1.17%   |
| 5.10.14-desktop-1omv4002 | 7         | 1.02%   |
| 5.8.0-14-generic         | 6         | 0.88%   |
| 5.4.0-58-generic         | 6         | 0.88%   |
| 5.3.0-28-generic         | 6         | 0.88%   |
| 5.11.0-7620-generic      | 6         | 0.88%   |
| 5.4.0-91-generic         | 5         | 0.73%   |
| 5.4.0-48-generic         | 5         | 0.73%   |
| 5.4.0-37-generic         | 5         | 0.73%   |
| 5.11.0-41-generic        | 5         | 0.73%   |
| 6.5.0-26-generic         | 4         | 0.58%   |
| 6.4.11-desktop-1omv2390  | 4         | 0.58%   |
| 5.8.0-59-generic         | 4         | 0.58%   |
| 5.8.0-48-generic         | 4         | 0.58%   |
| 5.4.0-52-generic         | 4         | 0.58%   |
| 5.3.0-26-generic         | 4         | 0.58%   |
| 5.15.0-58-generic        | 4         | 0.58%   |
| 5.15.0-56-generic        | 4         | 0.58%   |
| 5.13.0-30-generic        | 4         | 0.58%   |
| 5.11.0-40-generic        | 4         | 0.58%   |
| 4.18.0-10-generic        | 4         | 0.58%   |
| 6.5.0-28-generic         | 3         | 0.44%   |
| 6.2.9-300.fc38.x86_64    | 3         | 0.44%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.44%   |
| 6.2.6-76060206-generic   | 3         | 0.44%   |
| 6.2.0-39-generic         | 3         | 0.44%   |
| 6.2.0-26-generic         | 3         | 0.44%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.44%   |
| 6.1.0-13-amd64           | 3         | 0.44%   |
| 5.8.16-2-MANJARO         | 3         | 0.44%   |
| 5.8.0-7630-generic       | 3         | 0.44%   |
| 5.8.0-43-generic         | 3         | 0.44%   |
| 5.4.0-47-generic         | 3         | 0.44%   |
| 5.4.0-40-generic         | 3         | 0.44%   |
| 5.4.0-29-generic         | 3         | 0.44%   |
| 5.4.0-26-generic         | 3         | 0.44%   |
| 5.4.0-19-generic         | 3         | 0.44%   |
| 5.4.0-100-generic        | 3         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 89        | 13.65%  |
| 5.11.0  | 48        | 7.36%   |
| 5.15.0  | 45        | 6.9%    |
| 5.8.0   | 26        | 3.99%   |
| 4.15.0  | 26        | 3.99%   |
| 5.3.0   | 24        | 3.68%   |
| 5.13.0  | 24        | 3.68%   |
| 5.10.0  | 20        | 3.07%   |
| 4.18.0  | 19        | 2.91%   |
| 5.19.0  | 17        | 2.61%   |
| 5.16.7  | 15        | 2.3%    |
| 5.0.0   | 14        | 2.15%   |
| 6.2.0   | 13        | 1.99%   |
| 6.1.0   | 12        | 1.84%   |
| 6.5.0   | 11        | 1.69%   |
| 6.2.6   | 7         | 1.07%   |
| 5.10.14 | 7         | 1.07%   |
| 4.19.0  | 6         | 0.92%   |
| 6.4.11  | 5         | 0.77%   |
| 6.1.1   | 5         | 0.77%   |
| 5.9.16  | 4         | 0.61%   |
| 5.16.11 | 4         | 0.61%   |
| 5.14.0  | 4         | 0.61%   |
| 5.12.4  | 4         | 0.61%   |
| 6.5.9   | 3         | 0.46%   |
| 6.2.9   | 3         | 0.46%   |
| 6.0.5   | 3         | 0.46%   |
| 6.0.0   | 3         | 0.46%   |
| 5.8.16  | 3         | 0.46%   |
| 5.3.18  | 3         | 0.46%   |
| 5.15.8  | 3         | 0.46%   |
| 4.9.60  | 3         | 0.46%   |
| 6.8.7   | 2         | 0.31%   |
| 6.7.3   | 2         | 0.31%   |
| 6.6.9   | 2         | 0.31%   |
| 6.6.2   | 2         | 0.31%   |
| 6.6.11  | 2         | 0.31%   |
| 6.6.1   | 2         | 0.31%   |
| 6.5.4   | 2         | 0.31%   |
| 6.2.15  | 2         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 96        | 15%     |
| 5.15    | 62        | 9.69%   |
| 5.11    | 56        | 8.75%   |
| 5.10    | 37        | 5.78%   |
| 6.2     | 31        | 4.84%   |
| 5.8     | 30        | 4.69%   |
| 5.3     | 28        | 4.38%   |
| 5.13    | 27        | 4.22%   |
| 4.15    | 26        | 4.06%   |
| 6.1     | 25        | 3.91%   |
| 5.19    | 25        | 3.91%   |
| 5.16    | 23        | 3.59%   |
| 6.5     | 21        | 3.28%   |
| 4.18    | 19        | 2.97%   |
| 6.6     | 15        | 2.34%   |
| 5.0     | 15        | 2.34%   |
| 6.0     | 11        | 1.72%   |
| 5.9     | 9         | 1.41%   |
| 6.4     | 8         | 1.25%   |
| 5.18    | 8         | 1.25%   |
| 5.17    | 8         | 1.25%   |
| 5.14    | 8         | 1.25%   |
| 6.7     | 7         | 1.09%   |
| 4.9     | 6         | 0.94%   |
| 4.19    | 6         | 0.94%   |
| 5.6     | 5         | 0.78%   |
| 5.12    | 5         | 0.78%   |
| 6.8     | 4         | 0.63%   |
| 6.3     | 4         | 0.63%   |
| 5.7     | 3         | 0.47%   |
| 5.5     | 2         | 0.31%   |
| 4.16    | 2         | 0.31%   |
| 5.2     | 1         | 0.16%   |
| 5.1     | 1         | 0.16%   |
| 4.17    | 1         | 0.16%   |
| 4.14    | 1         | 0.16%   |
| 4.13    | 1         | 0.16%   |
| 4.12    | 1         | 0.16%   |
| 4.1     | 1         | 0.16%   |
| 3.10    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 541       | 97.13%  |
| i686    | 9         | 1.62%   |
| aarch64 | 5         | 0.9%    |
| armv7l  | 2         | 0.36%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 262       | 45.09%  |
| KDE5            | 115       | 19.79%  |
| Unknown         | 65        | 11.19%  |
| X-Cinnamon      | 33        | 5.68%   |
| XFCE            | 27        | 4.65%   |
| MATE            | 12        | 2.07%   |
| Cinnamon        | 12        | 2.07%   |
| KDE             | 11        | 1.89%   |
| Pantheon        | 5         | 0.86%   |
| GNOME Flashback | 5         | 0.86%   |
| Budgie          | 5         | 0.86%   |
| LXQt            | 4         | 0.69%   |
| LXDE            | 4         | 0.69%   |
| KDE4            | 4         | 0.69%   |
| DWM             | 4         | 0.69%   |
| Unity           | 3         | 0.52%   |
| openbox         | 2         | 0.34%   |
| i3              | 2         | 0.34%   |
| ubuntu          | 1         | 0.17%   |
| Trinity         | 1         | 0.17%   |
| KDE6            | 1         | 0.17%   |
| GNUstep         | 1         | 0.17%   |
| Deepin          | 1         | 0.17%   |
| bspwm           | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 422       | 71.53%  |
| Wayland | 116       | 19.66%  |
| Unknown | 39        | 6.61%   |
| Tty     | 13        | 2.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 263       | 45.66%  |
| SDDM    | 94        | 16.32%  |
| GDM     | 76        | 13.19%  |
| GDM3    | 64        | 11.11%  |
| LightDM | 60        | 10.42%  |
| TDM     | 15        | 2.6%    |
| KDM     | 3         | 0.52%   |
| Ly      | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 332       | 58.14%  |
| hr_HR   | 126       | 22.07%  |
| Unknown | 67        | 11.73%  |
| en_GB   | 26        | 4.55%   |
| C       | 8         | 1.4%    |
| de_DE   | 6         | 1.05%   |
| ru_RU   | 1         | 0.18%   |
| pl_PL   | 1         | 0.18%   |
| hr_BA   | 1         | 0.18%   |
| fr_FR   | 1         | 0.18%   |
| en_DE   | 1         | 0.18%   |
| en_150  | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 320       | 56.14%  |
| BIOS | 250       | 43.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 439       | 76.35%  |
| Btrfs   | 54        | 9.39%   |
| Overlay | 34        | 5.91%   |
| Unknown | 21        | 3.65%   |
| Zfs     | 9         | 1.57%   |
| Tmpfs   | 9         | 1.57%   |
| Xfs     | 7         | 1.22%   |
| Jfs     | 1         | 0.17%   |
| Ext2    | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 271       | 47.71%  |
| GPT     | 236       | 41.55%  |
| MBR     | 61        | 10.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 499       | 87.39%  |
| Yes       | 72        | 12.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 414       | 73.02%  |
| Yes       | 153       | 26.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 101       | 18.13%  |
| Hewlett-Packard         | 89        | 15.98%  |
| ASUSTek Computer        | 89        | 15.98%  |
| Acer                    | 61        | 10.95%  |
| Dell                    | 48        | 8.62%   |
| ASRock                  | 40        | 7.18%   |
| Gigabyte Technology     | 32        | 5.75%   |
| MSI                     | 16        | 2.87%   |
| Intel                   | 10        | 1.8%    |
| Apple                   | 9         | 1.62%   |
| Toshiba                 | 7         | 1.26%   |
| Pegatron                | 5         | 0.9%    |
| Tactus                  | 4         | 0.72%   |
| Samsung Electronics     | 4         | 0.72%   |
| Raspberry Pi Foundation | 4         | 0.72%   |
| Fujitsu Siemens         | 4         | 0.72%   |
| eMachines               | 4         | 0.72%   |
| HUAWEI                  | 3         | 0.54%   |
| ECS                     | 3         | 0.54%   |
| Unknown                 | 3         | 0.54%   |
| TUXEDO                  | 2         | 0.36%   |
| Supermicro              | 2         | 0.36%   |
| WinFast                 | 1         | 0.18%   |
| Valve                   | 1         | 0.18%   |
| Timi                    | 1         | 0.18%   |
| System76                | 1         | 0.18%   |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.18%   |
| Schenker                | 1         | 0.18%   |
| Razer                   | 1         | 0.18%   |
| Pretech                 | 1         | 0.18%   |
| Nvidia                  | 1         | 0.18%   |
| Notebook                | 1         | 0.18%   |
| Medion                  | 1         | 0.18%   |
| HPE                     | 1         | 0.18%   |
| Foxconn                 | 1         | 0.18%   |
| Dynabook                | 1         | 0.18%   |
| Chuwi                   | 1         | 0.18%   |
| AMI                     | 1         | 0.18%   |
| ABIT                    | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 6         | 1.08%   |
| Unknown                                  | 5         | 0.9%    |
| Tactus GeoBook 140                       | 4         | 0.72%   |
| ASRock B450M-HDV R4.0                    | 4         | 0.72%   |
| Acer Aspire A315-21                      | 4         | 0.72%   |
| Lenovo Legion 5 15ARH05 82B5             | 3         | 0.54%   |
| Lenovo G710 20252                        | 3         | 0.54%   |
| ASUS PRIME A320M-K                       | 3         | 0.54%   |
| Acer Aspire A515-51G                     | 3         | 0.54%   |
| TUXEDO Pulse 15 Gen1                     | 2         | 0.36%   |
| RPi Raspberry Pi 4 Model B Rev 1.1       | 2         | 0.36%   |
| MSI MS-7850                              | 2         | 0.36%   |
| Lenovo Z50-70 20354                      | 2         | 0.36%   |
| Lenovo ThinkBook 16p Gen 2 20YM          | 2         | 0.36%   |
| Lenovo ThinkBook 15 G2 ITL 20VE          | 2         | 0.36%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ         | 2         | 0.36%   |
| Lenovo G40-30 80FY                       | 2         | 0.36%   |
| Intel DH61CR AAG14064-204                | 2         | 0.36%   |
| HP ProBook 450 G7                        | 2         | 0.36%   |
| HP Presario CQ57                         | 2         | 0.36%   |
| HP OMEN by Laptop                        | 2         | 0.36%   |
| HP Notebook                              | 2         | 0.36%   |
| HP Laptop 15s-eq2xxx                     | 2         | 0.36%   |
| HP EliteBook 8560p                       | 2         | 0.36%   |
| HP EliteBook 850 G6                      | 2         | 0.36%   |
| HP EliteBook 845 G8 Notebook PC          | 2         | 0.36%   |
| HP 2000                                  | 2         | 0.36%   |
| Gigabyte A320M-S2H                       | 2         | 0.36%   |
| Fujitsu Siemens ESPRIMO Mobile V5535     | 2         | 0.36%   |
| Dell XPS 13 9310                         | 2         | 0.36%   |
| Dell Vostro 3500                         | 2         | 0.36%   |
| Dell Inspiron N5110                      | 2         | 0.36%   |
| Dell Inspiron 5570                       | 2         | 0.36%   |
| Dell Inspiron 3542                       | 2         | 0.36%   |
| ASUS X751NV                              | 2         | 0.36%   |
| ASUS VivoBook_ASUSLaptop X705FD_N705FD   | 2         | 0.36%   |
| ASUS VivoBook_ASUSLaptop M3500QA_M3500QA | 2         | 0.36%   |
| ASUS VivoBook 15_ASUS Laptop X560UD      | 2         | 0.36%   |
| ASUS VivoBook 15_ASUS Laptop X540BP      | 2         | 0.36%   |
| ASUS P8H77-V LE                          | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 43        | 7.72%   |
| Lenovo ThinkPad   | 39        | 7%      |
| HP EliteBook      | 17        | 3.05%   |
| ASUS VivoBook     | 13        | 2.33%   |
| HP ProBook        | 11        | 1.97%   |
| HP Pavilion       | 11        | 1.97%   |
| Dell Latitude     | 11        | 1.97%   |
| Dell Inspiron     | 11        | 1.97%   |
| Lenovo IdeaPad    | 10        | 1.8%    |
| Dell Vostro       | 10        | 1.8%    |
| Lenovo Legion     | 9         | 1.62%   |
| HP Laptop         | 9         | 1.62%   |
| ASUS PRIME        | 9         | 1.62%   |
| Acer Swift        | 8         | 1.44%   |
| Lenovo ThinkBook  | 7         | 1.26%   |
| Dell XPS          | 7         | 1.26%   |
| ASUS ZenBook      | 7         | 1.26%   |
| ASUS TUF          | 7         | 1.26%   |
| ASUS ROG          | 7         | 1.26%   |
| Toshiba Satellite | 6         | 1.08%   |
| HP Compaq         | 6         | 1.08%   |
| ASUS All          | 6         | 1.08%   |
| Lenovo Yoga       | 5         | 0.9%    |
| HP OMEN           | 5         | 0.9%    |
| Unknown           | 5         | 0.9%    |
| Tactus GeoBook    | 4         | 0.72%   |
| RPi Raspberry     | 4         | 0.72%   |
| HP ZBook          | 4         | 0.72%   |
| HP 250            | 4         | 0.72%   |
| ASUS ASUS         | 4         | 0.72%   |
| ASRock B450M-HDV  | 4         | 0.72%   |
| Acer Nitro        | 4         | 0.72%   |
| Lenovo IdeaCentre | 3         | 0.54%   |
| Lenovo G710       | 3         | 0.54%   |
| HP ProDesk        | 3         | 0.54%   |
| HP EliteDesk      | 3         | 0.54%   |
| Dell OptiPlex     | 3         | 0.54%   |
| TUXEDO Pulse      | 2         | 0.36%   |
| MSI MS-7850       | 2         | 0.36%   |
| Lenovo Z50-70     | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 61        | 10.95%  |
| 2021    | 56        | 10.05%  |
| 2020    | 54        | 9.69%   |
| 2017    | 49        | 8.8%    |
| 2013    | 41        | 7.36%   |
| 2019    | 38        | 6.82%   |
| 2011    | 36        | 6.46%   |
| 2012    | 34        | 6.1%    |
| 2014    | 33        | 5.92%   |
| 2022    | 25        | 4.49%   |
| 2016    | 23        | 4.13%   |
| 2008    | 19        | 3.41%   |
| 2007    | 18        | 3.23%   |
| 2015    | 17        | 3.05%   |
| 2009    | 17        | 3.05%   |
| 2010    | 14        | 2.51%   |
| 2023    | 9         | 1.62%   |
| Unknown | 6         | 1.08%   |
| 2006    | 5         | 0.9%    |
| 2005    | 2         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 356       | 63.91%  |
| Desktop        | 172       | 30.88%  |
| All in one     | 7         | 1.26%   |
| Convertible    | 6         | 1.08%   |
| System on chip | 5         | 0.9%    |
| Mini pc        | 5         | 0.9%    |
| Server         | 4         | 0.72%   |
| Stick pc       | 1         | 0.18%   |
| Tablet         | 1         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 506       | 90.04%  |
| Enabled  | 56        | 9.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 557       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 129       | 22.75%  |
| 8.01-16.0   | 126       | 22.22%  |
| 16.01-24.0  | 106       | 18.69%  |
| 3.01-4.0    | 93        | 16.4%   |
| 32.01-64.0  | 55        | 9.7%    |
| 1.01-2.0    | 22        | 3.88%   |
| 24.01-32.0  | 20        | 3.53%   |
| 64.01-256.0 | 10        | 1.76%   |
| 2.01-3.0    | 6         | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 204       | 32.28%  |
| 2.01-3.0   | 162       | 25.63%  |
| 4.01-8.0   | 108       | 17.09%  |
| 3.01-4.0   | 86        | 13.61%  |
| 8.01-16.0  | 33        | 5.22%   |
| 0.51-1.0   | 28        | 4.43%   |
| 16.01-24.0 | 6         | 0.95%   |
| 0.01-0.5   | 4         | 0.63%   |
| 24.01-32.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 352       | 60.9%   |
| 2       | 137       | 23.7%   |
| 3       | 46        | 7.96%   |
| 4       | 17        | 2.94%   |
| 5       | 12        | 2.08%   |
| 0       | 6         | 1.04%   |
| 6       | 4         | 0.69%   |
| 14      | 1         | 0.17%   |
| 8       | 1         | 0.17%   |
| 7       | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 373       | 66.49%  |
| Yes       | 188       | 33.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 472       | 84.59%  |
| No        | 86        | 15.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 438       | 78.35%  |
| No        | 121       | 21.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 356       | 63.01%  |
| No        | 209       | 36.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Croatia | 557       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Zagreb           | 331       | 52.21%  |
| Split            | 36        | 5.68%   |
| Rijeka           | 28        | 4.42%   |
| Varaždin        | 14        | 2.21%   |
| Pula             | 11        | 1.74%   |
| Osijek           | 11        | 1.74%   |
| Velika Gorica    | 10        | 1.58%   |
| Koprivnica       | 10        | 1.58%   |
| Bjelovar         | 8         | 1.26%   |
| Zaprešić       | 7         | 1.1%    |
| Zadar            | 7         | 1.1%    |
| Čakovec         | 7         | 1.1%    |
| Virovitica       | 5         | 0.79%   |
| Samobor          | 5         | 0.79%   |
| Pitomaca         | 4         | 0.63%   |
| Kastav           | 4         | 0.63%   |
| Jesenice         | 4         | 0.63%   |
| Đakovo          | 3         | 0.47%   |
| Vinkovci         | 3         | 0.47%   |
| Sisak            | 3         | 0.47%   |
| Petrinja         | 3         | 0.47%   |
| Krizevci         | 3         | 0.47%   |
| Karlovac         | 3         | 0.47%   |
| GJurgevac        | 3         | 0.47%   |
| Visnjevac        | 2         | 0.32%   |
| Supetar          | 2         | 0.32%   |
| Slatina          | 2         | 0.32%   |
| Šibenik         | 2         | 0.32%   |
| Sesvete          | 2         | 0.32%   |
| Rovinj           | 2         | 0.32%   |
| Omiš            | 2         | 0.32%   |
| Novska           | 2         | 0.32%   |
| Matulji          | 2         | 0.32%   |
| Labin            | 2         | 0.32%   |
| Komiža          | 2         | 0.32%   |
| Ivanja Reka      | 2         | 0.32%   |
| Hvar             | 2         | 0.32%   |
| Dugo Selo        | 2         | 0.32%   |
| Drakulica Rijeka | 2         | 0.32%   |
| Cres             | 2         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 133       | 207    | 16.46%  |
| Samsung Electronics         | 115       | 161    | 14.23%  |
| Kingston                    | 84        | 126    | 10.4%   |
| Seagate                     | 69        | 111    | 8.54%   |
| Toshiba                     | 56        | 86     | 6.93%   |
| SanDisk                     | 39        | 48     | 4.83%   |
| SK hynix                    | 35        | 50     | 4.33%   |
| Crucial                     | 33        | 48     | 4.08%   |
| Intel                       | 28        | 37     | 3.47%   |
| Micron Technology           | 26        | 31     | 3.22%   |
| Unknown                     | 22        | 25     | 2.72%   |
| A-DATA Technology           | 18        | 22     | 2.23%   |
| Hitachi                     | 16        | 20     | 1.98%   |
| HGST                        | 12        | 12     | 1.49%   |
| Patriot                     | 11        | 15     | 1.36%   |
| Apple                       | 11        | 19     | 1.36%   |
| Netac                       | 7         | 7      | 0.87%   |
| Silicon Motion              | 6         | 8      | 0.74%   |
| Transcend                   | 5         | 10     | 0.62%   |
| Phison                      | 5         | 5      | 0.62%   |
| Fujitsu                     | 5         | 7      | 0.62%   |
| LITEON                      | 4         | 5      | 0.5%    |
| KIOXIA                      | 4         | 4      | 0.5%    |
| SPCC                        | 3         | 3      | 0.37%   |
| Phison Electronics          | 3         | 4      | 0.37%   |
| Micron/Crucial Technology   | 3         | 3      | 0.37%   |
| Gigabyte Technology         | 3         | 3      | 0.37%   |
| Corsair                     | 3         | 3      | 0.37%   |
| UMIS                        | 2         | 2      | 0.25%   |
| StoreJet                    | 2         | 2      | 0.25%   |
| Realtek Semiconductor       | 2         | 4      | 0.25%   |
| OCZ                         | 2         | 3      | 0.25%   |
| Maxtor                      | 2         | 2      | 0.25%   |
| Lenovo                      | 2         | 3      | 0.25%   |
| Kingston Technology Company | 2         | 2      | 0.25%   |
| KingFast                    | 2         | 4      | 0.25%   |
| JMicron Technology          | 2         | 2      | 0.25%   |
| Intenso                     | 2         | 3      | 0.25%   |
| HPE                         | 2         | 4      | 0.25%   |
| External                    | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 14        | 1.6%    |
| Kingston SA400S37120G 120GB SSD                    | 12        | 1.37%   |
| Samsung NVMe SSD Drive 512GB                       | 9         | 1.03%   |
| Kingston SA400S37480G 480GB SSD                    | 9         | 1.03%   |
| Toshiba MQ01ABD100 1TB                             | 8         | 0.92%   |
| Samsung SSD 850 EVO 250GB                          | 7         | 0.8%    |
| SanDisk NVMe SSD Drive 512GB                       | 6         | 0.69%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 6         | 0.69%   |
| HGST HTS721010A9E630 1TB                           | 6         | 0.69%   |
| Crucial CT240BX500SSD1 240GB                       | 6         | 0.69%   |
| WDC WD10EZEX-08M2NA0 1TB                           | 5         | 0.57%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                 | 5         | 0.57%   |
| Toshiba HDWD130 3TB                                | 5         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 5         | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5         | 0.57%   |
| Netac SSD 128GB                                    | 5         | 0.57%   |
| Kingston SV300S37A120G 120GB SSD                   | 5         | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 4         | 0.46%   |
| Unknown MMC Card  32GB                             | 4         | 0.46%   |
| Toshiba HDWD110 1TB                                | 4         | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                    | 4         | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB                     | 4         | 0.46%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 4         | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB                       | 4         | 0.46%   |
| Samsung SSD 860 QVO 1TB                            | 4         | 0.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 4         | 0.46%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 4         | 0.46%   |
| Patriot Burst 240GB SSD                            | 4         | 0.46%   |
| Kingston SKC3000S1024G 1TB                         | 4         | 0.46%   |
| A-DATA SU650 240GB SSD                             | 4         | 0.46%   |
| A-DATA SU630 240GB SSD                             | 4         | 0.46%   |
| WDC WD5000AAKX-001CA0 500GB                        | 3         | 0.34%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 3         | 0.34%   |
| Unknown SD/MMC/MS PRO 128GB                        | 3         | 0.34%   |
| Unknown MMC Card  128GB                            | 3         | 0.34%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 0.34%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 0.34%   |
| Toshiba DT01ACA200 2TB                             | 3         | 0.34%   |
| Toshiba DT01ACA100 1TB                             | 3         | 0.34%   |
| SK hynix NVMe SSD Drive 512GB                      | 3         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 108       | 168    | 39.13%  |
| Seagate             | 67        | 98     | 24.28%  |
| Toshiba             | 46        | 70     | 16.67%  |
| Hitachi             | 16        | 20     | 5.8%    |
| HGST                | 12        | 12     | 4.35%   |
| Samsung Electronics | 10        | 13     | 3.62%   |
| Fujitsu             | 5         | 7      | 1.81%   |
| Unknown             | 3         | 3      | 1.09%   |
| Maxtor              | 2         | 2      | 0.72%   |
| TO Exter            | 1         | 1      | 0.36%   |
| Min Yi U            | 1         | 1      | 0.36%   |
| JMicron Technology  | 1         | 1      | 0.36%   |
| Intenso             | 1         | 2      | 0.36%   |
| HPE                 | 1         | 2      | 0.36%   |
| HGST HTS            | 1         | 1      | 0.36%   |
| ASMedia             | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 68        | 93     | 25.19%  |
| Samsung Electronics | 41        | 60     | 15.19%  |
| Crucial             | 27        | 39     | 10%     |
| SanDisk             | 18        | 25     | 6.67%   |
| A-DATA Technology   | 16        | 19     | 5.93%   |
| Intel               | 13        | 17     | 4.81%   |
| WDC                 | 10        | 12     | 3.7%    |
| Patriot             | 10        | 14     | 3.7%    |
| Micron Technology   | 10        | 11     | 3.7%    |
| SK hynix            | 8         | 14     | 2.96%   |
| Apple               | 8         | 12     | 2.96%   |
| Netac               | 6         | 6      | 2.22%   |
| Transcend           | 3         | 4      | 1.11%   |
| SPCC                | 3         | 3      | 1.11%   |
| LITEON              | 3         | 4      | 1.11%   |
| Gigabyte Technology | 3         | 3      | 1.11%   |
| Toshiba             | 2         | 4      | 0.74%   |
| StoreJet            | 2         | 2      | 0.74%   |
| OCZ                 | 2         | 3      | 0.74%   |
| External            | 2         | 2      | 0.74%   |
| AMD                 | 2         | 5      | 0.74%   |
| SSK                 | 1         | 1      | 0.37%   |
| Seagate             | 1         | 1      | 0.37%   |
| PNY                 | 1         | 1      | 0.37%   |
| Phison              | 1         | 1      | 0.37%   |
| Mushkin             | 1         | 2      | 0.37%   |
| KingSpec            | 1         | 1      | 0.37%   |
| Kingmax             | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| INNOVATION IT       | 1         | 1      | 0.37%   |
| GOODRAM             | 1         | 1      | 0.37%   |
| Emtec               | 1         | 1      | 0.37%   |
| Corsair             | 1         | 1      | 0.37%   |
| China               | 1         | 2      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 238       | 402    | 32.92%  |
| SSD     | 232       | 367    | 32.09%  |
| NVMe    | 222       | 329    | 30.71%  |
| MMC     | 19        | 22     | 2.63%   |
| Unknown | 12        | 25     | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 378       | 750    | 58.7%   |
| NVMe | 222       | 329    | 34.47%  |
| SAS  | 25        | 44     | 3.88%   |
| MMC  | 19        | 22     | 2.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 295       | 471    | 60.95%  |
| 0.51-1.0   | 129       | 187    | 26.65%  |
| 1.01-2.0   | 31        | 54     | 6.4%    |
| 2.01-3.0   | 15        | 33     | 3.1%    |
| 3.01-4.0   | 11        | 20     | 2.27%   |
| 4.01-10.0  | 3         | 4      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 169       | 28.45%  |
| 251-500        | 138       | 23.23%  |
| 501-1000       | 90        | 15.15%  |
| 1001-2000      | 60        | 10.1%   |
| 1-20           | 34        | 5.72%   |
| 51-100         | 33        | 5.56%   |
| More than 3000 | 26        | 4.38%   |
| 21-50          | 17        | 2.86%   |
| Unknown        | 17        | 2.86%   |
| 2001-3000      | 10        | 1.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 228       | 36.25%  |
| 21-50          | 117       | 18.6%   |
| 101-250        | 71        | 11.29%  |
| 51-100         | 63        | 10.02%  |
| 251-500        | 54        | 8.59%   |
| 501-1000       | 46        | 7.31%   |
| 1001-2000      | 18        | 2.86%   |
| Unknown        | 17        | 2.7%    |
| More than 3000 | 8         | 1.27%   |
| 2001-3000      | 7         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB             | 3         | 3      | 5.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 4      | 3.64%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 1.82%   |
| WDC WD6400AAKS-07A7B0 640GB          | 1         | 1      | 1.82%   |
| WDC WD600VE-75HDT0 64GB              | 1         | 1      | 1.82%   |
| WDC WD5003ABYX-88 LEN 500GB          | 1         | 1      | 1.82%   |
| WDC WD5000AAKX-221CA1 500GB          | 1         | 1      | 1.82%   |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 1      | 1.82%   |
| WDC WD3200AAKS-00L9A0 320GB          | 1         | 1      | 1.82%   |
| WDC WD2500AAKX-75U6AA0 250GB         | 1         | 1      | 1.82%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1      | 1.82%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 1      | 1.82%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 1      | 1.82%   |
| WDC WD10EZEX-00MFCA0 1TB             | 1         | 1      | 1.82%   |
| Transcend TS480GSSD220S 480GB        | 1         | 1      | 1.82%   |
| Toshiba MK6459GSXP 640GB             | 1         | 1      | 1.82%   |
| Toshiba MK2555GSX 250GB              | 1         | 1      | 1.82%   |
| Toshiba MK2552GSX 250GB              | 1         | 1      | 1.82%   |
| Toshiba DT01ACA100 1TB               | 1         | 1      | 1.82%   |
| SPCC Solid State Disk 128GB          | 1         | 1      | 1.82%   |
| SK hynix SH920 2.5 7MM 256GB SSD     | 1         | 2      | 1.82%   |
| SK hynix SC210 2.5 7MM 256GB SSD     | 1         | 1      | 1.82%   |
| Seagate ST9500420AS 500GB            | 1         | 2      | 1.82%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 1.82%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 1.82%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 2      | 1.82%   |
| Seagate ST3250410AS 250GB            | 1         | 1      | 1.82%   |
| Seagate ST31500341AS 1TB             | 1         | 1      | 1.82%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1      | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 1.82%   |
| Seagate ST1000DX002-2DV162 1TB       | 1         | 1      | 1.82%   |
| SanDisk SDSSDXPS960G 960GB           | 1         | 1      | 1.82%   |
| SanDisk SDSSDA240G 240GB             | 1         | 1      | 1.82%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD  | 1         | 1      | 1.82%   |
| Samsung Electronics HD161HJ 160GB    | 1         | 1      | 1.82%   |
| LITEON LMH-256V2M-11 MSATA 256GB SSD | 1         | 1      | 1.82%   |
| Kingston SKC2500M8500G 500GB         | 1         | 1      | 1.82%   |
| Kingston SHFS37A120G 120GB SSD       | 1         | 1      | 1.82%   |
| Intel SSDSC2KW512G8 512GB            | 1         | 1      | 1.82%   |
| Intel SSDSC2KF256H6 SATA 256GB       | 1         | 2      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 22.64%  |
| Seagate             | 10        | 15     | 18.87%  |
| HGST                | 5         | 5      | 9.43%   |
| Toshiba             | 4         | 4      | 7.55%   |
| Intel               | 4         | 5      | 7.55%   |
| Hitachi             | 3         | 3      | 5.66%   |
| Crucial             | 3         | 4      | 5.66%   |
| SK hynix            | 2         | 3      | 3.77%   |
| SanDisk             | 2         | 3      | 3.77%   |
| Kingston            | 2         | 2      | 3.77%   |
| A-DATA Technology   | 2         | 2      | 3.77%   |
| Transcend           | 1         | 1      | 1.89%   |
| SPCC                | 1         | 1      | 1.89%   |
| Samsung Electronics | 1         | 1      | 1.89%   |
| LITEON              | 1         | 1      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 32.35%  |
| Seagate             | 10        | 15     | 29.41%  |
| HGST                | 5         | 5      | 14.71%  |
| Toshiba             | 4         | 4      | 11.76%  |
| Hitachi             | 3         | 3      | 8.82%   |
| Samsung Electronics | 1         | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 39     | 64.71%  |
| SSD  | 17        | 22     | 33.33%  |
| NVMe | 1         | 1      | 1.96%   |

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
| Detected | 318       | 635    | 52.65%  |
| Works    | 238       | 448    | 39.4%   |
| Malfunc  | 48        | 62     | 7.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 361       | 49.45%  |
| AMD                              | 109       | 14.93%  |
| Samsung Electronics              | 73        | 10%     |
| SanDisk                          | 37        | 5.07%   |
| SK hynix                         | 27        | 3.7%    |
| Kingston Technology Company      | 23        | 3.15%   |
| Micron Technology                | 16        | 2.19%   |
| Toshiba America Info Systems     | 10        | 1.37%   |
| Phison Electronics               | 10        | 1.37%   |
| Micron/Crucial Technology        | 8         | 1.1%    |
| Silicon Motion                   | 6         | 0.82%   |
| Nvidia                           | 6         | 0.82%   |
| JMicron Technology               | 6         | 0.82%   |
| Marvell Technology Group         | 5         | 0.68%   |
| ASMedia Technology               | 5         | 0.68%   |
| ADATA Technology                 | 5         | 0.68%   |
| KIOXIA                           | 4         | 0.55%   |
| VIA Technologies                 | 2         | 0.27%   |
| Union Memory (Shenzhen)          | 2         | 0.27%   |
| Silicon Integrated Systems [SiS] | 2         | 0.27%   |
| Realtek Semiconductor            | 2         | 0.27%   |
| Lite-On Technology               | 2         | 0.27%   |
| Lenovo                           | 2         | 0.27%   |
| Broadcom / LSI                   | 2         | 0.27%   |
| Transcend                        | 1         | 0.14%   |
| Silicon Image                    | 1         | 0.14%   |
| Seagate Technology               | 1         | 0.14%   |
| LSI Logic / Symbios Logic        | 1         | 0.14%   |
| Adaptec                          | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 75        | 8.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 35        | 4.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 35        | 4.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 26        | 3.11%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 24        | 2.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 2.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 20        | 2.39%   |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 2.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 1.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 13        | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 13        | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 12        | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 11        | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 11        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 1.2%    |
| Intel Tiger Lake-LP SATA Controller                                            | 10        | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 10        | 1.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 1.2%    |
| AMD FCH SATA Controller D                                                      | 10        | 1.2%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 9         | 1.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 9         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 1.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8         | 0.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 0.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7         | 0.84%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 7         | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 0.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 6         | 0.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 0.72%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 5         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 404       | 54.37%  |
| NVMe | 222       | 29.88%  |
| IDE  | 77        | 10.36%  |
| RAID | 39        | 5.25%   |
| SAS  | 1         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 399       | 71.63%  |
| AMD     | 151       | 27.11%  |
| ARM     | 5         | 0.9%    |
| Unknown | 2         | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 2.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 1.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 1.25%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 7         | 1.25%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.07%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.89%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.89%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.89%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.89%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 5         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.71%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.71%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 0.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.71%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.71%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.54%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.54%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 0.54%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.54%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.54%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 3         | 0.54%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 3         | 0.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.54%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3         | 0.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.54%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 3         | 0.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 131       | 23.39%  |
| Intel Core i7           | 73        | 13.04%  |
| Other                   | 50        | 8.93%   |
| Intel Core i3           | 41        | 7.32%   |
| AMD Ryzen 7             | 38        | 6.79%   |
| AMD Ryzen 5             | 36        | 6.43%   |
| Intel Core 2 Duo        | 29        | 5.18%   |
| Intel Pentium           | 22        | 3.93%   |
| Intel Celeron           | 16        | 2.86%   |
| AMD Ryzen 9             | 11        | 1.96%   |
| AMD Ryzen 3             | 11        | 1.96%   |
| Intel Atom              | 8         | 1.43%   |
| Intel Core i9           | 7         | 1.25%   |
| Intel Xeon              | 6         | 1.07%   |
| Intel Pentium Dual-Core | 6         | 1.07%   |
| Intel Pentium Dual      | 6         | 1.07%   |
| AMD Ryzen 5 PRO         | 5         | 0.89%   |
| AMD FX                  | 5         | 0.89%   |
| AMD E                   | 5         | 0.89%   |
| AMD A6                  | 5         | 0.89%   |
| AMD Athlon II X4        | 4         | 0.71%   |
| Intel Pentium Silver    | 3         | 0.54%   |
| Intel Core 2            | 3         | 0.54%   |
| AMD Ryzen 7 PRO         | 3         | 0.54%   |
| AMD Phenom II X4        | 3         | 0.54%   |
| AMD Athlon X4           | 3         | 0.54%   |
| AMD Athlon 64 X2        | 3         | 0.54%   |
| Intel Pentium M         | 2         | 0.36%   |
| Intel Pentium 4         | 2         | 0.36%   |
| Intel Core 2 Quad       | 2         | 0.36%   |
| ARM BCM                 | 2         | 0.36%   |
| AMD E1                  | 2         | 0.36%   |
| AMD Athlon              | 2         | 0.36%   |
| AMD A8                  | 2         | 0.36%   |
| Intel Xeon Bronze       | 1         | 0.18%   |
| Intel Genuine           | 1         | 0.18%   |
| Intel Celeron M         | 1         | 0.18%   |
| AMD Turion 64 X2 Mobile | 1         | 0.18%   |
| AMD Ryzen Threadripper  | 1         | 0.18%   |
| AMD Ryzen 3 PRO         | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 209       | 37.32%  |
| 4       | 200       | 35.71%  |
| 8       | 56        | 10%     |
| 6       | 54        | 9.64%   |
| 1       | 9         | 1.61%   |
| 12      | 7         | 1.25%   |
| 10      | 7         | 1.25%   |
| 14      | 5         | 0.89%   |
| 16      | 4         | 0.71%   |
| 24      | 3         | 0.54%   |
| 3       | 3         | 0.54%   |
| 20      | 1         | 0.18%   |
| 18      | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 553       | 99.28%  |
| 2       | 3         | 0.54%   |
| Unknown | 1         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 370       | 66.31%  |
| 1       | 187       | 33.51%  |
| Unknown | 1         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 538       | 96.24%  |
| Unknown        | 14        | 2.5%    |
| 32-bit         | 5         | 0.89%   |
| 64-bit         | 2         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 162       | 27.5%   |
| 0x306c3    | 38        | 6.45%   |
| 0x206a7    | 21        | 3.57%   |
| 0x306a9    | 20        | 3.4%    |
| 0x906ea    | 18        | 3.06%   |
| 0x806ea    | 17        | 2.89%   |
| 0x806e9    | 17        | 2.89%   |
| 0x40651    | 14        | 2.38%   |
| 0x1067a    | 14        | 2.38%   |
| 0x0a50000c | 13        | 2.21%   |
| 0x806ec    | 12        | 2.04%   |
| 0x6fd      | 12        | 2.04%   |
| 0x806c1    | 11        | 1.87%   |
| 0x08600106 | 9         | 1.53%   |
| 0x08108109 | 9         | 1.53%   |
| 0x906e9    | 8         | 1.36%   |
| 0xa0652    | 6         | 1.02%   |
| 0x306d4    | 6         | 1.02%   |
| 0x08608103 | 6         | 1.02%   |
| 0x08600103 | 6         | 1.02%   |
| 0x0810100b | 6         | 1.02%   |
| 0xa0653    | 5         | 0.85%   |
| 0x906ed    | 5         | 0.85%   |
| 0x506e3    | 5         | 0.85%   |
| 0x30678    | 5         | 0.85%   |
| 0x0a50000d | 5         | 0.85%   |
| 0x0800820d | 5         | 0.85%   |
| 0x06006705 | 5         | 0.85%   |
| 0x6fb      | 4         | 0.68%   |
| 0x506c9    | 4         | 0.68%   |
| 0x406e3    | 4         | 0.68%   |
| 0x406c4    | 4         | 0.68%   |
| 0x20655    | 4         | 0.68%   |
| 0x10676    | 4         | 0.68%   |
| 0x0a601203 | 4         | 0.68%   |
| 0x08108102 | 4         | 0.68%   |
| 0x010000db | 4         | 0.68%   |
| 0x010000c8 | 4         | 0.68%   |
| 0xa0671    | 3         | 0.51%   |
| 0x906a3    | 3         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 100       | 17.92%  |
| Haswell          | 65        | 11.65%  |
| Unknown          | 38        | 6.81%   |
| Zen 2            | 27        | 4.84%   |
| SandyBridge      | 26        | 4.66%   |
| IvyBridge        | 26        | 4.66%   |
| Zen 3            | 24        | 4.3%    |
| Penryn           | 24        | 4.3%    |
| Core             | 22        | 3.94%   |
| Zen+             | 21        | 3.76%   |
| TigerLake        | 19        | 3.41%   |
| Skylake          | 18        | 3.23%   |
| Silvermont       | 14        | 2.51%   |
| CometLake        | 14        | 2.51%   |
| Alderlake Hybrid | 14        | 2.51%   |
| Zen              | 13        | 2.33%   |
| Broadwell        | 11        | 1.97%   |
| Icelake          | 10        | 1.79%   |
| K10              | 9         | 1.61%   |
| Piledriver       | 8         | 1.43%   |
| Goldmont plus    | 8         | 1.43%   |
| Excavator        | 8         | 1.43%   |
| Westmere         | 7         | 1.25%   |
| Bobcat           | 6         | 1.08%   |
| K8 Hammer        | 5         | 0.9%    |
| Goldmont         | 5         | 0.9%    |
| P6               | 4         | 0.72%   |
| Bulldozer        | 3         | 0.54%   |
| NetBurst         | 2         | 0.36%   |
| Bonnell          | 2         | 0.36%   |
| Tremont          | 1         | 0.18%   |
| Steamroller      | 1         | 0.18%   |
| Puma             | 1         | 0.18%   |
| Nehalem          | 1         | 0.18%   |
| Jaguar           | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 307       | 44.24%  |
| Nvidia                           | 192       | 27.67%  |
| AMD                              | 187       | 26.95%  |
| Matrox Electronics Systems       | 4         | 0.58%   |
| Silicon Integrated Systems [SiS] | 2         | 0.29%   |
| VIA Technologies                 | 1         | 0.14%   |
| ATI Technologies                 | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 25        | 3.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 2.83%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 19        | 2.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 2.55%   |
| Intel HD Graphics 620                                                                    | 18        | 2.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 1.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 1.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 13        | 1.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 1.42%   |
| AMD Lucienne                                                                             | 10        | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 1.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 7         | 0.99%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.99%   |
| Intel HD Graphics 5500                                                                   | 7         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 0.99%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 0.85%   |
| Intel HD Graphics 530                                                                    | 6         | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.85%   |
| AMD Raphael                                                                              | 6         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.71%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.71%   |
| Intel HD Graphics 630                                                                    | 5         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.71%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.71%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.71%   |
| AMD Rembrandt [Radeon 680M]                                                              | 5         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 189       | 33.39%  |
| 1 x AMD         | 137       | 24.2%   |
| Intel + Nvidia  | 87        | 15.37%  |
| 1 x Nvidia      | 86        | 15.19%  |
| Intel + AMD     | 25        | 4.42%   |
| AMD + Nvidia    | 18        | 3.18%   |
| Other           | 7         | 1.24%   |
| 2 x AMD         | 7         | 1.24%   |
| 2 x Intel       | 3         | 0.53%   |
| 1 x Matrox      | 3         | 0.53%   |
| 1 x SiS         | 2         | 0.35%   |
| 1 x VIA         | 1         | 0.18%   |
| Nvidia + Matrox | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 432       | 76.19%  |
| Proprietary | 112       | 19.75%  |
| Unknown     | 23        | 4.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 292       | 50.43%  |
| 1.01-2.0   | 85        | 14.68%  |
| 0.01-0.5   | 66        | 11.4%   |
| 3.01-4.0   | 50        | 8.64%   |
| 0.51-1.0   | 47        | 8.12%   |
| 7.01-8.0   | 22        | 3.8%    |
| 5.01-6.0   | 8         | 1.38%   |
| 8.01-16.0  | 5         | 0.86%   |
| 2.01-3.0   | 4         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 94        | 14.66%  |
| AU Optronics            | 78        | 12.17%  |
| Dell                    | 63        | 9.83%   |
| BOE                     | 61        | 9.52%   |
| LG Display              | 58        | 9.05%   |
| Chimei Innolux          | 52        | 8.11%   |
| AOC                     | 30        | 4.68%   |
| Goldstar                | 28        | 4.37%   |
| Philips                 | 20        | 3.12%   |
| Acer                    | 20        | 3.12%   |
| Lenovo                  | 15        | 2.34%   |
| Hewlett-Packard         | 11        | 1.72%   |
| Sharp                   | 10        | 1.56%   |
| Ancor Communications    | 10        | 1.56%   |
| Apple                   | 9         | 1.4%    |
| PANDA                   | 7         | 1.09%   |
| BenQ                    | 7         | 1.09%   |
| CSO                     | 6         | 0.94%   |
| Chi Mei Optoelectronics | 5         | 0.78%   |
| LG Philips              | 4         | 0.62%   |
| Grundig                 | 4         | 0.62%   |
| ASUSTek Computer        | 4         | 0.62%   |
| Unknown                 | 3         | 0.47%   |
| Sony                    | 3         | 0.47%   |
| LG Electronics          | 3         | 0.47%   |
| InfoVision              | 3         | 0.47%   |
| Fujitsu Siemens         | 3         | 0.47%   |
| TMX                     | 2         | 0.31%   |
| Quanta Display          | 2         | 0.31%   |
| Panasonic               | 2         | 0.31%   |
| InnoLux Display         | 2         | 0.31%   |
| Huion                   | 2         | 0.31%   |
| Vestel Elektronik       | 1         | 0.16%   |
| Valve                   | 1         | 0.16%   |
| TSL                     | 1         | 0.16%   |
| RTK                     | 1         | 0.16%   |
| NOA VISION              | 1         | 0.16%   |
| NEC Computers           | 1         | 0.16%   |
| NCS                     | 1         | 0.16%   |
| MStar                   | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 1.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 6         | 0.9%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.6%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.6%    |
| Grundig WXGA GRU4448 1600x1200                                        | 4         | 0.6%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.6%    |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 4         | 0.6%    |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 4         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.45%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 3         | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.45%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 3         | 0.45%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 3         | 0.45%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                     | 3         | 0.45%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                     | 3         | 0.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.45%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 3         | 0.45%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.3%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.3%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.3%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                     | 2         | 0.3%    |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch      | 2         | 0.3%    |
| Philips 190C PHLC017 1280x1024 338x270mm 17.0-inch                    | 2         | 0.3%    |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 288       | 47.37%  |
| 1366x768 (WXGA)    | 68        | 11.18%  |
| 3840x2160 (4K)     | 39        | 6.41%   |
| 2560x1440 (QHD)    | 36        | 5.92%   |
| 1600x900 (HD+)     | 33        | 5.43%   |
| 1680x1050 (WSXGA+) | 19        | 3.13%   |
| 1440x900 (WXGA+)   | 17        | 2.8%    |
| 1280x1024 (SXGA)   | 17        | 2.8%    |
| 1920x1200 (WUXGA)  | 14        | 2.3%    |
| Unknown            | 10        | 1.64%   |
| 1280x800 (WXGA)    | 9         | 1.48%   |
| 2880x1800          | 8         | 1.32%   |
| 2560x1600          | 7         | 1.15%   |
| 3840x1080          | 6         | 0.99%   |
| 2560x1080          | 5         | 0.82%   |
| 3440x1440          | 4         | 0.66%   |
| 1360x768           | 4         | 0.66%   |
| 2160x1440          | 3         | 0.49%   |
| 5760x1080          | 2         | 0.33%   |
| 3840x2400          | 2         | 0.33%   |
| 3200x2000          | 2         | 0.33%   |
| 2880x1620          | 2         | 0.33%   |
| 2048x1152          | 2         | 0.33%   |
| 1400x1050          | 2         | 0.33%   |
| 1024x600           | 2         | 0.33%   |
| 800x1280           | 1         | 0.16%   |
| 4480x1440          | 1         | 0.16%   |
| 1920x1280          | 1         | 0.16%   |
| 1280x960           | 1         | 0.16%   |
| 1280x720 (HD)      | 1         | 0.16%   |
| 1024x768 (XGA)     | 1         | 0.16%   |
| 1024x576           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 185       | 28.73%  |
| 17      | 60        | 9.32%   |
| 27      | 54        | 8.39%   |
| 24      | 49        | 7.61%   |
| 14      | 43        | 6.68%   |
| 13      | 43        | 6.68%   |
| 23      | 41        | 6.37%   |
| 21      | 32        | 4.97%   |
| Unknown | 25        | 3.88%   |
| 31      | 14        | 2.17%   |
| 22      | 11        | 1.71%   |
| 19      | 10        | 1.55%   |
| 54      | 9         | 1.4%    |
| 20      | 9         | 1.4%    |
| 34      | 8         | 1.24%   |
| 16      | 7         | 1.09%   |
| 12      | 7         | 1.09%   |
| 18      | 5         | 0.78%   |
| 26      | 4         | 0.62%   |
| 84      | 3         | 0.47%   |
| 72      | 3         | 0.47%   |
| 33      | 3         | 0.47%   |
| 25      | 3         | 0.47%   |
| 10      | 3         | 0.47%   |
| 49      | 2         | 0.31%   |
| 60      | 1         | 0.16%   |
| 58      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 46      | 1         | 0.16%   |
| 40      | 1         | 0.16%   |
| 39      | 1         | 0.16%   |
| 38      | 1         | 0.16%   |
| 32      | 1         | 0.16%   |
| 11      | 1         | 0.16%   |
| 8       | 1         | 0.16%   |
| 7       | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 258       | 40.95%  |
| 501-600     | 131       | 20.79%  |
| 351-400     | 62        | 9.84%   |
| 401-500     | 60        | 9.52%   |
| 201-300     | 33        | 5.24%   |
| Unknown     | 25        | 3.97%   |
| 601-700     | 23        | 3.65%   |
| 1001-1500   | 15        | 2.38%   |
| 701-800     | 12        | 1.9%    |
| 1501-2000   | 6         | 0.95%   |
| 801-900     | 2         | 0.32%   |
| 101-200     | 1         | 0.16%   |
| 901-1000    | 1         | 0.16%   |
| 1-100       | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 420       | 75.13%  |
| 16/10   | 81        | 14.49%  |
| Unknown | 21        | 3.76%   |
| 5/4     | 15        | 2.68%   |
| 21/9    | 9         | 1.61%   |
| 3/2     | 6         | 1.07%   |
| 4/3     | 5         | 0.89%   |
| 32/9    | 1         | 0.18%   |
| 0.67    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 183       | 28.64%  |
| 201-250        | 97        | 15.18%  |
| 81-90          | 72        | 11.27%  |
| 301-350        | 58        | 9.08%   |
| 121-130        | 43        | 6.73%   |
| 151-200        | 33        | 5.16%   |
| 351-500        | 26        | 4.07%   |
| Unknown        | 25        | 3.91%   |
| 251-300        | 20        | 3.13%   |
| More than 1000 | 19        | 2.97%   |
| 71-80          | 13        | 2.03%   |
| 141-150        | 13        | 2.03%   |
| 131-140        | 8         | 1.25%   |
| 111-120        | 8         | 1.25%   |
| 61-70          | 6         | 0.94%   |
| 501-1000       | 5         | 0.78%   |
| 91-100         | 4         | 0.63%   |
| 41-50          | 3         | 0.47%   |
| 1-40           | 2         | 0.31%   |
| 51-60          | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 201       | 32.47%  |
| 51-100        | 186       | 30.05%  |
| 101-120       | 140       | 22.62%  |
| 161-240       | 34        | 5.49%   |
| Unknown       | 25        | 4.04%   |
| 1-50          | 18        | 2.91%   |
| More than 240 | 15        | 2.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 437       | 75.34%  |
| 2     | 109       | 18.79%  |
| 0     | 18        | 3.1%    |
| 3     | 14        | 2.41%   |
| 4     | 2         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 331       | 38.18%  |
| Intel                             | 249       | 28.72%  |
| Qualcomm Atheros                  | 90        | 10.38%  |
| Broadcom                          | 42        | 4.84%   |
| MediaTek                          | 31        | 3.58%   |
| TP-Link                           | 14        | 1.61%   |
| Broadcom Limited                  | 11        | 1.27%   |
| Samsung Electronics               | 9         | 1.04%   |
| Ralink Technology                 | 8         | 0.92%   |
| D-Link                            | 8         | 0.92%   |
| Ralink                            | 7         | 0.81%   |
| Qualcomm Atheros Communications   | 7         | 0.81%   |
| Marvell Technology Group          | 7         | 0.81%   |
| ASIX Electronics                  | 6         | 0.69%   |
| Xiaomi                            | 5         | 0.58%   |
| Nvidia                            | 5         | 0.58%   |
| Lenovo                            | 4         | 0.46%   |
| Qualcomm                          | 3         | 0.35%   |
| VIA Technologies                  | 2         | 0.23%   |
| Sundance Technology Inc / IC Plus | 2         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.23%   |
| NetGear                           | 2         | 0.23%   |
| Huawei Technologies               | 2         | 0.23%   |
| FIBOCOM                           | 2         | 0.23%   |
| Ericsson Business Mobile Networks | 2         | 0.23%   |
| Dell                              | 2         | 0.23%   |
| ASUSTek Computer                  | 2         | 0.23%   |
| T & A Mobile Phones               | 1         | 0.12%   |
| Ovislink                          | 1         | 0.12%   |
| Nokia Mobile Phones               | 1         | 0.12%   |
| Microsoft                         | 1         | 0.12%   |
| Linksys                           | 1         | 0.12%   |
| ICS Advent                        | 1         | 0.12%   |
| HTC (High Tech Computer)          | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Edimax Technology                 | 1         | 0.12%   |
| DisplayLink                       | 1         | 0.12%   |
| D-Link System                     | 1         | 0.12%   |
| Aquantia                          | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 235       | 23.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 27        | 2.74%   |
| Intel Wireless 8265 / 8275                                              | 25        | 2.54%   |
| Intel Wi-Fi 6 AX200                                                     | 25        | 2.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 1.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                       | 13        | 1.32%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 1.22%   |
| Intel Wireless 3165                                                     | 12        | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 1.22%   |
| Intel Ethernet Connection I217-LM                                       | 11        | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 1.12%   |
| Intel Ethernet Connection (4) I219-V                                    | 10        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 0.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.81%   |
| Intel Wireless 7265                                                     | 8         | 0.81%   |
| Intel Wireless 7260                                                     | 8         | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 7         | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.61%   |
| Intel Wireless 3160                                                     | 6         | 0.61%   |
| Intel Ethernet Controller I225-V                                        | 6         | 0.61%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.51%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 0.51%   |
| Intel Ethernet Connection I217-V                                        | 5         | 0.51%   |
| Intel Ethernet Connection (7) I219-V                                    | 5         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                    | 5         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 197       | 42.73%  |
| Qualcomm Atheros                | 74        | 16.05%  |
| Realtek Semiconductor           | 67        | 14.53%  |
| Broadcom                        | 30        | 6.51%   |
| MediaTek                        | 29        | 6.29%   |
| TP-Link                         | 14        | 3.04%   |
| Ralink Technology               | 8         | 1.74%   |
| D-Link                          | 8         | 1.74%   |
| Ralink                          | 7         | 1.52%   |
| Qualcomm Atheros Communications | 7         | 1.52%   |
| Broadcom Limited                | 5         | 1.08%   |
| Qualcomm                        | 3         | 0.65%   |
| NetGear                         | 2         | 0.43%   |
| FIBOCOM                         | 2         | 0.43%   |
| Dell                            | 2         | 0.43%   |
| ASUSTek Computer                | 2         | 0.43%   |
| Ovislink                        | 1         | 0.22%   |
| Microsoft                       | 1         | 0.22%   |
| Linksys                         | 1         | 0.22%   |
| Edimax Technology               | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 25        | 5.39%   |
| Intel Wi-Fi 6 AX200                                                     | 25        | 5.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 4.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 4.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 4.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 3.23%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 2.59%   |
| Intel Wireless 3165                                                     | 12        | 2.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 2.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.94%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.72%   |
| Intel Wireless 7265                                                     | 8         | 1.72%   |
| Intel Wireless 7260                                                     | 8         | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 1.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 1.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.51%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 1.29%   |
| Intel Wireless 3160                                                     | 6         | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 6         | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.08%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 1.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.86%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 4         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.86%   |
| TP-Link 802.11ac NIC                                                    | 3         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.65%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 3         | 0.65%   |
| Intel WiFi Link 5100                                                    | 3         | 0.65%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 3         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 296       | 58.27%  |
| Intel                             | 116       | 22.83%  |
| Qualcomm Atheros                  | 26        | 5.12%   |
| Broadcom                          | 13        | 2.56%   |
| Samsung Electronics               | 9         | 1.77%   |
| Marvell Technology Group          | 7         | 1.38%   |
| Broadcom Limited                  | 6         | 1.18%   |
| ASIX Electronics                  | 6         | 1.18%   |
| Xiaomi                            | 5         | 0.98%   |
| Nvidia                            | 5         | 0.98%   |
| Lenovo                            | 4         | 0.79%   |
| VIA Technologies                  | 2         | 0.39%   |
| Sundance Technology Inc / IC Plus | 2         | 0.39%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.39%   |
| Huawei Technologies               | 2         | 0.39%   |
| T & A Mobile Phones               | 1         | 0.2%    |
| MediaTek                          | 1         | 0.2%    |
| ICS Advent                        | 1         | 0.2%    |
| HTC (High Tech Computer)          | 1         | 0.2%    |
| DisplayLink                       | 1         | 0.2%    |
| D-Link System                     | 1         | 0.2%    |
| Aquantia                          | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 235       | 45.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 27        | 5.25%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 2.33%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 2.14%   |
| Intel Ethernet Connection (4) I219-V                                   | 10        | 1.95%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 7         | 1.36%   |
| Intel Ethernet Controller I225-V                                       | 6         | 1.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 0.97%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.97%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                   | 5         | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.78%   |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.78%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.58%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.58%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.58%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.58%   |
| Intel Ethernet Connection (14) I219-V                                  | 3         | 0.58%   |
| Intel Ethernet Connection (13) I219-V                                  | 3         | 0.58%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2         | 0.39%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.39%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 472       | 51.42%  |
| WiFi     | 438       | 47.71%  |
| Modem    | 5         | 0.54%   |
| Unknown  | 3         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 357       | 61.76%  |
| Ethernet | 221       | 38.24%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 321       | 57.53%  |
| 1     | 220       | 39.43%  |
| 0     | 11        | 1.97%   |
| 4     | 4         | 0.72%   |
| 3     | 2         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 529       | 94.3%   |
| Yes  | 32        | 5.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 160       | 44.69%  |
| Realtek Semiconductor           | 41        | 11.45%  |
| Qualcomm Atheros Communications | 28        | 7.82%   |
| Lite-On Technology              | 26        | 7.26%   |
| IMC Networks                    | 24        | 6.7%    |
| Foxconn / Hon Hai               | 18        | 5.03%   |
| Broadcom                        | 16        | 4.47%   |
| Cambridge Silicon Radio         | 13        | 3.63%   |
| Apple                           | 9         | 2.51%   |
| Hewlett-Packard                 | 6         | 1.68%   |
| Toshiba                         | 3         | 0.84%   |
| Foxconn International           | 3         | 0.84%   |
| MediaTek                        | 2         | 0.56%   |
| Integrated System Solution      | 2         | 0.56%   |
| Dell                            | 2         | 0.56%   |
| ASUSTek Computer                | 2         | 0.56%   |
| USI                             | 1         | 0.28%   |
| TP-Link                         | 1         | 0.28%   |
| Realtek                         | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 36        | 10.06%  |
| Intel AX201 Bluetooth                               | 30        | 8.38%   |
| Realtek Bluetooth Radio                             | 25        | 6.98%   |
| Intel AX200 Bluetooth                               | 25        | 6.98%   |
| Intel Bluetooth Device                              | 24        | 6.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 5.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 4.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 3.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 3.07%   |
| IMC Networks Wireless_Device                        | 10        | 2.79%   |
| Realtek 802.11ac WLAN Adapter                       | 9         | 2.51%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 2.51%   |
| IMC Networks Bluetooth Radio                        | 9         | 2.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 1.96%   |
| Intel AX211 Bluetooth                               | 7         | 1.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 1.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.4%    |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 1.12%   |
| Lite-On Wireless_Device                             | 4         | 1.12%   |
| Lite-On Bluetooth Device                            | 4         | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.12%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 1.12%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.84%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.84%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.84%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.84%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.84%   |
| Apple Bluetooth Host Controller                     | 3         | 0.84%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.56%   |
| MediaTek Wireless_Device                            | 2         | 0.56%   |
| IMC Networks Bluetooth Device                       | 2         | 0.56%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.56%   |
| USI Bluetooth Device                                | 1         | 0.28%   |
| TP-Link UB500 Adapter                               | 1         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 386       | 50%     |
| AMD                              | 190       | 24.61%  |
| Nvidia                           | 122       | 15.8%   |
| C-Media Electronics              | 15        | 1.94%   |
| Logitech                         | 10        | 1.3%    |
| Lenovo                           | 6         | 0.78%   |
| JMTek                            | 5         | 0.65%   |
| Creative Labs                    | 3         | 0.39%   |
| VIA Technologies                 | 2         | 0.26%   |
| Trust                            | 2         | 0.26%   |
| Silicon Integrated Systems [SiS] | 2         | 0.26%   |
| Microsoft                        | 2         | 0.26%   |
| ZOOM                             | 1         | 0.13%   |
| YZ Technology                    | 1         | 0.13%   |
| Yamaha                           | 1         | 0.13%   |
| XMOS                             | 1         | 0.13%   |
| Texas Instruments                | 1         | 0.13%   |
| Tenx Technology                  | 1         | 0.13%   |
| SteelSeries ApS                  | 1         | 0.13%   |
| Samsung Electronics              | 1         | 0.13%   |
| Samson Technologies              | 1         | 0.13%   |
| Realtek Semiconductor            | 1         | 0.13%   |
| Razer USA                        | 1         | 0.13%   |
| Plantronics                      | 1         | 0.13%   |
| Pioneer DJ                       | 1         | 0.13%   |
| Nordic Semiconductor ASA         | 1         | 0.13%   |
| Native Instruments               | 1         | 0.13%   |
| MCS                              | 1         | 0.13%   |
| M-Audio                          | 1         | 0.13%   |
| Kingston Technology              | 1         | 0.13%   |
| GN Netcom                        | 1         | 0.13%   |
| Focusrite-Novation               | 1         | 0.13%   |
| Ensoniq                          | 1         | 0.13%   |
| Dell                             | 1         | 0.13%   |
| Cirrus Logic                     | 1         | 0.13%   |
| BEHRINGER International          | 1         | 0.13%   |
| ATI Technologies                 | 1         | 0.13%   |
| ASUSTek Computer                 | 1         | 0.13%   |
| Astro Gaming                     | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 86        | 9.19%   |
| Intel Sunrise Point-LP HD Audio                                            | 50        | 5.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 39        | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 36        | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 29        | 3.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 27        | 2.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 26        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 2.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 2.14%   |
| Intel 8 Series HD Audio Controller                                         | 20        | 2.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19        | 2.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19        | 2.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16        | 1.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 14        | 1.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 1.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 1.39%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 13        | 1.39%   |
| Nvidia GP106 High Definition Audio Controller                              | 12        | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 1.18%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 1.07%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 1.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10        | 1.07%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 0.96%   |
| AMD FCH Azalia Controller                                                  | 9         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 0.85%   |
| Intel 200 Series PCH HD Audio                                              | 8         | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8         | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.75%   |
| Nvidia Audio device                                                        | 7         | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7         | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                              | 6         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 86        | 22.93%  |
| SK hynix            | 74        | 19.73%  |
| Kingston            | 70        | 18.67%  |
| Micron Technology   | 38        | 10.13%  |
| Unknown             | 23        | 6.13%   |
| Crucial             | 21        | 5.6%    |
| Corsair             | 15        | 4%      |
| G.Skill             | 13        | 3.47%   |
| Ramaxel Technology  | 6         | 1.6%    |
| Patriot             | 5         | 1.33%   |
| Elpida              | 5         | 1.33%   |
| Transcend           | 4         | 1.07%   |
| A-DATA Technology   | 4         | 1.07%   |
| Unknown (ABCD)      | 2         | 0.53%   |
| Kingmax             | 2         | 0.53%   |
| Silicon Power       | 1         | 0.27%   |
| Qimonda             | 1         | 0.27%   |
| Mushkin             | 1         | 0.27%   |
| Avant               | 1         | 0.27%   |
| Apacer              | 1         | 0.27%   |
| 48spaces            | 1         | 0.27%   |
| Unknown             | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 9         | 2.24%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.24%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.24%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 1%      |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 1%      |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.75%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.75%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 3         | 0.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.75%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.5%    |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 2         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.5%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.5%    |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 2         | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.5%    |
| SK hynix RAM HMT125S6TFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 0.5%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.5%    |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.5%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.5%    |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.5%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.5%    |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 2         | 0.5%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.5%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.5%    |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s              | 2         | 0.5%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.5%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 152       | 49.19%  |
| DDR3    | 96        | 31.07%  |
| DDR2    | 13        | 4.21%   |
| LPDDR4  | 11        | 3.56%   |
| DDR5    | 10        | 3.24%   |
| LPDDR3  | 9         | 2.91%   |
| LPDDR5  | 6         | 1.94%   |
| Unknown | 6         | 1.94%   |
| SDRAM   | 5         | 1.62%   |
| DDR     | 1         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 193       | 62.26%  |
| DIMM         | 90        | 29.03%  |
| Row Of Chips | 26        | 8.39%   |
| Chip         | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 139       | 41%     |
| 4096  | 89        | 26.25%  |
| 16384 | 58        | 17.11%  |
| 2048  | 32        | 9.44%   |
| 32768 | 10        | 2.95%   |
| 1024  | 9         | 2.65%   |
| 512   | 2         | 0.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 67        | 20.3%   |
| 1600  | 66        | 20%     |
| 2667  | 57        | 17.27%  |
| 2400  | 17        | 5.15%   |
| 1333  | 16        | 4.85%   |
| 2133  | 14        | 4.24%   |
| 667   | 9         | 2.73%   |
| 1334  | 8         | 2.42%   |
| 6400  | 5         | 1.52%   |
| 3600  | 5         | 1.52%   |
| 3400  | 5         | 1.52%   |
| 1066  | 5         | 1.52%   |
| 800   | 5         | 1.52%   |
| 4800  | 4         | 1.21%   |
| 4267  | 4         | 1.21%   |
| 1800  | 4         | 1.21%   |
| 6000  | 3         | 0.91%   |
| 4266  | 3         | 0.91%   |
| 3266  | 3         | 0.91%   |
| 1867  | 3         | 0.91%   |
| 1067  | 3         | 0.91%   |
| 3866  | 2         | 0.61%   |
| 2933  | 2         | 0.61%   |
| 2800  | 2         | 0.61%   |
| 533   | 2         | 0.61%   |
| 8400  | 1         | 0.3%    |
| 6600  | 1         | 0.3%    |
| 5600  | 1         | 0.3%    |
| 5500  | 1         | 0.3%    |
| 5200  | 1         | 0.3%    |
| 4000  | 1         | 0.3%    |
| 3800  | 1         | 0.3%    |
| 3733  | 1         | 0.3%    |
| 3466  | 1         | 0.3%    |
| 3334  | 1         | 0.3%    |
| 3333  | 1         | 0.3%    |
| 3000  | 1         | 0.3%    |
| 2048  | 1         | 0.3%    |
| 975   | 1         | 0.3%    |
| 400   | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 55.56%  |
| Canon               | 4         | 22.22%  |
| Prolific Technology | 2         | 11.11%  |
| Seiko Epson         | 1         | 5.56%   |
| Samsung Electronics | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port   | 2         | 11.11%  |
| HP DeskJet 3630 series          | 2         | 11.11%  |
| Seiko Epson L395 Series         | 1         | 5.56%   |
| Samsung Composite Device        | 1         | 5.56%   |
| HP LaserJet P1102               | 1         | 5.56%   |
| HP LaserJet P1005               | 1         | 5.56%   |
| HP LaserJet M101-M106           | 1         | 5.56%   |
| HP LaserJet 400 colorMFP M475dw | 1         | 5.56%   |
| HP Ink Tank Wireless 410 series | 1         | 5.56%   |
| HP HP LaserJet M14-M17          | 1         | 5.56%   |
| HP DeskJet 2130 series          | 1         | 5.56%   |
| HP Deskjet 1050 J410            | 1         | 5.56%   |
| Canon PIXMA iP4300 Printer      | 1         | 5.56%   |
| Canon PIXMA iP1800 Printer      | 1         | 5.56%   |
| Canon LiDE 400                  | 1         | 5.56%   |
| Canon LBP6670 UFR II            | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 66.67%  |
| Ultima Electronics | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Ultima Artec Ultima 2000      | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 220       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 96        | 25.81%  |
| IMC Networks                           | 39        | 10.48%  |
| Quanta                                 | 37        | 9.95%   |
| Realtek Semiconductor                  | 28        | 7.53%   |
| Microdia                               | 24        | 6.45%   |
| Logitech                               | 19        | 5.11%   |
| Bison Electronics                      | 19        | 5.11%   |
| Sunplus Innovation Technology          | 16        | 4.3%    |
| Suyin                                  | 13        | 3.49%   |
| Syntek                                 | 12        | 3.23%   |
| Lite-On Technology                     | 11        | 2.96%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 1.88%   |
| Acer                                   | 7         | 1.88%   |
| Luxvisions Innotech Limited            | 6         | 1.61%   |
| Apple                                  | 6         | 1.61%   |
| Sonix Technology                       | 5         | 1.34%   |
| SunplusIT                              | 4         | 1.08%   |
| Silicon Motion                         | 3         | 0.81%   |
| Anker                                  | 3         | 0.81%   |
| Primax Electronics                     | 2         | 0.54%   |
| Jieli Technology                       | 2         | 0.54%   |
| Genesys Logic                          | 2         | 0.54%   |
| Z-Star Microelectronics                | 1         | 0.27%   |
| Xiaomi                                 | 1         | 0.27%   |
| Trust                                  | 1         | 0.27%   |
| Shinetech                              | 1         | 0.27%   |
| Samsung Electronics                    | 1         | 0.27%   |
| Ricoh                                  | 1         | 0.27%   |
| Goertek Electronics                    | 1         | 0.27%   |
| GenesysLogic Technology                | 1         | 0.27%   |
| Cubeternet                             | 1         | 0.27%   |
| AVerMedia Technologies                 | 1         | 0.27%   |
| Alcor Micro                            | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 18        | 4.83%   |
| Chicony HD WebCam                        | 16        | 4.29%   |
| IMC Networks Integrated Camera           | 13        | 3.49%   |
| Microdia Integrated_Webcam_HD            | 10        | 2.68%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 10        | 2.68%   |
| IMC Networks USB2.0 HD UVC WebCam        | 10        | 2.68%   |
| Quanta VGA WebCam                        | 9         | 2.41%   |
| Syntek Integrated Camera                 | 8         | 2.14%   |
| Quanta HD User Facing                    | 7         | 1.88%   |
| Bison Integrated Camera                  | 7         | 1.88%   |
| Realtek Integrated_Webcam_HD             | 6         | 1.61%   |
| Logitech Webcam C270                     | 6         | 1.61%   |
| Lite-On HP HD Camera                     | 6         | 1.61%   |
| Quanta HP HD Camera                      | 5         | 1.34%   |
| Quanta HD Webcam                         | 5         | 1.34%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 4         | 1.07%   |
| SunplusIT USB 2.0 Camera                 | 4         | 1.07%   |
| Quanta HP TrueVision HD Camera           | 4         | 1.07%   |
| Chicony HP Wide Vision HD Camera         | 4         | 1.07%   |
| Chicony HP Webcam                        | 4         | 1.07%   |
| Chicony HP HD Camera                     | 4         | 1.07%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 1.07%   |
| Suyin WebCam                             | 3         | 0.8%    |
| Sunplus HD 720P webcam                   | 3         | 0.8%    |
| Sunplus Asus Webcam                      | 3         | 0.8%    |
| Sonix USB2.0 FHD UVC WebCam              | 3         | 0.8%    |
| Realtek Lenovo EasyCamera                | 3         | 0.8%    |
| Realtek Integrated Webcam                | 3         | 0.8%    |
| Lite-On Integrated Camera                | 3         | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam            | 3         | 0.8%    |
| Chicony USB2.0 HD UVC WebCam             | 3         | 0.8%    |
| Chicony Integrated HP HD Webcam          | 3         | 0.8%    |
| Chicony HP Wide Vision HD                | 3         | 0.8%    |
| Chicony HD User Facing                   | 3         | 0.8%    |
| Bison Lenovo EasyCamera                  | 3         | 0.8%    |
| Anker Anker PowerConf C300               | 3         | 0.8%    |
| Suyin HP TrueVision HD Integrated Webcam | 2         | 0.54%   |
| Sunplus Integrated_Webcam_HD             | 2         | 0.54%   |
| Sunplus HD WebCam                        | 2         | 0.54%   |
| Sonix USB2.0 HD UVC WebCam               | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 31        | 37.8%   |
| Validity Sensors           | 18        | 21.95%  |
| Shenzhen Goodix Technology | 12        | 14.63%  |
| AuthenTec                  | 6         | 7.32%   |
| LighTuning Technology      | 5         | 6.1%    |
| Elan Microelectronics      | 5         | 6.1%    |
| Upek                       | 4         | 4.88%   |
| STMicroelectronics         | 1         | 1.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 9.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 8.54%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 7.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 6.1%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 6.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 6.1%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 4.88%   |
| Elan ELAN:Fingerprint                                                      | 4         | 4.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.66%   |
| Synaptics WBDI                                                             | 3         | 3.66%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 3.66%   |
| AuthenTec AES2810                                                          | 3         | 3.66%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 3.66%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.44%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.44%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.44%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.22%   |
| Validity Sensors VFS491                                                    | 1         | 1.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.22%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.22%   |
| Synaptics UWP WBDI                                                         | 1         | 1.22%   |
| Synaptics TouchPad                                                         | 1         | 1.22%   |
| Synaptics  WBDI                                                            | 1         | 1.22%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.22%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.22%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 1.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 9         | 34.62%  |
| Broadcom                   | 5         | 19.23%  |
| Lenovo                     | 4         | 15.38%  |
| Gemalto (was Gemplus)      | 3         | 11.54%  |
| Aladdin Knowledge Systems  | 2         | 7.69%   |
| Upek                       | 1         | 3.85%   |
| Realtek Semiconductor      | 1         | 3.85%   |
| Athena Smartcard Solutions | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 9         | 34.62%  |
| Lenovo Integrated Smart Card Reader                        | 4         | 15.38%  |
| Broadcom 58200                                             | 3         | 11.54%  |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader           | 2         | 7.69%   |
| Aladdin Knowledge Systems Token JC                         | 2         | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 3.85%   |
| Realtek Semiconductor Smart Card Reader Interface          | 1         | 3.85%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 3.85%   |
| Broadcom 5880                                              | 1         | 3.85%   |
| Athena Smartcard Solutions ASEDrive CCID                   | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 391       | 67.88%  |
| 1     | 142       | 24.65%  |
| 2     | 38        | 6.6%    |
| 3     | 4         | 0.69%   |
| 4     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 81        | 36.32%  |
| Graphics card            | 47        | 21.08%  |
| Net/wireless             | 26        | 11.66%  |
| Chipcard                 | 22        | 9.87%   |
| Multimedia controller    | 15        | 6.73%   |
| Communication controller | 6         | 2.69%   |
| Camera                   | 6         | 2.69%   |
| Bluetooth                | 4         | 1.79%   |
| Unassigned class         | 3         | 1.35%   |
| Card reader              | 3         | 1.35%   |
| Storage                  | 2         | 0.9%    |
| Sound                    | 2         | 0.9%    |
| Storage/raid             | 1         | 0.45%   |
| Storage/ide              | 1         | 0.45%   |
| Network                  | 1         | 0.45%   |
| Net/ethernet             | 1         | 0.45%   |
| Modem                    | 1         | 0.45%   |
| Flash memory             | 1         | 0.45%   |

