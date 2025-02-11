Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 3753

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 09KPNV A00                  | [d2a1de9dc7](https://linux-hardware.org/?probe=d2a1de9dc7) | Jan 04, 2025 |
| ASRock        | J5040-ITX                   | [cfe9a3c37e](https://linux-hardware.org/?probe=cfe9a3c37e) | Dec 28, 2024 |
| Gigabyte      | H370M D3H-CF                | [293052fc3b](https://linux-hardware.org/?probe=293052fc3b) | Dec 24, 2024 |
| ASRock        | J5040-ITX                   | [30c96f3002](https://linux-hardware.org/?probe=30c96f3002) | Dec 19, 2024 |
| ASUSTek       | PRIME B760-PLUS D4          | [379d336bc2](https://linux-hardware.org/?probe=379d336bc2) | Dec 16, 2024 |
| OEM           | B75 Ver:1.41                | [26fc19a77d](https://linux-hardware.org/?probe=26fc19a77d) | Dec 15, 2024 |
| ASUSTek       | PRIME Z590-P                | [2e9144632c](https://linux-hardware.org/?probe=2e9144632c) | Dec 02, 2024 |
| HP            | 339A                        | [c64449a47e](https://linux-hardware.org/?probe=c64449a47e) | Dec 02, 2024 |
| ASRock        | B450M Pro4                  | [c865d51386](https://linux-hardware.org/?probe=c865d51386) | Nov 30, 2024 |
| MSI           | 880GM-E41                   | [d2d4d7473b](https://linux-hardware.org/?probe=d2d4d7473b) | Nov 26, 2024 |
| ASUSTek       | Rampage III GENE            | [89662fc2f1](https://linux-hardware.org/?probe=89662fc2f1) | Nov 23, 2024 |
| ASUSTek       | PRIME Z590-P                | [5b66a14834](https://linux-hardware.org/?probe=5b66a14834) | Nov 20, 2024 |
| Unknown       | Unknown                     | [69c39a72ba](https://linux-hardware.org/?probe=69c39a72ba) | Nov 18, 2024 |
| Acer          | FI946GZG                    | [a7f49035aa](https://linux-hardware.org/?probe=a7f49035aa) | Nov 16, 2024 |
| Acer          | FI946GZG                    | [9d9080e57a](https://linux-hardware.org/?probe=9d9080e57a) | Nov 16, 2024 |
| Dell          | 0KWVT8 A00                  | [cbf908cc03](https://linux-hardware.org/?probe=cbf908cc03) | Nov 13, 2024 |
| Gigabyte      | GA-MA78GM-DS2H              | [5b63d6de06](https://linux-hardware.org/?probe=5b63d6de06) | Nov 12, 2024 |
| HP            | 1495                        | [5778238fb5](https://linux-hardware.org/?probe=5778238fb5) | Nov 09, 2024 |
| ASUSTek       | Z8PE-D12-EMBEDDED           | [a71b3adfe4](https://linux-hardware.org/?probe=a71b3adfe4) | Nov 09, 2024 |
| ASUSTek       | Z8PE-D12-EMBEDDED           | [03ca590abe](https://linux-hardware.org/?probe=03ca590abe) | Nov 09, 2024 |
| Dell          | 01XK1W A00                  | [a66d7f6087](https://linux-hardware.org/?probe=a66d7f6087) | Nov 09, 2024 |
| Intel         | DH77KC AAG39641-400         | [7e99679aa4](https://linux-hardware.org/?probe=7e99679aa4) | Nov 07, 2024 |
| Dell          | 0V8WGR A00                  | [8b995d3611](https://linux-hardware.org/?probe=8b995d3611) | Nov 05, 2024 |
| HP            | 1495                        | [00133664ce](https://linux-hardware.org/?probe=00133664ce) | Nov 02, 2024 |
| ASRock        | B450 Pro4 R2.0              | [9db603450a](https://linux-hardware.org/?probe=9db603450a) | Nov 01, 2024 |
| Gigabyte      | H81M-S2H                    | [b93eb7acfd](https://linux-hardware.org/?probe=b93eb7acfd) | Oct 28, 2024 |
| IBASE Tech... | MB980VF B1                  | [0950d198d6](https://linux-hardware.org/?probe=0950d198d6) | Oct 27, 2024 |
| IBASE Tech... | MB980VF B1                  | [b7bff2d716](https://linux-hardware.org/?probe=b7bff2d716) | Oct 27, 2024 |
| Dell          | 01XK1W A00                  | [5226011358](https://linux-hardware.org/?probe=5226011358) | Oct 27, 2024 |
| Acer          | FI946GZG                    | [5938a70edc](https://linux-hardware.org/?probe=5938a70edc) | Oct 26, 2024 |
| Acer          | FI946GZG                    | [57835df373](https://linux-hardware.org/?probe=57835df373) | Oct 26, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [0642feaea1](https://linux-hardware.org/?probe=0642feaea1) | Oct 22, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [b13668c203](https://linux-hardware.org/?probe=b13668c203) | Oct 22, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [daf26b85a4](https://linux-hardware.org/?probe=daf26b85a4) | Oct 19, 2024 |
| MSI           | MS-7071                     | [6cf8497c89](https://linux-hardware.org/?probe=6cf8497c89) | Oct 16, 2024 |
| Dell          | 0GXM1W A02                  | [e8c22589e3](https://linux-hardware.org/?probe=e8c22589e3) | Oct 16, 2024 |
| Dell          | 0GXM1W A02                  | [e2cdb3ceef](https://linux-hardware.org/?probe=e2cdb3ceef) | Oct 16, 2024 |
| ASRock        | H610M-HVS                   | [91361cad1e](https://linux-hardware.org/?probe=91361cad1e) | Oct 10, 2024 |
| HP            | ProLiant MicroServer Gen... | [2927ff6f0d](https://linux-hardware.org/?probe=2927ff6f0d) | Oct 09, 2024 |
| Acer          | FI946GZG                    | [92bd6f1fc1](https://linux-hardware.org/?probe=92bd6f1fc1) | Oct 09, 2024 |
| Acer          | FI946GZG                    | [535a355530](https://linux-hardware.org/?probe=535a355530) | Oct 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | [d0eaae2f60](https://linux-hardware.org/?probe=d0eaae2f60) | Oct 09, 2024 |
| ASRock        | B450M Steel Legend          | [1abb05bf25](https://linux-hardware.org/?probe=1abb05bf25) | Oct 03, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [eca6363c57](https://linux-hardware.org/?probe=eca6363c57) | Oct 02, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [3b48795f8e](https://linux-hardware.org/?probe=3b48795f8e) | Sep 30, 2024 |
| HP            | 3397                        | [63009f600f](https://linux-hardware.org/?probe=63009f600f) | Sep 30, 2024 |
| Dell          | 0T065F A01                  | [bcbba2bc39](https://linux-hardware.org/?probe=bcbba2bc39) | Sep 21, 2024 |
| Acer          | FI946GZG                    | [38457fe3eb](https://linux-hardware.org/?probe=38457fe3eb) | Sep 20, 2024 |
| Acer          | FI946GZG                    | [7f888553ed](https://linux-hardware.org/?probe=7f888553ed) | Sep 20, 2024 |
| Gigabyte      | B75M-D3V                    | [b96fef78f4](https://linux-hardware.org/?probe=b96fef78f4) | Sep 20, 2024 |
| ASRock        | X570 Phantom Gaming X       | [075f6eaa32](https://linux-hardware.org/?probe=075f6eaa32) | Sep 19, 2024 |
| Lenovo        | SHARKBAY SDK0J40697 WIN     | [6d2a1ac8e1](https://linux-hardware.org/?probe=6d2a1ac8e1) | Sep 18, 2024 |
| Dell          | 01XK1W A00                  | [b1768b27cf](https://linux-hardware.org/?probe=b1768b27cf) | Sep 14, 2024 |
| Dell          | 0NNNCT A01                  | [c3aeffdb84](https://linux-hardware.org/?probe=c3aeffdb84) | Sep 13, 2024 |
| Intel         | CRESCENTBAY                 | [14865f8a73](https://linux-hardware.org/?probe=14865f8a73) | Sep 10, 2024 |
| ASUSTek       | H110M-K                     | [ff593c19ff](https://linux-hardware.org/?probe=ff593c19ff) | Sep 10, 2024 |
| iEi           | SAX9 V1.00                  | [d25454a2fb](https://linux-hardware.org/?probe=d25454a2fb) | Sep 10, 2024 |
| Dell          | 0NNNCT A01                  | [c5d73da3a3](https://linux-hardware.org/?probe=c5d73da3a3) | Sep 09, 2024 |
| ASUSTek       | PRIME H310M-K               | [4a801900e1](https://linux-hardware.org/?probe=4a801900e1) | Sep 09, 2024 |
| ASUSTek       | PRIME H310M-K               | [1c6ee65d7a](https://linux-hardware.org/?probe=1c6ee65d7a) | Sep 09, 2024 |
| ASUSTek       | P8Z68-V LX                  | [9d86f13601](https://linux-hardware.org/?probe=9d86f13601) | Sep 05, 2024 |
| HP            | 18E7                        | [dbea31ed81](https://linux-hardware.org/?probe=dbea31ed81) | Sep 02, 2024 |
| ASRock        | 970M Pro3                   | [5310dbbf32](https://linux-hardware.org/?probe=5310dbbf32) | Sep 01, 2024 |
| MSI           | B85M-G43                    | [374b7d32b3](https://linux-hardware.org/?probe=374b7d32b3) | Sep 01, 2024 |
| Dell          | 01XK1W A00                  | [6e978f31cf](https://linux-hardware.org/?probe=6e978f31cf) | Sep 01, 2024 |
| MSI           | X79A-GD45                   | [2f16c5924f](https://linux-hardware.org/?probe=2f16c5924f) | Aug 29, 2024 |
| ASUSTek       | P5B SE                      | [d545ce5d36](https://linux-hardware.org/?probe=d545ce5d36) | Aug 28, 2024 |
| Phoenix Co... | PSB514 A12                  | [b6636750fd](https://linux-hardware.org/?probe=b6636750fd) | Aug 25, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b4dc6d4025](https://linux-hardware.org/?probe=b4dc6d4025) | Aug 24, 2024 |
| ASRockRack    | E3C246D4U2-2T               | [c0a760b1bf](https://linux-hardware.org/?probe=c0a760b1bf) | Aug 23, 2024 |
| TYAN Compu... | S5553GM2NR-2T-HE-B          | [81952b8f97](https://linux-hardware.org/?probe=81952b8f97) | Aug 23, 2024 |
| ASUSTek       | M4N78-AM                    | [b8ac55c9e9](https://linux-hardware.org/?probe=b8ac55c9e9) | Aug 22, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [921ec4cff0](https://linux-hardware.org/?probe=921ec4cff0) | Aug 21, 2024 |
| ASRock        | X570 PG Velocita            | [a7fa96eb22](https://linux-hardware.org/?probe=a7fa96eb22) | Aug 21, 2024 |
| ASUSTek       | M4N78-AM                    | [c0fb89099b](https://linux-hardware.org/?probe=c0fb89099b) | Aug 20, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [48f20ce29b](https://linux-hardware.org/?probe=48f20ce29b) | Aug 19, 2024 |
| Dell          | 01XK1W A00                  | [3d467b94d9](https://linux-hardware.org/?probe=3d467b94d9) | Aug 14, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [5aba1832f5](https://linux-hardware.org/?probe=5aba1832f5) | Aug 11, 2024 |
| AZW           | MINI S 10                   | [62de36544b](https://linux-hardware.org/?probe=62de36544b) | Aug 08, 2024 |
| Dell          | 0GXM1W A00                  | [e80fba5694](https://linux-hardware.org/?probe=e80fba5694) | Aug 05, 2024 |
| ASUSTek       | PRIME Z590-P                | [caf4309fbe](https://linux-hardware.org/?probe=caf4309fbe) | Aug 02, 2024 |
| HP            | 1998                        | [718d1847d7](https://linux-hardware.org/?probe=718d1847d7) | Aug 01, 2024 |
| Gigabyte      | GA-78LMT-USB3               | [f9b69bff33](https://linux-hardware.org/?probe=f9b69bff33) | Jul 31, 2024 |
| Seco          | D62 B.1                     | [fa8221ca8a](https://linux-hardware.org/?probe=fa8221ca8a) | Jul 30, 2024 |
| Dell          | 0XFWHV A00                  | [9845091f7e](https://linux-hardware.org/?probe=9845091f7e) | Jul 28, 2024 |
| Gigabyte      | B85M-DS3H-A                 | [345e2f9291](https://linux-hardware.org/?probe=345e2f9291) | Jul 24, 2024 |
| Gigabyte      | B75M-D3H                    | [6bfee437e7](https://linux-hardware.org/?probe=6bfee437e7) | Jul 23, 2024 |
| Gigabyte      | B550M DS3H                  | [03179392b1](https://linux-hardware.org/?probe=03179392b1) | Jul 22, 2024 |
| Gigabyte      | B365M H                     | [b2bc363dc6](https://linux-hardware.org/?probe=b2bc363dc6) | Jul 22, 2024 |
| Dell          | 051FJ8 A02                  | [757139a0c9](https://linux-hardware.org/?probe=757139a0c9) | Jul 21, 2024 |
| ASUSTek       | VANGUARD B85                | [7453f3f267](https://linux-hardware.org/?probe=7453f3f267) | Jul 19, 2024 |
| IceWhale T... | ZBB001-BK10032 ZMB          | [334a362aba](https://linux-hardware.org/?probe=334a362aba) | Jul 19, 2024 |
| Dell          | 01XK1W A00                  | [52d8794632](https://linux-hardware.org/?probe=52d8794632) | Jul 11, 2024 |
| Dell          | 01XK1W A00                  | [cc46df44b5](https://linux-hardware.org/?probe=cc46df44b5) | Jul 07, 2024 |
| Unknown       | Unknown                     | [e298a5c2b9](https://linux-hardware.org/?probe=e298a5c2b9) | Jul 06, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [6cadfd61f0](https://linux-hardware.org/?probe=6cadfd61f0) | Jul 05, 2024 |
| HP            | 213D A01                    | [84f1dcac4f](https://linux-hardware.org/?probe=84f1dcac4f) | Jul 02, 2024 |
| Inventec      | D CLASS A02                 | [b12e2708ad](https://linux-hardware.org/?probe=b12e2708ad) | Jun 30, 2024 |
| Unknown       | CN700-8237                  | [696664c26e](https://linux-hardware.org/?probe=696664c26e) | Jun 30, 2024 |
| ASUSTek       | M4N78-AM                    | [dcacfa2dba](https://linux-hardware.org/?probe=dcacfa2dba) | Jun 30, 2024 |
| HP            | ProLiant MicroServer        | [9c05a4ef2d](https://linux-hardware.org/?probe=9c05a4ef2d) | Jun 20, 2024 |
| Dell          | 0F56WK A03                  | [98a85a6db0](https://linux-hardware.org/?probe=98a85a6db0) | Jun 19, 2024 |
| Gigabyte      | B760M H DDR4                | [8d6956f9a6](https://linux-hardware.org/?probe=8d6956f9a6) | Jun 17, 2024 |
| Gigabyte      | B760M H DDR4                | [3e87b834d6](https://linux-hardware.org/?probe=3e87b834d6) | Jun 17, 2024 |
| ASRock        | 970M Pro3                   | [8fbbbe6686](https://linux-hardware.org/?probe=8fbbbe6686) | Jun 05, 2024 |
| ASRock        | 970M Pro3                   | [eeb2f4e975](https://linux-hardware.org/?probe=eeb2f4e975) | Jun 05, 2024 |
| ASRock        | B450 Pro4 R2.0              | [f8ad181953](https://linux-hardware.org/?probe=f8ad181953) | Jun 02, 2024 |
| Acer          | FI946GZG                    | [76cc9c0af8](https://linux-hardware.org/?probe=76cc9c0af8) | Jun 01, 2024 |
| Acer          | FI946GZG                    | [0cfa96d8b2](https://linux-hardware.org/?probe=0cfa96d8b2) | May 19, 2024 |
| Acer          | FI946GZG                    | [6abf4b2ff8](https://linux-hardware.org/?probe=6abf4b2ff8) | May 18, 2024 |
| Acer          | FI946GZG                    | [a4b0b80358](https://linux-hardware.org/?probe=a4b0b80358) | May 18, 2024 |
| Acer          | FI946GZG                    | [988cb72164](https://linux-hardware.org/?probe=988cb72164) | May 18, 2024 |
| Unknown       | CN700-8237                  | [45ae7f3f3d](https://linux-hardware.org/?probe=45ae7f3f3d) | May 17, 2024 |
| ASUSTek       | M4N78-AM                    | [b4082fa5bc](https://linux-hardware.org/?probe=b4082fa5bc) | May 17, 2024 |
| Dell          | 01XK1W A00                  | [29e720dc59](https://linux-hardware.org/?probe=29e720dc59) | May 15, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [a3d788cabf](https://linux-hardware.org/?probe=a3d788cabf) | May 15, 2024 |
| ASUSTek       | P5PL2                       | [fba00cbc3b](https://linux-hardware.org/?probe=fba00cbc3b) | May 14, 2024 |
| ASUSTek       | P5PL2                       | [299b8ee2c4](https://linux-hardware.org/?probe=299b8ee2c4) | May 14, 2024 |
| Unknown       | 775V88+                     | [73f73bf5c8](https://linux-hardware.org/?probe=73f73bf5c8) | May 11, 2024 |
| MSI           | Z490-A PRO                  | [79ec6e2044](https://linux-hardware.org/?probe=79ec6e2044) | May 09, 2024 |
| ASUSTek       | P8Z77-V LX                  | [b245c99221](https://linux-hardware.org/?probe=b245c99221) | May 07, 2024 |
| ASRock        | B450M Pro4                  | [b1caabc9b5](https://linux-hardware.org/?probe=b1caabc9b5) | May 05, 2024 |
| ASUSTek       | H81M-K                      | [f4dbf33638](https://linux-hardware.org/?probe=f4dbf33638) | May 02, 2024 |
| Acer          | Aspire M5910                | [61b5809dc9](https://linux-hardware.org/?probe=61b5809dc9) | May 01, 2024 |
| MSI           | MAG B550M MORTAR MAX WIF... | [d486386bde](https://linux-hardware.org/?probe=d486386bde) | Apr 26, 2024 |
| Dell          | 01XK1W A00                  | [a5fcd90239](https://linux-hardware.org/?probe=a5fcd90239) | Apr 26, 2024 |
| Colorful T... | C.A68M-E V15                | [b0b7690daa](https://linux-hardware.org/?probe=b0b7690daa) | Apr 20, 2024 |
| Unknown       | i855-W83627HF               | [e1c3562c4a](https://linux-hardware.org/?probe=e1c3562c4a) | Apr 18, 2024 |
| Gigabyte      | X570 UD                     | [5240449916](https://linux-hardware.org/?probe=5240449916) | Apr 18, 2024 |
| ASRock        | B550 Pro4                   | [f906fa4f7c](https://linux-hardware.org/?probe=f906fa4f7c) | Apr 18, 2024 |
| HP            | 805B                        | [d5bf7c2652](https://linux-hardware.org/?probe=d5bf7c2652) | Apr 18, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | [0d46687bb7](https://linux-hardware.org/?probe=0d46687bb7) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [ba12ac8498](https://linux-hardware.org/?probe=ba12ac8498) | Apr 17, 2024 |
| AMI           | Cherry Trail CR             | [e60bc95699](https://linux-hardware.org/?probe=e60bc95699) | Apr 16, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | [7cad8d2493](https://linux-hardware.org/?probe=7cad8d2493) | Apr 16, 2024 |
| ASRock        | Z690 PG Riptide             | [b5891958b5](https://linux-hardware.org/?probe=b5891958b5) | Apr 12, 2024 |
| Gigabyte      | Z77X-UD3H                   | [716fbdb5b2](https://linux-hardware.org/?probe=716fbdb5b2) | Apr 12, 2024 |
| HP            | 1998                        | [c0b0ec87ec](https://linux-hardware.org/?probe=c0b0ec87ec) | Apr 10, 2024 |
| Lenovo        | 32E6 NOK                    | [b560c0d5fe](https://linux-hardware.org/?probe=b560c0d5fe) | Apr 09, 2024 |
| Lenovo        | 3740 NOK                    | [355c32d663](https://linux-hardware.org/?probe=355c32d663) | Apr 09, 2024 |
| Dell          | 01XK1W A00                  | [708da72614](https://linux-hardware.org/?probe=708da72614) | Apr 07, 2024 |
| MSI           | MS-B0A21                    | [e74fc30957](https://linux-hardware.org/?probe=e74fc30957) | Apr 05, 2024 |
| ASUSTek       | M5A97 PLUS                  | [b45101bd55](https://linux-hardware.org/?probe=b45101bd55) | Apr 02, 2024 |
| ASUSTek       | H110M-K                     | [8b3c41683d](https://linux-hardware.org/?probe=8b3c41683d) | Mar 30, 2024 |
| Gigabyte      | X570 UD                     | [539238d399](https://linux-hardware.org/?probe=539238d399) | Mar 29, 2024 |
| ASRock        | B550 Pro4                   | [9144eb7fe4](https://linux-hardware.org/?probe=9144eb7fe4) | Mar 29, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [d84d712a77](https://linux-hardware.org/?probe=d84d712a77) | Mar 29, 2024 |
| Dell          | 01XK1W A00                  | [6940ab6143](https://linux-hardware.org/?probe=6940ab6143) | Mar 24, 2024 |
| Dell          | 048DY8 A01                  | [05267117e8](https://linux-hardware.org/?probe=05267117e8) | Mar 23, 2024 |
| ASUSTek       | PRIME B760M-A D4            | [870960dbb0](https://linux-hardware.org/?probe=870960dbb0) | Mar 21, 2024 |
| Intel         | DB85FL AAG89861-201         | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| MSI           | Z97 GAMING 3                | [ed6f176128](https://linux-hardware.org/?probe=ed6f176128) | Mar 20, 2024 |
| ASUSTek       | PRIME Z590-P                | [73f72d473b](https://linux-hardware.org/?probe=73f72d473b) | Mar 19, 2024 |
| ASUSTek       | PRIME Z590-P                | [b526dd935f](https://linux-hardware.org/?probe=b526dd935f) | Mar 19, 2024 |
| JGINYUE       | X99-D8 Server V1.0          | [aad6effeb0](https://linux-hardware.org/?probe=aad6effeb0) | Mar 18, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [fecb6cf968](https://linux-hardware.org/?probe=fecb6cf968) | Mar 18, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | [e467a62b44](https://linux-hardware.org/?probe=e467a62b44) | Mar 18, 2024 |
| ASUSTek       | AT4NM10T-I                  | [6d006ade6c](https://linux-hardware.org/?probe=6d006ade6c) | Mar 13, 2024 |
| ASUSTek       | AT4NM10T-I                  | [f7ddcc5c64](https://linux-hardware.org/?probe=f7ddcc5c64) | Mar 13, 2024 |
| Intel         | X58 V1608                   | [48e5f0f5a6](https://linux-hardware.org/?probe=48e5f0f5a6) | Mar 13, 2024 |
| Intel         | X58 V1608                   | [84ccc96b6b](https://linux-hardware.org/?probe=84ccc96b6b) | Mar 13, 2024 |
| ASRock        | X570 Phantom Gaming X       | [2a14a96457](https://linux-hardware.org/?probe=2a14a96457) | Mar 12, 2024 |
| Supermicro    | X9DR3-F                     | [f4f1646c44](https://linux-hardware.org/?probe=f4f1646c44) | Mar 10, 2024 |
| ASUSTek       | PRIME H510M-E               | [35d70301d6](https://linux-hardware.org/?probe=35d70301d6) | Mar 04, 2024 |
| MSI           | A320M-A PRO                 | [e69e7cf8f3](https://linux-hardware.org/?probe=e69e7cf8f3) | Mar 02, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [f526190f31](https://linux-hardware.org/?probe=f526190f31) | Mar 01, 2024 |
| Pegatron      | IPM41-D3                    | [5249318369](https://linux-hardware.org/?probe=5249318369) | Feb 29, 2024 |
| ASUSTek       | M2N-E                       | [b3041e34a7](https://linux-hardware.org/?probe=b3041e34a7) | Feb 27, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [16759c3ced](https://linux-hardware.org/?probe=16759c3ced) | Feb 26, 2024 |
| ASUSTek       | M5A97 R2.0                  | [702dee066a](https://linux-hardware.org/?probe=702dee066a) | Feb 25, 2024 |
| ASRock        | B450 Steel Legend           | [ed5e87fbaf](https://linux-hardware.org/?probe=ed5e87fbaf) | Feb 21, 2024 |
| Dell          | 088DT1 A01                  | [2d163839aa](https://linux-hardware.org/?probe=2d163839aa) | Feb 21, 2024 |
| BESSTAR Te... | HM80                        | [ec826c4feb](https://linux-hardware.org/?probe=ec826c4feb) | Feb 20, 2024 |
| Dell          | 05842Y A00                  | [50fc41ef5c](https://linux-hardware.org/?probe=50fc41ef5c) | Feb 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | [64bdaa6db8](https://linux-hardware.org/?probe=64bdaa6db8) | Feb 15, 2024 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [56739f7004](https://linux-hardware.org/?probe=56739f7004) | Feb 15, 2024 |
| YANYU         | EPIC-C19                    | [9a93a8fd98](https://linux-hardware.org/?probe=9a93a8fd98) | Feb 12, 2024 |
| ASUSTek       | M5A97 R2.0                  | [2ef5e51010](https://linux-hardware.org/?probe=2ef5e51010) | Feb 12, 2024 |
| Intel         | X99 V1.0                    | [225644e904](https://linux-hardware.org/?probe=225644e904) | Feb 09, 2024 |
| MSI           | H110M PRO-VD                | [ba8e24ef8f](https://linux-hardware.org/?probe=ba8e24ef8f) | Feb 08, 2024 |
| ASRock        | G31M-GS                     | [50925f48af](https://linux-hardware.org/?probe=50925f48af) | Feb 06, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d8d66e42bc](https://linux-hardware.org/?probe=d8d66e42bc) | Feb 05, 2024 |
| HP            | 3397                        | [fcbc5b3ac6](https://linux-hardware.org/?probe=fcbc5b3ac6) | Jan 29, 2024 |
| ASUSTek       | PRIME B250M-C               | [5c34879ea0](https://linux-hardware.org/?probe=5c34879ea0) | Jan 28, 2024 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [b0019abd70](https://linux-hardware.org/?probe=b0019abd70) | Jan 26, 2024 |
| ASRock        | 970M Pro3                   | [f5a09bd7f0](https://linux-hardware.org/?probe=f5a09bd7f0) | Jan 23, 2024 |
| Inventec      | D CLASS A02                 | [25d4886028](https://linux-hardware.org/?probe=25d4886028) | Jan 22, 2024 |
| ASRock        | H61M-HVS                    | [3cfc574d2d](https://linux-hardware.org/?probe=3cfc574d2d) | Jan 22, 2024 |
| MACHINIST     | X99 PR9                     | [2cac18e4ae](https://linux-hardware.org/?probe=2cac18e4ae) | Jan 21, 2024 |
| ASRock        | 970M Pro3                   | [37613f1ec6](https://linux-hardware.org/?probe=37613f1ec6) | Jan 20, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [5b5d90211c](https://linux-hardware.org/?probe=5b5d90211c) | Jan 18, 2024 |
| ASRock        | J5040-ITX                   | [1d65e65b24](https://linux-hardware.org/?probe=1d65e65b24) | Jan 14, 2024 |
| ASRock        | C2750D4I                    | [c1426b3157](https://linux-hardware.org/?probe=c1426b3157) | Jan 14, 2024 |
| ASUSTek       | Z87-C                       | [acc914cabd](https://linux-hardware.org/?probe=acc914cabd) | Jan 12, 2024 |
| ASUSTek       | PRIME B350M-A               | [7eabdfe5d0](https://linux-hardware.org/?probe=7eabdfe5d0) | Jan 12, 2024 |
| HP            | 0B4Ch D                     | [d04339c0dc](https://linux-hardware.org/?probe=d04339c0dc) | Jan 12, 2024 |
| Dell          | 00V62H A01                  | [6f8302ddde](https://linux-hardware.org/?probe=6f8302ddde) | Jan 08, 2024 |
| MSI           | X79A-GD65                   | [55c0071638](https://linux-hardware.org/?probe=55c0071638) | Jan 06, 2024 |
| Dell          | 00V62H A01                  | [a44b8f65f6](https://linux-hardware.org/?probe=a44b8f65f6) | Jan 06, 2024 |
| Sapphire      | PI-AM3RS760G2               | [78696f8410](https://linux-hardware.org/?probe=78696f8410) | Jan 05, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [408830a147](https://linux-hardware.org/?probe=408830a147) | Jan 05, 2024 |
| Dell          | 01XK1W A00                  | [90e3c8644a](https://linux-hardware.org/?probe=90e3c8644a) | Jan 05, 2024 |
| Phoenix Co... | PSB514 A12                  | [424bbc0491](https://linux-hardware.org/?probe=424bbc0491) | Jan 03, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [ee8caab1b7](https://linux-hardware.org/?probe=ee8caab1b7) | Jan 03, 2024 |
| HP            | 1495                        | [48d0ae2bf5](https://linux-hardware.org/?probe=48d0ae2bf5) | Dec 30, 2023 |
| ASUSTek       | CM6870                      | [529b92f758](https://linux-hardware.org/?probe=529b92f758) | Dec 28, 2023 |
| Gigabyte      | P55-UD4P                    | [62b547894e](https://linux-hardware.org/?probe=62b547894e) | Dec 25, 2023 |
| eMachines     | EMCP61M                     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| HP            | 3396                        | [d0d084ecc8](https://linux-hardware.org/?probe=d0d084ecc8) | Dec 20, 2023 |
| Gigabyte      | Z77X-UD3H                   | [25a077d35e](https://linux-hardware.org/?probe=25a077d35e) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| ASRock        | 970M Pro3                   | [85233c464d](https://linux-hardware.org/?probe=85233c464d) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | [acebee7435](https://linux-hardware.org/?probe=acebee7435) | Dec 19, 2023 |
| Gigabyte      | X570S UD                    | [058c14cd39](https://linux-hardware.org/?probe=058c14cd39) | Dec 17, 2023 |
| Dell          | 0M5WNK A02                  | [f47a8fcf1f](https://linux-hardware.org/?probe=f47a8fcf1f) | Dec 15, 2023 |
| Acer          | Aspire 1510 Rev.A           | [452be93d1b](https://linux-hardware.org/?probe=452be93d1b) | Dec 13, 2023 |
| AZW           | MINI S                      | [2512b54e60](https://linux-hardware.org/?probe=2512b54e60) | Dec 09, 2023 |
| Dell          | 0KP561                      | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| Intel         | H61                         | [fbc4dc7436](https://linux-hardware.org/?probe=fbc4dc7436) | Dec 06, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| MSI           | A78M-E45                    | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | [af727ea890](https://linux-hardware.org/?probe=af727ea890) | Nov 29, 2023 |
| HC Technol... | HCAR5000-MI                 | [7ff2232073](https://linux-hardware.org/?probe=7ff2232073) | Nov 29, 2023 |
| MSI           | X299 GAMING PRO CARBON      | [07d105a830](https://linux-hardware.org/?probe=07d105a830) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| AZW           | MINI S                      | [ea6ad73049](https://linux-hardware.org/?probe=ea6ad73049) | Nov 27, 2023 |
| AZW           | MINI S                      | [54b3a350cc](https://linux-hardware.org/?probe=54b3a350cc) | Nov 27, 2023 |
| MSI           | B85M-G43                    | [c8c114c2df](https://linux-hardware.org/?probe=c8c114c2df) | Nov 26, 2023 |
| AZW           | U59                         | [b03056a1ad](https://linux-hardware.org/?probe=b03056a1ad) | Nov 24, 2023 |
| ASRock        | AB350 Pro4                  | [eff446af17](https://linux-hardware.org/?probe=eff446af17) | Nov 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [26da233e2b](https://linux-hardware.org/?probe=26da233e2b) | Nov 21, 2023 |
| Dell          | 0D6H9T A02                  | [034fe5ff39](https://linux-hardware.org/?probe=034fe5ff39) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| HP            | 1905                        | [7718b065fd](https://linux-hardware.org/?probe=7718b065fd) | Nov 20, 2023 |
| ASUSTek       | PRIME Z370-P                | [2ffe9e80d4](https://linux-hardware.org/?probe=2ffe9e80d4) | Nov 19, 2023 |
| ASUSTek       | M5A97                       | [e5673cd079](https://linux-hardware.org/?probe=e5673cd079) | Nov 18, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [1b1258a703](https://linux-hardware.org/?probe=1b1258a703) | Nov 17, 2023 |
| SIEMENS       | A5E49569366 RS-AF           | [07d3a028ec](https://linux-hardware.org/?probe=07d3a028ec) | Nov 17, 2023 |
| ASRock        | B550 Pro4                   | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| Dell          | 02YRK5 A02                  | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| WanYou        | WanYouChunXiao              | [82c62804fc](https://linux-hardware.org/?probe=82c62804fc) | Nov 13, 2023 |
| ASRock        | J3455-ITX                   | [29b6fb8a4f](https://linux-hardware.org/?probe=29b6fb8a4f) | Nov 11, 2023 |
| Acer          | EG43M                       | [53270970b2](https://linux-hardware.org/?probe=53270970b2) | Nov 09, 2023 |
| HPE           | ProLiant MicroServer Gen... | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Unknown       | Unknown                     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Unknown       | Unknown                     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| Dell          | 01XK1W A00                  | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| ASRock        | H170M Pro4                  | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| ASRock        | Z77 WS                      | [73b9354a1a](https://linux-hardware.org/?probe=73b9354a1a) | Nov 02, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | [b684f82e3c](https://linux-hardware.org/?probe=b684f82e3c) | Nov 01, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [2d90a96dfb](https://linux-hardware.org/?probe=2d90a96dfb) | Oct 31, 2023 |
| Gigabyte      | H170N-WIFI-CF               | [af90b19d11](https://linux-hardware.org/?probe=af90b19d11) | Oct 30, 2023 |
| Shenzhen M... | TH80                        | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| ASUSTek       | H81M-PLUS                   | [f1ee66826b](https://linux-hardware.org/?probe=f1ee66826b) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | [0f58ce148b](https://linux-hardware.org/?probe=0f58ce148b) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [36f77e9a81](https://linux-hardware.org/?probe=36f77e9a81) | Oct 24, 2023 |
| Gigabyte      | 990FXA-UD5                  | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| ASRock        | B550 Pro4                   | [0d55c2a6af](https://linux-hardware.org/?probe=0d55c2a6af) | Oct 20, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [745f21d8bc](https://linux-hardware.org/?probe=745f21d8bc) | Oct 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [67365133d9](https://linux-hardware.org/?probe=67365133d9) | Oct 17, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [d48d54a951](https://linux-hardware.org/?probe=d48d54a951) | Oct 16, 2023 |
| ASUSTek       | B85M-E                      | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| ASUSTek       | PRIME B550M-A               | [2686ddd07b](https://linux-hardware.org/?probe=2686ddd07b) | Oct 15, 2023 |
| Quantum en... | HackBoard 2                 | [27781c0b8a](https://linux-hardware.org/?probe=27781c0b8a) | Oct 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | [5f59c8dd03](https://linux-hardware.org/?probe=5f59c8dd03) | Oct 14, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| Dell          | 0T10XW A00                  | [1489eccd85](https://linux-hardware.org/?probe=1489eccd85) | Oct 12, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [925371c475](https://linux-hardware.org/?probe=925371c475) | Oct 11, 2023 |
| ASRock        | H61M-DGS                    | [b16ee3559a](https://linux-hardware.org/?probe=b16ee3559a) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0cbd266486](https://linux-hardware.org/?probe=0cbd266486) | Oct 11, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [8606120535](https://linux-hardware.org/?probe=8606120535) | Oct 10, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [0198bbbc8c](https://linux-hardware.org/?probe=0198bbbc8c) | Oct 10, 2023 |
| Gigabyte      | G31M-ES2L                   | [7912f11c78](https://linux-hardware.org/?probe=7912f11c78) | Oct 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b54dca932a](https://linux-hardware.org/?probe=b54dca932a) | Oct 07, 2023 |
| ASUSTek       | PRIME B365M-A               | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| ASRock        | H81M-HG4                    | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| ASRock        | 970M Pro3                   | [f004fa8e32](https://linux-hardware.org/?probe=f004fa8e32) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | [3646127006](https://linux-hardware.org/?probe=3646127006) | Sep 27, 2023 |
| Intel         | DP35DP AAD81073-206         | [426e9aff0f](https://linux-hardware.org/?probe=426e9aff0f) | Sep 26, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| MSI           | MS-7318                     | [0e03a1818a](https://linux-hardware.org/?probe=0e03a1818a) | Sep 24, 2023 |
| Acer          | H11H4-AI V:1.0              | [971f03180e](https://linux-hardware.org/?probe=971f03180e) | Sep 24, 2023 |
| HP            | 1905                        | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [85c3791741](https://linux-hardware.org/?probe=85c3791741) | Sep 21, 2023 |
| MSI           | MS-7318                     | [38f011e50d](https://linux-hardware.org/?probe=38f011e50d) | Sep 21, 2023 |
| NetGear       | ReadyDATA 5200              | [c96e63c738](https://linux-hardware.org/?probe=c96e63c738) | Sep 20, 2023 |
| ASRock        | B550 Pro4                   | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| Gigabyte      | H55N-USB3                   | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| Supermicro    | X9DR3-F                     | [c2f0532df1](https://linux-hardware.org/?probe=c2f0532df1) | Sep 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| Dell          | 01XK1W A00                  | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Gigabyte      | P85-D3                      | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| MSI           | 970A-G46                    | [722b900724](https://linux-hardware.org/?probe=722b900724) | Sep 11, 2023 |
| ASRock        | H81M-HG4                    | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| HP            | 876C SMVB                   | [f122d202cc](https://linux-hardware.org/?probe=f122d202cc) | Sep 10, 2023 |
| ASRock        | J3455-ITX                   | [724826d84b](https://linux-hardware.org/?probe=724826d84b) | Sep 09, 2023 |
| ASUSTek       | PRIME Z370-P                | [9ce78af6e9](https://linux-hardware.org/?probe=9ce78af6e9) | Sep 08, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Unknown       | Unknown                     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| MEGA          | G41T-M7 LGT                 | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7e93b2a981](https://linux-hardware.org/?probe=7e93b2a981) | Sep 02, 2023 |
| HP            | 1495                        | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| Dell          | 0T10XW A00                  | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| HP            | 1495                        | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| HP            | 158A                        | [e154a48901](https://linux-hardware.org/?probe=e154a48901) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| ASRock        | J4125B-ITX                  | [93853db701](https://linux-hardware.org/?probe=93853db701) | Aug 21, 2023 |
| ASRock        | J4125B-ITX                  | [f9058bcea1](https://linux-hardware.org/?probe=f9058bcea1) | Aug 21, 2023 |
| Medion        | MS-7728                     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
| Dell          | 0CT017                      | [0800c86065](https://linux-hardware.org/?probe=0800c86065) | Aug 14, 2023 |
| Unknown       | CN700-8237                  | [5890f075f7](https://linux-hardware.org/?probe=5890f075f7) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Gigabyte      | B360HD3PLM-CF               | [650f840aa5](https://linux-hardware.org/?probe=650f840aa5) | Aug 13, 2023 |
| Unknown       | Unknown                     | [a28cd220cd](https://linux-hardware.org/?probe=a28cd220cd) | Aug 12, 2023 |
| Unknown       | Unknown                     | [f62d9a8a9a](https://linux-hardware.org/?probe=f62d9a8a9a) | Aug 12, 2023 |
| ASRock        | J4125B-ITX                  | [fa9ebd523f](https://linux-hardware.org/?probe=fa9ebd523f) | Aug 11, 2023 |
| Lenovo        | 3740 NOK                    | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| HP            | 8433 11                     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| ASUSTek       | P5LD2-SE                    | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| Biostar       | B365MHC                     | [1a7d051f1e](https://linux-hardware.org/?probe=1a7d051f1e) | Aug 06, 2023 |
| Gigabyte      | 990FXA-UD3                  | [4b57f7d6ea](https://linux-hardware.org/?probe=4b57f7d6ea) | Aug 06, 2023 |
| MSI           | B350 TOMAHAWK               | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| ASRock        | FM2A68M-DG3+                | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [18f95b58ac](https://linux-hardware.org/?probe=18f95b58ac) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [349de8928b](https://linux-hardware.org/?probe=349de8928b) | Aug 04, 2023 |
| Gigabyte      | H510M H                     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| ASRock        | X300-ITX                    | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| Unknown       | Unknown                     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Gigabyte      | B550M K                     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Dell          | 0K240Y A01                  | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| ASRockRack    | X470D4U                     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4cbba6622f](https://linux-hardware.org/?probe=4cbba6622f) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [8cf3decf30](https://linux-hardware.org/?probe=8cf3decf30) | Jul 28, 2023 |
| Dell          | 06X1TJ A00                  | [e873051e73](https://linux-hardware.org/?probe=e873051e73) | Jul 27, 2023 |
| ABIT          | NF7-S/NF7,NF7-V,1.0         | [f5184af4e0](https://linux-hardware.org/?probe=f5184af4e0) | Jul 27, 2023 |
| Dell          | 01XK1W A00                  | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| ASRock        | X570 PG Velocita            | [64d86600a4](https://linux-hardware.org/?probe=64d86600a4) | Jul 26, 2023 |
| Phoenix Co... | PSB514 A11                  | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| AAEON         | GENE-CML5 V1.0              | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [98cddbfe0e](https://linux-hardware.org/?probe=98cddbfe0e) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| HP            | 805A                        | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| MSI           | H81M-P33                    | [0d3af45e51](https://linux-hardware.org/?probe=0d3af45e51) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Unknown       | Unknown                     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Dell          | 06X1TJ A00                  | [8ca31a1cfb](https://linux-hardware.org/?probe=8ca31a1cfb) | Jul 15, 2023 |
| ASRock        | FM2A68M-DG3+                | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| MSI           | H170M PRO-VDH               | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [b330e5c4fb](https://linux-hardware.org/?probe=b330e5c4fb) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [c0fb949fdc](https://linux-hardware.org/?probe=c0fb949fdc) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Dell          | 0T10XW A01                  | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| ASUSTek       | A88XM-A                     | [544563aaae](https://linux-hardware.org/?probe=544563aaae) | Jul 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| Dell          | 0M5DCD A00                  | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Unknown       | Unknown                     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| AZW           | U59                         | [5cf3ddbe4b](https://linux-hardware.org/?probe=5cf3ddbe4b) | Jul 08, 2023 |
| AZW           | U59                         | [ea367423d1](https://linux-hardware.org/?probe=ea367423d1) | Jul 08, 2023 |
| AZW           | MINI S                      | [b13eb96728](https://linux-hardware.org/?probe=b13eb96728) | Jul 08, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| HP            | 895C                        | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Dell          | 0KYWH7 A00                  | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| ASUSTek       | Z87-A                       | [e000de29fe](https://linux-hardware.org/?probe=e000de29fe) | Jul 03, 2023 |
| EPoX Compu... | Intel I945 DDR2 : 5P945-... | [5aa77af58f](https://linux-hardware.org/?probe=5aa77af58f) | Jul 03, 2023 |
| Gigabyte      | B550 UD AC                  | [8e758ec922](https://linux-hardware.org/?probe=8e758ec922) | Jul 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [f17cce1847](https://linux-hardware.org/?probe=f17cce1847) | Jul 02, 2023 |
| Supermicro    | X8ST3                       | [bac142132d](https://linux-hardware.org/?probe=bac142132d) | Jul 01, 2023 |
| ASUSTek       | Z170-A                      | [24adbf0475](https://linux-hardware.org/?probe=24adbf0475) | Jul 01, 2023 |
| NetGear       | ReadyDATA 5200              | [b89ca471ef](https://linux-hardware.org/?probe=b89ca471ef) | Jul 01, 2023 |
| Gigabyte      | B365M D3H-CF                | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| Shuttle       | FS61                        | [a67d2edea8](https://linux-hardware.org/?probe=a67d2edea8) | Jun 28, 2023 |
| AMI           | Cherry Trail CR             | [65fb07ed8d](https://linux-hardware.org/?probe=65fb07ed8d) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [baf77629c1](https://linux-hardware.org/?probe=baf77629c1) | Jun 26, 2023 |
| ASRock        | H61M-HVS                    | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Dell          | 01XK1W A00                  | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASRockRack    | X470D4U                     | [2d49269787](https://linux-hardware.org/?probe=2d49269787) | Jun 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| HP            | 3397                        | [8c9be2f4c0](https://linux-hardware.org/?probe=8c9be2f4c0) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | [d419086209](https://linux-hardware.org/?probe=d419086209) | Jun 22, 2023 |
| HP            | 3397                        | [a47ce0d4dc](https://linux-hardware.org/?probe=a47ce0d4dc) | Jun 22, 2023 |
| ASRockRack    | X470D4U                     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| MSI           | H81M-P33                    | [62fb9cda50](https://linux-hardware.org/?probe=62fb9cda50) | Jun 20, 2023 |
| Dell          | 06FW8P A02                  | [f65ec61ffc](https://linux-hardware.org/?probe=f65ec61ffc) | Jun 20, 2023 |
| Dell          | 0PU052                      | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| AZW           | U59                         | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| HP            | 1589                        | [6bfe1d5b63](https://linux-hardware.org/?probe=6bfe1d5b63) | Jun 15, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [6e241e56cf](https://linux-hardware.org/?probe=6e241e56cf) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [f9ebdca1bd](https://linux-hardware.org/?probe=f9ebdca1bd) | Jun 14, 2023 |
| HP            | 2AED                        | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [764e533752](https://linux-hardware.org/?probe=764e533752) | Jun 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Intel         | SHARKBAY                    | [8772d55075](https://linux-hardware.org/?probe=8772d55075) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| ASUSTek       | P5GC-MX/1333                | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Inventec      | VXC Class A02               | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| ASRock        | B365M Pro4-F                | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| HP            | 843C                        | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Gigabyte      | P75-D3                      | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| ChangWang     | CW56-58                     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| Intel         | X99                         | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| ASUSTek       | P4S8L                       | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| Supermicro    | X9DR3-F                     | [afcfc0fdf3](https://linux-hardware.org/?probe=afcfc0fdf3) | May 30, 2023 |
| MSI           | H55M-ED55                   | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| ASRock        | H310CM-HDV                  | [e6e310a9b4](https://linux-hardware.org/?probe=e6e310a9b4) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | [84e791ec5e](https://linux-hardware.org/?probe=84e791ec5e) | May 29, 2023 |
| Inventec      | VXC Class A02               | [0befe25313](https://linux-hardware.org/?probe=0befe25313) | May 29, 2023 |
| Inventec      | VXC Class A02               | [363827ad8c](https://linux-hardware.org/?probe=363827ad8c) | May 29, 2023 |
| MSI           | Z390-A PRO                  | [c797a10bff](https://linux-hardware.org/?probe=c797a10bff) | May 29, 2023 |
| ASUSTek       | Z10PA-D8 Series             | [02821a3220](https://linux-hardware.org/?probe=02821a3220) | May 29, 2023 |
| Dell          | 040DDP A01                  | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Unknown       | Unknown                     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| MSI           | PRO Z690-A DDR4             | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| Intel         | X99                         | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| AZW           | MINI S                      | [55c17a6700](https://linux-hardware.org/?probe=55c17a6700) | May 27, 2023 |
| MSI           | H55M-ED55                   | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| ASUSTek       | K30BF_M32BF                 | [a262345925](https://linux-hardware.org/?probe=a262345925) | May 27, 2023 |
| HP            | 2B38                        | [528dfa2310](https://linux-hardware.org/?probe=528dfa2310) | May 27, 2023 |
| MSI           | MAG B460M MORTAR            | [ac03083cbd](https://linux-hardware.org/?probe=ac03083cbd) | May 27, 2023 |
| HP            | 895C                        | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| ASUSTek       | P4S8L                       | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| Acer          | EG31M R01-A4                | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| Unknown       | SKYBAY                      | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| ASUSTek       | Berkeley                    | [c3e5448952](https://linux-hardware.org/?probe=c3e5448952) | May 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| HP            | 1496                        | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A II             | [e1681daf09](https://linux-hardware.org/?probe=e1681daf09) | May 24, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [05a334c56f](https://linux-hardware.org/?probe=05a334c56f) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [c5d225afe1](https://linux-hardware.org/?probe=c5d225afe1) | May 23, 2023 |
| ASUSTek       | F2A85-M                     | [9532d524c9](https://linux-hardware.org/?probe=9532d524c9) | May 22, 2023 |
| Unknown       | Unknown                     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| AZW           | U59                         | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| ASUSTek       | K30BF_M32BF                 | [243f08edd7](https://linux-hardware.org/?probe=243f08edd7) | May 22, 2023 |
| Dell          | 0J1C3P A00                  | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| HP            | 2B38                        | [b45d316c65](https://linux-hardware.org/?probe=b45d316c65) | May 21, 2023 |
| HP            | 2B38                        | [c2ab5ab32a](https://linux-hardware.org/?probe=c2ab5ab32a) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [e2d9f2e00f](https://linux-hardware.org/?probe=e2d9f2e00f) | May 21, 2023 |
| MSI           | A320M PRO-VD/S V2           | [f573a9cfae](https://linux-hardware.org/?probe=f573a9cfae) | May 21, 2023 |
| MSI           | Z170A SLI PLUS              | [a28c25cf6a](https://linux-hardware.org/?probe=a28c25cf6a) | May 21, 2023 |
| BESSTAR Te... | HM90                        | [874345ef99](https://linux-hardware.org/?probe=874345ef99) | May 21, 2023 |
| Dell          | 09KPNV A00                  | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| MSI           | 2AE0                        | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [875d854ec4](https://linux-hardware.org/?probe=875d854ec4) | May 18, 2023 |
| HP            | 8076                        | [fe142eecf2](https://linux-hardware.org/?probe=fe142eecf2) | May 18, 2023 |
| Intel         | DB75EN AAG39650-302         | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Gigabyte      | B560 HD3                    | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| MSI           | H510M-A PRO                 | [94ee6e64c4](https://linux-hardware.org/?probe=94ee6e64c4) | May 17, 2023 |
| AMI           | Cherry Trail CR             | [60abe2cf78](https://linux-hardware.org/?probe=60abe2cf78) | May 17, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [84ee42ec2e](https://linux-hardware.org/?probe=84ee42ec2e) | May 17, 2023 |
| Dell          | 0D883F A04                  | [62cee990ff](https://linux-hardware.org/?probe=62cee990ff) | May 17, 2023 |
| Pegatron      | Yangtze                     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ce8f784b0](https://linux-hardware.org/?probe=6ce8f784b0) | May 17, 2023 |
| Dell          | 07KY25 A00                  | [16e4096f62](https://linux-hardware.org/?probe=16e4096f62) | May 16, 2023 |
| Dell          | 0782GW A00                  | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| ASUSTek       | PRIME B550M-K               | [61e6c3f5f1](https://linux-hardware.org/?probe=61e6c3f5f1) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| HP            | 339A                        | [4c56331906](https://linux-hardware.org/?probe=4c56331906) | May 14, 2023 |
| Intel         | D510MO AAE76523-404         | [03221e90c1](https://linux-hardware.org/?probe=03221e90c1) | May 14, 2023 |
| Dell          | 01XK1W A00                  | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [921f919bb6](https://linux-hardware.org/?probe=921f919bb6) | May 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [b56358c287](https://linux-hardware.org/?probe=b56358c287) | May 12, 2023 |
| HP            | 1632                        | [d3a5a15faa](https://linux-hardware.org/?probe=d3a5a15faa) | May 12, 2023 |
| Dell          | 0K240Y A01                  | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6c61b581ba](https://linux-hardware.org/?probe=6c61b581ba) | May 12, 2023 |
| Gigabyte      | GA-970A-D3                  | [2302fc6860](https://linux-hardware.org/?probe=2302fc6860) | May 12, 2023 |
| AZW           | Green G3                    | [e11013e93f](https://linux-hardware.org/?probe=e11013e93f) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [4b5279de3c](https://linux-hardware.org/?probe=4b5279de3c) | May 11, 2023 |
| Unknown       | Unknown                     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| Dell          | 0C1R19 A01                  | [8a436329aa](https://linux-hardware.org/?probe=8a436329aa) | May 09, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [99dfb3e933](https://linux-hardware.org/?probe=99dfb3e933) | May 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [e98eff32d6](https://linux-hardware.org/?probe=e98eff32d6) | May 08, 2023 |
| ASRock        | N68-VS3 FX                  | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| HP            | 0AA8h                       | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| ASUSTek       | PRIME X570-PRO              | [4a8c2101e8](https://linux-hardware.org/?probe=4a8c2101e8) | May 08, 2023 |
| HP            | 3031h                       | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| MSI           | H61M-E23                    | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| Unknown       | Unknown                     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | 0N4YC8 A00                  | [e3dc4ed549](https://linux-hardware.org/?probe=e3dc4ed549) | May 06, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| HP            | 1998                        | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| Dell          | 0RN474                      | [b638694274](https://linux-hardware.org/?probe=b638694274) | May 05, 2023 |
| Unknown       | Unknown                     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Unknown       | Unknown                     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| BESSTAR Te... | DMAF5                       | [b9f947fec3](https://linux-hardware.org/?probe=b9f947fec3) | May 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [86b607e7d4](https://linux-hardware.org/?probe=86b607e7d4) | May 02, 2023 |
| MSI           | Z87-G43                     | [8ba78b7b0b](https://linux-hardware.org/?probe=8ba78b7b0b) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [ec30321519](https://linux-hardware.org/?probe=ec30321519) | May 01, 2023 |
| Intel         | DN2820FYK H24582-201        | [cfe5e305c8](https://linux-hardware.org/?probe=cfe5e305c8) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [a237c703d9](https://linux-hardware.org/?probe=a237c703d9) | May 01, 2023 |
| HP            | 2B38                        | [bf99202e8b](https://linux-hardware.org/?probe=bf99202e8b) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| HP            | 2B38                        | [6942eb2544](https://linux-hardware.org/?probe=6942eb2544) | May 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| Hardkernel    | ODROID-H3                   | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| HP            | 3397                        | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| Medion        | MS-7708                     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Intel         | H61 V124                    | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| ASUSTek       | B150-PRO D3                 | [35fa6f9a33](https://linux-hardware.org/?probe=35fa6f9a33) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| Shenzhen M... | F6BFC                       | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| Unknown       | Unknown                     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| MSI           | MS-B0A21                    | [646d14f7b0](https://linux-hardware.org/?probe=646d14f7b0) | Apr 26, 2023 |
| HP            | 1632                        | [ace6df6aee](https://linux-hardware.org/?probe=ace6df6aee) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| ASUSTek       | PRIME Z590-P                | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| HP            | 8056                        | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| AZW           | MINI S                      | [d71153ae6e](https://linux-hardware.org/?probe=d71153ae6e) | Apr 24, 2023 |
| Intel         | SE7320EP2 D11950-402        | [ad1a126878](https://linux-hardware.org/?probe=ad1a126878) | Apr 24, 2023 |
| MSI           | Z87-G43                     | [4d908cb615](https://linux-hardware.org/?probe=4d908cb615) | Apr 24, 2023 |
| Dell          | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| Biostar       | B350ET2                     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [3a9f7b19fa](https://linux-hardware.org/?probe=3a9f7b19fa) | Apr 23, 2023 |
| MSI           | Z390-A PRO                  | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [965aa93228](https://linux-hardware.org/?probe=965aa93228) | Apr 23, 2023 |
| Unknown       | Unknown                     | [0605faa66d](https://linux-hardware.org/?probe=0605faa66d) | Apr 23, 2023 |
| AZW           | U59                         | [8921a6910d](https://linux-hardware.org/?probe=8921a6910d) | Apr 23, 2023 |
| Shuttle       | DS20U                       | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| HP            | 845A                        | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [0a90dc180c](https://linux-hardware.org/?probe=0a90dc180c) | Apr 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b5ffb4ee22](https://linux-hardware.org/?probe=b5ffb4ee22) | Apr 22, 2023 |
| Gigabyte      | B550M DS3H                  | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| ASUSTek       | B85M-G                      | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Shuttle       | FS81                        | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4abfcb4ab3](https://linux-hardware.org/?probe=4abfcb4ab3) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [e93357961f](https://linux-hardware.org/?probe=e93357961f) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [895abaa15e](https://linux-hardware.org/?probe=895abaa15e) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [f70d811bbd](https://linux-hardware.org/?probe=f70d811bbd) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [11f85df48e](https://linux-hardware.org/?probe=11f85df48e) | Apr 17, 2023 |
| ASRock        | H310M-STX                   | [438e774de5](https://linux-hardware.org/?probe=438e774de5) | Apr 17, 2023 |
| HP            | 0AECh D                     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ea01fad49](https://linux-hardware.org/?probe=6ea01fad49) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [a4bb147f89](https://linux-hardware.org/?probe=a4bb147f89) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Dell          | 0HHV7N A00                  | [4443ff9154](https://linux-hardware.org/?probe=4443ff9154) | Apr 16, 2023 |
| HP            | 18E7                        | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | [1f02ee3393](https://linux-hardware.org/?probe=1f02ee3393) | Apr 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Medion        | TJ4125                      | [887d24e023](https://linux-hardware.org/?probe=887d24e023) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7768947bc](https://linux-hardware.org/?probe=d7768947bc) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [5be961705c](https://linux-hardware.org/?probe=5be961705c) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| HP            | 21EF                        | [d2b3751fd1](https://linux-hardware.org/?probe=d2b3751fd1) | Apr 13, 2023 |
| Dell          | 0XD433 A00                  | [e0a30bf441](https://linux-hardware.org/?probe=e0a30bf441) | Apr 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [108725a205](https://linux-hardware.org/?probe=108725a205) | Apr 12, 2023 |
| MSI           | Z370 PC PRO                 | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Intel         | H61 V124                    | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| MSI           | MS-7060                     | [d78aaad9ec](https://linux-hardware.org/?probe=d78aaad9ec) | Apr 12, 2023 |
| HP            | 1589                        | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| HP            | 1589                        | [e52c705c13](https://linux-hardware.org/?probe=e52c705c13) | Apr 11, 2023 |
| ASUSTek       | PRIME Z370-A                | [64759fca72](https://linux-hardware.org/?probe=64759fca72) | Apr 10, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5b0601fc42](https://linux-hardware.org/?probe=5b0601fc42) | Apr 09, 2023 |
| Medion        | TJ4125                      | [5c5f39a8fd](https://linux-hardware.org/?probe=5c5f39a8fd) | Apr 09, 2023 |
| HP            | 2B29                        | [b909d3c46d](https://linux-hardware.org/?probe=b909d3c46d) | Apr 09, 2023 |
| HP            | 2B29                        | [1fd9cd3d7c](https://linux-hardware.org/?probe=1fd9cd3d7c) | Apr 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [3b665833d1](https://linux-hardware.org/?probe=3b665833d1) | Apr 09, 2023 |
| HP            | 83E9                        | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| AMI           | Intel                       | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [36c87da9d9](https://linux-hardware.org/?probe=36c87da9d9) | Apr 07, 2023 |
| Inventec      | D CLASS A02                 | [3d53baddbf](https://linux-hardware.org/?probe=3d53baddbf) | Apr 07, 2023 |
| Inventec      | VXC Class A02               | [3ff1b18b81](https://linux-hardware.org/?probe=3ff1b18b81) | Apr 07, 2023 |
| Dell          | 01XK1W A00                  | [023a578b76](https://linux-hardware.org/?probe=023a578b76) | Apr 07, 2023 |
| MSI           | MS-7253                     | [1b9074e1ac](https://linux-hardware.org/?probe=1b9074e1ac) | Apr 06, 2023 |
| Foxconn       | 2A8C                        | [f202bac0de](https://linux-hardware.org/?probe=f202bac0de) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [6d7db3d917](https://linux-hardware.org/?probe=6d7db3d917) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| MSI           | MS-B1831                    | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [ea7a921618](https://linux-hardware.org/?probe=ea7a921618) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [125f93468e](https://linux-hardware.org/?probe=125f93468e) | Apr 06, 2023 |
| HP            | 895C                        | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [9c6a3de994](https://linux-hardware.org/?probe=9c6a3de994) | Apr 05, 2023 |
| HP            | 895C                        | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [2783ec6da9](https://linux-hardware.org/?probe=2783ec6da9) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| HP            | 1790                        | [55e3d423e0](https://linux-hardware.org/?probe=55e3d423e0) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [58cf8c28ff](https://linux-hardware.org/?probe=58cf8c28ff) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [7f904181ea](https://linux-hardware.org/?probe=7f904181ea) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| Acer          | WG43M                       | [10bf0c0d1a](https://linux-hardware.org/?probe=10bf0c0d1a) | Apr 04, 2023 |
| MSI           | MAG B460 TORPEDO            | [62a628da55](https://linux-hardware.org/?probe=62a628da55) | Apr 04, 2023 |
| Unknown       | Q-790                       | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| ASUSTek       | P8Z77-M                     | [ec9901fcd5](https://linux-hardware.org/?probe=ec9901fcd5) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [aaa2e273c1](https://linux-hardware.org/?probe=aaa2e273c1) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Unknown       | Unknown                     | [cbcfbb8783](https://linux-hardware.org/?probe=cbcfbb8783) | Apr 03, 2023 |
| BESSTAR Te... | HM90                        | [722013016f](https://linux-hardware.org/?probe=722013016f) | Apr 03, 2023 |
| Shuttle       | FH370                       | [29b2ad6149](https://linux-hardware.org/?probe=29b2ad6149) | Apr 03, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6844d471e4](https://linux-hardware.org/?probe=6844d471e4) | Apr 02, 2023 |
| Unknown       | Unknown                     | [077bed9951](https://linux-hardware.org/?probe=077bed9951) | Apr 02, 2023 |
| Google        | Panther                     | [73f3ed3c65](https://linux-hardware.org/?probe=73f3ed3c65) | Apr 02, 2023 |
| MSI           | MS-7318                     | [3d02816b24](https://linux-hardware.org/?probe=3d02816b24) | Apr 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [2a597d7a33](https://linux-hardware.org/?probe=2a597d7a33) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [32c0716bfa](https://linux-hardware.org/?probe=32c0716bfa) | Apr 01, 2023 |
| Medion        | TJ4125                      | [2627cc2d42](https://linux-hardware.org/?probe=2627cc2d42) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| ASUSTek       | TS10                        | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [050875ba5f](https://linux-hardware.org/?probe=050875ba5f) | Mar 30, 2023 |
| AZW           | U59                         | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| HP            | 213D A01                    | [d5fb38a71b](https://linux-hardware.org/?probe=d5fb38a71b) | Mar 30, 2023 |
| HP            | 213D A01                    | [79d8e1b64f](https://linux-hardware.org/?probe=79d8e1b64f) | Mar 30, 2023 |
| HP            | 3048h                       | [1a4d86fca8](https://linux-hardware.org/?probe=1a4d86fca8) | Mar 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [4976f6b6b2](https://linux-hardware.org/?probe=4976f6b6b2) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [9251f2d561](https://linux-hardware.org/?probe=9251f2d561) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [2d28ba397e](https://linux-hardware.org/?probe=2d28ba397e) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Medion        | TJ4125                      | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| ECS           | G31T-M                      | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| HP            | 89B4 A                      | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| Pegatron      | Maureen                     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| HP            | 18E6                        | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Medion        | TJ4125                      | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| ASRock        | FM2A88X+ Killer             | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| ASRockRack    | D1541D4U-2T8R               | [012c10ae8c](https://linux-hardware.org/?probe=012c10ae8c) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LE                  | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Dell          | 0HY9JP A00                  | [d1c982b241](https://linux-hardware.org/?probe=d1c982b241) | Mar 26, 2023 |
| HP            | 83E2                        | [00f64e69cd](https://linux-hardware.org/?probe=00f64e69cd) | Mar 26, 2023 |
| Medion        | TJ4125                      | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| HP            | 1497                        | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| HP            | 83E2                        | [cd40c6aa18](https://linux-hardware.org/?probe=cd40c6aa18) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Dell          | 0PU052                      | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [9b8ddda3c3](https://linux-hardware.org/?probe=9b8ddda3c3) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| AZW           | U59                         | [b4058b773d](https://linux-hardware.org/?probe=b4058b773d) | Mar 24, 2023 |
| ASRockRack    | E3C242D4U2-2T               | [05eb6d08bd](https://linux-hardware.org/?probe=05eb6d08bd) | Mar 23, 2023 |
| Dell          | 0J3C2F A02                  | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| HP            | 0A68h                       | [527cad6ad0](https://linux-hardware.org/?probe=527cad6ad0) | Mar 23, 2023 |
| Unknown       | Unknown                     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| Unknown       | Unknown                     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| HP            | 3048h                       | [5163f9de22](https://linux-hardware.org/?probe=5163f9de22) | Mar 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [3b06195ff0](https://linux-hardware.org/?probe=3b06195ff0) | Mar 21, 2023 |
| Google        | Teemo                       | [3e60b11752](https://linux-hardware.org/?probe=3e60b11752) | Mar 21, 2023 |
| Supermicro    | X10DRi-T4+                  | [3aa5aebaee](https://linux-hardware.org/?probe=3aa5aebaee) | Mar 20, 2023 |
| HP            | 1825                        | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1a21f25ce5](https://linux-hardware.org/?probe=1a21f25ce5) | Mar 20, 2023 |
| ASUSTek       | A88X-PRO                    | [ea415770cb](https://linux-hardware.org/?probe=ea415770cb) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [5308592de8](https://linux-hardware.org/?probe=5308592de8) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Medion        | TJ4125                      | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Gigabyte      | Q270M-D3H                   | [b244f2a8fd](https://linux-hardware.org/?probe=b244f2a8fd) | Mar 18, 2023 |
| ASRock        | X570 PG Velocita            | [bc3f2240b9](https://linux-hardware.org/?probe=bc3f2240b9) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| HP            | 198E                        | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | PowerEdge M620              | [c628cb7f90](https://linux-hardware.org/?probe=c628cb7f90) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Gigabyte      | AX370-Gaming 5              | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | Q270M-D3H                   | [8841b23ef7](https://linux-hardware.org/?probe=8841b23ef7) | Mar 16, 2023 |
| ASRock        | X570 PG Velocita            | [bd8bc5740e](https://linux-hardware.org/?probe=bd8bc5740e) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Gigabyte      | Z77X-UD3H                   | [a22bba0e53](https://linux-hardware.org/?probe=a22bba0e53) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| HP            | 1495                        | [72769abb34](https://linux-hardware.org/?probe=72769abb34) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| Unknown       | Unknown                     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| ASRock        | 970M Pro3                   | [a35e76c9bf](https://linux-hardware.org/?probe=a35e76c9bf) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| HP            | 1825                        | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Medion        | TJ4125                      | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| Medion        | TJ4125                      | [a93f645a7b](https://linux-hardware.org/?probe=a93f645a7b) | Mar 11, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c91efb0de0](https://linux-hardware.org/?probe=c91efb0de0) | Mar 11, 2023 |
| MSI           | MS-B1831                    | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASRock        | 970M Pro3                   | [988d270005](https://linux-hardware.org/?probe=988d270005) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [2d0fdf6553](https://linux-hardware.org/?probe=2d0fdf6553) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [34a92205b4](https://linux-hardware.org/?probe=34a92205b4) | Mar 11, 2023 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | [eff63861e7](https://linux-hardware.org/?probe=eff63861e7) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| ASUSTek       | AT3N7A-I                    | [59de62aac5](https://linux-hardware.org/?probe=59de62aac5) | Mar 11, 2023 |
| Gigabyte      | Z77X-UD3H                   | [823c3530a1](https://linux-hardware.org/?probe=823c3530a1) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| GoWin Solu... | R86S                        | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| AZW           | MINI S                      | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| ASRock        | 990FX Killer                | [326cdc81b2](https://linux-hardware.org/?probe=326cdc81b2) | Mar 09, 2023 |
| ASUSTek       | P5G41T-M LX                 | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Intel         | JSL MRD                     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69dd85d8cf](https://linux-hardware.org/?probe=69dd85d8cf) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| MSI           | 880GM-E43                   | [f4027fb865](https://linux-hardware.org/?probe=f4027fb865) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| Dell          | 0F5C5X A00                  | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| HP            | ProLiant MicroServer Gen... | [ae0bbd2f73](https://linux-hardware.org/?probe=ae0bbd2f73) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| AZW           | MINI S                      | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| ASRock        | 990FX Extreme4              | [641d1c6a8f](https://linux-hardware.org/?probe=641d1c6a8f) | Mar 05, 2023 |
| Unknown       | i855-W83627HF               | [e60d4877f4](https://linux-hardware.org/?probe=e60d4877f4) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| Win elemen... | M600                        | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| Dell          | 0D6H9T A02                  | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| AMI           | Intel                       | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [93e91a76bf](https://linux-hardware.org/?probe=93e91a76bf) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [1774000cc4](https://linux-hardware.org/?probe=1774000cc4) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ECS           | G31T-M9                     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [977be97551](https://linux-hardware.org/?probe=977be97551) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [2191c9e96a](https://linux-hardware.org/?probe=2191c9e96a) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [5b8c79ac33](https://linux-hardware.org/?probe=5b8c79ac33) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [80644bb1ec](https://linux-hardware.org/?probe=80644bb1ec) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| CWWK          | CW-J6-6L                    | [aea23f5903](https://linux-hardware.org/?probe=aea23f5903) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Unknown       | J3160-4L                    | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| Gigabyte      | B650M DS3H                  | [6e5e4d848d](https://linux-hardware.org/?probe=6e5e4d848d) | Mar 01, 2023 |
| AZW           | MINI S                      | [2206d30a53](https://linux-hardware.org/?probe=2206d30a53) | Mar 01, 2023 |
| HP            | 8433 11                     | [15dccf1191](https://linux-hardware.org/?probe=15dccf1191) | Mar 01, 2023 |
| Medion        | TJ4125                      | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| HP            | 83E2                        | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| AZW           | MINI S                      | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| HP            | 3397                        | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Dell          | 0MH651                      | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| ASRock        | 970M Pro3                   | [787ddfd44c](https://linux-hardware.org/?probe=787ddfd44c) | Feb 26, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9c64d6366e](https://linux-hardware.org/?probe=9c64d6366e) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| MSI           | B85M-E45                    | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| Medion        | TJ4125                      | [bde9228741](https://linux-hardware.org/?probe=bde9228741) | Feb 25, 2023 |
| Intel         | JSL MRD                     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f5b4a5da72](https://linux-hardware.org/?probe=f5b4a5da72) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [efc9b2fdbf](https://linux-hardware.org/?probe=efc9b2fdbf) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [24dc4341d3](https://linux-hardware.org/?probe=24dc4341d3) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [0806dcb9ca](https://linux-hardware.org/?probe=0806dcb9ca) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [e3cdd0b411](https://linux-hardware.org/?probe=e3cdd0b411) | Feb 24, 2023 |
| Gigabyte      | H610M S2H DDR4              | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| ASUSTek       | KRPA-U16 Series             | [e417ffd8e7](https://linux-hardware.org/?probe=e417ffd8e7) | Feb 23, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [4f19f71811](https://linux-hardware.org/?probe=4f19f71811) | Feb 23, 2023 |
| ASUSTek       | P8H67-M                     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Intel         | H61                         | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| AZW           | U59                         | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| AZW           | U59                         | [368562790b](https://linux-hardware.org/?probe=368562790b) | Feb 22, 2023 |
| Unknown       | Unknown                     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58e 7269E3S    | [6b30da3a31](https://linux-hardware.org/?probe=6b30da3a31) | Feb 20, 2023 |
| Dell          | 073MMW A02                  | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Intel         | JSL MRD                     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Gigabyte      | GA-A55M-DS2                 | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.0-7-amd64         | 515      | 17.62%  |
| 5.10.0-8-amd64         | 230      | 7.87%   |
| 5.10.0-21-amd64        | 179      | 6.13%   |
| 5.10.0-9-amd64         | 121      | 4.14%   |
| 5.10.0-2-amd64         | 115      | 3.94%   |
| 5.10.0-20-amd64        | 106      | 3.63%   |
| 5.10.0-19-amd64        | 104      | 3.56%   |
| 5.10.0-23-amd64        | 94       | 3.22%   |
| 5.10.0-13-amd64        | 88       | 3.01%   |
| 5.10.0-18-amd64        | 84       | 2.87%   |
| 5.10.0-10-amd64        | 74       | 2.53%   |
| 5.10.0-11-amd64        | 72       | 2.46%   |
| 5.10.0-16-amd64        | 69       | 2.36%   |
| 5.10.0-14-amd64        | 51       | 1.75%   |
| 5.10.0-22-amd64        | 44       | 1.51%   |
| 5.10.0-15-amd64        | 44       | 1.51%   |
| 5.10.0-17-amd64        | 43       | 1.47%   |
| 5.10.0-26-amd64        | 31       | 1.06%   |
| 5.10.0-12-amd64        | 29       | 0.99%   |
| 5.10.0-25-amd64        | 23       | 0.79%   |
| 5.16.0-0.bpo.4-amd64   | 20       | 0.68%   |
| 5.15.102-1-pve         | 20       | 0.68%   |
| 5.15.0-2-amd64         | 20       | 0.68%   |
| 5.10.0-28-amd64        | 20       | 0.68%   |
| 6.0.0-0.deb11.6-amd64  | 19       | 0.65%   |
| 5.13.19-6-pve          | 18       | 0.62%   |
| 5.10.0-32-amd64        | 18       | 0.62%   |
| 5.18.0-0.bpo.1-amd64   | 16       | 0.55%   |
| 5.10.0-27-amd64        | 16       | 0.55%   |
| 6.1.0-0.deb11.7-amd64  | 14       | 0.48%   |
| 5.18.0-0.deb11.4-amd64 | 14       | 0.48%   |
| 5.15.83-1-pve          | 14       | 0.48%   |
| 5.13.19-2-pve          | 14       | 0.48%   |
| 5.15.30-2-pve          | 13       | 0.44%   |
| 5.10.0-6-amd64         | 13       | 0.44%   |
| 5.10.0-33-amd64        | 13       | 0.44%   |
| 5.15.85-1-pve          | 12       | 0.41%   |
| 5.15.74-1-pve          | 12       | 0.41%   |
| 5.15.107-2-pve         | 12       | 0.41%   |
| 5.15.53-1-pve          | 11       | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 2146     | 77.73%  |
| 6.1.0    | 55       | 1.99%   |
| 5.13.19  | 44       | 1.59%   |
| 5.18.0   | 43       | 1.56%   |
| 6.0.0    | 39       | 1.41%   |
| 5.15.0   | 35       | 1.27%   |
| 5.16.0   | 31       | 1.12%   |
| 5.19.0   | 21       | 0.76%   |
| 5.15.107 | 20       | 0.72%   |
| 5.15.102 | 20       | 0.72%   |
| 5.14.0   | 18       | 0.65%   |
| 5.11.22  | 17       | 0.62%   |
| 5.15.83  | 14       | 0.51%   |
| 5.15.39  | 13       | 0.47%   |
| 5.15.35  | 13       | 0.47%   |
| 5.15.30  | 13       | 0.47%   |
| 5.15.85  | 12       | 0.43%   |
| 5.15.74  | 12       | 0.43%   |
| 5.15.53  | 11       | 0.4%    |
| 5.17.0   | 10       | 0.36%   |
| 5.15.108 | 8        | 0.29%   |
| 5.15.104 | 8        | 0.29%   |
| 5.19.17  | 6        | 0.22%   |
| 5.15.126 | 6        | 0.22%   |
| 6.2.6    | 5        | 0.18%   |
| 6.1.15   | 5        | 0.18%   |
| 6.2.9    | 4        | 0.14%   |
| 6.2.11   | 4        | 0.14%   |
| 6.0.8    | 4        | 0.14%   |
| 5.15.60  | 4        | 0.14%   |
| 5.15.131 | 4        | 0.14%   |
| 5.15.116 | 4        | 0.14%   |
| 5.13.0   | 4        | 0.14%   |
| 5.16.5   | 3        | 0.11%   |
| 5.15.79  | 3        | 0.11%   |
| 5.15.158 | 3        | 0.11%   |
| 5.15.143 | 3        | 0.11%   |
| 5.10.57  | 3        | 0.11%   |
| 4.19.0   | 3        | 0.11%   |
| 6.1.12   | 2        | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10     | 2168     | 79.3%   |
| 5.15     | 198      | 7.24%   |
| 6.1      | 65       | 2.38%   |
| 5.13     | 54       | 1.98%   |
| 6.0      | 49       | 1.79%   |
| 5.18     | 47       | 1.72%   |
| 5.16     | 37       | 1.35%   |
| 5.19     | 30       | 1.1%    |
| 5.11     | 20       | 0.73%   |
| 5.14     | 19       | 0.69%   |
| 6.2      | 17       | 0.62%   |
| 5.17     | 12       | 0.44%   |
| 6.3      | 3        | 0.11%   |
| 5.4      | 3        | 0.11%   |
| 4.19     | 3        | 0.11%   |
| 6.9      | 1        | 0.04%   |
| 6.6      | 1        | 0.04%   |
| 6.5      | 1        | 0.04%   |
| 6.10     | 1        | 0.04%   |
| 5.8      | 1        | 0.04%   |
| 5.5      | 1        | 0.04%   |
| 5.12     | 1        | 0.04%   |
| 5.10.164 | 1        | 0.04%   |
| 5.1      | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 2599     | 97.38%  |
| i686    | 64       | 2.4%    |
| riscv64 | 4        | 0.15%   |
| i586    | 1        | 0.04%   |
| armv7l  | 1        | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 1105     | 40.85%  |
| GNOME             | 517      | 19.11%  |
| XFCE              | 300      | 11.09%  |
| KDE5              | 275      | 10.17%  |
| MATE              | 121      | 4.47%   |
| X-Cinnamon        | 89       | 3.29%   |
| LXDE              | 74       | 2.74%   |
| Cinnamon          | 63       | 2.33%   |
| LXQt              | 37       | 1.37%   |
| i3                | 25       | 0.92%   |
| Openbox           | 18       | 0.67%   |
| KDE               | 16       | 0.59%   |
| Trinity           | 13       | 0.48%   |
| GNOME Flashback   | 12       | 0.44%   |
| lightdm-xsession  | 11       | 0.41%   |
| Budgie            | 10       | 0.37%   |
| GNOME Classic     | 5        | 0.18%   |
| sway              | 3        | 0.11%   |
| awesome           | 3        | 0.11%   |
| UKUI              | 1        | 0.04%   |
| icewm             | 1        | 0.04%   |
| GNUstep           | 1        | 0.04%   |
| gnome-xorg        | 1        | 0.04%   |
| Enlightenment     | 1        | 0.04%   |
| e16-session       | 1        | 0.04%   |
| DWM               | 1        | 0.04%   |
| /etc/X11/Xsession | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 1238     | 45.8%   |
| Unknown     | 705      | 26.08%  |
| Tty         | 494      | 18.28%  |
| Wayland     | 261      | 9.66%   |
| Web         | 3        | 0.11%   |
| Unspecified | 2        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1406     | 52.29%  |
| LightDM | 514      | 19.11%  |
| GDM     | 387      | 14.39%  |
| SDDM    | 234      | 8.7%    |
| TDM     | 73       | 2.71%   |
| GDM3    | 51       | 1.9%    |
| SLiM    | 9        | 0.33%   |
| XDM     | 6        | 0.22%   |
| NODM    | 5        | 0.19%   |
| LXDM    | 2        | 0.07%   |
| WDM     | 1        | 0.04%   |
| SU      | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 974      | 36.32%  |
| ru_RU   | 676      | 25.21%  |
| de_DE   | 152      | 5.67%   |
| fr_FR   | 142      | 5.29%   |
| en_GB   | 107      | 3.99%   |
| es_ES   | 79       | 2.95%   |
| pt_BR   | 57       | 2.13%   |
| Unknown | 56       | 2.09%   |
| it_IT   | 52       | 1.94%   |
| en_CA   | 36       | 1.34%   |
| C       | 36       | 1.34%   |
| en_AU   | 34       | 1.27%   |
| pl_PL   | 27       | 1.01%   |
| es_MX   | 15       | 0.56%   |
| es_AR   | 14       | 0.52%   |
| en_IE   | 14       | 0.52%   |
| ja_JP   | 13       | 0.48%   |
| hu_HU   | 13       | 0.48%   |
| es_VE   | 13       | 0.48%   |
| zh_CN   | 11       | 0.41%   |
| en_IN   | 10       | 0.37%   |
| de_AT   | 9        | 0.34%   |
| nl_BE   | 8        | 0.3%    |
| nl_NL   | 7        | 0.26%   |
| en_NZ   | 7        | 0.26%   |
| pt_PT   | 6        | 0.22%   |
| de_CH   | 6        | 0.22%   |
| ca_ES   | 6        | 0.22%   |
| en_ZA   | 5        | 0.19%   |
| en_HK   | 5        | 0.19%   |
| uk_UA   | 4        | 0.15%   |
| tr_TR   | 4        | 0.15%   |
| sv_SE   | 4        | 0.15%   |
| fr_BE   | 4        | 0.15%   |
| es_PE   | 4        | 0.15%   |
| cs_CZ   | 4        | 0.15%   |
| ru_UA   | 3        | 0.11%   |
| hr_HR   | 3        | 0.11%   |
| fr_CH   | 3        | 0.11%   |
| fr_CA   | 3        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1638     | 60.53%  |
| EFI  | 1068     | 39.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1771     | 66.01%  |
| Overlay | 676      | 25.2%   |
| Btrfs   | 91       | 3.39%   |
| Zfs     | 73       | 2.72%   |
| Xfs     | 37       | 1.38%   |
| Ext3    | 14       | 0.52%   |
| Tmpfs   | 11       | 0.41%   |
| Ext2    | 4        | 0.15%   |
| Unknown | 4        | 0.15%   |
| Rootfs  | 1        | 0.04%   |
| Aufs    | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1323     | 48.95%  |
| MBR     | 1026     | 37.96%  |
| Unknown | 354      | 13.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2183     | 81.06%  |
| Yes       | 510      | 18.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1577     | 58.58%  |
| Yes       | 1115     | 41.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 695      | 26.05%  |
| Gigabyte Technology                  | 433      | 16.23%  |
| MSI                                  | 269      | 10.08%  |
| ASRock                               | 251      | 9.41%   |
| Dell                                 | 195      | 7.31%   |
| Hewlett-Packard                      | 174      | 6.52%   |
| Lenovo                               | 88       | 3.3%    |
| Intel                                | 88       | 3.3%    |
| Unknown                              | 55       | 2.06%   |
| ECS                                  | 49       | 1.84%   |
| Fujitsu                              | 36       | 1.35%   |
| AZW                                  | 31       | 1.16%   |
| ASRockRack                           | 31       | 1.16%   |
| Foxconn                              | 28       | 1.05%   |
| Acer                                 | 20       | 0.75%   |
| Supermicro                           | 19       | 0.71%   |
| Pegatron                             | 14       | 0.52%   |
| Biostar                              | 13       | 0.49%   |
| Inventec                             | 12       | 0.45%   |
| BESSTAR Tech                         | 10       | 0.37%   |
| IceWhale Technology                  | 8        | 0.3%    |
| Medion                               | 7        | 0.26%   |
| Huanan                               | 7        | 0.26%   |
| Shuttle                              | 6        | 0.22%   |
| Google                               | 6        | 0.22%   |
| Apple                                | 5        | 0.19%   |
| Shenzhen Meigao Electronic Equipment | 4        | 0.15%   |
| Positivo                             | 4        | 0.15%   |
| HPE                                  | 4        | 0.15%   |
| Fujitsu Siemens                      | 4        | 0.15%   |
| AMI                                  | 4        | 0.15%   |
| Techvision                           | 3        | 0.11%   |
| Packard Bell                         | 3        | 0.11%   |
| Hardkernel                           | 3        | 0.11%   |
| Aquarius                             | 3        | 0.11%   |
| AAEON                                | 3        | 0.11%   |
| Thecus                               | 2        | 0.07%   |
| Semp Toshiba                         | 2        | 0.07%   |
| Seeed Studio                         | 2        | 0.07%   |
| Phoenix Contact                      | 2        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 84       | 3.15%   |
| Unknown                      | 56       | 2.1%    |
| ASUS S20 K29                 | 55       | 2.06%   |
| MSI MS-7996                  | 39       | 1.46%   |
| MSI MS-7817                  | 22       | 0.82%   |
| ECS G31T-M9                  | 22       | 0.82%   |
| ASRock H470M-HVS             | 20       | 0.75%   |
| Gigabyte H81M-S2V            | 18       | 0.67%   |
| ASUS PRIME H510M-A           | 17       | 0.64%   |
| Gigabyte H410M S2H           | 16       | 0.6%    |
| ECS H61H2-M13                | 16       | 0.6%    |
| Dell OptiPlex 7010           | 16       | 0.6%    |
| ASUS P8H61-M LX3 R2.0        | 15       | 0.56%   |
| AZW MINI S                   | 13       | 0.49%   |
| AZW U59                      | 12       | 0.45%   |
| Gigabyte B450M DS3H          | 11       | 0.41%   |
| ASUS PRIME A320M-K           | 11       | 0.41%   |
| HP ProLiant MicroServer Gen8 | 10       | 0.37%   |
| ASUS TUF Gaming X570-PLUS    | 10       | 0.37%   |
| ASUS PRIME B450M-A           | 10       | 0.37%   |
| ASUS H110M-R                 | 10       | 0.37%   |
| HP Z420 Workstation          | 9        | 0.34%   |
| Dell OptiPlex 9020           | 9        | 0.34%   |
| ASUS P8H67-M                 | 9        | 0.34%   |
| ASRock B450M Pro4            | 9        | 0.34%   |
| Gigabyte B360M H             | 8        | 0.3%    |
| Dell OptiPlex 790            | 8        | 0.3%    |
| ASRock H61M-VG4              | 8        | 0.3%    |
| ASRock G31M-VS2              | 8        | 0.3%    |
| MSI MS-7C91                  | 7        | 0.26%   |
| MSI MS-7C56                  | 7        | 0.26%   |
| MSI MS-7C02                  | 7        | 0.26%   |
| Inventec D CLASS             | 7        | 0.26%   |
| HP Compaq Elite 8300 SFF     | 7        | 0.26%   |
| Gigabyte P85-D3              | 7        | 0.26%   |
| Gigabyte GA-78LMT-USB3       | 7        | 0.26%   |
| Gigabyte A320M-S2H           | 7        | 0.26%   |
| Fujitsu ESPRIMO P720         | 7        | 0.26%   |
| ASUS P8H61-M LX3 PLUS R2.0   | 7        | 0.26%   |
| ASUS P5G41T-M LE             | 7        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 149      | 5.58%   |
| Dell OptiPlex          | 104      | 3.9%    |
| ASUS All               | 84       | 3.15%   |
| Unknown                | 56       | 2.1%    |
| ASUS S20               | 55       | 2.06%   |
| Lenovo ThinkCentre     | 53       | 1.99%   |
| HP Compaq              | 48       | 1.8%    |
| ASUS ROG               | 48       | 1.8%    |
| ASUS TUF               | 45       | 1.69%   |
| Dell Precision         | 44       | 1.65%   |
| MSI MS-7996            | 39       | 1.46%   |
| ASUS P8H61-M           | 32       | 1.2%    |
| HP EliteDesk           | 26       | 0.97%   |
| Gigabyte B450M         | 25       | 0.94%   |
| Fujitsu ESPRIMO        | 23       | 0.86%   |
| MSI MS-7817            | 22       | 0.82%   |
| HP ProLiant            | 22       | 0.82%   |
| ECS G31T-M9            | 22       | 0.82%   |
| ASUS Pro               | 21       | 0.79%   |
| ASRock H470M-HVS       | 20       | 0.75%   |
| Gigabyte H410M         | 19       | 0.71%   |
| Gigabyte H81M-S2V      | 18       | 0.67%   |
| ECS H61H2-M13          | 16       | 0.6%    |
| Lenovo ThinkStation    | 15       | 0.56%   |
| Gigabyte X570          | 15       | 0.56%   |
| ASRock B450M           | 15       | 0.56%   |
| Gigabyte B550          | 14       | 0.52%   |
| ASUS M5A97             | 14       | 0.52%   |
| ASRock B450            | 14       | 0.52%   |
| Dell XPS               | 13       | 0.49%   |
| Dell Inspiron          | 13       | 0.49%   |
| AZW MINI               | 13       | 0.49%   |
| HP ProDesk             | 12       | 0.45%   |
| Gigabyte GA-78LMT-USB3 | 12       | 0.45%   |
| AZW U59                | 12       | 0.45%   |
| ASUS P5G41T-M          | 12       | 0.45%   |
| ASUS P8H67-M           | 11       | 0.41%   |
| Acer Aspire            | 11       | 0.41%   |
| Gigabyte B550M         | 10       | 0.37%   |
| Dell Vostro            | 10       | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 271      | 10.16%  |
| 2012    | 271      | 10.16%  |
| 2021    | 234      | 8.77%   |
| 2013    | 227      | 8.51%   |
| 2018    | 222      | 8.32%   |
| 2011    | 163      | 6.11%   |
| 2019    | 159      | 5.96%   |
| 2014    | 149      | 5.58%   |
| 2015    | 127      | 4.76%   |
| 2022    | 126      | 4.72%   |
| 2009    | 125      | 4.69%   |
| 2010    | 123      | 4.61%   |
| 2017    | 120      | 4.5%    |
| 2016    | 105      | 3.94%   |
| 2008    | 90       | 3.37%   |
| 2007    | 63       | 2.36%   |
| 2006    | 27       | 1.01%   |
| 2023    | 24       | 0.9%    |
| 2005    | 19       | 0.71%   |
| 2004    | 6        | 0.22%   |
| 2003    | 6        | 0.22%   |
| 2024    | 4        | 0.15%   |
| 2001    | 3        | 0.11%   |
| Unknown | 3        | 0.11%   |
| 2000    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2668     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2627     | 98.21%  |
| Enabled  | 48       | 1.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2655     | 99.51%  |
| Yes  | 13       | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 534      | 19.76%  |
| 4.01-8.0        | 495      | 18.32%  |
| 3.01-4.0        | 416      | 15.4%   |
| 8.01-16.0       | 383      | 14.17%  |
| 32.01-64.0      | 355      | 13.14%  |
| 64.01-256.0     | 244      | 9.03%   |
| 1.01-2.0        | 126      | 4.66%   |
| 24.01-32.0      | 65       | 2.41%   |
| 2.01-3.0        | 47       | 1.74%   |
| 0.51-1.0        | 19       | 0.7%    |
| More than 256.0 | 10       | 0.37%   |
| 0.01-0.5        | 8        | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 0.51-1.0        | 783      | 27.59%  |
| 1.01-2.0        | 565      | 19.91%  |
| 2.01-3.0        | 414      | 14.59%  |
| 4.01-8.0        | 363      | 12.79%  |
| 3.01-4.0        | 267      | 9.41%   |
| 8.01-16.0       | 160      | 5.64%   |
| 0.01-0.5        | 122      | 4.3%    |
| 16.01-24.0      | 66       | 2.33%   |
| 32.01-64.0      | 51       | 1.8%    |
| 24.01-32.0      | 31       | 1.09%   |
| 64.01-256.0     | 15       | 0.53%   |
| More than 256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1320     | 48.14%  |
| 2      | 569      | 20.75%  |
| 3      | 322      | 11.74%  |
| 4      | 223      | 8.13%   |
| 5      | 105      | 3.83%   |
| 6      | 69       | 2.52%   |
| 7      | 37       | 1.35%   |
| 8      | 29       | 1.06%   |
| 9      | 15       | 0.55%   |
| 0      | 15       | 0.55%   |
| 10     | 9        | 0.33%   |
| 12     | 6        | 0.22%   |
| 13     | 5        | 0.18%   |
| 11     | 5        | 0.18%   |
| 19     | 2        | 0.07%   |
| 18     | 2        | 0.07%   |
| 16     | 2        | 0.07%   |
| 14     | 2        | 0.07%   |
| 29     | 1        | 0.04%   |
| 28     | 1        | 0.04%   |
| 27     | 1        | 0.04%   |
| 22     | 1        | 0.04%   |
| 21     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1792     | 66.82%  |
| Yes       | 890      | 33.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2653     | 99.44%  |
| No        | 15       | 0.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1879     | 70.09%  |
| Yes       | 802      | 29.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2053     | 76.58%  |
| Yes       | 628      | 23.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 720      | 26.96%  |
| USA          | 406      | 15.2%   |
| Germany      | 253      | 9.47%   |
| France       | 176      | 6.59%   |
| Spain        | 107      | 4.01%   |
| Brazil       | 81       | 3.03%   |
| UK           | 77       | 2.88%   |
| Italy        | 75       | 2.81%   |
| Canada       | 65       | 2.43%   |
| Poland       | 51       | 1.91%   |
| Australia    | 51       | 1.91%   |
| Netherlands  | 39       | 1.46%   |
| Argentina    | 29       | 1.09%   |
| Mexico       | 28       | 1.05%   |
| Switzerland  | 24       | 0.9%    |
| Belgium      | 24       | 0.9%    |
| Austria      | 24       | 0.9%    |
| Ukraine      | 22       | 0.82%   |
| China        | 22       | 0.82%   |
| Hungary      | 21       | 0.79%   |
| Malaysia     | 18       | 0.67%   |
| Czechia      | 18       | 0.67%   |
| Bulgaria     | 17       | 0.64%   |
| Japan        | 16       | 0.6%    |
| Venezuela    | 15       | 0.56%   |
| Sweden       | 15       | 0.56%   |
| Portugal     | 15       | 0.56%   |
| Norway       | 15       | 0.56%   |
| India        | 15       | 0.56%   |
| Finland      | 15       | 0.56%   |
| Romania      | 13       | 0.49%   |
| Hong Kong    | 11       | 0.41%   |
| Taiwan       | 10       | 0.37%   |
| Turkey       | 9        | 0.34%   |
| Ireland      | 9        | 0.34%   |
| Denmark      | 9        | 0.34%   |
| New Zealand  | 8        | 0.3%    |
| Belarus      | 8        | 0.3%    |
| South Africa | 7        | 0.26%   |
| Morocco      | 7        | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Voronezh       | 570      | 20.79%  |
| Moscow         | 43       | 1.57%   |
| St Petersburg  | 25       | 0.91%   |
| Paris          | 20       | 0.73%   |
| Vienna         | 19       | 0.69%   |
| Falkenstein    | 18       | 0.66%   |
| Seville        | 16       | 0.58%   |
| Barcelona      | 16       | 0.58%   |
| Kuala Lumpur   | 15       | 0.55%   |
| Bangor         | 14       | 0.51%   |
| Sao Paulo      | 13       | 0.47%   |
| Berlin         | 13       | 0.47%   |
| Melbourne      | 12       | 0.44%   |
| Munich         | 11       | 0.4%    |
| Warsaw         | 10       | 0.36%   |
| Sydney         | 10       | 0.36%   |
| Dover-Foxcroft | 10       | 0.36%   |
| Buenos Aires   | 10       | 0.36%   |
| Toronto        | 9        | 0.33%   |
| Chicago        | 9        | 0.33%   |
| Brisbane       | 9        | 0.33%   |
| Sofia          | 8        | 0.29%   |
| Milan          | 8        | 0.29%   |
| Madrid         | 8        | 0.29%   |
| Amsterdam      | 8        | 0.29%   |
| Zurich         | 7        | 0.26%   |
| Yekaterinburg  | 7        | 0.26%   |
| Valencia       | 7        | 0.26%   |
| Stuttgart      | 7        | 0.26%   |
| Siegsdorf      | 7        | 0.26%   |
| San José      | 7        | 0.26%   |
| Nuremberg      | 7        | 0.26%   |
| New York       | 7        | 0.26%   |
| London         | 7        | 0.26%   |
| Las Vegas      | 7        | 0.26%   |
| Kyiv           | 7        | 0.26%   |
| Cologne        | 7        | 0.26%   |
| Central        | 7        | 0.26%   |
| Stockholm      | 6        | 0.22%   |
| Rio de Janeiro | 6        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 813      | 1511   | 17.79%  |
| WDC                         | 785      | 1421   | 17.18%  |
| Samsung Electronics         | 644      | 1025   | 14.09%  |
| Kingston                    | 342      | 459    | 7.48%   |
| Toshiba                     | 318      | 587    | 6.96%   |
| Crucial                     | 263      | 338    | 5.75%   |
| Hitachi                     | 157      | 226    | 3.44%   |
| SanDisk                     | 154      | 203    | 3.37%   |
| Intel                       | 85       | 116    | 1.86%   |
| China                       | 82       | 97     | 1.79%   |
| HGST                        | 77       | 135    | 1.68%   |
| A-DATA Technology           | 65       | 86     | 1.42%   |
| Unknown                     | 45       | 82     | 0.98%   |
| PNY                         | 45       | 91     | 0.98%   |
| SPCC                        | 43       | 49     | 0.94%   |
| Corsair                     | 30       | 46     | 0.66%   |
| Transcend                   | 27       | 28     | 0.59%   |
| Phison                      | 26       | 33     | 0.57%   |
| Netac                       | 26       | 85     | 0.57%   |
| Micron Technology           | 26       | 32     | 0.57%   |
| SK hynix                    | 24       | 52     | 0.53%   |
| Hewlett-Packard             | 24       | 41     | 0.53%   |
| Patriot                     | 23       | 30     | 0.5%    |
| Maxtor                      | 23       | 28     | 0.5%    |
| Intenso                     | 23       | 31     | 0.5%    |
| Unknown                     | 22       | 24     | 0.48%   |
| OCZ                         | 21       | 25     | 0.46%   |
| Gigabyte Technology         | 18       | 19     | 0.39%   |
| GOODRAM                     | 15       | 31     | 0.33%   |
| Apacer                      | 12       | 12     | 0.26%   |
| Team                        | 11       | 18     | 0.24%   |
| JMicron Technology          | 11       | 11     | 0.24%   |
| XPG                         | 8        | 9      | 0.18%   |
| Silicon Motion              | 8        | 11     | 0.18%   |
| Micron/Crucial Technology   | 8        | 10     | 0.18%   |
| LITEON                      | 8        | 12     | 0.18%   |
| Plextor                     | 7        | 10     | 0.15%   |
| Mushkin                     | 7        | 9      | 0.15%   |
| KIOXIA                      | 7        | 9      | 0.15%   |
| Kingston Technology Company | 7        | 13     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 88       | 1.63%   |
| Seagate ST500DM002-1BD142 500GB  | 87       | 1.61%   |
| Crucial CT480BX500SSD1 480GB     | 68       | 1.26%   |
| Toshiba DT01ACA050 500GB         | 63       | 1.17%   |
| Seagate ST1000DM010-2EP102 1TB   | 58       | 1.08%   |
| Kingston SV300S37A120G 120GB SSD | 48       | 0.89%   |
| Kingston SA400S37480G 480GB SSD  | 45       | 0.83%   |
| Samsung SSD 860 EVO 250GB        | 42       | 0.78%   |
| Toshiba DT01ACA100 1TB           | 40       | 0.74%   |
| Samsung SSD 860 EVO 500GB        | 37       | 0.69%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 36       | 0.67%   |
| Seagate ST1000DM003-1ER162 1TB   | 36       | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB   | 34       | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB         | 33       | 0.61%   |
| Samsung SSD 970 EVO Plus 1TB     | 33       | 0.61%   |
| Samsung SSD 860 EVO 1TB          | 33       | 0.61%   |
| Hitachi HDS721050CLA362 500GB    | 32       | 0.59%   |
| Toshiba HDWD110 1TB              | 31       | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB   | 31       | 0.57%   |
| Crucial CT500MX500SSD1 500GB     | 31       | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB   | 29       | 0.54%   |
| Crucial CT240BX500SSD1 240GB     | 29       | 0.54%   |
| Samsung SSD 850 EVO 250GB        | 28       | 0.52%   |
| Crucial CT1000MX500SSD1 1TB      | 27       | 0.5%    |
| Seagate ST4000DM004-2CV104 4TB   | 26       | 0.48%   |
| Samsung SSD 870 EVO 500GB        | 25       | 0.46%   |
| Samsung SSD 850 EVO 500GB        | 24       | 0.44%   |
| Kingston SA400S37120G 120GB SSD  | 24       | 0.44%   |
| Toshiba DT01ACA200 2TB           | 22       | 0.41%   |
| Samsung SSD 980 PRO 1TB          | 22       | 0.41%   |
| Unknown                          | 22       | 0.41%   |
| Seagate ST3500418AS 500GB        | 20       | 0.37%   |
| Seagate ST3250318AS 250GB        | 20       | 0.37%   |
| Netac SSD 240GB                  | 20       | 0.37%   |
| SanDisk NVMe SSD Drive 1TB       | 19       | 0.35%   |
| Samsung SSD 980 1TB              | 19       | 0.35%   |
| WDC WD40EFRX-68N32N0 4TB         | 18       | 0.33%   |
| Seagate ST250DM000-1BD141 250GB  | 18       | 0.33%   |
| Seagate ST1000DM003-1SB102 1TB   | 18       | 0.33%   |
| Samsung SSD 970 EVO Plus 2TB     | 17       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 796      | 1460   | 36.55%  |
| WDC                 | 682      | 1251   | 31.31%  |
| Toshiba             | 295      | 547    | 13.54%  |
| Hitachi             | 157      | 226    | 7.21%   |
| Samsung Electronics | 80       | 104    | 3.67%   |
| HGST                | 75       | 132    | 3.44%   |
| Maxtor              | 22       | 27     | 1.01%   |
| Unknown             | 10       | 15     | 0.46%   |
| Hewlett-Packard     | 9        | 20     | 0.41%   |
| JMicron Technology  | 6        | 6      | 0.28%   |
| SABRENT             | 5        | 5      | 0.23%   |
| External            | 4        | 5      | 0.18%   |
| Intenso             | 3        | 3      | 0.14%   |
| Fujitsu             | 3        | 4      | 0.14%   |
| ASMT                | 3        | 4      | 0.14%   |
| QNAP                | 2        | 3      | 0.09%   |
| IBM/Hitachi         | 2        | 2      | 0.09%   |
| HPE                 | 2        | 6      | 0.09%   |
| Apple               | 2        | 2      | 0.09%   |
| WD MediaMax         | 1        | 6      | 0.05%   |
| Unknown (CF)        | 1        | 1      | 0.05%   |
| Synology            | 1        | 1      | 0.05%   |
| StoreJet            | 1        | 1      | 0.05%   |
| SD                  | 1        | 1      | 0.05%   |
| RSH-319             | 1        | 1      | 0.05%   |
| pqi                 | 1        | 1      | 0.05%   |
| NAS                 | 1        | 5      | 0.05%   |
| MaxDigital          | 1        | 4      | 0.05%   |
| MARSHAL             | 1        | 1      | 0.05%   |
| Inateck             | 1        | 1      | 0.05%   |
| IBM                 | 1        | 4      | 0.05%   |
| Hajaan              | 1        | 1      | 0.05%   |
| H/W                 | 1        | 3      | 0.05%   |
| China               | 1        | 1      | 0.05%   |
| ASMedia             | 1        | 1      | 0.05%   |
| AMP                 | 1        | 1      | 0.05%   |
| Advantech           | 1        | 1      | 0.05%   |
| 3ware               | 1        | 4      | 0.05%   |
| 128MB               | 1        | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 360      | 535    | 21%     |
| Kingston            | 307      | 396    | 17.91%  |
| Crucial             | 235      | 297    | 13.71%  |
| SanDisk             | 102      | 132    | 5.95%   |
| WDC                 | 90       | 99     | 5.25%   |
| China               | 80       | 95     | 4.67%   |
| A-DATA Technology   | 48       | 57     | 2.8%    |
| Intel               | 46       | 61     | 2.68%   |
| SPCC                | 37       | 41     | 2.16%   |
| PNY                 | 33       | 76     | 1.93%   |
| Transcend           | 25       | 26     | 1.46%   |
| Netac               | 25       | 84     | 1.46%   |
| OCZ                 | 21       | 25     | 1.23%   |
| Toshiba             | 20       | 24     | 1.17%   |
| Intenso             | 18       | 24     | 1.05%   |
| Patriot             | 17       | 20     | 0.99%   |
| Micron Technology   | 16       | 18     | 0.93%   |
| GOODRAM             | 13       | 20     | 0.76%   |
| Gigabyte Technology | 11       | 11     | 0.64%   |
| Apacer              | 11       | 11     | 0.64%   |
| Hewlett-Packard     | 10       | 14     | 0.58%   |
| Corsair             | 10       | 14     | 0.58%   |
| Team                | 9        | 13     | 0.53%   |
| Unknown             | 9        | 10     | 0.53%   |
| LITEON              | 7        | 11     | 0.41%   |
| Hajaan              | 7        | 8      | 0.41%   |
| Seagate             | 6        | 7      | 0.35%   |
| NGFF                | 6        | 6      | 0.35%   |
| Mushkin             | 6        | 7      | 0.35%   |
| Xinhaike            | 5        | 8      | 0.29%   |
| SK hynix            | 5        | 6      | 0.29%   |
| Plextor             | 5        | 8      | 0.29%   |
| LITEONIT            | 5        | 9      | 0.29%   |
| Innodisk            | 5        | 5      | 0.29%   |
| Unknown             | 4        | 7      | 0.23%   |
| KingDian            | 4        | 4      | 0.23%   |
| Hoodisk             | 4        | 4      | 0.23%   |
| Foxline             | 4        | 4      | 0.23%   |
| Drevo               | 4        | 4      | 0.23%   |
| T-FORCE             | 3        | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1699     | 3862   | 43.85%  |
| SSD     | 1436     | 2297   | 37.06%  |
| NVMe    | 657      | 1040   | 16.95%  |
| Unknown | 56       | 123    | 1.45%   |
| MMC     | 27       | 30     | 0.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2402     | 5875   | 74%     |
| NVMe | 652      | 1029   | 20.09%  |
| SAS  | 165      | 418    | 5.08%   |
| MMC  | 27       | 30     | 0.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1851     | 2962   | 52.71%  |
| 0.51-1.0   | 796      | 1309   | 22.67%  |
| 1.01-2.0   | 364      | 656    | 10.36%  |
| 3.01-4.0   | 198      | 424    | 5.64%   |
| 4.01-10.0  | 152      | 368    | 4.33%   |
| 2.01-3.0   | 99       | 216    | 2.82%   |
| 10.01-20.0 | 52       | 224    | 1.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 705      | 25.78%  |
| 101-250        | 414      | 15.14%  |
| 251-500        | 344      | 12.58%  |
| 501-1000       | 338      | 12.36%  |
| More than 3000 | 285      | 10.42%  |
| 1001-2000      | 200      | 7.31%   |
| 51-100         | 150      | 5.48%   |
| 1-20           | 107      | 3.91%   |
| 2001-3000      | 102      | 3.73%   |
| 21-50          | 90       | 3.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 740      | 26.59%  |
| Unknown        | 705      | 25.33%  |
| 101-250        | 253      | 9.09%   |
| 21-50          | 217      | 7.8%    |
| 51-100         | 206      | 7.4%    |
| 251-500        | 179      | 6.43%   |
| 501-1000       | 162      | 5.82%   |
| More than 3000 | 130      | 4.67%   |
| 1001-2000      | 121      | 4.35%   |
| 2001-3000      | 62       | 2.23%   |
| 0              | 8        | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 22       | 37     | 3.45%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 20       | 24     | 3.13%   |
| Kingston SV300S37A120G 120GB SSD | 17       | 17     | 2.66%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 8        | 8      | 1.25%   |
| Seagate ST3500418AS 500GB        | 8        | 10     | 1.25%   |
| Hitachi HDS721050CLA362 500GB    | 8        | 8      | 1.25%   |
| Seagate ST3250318AS 250GB        | 7        | 8      | 1.1%    |
| Seagate ST250DM000-1BD141 250GB  | 7        | 7      | 1.1%    |
| Seagate ST1000DM003-9YN162 1TB   | 7        | 8      | 1.1%    |
| Toshiba DT01ACA050 500GB         | 6        | 7      | 0.94%   |
| Seagate ST31000528AS 1TB         | 6        | 7      | 0.94%   |
| Hitachi HDS721050DLE630 500GB    | 6        | 11     | 0.94%   |
| WDC WD20EARX-00PASB0 2TB         | 5        | 5      | 0.78%   |
| WDC WD20EARS-00MVWB0 2TB         | 5        | 5      | 0.78%   |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 5      | 0.78%   |
| Seagate ST3320613AS 320GB        | 5        | 5      | 0.78%   |
| Seagate ST31500341AS 1TB         | 5        | 7      | 0.78%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 4      | 0.63%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 4        | 5      | 0.63%   |
| Seagate ST3500413AS 500GB        | 4        | 5      | 0.63%   |
| Seagate ST2000DL003-9VT166 2TB   | 4        | 4      | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB   | 4        | 5      | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 4      | 0.63%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 3      | 0.47%   |
| WDC WD40EFRX-68N32N0 4TB         | 3        | 6      | 0.47%   |
| WDC WD3200AAJS-08L7A0 320GB      | 3        | 3      | 0.47%   |
| WDC WD3200AAJS-00L7A0 320GB      | 3        | 3      | 0.47%   |
| WDC WD30EFRX-68EUZN0 3TB         | 3        | 3      | 0.47%   |
| WDC WD2500AAJS-00YZCA0 250GB     | 3        | 3      | 0.47%   |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 3      | 0.47%   |
| Toshiba MK2555GSXF 250GB         | 3        | 3      | 0.47%   |
| Toshiba DT01ACA100 1TB           | 3        | 4      | 0.47%   |
| Seagate ST3320620AS 320GB        | 3        | 5      | 0.47%   |
| Seagate ST3320418AS 320GB        | 3        | 5      | 0.47%   |
| Seagate ST3250310AS 250GB        | 3        | 3      | 0.47%   |
| Seagate ST3120827AS 120GB        | 3        | 4      | 0.47%   |
| Seagate ST3120811AS 120GB        | 3        | 3      | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 4      | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 3      | 0.47%   |
| Seagate ST2000DM001-1CH164 2TB   | 3        | 4      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 187      | 260    | 30.76%  |
| WDC                 | 178      | 229    | 29.28%  |
| Hitachi             | 45       | 60     | 7.4%    |
| Samsung Electronics | 41       | 48     | 6.74%   |
| Toshiba             | 32       | 40     | 5.26%   |
| Kingston            | 31       | 36     | 5.1%    |
| Intel               | 18       | 22     | 2.96%   |
| A-DATA Technology   | 11       | 14     | 1.81%   |
| Maxtor              | 10       | 13     | 1.64%   |
| Crucial             | 8        | 13     | 1.32%   |
| SanDisk             | 7        | 7      | 1.15%   |
| HGST                | 6        | 6      | 0.99%   |
| China               | 4        | 4      | 0.66%   |
| Transcend           | 3        | 3      | 0.49%   |
| SK hynix            | 3        | 6      | 0.49%   |
| Apacer              | 3        | 3      | 0.49%   |
| SPCC                | 2        | 2      | 0.33%   |
| OCZ                 | 2        | 2      | 0.33%   |
| Micron Technology   | 2        | 2      | 0.33%   |
| Hewlett-Packard     | 2        | 3      | 0.33%   |
| Corsair             | 2        | 2      | 0.33%   |
| Western Digital     | 1        | 2      | 0.16%   |
| ShiJi               | 1        | 1      | 0.16%   |
| PNY                 | 1        | 1      | 0.16%   |
| Patriot             | 1        | 1      | 0.16%   |
| LITEONIT            | 1        | 1      | 0.16%   |
| KingDian            | 1        | 1      | 0.16%   |
| Intenso             | 1        | 1      | 0.16%   |
| IBM                 | 1        | 4      | 0.16%   |
| HANCHU              | 1        | 1      | 0.16%   |
| Fujitsu             | 1        | 2      | 0.16%   |
| EK46XL85C49         | 1        | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 187      | 260    | 39.29%  |
| WDC                 | 171      | 221    | 35.92%  |
| Hitachi             | 45       | 60     | 9.45%   |
| Toshiba             | 30       | 38     | 6.3%    |
| Samsung Electronics | 23       | 26     | 4.83%   |
| Maxtor              | 10       | 13     | 2.1%    |
| HGST                | 6        | 6      | 1.26%   |
| Hewlett-Packard     | 2        | 3      | 0.42%   |
| IBM                 | 1        | 4      | 0.21%   |
| Fujitsu             | 1        | 2      | 0.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 438      | 633    | 77.11%  |
| SSD  | 113      | 132    | 19.89%  |
| NVMe | 17       | 26     | 2.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| WDC WD4001FFSX-68JNUN0 4TB                  | 1        | 1      | 6.25%   |
| Seagate ST500DM005 HD502HJ 500GB            | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB             | 1        | 2      | 6.25%   |
| Seagate ST3500830AS 500GB                   | 1        | 1      | 6.25%   |
| Seagate ST3500630A 500GB                    | 1        | 1      | 6.25%   |
| Seagate ST2000NM0011 2TB                    | 1        | 1      | 6.25%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 980 1TB             | 1        | 1      | 6.25%   |
| Samsung Electronics SP0802N 80GB            | 1        | 1      | 6.25%   |
| Samsung Electronics HD253GJ 250GB           | 1        | 1      | 6.25%   |
| Samsung Electronics HD103SJ 1TB             | 1        | 1      | 6.25%   |
| Intel SSDSC2KW256G8 256GB                   | 1        | 1      | 6.25%   |
| Inland SATA SSD 128GB                       | 1        | 1      | 6.25%   |
| HGST HUH728080ALN600 8TB                    | 1        | 1      | 6.25%   |
| HGST HDN724040ALE640 4TB                    | 1        | 1      | 6.25%   |
| Hewlett-Packard SSD S700 500GB              | 1        | 2      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 31.25%  |
| Samsung Electronics | 5        | 5      | 31.25%  |
| HGST                | 2        | 2      | 12.5%   |
| WDC                 | 1        | 1      | 6.25%   |
| Intel               | 1        | 1      | 6.25%   |
| Inland              | 1        | 1      | 6.25%   |
| Hewlett-Packard     | 1        | 2      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 2037     | 4957   | 64.96%  |
| Malfunc  | 546      | 791    | 17.41%  |
| Detected | 536      | 1585   | 17.09%  |
| Failed   | 16       | 18     | 0.51%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1883     | 50.46%  |
| AMD                              | 694      | 18.6%   |
| Samsung Electronics              | 270      | 7.23%   |
| ASMedia Technology               | 134      | 3.59%   |
| SanDisk                          | 104      | 2.79%   |
| Phison Electronics               | 81       | 2.17%   |
| Marvell Technology Group         | 76       | 2.04%   |
| JMicron Technology               | 73       | 1.96%   |
| Nvidia                           | 56       | 1.5%    |
| Kingston Technology Company      | 50       | 1.34%   |
| Micron/Crucial Technology        | 39       | 1.05%   |
| LSI Logic / Symbios Logic        | 35       | 0.94%   |
| VIA Technologies                 | 33       | 0.88%   |
| Broadcom / LSI                   | 25       | 0.67%   |
| ADATA Technology                 | 23       | 0.62%   |
| Silicon Motion                   | 22       | 0.59%   |
| SK hynix                         | 18       | 0.48%   |
| Adaptec                          | 13       | 0.35%   |
| Toshiba America Info Systems     | 12       | 0.32%   |
| MAXIO Technology (Hangzhou)      | 12       | 0.32%   |
| Micron Technology                | 11       | 0.29%   |
| Silicon Image                    | 9        | 0.24%   |
| Realtek Semiconductor            | 9        | 0.24%   |
| KIOXIA                           | 8        | 0.21%   |
| Seagate Technology               | 6        | 0.16%   |
| INNOGRIT                         | 5        | 0.13%   |
| Silicon Integrated Systems [SiS] | 4        | 0.11%   |
| Hewlett-Packard                  | 4        | 0.11%   |
| Shenzhen Longsys Electronics     | 3        | 0.08%   |
| Lite-On Technology               | 3        | 0.08%   |
| Integrated Technology Express    | 3        | 0.08%   |
| Biwin Storage Technology         | 3        | 0.08%   |
| Swissbit                         | 2        | 0.05%   |
| 3ware                            | 2        | 0.05%   |
| Solid State Storage Technology   | 1        | 0.03%   |
| Netac Technology                 | 1        | 0.03%   |
| Jiangsu Huacun Elec.             | 1        | 0.03%   |
| Innodisk                         | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Broadcom                         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 380      | 8.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 234      | 5.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 153      | 3.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 152      | 3.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 150      | 3.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 150      | 3.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 141      | 3.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 138      | 3%      |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 110      | 2.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 106      | 2.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 102      | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 98       | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 93       | 2.02%   |
| Intel SATA Controller [RAID mode]                                                       | 81       | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 81       | 1.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 74       | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 71       | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 64       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 64       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 64       | 1.39%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 57       | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 56       | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 43       | 0.93%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 42       | 0.91%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 41       | 0.89%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 40       | 0.87%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 39       | 0.85%   |
| Phison E12 NVMe Controller                                                              | 38       | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 36       | 0.78%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 33       | 0.72%   |
| Nvidia MCP61 SATA Controller                                                            | 31       | 0.67%   |
| AMD 300 Series Chipset SATA Controller                                                  | 31       | 0.67%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 29       | 0.63%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 29       | 0.63%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 28       | 0.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 28       | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 26       | 0.56%   |
| Nvidia MCP61 IDE                                                                        | 25       | 0.54%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 25       | 0.54%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 25       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2161     | 58.55%  |
| NVMe | 653      | 17.69%  |
| IDE  | 623      | 16.88%  |
| RAID | 169      | 4.58%   |
| SAS  | 68       | 1.84%   |
| SCSI | 17       | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1903     | 71.33%  |
| AMD                   | 755      | 28.3%   |
| CentaurHauls          | 5        | 0.19%   |
| sifive,u74-mc         | 3        | 0.11%   |
| Marvell Semiconductor | 1        | 0.04%   |
| Unknown               | 1        | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 63       | 2.36%   |
| AMD Ryzen 5 3600 6-Core Processor           | 38       | 1.42%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 36       | 1.35%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 35       | 1.31%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 31       | 1.16%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 28       | 1.05%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 28       | 1.05%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 27       | 1.01%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 27       | 1.01%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 26       | 0.97%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 25       | 0.93%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 24       | 0.9%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 23       | 0.86%   |
| Intel Celeron N5105 @ 2.00GHz               | 23       | 0.86%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 23       | 0.86%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 22       | 0.82%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 22       | 0.82%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 22       | 0.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 22       | 0.82%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 21       | 0.79%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 21       | 0.79%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 20       | 0.75%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 20       | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 20       | 0.75%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 19       | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 19       | 0.71%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 19       | 0.71%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 19       | 0.71%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 19       | 0.71%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 18       | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 18       | 0.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 17       | 0.64%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 17       | 0.64%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 17       | 0.64%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 17       | 0.64%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 16       | 0.6%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16       | 0.6%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 16       | 0.6%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 16       | 0.6%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 15       | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 449      | 16.81%  |
| Intel Core i3           | 247      | 9.25%   |
| Intel Core i7           | 240      | 8.99%   |
| Intel Pentium           | 175      | 6.55%   |
| Intel Xeon              | 172      | 6.44%   |
| AMD Ryzen 5             | 166      | 6.21%   |
| Intel Celeron           | 159      | 5.95%   |
| AMD Ryzen 7             | 130      | 4.87%   |
| Other                   | 124      | 4.64%   |
| Intel Core 2 Duo        | 105      | 3.93%   |
| AMD Ryzen 9             | 91       | 3.41%   |
| AMD FX                  | 76       | 2.85%   |
| Intel Pentium Dual-Core | 59       | 2.21%   |
| Intel Core 2 Quad       | 37       | 1.39%   |
| AMD Ryzen 3             | 37       | 1.39%   |
| Intel Atom              | 33       | 1.24%   |
| Intel Core i9           | 26       | 0.97%   |
| AMD Ryzen Threadripper  | 25       | 0.94%   |
| AMD Athlon              | 21       | 0.79%   |
| AMD A10                 | 21       | 0.79%   |
| Intel Pentium Gold      | 20       | 0.75%   |
| AMD Athlon 64 X2        | 19       | 0.71%   |
| Intel Pentium 4         | 18       | 0.67%   |
| AMD Phenom II X4        | 18       | 0.67%   |
| AMD Athlon II X2        | 18       | 0.67%   |
| Intel Core 2            | 14       | 0.52%   |
| AMD GX                  | 14       | 0.52%   |
| Intel Pentium Silver    | 11       | 0.41%   |
| AMD Ryzen 5 PRO         | 11       | 0.41%   |
| AMD Phenom II X6        | 11       | 0.41%   |
| Intel Pentium Dual      | 9        | 0.34%   |
| AMD G                   | 9        | 0.34%   |
| AMD A8                  | 9        | 0.34%   |
| Intel Pentium D         | 8        | 0.3%    |
| AMD A4                  | 8        | 0.3%    |
| AMD Sempron             | 7        | 0.26%   |
| AMD Athlon II X4        | 6        | 0.22%   |
| AMD A6                  | 6        | 0.22%   |
| Intel Genuine           | 5        | 0.19%   |
| AMD Turion II Neo       | 5        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 896      | 33.52%  |
| 2       | 807      | 30.19%  |
| 6       | 390      | 14.59%  |
| 8       | 249      | 9.32%   |
| 1       | 81       | 3.03%   |
| 16      | 79       | 2.96%   |
| 12      | 76       | 2.84%   |
| 3       | 31       | 1.16%   |
| 10      | 20       | 0.75%   |
| 32      | 12       | 0.45%   |
| 24      | 12       | 0.45%   |
| 14      | 5        | 0.19%   |
| 18      | 4        | 0.15%   |
| Unknown | 4        | 0.15%   |
| 44      | 2        | 0.07%   |
| 20      | 2        | 0.07%   |
| 64      | 1        | 0.04%   |
| 36      | 1        | 0.04%   |
| 28      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2617     | 98.05%  |
| 2       | 47       | 1.76%   |
| Unknown | 4        | 0.15%   |
| 0       | 1        | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1388     | 51.95%  |
| 1       | 1280     | 47.9%   |
| Unknown | 4        | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2633     | 98.65%  |
| 32-bit         | 30       | 1.12%   |
| Unknown        | 6        | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 466      | 17.08%  |
| 0x306c3    | 243      | 8.91%   |
| 0x206a7    | 149      | 5.46%   |
| 0x306a9    | 144      | 5.28%   |
| 0x1067a    | 140      | 5.13%   |
| 0x506e3    | 117      | 4.29%   |
| 0x906ea    | 113      | 4.14%   |
| 0xa0653    | 74       | 2.71%   |
| 0x08701021 | 71       | 2.6%    |
| 0x906e9    | 52       | 1.91%   |
| 0x906c0    | 43       | 1.58%   |
| 0x0a201016 | 42       | 1.54%   |
| 0xa0671    | 39       | 1.43%   |
| 0xa0655    | 39       | 1.43%   |
| 0x08108109 | 38       | 1.39%   |
| 0x0800820d | 36       | 1.32%   |
| 0x90672    | 31       | 1.14%   |
| 0x010000c8 | 26       | 0.95%   |
| 0x6fd      | 23       | 0.84%   |
| 0x906ed    | 22       | 0.81%   |
| 0x306f2    | 22       | 0.81%   |
| 0x906eb    | 20       | 0.73%   |
| 0x0a50000c | 20       | 0.73%   |
| 0x08101016 | 20       | 0.73%   |
| 0x6fb      | 19       | 0.7%    |
| 0x0a50000d | 19       | 0.7%    |
| 0x90675    | 18       | 0.66%   |
| 0x206d7    | 18       | 0.66%   |
| 0x06003106 | 18       | 0.66%   |
| 0x06000852 | 18       | 0.66%   |
| 0x06000822 | 18       | 0.66%   |
| 0x306e4    | 17       | 0.62%   |
| 0x206c2    | 17       | 0.62%   |
| 0x706a8    | 16       | 0.59%   |
| 0x0a201009 | 16       | 0.59%   |
| 0x08600106 | 16       | 0.59%   |
| 0x506c9    | 15       | 0.55%   |
| 0x10676    | 15       | 0.55%   |
| 0x0a20120a | 15       | 0.55%   |
| 0x010000b6 | 15       | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 326      | 12.19%  |
| KabyLake         | 260      | 9.72%   |
| SandyBridge      | 195      | 7.29%   |
| IvyBridge        | 186      | 6.95%   |
| Penryn           | 178      | 6.65%   |
| Zen 3            | 154      | 5.76%   |
| Skylake          | 147      | 5.5%    |
| Zen 2            | 144      | 5.38%   |
| CometLake        | 132      | 4.93%   |
| Unknown          | 107      | 4%      |
| Zen+             | 104      | 3.89%   |
| Piledriver       | 74       | 2.77%   |
| Core             | 73       | 2.73%   |
| K10              | 72       | 2.69%   |
| Zen              | 66       | 2.47%   |
| Tremont          | 51       | 1.91%   |
| Westmere         | 46       | 1.72%   |
| Silvermont       | 36       | 1.35%   |
| NetBurst         | 33       | 1.23%   |
| Nehalem          | 31       | 1.16%   |
| K8 Hammer        | 31       | 1.16%   |
| Goldmont plus    | 28       | 1.05%   |
| Alderlake Hybrid | 27       | 1.01%   |
| Steamroller      | 22       | 0.82%   |
| Goldmont         | 21       | 0.79%   |
| Bulldozer        | 19       | 0.71%   |
| Bonnell          | 19       | 0.71%   |
| Broadwell        | 15       | 0.56%   |
| Icelake          | 13       | 0.49%   |
| Excavator        | 13       | 0.49%   |
| Bobcat           | 13       | 0.49%   |
| Jaguar           | 12       | 0.45%   |
| Puma             | 8        | 0.3%    |
| P6               | 6        | 0.22%   |
| TigerLake        | 4        | 0.15%   |
| K6               | 4        | 0.15%   |
| K10 Llano        | 2        | 0.07%   |
| Gracemont        | 2        | 0.07%   |
| Geode            | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1217     | 43.11%  |
| Nvidia                           | 878      | 31.1%   |
| AMD                              | 628      | 22.25%  |
| ASPEED Technology                | 61       | 2.16%   |
| Matrox Electronics Systems       | 27       | 0.96%   |
| VIA Technologies                 | 8        | 0.28%   |
| Silicon Integrated Systems [SiS] | 3        | 0.11%   |
| ATI Technologies                 | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 175      | 6.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 122      | 4.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 101      | 3.51%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 84       | 2.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 81       | 2.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 68       | 2.36%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 63       | 2.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 63       | 2.19%   |
| ASPEED Technology ASPEED Graphics Family                                    | 61       | 2.12%   |
| Nvidia GK208B [GeForce GT 710]                                              | 60       | 2.09%   |
| Intel HD Graphics 530                                                       | 56       | 1.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 51       | 1.77%   |
| Intel JasperLake [UHD Graphics]                                             | 45       | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 42       | 1.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 41       | 1.43%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 40       | 1.39%   |
| Nvidia GF108 [GeForce GT 730]                                               | 38       | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 36       | 1.25%   |
| Intel HD Graphics 630                                                       | 35       | 1.22%   |
| Intel HD Graphics 510                                                       | 30       | 1.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 29       | 1.01%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 28       | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 25       | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 25       | 0.87%   |
| Nvidia GF108 [GeForce GT 630]                                               | 25       | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 24       | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 23       | 0.8%    |
| Intel AlderLake-S GT1                                                       | 23       | 0.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 23       | 0.8%    |
| Nvidia GT218 [GeForce 210]                                                  | 22       | 0.76%   |
| Nvidia GK208B [GeForce GT 730]                                              | 21       | 0.73%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 19       | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 18       | 0.63%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 18       | 0.63%   |
| Intel HD Graphics 500                                                       | 17       | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 17       | 0.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 17       | 0.59%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 16       | 0.56%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 16       | 0.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 15       | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 1103     | 40.97%  |
| 1 x Nvidia                        | 789      | 29.31%  |
| 1 x AMD                           | 564      | 20.95%  |
| 1 x ASPEED                        | 45       | 1.67%   |
| Intel + Nvidia                    | 44       | 1.63%   |
| 1 x Matrox                        | 26       | 0.97%   |
| Other                             | 24       | 0.89%   |
| AMD + Nvidia                      | 24       | 0.89%   |
| 2 x AMD                           | 22       | 0.82%   |
| Nvidia + ASPEED                   | 9        | 0.33%   |
| Intel + AMD                       | 9        | 0.33%   |
| 2 x Nvidia                        | 8        | 0.3%    |
| 1 x VIA                           | 8        | 0.3%    |
| AMD + ASPEED                      | 5        | 0.19%   |
| 1 x SiS                           | 3        | 0.11%   |
| Intel + 2 x Nvidia                | 3        | 0.11%   |
| 3 x AMD                           | 2        | 0.07%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.04%   |
| 2 x Intel                         | 1        | 0.04%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.04%   |
| AMD + Matrox                      | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1428     | 53.05%  |
| Unknown     | 896      | 33.28%  |
| Proprietary | 368      | 13.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1799     | 66.46%  |
| 1.01-2.0   | 219      | 8.09%   |
| 0.01-0.5   | 160      | 5.91%   |
| 0.51-1.0   | 143      | 5.28%   |
| 3.01-4.0   | 137      | 5.06%   |
| 7.01-8.0   | 119      | 4.4%    |
| 5.01-6.0   | 59       | 2.18%   |
| 8.01-16.0  | 37       | 1.37%   |
| 2.01-3.0   | 19       | 0.7%    |
| 16.01-24.0 | 8        | 0.3%    |
| 4.01-5.0   | 5        | 0.18%   |
| 32.01-64.0 | 1        | 0.04%   |
| 24.01-32.0 | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 283      | 15.22%  |
| Dell                    | 210      | 11.3%   |
| Goldstar                | 183      | 9.84%   |
| Acer                    | 122      | 6.56%   |
| Hewlett-Packard         | 114      | 6.13%   |
| BenQ                    | 102      | 5.49%   |
| AOC                     | 92       | 4.95%   |
| Philips                 | 83       | 4.46%   |
| Ancor Communications    | 80       | 4.3%    |
| Unknown                 | 47       | 2.53%   |
| ViewSonic               | 43       | 2.31%   |
| Iiyama                  | 42       | 2.26%   |
| ASUSTek Computer        | 36       | 1.94%   |
| Eizo                    | 28       | 1.51%   |
| Lenovo                  | 26       | 1.4%    |
| Sony                    | 24       | 1.29%   |
| LG Electronics          | 22       | 1.18%   |
| NEC Computers           | 20       | 1.08%   |
| Unknown                 | 15       | 0.81%   |
| Vestel Elektronik       | 10       | 0.54%   |
| Medion                  | 10       | 0.54%   |
| Vizio                   | 9        | 0.48%   |
| MSI                     | 9        | 0.48%   |
| Fujitsu Siemens         | 8        | 0.43%   |
| Sceptre Tech            | 6        | 0.32%   |
| Packard Bell            | 6        | 0.32%   |
| HannStar                | 6        | 0.32%   |
| Belinea                 | 6        | 0.32%   |
| Toshiba                 | 5        | 0.27%   |
| Panasonic               | 5        | 0.27%   |
| Idek Iiyama             | 5        | 0.27%   |
| HPN                     | 5        | 0.27%   |
| Hitachi                 | 5        | 0.27%   |
| Plain Tree Systems      | 4        | 0.22%   |
| MStar                   | 4        | 0.22%   |
| Microstep               | 4        | 0.22%   |
| Lenovo Group Limited    | 4        | 0.22%   |
| HUAWEI                  | 4        | 0.22%   |
| HKC                     | 4        | 0.22%   |
| Chi Mei Optoelectronics | 4        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 34       | 1.73%   |
| Unknown                                                               | 15       | 0.77%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 11       | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 11       | 0.56%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 9        | 0.46%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 8        | 0.41%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 8        | 0.41%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 7        | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 7        | 0.36%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 6        | 0.31%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6        | 0.31%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 6        | 0.31%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 6        | 0.31%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                        | 6        | 0.31%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 5        | 0.26%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 0.26%   |
| Hewlett-Packard E201 HWP305F 1600x900 443x249mm 20.0-inch             | 5        | 0.26%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 5        | 0.26%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5        | 0.26%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 5        | 0.26%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 5        | 0.26%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 5        | 0.26%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 5        | 0.26%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 5        | 0.26%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 5        | 0.26%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 4        | 0.2%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 4        | 0.2%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 4        | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 4        | 0.2%    |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 4        | 0.2%    |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 4        | 0.2%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 4        | 0.2%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4        | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4        | 0.2%    |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                     | 4        | 0.2%    |
| BenQ GL2480 BNQ78ED 1920x1080 531x298mm 24.0-inch                     | 4        | 0.2%    |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 4        | 0.2%    |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                    | 4        | 0.2%    |
| AOC 2475W1 AOC2475 1920x1080 527x296mm 23.8-inch                      | 4        | 0.2%    |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 4        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 790      | 43.19%  |
| 3840x2160 (4K)     | 176      | 9.62%   |
| 1280x1024 (SXGA)   | 159      | 8.69%   |
| 2560x1440 (QHD)    | 126      | 6.89%   |
| 1680x1050 (WSXGA+) | 85       | 4.65%   |
| Unknown            | 62       | 3.39%   |
| 1366x768 (WXGA)    | 58       | 3.17%   |
| 1920x1200 (WUXGA)  | 48       | 2.62%   |
| 1600x900 (HD+)     | 48       | 2.62%   |
| 1440x900 (WXGA+)   | 43       | 2.35%   |
| 2288x1287          | 36       | 1.97%   |
| 3440x1440          | 24       | 1.31%   |
| 2560x1080          | 24       | 1.31%   |
| 1360x768           | 24       | 1.31%   |
| 1024x768 (XGA)     | 23       | 1.26%   |
| 3840x1080          | 19       | 1.04%   |
| 1600x1200          | 17       | 0.93%   |
| 1920x540           | 6        | 0.33%   |
| 4480x1440          | 5        | 0.27%   |
| 5760x1080          | 4        | 0.22%   |
| 3200x1080          | 4        | 0.22%   |
| 5120x1440          | 3        | 0.16%   |
| 2560x1600          | 3        | 0.16%   |
| 1400x1050          | 3        | 0.16%   |
| 5760x2160          | 2        | 0.11%   |
| 5360x1440          | 2        | 0.11%   |
| 3840x1200          | 2        | 0.11%   |
| 3360x1050          | 2        | 0.11%   |
| 2048x1152          | 2        | 0.11%   |
| 1280x800 (WXGA)    | 2        | 0.11%   |
| 1280x720 (HD)      | 2        | 0.11%   |
| 7680x4320          | 1        | 0.05%   |
| 6400x2160          | 1        | 0.05%   |
| 6160x1440          | 1        | 0.05%   |
| 5120x2160          | 1        | 0.05%   |
| 5120x1080          | 1        | 0.05%   |
| 4480x1600          | 1        | 0.05%   |
| 3840x2560          | 1        | 0.05%   |
| 3840x1600          | 1        | 0.05%   |
| 3600x1080          | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 268      | 14.81%  |
| 27      | 233      | 12.88%  |
| 23      | 215      | 11.89%  |
| 21      | 169      | 9.34%   |
| Unknown | 163      | 9.01%   |
| 19      | 115      | 6.36%   |
| 17      | 79       | 4.37%   |
| 31      | 77       | 4.26%   |
| 18      | 75       | 4.15%   |
| 22      | 60       | 3.32%   |
| 20      | 58       | 3.21%   |
| 15      | 43       | 2.38%   |
| 34      | 36       | 1.99%   |
| 142     | 34       | 1.88%   |
| 84      | 25       | 1.38%   |
| 72      | 19       | 1.05%   |
| 32      | 19       | 1.05%   |
| 54      | 13       | 0.72%   |
| 25      | 11       | 0.61%   |
| 28      | 10       | 0.55%   |
| 40      | 8        | 0.44%   |
| 52      | 7        | 0.39%   |
| 26      | 7        | 0.39%   |
| 13      | 7        | 0.39%   |
| 48      | 5        | 0.28%   |
| 65      | 4        | 0.22%   |
| 42      | 4        | 0.22%   |
| 35      | 4        | 0.22%   |
| 33      | 4        | 0.22%   |
| 29      | 4        | 0.22%   |
| 39      | 3        | 0.17%   |
| 16      | 3        | 0.17%   |
| 12      | 3        | 0.17%   |
| 75      | 2        | 0.11%   |
| 64      | 2        | 0.11%   |
| 60      | 2        | 0.11%   |
| 49      | 2        | 0.11%   |
| 43      | 2        | 0.11%   |
| 36      | 2        | 0.11%   |
| 99      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 650      | 37.12%  |
| 401-500        | 396      | 22.62%  |
| Unknown        | 163      | 9.31%   |
| 601-700        | 120      | 6.85%   |
| 301-350        | 117      | 6.68%   |
| 351-400        | 89       | 5.08%   |
| 701-800        | 59       | 3.37%   |
| 1501-2000      | 48       | 2.74%   |
| 1001-1500      | 37       | 2.11%   |
| More than 2000 | 35       | 2%      |
| 801-900        | 17       | 0.97%   |
| 201-300        | 12       | 0.69%   |
| 901-1000       | 6        | 0.34%   |
| 101-200        | 2        | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1051     | 61.86%  |
| 16/10   | 189      | 11.12%  |
| 5/4     | 147      | 8.65%   |
| Unknown | 146      | 8.59%   |
| 4/3     | 53       | 3.12%   |
| 21/9    | 45       | 2.65%   |
| 1.00    | 36       | 2.12%   |
| 3/2     | 13       | 0.77%   |
| 6/5     | 10       | 0.59%   |
| 32/9    | 4        | 0.24%   |
| 2.65    | 1        | 0.06%   |
| 2.00    | 1        | 0.06%   |
| 11/10   | 1        | 0.06%   |
| 1.96    | 1        | 0.06%   |
| 0.56    | 1        | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 569      | 32.13%  |
| 301-350        | 238      | 13.44%  |
| 151-200        | 227      | 12.82%  |
| Unknown        | 163      | 9.2%    |
| 351-500        | 149      | 8.41%   |
| 141-150        | 129      | 7.28%   |
| More than 1000 | 115      | 6.49%   |
| 251-300        | 92       | 5.19%   |
| 101-110        | 36       | 2.03%   |
| 501-1000       | 24       | 1.36%   |
| 71-80          | 7        | 0.4%    |
| 111-120        | 6        | 0.34%   |
| 131-140        | 5        | 0.28%   |
| 121-130        | 4        | 0.23%   |
| 81-90          | 3        | 0.17%   |
| 1-40           | 2        | 0.11%   |
| 41-50          | 1        | 0.06%   |
| 91-100         | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1051     | 62.01%  |
| 101-120       | 271      | 15.99%  |
| Unknown       | 163      | 9.62%   |
| 1-50          | 92       | 5.43%   |
| 121-160       | 80       | 4.72%   |
| 161-240       | 36       | 2.12%   |
| More than 240 | 2        | 0.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1331     | 49.13%  |
| 0     | 1037     | 38.28%  |
| 2     | 312      | 11.52%  |
| 3     | 27       | 1%      |
| 4     | 2        | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1657     | 46.27%  |
| Intel                            | 1092     | 30.49%  |
| Qualcomm Atheros                 | 193      | 5.39%   |
| Broadcom                         | 93       | 2.6%    |
| Ralink Technology                | 56       | 1.56%   |
| Nvidia                           | 48       | 1.34%   |
| TP-Link                          | 40       | 1.12%   |
| MediaTek                         | 34       | 0.95%   |
| Broadcom Limited                 | 28       | 0.78%   |
| Ralink                           | 24       | 0.67%   |
| Aquantia                         | 20       | 0.56%   |
| Marvell Technology Group         | 19       | 0.53%   |
| Mellanox Technologies            | 17       | 0.47%   |
| D-Link System                    | 16       | 0.45%   |
| Samsung Electronics              | 15       | 0.42%   |
| Qualcomm Atheros Communications  | 15       | 0.42%   |
| ASIX Electronics                 | 15       | 0.42%   |
| American Megatrends              | 13       | 0.36%   |
| VIA Technologies                 | 11       | 0.31%   |
| Huawei Technologies              | 10       | 0.28%   |
| D-Link                           | 10       | 0.28%   |
| NetGear                          | 9        | 0.25%   |
| Microsoft                        | 9        | 0.25%   |
| Edimax Technology                | 9        | 0.25%   |
| ASUSTek Computer                 | 9        | 0.25%   |
| Xiaomi                           | 8        | 0.22%   |
| 3Com                             | 7        | 0.2%    |
| Sigma Designs                    | 5        | 0.14%   |
| Gemtek                           | 5        | 0.14%   |
| Belkin Components                | 5        | 0.14%   |
| ZTE WCDMA Technologies MSM       | 4        | 0.11%   |
| Texas Instruments                | 4        | 0.11%   |
| Dresden Elektronik               | 4        | 0.11%   |
| Silicon Integrated Systems [SiS] | 3        | 0.08%   |
| QLogic                           | 3        | 0.08%   |
| QinHeng Electronics              | 3        | 0.08%   |
| OPPO Electronics                 | 3        | 0.08%   |
| IMC Networks                     | 3        | 0.08%   |
| ICS Advent                       | 3        | 0.08%   |
| Emulex                           | 3        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1324     | 33.07%  |
| Realtek RTL8125 2.5GbE Controller                                      | 133      | 3.32%   |
| Intel I211 Gigabit Network Connection                                  | 98       | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 96       | 2.4%    |
| Intel Wi-Fi 6 AX200                                                    | 89       | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 87       | 2.17%   |
| Intel Ethernet Controller I225-V                                       | 78       | 1.95%   |
| Intel Ethernet Connection (2) I219-V                                   | 64       | 1.6%    |
| Intel Ethernet Connection I217-LM                                      | 62       | 1.55%   |
| Intel I210 Gigabit Network Connection                                  | 58       | 1.45%   |
| Intel 82579V Gigabit Network Connection                                | 39       | 0.97%   |
| Intel Wireless 3165                                                    | 38       | 0.95%   |
| Intel 82574L Gigabit Network Connection                                | 38       | 0.95%   |
| Intel Ethernet Connection (14) I219-V                                  | 36       | 0.9%    |
| Intel Ethernet Connection (7) I219-V                                   | 32       | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                  | 30       | 0.75%   |
| Nvidia MCP61 Ethernet                                                  | 29       | 0.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 29       | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 29       | 0.72%   |
| Intel Ethernet Connection I217-V                                       | 28       | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 26       | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 24       | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 24       | 0.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 23       | 0.57%   |
| Ralink MT7601U Wireless Adapter                                        | 22       | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 22       | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 21       | 0.52%   |
| Intel Ethernet Controller X550                                         | 20       | 0.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 20       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 19       | 0.47%   |
| Realtek 802.11ac NIC                                                   | 19       | 0.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 19       | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 18       | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 18       | 0.45%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 18       | 0.45%   |
| Intel I350 Gigabit Network Connection                                  | 18       | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 17       | 0.42%   |
| Intel Wireless 7265                                                    | 17       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                  | 17       | 0.42%   |
| Intel Ethernet Connection (2) I218-V                                   | 17       | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 324      | 37.63%  |
| Realtek Semiconductor           | 176      | 20.44%  |
| Qualcomm Atheros                | 94       | 10.92%  |
| Ralink Technology               | 56       | 6.5%    |
| TP-Link                         | 37       | 4.3%    |
| MediaTek                        | 31       | 3.6%    |
| Ralink                          | 24       | 2.79%   |
| Broadcom                        | 21       | 2.44%   |
| Qualcomm Atheros Communications | 15       | 1.74%   |
| D-Link                          | 10       | 1.16%   |
| NetGear                         | 9        | 1.05%   |
| Edimax Technology               | 9        | 1.05%   |
| ASUSTek Computer                | 9        | 1.05%   |
| Microsoft                       | 8        | 0.93%   |
| D-Link System                   | 7        | 0.81%   |
| Belkin Components               | 5        | 0.58%   |
| Gemtek                          | 4        | 0.46%   |
| Broadcom Limited                | 4        | 0.46%   |
| IMC Networks                    | 3        | 0.35%   |
| AVM                             | 3        | 0.35%   |
| Wilocity                        | 2        | 0.23%   |
| Linksys                         | 2        | 0.23%   |
| Xiaomi                          | 1        | 0.12%   |
| Tenda                           | 1        | 0.12%   |
| Sitecom Europe                  | 1        | 0.12%   |
| Micro Star International        | 1        | 0.12%   |
| Marvell Technology Group        | 1        | 0.12%   |
| Encore Electronics              | 1        | 0.12%   |
| CyberTAN Technology             | 1        | 0.12%   |
| BUFFALO                         | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 89       | 10.29%  |
| Intel Wireless 3165                                            | 38       | 4.39%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 29       | 3.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 29       | 3.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 26       | 3.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24       | 2.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 23       | 2.66%   |
| Ralink MT7601U Wireless Adapter                                | 22       | 2.54%   |
| Realtek 802.11ac NIC                                           | 19       | 2.2%    |
| Intel Alder Lake-S PCH CNVi WiFi                               | 19       | 2.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 18       | 2.08%   |
| Intel Wireless 7265                                            | 17       | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16       | 1.85%   |
| Intel Wireless 7260                                            | 16       | 1.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 15       | 1.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 15       | 1.73%   |
| Qualcomm Atheros AR9271 802.11n                                | 14       | 1.62%   |
| Ralink RT5370 Wireless Adapter                                 | 13       | 1.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.39%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 10       | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10       | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10       | 1.16%   |
| Intel Wireless 8260                                            | 10       | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10       | 1.16%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 10       | 1.16%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 9        | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8        | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8        | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8        | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 7        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 7        | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7        | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6        | 0.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 6        | 0.69%   |
| Ralink RT5372 Wireless Adapter                                 | 6        | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6        | 0.69%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 5        | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 5        | 0.58%   |
| TP-Link 802.11ac NIC                                           | 5        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1588     | 54.29%  |
| Intel                             | 911      | 31.15%  |
| Qualcomm Atheros                  | 107      | 3.66%   |
| Broadcom                          | 76       | 2.6%    |
| Nvidia                            | 47       | 1.61%   |
| Broadcom Limited                  | 24       | 0.82%   |
| Aquantia                          | 20       | 0.68%   |
| Marvell Technology Group          | 19       | 0.65%   |
| Mellanox Technologies             | 16       | 0.55%   |
| ASIX Electronics                  | 15       | 0.51%   |
| American Megatrends               | 13       | 0.44%   |
| VIA Technologies                  | 11       | 0.38%   |
| Samsung Electronics               | 11       | 0.38%   |
| D-Link System                     | 9        | 0.31%   |
| Xiaomi                            | 7        | 0.24%   |
| 3Com                              | 7        | 0.24%   |
| Huawei Technologies               | 6        | 0.21%   |
| TP-Link                           | 3        | 0.1%    |
| Silicon Integrated Systems [SiS]  | 3        | 0.1%    |
| QLogic                            | 3        | 0.1%    |
| OPPO Electronics                  | 3        | 0.1%    |
| ICS Advent                        | 3        | 0.1%    |
| Emulex                            | 3        | 0.1%    |
| DisplayLink                       | 3        | 0.1%    |
| Qualcomm                          | 2        | 0.07%   |
| Motorola PCS                      | 2        | 0.07%   |
| MediaTek                          | 2        | 0.07%   |
| ADMtek                            | 2        | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.03%   |
| Tehuti Networks                   | 1        | 0.03%   |
| Sundance Technology Inc / IC Plus | 1        | 0.03%   |
| Microsoft                         | 1        | 0.03%   |
| Microchip Technology              | 1        | 0.03%   |
| Lenovo                            | 1        | 0.03%   |
| Gemtek                            | 1        | 0.03%   |
| ATEN International                | 1        | 0.03%   |
| Accton Technology                 | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1324     | 43%     |
| Realtek RTL8125 2.5GbE Controller                                              | 133      | 4.32%   |
| Intel I211 Gigabit Network Connection                                          | 98       | 3.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 96       | 3.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 87       | 2.83%   |
| Intel Ethernet Controller I225-V                                               | 78       | 2.53%   |
| Intel Ethernet Connection (2) I219-V                                           | 64       | 2.08%   |
| Intel Ethernet Connection I217-LM                                              | 62       | 2.01%   |
| Intel I210 Gigabit Network Connection                                          | 58       | 1.88%   |
| Intel 82579V Gigabit Network Connection                                        | 39       | 1.27%   |
| Intel 82574L Gigabit Network Connection                                        | 38       | 1.23%   |
| Intel Ethernet Connection (14) I219-V                                          | 36       | 1.17%   |
| Intel Ethernet Connection (7) I219-V                                           | 32       | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                          | 30       | 0.97%   |
| Nvidia MCP61 Ethernet                                                          | 29       | 0.94%   |
| Intel Ethernet Connection I217-V                                               | 28       | 0.91%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 24       | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 22       | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 21       | 0.68%   |
| Intel Ethernet Controller X550                                                 | 20       | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 20       | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 19       | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 18       | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 18       | 0.58%   |
| Intel I350 Gigabit Network Connection                                          | 18       | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 17       | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                          | 17       | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                           | 17       | 0.55%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 16       | 0.52%   |
| Intel Ethernet Controller I226-V                                               | 16       | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 16       | 0.52%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 14       | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 13       | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 13       | 0.42%   |
| American Megatrends Virtual Ethernet.                                          | 13       | 0.42%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12       | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 11       | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 11       | 0.36%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 11       | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 10       | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2653     | 75.5%   |
| WiFi     | 803      | 22.85%  |
| Modem    | 54       | 1.54%   |
| Unknown  | 4        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2336     | 87.95%  |
| WiFi     | 318      | 11.97%  |
| Modem    | 2        | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1741     | 64.94%  |
| 2     | 678      | 25.29%  |
| 3     | 154      | 5.74%   |
| 4     | 39       | 1.45%   |
| 5     | 21       | 0.78%   |
| 6     | 16       | 0.6%    |
| 0     | 12       | 0.45%   |
| 7     | 7        | 0.26%   |
| 8     | 6        | 0.22%   |
| 9     | 3        | 0.11%   |
| 12    | 2        | 0.07%   |
| 17    | 1        | 0.04%   |
| 13    | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2188     | 81.31%  |
| Yes  | 503      | 18.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 296      | 45.4%   |
| Cambridge Silicon Radio         | 146      | 22.39%  |
| Realtek Semiconductor           | 52       | 7.98%   |
| ASUSTek Computer                | 35       | 5.37%   |
| Broadcom                        | 29       | 4.45%   |
| MediaTek                        | 24       | 3.68%   |
| Qualcomm Atheros Communications | 23       | 3.53%   |
| IMC Networks                    | 15       | 2.3%    |
| TP-Link                         | 5        | 0.77%   |
| Foxconn / Hon Hai               | 5        | 0.77%   |
| Apple                           | 4        | 0.61%   |
| Lite-On Technology              | 3        | 0.46%   |
| Realtek                         | 2        | 0.31%   |
| Belkin Components               | 2        | 0.31%   |
| Toshiba                         | 1        | 0.15%   |
| Sitecom Europe                  | 1        | 0.15%   |
| SINO WEALTH                     | 1        | 0.15%   |
| Microsoft                       | 1        | 0.15%   |
| Micro Star International        | 1        | 0.15%   |
| Integrated System Solution      | 1        | 0.15%   |
| Hewlett-Packard                 | 1        | 0.15%   |
| Edimax Technology               | 1        | 0.15%   |
| Dynex                           | 1        | 0.15%   |
| Actions                         | 1        | 0.15%   |
| Unknown                         | 1        | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 146      | 22.36%  |
| Intel AX200 Bluetooth                                     | 84       | 12.86%  |
| Intel Bluetooth wireless interface                        | 83       | 12.71%  |
| Realtek Bluetooth Radio                                   | 42       | 6.43%   |
| Intel Wireless-AC 3168 Bluetooth                          | 28       | 4.29%   |
| Intel AX201 Bluetooth                                     | 26       | 3.98%   |
| MediaTek Wireless_Device                                  | 24       | 3.68%   |
| Intel AX210 Bluetooth                                     | 24       | 3.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 18       | 2.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 16       | 2.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 15       | 2.3%    |
| Intel AX211 Bluetooth                                     | 13       | 1.99%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 12       | 1.84%   |
| ASUS ASUS USB-BT500                                       | 9        | 1.38%   |
| IMC Networks Bluetooth Radio                              | 8        | 1.23%   |
| Realtek  Bluetooth 4.2 Adapter                            | 7        | 1.07%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 7        | 1.07%   |
| Qualcomm Atheros  Bluetooth Device                        | 6        | 0.92%   |
| TP-Link TP-Link Bluetooth USB Adapter                     | 5        | 0.77%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 5        | 0.77%   |
| ASUS Bluetooth Radio                                      | 5        | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 4        | 0.61%   |
| IMC Networks Bluetooth Device                             | 4        | 0.61%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 3        | 0.46%   |
| Realtek Bluetooth Radio                                   | 2        | 0.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 2        | 0.31%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)           | 2        | 0.31%   |
| Lite-On Bluetooth Device                                  | 2        | 0.31%   |
| IMC Networks Wireless_Device                              | 2        | 0.31%   |
| Foxconn / Hon Hai Wireless_Device                         | 2        | 0.31%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter          | 2        | 0.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 2        | 0.31%   |
| Broadcom BCM2045 Bluetooth                                | 2        | 0.31%   |
| ASUS Bluetooth Device                                     | 2        | 0.31%   |
| ASUS Bluetooth Adapter                                    | 2        | 0.31%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 2        | 0.31%   |
| Apple Bluetooth Host Controller                           | 2        | 0.31%   |
| Toshiba Atheros AR3012 Bluetooth                          | 1        | 0.15%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.15%   |
| SINO WEALTH RK Bluetooth Keyboard                         | 1        | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1746     | 44.94%  |
| AMD                                          | 852      | 21.93%  |
| Nvidia                                       | 821      | 21.13%  |
| C-Media Electronics                          | 79       | 2.03%   |
| Logitech                                     | 38       | 0.98%   |
| Creative Labs                                | 35       | 0.9%    |
| KTMicro                                      | 25       | 0.64%   |
| ASUSTek Computer                             | 25       | 0.64%   |
| VIA Technologies                             | 15       | 0.39%   |
| Texas Instruments                            | 15       | 0.39%   |
| Generalplus Technology                       | 15       | 0.39%   |
| Focusrite-Novation                           | 13       | 0.33%   |
| Creative Technology                          | 13       | 0.33%   |
| Micro Star International                     | 11       | 0.28%   |
| Kingston Technology                          | 9        | 0.23%   |
| JMTek                                        | 9        | 0.23%   |
| GN Netcom                                    | 9        | 0.23%   |
| SteelSeries ApS                              | 8        | 0.21%   |
| Plantronics                                  | 7        | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 6        | 0.15%   |
| RODE Microphones                             | 6        | 0.15%   |
| GYROCOM C&C                                  | 6        | 0.15%   |
| Yamaha                                       | 5        | 0.13%   |
| Samson Technologies                          | 5        | 0.13%   |
| Razer USA                                    | 5        | 0.13%   |
| Giga-Byte Technology                         | 5        | 0.13%   |
| Dell                                         | 5        | 0.13%   |
| BEHRINGER International                      | 5        | 0.13%   |
| Silicon Integrated Systems [SiS]             | 4        | 0.1%    |
| Cambridge Silicon Radio                      | 4        | 0.1%    |
| TerraTec Electronic                          | 3        | 0.08%   |
| Tenx Technology                              | 3        | 0.08%   |
| Realtek Semiconductor                        | 3        | 0.08%   |
| M-Audio                                      | 3        | 0.08%   |
| Ensoniq                                      | 3        | 0.08%   |
| DSEA A/S                                     | 3        | 0.08%   |
| Corsair                                      | 3        | 0.08%   |
| Blue Microphones                             | 3        | 0.08%   |
| XMOS                                         | 2        | 0.05%   |
| Valve Software                               | 2        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 253      | 5.61%   |
| AMD Starship/Matisse HD Audio Controller                                   | 211      | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 202      | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 189      | 4.19%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 155      | 3.44%   |
| Intel 200 Series PCH HD Audio                                              | 154      | 3.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 144      | 3.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 142      | 3.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 137      | 3.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 112      | 2.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 87       | 1.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 86       | 1.91%   |
| Nvidia GF108 High Definition Audio Controller                              | 82       | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 78       | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 70       | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 70       | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 68       | 1.51%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 66       | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 62       | 1.38%   |
| AMD FCH Azalia Controller                                                  | 61       | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 53       | 1.18%   |
| Intel Alder Lake-S HD Audio Controller                                     | 51       | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 47       | 1.04%   |
| Intel Jasper Lake HD Audio                                                 | 44       | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 43       | 0.95%   |
| Nvidia High Definition Audio Controller                                    | 41       | 0.91%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 40       | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 37       | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 36       | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 36       | 0.8%    |
| Nvidia GP108 High Definition Audio Controller                              | 36       | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 36       | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 36       | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 35       | 0.78%   |
| Intel Comet Lake PCH-V cAVS                                                | 34       | 0.75%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 33       | 0.73%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 32       | 0.71%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 31       | 0.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 31       | 0.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 30       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 459      | 17.41%  |
| Unknown                      | 393      | 14.91%  |
| Crucial                      | 315      | 11.95%  |
| Samsung Electronics          | 286      | 10.85%  |
| SK hynix                     | 241      | 9.14%   |
| Corsair                      | 218      | 8.27%   |
| G.Skill                      | 148      | 5.61%   |
| Micron Technology            | 112      | 4.25%   |
| Patriot                      | 69       | 2.62%   |
| A-DATA Technology            | 45       | 1.71%   |
| Unknown                      | 38       | 1.44%   |
| Team                         | 24       | 0.91%   |
| Ramaxel Technology           | 21       | 0.8%    |
| Hikvision                    | 21       | 0.8%    |
| Unknown (ABCD)               | 20       | 0.76%   |
| AMD                          | 18       | 0.68%   |
| Nanya Technology             | 17       | 0.64%   |
| Elpida                       | 15       | 0.57%   |
| Timetec                      | 10       | 0.38%   |
| GOODRAM                      | 10       | 0.38%   |
| Transcend                    | 9        | 0.34%   |
| Smart                        | 9        | 0.34%   |
| GeIL                         | 7        | 0.27%   |
| Apacer                       | 7        | 0.27%   |
| Unknown (0x5846)             | 6        | 0.23%   |
| Hewlett-Packard              | 6        | 0.23%   |
| Avant                        | 6        | 0.23%   |
| Qimonda                      | 5        | 0.19%   |
| Unknown (AB)                 | 4        | 0.15%   |
| Unknown (0x0DD5)             | 4        | 0.15%   |
| Unknown (0x0B45)             | 3        | 0.11%   |
| Unifosa                      | 3        | 0.11%   |
| Toshiba                      | 3        | 0.11%   |
| PNY                          | 3        | 0.11%   |
| Patriot Memory (PDP Systems) | 3        | 0.11%   |
| Kingmax                      | 3        | 0.11%   |
| Kimtigo                      | 3        | 0.11%   |
| Wilk                         | 2        | 0.08%   |
| V-Color                      | 2        | 0.08%   |
| Silicon Power                | 2        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                            | 45       | 1.55%   |
| Unknown                                                      | 38       | 1.31%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s        | 36       | 1.24%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2667MT/s        | 31       | 1.07%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s       | 29       | 1%      |
| Unknown RAM Module 1GB DIMM SDRAM                            | 26       | 0.9%    |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s         | 24       | 0.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 23       | 0.79%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 23       | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 20       | 0.69%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 20       | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s | 20       | 0.69%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s      | 20       | 0.69%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s        | 18       | 0.62%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 17       | 0.59%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 16       | 0.55%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s              | 16       | 0.55%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s               | 14       | 0.48%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 14       | 0.48%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 13       | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 12       | 0.41%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s         | 12       | 0.41%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s       | 12       | 0.41%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s        | 12       | 0.41%   |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s         | 12       | 0.41%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s       | 11       | 0.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s        | 11       | 0.38%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                         | 10       | 0.34%   |
| Unknown RAM Module 1GB DIMM                                  | 10       | 0.34%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 10       | 0.34%   |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s      | 10       | 0.34%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s       | 10       | 0.34%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 9        | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 9        | 0.31%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 9        | 0.31%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 9        | 0.31%   |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1600MT/s        | 9        | 0.31%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s       | 9        | 0.31%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 8        | 0.28%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                     | 8        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1063     | 45.35%  |
| DDR3         | 791      | 33.75%  |
| Unknown      | 158      | 6.74%   |
| SDRAM        | 131      | 5.59%   |
| DDR2         | 106      | 4.52%   |
| LPDDR4       | 32       | 1.37%   |
| DDR5         | 29       | 1.24%   |
| DDR          | 25       | 1.07%   |
| DRAM         | 8        | 0.34%   |
| DDR2 FB-DIMM | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2059     | 89.1%   |
| SODIMM       | 225      | 9.74%   |
| Row Of Chips | 12       | 0.52%   |
| RIMM         | 8        | 0.35%   |
| FB-DIMM      | 4        | 0.17%   |
| Unknown      | 2        | 0.09%   |
| Chip         | 1        | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 796      | 31.23%  |
| 4096    | 580      | 22.75%  |
| 16384   | 409      | 16.05%  |
| 2048    | 398      | 15.61%  |
| 32768   | 190      | 7.45%   |
| 1024    | 128      | 5.02%   |
| 512     | 30       | 1.18%   |
| 256     | 7        | 0.27%   |
| 65536   | 4        | 0.16%   |
| 12288   | 2        | 0.08%   |
| 3072    | 1        | 0.04%   |
| 1536    | 1        | 0.04%   |
| 128     | 1        | 0.04%   |
| 16      | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 447      | 17.46%  |
| 1333    | 280      | 10.94%  |
| 2667    | 236      | 9.22%   |
| 3200    | 226      | 8.83%   |
| 2400    | 162      | 6.33%   |
| 3600    | 133      | 5.2%    |
| 2133    | 124      | 4.84%   |
| 800     | 103      | 4.02%   |
| Unknown | 102      | 3.98%   |
| 1866    | 75       | 2.93%   |
| 667     | 53       | 2.07%   |
| 1867    | 40       | 1.56%   |
| 2666    | 39       | 1.52%   |
| 3000    | 37       | 1.45%   |
| 1800    | 32       | 1.25%   |
| 3733    | 30       | 1.17%   |
| 3400    | 30       | 1.17%   |
| 1067    | 30       | 1.17%   |
| 1066    | 30       | 1.17%   |
| 2933    | 28       | 1.09%   |
| 2866    | 26       | 1.02%   |
| 3800    | 25       | 0.98%   |
| 3466    | 23       | 0.9%    |
| 4800    | 18       | 0.7%    |
| 1334    | 15       | 0.59%   |
| 4000    | 14       | 0.55%   |
| 400     | 13       | 0.51%   |
| 3933    | 12       | 0.47%   |
| 3534    | 10       | 0.39%   |
| 3100    | 9        | 0.35%   |
| 2048    | 9        | 0.35%   |
| 533     | 9        | 0.35%   |
| 3666    | 8        | 0.31%   |
| 3266    | 8        | 0.31%   |
| 1648    | 8        | 0.31%   |
| 4333    | 7        | 0.27%   |
| 1639    | 7        | 0.27%   |
| 3866    | 6        | 0.23%   |
| 3500    | 6        | 0.23%   |
| 2733    | 6        | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 38       | 36.19%  |
| Brother Industries     | 20       | 19.05%  |
| Canon                  | 11       | 10.48%  |
| Samsung Electronics    | 8        | 7.62%   |
| Seiko Epson            | 4        | 3.81%   |
| Xerox                  | 3        | 2.86%   |
| Lexmark International  | 3        | 2.86%   |
| Dymo-CoStar            | 3        | 2.86%   |
| Zebra                  | 2        | 1.9%    |
| Prolific Technology    | 2        | 1.9%    |
| Pantum                 | 2        | 1.9%    |
| STMicroelectronics     | 1        | 0.95%   |
| Ricoh                  | 1        | 0.95%   |
| QinHeng Electronics    | 1        | 0.95%   |
| Printer                | 1        | 0.95%   |
| Kyocera                | 1        | 0.95%   |
| Konica Minolta         | 1        | 0.95%   |
| GODEX INTERNATIONAL    | 1        | 0.95%   |
| Custom Engineering SPA | 1        | 0.95%   |
| Apple                  | 1        | 0.95%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1200                                          | 5        | 4.76%   |
| Xerox B205                                                | 3        | 2.86%   |
| Samsung ML-1660 Series                                    | 3        | 2.86%   |
| HP LaserJet M101-M106                                     | 3        | 2.86%   |
| HP LaserJet 1020                                          | 3        | 2.86%   |
| Prolific PL2305 Parallel Port                             | 2        | 1.9%    |
| HP LaserJet P1005                                         | 2        | 1.9%    |
| HP ENVY 4520 series                                       | 2        | 1.9%    |
| HP DeskJet 2700 series                                    | 2        | 1.9%    |
| Canon MF4410                                              | 2        | 1.9%    |
| Brother MFC-7460DN                                        | 2        | 1.9%    |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 0.95%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 0.95%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.95%   |
| Seiko Epson XP-205 207 Series                             | 1        | 0.95%   |
| Seiko Epson M105 Series                                   | 1        | 0.95%   |
| Seiko Epson L3150 Series                                  | 1        | 0.95%   |
| Seiko Epson ET-2700 Series                                | 1        | 0.95%   |
| Samsung SCX-4x26 Series                                   | 1        | 0.95%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 0.95%   |
| Samsung SCX-3200 Series                                   | 1        | 0.95%   |
| Samsung ML-216x Series Laser Printer                      | 1        | 0.95%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.95%   |
| Ricoh SP 213w                                             | 1        | 0.95%   |
| QinHeng CH340S                                            | 1        | 0.95%   |
| Printer Printer                                           | 1        | 0.95%   |
| Pantum P2500W series                                      | 1        | 0.95%   |
| Pantum M6500-series                                       | 1        | 0.95%   |
| Lexmark International MS710                               | 1        | 0.95%   |
| Lexmark International Laser Printer                       | 1        | 0.95%   |
| Lexmark International B2338dw                             | 1        | 0.95%   |
| Kyocera ECOSYS M5521cdn                                   | 1        | 0.95%   |
| Konica Minolta bizhub 4402P                               | 1        | 0.95%   |
| HP Officejet J4500 series                                 | 1        | 0.95%   |
| HP Officejet 7110 series                                  | 1        | 0.95%   |
| HP LaserJet Pro M148-M149                                 | 1        | 0.95%   |
| HP LaserJet P2055 series                                  | 1        | 0.95%   |
| HP Laserjet P1505                                         | 1        | 0.95%   |
| HP LaserJet P1006                                         | 1        | 0.95%   |
| HP LaserJet 400 M401n                                     | 1        | 0.95%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 14       | 58.33%  |
| Seiko Epson     | 4        | 16.67%  |
| Hewlett-Packard | 3        | 12.5%   |
| AGFA-Gevaert NV | 2        | 8.33%   |
| Mustek Systems  | 1        | 4.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 3        | 12.5%   |
| Canon CanoScan LiDE 220                                       | 3        | 12.5%   |
| Canon CanoScan LiDE 210                                       | 2        | 8.33%   |
| Canon CanoScan LiDE 110                                       | 2        | 8.33%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2        | 8.33%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1        | 4.17%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 4.17%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1        | 4.17%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 4.17%   |
| Mustek Systems SNAPSCAN e22                                   | 1        | 4.17%   |
| HP ScanJet Pro 2500 f1                                        | 1        | 4.17%   |
| HP ScanJet 3970c                                              | 1        | 4.17%   |
| HP Scanjet 300                                                | 1        | 4.17%   |
| Canon CanoScan LiDE 60                                        | 1        | 4.17%   |
| Canon CanoScan 8800F                                          | 1        | 4.17%   |
| Canon CanoScan 5600F                                          | 1        | 4.17%   |
| Canon CanoScan 4400F                                          | 1        | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 143      | 40.63%  |
| Microdia                               | 24       | 6.82%   |
| Generalplus Technology                 | 17       | 4.83%   |
| Sunplus Innovation Technology          | 16       | 4.55%   |
| Microsoft                              | 15       | 4.26%   |
| Creative Technology                    | 12       | 3.41%   |
| Jieli Technology                       | 10       | 2.84%   |
| Apple                                  | 10       | 2.84%   |
| Samsung Electronics                    | 9        | 2.56%   |
| KYE Systems (Mouse Systems)            | 7        | 1.99%   |
| ARC International                      | 6        | 1.7%    |
| Z-Star Microelectronics                | 5        | 1.42%   |
| GEMBIRD                                | 5        | 1.42%   |
| Chicony Electronics                    | 5        | 1.42%   |
| Novatek Microelectronics               | 3        | 0.85%   |
| Google                                 | 3        | 0.85%   |
| Genesys Logic                          | 3        | 0.85%   |
| AVerMedia Technologies                 | 3        | 0.85%   |
| Xiongmai                               | 2        | 0.57%   |
| Valve Software                         | 2        | 0.57%   |
| SunplusIT                              | 2        | 0.57%   |
| Realtek Semiconductor                  | 2        | 0.57%   |
| Razer USA                              | 2        | 0.57%   |
| Nintendo                               | 2        | 0.57%   |
| MacroSilicon                           | 2        | 0.57%   |
| Cubeternet                             | 2        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) | 2        | 0.57%   |
| Aveo Technology                        | 2        | 0.57%   |
| Arkmicro Technologies                  | 2        | 0.57%   |
| 2M UVC CAMERA                          | 2        | 0.57%   |
| Xiaomi                                 | 1        | 0.28%   |
| WaveRider Communications               | 1        | 0.28%   |
| ValueHD                                | 1        | 0.28%   |
| USB3.0 HD Audio Capture                | 1        | 0.28%   |
| Unknown                                | 1        | 0.28%   |
| UltraSemi                              | 1        | 0.28%   |
| Trust                                  | 1        | 0.28%   |
| Tobii Technology AB                    | 1        | 0.28%   |
| Syntek                                 | 1        | 0.28%   |
| Sunplus IT                             | 1        | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 48       | 13.52%  |
| Logitech HD Pro Webcam C920                | 19       | 5.35%   |
| Logitech C922 Pro Stream Webcam            | 15       | 4.23%   |
| Generalplus GENERAL WEBCAM                 | 14       | 3.94%   |
| Jieli USB PHY 2.0                          | 10       | 2.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR         | 10       | 2.82%   |
| Samsung Galaxy series, misc. (MTP mode)    | 9        | 2.54%   |
| Microsoft LifeCam HD-3000                  | 8        | 2.25%   |
| Microdia Webcam Vitade AF                  | 8        | 2.25%   |
| Microdia USB 2.0 Camera                    | 8        | 2.25%   |
| Logitech Webcam C310                       | 7        | 1.97%   |
| Logitech Webcam C170                       | 7        | 1.97%   |
| Logitech HD Webcam C615                    | 7        | 1.97%   |
| Sunplus DICOTA 4K                          | 5        | 1.41%   |
| Logitech HD Webcam C525                    | 5        | 1.41%   |
| Z-Star Venus USB2.0 Camera                 | 4        | 1.13%   |
| ARC International Camera                   | 4        | 1.13%   |
| Sunplus Full HD webcam                     | 3        | 0.85%   |
| Novatek HP High Definition 2MP Webcam      | 3        | 0.85%   |
| Logitech Logitech Webcam C925e             | 3        | 0.85%   |
| Logitech Logi Webcam C920e                 | 3        | 0.85%   |
| Logitech HD Webcam C910                    | 3        | 0.85%   |
| Logitech BRIO Ultra HD Webcam              | 3        | 0.85%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 3        | 0.85%   |
| KYE Systems (Mouse Systems) Genius Webcam  | 3        | 0.85%   |
| Generalplus 808 Camera #9 (web-cam mode)   | 3        | 0.85%   |
| Creative Live! Cam Chat HD [VF0700/VF0790] | 3        | 0.85%   |
| Xiongmai web camera                        | 2        | 0.56%   |
| Valve Software 3D Camera                   | 2        | 0.56%   |
| Sunplus HD 720P webcam                     | 2        | 0.56%   |
| Razer USA Gaming Webcam [Kiyo]             | 2        | 0.56%   |
| Nintendo USB Camera                        | 2        | 0.56%   |
| Microsoft LifeCam HD-5000                  | 2        | 0.56%   |
| Microsoft LifeCam Cinema                   | 2        | 0.56%   |
| Microdia Sonix USB 2.0 Camera              | 2        | 0.56%   |
| Microdia Camera                            | 2        | 0.56%   |
| Logitech StreamCam                         | 2        | 0.56%   |
| Logitech QuickCam Pro 9000                 | 2        | 0.56%   |
| Logitech QuickCam Pro 4000                 | 2        | 0.56%   |
| Logitech QuickCam Communicate MP/S5500     | 2        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 50%     |
| Synaptics        | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 50%     |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| SCM Microsystems         | 3        | 17.65%  |
| Alcor Micro              | 3        | 17.65%  |
| Gemalto (was Gemplus)    | 2        | 11.76%  |
| Yubico.com               | 1        | 5.88%   |
| Reiner SCT Kartensysteme | 1        | 5.88%   |
| Realtek Semiconductor    | 1        | 5.88%   |
| Lenovo                   | 1        | 5.88%   |
| Feitian Technologies     | 1        | 5.88%   |
| Clay Logic               | 1        | 5.88%   |
| Chicony Electronics      | 1        | 5.88%   |
| Cherry                   | 1        | 5.88%   |
| Advanced Card Systems    | 1        | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 2        | 11.76%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 2        | 11.76%  |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 5.88%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 5.88%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 5.88%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 5.88%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 5.88%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 1        | 5.88%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 5.88%   |
| Feitian Technologies SCR301                                                | 1        | 5.88%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 5.88%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 5.88%   |
| Cherry SmartTerminal XX1X                                                  | 1        | 5.88%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 5.88%   |
| Advanced Card Systems ACR39U                                               | 1        | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1549     | 57.39%  |
| 1     | 999      | 37.01%  |
| 2     | 131      | 4.85%   |
| 3     | 15       | 0.56%   |
| 4     | 3        | 0.11%   |
| 7     | 1        | 0.04%   |
| 5     | 1        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 958      | 76.27%  |
| Net/wireless             | 107      | 8.52%   |
| Communication controller | 49       | 3.9%    |
| Unassigned class         | 41       | 3.26%   |
| Sound                    | 21       | 1.67%   |
| Multimedia controller    | 15       | 1.19%   |
| Bluetooth                | 15       | 1.19%   |
| Camera                   | 10       | 0.8%    |
| Chipcard                 | 8        | 0.64%   |
| Card reader              | 7        | 0.56%   |
| Net/ethernet             | 6        | 0.48%   |
| Storage/raid             | 5        | 0.4%    |
| Tv card                  | 3        | 0.24%   |
| Modem                    | 3        | 0.24%   |
| Network                  | 2        | 0.16%   |
| Fingerprint reader       | 2        | 0.16%   |
| Dvb card                 | 2        | 0.16%   |
| Storage/nvme             | 1        | 0.08%   |
| Storage                  | 1        | 0.08%   |

