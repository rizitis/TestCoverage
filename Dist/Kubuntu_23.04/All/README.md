Kubuntu 23.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_23.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_23.04/Notebook/README.md).

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

Total: 430

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P8Z68-V                     | Desktop     | [4a20d22dd5](https://linux-hardware.org/?probe=4a20d22dd5) | Nov 11, 2024 |
| ASUSTek       | P8Z68-V                     | Desktop     | [014f995cb5](https://linux-hardware.org/?probe=014f995cb5) | Nov 11, 2024 |
| ASUSTek       | P8Z68-V                     | Desktop     | [164a29cfe9](https://linux-hardware.org/?probe=164a29cfe9) | Nov 10, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [1972507830](https://linux-hardware.org/?probe=1972507830) | Jul 28, 2024 |
| Dell          | Inspiron 5406 2n1           | Convertible | [05e57ce9a8](https://linux-hardware.org/?probe=05e57ce9a8) | Jul 20, 2024 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | Notebook    | [bb5b1c44d8](https://linux-hardware.org/?probe=bb5b1c44d8) | May 12, 2024 |
| ASUSTek       | CROSSBLADE RANGER           | Desktop     | [ec49fe4be2](https://linux-hardware.org/?probe=ec49fe4be2) | May 10, 2024 |
| Intel Clie... | LAPBC710                    | Notebook    | [8a2e6ee6ff](https://linux-hardware.org/?probe=8a2e6ee6ff) | Apr 24, 2024 |
| Intel Clie... | LAPBC710                    | Notebook    | [1853edd88a](https://linux-hardware.org/?probe=1853edd88a) | Apr 24, 2024 |
| DERE          | Unknown                     | Tablet      | [7780e6cd50](https://linux-hardware.org/?probe=7780e6cd50) | Apr 20, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [daeb8bc353](https://linux-hardware.org/?probe=daeb8bc353) | Apr 07, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [0f3b430878](https://linux-hardware.org/?probe=0f3b430878) | Mar 15, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [5bd971f4fe](https://linux-hardware.org/?probe=5bd971f4fe) | Mar 12, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5602abb8e5](https://linux-hardware.org/?probe=5602abb8e5) | Mar 05, 2024 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [af9215d3a5](https://linux-hardware.org/?probe=af9215d3a5) | Jan 23, 2024 |
| Unknown       | AY07J                       | Desktop     | [1cb5749c2b](https://linux-hardware.org/?probe=1cb5749c2b) | Jan 13, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [bf4f14e416](https://linux-hardware.org/?probe=bf4f14e416) | Dec 30, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [5972225791](https://linux-hardware.org/?probe=5972225791) | Dec 25, 2023 |
| HP            | Notebook                    | Notebook    | [7541fcf0c8](https://linux-hardware.org/?probe=7541fcf0c8) | Dec 22, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [d8f95bfd45](https://linux-hardware.org/?probe=d8f95bfd45) | Dec 18, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [f9a70833ee](https://linux-hardware.org/?probe=f9a70833ee) | Dec 18, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [0a531cbda1](https://linux-hardware.org/?probe=0a531cbda1) | Dec 12, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [2a22b3adb4](https://linux-hardware.org/?probe=2a22b3adb4) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8395e5f595](https://linux-hardware.org/?probe=8395e5f595) | Dec 08, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [65530f33de](https://linux-hardware.org/?probe=65530f33de) | Dec 06, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [2fcc002511](https://linux-hardware.org/?probe=2fcc002511) | Dec 02, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [997c41ef61](https://linux-hardware.org/?probe=997c41ef61) | Dec 01, 2023 |
| HP            | 355 G2                      | Notebook    | [bb79df3643](https://linux-hardware.org/?probe=bb79df3643) | Nov 28, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [c3fc46a4a5](https://linux-hardware.org/?probe=c3fc46a4a5) | Nov 21, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [d91c0b4b6f](https://linux-hardware.org/?probe=d91c0b4b6f) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3f1d1d36ef](https://linux-hardware.org/?probe=3f1d1d36ef) | Nov 10, 2023 |
| HP            | Notebook                    | Notebook    | [f8cf975d3c](https://linux-hardware.org/?probe=f8cf975d3c) | Nov 04, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9cdd815382](https://linux-hardware.org/?probe=9cdd815382) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [493dcbc1f8](https://linux-hardware.org/?probe=493dcbc1f8) | Nov 01, 2023 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [67863a015a](https://linux-hardware.org/?probe=67863a015a) | Nov 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [6895dd827a](https://linux-hardware.org/?probe=6895dd827a) | Nov 01, 2023 |
| Sony          | VPCSA3J1E                   | Notebook    | [99b0d275ec](https://linux-hardware.org/?probe=99b0d275ec) | Nov 01, 2023 |
| ASUSTek       | BT1AD                       | Desktop     | [133784e5ee](https://linux-hardware.org/?probe=133784e5ee) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 15            | Notebook    | [2cad75b0fc](https://linux-hardware.org/?probe=2cad75b0fc) | Oct 31, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fe3816864f](https://linux-hardware.org/?probe=fe3816864f) | Oct 30, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [4825358a5d](https://linux-hardware.org/?probe=4825358a5d) | Oct 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5d7ab82de7](https://linux-hardware.org/?probe=5d7ab82de7) | Oct 30, 2023 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [b160015184](https://linux-hardware.org/?probe=b160015184) | Oct 29, 2023 |
| HP            | 1790                        | Desktop     | [8bde9984db](https://linux-hardware.org/?probe=8bde9984db) | Oct 29, 2023 |
| Dell          | Precision M6800             | Notebook    | [3645954ce0](https://linux-hardware.org/?probe=3645954ce0) | Oct 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0f69bc7ea0](https://linux-hardware.org/?probe=0f69bc7ea0) | Oct 28, 2023 |
| HP            | 14                          | Notebook    | [5e8b808f2f](https://linux-hardware.org/?probe=5e8b808f2f) | Oct 24, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [67564f88a0](https://linux-hardware.org/?probe=67564f88a0) | Oct 24, 2023 |
| Colorful T... | BATTLE-AX B450M-HD V14      | Desktop     | [314500a8ed](https://linux-hardware.org/?probe=314500a8ed) | Oct 23, 2023 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [db0826b2fc](https://linux-hardware.org/?probe=db0826b2fc) | Oct 22, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [5962f780e9](https://linux-hardware.org/?probe=5962f780e9) | Oct 22, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [9990a91f59](https://linux-hardware.org/?probe=9990a91f59) | Oct 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [33b1df369f](https://linux-hardware.org/?probe=33b1df369f) | Oct 21, 2023 |
| AZW           | SER V01                     | Mini pc     | [25ca388d81](https://linux-hardware.org/?probe=25ca388d81) | Oct 21, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [a7f26cedd6](https://linux-hardware.org/?probe=a7f26cedd6) | Oct 20, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8fd9d07f5d](https://linux-hardware.org/?probe=8fd9d07f5d) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0c25658c6d](https://linux-hardware.org/?probe=0c25658c6d) | Oct 18, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [413edf8cdb](https://linux-hardware.org/?probe=413edf8cdb) | Oct 18, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [05ee51f822](https://linux-hardware.org/?probe=05ee51f822) | Oct 18, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [77690da2b6](https://linux-hardware.org/?probe=77690da2b6) | Oct 17, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [86d888a421](https://linux-hardware.org/?probe=86d888a421) | Oct 17, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [116667b041](https://linux-hardware.org/?probe=116667b041) | Oct 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bc33324b0d](https://linux-hardware.org/?probe=bc33324b0d) | Oct 15, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [059145d98c](https://linux-hardware.org/?probe=059145d98c) | Oct 15, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [e4bcb7e688](https://linux-hardware.org/?probe=e4bcb7e688) | Oct 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [09d2bdba5b](https://linux-hardware.org/?probe=09d2bdba5b) | Oct 12, 2023 |
| HP            | ProBook 4540s               | Notebook    | [c3be7c74a0](https://linux-hardware.org/?probe=c3be7c74a0) | Oct 11, 2023 |
| ASRock        | X79 Extreme9                | Desktop     | [4a0805a07a](https://linux-hardware.org/?probe=4a0805a07a) | Oct 11, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [3fe42a607c](https://linux-hardware.org/?probe=3fe42a607c) | Oct 10, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [0e1ec62b3b](https://linux-hardware.org/?probe=0e1ec62b3b) | Oct 10, 2023 |
| Intel         | S5520HC E26045-454          | Server      | [5f179c5f02](https://linux-hardware.org/?probe=5f179c5f02) | Oct 09, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [38b7ffd223](https://linux-hardware.org/?probe=38b7ffd223) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7513e708f6](https://linux-hardware.org/?probe=7513e708f6) | Oct 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [364af80964](https://linux-hardware.org/?probe=364af80964) | Oct 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [c5a3a209c0](https://linux-hardware.org/?probe=c5a3a209c0) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c35ab8ae2e](https://linux-hardware.org/?probe=c35ab8ae2e) | Oct 05, 2023 |
| Google        | Woomax                      | Notebook    | [2163941472](https://linux-hardware.org/?probe=2163941472) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b34e8b6647](https://linux-hardware.org/?probe=b34e8b6647) | Oct 04, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [8892c7239e](https://linux-hardware.org/?probe=8892c7239e) | Oct 03, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [a9e2c9b64e](https://linux-hardware.org/?probe=a9e2c9b64e) | Oct 03, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [a44e0088f6](https://linux-hardware.org/?probe=a44e0088f6) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1330485afc](https://linux-hardware.org/?probe=1330485afc) | Oct 01, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [4a47d466d9](https://linux-hardware.org/?probe=4a47d466d9) | Sep 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [c9aca83f04](https://linux-hardware.org/?probe=c9aca83f04) | Sep 30, 2023 |
| HP            | 1790                        | Desktop     | [b87e9dd9ad](https://linux-hardware.org/?probe=b87e9dd9ad) | Sep 29, 2023 |
| HP            | 1790                        | Desktop     | [89791e7bf0](https://linux-hardware.org/?probe=89791e7bf0) | Sep 29, 2023 |
| MSI           | H97M-G43                    | Desktop     | [b74346acb3](https://linux-hardware.org/?probe=b74346acb3) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [76937ddbce](https://linux-hardware.org/?probe=76937ddbce) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [128658b9f0](https://linux-hardware.org/?probe=128658b9f0) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| CHIPHD        | NT125D                      | Notebook    | [7e966b32de](https://linux-hardware.org/?probe=7e966b32de) | Sep 26, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [e8397f6d0a](https://linux-hardware.org/?probe=e8397f6d0a) | Sep 26, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [1b72e3fe1c](https://linux-hardware.org/?probe=1b72e3fe1c) | Sep 26, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [0281cc244a](https://linux-hardware.org/?probe=0281cc244a) | Sep 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7f88191a7b](https://linux-hardware.org/?probe=7f88191a7b) | Sep 23, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [dc831a82cd](https://linux-hardware.org/?probe=dc831a82cd) | Sep 22, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [54a894ffd7](https://linux-hardware.org/?probe=54a894ffd7) | Sep 21, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [d4060b585a](https://linux-hardware.org/?probe=d4060b585a) | Sep 20, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [98aa98d974](https://linux-hardware.org/?probe=98aa98d974) | Sep 20, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [17e0d2ab92](https://linux-hardware.org/?probe=17e0d2ab92) | Sep 17, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [e60aae9a1b](https://linux-hardware.org/?probe=e60aae9a1b) | Sep 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [82879c821a](https://linux-hardware.org/?probe=82879c821a) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [76d6f570a8](https://linux-hardware.org/?probe=76d6f570a8) | Sep 16, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [a73abd96f1](https://linux-hardware.org/?probe=a73abd96f1) | Sep 15, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [3a1c100a69](https://linux-hardware.org/?probe=3a1c100a69) | Sep 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [20ad52b9a4](https://linux-hardware.org/?probe=20ad52b9a4) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [959fc9f783](https://linux-hardware.org/?probe=959fc9f783) | Sep 13, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [641089b224](https://linux-hardware.org/?probe=641089b224) | Sep 13, 2023 |
| AZW           | MINI S 10                   | Desktop     | [5cd0efea8b](https://linux-hardware.org/?probe=5cd0efea8b) | Sep 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [b12897892a](https://linux-hardware.org/?probe=b12897892a) | Sep 09, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [33cc2ca68e](https://linux-hardware.org/?probe=33cc2ca68e) | Sep 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [23da68a72c](https://linux-hardware.org/?probe=23da68a72c) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1275709f08](https://linux-hardware.org/?probe=1275709f08) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [5180b1e51e](https://linux-hardware.org/?probe=5180b1e51e) | Sep 09, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [6f3051262d](https://linux-hardware.org/?probe=6f3051262d) | Sep 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [fe6b08c772](https://linux-hardware.org/?probe=fe6b08c772) | Sep 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [c0422be924](https://linux-hardware.org/?probe=c0422be924) | Sep 08, 2023 |
| Google        | Robo360                     | Notebook    | [86308cca01](https://linux-hardware.org/?probe=86308cca01) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [81a5f77f1c](https://linux-hardware.org/?probe=81a5f77f1c) | Sep 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [48cc912b75](https://linux-hardware.org/?probe=48cc912b75) | Sep 06, 2023 |
| Lenovo        | 3708 NOK                    | Desktop     | [153f0dfa9d](https://linux-hardware.org/?probe=153f0dfa9d) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [f081f44bda](https://linux-hardware.org/?probe=f081f44bda) | Sep 05, 2023 |
| Samsung       | 950QED                      | Convertible | [e15539dd35](https://linux-hardware.org/?probe=e15539dd35) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| AZW           | SER V01                     | Mini pc     | [b744dfb20a](https://linux-hardware.org/?probe=b744dfb20a) | Sep 05, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [71da9ea288](https://linux-hardware.org/?probe=71da9ea288) | Sep 04, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [31cb6a887e](https://linux-hardware.org/?probe=31cb6a887e) | Sep 04, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [27e226b6d4](https://linux-hardware.org/?probe=27e226b6d4) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [a9d960e012](https://linux-hardware.org/?probe=a9d960e012) | Aug 29, 2023 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [a2f18f43e4](https://linux-hardware.org/?probe=a2f18f43e4) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5b0183001d](https://linux-hardware.org/?probe=5b0183001d) | Aug 28, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fa48902a10](https://linux-hardware.org/?probe=fa48902a10) | Aug 27, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1f47bfe737](https://linux-hardware.org/?probe=1f47bfe737) | Aug 26, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [65b6b29fc7](https://linux-hardware.org/?probe=65b6b29fc7) | Aug 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e4200e4c9a](https://linux-hardware.org/?probe=e4200e4c9a) | Aug 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bc15f84b8c](https://linux-hardware.org/?probe=bc15f84b8c) | Aug 24, 2023 |
| Dell          | Precision 7780              | Notebook    | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [7bd62bca50](https://linux-hardware.org/?probe=7bd62bca50) | Aug 23, 2023 |
| Intel         | H55                         | Desktop     | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [c78c246642](https://linux-hardware.org/?probe=c78c246642) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9a7f33c81b](https://linux-hardware.org/?probe=9a7f33c81b) | Aug 20, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [b5973b3c67](https://linux-hardware.org/?probe=b5973b3c67) | Aug 18, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [8e409a97d7](https://linux-hardware.org/?probe=8e409a97d7) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [f0d325d7d3](https://linux-hardware.org/?probe=f0d325d7d3) | Aug 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [a395628119](https://linux-hardware.org/?probe=a395628119) | Aug 15, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [e338ac8876](https://linux-hardware.org/?probe=e338ac8876) | Aug 14, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| AMI           | INTEL                       | Convertible | [21596eaf06](https://linux-hardware.org/?probe=21596eaf06) | Aug 14, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [7dd490a028](https://linux-hardware.org/?probe=7dd490a028) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [0c8514df53](https://linux-hardware.org/?probe=0c8514df53) | Aug 13, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [97c78c17bd](https://linux-hardware.org/?probe=97c78c17bd) | Aug 12, 2023 |
| AZW           | SER V01                     | Mini pc     | [542d8da36c](https://linux-hardware.org/?probe=542d8da36c) | Aug 11, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f28a198267](https://linux-hardware.org/?probe=f28a198267) | Aug 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [767792bf33](https://linux-hardware.org/?probe=767792bf33) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [e03fdd9f60](https://linux-hardware.org/?probe=e03fdd9f60) | Aug 07, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6d2ab6eef6](https://linux-hardware.org/?probe=6d2ab6eef6) | Aug 07, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [838f543301](https://linux-hardware.org/?probe=838f543301) | Aug 04, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [1b9b10c938](https://linux-hardware.org/?probe=1b9b10c938) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Dell          | Precision 7670              | Notebook    | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| HP            | 158A                        | Desktop     | [ae8ecc3ee7](https://linux-hardware.org/?probe=ae8ecc3ee7) | Aug 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [178bed5f56](https://linux-hardware.org/?probe=178bed5f56) | Aug 03, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| HPE           | ML10Gen9                    | Server      | [f5115c8a74](https://linux-hardware.org/?probe=f5115c8a74) | Aug 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [5e552472e5](https://linux-hardware.org/?probe=5e552472e5) | Aug 03, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [4d21c35777](https://linux-hardware.org/?probe=4d21c35777) | Aug 03, 2023 |
| Alienware     | 14                          | Notebook    | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| HP            | 158A                        | Desktop     | [bac95226bd](https://linux-hardware.org/?probe=bac95226bd) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [6519784d61](https://linux-hardware.org/?probe=6519784d61) | Aug 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9371aa866b](https://linux-hardware.org/?probe=9371aa866b) | Jul 30, 2023 |
| Google        | Zako                        | Desktop     | [66946b6b49](https://linux-hardware.org/?probe=66946b6b49) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [65a741810c](https://linux-hardware.org/?probe=65a741810c) | Jul 30, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [e5ad011556](https://linux-hardware.org/?probe=e5ad011556) | Jul 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [22b080cd6b](https://linux-hardware.org/?probe=22b080cd6b) | Jul 29, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8102a251ad](https://linux-hardware.org/?probe=8102a251ad) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e4e0bebde](https://linux-hardware.org/?probe=6e4e0bebde) | Jul 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [63c601695f](https://linux-hardware.org/?probe=63c601695f) | Jul 28, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [86868232f0](https://linux-hardware.org/?probe=86868232f0) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Acer          | Aspire X3990                | Desktop     | [7b6b27241f](https://linux-hardware.org/?probe=7b6b27241f) | Jul 24, 2023 |
| AZW           | SER V01                     | Mini pc     | [440a88b8bf](https://linux-hardware.org/?probe=440a88b8bf) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [273533f7f8](https://linux-hardware.org/?probe=273533f7f8) | Jul 24, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [26f325a346](https://linux-hardware.org/?probe=26f325a346) | Jul 23, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [881853b4dc](https://linux-hardware.org/?probe=881853b4dc) | Jul 23, 2023 |
| HP            | G62                         | Notebook    | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [751e776113](https://linux-hardware.org/?probe=751e776113) | Jul 23, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| HP            | 83E9                        | Desktop     | [35c7f631ac](https://linux-hardware.org/?probe=35c7f631ac) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [392b85a82b](https://linux-hardware.org/?probe=392b85a82b) | Jul 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [15ef7f9ce4](https://linux-hardware.org/?probe=15ef7f9ce4) | Jul 16, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [8fb3c405c0](https://linux-hardware.org/?probe=8fb3c405c0) | Jul 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d64ea4b9cd](https://linux-hardware.org/?probe=d64ea4b9cd) | Jul 15, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [bf8b4001a4](https://linux-hardware.org/?probe=bf8b4001a4) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0008f72dbf](https://linux-hardware.org/?probe=0008f72dbf) | Jul 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [745fa6a1b4](https://linux-hardware.org/?probe=745fa6a1b4) | Jul 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [8ea38146c1](https://linux-hardware.org/?probe=8ea38146c1) | Jul 14, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [87a3354fc2](https://linux-hardware.org/?probe=87a3354fc2) | Jul 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [81ca680697](https://linux-hardware.org/?probe=81ca680697) | Jul 13, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [6f62e1063c](https://linux-hardware.org/?probe=6f62e1063c) | Jul 11, 2023 |
| Dell          | G3 3779                     | Notebook    | [2cdd1427c9](https://linux-hardware.org/?probe=2cdd1427c9) | Jul 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [95b195418f](https://linux-hardware.org/?probe=95b195418f) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| HP            | 2B3E                        | All in one  | [9ec58b6284](https://linux-hardware.org/?probe=9ec58b6284) | Jul 09, 2023 |
| Acer          | Predator G3-572             | Notebook    | [fe7753845c](https://linux-hardware.org/?probe=fe7753845c) | Jul 09, 2023 |
| MSI           | B360M MORTAR TITANIUM       | Desktop     | [31b2aa5991](https://linux-hardware.org/?probe=31b2aa5991) | Jul 08, 2023 |
| Dell          | G3 3779                     | Notebook    | [9274552475](https://linux-hardware.org/?probe=9274552475) | Jul 08, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [a2981d590e](https://linux-hardware.org/?probe=a2981d590e) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c0b828ddc4](https://linux-hardware.org/?probe=c0b828ddc4) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| AZW           | SER V01                     | Mini pc     | [49552e2240](https://linux-hardware.org/?probe=49552e2240) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [e566cda2af](https://linux-hardware.org/?probe=e566cda2af) | Jul 06, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | Notebook    | [889e120cd5](https://linux-hardware.org/?probe=889e120cd5) | Jul 06, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [5800dc6fbf](https://linux-hardware.org/?probe=5800dc6fbf) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [61c278235a](https://linux-hardware.org/?probe=61c278235a) | Jul 03, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [8805bd2666](https://linux-hardware.org/?probe=8805bd2666) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [48f79dc803](https://linux-hardware.org/?probe=48f79dc803) | Jul 03, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [9d47ca40b8](https://linux-hardware.org/?probe=9d47ca40b8) | Jul 03, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [22ca0e18f4](https://linux-hardware.org/?probe=22ca0e18f4) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gateway       | IPISB-VR                    | Desktop     | [73ab7736ca](https://linux-hardware.org/?probe=73ab7736ca) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [51d5b7d342](https://linux-hardware.org/?probe=51d5b7d342) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [0571943e1f](https://linux-hardware.org/?probe=0571943e1f) | Jul 01, 2023 |
| ASUSTek       | Strix GL704GW_GL704GW       | Notebook    | [cb42a3f59d](https://linux-hardware.org/?probe=cb42a3f59d) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7e7099c099](https://linux-hardware.org/?probe=7e7099c099) | Jul 01, 2023 |
| Dell          | G3 3779                     | Notebook    | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7a5a27ddd7](https://linux-hardware.org/?probe=7a5a27ddd7) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [16c312b7be](https://linux-hardware.org/?probe=16c312b7be) | Jun 26, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | Notebook    | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [e5efed1ac5](https://linux-hardware.org/?probe=e5efed1ac5) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7cb19a32ac](https://linux-hardware.org/?probe=7cb19a32ac) | Jun 20, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [6ecfbb88a0](https://linux-hardware.org/?probe=6ecfbb88a0) | Jun 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0ec1b06d0c](https://linux-hardware.org/?probe=0ec1b06d0c) | Jun 13, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [787fa3215e](https://linux-hardware.org/?probe=787fa3215e) | Jun 12, 2023 |
| Dell          | G3 3779                     | Notebook    | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Seco          | C40 C                       | Desktop     | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6b694e4b4a](https://linux-hardware.org/?probe=6b694e4b4a) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [0b7fb76a0b](https://linux-hardware.org/?probe=0b7fb76a0b) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| Google        | Bluebird                    | Notebook    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | Notebook    | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| Unknown       | V00                         | Mini pc     | [79cb590ea8](https://linux-hardware.org/?probe=79cb590ea8) | May 17, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [0906223758](https://linux-hardware.org/?probe=0906223758) | May 17, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c071e02f0d](https://linux-hardware.org/?probe=c071e02f0d) | May 12, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| Biostar       | AM1MHP                      | Desktop     | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | Notebook    | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Gigabyte      | H87-HD3                     | Desktop     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fee636a549](https://linux-hardware.org/?probe=fee636a549) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3165ab3194](https://linux-hardware.org/?probe=3165ab3194) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Samsung       | 950QDB                      | Convertible | [09717388fb](https://linux-hardware.org/?probe=09717388fb) | Mar 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| Samsung       | 950QDB                      | Convertible | [2545626207](https://linux-hardware.org/?probe=2545626207) | Feb 23, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.2.0-20-generic       | 82        | 23.5%   |
| 6.2.0-27-generic       | 26        | 7.45%   |
| 6.2.0-26-generic       | 25        | 7.16%   |
| 6.2.0-34-generic       | 23        | 6.59%   |
| 6.2.0-32-generic       | 20        | 5.73%   |
| 6.2.0-24-generic       | 20        | 5.73%   |
| 6.2.0-33-generic       | 17        | 4.87%   |
| 6.2.0-23-generic       | 17        | 4.87%   |
| 6.2.0-25-generic       | 13        | 3.72%   |
| 6.2.0-39-generic       | 12        | 3.44%   |
| 6.2.0-35-generic       | 10        | 2.87%   |
| 6.2.0-36-generic       | 7         | 2.01%   |
| 6.2.0-31-generic       | 7         | 2.01%   |
| 6.2.0-18-generic       | 4         | 1.15%   |
| 6.2.0-1007-lowlatency  | 4         | 1.15%   |
| 6.2.0-1003-lowlatency  | 4         | 1.15%   |
| 6.2.0-37-generic       | 3         | 0.86%   |
| 6.2.0-1013-lowlatency  | 3         | 0.86%   |
| 6.2.0-1009-lowlatency  | 3         | 0.86%   |
| 6.4.8-060408-generic   | 2         | 0.57%   |
| 6.4.0-060400-generic   | 2         | 0.57%   |
| 6.2.0-1015-lowlatency  | 2         | 0.57%   |
| 6.2.0-1014-lowlatency  | 2         | 0.57%   |
| 6.2.0-1011-lowlatency  | 2         | 0.57%   |
| 6.2.0-1008-lowlatency  | 2         | 0.57%   |
| 6.2.0-1005-lowlatency  | 2         | 0.57%   |
| 5.19.0-42-generic      | 2         | 0.57%   |
| 5.19.0-28-generic      | 2         | 0.57%   |
| 6.5.2                  | 1         | 0.29%   |
| 6.5.1-060501-generic   | 1         | 0.29%   |
| 6.4.9-060409-generic   | 1         | 0.29%   |
| 6.4.6-060406-generic   | 1         | 0.29%   |
| 6.4.3-1-liquorix-amd64 | 1         | 0.29%   |
| 6.4.1-2-liquorix-amd64 | 1         | 0.29%   |
| 6.3.8-x64v3-xanmod1    | 1         | 0.29%   |
| 6.3.8                  | 1         | 0.29%   |
| 6.3.7-060307-generic   | 1         | 0.29%   |
| 6.3.6-custom           | 1         | 0.29%   |
| 6.3.5-060305-generic   | 1         | 0.29%   |
| 6.3.4-060304-generic   | 1         | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 291       | 89.26%  |
| 5.19.0  | 7         | 2.15%   |
| 6.1.0   | 3         | 0.92%   |
| 6.4.8   | 2         | 0.61%   |
| 6.4.0   | 2         | 0.61%   |
| 6.3.8   | 2         | 0.61%   |
| 6.3.1   | 2         | 0.61%   |
| 6.5.2   | 1         | 0.31%   |
| 6.5.1   | 1         | 0.31%   |
| 6.4.9   | 1         | 0.31%   |
| 6.4.6   | 1         | 0.31%   |
| 6.4.3   | 1         | 0.31%   |
| 6.4.1   | 1         | 0.31%   |
| 6.3.7   | 1         | 0.31%   |
| 6.3.6   | 1         | 0.31%   |
| 6.3.5   | 1         | 0.31%   |
| 6.3.4   | 1         | 0.31%   |
| 6.3.3   | 1         | 0.31%   |
| 6.3.10  | 1         | 0.31%   |
| 6.2.5   | 1         | 0.31%   |
| 6.2.10  | 1         | 0.31%   |
| 6.1.12  | 1         | 0.31%   |
| 6.1.11  | 1         | 0.31%   |
| 5.15.0  | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 293       | 89.88%  |
| 6.3     | 10        | 3.07%   |
| 6.4     | 8         | 2.45%   |
| 5.19    | 7         | 2.15%   |
| 6.1     | 5         | 1.53%   |
| 6.5     | 2         | 0.61%   |
| 5.15    | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 322       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| KDE5   | 310       | 96.27%  |
| KDE    | 8         | 2.48%   |
| GNOME  | 2         | 0.62%   |
| LXQt   | 1         | 0.31%   |
| Budgie | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 273       | 84.26%  |
| Wayland | 48        | 14.81%  |
| Tty     | 3         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 201       | 62.23%  |
| Unknown | 106       | 32.82%  |
| GDM3    | 10        | 3.1%    |
| LightDM | 6         | 1.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 156       | 48.3%   |
| de_DE  | 34        | 10.53%  |
| en_GB  | 26        | 8.05%   |
| it_IT  | 16        | 4.95%   |
| ru_RU  | 15        | 4.64%   |
| fr_FR  | 13        | 4.02%   |
| pt_BR  | 8         | 2.48%   |
| pl_PL  | 8         | 2.48%   |
| en_CA  | 5         | 1.55%   |
| es_ES  | 4         | 1.24%   |
| es_MX  | 3         | 0.93%   |
| en_IN  | 3         | 0.93%   |
| C      | 3         | 0.93%   |
| zh_TW  | 2         | 0.62%   |
| sv_SE  | 2         | 0.62%   |
| fr_BE  | 2         | 0.62%   |
| es_CR  | 2         | 0.62%   |
| es_CL  | 2         | 0.62%   |
| en_NZ  | 2         | 0.62%   |
| en_AU  | 2         | 0.62%   |
| zh_HK  | 1         | 0.31%   |
| sk_SK  | 1         | 0.31%   |
| pt_PT  | 1         | 0.31%   |
| nl_NL  | 1         | 0.31%   |
| nb_NO  | 1         | 0.31%   |
| hu_HU  | 1         | 0.31%   |
| es_PE  | 1         | 0.31%   |
| es_CO  | 1         | 0.31%   |
| es_419 | 1         | 0.31%   |
| en_PH  | 1         | 0.31%   |
| en_IL  | 1         | 0.31%   |
| en_DK  | 1         | 0.31%   |
| de_CH  | 1         | 0.31%   |
| da_DK  | 1         | 0.31%   |
| cs_CZ  | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 170       | 52.47%  |
| EFI  | 154       | 47.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 227       | 70.06%  |
| Tmpfs   | 65        | 20.06%  |
| Btrfs   | 20        | 6.17%   |
| Overlay | 7         | 2.16%   |
| Zfs     | 2         | 0.62%   |
| Xfs     | 2         | 0.62%   |
| F2fs    | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 205       | 63.47%  |
| Unknown | 105       | 32.51%  |
| MBR     | 13        | 4.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 283       | 87.08%  |
| Yes       | 42        | 12.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 222       | 68.94%  |
| Yes       | 100       | 31.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 62        | 19.25%  |
| Hewlett-Packard        | 48        | 14.91%  |
| Lenovo                 | 47        | 14.6%   |
| Dell                   | 25        | 7.76%   |
| Gigabyte Technology    | 23        | 7.14%   |
| MSI                    | 21        | 6.52%   |
| Acer                   | 14        | 4.35%   |
| Apple                  | 11        | 3.42%   |
| ASRock                 | 10        | 3.11%   |
| Google                 | 7         | 2.17%   |
| Intel                  | 6         | 1.86%   |
| HUAWEI                 | 5         | 1.55%   |
| AZW                    | 5         | 1.55%   |
| Unknown                | 5         | 1.55%   |
| Samsung Electronics    | 4         | 1.24%   |
| Timi                   | 2         | 0.62%   |
| Fujitsu                | 2         | 0.62%   |
| Alienware              | 2         | 0.62%   |
| Valve                  | 1         | 0.31%   |
| TECNO                  | 1         | 0.31%   |
| Sony                   | 1         | 0.31%   |
| Seco                   | 1         | 0.31%   |
| Pegatron               | 1         | 0.31%   |
| Medion                 | 1         | 0.31%   |
| Intel Client Systems   | 1         | 0.31%   |
| Huanan                 | 1         | 0.31%   |
| HPE                    | 1         | 0.31%   |
| GPU Company            | 1         | 0.31%   |
| GPD                    | 1         | 0.31%   |
| Gateway                | 1         | 0.31%   |
| Framework              | 1         | 0.31%   |
| Foxconn                | 1         | 0.31%   |
| Fanless Mini PC        | 1         | 0.31%   |
| DERE                   | 1         | 0.31%   |
| Colorful Technology    | 1         | 0.31%   |
| CHIPHD                 | 1         | 0.31%   |
| BOSGAME                | 1         | 0.31%   |
| Biostar                | 1         | 0.31%   |
| BESSTAR Tech           | 1         | 0.31%   |
| Avell High Performance | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 6         | 1.86%   |
| AZW SER                                     | 4         | 1.24%   |
| MSI MS-7D75                                 | 2         | 0.62%   |
| MSI MS-7C95                                 | 2         | 0.62%   |
| MSI MS-7C56                                 | 2         | 0.62%   |
| MSI MS-7B86                                 | 2         | 0.62%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW | 2         | 0.62%   |
| Intel NUC12WSHi7                            | 2         | 0.62%   |
| HP ProBook 650 G1                           | 2         | 0.62%   |
| HP ENVY x360 Convertible 15-eu0xxx          | 2         | 0.62%   |
| HP ENVY x360 Convertible 13-ay0xxx          | 2         | 0.62%   |
| Gigabyte B550 AORUS ELITE V2                | 2         | 0.62%   |
| Dell Latitude E5470                         | 2         | 0.62%   |
| Dell G3 3779                                | 2         | 0.62%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA      | 2         | 0.62%   |
| ASUS TUF Gaming B550-PLUS                   | 2         | 0.62%   |
| ASUS ROG STRIX B550-F GAMING                | 2         | 0.62%   |
| ASUS ASUS TUF Gaming F17 FX706LI_FX706LI    | 2         | 0.62%   |
| ASUS All Series                             | 2         | 0.62%   |
| Apple MacBookPro8,1                         | 2         | 0.62%   |
| Apple iMac11,1                              | 2         | 0.62%   |
| Valve Jupiter                               | 1         | 0.31%   |
| Timi RedmiBook Pro 15                       | 1         | 0.31%   |
| Timi Mi NoteBook Pro                        | 1         | 0.31%   |
| TECNO MEGABOOK T1                           | 1         | 0.31%   |
| Sony VPCSA3J1E                              | 1         | 0.31%   |
| Seco C40                                    | 1         | 0.31%   |
| Samsung 950XED                              | 1         | 0.31%   |
| Samsung 950QED                              | 1         | 0.31%   |
| Samsung 950QDB                              | 1         | 0.31%   |
| Samsung 730QCJ/730QCR                       | 1         | 0.31%   |
| Pegatron 520-1000nl                         | 1         | 0.31%   |
| MSI Titan GT77HX 13VH                       | 1         | 0.31%   |
| MSI Raider GE67HX 12UGS                     | 1         | 0.31%   |
| MSI MS-7D74                                 | 1         | 0.31%   |
| MSI MS-7D17                                 | 1         | 0.31%   |
| MSI MS-7C37                                 | 1         | 0.31%   |
| MSI MS-7B24                                 | 1         | 0.31%   |
| MSI MS-7B23                                 | 1         | 0.31%   |
| MSI MS-7A32                                 | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 19        | 5.9%    |
| Lenovo IdeaPad    | 15        | 4.66%   |
| ASUS PRIME        | 14        | 4.35%   |
| ASUS ROG          | 12        | 3.73%   |
| Acer Aspire       | 10        | 3.11%   |
| HP EliteBook      | 9         | 2.8%    |
| HP ENVY           | 7         | 2.17%   |
| Dell Latitude     | 7         | 2.17%   |
| ASUS VivoBook     | 7         | 2.17%   |
| Dell Precision    | 6         | 1.86%   |
| Dell Inspiron     | 6         | 1.86%   |
| ASUS TUF          | 6         | 1.86%   |
| Unknown           | 6         | 1.86%   |
| HP Pavilion       | 5         | 1.55%   |
| HP ProBook        | 4         | 1.24%   |
| HP Laptop         | 4         | 1.24%   |
| Gigabyte B550     | 4         | 1.24%   |
| AZW SER           | 4         | 1.24%   |
| ASUS ASUS         | 4         | 1.24%   |
| Lenovo Yoga       | 3         | 0.93%   |
| Lenovo Legion     | 3         | 0.93%   |
| HP ZBook          | 3         | 0.93%   |
| HP Spectre        | 3         | 0.93%   |
| Dell XPS          | 3         | 0.93%   |
| MSI MS-7D75       | 2         | 0.62%   |
| MSI MS-7C95       | 2         | 0.62%   |
| MSI MS-7C56       | 2         | 0.62%   |
| MSI MS-7B86       | 2         | 0.62%   |
| Lenovo IdeaCentre | 2         | 0.62%   |
| Intel NUC12WSHi7  | 2         | 0.62%   |
| HP Compaq         | 2         | 0.62%   |
| Gigabyte Z390     | 2         | 0.62%   |
| Gigabyte X570S    | 2         | 0.62%   |
| Gigabyte G5       | 2         | 0.62%   |
| Gigabyte B365M    | 2         | 0.62%   |
| Dell G3           | 2         | 0.62%   |
| ASUS Zenbook      | 2         | 0.62%   |
| ASUS P8Z68-V      | 2         | 0.62%   |
| ASUS Maximus      | 2         | 0.62%   |
| ASUS All          | 2         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 48        | 14.91%  |
| 2022 | 47        | 14.6%   |
| 2020 | 37        | 11.49%  |
| 2019 | 35        | 10.87%  |
| 2018 | 25        | 7.76%   |
| 2012 | 22        | 6.83%   |
| 2023 | 18        | 5.59%   |
| 2011 | 15        | 4.66%   |
| 2017 | 14        | 4.35%   |
| 2014 | 14        | 4.35%   |
| 2013 | 13        | 4.04%   |
| 2015 | 10        | 3.11%   |
| 2010 | 9         | 2.8%    |
| 2016 | 8         | 2.48%   |
| 2009 | 4         | 1.24%   |
| 2007 | 2         | 0.62%   |
| 2008 | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 167       | 51.86%  |
| Desktop     | 117       | 36.34%  |
| Convertible | 19        | 5.9%    |
| Mini pc     | 9         | 2.8%    |
| All in one  | 5         | 1.55%   |
| Tablet      | 3         | 0.93%   |
| Server      | 2         | 0.62%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 299       | 92.86%  |
| Enabled  | 23        | 7.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 315       | 97.83%  |
| Yes  | 7         | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 76        | 23.46%  |
| 8.01-16.0   | 72        | 22.22%  |
| 4.01-8.0    | 68        | 20.99%  |
| 32.01-64.0  | 54        | 16.67%  |
| 3.01-4.0    | 24        | 7.41%   |
| 64.01-256.0 | 17        | 5.25%   |
| 24.01-32.0  | 12        | 3.7%    |
| 2.01-3.0    | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 113       | 33.24%  |
| 2.01-3.0   | 83        | 24.41%  |
| 3.01-4.0   | 65        | 19.12%  |
| 1.01-2.0   | 47        | 13.82%  |
| 8.01-16.0  | 24        | 7.06%   |
| 16.01-24.0 | 5         | 1.47%   |
| 32.01-64.0 | 1         | 0.29%   |
| 24.01-32.0 | 1         | 0.29%   |
| 0.51-1.0   | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 169       | 51.52%  |
| 2      | 87        | 26.52%  |
| 3      | 35        | 10.67%  |
| 4      | 21        | 6.4%    |
| 5      | 7         | 2.13%   |
| 6      | 4         | 1.22%   |
| 8      | 2         | 0.61%   |
| 7      | 2         | 0.61%   |
| 11     | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 248       | 76.54%  |
| Yes       | 76        | 23.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 258       | 79.38%  |
| No        | 67        | 20.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 247       | 76.71%  |
| No        | 75        | 23.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 235       | 72.98%  |
| No        | 87        | 27.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 67        | 20.81%  |
| Germany      | 44        | 13.66%  |
| UK           | 26        | 8.07%   |
| Russia       | 19        | 5.9%    |
| Italy        | 17        | 5.28%   |
| France       | 16        | 4.97%   |
| Poland       | 11        | 3.42%   |
| Canada       | 11        | 3.42%   |
| Brazil       | 10        | 3.11%   |
| Sweden       | 7         | 2.17%   |
| Turkey       | 6         | 1.86%   |
| Switzerland  | 6         | 1.86%   |
| Spain        | 5         | 1.55%   |
| Netherlands  | 5         | 1.55%   |
| Mexico       | 5         | 1.55%   |
| India        | 5         | 1.55%   |
| Belgium      | 5         | 1.55%   |
| Hungary      | 4         | 1.24%   |
| Taiwan       | 3         | 0.93%   |
| Portugal     | 3         | 0.93%   |
| Slovakia     | 2         | 0.62%   |
| Serbia       | 2         | 0.62%   |
| Saudi Arabia | 2         | 0.62%   |
| Peru         | 2         | 0.62%   |
| New Zealand  | 2         | 0.62%   |
| Latvia       | 2         | 0.62%   |
| Kazakhstan   | 2         | 0.62%   |
| Israel       | 2         | 0.62%   |
| Costa Rica   | 2         | 0.62%   |
| Colombia     | 2         | 0.62%   |
| Chile        | 2         | 0.62%   |
| Bangladesh   | 2         | 0.62%   |
| Australia    | 2         | 0.62%   |
| South Africa | 1         | 0.31%   |
| Romania      | 1         | 0.31%   |
| Philippines  | 1         | 0.31%   |
| Pakistan     | 1         | 0.31%   |
| Norway       | 1         | 0.31%   |
| Luxembourg   | 1         | 0.31%   |
| Lithuania    | 1         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 7         | 2.12%   |
| Munich            | 5         | 1.52%   |
| London            | 4         | 1.21%   |
| Istanbul          | 4         | 1.21%   |
| Berlin            | 4         | 1.21%   |
| Oldenburg         | 3         | 0.91%   |
| Hamburg           | 3         | 0.91%   |
| Frankfurt am Main | 3         | 0.91%   |
| Warsaw            | 2         | 0.61%   |
| Virginia Beach    | 2         | 0.61%   |
| Vienna            | 2         | 0.61%   |
| Valley Center     | 2         | 0.61%   |
| Sherbrooke        | 2         | 0.61%   |
| Porto Alegre      | 2         | 0.61%   |
| Portimao          | 2         | 0.61%   |
| Philadelphia      | 2         | 0.61%   |
| Paris             | 2         | 0.61%   |
| Olathe            | 2         | 0.61%   |
| Oberburg          | 2         | 0.61%   |
| Münster          | 2         | 0.61%   |
| Montevrain        | 2         | 0.61%   |
| Minneapolis       | 2         | 0.61%   |
| Madrid            | 2         | 0.61%   |
| Grecia            | 2         | 0.61%   |
| Florence          | 2         | 0.61%   |
| Elkridge          | 2         | 0.61%   |
| Edinburgh         | 2         | 0.61%   |
| Brussels          | 2         | 0.61%   |
| Birmingham        | 2         | 0.61%   |
| Arzamas           | 2         | 0.61%   |
| Abtwil            | 2         | 0.61%   |
| Zuchwil           | 1         | 0.3%    |
| Zhubei            | 1         | 0.3%    |
| Zhangbagou        | 1         | 0.3%    |
| Zamora            | 1         | 0.3%    |
| Yerevan           | 1         | 0.3%    |
| Wooster           | 1         | 0.3%    |
| Woodstock         | 1         | 0.3%    |
| Wiesmoor          | 1         | 0.3%    |
| West Valley       | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 90        | 123    | 16.57%  |
| WDC                         | 59        | 73     | 10.87%  |
| Seagate                     | 52        | 81     | 9.58%   |
| SanDisk                     | 46        | 52     | 8.47%   |
| Toshiba                     | 26        | 35     | 4.79%   |
| Kingston                    | 26        | 35     | 4.79%   |
| Crucial                     | 25        | 31     | 4.6%    |
| Intel                       | 18        | 20     | 3.31%   |
| Micron Technology           | 16        | 19     | 2.95%   |
| SK hynix                    | 15        | 15     | 2.76%   |
| Phison Electronics          | 12        | 12     | 2.21%   |
| Unknown                     | 10        | 11     | 1.84%   |
| Hitachi                     | 10        | 11     | 1.84%   |
| A-DATA Technology           | 9         | 12     | 1.66%   |
| Silicon Motion              | 8         | 9      | 1.47%   |
| KIOXIA                      | 7         | 7      | 1.29%   |
| HGST                        | 7         | 9      | 1.29%   |
| Patriot                     | 6         | 6      | 1.1%    |
| Micron/Crucial Technology   | 6         | 8      | 1.1%    |
| Kingston Technology Company | 6         | 9      | 1.1%    |
| PNY                         | 4         | 4      | 0.74%   |
| China                       | 4         | 4      | 0.74%   |
| Unknown                     | 4         | 4      | 0.74%   |
| Transcend                   | 3         | 3      | 0.55%   |
| SPCC                        | 3         | 7      | 0.55%   |
| Maxtor                      | 3         | 3      | 0.55%   |
| Intenso                     | 3         | 4      | 0.55%   |
| Apple                       | 3         | 3      | 0.55%   |
| UMIS                        | 2         | 3      | 0.37%   |
| Team                        | 2         | 2      | 0.37%   |
| SSSTC                       | 2         | 2      | 0.37%   |
| Solid State Storage         | 2         | 2      | 0.37%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.37%   |
| Lexar                       | 2         | 2      | 0.37%   |
| JMicron Technology          | 2         | 2      | 0.37%   |
| Hewlett-Packard             | 2         | 3      | 0.37%   |
| Corsair                     | 2         | 2      | 0.37%   |
| ADATA Technology            | 2         | 2      | 0.37%   |
| Wibtek                      | 1         | 2      | 0.18%   |
| WALRAM                      | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST2000DM008-2FR102 2TB                        | 7         | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 7         | 1.16%   |
| Samsung SSD 860 EVO 500GB                             | 6         | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 6         | 0.99%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 6         | 0.99%   |
| Seagate ST4000DM004-2CV104 4TB                        | 5         | 0.83%   |
| SanDisk NVMe SSD Drive 1TB                            | 5         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 5         | 0.83%   |
| Intel SSD 660P Series 1024GB                          | 5         | 0.83%   |
| Seagate ST2000DM001-1ER164 2TB                        | 4         | 0.66%   |
| Sandisk WD Black SN850 2TB                            | 4         | 0.66%   |
| SanDisk NVMe SSD Drive 2TB                            | 4         | 0.66%   |
| Samsung SSD 850 EVO 250GB                             | 4         | 0.66%   |
| Kingston SNVS500G 500GB                               | 4         | 0.66%   |
| Kingston SA400S37480G 480GB SSD                       | 4         | 0.66%   |
| Kingston SA400S37240G 240GB SSD                       | 4         | 0.66%   |
| Crucial CT1000BX500SSD1 1TB                           | 4         | 0.66%   |
| Unknown                                               | 4         | 0.66%   |
| WDC WDBNCE5000PNC 500GB SSD                           | 3         | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB                           | 3         | 0.5%    |
| Toshiba MQ04ABF100 1TB                                | 3         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3         | 0.5%    |
| Seagate ST1000DM003-1ER162 1TB                        | 3         | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB                        | 3         | 0.5%    |
| Sandisk WD_BLACK SN850X 4000GB                        | 3         | 0.5%    |
| SanDisk SSD PLUS 1000GB                               | 3         | 0.5%    |
| Samsung SSD 980 PRO 2TB                               | 3         | 0.5%    |
| Samsung SSD 980 PRO 1TB                               | 3         | 0.5%    |
| Samsung SSD 980 1TB                                   | 3         | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB                        | 3         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB                          | 3         | 0.5%    |
| Samsung SSD 870 QVO 1TB                               | 3         | 0.5%    |
| Samsung SSD 850 PRO 512GB                             | 3         | 0.5%    |
| Samsung MZVLQ256HAJD-000H1 256GB                      | 3         | 0.5%    |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 3         | 0.5%    |
| Kingston Company SNV2S1000G 1TB                       | 3         | 0.5%    |
| Intel SSDPEKNU512GZ 512GB                             | 3         | 0.5%    |
| Crucial CT250MX500SSD1 250GB                          | 3         | 0.5%    |
| WDC WD5000AAKX-60U6AA0 500GB                          | 2         | 0.33%   |
| WDC WD10SPZX-24Z10 1TB                                | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 78     | 35.71%  |
| WDC                 | 35        | 44     | 25%     |
| Toshiba             | 20        | 26     | 14.29%  |
| Hitachi             | 10        | 11     | 7.14%   |
| HGST                | 7         | 9      | 5%      |
| Samsung Electronics | 5         | 5      | 3.57%   |
| Unknown             | 3         | 3      | 2.14%   |
| Maxtor              | 3         | 3      | 2.14%   |
| JMicron Technology  | 2         | 2      | 1.43%   |
| SSI                 | 1         | 1      | 0.71%   |
| LaCie               | 1         | 1      | 0.71%   |
| External            | 1         | 3      | 0.71%   |
| ASMT                | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 42     | 17.71%  |
| Kingston            | 20        | 25     | 11.43%  |
| SanDisk             | 18        | 22     | 10.29%  |
| Crucial             | 18        | 22     | 10.29%  |
| WDC                 | 16        | 19     | 9.14%   |
| Micron Technology   | 6         | 8      | 3.43%   |
| Intel               | 5         | 6      | 2.86%   |
| A-DATA Technology   | 5         | 7      | 2.86%   |
| PNY                 | 4         | 4      | 2.29%   |
| Patriot             | 4         | 4      | 2.29%   |
| China               | 4         | 4      | 2.29%   |
| Transcend           | 3         | 3      | 1.71%   |
| Team                | 2         | 2      | 1.14%   |
| SPCC                | 2         | 6      | 1.14%   |
| SK hynix            | 2         | 2      | 1.14%   |
| Seagate             | 2         | 2      | 1.14%   |
| Hewlett-Packard     | 2         | 2      | 1.14%   |
| Wibtek              | 1         | 2      | 0.57%   |
| Vaseky              | 1         | 1      | 0.57%   |
| Toshiba             | 1         | 1      | 0.57%   |
| Smartbuy            | 1         | 1      | 0.57%   |
| SCCTS-603-001T      | 1         | 1      | 0.57%   |
| SADAYU              | 1         | 1      | 0.57%   |
| S3+                 | 1         | 1      | 0.57%   |
| Plextor             | 1         | 1      | 0.57%   |
| PHD 3.0             | 1         | 1      | 0.57%   |
| OCZ                 | 1         | 1      | 0.57%   |
| Netac               | 1         | 1      | 0.57%   |
| Neo                 | 1         | 1      | 0.57%   |
| MII                 | 1         | 1      | 0.57%   |
| M4-CT128            | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| LITEON              | 1         | 1      | 0.57%   |
| Lexar               | 1         | 1      | 0.57%   |
| Lenovo              | 1         | 1      | 0.57%   |
| Intenso             | 1         | 1      | 0.57%   |
| INNOVATION IT       | 1         | 1      | 0.57%   |
| Hoodisk             | 1         | 1      | 0.57%   |
| Gigabyte Technology | 1         | 1      | 0.57%   |
| FURY                | 1         | 2      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 195       | 258    | 41.4%   |
| SSD     | 152       | 217    | 32.27%  |
| HDD     | 104       | 188    | 22.08%  |
| Unknown | 12        | 14     | 2.55%   |
| MMC     | 8         | 9      | 1.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 195       | 256    | 46.54%  |
| SATA | 191       | 383    | 45.58%  |
| SAS  | 25        | 38     | 5.97%   |
| MMC  | 8         | 9      | 1.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 132       | 188    | 46.48%  |
| 0.51-1.0   | 85        | 123    | 29.93%  |
| 1.01-2.0   | 39        | 56     | 13.73%  |
| 3.01-4.0   | 16        | 21     | 5.63%   |
| 4.01-10.0  | 8         | 13     | 2.82%   |
| 2.01-3.0   | 2         | 2      | 0.7%    |
| 10.01-20.0 | 2         | 2      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 25.98%  |
| 251-500        | 65        | 19.64%  |
| 501-1000       | 61        | 18.43%  |
| 1001-2000      | 42        | 12.69%  |
| More than 3000 | 32        | 9.67%   |
| 51-100         | 15        | 4.53%   |
| 2001-3000      | 14        | 4.23%   |
| 1-20           | 9         | 2.72%   |
| 21-50          | 7         | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 67        | 19.94%  |
| 1-20           | 66        | 19.64%  |
| 101-250        | 59        | 17.56%  |
| 51-100         | 42        | 12.5%   |
| 251-500        | 34        | 10.12%  |
| 501-1000       | 33        | 9.82%   |
| 1001-2000      | 17        | 5.06%   |
| More than 3000 | 12        | 3.57%   |
| 2001-3000      | 6         | 1.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 2      | 3.85%   |
| WDC WD3200AAJS-65M0A0 320GB                  | 1         | 1      | 3.85%   |
| WDC WD10EZEX-22MFCA0 1TB                     | 1         | 1      | 3.85%   |
| WDC WD10EURX-63UY4Y0 1TB                     | 1         | 1      | 3.85%   |
| WDC WD10EAVS-00D7B1 1TB                      | 1         | 1      | 3.85%   |
| WDC WD10EADS-65L5B1 1TB                      | 1         | 1      | 3.85%   |
| WDC WD Blue SA510 2.5 1000GB SSD             | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD075 752GB                     | 1         | 2      | 3.85%   |
| Team L3 EVO SSD 120GB                        | 1         | 1      | 3.85%   |
| SK hynix HFS256G32MND-2900A 256GB SSD        | 1         | 1      | 3.85%   |
| Seagate ST3500320AS 500GB                    | 1         | 1      | 3.85%   |
| Seagate ST31500341AS 1TB                     | 1         | 1      | 3.85%   |
| Seagate ST1000VX000-1CU162 1TB               | 1         | 1      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 3.85%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 3.85%   |
| SanDisk SDSSDXPS480G 480GB                   | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 970 EVO Plus 1TB     | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 850 EVO 250GB        | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 3.85%   |
| Samsung Electronics HD103SI 1TB              | 1         | 1      | 3.85%   |
| Neo Forza NFS121SA312-6007000 120GB SSD      | 1         | 1      | 3.85%   |
| Maxtor STM3160215AS 160GB                    | 1         | 1      | 3.85%   |
| Intel SSDSCKKW240H6 240GB                    | 1         | 1      | 3.85%   |
| Intel SSDPEKNW512G8 512GB                    | 1         | 2      | 3.85%   |
| Intel SSDPEKNU512GZ 512GB                    | 1         | 1      | 3.85%   |
| Apple HDD HTS541010A9E662 1TB                | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 26.92%  |
| Seagate             | 5         | 5      | 19.23%  |
| Samsung Electronics | 4         | 5      | 15.38%  |
| Intel               | 3         | 4      | 11.54%  |
| Toshiba             | 1         | 2      | 3.85%   |
| Team                | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| SanDisk             | 1         | 1      | 3.85%   |
| Neo                 | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| Apple               | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 40%     |
| Seagate             | 5         | 5      | 33.33%  |
| Toshiba             | 1         | 2      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| Maxtor              | 1         | 1      | 6.67%   |
| Apple               | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 17     | 52.38%  |
| SSD  | 7         | 9      | 33.33%  |
| NVMe | 3         | 4      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 195       | 415    | 54.93%  |
| Works    | 139       | 239    | 39.15%  |
| Malfunc  | 20        | 30     | 5.63%   |
| Failed   | 1         | 2      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 168       | 35.29%  |
| AMD                            | 85        | 17.86%  |
| Samsung Electronics            | 62        | 13.03%  |
| SanDisk                        | 37        | 7.77%   |
| Phison Electronics             | 14        | 2.94%   |
| SK hynix                       | 13        | 2.73%   |
| Micron/Crucial Technology      | 13        | 2.73%   |
| Kingston Technology Company    | 11        | 2.31%   |
| Silicon Motion                 | 10        | 2.1%    |
| Micron Technology              | 10        | 2.1%    |
| ASMedia Technology             | 7         | 1.47%   |
| Toshiba America Info Systems   | 6         | 1.26%   |
| KIOXIA                         | 6         | 1.26%   |
| ADATA Technology               | 5         | 1.05%   |
| Union Memory (Shenzhen)        | 4         | 0.84%   |
| Solid State Storage Technology | 4         | 0.84%   |
| JMicron Technology             | 4         | 0.84%   |
| Realtek Semiconductor          | 3         | 0.63%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.63%   |
| Marvell Technology Group       | 3         | 0.63%   |
| Shenzhen Longsys Electronics   | 2         | 0.42%   |
| VIA Technologies               | 1         | 0.21%   |
| Silicon Image                  | 1         | 0.21%   |
| Nvidia                         | 1         | 0.21%   |
| LSI Logic / Symbios Logic      | 1         | 0.21%   |
| Biwin Storage Technology       | 1         | 0.21%   |
| Apple                          | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 55        | 10.44%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 22        | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 3.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 2.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13        | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 2.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 2.47%   |
| AMD 500 Series Chipset SATA Controller                                         | 13        | 2.47%   |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 2.28%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10        | 1.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 1.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 8         | 1.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.52%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 7         | 1.33%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 7         | 1.33%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 7         | 1.33%   |
| Intel SSD 660P Series                                                          | 7         | 1.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.33%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 7         | 1.33%   |
| AMD 600 Series Chipset SATA Controller                                         | 7         | 1.33%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 6         | 1.14%   |
| Intel SATA Controller [RAID mode]                                              | 6         | 1.14%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 5         | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 0.95%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 0.95%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.95%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 0.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 0.76%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 4         | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4         | 0.76%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 4         | 0.76%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 4         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 219       | 48.03%  |
| NVMe | 194       | 42.54%  |
| RAID | 31        | 6.8%    |
| IDE  | 11        | 2.41%   |
| SAS  | 1         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 206       | 63.98%  |
| AMD    | 116       | 36.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 3.11%   |
| Intel 12th Gen Core i7-1260P                  | 7         | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 1.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 5         | 1.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.24%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.24%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.93%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.93%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 0.93%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 0.93%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 0.93%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 3         | 0.93%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 0.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.93%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.93%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.93%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 3         | 0.93%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.62%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.62%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.62%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.62%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.62%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.62%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.62%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 2         | 0.62%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 0.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.62%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 2         | 0.62%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 2         | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.62%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.62%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.62%   |
| Intel Celeron N5105 @ 2.00GHz                 | 2         | 0.62%   |
| Intel Celeron N5100 @ 1.10GHz                 | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 63        | 19.57%  |
| Other                   | 56        | 17.39%  |
| AMD Ryzen 5             | 48        | 14.91%  |
| Intel Core i7           | 47        | 14.6%   |
| AMD Ryzen 7             | 36        | 11.18%  |
| Intel Celeron           | 15        | 4.66%   |
| Intel Core i3           | 10        | 3.11%   |
| AMD Ryzen 9             | 10        | 3.11%   |
| Intel Xeon              | 6         | 1.86%   |
| Intel Pentium           | 3         | 0.93%   |
| AMD Ryzen 5 PRO         | 3         | 0.93%   |
| AMD FX                  | 3         | 0.93%   |
| Intel Pentium Dual-Core | 2         | 0.62%   |
| Intel Core 2 Duo        | 2         | 0.62%   |
| AMD Phenom II X4        | 2         | 0.62%   |
| AMD A4                  | 2         | 0.62%   |
| Intel Pentium Silver    | 1         | 0.31%   |
| Intel Pentium Gold      | 1         | 0.31%   |
| Intel Core i9           | 1         | 0.31%   |
| AMD Ryzen Embedded      | 1         | 0.31%   |
| AMD Ryzen 7 PRO         | 1         | 0.31%   |
| AMD Ryzen 3 PRO         | 1         | 0.31%   |
| AMD Ryzen 3             | 1         | 0.31%   |
| AMD PRO A10             | 1         | 0.31%   |
| AMD Phenom II X6        | 1         | 0.31%   |
| AMD Athlon II X3        | 1         | 0.31%   |
| AMD Athlon              | 1         | 0.31%   |
| AMD A8                  | 1         | 0.31%   |
| AMD A6                  | 1         | 0.31%   |
| AMD A10                 | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 123       | 38.2%   |
| 6      | 61        | 18.94%  |
| 2      | 57        | 17.7%   |
| 8      | 46        | 14.29%  |
| 12     | 14        | 4.35%   |
| 10     | 7         | 2.17%   |
| 16     | 5         | 1.55%   |
| 14     | 4         | 1.24%   |
| 3      | 3         | 0.93%   |
| 24     | 2         | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 321       | 99.69%  |
| 2      | 1         | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 250       | 77.64%  |
| 1      | 72        | 22.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 322       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 261       | 80.06%  |
| 0x0a50000c | 11        | 3.37%   |
| 0x0a601203 | 7         | 2.15%   |
| 0x08608103 | 6         | 1.84%   |
| 0x0a404102 | 4         | 1.23%   |
| 0x0a50000d | 3         | 0.92%   |
| 0x0a20120a | 3         | 0.92%   |
| 0x08701021 | 3         | 0.92%   |
| 0x08600104 | 3         | 0.92%   |
| 0x08108109 | 3         | 0.92%   |
| 0x0a404101 | 2         | 0.61%   |
| 0x0800820d | 2         | 0.61%   |
| 0x906a3    | 1         | 0.31%   |
| 0x90672    | 1         | 0.31%   |
| 0x306c3    | 1         | 0.31%   |
| 0x0a201025 | 1         | 0.31%   |
| 0x08a00008 | 1         | 0.31%   |
| 0x08900201 | 1         | 0.31%   |
| 0x08701030 | 1         | 0.31%   |
| 0x08701013 | 1         | 0.31%   |
| 0x08600106 | 1         | 0.31%   |
| 0x08108102 | 1         | 0.31%   |
| 0x08101016 | 1         | 0.31%   |
| 0x0810100b | 1         | 0.31%   |
| 0x08101007 | 1         | 0.31%   |
| 0x08001138 | 1         | 0.31%   |
| 0x0700010f | 1         | 0.31%   |
| 0x06000852 | 1         | 0.31%   |
| 0x03000027 | 1         | 0.31%   |
| 0x010000dc | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 48        | 14.86%  |
| KabyLake         | 44        | 13.62%  |
| Zen 3            | 31        | 9.6%    |
| Haswell          | 21        | 6.5%    |
| Zen 2            | 19        | 5.88%   |
| TigerLake        | 19        | 5.88%   |
| Zen+             | 18        | 5.57%   |
| Alderlake Hybrid | 18        | 5.57%   |
| Skylake          | 17        | 5.26%   |
| SandyBridge      | 17        | 5.26%   |
| IvyBridge        | 16        | 4.95%   |
| Zen              | 6         | 1.86%   |
| Nehalem          | 6         | 1.86%   |
| IceLake          | 5         | 1.55%   |
| CometLake        | 5         | 1.55%   |
| Broadwell        | 5         | 1.55%   |
| K10              | 4         | 1.24%   |
| Goldmont         | 4         | 1.24%   |
| Piledriver       | 3         | 0.93%   |
| Penryn           | 3         | 0.93%   |
| Westmere         | 2         | 0.62%   |
| Tremont          | 2         | 0.62%   |
| Puma             | 2         | 0.62%   |
| Goldmont plus    | 2         | 0.62%   |
| Excavator        | 2         | 0.62%   |
| Steamroller      | 1         | 0.31%   |
| K10 Llano        | 1         | 0.31%   |
| Jaguar           | 1         | 0.31%   |
| Core             | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 165       | 42.53%  |
| AMD    | 125       | 32.22%  |
| Nvidia | 98        | 25.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 15        | 3.81%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 13        | 3.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 13        | 3.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 12        | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 12        | 3.05%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 2.79%   |
| AMD Lucienne                                                                  | 11        | 2.79%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 10        | 2.54%   |
| Intel HD Graphics 530                                                         | 8         | 2.03%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 8         | 2.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 7         | 1.78%   |
| AMD Rembrandt [Radeon 680M]                                                   | 7         | 1.78%   |
| AMD Raphael                                                                   | 7         | 1.78%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 7         | 1.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 6         | 1.52%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 6         | 1.52%   |
| Intel JasperLake [UHD Graphics]                                               | 6         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 6         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 6         | 1.52%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 1.27%   |
| Intel HD Graphics 620                                                         | 5         | 1.27%   |
| AMD Barcelo                                                                   | 5         | 1.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4         | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 1.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 1.02%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 3         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 3         | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 3         | 0.76%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                | 3         | 0.76%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                 | 3         | 0.76%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 3         | 0.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 0.76%   |
| Intel HD Graphics 630                                                         | 3         | 0.76%   |
| Intel HD Graphics 500                                                         | 3         | 0.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 3         | 0.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 111       | 34.47%  |
| 1 x AMD         | 96        | 29.81%  |
| 1 x Nvidia      | 44        | 13.66%  |
| Intel + Nvidia  | 39        | 12.11%  |
| AMD + Nvidia    | 13        | 4.04%   |
| Intel + AMD     | 10        | 3.11%   |
| 2 x AMD         | 5         | 1.55%   |
| Other           | 1         | 0.31%   |
| 2 x Nvidia      | 1         | 0.31%   |
| 2 x Intel       | 1         | 0.31%   |
| Intel + 2 x AMD | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 241       | 74.15%  |
| Proprietary | 79        | 24.31%  |
| Unknown     | 5         | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 209       | 64.11%  |
| 0.01-0.5   | 25        | 7.67%   |
| 3.01-4.0   | 23        | 7.06%   |
| 7.01-8.0   | 20        | 6.13%   |
| 1.01-2.0   | 19        | 5.83%   |
| 5.01-6.0   | 8         | 2.45%   |
| 8.01-16.0  | 8         | 2.45%   |
| 0.51-1.0   | 8         | 2.45%   |
| 16.01-24.0 | 3         | 0.92%   |
| 2.01-3.0   | 2         | 0.61%   |
| 4.01-5.0   | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 51        | 13.71%  |
| BOE                     | 44        | 11.83%  |
| AU Optronics            | 38        | 10.22%  |
| Chimei Innolux          | 28        | 7.53%   |
| Dell                    | 24        | 6.45%   |
| LG Display              | 22        | 5.91%   |
| Goldstar                | 16        | 4.3%    |
| Hewlett-Packard         | 12        | 3.23%   |
| Philips                 | 10        | 2.69%   |
| Iiyama                  | 10        | 2.69%   |
| Acer                    | 10        | 2.69%   |
| Apple                   | 9         | 2.42%   |
| AOC                     | 9         | 2.42%   |
| Ancor Communications    | 8         | 2.15%   |
| Lenovo                  | 7         | 1.88%   |
| ASUSTek Computer        | 7         | 1.88%   |
| PANDA                   | 6         | 1.61%   |
| BenQ                    | 6         | 1.61%   |
| Sharp                   | 5         | 1.34%   |
| InfoVision              | 5         | 1.34%   |
| Eizo                    | 4         | 1.08%   |
| MSI                     | 3         | 0.81%   |
| Gigabyte Technology     | 3         | 0.81%   |
| ViewSonic               | 2         | 0.54%   |
| SAC                     | 2         | 0.54%   |
| Chi Mei Optoelectronics | 2         | 0.54%   |
| Wacom                   | 1         | 0.27%   |
| Vizio                   | 1         | 0.27%   |
| VIZ                     | 1         | 0.27%   |
| Valve                   | 1         | 0.27%   |
| UGD                     | 1         | 0.27%   |
| TMX                     | 1         | 0.27%   |
| STA                     | 1         | 0.27%   |
| Sceptre Tech            | 1         | 0.27%   |
| RTK                     | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| ONN                     | 1         | 0.27%   |
| NEC Computers           | 1         | 0.27%   |
| Mi                      | 1         | 0.27%   |
| Medion Akoya            | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 3         | 0.76%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 0.76%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 3         | 0.76%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.51%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 2         | 0.51%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 2         | 0.51%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 2         | 0.51%   |
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                 | 2         | 0.51%   |
| Iiyama PL2783Q IVM661E 2560x1440 597x336mm 27.0-inch                  | 2         | 0.51%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 2         | 0.51%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 2         | 0.51%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.51%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 2         | 0.51%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                 | 2         | 0.51%   |
| BOE LCD Monitor BOE0892 2160x1440 275x183mm 13.0-inch                 | 2         | 0.51%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch         | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch        | 2         | 0.51%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 2         | 0.51%   |
| Ancor Communications MX259 ACI25C2 1920x1080 550x310mm 24.9-inch      | 2         | 0.51%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch              | 1         | 0.25%   |
| Vizio D24h-G9 VIZ1028 1366x768 521x293mm 23.5-inch                    | 1         | 0.25%   |
| VIZ LCD Monitor D32h-J04 1920x1080                                    | 1         | 0.25%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch             | 1         | 0.25%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 1         | 0.25%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.25%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1         | 0.25%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 0.25%   |
| STA SEMP LEDTV STA0030 1920x1080 708x398mm 32.0-inch                  | 1         | 0.25%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.25%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.25%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.25%   |
| Sceptre Tech Sceptre F27 SPT0AD7 1920x1080 600x330mm 27.0-inch        | 1         | 0.25%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 169       | 47.34%  |
| 1366x768 (WXGA)    | 40        | 11.2%   |
| 3840x2160 (4K)     | 38        | 10.64%  |
| 2560x1440 (QHD)    | 26        | 7.28%   |
| 1920x1200 (WUXGA)  | 11        | 3.08%   |
| 1600x900 (HD+)     | 10        | 2.8%    |
| 2560x1080          | 8         | 2.24%   |
| 2560x1600          | 7         | 1.96%   |
| 1440x900 (WXGA+)   | 7         | 1.96%   |
| 3440x1440          | 6         | 1.68%   |
| 2880x1800          | 4         | 1.12%   |
| 1920x1280          | 3         | 0.84%   |
| 1680x1050 (WSXGA+) | 3         | 0.84%   |
| 1280x800 (WXGA)    | 3         | 0.84%   |
| 3840x2400          | 2         | 0.56%   |
| 2240x1400          | 2         | 0.56%   |
| 2160x1440          | 2         | 0.56%   |
| 1920x540           | 2         | 0.56%   |
| 1280x1024 (SXGA)   | 2         | 0.56%   |
| 800x1280           | 1         | 0.28%   |
| 3840x1100          | 1         | 0.28%   |
| 3840x1080          | 1         | 0.28%   |
| 3456x2160          | 1         | 0.28%   |
| 3200x2000          | 1         | 0.28%   |
| 3072x1920          | 1         | 0.28%   |
| 3000x2000          | 1         | 0.28%   |
| 2736x1824          | 1         | 0.28%   |
| 2256x1504          | 1         | 0.28%   |
| 1360x768           | 1         | 0.28%   |
| 1280x720 (HD)      | 1         | 0.28%   |
| Unknown            | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 75        | 19.95%  |
| 24      | 40        | 10.64%  |
| 27      | 39        | 10.37%  |
| 13      | 34        | 9.04%   |
| 14      | 32        | 8.51%   |
| 17      | 24        | 6.38%   |
| 31      | 19        | 5.05%   |
| 23      | 19        | 5.05%   |
| 21      | 14        | 3.72%   |
| 34      | 12        | 3.19%   |
| 19      | 10        | 2.66%   |
| 12      | 8         | 2.13%   |
| 16      | 7         | 1.86%   |
| 11      | 6         | 1.6%    |
| 28      | 4         | 1.06%   |
| Unknown | 4         | 1.06%   |
| 40      | 3         | 0.8%    |
| 22      | 3         | 0.8%    |
| 20      | 3         | 0.8%    |
| 18      | 3         | 0.8%    |
| 72      | 2         | 0.53%   |
| 46      | 2         | 0.53%   |
| 84      | 1         | 0.27%   |
| 69      | 1         | 0.27%   |
| 65      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 52      | 1         | 0.27%   |
| 43      | 1         | 0.27%   |
| 42      | 1         | 0.27%   |
| 37      | 1         | 0.27%   |
| 33      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 25      | 1         | 0.27%   |
| 7       | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 128       | 34.78%  |
| 501-600     | 93        | 25.27%  |
| 201-300     | 32        | 8.7%    |
| 401-500     | 30        | 8.15%   |
| 601-700     | 26        | 7.07%   |
| 351-400     | 25        | 6.79%   |
| 701-800     | 14        | 3.8%    |
| 1001-1500   | 5         | 1.36%   |
| 801-900     | 4         | 1.09%   |
| 1501-2000   | 4         | 1.09%   |
| Unknown     | 4         | 1.09%   |
| 901-1000    | 2         | 0.54%   |
| 1-100       | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 260       | 77.38%  |
| 16/10   | 47        | 13.99%  |
| 21/9    | 13        | 3.87%   |
| 3/2     | 8         | 2.38%   |
| Unknown | 3         | 0.89%   |
| 5/4     | 2         | 0.6%    |
| 4/3     | 1         | 0.3%    |
| 3.40    | 1         | 0.3%    |
| 0.67    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 75        | 20.05%  |
| 201-250        | 57        | 15.24%  |
| 81-90          | 52        | 13.9%   |
| 301-350        | 40        | 10.7%   |
| 351-500        | 35        | 9.36%   |
| 121-130        | 23        | 6.15%   |
| 251-300        | 19        | 5.08%   |
| 151-200        | 14        | 3.74%   |
| 71-80          | 12        | 3.21%   |
| 501-1000       | 8         | 2.14%   |
| More than 1000 | 7         | 1.87%   |
| 51-60          | 7         | 1.87%   |
| 111-120        | 7         | 1.87%   |
| 61-70          | 6         | 1.6%    |
| 141-150        | 4         | 1.07%   |
| Unknown        | 4         | 1.07%   |
| 91-100         | 3         | 0.8%    |
| 1-40           | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 114       | 32.2%   |
| 51-100        | 112       | 31.64%  |
| 101-120       | 64        | 18.08%  |
| 161-240       | 38        | 10.73%  |
| More than 240 | 15        | 4.24%   |
| 1-50          | 7         | 1.98%   |
| Unknown       | 4         | 1.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 244       | 75.54%  |
| 2     | 68        | 21.05%  |
| 3     | 7         | 2.17%   |
| 0     | 3         | 0.93%   |
| 4     | 1         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 186       | 38.91%  |
| Intel                             | 152       | 31.8%   |
| MediaTek                          | 30        | 6.28%   |
| Qualcomm Atheros                  | 26        | 5.44%   |
| Broadcom                          | 21        | 4.39%   |
| TP-Link                           | 7         | 1.46%   |
| Ralink                            | 7         | 1.46%   |
| ASIX Electronics                  | 6         | 1.26%   |
| Broadcom Limited                  | 5         | 1.05%   |
| Hewlett-Packard                   | 4         | 0.84%   |
| ASUSTek Computer                  | 4         | 0.84%   |
| Google                            | 3         | 0.63%   |
| Xiaomi                            | 2         | 0.42%   |
| Samsung Electronics               | 2         | 0.42%   |
| Qualcomm                          | 2         | 0.42%   |
| Microsoft                         | 2         | 0.42%   |
| Huawei Technologies               | 2         | 0.42%   |
| Arduino SA                        | 2         | 0.42%   |
| ZyXEL Communications              | 1         | 0.21%   |
| Van Ooijen Technische Informatica | 1         | 0.21%   |
| U-Blox                            | 1         | 0.21%   |
| Texas Instruments                 | 1         | 0.21%   |
| Tehuti Networks                   | 1         | 0.21%   |
| QinHeng Electronics               | 1         | 0.21%   |
| Nvidia                            | 1         | 0.21%   |
| NetGear                           | 1         | 0.21%   |
| Linksys                           | 1         | 0.21%   |
| Lenovo                            | 1         | 0.21%   |
| ICS Advent                        | 1         | 0.21%   |
| DisplayLink                       | 1         | 0.21%   |
| Dell                              | 1         | 0.21%   |
| D-Link System                     | 1         | 0.21%   |
| Aquantia                          | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 108       | 19.78%  |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 4.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 15        | 2.75%   |
| Intel Wi-Fi 6 AX201                                                    | 14        | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 2.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 11        | 2.01%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 2.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 11        | 2.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 10        | 1.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 9         | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.65%   |
| Intel Wireless 7265                                                    | 9         | 1.65%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9         | 1.65%   |
| Intel Wi-Fi 6 AX200                                                    | 9         | 1.65%   |
| Intel Wireless 8265 / 8275                                             | 7         | 1.28%   |
| Intel Ethernet Controller I225-V                                       | 7         | 1.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 1.1%    |
| Intel Wireless 8260                                                    | 6         | 1.1%    |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 5         | 0.92%   |
| Intel Wireless 7260                                                    | 5         | 0.92%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 0.73%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.73%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.73%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 4         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 0.55%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 3         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 118       | 45.74%  |
| Realtek Semiconductor | 47        | 18.22%  |
| MediaTek              | 25        | 9.69%   |
| Qualcomm Atheros      | 23        | 8.91%   |
| Broadcom              | 14        | 5.43%   |
| TP-Link               | 7         | 2.71%   |
| Ralink                | 7         | 2.71%   |
| ASUSTek Computer      | 4         | 1.55%   |
| Broadcom Limited      | 3         | 1.16%   |
| Microsoft             | 2         | 0.78%   |
| Hewlett-Packard       | 2         | 0.78%   |
| ZyXEL Communications  | 1         | 0.39%   |
| Qualcomm              | 1         | 0.39%   |
| NetGear               | 1         | 0.39%   |
| Linksys               | 1         | 0.39%   |
| Dell                  | 1         | 0.39%   |
| D-Link System         | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 14        | 5.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 4.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 4.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 3.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 3.47%   |
| Intel Wireless 7265                                            | 9         | 3.47%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 9         | 3.47%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 3.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8         | 3.09%   |
| Intel Wireless 8265 / 8275                                     | 7         | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 2.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 6         | 2.32%   |
| Intel Wireless 8260                                            | 6         | 2.32%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 6         | 2.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.93%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 1.93%   |
| Intel Wireless 7260                                            | 5         | 1.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.16%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 3         | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.16%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.77%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2         | 0.77%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.77%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.77%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.77%   |
| Realtek 802.11ac NIC                                           | 2         | 0.77%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 2         | 0.77%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 162       | 58.48%  |
| Intel                 | 67        | 24.19%  |
| Broadcom              | 12        | 4.33%   |
| Qualcomm Atheros      | 7         | 2.53%   |
| ASIX Electronics      | 6         | 2.17%   |
| MediaTek              | 5         | 1.81%   |
| Google                | 3         | 1.08%   |
| Xiaomi                | 2         | 0.72%   |
| Samsung Electronics   | 2         | 0.72%   |
| Huawei Technologies   | 2         | 0.72%   |
| Broadcom Limited      | 2         | 0.72%   |
| Tehuti Networks       | 1         | 0.36%   |
| Qualcomm              | 1         | 0.36%   |
| Nvidia                | 1         | 0.36%   |
| Lenovo                | 1         | 0.36%   |
| ICS Advent            | 1         | 0.36%   |
| DisplayLink           | 1         | 0.36%   |
| Aquantia              | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 108       | 38.71%  |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 8.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 15        | 5.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 4.3%    |
| Intel I211 Gigabit Network Connection                                  | 11        | 3.94%   |
| Intel Ethernet Controller I225-V                                       | 7         | 2.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 2.51%   |
| Intel Ethernet Connection (7) I219-V                                   | 5         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.43%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.43%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.08%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.72%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.72%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.72%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 0.72%   |
| Huawei FOA-LX9                                                         | 2         | 0.72%   |
| Google Pixel 6a                                                        | 2         | 0.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.36%   |
| Tehuti Networks TN9210 10GBase-T Ethernet Adapter                      | 1         | 0.36%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.36%   |
| Qualcomm POCO F3                                                       | 1         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.36%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.36%   |
| MediaTek Infinix SMART 5                                               | 1         | 0.36%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.36%   |
| Intel Ethernet Controller I219-V                                       | 1         | 0.36%   |
| Intel Ethernet Controller I219-LM                                      | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 255       | 50.1%   |
| WiFi     | 247       | 48.53%  |
| Modem    | 7         | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 199       | 58.53%  |
| Ethernet | 141       | 41.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 169       | 52.32%  |
| 2     | 147       | 45.51%  |
| 3     | 3         | 0.93%   |
| 0     | 3         | 0.93%   |
| 5     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 230       | 70.55%  |
| Yes  | 96        | 29.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 112       | 47.06%  |
| Realtek Semiconductor           | 33        | 13.87%  |
| Cambridge Silicon Radio         | 15        | 6.3%    |
| IMC Networks                    | 12        | 5.04%   |
| Apple                           | 11        | 4.62%   |
| Qualcomm Atheros Communications | 9         | 3.78%   |
| Foxconn / Hon Hai               | 9         | 3.78%   |
| MediaTek                        | 8         | 3.36%   |
| Lite-On Technology              | 8         | 3.36%   |
| Broadcom                        | 7         | 2.94%   |
| Realtek                         | 3         | 1.26%   |
| ASUSTek Computer                | 3         | 1.26%   |
| TP-Link                         | 2         | 0.84%   |
| Ralink                          | 2         | 0.84%   |
| Toshiba                         | 1         | 0.42%   |
| Logitech                        | 1         | 0.42%   |
| Foxconn International           | 1         | 0.42%   |
| Dell                            | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 30        | 12.61%  |
| Intel AX201 Bluetooth                               | 27        | 11.34%  |
| Realtek Bluetooth Radio                             | 26        | 10.92%  |
| Intel AX211 Bluetooth                               | 20        | 8.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 6.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 4.62%   |
| Intel AX210 Bluetooth                               | 10        | 4.2%    |
| Intel AX200 Bluetooth                               | 9         | 3.78%   |
| MediaTek Wireless_Device                            | 8         | 3.36%   |
| IMC Networks Wireless_Device                        | 6         | 2.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.1%    |
| IMC Networks Bluetooth Radio                        | 5         | 2.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 1.68%   |
| Lite-On Wireless_Device                             | 4         | 1.68%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 1.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 1.68%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.68%   |
| Realtek Bluetooth Radio                             | 3         | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.26%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.26%   |
| Apple Bluetooth Host Controller                     | 3         | 1.26%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 2         | 0.84%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.84%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.84%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.84%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.84%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.42%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.42%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.42%   |
| Lite-On Bluetooth Device                            | 1         | 0.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.42%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.42%   |
| IMC Networks BCM20702A0                             | 1         | 0.42%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.42%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.42%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.42%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 204       | 42.32%  |
| AMD                          | 137       | 28.42%  |
| Nvidia                       | 78        | 16.18%  |
| C-Media Electronics          | 10        | 2.07%   |
| Logitech                     | 6         | 1.24%   |
| Realtek Semiconductor        | 4         | 0.83%   |
| Focusrite-Novation           | 4         | 0.83%   |
| Texas Instruments            | 3         | 0.62%   |
| Generalplus Technology       | 3         | 0.62%   |
| VIA Technologies             | 2         | 0.41%   |
| SteelSeries ApS              | 2         | 0.41%   |
| SAVITECH                     | 2         | 0.41%   |
| Micro Star International     | 2         | 0.41%   |
| Hewlett-Packard              | 2         | 0.41%   |
| GN Netcom                    | 2         | 0.41%   |
| Creative Technology          | 2         | 0.41%   |
| Creative Labs                | 2         | 0.41%   |
| Corsair                      | 2         | 0.41%   |
| Trust                        | 1         | 0.21%   |
| TEAC                         | 1         | 0.21%   |
| Nordic Semiconductor ASA     | 1         | 0.21%   |
| Mackie Designs               | 1         | 0.21%   |
| M-Audio                      | 1         | 0.21%   |
| Lenovo                       | 1         | 0.21%   |
| JMTek                        | 1         | 0.21%   |
| DSEA A/S                     | 1         | 0.21%   |
| Dell                         | 1         | 0.21%   |
| D&M Holdings (Denon/Marantz) | 1         | 0.21%   |
| CMX Systems                  | 1         | 0.21%   |
| AudioQuest                   | 1         | 0.21%   |
| ASUSTek Computer             | 1         | 0.21%   |
| Asahi Kasei Microsystems     | 1         | 0.21%   |
| 2.4G Composite Device        | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 68        | 11.51%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 35        | 5.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21        | 3.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 3.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 16        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.37%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 14        | 2.37%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 2.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13        | 2.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 1.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 1.86%   |
| Intel 200 Series PCH HD Audio                                              | 10        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.52%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 1.35%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 1.35%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 1.18%   |
| Nvidia GA106 High Definition Audio Controller                              | 7         | 1.18%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.02%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 1.02%   |
| Intel Jasper Lake HD Audio                                                 | 6         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 0.85%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5         | 0.85%   |
| AMD FCH Azalia Controller                                                  | 5         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                         | 4         | 0.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.68%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.68%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 48        | 23.53%  |
| Micron Technology   | 34        | 16.67%  |
| SK hynix            | 29        | 14.22%  |
| Kingston            | 23        | 11.27%  |
| Crucial             | 13        | 6.37%   |
| Corsair             | 12        | 5.88%   |
| G.Skill             | 10        | 4.9%    |
| Unknown             | 5         | 2.45%   |
| Ramaxel Technology  | 5         | 2.45%   |
| A-DATA Technology   | 5         | 2.45%   |
| Unknown             | 4         | 1.96%   |
| Unknown (ABCD)      | 3         | 1.47%   |
| Patriot             | 3         | 1.47%   |
| Team                | 2         | 0.98%   |
| Transcend           | 1         | 0.49%   |
| Timetec             | 1         | 0.49%   |
| Nanya Technology    | 1         | 0.49%   |
| Micron/Elpida       | 1         | 0.49%   |
| GOODRAM             | 1         | 0.49%   |
| fef5                | 1         | 0.49%   |
| Atermiter           | 1         | 0.49%   |
| 4ea5                | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 4         | 1.87%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.4%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 2         | 0.93%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.93%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.93%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 2         | 0.93%   |
| Patriot RAM 3200 C16 Series 4GB DIMM DDR4 3600MT/s               | 2         | 0.93%   |
| Micron RAM MT53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s  | 2         | 0.93%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.93%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.93%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.93%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s              | 2         | 0.93%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s            | 2         | 0.93%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2         | 0.93%   |
| Unknown RAM Module 8GB DIMM 667MT/s                              | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM 800MT/s                            | 1         | 0.47%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 0.47%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 0.47%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 0.47%   |
| Timetec RAM S16G-3200 16GB SODIMM DDR4 3200MT/s                  | 1         | 0.47%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 0.47%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s               | 1         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.47%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.47%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.47%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s           | 1         | 0.47%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s            | 1         | 0.47%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 1         | 0.47%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 91        | 50.28%  |
| DDR3    | 34        | 18.78%  |
| LPDDR4  | 21        | 11.6%   |
| DDR5    | 14        | 7.73%   |
| LPDDR5  | 13        | 7.18%   |
| LPDDR3  | 4         | 2.21%   |
| Unknown | 3         | 1.66%   |
| SDRAM   | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 43.41%  |
| DIMM         | 61        | 33.52%  |
| Row Of Chips | 39        | 21.43%  |
| Unknown      | 3         | 1.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 80        | 41.24%  |
| 4096  | 51        | 26.29%  |
| 16384 | 39        | 20.1%   |
| 2048  | 11        | 5.67%   |
| 32768 | 10        | 5.15%   |
| 12288 | 2         | 1.03%   |
| 1024  | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 46        | 23.96%  |
| 2400    | 19        | 9.9%    |
| 2667    | 17        | 8.85%   |
| 1600    | 16        | 8.33%   |
| 4267    | 14        | 7.29%   |
| 6400    | 12        | 6.25%   |
| 1333    | 9         | 4.69%   |
| 3600    | 8         | 4.17%   |
| 4800    | 7         | 3.65%   |
| 2133    | 6         | 3.13%   |
| 1800    | 4         | 2.08%   |
| 6000    | 3         | 1.56%   |
| 3800    | 3         | 1.56%   |
| 5600    | 2         | 1.04%   |
| 3733    | 2         | 1.04%   |
| 3266    | 2         | 1.04%   |
| 2933    | 2         | 1.04%   |
| 2666    | 2         | 1.04%   |
| 1867    | 2         | 1.04%   |
| 1334    | 2         | 1.04%   |
| 12800   | 1         | 0.52%   |
| 8400    | 1         | 0.52%   |
| 7500    | 1         | 0.52%   |
| 4266    | 1         | 0.52%   |
| 3666    | 1         | 0.52%   |
| 3400    | 1         | 0.52%   |
| 3334    | 1         | 0.52%   |
| 3066    | 1         | 0.52%   |
| 2473    | 1         | 0.52%   |
| 1866    | 1         | 0.52%   |
| 1067    | 1         | 0.52%   |
| 800     | 1         | 0.52%   |
| 667     | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 25%     |
| Canon              | 2         | 25%     |
| Brother Industries | 2         | 25%     |
| Pantum             | 1         | 12.5%   |
| Hewlett-Packard    | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-7100 Series | 1         | 12.5%   |
| Seiko Epson XP-2200 Series | 1         | 12.5%   |
| Pantum P2200W series       | 1         | 12.5%   |
| HP LaserJet P1006          | 1         | 12.5%   |
| Canon PIXMA MX490 Series   | 1         | 12.5%   |
| Canon CAPT USB Device      | 1         | 12.5%   |
| Brother HL-L2310D series   | 1         | 12.5%   |
| Brother HL-3142CW series   | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 17%     |
| Microdia                               | 18        | 9%      |
| IMC Networks                           | 16        | 8%      |
| Realtek Semiconductor                  | 14        | 7%      |
| Quanta                                 | 14        | 7%      |
| Sunplus Innovation Technology          | 11        | 5.5%    |
| Apple                                  | 11        | 5.5%    |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5%      |
| Syntek                                 | 9         | 4.5%    |
| Logitech                               | 9         | 4.5%    |
| Bison Electronics                      | 9         | 4.5%    |
| Luxvisions Innotech Limited            | 7         | 3.5%    |
| Acer                                   | 5         | 2.5%    |
| Lite-On Technology                     | 4         | 2%      |
| SunplusIT                              | 2         | 1%      |
| Shenzhen Kingcome Optoelectronic       | 2         | 1%      |
| Samsung Electronics                    | 2         | 1%      |
| icSpring                               | 2         | 1%      |
| Alcor Micro                            | 2         | 1%      |
| Trust                                  | 1         | 0.5%    |
| Suyin                                  | 1         | 0.5%    |
| Sonix Technology                       | 1         | 0.5%    |
| SN0002                                 | 1         | 0.5%    |
| Silicon Motion                         | 1         | 0.5%    |
| ShineTech                              | 1         | 0.5%    |
| Ricoh                                  | 1         | 0.5%    |
| Primax Electronics                     | 1         | 0.5%    |
| OYT Tech                               | 1         | 0.5%    |
| OPPO Electronics                       | 1         | 0.5%    |
| Microsoft                              | 1         | 0.5%    |
| MacroSilicon                           | 1         | 0.5%    |
| Lenovo                                 | 1         | 0.5%    |
| Jieli Technology                       | 1         | 0.5%    |
| Generalplus Technology                 | 1         | 0.5%    |
| GEMBIRD                                | 1         | 0.5%    |
| AVerMedia Technologies                 | 1         | 0.5%    |
| Anker PowerConf C200                   | 1         | 0.5%    |
| A4Tech                                 | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 4.43%   |
| Chicony Integrated Camera                                                  | 9         | 4.43%   |
| Syntek Integrated Camera                                                   | 8         | 3.94%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.97%   |
| Realtek HP Truevision HD                                                   | 4         | 1.97%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.97%   |
| Apple FaceTime HD Camera                                                   | 4         | 1.97%   |
| Quanta USB2.0 HD UVC WebCam                                                | 3         | 1.48%   |
| Quanta HD User Facing                                                      | 3         | 1.48%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 1.48%   |
| Bison Integrated Camera                                                    | 3         | 1.48%   |
| Bison HD Webcam                                                            | 3         | 1.48%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                         | 3         | 1.48%   |
| Apple Built-in iSight                                                      | 3         | 1.48%   |
| Sunplus XiaoMi USB 2.0 Webcam                                              | 2         | 0.99%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                            | 2         | 0.99%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.99%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 0.99%   |
| Microdia Webcam Vitade AF                                                  | 2         | 0.99%   |
| Microdia Camera                                                            | 2         | 0.99%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 2         | 0.99%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 0.99%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 0.99%   |
| Logitech HD Webcam C615                                                    | 2         | 0.99%   |
| Logitech HD Pro Webcam C920                                                | 2         | 0.99%   |
| Lite-On HP HD Webcam                                                       | 2         | 0.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 0.99%   |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 0.99%   |
| icSpring camera                                                            | 2         | 0.99%   |
| Chicony HP TrueVision HD                                                   | 2         | 0.99%   |
| Chicony HD WebCam                                                          | 2         | 0.99%   |
| Chicony 720p HD Camera                                                     | 2         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 2         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 2         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 0.99%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 0.99%   |
| Alcor Micro USB 2.0 Camera                                                 | 2         | 0.99%   |
| Acer Integrated RGB Camera                                                 | 2         | 0.99%   |
| Acer Integrated Camera                                                     | 2         | 0.99%   |
| Trust Trust Full HD Webcam                                                 | 1         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 18        | 45%     |
| Validity Sensors                   | 11        | 27.5%   |
| Shenzhen Goodix Technology         | 7         | 17.5%   |
| Samsung Electronics                | 1         | 2.5%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.5%    |
| Elan Microelectronics              | 1         | 2.5%    |
| AuthenTec                          | 1         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 15%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 10%     |
| Synaptics Prometheus Fingerprint Reader                         | 4         | 10%     |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 4         | 10%     |
| Shenzhen Goodix  Fingerprint Device                             | 4         | 10%     |
| Validity Sensors Swipe Fingerprint Sensor                       | 3         | 7.5%    |
| Synaptics UWP WBDI                                              | 3         | 7.5%    |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 7.5%    |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 2.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 2.5%    |
| Synaptics WBDI                                                  | 1         | 2.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 2.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 2.5%    |
| Samsung Fingerprint Sensor Device - 730B                        | 1         | 2.5%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.5%    |
| Elan ELAN:ARM-M4                                                | 1         | 2.5%    |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 2.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 50%     |
| Alcor Micro           | 2         | 16.67%  |
| O2 Micro              | 1         | 8.33%   |
| Lenovo                | 1         | 8.33%   |
| Aladdin R.D.          | 1         | 8.33%   |
| Advanced Card Systems | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 2         | 16.67%  |
| Broadcom 58200                                                               | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 8.33%   |
| Aladdin R.D. JaCarta                                                         | 1         | 8.33%   |
| Advanced Card Systems ACR1252 CL Reader PICC                                 | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 223       | 68.83%  |
| 1     | 87        | 26.85%  |
| 2     | 13        | 4.01%   |
| 3     | 1         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 40        | 35.4%   |
| Net/wireless             | 14        | 12.39%  |
| Multimedia controller    | 14        | 12.39%  |
| Graphics card            | 14        | 12.39%  |
| Chipcard                 | 10        | 8.85%   |
| Camera                   | 8         | 7.08%   |
| Sound                    | 3         | 2.65%   |
| Unassigned class         | 2         | 1.77%   |
| Communication controller | 2         | 1.77%   |
| Bluetooth                | 2         | 1.77%   |
| Storage/raid             | 1         | 0.88%   |
| Storage                  | 1         | 0.88%   |
| Net/ethernet             | 1         | 0.88%   |
| Card reader              | 1         | 0.88%   |

