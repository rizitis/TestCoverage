Reborn OS - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Reborn OS.

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

Total: 116

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | G3 3779                     | [41b5171b06](https://linux-hardware.org/?probe=41b5171b06) | Nov 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8321ed5f6d](https://linux-hardware.org/?probe=8321ed5f6d) | Sep 24, 2024 |
| ASUSTek       | ZenBook UX534FTC_UX534FT... | [3c3e540de3](https://linux-hardware.org/?probe=3c3e540de3) | Aug 20, 2024 |
| HP            | Laptop 14-cf3xxx            | [b09688c182](https://linux-hardware.org/?probe=b09688c182) | Jul 30, 2024 |
| ASUSTek       | K56CM                       | [1d41cec4b2](https://linux-hardware.org/?probe=1d41cec4b2) | May 23, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [bd0e45f06f](https://linux-hardware.org/?probe=bd0e45f06f) | May 21, 2024 |
| Dell          | Inspiron 5577               | [e3f9a3a5ad](https://linux-hardware.org/?probe=e3f9a3a5ad) | Apr 20, 2024 |
| Dell          | Inspiron 5577               | [f328c7d8f4](https://linux-hardware.org/?probe=f328c7d8f4) | Apr 19, 2024 |
| Acer          | Aspire A315-42              | [a91a8f1789](https://linux-hardware.org/?probe=a91a8f1789) | Mar 25, 2024 |
| Lenovo        | Z50-70 20354                | [ba354037ff](https://linux-hardware.org/?probe=ba354037ff) | Dec 07, 2023 |
| HP            | EliteBook 8460p             | [a8792eb2aa](https://linux-hardware.org/?probe=a8792eb2aa) | Nov 07, 2023 |
| Apple         | MacBookPro9,2               | [01c73b9338](https://linux-hardware.org/?probe=01c73b9338) | Oct 18, 2023 |
| Dell          | Inspiron 3537               | [2b79052692](https://linux-hardware.org/?probe=2b79052692) | Aug 28, 2023 |
| HP            | Pavilion Notebook           | [8c5385a962](https://linux-hardware.org/?probe=8c5385a962) | Jul 17, 2023 |
| HP            | EliteBook Folio 9470m       | [8503c5d0fe](https://linux-hardware.org/?probe=8503c5d0fe) | Jun 21, 2023 |
| HP            | EliteBook Folio 9470m       | [ab83a7d817](https://linux-hardware.org/?probe=ab83a7d817) | Jun 11, 2023 |
| Chuwi         | GemiBook Pro                | [772d1f8765](https://linux-hardware.org/?probe=772d1f8765) | Jun 03, 2023 |
| Timi          | A35S                        | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Dell          | XPS 13 9380                 | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [bd0af3660b](https://linux-hardware.org/?probe=bd0af3660b) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [12d1ccac8d](https://linux-hardware.org/?probe=12d1ccac8d) | Mar 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [57edb37217](https://linux-hardware.org/?probe=57edb37217) | Mar 08, 2023 |
| Medion        | X6816                       | [3f05d06600](https://linux-hardware.org/?probe=3f05d06600) | Feb 18, 2023 |
| Medion        | X6816                       | [fe99854800](https://linux-hardware.org/?probe=fe99854800) | Feb 17, 2023 |
| Biostar       | A320MH                      | [3fb3a04230](https://linux-hardware.org/?probe=3fb3a04230) | Jan 14, 2023 |
| Dell          | G15 5511                    | [d2c2cb8454](https://linux-hardware.org/?probe=d2c2cb8454) | Nov 30, 2022 |
| Dell          | G15 5511                    | [f9e456efd0](https://linux-hardware.org/?probe=f9e456efd0) | Nov 30, 2022 |
| Dell          | Latitude 3410               | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| HP            | ProBook 6565b               | [2d35057d85](https://linux-hardware.org/?probe=2d35057d85) | Jul 03, 2022 |
| HP            | ProBook 6565b               | [947c54ac42](https://linux-hardware.org/?probe=947c54ac42) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [58e0a1814b](https://linux-hardware.org/?probe=58e0a1814b) | Apr 21, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| HP            | ProBook 6550b               | [c09879cfcd](https://linux-hardware.org/?probe=c09879cfcd) | Dec 15, 2021 |
| HUAWEI        | MRC-WX0                     | [714f759476](https://linux-hardware.org/?probe=714f759476) | Dec 06, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de36837a42](https://linux-hardware.org/?probe=de36837a42) | Nov 02, 2021 |
| Lenovo        | IdeaPad Y580                | [409fb80ae5](https://linux-hardware.org/?probe=409fb80ae5) | Sep 10, 2021 |
| Acer          | Aspire V3-111P              | [8c38c04148](https://linux-hardware.org/?probe=8c38c04148) | Sep 05, 2021 |
| Acer          | Aspire V3-111P              | [af61c27b54](https://linux-hardware.org/?probe=af61c27b54) | Sep 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [13aee77624](https://linux-hardware.org/?probe=13aee77624) | Jun 30, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [19226582d9](https://linux-hardware.org/?probe=19226582d9) | May 31, 2021 |
| HP            | EliteBook 8460p             | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| HP            | EliteBook 8460p             | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [989604544a](https://linux-hardware.org/?probe=989604544a) | Apr 02, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [1b1d0bc44f](https://linux-hardware.org/?probe=1b1d0bc44f) | Mar 27, 2021 |
| CyberPower... | Tracer Series               | [295977bfa3](https://linux-hardware.org/?probe=295977bfa3) | Mar 24, 2021 |
| Acer          | Extensa 5635Z               | [890d530c6a](https://linux-hardware.org/?probe=890d530c6a) | Mar 18, 2021 |
| Dell          | Latitude E6320              | [9439943a67](https://linux-hardware.org/?probe=9439943a67) | Mar 15, 2021 |
| Avell High... | A62 LIV                     | [1f0a994797](https://linux-hardware.org/?probe=1f0a994797) | Mar 08, 2021 |
| Dell          | Inspiron 5584               | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Dell          | Precision M4600             | [661670d030](https://linux-hardware.org/?probe=661670d030) | Jan 27, 2021 |
| HP            | EliteBook 2560p             | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| Acer          | Aspire E1-572               | [cb03a43d6b](https://linux-hardware.org/?probe=cb03a43d6b) | Jan 18, 2021 |
| Dell          | Studio 1747                 | [b07052df59](https://linux-hardware.org/?probe=b07052df59) | Jan 13, 2021 |
| Dell          | Inspiron 5584               | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Acer          | Aspire E5-523               | [99c0e6fe8e](https://linux-hardware.org/?probe=99c0e6fe8e) | Jan 03, 2021 |
| HP            | Pavilion g7                 | [4df7168c54](https://linux-hardware.org/?probe=4df7168c54) | Dec 27, 2020 |
| HP            | Pavilion g7                 | [e2b98139df](https://linux-hardware.org/?probe=e2b98139df) | Dec 27, 2020 |
| Acer          | Aspire E5-523               | [ff03816a1e](https://linux-hardware.org/?probe=ff03816a1e) | Dec 16, 2020 |
| Lenovo        | ThinkPad E570 20H50048US    | [db0d5b5a47](https://linux-hardware.org/?probe=db0d5b5a47) | Dec 15, 2020 |
| Acer          | Swift SF314-42              | [c5a5070a6f](https://linux-hardware.org/?probe=c5a5070a6f) | Dec 10, 2020 |
| Acer          | Swift SF314-42              | [f5429557cc](https://linux-hardware.org/?probe=f5429557cc) | Dec 10, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [6ea56336d8](https://linux-hardware.org/?probe=6ea56336d8) | Dec 03, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [a4e4cd792d](https://linux-hardware.org/?probe=a4e4cd792d) | Dec 02, 2020 |
| Lenovo        | IdeaPad Y450                | [a5ec379304](https://linux-hardware.org/?probe=a5ec379304) | Dec 01, 2020 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [67aeba9d99](https://linux-hardware.org/?probe=67aeba9d99) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y450                | [300a14fb31](https://linux-hardware.org/?probe=300a14fb31) | Nov 29, 2020 |
| HP            | ProBook 640 G5              | [fc9abd07f4](https://linux-hardware.org/?probe=fc9abd07f4) | Nov 20, 2020 |
| Lenovo        | G470 20078                  | [98c4778da6](https://linux-hardware.org/?probe=98c4778da6) | Nov 18, 2020 |
| Acer          | Aspire F5-573G              | [9153f43376](https://linux-hardware.org/?probe=9153f43376) | Nov 02, 2020 |
| Acer          | Aspire E5-571G              | [9d695214a4](https://linux-hardware.org/?probe=9d695214a4) | Oct 27, 2020 |
| Dell          | Latitude 5500               | [b1f5e9ea7a](https://linux-hardware.org/?probe=b1f5e9ea7a) | Oct 25, 2020 |
| Sony          | VPCEH10EB                   | [167720fe57](https://linux-hardware.org/?probe=167720fe57) | Oct 25, 2020 |
| Razer         | Blade                       | [14ed46b628](https://linux-hardware.org/?probe=14ed46b628) | Oct 04, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | [6141f19045](https://linux-hardware.org/?probe=6141f19045) | Sep 17, 2020 |
| Lenovo        | ThinkPad Edge E431 62775... | [a34a40a5ff](https://linux-hardware.org/?probe=a34a40a5ff) | Sep 17, 2020 |
| Dell          | Latitude E6430              | [4fcaaadd6e](https://linux-hardware.org/?probe=4fcaaadd6e) | Sep 12, 2020 |
| HP            | 630                         | [baf66f73a2](https://linux-hardware.org/?probe=baf66f73a2) | Aug 14, 2020 |
| HP            | 630                         | [1f0b52b96d](https://linux-hardware.org/?probe=1f0b52b96d) | Aug 12, 2020 |
| Dell          | Inspiron 5520               | [27ed844469](https://linux-hardware.org/?probe=27ed844469) | Aug 08, 2020 |
| Dell          | Inspiron 5520               | [d40ce43d66](https://linux-hardware.org/?probe=d40ce43d66) | Jul 31, 2020 |
| Toshiba       | Satellite C850-C1S          | [3b431d9c9a](https://linux-hardware.org/?probe=3b431d9c9a) | Jul 31, 2020 |
| Dell          | Inspiron 5520               | [3fea05b48d](https://linux-hardware.org/?probe=3fea05b48d) | Jul 30, 2020 |
| Dell          | Latitude E6430              | [d14e88e089](https://linux-hardware.org/?probe=d14e88e089) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [56cc69c796](https://linux-hardware.org/?probe=56cc69c796) | Jun 27, 2020 |
| ASUSTek       | X540SA                      | [a1aaa82c04](https://linux-hardware.org/?probe=a1aaa82c04) | Jun 25, 2020 |
| ASUSTek       | X540SA                      | [1bab33423f](https://linux-hardware.org/?probe=1bab33423f) | Jun 25, 2020 |
| Lenovo        | ThinkPad T510 4349BS9       | [c525e8d7d2](https://linux-hardware.org/?probe=c525e8d7d2) | May 18, 2020 |
| ASUSTek       | UX430UAR                    | [acc88c72e9](https://linux-hardware.org/?probe=acc88c72e9) | May 06, 2020 |
| ASUSTek       | UX430UAR                    | [34b28c7178](https://linux-hardware.org/?probe=34b28c7178) | May 06, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [cd1f7d692d](https://linux-hardware.org/?probe=cd1f7d692d) | May 01, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [ddff2712b8](https://linux-hardware.org/?probe=ddff2712b8) | Apr 17, 2020 |
| Dell          | G7 7588                     | [68c487eb50](https://linux-hardware.org/?probe=68c487eb50) | Apr 15, 2020 |
| Lenovo        | Z70-80 80FG                 | [c27fa8aa9c](https://linux-hardware.org/?probe=c27fa8aa9c) | Apr 06, 2020 |
| Dell          | Latitude E6410              | [9d64ff0beb](https://linux-hardware.org/?probe=9d64ff0beb) | Mar 22, 2020 |
| Dell          | Inspiron 5421               | [2d8871e6ac](https://linux-hardware.org/?probe=2d8871e6ac) | Mar 19, 2020 |
| HP            | Pavilion 17                 | [5d3ccb9ed7](https://linux-hardware.org/?probe=5d3ccb9ed7) | Feb 24, 2020 |
| HP            | Pavilion dm1                | [e2e4a2c41f](https://linux-hardware.org/?probe=e2e4a2c41f) | Feb 13, 2020 |
| HP            | Pavilion 17                 | [26bdca3832](https://linux-hardware.org/?probe=26bdca3832) | Feb 09, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [48487463eb](https://linux-hardware.org/?probe=48487463eb) | Feb 09, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [9c202df9eb](https://linux-hardware.org/?probe=9c202df9eb) | Jan 14, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [12d0a26c62](https://linux-hardware.org/?probe=12d0a26c62) | Jan 12, 2020 |
| HP            | Pavilion 17                 | [baeaa7afdc](https://linux-hardware.org/?probe=baeaa7afdc) | Jan 11, 2020 |
| Acer          | Aspire E1-571               | [3b1545354e](https://linux-hardware.org/?probe=3b1545354e) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | [25229b0eaf](https://linux-hardware.org/?probe=25229b0eaf) | Jan 08, 2020 |
| Acer          | Aspire E1-571               | [3d68993148](https://linux-hardware.org/?probe=3d68993148) | Jan 08, 2020 |
| Avell High... | G1550 FOX                   | [b2380e6e7a](https://linux-hardware.org/?probe=b2380e6e7a) | Dec 30, 2019 |
| ASUSTek       | X555YI                      | [728d78c48c](https://linux-hardware.org/?probe=728d78c48c) | Sep 25, 2019 |
| Dell          | Inspiron 5520               | [26951086cf](https://linux-hardware.org/?probe=26951086cf) | Aug 29, 2019 |
| Lenovo        | G570 20079                  | [b1b5baaf85](https://linux-hardware.org/?probe=b1b5baaf85) | Dec 12, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Reborn OS         | 72        | 85.71%  |
| Reborn OS Rolling | 12        | 14.29%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Reborn OS | 84        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.9.14-arch1-1    | 5         | 5.75%   |
| 5.9.10-arch1-1    | 3         | 3.45%   |
| 5.5.9-arch1-2     | 3         | 3.45%   |
| 5.9.1-arch1-1     | 2         | 2.3%    |
| 5.6.4-arch1-1     | 2         | 2.3%    |
| 5.5.2-arch1-1     | 2         | 2.3%    |
| 5.4.10-arch1-1    | 2         | 2.3%    |
| 6.9.1-zen1-1-zen  | 1         | 1.15%   |
| 6.8.7-arch1-1     | 1         | 1.15%   |
| 6.8.1-arch1-1     | 1         | 1.15%   |
| 6.7.1-zen1-1-zen  | 1         | 1.15%   |
| 6.6.4-zen1-1-zen  | 1         | 1.15%   |
| 6.5.7-arch1-1     | 1         | 1.15%   |
| 6.4.3-arch1-2     | 1         | 1.15%   |
| 6.4.12-zen1-1-zen | 1         | 1.15%   |
| 6.3.4-arch1-1     | 1         | 1.15%   |
| 6.2.8-arch1-1     | 1         | 1.15%   |
| 6.2.7-arch1-1     | 1         | 1.15%   |
| 6.2.2-zen1-1-zen  | 1         | 1.15%   |
| 6.2.2-arch1-1     | 1         | 1.15%   |
| 6.11.9-arch1-1    | 1         | 1.15%   |
| 6.10.5-zen1-1-zen | 1         | 1.15%   |
| 6.10.2-arch1-1    | 1         | 1.15%   |
| 6.10.10-arch1-1   | 1         | 1.15%   |
| 6.1.61-1-lts      | 1         | 1.15%   |
| 6.1.33-1-lts      | 1         | 1.15%   |
| 6.1.12-arch1-1    | 1         | 1.15%   |
| 6.0.10-arch2-1    | 1         | 1.15%   |
| 5.9.2-zen1-1-zen  | 1         | 1.15%   |
| 5.9.13-arch1-1    | 1         | 1.15%   |
| 5.9.11-arch2-1    | 1         | 1.15%   |
| 5.9.10-zen1-1-zen | 1         | 1.15%   |
| 5.8.8-arch1-1     | 1         | 1.15%   |
| 5.8.5-arch1-1     | 1         | 1.15%   |
| 5.8.13-arch1-1    | 1         | 1.15%   |
| 5.7.8-arch1-1     | 1         | 1.15%   |
| 5.7.6-arch1-1     | 1         | 1.15%   |
| 5.7.5-arch1-1     | 1         | 1.15%   |
| 5.7.12-arch1-1    | 1         | 1.15%   |
| 5.7.11-arch1-1    | 1         | 1.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 5         | 5.75%   |
| 5.9.10  | 4         | 4.6%    |
| 5.5.9   | 3         | 3.45%   |
| 6.2.2   | 2         | 2.3%    |
| 5.9.1   | 2         | 2.3%    |
| 5.6.4   | 2         | 2.3%    |
| 5.5.2   | 2         | 2.3%    |
| 5.4.10  | 2         | 2.3%    |
| 5.11.11 | 2         | 2.3%    |
| 6.9.1   | 1         | 1.15%   |
| 6.8.7   | 1         | 1.15%   |
| 6.8.1   | 1         | 1.15%   |
| 6.7.1   | 1         | 1.15%   |
| 6.6.4   | 1         | 1.15%   |
| 6.5.7   | 1         | 1.15%   |
| 6.4.3   | 1         | 1.15%   |
| 6.4.12  | 1         | 1.15%   |
| 6.3.4   | 1         | 1.15%   |
| 6.2.8   | 1         | 1.15%   |
| 6.2.7   | 1         | 1.15%   |
| 6.11.9  | 1         | 1.15%   |
| 6.10.5  | 1         | 1.15%   |
| 6.10.2  | 1         | 1.15%   |
| 6.10.10 | 1         | 1.15%   |
| 6.1.61  | 1         | 1.15%   |
| 6.1.33  | 1         | 1.15%   |
| 6.1.12  | 1         | 1.15%   |
| 6.0.10  | 1         | 1.15%   |
| 5.9.2   | 1         | 1.15%   |
| 5.9.13  | 1         | 1.15%   |
| 5.9.11  | 1         | 1.15%   |
| 5.8.8   | 1         | 1.15%   |
| 5.8.5   | 1         | 1.15%   |
| 5.8.13  | 1         | 1.15%   |
| 5.7.8   | 1         | 1.15%   |
| 5.7.6   | 1         | 1.15%   |
| 5.7.5   | 1         | 1.15%   |
| 5.7.12  | 1         | 1.15%   |
| 5.7.11  | 1         | 1.15%   |
| 5.7.10  | 1         | 1.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9     | 14        | 16.28%  |
| 5.7     | 6         | 6.98%   |
| 5.4     | 6         | 6.98%   |
| 5.10    | 6         | 6.98%   |
| 5.5     | 5         | 5.81%   |
| 5.11    | 5         | 5.81%   |
| 6.2     | 4         | 4.65%   |
| 5.6     | 4         | 4.65%   |
| 6.10    | 3         | 3.49%   |
| 6.1     | 3         | 3.49%   |
| 5.8     | 3         | 3.49%   |
| 5.15    | 3         | 3.49%   |
| 6.8     | 2         | 2.33%   |
| 6.4     | 2         | 2.33%   |
| 5.18    | 2         | 2.33%   |
| 5.14    | 2         | 2.33%   |
| 5.13    | 2         | 2.33%   |
| 5.12    | 2         | 2.33%   |
| 4.19    | 2         | 2.33%   |
| 6.9     | 1         | 1.16%   |
| 6.7     | 1         | 1.16%   |
| 6.6     | 1         | 1.16%   |
| 6.5     | 1         | 1.16%   |
| 6.3     | 1         | 1.16%   |
| 6.11    | 1         | 1.16%   |
| 6.0     | 1         | 1.16%   |
| 5.3     | 1         | 1.16%   |
| 5.2     | 1         | 1.16%   |
| 5.16    | 1         | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 84        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 19        | 22.35%  |
| KDE5              | 14        | 16.47%  |
| XFCE              | 10        | 11.76%  |
| Deepin            | 9         | 10.59%  |
| KDE               | 8         | 9.41%   |
| X-Cinnamon        | 7         | 8.24%   |
| KDE6              | 5         | 5.88%   |
| Budgie            | 3         | 3.53%   |
| Unknown           | 3         | 3.53%   |
| MATE              | 2         | 2.35%   |
| i3                | 2         | 2.35%   |
| Yaru:ubuntu:GNOME | 1         | 1.18%   |
| LXQt              | 1         | 1.18%   |
| Enlightenment     | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 63        | 74.12%  |
| Wayland | 22        | 25.88%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 69        | 82.14%  |
| LightDM | 8         | 9.52%   |
| SDDM    | 4         | 4.76%   |
| TDM     | 2         | 2.38%   |
| XDM     | 1         | 1.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 33        | 39.29%  |
| pt_BR   | 8         | 9.52%   |
| en_GB   | 6         | 7.14%   |
| en_AU   | 5         | 5.95%   |
| de_DE   | 5         | 5.95%   |
| en_CA   | 4         | 4.76%   |
| ru_RU   | 3         | 3.57%   |
| Unknown | 3         | 3.57%   |
| pl_PL   | 2         | 2.38%   |
| nl_NL   | 2         | 2.38%   |
| es_MX   | 2         | 2.38%   |
| es_ES   | 2         | 2.38%   |
| sv_SE   | 1         | 1.19%   |
| fr_BE   | 1         | 1.19%   |
| fi_FI   | 1         | 1.19%   |
| es_CO   | 1         | 1.19%   |
| es_CL   | 1         | 1.19%   |
| en_DK   | 1         | 1.19%   |
| de_CH   | 1         | 1.19%   |
| da_DK   | 1         | 1.19%   |
| cs_CZ   | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 61        | 71.76%  |
| EFI  | 24        | 28.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 67        | 78.82%  |
| Btrfs   | 7         | 8.24%   |
| Tmpfs   | 6         | 7.06%   |
| Unknown | 4         | 4.71%   |
| Ext3    | 1         | 1.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 69        | 82.14%  |
| GPT     | 12        | 14.29%  |
| MBR     | 3         | 3.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 97.62%  |
| Yes       | 2         | 2.38%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 94.05%  |
| Yes       | 5         | 5.95%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 22        | 26.19%  |
| Dell                   | 19        | 22.62%  |
| Hewlett-Packard        | 15        | 17.86%  |
| Acer                   | 9         | 10.71%  |
| ASUSTek Computer       | 8         | 9.52%   |
| Avell High Performance | 2         | 2.38%   |
| Toshiba                | 1         | 1.19%   |
| Timi                   | 1         | 1.19%   |
| Sony                   | 1         | 1.19%   |
| Razer                  | 1         | 1.19%   |
| Medion                 | 1         | 1.19%   |
| HUAWEI                 | 1         | 1.19%   |
| CyberPowerPC           | 1         | 1.19%   |
| Chuwi                  | 1         | 1.19%   |
| Apple                  | 1         | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Lenovo IdeaPad 1 14IGL05 81VU          | 3         | 3.57%   |
| Dell Inspiron 5520                     | 3         | 3.57%   |
| HP EliteBook 8460p                     | 2         | 2.38%   |
| Dell Latitude E6430                    | 2         | 2.38%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA | 2         | 2.38%   |
| Toshiba Satellite C850-C1S             | 1         | 1.19%   |
| Timi A35S                              | 1         | 1.19%   |
| Sony VPCEH10EB                         | 1         | 1.19%   |
| Razer Blade                            | 1         | 1.19%   |
| Medion X6816                           | 1         | 1.19%   |
| Lenovo Z70-80 80FG                     | 1         | 1.19%   |
| Lenovo Z50-70 20354                    | 1         | 1.19%   |
| Lenovo Y50-70 20378                    | 1         | 1.19%   |
| Lenovo ThinkPad T510 4349BS9           | 1         | 1.19%   |
| Lenovo ThinkPad T440p 20AWS0Y800       | 1         | 1.19%   |
| Lenovo ThinkPad T410 253725G           | 1         | 1.19%   |
| Lenovo ThinkPad Edge E431 62775AU      | 1         | 1.19%   |
| Lenovo ThinkPad E570 20H50048US        | 1         | 1.19%   |
| Lenovo ThinkPad E490 20N8CTO1WW        | 1         | 1.19%   |
| Lenovo IdeaPad Y580                    | 1         | 1.19%   |
| Lenovo IdeaPad Y450                    | 1         | 1.19%   |
| Lenovo IdeaPad S145-15IWL 81MV         | 1         | 1.19%   |
| Lenovo IdeaPad S145-15API 81UT         | 1         | 1.19%   |
| Lenovo IdeaPad L340-17API 81LY         | 1         | 1.19%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 1.19%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 1.19%   |
| Lenovo IdeaPad 330-17IKB 81DM          | 1         | 1.19%   |
| Lenovo G570 20079                      | 1         | 1.19%   |
| Lenovo G470 20078                      | 1         | 1.19%   |
| HUAWEI MRC-WX0                         | 1         | 1.19%   |
| HP ProBook 6565b                       | 1         | 1.19%   |
| HP ProBook 6550b                       | 1         | 1.19%   |
| HP ProBook 640 G5                      | 1         | 1.19%   |
| HP Pavilion Notebook                   | 1         | 1.19%   |
| HP Pavilion Laptop 15-cw0xxx           | 1         | 1.19%   |
| HP Pavilion Laptop 15-cs0xxx           | 1         | 1.19%   |
| HP Pavilion Laptop 15-cc6xx            | 1         | 1.19%   |
| HP Pavilion g7                         | 1         | 1.19%   |
| HP Pavilion dm1                        | 1         | 1.19%   |
| HP Pavilion 17                         | 1         | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo IdeaPad               | 11        | 13.1%   |
| HP Pavilion                  | 7         | 8.33%   |
| Dell Inspiron                | 7         | 8.33%   |
| Acer Aspire                  | 7         | 8.33%   |
| Lenovo ThinkPad              | 6         | 7.14%   |
| Dell Latitude                | 6         | 7.14%   |
| HP EliteBook                 | 4         | 4.76%   |
| HP ProBook                   | 3         | 3.57%   |
| ASUS VivoBook                | 3         | 3.57%   |
| Toshiba Satellite            | 1         | 1.19%   |
| Timi A35S                    | 1         | 1.19%   |
| Sony VPCEH10EB               | 1         | 1.19%   |
| Razer Blade                  | 1         | 1.19%   |
| Medion X6816                 | 1         | 1.19%   |
| Lenovo Z70-80                | 1         | 1.19%   |
| Lenovo Z50-70                | 1         | 1.19%   |
| Lenovo Y50-70                | 1         | 1.19%   |
| Lenovo G570                  | 1         | 1.19%   |
| Lenovo G470                  | 1         | 1.19%   |
| HUAWEI MRC-WX0               | 1         | 1.19%   |
| HP Laptop                    | 1         | 1.19%   |
| Dell XPS                     | 1         | 1.19%   |
| Dell Studio                  | 1         | 1.19%   |
| Dell Precision               | 1         | 1.19%   |
| Dell G7                      | 1         | 1.19%   |
| Dell G3                      | 1         | 1.19%   |
| Dell G15                     | 1         | 1.19%   |
| CyberPowerPC Tracer          | 1         | 1.19%   |
| Chuwi GemiBook               | 1         | 1.19%   |
| Avell High Performance G1550 | 1         | 1.19%   |
| Avell High Performance A62   | 1         | 1.19%   |
| ASUS ZenBook                 | 1         | 1.19%   |
| ASUS X555YI                  | 1         | 1.19%   |
| ASUS X540SA                  | 1         | 1.19%   |
| ASUS UX430UAR                | 1         | 1.19%   |
| ASUS K56CM                   | 1         | 1.19%   |
| Apple MacBookPro9            | 1         | 1.19%   |
| Acer Swift                   | 1         | 1.19%   |
| Acer Extensa                 | 1         | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 12        | 14.29%  |
| 2019 | 11        | 13.1%   |
| 2011 | 11        | 13.1%   |
| 2018 | 10        | 11.9%   |
| 2020 | 8         | 9.52%   |
| 2021 | 6         | 7.14%   |
| 2014 | 5         | 5.95%   |
| 2013 | 5         | 5.95%   |
| 2009 | 5         | 5.95%   |
| 2016 | 4         | 4.76%   |
| 2010 | 3         | 3.57%   |
| 2017 | 2         | 2.38%   |
| 2015 | 2         | 2.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 84        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 84        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 84        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 38        | 45.24%  |
| 8.01-16.0  | 18        | 21.43%  |
| 3.01-4.0   | 12        | 14.29%  |
| 16.01-24.0 | 11        | 13.1%   |
| 32.01-64.0 | 5         | 5.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 36        | 41.38%  |
| 2.01-3.0  | 28        | 32.18%  |
| 4.01-8.0  | 9         | 10.34%  |
| 3.01-4.0  | 8         | 9.2%    |
| 0.51-1.0  | 4         | 4.6%    |
| 8.01-16.0 | 2         | 2.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 65        | 76.47%  |
| 2      | 19        | 22.35%  |
| 3      | 1         | 1.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 59.52%  |
| Yes       | 34        | 40.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 82.14%  |
| No        | 15        | 17.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 76.19%  |
| No        | 20        | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 21        | 25%     |
| Brazil      | 10        | 11.9%   |
| Germany     | 7         | 8.33%   |
| Canada      | 5         | 5.95%   |
| Russia      | 4         | 4.76%   |
| Australia   | 4         | 4.76%   |
| UK          | 3         | 3.57%   |
| Spain       | 3         | 3.57%   |
| Turkey      | 2         | 2.38%   |
| Poland      | 2         | 2.38%   |
| Netherlands | 2         | 2.38%   |
| Mexico      | 2         | 2.38%   |
| Estonia     | 2         | 2.38%   |
| Switzerland | 1         | 1.19%   |
| Sweden      | 1         | 1.19%   |
| Romania     | 1         | 1.19%   |
| Portugal    | 1         | 1.19%   |
| Malaysia    | 1         | 1.19%   |
| Ireland     | 1         | 1.19%   |
| Hungary     | 1         | 1.19%   |
| Finland     | 1         | 1.19%   |
| Denmark     | 1         | 1.19%   |
| Czechia     | 1         | 1.19%   |
| Costa Rica  | 1         | 1.19%   |
| Colombia    | 1         | 1.19%   |
| Chile       | 1         | 1.19%   |
| Benin       | 1         | 1.19%   |
| Belgium     | 1         | 1.19%   |
| Barbados    | 1         | 1.19%   |
| Austria     | 1         | 1.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Melbourne    | 3         | 3.53%   |
| Aleksandrov  | 3         | 3.53%   |
| Toronto      | 2         | 2.35%   |
| Tallinn      | 2         | 2.35%   |
| Sao Paulo    | 2         | 2.35%   |
| Zabrze       | 1         | 1.18%   |
| Yadrin       | 1         | 1.18%   |
| Warsaw       | 1         | 1.18%   |
| Villahermosa | 1         | 1.18%   |
| Tres Cantos  | 1         | 1.18%   |
| The Hague    | 1         | 1.18%   |
| Tatabánya   | 1         | 1.18%   |
| St Louis     | 1         | 1.18%   |
| Santiago     | 1         | 1.18%   |
| San Jose     | 1         | 1.18%   |
| Roebel       | 1         | 1.18%   |
| Reynoldsburg | 1         | 1.18%   |
| Rainham      | 1         | 1.18%   |
| Potts Camp   | 1         | 1.18%   |
| Portsmouth   | 1         | 1.18%   |
| Porto Uniao  | 1         | 1.18%   |
| Peterborough | 1         | 1.18%   |
| Paderborn    | 1         | 1.18%   |
| Orem         | 1         | 1.18%   |
| Olyphant     | 1         | 1.18%   |
| North Bay    | 1         | 1.18%   |
| Nijmegen     | 1         | 1.18%   |
| Newport News | 1         | 1.18%   |
| New Orleans  | 1         | 1.18%   |
| Nashville    | 1         | 1.18%   |
| Mogi Mirim   | 1         | 1.18%   |
| Mexico City  | 1         | 1.18%   |
| Mesa         | 1         | 1.18%   |
| Madrid       | 1         | 1.18%   |
| Liverpool    | 1         | 1.18%   |
| Limeira      | 1         | 1.18%   |
| Lawley       | 1         | 1.18%   |
| Lagoa Santa  | 1         | 1.18%   |
| Kuala Lumpur | 1         | 1.18%   |
| Kestel       | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 14.85%  |
| WDC                 | 12        | 12     | 11.88%  |
| Seagate             | 11        | 13     | 10.89%  |
| Toshiba             | 9         | 10     | 8.91%   |
| Kingston            | 8         | 9      | 7.92%   |
| Unknown             | 5         | 5      | 4.95%   |
| Intel               | 5         | 5      | 4.95%   |
| SanDisk             | 4         | 4      | 3.96%   |
| HGST                | 4         | 4      | 3.96%   |
| Crucial             | 4         | 4      | 3.96%   |
| SPCC                | 3         | 4      | 2.97%   |
| SK hynix            | 3         | 3      | 2.97%   |
| Transcend           | 2         | 2      | 1.98%   |
| Micron Technology   | 2         | 2      | 1.98%   |
| ADATA Technology    | 2         | 2      | 1.98%   |
| Phison Electronics  | 1         | 1      | 0.99%   |
| Patriot             | 1         | 1      | 0.99%   |
| OYUNKEY             | 1         | 1      | 0.99%   |
| Netac               | 1         | 1      | 0.99%   |
| LITEONIT            | 1         | 1      | 0.99%   |
| KIOXIA              | 1         | 1      | 0.99%   |
| Hitachi             | 1         | 1      | 0.99%   |
| Emtec               | 1         | 2      | 0.99%   |
| Dell                | 1         | 1      | 0.99%   |
| Corsair             | 1         | 1      | 0.99%   |
| Apple               | 1         | 1      | 0.99%   |
| A-DATA Technology   | 1         | 2      | 0.99%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                 | 4         | 3.81%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 2.86%   |
| Intel NVMe SSD Drive 512GB             | 3         | 2.86%   |
| HGST HTS725050A7E630 500GB             | 3         | 2.86%   |
| WDC WD10JPVT-08A1YT2 1TB               | 2         | 1.9%    |
| SPCC Solid State Disk 512GB            | 2         | 1.9%    |
| SK hynix NVMe SSD Drive 256GB          | 2         | 1.9%    |
| Seagate ST9500325AS 500GB              | 2         | 1.9%    |
| Seagate ST500LT012-1DG142 500GB        | 2         | 1.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 1.9%    |
| Kingston SA400S37240G 240GB SSD        | 2         | 1.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.95%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 1         | 0.95%   |
| WDC WD7500LPCX-60HWST0 752GB           | 1         | 0.95%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.95%   |
| WDC WD5000LPCX-00VHAT0 500GB           | 1         | 0.95%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 1         | 0.95%   |
| WDC WD10SPZX-22Z10T0 1TB               | 1         | 0.95%   |
| WDC WD10JPVX-60JC3T0 1TB               | 1         | 0.95%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.95%   |
| WDC WD10JPCX-24UE4T0 1TB               | 1         | 0.95%   |
| Unknown SD/MMC/MS PRO 128GB            | 1         | 0.95%   |
| Transcend TS1TSSD230S 1TB              | 1         | 0.95%   |
| Transcend TS128GMSA370 128GB SSD       | 1         | 0.95%   |
| Toshiba XG6 NVMe SSD Controller 1024GB | 1         | 0.95%   |
| Toshiba TR200 240GB SSD                | 1         | 0.95%   |
| Toshiba NVMe SSD Drive 512GB           | 1         | 0.95%   |
| Toshiba MQ01ABD100M 1TB                | 1         | 0.95%   |
| Toshiba MQ01ABD075 752GB               | 1         | 0.95%   |
| Toshiba MK5065GSXN 500GB               | 1         | 0.95%   |
| Toshiba MK3265GSX 320GB                | 1         | 0.95%   |
| Toshiba MK2555GSX 250GB                | 1         | 0.95%   |
| Toshiba KBG30ZMS256G NVMe 256GB        | 1         | 0.95%   |
| SPCC Solid State Disk 256GB            | 1         | 0.95%   |
| SK hynix PC711 NVMe 1TB                | 1         | 0.95%   |
| Seagate ST9500420AS 500GB              | 1         | 0.95%   |
| Seagate ST9320423AS 320GB              | 1         | 0.95%   |
| Seagate ST500LT012-9WS142 500GB        | 1         | 0.95%   |
| Seagate ST1000LX015-1U7172 1TB         | 1         | 0.95%   |
| Seagate ST1000LM035-1RK1 1TB           | 1         | 0.95%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 32.35%  |
| WDC                 | 10        | 10     | 29.41%  |
| Toshiba             | 5         | 6      | 14.71%  |
| HGST                | 4         | 4      | 11.76%  |
| Unknown             | 1         | 1      | 2.94%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 21.62%  |
| Kingston            | 8         | 9      | 21.62%  |
| Crucial             | 4         | 4      | 10.81%  |
| SPCC                | 3         | 4      | 8.11%   |
| SanDisk             | 3         | 3      | 8.11%   |
| WDC                 | 2         | 2      | 5.41%   |
| Transcend           | 2         | 2      | 5.41%   |
| Toshiba             | 1         | 1      | 2.7%    |
| Patriot             | 1         | 1      | 2.7%    |
| Netac               | 1         | 1      | 2.7%    |
| LITEONIT            | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| Corsair             | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 2      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 35        | 43     | 35.35%  |
| HDD     | 34        | 37     | 34.34%  |
| NVMe    | 23        | 24     | 23.23%  |
| MMC     | 4         | 4      | 4.04%   |
| Unknown | 3         | 4      | 3.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 63        | 79     | 67.74%  |
| NVMe | 23        | 24     | 24.73%  |
| MMC  | 4         | 4      | 4.3%    |
| SAS  | 3         | 5      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 49     | 63.01%  |
| 0.51-1.0   | 26        | 29     | 35.62%  |
| 1.01-2.0   | 1         | 2      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 34        | 38.64%  |
| 101-250    | 25        | 28.41%  |
| 501-1000   | 15        | 17.05%  |
| 51-100     | 6         | 6.82%   |
| 1001-2000  | 4         | 4.55%   |
| Unknown    | 3         | 3.41%   |
| 2001-3000  | 1         | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 31        | 35.23%  |
| 21-50    | 19        | 21.59%  |
| 101-250  | 15        | 17.05%  |
| 51-100   | 13        | 14.77%  |
| 251-500  | 5         | 5.68%   |
| Unknown  | 3         | 3.41%   |
| 501-1000 | 2         | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 75        | 100    | 87.21%  |
| Works    | 11        | 12     | 12.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 64        | 65.98%  |
| AMD                          | 14        | 14.43%  |
| Samsung Electronics          | 6         | 6.19%   |
| Toshiba America Info Systems | 3         | 3.09%   |
| SK hynix                     | 3         | 3.09%   |
| Micron Technology            | 2         | 2.06%   |
| ADATA Technology             | 2         | 2.06%   |
| SanDisk                      | 1         | 1.03%   |
| Phison Electronics           | 1         | 1.03%   |
| KIOXIA                       | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 13        | 12.87%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 10.89%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 8         | 7.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 7         | 6.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 4.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 4.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 3.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 3.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 3.96%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1.98%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 1.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 2         | 1.98%   |
| Intel SSD 660P Series                                                                  | 2         | 1.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 1.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.98%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                    | 1         | 0.99%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 1         | 0.99%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                  | 1         | 0.99%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.99%   |
| Micron 2210 NVMe SSD [Cobain]                                                          | 1         | 0.99%   |
| Micron 2200S NVMe SSD [Cassandra]                                                      | 1         | 0.99%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 1         | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 0.99%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 0.99%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 1         | 0.99%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 1         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 0.99%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                             | 1         | 0.99%   |
| ADATA ATOM 50, LEGEND 840 NVMe SSD (DRAM-less)                                         | 1         | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 69        | 69.7%   |
| NVMe | 22        | 22.22%  |
| RAID | 6         | 6.06%   |
| IDE  | 2         | 2.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 68        | 80.95%  |
| AMD    | 16        | 19.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 4.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 4.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 3.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 3.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 3.57%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 3.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 2.38%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 2.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 2.38%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 2.38%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 2.38%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 2.38%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.19%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 1.19%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.19%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 1.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 1.19%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.19%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.19%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 1.19%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.19%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 1         | 1.19%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 1.19%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 1.19%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 1.19%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.19%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.19%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 1.19%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.19%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.19%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.19%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.19%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 1.19%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 1.19%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.19%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 32.14%  |
| Intel Core i7           | 22        | 26.19%  |
| Intel Core i3           | 7         | 8.33%   |
| Intel Celeron           | 6         | 7.14%   |
| AMD Ryzen 5             | 5         | 5.95%   |
| AMD Ryzen 7             | 4         | 4.76%   |
| Other                   | 3         | 3.57%   |
| Intel Pentium           | 2         | 2.38%   |
| AMD A8                  | 2         | 2.38%   |
| Intel Pentium Dual-Core | 1         | 1.19%   |
| Intel Core 2 Duo        | 1         | 1.19%   |
| AMD Ryzen 3             | 1         | 1.19%   |
| AMD E                   | 1         | 1.19%   |
| AMD A6                  | 1         | 1.19%   |
| AMD A4                  | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 40        | 47.62%  |
| 4      | 35        | 41.67%  |
| 6      | 7         | 8.33%   |
| 8      | 2         | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 84        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 79.76%  |
| 1      | 17        | 20.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 96.43%  |
| Unknown        | 3         | 3.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 51.76%  |
| 0x306a9    | 6         | 7.06%   |
| 0x206a7    | 5         | 5.88%   |
| 0x906ea    | 3         | 3.53%   |
| 0x806ec    | 2         | 2.35%   |
| 0x806eb    | 2         | 2.35%   |
| 0x806e9    | 2         | 2.35%   |
| 0x40651    | 2         | 2.35%   |
| 0x306c3    | 2         | 2.35%   |
| 0x20655    | 2         | 2.35%   |
| 0x1067a    | 2         | 2.35%   |
| 0x07030106 | 2         | 2.35%   |
| 0x806ea    | 1         | 1.18%   |
| 0x806d1    | 1         | 1.18%   |
| 0x406c3    | 1         | 1.18%   |
| 0x306d4    | 1         | 1.18%   |
| 0x20652    | 1         | 1.18%   |
| 0x106e5    | 1         | 1.18%   |
| 0x0a50000c | 1         | 1.18%   |
| 0x08600102 | 1         | 1.18%   |
| 0x0810100b | 1         | 1.18%   |
| 0x06006704 | 1         | 1.18%   |
| 0x05000119 | 1         | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 23.81%  |
| IvyBridge     | 12        | 14.29%  |
| SandyBridge   | 11        | 13.1%   |
| Haswell       | 6         | 7.14%   |
| Zen+          | 5         | 5.95%   |
| Westmere      | 4         | 4.76%   |
| Goldmont plus | 4         | 4.76%   |
| Zen 3         | 3         | 3.57%   |
| Puma          | 3         | 3.57%   |
| Silvermont    | 2         | 2.38%   |
| Penryn        | 2         | 2.38%   |
| Icelake       | 2         | 2.38%   |
| Zen 2         | 1         | 1.19%   |
| Zen           | 1         | 1.19%   |
| TigerLake     | 1         | 1.19%   |
| Skylake       | 1         | 1.19%   |
| Nehalem       | 1         | 1.19%   |
| K10 Llano     | 1         | 1.19%   |
| Excavator     | 1         | 1.19%   |
| CometLake     | 1         | 1.19%   |
| Broadwell     | 1         | 1.19%   |
| Bobcat        | 1         | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 63        | 58.88%  |
| Nvidia | 22        | 20.56%  |
| AMD    | 22        | 20.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 11        | 10.09%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 10        | 9.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 4.59%   |
| Intel UHD Graphics 620                                                    | 5         | 4.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 4.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 3.67%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 4         | 3.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 3.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 3         | 2.75%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 2.75%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                 | 3         | 2.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 2.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 2         | 1.83%   |
| Intel HD Graphics 620                                                     | 2         | 1.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.83%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.83%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.92%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.92%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.92%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.92%   |
| Nvidia GM206M [GeForce GTX 965M]                                          | 1         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.92%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 0.92%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.92%   |
| Nvidia GK208M [GeForce GT 730M]                                           | 1         | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.92%   |
| Nvidia GF108M [GeForce GT 635M]                                           | 1         | 0.92%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 0.92%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 1         | 0.92%   |
| Nvidia GF106M [GeForce GT 555M]                                           | 1         | 0.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.92%   |
| Nvidia G96CM [GeForce GT 130M]                                            | 1         | 0.92%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                               | 1         | 0.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 0.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 0.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 0.92%   |
| Intel HD Graphics 630                                                     | 1         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 48.81%  |
| Intel + Nvidia | 18        | 21.43%  |
| 1 x AMD        | 15        | 17.86%  |
| Intel + AMD    | 4         | 4.76%   |
| 1 x Nvidia     | 3         | 3.57%   |
| 2 x AMD        | 2         | 2.38%   |
| AMD + Nvidia   | 1         | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 75        | 89.29%  |
| Proprietary | 8         | 9.52%   |
| Unknown     | 1         | 1.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 76.19%  |
| 0.51-1.0   | 9         | 10.71%  |
| 0.01-0.5   | 6         | 7.14%   |
| 1.01-2.0   | 2         | 2.38%   |
| 7.01-8.0   | 1         | 1.19%   |
| 5.01-6.0   | 1         | 1.19%   |
| 3.01-4.0   | 1         | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 27.37%  |
| LG Display              | 18        | 18.95%  |
| BOE                     | 12        | 12.63%  |
| Samsung Electronics     | 10        | 10.53%  |
| Chimei Innolux          | 10        | 10.53%  |
| Chi Mei Optoelectronics | 5         | 5.26%   |
| Sharp                   | 2         | 2.11%   |
| Hewlett-Packard         | 2         | 2.11%   |
| Toshiba                 | 1         | 1.05%   |
| MStar                   | 1         | 1.05%   |
| Lenovo                  | 1         | 1.05%   |
| Insignia                | 1         | 1.05%   |
| InfoVision              | 1         | 1.05%   |
| Goldstar                | 1         | 1.05%   |
| Dell                    | 1         | 1.05%   |
| CSO                     | 1         | 1.05%   |
| Apple                   | 1         | 1.05%   |
| AOC                     | 1         | 1.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 3.13%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 3         | 3.13%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch | 2         | 2.08%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 2.08%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 1.04%   |
| Sharp LQ156M1JW08 SHP14D4 1920x1080 344x194mm 15.5-inch                  | 1         | 1.04%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM037B 1680x1050 474x296mm 22.0-inch     | 1         | 1.04%   |
| Samsung Electronics SyncMaster SAM0254 1680x1050 474x296mm 22.0-inch     | 1         | 1.04%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC464C 1366x768 309x174mm 14.0-inch     | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 1         | 1.04%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch    | 1         | 1.04%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                         | 1         | 1.04%   |
| LG Display LCD Monitor LGD1325 1600x900 382x215mm 17.3-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD05FF 1920x1080 344x194mm 15.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD05F3 1920x1080 309x174mm 14.0-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 1         | 1.04%   |
| LG Display LCD Monitor LGD03D2 1366x768 309x174mm 14.0-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 1         | 1.04%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 1         | 1.04%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 1         | 1.04%   |
| Insignia TV BBY3223 1920x1080 697x392mm 31.5-inch                        | 1         | 1.04%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 1         | 1.04%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 473x296mm 22.0-inch             | 1         | 1.04%   |
| Hewlett-Packard LA1905 HWP2845 1440x900 408x255mm 18.9-inch              | 1         | 1.04%   |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                    | 1         | 1.04%   |
| Dell ST2220L DELA065 1920x1080 477x268mm 21.5-inch                       | 1         | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 39        | 42.39%  |
| 1920x1080 (FHD)    | 31        | 33.7%   |
| 1600x900 (HD+)     | 9         | 9.78%   |
| 3840x2160 (4K)     | 3         | 3.26%   |
| 1680x1050 (WSXGA+) | 3         | 3.26%   |
| 1440x900 (WXGA+)   | 3         | 3.26%   |
| 3456x2160          | 1         | 1.09%   |
| 2560x1600          | 1         | 1.09%   |
| 2160x1440          | 1         | 1.09%   |
| 1280x800 (WXGA)    | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 47        | 48.96%  |
| 14     | 16        | 16.67%  |
| 17     | 9         | 9.38%   |
| 13     | 9         | 9.38%   |
| 22     | 3         | 3.13%   |
| 21     | 2         | 2.08%   |
| 11     | 2         | 2.08%   |
| 86     | 1         | 1.04%   |
| 54     | 1         | 1.04%   |
| 52     | 1         | 1.04%   |
| 31     | 1         | 1.04%   |
| 27     | 1         | 1.04%   |
| 23     | 1         | 1.04%   |
| 19     | 1         | 1.04%   |
| 16     | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 70.83%  |
| 351-400     | 9         | 9.38%   |
| 201-300     | 7         | 7.29%   |
| 401-500     | 6         | 6.25%   |
| 1001-1500   | 3         | 3.13%   |
| 501-600     | 2         | 2.08%   |
| 601-700     | 1         | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 78        | 87.64%  |
| 16/10 | 9         | 10.11%  |
| 3/2   | 1         | 1.12%   |
| 0.56  | 1         | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 48.96%  |
| 81-90          | 22        | 22.92%  |
| 121-130        | 9         | 9.38%   |
| 201-250        | 6         | 6.25%   |
| More than 1000 | 3         | 3.13%   |
| 71-80          | 3         | 3.13%   |
| 51-60          | 2         | 2.08%   |
| 351-500        | 1         | 1.04%   |
| 301-350        | 1         | 1.04%   |
| 151-200        | 1         | 1.04%   |
| 111-120        | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 43        | 44.79%  |
| 121-160       | 35        | 36.46%  |
| 51-100        | 10        | 10.42%  |
| More than 240 | 3         | 3.13%   |
| 1-50          | 3         | 3.13%   |
| 161-240       | 2         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 72        | 85.71%  |
| 2     | 12        | 14.29%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 49        | 36.3%   |
| Intel                             | 40        | 29.63%  |
| Qualcomm Atheros                  | 24        | 17.78%  |
| Broadcom                          | 8         | 5.93%   |
| Huawei Technologies               | 3         | 2.22%   |
| Xiaomi                            | 1         | 0.74%   |
| TP-Link                           | 1         | 0.74%   |
| Spreadtrum Communications         | 1         | 0.74%   |
| Samsung Electronics               | 1         | 0.74%   |
| Ralink Technology                 | 1         | 0.74%   |
| Ralink                            | 1         | 0.74%   |
| Qualcomm                          | 1         | 0.74%   |
| Ericsson Business Mobile Networks | 1         | 0.74%   |
| DisplayLink                       | 1         | 0.74%   |
| Dell                              | 1         | 0.74%   |
| Broadcom Limited                  | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 18.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 5.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 4.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 3.57%   |
| Intel Centrino Ultimate-N 6300                                         | 6         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 2.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 2.38%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 3         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.79%   |
| Huawei E353/E3131                                                      | 3         | 1.79%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 1.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2         | 1.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.19%   |
| Intel Wireless 8265 / 8275                                             | 2         | 1.19%   |
| Intel Wireless 7265                                                    | 2         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.19%   |
| Intel Centrino Wireless-N 2230                                         | 2         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 1.19%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1         | 0.6%    |
| Spreadtrum Unisoc Phone                                                | 1         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.6%    |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.6%    |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.6%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 1         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 44.83%  |
| Qualcomm Atheros      | 23        | 26.44%  |
| Realtek Semiconductor | 15        | 17.24%  |
| Broadcom              | 6         | 6.9%    |
| TP-Link               | 1         | 1.15%   |
| Ralink Technology     | 1         | 1.15%   |
| Ralink                | 1         | 1.15%   |
| Broadcom Limited      | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 8.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 6.74%   |
| Intel Centrino Ultimate-N 6300                                 | 6         | 6.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 5.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 5.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 4.49%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 4.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 3.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.37%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 3.37%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 2.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 2.25%   |
| Intel Wireless 8265 / 8275                                     | 2         | 2.25%   |
| Intel Wireless 7265                                            | 2         | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.25%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.12%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.12%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.12%   |
| Intel Wireless 7260                                            | 1         | 1.12%   |
| Intel Wireless 3165                                            | 1         | 1.12%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.12%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.12%   |
| Intel Centrino Wireless-N 2200                                 | 1         | 1.12%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 1.12%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.12%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.12%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 43        | 58.9%   |
| Intel                     | 15        | 20.55%  |
| Qualcomm Atheros          | 5         | 6.85%   |
| Huawei Technologies       | 3         | 4.11%   |
| Broadcom                  | 3         | 4.11%   |
| Xiaomi                    | 1         | 1.37%   |
| Spreadtrum Communications | 1         | 1.37%   |
| Qualcomm                  | 1         | 1.37%   |
| DisplayLink               | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 40.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 13.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 10.53%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 3.95%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 3.95%   |
| Huawei E353/E3131                                                      | 3         | 3.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 1.32%   |
| Spreadtrum Unisoc Phone                                                | 1         | 1.32%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 1.32%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1.32%   |
| Qualcomm Airtel 4G                                                     | 1         | 1.32%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.32%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.32%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.32%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 1.32%   |
| DisplayLink Dell Universal Dock D6000                                  | 1         | 1.32%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.32%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 53.85%  |
| Ethernet | 69        | 44.23%  |
| Modem    | 3         | 1.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 74.71%  |
| Ethernet | 22        | 25.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 65        | 77.38%  |
| 1     | 19        | 22.62%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 74        | 88.1%   |
| Yes  | 10        | 11.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 40.63%  |
| Realtek Semiconductor           | 11        | 17.19%  |
| Qualcomm Atheros Communications | 6         | 9.38%   |
| Lite-On Technology              | 6         | 9.38%   |
| Hewlett-Packard                 | 3         | 4.69%   |
| Dell                            | 3         | 4.69%   |
| Broadcom                        | 3         | 4.69%   |
| IMC Networks                    | 2         | 3.13%   |
| Foxconn / Hon Hai               | 2         | 3.13%   |
| Foxconn International           | 1         | 1.56%   |
| Apple                           | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 7         | 10.94%  |
| Realtek Bluetooth Radio                           | 6         | 9.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 5         | 7.81%   |
| Intel AX201 Bluetooth                             | 5         | 7.81%   |
| Qualcomm Atheros  Bluetooth Device                | 4         | 6.25%   |
| Intel AX200 Bluetooth                             | 4         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                    | 3         | 4.69%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 3         | 4.69%   |
| HP Broadcom 2070 Bluetooth Combo                  | 3         | 4.69%   |
| Realtek RTL8723B Bluetooth                        | 2         | 3.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 3.13%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 3.13%   |
| Dell BCM20702A0 Bluetooth Module                  | 2         | 3.13%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 1.56%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 1.56%   |
| Lite-On Qualcomm Atheros Bluetooth                | 1         | 1.56%   |
| Lite-On BCM43142A0                                | 1         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.56%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.56%   |
| IMC Networks Bluetooth Device                     | 1         | 1.56%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.56%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device   | 1         | 1.56%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 1         | 1.56%   |
| Dell DW375 Bluetooth Module                       | 1         | 1.56%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.56%   |
| Broadcom BCM2046 Bluetooth Device                 | 1         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1)                       | 1         | 1.56%   |
| Apple Bluetooth USB Host Controller               | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 68        | 68%     |
| AMD       | 18        | 18%     |
| Nvidia    | 11        | 11%     |
| GN Netcom | 2         | 2%      |
| JMTek     | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 10.57%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 8.13%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 10        | 8.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 5.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 4.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 4.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 3.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.25%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 3.25%   |
| AMD FCH Azalia Controller                                                                         | 4         | 3.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 2.44%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.44%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.81%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.81%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.81%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.81%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.81%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.81%   |
| GN Netcom Jabra Evolve2 40                                                                        | 1         | 0.81%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 33.33%  |
| SK hynix            | 4         | 22.22%  |
| Unknown             | 2         | 11.11%  |
| Unknown (ABCD)      | 1         | 5.56%   |
| Team                | 1         | 5.56%   |
| Smart               | 1         | 5.56%   |
| Ramaxel Technology  | 1         | 5.56%   |
| Micron Technology   | 1         | 5.56%   |
| Kingston            | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 9.52%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 4.76%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 4.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 4.76%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 4.76%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 1         | 4.76%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 4.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 4.76%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 4.76%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 4.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 4.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 4.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 4.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 4.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 4.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 4.76%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 4.76%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 4.76%   |
| Micron RAM 4ATF11G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s      | 1         | 4.76%   |
| Kingston RAM HX426C16FB2/8 8GB DIMM DDR4 2667MT/s                | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 8         | 47.06%  |
| DDR3    | 6         | 35.29%  |
| LPDDR4  | 1         | 5.88%   |
| LPDDR3  | 1         | 5.88%   |
| Unknown | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 76.47%  |
| Row Of Chips | 3         | 17.65%  |
| DIMM         | 1         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 10        | 52.63%  |
| 4096  | 5         | 26.32%  |
| 2048  | 3         | 15.79%  |
| 32768 | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 5         | 27.78%  |
| 1600  | 5         | 27.78%  |
| 2667  | 4         | 22.22%  |
| 2400  | 1         | 5.56%   |
| 2133  | 1         | 5.56%   |
| 1067  | 1         | 5.56%   |
| 800   | 1         | 5.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Canon PIXMA MX920 Series | 1         | 100%    |

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
| Chicony Electronics                    | 18        | 22.22%  |
| Microdia                               | 12        | 14.81%  |
| Realtek Semiconductor                  | 10        | 12.35%  |
| IMC Networks                           | 10        | 12.35%  |
| Bison Electronics                      | 5         | 6.17%   |
| Syntek                                 | 4         | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.94%   |
| Suyin                                  | 3         | 3.7%    |
| Sunplus Innovation Technology          | 3         | 3.7%    |
| Quanta                                 | 2         | 2.47%   |
| Acer                                   | 2         | 2.47%   |
| Samsung Electronics                    | 1         | 1.23%   |
| Ricoh                                  | 1         | 1.23%   |
| Logitech                               | 1         | 1.23%   |
| Lite-On Technology                     | 1         | 1.23%   |
| Lenovo                                 | 1         | 1.23%   |
| Cubeternet                             | 1         | 1.23%   |
| Apple                                  | 1         | 1.23%   |
| Alcor Micro                            | 1         | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                       | 5         | 6.17%   |
| Microdia Integrated_Webcam_HD                           | 4         | 4.94%   |
| Microdia Laptop_Integrated_Webcam_E4HD                  | 3         | 3.7%    |
| Chicony Integrated HP HD Webcam                         | 3         | 3.7%    |
| Chicony Integrated Camera                               | 3         | 3.7%    |
| Bison EasyCamera                                        | 3         | 3.7%    |
| Syntek Lenovo EasyCamera                                | 2         | 2.47%   |
| Syntek Integrated Camera                                | 2         | 2.47%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 2         | 2.47%   |
| IMC Networks Integrated Camera                          | 2         | 2.47%   |
| Suyin Sony Visual Communication Camera                  | 1         | 1.23%   |
| Suyin Lenovo EasyCamera                                 | 1         | 1.23%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 1.23%   |
| Sunplus USB 2.0 Camera                                  | 1         | 1.23%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 1.23%   |
| Sunplus HD WebCam                                       | 1         | 1.23%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 1         | 1.23%   |
| Ricoh HD Webcam                                         | 1         | 1.23%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 1.23%   |
| Realtek USB Camera                                      | 1         | 1.23%   |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 1.23%   |
| Realtek Integrated_Webcam_HD                            | 1         | 1.23%   |
| Realtek Integrated Webcam                               | 1         | 1.23%   |
| Realtek HP Wide Vision FHD Camera                       | 1         | 1.23%   |
| Realtek HP Truevision HD                                | 1         | 1.23%   |
| Realtek HP "Truevision HD" laptop camera                | 1         | 1.23%   |
| Realtek HD WebCam                                       | 1         | 1.23%   |
| Realtek Front Camera                                    | 1         | 1.23%   |
| Quanta hm1091_techfront                                 | 1         | 1.23%   |
| Quanta HD User Facing                                   | 1         | 1.23%   |
| Microdia Webcam Vitade AF                               | 1         | 1.23%   |
| Microdia Laptop_Integrated_Webcam_2M                    | 1         | 1.23%   |
| Microdia Laptop Integrated Webcam HD (Composite Device) | 1         | 1.23%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 1.23%   |
| Microdia Dell Integrated HD Webcam                      | 1         | 1.23%   |
| Logitech HD Pro Webcam C920                             | 1         | 1.23%   |
| Lite-On HP Wide Vision HD Camera                        | 1         | 1.23%   |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 1.23%   |
| IMC Networks XiaoMi Webcam                              | 1         | 1.23%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 1         | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 64.29%  |
| Synaptics             | 2         | 14.29%  |
| Elan Microelectronics | 2         | 14.29%  |
| Upek                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader             | 4         | 28.57%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 14.29%  |
| Elan ELAN:Fingerprint                                  | 2         | 14.29%  |
| Validity Sensors VFS491                                | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 50%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 49        | 58.33%  |
| 1     | 30        | 35.71%  |
| 2     | 5         | 5.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 35%     |
| Net/wireless          | 7         | 17.5%   |
| Graphics card         | 6         | 15%     |
| Chipcard              | 6         | 15%     |
| Multimedia controller | 3         | 7.5%    |
| Storage               | 2         | 5%      |
| Net/ethernet          | 1         | 2.5%    |
| Camera                | 1         | 2.5%    |

