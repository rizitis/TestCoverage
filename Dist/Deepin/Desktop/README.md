Deepin - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Deepin.

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

Total: 127

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [91cdbe5df9](https://linux-hardware.org/?probe=91cdbe5df9) | Dec 25, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [32e2211a4c](https://linux-hardware.org/?probe=32e2211a4c) | Dec 25, 2024 |
| Intel         | B75A                        | [974983efed](https://linux-hardware.org/?probe=974983efed) | Dec 05, 2024 |
| Intel         | B75A                        | [bb9185a4b6](https://linux-hardware.org/?probe=bb9185a4b6) | Dec 04, 2024 |
| Dell          | 0XFWHV A00                  | [c60047b59a](https://linux-hardware.org/?probe=c60047b59a) | Dec 02, 2024 |
| Lenovo        | 3102 SDK0L77767 WIN 3423... | [3a3945760d](https://linux-hardware.org/?probe=3a3945760d) | Nov 09, 2024 |
| Lenovo        | MAHOBAY NOK                 | [87eb4b588b](https://linux-hardware.org/?probe=87eb4b588b) | Oct 10, 2024 |
| Gigabyte      | F2A55M-S1                   | [1d3cf1476f](https://linux-hardware.org/?probe=1d3cf1476f) | Sep 30, 2024 |
| ASRock        | B550M Pro4                  | [9ef268f88f](https://linux-hardware.org/?probe=9ef268f88f) | Sep 20, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [74442529cd](https://linux-hardware.org/?probe=74442529cd) | Sep 20, 2024 |
| Colorful T... | B460M-K PRO V21             | [6d090db07d](https://linux-hardware.org/?probe=6d090db07d) | Sep 19, 2024 |
| ASUSTek       | PRIME B760M-A WIFI          | [ef787d7934](https://linux-hardware.org/?probe=ef787d7934) | Sep 13, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8fe595fe5f](https://linux-hardware.org/?probe=8fe595fe5f) | Sep 05, 2024 |
| Gigabyte      | F2A55M-S1                   | [0ff77db375](https://linux-hardware.org/?probe=0ff77db375) | Sep 03, 2024 |
| Dell          | 0XR1GT A00                  | [a2aa1e0463](https://linux-hardware.org/?probe=a2aa1e0463) | Jul 08, 2024 |
| MACHINIST     | E5-RS9 V1.1                 | [c637868885](https://linux-hardware.org/?probe=c637868885) | Jun 20, 2024 |
| Intel         | DX58SO AAE29331-504         | [f4b6b040b5](https://linux-hardware.org/?probe=f4b6b040b5) | May 13, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ac24b8ae8b](https://linux-hardware.org/?probe=ac24b8ae8b) | Mar 06, 2024 |
| ASUSTek       | B85M-K                      | [dc3ec9e412](https://linux-hardware.org/?probe=dc3ec9e412) | Feb 03, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8b1e8e6fe4](https://linux-hardware.org/?probe=8b1e8e6fe4) | Jan 08, 2024 |
| Dell          | 0XPDFK A01                  | [6990382d8a](https://linux-hardware.org/?probe=6990382d8a) | Dec 14, 2023 |
| Dell          | 0XPDFK A01                  | [da80cd5bbd](https://linux-hardware.org/?probe=da80cd5bbd) | Dec 14, 2023 |
| Dell          | 0XR1GT A00                  | [17b5d35090](https://linux-hardware.org/?probe=17b5d35090) | Nov 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [12d30e16b4](https://linux-hardware.org/?probe=12d30e16b4) | Nov 07, 2023 |
| Dell          | 0XR1GT A00                  | [f01a35c9a7](https://linux-hardware.org/?probe=f01a35c9a7) | Nov 06, 2023 |
| Intel         | DX58SO AAE29331-504         | [33d7713b52](https://linux-hardware.org/?probe=33d7713b52) | Oct 21, 2023 |
| Intel         | DX58SO AAE29331-504         | [afe13c52df](https://linux-hardware.org/?probe=afe13c52df) | Oct 11, 2023 |
| Dell          | 0NW6H5 A00                  | [e337e05dff](https://linux-hardware.org/?probe=e337e05dff) | Oct 08, 2023 |
| Dell          | 0NW6H5 A00                  | [dc4ec4e72a](https://linux-hardware.org/?probe=dc4ec4e72a) | Oct 02, 2023 |
| TSINGHUA T... | B460M-HDV                   | [f82a030bce](https://linux-hardware.org/?probe=f82a030bce) | Aug 30, 2023 |
| TSINGHUA T... | B460M-HDV                   | [815cb59889](https://linux-hardware.org/?probe=815cb59889) | Aug 16, 2023 |
| TSINGHUA T... | B460-N2                     | [f7f87f7a07](https://linux-hardware.org/?probe=f7f87f7a07) | Aug 16, 2023 |
| HP            | 18EA                        | [d6e48a99e7](https://linux-hardware.org/?probe=d6e48a99e7) | Jun 08, 2023 |
| MSI           | A55M-E35                    | [fa4eba3787](https://linux-hardware.org/?probe=fa4eba3787) | Jun 08, 2023 |
| Intel         | DH77EB AAG39073-304         | [8310aaaa78](https://linux-hardware.org/?probe=8310aaaa78) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | [86545c89c0](https://linux-hardware.org/?probe=86545c89c0) | May 27, 2023 |
| Koloe         | X58                         | [7c1acc3b84](https://linux-hardware.org/?probe=7c1acc3b84) | May 08, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [a22f7f4309](https://linux-hardware.org/?probe=a22f7f4309) | Mar 13, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [d4f6b075c4](https://linux-hardware.org/?probe=d4f6b075c4) | Mar 13, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [44a3952ccf](https://linux-hardware.org/?probe=44a3952ccf) | Feb 15, 2023 |
| OEM           | KX-01 V1.0                  | [75d9dc396c](https://linux-hardware.org/?probe=75d9dc396c) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [510b879339](https://linux-hardware.org/?probe=510b879339) | Jan 26, 2023 |
| Unknown       | Unknown                     | [98e2d17193](https://linux-hardware.org/?probe=98e2d17193) | Jul 21, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | [843d2132ad](https://linux-hardware.org/?probe=843d2132ad) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [3e37ded7e2](https://linux-hardware.org/?probe=3e37ded7e2) | Jan 04, 2022 |
| TSINGHUA T... | B460M-HDV                   | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| TSINGHUA T... | B460M-HDV                   | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| Dell          | 07N90W A02                  | [43a5aec999](https://linux-hardware.org/?probe=43a5aec999) | Dec 07, 2021 |
| ECS           | H81H3-M4                    | [cdaf4b1031](https://linux-hardware.org/?probe=cdaf4b1031) | Dec 07, 2021 |
| TSINGHUA T... | B460M-HDV                   | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [a428f57f6a](https://linux-hardware.org/?probe=a428f57f6a) | Sep 17, 2021 |
| TSINGHUA T... | B460-N2                     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| Gigabyte      | B550M DS3H                  | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| Toshiba       | STI 005492G                 | [d7fe511a9e](https://linux-hardware.org/?probe=d7fe511a9e) | Jul 19, 2021 |
| AMD           | BL2 V2.3                    | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| ECS           | H81H3-M4                    | [838f10c576](https://linux-hardware.org/?probe=838f10c576) | Jun 25, 2021 |
| ECS           | H81H3-M4                    | [bfc9a4d537](https://linux-hardware.org/?probe=bfc9a4d537) | Jun 25, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Toshiba       | STI 005492G                 | [e28291b9ed](https://linux-hardware.org/?probe=e28291b9ed) | Jun 13, 2021 |
| MSI           | H81I                        | [a0f0f9e7e8](https://linux-hardware.org/?probe=a0f0f9e7e8) | May 06, 2021 |
| Huanan        | X99-8M-F V1.1               | [13daa2d4a6](https://linux-hardware.org/?probe=13daa2d4a6) | Apr 23, 2021 |
| ASUSTek       | P8H61-MX                    | [9212747e6a](https://linux-hardware.org/?probe=9212747e6a) | Apr 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [e6db1c79cc](https://linux-hardware.org/?probe=e6db1c79cc) | Mar 25, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [edb786e43a](https://linux-hardware.org/?probe=edb786e43a) | Mar 25, 2021 |
| ASUSTek       | PRIME A320M-K               | [1db414e1cd](https://linux-hardware.org/?probe=1db414e1cd) | Mar 21, 2021 |
| Gigabyte      | H81M-D2V                    | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [b165cd04ce](https://linux-hardware.org/?probe=b165cd04ce) | Feb 25, 2021 |
| Dell          | 0KWVT8 A00                  | [56f1d17280](https://linux-hardware.org/?probe=56f1d17280) | Feb 04, 2021 |
| Dell          | 00V62H A00                  | [863c1d64fe](https://linux-hardware.org/?probe=863c1d64fe) | Jan 23, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [842703dc6b](https://linux-hardware.org/?probe=842703dc6b) | Jan 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [5b9e365258](https://linux-hardware.org/?probe=5b9e365258) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Gigabyte      | H81M-D2V                    | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| Foxconn       | 2ADA                        | [2c76ab07eb](https://linux-hardware.org/?probe=2c76ab07eb) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0b46341e31](https://linux-hardware.org/?probe=0b46341e31) | Nov 07, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [a4fa363ca9](https://linux-hardware.org/?probe=a4fa363ca9) | Oct 29, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [181ccd5686](https://linux-hardware.org/?probe=181ccd5686) | Oct 10, 2020 |
| Toshiba       | STI 013442                  | [25aa1737df](https://linux-hardware.org/?probe=25aa1737df) | Oct 02, 2020 |
| Toshiba       | STI 013442                  | [325dccb021](https://linux-hardware.org/?probe=325dccb021) | Oct 01, 2020 |
| Toshiba       | STI 013442                  | [d878c17ac5](https://linux-hardware.org/?probe=d878c17ac5) | Oct 01, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [d5c18b2ad2](https://linux-hardware.org/?probe=d5c18b2ad2) | Sep 27, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | [27f0cbcbfa](https://linux-hardware.org/?probe=27f0cbcbfa) | Sep 27, 2020 |
| ASUSTek       | P8H77-M PRO                 | [7318b0893d](https://linux-hardware.org/?probe=7318b0893d) | Sep 22, 2020 |
| Gigabyte      | H81M-D2V                    | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| Gigabyte      | Z77-DS3H                    | [d7f43611eb](https://linux-hardware.org/?probe=d7f43611eb) | Sep 13, 2020 |
| HP            | 81B4                        | [9e3aa00a36](https://linux-hardware.org/?probe=9e3aa00a36) | Aug 21, 2020 |
| HP            | 81B4                        | [03c849fcd2](https://linux-hardware.org/?probe=03c849fcd2) | Jul 26, 2020 |
| Foxconn       | 2ADA                        | [035b1fd159](https://linux-hardware.org/?probe=035b1fd159) | Jul 24, 2020 |
| ASUSTek       | AM1M-A/BR                   | [dafd042867](https://linux-hardware.org/?probe=dafd042867) | Jul 22, 2020 |
| ASUSTek       | H110M-A/M.2                 | [a3dc30f185](https://linux-hardware.org/?probe=a3dc30f185) | Jul 21, 2020 |
| Positivo      | POS-PQ45AU                  | [056dd1ec51](https://linux-hardware.org/?probe=056dd1ec51) | Jul 15, 2020 |
| ASUSTek       | H110I-PLUS                  | [116754d157](https://linux-hardware.org/?probe=116754d157) | Jul 11, 2020 |
| ASUSTek       | H110I-PLUS                  | [4a0dcf77f1](https://linux-hardware.org/?probe=4a0dcf77f1) | Jun 24, 2020 |
| MSI           | P67A-GD65                   | [c0df14bdee](https://linux-hardware.org/?probe=c0df14bdee) | Jun 22, 2020 |
| ASRock        | Z77 Extreme4                | [2e074b7913](https://linux-hardware.org/?probe=2e074b7913) | May 30, 2020 |
| Gigabyte      | 990XA-UD3                   | [cc7c6da435](https://linux-hardware.org/?probe=cc7c6da435) | May 19, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b8f32a998c](https://linux-hardware.org/?probe=b8f32a998c) | Mar 31, 2020 |
| Dell          | 0M863N A00                  | [39201e0067](https://linux-hardware.org/?probe=39201e0067) | Mar 30, 2020 |
| Dell          | 07C0H8 A00                  | [6863933279](https://linux-hardware.org/?probe=6863933279) | Mar 18, 2020 |
| ASRock        | J5005-ITX                   | [94c7463689](https://linux-hardware.org/?probe=94c7463689) | Mar 16, 2020 |
| ASRock        | J5005-ITX                   | [12e2c41514](https://linux-hardware.org/?probe=12e2c41514) | Mar 08, 2020 |
| ASRock        | J5005-ITX                   | [77ca797332](https://linux-hardware.org/?probe=77ca797332) | Mar 04, 2020 |
| ASRock        | J5005-ITX                   | [455989807e](https://linux-hardware.org/?probe=455989807e) | Mar 04, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c8e114bee8](https://linux-hardware.org/?probe=c8e114bee8) | Feb 14, 2020 |
| Medion        | MS-7728                     | [645a7667ce](https://linux-hardware.org/?probe=645a7667ce) | Feb 07, 2020 |
| Medion        | MS-7728                     | [c55f5705f3](https://linux-hardware.org/?probe=c55f5705f3) | Feb 07, 2020 |
| ASUSTek       | Z170-AR                     | [cd4ef749f3](https://linux-hardware.org/?probe=cd4ef749f3) | Feb 03, 2020 |
| ASUSTek       | Z170-AR                     | [74934afe78](https://linux-hardware.org/?probe=74934afe78) | Feb 03, 2020 |
| ASRock        | N68-S3 FX                   | [ddf39244d2](https://linux-hardware.org/?probe=ddf39244d2) | Dec 24, 2019 |
| ASRock        | N68-S3 FX                   | [5f2a15fa54](https://linux-hardware.org/?probe=5f2a15fa54) | Dec 24, 2019 |
| Lenovo        | 3107 NOK                    | [8545691fd8](https://linux-hardware.org/?probe=8545691fd8) | Oct 24, 2019 |
| ASUSTek       | Z97-A                       | [1c2f2dd0b9](https://linux-hardware.org/?probe=1c2f2dd0b9) | Aug 06, 2019 |
| ASUSTek       | P5G41T-M LX2/BR             | [834659c2b7](https://linux-hardware.org/?probe=834659c2b7) | Jun 18, 2019 |
| ASUSTek       | P8H61-M LX2 R2.0            | [883fb20fad](https://linux-hardware.org/?probe=883fb20fad) | Jun 18, 2019 |
| ASUSTek       | P5Q-E                       | [f16456d590](https://linux-hardware.org/?probe=f16456d590) | Mar 28, 2019 |
| ASUSTek       | P5G41T-M LX2/BR             | [dacef5f8e5](https://linux-hardware.org/?probe=dacef5f8e5) | Mar 28, 2019 |
| Positivo      | POS-EINM70CS POSITIVO       | [296a0cde2c](https://linux-hardware.org/?probe=296a0cde2c) | Mar 27, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [175525d48c](https://linux-hardware.org/?probe=175525d48c) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [dccca67c2e](https://linux-hardware.org/?probe=dccca67c2e) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [d0787d5045](https://linux-hardware.org/?probe=d0787d5045) | Mar 25, 2019 |
| Gigabyte      | H110M-H-CF                  | [730a46747b](https://linux-hardware.org/?probe=730a46747b) | Nov 07, 2018 |
| Gigabyte      | H110M-H-CF                  | [0e7a915eb4](https://linux-hardware.org/?probe=0e7a915eb4) | Oct 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Deepin 23      | 22       | 25.58%  |
| Deepin         | 14       | 16.28%  |
| UOS 20         | 10       | 11.63%  |
| Deepin 20      | 10       | 11.63%  |
| Deepin 20.9    | 4        | 4.65%   |
| Deepin 20 beta | 4        | 4.65%   |
| Deepin 15.9.2  | 4        | 4.65%   |
| Deepin 20.1    | 3        | 3.49%   |
| Deepin 15.11   | 3        | 3.49%   |
| Deepin 20.6    | 2        | 2.33%   |
| Deepin 20.3    | 2        | 2.33%   |
| Deepin 20.2.2  | 2        | 2.33%   |
| Deepin 15.10.1 | 2        | 2.33%   |
| Deepin 20.2.4  | 1        | 1.16%   |
| Deepin 20.2.3  | 1        | 1.16%   |
| Deepin 20.2    | 1        | 1.16%   |
| Deepin 15.7    | 1        | 1.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Deepin | 82       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.4.70-amd64-desktop        | 7        | 7.95%   |
| 4.15.0-30deepin-generic     | 7        | 7.95%   |
| 4.15.0-29deepin-generic     | 7        | 7.95%   |
| 5.4.50-amd64-desktop        | 6        | 6.82%   |
| 5.3.0-3-amd64               | 6        | 6.82%   |
| 6.9.6-amd64-desktop-rolling | 4        | 4.55%   |
| 6.6.47-amd64-desktop-hwe    | 4        | 4.55%   |
| 6.1.32-amd64-desktop-hwe    | 3        | 3.41%   |
| 5.15.77-amd64-desktop       | 3        | 3.41%   |
| 5.15.45-amd64-desktop       | 3        | 3.41%   |
| 5.10.60-amd64-desktop       | 3        | 3.41%   |
| 5.10.36-amd64-desktop       | 3        | 3.41%   |
| 5.10.0-amd64-desktop        | 3        | 3.41%   |
| 4.19.0-amd64-desktop        | 3        | 3.41%   |
| 6.3.0-rc4-amd64-exton       | 2        | 2.27%   |
| 5.7.7-amd64-desktop         | 2        | 2.27%   |
| 5.10.29-amd64-desktop       | 2        | 2.27%   |
| 5.10.18-amd64-desktop       | 2        | 2.27%   |
| 6.7.4-amd64-extix           | 1        | 1.14%   |
| 6.6.59-amd64-desktop-hwe    | 1        | 1.14%   |
| 6.6.36-amd64-desktop-hwe    | 1        | 1.14%   |
| 6.6.25-amd64-desktop-hwe    | 1        | 1.14%   |
| 6.10.8-1-liquorix-amd64     | 1        | 1.14%   |
| 6.1.12-1-liquorix-amd64     | 1        | 1.14%   |
| 6.1.11-amd64-desktop-hwe    | 1        | 1.14%   |
| 5.8.14-amd64-desktop        | 1        | 1.14%   |
| 5.5.4-xanmod3               | 1        | 1.14%   |
| 5.18.17-amd64-desktop-hwe   | 1        | 1.14%   |
| 5.15.34-amd64-desktop       | 1        | 1.14%   |
| 5.15.24-amd64-desktop       | 1        | 1.14%   |
| 5.14.0-rc3-amd64-desktop    | 1        | 1.14%   |
| 5.10.50-amd64-desktop       | 1        | 1.14%   |
| 5.10.5-amd64-desktop+       | 1        | 1.14%   |
| 5.10.101-amd64-desktop      | 1        | 1.14%   |
| 4.19.90-1.lns7.2.mips64el   | 1        | 1.14%   |
| 4.19.0-5-amd64              | 1        | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 14       | 15.91%  |
| 5.4.70   | 7        | 7.95%   |
| 5.4.50   | 6        | 6.82%   |
| 5.3.0    | 6        | 6.82%   |
| 6.9.6    | 4        | 4.55%   |
| 6.6.47   | 4        | 4.55%   |
| 4.19.0   | 4        | 4.55%   |
| 6.1.32   | 3        | 3.41%   |
| 5.15.77  | 3        | 3.41%   |
| 5.15.45  | 3        | 3.41%   |
| 5.10.60  | 3        | 3.41%   |
| 5.10.36  | 3        | 3.41%   |
| 5.10.0   | 3        | 3.41%   |
| 6.3.0    | 2        | 2.27%   |
| 5.7.7    | 2        | 2.27%   |
| 5.10.29  | 2        | 2.27%   |
| 5.10.18  | 2        | 2.27%   |
| 6.7.4    | 1        | 1.14%   |
| 6.6.59   | 1        | 1.14%   |
| 6.6.36   | 1        | 1.14%   |
| 6.6.25   | 1        | 1.14%   |
| 6.10.8   | 1        | 1.14%   |
| 6.1.12   | 1        | 1.14%   |
| 6.1.11   | 1        | 1.14%   |
| 5.8.14   | 1        | 1.14%   |
| 5.5.4    | 1        | 1.14%   |
| 5.18.17  | 1        | 1.14%   |
| 5.15.34  | 1        | 1.14%   |
| 5.15.24  | 1        | 1.14%   |
| 5.14.0   | 1        | 1.14%   |
| 5.10.50  | 1        | 1.14%   |
| 5.10.5   | 1        | 1.14%   |
| 5.10.101 | 1        | 1.14%   |
| 4.19.90  | 1        | 1.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 14       | 16.47%  |
| 4.15    | 14       | 16.47%  |
| 5.4     | 12       | 14.12%  |
| 5.15    | 8        | 9.41%   |
| 6.6     | 7        | 8.24%   |
| 5.3     | 6        | 7.06%   |
| 6.1     | 5        | 5.88%   |
| 4.19    | 5        | 5.88%   |
| 6.9     | 4        | 4.71%   |
| 6.3     | 2        | 2.35%   |
| 5.7     | 2        | 2.35%   |
| 6.7     | 1        | 1.18%   |
| 6.10    | 1        | 1.18%   |
| 5.8     | 1        | 1.18%   |
| 5.5     | 1        | 1.18%   |
| 5.18    | 1        | 1.18%   |
| 5.14    | 1        | 1.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 81       | 98.78%  |
| mips64 | 1        | 1.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Deepin  | 57       | 68.67%  |
| DDE     | 16       | 19.28%  |
| Unknown | 9        | 10.84%  |
| MATE    | 1        | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 77       | 92.77%  |
| Wayland | 4        | 4.82%   |
| Tty     | 2        | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 41       | 49.4%   |
| LightDM | 31       | 37.35%  |
| TDM     | 11       | 13.25%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 22       | 26.19%  |
| zh_CN   | 17       | 20.24%  |
| pt_BR   | 14       | 16.67%  |
| es_ES   | 9        | 10.71%  |
| Unknown | 8        | 9.52%   |
| de_DE   | 5        | 5.95%   |
| ru_RU   | 2        | 2.38%   |
| tr_TR   | 1        | 1.19%   |
| pl_PL   | 1        | 1.19%   |
| lt_LT   | 1        | 1.19%   |
| it_IT   | 1        | 1.19%   |
| id_ID   | 1        | 1.19%   |
| fr_FR   | 1        | 1.19%   |
| en_GB   | 1        | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 43       | 51.81%  |
| BIOS | 40       | 48.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 73       | 89.02%  |
| Btrfs   | 4        | 4.88%   |
| Unknown | 4        | 4.88%   |
| Tmpfs   | 1        | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 44.71%  |
| GPT     | 36       | 42.35%  |
| MBR     | 11       | 12.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 74.7%   |
| Yes       | 21       | 25.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 65       | 77.38%  |
| Yes       | 19       | 22.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 22       | 26.83%  |
| Gigabyte Technology        | 11       | 13.41%  |
| Dell                       | 8        | 9.76%   |
| TSINGHUA TONGFANG COMPUTER | 7        | 8.54%   |
| ASRock                     | 5        | 6.1%    |
| MSI                        | 4        | 4.88%   |
| Lenovo                     | 4        | 4.88%   |
| Intel                      | 3        | 3.66%   |
| Semp Toshiba               | 2        | 2.44%   |
| Positivo                   | 2        | 2.44%   |
| Hewlett-Packard            | 2        | 2.44%   |
| ECS                        | 2        | 2.44%   |
| OEM                        | 1        | 1.22%   |
| Medion                     | 1        | 1.22%   |
| MACHINIST                  | 1        | 1.22%   |
| Loongson                   | 1        | 1.22%   |
| Koloe                      | 1        | 1.22%   |
| Huanan                     | 1        | 1.22%   |
| Foxconn                    | 1        | 1.22%   |
| Colorful Technology        | 1        | 1.22%   |
| AMD                        | 1        | 1.22%   |
| Unknown                    | 1        | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500          | 7        | 8.54%   |
| ASUS All Series                          | 3        | 3.66%   |
| Semp Toshiba STI                         | 2        | 2.44%   |
| ECS H81H3-M4                             | 2        | 2.44%   |
| Positivo POS-PQ45AU                      | 1        | 1.22%   |
| Positivo POS-EINM70CS                    | 1        | 1.22%   |
| OEM ZXE CRB                              | 1        | 1.22%   |
| MSI MS-7C84                              | 1        | 1.22%   |
| MSI MS-7C83                              | 1        | 1.22%   |
| MSI MS-7851                              | 1        | 1.22%   |
| MSI MS-7681                              | 1        | 1.22%   |
| Medion MS-7728                           | 1        | 1.22%   |
| MACHINIST E5-RS9 V1.1                    | 1        | 1.22%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev     | 1        | 1.22%   |
| Lenovo YangTianT4900d-00 90GKCTO1WW      | 1        | 1.22%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW | 1        | 1.22%   |
| Lenovo ThinkCentre M82 2929AJ2           | 1        | 1.22%   |
| Lenovo ThinkCentre M82 2756CN9           | 1        | 1.22%   |
| Koloe Thurley                            | 1        | 1.22%   |
| Intel DX58SO AAE29331-504                | 1        | 1.22%   |
| Intel DH77EB AAG39073-304                | 1        | 1.22%   |
| Intel B75A                               | 1        | 1.22%   |
| Huanan X99-8M-F V1.1                     | 1        | 1.22%   |
| HP ProOne 400 G1 AiO                     | 1        | 1.22%   |
| HP 260-P020il                            | 1        | 1.22%   |
| Gigabyte Z77-DS3H                        | 1        | 1.22%   |
| Gigabyte Z170X-Gaming 7                  | 1        | 1.22%   |
| Gigabyte H81M-D2V                        | 1        | 1.22%   |
| Gigabyte H110M-H                         | 1        | 1.22%   |
| Gigabyte GA-78LMT-USB3                   | 1        | 1.22%   |
| Gigabyte F2A55M-S1                       | 1        | 1.22%   |
| Gigabyte B550M DS3H                      | 1        | 1.22%   |
| Gigabyte B450 I AORUS PRO WIFI           | 1        | 1.22%   |
| Gigabyte B365M D3H                       | 1        | 1.22%   |
| Gigabyte B360M AORUS Gaming 3            | 1        | 1.22%   |
| Gigabyte 990XA-UD3                       | 1        | 1.22%   |
| Foxconn p7-1430br                        | 1        | 1.22%   |
| Dell Vostro 270                          | 1        | 1.22%   |
| Dell Vostro 230                          | 1        | 1.22%   |
| Dell Precision WorkStation T3500         | 1        | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| TSINGHUA TONGFANG COMPUTER E500      | 7        | 8.54%   |
| ASUS ROG                             | 5        | 6.1%    |
| ASUS PRIME                           | 4        | 4.88%   |
| Lenovo ThinkCentre                   | 3        | 3.66%   |
| Dell OptiPlex                        | 3        | 3.66%   |
| ASUS All                             | 3        | 3.66%   |
| Semp Toshiba STI                     | 2        | 2.44%   |
| ECS H81H3-M4                         | 2        | 2.44%   |
| Dell Vostro                          | 2        | 2.44%   |
| Dell Inspiron                        | 2        | 2.44%   |
| ASUS TUF                             | 2        | 2.44%   |
| Positivo POS-PQ45AU                  | 1        | 1.22%   |
| Positivo POS-EINM70CS                | 1        | 1.22%   |
| OEM ZXE                              | 1        | 1.22%   |
| MSI MS-7C84                          | 1        | 1.22%   |
| MSI MS-7C83                          | 1        | 1.22%   |
| MSI MS-7851                          | 1        | 1.22%   |
| MSI MS-7681                          | 1        | 1.22%   |
| Medion MS-7728                       | 1        | 1.22%   |
| MACHINIST E5-RS9                     | 1        | 1.22%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev | 1        | 1.22%   |
| Lenovo YangTianT4900d-00             | 1        | 1.22%   |
| Koloe Thurley                        | 1        | 1.22%   |
| Intel DX58SO                         | 1        | 1.22%   |
| Intel DH77EB                         | 1        | 1.22%   |
| Intel B75A                           | 1        | 1.22%   |
| Huanan X99-8M-F                      | 1        | 1.22%   |
| HP ProOne                            | 1        | 1.22%   |
| HP 260-P020il                        | 1        | 1.22%   |
| Gigabyte Z77-DS3H                    | 1        | 1.22%   |
| Gigabyte Z170X-Gaming                | 1        | 1.22%   |
| Gigabyte H81M-D2V                    | 1        | 1.22%   |
| Gigabyte H110M-H                     | 1        | 1.22%   |
| Gigabyte GA-78LMT-USB3               | 1        | 1.22%   |
| Gigabyte F2A55M-S1                   | 1        | 1.22%   |
| Gigabyte B550M                       | 1        | 1.22%   |
| Gigabyte B450                        | 1        | 1.22%   |
| Gigabyte B365M                       | 1        | 1.22%   |
| Gigabyte B360M                       | 1        | 1.22%   |
| Gigabyte 990XA-UD3                   | 1        | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 15.85%  |
| 2020 | 11       | 13.41%  |
| 2021 | 10       | 12.2%   |
| 2012 | 8        | 9.76%   |
| 2018 | 6        | 7.32%   |
| 2011 | 6        | 7.32%   |
| 2017 | 5        | 6.1%    |
| 2014 | 4        | 4.88%   |
| 2010 | 4        | 4.88%   |
| 2009 | 4        | 4.88%   |
| 2022 | 3        | 3.66%   |
| 2016 | 3        | 3.66%   |
| 2019 | 2        | 2.44%   |
| 2023 | 1        | 1.22%   |
| 2015 | 1        | 1.22%   |
| 2008 | 1        | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 82       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 79       | 96.34%  |
| Enabled  | 3        | 3.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 82       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 27       | 32.93%  |
| 8.01-16.0   | 20       | 24.39%  |
| 4.01-8.0    | 14       | 17.07%  |
| 32.01-64.0  | 10       | 12.2%   |
| 3.01-4.0    | 7        | 8.54%   |
| 24.01-32.0  | 2        | 2.44%   |
| 64.01-256.0 | 1        | 1.22%   |
| 1.01-2.0    | 1        | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 23       | 25.84%  |
| 2.01-3.0   | 21       | 23.6%   |
| 1.01-2.0   | 20       | 22.47%  |
| 3.01-4.0   | 14       | 15.73%  |
| 0.51-1.0   | 6        | 6.74%   |
| 8.01-16.0  | 4        | 4.49%   |
| 16.01-24.0 | 1        | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 37.35%  |
| 2      | 27       | 32.53%  |
| 3      | 12       | 14.46%  |
| 4      | 10       | 12.05%  |
| 5      | 2        | 2.41%   |
| 8      | 1        | 1.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 69.05%  |
| Yes       | 26       | 30.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 82       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 58.54%  |
| Yes       | 34       | 41.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 64.63%  |
| Yes       | 29       | 35.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| China       | 20       | 24.39%  |
| Brazil      | 19       | 23.17%  |
| USA         | 8        | 9.76%   |
| Germany     | 4        | 4.88%   |
| Colombia    | 3        | 3.66%   |
| Russia      | 2        | 2.44%   |
| Panama      | 2        | 2.44%   |
| Mexico      | 2        | 2.44%   |
| Argentina   | 2        | 2.44%   |
| Ukraine     | 1        | 1.22%   |
| UK          | 1        | 1.22%   |
| Turkey      | 1        | 1.22%   |
| Spain       | 1        | 1.22%   |
| Romania     | 1        | 1.22%   |
| Poland      | 1        | 1.22%   |
| New Zealand | 1        | 1.22%   |
| Namibia     | 1        | 1.22%   |
| Morocco     | 1        | 1.22%   |
| Lithuania   | 1        | 1.22%   |
| Kenya       | 1        | 1.22%   |
| Italy       | 1        | 1.22%   |
| Indonesia   | 1        | 1.22%   |
| India       | 1        | 1.22%   |
| Iceland     | 1        | 1.22%   |
| Belgium     | 1        | 1.22%   |
| Bangladesh  | 1        | 1.22%   |
| Austria     | 1        | 1.22%   |
| Australia   | 1        | 1.22%   |
| Albania     | 1        | 1.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Wuhan              | 6        | 7.06%   |
| Sao Paulo          | 3        | 3.53%   |
| Nanjing            | 3        | 3.53%   |
| Beijing            | 3        | 3.53%   |
| Shanghai           | 2        | 2.35%   |
| San Francisco      | 2        | 2.35%   |
| David              | 2        | 2.35%   |
| Zhongshan          | 1        | 1.18%   |
| Yichun             | 1        | 1.18%   |
| Windhoek           | 1        | 1.18%   |
| Voluntari          | 1        | 1.18%   |
| Uberlândia        | 1        | 1.18%   |
| Tychy              | 1        | 1.18%   |
| Toluca             | 1        | 1.18%   |
| Tirana             | 1        | 1.18%   |
| Taua               | 1        | 1.18%   |
| Sydney             | 1        | 1.18%   |
| Surakarta          | 1        | 1.18%   |
| St Petersburg      | 1        | 1.18%   |
| Sonnen             | 1        | 1.18%   |
| Socorro            | 1        | 1.18%   |
| Shenzhen           | 1        | 1.18%   |
| Seesen             | 1        | 1.18%   |
| Sao Caetano do Sul | 1        | 1.18%   |
| Santo André       | 1        | 1.18%   |
| Santa Clarita      | 1        | 1.18%   |
| Rome               | 1        | 1.18%   |
| Rio de Janeiro     | 1        | 1.18%   |
| Reykjavik          | 1        | 1.18%   |
| Reading            | 1        | 1.18%   |
| Ransart            | 1        | 1.18%   |
| Qingdao            | 1        | 1.18%   |
| Para de Minas      | 1        | 1.18%   |
| Olinda             | 1        | 1.18%   |
| Oerlinghausen      | 1        | 1.18%   |
| Niterói           | 1        | 1.18%   |
| Naucalpan          | 1        | 1.18%   |
| Moscow             | 1        | 1.18%   |
| Mesa               | 1        | 1.18%   |
| Medellín          | 1        | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 31       | 40     | 19.38%  |
| Seagate                      | 22       | 29     | 13.75%  |
| Samsung Electronics          | 16       | 17     | 10%     |
| SanDisk                      | 10       | 14     | 6.25%   |
| Kingston                     | 10       | 15     | 6.25%   |
| Toshiba                      | 8        | 9      | 5%      |
| Crucial                      | 6        | 7      | 3.75%   |
| Hitachi                      | 5        | 6      | 3.13%   |
| Silicon Motion               | 4        | 4      | 2.5%    |
| China                        | 4        | 4      | 2.5%    |
| A-DATA Technology            | 4        | 5      | 2.5%    |
| Phison                       | 3        | 3      | 1.88%   |
| FORESEE                      | 3        | 3      | 1.88%   |
| SPCC                         | 2        | 2      | 1.25%   |
| Maxtor                       | 2        | 4      | 1.25%   |
| Intenso                      | 2        | 3      | 1.25%   |
| Hewlett-Packard              | 2        | 3      | 1.25%   |
| Gigabyte Technology          | 2        | 2      | 1.25%   |
| Yangtze Memory Technologies  | 1        | 1      | 0.63%   |
| Vaseky                       | 1        | 1      | 0.63%   |
| Unknown                      | 1        | 2      | 0.63%   |
| Shenzhen Longsys Electronics | 1        | 1      | 0.63%   |
| RZX                          | 1        | 1      | 0.63%   |
| Realtek Semiconductor        | 1        | 1      | 0.63%   |
| Phytium                      | 1        | 1      | 0.63%   |
| Phison Electronics           | 1        | 2      | 0.63%   |
| Mushkin                      | 1        | 1      | 0.63%   |
| Micron Technology            | 1        | 2      | 0.63%   |
| Maxtor 6                     | 1        | 1      | 0.63%   |
| MAXIO Technology (Hangzhou)  | 1        | 2      | 0.63%   |
| LaCie                        | 1        | 2      | 0.63%   |
| KingDian                     | 1        | 1      | 0.63%   |
| KINGBANK                     | 1        | 1      | 0.63%   |
| JMicron Technology           | 1        | 1      | 0.63%   |
| Intel                        | 1        | 2      | 0.63%   |
| HGST                         | 1        | 1      | 0.63%   |
| GLOWAY                       | 1        | 1      | 0.63%   |
| Colorful                     | 1        | 2      | 0.63%   |
| Beijing Starblaze            | 1        | 1      | 0.63%   |
| ASMT                         | 1        | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB                        | 4        | 2.29%   |
| Phison ESO256GMFCH-E3C-2 256GB                        | 3        | 1.71%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                      | 2        | 1.14%   |
| WDC WD5000AAKX-003CA0 500GB                           | 2        | 1.14%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 2        | 1.14%   |
| Toshiba DT01ACA200 2TB                                | 2        | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2        | 1.14%   |
| Seagate ST500DM002-1BD142 500GB                       | 2        | 1.14%   |
| Seagate ST3500418AS 500GB                             | 2        | 1.14%   |
| Seagate ST1000DM003-1SB102 1TB                        | 2        | 1.14%   |
| SanDisk SDSSDH3512G 512GB                             | 2        | 1.14%   |
| Samsung SSD 850 PRO 256GB                             | 2        | 1.14%   |
| Kingston SV300S37A120G 120GB SSD                      | 2        | 1.14%   |
| Kingston SA400S37480G 480GB SSD                       | 2        | 1.14%   |
| Kingston SA400S37240G 240GB SSD                       | 2        | 1.14%   |
| Kingston SA400S37120G 120GB SSD                       | 2        | 1.14%   |
| FORESEE P900F256GBH                                   | 2        | 1.14%   |
| Yangtze Memory ZHITAI PC005 Active 512GB              | 1        | 0.57%   |
| WDC WDS500G2B0C-00PXH0 500GB                          | 1        | 0.57%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                      | 1        | 0.57%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                        | 1        | 0.57%   |
| WDC WD80 0BEVE-11UYT0 80GB                            | 1        | 0.57%   |
| WDC WD7500BPKX-80HPJT0 752GB                          | 1        | 0.57%   |
| WDC WD7500BPKX-22HPJT0 752GB                          | 1        | 0.57%   |
| WDC WD6400AAKS-75A7B0 640GB                           | 1        | 0.57%   |
| WDC WD5000LPLX-66ZNTT1 500GB                          | 1        | 0.57%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 1        | 0.57%   |
| WDC WD5000AAKX-08U6AA0 500GB                          | 1        | 0.57%   |
| WDC WD5000AAKX-00U6AA0 500GB                          | 1        | 0.57%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 1        | 0.57%   |
| WDC WD5000AAKS-00A7B2 500GB                           | 1        | 0.57%   |
| WDC WD5000AAJS-57TKA0 500GB                           | 1        | 0.57%   |
| WDC WD3200BPVT-00JJ5T0 320GB                          | 1        | 0.57%   |
| WDC WD3200AAKS-61L9A0 320GB                           | 1        | 0.57%   |
| WDC WD3200AAKS-00VYA0 320GB                           | 1        | 0.57%   |
| WDC WD30EZRX-22D8PB0 3TB                              | 1        | 0.57%   |
| WDC WD2500BPVT-22ZEST0 250GB                          | 1        | 0.57%   |
| WDC WD2500AAKX-75U6AA0 250GB                          | 1        | 0.57%   |
| WDC WD20PURX-64P6ZY0 2TB                              | 1        | 0.57%   |
| WDC WD20EARX-00PASB0 2TB                              | 1        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 35     | 37.5%   |
| Seagate             | 22       | 29     | 30.56%  |
| Toshiba             | 8        | 9      | 11.11%  |
| Hitachi             | 5        | 6      | 6.94%   |
| Samsung Electronics | 3        | 3      | 4.17%   |
| Maxtor              | 2        | 4      | 2.78%   |
| Unknown             | 1        | 2      | 1.39%   |
| Maxtor 6            | 1        | 1      | 1.39%   |
| JMicron Technology  | 1        | 1      | 1.39%   |
| HGST                | 1        | 1      | 1.39%   |
| Hewlett-Packard     | 1        | 2      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 8        | 12     | 14.81%  |
| Kingston            | 8        | 13     | 14.81%  |
| Samsung Electronics | 7        | 8      | 12.96%  |
| Crucial             | 5        | 6      | 9.26%   |
| WDC                 | 4        | 4      | 7.41%   |
| China               | 4        | 4      | 7.41%   |
| A-DATA Technology   | 3        | 4      | 5.56%   |
| SPCC                | 2        | 2      | 3.7%    |
| Intenso             | 2        | 3      | 3.7%    |
| Vaseky              | 1        | 1      | 1.85%   |
| RZX                 | 1        | 1      | 1.85%   |
| Micron Technology   | 1        | 2      | 1.85%   |
| KingDian            | 1        | 1      | 1.85%   |
| KINGBANK            | 1        | 1      | 1.85%   |
| Intel               | 1        | 2      | 1.85%   |
| Hewlett-Packard     | 1        | 1      | 1.85%   |
| GLOWAY              | 1        | 1      | 1.85%   |
| Gigabyte Technology | 1        | 1      | 1.85%   |
| Colorful            | 1        | 2      | 1.85%   |
| Apacer              | 1        | 3      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 56       | 93     | 43.08%  |
| SSD     | 46       | 72     | 35.38%  |
| NVMe    | 27       | 36     | 20.77%  |
| Unknown | 1        | 2      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 77       | 155    | 70.64%  |
| NVMe | 27       | 35     | 24.77%  |
| SAS  | 5        | 13     | 4.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 58       | 97     | 52.73%  |
| 0.51-1.0   | 38       | 48     | 34.55%  |
| 1.01-2.0   | 11       | 15     | 10%     |
| 3.01-4.0   | 1        | 2      | 0.91%   |
| 2.01-3.0   | 1        | 1      | 0.91%   |
| 10.01-20.0 | 1        | 2      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 24       | 28.57%  |
| 101-250        | 15       | 17.86%  |
| 501-1000       | 14       | 16.67%  |
| 251-500        | 13       | 15.48%  |
| 2001-3000      | 8        | 9.52%   |
| More than 3000 | 5        | 5.95%   |
| 51-100         | 4        | 4.76%   |
| Unknown        | 1        | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 18       | 20.45%  |
| 501-1000       | 16       | 18.18%  |
| 251-500        | 14       | 15.91%  |
| 21-50          | 14       | 15.91%  |
| 1-20           | 13       | 14.77%  |
| 51-100         | 4        | 4.55%   |
| 2001-3000      | 3        | 3.41%   |
| 1001-2000      | 3        | 3.41%   |
| More than 3000 | 2        | 2.27%   |
| Unknown        | 1        | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD7500BPKX-80HPJT0 752GB       | 1        | 1      | 9.09%   |
| WDC WD5000LPLX-66ZNTT1 500GB       | 1        | 1      | 9.09%   |
| WDC WD3200AAKS-61L9A0 320GB        | 1        | 1      | 9.09%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 1      | 9.09%   |
| Toshiba MK8052GSX 80GB             | 1        | 1      | 9.09%   |
| Seagate ST3750528AS 752GB          | 1        | 1      | 9.09%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 9.09%   |
| Seagate ST1000DL002-9TT153 1TB     | 1        | 1      | 9.09%   |
| Samsung Electronics HD502HJ 500GB  | 1        | 1      | 9.09%   |
| Samsung Electronics HD250HJ 250GB  | 1        | 1      | 9.09%   |
| Hitachi HDP725050GLA360 500GB      | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 40%     |
| Seagate             | 2        | 3      | 20%     |
| Samsung Electronics | 2        | 2      | 20%     |
| Toshiba             | 1        | 1      | 10%     |
| Hitachi             | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 40%     |
| Seagate             | 2        | 3      | 20%     |
| Samsung Electronics | 2        | 2      | 20%     |
| Toshiba             | 1        | 1      | 10%     |
| Hitachi             | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 11     | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Hitachi HUA722010CLA330 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 46       | 84     | 46.94%  |
| Detected | 41       | 107    | 41.84%  |
| Malfunc  | 10       | 11     | 10.2%   |
| Failed   | 1        | 1      | 1.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 60       | 48.39%  |
| AMD                          | 18       | 14.52%  |
| Silicon Motion               | 6        | 4.84%   |
| Samsung Electronics          | 6        | 4.84%   |
| ASMedia Technology           | 6        | 4.84%   |
| Phison Electronics           | 5        | 4.03%   |
| Marvell Technology Group     | 4        | 3.23%   |
| Shenzhen Longsys Electronics | 3        | 2.42%   |
| SanDisk                      | 3        | 2.42%   |
| Kingston Technology Company  | 2        | 1.61%   |
| Beijing Starblaze Technology | 2        | 1.61%   |
| Zhaoxin                      | 1        | 0.81%   |
| Yangtze Memory Technologies  | 1        | 0.81%   |
| Realtek Semiconductor        | 1        | 0.81%   |
| Nvidia                       | 1        | 0.81%   |
| Micron/Crucial Technology    | 1        | 0.81%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.81%   |
| Loongson Technology          | 1        | 0.81%   |
| JMicron Technology           | 1        | 0.81%   |
| ADATA Technology             | 1        | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 6.29%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 9        | 6.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 5.59%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 8        | 5.59%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6        | 4.2%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 3.5%    |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 3.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4        | 2.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 3        | 2.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 2.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 2.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.1%    |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                                  | 2        | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 1.4%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 2        | 1.4%    |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 1.4%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.4%    |
| Beijing Starblaze STAR1200C NVMe SSD                                                    | 2        | 1.4%    |
| AMD FCH IDE Controller                                                                  | 2        | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.4%    |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000/KX-7000 StorX AHCI Controller           | 1        | 0.7%    |
| Yangtze Memory ZHITAI PC005 NVMe SSD                                                    | 1        | 0.7%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.7%    |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                                       | 1        | 0.7%    |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 1        | 0.7%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 1        | 0.7%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 1        | 0.7%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 1        | 0.7%    |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                           | 1        | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.7%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 1        | 0.7%    |
| Realtek RTS5762 NVMe SSD Controller                                                     | 1        | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 70       | 60.87%  |
| NVMe | 26       | 22.61%  |
| IDE  | 16       | 13.91%  |
| RAID | 3        | 2.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 61       | 74.39%  |
| AMD          | 19       | 23.17%  |
| CentaurHauls | 1        | 1.22%   |
| Unknown      | 1        | 1.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz           | 7        | 8.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 4.88%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 4.88%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 2.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 2.44%   |
| Intel Core i5-3550 CPU @ 3.30GHz            | 2        | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 2.44%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 2.44%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 2.44%   |
| AMD FX-8320 Eight-Core Processor            | 2        | 2.44%   |
| Intel Xeon CPU W3503 @ 2.40GHz              | 1        | 1.22%   |
| Intel Xeon CPU L5640 @ 2.27GHz              | 1        | 1.22%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1.22%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 1        | 1.22%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 1.22%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.22%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.22%   |
| Intel Core i9-14900                         | 1        | 1.22%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 1.22%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.22%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.22%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 1.22%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1        | 1.22%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.22%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 1        | 1.22%   |
| Intel Core i7 CPU 975 @ 3.33GHz             | 1        | 1.22%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.22%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.22%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.22%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.22%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.22%   |
| Intel Core i5-2300 CPU @ 2.80GHz            | 1        | 1.22%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 1        | 1.22%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 1        | 1.22%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 1        | 1.22%   |
| Intel Core i3-4160T CPU @ 3.10GHz           | 1        | 1.22%   |
| Intel Core i3-3240T CPU @ 2.90GHz           | 1        | 1.22%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 23       | 28.05%  |
| Intel Core i5           | 10       | 12.2%   |
| Intel Core i3           | 9        | 10.98%  |
| AMD Ryzen 5             | 6        | 7.32%   |
| Intel Xeon              | 5        | 6.1%    |
| Intel Celeron           | 5        | 6.1%    |
| Other                   | 4        | 4.88%   |
| Intel Core 2 Duo        | 4        | 4.88%   |
| AMD FX                  | 4        | 4.88%   |
| Intel Core i9           | 2        | 2.44%   |
| AMD Ryzen 9             | 2        | 2.44%   |
| AMD Ryzen 7             | 2        | 2.44%   |
| Intel Pentium Silver    | 1        | 1.22%   |
| Intel Pentium Dual-Core | 1        | 1.22%   |
| AMD Ryzen 3             | 1        | 1.22%   |
| AMD C-60                | 1        | 1.22%   |
| AMD Athlon              | 1        | 1.22%   |
| AMD A10                 | 1        | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 38       | 46.34%  |
| 2      | 17       | 20.73%  |
| 8      | 11       | 13.41%  |
| 6      | 8        | 9.76%   |
| 24     | 2        | 2.44%   |
| 12     | 2        | 2.44%   |
| 16     | 1        | 1.22%   |
| 10     | 1        | 1.22%   |
| 3      | 1        | 1.22%   |
| 1      | 1        | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 82       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 52       | 63.41%  |
| 1      | 30       | 36.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 77       | 93.9%   |
| Unknown        | 5        | 6.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 35.71%  |
| 0x306c3    | 9        | 10.71%  |
| 0x306a9    | 9        | 10.71%  |
| 0xa0655    | 5        | 5.95%   |
| 0x906e9    | 4        | 4.76%   |
| 0x1067a    | 4        | 4.76%   |
| 0x206a7    | 2        | 2.38%   |
| 0x0a20120e | 2        | 2.38%   |
| 0xb0671    | 1        | 1.19%   |
| 0xa0653    | 1        | 1.19%   |
| 0x906eb    | 1        | 1.19%   |
| 0x706a8    | 1        | 1.19%   |
| 0x506e3    | 1        | 1.19%   |
| 0x306f2    | 1        | 1.19%   |
| 0x206c2    | 1        | 1.19%   |
| 0x0a50000d | 1        | 1.19%   |
| 0x0a201016 | 1        | 1.19%   |
| 0x08701021 | 1        | 1.19%   |
| 0x08701013 | 1        | 1.19%   |
| 0x08101016 | 1        | 1.19%   |
| 0x08001138 | 1        | 1.19%   |
| 0x08001137 | 1        | 1.19%   |
| 0x07026101 | 1        | 1.19%   |
| 0x06000822 | 1        | 1.19%   |
| 0x06000629 | 1        | 1.19%   |
| 0x06000626 | 1        | 1.19%   |
| 0x0500010d | 1        | 1.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 13       | 15.85%  |
| Haswell          | 11       | 13.41%  |
| CometLake        | 11       | 13.41%  |
| Penryn           | 6        | 7.32%   |
| KabyLake         | 6        | 7.32%   |
| Zen 3            | 4        | 4.88%   |
| Zen 2            | 4        | 4.88%   |
| SandyBridge      | 4        | 4.88%   |
| Zen              | 3        | 3.66%   |
| Skylake          | 3        | 3.66%   |
| Unknown          | 3        | 3.66%   |
| Piledriver       | 2        | 2.44%   |
| Nehalem          | 2        | 2.44%   |
| Goldmont plus    | 2        | 2.44%   |
| Bulldozer        | 2        | 2.44%   |
| Alderlake Hybrid | 2        | 2.44%   |
| Westmere         | 1        | 1.22%   |
| Steamroller      | 1        | 1.22%   |
| Jaguar           | 1        | 1.22%   |
| Bobcat           | 1        | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Nvidia              | 34       | 36.56%  |
| Intel               | 29       | 31.18%  |
| AMD                 | 28       | 30.11%  |
| Zhaoxin             | 1        | 1.08%   |
| Loongson Technology | 1        | 1.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 7.29%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 6        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 4.17%   |
| Intel HD Graphics 630                                                       | 4        | 4.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 3.13%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 3.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 3.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 3.13%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 2.08%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 2.08%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 2.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 2.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.08%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 2.08%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 2.08%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 2.08%   |
| Zhaoxin KX-6000 C-960 GPU                                                   | 1        | 1.04%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.04%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 1.04%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.04%   |
| Nvidia GP106 [P106-100]                                                     | 1        | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.04%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 1.04%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.04%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.04%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.04%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 1.04%   |
| Nvidia GK104 [GeForce GTX 760 OEM]                                          | 1        | 1.04%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.04%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 1.04%   |
| Nvidia GF119 [GeForce 605]                                                  | 1        | 1.04%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.04%   |
| Nvidia GF116 [GeForce GT 545]                                               | 1        | 1.04%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.04%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 1.04%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.04%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 1        | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Nvidia              | 30       | 36.59%  |
| 1 x AMD                 | 25       | 30.49%  |
| 1 x Intel               | 19       | 23.17%  |
| Intel + Nvidia          | 3        | 3.66%   |
| Intel + AMD             | 2        | 2.44%   |
| 1 x Zhaoxin             | 1        | 1.22%   |
| 1 x Loongson Technology | 1        | 1.22%   |
| AMD + Nvidia            | 1        | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 55       | 67.07%  |
| Proprietary | 20       | 24.39%  |
| Unknown     | 7        | 8.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 47.06%  |
| 1.01-2.0   | 18       | 21.18%  |
| 7.01-8.0   | 8        | 9.41%   |
| 3.01-4.0   | 6        | 7.06%   |
| 0.51-1.0   | 5        | 5.88%   |
| 5.01-6.0   | 3        | 3.53%   |
| 0.01-0.5   | 3        | 3.53%   |
| 16.01-24.0 | 1        | 1.18%   |
| 8.01-16.0  | 1        | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 21.69%  |
| Goldstar             | 10       | 12.05%  |
| ViewSonic            | 5        | 6.02%   |
| Hewlett-Packard      | 5        | 6.02%   |
| Dell                 | 5        | 6.02%   |
| AOC                  | 4        | 4.82%   |
| Philips              | 3        | 3.61%   |
| Lenovo               | 3        | 3.61%   |
| Ancor Communications | 3        | 3.61%   |
| Acer                 | 3        | 3.61%   |
| Iiyama               | 2        | 2.41%   |
| HKC                  | 2        | 2.41%   |
| HannStar             | 2        | 2.41%   |
| BenQ                 | 2        | 2.41%   |
| ASUSTek Computer     | 2        | 2.41%   |
| Xiaomi               | 1        | 1.2%    |
| Unknown              | 1        | 1.2%    |
| Toshiba              | 1        | 1.2%    |
| TFC                  | 1        | 1.2%    |
| SKY                  | 1        | 1.2%    |
| SAC                  | 1        | 1.2%    |
| RTK                  | 1        | 1.2%    |
| Positivo             | 1        | 1.2%    |
| Packard Bell         | 1        | 1.2%    |
| MSI                  | 1        | 1.2%    |
| Hisense              | 1        | 1.2%    |
| Gateway              | 1        | 1.2%    |
| DTV                  | 1        | 1.2%    |
| BOE                  | 1        | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch              | 3        | 3.23%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch              | 2        | 2.15%   |
| Samsung Electronics LCD Monitor SAM0FF0 3840x2160 1872x1053mm 84.6-inch | 2        | 2.15%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 2        | 2.15%   |
| Xiaomi Mi TV XMD0076 3840x2160 800x450mm 36.1-inch                      | 1        | 1.08%   |
| ViewSonic VA2430-FHD VSC4038 1920x1080 527x296mm 23.8-inch              | 1        | 1.08%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1        | 1.08%   |
| Toshiba TV TSB0108 1920x540                                             | 1        | 1.08%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                        | 1        | 1.08%   |
| SKY 24X1Q SKY2380 2560x1440 520x290mm 23.4-inch                         | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch    | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                         | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch     | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch     | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch    | 1        | 1.08%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1        | 1.08%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch     | 1        | 1.08%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 521x293mm 23.5-inch       | 1        | 1.08%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch       | 1        | 1.08%   |
| Samsung Electronics LCD Monitor U32J59x 3840x2160                       | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                    | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM0E90 1366x768 609x347mm 27.6-inch    | 1        | 1.08%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1        | 1.08%   |
| Samsung Electronics LCD Monitor S24E390 1920x1080                       | 1        | 1.08%   |
| Samsung Electronics LCD Monitor S24E360 1920x1080                       | 1        | 1.08%   |
| Samsung Electronics LCD Monitor S24E310 3840x1080                       | 1        | 1.08%   |
| Samsung Electronics LCD Monitor S24E310                                 | 1        | 1.08%   |
| Samsung Electronics LCD Monitor LC49G95T 3840x1080                      | 1        | 1.08%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch       | 1        | 1.08%   |
| SAC G7u Pro SAC2766 3840x2160 597x336mm 27.0-inch                       | 1        | 1.08%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                       | 1        | 1.08%   |
| Positivo SMILE85X NON1801 1360x768 344x194mm 15.5-inch                  | 1        | 1.08%   |
| Philips FTV PHL04C2 1920x1080 1440x810mm 65.0-inch                      | 1        | 1.08%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 1        | 1.08%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                      | 1        | 1.08%   |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch           | 1        | 1.08%   |
| MSI MAG271C MSI3FA6 1920x1080 598x336mm 27.0-inch                       | 1        | 1.08%   |
| Lenovo LEN T2324C LEN60F2 1920x1080 510x287mm 23.0-inch                 | 1        | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 39       | 45.88%  |
| 3840x2160 (4K)     | 12       | 14.12%  |
| 2560x1440 (QHD)    | 7        | 8.24%   |
| 1600x900 (HD+)     | 6        | 7.06%   |
| 1680x1050 (WSXGA+) | 4        | 4.71%   |
| 3840x1080          | 3        | 3.53%   |
| 1440x900 (WXGA+)   | 3        | 3.53%   |
| 1366x768 (WXGA)    | 2        | 2.35%   |
| 1360x768           | 2        | 2.35%   |
| Unknown            | 2        | 2.35%   |
| 3440x1440          | 1        | 1.18%   |
| 2288x1287          | 1        | 1.18%   |
| 1920x540           | 1        | 1.18%   |
| 1920x1200 (WUXGA)  | 1        | 1.18%   |
| 1280x1024 (SXGA)   | 1        | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 22       | 25.58%  |
| Unknown | 11       | 12.79%  |
| 27      | 9        | 10.47%  |
| 24      | 8        | 9.3%    |
| 21      | 6        | 6.98%   |
| 20      | 5        | 5.81%   |
| 84      | 4        | 4.65%   |
| 22      | 4        | 4.65%   |
| 19      | 3        | 3.49%   |
| 18      | 3        | 3.49%   |
| 31      | 2        | 2.33%   |
| 142     | 1        | 1.16%   |
| 72      | 1        | 1.16%   |
| 65      | 1        | 1.16%   |
| 54      | 1        | 1.16%   |
| 34      | 1        | 1.16%   |
| 32      | 1        | 1.16%   |
| 28      | 1        | 1.16%   |
| 25      | 1        | 1.16%   |
| 12      | 1        | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 39       | 46.99%  |
| 401-500        | 19       | 22.89%  |
| Unknown        | 11       | 13.25%  |
| 1501-2000      | 5        | 6.02%   |
| 601-700        | 3        | 3.61%   |
| 701-800        | 2        | 2.41%   |
| 1001-1500      | 2        | 2.41%   |
| More than 2000 | 1        | 1.2%    |
| 201-300        | 1        | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 61       | 76.25%  |
| Unknown | 10       | 12.5%   |
| 16/10   | 7        | 8.75%   |
| 21/9    | 1        | 1.25%   |
| 1.00    | 1        | 1.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 33       | 39.29%  |
| 151-200        | 12       | 14.29%  |
| Unknown        | 11       | 13.1%   |
| 301-350        | 9        | 10.71%  |
| More than 1000 | 8        | 9.52%   |
| 351-500        | 5        | 5.95%   |
| 251-300        | 3        | 3.57%   |
| 141-150        | 2        | 2.38%   |
| 61-70          | 1        | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 50       | 61.73%  |
| 101-120 | 12       | 14.81%  |
| Unknown | 11       | 13.58%  |
| 1-50    | 4        | 4.94%   |
| 161-240 | 2        | 2.47%   |
| 121-160 | 2        | 2.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 66       | 78.57%  |
| 2     | 14       | 16.67%  |
| 0     | 3        | 3.57%   |
| 3     | 1        | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 54       | 47.37%  |
| Intel                      | 29       | 25.44%  |
| Qualcomm Atheros           | 5        | 4.39%   |
| Broadcom                   | 5        | 4.39%   |
| TP-Link                    | 3        | 2.63%   |
| MediaTek                   | 3        | 2.63%   |
| Xiaomi                     | 2        | 1.75%   |
| Ralink Technology          | 2        | 1.75%   |
| Unknown                    | 1        | 0.88%   |
| Shenzhen Goodix Technology | 1        | 0.88%   |
| Ralink                     | 1        | 0.88%   |
| NXP Semiconductors         | 1        | 0.88%   |
| Nvidia                     | 1        | 0.88%   |
| NetGear                    | 1        | 0.88%   |
| Marvell Technology Group   | 1        | 0.88%   |
| Loongson Technology        | 1        | 0.88%   |
| IMC Networks               | 1        | 0.88%   |
| Broadcom Limited           | 1        | 0.88%   |
| Aquantia                   | 1        | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 43       | 33.33%  |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 3.88%   |
| Intel Wi-Fi 6 AX200                                                    | 4        | 3.1%    |
| Intel Ethernet Connection (12) I219-V                                  | 4        | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 2.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 1.55%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)              | 2        | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 1.55%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 1.55%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 2        | 1.55%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 1.55%   |
| Intel Ethernet Controller I225-V                                       | 2        | 1.55%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 1.55%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 1.55%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2        | 1.55%   |
| Unknown                                                                | 2        | 1.55%   |
| Unknown Network controller                                             | 1        | 0.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 0.78%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1        | 0.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 1        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 0.78%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                 | 1        | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.78%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.78%   |
| NetGear A6210                                                          | 1        | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1        | 0.78%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                    | 1        | 0.78%   |
| MediaTek Infinix SMART 5                                               | 1        | 0.78%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.78%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 29.41%  |
| Realtek Semiconductor | 9        | 26.47%  |
| TP-Link               | 3        | 8.82%   |
| Qualcomm Atheros      | 3        | 8.82%   |
| Ralink Technology     | 2        | 5.88%   |
| MediaTek              | 2        | 5.88%   |
| Ralink                | 1        | 2.94%   |
| NetGear               | 1        | 2.94%   |
| IMC Networks          | 1        | 2.94%   |
| Broadcom Limited      | 1        | 2.94%   |
| Broadcom              | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 4        | 11.76%  |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)            | 2        | 5.88%   |
| Ralink MT7601U Wireless Adapter                                      | 2        | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 5.88%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 2        | 5.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1        | 2.94%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 2.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 2.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 2.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1        | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 1        | 2.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1        | 2.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1        | 2.94%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 2.94%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1        | 2.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1        | 2.94%   |
| NetGear A6210                                                        | 1        | 2.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1        | 2.94%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                  | 1        | 2.94%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 1        | 2.94%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1        | 2.94%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                 | 1        | 2.94%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 2.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 53       | 58.89%  |
| Intel                    | 24       | 26.67%  |
| Broadcom                 | 4        | 4.44%   |
| Xiaomi                   | 2        | 2.22%   |
| Qualcomm Atheros         | 2        | 2.22%   |
| Nvidia                   | 1        | 1.11%   |
| MediaTek                 | 1        | 1.11%   |
| Marvell Technology Group | 1        | 1.11%   |
| Loongson Technology      | 1        | 1.11%   |
| Aquantia                 | 1        | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 43       | 46.74%  |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 5.43%   |
| Intel Ethernet Connection (12) I219-V                                  | 4        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 3.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 2.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 2.17%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 2.17%   |
| Intel Ethernet Controller I225-V                                       | 2        | 2.17%   |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 2.17%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 2        | 2.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.09%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 1.09%   |
| MediaTek Infinix SMART 5                                               | 1        | 1.09%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 1.09%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 1        | 1.09%   |
| Loongson Gigabit Ethernet Controller                                   | 1        | 1.09%   |
| Intel Ethernet Controller I226-V                                       | 1        | 1.09%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.09%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.09%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.09%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.09%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.09%   |
| Intel 82575EB Gigabit Network Connection                               | 1        | 1.09%   |
| Intel 82567LM-2 Gigabit Network Connection                             | 1        | 1.09%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 1.09%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 1        | 1.09%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]      | 1        | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 68.91%  |
| WiFi     | 34       | 28.57%  |
| Unknown  | 2        | 1.68%   |
| Modem    | 1        | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 66       | 78.57%  |
| WiFi     | 18       | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 56       | 67.47%  |
| 2     | 22       | 26.51%  |
| 3     | 4        | 4.82%   |
| 4     | 1        | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 87.8%   |
| Yes  | 10       | 12.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 11       | 36.67%  |
| Intel                           | 10       | 33.33%  |
| Realtek Semiconductor           | 1        | 3.33%   |
| Qualcomm Atheros Communications | 1        | 3.33%   |
| MediaTek                        | 1        | 3.33%   |
| Lite-On Technology              | 1        | 3.33%   |
| IMC Networks                    | 1        | 3.33%   |
| Dynex                           | 1        | 3.33%   |
| Broadcom                        | 1        | 3.33%   |
| ASUSTek Computer                | 1        | 3.33%   |
| Apple                           | 1        | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 11       | 36.67%  |
| Intel AX200 Bluetooth                                    | 4        | 13.33%  |
| Intel AX201 Bluetooth                                    | 2        | 6.67%   |
| Realtek Bluetooth Radio                                  | 1        | 3.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 3.33%   |
| MediaTek BT                                              | 1        | 3.33%   |
| Lite-On Bluetooth Device                                 | 1        | 3.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1        | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                         | 1        | 3.33%   |
| Intel Bluetooth wireless interface                       | 1        | 3.33%   |
| Intel AX211 Bluetooth                                    | 1        | 3.33%   |
| IMC Networks Wireless_Device                             | 1        | 3.33%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 3.33%   |
| Broadcom HP Portable Bumble Bee                          | 1        | 3.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 3.33%   |
| Apple Bluetooth Host Controller                          | 1        | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 61       | 43.26%  |
| AMD                                          | 35       | 24.82%  |
| Nvidia                                       | 32       | 22.7%   |
| C-Media Electronics                          | 3        | 2.13%   |
| ASUSTek Computer                             | 2        | 1.42%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.71%   |
| Zhaoxin                                      | 1        | 0.71%   |
| XMOS                                         | 1        | 0.71%   |
| Microdia                                     | 1        | 0.71%   |
| Loongson Technology                          | 1        | 0.71%   |
| JMTek                                        | 1        | 0.71%   |
| Generalplus Technology                       | 1        | 0.71%   |
| BEHRINGER International                      | 1        | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                     | Desktops | Percent |
|-------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                       | 10       | 6.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                       | 10       | 6.33%   |
| Intel Comet Lake PCH-V cAVS                                                               | 9        | 5.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                   | 8        | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                | 7        | 4.43%   |
| AMD Starship/Matisse HD Audio Controller                                                  | 7        | 4.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                          | 4        | 2.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                          | 4        | 2.53%   |
| Intel 200 Series PCH HD Audio                                                             | 4        | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                           | 4        | 2.53%   |
| Nvidia GP106 High Definition Audio Controller                                             | 3        | 1.9%    |
| Nvidia GM204 High Definition Audio Controller                                             | 3        | 1.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                     | 3        | 1.9%    |
| Nvidia GF119 HDMI Audio Controller                                                        | 3        | 1.9%    |
| Nvidia GF116 High Definition Audio Controller                                             | 3        | 1.9%    |
| Nvidia GA104 High Definition Audio Controller                                             | 3        | 1.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                   | 3        | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                              | 3        | 1.9%    |
| AMD FCH Azalia Controller                                                                 | 3        | 1.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                | 3        | 1.9%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]         | 3        | 1.9%    |
| Nvidia High Definition Audio Controller                                                   | 2        | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                                        | 2        | 1.27%   |
| Intel Raptor Lake High Definition Audio Controller                                        | 2        | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                              | 2        | 1.27%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                       | 2        | 1.27%   |
| ASUSTek Computer USB Audio                                                                | 2        | 1.27%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                   | 2        | 1.27%   |
| AMD Navi 10 HDMI Audio                                                                    | 2        | 1.27%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                | 2        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                       | 2        | 1.27%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                            | 1        | 0.63%   |
| Zhaoxin ZX-E High Definition Audio Controller                                             | 1        | 0.63%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller | 1        | 0.63%   |
| XMOS iFi (by AMR) HD USB Audio                                                            | 1        | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                                             | 1        | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                            | 1        | 0.63%   |
| Nvidia MCP61 High Definition Audio                                                        | 1        | 0.63%   |
| Nvidia GP108 High Definition Audio Controller                                             | 1        | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                           | 1        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston                           | 14       | 29.17%  |
| Unknown                            | 5        | 10.42%  |
| SK hynix                           | 4        | 8.33%   |
| Samsung Electronics                | 3        | 6.25%   |
| G.Skill                            | 3        | 6.25%   |
| Corsair                            | 3        | 6.25%   |
| Unknown                            | 3        | 6.25%   |
| Team                               | 2        | 4.17%   |
| Ramaxel Technology                 | 2        | 4.17%   |
| A-DATA Technology                  | 2        | 4.17%   |
| Nanya Technology                   | 1        | 2.08%   |
| KINGBANK                           | 1        | 2.08%   |
| Kimtigo Semiconductor (HK) Limited | 1        | 2.08%   |
| Elpida                             | 1        | 2.08%   |
| CSX                                | 1        | 2.08%   |
| Crucial                            | 1        | 2.08%   |
| Apacer                             | 1        | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Kingston RAM TF32D4U2S1MEH-8 8192MB DIMM DDR4 3200MT/s     | 3        | 5.66%   |
| Unknown                                                    | 3        | 5.66%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 2        | 3.77%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                  | 1        | 1.89%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s               | 1        | 1.89%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                     | 1        | 1.89%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 1.89%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s         | 1        | 1.89%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s         | 1        | 1.89%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s         | 1        | 1.89%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.89%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 1        | 1.89%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s       | 1        | 1.89%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s       | 1        | 1.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 1        | 1.89%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s     | 1        | 1.89%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s        | 1        | 1.89%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s        | 1        | 1.89%   |
| Ramaxel RAM RMUA5110MB78HAF2400 8192MB DIMM DDR4 2400MT/s  | 1        | 1.89%   |
| Ramaxel RAM RMSA3230KE68H9F213 4096MB SODIMM DDR4 2133MT/s | 1        | 1.89%   |
| Nanya RAM M2X4G64CB8HG5N-DG 4GB DIMM DDR3 1867MT/s         | 1        | 1.89%   |
| Kingston RAM Module 4GB DIMM DDR3 1067MT/s                 | 1        | 1.89%   |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s             | 1        | 1.89%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 1.89%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s          | 1        | 1.89%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 3000MT/s        | 1        | 1.89%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 1.89%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s        | 1        | 1.89%   |
| Kingston RAM BRAP1G48GB16C1600 8192MB DIMM DDR3 1600MT/s   | 1        | 1.89%   |
| Kingston RAM 99U5474-038.A00LF 4GB DIMM DDR3 1333MT/s      | 1        | 1.89%   |
| Kingston RAM 99U5403-034.A00LF 4096MB DIMM DDR3 1333MT/s   | 1        | 1.89%   |
| Kingston RAM 99P5471-048.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.89%   |
| Kingston RAM 99P5471-016.A00LF 8GB DIMM DDR3 1600MT/s      | 1        | 1.89%   |
| KINGBANK RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 1.89%   |
| Kimtigo (HK) Limited RAM Module 8192MB DIMM DDR4 2666MT/s  | 1        | 1.89%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s       | 1        | 1.89%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s         | 1        | 1.89%   |
| G.Skill RAM F3-14900CL10-8GBXL 8GB DIMM DDR3 1867MT/s      | 1        | 1.89%   |
| Elpida RAM EBJ10UE8BBF0-AE-F 1GB DIMM DDR3 1066MT/s        | 1        | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 24       | 57.14%  |
| DDR3    | 15       | 35.71%  |
| Unknown | 2        | 4.76%   |
| SDRAM   | 1        | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 39       | 92.86%  |
| SODIMM | 3        | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 51.11%  |
| 4096  | 10       | 22.22%  |
| 16384 | 7        | 15.56%  |
| 32768 | 2        | 4.44%   |
| 1024  | 2        | 4.44%   |
| 2048  | 1        | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 8        | 16.33%  |
| 3600    | 4        | 8.16%   |
| 3200    | 4        | 8.16%   |
| 2400    | 4        | 8.16%   |
| 2133    | 3        | 6.12%   |
| 1867    | 3        | 6.12%   |
| 3800    | 2        | 4.08%   |
| 3400    | 2        | 4.08%   |
| 3000    | 2        | 4.08%   |
| 2667    | 2        | 4.08%   |
| 2666    | 2        | 4.08%   |
| 1333    | 2        | 4.08%   |
| 1067    | 2        | 4.08%   |
| 4266    | 1        | 2.04%   |
| 3500    | 1        | 2.04%   |
| 3466    | 1        | 2.04%   |
| 3066    | 1        | 2.04%   |
| 1866    | 1        | 2.04%   |
| 1648    | 1        | 2.04%   |
| 1066    | 1        | 2.04%   |
| 667     | 1        | 2.04%   |
| Unknown | 1        | 2.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 66.67%  |
| Seiko Epson     | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1        | 33.33%  |
| HP ENVY 5000 series                           | 1        | 33.33%  |
| HP Deskjet 3520 series                        | 1        | 33.33%  |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 7        | 50%     |
| Microdia               | 2        | 14.29%  |
| Trust                  | 1        | 7.14%   |
| Generalplus Technology | 1        | 7.14%   |
| Chicony Electronics    | 1        | 7.14%   |
| Arkmicro Technologies  | 1        | 7.14%   |
| 2M UVC CAMERA          | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech Webcam C270                  | 4        | 28.57%  |
| Trust Trust Full HD Webcam            | 1        | 7.14%   |
| Microdia Webcam Vitade AF             | 1        | 7.14%   |
| Microdia Integrated_Webcam_HD         | 1        | 7.14%   |
| Logitech Webcam C930e                 | 1        | 7.14%   |
| Logitech Webcam C200                  | 1        | 7.14%   |
| Logitech HD Pro Webcam C920           | 1        | 7.14%   |
| Generalplus GENERAL WEBCAM            | 1        | 7.14%   |
| Chicony HP High Definition 1MP Webcam | 1        | 7.14%   |
| Arkmicro USB2.0 PC CAMERA             | 1        | 7.14%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam   | 1        | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 70       | 84.34%  |
| 1     | 10       | 12.05%  |
| 2     | 3        | 3.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 9        | 64.29%  |
| Net/wireless  | 4        | 28.57%  |
| Network       | 1        | 7.14%   |

