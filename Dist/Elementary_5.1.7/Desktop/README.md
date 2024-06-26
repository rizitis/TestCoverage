Elementary 5.1.7 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Elementary 5.1.7.

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

Total: 101

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte  | GA-880GMA-UD2H              | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| ASUSTek   | Z87-A                       | [755bed02ff](https://linux-hardware.org/?probe=755bed02ff) | Jan 25, 2023 |
| ASUSTek   | Z87-A                       | [6ccfafe0d6](https://linux-hardware.org/?probe=6ccfafe0d6) | Jan 24, 2023 |
| Lenovo    | ThinkCentre M71e 3129C3G    | [cb9f99f1cf](https://linux-hardware.org/?probe=cb9f99f1cf) | Dec 23, 2022 |
| MSI       | B350 TOMAHAWK               | [0ce6563922](https://linux-hardware.org/?probe=0ce6563922) | Dec 11, 2022 |
| MSI       | IONA                        | [280083cfa1](https://linux-hardware.org/?probe=280083cfa1) | Nov 22, 2022 |
| Lenovo    | MAHOBAY NO DPK              | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
| Gigabyte  | H81M-DS2                    | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| Gigabyte  | H81M-DS2                    | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| Dell      | 0GM819                      | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| ASUSTek   | P5KPL-VM/S                  | [66223d6ef0](https://linux-hardware.org/?probe=66223d6ef0) | May 25, 2022 |
| ASUSTek   | P5KPL-VM/S                  | [d44e9d6290](https://linux-hardware.org/?probe=d44e9d6290) | May 25, 2022 |
| Gigabyte  | GA-880GMA-UD2H              | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| ASUSTek   | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| HP        | 18E7                        | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| Dell      | 0HMX8D A01                  | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| ASUSTek   | H81-PLUS                    | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| ASUSTek   | P8H61-M LX3 R2.0            | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| ASRock    | H97M Pro4                   | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASRock    | Z370 Pro4                   | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| ASUSTek   | PRIME X470-PRO              | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Foxconn   | 2AB1                        | [09a8a91f9e](https://linux-hardware.org/?probe=09a8a91f9e) | Nov 26, 2021 |
| Foxconn   | 2AB1                        | [f965bf0bd8](https://linux-hardware.org/?probe=f965bf0bd8) | Nov 18, 2021 |
| Apple     | Mac-F4208DC8 PVT            | [3369764322](https://linux-hardware.org/?probe=3369764322) | Nov 17, 2021 |
| Intel     | DG35EC AAE29266-205         | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel     | DG35EC AAE29266-205         | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| Foxconn   | 2AB1                        | [49aef5b72e](https://linux-hardware.org/?probe=49aef5b72e) | Oct 26, 2021 |
| Gigabyte  | H67A-USB3-B3                | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| Gigabyte  | H67A-USB3-B3                | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Gigabyte  | H67A-USB3-B3                | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| Gigabyte  | Z68P-DS3                    | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| Acer      | Aspire XC-603G              | [8a37f28ecc](https://linux-hardware.org/?probe=8a37f28ecc) | Jul 31, 2021 |
| Biostar   | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar   | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek   | ROG STRIX Z390-H GAMING     | [9e27318e84](https://linux-hardware.org/?probe=9e27318e84) | Jul 14, 2021 |
| ASUSTek   | PRIME A320M-K               | [5e0580b431](https://linux-hardware.org/?probe=5e0580b431) | Jun 08, 2021 |
| ASUSTek   | H81M-K                      | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| Gigabyte  | AB350M-DS3H V2-CF           | [98d6e8f2d2](https://linux-hardware.org/?probe=98d6e8f2d2) | Apr 15, 2021 |
| ASUSTek   | SABERTOOTH Z87              | [542d0b7163](https://linux-hardware.org/?probe=542d0b7163) | Apr 13, 2021 |
| Dell      | 06NWYK A01                  | [304541ce36](https://linux-hardware.org/?probe=304541ce36) | Apr 08, 2021 |
| Dell      | 06NWYK A01                  | [47766de8d9](https://linux-hardware.org/?probe=47766de8d9) | Apr 07, 2021 |
| MSI       | H61M-P31                    | [867b109a0b](https://linux-hardware.org/?probe=867b109a0b) | Apr 07, 2021 |
| HP        | 843F                        | [d5b68ba3fb](https://linux-hardware.org/?probe=d5b68ba3fb) | Apr 07, 2021 |
| MSI       | B450M PRO-VDH MAX           | [9a1463fd59](https://linux-hardware.org/?probe=9a1463fd59) | Mar 22, 2021 |
| Gigabyte  | H61M-S2PV                   | [bbe4962b33](https://linux-hardware.org/?probe=bbe4962b33) | Mar 22, 2021 |
| HP        | 843F                        | [a4fc49c430](https://linux-hardware.org/?probe=a4fc49c430) | Mar 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [65c7806bad](https://linux-hardware.org/?probe=65c7806bad) | Mar 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [e1289a40a1](https://linux-hardware.org/?probe=e1289a40a1) | Feb 28, 2021 |
| Lenovo    | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| ASUSTek   | ROG STRIX B350-F GAMING     | [268b9f895a](https://linux-hardware.org/?probe=268b9f895a) | Feb 10, 2021 |
| Gigabyte  | Z77-DS3H                    | [a5a556b691](https://linux-hardware.org/?probe=a5a556b691) | Feb 09, 2021 |
| Gigabyte  | A320M-S2H V2-CF             | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| MSI       | B450M PRO-VDH MAX           | [895ec88c20](https://linux-hardware.org/?probe=895ec88c20) | Feb 08, 2021 |
| ASRock    | Z75 Pro3                    | [f2d919b5c5](https://linux-hardware.org/?probe=f2d919b5c5) | Feb 03, 2021 |
| Biostar   | Hi-Fi A70U3P                | [c2727e98b9](https://linux-hardware.org/?probe=c2727e98b9) | Feb 02, 2021 |
| Biostar   | Hi-Fi A70U3P                | [2c11d020c7](https://linux-hardware.org/?probe=2c11d020c7) | Feb 02, 2021 |
| MSI       | B450M PRO-VDH MAX           | [98cc7a4bca](https://linux-hardware.org/?probe=98cc7a4bca) | Jan 15, 2021 |
| Gigabyte  | GA-MA78GM-S2H               | [d40272076d](https://linux-hardware.org/?probe=d40272076d) | Jan 13, 2021 |
| Gigabyte  | GA-MA78GM-S2H               | [d31c109973](https://linux-hardware.org/?probe=d31c109973) | Jan 13, 2021 |
| EVGA      | 132-CK-NF79 2               | [44c54ae3df](https://linux-hardware.org/?probe=44c54ae3df) | Jan 09, 2021 |
| MSI       | P35 Platinum                | [105ebcfc8d](https://linux-hardware.org/?probe=105ebcfc8d) | Jan 08, 2021 |
| ASUSTek   | M5A97                       | [0f975cd5e6](https://linux-hardware.org/?probe=0f975cd5e6) | Jan 03, 2021 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [721dd0a694](https://linux-hardware.org/?probe=721dd0a694) | Jan 03, 2021 |
| MSI       | B450M PRO-VDH MAX           | [7197a45b8a](https://linux-hardware.org/?probe=7197a45b8a) | Dec 30, 2020 |
| Dell      | 0T656F A02                  | [1830ce642b](https://linux-hardware.org/?probe=1830ce642b) | Dec 29, 2020 |
| ASUSTek   | M5A97                       | [800aa16703](https://linux-hardware.org/?probe=800aa16703) | Dec 29, 2020 |
| HP        | 18EA                        | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| MSI       | B450M PRO-VDH MAX           | [803e6b6194](https://linux-hardware.org/?probe=803e6b6194) | Dec 25, 2020 |
| Biostar   | TA785G3 HD                  | [ed91ded9e9](https://linux-hardware.org/?probe=ed91ded9e9) | Dec 23, 2020 |
| ASRock    | Z87E-ITX                    | [861b40ea1d](https://linux-hardware.org/?probe=861b40ea1d) | Dec 21, 2020 |
| Dell      | 0GN723                      | [a952bf5fa6](https://linux-hardware.org/?probe=a952bf5fa6) | Dec 20, 2020 |
| ASUSTek   | PRIME H310M-E R2.0          | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Gigabyte  | H61M-DS2                    | [49263df7ee](https://linux-hardware.org/?probe=49263df7ee) | Dec 02, 2020 |
| HP        | 304Bh                       | [d30d065810](https://linux-hardware.org/?probe=d30d065810) | Nov 30, 2020 |
| Gigabyte  | Z77M-D3H                    | [47c75561ac](https://linux-hardware.org/?probe=47c75561ac) | Nov 21, 2020 |
| ASUSTek   | TUF Gaming X570-PLUS        | [10e9d31bdb](https://linux-hardware.org/?probe=10e9d31bdb) | Nov 20, 2020 |
| ASUSTek   | PRIME Z270-A                | [d47493ecae](https://linux-hardware.org/?probe=d47493ecae) | Nov 16, 2020 |
| Gigabyte  | H81M-S2H                    | [54fd3c5678](https://linux-hardware.org/?probe=54fd3c5678) | Nov 15, 2020 |
| ASUSTek   | PRIME A320I-K               | [6bfc04099a](https://linux-hardware.org/?probe=6bfc04099a) | Nov 06, 2020 |
| eMachines | EL1358G                     | [9aabea4465](https://linux-hardware.org/?probe=9aabea4465) | Oct 28, 2020 |
| MSI       | P35 Platinum                | [232a14759f](https://linux-hardware.org/?probe=232a14759f) | Oct 14, 2020 |
| MSI       | MAG B550M MORTAR            | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| HP        | 304Ah                       | [5143880fd9](https://linux-hardware.org/?probe=5143880fd9) | Oct 09, 2020 |
| ASUSTek   | PRIME A320M-K               | [55e4fca971](https://linux-hardware.org/?probe=55e4fca971) | Oct 08, 2020 |
| ASUSTek   | TUF B360-PLUS GAMING        | [1779589a19](https://linux-hardware.org/?probe=1779589a19) | Oct 08, 2020 |
| Gigabyte  | Z390 DESIGNARE-CF           | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| Acer      | WMCP78M                     | [2510b2bc49](https://linux-hardware.org/?probe=2510b2bc49) | Oct 02, 2020 |
| Intel     | DG41RQ AAE54511-204         | [651cef3c94](https://linux-hardware.org/?probe=651cef3c94) | Sep 29, 2020 |
| MSI       | FM2-A55M-E33                | [50d8cc3e2d](https://linux-hardware.org/?probe=50d8cc3e2d) | Sep 28, 2020 |
| ASUSTek   | Z170-DELUXE                 | [8eef95cd00](https://linux-hardware.org/?probe=8eef95cd00) | Sep 12, 2020 |
| MSI       | B450 TOMAHAWK MAX           | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Dell      | 0Y958C A00                  | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Gigabyte  | F2A88XN-WIFI                | [3b51467541](https://linux-hardware.org/?probe=3b51467541) | Sep 06, 2020 |
| Lenovo    | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| ASUSTek   | CM6330_CM6630_CM6730_CM6... | [78ec970ee1](https://linux-hardware.org/?probe=78ec970ee1) | Aug 29, 2020 |
| ASUSTek   | STRIX Z270H GAMING          | [ce54993f5d](https://linux-hardware.org/?probe=ce54993f5d) | Aug 29, 2020 |
| ASUSTek   | M5A78L-M PLUS/USB3          | [40f5f91c4e](https://linux-hardware.org/?probe=40f5f91c4e) | Aug 26, 2020 |
| HP        | 81B4                        | [6747078a67](https://linux-hardware.org/?probe=6747078a67) | Aug 24, 2020 |
| HP        | 81B4                        | [ff66e031e4](https://linux-hardware.org/?probe=ff66e031e4) | Aug 18, 2020 |
| ASUSTek   | SABERTOOTH Z87              | [86ff4005e2](https://linux-hardware.org/?probe=86ff4005e2) | Aug 15, 2020 |
| MSI       | B450M PRO-VDH MAX           | [ae51610784](https://linux-hardware.org/?probe=ae51610784) | Aug 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.4.0-48-generic       | 8        | 9.76%   |
| 5.4.0-65-generic       | 6        | 7.32%   |
| 5.4.0-58-generic       | 5        | 6.1%    |
| 5.4.0-54-generic       | 5        | 6.1%    |
| 5.4.0-42-generic       | 5        | 6.1%    |
| 5.4.0-47-generic       | 3        | 3.66%   |
| 5.4.0-90-generic       | 2        | 2.44%   |
| 5.4.0-80-generic       | 2        | 2.44%   |
| 5.4.0-71-generic       | 2        | 2.44%   |
| 5.4.0-70-generic       | 2        | 2.44%   |
| 5.4.0-60-generic       | 2        | 2.44%   |
| 5.4.0-56-generic       | 2        | 2.44%   |
| 5.4.0-53-generic       | 2        | 2.44%   |
| 5.4.0-52-generic       | 2        | 2.44%   |
| 5.4.0-124-generic      | 2        | 2.44%   |
| 4.15.0-161-generic     | 2        | 2.44%   |
| 4.15.0-128-generic     | 2        | 2.44%   |
| 4.15.0-112-generic     | 2        | 2.44%   |
| 5.4.0-99-generic       | 1        | 1.22%   |
| 5.4.0-94-generic       | 1        | 1.22%   |
| 5.4.0-91-generic       | 1        | 1.22%   |
| 5.4.0-84-generic       | 1        | 1.22%   |
| 5.4.0-77-generic       | 1        | 1.22%   |
| 5.4.0-74-generic       | 1        | 1.22%   |
| 5.4.0-73-generic       | 1        | 1.22%   |
| 5.4.0-67-generic       | 1        | 1.22%   |
| 5.4.0-66-generic       | 1        | 1.22%   |
| 5.4.0-62-generic       | 1        | 1.22%   |
| 5.4.0-49-generic       | 1        | 1.22%   |
| 5.4.0-45-generic       | 1        | 1.22%   |
| 5.4.0-139-generic      | 1        | 1.22%   |
| 5.4.0-137-generic      | 1        | 1.22%   |
| 5.4.0-135-generic      | 1        | 1.22%   |
| 5.4.0-113-generic      | 1        | 1.22%   |
| 5.4.0-109-generic      | 1        | 1.22%   |
| 5.4.0-107-generic      | 1        | 1.22%   |
| 5.4.0-100-generic      | 1        | 1.22%   |
| 5.17.0-051700-generic  | 1        | 1.22%   |
| 5.15.12-051512-generic | 1        | 1.22%   |
| 4.18.0-25-generic      | 1        | 1.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 60       | 85.71%  |
| 4.15.0  | 7        | 10%     |
| 5.17.0  | 1        | 1.43%   |
| 5.15.12 | 1        | 1.43%   |
| 4.18.0  | 1        | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 60       | 85.71%  |
| 4.15    | 7        | 10%     |
| 5.17    | 1        | 1.43%   |
| 5.15    | 1        | 1.43%   |
| 4.18    | 1        | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 70       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 67       | 94.37%  |
| Unknown  | 4        | 5.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 70       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 53       | 75.71%  |
| LightDM | 9        | 12.86%  |
| TDM     | 6        | 8.57%   |
| SDDM    | 1        | 1.43%   |
| GDM     | 1        | 1.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 24       | 33.8%   |
| en_GB   | 7        | 9.86%   |
| en_CA   | 5        | 7.04%   |
| es_ES   | 4        | 5.63%   |
| pt_BR   | 2        | 2.82%   |
| pl_PL   | 2        | 2.82%   |
| fr_FR   | 2        | 2.82%   |
| es_MX   | 2        | 2.82%   |
| de_DE   | 2        | 2.82%   |
| zh_TW   | 1        | 1.41%   |
| uk_UA   | 1        | 1.41%   |
| sv_SE   | 1        | 1.41%   |
| it_IT   | 1        | 1.41%   |
| hu_HU   | 1        | 1.41%   |
| hr_HR   | 1        | 1.41%   |
| gl_ES   | 1        | 1.41%   |
| fr_BE   | 1        | 1.41%   |
| es_SV   | 1        | 1.41%   |
| es_PA   | 1        | 1.41%   |
| es_EC   | 1        | 1.41%   |
| en_ZA   | 1        | 1.41%   |
| en_PH   | 1        | 1.41%   |
| en_IN   | 1        | 1.41%   |
| en_IE   | 1        | 1.41%   |
| en_HK   | 1        | 1.41%   |
| en_AU   | 1        | 1.41%   |
| el_GR   | 1        | 1.41%   |
| de_AT   | 1        | 1.41%   |
| cs_CZ   | 1        | 1.41%   |
| Unknown | 1        | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 43       | 60.56%  |
| EFI  | 28       | 39.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 67       | 94.37%  |
| Btrfs | 3        | 4.23%   |
| Xfs   | 1        | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 58       | 82.86%  |
| GPT     | 8        | 11.43%  |
| MBR     | 4        | 5.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 94.29%  |
| Yes       | 4        | 5.71%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 78.57%  |
| Yes       | 15       | 21.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 28.57%  |
| Gigabyte Technology | 14       | 20%     |
| MSI                 | 7        | 10%     |
| Hewlett-Packard     | 6        | 8.57%   |
| Dell                | 5        | 7.14%   |
| ASRock              | 4        | 5.71%   |
| Lenovo              | 3        | 4.29%   |
| Biostar             | 3        | 4.29%   |
| Intel               | 2        | 2.86%   |
| Acer                | 2        | 2.86%   |
| Foxconn             | 1        | 1.43%   |
| EVGA                | 1        | 1.43%   |
| eMachines           | 1        | 1.43%   |
| Apple               | 1        | 1.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 3        | 4.29%   |
| ASUS P8H61-M LX3 R2.0           | 2        | 2.86%   |
| MSI P35 Platinum(MS-7345)       | 1        | 1.43%   |
| MSI MS-7C94                     | 1        | 1.43%   |
| MSI MS-7C02                     | 1        | 1.43%   |
| MSI MS-7A38                     | 1        | 1.43%   |
| MSI MS-7A34                     | 1        | 1.43%   |
| MSI MS-7788                     | 1        | 1.43%   |
| MSI MS-7721                     | 1        | 1.43%   |
| Lenovo ThinkCentre M92p 3227D13 | 1        | 1.43%   |
| Lenovo ThinkCentre M92p 3212DF9 | 1        | 1.43%   |
| Lenovo ThinkCentre M71e 3129C3G | 1        | 1.43%   |
| Intel DG41RQ AAE54511-204       | 1        | 1.43%   |
| Intel DG35EC AAE29266-205       | 1        | 1.43%   |
| HP Slim Desktop 290-p0xxx       | 1        | 1.43%   |
| HP ProOne 400 G1 AiO            | 1        | 1.43%   |
| HP ProDesk 600 G1 SFF           | 1        | 1.43%   |
| HP Compaq 8100 Elite SFF PC     | 1        | 1.43%   |
| HP Compaq 8100 Elite CMT PC     | 1        | 1.43%   |
| HP 260-p128ns                   | 1        | 1.43%   |
| Gigabyte Z77M-D3H               | 1        | 1.43%   |
| Gigabyte Z77-DS3H               | 1        | 1.43%   |
| Gigabyte Z68P-DS3               | 1        | 1.43%   |
| Gigabyte Z390 DESIGNARE         | 1        | 1.43%   |
| Gigabyte H81M-S2H               | 1        | 1.43%   |
| Gigabyte H81M-DS2               | 1        | 1.43%   |
| Gigabyte H67A-USB3-B3           | 1        | 1.43%   |
| Gigabyte H61M-S2PV              | 1        | 1.43%   |
| Gigabyte H61M-DS2               | 1        | 1.43%   |
| Gigabyte GA-MA78GM-S2H          | 1        | 1.43%   |
| Gigabyte GA-880GMA-UD2H         | 1        | 1.43%   |
| Gigabyte F2A88XN-WIFI           | 1        | 1.43%   |
| Gigabyte AB350M-DS3H V2         | 1        | 1.43%   |
| Gigabyte A320M-S2H V2           | 1        | 1.43%   |
| Foxconn p6610f                  | 1        | 1.43%   |
| EVGA 132-CK-NF79                | 1        | 1.43%   |
| eMachines EL1358G               | 1        | 1.43%   |
| Dell Vostro 400                 | 1        | 1.43%   |
| Dell Precision T1600            | 1        | 1.43%   |
| Dell OptiPlex 960               | 1        | 1.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 5        | 7.14%   |
| Lenovo ThinkCentre      | 3        | 4.29%   |
| Dell OptiPlex           | 3        | 4.29%   |
| ASUS All                | 3        | 4.29%   |
| HP Compaq               | 2        | 2.86%   |
| ASUS TUF                | 2        | 2.86%   |
| ASUS ROG                | 2        | 2.86%   |
| ASUS P8H61-M            | 2        | 2.86%   |
| Acer Aspire             | 2        | 2.86%   |
| MSI P35                 | 1        | 1.43%   |
| MSI MS-7C94             | 1        | 1.43%   |
| MSI MS-7C02             | 1        | 1.43%   |
| MSI MS-7A38             | 1        | 1.43%   |
| MSI MS-7A34             | 1        | 1.43%   |
| MSI MS-7788             | 1        | 1.43%   |
| MSI MS-7721             | 1        | 1.43%   |
| Intel DG41RQ            | 1        | 1.43%   |
| Intel DG35EC            | 1        | 1.43%   |
| HP Slim                 | 1        | 1.43%   |
| HP ProOne               | 1        | 1.43%   |
| HP ProDesk              | 1        | 1.43%   |
| HP 260-p128ns           | 1        | 1.43%   |
| Gigabyte Z77M-D3H       | 1        | 1.43%   |
| Gigabyte Z77-DS3H       | 1        | 1.43%   |
| Gigabyte Z68P-DS3       | 1        | 1.43%   |
| Gigabyte Z390           | 1        | 1.43%   |
| Gigabyte H81M-S2H       | 1        | 1.43%   |
| Gigabyte H81M-DS2       | 1        | 1.43%   |
| Gigabyte H67A-USB3-B3   | 1        | 1.43%   |
| Gigabyte H61M-S2PV      | 1        | 1.43%   |
| Gigabyte H61M-DS2       | 1        | 1.43%   |
| Gigabyte GA-MA78GM-S2H  | 1        | 1.43%   |
| Gigabyte GA-880GMA-UD2H | 1        | 1.43%   |
| Gigabyte F2A88XN-WIFI   | 1        | 1.43%   |
| Gigabyte AB350M-DS3H    | 1        | 1.43%   |
| Gigabyte A320M-S2H      | 1        | 1.43%   |
| Foxconn p6610f          | 1        | 1.43%   |
| EVGA 132-CK-NF79        | 1        | 1.43%   |
| eMachines EL1358G       | 1        | 1.43%   |
| Dell Vostro             | 1        | 1.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 13       | 18.57%  |
| 2011 | 8        | 11.43%  |
| 2019 | 7        | 10%     |
| 2012 | 7        | 10%     |
| 2008 | 7        | 10%     |
| 2018 | 6        | 8.57%   |
| 2009 | 6        | 8.57%   |
| 2017 | 5        | 7.14%   |
| 2016 | 4        | 5.71%   |
| 2014 | 2        | 2.86%   |
| 2010 | 2        | 2.86%   |
| 2020 | 1        | 1.43%   |
| 2015 | 1        | 1.43%   |
| 2007 | 1        | 1.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 70       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 70       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 70       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 24       | 34.29%  |
| 4.01-8.0    | 12       | 17.14%  |
| 3.01-4.0    | 10       | 14.29%  |
| 16.01-24.0  | 10       | 14.29%  |
| 32.01-64.0  | 7        | 10%     |
| 2.01-3.0    | 3        | 4.29%   |
| 1.01-2.0    | 2        | 2.86%   |
| 24.01-32.0  | 1        | 1.43%   |
| 64.01-256.0 | 1        | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 30       | 37.97%  |
| 2.01-3.0  | 18       | 22.78%  |
| 4.01-8.0  | 16       | 20.25%  |
| 3.01-4.0  | 13       | 16.46%  |
| 8.01-16.0 | 1        | 1.27%   |
| 0.51-1.0  | 1        | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 45.21%  |
| 2      | 22       | 30.14%  |
| 3      | 6        | 8.22%   |
| 4      | 4        | 5.48%   |
| 5      | 3        | 4.11%   |
| 7      | 2        | 2.74%   |
| 6      | 2        | 2.74%   |
| 0      | 1        | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 52.05%  |
| Yes       | 35       | 47.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 68       | 97.14%  |
| No        | 2        | 2.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 37       | 52.11%  |
| No        | 34       | 47.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 67.14%  |
| Yes       | 23       | 32.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 6        | 8.57%   |
| UK           | 6        | 8.57%   |
| Canada       | 6        | 8.57%   |
| Brazil       | 6        | 8.57%   |
| Spain        | 4        | 5.71%   |
| Poland       | 4        | 5.71%   |
| Mexico       | 3        | 4.29%   |
| India        | 2        | 2.86%   |
| Hong Kong    | 2        | 2.86%   |
| Germany      | 2        | 2.86%   |
| France       | 2        | 2.86%   |
| Venezuela    | 1        | 1.43%   |
| Ukraine      | 1        | 1.43%   |
| Thailand     | 1        | 1.43%   |
| Sweden       | 1        | 1.43%   |
| Sint Maarten | 1        | 1.43%   |
| Russia       | 1        | 1.43%   |
| Philippines  | 1        | 1.43%   |
| Panama       | 1        | 1.43%   |
| Netherlands  | 1        | 1.43%   |
| Malaysia     | 1        | 1.43%   |
| Luxembourg   | 1        | 1.43%   |
| Kosovo       | 1        | 1.43%   |
| Italy        | 1        | 1.43%   |
| Ireland      | 1        | 1.43%   |
| Indonesia    | 1        | 1.43%   |
| Hungary      | 1        | 1.43%   |
| Greece       | 1        | 1.43%   |
| Eswatini     | 1        | 1.43%   |
| El Salvador  | 1        | 1.43%   |
| Ecuador      | 1        | 1.43%   |
| Czechia      | 1        | 1.43%   |
| Croatia      | 1        | 1.43%   |
| Costa Rica   | 1        | 1.43%   |
| Belgium      | 1        | 1.43%   |
| Austria      | 1        | 1.43%   |
| Australia    | 1        | 1.43%   |
| Argentina    | 1        | 1.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Fortaleza               | 3        | 4.17%   |
| Warsaw                  | 2        | 2.78%   |
| Berlin                  | 2        | 2.78%   |
| Wroclaw                 | 1        | 1.39%   |
| Vigo                    | 1        | 1.39%   |
| Tseung Kwan O           | 1        | 1.39%   |
| Toronto                 | 1        | 1.39%   |
| Theodore                | 1        | 1.39%   |
| Talavera de la Reina    | 1        | 1.39%   |
| Sao José dos Campos    | 1        | 1.39%   |
| Santa Brigida           | 1        | 1.39%   |
| Sant Andreu de la Barca | 1        | 1.39%   |
| San Salvador            | 1        | 1.39%   |
| Samobor                 | 1        | 1.39%   |
| Rome                    | 1        | 1.39%   |
| Rio de Janeiro          | 1        | 1.39%   |
| Quito                   | 1        | 1.39%   |
| Quezon City             | 1        | 1.39%   |
| Prizren                 | 1        | 1.39%   |
| Philipsburg             | 1        | 1.39%   |
| Pécs                   | 1        | 1.39%   |
| Panchkula               | 1        | 1.39%   |
| Panama City             | 1        | 1.39%   |
| Novosibirsk             | 1        | 1.39%   |
| Mulhouse                | 1        | 1.39%   |
| Morelia                 | 1        | 1.39%   |
| Montreal                | 1        | 1.39%   |
| Mexico City             | 1        | 1.39%   |
| Mbabane                 | 1        | 1.39%   |
| Luxembourg              | 1        | 1.39%   |
| Lund                    | 1        | 1.39%   |
| Locust Grove            | 1        | 1.39%   |
| Lamia                   | 1        | 1.39%   |
| Kentville               | 1        | 1.39%   |
| Juazeiro                | 1        | 1.39%   |
| Jepara                  | 1        | 1.39%   |
| Isle of Arran           | 1        | 1.39%   |
| Innsbruck               | 1        | 1.39%   |
| Hua Hin                 | 1        | 1.39%   |
| Hook                    | 1        | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 39     | 24.58%  |
| WDC                 | 19       | 28     | 16.1%   |
| Samsung Electronics | 16       | 28     | 13.56%  |
| Kingston            | 10       | 20     | 8.47%   |
| Crucial             | 9        | 11     | 7.63%   |
| Toshiba             | 6        | 15     | 5.08%   |
| SanDisk             | 6        | 6      | 5.08%   |
| Hitachi             | 3        | 3      | 2.54%   |
| HGST                | 3        | 4      | 2.54%   |
| Unknown             | 2        | 2      | 1.69%   |
| OCZ                 | 2        | 3      | 1.69%   |
| A-DATA Technology   | 2        | 3      | 1.69%   |
| WDC WDS             | 1        | 1      | 0.85%   |
| Transcend           | 1        | 2      | 0.85%   |
| PNY                 | 1        | 1      | 0.85%   |
| Patriot             | 1        | 1      | 0.85%   |
| OWC                 | 1        | 1      | 0.85%   |
| KingSpec            | 1        | 1      | 0.85%   |
| KingFast            | 1        | 1      | 0.85%   |
| Intel               | 1        | 1      | 0.85%   |
| GOODRAM             | 1        | 2      | 0.85%   |
| GeIL                | 1        | 1      | 0.85%   |
| China               | 1        | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB   | 4        | 2.9%    |
| Kingston SA400S37240G 240GB SSD   | 4        | 2.9%    |
| Toshiba DT01ACA100 1TB            | 3        | 2.17%   |
| SanDisk SSD PLUS 480GB            | 3        | 2.17%   |
| Samsung SSD 850 EVO 500GB         | 3        | 2.17%   |
| Samsung SSD 850 EVO 250GB         | 3        | 2.17%   |
| Kingston SV300S37A120G 120GB SSD  | 3        | 2.17%   |
| Crucial CT120BX300SSD1 120GB      | 3        | 2.17%   |
| Seagate ST3500418AS 500GB         | 2        | 1.45%   |
| Seagate ST2000DM008-2FR102 2TB    | 2        | 1.45%   |
| Seagate ST1000DM003-1ER162 1TB    | 2        | 1.45%   |
| Samsung SSD 970 EVO 500GB         | 2        | 1.45%   |
| Samsung SSD 840 EVO 500GB         | 2        | 1.45%   |
| Kingston SA400S37120G 120GB SSD   | 2        | 1.45%   |
| Crucial CT120BX500SSD1 120GB      | 2        | 1.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1        | 0.72%   |
| WDC WDS250G2B0B-00YS70 250GB SSD  | 1        | 0.72%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD  | 1        | 0.72%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 0.72%   |
| WDC WDS100T1R0B-68A4Z0 1TB SSD    | 1        | 0.72%   |
| WDC WDS 500G2B0B-00YS70 500GB SSD | 1        | 0.72%   |
| WDC WD6003FZBX-00K5WB0 6TB        | 1        | 0.72%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 0.72%   |
| WDC WD5000AAKX-221CA1 500GB       | 1        | 0.72%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 0.72%   |
| WDC WD5000AAKS-00M9A0 500GB       | 1        | 0.72%   |
| WDC WD5000AAKS-00A7B2 500GB       | 1        | 0.72%   |
| WDC WD400BB-75DEA0 40GB           | 1        | 0.72%   |
| WDC WD3000GLFS-01F8U0 304GB       | 1        | 0.72%   |
| WDC WD20EZRX-22D8PB0 2TB          | 1        | 0.72%   |
| WDC WD20EZBX-00AYRA0 2TB          | 1        | 0.72%   |
| WDC WD20EARS-00MVWB0 2TB          | 1        | 0.72%   |
| WDC WD2003FZEX-00Z4SA0 2TB        | 1        | 0.72%   |
| WDC WD2003FZEX-00SRLA0 2TB        | 1        | 0.72%   |
| WDC WD10JPVT-22A1YT0 1TB          | 1        | 0.72%   |
| WDC WD10EZEX-75M2NA0 1TB          | 1        | 0.72%   |
| WDC WD10EZEX-08M2NA0 1TB          | 1        | 0.72%   |
| WDC WD10EURX-63UY4Y0 1TB          | 1        | 0.72%   |
| WDC WD10EALX-009BA0 1TB           | 1        | 0.72%   |
| Unknown SD/MMC/MS PRO 64GB        | 1        | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 39     | 49.15%  |
| WDC                 | 14       | 23     | 23.73%  |
| Toshiba             | 6        | 15     | 10.17%  |
| Samsung Electronics | 3        | 3      | 5.08%   |
| Hitachi             | 3        | 3      | 5.08%   |
| HGST                | 3        | 4      | 5.08%   |
| Unknown             | 1        | 1      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 19     | 22.81%  |
| Kingston            | 10       | 14     | 17.54%  |
| Crucial             | 9        | 11     | 15.79%  |
| SanDisk             | 6        | 6      | 10.53%  |
| WDC                 | 5        | 5      | 8.77%   |
| OCZ                 | 2        | 3      | 3.51%   |
| A-DATA Technology   | 2        | 3      | 3.51%   |
| WDC WDS             | 1        | 1      | 1.75%   |
| Transcend           | 1        | 2      | 1.75%   |
| PNY                 | 1        | 1      | 1.75%   |
| Patriot             | 1        | 1      | 1.75%   |
| OWC                 | 1        | 1      | 1.75%   |
| KingSpec            | 1        | 1      | 1.75%   |
| Intel               | 1        | 1      | 1.75%   |
| GOODRAM             | 1        | 2      | 1.75%   |
| GeIL                | 1        | 1      | 1.75%   |
| China               | 1        | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 46       | 88     | 47.92%  |
| SSD     | 42       | 73     | 43.75%  |
| NVMe    | 7        | 13     | 7.29%   |
| Unknown | 1        | 1      | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 67       | 157    | 84.81%  |
| NVMe | 7        | 13     | 8.86%   |
| SAS  | 5        | 5      | 6.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 57       | 106    | 63.33%  |
| 0.51-1.0   | 20       | 32     | 22.22%  |
| 1.01-2.0   | 7        | 13     | 7.78%   |
| 2.01-3.0   | 3        | 7      | 3.33%   |
| 4.01-10.0  | 3        | 3      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 22       | 29.73%  |
| 251-500        | 20       | 27.03%  |
| 501-1000       | 12       | 16.22%  |
| 1001-2000      | 5        | 6.76%   |
| More than 3000 | 4        | 5.41%   |
| 2001-3000      | 4        | 5.41%   |
| 51-100         | 4        | 5.41%   |
| 21-50          | 3        | 4.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 17       | 22.37%  |
| 51-100         | 15       | 19.74%  |
| 21-50          | 14       | 18.42%  |
| 101-250        | 12       | 15.79%  |
| 501-1000       | 7        | 9.21%   |
| 251-500        | 4        | 5.26%   |
| More than 3000 | 3        | 3.95%   |
| 1001-2000      | 3        | 3.95%   |
| 2001-3000      | 1        | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB    | 1        | 1      | 12.5%   |
| WDC WD5000AAKX-221CA1 500GB     | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 12.5%   |
| Seagate ST3320613AS 320GB       | 1        | 1      | 12.5%   |
| Seagate ST2000DM006-2DM164 2TB  | 1        | 1      | 12.5%   |
| Samsung Electronics HD204UI 2TB | 1        | 1      | 12.5%   |
| Kingston SA400S37120G 120GB SSD | 1        | 1      | 12.5%   |
| HGST HUS724030ALA640 3TB        | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 37.5%   |
| WDC                 | 2        | 2      | 25%     |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Kingston            | 1        | 1      | 12.5%   |
| HGST                | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 42.86%  |
| WDC                 | 2        | 2      | 28.57%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| HGST                | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 7      | 87.5%   |
| SSD  | 1        | 1      | 12.5%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 59       | 144    | 76.62%  |
| Works    | 10       | 23     | 12.99%  |
| Malfunc  | 8        | 8      | 10.39%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 47       | 54.65%  |
| AMD                         | 20       | 23.26%  |
| Samsung Electronics         | 5        | 5.81%   |
| Nvidia                      | 3        | 3.49%   |
| JMicron Technology          | 3        | 3.49%   |
| ASMedia Technology          | 3        | 3.49%   |
| Kingston Technology Company | 2        | 2.33%   |
| Silicon Image               | 1        | 1.16%   |
| Marvell Technology Group    | 1        | 1.16%   |
| ADATA Technology            | 1        | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12       | 10.62%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 7.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 6.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 4.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 3.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 3.54%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 3.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.65%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 2.65%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 1.77%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.77%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.77%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.77%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.77%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.77%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.77%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 1        | 0.88%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.88%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.88%   |
| Nvidia MCP78S [GeForce 8200] AHCI Controller                                            | 1        | 0.88%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.88%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.88%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.88%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 0.88%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.88%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.88%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 0.88%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 56       | 65.88%  |
| IDE  | 19       | 22.35%  |
| NVMe | 7        | 8.24%   |
| RAID | 3        | 3.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 48       | 68.57%  |
| AMD    | 22       | 31.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3330S CPU @ 2.70GHz           | 3        | 4.29%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 2.86%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 2.86%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 2.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 2.86%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 2.86%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 2.86%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 2.86%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 2.86%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 2.86%   |
| AMD FX-6100 Six-Core Processor              | 2        | 2.86%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 1.43%   |
| Intel Xeon CPU E31225 @ 3.10GHz             | 1        | 1.43%   |
| Intel Xeon CPU 5160 @ 3.00GHz               | 1        | 1.43%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 1.43%   |
| Intel Core i7-9700KF CPU @ 3.60GHz          | 1        | 1.43%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.43%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.43%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.43%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.43%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.43%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1        | 1.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.43%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 1.43%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1        | 1.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.43%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 1.43%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.43%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 1.43%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.43%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.43%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1        | 1.43%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.43%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.43%   |
| Intel Core i3-4160T CPU @ 3.10GHz           | 1        | 1.43%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.43%   |
| Intel Core i3-4130T CPU @ 2.90GHz           | 1        | 1.43%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.43%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 28.57%  |
| Intel Core i7           | 8        | 11.43%  |
| AMD Ryzen 5             | 7        | 10%     |
| Intel Core i3           | 6        | 8.57%   |
| Intel Core 2 Quad       | 4        | 5.71%   |
| Intel Xeon              | 3        | 4.29%   |
| AMD Ryzen 3             | 3        | 4.29%   |
| AMD Phenom II X4        | 3        | 4.29%   |
| Intel Pentium Dual-Core | 2        | 2.86%   |
| Intel Core 2 Duo        | 2        | 2.86%   |
| Intel Celeron           | 2        | 2.86%   |
| AMD FX                  | 2        | 2.86%   |
| AMD A8                  | 2        | 2.86%   |
| Intel Pentium           | 1        | 1.43%   |
| AMD Ryzen 9             | 1        | 1.43%   |
| AMD Phenom              | 1        | 1.43%   |
| AMD Athlon II X4        | 1        | 1.43%   |
| AMD Athlon II X3        | 1        | 1.43%   |
| AMD A4                  | 1        | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 44       | 62.86%  |
| 2      | 12       | 17.14%  |
| 6      | 5        | 7.14%   |
| 3      | 5        | 7.14%   |
| 8      | 2        | 2.86%   |
| 12     | 1        | 1.43%   |
| 1      | 1        | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 69       | 98.57%  |
| 2      | 1        | 1.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 65.71%  |
| 2      | 24       | 34.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 70       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 8        | 11.43%  |
| 0x206a7    | 8        | 11.43%  |
| 0x306a9    | 7        | 10%     |
| 0x906eb    | 4        | 5.71%   |
| 0x1067a    | 4        | 5.71%   |
| Unknown    | 4        | 5.71%   |
| 0x08108109 | 3        | 4.29%   |
| 0x906e9    | 2        | 2.86%   |
| 0x506e3    | 2        | 2.86%   |
| 0x10676    | 2        | 2.86%   |
| 0x08701021 | 2        | 2.86%   |
| 0x08001129 | 2        | 2.86%   |
| 0x0600063e | 2        | 2.86%   |
| 0x010000db | 2        | 2.86%   |
| 0x010000c8 | 2        | 2.86%   |
| 0x906ed    | 1        | 1.43%   |
| 0x906ec    | 1        | 1.43%   |
| 0x906ea    | 1        | 1.43%   |
| 0x6fb      | 1        | 1.43%   |
| 0x6f6      | 1        | 1.43%   |
| 0x30673    | 1        | 1.43%   |
| 0x20652    | 1        | 1.43%   |
| 0x106e5    | 1        | 1.43%   |
| 0x08701013 | 1        | 1.43%   |
| 0x08101016 | 1        | 1.43%   |
| 0x0810100b | 1        | 1.43%   |
| 0x0800820d | 1        | 1.43%   |
| 0x0600611a | 1        | 1.43%   |
| 0x06003106 | 1        | 1.43%   |
| 0x06001119 | 1        | 1.43%   |
| 0x01000083 | 1        | 1.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| SandyBridge | 9        | 12.86%  |
| KabyLake    | 9        | 12.86%  |
| Haswell     | 9        | 12.86%  |
| IvyBridge   | 7        | 10%     |
| Penryn      | 6        | 8.57%   |
| K10         | 6        | 8.57%   |
| Zen+        | 4        | 5.71%   |
| Zen         | 4        | 5.71%   |
| Zen 2       | 3        | 4.29%   |
| Core        | 3        | 4.29%   |
| Skylake     | 2        | 2.86%   |
| Bulldozer   | 2        | 2.86%   |
| Westmere    | 1        | 1.43%   |
| Steamroller | 1        | 1.43%   |
| Silvermont  | 1        | 1.43%   |
| Piledriver  | 1        | 1.43%   |
| Nehalem     | 1        | 1.43%   |
| Excavator   | 1        | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 27       | 36%     |
| Nvidia | 25       | 33.33%  |
| Intel  | 23       | 30.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 6.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 6.41%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 5.13%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 3.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 3.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.56%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 2.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 2.56%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.28%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.28%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.28%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 1.28%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 1.28%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.28%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.28%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.28%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.28%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.28%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.28%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.28%   |
| Nvidia G98 [GeForce 9300 GE]                                                | 1        | 1.28%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.28%   |
| Nvidia G84GL [Quadro FX 570]                                                | 1        | 1.28%   |
| Nvidia C77 [GeForce 8200]                                                   | 1        | 1.28%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.28%   |
| Intel HD Graphics 530                                                       | 1        | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.28%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.28%   |
| Intel 82G35 Express Integrated Graphics Controller                          | 1        | 1.28%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 1        | 1.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.28%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 26       | 37.14%  |
| 1 x Nvidia     | 22       | 31.43%  |
| 1 x Intel      | 18       | 25.71%  |
| Intel + Nvidia | 2        | 2.86%   |
| 2 x Nvidia     | 1        | 1.43%   |
| 2 x AMD        | 1        | 1.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 47       | 67.14%  |
| Proprietary | 21       | 30%     |
| Unknown     | 2        | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 21       | 30%     |
| Unknown    | 17       | 24.29%  |
| 0.01-0.5   | 10       | 14.29%  |
| 7.01-8.0   | 7        | 10%     |
| 0.51-1.0   | 7        | 10%     |
| 3.01-4.0   | 6        | 8.57%   |
| 5.01-6.0   | 2        | 2.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 11       | 14.86%  |
| Samsung Electronics  | 9        | 12.16%  |
| Goldstar             | 9        | 12.16%  |
| Acer                 | 6        | 8.11%   |
| AOC                  | 5        | 6.76%   |
| Ancor Communications | 5        | 6.76%   |
| ViewSonic            | 3        | 4.05%   |
| LG Electronics       | 3        | 4.05%   |
| Hewlett-Packard      | 3        | 4.05%   |
| Unknown              | 2        | 2.7%    |
| BenQ                 | 2        | 2.7%    |
| Apple                | 2        | 2.7%    |
| ___                  | 1        | 1.35%   |
| Vizio                | 1        | 1.35%   |
| Vestel               | 1        | 1.35%   |
| SAC                  | 1        | 1.35%   |
| Ruijiang             | 1        | 1.35%   |
| Philips              | 1        | 1.35%   |
| PDA                  | 1        | 1.35%   |
| PANDA                | 1        | 1.35%   |
| KIV                  | 1        | 1.35%   |
| Iiyama               | 1        | 1.35%   |
| HPN                  | 1        | 1.35%   |
| HKC                  | 1        | 1.35%   |
| Haier                | 1        | 1.35%   |
| Fujitsu Siemens      | 1        | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 3        | 3.85%   |
| ___ LCDTV16 ___0101 1360x768                                            | 1        | 1.28%   |
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                     | 1        | 1.28%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch           | 1        | 1.28%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 1.28%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch            | 1        | 1.28%   |
| Vestel LCD Monitor 43UHD_LCD_TV 3840x2160                               | 1        | 1.28%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                     | 1        | 1.28%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 1.28%   |
| Samsung Electronics T27C370 SAM0ADE 1920x1080 598x336mm 27.0-inch       | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM0595 2048x1152 510x287mm 23.0-inch    | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch     | 1        | 1.28%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch     | 1        | 1.28%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch    | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 1.28%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 1.28%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                       | 1        | 1.28%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                   | 1        | 1.28%   |
| Ruijiang HDMI RJT003A 1920x1080 1280x720mm 57.8-inch                    | 1        | 1.28%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 1        | 1.28%   |
| PDA P24FA2 PDA2380 1920x1080 409x230mm 18.5-inch                        | 1        | 1.28%   |
| PANDA P24FA2 PDA2380 1920x1080 409x230mm 18.5-inch                      | 1        | 1.28%   |
| LG Electronics LCD Monitor W2252 3600x1080                              | 1        | 1.28%   |
| LG Electronics LCD Monitor M227WAP 1920x1080                            | 1        | 1.28%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                       | 1        | 1.28%   |
| KIV Kivi TV KIV0030 1920x1080 708x398mm 32.0-inch                       | 1        | 1.28%   |
| Iiyama PL3270Q IVM7608 2560x1440 698x393mm 31.5-inch                    | 1        | 1.28%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                    | 1        | 1.28%   |
| HPN LCD Monitor HP 27fh 1920x1080                                       | 1        | 1.28%   |
| HKC LCD Monitor TV 1920x1080                                            | 1        | 1.28%   |
| Hewlett-Packard 27xw HWP3197 1920x1080 598x336mm 27.0-inch              | 1        | 1.28%   |
| Hewlett-Packard 27er HWP3325 1920x1080 598x336mm 27.0-inch              | 1        | 1.28%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch              | 1        | 1.28%   |
| Haier SMART TV HRE0030 3840x2160 708x398mm 32.0-inch                    | 1        | 1.28%   |
| Goldstar M228WA GSM563D 1680x1050 434x270mm 20.1-inch                   | 1        | 1.28%   |
| Goldstar L1750SQ GSM43E8 1280x1024 338x270mm 17.0-inch                  | 1        | 1.28%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 1        | 1.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1        | 1.28%   |
| Goldstar E2250 GSM578D 1920x1080 477x268mm 21.5-inch                    | 1        | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 42.86%  |
| 1600x900 (HD+)     | 7        | 10%     |
| 3840x2160 (4K)     | 4        | 5.71%   |
| 2560x1440 (QHD)    | 4        | 5.71%   |
| 1680x1050 (WSXGA+) | 4        | 5.71%   |
| 1366x768 (WXGA)    | 3        | 4.29%   |
| 1280x1024 (SXGA)   | 3        | 4.29%   |
| Unknown            | 3        | 4.29%   |
| 3440x1440          | 2        | 2.86%   |
| 2560x1600          | 2        | 2.86%   |
| 5120x1440          | 1        | 1.43%   |
| 3968x1280          | 1        | 1.43%   |
| 3600x1080          | 1        | 1.43%   |
| 2288x1287          | 1        | 1.43%   |
| 2048x1152          | 1        | 1.43%   |
| 1600x1200          | 1        | 1.43%   |
| 1440x900 (WXGA+)   | 1        | 1.43%   |
| 1024x768 (XGA)     | 1        | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 22.97%  |
| 27      | 7        | 9.46%   |
| 21      | 7        | 9.46%   |
| 20      | 7        | 9.46%   |
| 19      | 6        | 8.11%   |
| 24      | 5        | 6.76%   |
| 23      | 5        | 6.76%   |
| 18      | 3        | 4.05%   |
| 84      | 2        | 2.7%    |
| 29      | 2        | 2.7%    |
| 22      | 2        | 2.7%    |
| 17      | 2        | 2.7%    |
| 72      | 1        | 1.35%   |
| 57      | 1        | 1.35%   |
| 38      | 1        | 1.35%   |
| 36      | 1        | 1.35%   |
| 34      | 1        | 1.35%   |
| 33      | 1        | 1.35%   |
| 32      | 1        | 1.35%   |
| 31      | 1        | 1.35%   |
| 15      | 1        | 1.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 21       | 30.43%  |
| Unknown     | 17       | 24.64%  |
| 501-600     | 14       | 20.29%  |
| 701-800     | 4        | 5.8%    |
| 601-700     | 3        | 4.35%   |
| 301-350     | 3        | 4.35%   |
| 1501-2000   | 3        | 4.35%   |
| 351-400     | 2        | 2.9%    |
| 801-900     | 1        | 1.45%   |
| 1001-1500   | 1        | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 34       | 53.97%  |
| Unknown | 16       | 25.4%   |
| 16/10   | 5        | 7.94%   |
| 5/4     | 4        | 6.35%   |
| 4/3     | 2        | 3.17%   |
| 3/2     | 1        | 1.59%   |
| 21/9    | 1        | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 17       | 24.29%  |
| 201-250        | 16       | 22.86%  |
| 151-200        | 11       | 15.71%  |
| 301-350        | 7        | 10%     |
| 351-500        | 6        | 8.57%   |
| 141-150        | 5        | 7.14%   |
| More than 1000 | 4        | 5.71%   |
| 501-1000       | 2        | 2.86%   |
| 251-300        | 1        | 1.43%   |
| 101-110        | 1        | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 32       | 50%     |
| Unknown | 17       | 26.56%  |
| 101-120 | 12       | 18.75%  |
| 1-50    | 2        | 3.13%   |
| 121-160 | 1        | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 52       | 73.24%  |
| 2     | 12       | 16.9%   |
| 3     | 4        | 5.63%   |
| 0     | 3        | 4.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 46       | 45.1%   |
| Intel                           | 26       | 25.49%  |
| Qualcomm Atheros                | 8        | 7.84%   |
| Broadcom                        | 6        | 5.88%   |
| TP-Link                         | 4        | 3.92%   |
| Nvidia                          | 3        | 2.94%   |
| VIA Technologies                | 1        | 0.98%   |
| Samsung Electronics             | 1        | 0.98%   |
| Qualcomm Atheros Communications | 1        | 0.98%   |
| Microsoft                       | 1        | 0.98%   |
| Huawei Technologies             | 1        | 0.98%   |
| D-Link System                   | 1        | 0.98%   |
| D-Link                          | 1        | 0.98%   |
| BUFFALO                         | 1        | 0.98%   |
| Broadcom Limited                | 1        | 0.98%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 37       | 32.46%  |
| Intel I211 Gigabit Network Connection                                  | 4        | 3.51%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 3.51%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 3        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3        | 2.63%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 2.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2        | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2        | 1.75%   |
| Realtek 802.11ac NIC                                                   | 2        | 1.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 1.75%   |
| Intel Wireless-AC 9260                                                 | 2        | 1.75%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 1.75%   |
| Intel 82578DM Gigabit Network Connection                               | 2        | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 2        | 1.75%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1        | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1        | 0.88%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                        | 1        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 0.88%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 0.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 0.88%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 1        | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 0.88%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 1        | 0.88%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 0.88%   |
| Nvidia MCP77 Ethernet                                                  | 1        | 0.88%   |
| Nvidia MCP61 Ethernet                                                  | 1        | 0.88%   |
| Nvidia MCP55 Ethernet                                                  | 1        | 0.88%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 1        | 0.88%   |
| Intel Wireless 8260                                                    | 1        | 0.88%   |
| Intel Wireless 7260                                                    | 1        | 0.88%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 28.21%  |
| Intel                           | 7        | 17.95%  |
| Qualcomm Atheros                | 6        | 15.38%  |
| Broadcom                        | 5        | 12.82%  |
| TP-Link                         | 4        | 10.26%  |
| Qualcomm Atheros Communications | 1        | 2.56%   |
| Microsoft                       | 1        | 2.56%   |
| D-Link System                   | 1        | 2.56%   |
| D-Link                          | 1        | 2.56%   |
| BUFFALO                         | 1        | 2.56%   |
| Broadcom Limited                | 1        | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                               | 3        | 7.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 3        | 7.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 5%      |
| Realtek 802.11ac NIC                                                              | 2        | 5%      |
| Intel Wireless-AC 9260                                                            | 2        | 5%      |
| Intel Wi-Fi 6 AX200                                                               | 2        | 5%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 2        | 5%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 1        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 2.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                           | 1        | 2.5%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                   | 1        | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 1        | 2.5%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 2.5%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 1        | 2.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 1        | 2.5%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                         | 1        | 2.5%    |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 1        | 2.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 1        | 2.5%    |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]            | 1        | 2.5%    |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 2.5%    |
| Intel Wireless 8260                                                               | 1        | 2.5%    |
| Intel Wireless 7260                                                               | 1        | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 1        | 2.5%    |
| D-Link System DWA-131 802.11n Wireless N Nano Adapter(rev.A1) [Realtek RTL8192SU] | 1        | 2.5%    |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]              | 1        | 2.5%    |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]                           | 1        | 2.5%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                        | 1        | 2.5%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 1        | 2.5%    |
| Broadcom BCM43228 802.11a/b/g/n                                                   | 1        | 2.5%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller               | 1        | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 41       | 56.94%  |
| Intel                 | 21       | 29.17%  |
| Qualcomm Atheros      | 3        | 4.17%   |
| Nvidia                | 3        | 4.17%   |
| VIA Technologies      | 1        | 1.39%   |
| Samsung Electronics   | 1        | 1.39%   |
| Huawei Technologies   | 1        | 1.39%   |
| Broadcom              | 1        | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37       | 50%     |
| Intel I211 Gigabit Network Connection                             | 4        | 5.41%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 5.41%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 2.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 2.7%    |
| Intel 82578DM Gigabit Network Connection                          | 2        | 2.7%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 1.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.35%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 1.35%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.35%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.35%   |
| Nvidia MCP55 Ethernet                                             | 1        | 1.35%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.35%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.35%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 1.35%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 1.35%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 1.35%   |
| Huawei ANA-NX9                                                    | 1        | 1.35%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 64.76%  |
| WiFi     | 37       | 35.24%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 68.42%  |
| WiFi     | 24       | 31.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 69.01%  |
| 2     | 15       | 21.13%  |
| 3     | 5        | 7.04%   |
| 4     | 1        | 1.41%   |
| 0     | 1        | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 85.71%  |
| Yes  | 10       | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 11       | 44%     |
| Intel                   | 7        | 28%     |
| Realtek Semiconductor   | 2        | 8%      |
| ASUSTek Computer        | 2        | 8%      |
| IMC Networks            | 1        | 4%      |
| Broadcom                | 1        | 4%      |
| Apple                   | 1        | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 11       | 44%     |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 8%      |
| Intel Bluetooth wireless interface                    | 2        | 8%      |
| Intel AX200 Bluetooth                                 | 2        | 8%      |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 4%      |
| Realtek Bluetooth Radio                               | 1        | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 4%      |
| IMC Networks BCM20702A0                               | 1        | 4%      |
| Broadcom HP Portable Bumble Bee                       | 1        | 4%      |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 4%      |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4%      |
| Apple Bluetooth USB Host Controller                   | 1        | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 47       | 39.83%  |
| AMD                    | 33       | 27.97%  |
| Nvidia                 | 24       | 20.34%  |
| C-Media Electronics    | 5        | 4.24%   |
| JMTek                  | 3        | 2.54%   |
| Generalplus Technology | 2        | 1.69%   |
| Texas Instruments      | 1        | 0.85%   |
| Hewlett-Packard        | 1        | 0.85%   |
| Fortemedia             | 1        | 0.85%   |
| Astro Gaming           | 1        | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 8.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 5.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 4.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5        | 3.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 3.65%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 3.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 3.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 3.65%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5        | 3.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 3.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 2.92%   |
| Intel 200 Series PCH HD Audio                                              | 4        | 2.92%   |
| JMTek USB PnP Audio Device                                                 | 3        | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 2.19%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 2.19%   |
| AMD FCH Azalia Controller                                                  | 3        | 2.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.46%   |
| Generalplus Technology USB Audio Device                                    | 2        | 1.46%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 2        | 1.46%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.46%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 0.73%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                  | 1        | 0.73%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.73%   |
| Nvidia MCP55 High Definition Audio                                         | 1        | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.73%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.73%   |
| Nvidia GF116 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 10       | 31.25%  |
| Unknown             | 4        | 12.5%   |
| Crucial             | 4        | 12.5%   |
| SK hynix            | 3        | 9.38%   |
| Samsung Electronics | 2        | 6.25%   |
| Patriot             | 2        | 6.25%   |
| G.Skill             | 2        | 6.25%   |
| Corsair             | 2        | 6.25%   |
| Ramaxel Technology  | 1        | 3.13%   |
| Nanya Technology    | 1        | 3.13%   |
| Micron Technology   | 1        | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 5.88%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 2.94%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 2.94%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 2.94%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 2.94%   |
| SK hynix RAM HYMP112U64CP8-Y5 1024MB DIMM DDR2 1639MT/s  | 1        | 2.94%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 2.94%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s     | 1        | 2.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 2.94%   |
| Samsung RAM M378A5244CB0-CTD 4096MB DIMM DDR4 3334MT/s   | 1        | 2.94%   |
| Ramaxel RAM RMR1870ED48E8F1333 2048MB DIMM DDR3 1333MT/s | 1        | 2.94%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s          | 1        | 2.94%   |
| Patriot RAM PSD22G8002 2GB DIMM DDR2 800MT/s             | 1        | 2.94%   |
| Nanya RAM Module 4GB FB-DIMM DDR2 667MT/s                | 1        | 2.94%   |
| Micron RAM 16JTF25664AZ-1G4F 2GB DIMM DDR3 1333MT/s      | 1        | 2.94%   |
| Kingston RAM Module 4GB FB-DIMM DDR2 667MT/s             | 1        | 2.94%   |
| Kingston RAM Module 4096MB SODIMM DDR3 1333MT/s          | 1        | 2.94%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 2.94%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 1        | 2.94%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 1        | 2.94%   |
| Kingston RAM KHX1866C9D3/8GX 8GB DIMM DDR3 1866MT/s      | 1        | 2.94%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1600MT/s      | 1        | 2.94%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 1        | 2.94%   |
| Kingston RAM HP497157-B88-ELDW 2048MB DIMM DDR3 1333MT/s | 1        | 2.94%   |
| Kingston RAM 99U5474-028.A00LF 4096MB DIMM DDR3 1333MT/s | 1        | 2.94%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1867MT/s        | 1        | 2.94%   |
| G.Skill RAM F3-12800CL9-4GBRL 4GB DIMM DDR3 1866MT/s     | 1        | 2.94%   |
| Crucial RAM CT51264AA667.M16FC 4GB DIMM DDR2 667MT/s     | 1        | 2.94%   |
| Crucial RAM CT12864BA1339A.C8F 1024MB DIMM DDR3 667MT/s  | 1        | 2.94%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s   | 1        | 2.94%   |
| Crucial RAM BLS16G4D240FSC.16FBD 16GB DIMM DDR4 2400MT/s | 1        | 2.94%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 1        | 2.94%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s    | 1        | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 11       | 44%     |
| DDR4    | 7        | 28%     |
| DDR2    | 5        | 20%     |
| Unknown | 2        | 8%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 22       | 88%     |
| SODIMM  | 2        | 8%      |
| FB-DIMM | 1        | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 11       | 36.67%  |
| 8192  | 9        | 30%     |
| 2048  | 6        | 20%     |
| 16384 | 2        | 6.67%   |
| 1024  | 2        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 6        | 20.69%  |
| 667   | 4        | 13.79%  |
| 3466  | 2        | 6.9%    |
| 2400  | 2        | 6.9%    |
| 1867  | 2        | 6.9%    |
| 1866  | 2        | 6.9%    |
| 1600  | 2        | 6.9%    |
| 800   | 2        | 6.9%    |
| 3600  | 1        | 3.45%   |
| 3334  | 1        | 3.45%   |
| 2934  | 1        | 3.45%   |
| 2933  | 1        | 3.45%   |
| 2133  | 1        | 3.45%   |
| 1800  | 1        | 3.45%   |
| 1639  | 1        | 3.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 5        | 71.43%  |
| Canon              | 1        | 14.29%  |
| Brother Industries | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP Printing Support         | 1        | 14.29%  |
| HP LaserJet Pro M202dw      | 1        | 14.29%  |
| HP LaserJet 1320            | 1        | 14.29%  |
| HP Deskjet 2050 J510        | 1        | 14.29%  |
| HP Deskjet 1000 J110 series | 1        | 14.29%  |
| Canon TR8500 series         | 1        | 14.29%  |
| Brother MFC-T910DW          | 1        | 14.29%  |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 5        | 31.25%  |
| Chicony Electronics         | 2        | 12.5%   |
| Z-Star Microelectronics     | 1        | 6.25%   |
| Samsung Electronics         | 1        | 6.25%   |
| Microsoft                   | 1        | 6.25%   |
| Microdia                    | 1        | 6.25%   |
| LG Electronics              | 1        | 6.25%   |
| KYE Systems (Mouse Systems) | 1        | 6.25%   |
| Generalplus Technology      | 1        | 6.25%   |
| Cubeternet                  | 1        | 6.25%   |
| Apple                       | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 4        | 25%     |
| Z-Star Venus USB2.0 Camera                            | 1        | 6.25%   |
| Samsung Galaxy A5 (MTP)                               | 1        | 6.25%   |
| Microsoft LifeCam VX-2000                             | 1        | 6.25%   |
| Microdia Sonix USB 2.0 Camera                         | 1        | 6.25%   |
| Logitech Webcam C270                                  | 1        | 6.25%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 6.25%   |
| KYE Systems (Mouse Systems) PC-W3 Camera              | 1        | 6.25%   |
| Generalplus GENERAL WEBCAM                            | 1        | 6.25%   |
| Cubeternet GL-UPC822 UVC WebCam                       | 1        | 6.25%   |
| Chicony USB2.0 UVC VGA                                | 1        | 6.25%   |
| Chicony HP High Definition 1MP Webcam                 | 1        | 6.25%   |
| Apple iPhone 4                                        | 1        | 6.25%   |

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
| 0     | 64       | 88.89%  |
| 1     | 8        | 11.11%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 3        | 33.33%  |
| Net/wireless  | 2        | 22.22%  |
| Camera        | 2        | 22.22%  |
| Network       | 1        | 11.11%  |
| Card reader   | 1        | 11.11%  |

