Linux in Lithuania - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Lithuania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Lithuania/Desktop/README.md) and [notebooks](/Location/Lithuania/Notebook/README.md).

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

Total: 742

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [3cd4965210](https://linux-hardware.org/?probe=3cd4965210) | Jan 04, 2025 |
| MSI           | B450-A PRO                  | Desktop     | [fa8374d09c](https://linux-hardware.org/?probe=fa8374d09c) | Jan 01, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | Desktop     | [9ba5e6b3c0](https://linux-hardware.org/?probe=9ba5e6b3c0) | Dec 30, 2024 |
| HONOR         | HYM-WXX                     | Notebook    | [6b719e5c5d](https://linux-hardware.org/?probe=6b719e5c5d) | Dec 28, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [bbae43def0](https://linux-hardware.org/?probe=bbae43def0) | Dec 24, 2024 |
| Lenovo        | LOQ 15AHP9 83DX             | Notebook    | [c4d33f738c](https://linux-hardware.org/?probe=c4d33f738c) | Dec 22, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y2... | Notebook    | [b7ad8c7467](https://linux-hardware.org/?probe=b7ad8c7467) | Dec 21, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [ccdf904498](https://linux-hardware.org/?probe=ccdf904498) | Dec 20, 2024 |
| MSI           | Stealth 16 AI Studio A1V... | Notebook    | [ab7f87b6f5](https://linux-hardware.org/?probe=ab7f87b6f5) | Dec 16, 2024 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [1f398807de](https://linux-hardware.org/?probe=1f398807de) | Dec 12, 2024 |
| MSI           | H61M-P23                    | Desktop     | [4e730504db](https://linux-hardware.org/?probe=4e730504db) | Dec 06, 2024 |
| ASUSTek       | G751JT                      | Notebook    | [2bbcb36d29](https://linux-hardware.org/?probe=2bbcb36d29) | Dec 03, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [1fb7124f16](https://linux-hardware.org/?probe=1fb7124f16) | Dec 03, 2024 |
| ASUSTek       | X555LN                      | Notebook    | [8fe10d8894](https://linux-hardware.org/?probe=8fe10d8894) | Nov 30, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [58f0a1ff3a](https://linux-hardware.org/?probe=58f0a1ff3a) | Nov 30, 2024 |
| Dell          | Vostro 3578                 | Notebook    | [2490918f08](https://linux-hardware.org/?probe=2490918f08) | Nov 24, 2024 |
| Acer          | Aspire A515-48M             | Notebook    | [7e76e833e3](https://linux-hardware.org/?probe=7e76e833e3) | Nov 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [c3b63fd37e](https://linux-hardware.org/?probe=c3b63fd37e) | Nov 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [1caa8b41f8](https://linux-hardware.org/?probe=1caa8b41f8) | Nov 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [158bfeec61](https://linux-hardware.org/?probe=158bfeec61) | Nov 13, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [03d50f54b5](https://linux-hardware.org/?probe=03d50f54b5) | Nov 12, 2024 |
| Toshiba       | WT8-A                       | Notebook    | [e99f4125d4](https://linux-hardware.org/?probe=e99f4125d4) | Nov 10, 2024 |
| Acer          | Predator PH315-53           | Notebook    | [f1266330e4](https://linux-hardware.org/?probe=f1266330e4) | Nov 08, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [4690d07a14](https://linux-hardware.org/?probe=4690d07a14) | Nov 03, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ceeeb0ce3f](https://linux-hardware.org/?probe=ceeeb0ce3f) | Nov 01, 2024 |
| Lenovo        | ThinkPad T450 20BUS0H200    | Notebook    | [f2c4a96ba0](https://linux-hardware.org/?probe=f2c4a96ba0) | Nov 01, 2024 |
| Lenovo        | ThinkPad T450 20BUS0H200    | Notebook    | [c169540ec2](https://linux-hardware.org/?probe=c169540ec2) | Nov 01, 2024 |
| Dell          | Latitude 5580               | Notebook    | [5eb086f8c2](https://linux-hardware.org/?probe=5eb086f8c2) | Oct 28, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [954f4f20de](https://linux-hardware.org/?probe=954f4f20de) | Oct 28, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [08b6a5d7d3](https://linux-hardware.org/?probe=08b6a5d7d3) | Oct 26, 2024 |
| Lenovo        | ThinkPad T410s 291238G      | Notebook    | [7f94eafaf2](https://linux-hardware.org/?probe=7f94eafaf2) | Oct 25, 2024 |
| Lenovo        | ThinkPad T410s 291238G      | Notebook    | [20e158e9fb](https://linux-hardware.org/?probe=20e158e9fb) | Oct 25, 2024 |
| Dell          | Latitude E6420              | Notebook    | [62acf0960f](https://linux-hardware.org/?probe=62acf0960f) | Oct 13, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [1da2193371](https://linux-hardware.org/?probe=1da2193371) | Oct 12, 2024 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [0bfa5ff580](https://linux-hardware.org/?probe=0bfa5ff580) | Oct 08, 2024 |
| HP            | 805D                        | Desktop     | [9b68e25a8d](https://linux-hardware.org/?probe=9b68e25a8d) | Oct 02, 2024 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [e9bef43957](https://linux-hardware.org/?probe=e9bef43957) | Oct 02, 2024 |
| XIAOMI        | Redmi Book Pro 16 2024      | Notebook    | [0566eccc4c](https://linux-hardware.org/?probe=0566eccc4c) | Sep 29, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [27da4fdb75](https://linux-hardware.org/?probe=27da4fdb75) | Sep 26, 2024 |
| ASUSTek       | X555LN                      | Notebook    | [fc48a399c1](https://linux-hardware.org/?probe=fc48a399c1) | Sep 23, 2024 |
| ASUSTek       | M50Vn                       | Notebook    | [2e22fd3bd2](https://linux-hardware.org/?probe=2e22fd3bd2) | Sep 22, 2024 |
| ASUSTek       | X555LN                      | Notebook    | [acbf9d7e70](https://linux-hardware.org/?probe=acbf9d7e70) | Sep 12, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [144f86e54b](https://linux-hardware.org/?probe=144f86e54b) | Sep 07, 2024 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4S... | Notebook    | [f6500b9c01](https://linux-hardware.org/?probe=f6500b9c01) | Sep 06, 2024 |
| Toshiba       | WT8-A                       | Notebook    | [427fe42ea1](https://linux-hardware.org/?probe=427fe42ea1) | Aug 30, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [bd4a519cc3](https://linux-hardware.org/?probe=bd4a519cc3) | Aug 26, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [69ab889544](https://linux-hardware.org/?probe=69ab889544) | Aug 26, 2024 |
| Lenovo        | Z710 20250                  | Notebook    | [b199061083](https://linux-hardware.org/?probe=b199061083) | Aug 25, 2024 |
| Lenovo        | Z710 20250                  | Notebook    | [4f5bbb6201](https://linux-hardware.org/?probe=4f5bbb6201) | Aug 25, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [550fd81be0](https://linux-hardware.org/?probe=550fd81be0) | Aug 23, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [5171e2cc88](https://linux-hardware.org/?probe=5171e2cc88) | Aug 22, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b543fa8dec](https://linux-hardware.org/?probe=b543fa8dec) | Aug 17, 2024 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [8ead28af74](https://linux-hardware.org/?probe=8ead28af74) | Aug 07, 2024 |
| ASUSTek       | X555LN                      | Notebook    | [f1bf5f5504](https://linux-hardware.org/?probe=f1bf5f5504) | Aug 06, 2024 |
| Lenovo        | IdeaPad Z580                | Notebook    | [cb672c1d21](https://linux-hardware.org/?probe=cb672c1d21) | Aug 05, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [520f0fd81e](https://linux-hardware.org/?probe=520f0fd81e) | Aug 02, 2024 |
| Dell          | Vostro 5490                 | Notebook    | [8582fd1c71](https://linux-hardware.org/?probe=8582fd1c71) | Aug 01, 2024 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [df893fa78f](https://linux-hardware.org/?probe=df893fa78f) | Jul 30, 2024 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [010cf4260e](https://linux-hardware.org/?probe=010cf4260e) | Jul 30, 2024 |
| ASUSTek       | GL552VX                     | Notebook    | [a54d8753e5](https://linux-hardware.org/?probe=a54d8753e5) | Jul 28, 2024 |
| HP            | Pavilion g6                 | Notebook    | [8d4cd1cce3](https://linux-hardware.org/?probe=8d4cd1cce3) | Jul 25, 2024 |
| ASUSTek       | X555LN                      | Notebook    | [c97fa10f61](https://linux-hardware.org/?probe=c97fa10f61) | Jul 14, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a89abcf2b8](https://linux-hardware.org/?probe=a89abcf2b8) | Jul 13, 2024 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7b6bf257b9](https://linux-hardware.org/?probe=7b6bf257b9) | Jul 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [111614cf4c](https://linux-hardware.org/?probe=111614cf4c) | Jul 08, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [647ca9ecb0](https://linux-hardware.org/?probe=647ca9ecb0) | Jul 04, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [b2c03fc0a5](https://linux-hardware.org/?probe=b2c03fc0a5) | Jun 18, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [110790c81a](https://linux-hardware.org/?probe=110790c81a) | Jun 14, 2024 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [ed148c6672](https://linux-hardware.org/?probe=ed148c6672) | Jun 09, 2024 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [46b02b8b55](https://linux-hardware.org/?probe=46b02b8b55) | Jun 08, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6f98b9d085](https://linux-hardware.org/?probe=6f98b9d085) | Jun 08, 2024 |
| Lenovo        | G560 20042                  | Notebook    | [3cf1e98f3b](https://linux-hardware.org/?probe=3cf1e98f3b) | Jun 06, 2024 |
| Prestigio     | PSB141C03                   | Notebook    | [c7612dfd34](https://linux-hardware.org/?probe=c7612dfd34) | Jun 03, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [0707d81b82](https://linux-hardware.org/?probe=0707d81b82) | Jun 03, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [d9d57e90a2](https://linux-hardware.org/?probe=d9d57e90a2) | Jun 03, 2024 |
| Jumper        | EZbook                      | Convertible | [f68fd52a56](https://linux-hardware.org/?probe=f68fd52a56) | Jun 02, 2024 |
| Jumper        | EZbook                      | Convertible | [10ae45e84e](https://linux-hardware.org/?probe=10ae45e84e) | Jun 02, 2024 |
| Nvidia        | Tegra                       | Soc         | [6cf4a3e280](https://linux-hardware.org/?probe=6cf4a3e280) | May 30, 2024 |
| Dell          | Latitude 5540               | Notebook    | [dba27825e6](https://linux-hardware.org/?probe=dba27825e6) | May 29, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [803cb92786](https://linux-hardware.org/?probe=803cb92786) | May 29, 2024 |
| Dell          | Latitude 5540               | Notebook    | [aa8fd65cf6](https://linux-hardware.org/?probe=aa8fd65cf6) | May 29, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [50e4cb18c3](https://linux-hardware.org/?probe=50e4cb18c3) | May 23, 2024 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [58a45e4ab3](https://linux-hardware.org/?probe=58a45e4ab3) | May 21, 2024 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [e2d7993d49](https://linux-hardware.org/?probe=e2d7993d49) | May 20, 2024 |
| ASUSTek       | X556UQ                      | Notebook    | [54473bca57](https://linux-hardware.org/?probe=54473bca57) | May 20, 2024 |
| HP            | 0AECh D                     | Desktop     | [7173a4bf88](https://linux-hardware.org/?probe=7173a4bf88) | May 18, 2024 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [4301eba9f0](https://linux-hardware.org/?probe=4301eba9f0) | May 17, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [204a955e18](https://linux-hardware.org/?probe=204a955e18) | May 17, 2024 |
| Dell          | 0F96C8 A00                  | All in one  | [dae277f71d](https://linux-hardware.org/?probe=dae277f71d) | May 03, 2024 |
| ASUSTek       | K53E                        | Notebook    | [2c14a21fe8](https://linux-hardware.org/?probe=2c14a21fe8) | May 02, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [077d8caca8](https://linux-hardware.org/?probe=077d8caca8) | Apr 22, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [1e07f3fb8f](https://linux-hardware.org/?probe=1e07f3fb8f) | Apr 22, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [909681165a](https://linux-hardware.org/?probe=909681165a) | Apr 22, 2024 |
| ASUSTek       | P9X79                       | Desktop     | [f5f0955b10](https://linux-hardware.org/?probe=f5f0955b10) | Apr 20, 2024 |
| ASRock        | B760M Pro RS                | Desktop     | [ba1fde2d8b](https://linux-hardware.org/?probe=ba1fde2d8b) | Apr 17, 2024 |
| Acer          | Aspire E5-771G              | Notebook    | [752982118a](https://linux-hardware.org/?probe=752982118a) | Apr 09, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [c6e809a3fa](https://linux-hardware.org/?probe=c6e809a3fa) | Apr 08, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [3e60ae1de4](https://linux-hardware.org/?probe=3e60ae1de4) | Apr 08, 2024 |
| Maibenben     | MaiBook X series            | Notebook    | [44a21e3fc3](https://linux-hardware.org/?probe=44a21e3fc3) | Apr 05, 2024 |
| ASUSTek       | K53E                        | Notebook    | [0564fa09ec](https://linux-hardware.org/?probe=0564fa09ec) | Apr 05, 2024 |
| Rockchip      | Orange Pi 5                 | Soc         | [0bc6342638](https://linux-hardware.org/?probe=0bc6342638) | Apr 02, 2024 |
| Lenovo        | ThinkPad T470 20HD0001MH    | Notebook    | [5999aa3b46](https://linux-hardware.org/?probe=5999aa3b46) | Mar 26, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [98f3a35dbb](https://linux-hardware.org/?probe=98f3a35dbb) | Mar 24, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [bdd0b87420](https://linux-hardware.org/?probe=bdd0b87420) | Mar 19, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [33164bcce1](https://linux-hardware.org/?probe=33164bcce1) | Mar 14, 2024 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [30345806ba](https://linux-hardware.org/?probe=30345806ba) | Mar 11, 2024 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [cdc8c121ad](https://linux-hardware.org/?probe=cdc8c121ad) | Mar 09, 2024 |
| HP            | 8950                        | Desktop     | [ee925d29a1](https://linux-hardware.org/?probe=ee925d29a1) | Mar 08, 2024 |
| HP            | 8950                        | Desktop     | [f2b8f96540](https://linux-hardware.org/?probe=f2b8f96540) | Mar 08, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [95f6ca3672](https://linux-hardware.org/?probe=95f6ca3672) | Mar 04, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [0304104a60](https://linux-hardware.org/?probe=0304104a60) | Mar 03, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [336cabac77](https://linux-hardware.org/?probe=336cabac77) | Mar 02, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [f4f2d5a42e](https://linux-hardware.org/?probe=f4f2d5a42e) | Feb 28, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [a8565459dd](https://linux-hardware.org/?probe=a8565459dd) | Feb 28, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [9a57de6e15](https://linux-hardware.org/?probe=9a57de6e15) | Feb 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [46c0e99842](https://linux-hardware.org/?probe=46c0e99842) | Feb 27, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7167de20ce](https://linux-hardware.org/?probe=7167de20ce) | Feb 27, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [40fbd1acd6](https://linux-hardware.org/?probe=40fbd1acd6) | Feb 06, 2024 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [ce905760f2](https://linux-hardware.org/?probe=ce905760f2) | Jan 31, 2024 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [99e8a768ca](https://linux-hardware.org/?probe=99e8a768ca) | Jan 30, 2024 |
| AMI           | Intel                       | Desktop     | [5085eba8b2](https://linux-hardware.org/?probe=5085eba8b2) | Jan 23, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [0833d2c5c5](https://linux-hardware.org/?probe=0833d2c5c5) | Jan 22, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [adb9343764](https://linux-hardware.org/?probe=adb9343764) | Jan 16, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [cb33073a09](https://linux-hardware.org/?probe=cb33073a09) | Jan 15, 2024 |
| ASRock        | B760M Pro RS                | Desktop     | [34ecc17795](https://linux-hardware.org/?probe=34ecc17795) | Jan 10, 2024 |
| MSI           | PRO H610M-B DDR4            | Notebook    | [fa4ed3c75c](https://linux-hardware.org/?probe=fa4ed3c75c) | Jan 10, 2024 |
| HP            | Pavilion dv6                | Notebook    | [39515c70db](https://linux-hardware.org/?probe=39515c70db) | Dec 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c29956a752](https://linux-hardware.org/?probe=c29956a752) | Dec 27, 2023 |
| HP            | Pavilion g6                 | Notebook    | [62a002d063](https://linux-hardware.org/?probe=62a002d063) | Dec 26, 2023 |
| ASRock        | B760M Pro RS                | Desktop     | [f648cda96d](https://linux-hardware.org/?probe=f648cda96d) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5a16e00d6c](https://linux-hardware.org/?probe=5a16e00d6c) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [262bfe0585](https://linux-hardware.org/?probe=262bfe0585) | Dec 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [fbe4d2ec54](https://linux-hardware.org/?probe=fbe4d2ec54) | Dec 08, 2023 |
| ASRock        | B760M Pro RS                | Desktop     | [77b3b5fc4d](https://linux-hardware.org/?probe=77b3b5fc4d) | Dec 07, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [f60bc8a984](https://linux-hardware.org/?probe=f60bc8a984) | Dec 03, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [ec97e6b200](https://linux-hardware.org/?probe=ec97e6b200) | Dec 02, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [f03f814b9c](https://linux-hardware.org/?probe=f03f814b9c) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [aaccb61f12](https://linux-hardware.org/?probe=aaccb61f12) | Nov 24, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [f5ced375d8](https://linux-hardware.org/?probe=f5ced375d8) | Nov 17, 2023 |
| ASUSTek       | M50Vn                       | Notebook    | [9c35898e36](https://linux-hardware.org/?probe=9c35898e36) | Nov 16, 2023 |
| HP            | Mini 110-4100               | Notebook    | [a7aaa77ba5](https://linux-hardware.org/?probe=a7aaa77ba5) | Nov 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3281df4dcd](https://linux-hardware.org/?probe=3281df4dcd) | Nov 15, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [81fb4db1cc](https://linux-hardware.org/?probe=81fb4db1cc) | Nov 15, 2023 |
| Acer          | Extensa 5620                | Notebook    | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [f212dcca29](https://linux-hardware.org/?probe=f212dcca29) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [49b3b70e38](https://linux-hardware.org/?probe=49b3b70e38) | Nov 07, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [b153378dab](https://linux-hardware.org/?probe=b153378dab) | Nov 06, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [c7d2d860fb](https://linux-hardware.org/?probe=c7d2d860fb) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [6e619afdba](https://linux-hardware.org/?probe=6e619afdba) | Oct 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7f2d93dc09](https://linux-hardware.org/?probe=7f2d93dc09) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f59a3c2021](https://linux-hardware.org/?probe=f59a3c2021) | Oct 25, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a368ef3766](https://linux-hardware.org/?probe=a368ef3766) | Oct 22, 2023 |
| Samsung       | R530/R730/P530              | Notebook    | [ba506f75d1](https://linux-hardware.org/?probe=ba506f75d1) | Oct 21, 2023 |
| MSI           | H81M-P33                    | Desktop     | [04b9d686b6](https://linux-hardware.org/?probe=04b9d686b6) | Oct 21, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [6bd80595bd](https://linux-hardware.org/?probe=6bd80595bd) | Oct 19, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [3d62b547f3](https://linux-hardware.org/?probe=3d62b547f3) | Oct 16, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [02211f49db](https://linux-hardware.org/?probe=02211f49db) | Oct 08, 2023 |
| Lenovo        | ThinkPad T450 20BUS0H200    | Notebook    | [c38151f281](https://linux-hardware.org/?probe=c38151f281) | Sep 20, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [87f5275af6](https://linux-hardware.org/?probe=87f5275af6) | Sep 18, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [faddcc51a7](https://linux-hardware.org/?probe=faddcc51a7) | Sep 17, 2023 |
| HP            | 829A                        | Mini pc     | [204c5a2a04](https://linux-hardware.org/?probe=204c5a2a04) | Sep 13, 2023 |
| LIVEFAN       | Unknown                     | Notebook    | [102a13c2c5](https://linux-hardware.org/?probe=102a13c2c5) | Sep 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [820eeccddf](https://linux-hardware.org/?probe=820eeccddf) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b52a6f9b59](https://linux-hardware.org/?probe=b52a6f9b59) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8b6b039242](https://linux-hardware.org/?probe=8b6b039242) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [cdabed6210](https://linux-hardware.org/?probe=cdabed6210) | Sep 05, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [0309bcca29](https://linux-hardware.org/?probe=0309bcca29) | Sep 05, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [8d2e359aec](https://linux-hardware.org/?probe=8d2e359aec) | Sep 03, 2023 |
| Intel         | D915GAV AAC64134-400        | Desktop     | [c7cad9e093](https://linux-hardware.org/?probe=c7cad9e093) | Aug 20, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [009242b925](https://linux-hardware.org/?probe=009242b925) | Aug 13, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| HP            | Presario CQ57               | Notebook    | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [079428c572](https://linux-hardware.org/?probe=079428c572) | Aug 05, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [663f989185](https://linux-hardware.org/?probe=663f989185) | Aug 05, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| Acer          | Aspire xxxx                 | Notebook    | [8bc8edb11c](https://linux-hardware.org/?probe=8bc8edb11c) | Aug 03, 2023 |
| Dell          | G5 5590                     | Notebook    | [2745b35776](https://linux-hardware.org/?probe=2745b35776) | Jul 29, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [73f0811a7b](https://linux-hardware.org/?probe=73f0811a7b) | Jul 23, 2023 |
| Dell          | Latitude E7250              | Notebook    | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [2f730cccf1](https://linux-hardware.org/?probe=2f730cccf1) | Jul 18, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [d32668cf0c](https://linux-hardware.org/?probe=d32668cf0c) | Jul 15, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [0dbf02ef16](https://linux-hardware.org/?probe=0dbf02ef16) | Jul 13, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [6eb4d71389](https://linux-hardware.org/?probe=6eb4d71389) | Jul 10, 2023 |
| Alienware     | 17                          | Notebook    | [90e6911a60](https://linux-hardware.org/?probe=90e6911a60) | Jul 09, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [8a5cbee239](https://linux-hardware.org/?probe=8a5cbee239) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f1b70e168](https://linux-hardware.org/?probe=2f1b70e168) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [282c9db256](https://linux-hardware.org/?probe=282c9db256) | Jul 08, 2023 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [0b81f2e9b0](https://linux-hardware.org/?probe=0b81f2e9b0) | Jul 07, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [d487f9f635](https://linux-hardware.org/?probe=d487f9f635) | Jul 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [d62c8c81d4](https://linux-hardware.org/?probe=d62c8c81d4) | Jul 04, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [97b1fc630a](https://linux-hardware.org/?probe=97b1fc630a) | Jun 25, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [1773c81302](https://linux-hardware.org/?probe=1773c81302) | Jun 23, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [80b535ff26](https://linux-hardware.org/?probe=80b535ff26) | Jun 23, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | G50V                        | Notebook    | [32048be4b5](https://linux-hardware.org/?probe=32048be4b5) | Jun 16, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [e2919326cd](https://linux-hardware.org/?probe=e2919326cd) | Jun 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [c5accf4cf8](https://linux-hardware.org/?probe=c5accf4cf8) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [45e51a6b5d](https://linux-hardware.org/?probe=45e51a6b5d) | Jun 09, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [79bb8d8e39](https://linux-hardware.org/?probe=79bb8d8e39) | Jun 08, 2023 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [bdf4ee4d4f](https://linux-hardware.org/?probe=bdf4ee4d4f) | Jun 04, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [72ccbe10aa](https://linux-hardware.org/?probe=72ccbe10aa) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d2189d4a5f](https://linux-hardware.org/?probe=d2189d4a5f) | Jun 02, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ea2d944708](https://linux-hardware.org/?probe=ea2d944708) | Jun 01, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [f9995cb422](https://linux-hardware.org/?probe=f9995cb422) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [230a02bfda](https://linux-hardware.org/?probe=230a02bfda) | May 29, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [0e9ccef97f](https://linux-hardware.org/?probe=0e9ccef97f) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [767c697ac8](https://linux-hardware.org/?probe=767c697ac8) | May 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [0f593c947e](https://linux-hardware.org/?probe=0f593c947e) | May 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [e7a8d68439](https://linux-hardware.org/?probe=e7a8d68439) | May 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f7beed595](https://linux-hardware.org/?probe=3f7beed595) | May 25, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fff0e981f2](https://linux-hardware.org/?probe=fff0e981f2) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [da9ebc680a](https://linux-hardware.org/?probe=da9ebc680a) | May 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8933c29ce](https://linux-hardware.org/?probe=b8933c29ce) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [db7e2a1d87](https://linux-hardware.org/?probe=db7e2a1d87) | Apr 29, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| HUAWEI        | MRGF-XX                     | Notebook    | [25233eb8d1](https://linux-hardware.org/?probe=25233eb8d1) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [517662dd54](https://linux-hardware.org/?probe=517662dd54) | Apr 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [083aef9e64](https://linux-hardware.org/?probe=083aef9e64) | Apr 20, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [8957c4fdd0](https://linux-hardware.org/?probe=8957c4fdd0) | Apr 19, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [27df270817](https://linux-hardware.org/?probe=27df270817) | Apr 09, 2023 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [ea2ee391a5](https://linux-hardware.org/?probe=ea2ee391a5) | Apr 07, 2023 |
| Lenovo        | ThinkPad E470 20H1006VRT    | Notebook    | [a9b909f3df](https://linux-hardware.org/?probe=a9b909f3df) | Apr 05, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e13bc4c0b8](https://linux-hardware.org/?probe=e13bc4c0b8) | Apr 04, 2023 |
| Notebook      | L140CU                      | Notebook    | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Notebook      | L140CU                      | Notebook    | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [c1f3b9658c](https://linux-hardware.org/?probe=c1f3b9658c) | Mar 26, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [3f74c992e7](https://linux-hardware.org/?probe=3f74c992e7) | Mar 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| HP            | 1825                        | Desktop     | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [ba879b76da](https://linux-hardware.org/?probe=ba879b76da) | Mar 19, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [547559d982](https://linux-hardware.org/?probe=547559d982) | Mar 19, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| MSI           | GT72 2PE                    | Notebook    | [0483315836](https://linux-hardware.org/?probe=0483315836) | Mar 16, 2023 |
| ASUSTek       | N61Jq                       | Notebook    | [706eca5e8a](https://linux-hardware.org/?probe=706eca5e8a) | Mar 15, 2023 |
| HP            | 1850                        | Desktop     | [1b56ff36d2](https://linux-hardware.org/?probe=1b56ff36d2) | Mar 10, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [b4046bce15](https://linux-hardware.org/?probe=b4046bce15) | Mar 10, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [cbdc8bcd6a](https://linux-hardware.org/?probe=cbdc8bcd6a) | Mar 06, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| ASRock        | H67M-GE/HT                  | Desktop     | [3410887193](https://linux-hardware.org/?probe=3410887193) | Feb 25, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [7933746ce1](https://linux-hardware.org/?probe=7933746ce1) | Feb 17, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [8ba717ec45](https://linux-hardware.org/?probe=8ba717ec45) | Feb 13, 2023 |
| Gigabyte      | GB-BSi5-1135G7              | Desktop     | [93002e901f](https://linux-hardware.org/?probe=93002e901f) | Feb 10, 2023 |
| MSI           | H61M-P23                    | Desktop     | [86404b5b68](https://linux-hardware.org/?probe=86404b5b68) | Feb 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [a3a0a3a505](https://linux-hardware.org/?probe=a3a0a3a505) | Jan 25, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [d196ac82e2](https://linux-hardware.org/?probe=d196ac82e2) | Jan 23, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [bd51c2a953](https://linux-hardware.org/?probe=bd51c2a953) | Jan 20, 2023 |
| MSI           | GP70 2PE                    | Notebook    | [697974aa68](https://linux-hardware.org/?probe=697974aa68) | Jan 08, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [10ae4cbb25](https://linux-hardware.org/?probe=10ae4cbb25) | Jan 08, 2023 |
| HP            | ProBook 450 G0              | Notebook    | [e7af660f1a](https://linux-hardware.org/?probe=e7af660f1a) | Jan 05, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [196d64e793](https://linux-hardware.org/?probe=196d64e793) | Dec 25, 2022 |
| Acer          | Iconia Tab W501             | Tablet      | [32f9cc7e0b](https://linux-hardware.org/?probe=32f9cc7e0b) | Dec 25, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [11fe73ea9d](https://linux-hardware.org/?probe=11fe73ea9d) | Dec 11, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [7a6ba7238f](https://linux-hardware.org/?probe=7a6ba7238f) | Dec 08, 2022 |
| Dell          | Vostro 5502                 | Notebook    | [862097a47c](https://linux-hardware.org/?probe=862097a47c) | Dec 05, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [b7ff70b9b2](https://linux-hardware.org/?probe=b7ff70b9b2) | Nov 14, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f6bfbc00ba](https://linux-hardware.org/?probe=f6bfbc00ba) | Nov 14, 2022 |
| HP            | 3397                        | Desktop     | [27c0a5213d](https://linux-hardware.org/?probe=27c0a5213d) | Nov 11, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [bdca860f08](https://linux-hardware.org/?probe=bdca860f08) | Nov 06, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [8598cf3c36](https://linux-hardware.org/?probe=8598cf3c36) | Nov 04, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [496a16216c](https://linux-hardware.org/?probe=496a16216c) | Nov 02, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | Desktop     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f38198e874](https://linux-hardware.org/?probe=f38198e874) | Oct 23, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| HP            | 3047h                       | Desktop     | [1a0f4c46f9](https://linux-hardware.org/?probe=1a0f4c46f9) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| Dell          | G3 3579                     | Notebook    | [2191706dd0](https://linux-hardware.org/?probe=2191706dd0) | Oct 11, 2022 |
| Dell          | G3 3579                     | Notebook    | [7f20851840](https://linux-hardware.org/?probe=7f20851840) | Oct 10, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| Dell          | 0F96C8 A00                  | All in one  | [5b19e47aa9](https://linux-hardware.org/?probe=5b19e47aa9) | Oct 03, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [258d99cc9e](https://linux-hardware.org/?probe=258d99cc9e) | Sep 06, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [5ee4e3aec0](https://linux-hardware.org/?probe=5ee4e3aec0) | Sep 02, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| HP            | ProBook 440 G3              | Notebook    | [e51d4ae241](https://linux-hardware.org/?probe=e51d4ae241) | Aug 20, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| Lenovo        | ThinkPad T590 20N4004EMH    | Notebook    | [42d130e184](https://linux-hardware.org/?probe=42d130e184) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [6440e9a054](https://linux-hardware.org/?probe=6440e9a054) | Aug 12, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [063c2efc80](https://linux-hardware.org/?probe=063c2efc80) | Aug 12, 2022 |
| MSI           | MS-16F1                     | Notebook    | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [f3a7c88015](https://linux-hardware.org/?probe=f3a7c88015) | Aug 11, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | Notebook    | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| Dell          | 07T4MC A11                  | Desktop     | [61d394116d](https://linux-hardware.org/?probe=61d394116d) | Jul 20, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| eMachines     | eME443                      | Notebook    | [9197e8ef17](https://linux-hardware.org/?probe=9197e8ef17) | Jul 11, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a6420a89b6](https://linux-hardware.org/?probe=a6420a89b6) | Jun 29, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f23b75e3ca](https://linux-hardware.org/?probe=f23b75e3ca) | Jun 19, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [8f2740e70e](https://linux-hardware.org/?probe=8f2740e70e) | Jun 18, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [0d78267c59](https://linux-hardware.org/?probe=0d78267c59) | Jun 16, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [bd3336efcb](https://linux-hardware.org/?probe=bd3336efcb) | Jun 14, 2022 |
| Panasonic     | CF-52VDA131M                | Notebook    | [aa40370193](https://linux-hardware.org/?probe=aa40370193) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [310aadd79a](https://linux-hardware.org/?probe=310aadd79a) | May 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [a068dc57c8](https://linux-hardware.org/?probe=a068dc57c8) | May 13, 2022 |
| Dell          | 0F96C8 A00                  | All in one  | [b0e5c67fda](https://linux-hardware.org/?probe=b0e5c67fda) | May 11, 2022 |
| Alienware     | 17                          | Notebook    | [b30786ba0e](https://linux-hardware.org/?probe=b30786ba0e) | May 10, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [96f6c5bf2a](https://linux-hardware.org/?probe=96f6c5bf2a) | May 10, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [3e171a4858](https://linux-hardware.org/?probe=3e171a4858) | May 09, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9e90322621](https://linux-hardware.org/?probe=9e90322621) | May 06, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [08e665f8bf](https://linux-hardware.org/?probe=08e665f8bf) | May 04, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [96fc510369](https://linux-hardware.org/?probe=96fc510369) | Apr 29, 2022 |
| Dell          | Latitude 5401               | Notebook    | [d115db916d](https://linux-hardware.org/?probe=d115db916d) | Apr 23, 2022 |
| Dell          | Latitude 5401               | Notebook    | [c9f380ea26](https://linux-hardware.org/?probe=c9f380ea26) | Apr 23, 2022 |
| ASUSTek       | X55A                        | Notebook    | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [a3bf1cf766](https://linux-hardware.org/?probe=a3bf1cf766) | Apr 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [f2e4d7052d](https://linux-hardware.org/?probe=f2e4d7052d) | Apr 16, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8ba327aee7](https://linux-hardware.org/?probe=8ba327aee7) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| ASUSTek       | X55A                        | Notebook    | [9b02d587bf](https://linux-hardware.org/?probe=9b02d587bf) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5d0113f42d](https://linux-hardware.org/?probe=5d0113f42d) | Mar 16, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [c6ad6edf70](https://linux-hardware.org/?probe=c6ad6edf70) | Mar 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4b0c952d9b](https://linux-hardware.org/?probe=4b0c952d9b) | Mar 09, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [573ff5a0d0](https://linux-hardware.org/?probe=573ff5a0d0) | Feb 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [54f55cc209](https://linux-hardware.org/?probe=54f55cc209) | Feb 16, 2022 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [12a1b54a3a](https://linux-hardware.org/?probe=12a1b54a3a) | Feb 16, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [130c778a64](https://linux-hardware.org/?probe=130c778a64) | Feb 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| ASUSTek       | X55A                        | Notebook    | [dbbb7b1213](https://linux-hardware.org/?probe=dbbb7b1213) | Feb 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5616230c16](https://linux-hardware.org/?probe=5616230c16) | Feb 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a7d1f29451](https://linux-hardware.org/?probe=a7d1f29451) | Jan 31, 2022 |
| Jumper        | EZbook                      | Notebook    | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [8f6a587ed3](https://linux-hardware.org/?probe=8f6a587ed3) | Jan 20, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [a5b43fd8b4](https://linux-hardware.org/?probe=a5b43fd8b4) | Jan 05, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [8e0b4fec6c](https://linux-hardware.org/?probe=8e0b4fec6c) | Dec 26, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d824937c84](https://linux-hardware.org/?probe=d824937c84) | Dec 22, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [1252e4adb0](https://linux-hardware.org/?probe=1252e4adb0) | Dec 18, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [113924cdba](https://linux-hardware.org/?probe=113924cdba) | Dec 12, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [bc5923cefe](https://linux-hardware.org/?probe=bc5923cefe) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [f8ed9dbcf4](https://linux-hardware.org/?probe=f8ed9dbcf4) | Dec 04, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [cc0c8de988](https://linux-hardware.org/?probe=cc0c8de988) | Nov 27, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [557bb216fc](https://linux-hardware.org/?probe=557bb216fc) | Nov 20, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [2f5b5e4c72](https://linux-hardware.org/?probe=2f5b5e4c72) | Nov 19, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [d998144d2e](https://linux-hardware.org/?probe=d998144d2e) | Nov 18, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [1907e644a0](https://linux-hardware.org/?probe=1907e644a0) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [3119a05196](https://linux-hardware.org/?probe=3119a05196) | Nov 15, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b1edada81b](https://linux-hardware.org/?probe=b1edada81b) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [b455b4457c](https://linux-hardware.org/?probe=b455b4457c) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| ASUSTek       | X55A                        | Notebook    | [a55961748f](https://linux-hardware.org/?probe=a55961748f) | Nov 10, 2021 |
| ASUSTek       | X55A                        | Notebook    | [8c59513ced](https://linux-hardware.org/?probe=8c59513ced) | Nov 10, 2021 |
| ASUSTek       | K52F                        | Notebook    | [f90cbb4d26](https://linux-hardware.org/?probe=f90cbb4d26) | Nov 04, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [fe22676441](https://linux-hardware.org/?probe=fe22676441) | Nov 03, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [54e81a5d8d](https://linux-hardware.org/?probe=54e81a5d8d) | Nov 02, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3adcb9ecf9](https://linux-hardware.org/?probe=3adcb9ecf9) | Oct 26, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [1876547e8e](https://linux-hardware.org/?probe=1876547e8e) | Oct 25, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [078863a9b7](https://linux-hardware.org/?probe=078863a9b7) | Oct 25, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [7b9e7ec5f4](https://linux-hardware.org/?probe=7b9e7ec5f4) | Oct 23, 2021 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [55468e657e](https://linux-hardware.org/?probe=55468e657e) | Oct 16, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [c49552f889](https://linux-hardware.org/?probe=c49552f889) | Oct 14, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [d606b23e02](https://linux-hardware.org/?probe=d606b23e02) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [5db12e2534](https://linux-hardware.org/?probe=5db12e2534) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [239dced9a1](https://linux-hardware.org/?probe=239dced9a1) | Sep 19, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [4db5d51b06](https://linux-hardware.org/?probe=4db5d51b06) | Sep 17, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [34c7038f6f](https://linux-hardware.org/?probe=34c7038f6f) | Sep 12, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [6c5f2b8c6d](https://linux-hardware.org/?probe=6c5f2b8c6d) | Sep 11, 2021 |
| HP            | 250 G4                      | Notebook    | [6c66581e62](https://linux-hardware.org/?probe=6c66581e62) | Sep 06, 2021 |
| HP            | 09F8h                       | Desktop     | [60e1a81b56](https://linux-hardware.org/?probe=60e1a81b56) | Sep 05, 2021 |
| HP            | 250 G4                      | Notebook    | [619fff9116](https://linux-hardware.org/?probe=619fff9116) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [057cfec49e](https://linux-hardware.org/?probe=057cfec49e) | Sep 01, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [626023b280](https://linux-hardware.org/?probe=626023b280) | Aug 24, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [523f5ca193](https://linux-hardware.org/?probe=523f5ca193) | Aug 23, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [9e64453373](https://linux-hardware.org/?probe=9e64453373) | Aug 23, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [90e24e0335](https://linux-hardware.org/?probe=90e24e0335) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1c59d4f975](https://linux-hardware.org/?probe=1c59d4f975) | Aug 19, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [c358dfd2e6](https://linux-hardware.org/?probe=c358dfd2e6) | Aug 18, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | Desktop     | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| HP            | Pavilion dv7                | Notebook    | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5d33b12497](https://linux-hardware.org/?probe=5d33b12497) | Aug 13, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [652f1a31e9](https://linux-hardware.org/?probe=652f1a31e9) | Aug 10, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [80648f256b](https://linux-hardware.org/?probe=80648f256b) | Aug 10, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| HP            | 250 G4                      | Notebook    | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4752d9cb90](https://linux-hardware.org/?probe=4752d9cb90) | Aug 01, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [ffde05f551](https://linux-hardware.org/?probe=ffde05f551) | Aug 01, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [ee3189a7be](https://linux-hardware.org/?probe=ee3189a7be) | Jul 11, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [714a2fb6ec](https://linux-hardware.org/?probe=714a2fb6ec) | Jul 02, 2021 |
| Gigabyte      | P41-ES3G                    | Desktop     | [653a634621](https://linux-hardware.org/?probe=653a634621) | Jun 29, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e78af672d3](https://linux-hardware.org/?probe=e78af672d3) | Jun 18, 2021 |
| Alienware     | 17                          | Notebook    | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4020e881a1](https://linux-hardware.org/?probe=4020e881a1) | Jun 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7fa170e5ca](https://linux-hardware.org/?probe=7fa170e5ca) | Jun 10, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [45b678cc45](https://linux-hardware.org/?probe=45b678cc45) | Jun 07, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [dab115ff9f](https://linux-hardware.org/?probe=dab115ff9f) | Jun 07, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [63b5d9a81a](https://linux-hardware.org/?probe=63b5d9a81a) | Jun 05, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [56308999d2](https://linux-hardware.org/?probe=56308999d2) | Jun 05, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [20b885e70c](https://linux-hardware.org/?probe=20b885e70c) | Jun 01, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [74979cf76a](https://linux-hardware.org/?probe=74979cf76a) | Jun 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [92db46133f](https://linux-hardware.org/?probe=92db46133f) | May 24, 2021 |
| Dell          | Precision M4700             | Notebook    | [1d14e22fbd](https://linux-hardware.org/?probe=1d14e22fbd) | May 22, 2021 |
| Dell          | Inspiron 5579               | Notebook    | [83c30b9084](https://linux-hardware.org/?probe=83c30b9084) | May 15, 2021 |
| MSI           | H81M-P33                    | Desktop     | [ab8a093d72](https://linux-hardware.org/?probe=ab8a093d72) | May 12, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [84b8a6331d](https://linux-hardware.org/?probe=84b8a6331d) | May 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [49aad4b320](https://linux-hardware.org/?probe=49aad4b320) | May 04, 2021 |
| Gigabyte      | M55S-S3                     | Desktop     | [7114f9857a](https://linux-hardware.org/?probe=7114f9857a) | Apr 29, 2021 |
| Lenovo        | ThinkPad P53 20QN0034MH     | Notebook    | [bcb2272cf0](https://linux-hardware.org/?probe=bcb2272cf0) | Apr 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [26133ce35a](https://linux-hardware.org/?probe=26133ce35a) | Apr 24, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [dc665ba00d](https://linux-hardware.org/?probe=dc665ba00d) | Apr 14, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [1e30c2850c](https://linux-hardware.org/?probe=1e30c2850c) | Apr 09, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [499ccddfc2](https://linux-hardware.org/?probe=499ccddfc2) | Apr 09, 2021 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [faca4e4038](https://linux-hardware.org/?probe=faca4e4038) | Apr 08, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [f7341fd5b2](https://linux-hardware.org/?probe=f7341fd5b2) | Apr 01, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [feedaccb5b](https://linux-hardware.org/?probe=feedaccb5b) | Mar 24, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| HP            | 805A                        | Desktop     | [76ad927d3b](https://linux-hardware.org/?probe=76ad927d3b) | Mar 18, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [ad58858e33](https://linux-hardware.org/?probe=ad58858e33) | Mar 17, 2021 |
| ASUSTek       | K50C                        | Notebook    | [4ccd0463c4](https://linux-hardware.org/?probe=4ccd0463c4) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480 20L50002MH    | Notebook    | [554173e0d7](https://linux-hardware.org/?probe=554173e0d7) | Mar 17, 2021 |
| ASUSTek       | K50C                        | Notebook    | [65941d7354](https://linux-hardware.org/?probe=65941d7354) | Mar 17, 2021 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [391c72b961](https://linux-hardware.org/?probe=391c72b961) | Mar 17, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [530ac66726](https://linux-hardware.org/?probe=530ac66726) | Mar 17, 2021 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [6a44f69309](https://linux-hardware.org/?probe=6a44f69309) | Mar 17, 2021 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [e671743616](https://linux-hardware.org/?probe=e671743616) | Mar 17, 2021 |
| Lenovo        | MIIX 2 10 20359             | Tablet      | [edff48d58f](https://linux-hardware.org/?probe=edff48d58f) | Mar 13, 2021 |
| Dell          | Latitude 7380               | Notebook    | [43510cebc1](https://linux-hardware.org/?probe=43510cebc1) | Mar 13, 2021 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [15c953bc70](https://linux-hardware.org/?probe=15c953bc70) | Mar 09, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d4e62a32a8](https://linux-hardware.org/?probe=d4e62a32a8) | Mar 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7ab4c4e090](https://linux-hardware.org/?probe=7ab4c4e090) | Mar 03, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [f371afba83](https://linux-hardware.org/?probe=f371afba83) | Feb 27, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d36796da44](https://linux-hardware.org/?probe=d36796da44) | Feb 27, 2021 |
| Lenovo        | ThinkPad T430 2347EV8       | Notebook    | [3bf5967320](https://linux-hardware.org/?probe=3bf5967320) | Feb 19, 2021 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [e4702a62a8](https://linux-hardware.org/?probe=e4702a62a8) | Feb 19, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ceffe7a79e](https://linux-hardware.org/?probe=ceffe7a79e) | Feb 16, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [446351d845](https://linux-hardware.org/?probe=446351d845) | Feb 15, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [b5e1004909](https://linux-hardware.org/?probe=b5e1004909) | Feb 12, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [504106eb2c](https://linux-hardware.org/?probe=504106eb2c) | Feb 12, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [c951026b91](https://linux-hardware.org/?probe=c951026b91) | Feb 07, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [80724d2ba1](https://linux-hardware.org/?probe=80724d2ba1) | Jan 31, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a398ccbc3d](https://linux-hardware.org/?probe=a398ccbc3d) | Jan 31, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XN0... | Notebook    | [f25ec6b2f3](https://linux-hardware.org/?probe=f25ec6b2f3) | Jan 31, 2021 |
| ASRock        | H61M/U3S3                   | Desktop     | [2d831a72bb](https://linux-hardware.org/?probe=2d831a72bb) | Jan 27, 2021 |
| Acer          | Extensa 5220                | Notebook    | [20ea0cd55c](https://linux-hardware.org/?probe=20ea0cd55c) | Jan 23, 2021 |
| Acer          | Extensa 5220                | Notebook    | [9fe95abf63](https://linux-hardware.org/?probe=9fe95abf63) | Jan 23, 2021 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [a38c700d1b](https://linux-hardware.org/?probe=a38c700d1b) | Jan 16, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [b7b3175352](https://linux-hardware.org/?probe=b7b3175352) | Jan 14, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [ed7d9bff15](https://linux-hardware.org/?probe=ed7d9bff15) | Jan 13, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [91885a7829](https://linux-hardware.org/?probe=91885a7829) | Jan 05, 2021 |
| ASUSTek       | Leonite2                    | Desktop     | [9867e750d0](https://linux-hardware.org/?probe=9867e750d0) | Jan 01, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [34198a369d](https://linux-hardware.org/?probe=34198a369d) | Dec 26, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [f4ab3e4295](https://linux-hardware.org/?probe=f4ab3e4295) | Dec 26, 2020 |
| Acer          | Aspire 1410                 | Notebook    | [3ff80e7b33](https://linux-hardware.org/?probe=3ff80e7b33) | Dec 26, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [44990d7fc0](https://linux-hardware.org/?probe=44990d7fc0) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [e6e91c5ea2](https://linux-hardware.org/?probe=e6e91c5ea2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [5b56323f14](https://linux-hardware.org/?probe=5b56323f14) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [2c7c774492](https://linux-hardware.org/?probe=2c7c774492) | Dec 15, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [649ea3d331](https://linux-hardware.org/?probe=649ea3d331) | Dec 10, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [48d0f1a04c](https://linux-hardware.org/?probe=48d0f1a04c) | Dec 08, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [5c89245f08](https://linux-hardware.org/?probe=5c89245f08) | Dec 02, 2020 |
| Dell          | Latitude E7470              | Notebook    | [3c76403f27](https://linux-hardware.org/?probe=3c76403f27) | Dec 01, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [a37a75cdcb](https://linux-hardware.org/?probe=a37a75cdcb) | Nov 29, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a58e43a971](https://linux-hardware.org/?probe=a58e43a971) | Nov 20, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [374504e0bd](https://linux-hardware.org/?probe=374504e0bd) | Nov 20, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [1310e54c33](https://linux-hardware.org/?probe=1310e54c33) | Nov 20, 2020 |
| Gigabyte      | H81M-D2V                    | Desktop     | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [574e7cc90c](https://linux-hardware.org/?probe=574e7cc90c) | Nov 18, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [778d8e5380](https://linux-hardware.org/?probe=778d8e5380) | Nov 18, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [fb41abdfb1](https://linux-hardware.org/?probe=fb41abdfb1) | Nov 13, 2020 |
| Alienware     | 17                          | Notebook    | [59fdbdd4d7](https://linux-hardware.org/?probe=59fdbdd4d7) | Nov 11, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [86837daf1c](https://linux-hardware.org/?probe=86837daf1c) | Nov 10, 2020 |
| ASRock        | 880GM-LE FX                 | Desktop     | [c16ef7ddf0](https://linux-hardware.org/?probe=c16ef7ddf0) | Nov 09, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [2788cb02ed](https://linux-hardware.org/?probe=2788cb02ed) | Nov 08, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cf2cbcbe72](https://linux-hardware.org/?probe=cf2cbcbe72) | Nov 05, 2020 |
| HP            | 3048h                       | Desktop     | [96c9bd0ab6](https://linux-hardware.org/?probe=96c9bd0ab6) | Nov 05, 2020 |
| MSI           | Z87M-G43                    | Desktop     | [9de0cc7bbf](https://linux-hardware.org/?probe=9de0cc7bbf) | Nov 03, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [39dcf2485b](https://linux-hardware.org/?probe=39dcf2485b) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [f507c9b3e5](https://linux-hardware.org/?probe=f507c9b3e5) | Oct 25, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1b2dd49d08](https://linux-hardware.org/?probe=1b2dd49d08) | Oct 20, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [b3e5017b13](https://linux-hardware.org/?probe=b3e5017b13) | Oct 20, 2020 |
| HP            | 0A64h                       | Desktop     | [88899b775b](https://linux-hardware.org/?probe=88899b775b) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [09fbf70f49](https://linux-hardware.org/?probe=09fbf70f49) | Oct 16, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [c69e6488fd](https://linux-hardware.org/?probe=c69e6488fd) | Oct 14, 2020 |
| Dell          | G5 5587                     | Notebook    | [ba6fbeb10c](https://linux-hardware.org/?probe=ba6fbeb10c) | Oct 09, 2020 |
| Dell          | G5 5587                     | Notebook    | [8b28232f32](https://linux-hardware.org/?probe=8b28232f32) | Oct 09, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [5b52249750](https://linux-hardware.org/?probe=5b52249750) | Oct 04, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [a5e1c0e5f3](https://linux-hardware.org/?probe=a5e1c0e5f3) | Oct 03, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [0362c406d8](https://linux-hardware.org/?probe=0362c406d8) | Oct 03, 2020 |
| HP            | ProBook 4720s               | Notebook    | [a882fdd653](https://linux-hardware.org/?probe=a882fdd653) | Oct 02, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [d4d74a6e34](https://linux-hardware.org/?probe=d4d74a6e34) | Sep 29, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [2acb54cb0d](https://linux-hardware.org/?probe=2acb54cb0d) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [b765d71b82](https://linux-hardware.org/?probe=b765d71b82) | Sep 28, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [87092c4768](https://linux-hardware.org/?probe=87092c4768) | Sep 21, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [48825acdce](https://linux-hardware.org/?probe=48825acdce) | Sep 18, 2020 |
| Gigabyte      | H81M-D2V                    | Desktop     | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [aef0cb23ec](https://linux-hardware.org/?probe=aef0cb23ec) | Sep 16, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [6fffc9928f](https://linux-hardware.org/?probe=6fffc9928f) | Sep 10, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [7465caa486](https://linux-hardware.org/?probe=7465caa486) | Sep 10, 2020 |
| Lenovo        | ThinkPad T460s 20F90058M... | Notebook    | [352f3932b4](https://linux-hardware.org/?probe=352f3932b4) | Sep 09, 2020 |
| Dell          | Latitude 5491               | Notebook    | [06d4120fc1](https://linux-hardware.org/?probe=06d4120fc1) | Sep 08, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4d40f1808](https://linux-hardware.org/?probe=d4d40f1808) | Sep 04, 2020 |
| Lenovo        | ThinkPad L440 20ASS10F00    | Notebook    | [cb6b544787](https://linux-hardware.org/?probe=cb6b544787) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [0097d71249](https://linux-hardware.org/?probe=0097d71249) | Sep 04, 2020 |
| Timi          | TM1701                      | Notebook    | [4c01fca357](https://linux-hardware.org/?probe=4c01fca357) | Aug 25, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4bd12a2bcc](https://linux-hardware.org/?probe=4bd12a2bcc) | Aug 25, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [a5338ac2ec](https://linux-hardware.org/?probe=a5338ac2ec) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [d053bf3f76](https://linux-hardware.org/?probe=d053bf3f76) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [2551496802](https://linux-hardware.org/?probe=2551496802) | Aug 18, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8a4f211ca2](https://linux-hardware.org/?probe=8a4f211ca2) | Aug 18, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [f6a94becbf](https://linux-hardware.org/?probe=f6a94becbf) | Aug 13, 2020 |
| Dell          | XPS M1330                   | Notebook    | [4a907eebb9](https://linux-hardware.org/?probe=4a907eebb9) | Aug 02, 2020 |
| MSI           | H81M-P33                    | Desktop     | [5d7abb7a5b](https://linux-hardware.org/?probe=5d7abb7a5b) | Jul 31, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [a52cd7499e](https://linux-hardware.org/?probe=a52cd7499e) | Jul 28, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [a4948f0d33](https://linux-hardware.org/?probe=a4948f0d33) | Jul 24, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [cd250d0e7b](https://linux-hardware.org/?probe=cd250d0e7b) | Jul 24, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [810f713a78](https://linux-hardware.org/?probe=810f713a78) | Jul 24, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4c09684767](https://linux-hardware.org/?probe=4c09684767) | Jul 23, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [f31ba594be](https://linux-hardware.org/?probe=f31ba594be) | Jul 19, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [90f3c751dc](https://linux-hardware.org/?probe=90f3c751dc) | Jul 19, 2020 |
| ASUSTek       | N71Ja                       | Notebook    | [db78759a1a](https://linux-hardware.org/?probe=db78759a1a) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [0fb6ac937d](https://linux-hardware.org/?probe=0fb6ac937d) | Jul 06, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [fc16d36603](https://linux-hardware.org/?probe=fc16d36603) | Jul 03, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [9c1c6b6919](https://linux-hardware.org/?probe=9c1c6b6919) | Jun 30, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [ab2ec330ab](https://linux-hardware.org/?probe=ab2ec330ab) | Jun 24, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [78351d2937](https://linux-hardware.org/?probe=78351d2937) | Jun 22, 2020 |
| Lenovo        | ThinkPad L460 20FU0007MH    | Notebook    | [27a87ca264](https://linux-hardware.org/?probe=27a87ca264) | Jun 18, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [9c0419884f](https://linux-hardware.org/?probe=9c0419884f) | Jun 17, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [ed27c7aa81](https://linux-hardware.org/?probe=ed27c7aa81) | Jun 10, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [574368a188](https://linux-hardware.org/?probe=574368a188) | Jun 09, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [feebe9e438](https://linux-hardware.org/?probe=feebe9e438) | Jun 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [ebac9eaefe](https://linux-hardware.org/?probe=ebac9eaefe) | Jun 02, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [85443edb8d](https://linux-hardware.org/?probe=85443edb8d) | May 22, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [368e9f53e5](https://linux-hardware.org/?probe=368e9f53e5) | May 22, 2020 |
| Samsung       | RC530/RC730                 | Notebook    | [7e180f5fd2](https://linux-hardware.org/?probe=7e180f5fd2) | May 21, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [04ed3686b1](https://linux-hardware.org/?probe=04ed3686b1) | May 19, 2020 |
| ASUSTek       | X51RL                       | Notebook    | [afee28a69b](https://linux-hardware.org/?probe=afee28a69b) | May 16, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Lenovo        | ThinkPad Edge E320 12985... | Notebook    | [e4a1ece1ec](https://linux-hardware.org/?probe=e4a1ece1ec) | Apr 28, 2020 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [6100c873a3](https://linux-hardware.org/?probe=6100c873a3) | Apr 26, 2020 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [cbc58485b8](https://linux-hardware.org/?probe=cbc58485b8) | Apr 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [70daf3ad77](https://linux-hardware.org/?probe=70daf3ad77) | Apr 20, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [c4b061e0f5](https://linux-hardware.org/?probe=c4b061e0f5) | Apr 19, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| ASUSTek       | M50SA                       | Notebook    | [a7381b478e](https://linux-hardware.org/?probe=a7381b478e) | Apr 10, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [38086a42be](https://linux-hardware.org/?probe=38086a42be) | Apr 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [2246b94acb](https://linux-hardware.org/?probe=2246b94acb) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [0552ab024f](https://linux-hardware.org/?probe=0552ab024f) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [0fd03337ad](https://linux-hardware.org/?probe=0fd03337ad) | Mar 29, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [055f9887c3](https://linux-hardware.org/?probe=055f9887c3) | Mar 29, 2020 |
| Lenovo        | G550 20023                  | Notebook    | [0e9b1fb324](https://linux-hardware.org/?probe=0e9b1fb324) | Mar 29, 2020 |
| HP            | 630                         | Notebook    | [fc76abe01b](https://linux-hardware.org/?probe=fc76abe01b) | Mar 29, 2020 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [23a0bdb230](https://linux-hardware.org/?probe=23a0bdb230) | Mar 19, 2020 |
| MSI           | H61M-P20                    | Desktop     | [bd9fc44d34](https://linux-hardware.org/?probe=bd9fc44d34) | Mar 17, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| MSI           | H61M-P20                    | Desktop     | [9111061475](https://linux-hardware.org/?probe=9111061475) | Mar 10, 2020 |
| ASUSTek       | K53E                        | Notebook    | [8729f56cdc](https://linux-hardware.org/?probe=8729f56cdc) | Mar 07, 2020 |
| MSI           | Z170A GAMING M5             | Desktop     | [f1eb3e7e12](https://linux-hardware.org/?probe=f1eb3e7e12) | Mar 01, 2020 |
| MSI           | Z170A GAMING M5             | Desktop     | [7058bdb7d6](https://linux-hardware.org/?probe=7058bdb7d6) | Mar 01, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [3b537b4a10](https://linux-hardware.org/?probe=3b537b4a10) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [816d9c42da](https://linux-hardware.org/?probe=816d9c42da) | Feb 28, 2020 |
| HP            | 1589                        | Desktop     | [0c9be85544](https://linux-hardware.org/?probe=0c9be85544) | Feb 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f08088a64d](https://linux-hardware.org/?probe=f08088a64d) | Feb 20, 2020 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [2d24c5a932](https://linux-hardware.org/?probe=2d24c5a932) | Feb 15, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [c95a831b3c](https://linux-hardware.org/?probe=c95a831b3c) | Feb 11, 2020 |
| HP            | ProBook 4740s               | Notebook    | [4d4d26ef02](https://linux-hardware.org/?probe=4d4d26ef02) | Feb 03, 2020 |
| Lenovo        | ThinkPad E590 20NB0065MH    | Notebook    | [e895371f73](https://linux-hardware.org/?probe=e895371f73) | Feb 03, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [226b976601](https://linux-hardware.org/?probe=226b976601) | Jan 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6973864306](https://linux-hardware.org/?probe=6973864306) | Jan 25, 2020 |
| Acer          | Aspire V3-772               | Notebook    | [17005306cd](https://linux-hardware.org/?probe=17005306cd) | Jan 24, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [4335a97dd6](https://linux-hardware.org/?probe=4335a97dd6) | Jan 24, 2020 |
| Dell          | G3 3579                     | Notebook    | [56f84db06b](https://linux-hardware.org/?probe=56f84db06b) | Jan 22, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [f22d44d39f](https://linux-hardware.org/?probe=f22d44d39f) | Jan 22, 2020 |
| Panasonic     | CF-52WEBBYDE                | Notebook    | [0d21ee7063](https://linux-hardware.org/?probe=0d21ee7063) | Jan 17, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [cf8ada0ad0](https://linux-hardware.org/?probe=cf8ada0ad0) | Jan 16, 2020 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | Notebook    | [f57bc0120b](https://linux-hardware.org/?probe=f57bc0120b) | Jan 15, 2020 |
| MSI           | B450M PRO-VDH               | Desktop     | [5b95761a5d](https://linux-hardware.org/?probe=5b95761a5d) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [660da3e630](https://linux-hardware.org/?probe=660da3e630) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH               | Desktop     | [f45d7203c0](https://linux-hardware.org/?probe=f45d7203c0) | Jan 03, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [b0c00423bd](https://linux-hardware.org/?probe=b0c00423bd) | Dec 31, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | Notebook    | [4ea8d503ae](https://linux-hardware.org/?probe=4ea8d503ae) | Dec 13, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | Notebook    | [a298251c28](https://linux-hardware.org/?probe=a298251c28) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [924e886e1f](https://linux-hardware.org/?probe=924e886e1f) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [4a5d98c236](https://linux-hardware.org/?probe=4a5d98c236) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [b919c0cb27](https://linux-hardware.org/?probe=b919c0cb27) | Dec 13, 2019 |
| ASRock        | H61M-VS                     | Desktop     | [6d7e3aa70a](https://linux-hardware.org/?probe=6d7e3aa70a) | Dec 11, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 856               | Notebook    | [80cf2af707](https://linux-hardware.org/?probe=80cf2af707) | Nov 22, 2019 |
| HP            | Pavilion dv6                | Notebook    | [6f6270eb8e](https://linux-hardware.org/?probe=6f6270eb8e) | Nov 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [c08e4bac64](https://linux-hardware.org/?probe=c08e4bac64) | Nov 16, 2019 |
| HP            | EliteBook 8460p             | Notebook    | [56a12d5f20](https://linux-hardware.org/?probe=56a12d5f20) | Nov 09, 2019 |
| Acer          | AOD260                      | Notebook    | [a911172500](https://linux-hardware.org/?probe=a911172500) | Nov 09, 2019 |
| ASUSTek       | H110M-R                     | Desktop     | [3068ae6e29](https://linux-hardware.org/?probe=3068ae6e29) | Nov 05, 2019 |
| Sony          | VGN-C260E                   | Notebook    | [c623de88ee](https://linux-hardware.org/?probe=c623de88ee) | Oct 24, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [36deb3b32d](https://linux-hardware.org/?probe=36deb3b32d) | Oct 13, 2019 |
| HP            | Pavilion dv6                | Notebook    | [c2264e7abd](https://linux-hardware.org/?probe=c2264e7abd) | Oct 11, 2019 |
| ASUSTek       | H110M-R                     | Desktop     | [dc23169db8](https://linux-hardware.org/?probe=dc23169db8) | Oct 10, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [77b1afae40](https://linux-hardware.org/?probe=77b1afae40) | Oct 09, 2019 |
| Fujitsu Si... | D2119 S26361-D2119          | Server      | [1a0dfe074e](https://linux-hardware.org/?probe=1a0dfe074e) | Oct 01, 2019 |
| Fujitsu Si... | D2119 S26361-D2119          | Server      | [7cad023dc8](https://linux-hardware.org/?probe=7cad023dc8) | Oct 01, 2019 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [ec4b0c74d2](https://linux-hardware.org/?probe=ec4b0c74d2) | Sep 27, 2019 |
| HP            | 0A60h                       | Desktop     | [e587b4122a](https://linux-hardware.org/?probe=e587b4122a) | Sep 22, 2019 |
| ASUSTek       | K53SV                       | Notebook    | [61f7ec13d8](https://linux-hardware.org/?probe=61f7ec13d8) | Sep 19, 2019 |
| ASUSTek       | K53E                        | Notebook    | [71fd2610fe](https://linux-hardware.org/?probe=71fd2610fe) | Sep 15, 2019 |
| ASUSTek       | K53E                        | Notebook    | [e435064ad7](https://linux-hardware.org/?probe=e435064ad7) | Sep 15, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [3baafefb84](https://linux-hardware.org/?probe=3baafefb84) | Aug 27, 2019 |
| Prestigio     | PSB141C02                   | Notebook    | [3e96d56c17](https://linux-hardware.org/?probe=3e96d56c17) | Aug 25, 2019 |
| ASUSTek       | K53E                        | Notebook    | [c1811b7ec3](https://linux-hardware.org/?probe=c1811b7ec3) | Aug 23, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [15419d9561](https://linux-hardware.org/?probe=15419d9561) | Aug 20, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7653d7fa4d](https://linux-hardware.org/?probe=7653d7fa4d) | Jul 29, 2019 |
| Lenovo        | G550 20023                  | Notebook    | [601d53f9eb](https://linux-hardware.org/?probe=601d53f9eb) | Jul 23, 2019 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5b8d494c04](https://linux-hardware.org/?probe=5b8d494c04) | Jul 12, 2019 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [fd394cc113](https://linux-hardware.org/?probe=fd394cc113) | Jun 05, 2019 |
| Lenovo        | ThinkPad R500 27327KG       | Notebook    | [c8b31c9d99](https://linux-hardware.org/?probe=c8b31c9d99) | Jun 04, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [23d8e1dd30](https://linux-hardware.org/?probe=23d8e1dd30) | May 31, 2019 |
| Acer          | TravelMate 5740G            | Notebook    | [0d4611c952](https://linux-hardware.org/?probe=0d4611c952) | May 25, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [be887070fe](https://linux-hardware.org/?probe=be887070fe) | May 17, 2019 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [c39268dff8](https://linux-hardware.org/?probe=c39268dff8) | May 13, 2019 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [e0d133befc](https://linux-hardware.org/?probe=e0d133befc) | May 13, 2019 |
| HP            | ProBook 6555b               | Notebook    | [598fc6c1ca](https://linux-hardware.org/?probe=598fc6c1ca) | May 13, 2019 |
| HP            | ProBook 4540s               | Notebook    | [2e61bfe1be](https://linux-hardware.org/?probe=2e61bfe1be) | Apr 28, 2019 |
| HP            | ProBook 4540s               | Notebook    | [8d460232a9](https://linux-hardware.org/?probe=8d460232a9) | Apr 28, 2019 |
| Dell          | Inspiron 5737               | Notebook    | [2c7d308e3a](https://linux-hardware.org/?probe=2c7d308e3a) | Apr 26, 2019 |
| Dell          | Inspiron 5737               | Notebook    | [dcf03f780e](https://linux-hardware.org/?probe=dcf03f780e) | Apr 26, 2019 |
| Acer          | TravelMate 5740G            | Notebook    | [6b69828c13](https://linux-hardware.org/?probe=6b69828c13) | Apr 07, 2019 |
| Sony          | VPCZ1390S                   | Notebook    | [eb4e58c4d9](https://linux-hardware.org/?probe=eb4e58c4d9) | Mar 05, 2019 |
| Sony          | VPCZ1390S                   | Notebook    | [8995c67e48](https://linux-hardware.org/?probe=8995c67e48) | Mar 05, 2019 |
| ASRock        | X370 Taichi                 | Desktop     | [283ce85ac6](https://linux-hardware.org/?probe=283ce85ac6) | Feb 20, 2019 |
| Lenovo        | ThinkPad X230 2325AEG       | Notebook    | [2b8bcfe576](https://linux-hardware.org/?probe=2b8bcfe576) | Feb 19, 2019 |
| ASUSTek       | X550LB                      | Notebook    | [992697103b](https://linux-hardware.org/?probe=992697103b) | Jan 18, 2019 |
| ASUSTek       | X550LB                      | Notebook    | [5228ac3dbc](https://linux-hardware.org/?probe=5228ac3dbc) | Jan 18, 2019 |
| Dell          | 0XFWHV A00                  | Desktop     | [f9e47efc1f](https://linux-hardware.org/?probe=f9e47efc1f) | Jan 12, 2019 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [dffa2ed3ef](https://linux-hardware.org/?probe=dffa2ed3ef) | Dec 20, 2018 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [e192353344](https://linux-hardware.org/?probe=e192353344) | Dec 20, 2018 |
| Lenovo        | G550 20023                  | Notebook    | [54fd0e13d2](https://linux-hardware.org/?probe=54fd0e13d2) | Oct 29, 2018 |
| MSI           | Z170A GAMING M5             | Desktop     | [68365011c2](https://linux-hardware.org/?probe=68365011c2) | Oct 26, 2018 |
| Lenovo        | G550 20023                  | Notebook    | [3011864d4b](https://linux-hardware.org/?probe=3011864d4b) | Oct 25, 2018 |
| Intel         | DB65AL AAG12530-302         | Desktop     | [be0b280760](https://linux-hardware.org/?probe=be0b280760) | Oct 25, 2018 |
| ASUSTek       | K53E                        | Notebook    | [0e63193763](https://linux-hardware.org/?probe=0e63193763) | Oct 21, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8a053e30bf](https://linux-hardware.org/?probe=8a053e30bf) | Sep 30, 2018 |
| HP            | 0A60h                       | Desktop     | [887d9e063a](https://linux-hardware.org/?probe=887d9e063a) | Sep 24, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8e1eab57d7](https://linux-hardware.org/?probe=8e1eab57d7) | Sep 03, 2018 |
| ASUSTek       | 1225B                       | Notebook    | [fb333d2cde](https://linux-hardware.org/?probe=fb333d2cde) | Aug 23, 2018 |
| HP            | 0A60h                       | Desktop     | [180ad06c55](https://linux-hardware.org/?probe=180ad06c55) | Aug 21, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8ebafe3965](https://linux-hardware.org/?probe=8ebafe3965) | Aug 04, 2018 |
| HP            | 0A60h                       | Desktop     | [4ed0a42e5c](https://linux-hardware.org/?probe=4ed0a42e5c) | Jun 30, 2018 |
| ASUSTek       | K53E                        | Notebook    | [58b632622d](https://linux-hardware.org/?probe=58b632622d) | Apr 15, 2018 |
| ASUSTek       | X555LN                      | Notebook    | [9760e114b0](https://linux-hardware.org/?probe=9760e114b0) | Apr 07, 2018 |
| ASUSTek       | X555LN                      | Notebook    | [c3f232766b](https://linux-hardware.org/?probe=c3f232766b) | Apr 07, 2018 |
| ASUSTek       | K53SV                       | Notebook    | [e3e865dedf](https://linux-hardware.org/?probe=e3e865dedf) | Apr 06, 2018 |
| ASUSTek       | M4A785T-M                   | Desktop     | [0f2664d3b1](https://linux-hardware.org/?probe=0f2664d3b1) | Mar 29, 2018 |
| ASUSTek       | M4A785T-M                   | Desktop     | [1a91c5f47f](https://linux-hardware.org/?probe=1a91c5f47f) | Mar 05, 2018 |
| Intel         | D102GGC2 AAD42789-201       | Desktop     | [d52ebc3540](https://linux-hardware.org/?probe=d52ebc3540) | Jan 09, 2018 |
| Intel         | D102GGC2 AAD42789-201       | Desktop     | [16d64740e8](https://linux-hardware.org/?probe=16d64740e8) | Jan 09, 2018 |
| ASUSTek       | K53SV                       | Notebook    | [041cd61823](https://linux-hardware.org/?probe=041cd61823) | Dec 14, 2017 |
| Acer          | Aspire 5610Z                | Notebook    | [c79786fae0](https://linux-hardware.org/?probe=c79786fae0) | Dec 12, 2017 |
| ASRock        | ALiveDual-eSATA2            | Desktop     | [7330a7e461](https://linux-hardware.org/?probe=7330a7e461) | Sep 27, 2017 |
| Dell          | Inspiron 3537               | Notebook    | [0cb8d57f73](https://linux-hardware.org/?probe=0cb8d57f73) | Sep 25, 2017 |
| ASUSTek       | M50Vc                       | Notebook    | [9224093b58](https://linux-hardware.org/?probe=9224093b58) | Aug 22, 2017 |
| ASUSTek       | K53SV                       | Notebook    | [366e5e884c](https://linux-hardware.org/?probe=366e5e884c) | Jun 23, 2017 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0ba3b01a3b](https://linux-hardware.org/?probe=0ba3b01a3b) | May 17, 2017 |
| ASRock        | 980DE3/U3S3 R2.0            | Desktop     | [ce9b629fa0](https://linux-hardware.org/?probe=ce9b629fa0) | Apr 21, 2017 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0a9d97b358](https://linux-hardware.org/?probe=0a9d97b358) | Apr 11, 2017 |
| Dell          | Precision M4600             | Notebook    | [2a09c39637](https://linux-hardware.org/?probe=2a09c39637) | Mar 15, 2017 |
| Dell          | Precision M4600             | Notebook    | [c9a115e18c](https://linux-hardware.org/?probe=c9a115e18c) | Mar 15, 2017 |
| ASRock        | G41M-VS3                    | Desktop     | [8915ed904a](https://linux-hardware.org/?probe=8915ed904a) | Mar 14, 2017 |
| Acer          | Aspire ES1-711              | Notebook    | [0f7625ddc4](https://linux-hardware.org/?probe=0f7625ddc4) | Mar 10, 2017 |
| Acer          | Aspire ES1-711              | Notebook    | [64cea7b4eb](https://linux-hardware.org/?probe=64cea7b4eb) | Mar 10, 2017 |
| ASRock        | G41C-VS                     | Desktop     | [3688013a36](https://linux-hardware.org/?probe=3688013a36) | Dec 02, 2016 |
| ASRock        | G41C-VS                     | Desktop     | [9f9c0116cd](https://linux-hardware.org/?probe=9f9c0116cd) | Nov 30, 2016 |
| ASRock        | G41C-VS                     | Desktop     | [a1993f9fc4](https://linux-hardware.org/?probe=a1993f9fc4) | Nov 28, 2016 |
| Dell          | Precision M4600             | Notebook    | [e851921cd7](https://linux-hardware.org/?probe=e851921cd7) | Oct 24, 2016 |
| Dell          | Latitude E6440              | Notebook    | [ea1b5da2e7](https://linux-hardware.org/?probe=ea1b5da2e7) | Dec 07, 2015 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Lithuania/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 34        | 6.33%   |
| Arch Rolling                 | 30        | 5.59%   |
| Ubuntu 18.04                 | 27        | 5.03%   |
| Ubuntu 22.04                 | 23        | 4.28%   |
| Arch                         | 11        | 2.05%   |
| Pop!_OS 22.04                | 9         | 1.68%   |
| ROSA R11                     | 8         | 1.49%   |
| Pop!_OS 21.04                | 8         | 1.49%   |
| OpenMandriva 4.3             | 8         | 1.49%   |
| Debian 12                    | 8         | 1.49%   |
| Debian 11                    | 8         | 1.49%   |
| ArcoLinux Rolling            | 8         | 1.49%   |
| Zorin 16                     | 7         | 1.3%    |
| ROSA R8.1                    | 7         | 1.3%    |
| ROSA R10                     | 7         | 1.3%    |
| OpenMandriva 4.2             | 7         | 1.3%    |
| OpenMandriva 23.03           | 7         | 1.3%    |
| Manjaro                      | 7         | 1.3%    |
| Linux Mint 21.1              | 7         | 1.3%    |
| KDE neon 20.04               | 7         | 1.3%    |
| Ubuntu 19.10                 | 6         | 1.12%   |
| Ubuntu 19.04                 | 6         | 1.12%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.12%   |
| OpenMandriva 24.07           | 6         | 1.12%   |
| Kubuntu 22.04                | 6         | 1.12%   |
| Xubuntu 20.04                | 5         | 0.93%   |
| Ubuntu 24.04                 | 5         | 0.93%   |
| Ubuntu 21.10                 | 5         | 0.93%   |
| ROSA R9                      | 5         | 0.93%   |
| ROSA R11.1                   | 5         | 0.93%   |
| Pop!_OS 21.10                | 5         | 0.93%   |
| Pop!_OS 20.04                | 5         | 0.93%   |
| OpenMandriva 23.08           | 5         | 0.93%   |
| OpenMandriva 23.01           | 5         | 0.93%   |
| Manjaro 20.2.1               | 5         | 0.93%   |
| Linux Mint 20.1              | 5         | 0.93%   |
| Linux Mint 20                | 5         | 0.93%   |
| KDE neon 22.04               | 5         | 0.93%   |
| Fedora 40                    | 5         | 0.93%   |
| Fedora 38                    | 5         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 114       | 23.03%  |
| OpenMandriva  | 39        | 7.88%   |
| Arch          | 38        | 7.68%   |
| Linux Mint    | 34        | 6.87%   |
| Fedora        | 34        | 6.87%   |
| ROSA          | 30        | 6.06%   |
| Pop!_OS       | 28        | 5.66%   |
| Manjaro       | 24        | 4.85%   |
| Debian        | 23        | 4.65%   |
| Zorin         | 13        | 2.63%   |
| KDE neon      | 13        | 2.63%   |
| Kubuntu       | 11        | 2.22%   |
| Xubuntu       | 9         | 1.82%   |
| ArcoLinux     | 8         | 1.62%   |
| openSUSE      | 7         | 1.41%   |
| Lubuntu       | 6         | 1.21%   |
| Ubuntu Unity  | 5         | 1.01%   |
| Endless       | 5         | 1.01%   |
| EndeavourOS   | 5         | 1.01%   |
| Elementary    | 5         | 1.01%   |
| Gentoo        | 4         | 0.81%   |
| SteamOS       | 3         | 0.61%   |
| RHEL          | 3         | 0.61%   |
| LMDE          | 3         | 0.61%   |
| CentOS        | 3         | 0.61%   |
| Ubuntu MATE   | 2         | 0.4%    |
| RED           | 2         | 0.4%    |
| Nobara        | 2         | 0.4%    |
| NixOS         | 2         | 0.4%    |
| MX            | 2         | 0.4%    |
| Kali          | 2         | 0.4%    |
| Garuda Linux  | 2         | 0.4%    |
| Artix         | 2         | 0.4%    |
| Ubuntu Budgie | 1         | 0.2%    |
| Sparky        | 1         | 0.2%    |
| Slackware     | 1         | 0.2%    |
| PostmarketOS  | 1         | 0.2%    |
| Peppermint    | 1         | 0.2%    |
| Parrot        | 1         | 0.2%    |
| Manjaro-ARM   | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                  | Computers | Percent |
|------------------------------------------|-----------|---------|
| 5.4.0-42-generic                         | 7         | 1.19%   |
| 5.10.14-desktop-1omv4002                 | 7         | 1.19%   |
| 6.2.6-desktop-1omv2390                   | 6         | 1.02%   |
| 5.13.0-40-generic                        | 6         | 1.02%   |
| 6.10.0-desktop-1omv2490                  | 5         | 0.85%   |
| 6.1.1-desktop-1omv2290                   | 5         | 0.85%   |
| 5.4.0-48-generic                         | 5         | 0.85%   |
| 5.16.7-desktop-1omv4003                  | 5         | 0.85%   |
| 5.15.0-56-generic                        | 5         | 0.85%   |
| 5.4.0-66-generic                         | 4         | 0.68%   |
| 5.3.0-28-generic                         | 4         | 0.68%   |
| 6.8.0-45-generic                         | 3         | 0.51%   |
| 6.6.2-desktop-1omv2390                   | 3         | 0.51%   |
| 6.4.11-desktop-1omv2390                  | 3         | 0.51%   |
| 6.3.5-desktop-3omv2390                   | 3         | 0.51%   |
| 6.2.0-35-generic                         | 3         | 0.51%   |
| 6.2.0-20-generic                         | 3         | 0.51%   |
| 6.1.0-10-amd64                           | 3         | 0.51%   |
| 5.9.16-1-MANJARO                         | 3         | 0.51%   |
| 5.4.0-70-generic                         | 3         | 0.51%   |
| 5.4.0-47-generic                         | 3         | 0.51%   |
| 5.3.0-26-generic                         | 3         | 0.51%   |
| 5.3.0-23-generic                         | 3         | 0.51%   |
| 5.11.0-7620-generic                      | 3         | 0.51%   |
| 4.9.60-nrj-desktop-1rosa-i586            | 3         | 0.51%   |
| 4.9.41-nrj-desktop-1rosa-x86_64          | 3         | 0.51%   |
| 4.15.0-desktop-60.7rosa-i586             | 3         | 0.51%   |
| 4.15.0-91-generic                        | 3         | 0.51%   |
| 6.9.3-76060903-generic                   | 2         | 0.34%   |
| 6.8.5-301.fc40.x86_64                    | 2         | 0.34%   |
| 6.8.4-200.fc39.x86_64                    | 2         | 0.34%   |
| 6.8.0-51-generic                         | 2         | 0.34%   |
| 6.8.0-31-generic                         | 2         | 0.34%   |
| 6.5.0-valve22-1-neptune-65-g9a338ed8a75e | 2         | 0.34%   |
| 6.5.0-21-generic                         | 2         | 0.34%   |
| 6.4.8-desktop-2omv2390                   | 2         | 0.34%   |
| 6.2.11-300.fc38.x86_64                   | 2         | 0.34%   |
| 6.2.0-39-generic                         | 2         | 0.34%   |
| 6.2.0-33-generic                         | 2         | 0.34%   |
| 6.2.0-32-generic                         | 2         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 53        | 9.52%   |
| 5.15.0  | 40        | 7.18%   |
| 4.15.0  | 28        | 5.03%   |
| 5.3.0   | 22        | 3.95%   |
| 5.13.0  | 19        | 3.41%   |
| 5.8.0   | 16        | 2.87%   |
| 6.2.0   | 15        | 2.69%   |
| 6.1.0   | 14        | 2.51%   |
| 5.11.0  | 13        | 2.33%   |
| 5.19.0  | 12        | 2.15%   |
| 5.0.0   | 12        | 2.15%   |
| 6.8.0   | 11        | 1.97%   |
| 6.2.6   | 8         | 1.44%   |
| 5.10.0  | 8         | 1.44%   |
| 5.16.7  | 7         | 1.26%   |
| 5.10.14 | 7         | 1.26%   |
| 4.18.0  | 7         | 1.26%   |
| 6.5.0   | 6         | 1.08%   |
| 6.10.0  | 5         | 0.9%    |
| 6.1.1   | 5         | 0.9%    |
| 6.9.3   | 4         | 0.72%   |
| 6.6.2   | 4         | 0.72%   |
| 6.3.5   | 4         | 0.72%   |
| 4.9.60  | 4         | 0.72%   |
| 4.19.0  | 4         | 0.72%   |
| 6.4.11  | 3         | 0.54%   |
| 6.12.1  | 3         | 0.54%   |
| 6.0.0   | 3         | 0.54%   |
| 5.9.16  | 3         | 0.54%   |
| 4.9.9   | 3         | 0.54%   |
| 4.9.41  | 3         | 0.54%   |
| 4.9.20  | 3         | 0.54%   |
| 6.8.9   | 2         | 0.36%   |
| 6.8.5   | 2         | 0.36%   |
| 6.8.4   | 2         | 0.36%   |
| 6.8.11  | 2         | 0.36%   |
| 6.6.6   | 2         | 0.36%   |
| 6.6.10  | 2         | 0.36%   |
| 6.4.8   | 2         | 0.36%   |
| 6.2.7   | 2         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 63        | 11.52%  |
| 5.15    | 56        | 10.24%  |
| 6.1     | 32        | 5.85%   |
| 6.2     | 31        | 5.67%   |
| 5.10    | 30        | 5.48%   |
| 4.15    | 28        | 5.12%   |
| 5.8     | 25        | 4.57%   |
| 6.8     | 22        | 4.02%   |
| 5.3     | 22        | 4.02%   |
| 5.13    | 22        | 4.02%   |
| 4.9     | 19        | 3.47%   |
| 6.6     | 17        | 3.11%   |
| 5.19    | 16        | 2.93%   |
| 5.16    | 16        | 2.93%   |
| 5.11    | 16        | 2.93%   |
| 6.10    | 13        | 2.38%   |
| 5.0     | 13        | 2.38%   |
| 6.4     | 10        | 1.83%   |
| 6.11    | 8         | 1.46%   |
| 6.5     | 7         | 1.28%   |
| 6.3     | 7         | 1.28%   |
| 6.0     | 7         | 1.28%   |
| 5.12    | 7         | 1.28%   |
| 4.18    | 7         | 1.28%   |
| 5.9     | 6         | 1.1%    |
| 6.9     | 5         | 0.91%   |
| 6.12    | 5         | 0.91%   |
| 5.18    | 5         | 0.91%   |
| 4.19    | 5         | 0.91%   |
| 5.7     | 4         | 0.73%   |
| 5.17    | 4         | 0.73%   |
| 5.14    | 4         | 0.73%   |
| 4.14    | 4         | 0.73%   |
| 5.6     | 3         | 0.55%   |
| 4.4     | 3         | 0.55%   |
| 4.1     | 3         | 0.55%   |
| 5.5     | 1         | 0.18%   |
| 3.16    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 446       | 95.3%   |
| i686    | 17        | 3.63%   |
| aarch64 | 4         | 0.85%   |
| armv7l  | 1         | 0.21%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 184       | 36.44%  |
| KDE5            | 92        | 18.22%  |
| Unknown         | 54        | 10.69%  |
| XFCE            | 38        | 7.52%   |
| X-Cinnamon      | 29        | 5.74%   |
| KDE4            | 24        | 4.75%   |
| KDE             | 15        | 2.97%   |
| LXQt            | 12        | 2.38%   |
| MATE            | 9         | 1.78%   |
| KDE6            | 8         | 1.58%   |
| Unity           | 6         | 1.19%   |
| Pantheon        | 5         | 0.99%   |
| Hyprland        | 5         | 0.99%   |
| Cinnamon        | 5         | 0.99%   |
| LXDE            | 3         | 0.59%   |
| GNOME Flashback | 2         | 0.4%    |
| GNOME Classic   | 2         | 0.4%    |
| Enlightenment   | 2         | 0.4%    |
| dwm             | 2         | 0.4%    |
| Deepin          | 2         | 0.4%    |
| Budgie          | 2         | 0.4%    |
| awesome         | 2         | 0.4%    |
| qtile           | 1         | 0.2%    |
| i3              | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 346       | 70.04%  |
| Wayland | 112       | 22.67%  |
| Unknown | 21        | 4.25%   |
| Tty     | 15        | 3.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 216       | 43.81%  |
| SDDM    | 93        | 18.86%  |
| GDM     | 56        | 11.36%  |
| LightDM | 50        | 10.14%  |
| GDM3    | 39        | 7.91%   |
| KDM     | 23        | 4.67%   |
| TDM     | 14        | 2.84%   |
| XDM     | 1         | 0.2%    |
| Ly      | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 298       | 61.7%   |
| lt_LT   | 66        | 13.66%  |
| Unknown | 56        | 11.59%  |
| en_GB   | 24        | 4.97%   |
| ru_RU   | 21        | 4.35%   |
| C       | 10        | 2.07%   |
| en_AU   | 2         | 0.41%   |
| de_DE   | 2         | 0.41%   |
| uk_UA   | 1         | 0.21%   |
| nl_NL   | 1         | 0.21%   |
| en_DK   | 1         | 0.21%   |
| be_BY   | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 254       | 53.36%  |
| EFI  | 222       | 46.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 336       | 69.14%  |
| Btrfs   | 55        | 11.32%  |
| Overlay | 36        | 7.41%   |
| Unknown | 23        | 4.73%   |
| Tmpfs   | 21        | 4.32%   |
| Xfs     | 9         | 1.85%   |
| Zfs     | 2         | 0.41%   |
| SAMSUNG | 1         | 0.21%   |
| F2fs    | 1         | 0.21%   |
| ExX4    | 1         | 0.21%   |
| Ext2    | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 219       | 44.97%  |
| GPT     | 203       | 41.68%  |
| MBR     | 65        | 13.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 408       | 85.71%  |
| Yes       | 68        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 357       | 74.84%  |
| Yes       | 120       | 25.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 100       | 21.51%  |
| Lenovo                  | 94        | 20.22%  |
| Hewlett-Packard         | 57        | 12.26%  |
| Dell                    | 49        | 10.54%  |
| MSI                     | 33        | 7.1%    |
| Gigabyte Technology     | 26        | 5.59%   |
| ASRock                  | 26        | 5.59%   |
| Acer                    | 20        | 4.3%    |
| Apple                   | 8         | 1.72%   |
| Intel                   | 7         | 1.51%   |
| Samsung Electronics     | 4         | 0.86%   |
| Valve                   | 3         | 0.65%   |
| Toshiba                 | 3         | 0.65%   |
| Fujitsu Siemens         | 3         | 0.65%   |
| Fujitsu                 | 3         | 0.65%   |
| AMI                     | 3         | 0.65%   |
| Unknown                 | 3         | 0.65%   |
| Sony                    | 2         | 0.43%   |
| Prestigio               | 2         | 0.43%   |
| Panasonic               | 2         | 0.43%   |
| Jumper                  | 2         | 0.43%   |
| HUAWEI                  | 2         | 0.43%   |
| Timi                    | 1         | 0.22%   |
| Rockchip                | 1         | 0.22%   |
| Raspberry Pi Foundation | 1         | 0.22%   |
| Packard Bell            | 1         | 0.22%   |
| Nvidia                  | 1         | 0.22%   |
| Notebook                | 1         | 0.22%   |
| Microsoft               | 1         | 0.22%   |
| LIVEFAN                 | 1         | 0.22%   |
| HONOR                   | 1         | 0.22%   |
| Hardkernel              | 1         | 0.22%   |
| eMachines               | 1         | 0.22%   |
| BESSTAR Tech            | 1         | 0.22%   |
| Alienware               | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 4         | 0.86%   |
| Valve Jupiter                   | 3         | 0.65%   |
| MSI MS-7A38                     | 3         | 0.65%   |
| MSI MS-7817                     | 3         | 0.65%   |
| ASUS All Series                 | 3         | 0.65%   |
| MSI MS-7C82                     | 2         | 0.43%   |
| MSI MS-7A34                     | 2         | 0.43%   |
| MSI MS-7823                     | 2         | 0.43%   |
| Lenovo ThinkPad T490 20N3000KMH | 2         | 0.43%   |
| Lenovo S40-40 F0AX00EAPB        | 2         | 0.43%   |
| Lenovo Legion Y530-15ICH 81FV   | 2         | 0.43%   |
| Lenovo Legion 5 15ACH6H 82JU    | 2         | 0.43%   |
| Lenovo IdeaPad Y700-15ISK 80NV  | 2         | 0.43%   |
| Lenovo G550 20023               | 2         | 0.43%   |
| Jumper EZbook                   | 2         | 0.43%   |
| HP Pavilion g6                  | 2         | 0.43%   |
| HP Pavilion dv6                 | 2         | 0.43%   |
| HP EliteBook 8460p              | 2         | 0.43%   |
| HP EliteBook 8440p              | 2         | 0.43%   |
| Fujitsu LIFEBOOK E554           | 2         | 0.43%   |
| Dell Inspiron 7720              | 2         | 0.43%   |
| ASUS X555LN                     | 2         | 0.43%   |
| ASUS TUF Gaming X570-PLUS       | 2         | 0.43%   |
| ASUS TUF Gaming B550-PLUS       | 2         | 0.43%   |
| ASUS PRIME Z390-A               | 2         | 0.43%   |
| ASUS PRIME B450M-K              | 2         | 0.43%   |
| ASUS PRIME B450M-A              | 2         | 0.43%   |
| ASUS K53E                       | 2         | 0.43%   |
| ASUS GL552VX                    | 2         | 0.43%   |
| ASRock B450 Pro4                | 2         | 0.43%   |
| Apple MacBookPro9,2             | 2         | 0.43%   |
| Apple MacBook5,1                | 2         | 0.43%   |
| AMI Aptio CRB                   | 2         | 0.43%   |
| Acer Aspire ES1-711             | 2         | 0.43%   |
| Acer Aspire 5750G               | 2         | 0.43%   |
| Toshiba WT8-A                   | 1         | 0.22%   |
| Toshiba Satellite L855          | 1         | 0.22%   |
| Toshiba Satellite C50D-A-13G    | 1         | 0.22%   |
| Timi TM1701                     | 1         | 0.22%   |
| Sony VPCZ1390S                  | 1         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 50        | 10.75%  |
| Dell Inspiron     | 16        | 3.44%   |
| ASUS PRIME        | 16        | 3.44%   |
| Lenovo IdeaPad    | 14        | 3.01%   |
| Acer Aspire       | 13        | 2.8%    |
| HP ProBook        | 12        | 2.58%   |
| HP EliteBook      | 11        | 2.37%   |
| Dell Latitude     | 11        | 2.37%   |
| HP Compaq         | 9         | 1.94%   |
| ASUS TUF          | 9         | 1.94%   |
| Lenovo Legion     | 8         | 1.72%   |
| Dell Vostro       | 8         | 1.72%   |
| ASUS VivoBook     | 7         | 1.51%   |
| ASUS ROG          | 6         | 1.29%   |
| ASUS ASUS         | 5         | 1.08%   |
| Lenovo Yoga       | 4         | 0.86%   |
| HP Pavilion       | 4         | 0.86%   |
| HP Laptop         | 4         | 0.86%   |
| Dell XPS          | 4         | 0.86%   |
| Dell OptiPlex     | 4         | 0.86%   |
| Unknown           | 4         | 0.86%   |
| Valve Jupiter     | 3         | 0.65%   |
| MSI MS-7A38       | 3         | 0.65%   |
| MSI MS-7817       | 3         | 0.65%   |
| HP EliteDesk      | 3         | 0.65%   |
| Gigabyte X570     | 3         | 0.65%   |
| ASUS ZenBook      | 3         | 0.65%   |
| ASUS All          | 3         | 0.65%   |
| ASRock B450       | 3         | 0.65%   |
| Toshiba Satellite | 2         | 0.43%   |
| MSI MS-7C82       | 2         | 0.43%   |
| MSI MS-7A34       | 2         | 0.43%   |
| MSI MS-7823       | 2         | 0.43%   |
| Lenovo S40-40     | 2         | 0.43%   |
| Lenovo LOQ        | 2         | 0.43%   |
| Lenovo G550       | 2         | 0.43%   |
| Jumper EZbook     | 2         | 0.43%   |
| HP ENVY           | 2         | 0.43%   |
| HP 250            | 2         | 0.43%   |
| Fujitsu LIFEBOOK  | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 46        | 9.89%   |
| 2020    | 40        | 8.6%    |
| 2021    | 38        | 8.17%   |
| 2011    | 37        | 7.96%   |
| 2014    | 35        | 7.53%   |
| 2019    | 30        | 6.45%   |
| 2012    | 29        | 6.24%   |
| 2013    | 28        | 6.02%   |
| 2017    | 25        | 5.38%   |
| 2015    | 25        | 5.38%   |
| 2010    | 22        | 4.73%   |
| 2016    | 21        | 4.52%   |
| 2009    | 21        | 4.52%   |
| 2022    | 20        | 4.3%    |
| 2008    | 12        | 2.58%   |
| 2007    | 10        | 2.15%   |
| 2006    | 8         | 1.72%   |
| 2023    | 7         | 1.51%   |
| 2024    | 5         | 1.08%   |
| Unknown | 3         | 0.65%   |
| 2004    | 2         | 0.43%   |
| 2005    | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 289       | 62.15%  |
| Desktop        | 150       | 32.26%  |
| All in one     | 7         | 1.51%   |
| Convertible    | 5         | 1.08%   |
| System on chip | 4         | 0.86%   |
| Tablet         | 4         | 0.86%   |
| Mini pc        | 4         | 0.86%   |
| Server         | 2         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 440       | 93.62%  |
| Enabled  | 30        | 6.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 465       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 117       | 24.63%  |
| 4.01-8.0    | 97        | 20.42%  |
| 8.01-16.0   | 87        | 18.32%  |
| 3.01-4.0    | 86        | 18.11%  |
| 32.01-64.0  | 42        | 8.84%   |
| 1.01-2.0    | 17        | 3.58%   |
| 64.01-256.0 | 12        | 2.53%   |
| 2.01-3.0    | 8         | 1.68%   |
| 24.01-32.0  | 6         | 1.26%   |
| 0.51-1.0    | 3         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 152       | 27.99%  |
| 2.01-3.0   | 132       | 24.31%  |
| 4.01-8.0   | 104       | 19.15%  |
| 3.01-4.0   | 72        | 13.26%  |
| 0.51-1.0   | 40        | 7.37%   |
| 8.01-16.0  | 27        | 4.97%   |
| 0.01-0.5   | 7         | 1.29%   |
| 16.01-24.0 | 5         | 0.92%   |
| 24.01-32.0 | 3         | 0.55%   |
| 32.01-64.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 291       | 60.37%  |
| 2       | 130       | 26.97%  |
| 3       | 36        | 7.47%   |
| 4       | 12        | 2.49%   |
| 5       | 7         | 1.45%   |
| 0       | 3         | 0.62%   |
| 6       | 2         | 0.41%   |
| Unknown | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 311       | 65.89%  |
| Yes       | 161       | 34.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 409       | 87.77%  |
| No        | 57        | 12.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 349       | 74.41%  |
| No        | 120       | 25.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 286       | 60.59%  |
| No        | 186       | 39.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Lithuania | 465       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Vilnius       | 244       | 50.52%  |
| Kaunas        | 78        | 16.15%  |
| Klaipėda     | 33        | 6.83%   |
| Šiauliai     | 27        | 5.59%   |
| Mažeikiai    | 15        | 3.11%   |
| Alytus        | 9         | 1.86%   |
| Panevezys     | 6         | 1.24%   |
| Telšiai      | 4         | 0.83%   |
| Kėdainiai    | 4         | 0.83%   |
| Jonava        | 4         | 0.83%   |
| Utena         | 3         | 0.62%   |
| Trakai        | 3         | 0.62%   |
| Tauragė      | 3         | 0.62%   |
| Šilalė      | 3         | 0.62%   |
| Gargždai     | 3         | 0.62%   |
| Anykščiai   | 3         | 0.62%   |
| Visaginas     | 2         | 0.41%   |
| Ukmerge       | 2         | 0.41%   |
| Rokiškis     | 2         | 0.41%   |
| Plungė       | 2         | 0.41%   |
| Palanga       | 2         | 0.41%   |
| Marijampolė  | 2         | 0.41%   |
| Elektrėnai   | 2         | 0.41%   |
| Agluonenai    | 2         | 0.41%   |
| Želva        | 1         | 0.21%   |
| Zapyškis     | 1         | 0.21%   |
| Vėžaičiai  | 1         | 0.21%   |
| Vainutas      | 1         | 0.21%   |
| Širvintos    | 1         | 0.21%   |
| Serdokai      | 1         | 0.21%   |
| Šeduva       | 1         | 0.21%   |
| Šalčininkai | 1         | 0.21%   |
| Rietavas      | 1         | 0.21%   |
| Raseiniai     | 1         | 0.21%   |
| Pasvalys      | 1         | 0.21%   |
| Pakruojis     | 1         | 0.21%   |
| Nemenčinė   | 1         | 0.21%   |
| Molėtai      | 1         | 0.21%   |
| Mauruciai     | 1         | 0.21%   |
| Maneikiai     | 1         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 116       | 190    | 17.06%  |
| WDC                          | 82        | 114    | 12.06%  |
| Seagate                      | 72        | 94     | 10.59%  |
| Kingston                     | 51        | 72     | 7.5%    |
| Toshiba                      | 50        | 68     | 7.35%   |
| A-DATA Technology            | 36        | 41     | 5.29%   |
| SanDisk                      | 33        | 37     | 4.85%   |
| Crucial                      | 25        | 32     | 3.68%   |
| Unknown                      | 22        | 44     | 3.24%   |
| Hitachi                      | 19        | 26     | 2.79%   |
| Patriot                      | 17        | 18     | 2.5%    |
| Intel                        | 17        | 21     | 2.5%    |
| SK hynix                     | 13        | 14     | 1.91%   |
| Micron Technology            | 11        | 12     | 1.62%   |
| HGST                         | 9         | 11     | 1.32%   |
| SPCC                         | 7         | 13     | 1.03%   |
| China                        | 7         | 9      | 1.03%   |
| KIOXIA                       | 6         | 8      | 0.88%   |
| MAXIO Technology (Hangzhou)  | 5         | 10     | 0.74%   |
| Apacer                       | 4         | 6      | 0.59%   |
| XrayDisk                     | 3         | 3      | 0.44%   |
| Plextor                      | 3         | 3      | 0.44%   |
| Micron/Crucial Technology    | 3         | 5      | 0.44%   |
| Kingston Technology Company  | 3         | 3      | 0.44%   |
| GOODRAM                      | 3         | 3      | 0.44%   |
| Corsair                      | 3         | 5      | 0.44%   |
| ADATA Technology             | 3         | 4      | 0.44%   |
| XPG                          | 2         | 2      | 0.29%   |
| Transcend                    | 2         | 2      | 0.29%   |
| Shenzhen Longsys Electronics | 2         | 4      | 0.29%   |
| PNY                          | 2         | 2      | 0.29%   |
| Phison Electronics           | 2         | 3      | 0.29%   |
| OCZ                          | 2         | 3      | 0.29%   |
| Lite-On Technology           | 2         | 2      | 0.29%   |
| Lexar                        | 2         | 3      | 0.29%   |
| KingSpec                     | 2         | 2      | 0.29%   |
| KingDian                     | 2         | 3      | 0.29%   |
| JMicron Technology           | 2         | 2      | 0.29%   |
| Intenso                      | 2         | 3      | 0.29%   |
| Hewlett-Packard              | 2         | 6      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                      | 9         | 1.23%   |
| Samsung SSD 850 EVO 250GB                            | 8         | 1.1%    |
| Kingston SV300S37A120G 120GB SSD                     | 8         | 1.1%    |
| Kingston SA400S37480G 480GB SSD                      | 8         | 1.1%    |
| Toshiba MQ01ABD100 1TB                               | 7         | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 7         | 0.96%   |
| Seagate ST500DM002-1BD142 500GB                      | 6         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 6         | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 6         | 0.82%   |
| Kingston SA400S37120G 120GB SSD                      | 6         | 0.82%   |
| A-DATA SU650 120GB SSD                               | 6         | 0.82%   |
| WDC WD20EFRX-68EUZN0 2TB                             | 5         | 0.69%   |
| Toshiba MQ01ABF050 500GB                             | 5         | 0.69%   |
| Seagate ST500LT012-1DG142 500GB                      | 5         | 0.69%   |
| SanDisk NVMe SSD Drive 256GB                         | 5         | 0.69%   |
| Samsung SSD 860 EVO 250GB                            | 5         | 0.69%   |
| Intel NVMe SSD Drive 512GB                           | 5         | 0.69%   |
| Unknown MMC Card  64GB                               | 4         | 0.55%   |
| Unknown MMC Card  128GB                              | 4         | 0.55%   |
| Toshiba BG3 NVMe SSD Controller 128GB                | 4         | 0.55%   |
| Seagate ST9500325AS 500GB                            | 4         | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB                       | 4         | 0.55%   |
| Samsung SSD 860 EVO 500GB                            | 4         | 0.55%   |
| Samsung SSD 860 EVO 1TB                              | 4         | 0.55%   |
| Samsung SSD 850 EVO 500GB                            | 4         | 0.55%   |
| Patriot Burst 480GB SSD                              | 4         | 0.55%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB   | 4         | 0.55%   |
| Crucial CT500MX500SSD1 500GB                         | 4         | 0.55%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 3         | 0.41%   |
| Unknown MMC Card  32GB                               | 3         | 0.41%   |
| Toshiba DT01ACA100 1TB                               | 3         | 0.41%   |
| Seagate ST750LM022 HN-M750MBB 752GB                  | 3         | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB                       | 3         | 0.41%   |
| SanDisk NVMe SSD Drive 500GB                         | 3         | 0.41%   |
| Samsung SSD 980 1TB                                  | 3         | 0.41%   |
| Samsung NVMe SSD Drive 500GB                         | 3         | 0.41%   |
| Samsung NVMe SSD Drive 256GB                         | 3         | 0.41%   |
| Samsung NVMe SSD Drive 1TB                           | 3         | 0.41%   |
| Samsung HD501LJ 500GB                                | 3         | 0.41%   |
| Patriot Burst 240GB SSD                              | 3         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 94     | 33.18%  |
| WDC                 | 65        | 94     | 29.95%  |
| Toshiba             | 32        | 43     | 14.75%  |
| Hitachi             | 19        | 26     | 8.76%   |
| Samsung Electronics | 13        | 30     | 5.99%   |
| HGST                | 9         | 11     | 4.15%   |
| ASMT                | 2         | 2      | 0.92%   |
| Unknown             | 1         | 1      | 0.46%   |
| JMicron Technology  | 1         | 1      | 0.46%   |
| Fujitsu             | 1         | 1      | 0.46%   |
| ExcelStor           | 1         | 1      | 0.46%   |
| Apple               | 1         | 2      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 53        | 87     | 20.38%  |
| Kingston            | 43        | 62     | 16.54%  |
| A-DATA Technology   | 30        | 35     | 11.54%  |
| Crucial             | 22        | 28     | 8.46%   |
| Patriot             | 17        | 18     | 6.54%   |
| SanDisk             | 10        | 11     | 3.85%   |
| WDC                 | 7         | 10     | 2.69%   |
| SPCC                | 7         | 13     | 2.69%   |
| China               | 7         | 9      | 2.69%   |
| SK hynix            | 6         | 7      | 2.31%   |
| Toshiba             | 5         | 7      | 1.92%   |
| Intel               | 5         | 5      | 1.92%   |
| Apacer              | 4         | 6      | 1.54%   |
| Plextor             | 3         | 3      | 1.15%   |
| GOODRAM             | 3         | 3      | 1.15%   |
| XrayDisk            | 2         | 2      | 0.77%   |
| Transcend           | 2         | 2      | 0.77%   |
| PNY                 | 2         | 2      | 0.77%   |
| OCZ                 | 2         | 3      | 0.77%   |
| Micron Technology   | 2         | 2      | 0.77%   |
| KingSpec            | 2         | 2      | 0.77%   |
| Intenso             | 2         | 3      | 0.77%   |
| Hewlett-Packard     | 2         | 6      | 0.77%   |
| Gigabyte Technology | 2         | 2      | 0.77%   |
| FORESEE             | 2         | 2      | 0.77%   |
| Dahua               | 2         | 3      | 0.77%   |
| Corsair             | 2         | 2      | 0.77%   |
| Unknown             | 1         | 1      | 0.38%   |
| Team                | 1         | 1      | 0.38%   |
| StoreJet            | 1         | 1      | 0.38%   |
| OWC                 | 1         | 2      | 0.38%   |
| Netac               | 1         | 1      | 0.38%   |
| LITEONIT            | 1         | 1      | 0.38%   |
| LITEON              | 1         | 2      | 0.38%   |
| Leven               | 1         | 3      | 0.38%   |
| KingDian            | 1         | 2      | 0.38%   |
| CT120BX5            | 1         | 1      | 0.38%   |
| Colorful            | 1         | 1      | 0.38%   |
| BR                  | 1         | 1      | 0.38%   |
| Apple               | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 230       | 354    | 37.34%  |
| HDD     | 193       | 306    | 31.33%  |
| NVMe    | 168       | 232    | 27.27%  |
| MMC     | 20        | 43     | 3.25%   |
| Unknown | 5         | 5      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 327       | 639    | 60.89%  |
| NVMe | 167       | 231    | 31.1%   |
| SAS  | 23        | 27     | 4.28%   |
| MMC  | 20        | 43     | 3.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 275       | 468    | 67.07%  |
| 0.51-1.0   | 102       | 145    | 24.88%  |
| 1.01-2.0   | 23        | 34     | 5.61%   |
| 3.01-4.0   | 6         | 8      | 1.46%   |
| 2.01-3.0   | 3         | 4      | 0.73%   |
| 4.01-10.0  | 1         | 1      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 146       | 28.68%  |
| 251-500        | 122       | 23.97%  |
| 501-1000       | 66        | 12.97%  |
| 1-20           | 39        | 7.66%   |
| 1001-2000      | 34        | 6.68%   |
| 51-100         | 32        | 6.29%   |
| 21-50          | 23        | 4.52%   |
| More than 3000 | 16        | 3.14%   |
| 2001-3000      | 16        | 3.14%   |
| Unknown        | 15        | 2.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 197       | 36.82%  |
| 21-50          | 84        | 15.7%   |
| 101-250        | 70        | 13.08%  |
| 51-100         | 63        | 11.78%  |
| 251-500        | 53        | 9.91%   |
| 501-1000       | 21        | 3.93%   |
| 1001-2000      | 20        | 3.74%   |
| Unknown        | 15        | 2.8%    |
| More than 3000 | 8         | 1.5%    |
| 2001-3000      | 4         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB                            | 3         | 7      | 5.56%   |
| WDC WD800AAJS-60PSA0 80GB                           | 2         | 2      | 3.7%    |
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 3.7%    |
| Toshiba MK3261GSYN 320GB                            | 2         | 2      | 3.7%    |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 1.85%   |
| WDC WD6400BPVT-80HXZT1 640GB                        | 1         | 1      | 1.85%   |
| WDC WD6400BPVT-22HXZT1 640GB                        | 1         | 2      | 1.85%   |
| WDC WD5000BEVT-24A0RT0 500GB                        | 1         | 1      | 1.85%   |
| WDC WD5000AAKX-001CA0 500GB                         | 1         | 1      | 1.85%   |
| WDC WD5000AAKS-00A7B2 500GB                         | 1         | 1      | 1.85%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 1.85%   |
| WDC WD1003FBYX-01Y7B0 1TB                           | 1         | 2      | 1.85%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 2      | 1.85%   |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 1.85%   |
| Toshiba MK1652GSX 160GB                             | 1         | 2      | 1.85%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1      | 1.85%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD               | 1         | 1      | 1.85%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 1.85%   |
| Seagate ST9640320AS 640GB                           | 1         | 2      | 1.85%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 1.85%   |
| Seagate ST500LX012-SSHD-8GB                         | 1         | 1      | 1.85%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 1.85%   |
| Seagate ST3250410AS 250GB                           | 1         | 1      | 1.85%   |
| Seagate ST3250318AS 250GB                           | 1         | 1      | 1.85%   |
| Seagate ST2000VX000-1CU164 2TB                      | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 850 EVO 250GB               | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 840 Series 500GB            | 1         | 3      | 1.85%   |
| Samsung Electronics HM641JI 640GB                   | 1         | 2      | 1.85%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 1.85%   |
| Samsung Electronics HD403LJ 400GB                   | 1         | 1      | 1.85%   |
| Samsung Electronics HD103SJ 1TB                     | 1         | 1      | 1.85%   |
| Samsung Electronics HD080HJ/ 80GB                   | 1         | 4      | 1.85%   |
| Plextor PX-128M6M 128GB SSD                         | 1         | 1      | 1.85%   |
| Micron Technology MTFDDAK512TBN-1AR15ABHA 512GB SSD | 1         | 1      | 1.85%   |
| Leven JAJS300M240C 240GB SSD                        | 1         | 3      | 1.85%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 1.85%   |
| Hitachi HTS547575A9E384 752GB                       | 1         | 1      | 1.85%   |
| Hitachi HTS545050KTA300 500GB                       | 1         | 1      | 1.85%   |
| Hitachi HTS545032B9A300 320GB                       | 1         | 1      | 1.85%   |
| Hitachi HTS545025B9A300 250GB                       | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 19     | 24.53%  |
| Seagate             | 7         | 8      | 13.21%  |
| Samsung Electronics | 7         | 13     | 13.21%  |
| Toshiba             | 6         | 9      | 11.32%  |
| Hitachi             | 5         | 5      | 9.43%   |
| SK hynix            | 3         | 3      | 5.66%   |
| A-DATA Technology   | 3         | 4      | 5.66%   |
| HGST                | 2         | 3      | 3.77%   |
| Plextor             | 1         | 1      | 1.89%   |
| Micron Technology   | 1         | 1      | 1.89%   |
| Leven               | 1         | 3      | 1.89%   |
| Kingston            | 1         | 1      | 1.89%   |
| ExcelStor           | 1         | 1      | 1.89%   |
| Crucial             | 1         | 1      | 1.89%   |
| Colorful            | 1         | 1      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 19     | 33.33%  |
| Seagate             | 7         | 8      | 17.95%  |
| Toshiba             | 6         | 9      | 15.38%  |
| Samsung Electronics | 5         | 9      | 12.82%  |
| Hitachi             | 5         | 5      | 12.82%  |
| HGST                | 2         | 3      | 5.13%   |
| ExcelStor           | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 54     | 70.83%  |
| SSD  | 13        | 18     | 27.08%  |
| NVMe | 1         | 1      | 2.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate ST3160812A 160GB    | 1         | 2      | 50%     |
| Hitachi HTS541010A9E680 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 266       | 511    | 52.47%  |
| Works    | 195       | 353    | 38.46%  |
| Malfunc  | 44        | 73     | 8.68%   |
| Failed   | 2         | 3      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 301       | 51.72%  |
| AMD                              | 86        | 14.78%  |
| Samsung Electronics              | 56        | 9.62%   |
| SanDisk                          | 29        | 4.98%   |
| Toshiba America Info Systems     | 13        | 2.23%   |
| Kingston Technology Company      | 11        | 1.89%   |
| ASMedia Technology               | 10        | 1.72%   |
| Micron Technology                | 9         | 1.55%   |
| ADATA Technology                 | 9         | 1.55%   |
| SK hynix                         | 7         | 1.2%    |
| Nvidia                           | 6         | 1.03%   |
| Micron/Crucial Technology        | 6         | 1.03%   |
| KIOXIA                           | 6         | 1.03%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.86%   |
| Phison Electronics               | 4         | 0.69%   |
| JMicron Technology               | 4         | 0.69%   |
| Shenzhen Longsys Electronics     | 3         | 0.52%   |
| Marvell Technology Group         | 3         | 0.52%   |
| Union Memory (Shenzhen)          | 2         | 0.34%   |
| Solidigm                         | 2         | 0.34%   |
| Realtek Semiconductor            | 2         | 0.34%   |
| Lite-On Technology               | 2         | 0.34%   |
| Yangtze Memory Technologies      | 1         | 0.17%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| OCZ Technology Group             | 1         | 0.17%   |
| O2 Micro                         | 1         | 0.17%   |
| LSI Logic / Symbios Logic        | 1         | 0.17%   |
| Broadcom / LSI                   | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 52        | 7.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 33        | 4.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27        | 4%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 21        | 3.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 2.81%   |
| AMD 400 Series Chipset SATA Controller                                         | 16        | 2.37%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 15        | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14        | 2.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 1.78%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 1.63%   |
| AMD 500 Series Chipset SATA Controller                                         | 11        | 1.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10        | 1.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 1.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 1.33%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 9         | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 8         | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 1.19%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 7         | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.04%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 6         | 0.89%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 0.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 0.74%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 0.74%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 322       | 55.52%  |
| NVMe | 167       | 28.79%  |
| IDE  | 55        | 9.48%   |
| RAID | 33        | 5.69%   |
| SAS  | 2         | 0.34%   |
| SCSI | 1         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 338       | 72.69%  |
| AMD    | 122       | 26.24%  |
| ARM    | 5         | 1.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 1.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 1.29%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.07%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 5         | 1.07%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 5         | 1.07%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 5         | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 1.07%   |
| AMD Ryzen 5 5600H with Radeon Graphics      | 5         | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 4         | 0.86%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 4         | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 0.86%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 0.86%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 4         | 0.86%   |
| ARM Processor                               | 4         | 0.86%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 4         | 0.86%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4         | 0.86%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 3         | 0.64%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 3         | 0.64%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 0.64%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 3         | 0.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.64%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 3         | 0.64%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.64%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 0.64%   |
| Intel Core i3-4000M CPU @ 2.40GHz           | 3         | 0.64%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 0.64%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 0.64%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3         | 0.64%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3         | 0.64%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 3         | 0.64%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3         | 0.64%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3         | 0.64%   |
| AMD FX-8350 Eight-Core Processor            | 3         | 0.64%   |
| AMD Custom APU 0405                         | 3         | 0.64%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.43%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 96        | 20.65%  |
| Intel Core i7           | 77        | 16.56%  |
| Intel Core i3           | 45        | 9.68%   |
| AMD Ryzen 5             | 45        | 9.68%   |
| Other                   | 38        | 8.17%   |
| AMD Ryzen 7             | 26        | 5.59%   |
| Intel Core 2 Duo        | 18        | 3.87%   |
| Intel Celeron           | 17        | 3.66%   |
| Intel Pentium           | 11        | 2.37%   |
| Intel Pentium Dual-Core | 8         | 1.72%   |
| Intel Atom              | 8         | 1.72%   |
| AMD Ryzen 9             | 8         | 1.72%   |
| Intel Xeon              | 6         | 1.29%   |
| AMD Ryzen 3             | 6         | 1.29%   |
| Intel Core i9           | 5         | 1.08%   |
| AMD Ryzen 7 PRO         | 5         | 1.08%   |
| AMD FX                  | 5         | 1.08%   |
| Intel Core 2            | 4         | 0.86%   |
| Intel Pentium 4         | 3         | 0.65%   |
| AMD Phenom II           | 3         | 0.65%   |
| AMD Athlon II X2        | 3         | 0.65%   |
| AMD A8                  | 3         | 0.65%   |
| Intel Pentium Silver    | 2         | 0.43%   |
| Intel Pentium D         | 2         | 0.43%   |
| Intel Genuine           | 2         | 0.43%   |
| AMD Phenom II X4        | 2         | 0.43%   |
| AMD E                   | 2         | 0.43%   |
| AMD Athlon 64 X2        | 2         | 0.43%   |
| Intel Pentium Gold      | 1         | 0.22%   |
| Intel Core m7           | 1         | 0.22%   |
| Intel Core 2 Quad       | 1         | 0.22%   |
| Intel Core              | 1         | 0.22%   |
| AMD Sempron             | 1         | 0.22%   |
| AMD Ryzen 5 PRO         | 1         | 0.22%   |
| AMD PRO A8              | 1         | 0.22%   |
| AMD C-60                | 1         | 0.22%   |
| AMD C-50                | 1         | 0.22%   |
| AMD Athlon II X4        | 1         | 0.22%   |
| AMD A6                  | 1         | 0.22%   |
| AMD A4                  | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 178       | 38.12%  |
| 4       | 155       | 33.19%  |
| 6       | 63        | 13.49%  |
| 8       | 44        | 9.42%   |
| 12      | 7         | 1.5%    |
| 1       | 6         | 1.28%   |
| 16      | 5         | 1.07%   |
| 10      | 4         | 0.86%   |
| 14      | 3         | 0.64%   |
| Unknown | 2         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 463       | 99.14%  |
| 2       | 3         | 0.64%   |
| Unknown | 1         | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 325       | 69.59%  |
| 1       | 140       | 29.98%  |
| Unknown | 2         | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 458       | 98.49%  |
| 32-bit         | 3         | 0.65%   |
| Unknown        | 3         | 0.65%   |
| 64-bit         | 1         | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 189       | 38.81%  |
| 0x306c3    | 24        | 4.93%   |
| 0x306a9    | 24        | 4.93%   |
| 0x206a7    | 24        | 4.93%   |
| 0x1067a    | 12        | 2.46%   |
| 0x806ea    | 11        | 2.26%   |
| 0x406e3    | 11        | 2.26%   |
| 0x806c1    | 9         | 1.85%   |
| 0x20655    | 9         | 1.85%   |
| 0x906e9    | 6         | 1.23%   |
| 0x806ec    | 6         | 1.23%   |
| 0x506e3    | 6         | 1.23%   |
| 0x40651    | 6         | 1.23%   |
| 0x306d4    | 6         | 1.23%   |
| 0x0a50000d | 6         | 1.23%   |
| 0x0a50000c | 6         | 1.23%   |
| 0x010000c8 | 6         | 1.23%   |
| 0x30678    | 5         | 1.03%   |
| 0x08701021 | 5         | 1.03%   |
| 0xa0652    | 4         | 0.82%   |
| 0x906ea    | 4         | 0.82%   |
| 0x20652    | 4         | 0.82%   |
| 0x08108109 | 4         | 0.82%   |
| 0x08001137 | 4         | 0.82%   |
| 0xa0653    | 3         | 0.62%   |
| 0x906ed    | 3         | 0.62%   |
| 0x806eb    | 3         | 0.62%   |
| 0x6fd      | 3         | 0.62%   |
| 0x08600106 | 3         | 0.62%   |
| 0x0800820d | 3         | 0.62%   |
| 0xf43      | 2         | 0.41%   |
| 0x706a1    | 2         | 0.41%   |
| 0x6f2      | 2         | 0.41%   |
| 0x406c3    | 2         | 0.41%   |
| 0x106e5    | 2         | 0.41%   |
| 0x10676    | 2         | 0.41%   |
| 0x0a50000b | 2         | 0.41%   |
| 0x0a404102 | 2         | 0.41%   |
| 0x0a404101 | 2         | 0.41%   |
| 0x0a201016 | 2         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 57        | 12.26%  |
| Haswell          | 45        | 9.68%   |
| Zen 3            | 36        | 7.74%   |
| IvyBridge        | 36        | 7.74%   |
| Unknown          | 34        | 7.31%   |
| SandyBridge      | 33        | 7.1%    |
| Skylake          | 25        | 5.38%   |
| Penryn           | 21        | 4.52%   |
| Zen 2            | 17        | 3.66%   |
| Westmere         | 17        | 3.66%   |
| Zen+             | 16        | 3.44%   |
| TigerLake        | 15        | 3.23%   |
| CometLake        | 14        | 3.01%   |
| Core             | 13        | 2.8%    |
| Silvermont       | 12        | 2.58%   |
| Zen              | 9         | 1.94%   |
| K10              | 9         | 1.94%   |
| Piledriver       | 8         | 1.72%   |
| Broadwell        | 8         | 1.72%   |
| NetBurst         | 5         | 1.08%   |
| Nehalem          | 5         | 1.08%   |
| Goldmont plus    | 5         | 1.08%   |
| Alderlake Hybrid | 5         | 1.08%   |
| Goldmont         | 4         | 0.86%   |
| Bobcat           | 4         | 0.86%   |
| K8 Hammer        | 2         | 0.43%   |
| Jaguar           | 2         | 0.43%   |
| Icelake          | 2         | 0.43%   |
| Bonnell          | 2         | 0.43%   |
| Tremont          | 1         | 0.22%   |
| Steamroller      | 1         | 0.22%   |
| K8 & K10 hybrid  | 1         | 0.22%   |
| Excavator        | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 260       | 46.26%  |
| Nvidia                           | 164       | 29.18%  |
| AMD                              | 136       | 24.2%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Matrox Electronics Systems       | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 4.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 3.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 2.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 2.39%   |
| Intel UHD Graphics 620                                                                   | 12        | 2.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.37%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 8         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.37%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.19%   |
| Intel HD Graphics 530                                                                    | 7         | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.19%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 1.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.02%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.85%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 5         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 0.85%   |
| Intel HD Graphics 620                                                                    | 5         | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.68%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 4         | 0.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.68%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.68%   |
| Intel HD Graphics 630                                                                    | 4         | 0.68%   |
| Intel HD Graphics 500                                                                    | 4         | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 171       | 36.38%  |
| 1 x AMD        | 99        | 21.06%  |
| 1 x Nvidia     | 84        | 17.87%  |
| Intel + Nvidia | 69        | 14.68%  |
| Intel + AMD    | 14        | 2.98%   |
| 2 x AMD        | 13        | 2.77%   |
| AMD + Nvidia   | 9         | 1.91%   |
| Other          | 6         | 1.28%   |
| 2 x Nvidia     | 2         | 0.43%   |
| 2 x Intel      | 1         | 0.21%   |
| 1 x SiS        | 1         | 0.21%   |
| 1 x Matrox     | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 368       | 76.83%  |
| Proprietary | 87        | 18.16%  |
| Unknown     | 24        | 5.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 255       | 52.47%  |
| 1.01-2.0   | 69        | 14.2%   |
| 0.01-0.5   | 54        | 11.11%  |
| 0.51-1.0   | 32        | 6.58%   |
| 3.01-4.0   | 31        | 6.38%   |
| 7.01-8.0   | 19        | 3.91%   |
| 5.01-6.0   | 16        | 3.29%   |
| 8.01-16.0  | 7         | 1.44%   |
| 2.01-3.0   | 2         | 0.41%   |
| 16.01-24.0 | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 74        | 14.45%  |
| AU Optronics            | 56        | 10.94%  |
| LG Display              | 52        | 10.16%  |
| BOE                     | 45        | 8.79%   |
| Chimei Innolux          | 44        | 8.59%   |
| Dell                    | 40        | 7.81%   |
| Lenovo                  | 25        | 4.88%   |
| Goldstar                | 24        | 4.69%   |
| Philips                 | 22        | 4.3%    |
| AOC                     | 21        | 4.1%    |
| Chi Mei Optoelectronics | 13        | 2.54%   |
| Hewlett-Packard         | 9         | 1.76%   |
| BenQ                    | 9         | 1.76%   |
| PANDA                   | 8         | 1.56%   |
| Ancor Communications    | 8         | 1.56%   |
| Apple                   | 7         | 1.37%   |
| Sony                    | 5         | 0.98%   |
| CSO                     | 5         | 0.98%   |
| Sharp                   | 4         | 0.78%   |
| Valve                   | 3         | 0.59%   |
| ASUSTek Computer        | 3         | 0.59%   |
| ViewSonic               | 2         | 0.39%   |
| NEC Computers           | 2         | 0.39%   |
| LG Philips              | 2         | 0.39%   |
| LG Electronics          | 2         | 0.39%   |
| Iiyama                  | 2         | 0.39%   |
| Acer                    | 2         | 0.39%   |
| Unknown (XXX)           | 1         | 0.2%    |
| Unknown (AAA)           | 1         | 0.2%    |
| Unknown                 | 1         | 0.2%    |
| Toshiba                 | 1         | 0.2%    |
| TMX                     | 1         | 0.2%    |
| Panasonic               | 1         | 0.2%    |
| MStar                   | 1         | 0.2%    |
| Mi                      | 1         | 0.2%    |
| Medion                  | 1         | 0.2%    |
| LGD                     | 1         | 0.2%    |
| KDC                     | 1         | 0.2%    |
| JDI                     | 1         | 0.2%    |
| InfoVision              | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 5         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.74%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.56%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 3         | 0.56%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 3         | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.56%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                     | 3         | 0.56%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.56%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 3         | 0.56%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.56%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                        | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.56%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                       | 3         | 0.56%   |
| Sony LCD Monitor MS_9005 1920x1080                                       | 2         | 0.37%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch        | 2         | 0.37%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 2         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.37%   |
| Samsung Electronics LCD Monitor C32HG7x 2560x1440                        | 2         | 0.37%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 2         | 0.37%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 2         | 0.37%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 2         | 0.37%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.37%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 2         | 0.37%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.37%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.37%   |
| LG Display LCD Monitor LGD03DE 1600x900 382x215mm 17.3-inch              | 2         | 0.37%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 2         | 0.37%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch             | 2         | 0.37%   |
| Lenovo P24h-2L LEN62B2 2560x1440 527x296mm 23.8-inch                     | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 233       | 47.36%  |
| 1366x768 (WXGA)    | 77        | 15.65%  |
| 2560x1440 (QHD)    | 33        | 6.71%   |
| 3840x2160 (4K)     | 27        | 5.49%   |
| 1600x900 (HD+)     | 23        | 4.67%   |
| 1280x1024 (SXGA)   | 20        | 4.07%   |
| 1280x800 (WXGA)    | 15        | 3.05%   |
| 1920x1200 (WUXGA)  | 11        | 2.24%   |
| 2560x1600          | 7         | 1.42%   |
| 3440x1440          | 6         | 1.22%   |
| 1440x900 (WXGA+)   | 6         | 1.22%   |
| 1680x1050 (WSXGA+) | 5         | 1.02%   |
| 2560x1080          | 4         | 0.81%   |
| 800x1280           | 3         | 0.61%   |
| Unknown            | 3         | 0.61%   |
| 3840x2400          | 2         | 0.41%   |
| 3840x1600          | 2         | 0.41%   |
| 3840x1080          | 2         | 0.41%   |
| 3000x2000          | 2         | 0.41%   |
| 2880x1800          | 2         | 0.41%   |
| 3200x1080          | 1         | 0.2%    |
| 3120x2080          | 1         | 0.2%    |
| 2880x1620          | 1         | 0.2%    |
| 2288x1287          | 1         | 0.2%    |
| 2160x1440          | 1         | 0.2%    |
| 1360x768           | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |
| 1024x768 (XGA)     | 1         | 0.2%    |
| 1024x600           | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 156       | 30.12%  |
| 24      | 47        | 9.07%   |
| 27      | 38        | 7.34%   |
| 13      | 38        | 7.34%   |
| 23      | 36        | 6.95%   |
| 14      | 35        | 6.76%   |
| 17      | 31        | 5.98%   |
| 21      | 28        | 5.41%   |
| Unknown | 15        | 2.9%    |
| 31      | 12        | 2.32%   |
| 19      | 11        | 2.12%   |
| 16      | 11        | 2.12%   |
| 12      | 10        | 1.93%   |
| 34      | 8         | 1.54%   |
| 18      | 7         | 1.35%   |
| 40      | 5         | 0.97%   |
| 20      | 4         | 0.77%   |
| 84      | 3         | 0.58%   |
| 7       | 3         | 0.58%   |
| 54      | 2         | 0.39%   |
| 25      | 2         | 0.39%   |
| 22      | 2         | 0.39%   |
| 11      | 2         | 0.39%   |
| 10      | 2         | 0.39%   |
| 142     | 1         | 0.19%   |
| 75      | 1         | 0.19%   |
| 72      | 1         | 0.19%   |
| 55      | 1         | 0.19%   |
| 52      | 1         | 0.19%   |
| 50      | 1         | 0.19%   |
| 37      | 1         | 0.19%   |
| 33      | 1         | 0.19%   |
| 32      | 1         | 0.19%   |
| 29      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 229       | 44.99%  |
| 501-600        | 110       | 21.61%  |
| 401-500        | 42        | 8.25%   |
| 351-400        | 35        | 6.88%   |
| 201-300        | 30        | 5.89%   |
| 601-700        | 18        | 3.54%   |
| Unknown        | 15        | 2.95%   |
| 701-800        | 10        | 1.96%   |
| 801-900        | 6         | 1.18%   |
| 1501-2000      | 5         | 0.98%   |
| 1001-1500      | 5         | 0.98%   |
| 1-100          | 3         | 0.59%   |
| More than 2000 | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 357       | 77.44%  |
| 16/10   | 52        | 11.28%  |
| 5/4     | 19        | 4.12%   |
| Unknown | 12        | 2.6%    |
| 21/9    | 9         | 1.95%   |
| 3/2     | 6         | 1.3%    |
| 0.67    | 3         | 0.65%   |
| 4/3     | 2         | 0.43%   |
| 1.00    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 153       | 29.77%  |
| 201-250        | 88        | 17.12%  |
| 81-90          | 62        | 12.06%  |
| 301-350        | 38        | 7.39%   |
| 151-200        | 24        | 4.67%   |
| 351-500        | 23        | 4.47%   |
| 121-130        | 20        | 3.89%   |
| 141-150        | 16        | 3.11%   |
| 251-300        | 15        | 2.92%   |
| Unknown        | 15        | 2.92%   |
| More than 1000 | 11        | 2.14%   |
| 111-120        | 11        | 2.14%   |
| 71-80          | 10        | 1.95%   |
| 61-70          | 9         | 1.75%   |
| 501-1000       | 6         | 1.17%   |
| 1-40           | 3         | 0.58%   |
| 131-140        | 3         | 0.58%   |
| 91-100         | 3         | 0.58%   |
| 51-60          | 2         | 0.39%   |
| 41-50          | 2         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 172       | 34.13%  |
| 121-160       | 156       | 30.95%  |
| 101-120       | 116       | 23.02%  |
| 161-240       | 31        | 6.15%   |
| Unknown       | 15        | 2.98%   |
| More than 240 | 8         | 1.59%   |
| 1-50          | 6         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 365       | 77.83%  |
| 2     | 75        | 15.99%  |
| 0     | 20        | 4.26%   |
| 3     | 9         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 258       | 37.07%  |
| Intel                             | 206       | 29.6%   |
| Qualcomm Atheros                  | 83        | 11.93%  |
| Broadcom                          | 44        | 6.32%   |
| MediaTek                          | 19        | 2.73%   |
| Broadcom Limited                  | 11        | 1.58%   |
| TP-Link                           | 8         | 1.15%   |
| Ralink                            | 7         | 1.01%   |
| Marvell Technology Group          | 7         | 1.01%   |
| Nvidia                            | 5         | 0.72%   |
| Ralink Technology                 | 4         | 0.57%   |
| Lenovo                            | 4         | 0.57%   |
| Qualcomm Atheros Communications   | 3         | 0.43%   |
| Qualcomm                          | 3         | 0.43%   |
| Microsoft                         | 3         | 0.43%   |
| D-Link                            | 3         | 0.43%   |
| Sierra Wireless                   | 2         | 0.29%   |
| Samsung Electronics               | 2         | 0.29%   |
| JMicron Technology                | 2         | 0.29%   |
| Huawei Technologies               | 2         | 0.29%   |
| Hewlett-Packard                   | 2         | 0.29%   |
| Fibocom                           | 2         | 0.29%   |
| Ericsson Business Mobile Networks | 2         | 0.29%   |
| Edimax Technology                 | 2         | 0.29%   |
| Dell                              | 2         | 0.29%   |
| ASIX Electronics                  | 2         | 0.29%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.14%   |
| U-Blox                            | 1         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.14%   |
| MOBILE                            | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| ASUSTek Computer                  | 1         | 0.14%   |
| Aquantia                          | 1         | 0.14%   |
| 3Com                              | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 179       | 21.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 3.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 19        | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 2.07%   |
| Intel Wi-Fi 6 AX200                                                    | 15        | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 14        | 1.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 1.7%    |
| Intel Wi-Fi 6 AX201                                                    | 14        | 1.7%    |
| Intel Wireless 8265 / 8275                                             | 12        | 1.46%   |
| Intel Wireless 7260                                                    | 12        | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 1.34%   |
| Intel Wireless 8260                                                    | 11        | 1.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 10        | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 1.09%   |
| Intel Wireless 7265                                                    | 9         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 9         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.97%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.73%   |
| Intel Wireless 3165                                                    | 6         | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.61%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 0.61%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.61%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 0.61%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 4         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 168       | 45.53%  |
| Qualcomm Atheros                | 65        | 17.62%  |
| Realtek Semiconductor           | 45        | 12.2%   |
| Broadcom                        | 31        | 8.4%    |
| MediaTek                        | 15        | 4.07%   |
| TP-Link                         | 8         | 2.17%   |
| Ralink                          | 7         | 1.9%    |
| Ralink Technology               | 4         | 1.08%   |
| Broadcom Limited                | 4         | 1.08%   |
| Qualcomm Atheros Communications | 3         | 0.81%   |
| Qualcomm                        | 3         | 0.81%   |
| Microsoft                       | 3         | 0.81%   |
| D-Link                          | 3         | 0.81%   |
| Sierra Wireless                 | 2         | 0.54%   |
| Fibocom                         | 2         | 0.54%   |
| Edimax Technology               | 2         | 0.54%   |
| Dell                            | 2         | 0.54%   |
| D-Link System                   | 1         | 0.27%   |
| ASUSTek Computer                | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 5.15%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 4.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 3.79%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 3.79%   |
| Intel Wireless 8265 / 8275                                              | 12        | 3.25%   |
| Intel Wireless 7260                                                     | 12        | 3.25%   |
| Intel Wireless 8260                                                     | 11        | 2.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 2.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 2.44%   |
| Intel Wireless 7265                                                     | 9         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.63%   |
| Intel Wireless 3165                                                     | 6         | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 5         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.36%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 1.08%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 4         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.81%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 3         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.81%   |
| Intel Wireless 3160                                                     | 3         | 0.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.81%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 240       | 55.43%  |
| Intel                         | 102       | 23.56%  |
| Qualcomm Atheros              | 32        | 7.39%   |
| Broadcom                      | 22        | 5.08%   |
| Marvell Technology Group      | 7         | 1.62%   |
| Broadcom Limited              | 7         | 1.62%   |
| Nvidia                        | 5         | 1.15%   |
| Lenovo                        | 4         | 0.92%   |
| MediaTek                      | 3         | 0.69%   |
| JMicron Technology            | 2         | 0.46%   |
| Huawei Technologies           | 2         | 0.46%   |
| ASIX Electronics              | 2         | 0.46%   |
| Samsung Electronics           | 1         | 0.23%   |
| OnePlus Technology (Shenzhen) | 1         | 0.23%   |
| MOBILE                        | 1         | 0.23%   |
| Aquantia                      | 1         | 0.23%   |
| 3Com                          | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 179       | 40.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 29        | 6.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 3.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 3.15%   |
| Realtek RTL8125 2.5GbE Controller                                              | 11        | 2.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.8%    |
| Intel I211 Gigabit Network Connection                                          | 8         | 1.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 5         | 1.12%   |
| Intel Ethernet Controller I225-V                                               | 5         | 1.12%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.12%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 1.12%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4         | 0.9%    |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 0.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 3         | 0.67%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 0.67%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 3         | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.45%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.45%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.45%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.45%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 411       | 53.45%  |
| WiFi     | 350       | 45.51%  |
| Modem    | 7         | 0.91%   |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 277       | 56.53%  |
| Ethernet | 212       | 43.27%  |
| Modem    | 1         | 0.2%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 273       | 58.33%  |
| 1     | 174       | 37.18%  |
| 3     | 10        | 2.14%   |
| 0     | 10        | 2.14%   |
| 5     | 1         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 461       | 98.93%  |
| Yes  | 5         | 1.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 126       | 43%     |
| Qualcomm Atheros Communications | 32        | 10.92%  |
| Realtek Semiconductor           | 23        | 7.85%   |
| IMC Networks                    | 21        | 7.17%   |
| Cambridge Silicon Radio         | 21        | 7.17%   |
| Foxconn / Hon Hai               | 18        | 6.14%   |
| Broadcom                        | 18        | 6.14%   |
| Apple                           | 8         | 2.73%   |
| Ralink                          | 4         | 1.37%   |
| Hewlett-Packard                 | 4         | 1.37%   |
| ASUSTek Computer                | 4         | 1.37%   |
| Lite-On Technology              | 3         | 1.02%   |
| Dell                            | 3         | 1.02%   |
| Toshiba                         | 2         | 0.68%   |
| Edimax Technology               | 2         | 0.68%   |
| USI                             | 1         | 0.34%   |
| TP-Link                         | 1         | 0.34%   |
| Taiyo Yuden                     | 1         | 0.34%   |
| MediaTek                        | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 49        | 16.72%  |
| Intel AX201 Bluetooth                               | 27        | 9.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 7.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 5.46%   |
| Realtek Bluetooth Radio                             | 15        | 5.12%   |
| Intel AX200 Bluetooth                               | 14        | 4.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 3.75%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 3.75%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.39%   |
| IMC Networks Wireless_Device                        | 6         | 2.05%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 2.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.71%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.37%   |
| Ralink RT3290 Bluetooth                             | 4         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.37%   |
| Intel AX211 Bluetooth                               | 4         | 1.37%   |
| Intel AX210 Bluetooth                               | 4         | 1.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.37%   |
| Apple Bluetooth Host Controller                     | 4         | 1.37%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 1.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.02%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 1.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.02%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 1.02%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.68%   |
| IMC Networks Bluetooth Device                       | 2         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.68%   |
| Edimax Bluetooth Adapter                            | 2         | 0.68%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.68%   |
| Broadcom HP Portable Valentine                      | 2         | 0.68%   |
| Broadcom BCM2046 Bluetooth Device                   | 2         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.68%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 0.68%   |
| USI Bluetooth Device                                | 1         | 0.34%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 0.34%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 327       | 49.1%   |
| AMD                                             | 144       | 21.62%  |
| Nvidia                                          | 116       | 17.42%  |
| C-Media Electronics                             | 11        | 1.65%   |
| JMTek                                           | 8         | 1.2%    |
| Logitech                                        | 5         | 0.75%   |
| Lenovo                                          | 4         | 0.6%    |
| ASUSTek Computer                                | 4         | 0.6%    |
| Texas Instruments                               | 3         | 0.45%   |
| Realtek Semiconductor                           | 3         | 0.45%   |
| Kingston Technology                             | 3         | 0.45%   |
| Hewlett-Packard                                 | 3         | 0.45%   |
| Creative Technology                             | 3         | 0.45%   |
| Yamaha                                          | 2         | 0.3%    |
| SteelSeries ApS                                 | 2         | 0.3%    |
| Sony                                            | 2         | 0.3%    |
| Razer USA                                       | 2         | 0.3%    |
| PreSonus Audio Electronics                      | 2         | 0.3%    |
| GN Netcom                                       | 2         | 0.3%    |
| Generalplus Technology                          | 2         | 0.3%    |
| Focusrite-Novation                              | 2         | 0.3%    |
| Creative Labs                                   | 2         | 0.3%    |
| XMOS                                            | 1         | 0.15%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.15%   |
| Sennheiser Communications                       | 1         | 0.15%   |
| Schiit Audio                                    | 1         | 0.15%   |
| Panasonic (Matsushita)                          | 1         | 0.15%   |
| Native Instruments                              | 1         | 0.15%   |
| Microsoft                                       | 1         | 0.15%   |
| Micro Star International                        | 1         | 0.15%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.15%   |
| DSEA A/S                                        | 1         | 0.15%   |
| Comtrue                                         | 1         | 0.15%   |
| Beijing Chushifengmang Technology Development   | 1         | 0.15%   |
| Audio-Technica                                  | 1         | 0.15%   |
| Allen&Heath                                     | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 56        | 7.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35        | 4.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 33        | 4.14%   |
| Intel Sunrise Point-LP HD Audio                                            | 32        | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 4.01%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 31        | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23        | 2.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19        | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19        | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 18        | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 15        | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15        | 1.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14        | 1.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 13        | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1.38%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 1.25%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10        | 1.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.13%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.13%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 8         | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1%      |
| Intel Broadwell-U Audio Controller                                         | 8         | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 0.88%   |
| JMTek USB PnP Audio Device                                                 | 7         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 0.88%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6         | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.63%   |
| Nvidia AD107 High Definition Audio Controller                              | 5         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 73        | 21.99%  |
| Kingston                     | 52        | 15.66%  |
| SK hynix                     | 45        | 13.55%  |
| Micron Technology            | 32        | 9.64%   |
| Unknown                      | 24        | 7.23%   |
| G.Skill                      | 21        | 6.33%   |
| Crucial                      | 19        | 5.72%   |
| Ramaxel Technology           | 10        | 3.01%   |
| Patriot                      | 10        | 3.01%   |
| A-DATA Technology            | 8         | 2.41%   |
| Corsair                      | 7         | 2.11%   |
| Nanya Technology             | 6         | 1.81%   |
| Elpida                       | 6         | 1.81%   |
| Unknown (ABCD)               | 4         | 1.2%    |
| GOODRAM                      | 4         | 1.2%    |
| Transcend                    | 3         | 0.9%    |
| Team                         | 3         | 0.9%    |
| Lexar                        | 2         | 0.6%    |
| Patriot Memory (PDP Systems) | 1         | 0.3%    |
| Atermiter                    | 1         | 0.3%    |
| Unknown                      | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.4%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 4         | 1.12%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 1.12%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.12%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s               | 4         | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.84%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.84%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.84%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.84%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.84%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 3         | 0.84%   |
| Patriot RAM 3200 C16 Series 4GB DIMM DDR4 3600MT/s               | 3         | 0.84%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.84%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 3         | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.56%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s             | 2         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.56%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.56%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.56%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.56%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.56%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                  | 2         | 0.56%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.56%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s       | 2         | 0.56%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.56%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.56%   |
| Kingston RAM MSI16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s           | 2         | 0.56%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s                 | 2         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 117       | 41.49%  |
| DDR3    | 105       | 37.23%  |
| LPDDR4  | 12        | 4.26%   |
| DDR2    | 12        | 4.26%   |
| DDR5    | 11        | 3.9%    |
| Unknown | 7         | 2.48%   |
| SDRAM   | 6         | 2.13%   |
| LPDDR3  | 6         | 2.13%   |
| LPDDR5  | 3         | 1.06%   |
| DDR     | 2         | 0.71%   |
| DRAM    | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 173       | 62.23%  |
| DIMM         | 93        | 33.45%  |
| Row Of Chips | 12        | 4.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 120       | 40%     |
| 4096  | 87        | 29%     |
| 16384 | 44        | 14.67%  |
| 2048  | 28        | 9.33%   |
| 32768 | 10        | 3.33%   |
| 1024  | 7         | 2.33%   |
| 512   | 4         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 73        | 23.47%  |
| 3200    | 48        | 15.43%  |
| 2667    | 46        | 14.79%  |
| 1333    | 19        | 6.11%   |
| 1334    | 15        | 4.82%   |
| 2400    | 13        | 4.18%   |
| 2133    | 13        | 4.18%   |
| 667     | 8         | 2.57%   |
| 800     | 7         | 2.25%   |
| 4800    | 6         | 1.93%   |
| 3600    | 6         | 1.93%   |
| 1867    | 6         | 1.93%   |
| 1067    | 5         | 1.61%   |
| 6400    | 4         | 1.29%   |
| 5600    | 4         | 1.29%   |
| 3800    | 4         | 1.29%   |
| Unknown | 4         | 1.29%   |
| 4267    | 3         | 0.96%   |
| 3866    | 3         | 0.96%   |
| 2666    | 3         | 0.96%   |
| 3733    | 2         | 0.64%   |
| 3266    | 2         | 0.64%   |
| 2934    | 2         | 0.64%   |
| 2800    | 2         | 0.64%   |
| 1066    | 2         | 0.64%   |
| 400     | 2         | 0.64%   |
| 333     | 2         | 0.64%   |
| 4266    | 1         | 0.32%   |
| 3400    | 1         | 0.32%   |
| 3066    | 1         | 0.32%   |
| 3000    | 1         | 0.32%   |
| 2933    | 1         | 0.32%   |
| 2734    | 1         | 0.32%   |
| 2048    | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 50%     |
| Hewlett-Packard     | 3         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 16.67%  |
| Samsung ML-1670 Series  | 1         | 16.67%  |
| Samsung M2070 Series    | 1         | 16.67%  |
| HP PSC-1315/PSC-1317    | 1         | 16.67%  |
| HP LaserJet 1020        | 1         | 16.67%  |
| HP LaserJet 1000        | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 62        | 20.33%  |
| IMC Networks                           | 45        | 14.75%  |
| Microdia                               | 23        | 7.54%   |
| Sunplus Innovation Technology          | 19        | 6.23%   |
| Logitech                               | 18        | 5.9%    |
| Bison Electronics                      | 17        | 5.57%   |
| Realtek Semiconductor                  | 16        | 5.25%   |
| Suyin                                  | 13        | 4.26%   |
| Luxvisions Innotech Limited            | 9         | 2.95%   |
| Apple                                  | 9         | 2.95%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.62%   |
| Alcor Micro                            | 8         | 2.62%   |
| Syntek                                 | 7         | 2.3%    |
| Quanta                                 | 6         | 1.97%   |
| Sonix Technology                       | 4         | 1.31%   |
| Lite-On Technology                     | 4         | 1.31%   |
| Acer                                   | 4         | 1.31%   |
| Silicon Motion                         | 3         | 0.98%   |
| Lenovo                                 | 3         | 0.98%   |
| Samsung Electronics                    | 2         | 0.66%   |
| Panasonic (Matsushita)                 | 2         | 0.66%   |
| OmniVision Technologies                | 2         | 0.66%   |
| Genesys Logic                          | 2         | 0.66%   |
| DigiTech                               | 2         | 0.66%   |
| Z-Star Microelectronics                | 1         | 0.33%   |
| SunplusIT                              | 1         | 0.33%   |
| ShineTech                              | 1         | 0.33%   |
| Ricoh                                  | 1         | 0.33%   |
| Razer USA                              | 1         | 0.33%   |
| Qtech                                  | 1         | 0.33%   |
| Primax Electronics                     | 1         | 0.33%   |
| Pixart Imaging                         | 1         | 0.33%   |
| MTD                                    | 1         | 0.33%   |
| Intel                                  | 1         | 0.33%   |
| Importek                               | 1         | 0.33%   |
| Huawei Technologies                    | 1         | 0.33%   |
| Generalplus Technology                 | 1         | 0.33%   |
| Cubeternet                             | 1         | 0.33%   |
| Creative Technology                    | 1         | 0.33%   |
| Arkmicro Technologies                  | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 22        | 7.21%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 15        | 4.92%   |
| IMC Networks Integrated Camera                    | 13        | 4.26%   |
| Microdia Integrated_Webcam_HD                     | 9         | 2.95%   |
| Sunplus Integrated_Webcam_HD                      | 7         | 2.3%    |
| Realtek Integrated_Webcam_HD                      | 5         | 1.64%   |
| Bison Integrated Camera                           | 5         | 1.64%   |
| Syntek Lenovo EasyCamera                          | 4         | 1.31%   |
| Logitech Webcam C270                              | 4         | 1.31%   |
| Alcor Micro USB 2.0 Camera                        | 4         | 1.31%   |
| Sunplus HP HD Webcam [Fixed]                      | 3         | 0.98%   |
| Sonix USB2.0 HD UVC WebCam                        | 3         | 0.98%   |
| Microdia Integrated Webcam                        | 3         | 0.98%   |
| Luxvisions Innotech Limited Integrated Camera     | 3         | 0.98%   |
| Luxvisions Innotech Limited HP HD Camera          | 3         | 0.98%   |
| IMC Networks UVC VGA Webcam                       | 3         | 0.98%   |
| IMC Networks 2M Integrated Webcam                 | 3         | 0.98%   |
| Chicony USB2.0 HD UVC WebCam                      | 3         | 0.98%   |
| Chicony ThinkPad T490 Webcam                      | 3         | 0.98%   |
| Apple Built-in iSight                             | 3         | 0.98%   |
| Suyin Laptop_Integrated_Webcam_HD                 | 2         | 0.66%   |
| Suyin HP Webcam                                   | 2         | 0.66%   |
| Suyin 1.3M HD WebCam                              | 2         | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 2         | 0.66%   |
| Sunplus HD WebCam                                 | 2         | 0.66%   |
| Sunplus Asus Webcam                               | 2         | 0.66%   |
| Silicon Motion Lenovo EasyCamera                  | 2         | 0.66%   |
| Samsung Galaxy series, misc. (MTP mode)           | 2         | 0.66%   |
| Realtek USB Camera                                | 2         | 0.66%   |
| Quanta HD User Facing                             | 2         | 0.66%   |
| Panasonic (Matsushita) TY-CC20W                   | 2         | 0.66%   |
| Microdia Webcam Vitade AF                         | 2         | 0.66%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 2         | 0.66%   |
| Logitech HD Webcam C615                           | 2         | 0.66%   |
| Logitech HD Pro Webcam C920                       | 2         | 0.66%   |
| Logitech C922 Pro Stream Webcam                   | 2         | 0.66%   |
| Lite-On Integrated Camera                         | 2         | 0.66%   |
| IMC Networks VGA UVC WebCam                       | 2         | 0.66%   |
| IMC Networks USB2.0 UVC HD Webcam                 | 2         | 0.66%   |
| Chicony Webcam                                    | 2         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 21        | 35%     |
| Validity Sensors           | 20        | 33.33%  |
| Shenzhen Goodix Technology | 7         | 11.67%  |
| Elan Microelectronics      | 4         | 6.67%   |
| AuthenTec                  | 4         | 6.67%   |
| STMicroelectronics         | 2         | 3.33%   |
| Upek                       | 1         | 1.67%   |
| LighTuning Technology      | 1         | 1.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 11        | 18.33%  |
| Validity Sensors VFS471 Fingerprint Reader                  | 4         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 3         | 5%      |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 3         | 5%      |
| Shenzhen Goodix  Fingerprint Device                         | 3         | 5%      |
| Shenzhen Goodix Fingerprint Reader                          | 3         | 5%      |
| Elan ELAN:Fingerprint                                       | 3         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader                 | 2         | 3.33%   |
| Validity Sensors Fingerprint scanner                        | 2         | 3.33%   |
| Synaptics UWP WBDI Device                                   | 2         | 3.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 2         | 3.33%   |
| STMicroelectronics Fingerprint Reader                       | 2         | 3.33%   |
| AuthenTec AES2810                                           | 2         | 3.33%   |
| AuthenTec AES1600                                           | 2         | 3.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 1         | 1.67%   |
| Validity Sensors VFS491                                     | 1         | 1.67%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 1         | 1.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 1.67%   |
| Validity Sensors Synaptics WBDI                             | 1         | 1.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 1.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 1         | 1.67%   |
| Synaptics UWP WBDI                                          | 1         | 1.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 1.67%   |
| Synaptics Fingerprint reader [HP G6]                        | 1         | 1.67%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 1.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 1         | 1.67%   |
| Elan ELAN:ARM-M4                                            | 1         | 1.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 15        | 53.57%  |
| Broadcom              | 8         | 28.57%  |
| Gemalto (was Gemplus) | 3         | 10.71%  |
| Upek                  | 1         | 3.57%   |
| Microchip Technology  | 1         | 3.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 53.57%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 7.14%   |
| Broadcom 5880                                                                | 2         | 7.14%   |
| Broadcom 58200                                                               | 2         | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.57%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 3.57%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 3.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 334       | 70.32%  |
| 1     | 108       | 22.74%  |
| 2     | 23        | 4.84%   |
| 3     | 8         | 1.68%   |
| 7     | 1         | 0.21%   |
| 4     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 58        | 31.35%  |
| Graphics card            | 45        | 24.32%  |
| Chipcard                 | 25        | 13.51%  |
| Net/wireless             | 16        | 8.65%   |
| Multimedia controller    | 10        | 5.41%   |
| Bluetooth                | 9         | 4.86%   |
| Communication controller | 5         | 2.7%    |
| Camera                   | 5         | 2.7%    |
| Net/ethernet             | 3         | 1.62%   |
| Sound                    | 2         | 1.08%   |
| Network                  | 2         | 1.08%   |
| Card reader              | 2         | 1.08%   |
| Storage/raid             | 1         | 0.54%   |
| Storage                  | 1         | 0.54%   |
| Flash memory             | 1         | 0.54%   |

