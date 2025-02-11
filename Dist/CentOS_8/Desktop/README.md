CentOS 8 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 259

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H81M-DS2                    | [5dc1de492f](https://linux-hardware.org/?probe=5dc1de492f) | Nov 27, 2024 |
| Gigabyte      | H77N-WIFI                   | [93b16c2f95](https://linux-hardware.org/?probe=93b16c2f95) | Nov 08, 2024 |
| Gigabyte      | X570 GAMING X               | [d8462744c6](https://linux-hardware.org/?probe=d8462744c6) | Sep 05, 2024 |
| Acer          | B360H5-M14 P21-A0           | [e66929de9b](https://linux-hardware.org/?probe=e66929de9b) | Jun 27, 2024 |
| Gigabyte      | H77N-WIFI                   | [3a99c46a79](https://linux-hardware.org/?probe=3a99c46a79) | Mar 30, 2024 |
| Gigabyte      | H77N-WIFI                   | [6c0119ee26](https://linux-hardware.org/?probe=6c0119ee26) | Feb 19, 2024 |
| AZW           | Green G4 10                 | [143e042311](https://linux-hardware.org/?probe=143e042311) | Feb 08, 2024 |
| Acer          | Aspire XC-830               | [21a3b6601a](https://linux-hardware.org/?probe=21a3b6601a) | Oct 10, 2023 |
| Acer          | Aspire XC-830               | [c7453db83a](https://linux-hardware.org/?probe=c7453db83a) | Oct 10, 2023 |
| Dell          | 088DT1 A00                  | [4e85b8e145](https://linux-hardware.org/?probe=4e85b8e145) | Oct 03, 2023 |
| ASUSTek       | AT4NM10T-I                  | [a650338ead](https://linux-hardware.org/?probe=a650338ead) | Aug 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | [8ff38f3782](https://linux-hardware.org/?probe=8ff38f3782) | Jul 18, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | [a7bcb95d10](https://linux-hardware.org/?probe=a7bcb95d10) | Jun 30, 2023 |
| Gigabyte      | H77N-WIFI                   | [8dce973d6b](https://linux-hardware.org/?probe=8dce973d6b) | Jun 02, 2023 |
| MSI           | B460M PRO-VDH WIFI          | [8b0573684a](https://linux-hardware.org/?probe=8b0573684a) | Apr 12, 2023 |
| Dell          | 0MW50N A01                  | [dd68ce3b10](https://linux-hardware.org/?probe=dd68ce3b10) | Apr 11, 2023 |
| Gigabyte      | H77N-WIFI                   | [24b14fa9bb](https://linux-hardware.org/?probe=24b14fa9bb) | Mar 30, 2023 |
| Dell          | 0NDYHG A00                  | [f007ab3692](https://linux-hardware.org/?probe=f007ab3692) | Mar 20, 2023 |
| ASUSTek       | AT4NM10T-I                  | [ca09a29082](https://linux-hardware.org/?probe=ca09a29082) | Mar 01, 2023 |
| Gigabyte      | H77N-WIFI                   | [f1b85863bc](https://linux-hardware.org/?probe=f1b85863bc) | Feb 20, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [efecce0072](https://linux-hardware.org/?probe=efecce0072) | Nov 30, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [0149d91a8d](https://linux-hardware.org/?probe=0149d91a8d) | Nov 28, 2022 |
| HP            | 3397                        | [9cb876048a](https://linux-hardware.org/?probe=9cb876048a) | Nov 05, 2022 |
| ASUSTek       | Z87-A                       | [d57a581b09](https://linux-hardware.org/?probe=d57a581b09) | Sep 04, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6069a015bb](https://linux-hardware.org/?probe=6069a015bb) | Jul 03, 2022 |
| Dell          | 0HD5W2 A01                  | [924537ba87](https://linux-hardware.org/?probe=924537ba87) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Dell          | 0WN7Y6 A02                  | [3e2f6e6e1c](https://linux-hardware.org/?probe=3e2f6e6e1c) | Jun 22, 2022 |
| Unknown       | G41 Series                  | [d257436f52](https://linux-hardware.org/?probe=d257436f52) | Jun 17, 2022 |
| Gigabyte      | H77N-WIFI                   | [a989dee1a0](https://linux-hardware.org/?probe=a989dee1a0) | Jun 06, 2022 |
| ASUSTek       | AT4NM10T-I                  | [c70d152830](https://linux-hardware.org/?probe=c70d152830) | May 29, 2022 |
| Unknown       | G41 Series                  | [e9a273726a](https://linux-hardware.org/?probe=e9a273726a) | May 26, 2022 |
| Unknown       | G41 Series                  | [f0890bb556](https://linux-hardware.org/?probe=f0890bb556) | May 24, 2022 |
| Unknown       | G41 Series                  | [94dcbec5e7](https://linux-hardware.org/?probe=94dcbec5e7) | May 20, 2022 |
| Unknown       | G41 Series                  | [c6040e6638](https://linux-hardware.org/?probe=c6040e6638) | Apr 21, 2022 |
| Gigabyte      | H410M H V3                  | [5b5118db5d](https://linux-hardware.org/?probe=5b5118db5d) | Apr 06, 2022 |
| Unknown       | G41 Series                  | [4dbde5e06f](https://linux-hardware.org/?probe=4dbde5e06f) | Mar 28, 2022 |
| ASUSTek       | PRIME X570-PRO              | [beda807e51](https://linux-hardware.org/?probe=beda807e51) | Mar 20, 2022 |
| Daewoo Luc... | Solo Top                    | [6d961af923](https://linux-hardware.org/?probe=6d961af923) | Mar 03, 2022 |
| Intel         | X99                         | [9cc44f0705](https://linux-hardware.org/?probe=9cc44f0705) | Feb 26, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | [746ddfc621](https://linux-hardware.org/?probe=746ddfc621) | Feb 09, 2022 |
| ASUSTek       | F1A55-M LX PLUS             | [706b5f2fab](https://linux-hardware.org/?probe=706b5f2fab) | Jan 27, 2022 |
| Unknown       | G41 Series                  | [28502ce22e](https://linux-hardware.org/?probe=28502ce22e) | Jan 27, 2022 |
| ASUSTek       | PRIME X470-PRO              | [c7f152495b](https://linux-hardware.org/?probe=c7f152495b) | Jan 21, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [6d015ef040](https://linux-hardware.org/?probe=6d015ef040) | Jan 15, 2022 |
| Gigabyte      | H77N-WIFI                   | [010543afde](https://linux-hardware.org/?probe=010543afde) | Jan 13, 2022 |
| ASUSTek       | V-P7H55E                    | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| MSI           | Z270 GAMING PLUS            | [bd96b37321](https://linux-hardware.org/?probe=bd96b37321) | Jan 07, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [aad21a9d66](https://linux-hardware.org/?probe=aad21a9d66) | Dec 21, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [fe889c0a84](https://linux-hardware.org/?probe=fe889c0a84) | Dec 15, 2021 |
| Unknown       | G41 Series                  | [45a2524e2b](https://linux-hardware.org/?probe=45a2524e2b) | Dec 11, 2021 |
| Unknown       | G41 Series                  | [77c738bc15](https://linux-hardware.org/?probe=77c738bc15) | Dec 09, 2021 |
| Unknown       | G41 Series                  | [e9846d4aa5](https://linux-hardware.org/?probe=e9846d4aa5) | Dec 05, 2021 |
| ASRock        | X570 Steel Legend           | [e5e357405c](https://linux-hardware.org/?probe=e5e357405c) | Nov 29, 2021 |
| Dell          | 0KC9NP A01                  | [cdc7bbd885](https://linux-hardware.org/?probe=cdc7bbd885) | Nov 29, 2021 |
| ASUSTek       | P5QL PRO                    | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| Dell          | 0C2KJT A00                  | [b4fb255866](https://linux-hardware.org/?probe=b4fb255866) | Nov 23, 2021 |
| MSI           | A88X-G43                    | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| Dell          | 0R038D A00                  | [6b0833e390](https://linux-hardware.org/?probe=6b0833e390) | Nov 05, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [97ece593e1](https://linux-hardware.org/?probe=97ece593e1) | Nov 01, 2021 |
| Gigabyte      | 970-GAMING                  | [9a9b258736](https://linux-hardware.org/?probe=9a9b258736) | Oct 22, 2021 |
| ASUSTek       | KGPE-D16                    | [b5d2358b76](https://linux-hardware.org/?probe=b5d2358b76) | Oct 21, 2021 |
| Dell          | 0GTK4K A02                  | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| ASRock        | Z77 Extreme4                | [53b29edc51](https://linux-hardware.org/?probe=53b29edc51) | Oct 14, 2021 |
| ASRock        | Z77 Extreme4                | [0d69ee2560](https://linux-hardware.org/?probe=0d69ee2560) | Oct 10, 2021 |
| Gigabyte      | 970-GAMING                  | [9a4c250f63](https://linux-hardware.org/?probe=9a4c250f63) | Oct 06, 2021 |
| MSI           | FM2-A55M-E33                | [2ff5df695f](https://linux-hardware.org/?probe=2ff5df695f) | Oct 05, 2021 |
| MSI           | FM2-A55M-E33                | [f6ff6eebb3](https://linux-hardware.org/?probe=f6ff6eebb3) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | [21d49c2826](https://linux-hardware.org/?probe=21d49c2826) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | [cb940b924d](https://linux-hardware.org/?probe=cb940b924d) | Sep 30, 2021 |
| HP            | 0AACh                       | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| Unknown       | Unknown                     | [7baf2629b9](https://linux-hardware.org/?probe=7baf2629b9) | Sep 26, 2021 |
| ASRock        | Z77 Extreme4                | [b603b360a4](https://linux-hardware.org/?probe=b603b360a4) | Sep 25, 2021 |
| Dell          | 0FM586                      | [5ec44ec202](https://linux-hardware.org/?probe=5ec44ec202) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [976ca14e35](https://linux-hardware.org/?probe=976ca14e35) | Sep 19, 2021 |
| ASRock        | Z77 Extreme4                | [36129a77bf](https://linux-hardware.org/?probe=36129a77bf) | Sep 18, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [4720c56d37](https://linux-hardware.org/?probe=4720c56d37) | Sep 15, 2021 |
| HP            | 8750                        | [b5bbf3502f](https://linux-hardware.org/?probe=b5bbf3502f) | Sep 08, 2021 |
| ASRock        | Z77 Extreme4                | [5cda73f744](https://linux-hardware.org/?probe=5cda73f744) | Sep 05, 2021 |
| Intel         | DH55TC AAE70932-302         | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [5d701efa3e](https://linux-hardware.org/?probe=5d701efa3e) | Sep 03, 2021 |
| ASRock        | Z77 Extreme4                | [f754b0f478](https://linux-hardware.org/?probe=f754b0f478) | Sep 03, 2021 |
| MSI           | MAG B550M MORTAR            | [5ae94fc78a](https://linux-hardware.org/?probe=5ae94fc78a) | Aug 28, 2021 |
| Supermicro    | X8SAX                       | [3795e4ab95](https://linux-hardware.org/?probe=3795e4ab95) | Aug 28, 2021 |
| Gigabyte      | H97N-WIFI                   | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| Gigabyte      | Z170MX-Gaming 5             | [461d550db6](https://linux-hardware.org/?probe=461d550db6) | Aug 19, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | 2B3C                        | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [3501d4479e](https://linux-hardware.org/?probe=3501d4479e) | Aug 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [0cecab8e81](https://linux-hardware.org/?probe=0cecab8e81) | Aug 11, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [92336b575c](https://linux-hardware.org/?probe=92336b575c) | Aug 10, 2021 |
| HP            | 0AECh D                     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Gigabyte      | H57M-USB3                   | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| MSI           | MAG B550M MORTAR            | [59a63323ed](https://linux-hardware.org/?probe=59a63323ed) | Jul 23, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [ec0e7ce341](https://linux-hardware.org/?probe=ec0e7ce341) | Jul 19, 2021 |
| MSI           | B460M-A PRO                 | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| MSI           | MAG B550M MORTAR            | [4ac62bb08e](https://linux-hardware.org/?probe=4ac62bb08e) | Jul 13, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [f4606d038d](https://linux-hardware.org/?probe=f4606d038d) | Jun 29, 2021 |
| ASRock        | A320M-HD                    | [e09e4e329c](https://linux-hardware.org/?probe=e09e4e329c) | Jun 14, 2021 |
| Dell          | 0M5DCD A00                  | [00ce09b473](https://linux-hardware.org/?probe=00ce09b473) | May 31, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [de14f99534](https://linux-hardware.org/?probe=de14f99534) | May 24, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | [8ecaed3eb2](https://linux-hardware.org/?probe=8ecaed3eb2) | May 24, 2021 |
| Dell          | 0200DY A02                  | [340184fb36](https://linux-hardware.org/?probe=340184fb36) | May 23, 2021 |
| HP            | 18E7                        | [3045530e64](https://linux-hardware.org/?probe=3045530e64) | May 17, 2021 |
| MSI           | MAG B550M MORTAR            | [640c5adfc3](https://linux-hardware.org/?probe=640c5adfc3) | May 10, 2021 |
| ASUSTek       | PRIME X570-PRO              | [88b8ca6dbe](https://linux-hardware.org/?probe=88b8ca6dbe) | Apr 30, 2021 |
| ASUSTek       | PRIME X570-PRO              | [be1a846088](https://linux-hardware.org/?probe=be1a846088) | Apr 30, 2021 |
| ASUSTek       | Z97-E/USB                   | [8524f8f381](https://linux-hardware.org/?probe=8524f8f381) | Apr 16, 2021 |
| ASRock        | X570 Steel Legend           | [f8b36f6373](https://linux-hardware.org/?probe=f8b36f6373) | Mar 29, 2021 |
| Gigabyte      | Z490 GAMING X               | [f37546f14b](https://linux-hardware.org/?probe=f37546f14b) | Mar 26, 2021 |
| Dell          | 0XHGV1 A00                  | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Lenovo        | MAHOBAY                     | [3bce30311a](https://linux-hardware.org/?probe=3bce30311a) | Mar 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [c46179b0b2](https://linux-hardware.org/?probe=c46179b0b2) | Mar 22, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | [0473f156a3](https://linux-hardware.org/?probe=0473f156a3) | Mar 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | [ccdc5f822c](https://linux-hardware.org/?probe=ccdc5f822c) | Mar 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9fdca2136a](https://linux-hardware.org/?probe=9fdca2136a) | Mar 19, 2021 |
| Dell          | 0NC2VH A01                  | [cc8791aaa6](https://linux-hardware.org/?probe=cc8791aaa6) | Mar 17, 2021 |
| ASUSTek       | PRIME A320M-R               | [adac87af3d](https://linux-hardware.org/?probe=adac87af3d) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [0190551f1e](https://linux-hardware.org/?probe=0190551f1e) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [1184f695c1](https://linux-hardware.org/?probe=1184f695c1) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | [b5658ed87e](https://linux-hardware.org/?probe=b5658ed87e) | Mar 12, 2021 |
| Gigabyte      | B75M-D3H                    | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1314989a9a](https://linux-hardware.org/?probe=1314989a9a) | Feb 21, 2021 |
| Dell          | 0WR7PY A01                  | [ad06439414](https://linux-hardware.org/?probe=ad06439414) | Feb 19, 2021 |
| Supermicro    | X9SCI/X9SCA                 | [28940aaa42](https://linux-hardware.org/?probe=28940aaa42) | Feb 16, 2021 |
| Dell          | 07T4MC A06                  | [ae053aa0ed](https://linux-hardware.org/?probe=ae053aa0ed) | Feb 15, 2021 |
| ASUSTek       | Z97-E/USB                   | [0cf9401181](https://linux-hardware.org/?probe=0cf9401181) | Feb 12, 2021 |
| Gigabyte      | MZBSWMP-00                  | [754ea78372](https://linux-hardware.org/?probe=754ea78372) | Feb 09, 2021 |
| Gigabyte      | MZBSWMP-00                  | [5e6e46d3b1](https://linux-hardware.org/?probe=5e6e46d3b1) | Feb 09, 2021 |
| Gigabyte      | H77N-WIFI                   | [8469853bc1](https://linux-hardware.org/?probe=8469853bc1) | Feb 08, 2021 |
| Gigabyte      | H77N-WIFI                   | [7b44703f86](https://linux-hardware.org/?probe=7b44703f86) | Feb 08, 2021 |
| ASRock        | X570 Steel Legend           | [59145ca9e6](https://linux-hardware.org/?probe=59145ca9e6) | Jan 24, 2021 |
| ASUSTek       | GD30CI                      | [201c54f6b8](https://linux-hardware.org/?probe=201c54f6b8) | Jan 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [d798d76c9a](https://linux-hardware.org/?probe=d798d76c9a) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [6de78c3913](https://linux-hardware.org/?probe=6de78c3913) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | [e2cd4bfc82](https://linux-hardware.org/?probe=e2cd4bfc82) | Jan 11, 2021 |
| MSI           | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| ASUSTek       | GD30CI                      | [4f2d51ec4b](https://linux-hardware.org/?probe=4f2d51ec4b) | Jan 09, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | 806A                        | [f02a4a5e93](https://linux-hardware.org/?probe=f02a4a5e93) | Jan 05, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ac785c27e5](https://linux-hardware.org/?probe=ac785c27e5) | Dec 27, 2020 |
| Dell          | 0VD5HY A00                  | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| ASRock        | X570 Steel Legend           | [c96512d726](https://linux-hardware.org/?probe=c96512d726) | Dec 25, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [2b7bb243da](https://linux-hardware.org/?probe=2b7bb243da) | Dec 23, 2020 |
| Gigabyte      | Z370 AORUS Gaming WIFI-C... | [5438d83866](https://linux-hardware.org/?probe=5438d83866) | Dec 14, 2020 |
| ASUSTek       | Z170-A                      | [b4e9865791](https://linux-hardware.org/?probe=b4e9865791) | Nov 25, 2020 |
| ASUSTek       | H87M-PLUS                   | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| ASRock        | Z390M-ITX/ac                | [3d5c6b679d](https://linux-hardware.org/?probe=3d5c6b679d) | Nov 22, 2020 |
| ASRock        | Z390M-ITX/ac                | [b3f3cd1511](https://linux-hardware.org/?probe=b3f3cd1511) | Nov 22, 2020 |
| HP            | 81C9                        | [ea900ff5b1](https://linux-hardware.org/?probe=ea900ff5b1) | Nov 19, 2020 |
| ASUSTek       | PRIME X370-PRO              | [70fc4e5649](https://linux-hardware.org/?probe=70fc4e5649) | Nov 16, 2020 |
| HP            | 1587h                       | [4b1f2221ee](https://linux-hardware.org/?probe=4b1f2221ee) | Nov 16, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | 1495                        | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| HP            | 1495                        | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| Supermicro    | X8SIL                       | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| Supermicro    | X8SIL                       | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [1741a29fd6](https://linux-hardware.org/?probe=1741a29fd6) | Nov 01, 2020 |
| ASRock        | G31M-S                      | [e579695cc9](https://linux-hardware.org/?probe=e579695cc9) | Nov 01, 2020 |
| ASUSTek       | PRIME X570-P                | [4e9d94747a](https://linux-hardware.org/?probe=4e9d94747a) | Oct 30, 2020 |
| Supermicro    | X8SIL                       | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro    | X8SIL                       | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| MSI           | A320M PRO-VD/S V2           | [56d1218104](https://linux-hardware.org/?probe=56d1218104) | Oct 25, 2020 |
| ASUSTek       | Z170-A                      | [e5b6274c3e](https://linux-hardware.org/?probe=e5b6274c3e) | Oct 22, 2020 |
| ASUSTek       | P9X79                       | [e0a6bc45ee](https://linux-hardware.org/?probe=e0a6bc45ee) | Oct 17, 2020 |
| ASUSTek       | P9X79                       | [d14403a73b](https://linux-hardware.org/?probe=d14403a73b) | Oct 17, 2020 |
| HP            | 1495                        | [a678a5caf0](https://linux-hardware.org/?probe=a678a5caf0) | Oct 13, 2020 |
| ASRock        | X99 Taichi                  | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| MSI           | B450I GAMING PLUS AC        | [ff2176937d](https://linux-hardware.org/?probe=ff2176937d) | Oct 03, 2020 |
| ASUSTek       | Berkeley                    | [8ead41d349](https://linux-hardware.org/?probe=8ead41d349) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [29fdcb6b00](https://linux-hardware.org/?probe=29fdcb6b00) | Sep 28, 2020 |
| Gigabyte      | A320M-S2H-CF                | [bcf59e135b](https://linux-hardware.org/?probe=bcf59e135b) | Sep 19, 2020 |
| Gigabyte      | A320M-S2H-CF                | [43d38ed1be](https://linux-hardware.org/?probe=43d38ed1be) | Sep 19, 2020 |
| HP            | 8053                        | [b00f600647](https://linux-hardware.org/?probe=b00f600647) | Sep 09, 2020 |
| Intel         | D54250WYK H13922-303        | [219e110c70](https://linux-hardware.org/?probe=219e110c70) | Sep 03, 2020 |
| HP            | 0B54h D                     | [b39f47faf8](https://linux-hardware.org/?probe=b39f47faf8) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | [81f3fe5ce0](https://linux-hardware.org/?probe=81f3fe5ce0) | Aug 26, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [1c28fb67ab](https://linux-hardware.org/?probe=1c28fb67ab) | Aug 20, 2020 |
| ASUSTek       | Z97-E/USB                   | [2377cf4d5e](https://linux-hardware.org/?probe=2377cf4d5e) | Aug 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [eeaeff9e52](https://linux-hardware.org/?probe=eeaeff9e52) | Aug 12, 2020 |
| MSI           | B350M PRO-VDH               | [301fe36ff7](https://linux-hardware.org/?probe=301fe36ff7) | Aug 06, 2020 |
| Gigabyte      | A320M-S2H-CF                | [cbcae43afd](https://linux-hardware.org/?probe=cbcae43afd) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [d9b3b9a12e](https://linux-hardware.org/?probe=d9b3b9a12e) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | [3a33cfc73c](https://linux-hardware.org/?probe=3a33cfc73c) | Aug 02, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Gigabyte      | A320M-S2H-CF                | [08325f77c1](https://linux-hardware.org/?probe=08325f77c1) | Aug 01, 2020 |
| Gigabyte      | H97-HD3                     | [06c68b698e](https://linux-hardware.org/?probe=06c68b698e) | Jul 24, 2020 |
| ASUSTek       | Z97-E/USB                   | [f6f4d985ea](https://linux-hardware.org/?probe=f6f4d985ea) | Jul 13, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [2244646450](https://linux-hardware.org/?probe=2244646450) | Jul 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [80c07a542a](https://linux-hardware.org/?probe=80c07a542a) | Jul 11, 2020 |
| Dell          | 0YXT71 A02                  | [0d249e4d90](https://linux-hardware.org/?probe=0d249e4d90) | Jul 08, 2020 |
| ASRockRack    | EP2C612 WS                  | [4392ed1437](https://linux-hardware.org/?probe=4392ed1437) | Jul 08, 2020 |
| Dell          | 073MMW A00                  | [115d71c055](https://linux-hardware.org/?probe=115d71c055) | Jul 06, 2020 |
| Gigabyte      | EP45-DS3R                   | [cfad3da667](https://linux-hardware.org/?probe=cfad3da667) | Jul 03, 2020 |
| Unknown       | IPM31-AK                    | [acd334c9b0](https://linux-hardware.org/?probe=acd334c9b0) | Jun 28, 2020 |
| ASUSTek       | P8Z77-V                     | [f94256b581](https://linux-hardware.org/?probe=f94256b581) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [f9990a3c91](https://linux-hardware.org/?probe=f9990a3c91) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [6d4908178c](https://linux-hardware.org/?probe=6d4908178c) | Jun 22, 2020 |
| ASRock        | Z170 Extreme7+              | [56fa210d0c](https://linux-hardware.org/?probe=56fa210d0c) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | [b2d975c2e7](https://linux-hardware.org/?probe=b2d975c2e7) | Jun 20, 2020 |
| MSI           | 2A9C                        | [9af3bb0a4e](https://linux-hardware.org/?probe=9af3bb0a4e) | Jun 17, 2020 |
| Packard Be... | MCP73VT-PM                  | [8cba2e7fa8](https://linux-hardware.org/?probe=8cba2e7fa8) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | [26f700fbc5](https://linux-hardware.org/?probe=26f700fbc5) | Jun 14, 2020 |
| ASRock        | X399 Professional Gaming    | [d313005743](https://linux-hardware.org/?probe=d313005743) | Jun 10, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9020f6e51c](https://linux-hardware.org/?probe=9020f6e51c) | Jun 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [edbd2a746d](https://linux-hardware.org/?probe=edbd2a746d) | Jun 06, 2020 |
| Intel         | DP45SG AAE27733-405         | [f195015cf8](https://linux-hardware.org/?probe=f195015cf8) | Jun 02, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d4cbe90b0f](https://linux-hardware.org/?probe=d4cbe90b0f) | May 27, 2020 |
| Dell          | 0YXT71 A02                  | [e3f86df812](https://linux-hardware.org/?probe=e3f86df812) | May 25, 2020 |
| Supermicro    | X10DAI                      | [c2d45e8975](https://linux-hardware.org/?probe=c2d45e8975) | May 21, 2020 |
| Gigabyte      | Z68P-DS3                    | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [3f253aecbb](https://linux-hardware.org/?probe=3f253aecbb) | May 15, 2020 |
| Lenovo        | MAHOBAY                     | [3ad583ff3d](https://linux-hardware.org/?probe=3ad583ff3d) | May 14, 2020 |
| Foxconn       | 17A0                        | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Biostar       | A320MH                      | [bc6b5804c2](https://linux-hardware.org/?probe=bc6b5804c2) | Apr 24, 2020 |
| Foxconn       | 2A8C                        | [64941f8ea2](https://linux-hardware.org/?probe=64941f8ea2) | Apr 21, 2020 |
| ASRockRack    | EP2C612 WS                  | [22419b4efe](https://linux-hardware.org/?probe=22419b4efe) | Apr 20, 2020 |
| Dell          | 0C3YXR A01                  | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [cfed23f08f](https://linux-hardware.org/?probe=cfed23f08f) | Apr 18, 2020 |
| Dell          | 0YXT71 A02                  | [f454033e1f](https://linux-hardware.org/?probe=f454033e1f) | Apr 13, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | [17ba5a84d9](https://linux-hardware.org/?probe=17ba5a84d9) | Apr 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c670b78e38](https://linux-hardware.org/?probe=c670b78e38) | Apr 11, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [5d17d05d00](https://linux-hardware.org/?probe=5d17d05d00) | Apr 11, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | [95a4ea12d4](https://linux-hardware.org/?probe=95a4ea12d4) | Apr 05, 2020 |
| Unknown       | LakePort                    | [85bfbe1e35](https://linux-hardware.org/?probe=85bfbe1e35) | Apr 02, 2020 |
| HP            | 843F                        | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| Dell          | 040DDP A01                  | [1e1a7753ca](https://linux-hardware.org/?probe=1e1a7753ca) | Mar 10, 2020 |
| Gigabyte      | EX58-EXTREME                | [29d31a8603](https://linux-hardware.org/?probe=29d31a8603) | Mar 08, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [54d3d863ad](https://linux-hardware.org/?probe=54d3d863ad) | Feb 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [72895d5cc3](https://linux-hardware.org/?probe=72895d5cc3) | Feb 23, 2020 |
| Gigabyte      | EX58-EXTREME                | [2ce62d5ef2](https://linux-hardware.org/?probe=2ce62d5ef2) | Feb 23, 2020 |
| Supermicro    | X10DAI                      | [8bb87102a9](https://linux-hardware.org/?probe=8bb87102a9) | Feb 20, 2020 |
| ASUSTek       | H87M-PLUS                   | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| Gigabyte      | Z77X-UD5H                   | [2c5e967e3a](https://linux-hardware.org/?probe=2c5e967e3a) | Jan 25, 2020 |
| MSI           | H77MA-G43                   | [5a0c6d2f14](https://linux-hardware.org/?probe=5a0c6d2f14) | Jan 24, 2020 |
| Gigabyte      | Z77N-WIFI                   | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Foxconn       | 2AA9                        | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn       | 2AA9                        | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [3c407e606c](https://linux-hardware.org/?probe=3c407e606c) | Dec 31, 2019 |
| Gigabyte      | EP45-DS4                    | [13acec4985](https://linux-hardware.org/?probe=13acec4985) | Dec 25, 2019 |
| MSI           | H55M-E33                    | [48d4121155](https://linux-hardware.org/?probe=48d4121155) | Dec 10, 2019 |
| ASRock        | X79 Extreme11               | [1b28cc994f](https://linux-hardware.org/?probe=1b28cc994f) | Dec 07, 2019 |
| Dell          | 0PC5F7 A01                  | [ba442e31fa](https://linux-hardware.org/?probe=ba442e31fa) | Nov 24, 2019 |
| ASUSTek       | Benicia                     | [5d4f2621ec](https://linux-hardware.org/?probe=5d4f2621ec) | Nov 22, 2019 |
| Dell          | 0XR1GT A00                  | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| HP            | ProLiant MicroServer        | [fdfa4ab709](https://linux-hardware.org/?probe=fdfa4ab709) | Nov 14, 2019 |
| Dell          | 07T4MC A06                  | [8fba67a719](https://linux-hardware.org/?probe=8fba67a719) | Nov 14, 2019 |
| Lenovo        | MAHOBAY                     | [652157e27c](https://linux-hardware.org/?probe=652157e27c) | Nov 03, 2019 |
| Lenovo        | MAHOBAY                     | [fd672567d1](https://linux-hardware.org/?probe=fd672567d1) | Nov 03, 2019 |
| ASUSTek       | Benicia                     | [764ecc00c4](https://linux-hardware.org/?probe=764ecc00c4) | Oct 30, 2019 |
| ASUSTek       | Benicia                     | [c604466168](https://linux-hardware.org/?probe=c604466168) | Oct 26, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [17d03076df](https://linux-hardware.org/?probe=17d03076df) | Oct 16, 2019 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [11a89e3f6f](https://linux-hardware.org/?probe=11a89e3f6f) | Oct 13, 2019 |
| Gigabyte      | X58A-UD5                    | [c1cd5017a5](https://linux-hardware.org/?probe=c1cd5017a5) | Oct 05, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64  | 13       | 6.91%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 12       | 6.38%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 12       | 6.38%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 9        | 4.79%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 9        | 4.79%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 9        | 4.79%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 9        | 4.79%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 7        | 3.72%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7        | 3.72%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 6        | 3.19%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 6        | 3.19%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 6        | 3.19%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 6        | 3.19%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 5        | 2.66%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 4        | 2.13%   |
| 4.18.0-301.1.el8.x86_64      | 4        | 2.13%   |
| 4.18.0-147.el8.x86_64        | 4        | 2.13%   |
| 4.18.0-358.el8.x86_64        | 3        | 1.6%    |
| 4.18.0-348.el8.x86_64        | 3        | 1.6%    |
| 4.18.0-80.el8.x86_64         | 2        | 1.06%   |
| 4.18.0-394.el8.x86_64        | 2        | 1.06%   |
| 4.18.0-383.el8.x86_64        | 2        | 1.06%   |
| 4.18.0-338.el8.x86_64        | 2        | 1.06%   |
| 4.18.0-315.el8.x86_64        | 2        | 1.06%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 2        | 1.06%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 1.06%   |
| 4.18.0-305.0.1.el8.x86_64    | 2        | 1.06%   |
| 4.18.0-294.el8.x86_64        | 2        | 1.06%   |
| 4.18.0-277.el8.x86_64        | 2        | 1.06%   |
| 4.18.0-240.el8.x86_64        | 2        | 1.06%   |
| 4.18.0-193.10.el8.x86_64     | 2        | 1.06%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 2        | 1.06%   |
| 5.18.0-1.el8.elrepo.x86_64   | 1        | 0.53%   |
| 5.13.11-1.el8.elrepo.x86_64  | 1        | 0.53%   |
| 5.10.3-1.el8.elrepo.x86_64   | 1        | 0.53%   |
| 5.10.10                      | 1        | 0.53%   |
| 4.18.0-80.7.1.el8_0.x86_64   | 1        | 0.53%   |
| 4.18.0-552.3.1.el8.x86_64    | 1        | 0.53%   |
| 4.18.0-536.el8.x86_64        | 1        | 0.53%   |
| 4.18.0-514.el8.x86_64        | 1        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 158      | 96.93%  |
| 5.18.0  | 1        | 0.61%   |
| 5.13.11 | 1        | 0.61%   |
| 5.10.3  | 1        | 0.61%   |
| 5.10.10 | 1        | 0.61%   |
| 3.10.0  | 1        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 158      | 96.93%  |
| 5.10    | 2        | 1.23%   |
| 5.18    | 1        | 0.61%   |
| 5.13    | 1        | 0.61%   |
| 3.10    | 1        | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 162      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 119      | 71.69%  |
| Unknown       | 22       | 13.25%  |
| GNOME Classic | 11       | 6.63%   |
| XFCE          | 8        | 4.82%   |
| KDE5          | 4        | 2.41%   |
| X-Cinnamon    | 1        | 0.6%    |
| MATE          | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 79       | 46.47%  |
| X11     | 67       | 39.41%  |
| Unknown | 22       | 12.94%  |
| Web     | 2        | 1.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 106      | 65.03%  |
| GDM     | 53       | 32.52%  |
| LightDM | 3        | 1.84%   |
| SDDM    | 1        | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 91       | 54.82%  |
| Unknown     | 13       | 7.83%   |
| en_GB       | 10       | 6.02%   |
| de_DE       | 10       | 6.02%   |
| pl_PL       | 6        | 3.61%   |
| ru_RU       | 4        | 2.41%   |
| pt_BR       | 4        | 2.41%   |
| fr_FR       | 3        | 1.81%   |
| en_IN       | 3        | 1.81%   |
| en_CA       | 3        | 1.81%   |
| hu_HU       | 2        | 1.2%    |
| es_PE       | 2        | 1.2%    |
| en_AU       | 2        | 1.2%    |
| uk_UA       | 1        | 0.6%    |
| tr_TR       | 1        | 0.6%    |
| sl_SI       | 1        | 0.6%    |
| ko_KR       | 1        | 0.6%    |
| it_IT       | 1        | 0.6%    |
| fr_CA       | 1        | 0.6%    |
| fi_FI       | 1        | 0.6%    |
| es_US       | 1        | 0.6%    |
| en_US.utf-8 | 1        | 0.6%    |
| de_LU       | 1        | 0.6%    |
| de_CH       | 1        | 0.6%    |
| cs_CZ       | 1        | 0.6%    |
| C           | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 84       | 51.53%  |
| EFI  | 79       | 48.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Xfs     | 141      | 86.5%   |
| Ext4    | 18       | 11.04%  |
| Unknown | 4        | 2.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 90       | 54.55%  |
| GPT     | 52       | 31.52%  |
| MBR     | 23       | 13.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 141      | 86.5%   |
| Yes       | 22       | 13.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 90.74%  |
| Yes       | 15       | 9.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 39       | 24.07%  |
| Gigabyte Technology | 34       | 20.99%  |
| Dell                | 24       | 14.81%  |
| MSI                 | 16       | 9.88%   |
| Hewlett-Packard     | 15       | 9.26%   |
| ASRock              | 7        | 4.32%   |
| Supermicro          | 5        | 3.09%   |
| Intel               | 4        | 2.47%   |
| Unknown             | 4        | 2.47%   |
| Foxconn             | 3        | 1.85%   |
| Lenovo              | 2        | 1.23%   |
| Fujitsu             | 2        | 1.23%   |
| Acer                | 2        | 1.23%   |
| Packard Bell        | 1        | 0.62%   |
| Biostar             | 1        | 0.62%   |
| AZW                 | 1        | 0.62%   |
| ASRockRack          | 1        | 0.62%   |
| Apple               | 1        | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 4        | 2.47%   |
| ASUS All Series                  | 3        | 1.85%   |
| Supermicro SYS-7048A-T           | 2        | 1.23%   |
| HP Compaq 8200 Elite SFF PC      | 2        | 1.23%   |
| Gigabyte X470 AORUS ULTRA GAMING | 2        | 1.23%   |
| Gigabyte A320M-S2H               | 2        | 1.23%   |
| Dell PowerEdge T40               | 2        | 1.23%   |
| Dell OptiPlex 9020               | 2        | 1.23%   |
| Dell OptiPlex 7010               | 2        | 1.23%   |
| ASUS TUF B450M-PRO GAMING        | 2        | 1.23%   |
| ASUS PRIME X570-PRO              | 2        | 1.23%   |
| ASUS PRIME X570-P                | 2        | 1.23%   |
| ASUS M5A99FX PRO R2.0            | 2        | 1.23%   |
| Supermicro X9SCI/X9SCA           | 1        | 0.62%   |
| Supermicro X8SIL                 | 1        | 0.62%   |
| Supermicro X8SAX                 | 1        | 0.62%   |
| Packard Bell IMEDIA D3610 FR     | 1        | 0.62%   |
| MSI MS-7C94                      | 1        | 0.62%   |
| MSI MS-7C91                      | 1        | 0.62%   |
| MSI MS-7C88                      | 1        | 0.62%   |
| MSI MS-7C84                      | 1        | 0.62%   |
| MSI MS-7C83                      | 1        | 0.62%   |
| MSI MS-7C37                      | 1        | 0.62%   |
| MSI MS-7C02                      | 1        | 0.62%   |
| MSI MS-7A75                      | 1        | 0.62%   |
| MSI MS-7A40                      | 1        | 0.62%   |
| MSI MS-7A38                      | 1        | 0.62%   |
| MSI MS-7A36                      | 1        | 0.62%   |
| MSI MS-7918                      | 1        | 0.62%   |
| MSI MS-7793                      | 1        | 0.62%   |
| MSI MS-7756                      | 1        | 0.62%   |
| MSI MS-7636                      | 1        | 0.62%   |
| MSI HPE-421f                     | 1        | 0.62%   |
| Lenovo ThinkCentre M92p 3238AZ8  | 1        | 0.62%   |
| Lenovo IdeaCentre K410           | 1        | 0.62%   |
| Intel X99                        | 1        | 0.62%   |
| Intel DP45SG AAE27733-405        | 1        | 0.62%   |
| Intel DH55TC AAE70932-302        | 1        | 0.62%   |
| Intel D54250WYK H13922-303       | 1        | 0.62%   |
| HP Z800 Workstation              | 1        | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 11       | 6.79%   |
| ASUS PRIME             | 7        | 4.32%   |
| ASUS TUF               | 5        | 3.09%   |
| HP Compaq              | 4        | 2.47%   |
| Dell Precision         | 4        | 2.47%   |
| Dell PowerEdge         | 4        | 2.47%   |
| Dell Inspiron          | 4        | 2.47%   |
| Unknown                | 4        | 2.47%   |
| Gigabyte X570          | 3        | 1.85%   |
| ASUS ROG               | 3        | 1.85%   |
| ASUS P8Z77-V           | 3        | 1.85%   |
| ASUS All               | 3        | 1.85%   |
| Supermicro SYS-7048A-T | 2        | 1.23%   |
| HP ProDesk             | 2        | 1.23%   |
| Gigabyte Z370          | 2        | 1.23%   |
| Gigabyte X470          | 2        | 1.23%   |
| Gigabyte A320M-S2H     | 2        | 1.23%   |
| ASUS M5A99FX           | 2        | 1.23%   |
| ASUS M5A78L-M          | 2        | 1.23%   |
| Supermicro X9SCI       | 1        | 0.62%   |
| Supermicro X8SIL       | 1        | 0.62%   |
| Supermicro X8SAX       | 1        | 0.62%   |
| Packard Bell IMEDIA    | 1        | 0.62%   |
| MSI MS-7C94            | 1        | 0.62%   |
| MSI MS-7C91            | 1        | 0.62%   |
| MSI MS-7C88            | 1        | 0.62%   |
| MSI MS-7C84            | 1        | 0.62%   |
| MSI MS-7C83            | 1        | 0.62%   |
| MSI MS-7C37            | 1        | 0.62%   |
| MSI MS-7C02            | 1        | 0.62%   |
| MSI MS-7A75            | 1        | 0.62%   |
| MSI MS-7A40            | 1        | 0.62%   |
| MSI MS-7A38            | 1        | 0.62%   |
| MSI MS-7A36            | 1        | 0.62%   |
| MSI MS-7918            | 1        | 0.62%   |
| MSI MS-7793            | 1        | 0.62%   |
| MSI MS-7756            | 1        | 0.62%   |
| MSI MS-7636            | 1        | 0.62%   |
| MSI HPE-421f           | 1        | 0.62%   |
| Lenovo ThinkCentre     | 1        | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 20       | 12.35%  |
| 2012 | 19       | 11.73%  |
| 2018 | 17       | 10.49%  |
| 2013 | 16       | 9.88%   |
| 2017 | 15       | 9.26%   |
| 2010 | 11       | 6.79%   |
| 2016 | 10       | 6.17%   |
| 2011 | 10       | 6.17%   |
| 2020 | 9        | 5.56%   |
| 2009 | 8        | 4.94%   |
| 2014 | 7        | 4.32%   |
| 2015 | 6        | 3.7%    |
| 2008 | 5        | 3.09%   |
| 2007 | 4        | 2.47%   |
| 2021 | 3        | 1.85%   |
| 2023 | 1        | 0.62%   |
| 2022 | 1        | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 162      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 161      | 99.38%  |
| Enabled  | 1        | 0.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 162      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 36       | 22.09%  |
| 4.01-8.0    | 33       | 20.25%  |
| 32.01-64.0  | 30       | 18.4%   |
| 3.01-4.0    | 19       | 11.66%  |
| 64.01-256.0 | 19       | 11.66%  |
| 8.01-16.0   | 19       | 11.66%  |
| 24.01-32.0  | 5        | 3.07%   |
| 2.01-3.0    | 1        | 0.61%   |
| 1.01-2.0    | 1        | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 46       | 25.14%  |
| 3.01-4.0   | 38       | 20.77%  |
| 4.01-8.0   | 37       | 20.22%  |
| 1.01-2.0   | 31       | 16.94%  |
| 8.01-16.0  | 16       | 8.74%   |
| 0.51-1.0   | 8        | 4.37%   |
| 16.01-24.0 | 3        | 1.64%   |
| 32.01-64.0 | 2        | 1.09%   |
| 0.01-0.5   | 2        | 1.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 35.76%  |
| 2      | 42       | 25.45%  |
| 3      | 27       | 16.36%  |
| 4      | 14       | 8.48%   |
| 5      | 6        | 3.64%   |
| 6      | 5        | 3.03%   |
| 8      | 3        | 1.82%   |
| 7      | 3        | 1.82%   |
| 19     | 2        | 1.21%   |
| 9      | 2        | 1.21%   |
| 15     | 1        | 0.61%   |
| 13     | 1        | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 58.9%   |
| Yes       | 67       | 41.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 162      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 67.68%  |
| Yes       | 53       | 32.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 68.52%  |
| Yes       | 51       | 31.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 36       | 22.22%  |
| Germany      | 17       | 10.49%  |
| India        | 11       | 6.79%   |
| Brazil       | 8        | 4.94%   |
| Russia       | 7        | 4.32%   |
| Canada       | 7        | 4.32%   |
| Poland       | 6        | 3.7%    |
| UK           | 5        | 3.09%   |
| France       | 4        | 2.47%   |
| Ukraine      | 3        | 1.85%   |
| Turkey       | 3        | 1.85%   |
| Switzerland  | 3        | 1.85%   |
| Sweden       | 3        | 1.85%   |
| Netherlands  | 3        | 1.85%   |
| Italy        | 3        | 1.85%   |
| Hungary      | 3        | 1.85%   |
| Finland      | 3        | 1.85%   |
| Czechia      | 3        | 1.85%   |
| China        | 3        | 1.85%   |
| Romania      | 2        | 1.23%   |
| Peru         | 2        | 1.23%   |
| Indonesia    | 2        | 1.23%   |
| Hong Kong    | 2        | 1.23%   |
| Australia    | 2        | 1.23%   |
| Thailand     | 1        | 0.62%   |
| Taiwan       | 1        | 0.62%   |
| South Korea  | 1        | 0.62%   |
| South Africa | 1        | 0.62%   |
| Slovenia     | 1        | 0.62%   |
| Slovakia     | 1        | 0.62%   |
| Serbia       | 1        | 0.62%   |
| Saudi Arabia | 1        | 0.62%   |
| Portugal     | 1        | 0.62%   |
| Norway       | 1        | 0.62%   |
| Mexico       | 1        | 0.62%   |
| Malaysia     | 1        | 0.62%   |
| Luxembourg   | 1        | 0.62%   |
| Lithuania    | 1        | 0.62%   |
| Iran         | 1        | 0.62%   |
| Greece       | 1        | 0.62%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Portland            | 4        | 2.44%   |
| Berlin              | 4        | 2.44%   |
| Warsaw              | 2        | 1.22%   |
| Sydney              | 2        | 1.22%   |
| Sao Paulo           | 2        | 1.22%   |
| Prague              | 2        | 1.22%   |
| Munich              | 2        | 1.22%   |
| Moscow              | 2        | 1.22%   |
| Lima                | 2        | 1.22%   |
| Istanbul            | 2        | 1.22%   |
| Ernakulam           | 2        | 1.22%   |
| Central             | 2        | 1.22%   |
| Budapest            | 2        | 1.22%   |
| Bengaluru           | 2        | 1.22%   |
| Alexandria          | 2        | 1.22%   |
| Zurich              | 1        | 0.61%   |
| Zaporizhzhia        | 1        | 0.61%   |
| Zapopan             | 1        | 0.61%   |
| Yozgat              | 1        | 0.61%   |
| Wodzisław Śląski | 1        | 0.61%   |
| West Bromwich       | 1        | 0.61%   |
| Waxhaw              | 1        | 0.61%   |
| Vitebsk             | 1        | 0.61%   |
| Vaugneray           | 1        | 0.61%   |
| Val-des-Monts       | 1        | 0.61%   |
| Tuusula             | 1        | 0.61%   |
| Tremembe            | 1        | 0.61%   |
| Tehran              | 1        | 0.61%   |
| Taubate             | 1        | 0.61%   |
| Tambov              | 1        | 0.61%   |
| Sunderland          | 1        | 0.61%   |
| Sundbyberg          | 1        | 0.61%   |
| Sucy-en-Brie        | 1        | 0.61%   |
| Stuttgart           | 1        | 0.61%   |
| Stockholm           | 1        | 0.61%   |
| Southlake           | 1        | 0.61%   |
| South Jordan        | 1        | 0.61%   |
| Sopot               | 1        | 0.61%   |
| Sollentuna          | 1        | 0.61%   |
| Shenzhen            | 1        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 68       | 239    | 22.22%  |
| Seagate                     | 54       | 115    | 17.65%  |
| Samsung Electronics         | 46       | 72     | 15.03%  |
| Kingston                    | 21       | 30     | 6.86%   |
| Hitachi                     | 12       | 14     | 3.92%   |
| Toshiba                     | 10       | 18     | 3.27%   |
| SanDisk                     | 9        | 10     | 2.94%   |
| Intel                       | 8        | 11     | 2.61%   |
| Crucial                     | 7        | 8      | 2.29%   |
| HGST                        | 6        | 32     | 1.96%   |
| Unknown                     | 5        | 13     | 1.63%   |
| Silicon Motion              | 5        | 5      | 1.63%   |
| Phison                      | 4        | 5      | 1.31%   |
| A-DATA Technology           | 4        | 5      | 1.31%   |
| SPCC                        | 3        | 8      | 0.98%   |
| SK hynix                    | 3        | 4      | 0.98%   |
| Micron Technology           | 3        | 5      | 0.98%   |
| XPG                         | 2        | 2      | 0.65%   |
| PNY                         | 2        | 3      | 0.65%   |
| OCZ                         | 2        | 3      | 0.65%   |
| Micron/Crucial Technology   | 2        | 3      | 0.65%   |
| KIOXIA-EXCERIA              | 2        | 5      | 0.65%   |
| Hewlett-Packard             | 2        | 5      | 0.65%   |
| Gigabyte Technology         | 2        | 2      | 0.65%   |
| Dell                        | 2        | 4      | 0.65%   |
| Apacer                      | 2        | 2      | 0.65%   |
| Verbatim                    | 1        | 1      | 0.33%   |
| V-GeN                       | 1        | 1      | 0.33%   |
| Team                        | 1        | 1      | 0.33%   |
| SSSTC                       | 1        | 1      | 0.33%   |
| SATADOM-SL                  | 1        | 1      | 0.33%   |
| ROG                         | 1        | 1      | 0.33%   |
| Realtek Semiconductor       | 1        | 1      | 0.33%   |
| Plextor                     | 1        | 1      | 0.33%   |
| Patriot                     | 1        | 3      | 0.33%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 0.33%   |
| Lexar                       | 1        | 1      | 0.33%   |
| Leven                       | 1        | 1      | 0.33%   |
| KIOXIA                      | 1        | 1      | 0.33%   |
| Kingston Technology Company | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WD20EARX-00PASB0 2TB            | 6        | 1.52%   |
| Toshiba DT01ACA100 1TB              | 5        | 1.27%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 4        | 1.01%   |
| WDC WD10EZEX-08WN4A0 1TB            | 4        | 1.01%   |
| Seagate ST500DM002-1BD142 500GB     | 4        | 1.01%   |
| Seagate ST31000528AS 1TB            | 4        | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 1.01%   |
| Kingston SA400S37480G 480GB SSD     | 4        | 1.01%   |
| Kingston SA400S37240G 240GB SSD     | 4        | 1.01%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3        | 0.76%   |
| WDC WD40EZRZ-00GXCB0 4TB            | 3        | 0.76%   |
| WDC WD40EFRX-68N32N0 4TB            | 3        | 0.76%   |
| WDC WD20EZRX-00D8PB0 2TB            | 3        | 0.76%   |
| Seagate ST1000DM003-1ER162 1TB      | 3        | 0.76%   |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 0.76%   |
| Samsung SSD 970 PRO 512GB           | 3        | 0.76%   |
| Samsung SSD 860 EVO 500GB           | 3        | 0.76%   |
| Samsung SSD 860 EVO 1TB             | 3        | 0.76%   |
| Samsung SSD 850 EVO 250GB           | 3        | 0.76%   |
| Samsung SSD 840 EVO 250GB           | 3        | 0.76%   |
| Samsung NVMe SSD Drive 500GB        | 3        | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2        | 0.51%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2        | 0.51%   |
| WDC WD40PURZ-85TTDY0 4TB            | 2        | 0.51%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2        | 0.51%   |
| WDC WD2500AAJS-75M0A0 250GB         | 2        | 0.51%   |
| WDC WD20PURZ-85AKKY0 2TB            | 2        | 0.51%   |
| WDC WD20PURX-64PFUY0 2TB            | 2        | 0.51%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 0.51%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 2        | 0.51%   |
| WDC WD2002FAEX-007BA0 2TB           | 2        | 0.51%   |
| Unknown SD/MMC/MS PRO 128GB         | 2        | 0.51%   |
| Unknown HUH728080ALE601 8TB         | 2        | 0.51%   |
| Silicon Motion NVMe SSD Drive 512GB | 2        | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB      | 2        | 0.51%   |
| Seagate ST31000524AS 1TB            | 2        | 0.51%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 0.51%   |
| Seagate ST2000DM001-9YN164 2TB      | 2        | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB      | 2        | 0.51%   |
| Seagate Expansion Desk 5TB          | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 65       | 229    | 39.63%  |
| Seagate             | 52       | 113    | 31.71%  |
| Hitachi             | 12       | 14     | 7.32%   |
| Toshiba             | 10       | 18     | 6.1%    |
| Samsung Electronics | 7        | 7      | 4.27%   |
| HGST                | 6        | 32     | 3.66%   |
| Unknown             | 4        | 12     | 2.44%   |
| Hewlett-Packard     | 2        | 5      | 1.22%   |
| Dell                | 2        | 4      | 1.22%   |
| JMicron Technology  | 1        | 1      | 0.61%   |
| Fujitsu             | 1        | 2      | 0.61%   |
| ASMT                | 1        | 1      | 0.61%   |
| Apple               | 1        | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 28       | 44     | 27.72%  |
| Kingston            | 20       | 29     | 19.8%   |
| WDC                 | 7        | 10     | 6.93%   |
| Intel               | 7        | 8      | 6.93%   |
| Crucial             | 6        | 7      | 5.94%   |
| SanDisk             | 5        | 6      | 4.95%   |
| SPCC                | 3        | 8      | 2.97%   |
| SK hynix            | 3        | 4      | 2.97%   |
| PNY                 | 2        | 3      | 1.98%   |
| OCZ                 | 2        | 3      | 1.98%   |
| Micron Technology   | 2        | 3      | 1.98%   |
| Apacer              | 2        | 2      | 1.98%   |
| A-DATA Technology   | 2        | 2      | 1.98%   |
| Verbatim            | 1        | 1      | 0.99%   |
| V-GeN               | 1        | 1      | 0.99%   |
| Team                | 1        | 1      | 0.99%   |
| Seagate             | 1        | 1      | 0.99%   |
| SATADOM-SL          | 1        | 1      | 0.99%   |
| Plextor             | 1        | 1      | 0.99%   |
| Patriot             | 1        | 3      | 0.99%   |
| Lexar               | 1        | 1      | 0.99%   |
| Leven               | 1        | 1      | 0.99%   |
| KIOXIA-EXCERIA      | 1        | 2      | 0.99%   |
| GOODRAM             | 1        | 1      | 0.99%   |
| China               | 1        | 4      | 0.99%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 115      | 439    | 46.94%  |
| SSD     | 84       | 147    | 34.29%  |
| NVMe    | 44       | 61     | 17.96%  |
| Unknown | 2        | 2      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 149      | 569    | 72.68%  |
| NVMe | 44       | 61     | 21.46%  |
| SAS  | 12       | 19     | 5.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 103      | 198    | 42.74%  |
| 0.51-1.0   | 67       | 119    | 27.8%   |
| 1.01-2.0   | 39       | 99     | 16.18%  |
| 4.01-10.0  | 13       | 33     | 5.39%   |
| 3.01-4.0   | 11       | 70     | 4.56%   |
| 2.01-3.0   | 5        | 45     | 2.07%   |
| 10.01-20.0 | 3        | 22     | 1.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 38       | 22.62%  |
| 251-500        | 31       | 18.45%  |
| 101-250        | 30       | 17.86%  |
| More than 3000 | 23       | 13.69%  |
| 1001-2000      | 23       | 13.69%  |
| Unknown        | 7        | 4.17%   |
| 51-100         | 6        | 3.57%   |
| 21-50          | 4        | 2.38%   |
| 2001-3000      | 4        | 2.38%   |
| 1-20           | 2        | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 48       | 27.12%  |
| 21-50          | 32       | 18.08%  |
| 101-250        | 26       | 14.69%  |
| 51-100         | 16       | 9.04%   |
| 251-500        | 15       | 8.47%   |
| More than 3000 | 12       | 6.78%   |
| 501-1000       | 12       | 6.78%   |
| 1001-2000      | 9        | 5.08%   |
| Unknown        | 7        | 3.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB              | 2        | 5      | 7.41%   |
| Seagate ST2000DM001-9YN164 2TB        | 2        | 2      | 7.41%   |
| WDC WD6400AADS-00M2B0 640GB           | 1        | 1      | 3.7%    |
| WDC WD5000LPVX-22V0TT0 500GB          | 1        | 1      | 3.7%    |
| WDC WD5000AACS-00G8B0 500GB           | 1        | 1      | 3.7%    |
| WDC WD3200AVVS-63L2B0 320GB           | 1        | 1      | 3.7%    |
| WDC WD20PURX-64PFUY0 2TB              | 1        | 1      | 3.7%    |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1        | 1      | 3.7%    |
| WDC WD1003FBYX-01Y7B0 1TB             | 1        | 1      | 3.7%    |
| WDC WD1002FBYS-18A6B0 1TB             | 1        | 1      | 3.7%    |
| WDC RFT030VQFF-KRM5P7 3TB             | 1        | 1      | 3.7%    |
| Toshiba MK2552GSX 250GB               | 1        | 1      | 3.7%    |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1        | 1      | 3.7%    |
| Seagate ST500LT012-1DG142 500GB       | 1        | 1      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 3.7%    |
| Seagate ST3400820AS 400GB             | 1        | 1      | 3.7%    |
| Seagate ST3000VM002-1ET166 3TB        | 1        | 1      | 3.7%    |
| Seagate ST1000DM003-1ER162 1TB        | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 840 EVO 250GB | 1        | 1      | 3.7%    |
| Intel SSDSA2M040G2GC 40GB             | 1        | 1      | 3.7%    |
| Hitachi HUS724040ALE641 4TB           | 1        | 1      | 3.7%    |
| Hitachi HTS723232A7A364 320GB         | 1        | 1      | 3.7%    |
| Hitachi HDT721010SLA360 1TB           | 1        | 1      | 3.7%    |
| HGST HUS726060ALA640 6TB              | 1        | 1      | 3.7%    |
| HGST HDS724040ALE640 4TB              | 1        | 2      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 14     | 33.33%  |
| Seagate             | 7        | 7      | 29.17%  |
| Hitachi             | 3        | 3      | 12.5%   |
| HGST                | 2        | 3      | 8.33%   |
| Toshiba             | 1        | 1      | 4.17%   |
| SK hynix            | 1        | 1      | 4.17%   |
| Samsung Electronics | 1        | 1      | 4.17%   |
| Intel               | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 8        | 14     | 38.1%   |
| Seagate | 7        | 7      | 33.33%  |
| Hitachi | 3        | 3      | 14.29%  |
| HGST    | 2        | 3      | 9.52%   |
| Toshiba | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 28     | 85.71%  |
| SSD  | 3        | 3      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Desktops | Drives | Percent |
|------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB | 1        | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 97       | 299    | 52.15%  |
| Works    | 68       | 317    | 36.56%  |
| Malfunc  | 20       | 31     | 10.75%  |
| Failed   | 1        | 2      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 111      | 45.12%  |
| AMD                            | 49       | 19.92%  |
| Samsung Electronics            | 17       | 6.91%   |
| ASMedia Technology             | 13       | 5.28%   |
| Marvell Technology Group       | 7        | 2.85%   |
| JMicron Technology             | 7        | 2.85%   |
| Silicon Motion                 | 6        | 2.44%   |
| Phison Electronics             | 6        | 2.44%   |
| LSI Logic / Symbios Logic      | 5        | 2.03%   |
| Sandisk                        | 4        | 1.63%   |
| Broadcom / LSI                 | 3        | 1.22%   |
| ADATA Technology               | 3        | 1.22%   |
| Micron/Crucial Technology      | 2        | 0.81%   |
| Micron Technology              | 2        | 0.81%   |
| Kingston Technology Company    | 2        | 0.81%   |
| Toshiba America Info Systems   | 1        | 0.41%   |
| Solid State Storage Technology | 1        | 0.41%   |
| Silicon Image                  | 1        | 0.41%   |
| Realtek Semiconductor          | 1        | 0.41%   |
| Nvidia                         | 1        | 0.41%   |
| MAXIO Technology (Hangzhou)    | 1        | 0.41%   |
| KIOXIA                         | 1        | 0.41%   |
| Integrated Technology Express  | 1        | 0.41%   |
| Adaptec                        | 1        | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33       | 11.04%  |
| Intel SATA Controller [RAID mode]                                              | 19       | 6.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 14       | 4.68%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 12       | 4.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 3.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 3.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8        | 2.68%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 2.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6        | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 2.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6        | 2.01%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 6        | 2.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5        | 1.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 5        | 1.67%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 5        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5        | 1.67%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4        | 1.34%   |
| JMicron JMB363 SATA/IDE Controller                                             | 4        | 1.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 1.34%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 4        | 1.34%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 4        | 1.34%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 4        | 1.34%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 4        | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4        | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 1.34%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3        | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 1%      |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 3        | 1%      |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 3        | 1%      |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 1%      |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 3        | 1%      |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 1%      |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 1%      |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2        | 0.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2        | 0.67%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2        | 0.67%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 2        | 0.67%   |
| JMicron JMB368 IDE controller                                                  | 2        | 0.67%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 116      | 51.56%  |
| NVMe | 44       | 19.56%  |
| IDE  | 31       | 13.78%  |
| RAID | 28       | 12.44%  |
| SAS  | 4        | 1.78%   |
| SCSI | 2        | 0.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 113      | 69.75%  |
| AMD    | 49       | 30.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 3.07%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 3.07%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 2.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.45%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.45%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 3        | 1.84%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.84%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 1.84%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.84%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.84%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.84%   |
| Intel Xeon E-2224G CPU @ 3.50GHz            | 2        | 1.23%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 2        | 1.23%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 1.23%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 1.23%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 1.23%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 1.23%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.23%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 1.23%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.23%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.23%   |
| Intel Core i7-10700F CPU @ 2.90GHz          | 2        | 1.23%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 2        | 1.23%   |
| Intel Core i5-3470S CPU @ 2.90GHz           | 2        | 1.23%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 1.23%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 2        | 1.23%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 2        | 1.23%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.23%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.23%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 0.61%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1        | 0.61%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.61%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5606 @ 2.13GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1        | 0.61%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 0.61%   |
| Intel Xeon CPU E31260L @ 2.40GHz            | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 19.02%  |
| Intel Core i7           | 27       | 16.56%  |
| Intel Xeon              | 18       | 11.04%  |
| AMD Ryzen 5             | 12       | 7.36%   |
| AMD Ryzen 9             | 9        | 5.52%   |
| Intel Core i3           | 8        | 4.91%   |
| Intel Core 2 Quad       | 8        | 4.91%   |
| AMD FX                  | 8        | 4.91%   |
| AMD Ryzen 7             | 7        | 4.29%   |
| Intel Core 2 Duo        | 5        | 3.07%   |
| Intel Pentium           | 4        | 2.45%   |
| AMD Ryzen 3             | 4        | 2.45%   |
| Other                   | 3        | 1.84%   |
| AMD Ryzen Threadripper  | 3        | 1.84%   |
| Intel Celeron           | 2        | 1.23%   |
| Intel Atom              | 2        | 1.23%   |
| AMD Ryzen 7 PRO         | 2        | 1.23%   |
| Intel Pentium Gold      | 1        | 0.61%   |
| Intel Pentium Dual-Core | 1        | 0.61%   |
| Intel Pentium Dual      | 1        | 0.61%   |
| Intel Genuine           | 1        | 0.61%   |
| Intel Core i9           | 1        | 0.61%   |
| AMD Turion II Neo       | 1        | 0.61%   |
| AMD Phenom II X4        | 1        | 0.61%   |
| AMD Opteron             | 1        | 0.61%   |
| AMD A4                  | 1        | 0.61%   |
| AMD A10                 | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 77       | 47.24%  |
| 2      | 25       | 15.34%  |
| 6      | 22       | 13.5%   |
| 8      | 15       | 9.2%    |
| 12     | 12       | 7.36%   |
| 16     | 8        | 4.91%   |
| 3      | 2        | 1.23%   |
| 1      | 2        | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 155      | 95.68%  |
| 2      | 7        | 4.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 95       | 57.93%  |
| 1      | 69       | 42.07%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 158      | 97.53%  |
| Unknown        | 4        | 2.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 16       | 9.7%    |
| 0x306a9    | 16       | 9.7%    |
| 0x08701021 | 11       | 6.67%   |
| 0x206a7    | 9        | 5.45%   |
| 0x06000852 | 9        | 5.45%   |
| 0x906ea    | 8        | 4.85%   |
| Unknown    | 8        | 4.85%   |
| 0x506e3    | 7        | 4.24%   |
| 0x0800820d | 7        | 4.24%   |
| 0x1067a    | 6        | 3.64%   |
| 0x106e5    | 5        | 3.03%   |
| 0x08701013 | 5        | 3.03%   |
| 0xa0655    | 4        | 2.42%   |
| 0x906e9    | 4        | 2.42%   |
| 0x6fb      | 4        | 2.42%   |
| 0x306f2    | 4        | 2.42%   |
| 0x6fd      | 3        | 1.82%   |
| 0x206c2    | 3        | 1.82%   |
| 0x0a201009 | 3        | 1.82%   |
| 0x08101016 | 3        | 1.82%   |
| 0x106a5    | 2        | 1.21%   |
| 0x10677    | 2        | 1.21%   |
| 0x08001137 | 2        | 1.21%   |
| 0xa0671    | 1        | 0.61%   |
| 0xa0653    | 1        | 0.61%   |
| 0x906ed    | 1        | 0.61%   |
| 0x906eb    | 1        | 0.61%   |
| 0x90672    | 1        | 0.61%   |
| 0x406f1    | 1        | 0.61%   |
| 0x406c4    | 1        | 0.61%   |
| 0x40651    | 1        | 0.61%   |
| 0x306e4    | 1        | 0.61%   |
| 0x206d7    | 1        | 0.61%   |
| 0x20655    | 1        | 0.61%   |
| 0x20652    | 1        | 0.61%   |
| 0x106ca    | 1        | 0.61%   |
| 0x106c2    | 1        | 0.61%   |
| 0x10676    | 1        | 0.61%   |
| 0x08701012 | 1        | 0.61%   |
| 0x08701011 | 1        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 12.88%  |
| Zen 2            | 19       | 11.66%  |
| IvyBridge        | 17       | 10.43%  |
| KabyLake         | 14       | 8.59%   |
| SandyBridge      | 11       | 6.75%   |
| Piledriver       | 10       | 6.13%   |
| Penryn           | 9        | 5.52%   |
| Zen              | 8        | 4.91%   |
| Skylake          | 8        | 4.91%   |
| Zen+             | 7        | 4.29%   |
| Nehalem          | 7        | 4.29%   |
| Core             | 7        | 4.29%   |
| Westmere         | 6        | 3.68%   |
| CometLake        | 5        | 3.07%   |
| Zen 3            | 3        | 1.84%   |
| K10              | 2        | 1.23%   |
| Bonnell          | 2        | 1.23%   |
| Silvermont       | 1        | 0.61%   |
| K10 Llano        | 1        | 0.61%   |
| Gracemont        | 1        | 0.61%   |
| Goldmont plus    | 1        | 0.61%   |
| Broadwell        | 1        | 0.61%   |
| Alderlake Hybrid | 1        | 0.61%   |
| Unknown          | 1        | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 67       | 37.64%  |
| Nvidia                     | 66       | 37.08%  |
| AMD                        | 41       | 23.03%  |
| S3 Graphics                | 2        | 1.12%   |
| Matrox Electronics Systems | 1        | 0.56%   |
| ASPEED Technology          | 1        | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 7.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 6.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 11       | 6.15%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 3.35%   |
| Intel HD Graphics 530                                                       | 6        | 3.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 3.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 2.79%   |
| Nvidia GT218 [GeForce G210]                                                 | 3        | 1.68%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.68%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.68%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 3        | 1.68%   |
| Intel HD Graphics 630                                                       | 3        | 1.68%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.12%   |
| Nvidia GK107 [NVS 510]                                                      | 2        | 1.12%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.12%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 2        | 1.12%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 1.12%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.12%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.12%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 1.12%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.12%   |
| S3 Graphics Savage 4                                                        | 1        | 0.56%   |
| S3 Graphics 86c375 [ViRGE/DX] or 86c385 [ViRGE/GX]                          | 1        | 0.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.56%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.56%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.56%   |
| Nvidia TU104GL [Quadro RTX 5000]                                            | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.56%   |
| Nvidia GT218 [NVS 300]                                                      | 1        | 0.56%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 1        | 0.56%   |
| Nvidia GP107GL [Quadro P620]                                                | 1        | 0.56%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 60       | 36.81%  |
| 1 x Intel            | 56       | 34.36%  |
| 1 x AMD              | 35       | 21.47%  |
| Intel + AMD          | 3        | 1.84%   |
| 1 x S3 Graphics      | 2        | 1.23%   |
| Intel + Nvidia       | 2        | 1.23%   |
| 2 x AMD + 1 x ASPEED | 1        | 0.61%   |
| 2 x AMD              | 1        | 0.61%   |
| 1 x Matrox           | 1        | 0.61%   |
| Intel + 2 x Nvidia   | 1        | 0.61%   |
| AMD + Nvidia         | 1        | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 122      | 73.05%  |
| Proprietary | 29       | 17.37%  |
| Unknown     | 16       | 9.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 45.29%  |
| 1.01-2.0   | 25       | 14.71%  |
| 0.51-1.0   | 20       | 11.76%  |
| 0.01-0.5   | 16       | 9.41%   |
| 7.01-8.0   | 15       | 8.82%   |
| 3.01-4.0   | 9        | 5.29%   |
| 8.01-16.0  | 3        | 1.76%   |
| 5.01-6.0   | 2        | 1.18%   |
| 2.01-3.0   | 2        | 1.18%   |
| 4.01-5.0   | 1        | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 27       | 15.88%  |
| Dell                 | 27       | 15.88%  |
| Goldstar             | 20       | 11.76%  |
| Hewlett-Packard      | 18       | 10.59%  |
| Acer                 | 14       | 8.24%   |
| BenQ                 | 7        | 4.12%   |
| ViewSonic            | 6        | 3.53%   |
| Philips              | 6        | 3.53%   |
| LG Electronics       | 5        | 2.94%   |
| Eizo                 | 5        | 2.94%   |
| Ancor Communications | 5        | 2.94%   |
| Sony                 | 3        | 1.76%   |
| Iiyama               | 3        | 1.76%   |
| Xiaomi               | 2        | 1.18%   |
| Unknown              | 2        | 1.18%   |
| MStar                | 2        | 1.18%   |
| HPN                  | 2        | 1.18%   |
| HannStar             | 2        | 1.18%   |
| AOC                  | 2        | 1.18%   |
| Xerox                | 1        | 0.59%   |
| Unknown (XXX)        | 1        | 0.59%   |
| Sceptre Tech         | 1        | 0.59%   |
| NEC Computers        | 1        | 0.59%   |
| Lenovo               | 1        | 0.59%   |
| Insignia             | 1        | 0.59%   |
| HannStar Display     | 1        | 0.59%   |
| Gateway              | 1        | 0.59%   |
| Chimei Innolux       | 1        | 0.59%   |
| AUS                  | 1        | 0.59%   |
| ASUSTek Computer     | 1        | 0.59%   |
| Apple                | 1        | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch             | 3        | 1.52%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 3        | 1.52%   |
| Xiaomi Mi TV XMD009A 2880x1800 480x270mm 21.7-inch                   | 2        | 1.02%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch | 2        | 1.02%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch  | 2        | 1.02%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 2        | 1.02%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                     | 2        | 1.02%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch         | 2        | 1.02%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 2        | 1.02%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 1.02%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 2        | 1.02%   |
| BenQ LCD Monitor GW2283 3840x1080                                    | 2        | 1.02%   |
| BenQ LCD Monitor GW2283                                              | 2        | 1.02%   |
| Xerox XM7-22w XER08E8 1680x1050 474x296mm 22.0-inch                  | 1        | 0.51%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 698x393mm 31.5-inch            | 1        | 0.51%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 0.51%   |
| ViewSonic VA2759 Series VSC6832 1920x1080 598x336mm 27.0-inch        | 1        | 0.51%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 509x286mm 23.0-inch        | 1        | 0.51%   |
| ViewSonic VA2210-FHD VSCC536 1920x1080 476x268mm 21.5-inch           | 1        | 0.51%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch           | 1        | 0.51%   |
| Unknown LCD Monitor XXX AAA 1366x768                                 | 1        | 0.51%   |
| Unknown LCD Monitor BENQ G2200W 5520x2160                            | 1        | 0.51%   |
| Unknown (XXX) FURRION TV XXX3553 1920x1080 520x290mm 23.4-inch       | 1        | 0.51%   |
| Sony TV *00 SNY8404 3840x2160 1439x809mm 65.0-inch                   | 1        | 0.51%   |
| Sony TV *00 SNY7C04 3840x2160 1660x934mm 75.0-inch                   | 1        | 0.51%   |
| Sony SDM-E96D SNYB400 1280x1024 376x301mm 19.0-inch                  | 1        | 0.51%   |
| Sceptre Tech U435CV-UMC SPT1109 3840x2160 575x323mm 26.0-inch        | 1        | 0.51%   |
| Samsung Electronics U28E850 SAM0CCD 3840x2160 608x345mm 27.5-inch    | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM0094 1280x1024 338x270mm 17.0-inch | 1        | 0.51%   |
| Samsung Electronics SMS27A650 SAM082C 1920x1080 598x336mm 27.0-inch  | 1        | 0.51%   |
| Samsung Electronics SMEX2220 SAM0685 1920x1080 477x268mm 21.5-inch   | 1        | 0.51%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 477x268mm 21.5-inch   | 1        | 0.51%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch    | 1        | 0.51%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch    | 1        | 0.51%   |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch    | 1        | 0.51%   |
| Samsung Electronics S27E330 SAM0D90 1920x1080 598x336mm 27.0-inch    | 1        | 0.51%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 1        | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 72       | 43.37%  |
| 3840x2160 (4K)     | 18       | 10.84%  |
| 1920x1200 (WUXGA)  | 12       | 7.23%   |
| Unknown            | 11       | 6.63%   |
| 1680x1050 (WSXGA+) | 9        | 5.42%   |
| 2560x1440 (QHD)    | 7        | 4.22%   |
| 1366x768 (WXGA)    | 5        | 3.01%   |
| 3840x1080          | 4        | 2.41%   |
| 1600x900 (HD+)     | 4        | 2.41%   |
| 1280x1024 (SXGA)   | 4        | 2.41%   |
| 3440x1440          | 3        | 1.81%   |
| 2560x1080          | 3        | 1.81%   |
| 1024x768 (XGA)     | 3        | 1.81%   |
| 1600x1200          | 2        | 1.2%    |
| 7680x1080          | 1        | 0.6%    |
| 7280x2160          | 1        | 0.6%    |
| 5520x2160          | 1        | 0.6%    |
| 3840x1200          | 1        | 0.6%    |
| 3640x1920          | 1        | 0.6%    |
| 2560x1600          | 1        | 0.6%    |
| 1440x900 (WXGA+)   | 1        | 0.6%    |
| 1400x1050          | 1        | 0.6%    |
| 1280x960           | 1        | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 30       | 17.34%  |
| 24      | 26       | 15.03%  |
| Unknown | 23       | 13.29%  |
| 23      | 22       | 12.72%  |
| 21      | 22       | 12.72%  |
| 20      | 8        | 4.62%   |
| 31      | 5        | 2.89%   |
| 19      | 5        | 2.89%   |
| 15      | 5        | 2.89%   |
| 34      | 4        | 2.31%   |
| 22      | 4        | 2.31%   |
| 40      | 3        | 1.73%   |
| 52      | 2        | 1.16%   |
| 32      | 2        | 1.16%   |
| 25      | 2        | 1.16%   |
| 18      | 2        | 1.16%   |
| 17      | 2        | 1.16%   |
| 84      | 1        | 0.58%   |
| 75      | 1        | 0.58%   |
| 65      | 1        | 0.58%   |
| 58      | 1        | 0.58%   |
| 49      | 1        | 0.58%   |
| 30      | 1        | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 68       | 42.24%  |
| 401-500     | 35       | 21.74%  |
| Unknown     | 23       | 14.29%  |
| 601-700     | 9        | 5.59%   |
| 301-350     | 7        | 4.35%   |
| 701-800     | 6        | 3.73%   |
| 1001-1500   | 5        | 3.11%   |
| 801-900     | 3        | 1.86%   |
| 351-400     | 3        | 1.86%   |
| 1501-2000   | 2        | 1.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 90       | 59.6%   |
| 16/10   | 23       | 15.23%  |
| Unknown | 22       | 14.57%  |
| 4/3     | 6        | 3.97%   |
| 5/4     | 5        | 3.31%   |
| 21/9    | 4        | 2.65%   |
| 3/2     | 1        | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 53       | 31.93%  |
| 301-350        | 30       | 18.07%  |
| Unknown        | 23       | 13.86%  |
| 151-200        | 16       | 9.64%   |
| 251-300        | 13       | 7.83%   |
| 351-500        | 12       | 7.23%   |
| More than 1000 | 7        | 4.22%   |
| 141-150        | 4        | 2.41%   |
| 101-110        | 4        | 2.41%   |
| 501-1000       | 3        | 1.81%   |
| 111-120        | 1        | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 91       | 59.09%  |
| 101-120 | 27       | 17.53%  |
| Unknown | 23       | 14.94%  |
| 121-160 | 5        | 3.25%   |
| 1-50    | 4        | 2.6%    |
| 161-240 | 4        | 2.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 101      | 60.12%  |
| 2     | 31       | 18.45%  |
| 0     | 28       | 16.67%  |
| 3     | 4        | 2.38%   |
| 4     | 3        | 1.79%   |
| 6     | 1        | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 92       | 39.48%  |
| Intel                     | 89       | 38.2%   |
| Qualcomm Atheros          | 13       | 5.58%   |
| Broadcom                  | 11       | 4.72%   |
| Ralink Technology         | 9        | 3.86%   |
| Mellanox Technologies     | 3        | 1.29%   |
| Aquantia                  | 3        | 1.29%   |
| TP-Link                   | 2        | 0.86%   |
| D-Link System             | 2        | 0.86%   |
| Broadcom Limited          | 2        | 0.86%   |
| ASIX Electronics          | 2        | 0.86%   |
| Spreadtrum Communications | 1        | 0.43%   |
| Ralink                    | 1        | 0.43%   |
| ICS Advent                | 1        | 0.43%   |
| DisplayLink               | 1        | 0.43%   |
| D-Link                    | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 73       | 27.86%  |
| Intel I211 Gigabit Network Connection                                          | 18       | 6.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 3.82%   |
| Intel 82574L Gigabit Network Connection                                        | 8        | 3.05%   |
| Intel Wi-Fi 6 AX200                                                            | 7        | 2.67%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6        | 2.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6        | 2.29%   |
| Intel Ethernet Connection I217-LM                                              | 6        | 2.29%   |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 2.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 6        | 2.29%   |
| Intel 82579V Gigabit Network Connection                                        | 5        | 1.91%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 1.53%   |
| Ralink RT5370 Wireless Adapter                                                 | 3        | 1.15%   |
| Ralink MT7601U Wireless Adapter                                                | 3        | 1.15%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 3        | 1.15%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3        | 1.15%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 1.15%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 3        | 1.15%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3        | 1.15%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 2        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 0.76%   |
| Realtek 802.11ac NIC                                                           | 2        | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2        | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                               | 2        | 0.76%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 2        | 0.76%   |
| Intel Wireless 8265 / 8275                                                     | 2        | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 0.76%   |
| Intel Ethernet Connection (2) I218-V                                           | 2        | 0.76%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 2        | 0.76%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 0.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1        | 0.38%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                         | 1        | 0.38%   |
| Spreadtrum realme Phone                                                        | 1        | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1        | 0.38%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 1        | 0.38%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                         | 1        | 0.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1        | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 25       | 42.37%  |
| Realtek Semiconductor | 9        | 15.25%  |
| Ralink Technology     | 9        | 15.25%  |
| Qualcomm Atheros      | 7        | 11.86%  |
| Broadcom              | 5        | 8.47%   |
| TP-Link               | 2        | 3.39%   |
| Ralink                | 1        | 1.69%   |
| D-Link                | 1        | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 7        | 11.86%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 6        | 10.17%  |
| Ralink RT5370 Wireless Adapter                                                                | 3        | 5.08%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 5.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 3        | 5.08%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 3        | 5.08%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 2        | 3.39%   |
| Realtek 802.11ac NIC                                                                          | 2        | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 2        | 3.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 2        | 3.39%   |
| Intel Wireless 8265 / 8275                                                                    | 2        | 3.39%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 1.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1        | 1.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 1        | 1.69%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1        | 1.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1        | 1.69%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 1.69%   |
| Ralink RT2770 Wireless Adapter                                                                | 1        | 1.69%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1        | 1.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1        | 1.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1        | 1.69%   |
| Intel Wireless 7265                                                                           | 1        | 1.69%   |
| Intel Wireless 7260                                                                           | 1        | 1.69%   |
| Intel Wireless 3165                                                                           | 1        | 1.69%   |
| Intel Wireless 3160                                                                           | 1        | 1.69%   |
| Intel Centrino Advanced-N 6235                                                                | 1        | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1        | 1.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 1.69%   |
| D-Link 802.11 n WLAN                                                                          | 1        | 1.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1        | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 1        | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 89       | 47.09%  |
| Intel                     | 76       | 40.21%  |
| Qualcomm Atheros          | 6        | 3.17%   |
| Broadcom                  | 6        | 3.17%   |
| Aquantia                  | 3        | 1.59%   |
| D-Link System             | 2        | 1.06%   |
| Broadcom Limited          | 2        | 1.06%   |
| ASIX Electronics          | 2        | 1.06%   |
| Spreadtrum Communications | 1        | 0.53%   |
| ICS Advent                | 1        | 0.53%   |
| DisplayLink               | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 73       | 36.5%   |
| Intel I211 Gigabit Network Connection                                          | 18       | 9%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10       | 5%      |
| Intel 82574L Gigabit Network Connection                                        | 8        | 4%      |
| Realtek RTL8125 2.5GbE Controller                                              | 6        | 3%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6        | 3%      |
| Intel Ethernet Connection I217-LM                                              | 6        | 3%      |
| Intel Ethernet Connection (2) I219-V                                           | 6        | 3%      |
| Intel 82579V Gigabit Network Connection                                        | 5        | 2.5%    |
| Intel I210 Gigabit Network Connection                                          | 4        | 2%      |
| Intel Ethernet Connection (7) I219-LM                                          | 3        | 1.5%    |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 1.5%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3        | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2        | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2        | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 1%      |
| Intel Ethernet Connection (7) I219-V                                           | 2        | 1%      |
| Intel Ethernet Connection (2) I218-V                                           | 2        | 1%      |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)  | 2        | 1%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2        | 1%      |
| Spreadtrum realme Phone                                                        | 1        | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1        | 0.5%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 0.5%    |
| Realtek Killer E2600 GbE Controller                                            | 1        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 0.5%    |
| Intel Ethernet Connection I218-V                                               | 1        | 0.5%    |
| Intel Ethernet Connection I217-V                                               | 1        | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.5%    |
| Intel Ethernet Connection (17) I219-LM                                         | 1        | 0.5%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.5%    |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                                         | 1        | 0.5%    |
| Intel CNVi: Wi-Fi                                                              | 1        | 0.5%    |
| Intel 82578DC Gigabit Network Connection                                       | 1        | 0.5%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                             | 1        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 0.5%    |
| Intel 82567LF-2 Gigabit Network Connection                                     | 1        | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 162      | 73.97%  |
| WiFi     | 54       | 24.66%  |
| Unknown  | 3        | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 150      | 88.24%  |
| WiFi     | 19       | 11.18%  |
| Unknown  | 1        | 0.59%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 85       | 52.15%  |
| 2     | 58       | 35.58%  |
| 3     | 15       | 9.2%    |
| 5     | 2        | 1.23%   |
| 7     | 1        | 0.61%   |
| 4     | 1        | 0.61%   |
| 0     | 1        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 152      | 93.83%  |
| Yes  | 10       | 6.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 25       | 49.02%  |
| Cambridge Silicon Radio         | 13       | 25.49%  |
| Broadcom                        | 5        | 9.8%    |
| ASUSTek Computer                | 3        | 5.88%   |
| Realtek Semiconductor           | 2        | 3.92%   |
| Qualcomm Atheros Communications | 1        | 1.96%   |
| IMC Networks                    | 1        | 1.96%   |
| Apple                           | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13       | 25.49%  |
| Intel AX200 Bluetooth                               | 7        | 13.73%  |
| Intel Wireless-AC 3168 Bluetooth                    | 6        | 11.76%  |
| Intel Bluetooth wireless interface                  | 5        | 9.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4        | 7.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 5.88%   |
| Realtek Bluetooth Radio                             | 2        | 3.92%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.96%   |
| Intel AX211 Bluetooth                               | 1        | 1.96%   |
| Intel AX201 Bluetooth                               | 1        | 1.96%   |
| IMC Networks Bluetooth Device                       | 1        | 1.96%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.96%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.96%   |
| ASUS Bluetooth Radio                                | 1        | 1.96%   |
| ASUS BCM20702A0                                     | 1        | 1.96%   |
| Apple Bluetooth Host Controller                     | 1        | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 102      | 41.3%   |
| Nvidia              | 61       | 24.7%   |
| AMD                 | 61       | 24.7%   |
| Logitech            | 3        | 1.21%   |
| Creative Labs       | 3        | 1.21%   |
| C-Media Electronics | 3        | 1.21%   |
| Plantronics         | 2        | 0.81%   |
| JMTek               | 2        | 0.81%   |
| Creative Technology | 2        | 0.81%   |
| Texas Instruments   | 1        | 0.4%    |
| SteelSeries ApS     | 1        | 0.4%    |
| Razer USA           | 1        | 0.4%    |
| NEC Computers       | 1        | 0.4%    |
| Lynx                | 1        | 0.4%    |
| Fry's Electronics   | 1        | 0.4%    |
| Corsair             | 1        | 0.4%    |
| Avid Technology     | 1        | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 21       | 7.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 16       | 5.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 12       | 4.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 12       | 4.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 12       | 4.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 12       | 4.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 10       | 3.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 10       | 3.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 9        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 8        | 2.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 8        | 2.8%    |
| Nvidia High Definition Audio Controller                                                         | 7        | 2.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 6        | 2.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 6        | 2.1%    |
| Intel 200 Series PCH HD Audio                                                                   | 6        | 2.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 6        | 2.1%    |
| Nvidia GK107 HDMI Audio Controller                                                              | 5        | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5        | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                      | 5        | 1.75%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 5        | 1.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 5        | 1.75%   |
| Nvidia TU104 HD Audio Controller                                                                | 4        | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                                                   | 4        | 1.4%    |
| Nvidia GF106 High Definition Audio Controller                                                   | 4        | 1.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 4        | 1.4%    |
| AMD Family 17h/19h/1ah HD Audio Controller                                                      | 4        | 1.4%    |
| Nvidia GP102 HDMI Audio Controller                                                              | 3        | 1.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 3        | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 2        | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                                                   | 2        | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                                                   | 2        | 0.7%    |
| Nvidia GM206 High Definition Audio Controller                                                   | 2        | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 2        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                                                   | 2        | 0.7%    |
| Logitech H390 headset with microphone                                                           | 2        | 0.7%    |
| Intel Comet Lake PCH-V cAVS                                                                     | 2        | 0.7%    |
| Intel Comet Lake PCH cAVS                                                                       | 2        | 0.7%    |
| Creative Technology Sound Blaster Play! 3                                                       | 2        | 0.7%    |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2        | 0.7%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                   | 2        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 16       | 17.78%  |
| Kingston            | 13       | 14.44%  |
| SK hynix            | 11       | 12.22%  |
| Samsung Electronics | 10       | 11.11%  |
| Crucial             | 9        | 10%     |
| Corsair             | 9        | 10%     |
| G.Skill             | 7        | 7.78%   |
| Team                | 3        | 3.33%   |
| Micron Technology   | 3        | 3.33%   |
| A-DATA Technology   | 2        | 2.22%   |
| TwinMOS             | 1        | 1.11%   |
| Transcend           | 1        | 1.11%   |
| Ramaxel Technology  | 1        | 1.11%   |
| Nanya Technology    | 1        | 1.11%   |
| Elpida              | 1        | 1.11%   |
| Apacer              | 1        | 1.11%   |
| Unknown             | 1        | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1600MT/s                      | 2        | 2.17%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2        | 2.17%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 2        | 2.17%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 2        | 2.17%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s     | 2        | 2.17%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1        | 1.09%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 1.09%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                  | 1        | 1.09%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                    | 1        | 1.09%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                | 1        | 1.09%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                   | 1        | 1.09%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 1        | 1.09%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 1        | 1.09%   |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s       | 1        | 1.09%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s          | 1        | 1.09%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s        | 1        | 1.09%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s        | 1        | 1.09%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                     | 1        | 1.09%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s                | 1        | 1.09%   |
| SK hynix RAM Module 16GB DIMM DDR4 3200MT/s               | 1        | 1.09%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR 667MT/s      | 1        | 1.09%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s      | 1        | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 1        | 1.09%   |
| SK hynix RAM HMT351U7BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 1.09%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 1.09%   |
| SK hynix RAM HMT151R7TFR4C-H9 4GB DIMM DDR3 1333MT/s      | 1        | 1.09%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s      | 1        | 1.09%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s      | 1        | 1.09%   |
| SK hynix RAM HMA81GR7AFR8N-UH 8GB DIMM DDR4 2400MT/s      | 1        | 1.09%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                 | 1        | 1.09%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 1        | 1.09%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s      | 1        | 1.09%   |
| Samsung RAM M391B5273DH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.09%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s       | 1        | 1.09%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s    | 1        | 1.09%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s      | 1        | 1.09%   |
| Samsung RAM M378A1K43BB1-CPB 8GB DIMM DDR4 2733MT/s       | 1        | 1.09%   |
| Samsung RAM M3 78T2953EZ3-CE6 1GB DIMM DDR2 1331MT/s      | 1        | 1.09%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s     | 1        | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 31       | 40.26%  |
| DDR3    | 28       | 36.36%  |
| Unknown | 8        | 10.39%  |
| SDRAM   | 4        | 5.19%   |
| DDR2    | 3        | 3.9%    |
| DDR     | 2        | 2.6%    |
| DRAM    | 1        | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 70       | 90.91%  |
| SODIMM | 7        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 25       | 30.86%  |
| 8192  | 23       | 28.4%   |
| 16384 | 15       | 18.52%  |
| 2048  | 11       | 13.58%  |
| 32768 | 4        | 4.94%   |
| 1024  | 2        | 2.47%   |
| 512   | 1        | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 17       | 20%     |
| 1333    | 14       | 16.47%  |
| 2400    | 8        | 9.41%   |
| 3600    | 6        | 7.06%   |
| 3200    | 6        | 7.06%   |
| 2667    | 6        | 7.06%   |
| 2133    | 3        | 3.53%   |
| 667     | 3        | 3.53%   |
| Unknown | 3        | 3.53%   |
| 2666    | 2        | 2.35%   |
| 1867    | 2        | 2.35%   |
| 1800    | 2        | 2.35%   |
| 800     | 2        | 2.35%   |
| 3733    | 1        | 1.18%   |
| 3466    | 1        | 1.18%   |
| 3266    | 1        | 1.18%   |
| 3066    | 1        | 1.18%   |
| 3000    | 1        | 1.18%   |
| 2733    | 1        | 1.18%   |
| 2500    | 1        | 1.18%   |
| 2048    | 1        | 1.18%   |
| 1866    | 1        | 1.18%   |
| 1331    | 1        | 1.18%   |
| 400     | 1        | 1.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 3        | 50%     |
| Brother Industries | 2        | 33.33%  |
| Kyocera            | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| HP DeskJet 2130 series           | 2        | 33.33%  |
| Kyocera FS-1030D printer         | 1        | 16.67%  |
| HP LaserJet Professional P1606dn | 1        | 16.67%  |
| Brother MFC-J450DW               | 1        | 16.67%  |
| Brother HL-L2390DW               | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 110 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Logitech              | 11       | 44%     |
| Microdia              | 5        | 20%     |
| Realtek Semiconductor | 2        | 8%      |
| Lenovo                | 2        | 8%      |
| Sunplus IT            | 1        | 4%      |
| Samsung Electronics   | 1        | 4%      |
| Cubeternet            | 1        | 4%      |
| Creative Technology   | 1        | 4%      |
| Chicony Electronics   | 1        | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Logitech HD Webcam C615                     | 3        | 12%     |
| Logitech HD Pro Webcam C920                 | 3        | 12%     |
| Microdia Defender G-Lens 2577 HD720p Camera | 2        | 8%      |
| Microdia Camera                             | 2        | 8%      |
| Logitech Webcam C270                        | 2        | 8%      |
| Lenovo Lenovo FHD Webcam Audio              | 2        | 8%      |
| Sunplus IT PC Camera                        | 1        | 4%      |
| Samsung Galaxy series, misc. (MTP mode)     | 1        | 4%      |
| Realtek HD Camera                           | 1        | 4%      |
| Realtek FULL HD 1080P Webcam                | 1        | 4%      |
| Microdia USB 2.0 Camera                     | 1        | 4%      |
| Logitech Webcam C930e                       | 1        | 4%      |
| Logitech Webcam C210                        | 1        | 4%      |
| Logitech StreamCam                          | 1        | 4%      |
| Cubeternet USB2.0 Camera                    | 1        | 4%      |
| Creative Live! Cam Chat HD [VF0700/VF0790]  | 1        | 4%      |
| Chicony HP Integrated Webcam                | 1        | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Dell   | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Giesecke & Devrient | 2        | 50%     |
| SCM Microsystems    | 1        | 25%     |
| CHERRY              | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Giesecke & Devrient StarSign CUT S                     | 2        | 50%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 25%     |
| CHERRY SmartCard Reader Keyboard KC 1000 SC            | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 129      | 77.25%  |
| 1     | 31       | 18.56%  |
| 2     | 7        | 4.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 18       | 39.13%  |
| Unassigned class         | 7        | 15.22%  |
| Storage/ide              | 7        | 15.22%  |
| Net/wireless             | 5        | 10.87%  |
| Sound                    | 2        | 4.35%   |
| Network                  | 2        | 4.35%   |
| Communication controller | 2        | 4.35%   |
| Storage/ata              | 1        | 2.17%   |
| Net/ethernet             | 1        | 2.17%   |
| Dvb card                 | 1        | 2.17%   |

