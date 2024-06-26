RHEL 8 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for RHEL 8.

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

Total: 202

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| HP      | ZBook Fury 16 G9 Mobile ... | [10ff3b22cf](https://linux-hardware.org/?probe=10ff3b22cf) | Apr 03, 2024 |
| HP      | ZBook Fury 16 G9 Mobile ... | [896bd3d75a](https://linux-hardware.org/?probe=896bd3d75a) | Apr 03, 2024 |
| HP      | ZBook Fury 15 G7 Mobile ... | [59749a8b22](https://linux-hardware.org/?probe=59749a8b22) | Mar 17, 2024 |
| ASUSTek | VivoBook_ASUSLaptop M340... | [24f8aa7cd0](https://linux-hardware.org/?probe=24f8aa7cd0) | Mar 07, 2024 |
| Dell    | Latitude 5340               | [c9d3b3d7a7](https://linux-hardware.org/?probe=c9d3b3d7a7) | Dec 19, 2023 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [5c4714ecce](https://linux-hardware.org/?probe=5c4714ecce) | Dec 01, 2023 |
| Dell    | Latitude 5420               | [f2bb4ee9f0](https://linux-hardware.org/?probe=f2bb4ee9f0) | Sep 23, 2023 |
| HP      | ProBook 640 G2              | [c0af84c629](https://linux-hardware.org/?probe=c0af84c629) | Sep 02, 2023 |
| HP      | Laptop 15-bs0xx             | [5f2a27253a](https://linux-hardware.org/?probe=5f2a27253a) | Aug 21, 2023 |
| HP      | Laptop 15-bs0xx             | [5e76f9bfc3](https://linux-hardware.org/?probe=5e76f9bfc3) | Aug 21, 2023 |
| ASUSTek | X550ZA                      | [cc243873e2](https://linux-hardware.org/?probe=cc243873e2) | Mar 26, 2023 |
| ASUSTek | X550ZA                      | [2e55d2163a](https://linux-hardware.org/?probe=2e55d2163a) | Mar 26, 2023 |
| Lenovo  | ThinkPad P1 Gen 4i 20Y4S... | [52e2d79bad](https://linux-hardware.org/?probe=52e2d79bad) | Mar 01, 2023 |
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo  | ThinkPad X1 Carbon Gen 9... | [affa3bb9f1](https://linux-hardware.org/?probe=affa3bb9f1) | Feb 19, 2023 |
| Lenovo  | ThinkPad T480s 20L8S2N80... | [2a4e6ab2d4](https://linux-hardware.org/?probe=2a4e6ab2d4) | Feb 07, 2023 |
| Getac   | S410G4                      | [81b80297ab](https://linux-hardware.org/?probe=81b80297ab) | Feb 06, 2023 |
| Getac   | S410G4                      | [1d8e6ad383](https://linux-hardware.org/?probe=1d8e6ad383) | Feb 06, 2023 |
| Lenovo  | ThinkPad T14 Gen 2i 20W1... | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [34169c74c5](https://linux-hardware.org/?probe=34169c74c5) | Dec 31, 2022 |
| HP      | EliteBook 2570p             | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [64fb254a64](https://linux-hardware.org/?probe=64fb254a64) | Nov 17, 2022 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [de9e18e6ca](https://linux-hardware.org/?probe=de9e18e6ca) | Nov 14, 2022 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [8656acec04](https://linux-hardware.org/?probe=8656acec04) | Sep 14, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [23649c49e3](https://linux-hardware.org/?probe=23649c49e3) | Sep 14, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [3df0bebc37](https://linux-hardware.org/?probe=3df0bebc37) | Aug 03, 2022 |
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [71c31086e6](https://linux-hardware.org/?probe=71c31086e6) | Jul 11, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [714c212f51](https://linux-hardware.org/?probe=714c212f51) | Jul 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo  | ThinkPad T480 20L60034MX    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Lenovo  | ThinkPad T15 Gen 2i 20W5... | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| Lenovo  | Legion 5 15ACH6 82JW        | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo  | Legion 5 15ACH6 82JW        | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo  | Legion 5 15ACH6 82JW        | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek | VivoBook_ASUSLaptop X409... | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek | VivoBook_ASUSLaptop X409... | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| Lenovo  | ThinkPad T480 20L6S29D02    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell    | Precision 5550              | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell    | Precision 7560              | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [eed6e0f012](https://linux-hardware.org/?probe=eed6e0f012) | Mar 01, 2022 |
| Lenovo  | Z40-70 20366                | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| Lenovo  | ThinkPad X1 Yoga 1st 20F... | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Lenovo  | ThinkPad T490 20N3S5DV0S    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP      | EliteBook 8460p             | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| ASUSTek | X550VX                      | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| Toshiba | Satellite Pro R50-C         | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| Toshiba | Satellite Pro R50-C         | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| Dell    | Precision 3551              | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo  | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Acer    | Nitro AN515-54              | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP      | EliteBook 840 G8 Noteboo... | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo  | ThinkPad T480 20L6S29E1T    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo  | ThinkPad P17 Gen 2i 20YU... | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo  | ThinkPad P50 20ENS1L000     | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo  | ThinkPad E490 20N8000JAD    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo  | ThinkPad E490 20N8000JAD    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| HP      | ZBook Firefly 15 inch G8... | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| Lenovo  | ThinkPad P50 20ENS1L000     | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| Lenovo  | ThinkPad T490s 20NYS7K90... | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| Lenovo  | ThinkPad T470 20HES57W00    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo  | ThinkPad X230 Tablet 343... | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell    | XPS 15 9560                 | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek | TUF Gaming FX505DU_FX505... | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek | TUF Gaming FX505DU_FX505... | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell    | XPS 15 9560                 | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| HP      | ZBook 15 G5                 | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Dell    | Latitude E5510              | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP      | EliteBook 850 G7 Noteboo... | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell    | Latitude E6430              | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell    | Latitude E6430              | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell    | Latitude E6430              | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo  | ThinkPad P15 Gen 1 20SUS... | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Dell    | Precision 3541              | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP      | ZBook Studio G5             | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP      | ZBook Studio G5             | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell    | Latitude E6530              | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell    | Inspiron 3559               | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP      | OMEN by Laptop 15-dc1xxx    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo  | ThinkPad P1 Gen 3 20TJS2... | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo  | ThinkPad T460 20FMS1VA09    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo  | ThinkPad T460 20FMS1VA09    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo  | ThinkPad W530 2441B32       | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek | Zephyrus G GU502DU_GA502... | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| Sony    | VPCEB4L1R                   | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP      | EliteBook 8460p             | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Lenovo  | ThinkPad X201 3680PKS       | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo  | ThinkPad X201 3680PKS       | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo  | ThinkPad L480 20LSCTO1WW    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Lenovo  | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo  | ThinkPad T14 Gen 1 20S1S... | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| Lenovo  | ThinkPad T480s 20L8S2N80... | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| Lenovo  | ThinkPad T14s Gen 1 20T1... | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo  | ThinkPad E15 Gen 2 20T80... | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo  | ThinkPad T490s 20NYS7K91... | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Dell    | Latitude 5290               | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell    | Latitude 5290               | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP      | Pavilion 14                 | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo  | ThinkPad X250 20CLS0H807    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo  | ThinkPad T460 20BUS0QT0A    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| Dell    | Precision 7510              | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| TUXEDO  | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell    | Inspiron 5567               | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Dell    | Latitude E6420              | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell    | Latitude E6420              | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| TUXEDO  | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO  | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell    | Precision 7510              | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP      | Pavilion 14                 | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell    | Precision 7510              | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo  | ThinkPad T520 42404CG       | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo  | ThinkPad T520 42404CG       | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo  | ThinkPad T14s Gen 1 20UJ... | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell    | Latitude 5300               | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell    | Latitude 5300               | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP      | Pavilion 14                 | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo  | ThinkPad W520 4284GN2       | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo  | ThinkPad W520 4284GN2       | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| Lenovo  | ThinkPad P50 20EN0005UK     | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| HP      | ProBook 430 G5              | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell    | Inspiron N5110              | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell    | Inspiron N5110              | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| ASUSTek | GL502VMK                    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| Dell    | Latitude 5300               | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi    | TM1707                      | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi    | TM1707                      | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek | GL502VMK                    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell    | Latitude 5300               | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0N    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0N    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| HP      | ProBook 430 G5              | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP      | ProBook 430 G5              | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell    | G3 3779                     | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell    | Precision 5540              | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| Lenovo  | ThinkPad T450s 20BWS0B50... | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC0N    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC00    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo  | ThinkPad T590 20N5S2NC00    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Lenovo  | ThinkPad T450s 20BWS0B50... | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Sony    | VPCEB23FM                   | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony    | VPCEB23FM                   | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Lenovo  | ThinkPad P52 20M9CTO1WW     | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo  | ThinkPad P52 20M9CTO1WW     | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Lenovo  | ThinkPad T490s 20NX002HU... | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| Lenovo  | ThinkPad P1 Gen 2 20QUS1... | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| Lenovo  | ThinkPad X1 Carbon 6th 2... | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo  | ThinkPad X1 Carbon 7th 2... | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Lenovo  | ThinkPad X270 20HN001EMC    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Dell    | Inspiron 5567               | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP      | 250 G4 Notebook PC          | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP      | 250 G4 Notebook PC          | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo  | ThinkPad X1 Carbon 6th 2... | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Lenovo  | ThinkPad T590 20N5S2NC0V    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo  | ThinkPad T480s 20L8S2N80... | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64 | 10        | 6.8%    |
| 4.18.0-240.1.1.el8_3.x86_64  | 10        | 6.8%    |
| 4.18.0-80.11.2.el8_0.x86_64  | 8         | 5.44%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 8         | 5.44%   |
| 4.18.0-425.10.1.el8_7.x86_64 | 7         | 4.76%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 7         | 4.76%   |
| 4.18.0-305.3.1.el8_4.x86_64  | 7         | 4.76%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 4         | 2.72%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 4         | 2.72%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 4         | 2.72%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 4         | 2.72%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 4         | 2.72%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 4         | 2.72%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 2.72%   |
| 4.18.0-193.el8.x86_64        | 4         | 2.72%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 4         | 2.72%   |
| 4.18.0-425.3.1.el8.x86_64    | 3         | 2.04%   |
| 4.18.0-372.9.1.el8.x86_64    | 3         | 2.04%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 2.04%   |
| 4.18.0-305.el8.x86_64        | 3         | 2.04%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.04%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 3         | 2.04%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 3         | 2.04%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 3         | 2.04%   |
| 4.18.0-477.27.1.el8_8.x86_64 | 2         | 1.36%   |
| 4.18.0-477.21.1.el8_8.x86_64 | 2         | 1.36%   |
| 4.18.0-348.el8.x86_64        | 2         | 1.36%   |
| 4.18.0-193.14.3.el8_2.x86_64 | 2         | 1.36%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.36%   |
| 4.18.0-147.8.1.el8_1.x86_64  | 2         | 1.36%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.68%   |
| 4.18.0-80.el8.x86_64         | 1         | 0.68%   |
| 4.18.0-80.4.2.el8_0.x86_64   | 1         | 0.68%   |
| 4.18.0-513.9.1.el8_9.x86_64  | 1         | 0.68%   |
| 4.18.0-513.18.1.el8_9.x86_64 | 1         | 0.68%   |
| 4.18.0-425.19.2.el8_7.x86_64 | 1         | 0.68%   |
| 4.18.0-372.32.1.el8_6.x86_64 | 1         | 0.68%   |
| 4.18.0-372.26.1.el8_6.x86_64 | 1         | 0.68%   |
| 4.18.0-372.19.1.el8_6.x86_64 | 1         | 0.68%   |
| 4.18.0-372.13.1.el8_6.x86_64 | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 120       | 99.17%  |
| 5.9.1   | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 120       | 99.17%  |
| 5.9     | 1         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 121       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 108       | 86.4%   |
| Unknown       | 9         | 7.2%    |
| GNOME Classic | 6         | 4.8%    |
| KDE5          | 2         | 1.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 73        | 58.4%   |
| Wayland | 47        | 37.6%   |
| Unknown | 5         | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 97        | 76.38%  |
| GDM     | 29        | 22.83%  |
| SDDM    | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 87        | 69.6%   |
| Unknown | 7         | 5.6%    |
| en_GB   | 6         | 4.8%    |
| fr_FR   | 4         | 3.2%    |
| pt_BR   | 2         | 1.6%    |
| pl_PL   | 2         | 1.6%    |
| nl_NL   | 2         | 1.6%    |
| en_IN   | 2         | 1.6%    |
| en_IE   | 2         | 1.6%    |
| de_DE   | 2         | 1.6%    |
| ru_RU   | 1         | 0.8%    |
| nl_BE   | 1         | 0.8%    |
| ja_JP   | 1         | 0.8%    |
| it_IT   | 1         | 0.8%    |
| es_ES   | 1         | 0.8%    |
| es_EC   | 1         | 0.8%    |
| es_CO   | 1         | 0.8%    |
| en_DK   | 1         | 0.8%    |
| de_CH   | 1         | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 102       | 82.26%  |
| BIOS | 22        | 17.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 105       | 85.37%  |
| Ext4    | 13        | 10.57%  |
| Unknown | 5         | 4.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 95        | 75.4%   |
| GPT     | 30        | 23.81%  |
| MBR     | 1         | 0.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 94.31%  |
| Yes       | 7         | 5.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 113       | 91.13%  |
| Yes       | 11        | 8.87%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 71        | 58.68%  |
| Dell             | 21        | 17.36%  |
| Hewlett-Packard  | 15        | 12.4%   |
| ASUSTek Computer | 7         | 5.79%   |
| Sony             | 2         | 1.65%   |
| TUXEDO           | 1         | 0.83%   |
| Toshiba          | 1         | 0.83%   |
| Timi             | 1         | 0.83%   |
| Getac            | 1         | 0.83%   |
| Acer             | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X        | 4         | 3.31%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401   | 2         | 1.65%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00   | 2         | 1.65%   |
| Lenovo ThinkPad T590 20N5S2NC0N            | 2         | 1.65%   |
| Lenovo ThinkPad T490s 20NYS7K91R           | 2         | 1.65%   |
| Lenovo ThinkPad T480s 20L8S2N800           | 2         | 1.65%   |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08      | 2         | 1.65%   |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q        | 2         | 1.65%   |
| HP EliteBook 8460p                         | 2         | 1.65%   |
| Dell Latitude E6430                        | 2         | 1.65%   |
| Dell Latitude 5300                         | 2         | 1.65%   |
| TUXEDO N13xWU                              | 1         | 0.83%   |
| Toshiba Satellite Pro R50-C                | 1         | 0.83%   |
| Timi TM1707                                | 1         | 0.83%   |
| Sony VPCEB4L1R                             | 1         | 0.83%   |
| Sony VPCEB23FM                             | 1         | 0.83%   |
| Lenovo Z40-70 20366                        | 1         | 0.83%   |
| Lenovo ThinkPad X270 20HN001EMC            | 1         | 0.83%   |
| Lenovo ThinkPad X250 20CLS0H807            | 1         | 0.83%   |
| Lenovo ThinkPad X230 Tablet 34373KU        | 1         | 0.83%   |
| Lenovo ThinkPad X201 3680PKS               | 1         | 0.83%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100     | 1         | 0.83%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XXS3HC1G | 1         | 0.83%   |
| Lenovo ThinkPad W530 2441B32               | 1         | 0.83%   |
| Lenovo ThinkPad W520 4284GN2               | 1         | 0.83%   |
| Lenovo ThinkPad T590 20N5S2NC0V            | 1         | 0.83%   |
| Lenovo ThinkPad T590 20N5S2NC00            | 1         | 0.83%   |
| Lenovo ThinkPad T520 42404CG               | 1         | 0.83%   |
| Lenovo ThinkPad T490s 20NYS7K905           | 1         | 0.83%   |
| Lenovo ThinkPad T490s 20NX002HUS           | 1         | 0.83%   |
| Lenovo ThinkPad T490 20N3S5DV0S            | 1         | 0.83%   |
| Lenovo ThinkPad T480s 20L8S2N80V           | 1         | 0.83%   |
| Lenovo ThinkPad T480 20L6S29E1T            | 1         | 0.83%   |
| Lenovo ThinkPad T480 20L6S29D02            | 1         | 0.83%   |
| Lenovo ThinkPad T480 20L60034MX            | 1         | 0.83%   |
| Lenovo ThinkPad T470 20HES57W00            | 1         | 0.83%   |
| Lenovo ThinkPad T460 20FMS1VA09            | 1         | 0.83%   |
| Lenovo ThinkPad T460 20BUS0QT0A            | 1         | 0.83%   |
| Lenovo ThinkPad T450s 20BWS0B500           | 1         | 0.83%   |
| Lenovo ThinkPad T15 Gen 2i 20W5S12J0K      | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 69        | 57.02%  |
| Dell Latitude     | 10        | 8.26%   |
| Dell Precision    | 6         | 4.96%   |
| HP EliteBook      | 5         | 4.13%   |
| HP ZBook          | 4         | 3.31%   |
| Dell Inspiron     | 3         | 2.48%   |
| HP ProBook        | 2         | 1.65%   |
| ASUS VivoBook     | 2         | 1.65%   |
| TUXEDO N13xWU     | 1         | 0.83%   |
| Toshiba Satellite | 1         | 0.83%   |
| Timi TM1707       | 1         | 0.83%   |
| Sony VPCEB4L1R    | 1         | 0.83%   |
| Sony VPCEB23FM    | 1         | 0.83%   |
| Lenovo Z40-70     | 1         | 0.83%   |
| Lenovo Legion     | 1         | 0.83%   |
| HP Pavilion       | 1         | 0.83%   |
| HP OMEN           | 1         | 0.83%   |
| HP Laptop         | 1         | 0.83%   |
| HP 250            | 1         | 0.83%   |
| Getac S410G4      | 1         | 0.83%   |
| Dell XPS          | 1         | 0.83%   |
| Dell G3           | 1         | 0.83%   |
| ASUS Zephyrus     | 1         | 0.83%   |
| ASUS X550ZA       | 1         | 0.83%   |
| ASUS X550VX       | 1         | 0.83%   |
| ASUS TUF          | 1         | 0.83%   |
| ASUS GL502VMK     | 1         | 0.83%   |
| Acer Nitro        | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 31        | 25.62%  |
| 2019 | 22        | 18.18%  |
| 2018 | 16        | 13.22%  |
| 2021 | 9         | 7.44%   |
| 2017 | 7         | 5.79%   |
| 2016 | 7         | 5.79%   |
| 2011 | 7         | 5.79%   |
| 2015 | 6         | 4.96%   |
| 2012 | 6         | 4.96%   |
| 2014 | 3         | 2.48%   |
| 2010 | 3         | 2.48%   |
| 2022 | 2         | 1.65%   |
| 2023 | 1         | 0.83%   |
| 2013 | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 121       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 101       | 82.79%  |
| Enabled  | 21        | 17.21%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 121       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 46        | 36.8%   |
| 8.01-16.0   | 24        | 19.2%   |
| 16.01-24.0  | 21        | 16.8%   |
| 4.01-8.0    | 19        | 15.2%   |
| 64.01-256.0 | 8         | 6.4%    |
| 3.01-4.0    | 5         | 4%      |
| 24.01-32.0  | 2         | 1.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 61        | 44.85%  |
| 8.01-16.0  | 22        | 16.18%  |
| 3.01-4.0   | 19        | 13.97%  |
| 2.01-3.0   | 17        | 12.5%   |
| 1.01-2.0   | 10        | 7.35%   |
| 16.01-24.0 | 3         | 2.21%   |
| 24.01-32.0 | 2         | 1.47%   |
| 32.01-64.0 | 1         | 0.74%   |
| 0.51-1.0   | 1         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 95        | 76.61%  |
| 2      | 20        | 16.13%  |
| 3      | 8         | 6.45%   |
| 4      | 1         | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 87.7%   |
| Yes       | 15        | 12.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 87.7%   |
| No        | 15        | 12.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 99.17%  |
| No        | 1         | 0.83%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 77.95%  |
| No        | 28        | 22.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 27        | 22.31%  |
| India        | 15        | 12.4%   |
| Germany      | 8         | 6.61%   |
| UK           | 6         | 4.96%   |
| France       | 5         | 4.13%   |
| Czechia      | 5         | 4.13%   |
| Switzerland  | 3         | 2.48%   |
| South Africa | 3         | 2.48%   |
| Netherlands  | 3         | 2.48%   |
| Mexico       | 3         | 2.48%   |
| Brazil       | 3         | 2.48%   |
| Spain        | 2         | 1.65%   |
| Romania      | 2         | 1.65%   |
| Poland       | 2         | 1.65%   |
| Japan        | 2         | 1.65%   |
| Colombia     | 2         | 1.65%   |
| Chile        | 2         | 1.65%   |
| Canada       | 2         | 1.65%   |
| Australia    | 2         | 1.65%   |
| Singapore    | 1         | 0.83%   |
| Saudi Arabia | 1         | 0.83%   |
| Russia       | 1         | 0.83%   |
| Portugal     | 1         | 0.83%   |
| Pakistan     | 1         | 0.83%   |
| Nepal        | 1         | 0.83%   |
| Myanmar      | 1         | 0.83%   |
| Morocco      | 1         | 0.83%   |
| Luxembourg   | 1         | 0.83%   |
| Lithuania    | 1         | 0.83%   |
| Kuwait       | 1         | 0.83%   |
| Kenya        | 1         | 0.83%   |
| Italy        | 1         | 0.83%   |
| Israel       | 1         | 0.83%   |
| Ireland      | 1         | 0.83%   |
| Georgia      | 1         | 0.83%   |
| Finland      | 1         | 0.83%   |
| Egypt        | 1         | 0.83%   |
| Ecuador      | 1         | 0.83%   |
| China        | 1         | 0.83%   |
| Bulgaria     | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Prague                   | 4         | 3.08%   |
| Munich                   | 3         | 2.31%   |
| Mexico City              | 3         | 2.31%   |
| Chennai                  | 2         | 1.54%   |
| Berlin                   | 2         | 1.54%   |
| Bengaluru                | 2         | 1.54%   |
| Zaragoza                 | 1         | 0.77%   |
| Webster                  | 1         | 0.77%   |
| Wayne                    | 1         | 0.77%   |
| Wagholi                  | 1         | 0.77%   |
| Vardenis                 | 1         | 0.77%   |
| Udaipur                  | 1         | 0.77%   |
| Turku                    | 1         | 0.77%   |
| Temuco                   | 1         | 0.77%   |
| Temara                   | 1         | 0.77%   |
| Taringa                  | 1         | 0.77%   |
| Talkha                   | 1         | 0.77%   |
| Syracuse                 | 1         | 0.77%   |
| Stuttgart                | 1         | 0.77%   |
| Streatham                | 1         | 0.77%   |
| Stellenbosch             | 1         | 0.77%   |
| Steamboat Springs        | 1         | 0.77%   |
| Sofia                    | 1         | 0.77%   |
| Singapore                | 1         | 0.77%   |
| Šilalė                 | 1         | 0.77%   |
| Sheffield                | 1         | 0.77%   |
| Santiago                 | 1         | 0.77%   |
| San Jose                 | 1         | 0.77%   |
| San Francisco            | 1         | 0.77%   |
| Salt Lake City           | 1         | 0.77%   |
| Saint-Ismier             | 1         | 0.77%   |
| Saint-Alphonse-Rodriguez | 1         | 0.77%   |
| Roha                     | 1         | 0.77%   |
| Rochester                | 1         | 0.77%   |
| Reims                    | 1         | 0.77%   |
| Raleigh                  | 1         | 0.77%   |
| Quito                    | 1         | 0.77%   |
| Queenscliff              | 1         | 0.77%   |
| Queens                   | 1         | 0.77%   |
| Portalegre               | 1         | 0.77%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 37        | 56     | 24.03%  |
| Toshiba                     | 17        | 21     | 11.04%  |
| WDC                         | 15        | 19     | 9.74%   |
| SK hynix                    | 13        | 14     | 8.44%   |
| Seagate                     | 12        | 17     | 7.79%   |
| SanDisk                     | 12        | 16     | 7.79%   |
| Micron Technology           | 7         | 9      | 4.55%   |
| Unknown                     | 6         | 8      | 3.9%    |
| Kingston                    | 6         | 6      | 3.9%    |
| Intel                       | 6         | 9      | 3.9%    |
| Lenovo                      | 3         | 3      | 1.95%   |
| HGST                        | 3         | 3      | 1.95%   |
| Silicon Motion              | 2         | 3      | 1.3%    |
| Crucial                     | 2         | 2      | 1.3%    |
| A-DATA Technology           | 2         | 2      | 1.3%    |
| UMIS                        | 1         | 1      | 0.65%   |
| Team                        | 1         | 2      | 0.65%   |
| SSSTC                       | 1         | 1      | 0.65%   |
| SMI                         | 1         | 2      | 0.65%   |
| PNY                         | 1         | 2      | 0.65%   |
| Lite-On                     | 1         | 1      | 0.65%   |
| KIOXIA                      | 1         | 1      | 0.65%   |
| Kingston Technology Company | 1         | 1      | 0.65%   |
| Intenso                     | 1         | 1      | 0.65%   |
| Gigabyte Technology         | 1         | 1      | 0.65%   |
| Corsair                     | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB                    | 10        | 6.02%   |
| SanDisk NVMe SSD Drive 256GB                     | 6         | 3.61%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB           | 6         | 3.61%   |
| Samsung NVMe SSD Drive 512GB                     | 5         | 3.01%   |
| Samsung NVMe SSD Drive 1024GB                    | 5         | 3.01%   |
| Toshiba NVMe SSD Drive 256GB                     | 4         | 2.41%   |
| Toshiba NVMe SSD Drive 512GB                     | 3         | 1.81%   |
| Micron NVMe SSD Drive 256GB                      | 3         | 1.81%   |
| Unknown NVMe SSD Drive 256GB                     | 2         | 1.2%    |
| Unknown MMC Card  16GB                           | 2         | 1.2%    |
| Toshiba XG6 NVMe SSD Controller 1024GB           | 2         | 1.2%    |
| Toshiba KXG6AZNV256G 256GB                       | 2         | 1.2%    |
| Seagate Expansion 2TB                            | 2         | 1.2%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 2         | 1.2%    |
| Samsung SSD 860 QVO 1TB                          | 2         | 1.2%    |
| Samsung SSD 860 EVO 1TB                          | 2         | 1.2%    |
| Samsung Portable SSD T5 500GB                    | 2         | 1.2%    |
| Samsung NVMe SSD Drive 500GB                     | 2         | 1.2%    |
| Samsung NVMe SSD Drive 2TB                       | 2         | 1.2%    |
| Samsung NVMe SSD Drive 1TB                       | 2         | 1.2%    |
| Samsung MZVL21T0HCLR-00BL7 1TB                   | 2         | 1.2%    |
| Kingston SA400S37480G 480GB SSD                  | 2         | 1.2%    |
| Intel NVMe SSD Drive 512GB                       | 2         | 1.2%    |
| Intel NVMe SSD Drive 2TB                         | 2         | 1.2%    |
| HGST HTS721010A9E630 1TB                         | 2         | 1.2%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                 | 1         | 0.6%    |
| WDC WDS400T2B0A-00SM50 4TB SSD                   | 1         | 0.6%    |
| WDC WDS200T2B0B-00YS70 2TB SSD                   | 1         | 0.6%    |
| WDC WD6400BPVT-75HXZT1 640GB                     | 1         | 0.6%    |
| WDC WD5000LPLX-08ZNTT0 500GB                     | 1         | 0.6%    |
| WDC WD2500BEVT-60ZCT1 250GB                      | 1         | 0.6%    |
| WDC WD20 SPZX-11UA7T0 2TB                        | 1         | 0.6%    |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 0.6%    |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 0.6%    |
| WDC WD10SPZX-08Z10 1TB                           | 1         | 0.6%    |
| WDC WD10JPVX-75JC3T0 1TB                         | 1         | 0.6%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB             | 1         | 0.6%    |
| WDC PC SN730 SDBQNTY-256G-1001 256GB             | 1         | 0.6%    |
| WDC PC SN720 SDAQNTW-512G-1001 512GB             | 1         | 0.6%    |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB             | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 16     | 44.44%  |
| WDC     | 8         | 10     | 29.63%  |
| Toshiba | 4         | 6      | 14.81%  |
| HGST    | 3         | 3      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 15     | 40%     |
| Kingston            | 4         | 4      | 11.43%  |
| WDC                 | 3         | 4      | 8.57%   |
| SanDisk             | 3         | 4      | 8.57%   |
| Crucial             | 2         | 2      | 5.71%   |
| A-DATA Technology   | 2         | 2      | 5.71%   |
| Toshiba             | 1         | 1      | 2.86%   |
| Team                | 1         | 2      | 2.86%   |
| Seagate             | 1         | 1      | 2.86%   |
| PNY                 | 1         | 2      | 2.86%   |
| Micron Technology   | 1         | 1      | 2.86%   |
| Intenso             | 1         | 1      | 2.86%   |
| Corsair             | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 85        | 120    | 56.67%  |
| SSD     | 33        | 40     | 22%     |
| HDD     | 27        | 35     | 18%     |
| MMC     | 4         | 5      | 2.67%   |
| Unknown | 1         | 2      | 0.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 85        | 120    | 59.86%  |
| SATA | 44        | 65     | 30.99%  |
| SAS  | 9         | 12     | 6.34%   |
| MMC  | 4         | 5      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 35     | 50%     |
| 0.51-1.0   | 19        | 27     | 33.93%  |
| 1.01-2.0   | 6         | 8      | 10.71%  |
| 3.01-4.0   | 2         | 2      | 3.57%   |
| 4.01-10.0  | 1         | 3      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 44.44%  |
| 251-500        | 24        | 19.05%  |
| 501-1000       | 18        | 14.29%  |
| 1001-2000      | 9         | 7.14%   |
| More than 3000 | 6         | 4.76%   |
| 51-100         | 4         | 3.17%   |
| 21-50          | 3         | 2.38%   |
| 2001-3000      | 3         | 2.38%   |
| 1-20           | 2         | 1.59%   |
| Unknown        | 1         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 30        | 22.39%  |
| 101-250        | 26        | 19.4%   |
| 1-20           | 26        | 19.4%   |
| 51-100         | 24        | 17.91%  |
| 251-500        | 15        | 11.19%  |
| 501-1000       | 7         | 5.22%   |
| 1001-2000      | 3         | 2.24%   |
| More than 3000 | 1         | 0.75%   |
| 2001-3000      | 1         | 0.75%   |
| Unknown        | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 99        | 164    | 76.74%  |
| Works    | 29        | 37     | 22.48%  |
| Malfunc  | 1         | 1      | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 54        | 38.3%   |
| Samsung Electronics            | 25        | 17.73%  |
| SK hynix                       | 13        | 9.22%   |
| SanDisk                        | 13        | 9.22%   |
| Toshiba America Info Systems   | 12        | 8.51%   |
| Micron Technology              | 6         | 4.26%   |
| AMD                            | 4         | 2.84%   |
| Lenovo                         | 3         | 2.13%   |
| KIOXIA                         | 3         | 2.13%   |
| Silicon Motion                 | 2         | 1.42%   |
| Kingston Technology Company    | 2         | 1.42%   |
| Union Memory (Shenzhen)        | 1         | 0.71%   |
| Solid State Storage Technology | 1         | 0.71%   |
| Phison Electronics             | 1         | 0.71%   |
| Lite-On Technology             | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 19        | 13.29%  |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 11        | 7.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 11        | 7.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 9         | 6.29%   |
| SK hynix PC611 NVMe Solid State Drive                                         | 7         | 4.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 6         | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 4.2%    |
| SK hynix PC601 NVMe Solid State Drive                                         | 4         | 2.8%    |
| Micron 2300 NVMe SSD [Santana]                                                | 4         | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 2.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 4         | 2.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.1%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 3         | 2.1%    |
| Intel SSD 660P Series                                                         | 3         | 2.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 2.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 3         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 3         | 2.1%    |
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 2.1%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2         | 1.4%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 1.4%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                   | 2         | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 2         | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 1.4%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 1.4%    |
| Micron 3400 NVMe SSD [Hendrix]                                                | 2         | 1.4%    |
| Lenovo LENSE20256GMSP34MEAT2TA                                                | 2         | 1.4%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 2         | 1.4%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 2         | 1.4%    |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                 | 1         | 0.7%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.7%    |
| Solid State Storage CA5-8D256 NVMe SSD M.2                                    | 1         | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                         | 1         | 0.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 1         | 0.7%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 1         | 0.7%    |
| Lite-On CA5-8D512 NVMe SSD                                                    | 1         | 0.7%    |
| Lenovo LENSE30256GMSP34MEAT3TA                                                | 1         | 0.7%    |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 1         | 0.7%    |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                              | 1         | 0.7%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                      | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 85        | 61.15%  |
| SATA | 49        | 35.25%  |
| RAID | 5         | 3.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 113       | 93.39%  |
| AMD    | 8         | 6.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 9.09%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 10        | 8.26%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 7.44%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 4.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.48%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 2.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.48%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 1.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.65%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.65%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.65%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.65%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 1.65%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.65%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.65%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 2         | 1.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.65%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.65%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.65%   |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.83%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.83%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.83%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.83%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.83%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.83%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.83%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.83%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.83%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.83%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.83%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 64        | 52.89%  |
| Intel Core i5   | 26        | 21.49%  |
| Other           | 10        | 8.26%   |
| AMD Ryzen 7     | 6         | 4.96%   |
| Intel Xeon      | 5         | 4.13%   |
| Intel Core i3   | 4         | 3.31%   |
| Intel Core i9   | 3         | 2.48%   |
| Intel Pentium   | 1         | 0.83%   |
| AMD Ryzen 7 PRO | 1         | 0.83%   |
| AMD A10         | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 56        | 46.28%  |
| 2      | 31        | 25.62%  |
| 6      | 21        | 17.36%  |
| 8      | 11        | 9.09%   |
| 16     | 1         | 0.83%   |
| 10     | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 121       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 117       | 96.69%  |
| 1      | 4         | 3.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 119       | 96.75%  |
| Unknown        | 4         | 3.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 27        | 21.95%  |
| 0x806ea    | 13        | 10.57%  |
| 0xa0652    | 12        | 9.76%   |
| 0x906ea    | 7         | 5.69%   |
| 0x406e3    | 7         | 5.69%   |
| 0x806c1    | 6         | 4.88%   |
| 0x306a9    | 6         | 4.88%   |
| 0x206a7    | 6         | 4.88%   |
| Unknown    | 6         | 4.88%   |
| 0x906ed    | 4         | 3.25%   |
| 0x506e3    | 4         | 3.25%   |
| 0x806e9    | 3         | 2.44%   |
| 0x806d1    | 3         | 2.44%   |
| 0x306d4    | 3         | 2.44%   |
| 0x20655    | 3         | 2.44%   |
| 0x906e9    | 2         | 1.63%   |
| 0x40651    | 2         | 1.63%   |
| 0x0a50000c | 2         | 1.63%   |
| 0x08600103 | 2         | 1.63%   |
| 0x08108102 | 2         | 1.63%   |
| 0x20652    | 1         | 0.81%   |
| 0x08600104 | 1         | 0.81%   |
| 0x06003106 | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 57        | 46.72%  |
| CometLake        | 13        | 10.66%  |
| Skylake          | 11        | 9.02%   |
| TigerLake        | 6         | 4.92%   |
| SandyBridge      | 6         | 4.92%   |
| IvyBridge        | 6         | 4.92%   |
| Westmere         | 4         | 3.28%   |
| Zen 2            | 3         | 2.46%   |
| Icelake          | 3         | 2.46%   |
| Broadwell        | 3         | 2.46%   |
| Zen+             | 2         | 1.64%   |
| Zen 3            | 2         | 1.64%   |
| Haswell          | 2         | 1.64%   |
| Unknown          | 2         | 1.64%   |
| Steamroller      | 1         | 0.82%   |
| Alderlake Hybrid | 1         | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 102       | 67.55%  |
| Nvidia | 34        | 22.52%  |
| AMD    | 15        | 9.93%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 14        | 9.27%   |
| Intel UHD Graphics 620                                                    | 13        | 8.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 13        | 8.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 12        | 7.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 7         | 4.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 7         | 4.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 3.97%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 3.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.65%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 3         | 1.99%   |
| Intel HD Graphics 620                                                     | 3         | 1.99%   |
| Intel HD Graphics 5500                                                    | 3         | 1.99%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 1.99%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 3         | 1.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.32%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.32%   |
| Nvidia GP107GLM [Quadro P620]                                             | 2         | 1.32%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 2         | 1.32%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.32%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.32%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.32%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.66%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                             | 1         | 0.66%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                     | 1         | 0.66%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 1         | 0.66%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.66%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                     | 1         | 0.66%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 0.66%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.66%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.66%   |
| Nvidia GK107GLM [Quadro K2000M]                                           | 1         | 0.66%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 0.66%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 0.66%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 76        | 62.3%   |
| Intel + Nvidia | 22        | 18.03%  |
| 1 x Nvidia     | 9         | 7.38%   |
| 1 x AMD        | 7         | 5.74%   |
| Intel + AMD    | 4         | 3.28%   |
| AMD + Nvidia   | 4         | 3.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 108       | 87.8%   |
| Proprietary | 10        | 8.13%   |
| Unknown     | 5         | 4.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 71.31%  |
| 3.01-4.0   | 11        | 9.02%   |
| 1.01-2.0   | 8         | 6.56%   |
| 0.51-1.0   | 6         | 4.92%   |
| 5.01-6.0   | 4         | 3.28%   |
| 0.01-0.5   | 4         | 3.28%   |
| 7.01-8.0   | 1         | 0.82%   |
| 8.01-16.0  | 1         | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 16.77%  |
| BOE                     | 21        | 12.57%  |
| LG Display              | 20        | 11.98%  |
| Chimei Innolux          | 19        | 11.38%  |
| Dell                    | 16        | 9.58%   |
| Samsung Electronics     | 14        | 8.38%   |
| Lenovo                  | 12        | 7.19%   |
| Hewlett-Packard         | 6         | 3.59%   |
| Sharp                   | 5         | 2.99%   |
| InfoVision              | 4         | 2.4%    |
| Goldstar                | 4         | 2.4%    |
| PANDA                   | 3         | 1.8%    |
| Acer                    | 3         | 1.8%    |
| Philips                 | 2         | 1.2%    |
| LGD                     | 2         | 1.2%    |
| AOC                     | 2         | 1.2%    |
| Sun                     | 1         | 0.6%    |
| Sceptre Tech            | 1         | 0.6%    |
| Planar                  | 1         | 0.6%    |
| Eizo                    | 1         | 0.6%    |
| Chi Mei Optoelectronics | 1         | 0.6%    |
| BOE Technology Group    | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 4%      |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 2.86%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 5         | 2.86%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 1.71%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 1.71%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 3         | 1.71%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 3         | 1.71%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 1.71%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 1.71%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 1.71%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 3         | 1.71%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 1.14%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.14%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 1.14%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 1.14%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 1.14%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch            | 2         | 1.14%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.14%   |
| Sun LCD Monitor SUN059A 1920x1080 518x324mm 24.1-inch                 | 1         | 0.57%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.57%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.57%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.57%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch               | 1         | 0.57%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.57%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.57%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.57%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.57%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.57%   |
| Samsung Electronics SMBX2431 SAM0771 1920x1080 531x299mm 24.0-inch    | 1         | 0.57%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch | 1         | 0.57%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.57%   |
| Samsung Electronics S22E310 SAM0C2D 1920x1080 477x268mm 21.5-inch     | 1         | 0.57%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.57%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 81        | 57.04%  |
| 1366x768 (WXGA)    | 19        | 13.38%  |
| 3840x2160 (4K)     | 8         | 5.63%   |
| 2560x1440 (QHD)    | 7         | 4.93%   |
| 1600x900 (HD+)     | 7         | 4.93%   |
| 1920x1200 (WUXGA)  | 5         | 3.52%   |
| 2560x1080          | 3         | 2.11%   |
| 3440x1440          | 2         | 1.41%   |
| 1680x1050 (WSXGA+) | 2         | 1.41%   |
| 6400x2160          | 1         | 0.7%    |
| 3840x1080          | 1         | 0.7%    |
| 2880x1800          | 1         | 0.7%    |
| 2560x1600          | 1         | 0.7%    |
| 2048x1152          | 1         | 0.7%    |
| 1440x900 (WXGA+)   | 1         | 0.7%    |
| 1280x800 (WXGA)    | 1         | 0.7%    |
| Unknown            | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 47        | 28.14%  |
| 14      | 34        | 20.36%  |
| 13      | 20        | 11.98%  |
| 24      | 17        | 10.18%  |
| 27      | 12        | 7.19%   |
| 23      | 7         | 4.19%   |
| 34      | 5         | 2.99%   |
| 12      | 5         | 2.99%   |
| 21      | 4         | 2.4%    |
| 17      | 3         | 1.8%    |
| Unknown | 3         | 1.8%    |
| 31      | 2         | 1.2%    |
| 22      | 2         | 1.2%    |
| 16      | 2         | 1.2%    |
| 49      | 1         | 0.6%    |
| 32      | 1         | 0.6%    |
| 19      | 1         | 0.6%    |
| 18      | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 98        | 59.76%  |
| 501-600     | 30        | 18.29%  |
| 201-300     | 10        | 6.1%    |
| 401-500     | 8         | 4.88%   |
| 701-800     | 6         | 3.66%   |
| 601-700     | 5         | 3.05%   |
| 351-400     | 3         | 1.83%   |
| Unknown     | 3         | 1.83%   |
| 1001-1500   | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 108       | 82.44%  |
| 16/10   | 13        | 9.92%   |
| 21/9    | 5         | 3.82%   |
| Unknown | 3         | 2.29%   |
| 32/9    | 1         | 0.76%   |
| 3/2     | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 49        | 29.7%   |
| 101-110        | 46        | 27.88%  |
| 201-250        | 22        | 13.33%  |
| 301-350        | 12        | 7.27%   |
| 351-500        | 7         | 4.24%   |
| 251-300        | 6         | 3.64%   |
| 71-80          | 5         | 3.03%   |
| 61-70          | 5         | 3.03%   |
| 121-130        | 3         | 1.82%   |
| 111-120        | 3         | 1.82%   |
| Unknown        | 3         | 1.82%   |
| 151-200        | 2         | 1.21%   |
| 141-150        | 1         | 0.61%   |
| 501-1000       | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 83        | 51.88%  |
| 51-100        | 35        | 21.88%  |
| 101-120       | 26        | 16.25%  |
| 161-240       | 7         | 4.38%   |
| More than 240 | 6         | 3.75%   |
| Unknown       | 3         | 1.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 74        | 57.81%  |
| 2     | 41        | 32.03%  |
| 3     | 7         | 5.47%   |
| 0     | 6         | 4.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 105       | 57.07%  |
| Realtek Semiconductor             | 32        | 17.39%  |
| Lenovo                            | 18        | 9.78%   |
| Qualcomm Atheros                  | 5         | 2.72%   |
| Sierra Wireless                   | 2         | 1.09%   |
| MediaTek                          | 2         | 1.09%   |
| Marvell Technology Group          | 2         | 1.09%   |
| Broadcom Limited                  | 2         | 1.09%   |
| ASIX Electronics                  | 2         | 1.09%   |
| Xiaomi                            | 1         | 0.54%   |
| TP-Link                           | 1         | 0.54%   |
| Samsung Electronics               | 1         | 0.54%   |
| Ralink                            | 1         | 0.54%   |
| Qualcomm Atheros Communications   | 1         | 0.54%   |
| Luminary Micro                    | 1         | 0.54%   |
| ICS Advent                        | 1         | 0.54%   |
| Huawei Technologies               | 1         | 0.54%   |
| Google                            | 1         | 0.54%   |
| Ericsson Business Mobile Networks | 1         | 0.54%   |
| DisplayLink                       | 1         | 0.54%   |
| Dell                              | 1         | 0.54%   |
| Broadcom                          | 1         | 0.54%   |
| Aquantia                          | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 17        | 6.56%   |
| Intel Wireless 8265 / 8275                                                     | 15        | 5.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 13        | 5.02%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 13        | 5.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 13        | 5.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 4.25%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 3.86%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 3.86%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 3.86%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 2.7%    |
| Intel Wireless 8260                                                            | 7         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                                | 7         | 2.7%    |
| Intel Wi-Fi 6 AX201                                                            | 6         | 2.32%   |
| Intel Wi-Fi 6 AX200                                                            | 6         | 2.32%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 2.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 2.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 1.54%   |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 1.54%   |
| Lenovo USB-C to LAN                                                            | 3         | 1.16%   |
| Intel Wireless 7265                                                            | 3         | 1.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 3         | 1.16%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.16%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 1.16%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 2         | 0.77%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.77%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.77%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.77%   |
| Intel Wireless 3165                                                            | 2         | 0.77%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 2         | 0.77%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.77%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 81.75%  |
| Realtek Semiconductor           | 8         | 6.35%   |
| Qualcomm Atheros                | 5         | 3.97%   |
| Sierra Wireless                 | 2         | 1.59%   |
| MediaTek                        | 2         | 1.59%   |
| TP-Link                         | 1         | 0.79%   |
| Ralink                          | 1         | 0.79%   |
| Qualcomm Atheros Communications | 1         | 0.79%   |
| Dell                            | 1         | 0.79%   |
| Broadcom Limited                | 1         | 0.79%   |
| Broadcom                        | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                   | 15        | 11.9%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                            | 13        | 10.32%  |
| Intel Comet Lake PCH CNVi WiFi                                               | 13        | 10.32%  |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                     | 13        | 10.32%  |
| Intel Wireless 8260                                                          | 7         | 5.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 7         | 5.56%   |
| Intel Wi-Fi 6 AX201                                                          | 6         | 4.76%   |
| Intel Wi-Fi 6 AX200                                                          | 6         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                 | 6         | 4.76%   |
| Intel Centrino Ultimate-N 6300                                               | 4         | 3.17%   |
| Intel Wireless 7265                                                          | 3         | 2.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                    | 3         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                     | 2         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                   | 2         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                   | 2         | 1.59%   |
| Intel Wireless 3165                                                          | 2         | 1.59%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                      | 2         | 1.59%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                       | 1         | 0.79%   |
| Sierra Wireless Sierra Wireless EM7431 QualcommÂ Snapdragonâ¢ X16 LTE-A | 1         | 0.79%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                              | 1         | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                     | 1         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                              | 1         | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                                   | 1         | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                      | 1         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                    | 1         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                   | 1         | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                              | 1         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 1         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)               | 1         | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                | 1         | 0.79%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                          | 1         | 0.79%   |
| Intel Raptor Lake PCH CNVi WiFi                                              | 1         | 0.79%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                | 1         | 0.79%   |
| Intel Alder Lake-S PCH CNVi WiFi                                             | 1         | 0.79%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                         | 1         | 0.79%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter         | 1         | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                                | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 73        | 56.15%  |
| Realtek Semiconductor    | 27        | 20.77%  |
| Lenovo                   | 18        | 13.85%  |
| Marvell Technology Group | 2         | 1.54%   |
| ASIX Electronics         | 2         | 1.54%   |
| Xiaomi                   | 1         | 0.77%   |
| Samsung Electronics      | 1         | 0.77%   |
| ICS Advent               | 1         | 0.77%   |
| Huawei Technologies      | 1         | 0.77%   |
| Google                   | 1         | 0.77%   |
| DisplayLink              | 1         | 0.77%   |
| Broadcom Limited         | 1         | 0.77%   |
| Aquantia                 | 1         | 0.77%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 17        | 12.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 8.4%    |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 7.63%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 7.63%   |
| Intel Ethernet Connection (10) I219-LM                                         | 10        | 7.63%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 9         | 6.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 5.34%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 3.05%   |
| Lenovo USB-C to LAN                                                            | 3         | 2.29%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 2.29%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 2.29%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 2.29%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 2.29%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.53%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 1.53%   |
| Lenovo ThinkPad Lan                                                            | 2         | 1.53%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.53%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.53%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.53%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 1.53%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.76%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.76%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.76%   |
| Intel Ethernet Controller I225-LM                                              | 1         | 0.76%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.76%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1         | 0.76%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.76%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.76%   |
| Huawei E353/E3131                                                              | 1         | 0.76%   |
| Google Pixel 7 Pro                                                             | 1         | 0.76%   |
| DisplayLink Plugable UGA-2KHDMI                                                | 1         | 0.76%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.76%   |
| Aquantia 5G USB Ethernet Adapter                                               | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 52.4%   |
| Ethernet | 107       | 46.72%  |
| Modem    | 2         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 89        | 66.42%  |
| Ethernet | 45        | 33.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 96        | 79.34%  |
| 1     | 25        | 20.66%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 111       | 90.98%  |
| Yes  | 11        | 9.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 79        | 79.8%   |
| Broadcom                        | 6         | 6.06%   |
| IMC Networks                    | 3         | 3.03%   |
| Foxconn / Hon Hai               | 3         | 3.03%   |
| Realtek Semiconductor           | 2         | 2.02%   |
| Qualcomm Atheros Communications | 2         | 2.02%   |
| Cambridge Silicon Radio         | 2         | 2.02%   |
| Ralink                          | 1         | 1.01%   |
| Dell                            | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 31        | 31.31%  |
| Intel Bluetooth Device                                                              | 16        | 16.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 16.16%  |
| Intel AX200 Bluetooth                                                               | 6         | 6.06%   |
| Intel Bluetooth wireless interface                                                  | 4         | 4.04%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.03%   |
| Intel AX211 Bluetooth                                                               | 2         | 2.02%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.01%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.01%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.01%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.01%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 1.01%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.01%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.01%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.01%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.01%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.01%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.01%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 113       | 61.41%  |
| Nvidia                 | 20        | 10.87%  |
| Lenovo                 | 14        | 7.61%   |
| AMD                    | 11        | 5.98%   |
| GN Netcom              | 5         | 2.72%   |
| Plantronics            | 3         | 1.63%   |
| Texas Instruments      | 2         | 1.09%   |
| Realtek Semiconductor  | 2         | 1.09%   |
| JMTek                  | 2         | 1.09%   |
| Generalplus Technology | 2         | 1.09%   |
| C-Media Electronics    | 2         | 1.09%   |
| Logitech               | 1         | 0.54%   |
| Hewlett-Packard        | 1         | 0.54%   |
| Google                 | 1         | 0.54%   |
| Focusrite-Novation     | 1         | 0.54%   |
| DSEA A/S               | 1         | 0.54%   |
| Dell                   | 1         | 0.54%   |
| Corsair                | 1         | 0.54%   |
| Blue Microphones       | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 23        | 11.79%  |
| Intel Cannon Point-LP High Definition Audio Controller                            | 15        | 7.69%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 13        | 6.67%   |
| Intel Comet Lake PCH cAVS                                                         | 13        | 6.67%   |
| Intel Cannon Lake PCH cAVS                                                        | 11        | 5.64%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 9         | 4.62%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7         | 3.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 6         | 3.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 3.08%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 2.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 2.05%   |
| Plantronics BT600                                                                 | 3         | 1.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 1.54%   |
| Nvidia Audio device                                                               | 3         | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.54%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 1.54%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 1.54%   |
| Texas Instruments PCM2902 Audio Codec                                             | 2         | 1.03%   |
| Realtek Semiconductor USB Audio                                                   | 2         | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2         | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.03%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 1.03%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.03%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.03%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.03%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.51%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1         | 0.51%   |
| Logitech H555 Headset                                                             | 1         | 0.51%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                         | 1         | 0.51%   |
| Lenovo ThinkPad Dock Audio                                                        | 1         | 0.51%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 1         | 0.51%   |
| JMTek USB PnP Audio Device                                                        | 1         | 0.51%   |
| JMTek iTalk-02                                                                    | 1         | 0.51%   |
| Intel Raptor Lake-P/U/H cAVS                                                      | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 40.82%  |
| SK hynix            | 14        | 28.57%  |
| Micron Technology   | 3         | 6.12%   |
| Crucial             | 3         | 6.12%   |
| Unknown             | 2         | 4.08%   |
| Kingston            | 2         | 4.08%   |
| Unknown (0x0B5E)    | 1         | 2.04%   |
| Smart               | 1         | 2.04%   |
| Innodisk            | 1         | 2.04%   |
| GOODRAM             | 1         | 2.04%   |
| Elpida              | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 4         | 7.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 3.92%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 3.92%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s          | 2         | 3.92%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 3.92%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s        | 2         | 3.92%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s      | 1         | 1.96%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.96%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 1.96%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s          | 1         | 1.96%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.96%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.96%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.96%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 1.96%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.96%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s         | 1         | 1.96%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s         | 1         | 1.96%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s         | 1         | 1.96%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                    | 1         | 1.96%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.96%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Micron RAM 8KTF51264HZ-1G9E5 4GB SODIMM DDR3 1333MT/s           | 1         | 1.96%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s           | 1         | 1.96%   |
| Kingston RAM 99U5469-042.A00LF 4096MB SODIMM DDR3 1333MT/s      | 1         | 1.96%   |
| Innodisk RAM M4S0-BGS2OCEM 32GB SODIMM DDR4 3200MT/s            | 1         | 1.96%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s         | 1         | 1.96%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 23        | 60.53%  |
| DDR3   | 12        | 31.58%  |
| LPDDR4 | 1         | 2.63%   |
| LPDDR3 | 1         | 2.63%   |
| DDR5   | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 97.3%   |
| Row Of Chips | 1         | 2.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 16        | 39.02%  |
| 8192  | 13        | 31.71%  |
| 4096  | 9         | 21.95%  |
| 32768 | 3         | 7.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 13        | 32.5%   |
| 2667  | 9         | 22.5%   |
| 1600  | 9         | 22.5%   |
| 1333  | 3         | 7.5%    |
| 2400  | 2         | 5%      |
| 2133  | 2         | 5%      |
| 4800  | 1         | 2.5%    |
| 1334  | 1         | 2.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| HP ENVY 4500 series | 1         | 100%    |

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
| Chicony Electronics                    | 38        | 29.92%  |
| IMC Networks                           | 20        | 15.75%  |
| Bison Electronics                      | 12        | 9.45%   |
| Realtek Semiconductor                  | 11        | 8.66%   |
| Sunplus Innovation Technology          | 7         | 5.51%   |
| Microdia                               | 7         | 5.51%   |
| Logitech                               | 7         | 5.51%   |
| Lite-On Technology                     | 4         | 3.15%   |
| Suyin                                  | 3         | 2.36%   |
| Luxvisions Innotech Limited            | 3         | 2.36%   |
| Samsung Electronics                    | 2         | 1.57%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.57%   |
| Acer                                   | 2         | 1.57%   |
| Syntek                                 | 1         | 0.79%   |
| Ruision                                | 1         | 0.79%   |
| Remo Tech                              | 1         | 0.79%   |
| Quanta                                 | 1         | 0.79%   |
| Microsoft                              | 1         | 0.79%   |
| Lenovo                                 | 1         | 0.79%   |
| KYE Systems (Mouse Systems)            | 1         | 0.79%   |
| Hopewin Electronic Material            | 1         | 0.79%   |
| Creative Technology                    | 1         | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 20        | 15.38%  |
| IMC Networks Integrated Camera                    | 17        | 13.08%  |
| Realtek Integrated_Webcam_HD                      | 7         | 5.38%   |
| Bison Integrated Camera                           | 7         | 5.38%   |
| Bison SunplusIT Integrated Camera                 | 5         | 3.85%   |
| Logitech HD Pro Webcam C920                       | 4         | 3.08%   |
| Chicony Integrated Camera (1280x720@30)           | 4         | 3.08%   |
| Sunplus Integrated_Webcam_HD                      | 3         | 2.31%   |
| Lite-On Integrated Camera                         | 3         | 2.31%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 3         | 2.31%   |
| Chicony ThinkPad T490 Webcam                      | 3         | 2.31%   |
| Chicony HP HD Camera                              | 3         | 2.31%   |
| Samsung Galaxy series, misc. (MTP mode)           | 2         | 1.54%   |
| Microdia Webcam                                   | 2         | 1.54%   |
| Microdia Integrated Webcam                        | 2         | 1.54%   |
| Chicony Integrated Camera [ThinkPad]              | 2         | 1.54%   |
| Bison Integrated IR Camera                        | 2         | 1.54%   |
| Syntek Lenovo EasyCamera                          | 1         | 0.77%   |
| Suyin RGBIR Camera                                | 1         | 0.77%   |
| Suyin Integrated_Webcam_HD                        | 1         | 0.77%   |
| Suyin HP Truevision HD                            | 1         | 0.77%   |
| Sunplus USB2.0 Camera                             | 1         | 0.77%   |
| Sunplus PC Camera                                 | 1         | 0.77%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 0.77%   |
| Sunplus HP HD Webcam [Fixed]                      | 1         | 0.77%   |
| Ruision UVC Camera                                | 1         | 0.77%   |
| Remo Tech OBSBOT Tiny 4K                          | 1         | 0.77%   |
| Realtek USB2.0 VGA UVC WebCam                     | 1         | 0.77%   |
| Realtek USB Camera                                | 1         | 0.77%   |
| Realtek Thronmax Stream Go Pro Webcam             | 1         | 0.77%   |
| Realtek HP Webcam                                 | 1         | 0.77%   |
| Quanta HP HD Camera                               | 1         | 0.77%   |
| Microsoft LifeCam Cinema                          | 1         | 0.77%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 0.77%   |
| Microdia Laptop_Integrated_Webcam_E4HD            | 1         | 0.77%   |
| Microdia Integrated_Webcam_HD                     | 1         | 0.77%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 0.77%   |
| Luxvisions Innotech Limited HP HD Camera          | 1         | 0.77%   |
| Luxvisions Innotech Limited HP 5MP Camera         | 1         | 0.77%   |
| Logitech Webcam C925e                             | 1         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 34        | 64.15%  |
| Validity Sensors           | 14        | 26.42%  |
| Upek                       | 2         | 3.77%   |
| Shenzhen Goodix Technology | 2         | 3.77%   |
| Elan Microelectronics      | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 43.4%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 11.32%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 5.66%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.77%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 3.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.89%   |
| Validity Sensors VFS491                                                    | 1         | 1.89%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.89%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.89%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.89%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.89%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.89%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 50%     |
| Alcor Micro | 5         | 31.25%  |
| Lenovo      | 2         | 12.5%   |
| Upek        | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                             | 5         | 31.25%  |
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 31.25%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 12.5%   |
| Broadcom 5880                                              | 2         | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 63        | 51.64%  |
| 0     | 41        | 33.61%  |
| 2     | 14        | 11.48%  |
| 3     | 3         | 2.46%   |
| 4     | 1         | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 53        | 51.46%  |
| Graphics card         | 15        | 14.56%  |
| Chipcard              | 13        | 12.62%  |
| Net/wireless          | 7         | 6.8%    |
| Multimedia controller | 4         | 3.88%   |
| Card reader           | 4         | 3.88%   |
| Net/ethernet          | 3         | 2.91%   |
| Bluetooth             | 3         | 2.91%   |
| Storage               | 1         | 0.97%   |

