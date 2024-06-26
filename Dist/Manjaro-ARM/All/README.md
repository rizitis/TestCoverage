Manjaro-ARM - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Manjaro-ARM.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro-ARM/Desktop/README.md) and [notebooks](/Dist/Manjaro-ARM/Notebook/README.md).

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

Total: 159

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [2793d6ee33](https://linux-hardware.org/?probe=2793d6ee33) | Apr 15, 2024 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [a7100603cf](https://linux-hardware.org/?probe=a7100603cf) | Apr 15, 2024 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fe721c2b8b](https://linux-hardware.org/?probe=fe721c2b8b) | Mar 27, 2024 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [796c7c1066](https://linux-hardware.org/?probe=796c7c1066) | Feb 28, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [16ecae0578](https://linux-hardware.org/?probe=16ecae0578) | Jan 08, 2024 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [961dddc49e](https://linux-hardware.org/?probe=961dddc49e) | Dec 22, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [1b0dd94e69](https://linux-hardware.org/?probe=1b0dd94e69) | Nov 30, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [29d00359b8](https://linux-hardware.org/?probe=29d00359b8) | Nov 28, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [35e990cfea](https://linux-hardware.org/?probe=35e990cfea) | Sep 07, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [80e1d849fd](https://linux-hardware.org/?probe=80e1d849fd) | Sep 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0aaecbe0a9](https://linux-hardware.org/?probe=0aaecbe0a9) | Aug 18, 2023 |
| Ugoos         | AM6b Plus                   | Soc         | [a5ff8e9a5d](https://linux-hardware.org/?probe=a5ff8e9a5d) | Jul 29, 2023 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [cd17b6716c](https://linux-hardware.org/?probe=cd17b6716c) | Jul 16, 2023 |
| Unknown       | Beelink GT-King Pro         | Soc         | [c3b05a3295](https://linux-hardware.org/?probe=c3b05a3295) | Jul 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a536b66fc6](https://linux-hardware.org/?probe=a536b66fc6) | Jun 29, 2023 |
| Unknown       | Beelink GT-King Pro         | Soc         | [766d906989](https://linux-hardware.org/?probe=766d906989) | Jun 13, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [e6effbe52e](https://linux-hardware.org/?probe=e6effbe52e) | Apr 11, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [5b53728575](https://linux-hardware.org/?probe=5b53728575) | Mar 26, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [4a8ec9290e](https://linux-hardware.org/?probe=4a8ec9290e) | Mar 12, 2023 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [121fcf8fd6](https://linux-hardware.org/?probe=121fcf8fd6) | Feb 12, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [dea7831935](https://linux-hardware.org/?probe=dea7831935) | Feb 10, 2023 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [09b7f2f81f](https://linux-hardware.org/?probe=09b7f2f81f) | Feb 10, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [a4e4317d4d](https://linux-hardware.org/?probe=a4e4317d4d) | Jan 24, 2023 |
| Pine Micro... | Pine64 PinePhonePro (DT)    | Phone       | [a3cfc48f91](https://linux-hardware.org/?probe=a3cfc48f91) | Jan 11, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [b8cb61c70a](https://linux-hardware.org/?probe=b8cb61c70a) | Dec 29, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [c8b4b6d3bc](https://linux-hardware.org/?probe=c8b4b6d3bc) | Dec 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7714ba77eb](https://linux-hardware.org/?probe=7714ba77eb) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8c140bbafc](https://linux-hardware.org/?probe=8c140bbafc) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5981154034](https://linux-hardware.org/?probe=5981154034) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0361b1083f](https://linux-hardware.org/?probe=0361b1083f) | Dec 20, 2022 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [760fd1ae84](https://linux-hardware.org/?probe=760fd1ae84) | Dec 13, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cc309bb44c](https://linux-hardware.org/?probe=cc309bb44c) | Nov 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a0d94329a6](https://linux-hardware.org/?probe=a0d94329a6) | Nov 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9f0e94860c](https://linux-hardware.org/?probe=9f0e94860c) | Nov 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [81f59ba6f5](https://linux-hardware.org/?probe=81f59ba6f5) | Nov 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3fe8b5fef3](https://linux-hardware.org/?probe=3fe8b5fef3) | Nov 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [012705552d](https://linux-hardware.org/?probe=012705552d) | Nov 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [34061efe0c](https://linux-hardware.org/?probe=34061efe0c) | Oct 25, 2022 |
| Radxa         | ROCK Pi 4B (DT)             | Soc         | [f05063925b](https://linux-hardware.org/?probe=f05063925b) | Oct 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7207f549c7](https://linux-hardware.org/?probe=7207f549c7) | Oct 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d18c649cb6](https://linux-hardware.org/?probe=d18c649cb6) | Oct 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f9dc4fff88](https://linux-hardware.org/?probe=f9dc4fff88) | Oct 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d2f6a610d9](https://linux-hardware.org/?probe=d2f6a610d9) | Oct 06, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ac0705feae](https://linux-hardware.org/?probe=ac0705feae) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0c25e7e0a0](https://linux-hardware.org/?probe=0c25e7e0a0) | Oct 02, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc3501546b](https://linux-hardware.org/?probe=bc3501546b) | Sep 28, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc6ffac174](https://linux-hardware.org/?probe=bc6ffac174) | Sep 11, 2022 |
| Unknown       | Unknown                     | Soc         | [6e8246d8bc](https://linux-hardware.org/?probe=6e8246d8bc) | Sep 05, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [533e62b70d](https://linux-hardware.org/?probe=533e62b70d) | Aug 20, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [2b238b3dc7](https://linux-hardware.org/?probe=2b238b3dc7) | Aug 19, 2022 |
| PINE64        | Pinebook Pro                | Soc         | [5f5c134bd6](https://linux-hardware.org/?probe=5f5c134bd6) | Aug 14, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [54465a49f5](https://linux-hardware.org/?probe=54465a49f5) | Aug 09, 2022 |
| Pine Micro... | Pine64 PinePhonePro (DT)    | Phone       | [7b62ba2ec4](https://linux-hardware.org/?probe=7b62ba2ec4) | Jul 31, 2022 |
| Unknown       | Beelink GT1                 | Soc         | [2e00352c95](https://linux-hardware.org/?probe=2e00352c95) | Jul 25, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8e2855140c](https://linux-hardware.org/?probe=8e2855140c) | Jul 24, 2022 |
| Unknown       | Unknown                     | Soc         | [ec9eb5536d](https://linux-hardware.org/?probe=ec9eb5536d) | Jul 18, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [03fca40d38](https://linux-hardware.org/?probe=03fca40d38) | Jul 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a9a3470242](https://linux-hardware.org/?probe=a9a3470242) | Jun 19, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8226efcb30](https://linux-hardware.org/?probe=8226efcb30) | Jun 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f2e5a856f4](https://linux-hardware.org/?probe=f2e5a856f4) | May 25, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [b31235961f](https://linux-hardware.org/?probe=b31235961f) | May 24, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [37f92aa173](https://linux-hardware.org/?probe=37f92aa173) | May 21, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [5a75c038d2](https://linux-hardware.org/?probe=5a75c038d2) | Apr 19, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8ff8aa816f](https://linux-hardware.org/?probe=8ff8aa816f) | Apr 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [93d20b6e00](https://linux-hardware.org/?probe=93d20b6e00) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [0e115f2126](https://linux-hardware.org/?probe=0e115f2126) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5c31fd2838](https://linux-hardware.org/?probe=5c31fd2838) | Apr 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b929783867](https://linux-hardware.org/?probe=b929783867) | Apr 08, 2022 |
| Unknown       | Unknown                     | Soc         | [509d960112](https://linux-hardware.org/?probe=509d960112) | Mar 30, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [235c763f19](https://linux-hardware.org/?probe=235c763f19) | Mar 28, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [f3c11793ee](https://linux-hardware.org/?probe=f3c11793ee) | Mar 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6b82f2f5f8](https://linux-hardware.org/?probe=6b82f2f5f8) | Mar 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bd24a29894](https://linux-hardware.org/?probe=bd24a29894) | Mar 11, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [6218135a7c](https://linux-hardware.org/?probe=6218135a7c) | Mar 06, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d2b091c26b](https://linux-hardware.org/?probe=d2b091c26b) | Feb 22, 2022 |
| Shenzhen A... | X96 Max                     | Soc         | [440ca2b84f](https://linux-hardware.org/?probe=440ca2b84f) | Feb 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [da8754f5d5](https://linux-hardware.org/?probe=da8754f5d5) | Jan 30, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d40ebefd39](https://linux-hardware.org/?probe=d40ebefd39) | Jan 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e21b25bba](https://linux-hardware.org/?probe=1e21b25bba) | Jan 12, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6d8df9807e](https://linux-hardware.org/?probe=6d8df9807e) | Jan 11, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6583550f14](https://linux-hardware.org/?probe=6583550f14) | Jan 11, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e6147adb9d](https://linux-hardware.org/?probe=e6147adb9d) | Dec 25, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [138b3d17bc](https://linux-hardware.org/?probe=138b3d17bc) | Dec 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2cfa03ec21](https://linux-hardware.org/?probe=2cfa03ec21) | Dec 23, 2021 |
| Unknown       | Beelink GT1                 | Soc         | [a8749745a4](https://linux-hardware.org/?probe=a8749745a4) | Dec 21, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [94f3848f94](https://linux-hardware.org/?probe=94f3848f94) | Dec 18, 2021 |
| Unknown       | Beelink GT1                 | Soc         | [51e764f297](https://linux-hardware.org/?probe=51e764f297) | Dec 17, 2021 |
| Unknown       | Beelink GT1                 | Soc         | [c5f5fd7e8f](https://linux-hardware.org/?probe=c5f5fd7e8f) | Dec 16, 2021 |
| Khadas        | VIM2                        | Soc         | [77b3e7305b](https://linux-hardware.org/?probe=77b3e7305b) | Dec 16, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [50d5c7e182](https://linux-hardware.org/?probe=50d5c7e182) | Dec 06, 2021 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [4239296e76](https://linux-hardware.org/?probe=4239296e76) | Dec 01, 2021 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [965f364f1d](https://linux-hardware.org/?probe=965f364f1d) | Nov 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c79ad4a8db](https://linux-hardware.org/?probe=c79ad4a8db) | Nov 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [077a2863fd](https://linux-hardware.org/?probe=077a2863fd) | Nov 05, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [20c4658fbc](https://linux-hardware.org/?probe=20c4658fbc) | Nov 04, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ac4e15828b](https://linux-hardware.org/?probe=ac4e15828b) | Nov 02, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b785cdc0bb](https://linux-hardware.org/?probe=b785cdc0bb) | Oct 30, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [df99169555](https://linux-hardware.org/?probe=df99169555) | Oct 30, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [4a5e673fe5](https://linux-hardware.org/?probe=4a5e673fe5) | Oct 14, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [52c09b147c](https://linux-hardware.org/?probe=52c09b147c) | Sep 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c189148518](https://linux-hardware.org/?probe=c189148518) | Sep 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9ef99e18e2](https://linux-hardware.org/?probe=9ef99e18e2) | Aug 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f7a1b3b0e4](https://linux-hardware.org/?probe=f7a1b3b0e4) | Aug 18, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bff99d5a7c](https://linux-hardware.org/?probe=bff99d5a7c) | Jul 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [f003dd4906](https://linux-hardware.org/?probe=f003dd4906) | Jul 23, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [ca01402661](https://linux-hardware.org/?probe=ca01402661) | Jul 03, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [64603b3562](https://linux-hardware.org/?probe=64603b3562) | Jul 02, 2021 |
| Lenovo        | Yoga C630-13Q50 81JL        | Tablet      | [805ea3b3c5](https://linux-hardware.org/?probe=805ea3b3c5) | Jul 01, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4020e881a1](https://linux-hardware.org/?probe=4020e881a1) | Jun 16, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [f1bc769db9](https://linux-hardware.org/?probe=f1bc769db9) | Jun 15, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7fa170e5ca](https://linux-hardware.org/?probe=7fa170e5ca) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [dc7b014ec9](https://linux-hardware.org/?probe=dc7b014ec9) | May 26, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [896bd98421](https://linux-hardware.org/?probe=896bd98421) | May 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [368044e19e](https://linux-hardware.org/?probe=368044e19e) | May 18, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e436e57831](https://linux-hardware.org/?probe=e436e57831) | May 17, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [07d8401514](https://linux-hardware.org/?probe=07d8401514) | May 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [321b9f409a](https://linux-hardware.org/?probe=321b9f409a) | May 14, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [2aee3702e9](https://linux-hardware.org/?probe=2aee3702e9) | May 08, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cf555f92bc](https://linux-hardware.org/?probe=cf555f92bc) | May 02, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [1f32cfa090](https://linux-hardware.org/?probe=1f32cfa090) | May 01, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [7d7e3bfc9f](https://linux-hardware.org/?probe=7d7e3bfc9f) | Apr 06, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [d97055c68d](https://linux-hardware.org/?probe=d97055c68d) | Apr 04, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [861c7906fa](https://linux-hardware.org/?probe=861c7906fa) | Mar 29, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [543a85726b](https://linux-hardware.org/?probe=543a85726b) | Mar 22, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [105dc78331](https://linux-hardware.org/?probe=105dc78331) | Mar 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae40e5f830](https://linux-hardware.org/?probe=ae40e5f830) | Mar 19, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [2ad000987e](https://linux-hardware.org/?probe=2ad000987e) | Mar 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6c54a4db87](https://linux-hardware.org/?probe=6c54a4db87) | Feb 13, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [7b691e6c3a](https://linux-hardware.org/?probe=7b691e6c3a) | Feb 04, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [7f2e3317b5](https://linux-hardware.org/?probe=7f2e3317b5) | Jan 30, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [24c4a691d7](https://linux-hardware.org/?probe=24c4a691d7) | Jan 30, 2021 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [d9070da088](https://linux-hardware.org/?probe=d9070da088) | Dec 20, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [947451c5ef](https://linux-hardware.org/?probe=947451c5ef) | Nov 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7b35e5e525](https://linux-hardware.org/?probe=7b35e5e525) | Nov 04, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c4e2010c1b](https://linux-hardware.org/?probe=c4e2010c1b) | Nov 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [169238c060](https://linux-hardware.org/?probe=169238c060) | Nov 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fb24852769](https://linux-hardware.org/?probe=fb24852769) | Nov 01, 2020 |
| Pine Micro... | PineTab                     | Soc         | [d3736a7d1f](https://linux-hardware.org/?probe=d3736a7d1f) | Sep 29, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [dabd07ba39](https://linux-hardware.org/?probe=dabd07ba39) | Sep 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [199d9ad3ff](https://linux-hardware.org/?probe=199d9ad3ff) | Sep 18, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6831742863](https://linux-hardware.org/?probe=6831742863) | Sep 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [b7a5bf61e7](https://linux-hardware.org/?probe=b7a5bf61e7) | Sep 16, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [903bc538dd](https://linux-hardware.org/?probe=903bc538dd) | Sep 16, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [0ccf4e6f67](https://linux-hardware.org/?probe=0ccf4e6f67) | Sep 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ec849f00fc](https://linux-hardware.org/?probe=ec849f00fc) | Sep 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [1ef25f0a09](https://linux-hardware.org/?probe=1ef25f0a09) | Sep 03, 2020 |
| PINE64        | Pinebook Pro                | Soc         | [0f15ee91d5](https://linux-hardware.org/?probe=0f15ee91d5) | Aug 25, 2020 |
| PINE64        | Pinebook Pro                | Soc         | [e7ac0707cd](https://linux-hardware.org/?probe=e7ac0707cd) | Aug 25, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2098b09526](https://linux-hardware.org/?probe=2098b09526) | Aug 17, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [b0d04bed01](https://linux-hardware.org/?probe=b0d04bed01) | Aug 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [454d02d902](https://linux-hardware.org/?probe=454d02d902) | Jul 22, 2020 |
| Unknown       | Unknown                     | Soc         | [4fa39ff4f7](https://linux-hardware.org/?probe=4fa39ff4f7) | Jul 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bccab0e704](https://linux-hardware.org/?probe=bccab0e704) | Jul 04, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [edb48aa099](https://linux-hardware.org/?probe=edb48aa099) | Jun 03, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1c8aa5a7be](https://linux-hardware.org/?probe=1c8aa5a7be) | Jun 03, 2020 |
| Radxa         | ROCK Pi 4                   | Soc         | [543099b0fa](https://linux-hardware.org/?probe=543099b0fa) | Mar 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [74359d777e](https://linux-hardware.org/?probe=74359d777e) | Mar 16, 2020 |
| Radxa         | ROCK Pi 4                   | Soc         | [688046c3d7](https://linux-hardware.org/?probe=688046c3d7) | Feb 01, 2020 |
| Radxa         | ROCK Pi 4                   | Soc         | [3d67546a89](https://linux-hardware.org/?probe=3d67546a89) | Jan 29, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Manjaro-ARM       | 73        | 65.77%  |
| Manjaro-ARM 21.10 | 8         | 7.21%   |
| Manjaro-ARM 23.02 | 5         | 4.5%    |
| Manjaro-ARM 22.01 | 4         | 3.6%    |
| Manjaro-ARM 22.09 | 2         | 1.8%    |
| Manjaro-ARM 22.07 | 2         | 1.8%    |
| Manjaro-ARM 22.03 | 2         | 1.8%    |
| Manjaro-ARM 20.09 | 2         | 1.8%    |
| Manjaro-ARM 24.03 | 1         | 0.9%    |
| Manjaro-ARM 23.01 | 1         | 0.9%    |
| Manjaro-ARM 22.12 | 1         | 0.9%    |
| Manjaro-ARM 22.06 | 1         | 0.9%    |
| Manjaro-ARM 22.05 | 1         | 0.9%    |
| Manjaro-ARM 21.08 | 1         | 0.9%    |
| Manjaro-ARM 21.06 | 1         | 0.9%    |
| Manjaro-ARM 21.05 | 1         | 0.9%    |
| Manjaro-ARM 21.03 | 1         | 0.9%    |
| Manjaro-ARM 20.12 | 1         | 0.9%    |
| Manjaro-ARM 20.10 | 1         | 0.9%    |
| Manjaro-ARM 20.03 | 1         | 0.9%    |
| Manjaro-ARM 19.12 | 1         | 0.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Manjaro-ARM | 101       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.7-1-MANJARO-ARM        | 4         | 3.25%   |
| 5.10.74-1-MANJARO-ARM       | 4         | 3.25%   |
| 6.2.5-1-MANJARO-ARM         | 3         | 2.44%   |
| 6.1.7-1-MANJARO-ARM         | 3         | 2.44%   |
| 5.15.24-1-MANJARO-ARM-RPI   | 3         | 2.44%   |
| 6.6.7-1-MANJARO-ARM         | 2         | 1.63%   |
| 6.1.37-1-MANJARO-ARM-RPI    | 2         | 1.63%   |
| 5.9.1-3-MANJARO-ARM         | 2         | 1.63%   |
| 5.8.3-2-MANJARO-ARM         | 2         | 1.63%   |
| 5.4.61-1-MANJARO-ARM        | 2         | 1.63%   |
| 5.19.1-1-MANJARO-ARM        | 2         | 1.63%   |
| 5.18.9-1-MANJARO-ARM        | 2         | 1.63%   |
| 5.16.16-1-MANJARO-ARM       | 2         | 1.63%   |
| 5.15.70-1-MANJARO-ARM-RPI   | 2         | 1.63%   |
| 5.11.6-2-MANJARO-ARM        | 2         | 1.63%   |
| 5.11.3-1-MANJARO-ARM        | 2         | 1.63%   |
| 5.11.17-1-MANJARO-ARM       | 2         | 1.63%   |
| 5.10.88-1-MANJARO-ARM-RPI   | 2         | 1.63%   |
| 5.10.36-1-MANJARO-ARM       | 2         | 1.63%   |
| 4.19.127-1-MANJARO-ARM      | 2         | 1.63%   |
| 6.7.9-1-MANJARO-ARM         | 1         | 0.81%   |
| 6.5.7-1-MANJARO-ARM         | 1         | 0.81%   |
| 6.4.4-1-MANJARO-ARM         | 1         | 0.81%   |
| 6.3.9-1-MANJARO-ARM         | 1         | 0.81%   |
| 6.3.11-1-MANJARO-ARM        | 1         | 0.81%   |
| 6.1.69-1-MANJARO-RPI4       | 1         | 0.81%   |
| 6.1.35-1-MANJARO-ARM-AML    | 1         | 0.81%   |
| 6.1.34-1-MANJARO-ARM-RPI    | 1         | 0.81%   |
| 6.1.33-1-MANJARO-ARM-AML    | 1         | 0.81%   |
| 6.1.0-rc8-1-MANJARO-ARM-RPI | 1         | 0.81%   |
| 6.1.0-rc8-1-MANJARO-ARM     | 1         | 0.81%   |
| 6.1.0-rc1-2-MANJARO-ARM-RPI | 1         | 0.81%   |
| 6.1.0-2-MANJARO-ARM         | 1         | 0.81%   |
| 6.1.0-1-MANJARO-ARM         | 1         | 0.81%   |
| 6.0.3-1-MANJARO-ARM         | 1         | 0.81%   |
| 6.0.12-1-MANJARO-ARM        | 1         | 0.81%   |
| 5.9.12-1-MANJARO-ARM        | 1         | 0.81%   |
| 5.9.0-rc7-1-MANJARO-ARM     | 1         | 0.81%   |
| 5.8.6-1-MANJARO-ARM         | 1         | 0.81%   |
| 5.8.5-1-MANJARO-ARM         | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.0    | 4         | 3.33%   |
| 5.15.7   | 4         | 3.33%   |
| 5.10.74  | 4         | 3.33%   |
| 6.2.5    | 3         | 2.5%    |
| 6.1.7    | 3         | 2.5%    |
| 5.15.24  | 3         | 2.5%    |
| 5.11.6   | 3         | 2.5%    |
| 6.6.7    | 2         | 1.67%   |
| 6.1.37   | 2         | 1.67%   |
| 5.9.1    | 2         | 1.67%   |
| 5.8.3    | 2         | 1.67%   |
| 5.7.0    | 2         | 1.67%   |
| 5.4.61   | 2         | 1.67%   |
| 5.19.1   | 2         | 1.67%   |
| 5.19.0   | 2         | 1.67%   |
| 5.18.9   | 2         | 1.67%   |
| 5.16.16  | 2         | 1.67%   |
| 5.15.70  | 2         | 1.67%   |
| 5.11.3   | 2         | 1.67%   |
| 5.11.17  | 2         | 1.67%   |
| 5.11.0   | 2         | 1.67%   |
| 5.10.88  | 2         | 1.67%   |
| 5.10.36  | 2         | 1.67%   |
| 4.19.127 | 2         | 1.67%   |
| 6.7.9    | 1         | 0.83%   |
| 6.5.7    | 1         | 0.83%   |
| 6.4.4    | 1         | 0.83%   |
| 6.3.9    | 1         | 0.83%   |
| 6.3.11   | 1         | 0.83%   |
| 6.1.69   | 1         | 0.83%   |
| 6.1.35   | 1         | 0.83%   |
| 6.1.34   | 1         | 0.83%   |
| 6.1.33   | 1         | 0.83%   |
| 6.0.3    | 1         | 0.83%   |
| 6.0.12   | 1         | 0.83%   |
| 5.9.12   | 1         | 0.83%   |
| 5.9.0    | 1         | 0.83%   |
| 5.8.6    | 1         | 0.83%   |
| 5.8.5    | 1         | 0.83%   |
| 5.8.12   | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 18.58%  |
| 6.1     | 12        | 10.62%  |
| 5.15    | 12        | 10.62%  |
| 5.11    | 10        | 8.85%   |
| 5.18    | 7         | 6.19%   |
| 5.8     | 5         | 4.42%   |
| 5.4     | 5         | 4.42%   |
| 5.19    | 5         | 4.42%   |
| 5.9     | 4         | 3.54%   |
| 5.16    | 4         | 3.54%   |
| 6.2     | 3         | 2.65%   |
| 5.7     | 3         | 2.65%   |
| 5.17    | 3         | 2.65%   |
| 5.12    | 3         | 2.65%   |
| 4.19    | 3         | 2.65%   |
| 6.6     | 2         | 1.77%   |
| 6.3     | 2         | 1.77%   |
| 6.0     | 2         | 1.77%   |
| 5.14    | 2         | 1.77%   |
| 6.7     | 1         | 0.88%   |
| 6.5     | 1         | 0.88%   |
| 6.4     | 1         | 0.88%   |
| 5.6     | 1         | 0.88%   |
| 5.5     | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| aarch64 | 101       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KDE5        | 38        | 36.19%  |
| KDE         | 22        | 20.95%  |
| XFCE        | 16        | 15.24%  |
| GNOME       | 12        | 11.43%  |
| Unknown     | 5         | 4.76%   |
| MATE        | 4         | 3.81%   |
| X-Cinnamon  | 3         | 2.86%   |
| Phosh:GNOME | 2         | 1.9%    |
| sway        | 1         | 0.95%   |
| LXQt        | 1         | 0.95%   |
| dwl         | 1         | 0.95%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 56        | 54.9%   |
| Wayland | 37        | 36.27%  |
| Tty     | 6         | 5.88%   |
| Unknown | 3         | 2.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 75        | 72.82%  |
| SDDM    | 13        | 12.62%  |
| LightDM | 7         | 6.8%    |
| GDM     | 6         | 5.83%   |
| TDM     | 2         | 1.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 54        | 51.92%  |
| fr_FR   | 9         | 8.65%   |
| C       | 7         | 6.73%   |
| en_GB   | 5         | 4.81%   |
| en_CA   | 5         | 4.81%   |
| de_DE   | 5         | 4.81%   |
| ru_RU   | 2         | 1.92%   |
| en_AU   | 2         | 1.92%   |
| Unknown | 2         | 1.92%   |
| pt_PT   | 1         | 0.96%   |
| pl_PL   | 1         | 0.96%   |
| nl_NL   | 1         | 0.96%   |
| lt_LT   | 1         | 0.96%   |
| it_IT   | 1         | 0.96%   |
| it_CH   | 1         | 0.96%   |
| es_PE   | 1         | 0.96%   |
| es_ES   | 1         | 0.96%   |
| en_ZA   | 1         | 0.96%   |
| de_CH   | 1         | 0.96%   |
| de_AT   | 1         | 0.96%   |
| da_DK   | 1         | 0.96%   |
| bg_BG   | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 67        | 65.05%  |
| BIOS | 36        | 34.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 97        | 96.04%  |
| F2fs  | 2         | 1.98%   |
| Btrfs | 2         | 1.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 72        | 70.59%  |
| GPT     | 16        | 15.69%  |
| MBR     | 14        | 13.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 94        | 93.07%  |
| Yes       | 7         | 6.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 97.03%  |
| Yes       | 3         | 2.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Pine Microsystems              | 47        | 46.53%  |
| Raspberry Pi Foundation        | 38        | 37.62%  |
| Unknown                        | 7         | 6.93%   |
| Radxa                          | 2         | 1.98%   |
| PINE64                         | 2         | 1.98%   |
| Ugoos                          | 1         | 0.99%   |
| Shenzhen Amediatech Technology | 1         | 0.99%   |
| Lenovo                         | 1         | 0.99%   |
| Khadas                         | 1         | 0.99%   |
| Hardkernel                     | 1         | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Pine Microsystems Pine64 PinePhone (1.2)   | 19        | 18.81%  |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 17        | 16.83%  |
| Pine Microsystems Pine64 Pinebook Pro      | 16        | 15.84%  |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 7         | 6.93%   |
| Unknown                                    | 7         | 6.93%   |
| Pine Microsystems Pine64 PinePhonePro      | 6         | 5.94%   |
| RPi Raspberry Pi 400 Rev 1.0               | 4         | 3.96%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 4         | 3.96%   |
| RPi Raspberry Pi                           | 3         | 2.97%   |
| Pine Microsystems Pine64 RK3566 Quartz64-A | 3         | 2.97%   |
| RPi Raspberry Pi 4 Model B Rev 1.5         | 2         | 1.98%   |
| PINE64 Pinebook Pro                        | 2         | 1.98%   |
| Pine Microsystems Pine64 PinePhonePro (DT) | 2         | 1.98%   |
| Ugoos AM6b Plus                            | 1         | 0.99%   |
| Shenzhen Amediatech X96 Max                | 1         | 0.99%   |
| RPi Raspberry Pi 400 Rev 1.1               | 1         | 0.99%   |
| Radxa ROCK Pi 4B (DT)                      | 1         | 0.99%   |
| Radxa ROCK Pi 4                            | 1         | 0.99%   |
| Pine Microsystems PineTab                  | 1         | 0.99%   |
| Lenovo Yoga C630-13Q50 81JL                | 1         | 0.99%   |
| Khadas VIM2                                | 1         | 0.99%   |
| Hardkernel ODROID-N2Plus                   | 1         | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Pine Microsystems Pine64  | 46        | 45.54%  |
| RPi Raspberry             | 38        | 37.62%  |
| Unknown                   | 7         | 6.93%   |
| Radxa ROCK                | 2         | 1.98%   |
| PINE64 Pinebook           | 2         | 1.98%   |
| Ugoos AM6b                | 1         | 0.99%   |
| Shenzhen Amediatech X96   | 1         | 0.99%   |
| Pine Microsystems PineTab | 1         | 0.99%   |
| Lenovo Yoga               | 1         | 0.99%   |
| Khadas VIM2               | 1         | 0.99%   |
| Hardkernel ODROID-N2Plus  | 1         | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 87.13%  |
| 2020    | 10        | 9.9%    |
| 2021    | 2         | 1.98%   |
| 2019    | 1         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| System on chip | 57        | 56.44%  |
| Phone          | 27        | 26.73%  |
| Notebook       | 16        | 15.84%  |
| Tablet         | 1         | 0.99%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 101       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 101       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 70        | 69.31%  |
| 4.01-8.0   | 18        | 17.82%  |
| 1.01-2.0   | 7         | 6.93%   |
| 2.01-3.0   | 6         | 5.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 61        | 56.48%  |
| 2.01-3.0 | 22        | 20.37%  |
| 0.51-1.0 | 21        | 19.44%  |
| 0.01-0.5 | 3         | 2.78%   |
| 3.01-4.0 | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 64.49%  |
| 2      | 33        | 30.84%  |
| 0      | 4         | 3.74%   |
| 3      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 99.01%  |
| Yes       | 1         | 0.99%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 88.35%  |
| Yes       | 12        | 11.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 65.38%  |
| Yes       | 36        | 34.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 98.04%  |
| Yes       | 2         | 1.96%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 40        | 39.6%   |
| France       | 11        | 10.89%  |
| Germany      | 7         | 6.93%   |
| Canada       | 6         | 5.94%   |
| UK           | 5         | 4.95%   |
| Australia    | 5         | 4.95%   |
| Russia       | 3         | 2.97%   |
| Netherlands  | 3         | 2.97%   |
| Switzerland  | 2         | 1.98%   |
| Spain        | 2         | 1.98%   |
| Portugal     | 2         | 1.98%   |
| Italy        | 2         | 1.98%   |
| Turkey       | 1         | 0.99%   |
| Sweden       | 1         | 0.99%   |
| South Africa | 1         | 0.99%   |
| Poland       | 1         | 0.99%   |
| Peru         | 1         | 0.99%   |
| Malta        | 1         | 0.99%   |
| Lithuania    | 1         | 0.99%   |
| Kuwait       | 1         | 0.99%   |
| India        | 1         | 0.99%   |
| Finland      | 1         | 0.99%   |
| Denmark      | 1         | 0.99%   |
| Cyprus       | 1         | 0.99%   |
| Bulgaria     | 1         | 0.99%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Greoux-les-Bains       | 5         | 4.59%   |
| Paris                  | 2         | 1.83%   |
| Mississauga            | 2         | 1.83%   |
| London                 | 2         | 1.83%   |
| Denver                 | 2         | 1.83%   |
| Berlin                 | 2         | 1.83%   |
| Adelaide               | 2         | 1.83%   |
| Yaroslavl              | 1         | 0.92%   |
| Wooster                | 1         | 0.92%   |
| Woodville              | 1         | 0.92%   |
| Weinheim               | 1         | 0.92%   |
| Viseu                  | 1         | 0.92%   |
| Virginia Beach         | 1         | 0.92%   |
| Vallauris              | 1         | 0.92%   |
| Union City             | 1         | 0.92%   |
| Ulyanovsk              | 1         | 0.92%   |
| Toronto                | 1         | 0.92%   |
| Thun                   | 1         | 0.92%   |
| Sydney                 | 1         | 0.92%   |
| Strasbourg             | 1         | 0.92%   |
| Springboro             | 1         | 0.92%   |
| Sofia                  | 1         | 0.92%   |
| San Pawl il-Bahar      | 1         | 0.92%   |
| San Mateo              | 1         | 0.92%   |
| San Germano Vercellese | 1         | 0.92%   |
| San Francisco          | 1         | 0.92%   |
| San Diego              | 1         | 0.92%   |
| Saint-Martin-d'Hères  | 1         | 0.92%   |
| Rotterdam              | 1         | 0.92%   |
| Redding                | 1         | 0.92%   |
| Potomac                | 1         | 0.92%   |
| Portland               | 1         | 0.92%   |
| Pinetop-Lakeside       | 1         | 0.92%   |
| Perth                  | 1         | 0.92%   |
| Perm                   | 1         | 0.92%   |
| Pasadena               | 1         | 0.92%   |
| Pabianice              | 1         | 0.92%   |
| Ontario                | 1         | 0.92%   |
| Nottingham             | 1         | 0.92%   |
| North Battleford       | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 90        | 129    | 78.26%  |
| Seagate             | 4         | 7      | 3.48%   |
| SanDisk             | 4         | 5      | 3.48%   |
| ASMT                | 3         | 3      | 2.61%   |
| Toshiba             | 2         | 2      | 1.74%   |
| SK hynix            | 2         | 3      | 1.74%   |
| Argon               | 2         | 3      | 1.74%   |
| USB3.0              | 1         | 1      | 0.87%   |
| Samsung Electronics | 1         | 6      | 0.87%   |
| PNY USB             | 1         | 1      | 0.87%   |
| Phison              | 1         | 1      | 0.87%   |
| LaCie               | 1         | 1      | 0.87%   |
| Kingston            | 1         | 1      | 0.87%   |
| Intel               | 1         | 1      | 0.87%   |
| Best Buy            | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown MMC Card  32GB          | 29        | 21.8%   |
| Unknown MMC Card  64GB          | 27        | 20.3%   |
| Unknown MMC Card  128GB         | 22        | 16.54%  |
| Unknown SLD32G  32GB            | 5         | 3.76%   |
| Unknown SE32G  32GB             | 5         | 3.76%   |
| Unknown MMC Card  16GB          | 4         | 3.01%   |
| Unknown DA4064  64GB            | 4         | 3.01%   |
| Unknown MMC Card  256GB         | 3         | 2.26%   |
| ASMT 2115 128GB                 | 3         | 2.26%   |
| Seagate Expansion 2TB           | 2         | 1.5%    |
| Argon Forty 120GB               | 2         | 1.5%    |
| USB3.0 Disk 2TB                 | 1         | 0.75%   |
| Unknown SN64G  64GB             | 1         | 0.75%   |
| Unknown SN128  128GB            | 1         | 0.75%   |
| Unknown SL64G  64GB             | 1         | 0.75%   |
| Unknown SC32G  32GB             | 1         | 0.75%   |
| Unknown MMC Card  512GB         | 1         | 0.75%   |
| Unknown MMC Card  272GB         | 1         | 0.75%   |
| Unknown MMC Card  249GB         | 1         | 0.75%   |
| Unknown CJTD4R  64GB            | 1         | 0.75%   |
| Toshiba NVMe SSD Drive 256GB    | 1         | 0.75%   |
| Toshiba HDWD240 4TB             | 1         | 0.75%   |
| SK hynix PC611 NVMe 512GB       | 1         | 0.75%   |
| SK hynix HBG4e  32GB            | 1         | 0.75%   |
| Seagate ST925031 5AS 250GB      | 1         | 0.75%   |
| Seagate Expansion+ Desk 4TB     | 1         | 0.75%   |
| SanDisk SSD PLUS 240GB          | 1         | 0.75%   |
| SanDisk SL32G  32GB             | 1         | 0.75%   |
| SanDisk Portable SSD 1TB        | 1         | 0.75%   |
| SanDisk Extreme 55AE 1TB SSD    | 1         | 0.75%   |
| Samsung PSSD T7 500GB           | 1         | 0.75%   |
| Samsung Portable SSD T5 500GB   | 1         | 0.75%   |
| PNY USB 3.0 to SATA- 1TB SSD    | 1         | 0.75%   |
| Phison NVMe SSD Drive 256GB     | 1         | 0.75%   |
| LaCie Rugged USB-C 5TB          | 1         | 0.75%   |
| Kingston SHFS37A120G 120GB SSD  | 1         | 0.75%   |
| Intel NVMe SSD Drive 512GB      | 1         | 0.75%   |
| Best Buy NS-PCNVMEHDE(-C) 512GB | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 7      | 66.67%  |
| USB3.0  | 1         | 1      | 16.67%  |
| Toshiba | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 27.27%  |
| ASMT                | 3         | 3      | 27.27%  |
| Argon               | 2         | 3      | 18.18%  |
| Samsung Electronics | 1         | 6      | 9.09%   |
| PNY USB             | 1         | 1      | 9.09%   |
| Kingston            | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| MMC     | 90        | 133    | 80.36%  |
| SSD     | 11        | 17     | 9.82%   |
| HDD     | 5         | 9      | 4.46%   |
| NVMe    | 4         | 4      | 3.57%   |
| Unknown | 2         | 2      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| MMC  | 90        | 133    | 79.65%  |
| SAS  | 18        | 27     | 15.93%  |
| NVMe | 4         | 4      | 3.54%   |
| SATA | 1         | 1      | 0.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9         | 16     | 56.25%  |
| 1.01-2.0   | 3         | 5      | 18.75%  |
| 0.51-1.0   | 3         | 3      | 18.75%  |
| 3.01-4.0   | 1         | 2      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 29        | 27.1%   |
| 51-100         | 28        | 26.17%  |
| 101-250        | 27        | 25.23%  |
| 251-500        | 11        | 10.28%  |
| 1-20           | 4         | 3.74%   |
| 501-1000       | 4         | 3.74%   |
| 1001-2000      | 2         | 1.87%   |
| More than 3000 | 1         | 0.93%   |
| Unknown        | 1         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 60        | 54.55%  |
| 21-50     | 32        | 29.09%  |
| 51-100    | 9         | 8.18%   |
| 101-250   | 4         | 3.64%   |
| 251-500   | 3         | 2.73%   |
| 1001-2000 | 1         | 0.91%   |
| Unknown   | 1         | 0.91%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 97        | 161    | 96.04%  |
| Works    | 4         | 4      | 3.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Toshiba America Info Systems | 1         | 20%     |
| SK hynix                     | 1         | 20%     |
| Phison Electronics           | 1         | 20%     |
| LSI Logic / Symbios Logic    | 1         | 20%     |
| Intel                        | 1         | 20%     |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba America Info Systems XG6 NVMe SSD Controller | 1         | 20%     |
| SK hynix PC611 NVMe Solid State Drive                | 1         | 20%     |
| Phison E12 NVMe Controller                           | 1         | 20%     |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon] | 1         | 20%     |
| Intel SSD 660P Series                                | 1         | 20%     |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 4         | 80%     |
| RAID | 1         | 20%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| ARM      | 100       | 99.01%  |
| QUALCOMM | 1         | 0.99%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| ARM Processor      | 100       | 99.01%  |
| QUALCOMM Processor | 1         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model | Computers | Percent |
|-------|-----------|---------|
| Other | 101       | 100%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 42        | 40.78%  |
| Unknown | 30        | 29.13%  |
| 2       | 17        | 16.5%   |
| 6       | 14        | 13.59%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 59        | 57.28%  |
| Unknown | 30        | 29.13%  |
| 2       | 14        | 13.59%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 72        | 70.59%  |
| Unknown | 30        | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 64-bit         | 59        | 56.73%  |
| 32-bit, 64-bit | 27        | 25.96%  |
| Unknown        | 18        | 17.31%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 101       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 101       | 100%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

Zero info for selected period =(

GPU Model
---------

Graphics card models

Zero info for selected period =(

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Other | 101       | 100%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 101       | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 13        | 24.53%  |
| Dell                 | 5         | 9.43%   |
| AOC                  | 4         | 7.55%   |
| Philips              | 3         | 5.66%   |
| Iiyama               | 3         | 5.66%   |
| Hewlett-Packard      | 3         | 5.66%   |
| Ancor Communications | 3         | 5.66%   |
| Sceptre Tech         | 2         | 3.77%   |
| BenQ                 | 2         | 3.77%   |
| ASUSTek Computer     | 2         | 3.77%   |
| ViewSonic            | 1         | 1.89%   |
| Vestel Elektronik    | 1         | 1.89%   |
| Unknown (XXX)        | 1         | 1.89%   |
| Unknown (ADA)        | 1         | 1.89%   |
| TXD                  | 1         | 1.89%   |
| ONN                  | 1         | 1.89%   |
| InfoVision           | 1         | 1.89%   |
| HJW                  | 1         | 1.89%   |
| Grundig              | 1         | 1.89%   |
| Goldstar             | 1         | 1.89%   |
| GKK                  | 1         | 1.89%   |
| Eizo                 | 1         | 1.89%   |
| DMT                  | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Iiyama PL4071UH IVM000A 3840x2160 878x485mm 39.5-inch                   | 3         | 5.66%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2         | 3.77%   |
| AOC 28E850 AOC0CCD 2560x1440 620x340mm 27.8-inch                        | 2         | 3.77%   |
| Ancor Communications ASUS VH242 ACI24FA 1920x1080 521x293mm 23.5-inch   | 2         | 3.77%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch           | 1         | 1.89%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                           | 1         | 1.89%   |
| Unknown (XXX) HDMI     XXX0029 1920x1080 1150x650mm 52.0-inch           | 1         | 1.89%   |
| Unknown (ADA) MPI4008 ADA0004 480x800 150x100mm 7.1-inch                | 1         | 1.89%   |
| TXD Display TXD7825 1024x600 410x230mm 18.5-inch                        | 1         | 1.89%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch          | 1         | 1.89%   |
| Sceptre Tech E20 SPT080D 1600x900 410x280mm 19.5-inch                   | 1         | 1.89%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1         | 1.89%   |
| Samsung Electronics SyncMaster SAM02FD 1680x1050 433x271mm 20.1-inch    | 1         | 1.89%   |
| Samsung Electronics SyncMaster SAM01D4 1440x900 408x225mm 18.3-inch     | 1         | 1.89%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch       | 1         | 1.89%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM7003 3840x2160 1872x1053mm 84.6-inch | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM0E35 1920x1080 1210x680mm 54.6-inch  | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 1210x680mm 54.6-inch  | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                        | 1         | 1.89%   |
| Philips PHL 328E9F PHLC181 2560x1440 697x392mm 31.5-inch                | 1         | 1.89%   |
| Philips PHL 252B9 PHL092C 1920x1200 535x339mm 24.9-inch                 | 1         | 1.89%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                 | 1         | 1.89%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 520x320mm 24.0-inch                  | 1         | 1.89%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch            | 1         | 1.89%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                   | 1         | 1.89%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 546x352mm 25.6-inch           | 1         | 1.89%   |
| Hewlett-Packard f1523 HWP2607 1024x768 304x228mm 15.0-inch              | 1         | 1.89%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch             | 1         | 1.89%   |
| Grundig WXGA GRU4448 1600x1200                                          | 1         | 1.89%   |
| Goldstar M228WA GSM563D 1680x1050 434x270mm 20.1-inch                   | 1         | 1.89%   |
| GKK MONITOR GKK3034 1920x1080                                           | 1         | 1.89%   |
| Eizo S1921 ENC1831 1280x1024 376x301mm 19.0-inch                        | 1         | 1.89%   |
| DMT CHHWJT* DMT0030 1440x900 710x400mm 32.1-inch                        | 1         | 1.89%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                      | 1         | 1.89%   |
| Dell P2815Q DELF05C 3840x2160 620x340mm 27.8-inch                       | 1         | 1.89%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                       | 1         | 1.89%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                       | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 21        | 42%     |
| 3840x2160 (4K)     | 11        | 22%     |
| 2560x1440 (QHD)    | 4         | 8%      |
| 1440x900 (WXGA+)   | 3         | 6%      |
| 2560x1600          | 2         | 4%      |
| 1920x1200 (WUXGA)  | 2         | 4%      |
| 1680x1050 (WSXGA+) | 2         | 4%      |
| 1280x1024 (SXGA)   | 2         | 4%      |
| 1600x900 (HD+)     | 1         | 2%      |
| 1280x800 (WXGA)    | 1         | 2%      |
| 1024x768 (XGA)     | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 11        | 20.75%  |
| 24      | 5         | 9.43%   |
| 23      | 5         | 9.43%   |
| 84      | 4         | 7.55%   |
| 21      | 4         | 7.55%   |
| 19      | 4         | 7.55%   |
| 54      | 3         | 5.66%   |
| 39      | 3         | 5.66%   |
| 32      | 2         | 3.77%   |
| 31      | 2         | 3.77%   |
| 25      | 2         | 3.77%   |
| 52      | 1         | 1.89%   |
| 22      | 1         | 1.89%   |
| 20      | 1         | 1.89%   |
| 17      | 1         | 1.89%   |
| 15      | 1         | 1.89%   |
| 13      | 1         | 1.89%   |
| 7       | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 17        | 32.69%  |
| 401-500     | 8         | 15.38%  |
| 601-700     | 7         | 13.46%  |
| 1501-2000   | 4         | 7.69%   |
| 1001-1500   | 4         | 7.69%   |
| 801-900     | 3         | 5.77%   |
| 701-800     | 2         | 3.85%   |
| 351-400     | 2         | 3.85%   |
| 301-350     | 2         | 3.85%   |
| 201-300     | 1         | 1.92%   |
| 101-200     | 1         | 1.92%   |
| Unknown     | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 75.51%  |
| 16/10 | 7         | 14.29%  |
| 5/4   | 3         | 6.12%   |
| 4/3   | 1         | 2.04%   |
| 3/2   | 1         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 12        | 23.53%  |
| 301-350        | 11        | 21.57%  |
| More than 1000 | 8         | 15.69%  |
| 151-200        | 5         | 9.8%    |
| 351-500        | 4         | 7.84%   |
| 251-300        | 3         | 5.88%   |
| 501-1000       | 3         | 5.88%   |
| 71-80          | 1         | 1.96%   |
| 1-40           | 1         | 1.96%   |
| 141-150        | 1         | 1.96%   |
| 111-120        | 1         | 1.96%   |
| Unknown        | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 29        | 59.18%  |
| 101-120 | 9         | 18.37%  |
| 121-160 | 5         | 10.2%   |
| 1-50    | 3         | 6.12%   |
| 161-240 | 2         | 4.08%   |
| Unknown | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 89        | 86.41%  |
| 0     | 11        | 10.68%  |
| 2     | 3         | 2.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 7         | 29.17%  |
| ICS Advent                      | 5         | 20.83%  |
| TP-Link                         | 4         | 16.67%  |
| ASIX Electronics                | 2         | 8.33%   |
| Sigma Designs                   | 1         | 4.17%   |
| Qualcomm Atheros Communications | 1         | 4.17%   |
| Netchip Technology              | 1         | 4.17%   |
| Intel                           | 1         | 4.17%   |
| D-Link                          | 1         | 4.17%   |
| Arduino SA                      | 1         | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| ICS Advent 10/100M LAN                                                               | 5         | 20.83%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 2         | 8.33%   |
| ASIX AX88179 Gigabit Ethernet                                                        | 2         | 8.33%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1         | 4.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1         | 4.17%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 4.17%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1         | 4.17%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                                      | 1         | 4.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 1         | 4.17%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                  | 1         | 4.17%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                              | 1         | 4.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 4.17%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                | 1         | 4.17%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 4.17%   |
| Netchip Linux-USB Ethernet/RNDIS Gadget                                              | 1         | 4.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 1         | 4.17%   |
| D-Link 802.11ac NIC                                                                  | 1         | 4.17%   |
| Arduino SA Uno R3 (CDC ACM)                                                          | 1         | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| TP-Link                         | 4         | 36.36%  |
| Realtek Semiconductor           | 4         | 36.36%  |
| Qualcomm Atheros Communications | 1         | 9.09%   |
| Intel                           | 1         | 9.09%   |
| D-Link                          | 1         | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1         | 9.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1         | 9.09%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 9.09%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1         | 9.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                   | 1         | 9.09%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                  | 1         | 9.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                              | 1         | 9.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 9.09%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 9.09%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 1         | 9.09%   |
| D-Link 802.11ac NIC                                                                  | 1         | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| ICS Advent            | 5         | 45.45%  |
| Realtek Semiconductor | 3         | 27.27%  |
| ASIX Electronics      | 2         | 18.18%  |
| Netchip Technology    | 1         | 9.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| ICS Advent 10/100M LAN                   | 5         | 45.45%  |
| Realtek RTL8153 Gigabit Ethernet Adapter | 2         | 18.18%  |
| ASIX AX88179 Gigabit Ethernet            | 2         | 18.18%  |
| Realtek RTL8152 Fast Ethernet Adapter    | 1         | 9.09%   |
| Netchip Linux-USB Ethernet/RNDIS Gadget  | 1         | 9.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 11        | 52.38%  |
| WiFi     | 8         | 38.1%   |
| Modem    | 2         | 9.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3         | 60%     |
| Ethernet | 2         | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 101       | 99.02%  |
| 1     | 1         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 83        | 79.81%  |
| Yes  | 21        | 20.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Realtek Semiconductor   | 1         | 50%     |
| Cambridge Silicon Radio | 1         | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 1         | 50%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Texas Instruments      | 1         | 20%     |
| Logitech               | 1         | 20%     |
| Generalplus Technology | 1         | 20%     |
| DSEA A/S               | 1         | 20%     |
| C-Media Electronics    | 1         | 20%     |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Texas Instruments PCM2902C Audio CODEC            | 1         | 20%     |
| Logitech [G533 Wireless Headset Dongle]           | 1         | 20%     |
| Generalplus Technology USB Audio Device           | 1         | 20%     |
| DSEA A/S Sennheiser Main Audio                    | 1         | 20%     |
| C-Media Electronics Audio Adapter (Unitek Y-247A) | 1         | 20%     |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4600 Series | 1         | 100%    |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Microdia                      | 15        | 78.95%  |
| OnePlus Technology (Shenzhen) | 1         | 5.26%   |
| MacroSilicon                  | 1         | 5.26%   |
| LG Electronics                | 1         | 5.26%   |
| Bison Electronics             | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Microdia HP Integrated Webcam                         | 15        | 78.95%  |
| OnePlus (Shenzhen) SM8150-MTP _SN:A05FE1A2            | 1         | 5.26%   |
| MacroSilicon MiraBox Capture                          | 1         | 5.26%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 5.26%   |
| Bison Integrated Camera                               | 1         | 5.26%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 100       | 98.04%  |
| 1     | 2         | 1.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Computers | Percent |
|--------------|-----------|---------|
| Net/wireless | 2         | 100%    |

