Ubuntu Studio - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Studio.

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

Total: 121

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | AERO 15-X9                  | [a62c895461](https://linux-hardware.org/?probe=a62c895461) | Apr 26, 2024 |
| Gigabyte      | AERO 15-X9                  | [25245adc43](https://linux-hardware.org/?probe=25245adc43) | Apr 26, 2024 |
| Samsung       | 730QCJ/730QCR               | [0d6a3363b8](https://linux-hardware.org/?probe=0d6a3363b8) | Apr 15, 2024 |
| Acer          | Aspire A317-53              | [ddd85b18e6](https://linux-hardware.org/?probe=ddd85b18e6) | Apr 04, 2024 |
| HP            | Pavilion 15                 | [520fd1241e](https://linux-hardware.org/?probe=520fd1241e) | Mar 14, 2024 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [cf518d2630](https://linux-hardware.org/?probe=cf518d2630) | Mar 10, 2024 |
| MSI           | Alpha 15 A4DEK              | [bf844ef78f](https://linux-hardware.org/?probe=bf844ef78f) | Mar 09, 2024 |
| Lenovo        | ThinkPad L540 20AV004VGE    | [05d6a4d686](https://linux-hardware.org/?probe=05d6a4d686) | Feb 03, 2024 |
| Dell          | Latitude E6420              | [f4dcc8c239](https://linux-hardware.org/?probe=f4dcc8c239) | Jan 26, 2024 |
| Acer          | Aspire A317-53              | [efa0303d01](https://linux-hardware.org/?probe=efa0303d01) | Jan 24, 2024 |
| Dell          | Inspiron 3482               | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [0c55b9f3e3](https://linux-hardware.org/?probe=0c55b9f3e3) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [9197fe40a7](https://linux-hardware.org/?probe=9197fe40a7) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [e36502092e](https://linux-hardware.org/?probe=e36502092e) | Dec 27, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [b000376310](https://linux-hardware.org/?probe=b000376310) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ff3773b480](https://linux-hardware.org/?probe=ff3773b480) | Dec 26, 2023 |
| HP            | EliteBook 850 G3            | [1265cfb294](https://linux-hardware.org/?probe=1265cfb294) | Dec 21, 2023 |
| HP            | EliteBook 850 G3            | [6067c56124](https://linux-hardware.org/?probe=6067c56124) | Dec 19, 2023 |
| HP            | EliteBook 640 14 inch G9... | [51b0a49d02](https://linux-hardware.org/?probe=51b0a49d02) | Nov 27, 2023 |
| Dell          | System XPS L502X            | [33f54ee5dc](https://linux-hardware.org/?probe=33f54ee5dc) | Nov 16, 2023 |
| HP            | ZBook 17 G5                 | [4377844e75](https://linux-hardware.org/?probe=4377844e75) | Nov 02, 2023 |
| Lenovo        | ZIWB2                       | [9e6bd45db9](https://linux-hardware.org/?probe=9e6bd45db9) | Oct 29, 2023 |
| Lenovo        | ZIWB2                       | [2537a6e7b9](https://linux-hardware.org/?probe=2537a6e7b9) | Oct 26, 2023 |
| Lenovo        | ThinkPad T480 20L50101US    | [c6913c1b75](https://linux-hardware.org/?probe=c6913c1b75) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | [188b107eb5](https://linux-hardware.org/?probe=188b107eb5) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bab5438645](https://linux-hardware.org/?probe=bab5438645) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ab3c1508f9](https://linux-hardware.org/?probe=ab3c1508f9) | Aug 30, 2023 |
| Toshiba       | Satellite A505              | [a7b1465809](https://linux-hardware.org/?probe=a7b1465809) | Aug 25, 2023 |
| Acer          | Nitro AN515-55              | [191aa2a04f](https://linux-hardware.org/?probe=191aa2a04f) | Aug 04, 2023 |
| Toshiba       | Satellite L505              | [bab52bec2c](https://linux-hardware.org/?probe=bab52bec2c) | Aug 04, 2023 |
| win elemen... | MoreFine S500+              | [d3718d1a8d](https://linux-hardware.org/?probe=d3718d1a8d) | Jul 16, 2023 |
| ASUSTek       | G73Jh                       | [60e43d39b2](https://linux-hardware.org/?probe=60e43d39b2) | Jul 10, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV03     | [c2a4d4d2c0](https://linux-hardware.org/?probe=c2a4d4d2c0) | Jun 17, 2023 |
| HP            | EliteBook 745 G3            | [5a1b8d9fd3](https://linux-hardware.org/?probe=5a1b8d9fd3) | Jun 04, 2023 |
| COM1          | NBINF-X5-9G5                | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| Lenovo        | ThinkPad L460 20FVS3JK00    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| GPU Compan... | GWNR71517                   | [2743830739](https://linux-hardware.org/?probe=2743830739) | Apr 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3ce456f3c8](https://linux-hardware.org/?probe=3ce456f3c8) | Mar 25, 2023 |
| Lenovo        | ThinkPad X250 20CL001LMB    | [d78880e600](https://linux-hardware.org/?probe=d78880e600) | Mar 17, 2023 |
| HP            | Pavilion dv8                | [105a616a39](https://linux-hardware.org/?probe=105a616a39) | Mar 14, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | TP300UA                     | [22ff7f5827](https://linux-hardware.org/?probe=22ff7f5827) | Feb 20, 2023 |
| Dell          | Latitude 5511               | [05e11b64d6](https://linux-hardware.org/?probe=05e11b64d6) | Feb 09, 2023 |
| Apple         | MacBookPro8,2               | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| HP            | EliteBook 735 G6            | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| ASUSTek       | K53U                        | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Apple         | MacBookPro8,2               | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| Acer          | Aspire E5-573G              | [ec1e8e146a](https://linux-hardware.org/?probe=ec1e8e146a) | Dec 10, 2022 |
| Dell          | Latitude E6500              | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | G70-80 80FF                 | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| Gigabyte      | AERO 15-X9                  | [1d490bb7d1](https://linux-hardware.org/?probe=1d490bb7d1) | Nov 11, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | [55771f0c33](https://linux-hardware.org/?probe=55771f0c33) | Oct 18, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | [7e0028c2fa](https://linux-hardware.org/?probe=7e0028c2fa) | Oct 18, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [5bfc8f0a7d](https://linux-hardware.org/?probe=5bfc8f0a7d) | Sep 30, 2022 |
| HP            | ZBook 15 G3                 | [2dc3febd4d](https://linux-hardware.org/?probe=2dc3febd4d) | Sep 24, 2022 |
| ASUSTek       | GL503VD                     | [b1d97f239e](https://linux-hardware.org/?probe=b1d97f239e) | Sep 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [de37b9cf96](https://linux-hardware.org/?probe=de37b9cf96) | Sep 13, 2022 |
| Gigabyte      | AERO 15-X9                  | [d6d8f577e0](https://linux-hardware.org/?probe=d6d8f577e0) | Sep 12, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [a23b4a8cd4](https://linux-hardware.org/?probe=a23b4a8cd4) | Aug 27, 2022 |
| HP            | G62                         | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| Apple         | MacBookPro11,5              | [25e69108df](https://linux-hardware.org/?probe=25e69108df) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [4ed102b3fa](https://linux-hardware.org/?probe=4ed102b3fa) | Jun 15, 2022 |
| Getac         | S400G3                      | [56cc8b4c1a](https://linux-hardware.org/?probe=56cc8b4c1a) | May 16, 2022 |
| Acer          | Aspire A114-32              | [3c048f588e](https://linux-hardware.org/?probe=3c048f588e) | Apr 12, 2022 |
| Dell          | XPS 15 9570                 | [3f8fe40793](https://linux-hardware.org/?probe=3f8fe40793) | Mar 08, 2022 |
| Dell          | Inspiron N5110              | [4206238fce](https://linux-hardware.org/?probe=4206238fce) | Mar 01, 2022 |
| HP            | Sona                        | [4fcab0b3b7](https://linux-hardware.org/?probe=4fcab0b3b7) | Feb 24, 2022 |
| HP            | Sona                        | [d0b3189e0f](https://linux-hardware.org/?probe=d0b3189e0f) | Feb 24, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Google        | Nami                        | [5f1ba9ab72](https://linux-hardware.org/?probe=5f1ba9ab72) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Samsung       | 305V4A/305V5A               | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| HP            | EliteBook 840 G3            | [fe9fed2a45](https://linux-hardware.org/?probe=fe9fed2a45) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | [5ccce1fb71](https://linux-hardware.org/?probe=5ccce1fb71) | Jan 21, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | [91adda5a0e](https://linux-hardware.org/?probe=91adda5a0e) | Jan 21, 2022 |
| Clevo         | W35_37ET                    | [f8858fd0c3](https://linux-hardware.org/?probe=f8858fd0c3) | Jan 20, 2022 |
| Dell          | Inspiron 7348               | [b479441fe2](https://linux-hardware.org/?probe=b479441fe2) | Jan 15, 2022 |
| Dell          | Inspiron 3501               | [e071d4f83a](https://linux-hardware.org/?probe=e071d4f83a) | Jan 02, 2022 |
| Toshiba       | Satellite C855              | [7914ab9929](https://linux-hardware.org/?probe=7914ab9929) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| Razer         | Blade Stealth 13 Late 20... | [22033e7185](https://linux-hardware.org/?probe=22033e7185) | Oct 05, 2021 |
| Toshiba       | Satellite L755D             | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| ASUSTek       | UX305FA                     | [91b4275b9b](https://linux-hardware.org/?probe=91b4275b9b) | Aug 25, 2021 |
| HUAWEI        | HLYL-WXX9                   | [35e6393ea4](https://linux-hardware.org/?probe=35e6393ea4) | Aug 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [9d8c462df3](https://linux-hardware.org/?probe=9d8c462df3) | Jul 20, 2021 |
| HP            | Pavilion dv6                | [089a39fe70](https://linux-hardware.org/?probe=089a39fe70) | Jul 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [64c8a86c5b](https://linux-hardware.org/?probe=64c8a86c5b) | Jun 19, 2021 |
| Intel Clie... | LAPBC510                    | [06421d0916](https://linux-hardware.org/?probe=06421d0916) | Jun 15, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [f88f0c3680](https://linux-hardware.org/?probe=f88f0c3680) | Jun 14, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [749002b5ad](https://linux-hardware.org/?probe=749002b5ad) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [aec24cb317](https://linux-hardware.org/?probe=aec24cb317) | Apr 20, 2021 |
| Dell          | Precision M4500             | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | X541NA                      | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | Pavilion dv6                | [369f0a0cdb](https://linux-hardware.org/?probe=369f0a0cdb) | Mar 12, 2021 |
| Lenovo        | G50-45 80E3                 | [e4fb438978](https://linux-hardware.org/?probe=e4fb438978) | Feb 24, 2021 |
| Sony          | VGN-NS31M_W                 | [dcc1660569](https://linux-hardware.org/?probe=dcc1660569) | Feb 17, 2021 |
| ASUSTek       | U56E                        | [eba46128ee](https://linux-hardware.org/?probe=eba46128ee) | Jan 04, 2021 |
| Dell          | Inspiron 3543               | [1b1044cc21](https://linux-hardware.org/?probe=1b1044cc21) | Nov 28, 2020 |
| Dell          | Latitude E6530              | [3d606b3078](https://linux-hardware.org/?probe=3d606b3078) | Nov 09, 2020 |
| Dell          | Latitude E7250              | [d5e2f8b706](https://linux-hardware.org/?probe=d5e2f8b706) | Nov 01, 2020 |
| Acer          | ASPIRE1420P_MSFT            | [5185b46abc](https://linux-hardware.org/?probe=5185b46abc) | Oct 31, 2020 |
| Avell High... | Avell G1555 MUV / A62 MU... | [c2994bb093](https://linux-hardware.org/?probe=c2994bb093) | Sep 18, 2020 |
| Dell          | Inspiron 1520               | [e00620b124](https://linux-hardware.org/?probe=e00620b124) | Sep 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | [57d3d832f5](https://linux-hardware.org/?probe=57d3d832f5) | Sep 04, 2020 |
| Dell          | Latitude E4300              | [3e0fb2e03f](https://linux-hardware.org/?probe=3e0fb2e03f) | Sep 03, 2020 |
| HP            | Compaq 8510p                | [2ea87d13f0](https://linux-hardware.org/?probe=2ea87d13f0) | Aug 26, 2020 |
| ASUSTek       | 1001P                       | [d4f13322ac](https://linux-hardware.org/?probe=d4f13322ac) | Aug 19, 2020 |
| ASUSTek       | 1001P                       | [92e2a05f2d](https://linux-hardware.org/?probe=92e2a05f2d) | Aug 13, 2020 |
| ASUSTek       | 1001P                       | [0ae5a1aab2](https://linux-hardware.org/?probe=0ae5a1aab2) | Aug 13, 2020 |
| Dell          | Inspiron 5566               | [3162979c2e](https://linux-hardware.org/?probe=3162979c2e) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| HP            | Notebook                    | [e406d5cf9e](https://linux-hardware.org/?probe=e406d5cf9e) | Jun 02, 2020 |
| Lenovo        | ThinkPad W530 2447IG0       | [f7125d9a17](https://linux-hardware.org/?probe=f7125d9a17) | Mar 19, 2020 |
| Lenovo        | ThinkPad X230 23245S1       | [047f29b7c7](https://linux-hardware.org/?probe=047f29b7c7) | Nov 01, 2019 |
| Lenovo        | G50-45 80E3                 | [ebbf8cd8d4](https://linux-hardware.org/?probe=ebbf8cd8d4) | May 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 39        | 38.61%  |
| Ubuntu Studio 22.04 | 35        | 34.65%  |
| Ubuntu Studio 23.04 | 6         | 5.94%   |
| Ubuntu Studio 23.10 | 4         | 3.96%   |
| Ubuntu Studio 22.10 | 4         | 3.96%   |
| Ubuntu Studio 21.10 | 3         | 2.97%   |
| Ubuntu Studio 21.04 | 3         | 2.97%   |
| Ubuntu Studio 20.10 | 3         | 2.97%   |
| Ubuntu Studio 18.04 | 2         | 1.98%   |
| Ubuntu Studio 24.04 | 1         | 0.99%   |
| Ubuntu Studio 19.10 | 1         | 0.99%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 99        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-1009-lowlatency   | 3         | 2.86%   |
| 6.2.0-1003-lowlatency   | 3         | 2.86%   |
| 5.4.0-52-lowlatency     | 3         | 2.86%   |
| 5.15.0-56-lowlatency    | 3         | 2.86%   |
| 5.15.0-47-lowlatency    | 3         | 2.86%   |
| 5.13.0-28-lowlatency    | 3         | 2.86%   |
| 6.5.0-27-lowlatency     | 2         | 1.9%    |
| 6.5.0-25-lowlatency     | 2         | 1.9%    |
| 6.5.0-15-lowlatency     | 2         | 1.9%    |
| 6.2.0-1018-lowlatency   | 2         | 1.9%    |
| 5.8.0-55-lowlatency     | 2         | 1.9%    |
| 5.4.0-94-lowlatency     | 2         | 1.9%    |
| 5.4.0-65-lowlatency     | 2         | 1.9%    |
| 5.4.0-45-lowlatency     | 2         | 1.9%    |
| 5.4.0-42-lowlatency     | 2         | 1.9%    |
| 5.19.0-1015-lowlatency  | 2         | 1.9%    |
| 5.15.0-67-lowlatency    | 2         | 1.9%    |
| 5.15.0-50-lowlatency    | 2         | 1.9%    |
| 5.15.0-48-lowlatency    | 2         | 1.9%    |
| 5.15.0-46-lowlatency    | 2         | 1.9%    |
| 5.13.0-30-lowlatency    | 2         | 1.9%    |
| 5.11.0-34-lowlatency    | 2         | 1.9%    |
| 5.11.0-27-lowlatency    | 2         | 1.9%    |
| 6.8.0-31-lowlatency     | 1         | 0.95%   |
| 6.5.0-17-lowlatency     | 1         | 0.95%   |
| 6.5.0-13-lowlatency     | 1         | 0.95%   |
| 6.5.0-10-lowlatency     | 1         | 0.95%   |
| 6.2.8-x64v3-xanmod1     | 1         | 0.95%   |
| 6.2.0-1017-lowlatency   | 1         | 0.95%   |
| 6.2.0-1016-lowlatency   | 1         | 0.95%   |
| 6.2.0-1014-lowlatency   | 1         | 0.95%   |
| 6.2.0-1008-lowlatency   | 1         | 0.95%   |
| 5.8.0-59-lowlatency     | 1         | 0.95%   |
| 5.8.0-50-lowlatency     | 1         | 0.95%   |
| 5.8.0-44-lowlatency     | 1         | 0.95%   |
| 5.8.0-43-lowlatency     | 1         | 0.95%   |
| 5.8.0-34-generic        | 1         | 0.95%   |
| 5.8.0-29-lowlatency     | 1         | 0.95%   |
| 5.8.0-25-lowlatency     | 1         | 0.95%   |
| 5.7.6-050706-lowlatency | 1         | 0.95%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 25        | 24.75%  |
| 5.4.0   | 20        | 19.8%   |
| 6.2.0   | 12        | 11.88%  |
| 5.8.0   | 9         | 8.91%   |
| 5.11.0  | 9         | 8.91%   |
| 6.5.0   | 8         | 7.92%   |
| 5.19.0  | 6         | 5.94%   |
| 5.13.0  | 6         | 5.94%   |
| 4.15.0  | 2         | 1.98%   |
| 6.8.0   | 1         | 0.99%   |
| 6.2.8   | 1         | 0.99%   |
| 5.7.6   | 1         | 0.99%   |
| 5.3.0   | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 25        | 24.75%  |
| 5.4     | 20        | 19.8%   |
| 6.2     | 13        | 12.87%  |
| 5.8     | 9         | 8.91%   |
| 5.11    | 9         | 8.91%   |
| 6.5     | 8         | 7.92%   |
| 5.19    | 6         | 5.94%   |
| 5.13    | 6         | 5.94%   |
| 4.15    | 2         | 1.98%   |
| 6.8     | 1         | 0.99%   |
| 5.7     | 1         | 0.99%   |
| 5.3     | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 99        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| KDE5  | 54        | 54.55%  |
| XFCE  | 38        | 38.38%  |
| GNOME | 6         | 6.06%   |
| LXQt  | 1         | 1.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 94        | 94.95%  |
| Wayland | 5         | 5.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 49        | 49.49%  |
| LightDM | 23        | 23.23%  |
| TDM     | 21        | 21.21%  |
| GDM     | 5         | 5.05%   |
| LXDM    | 1         | 1.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 39        | 39%     |
| fr_FR   | 15        | 15%     |
| ru_RU   | 5         | 5%      |
| en_GB   | 5         | 5%      |
| de_DE   | 5         | 5%      |
| C       | 4         | 4%      |
| it_IT   | 3         | 3%      |
| es_ES   | 3         | 3%      |
| en_CA   | 3         | 3%      |
| pt_BR   | 2         | 2%      |
| hu_HU   | 2         | 2%      |
| es_MX   | 2         | 2%      |
| en_IE   | 2         | 2%      |
| Unknown | 2         | 2%      |
| nl_NL   | 1         | 1%      |
| es_NI   | 1         | 1%      |
| es_CR   | 1         | 1%      |
| es_AR   | 1         | 1%      |
| en_NG   | 1         | 1%      |
| en_AU   | 1         | 1%      |
| en_AG   | 1         | 1%      |
| de_CH   | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 69        | 69.7%   |
| BIOS | 30        | 30.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 95        | 95.96%  |
| Overlay | 4         | 4.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 73        | 73.74%  |
| MBR  | 26        | 26.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 88.12%  |
| Yes       | 12        | 11.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 52.53%  |
| Yes       | 47        | 47.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 26        | 26.26%  |
| Hewlett-Packard        | 17        | 17.17%  |
| Dell                   | 15        | 15.15%  |
| ASUSTek Computer       | 12        | 12.12%  |
| Acer                   | 5         | 5.05%   |
| Toshiba                | 4         | 4.04%   |
| Apple                  | 3         | 3.03%   |
| Samsung Electronics    | 2         | 2.02%   |
| HUAWEI                 | 2         | 2.02%   |
| win element            | 1         | 1.01%   |
| Sony                   | 1         | 1.01%   |
| Razer                  | 1         | 1.01%   |
| MSI                    | 1         | 1.01%   |
| Intel Client Systems   | 1         | 1.01%   |
| GPU Company            | 1         | 1.01%   |
| Google                 | 1         | 1.01%   |
| Gigabyte Technology    | 1         | 1.01%   |
| Getac                  | 1         | 1.01%   |
| COM1                   | 1         | 1.01%   |
| Clevo                  | 1         | 1.01%   |
| Avell High Performance | 1         | 1.01%   |
| ARDOR GAMING           | 1         | 1.01%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G50-45 80E3                       | 2         | 2.02%   |
| HP Pavilion dv6                          | 2         | 2.02%   |
| win element MoreFine S500+               | 1         | 1.01%   |
| Toshiba Satellite L755D                  | 1         | 1.01%   |
| Toshiba Satellite L505                   | 1         | 1.01%   |
| Toshiba Satellite C855                   | 1         | 1.01%   |
| Toshiba Satellite A505                   | 1         | 1.01%   |
| Sony VGN-NS31M_W                         | 1         | 1.01%   |
| Samsung 730QCJ/730QCR                    | 1         | 1.01%   |
| Samsung 305V4A/305V5A                    | 1         | 1.01%   |
| Razer Blade Stealth 13 Late 2019         | 1         | 1.01%   |
| MSI Alpha 15 A4DEK                       | 1         | 1.01%   |
| Lenovo ZIWB2                             | 1         | 1.01%   |
| Lenovo ThinkPad X250 20CL001LMB          | 1         | 1.01%   |
| Lenovo ThinkPad X230 2333A86             | 1         | 1.01%   |
| Lenovo ThinkPad X230 2325AJG             | 1         | 1.01%   |
| Lenovo ThinkPad X230 23245S1             | 1         | 1.01%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHCTO1WW | 1         | 1.01%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A80035US | 1         | 1.01%   |
| Lenovo ThinkPad W530 2447IG0             | 1         | 1.01%   |
| Lenovo ThinkPad T530 24296HG             | 1         | 1.01%   |
| Lenovo ThinkPad T520 4243K86             | 1         | 1.01%   |
| Lenovo ThinkPad T480 20L50101US          | 1         | 1.01%   |
| Lenovo ThinkPad P50 20EQS0VV03           | 1         | 1.01%   |
| Lenovo ThinkPad L540 20AV004VGE          | 1         | 1.01%   |
| Lenovo ThinkPad L460 20FVS3JK00          | 1         | 1.01%   |
| Lenovo ThinkPad E14 Gen 3 20Y70073GE     | 1         | 1.01%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 1.01%   |
| Lenovo Legion 5 15ARH05 82B5             | 1         | 1.01%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.01%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.01%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 1.01%   |
| Lenovo IdeaPad 300-17ISK 80QH            | 1         | 1.01%   |
| Lenovo IdeaPad 3 15ABA7 82RN             | 1         | 1.01%   |
| Lenovo IdeaPad 3 14ARE05 81W3            | 1         | 1.01%   |
| Lenovo G70-80 80FF                       | 1         | 1.01%   |
| Intel Client Systems LAPBC510            | 1         | 1.01%   |
| HUAWEI KLVL-WXXW                         | 1         | 1.01%   |
| HUAWEI HLYL-WXX9                         | 1         | 1.01%   |
| HP ZBook 17 G5                           | 1         | 1.01%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 14        | 14.14%  |
| Lenovo IdeaPad                | 6         | 6.06%   |
| Dell Latitude                 | 6         | 6.06%   |
| Dell Inspiron                 | 6         | 6.06%   |
| HP EliteBook                  | 5         | 5.05%   |
| Toshiba Satellite             | 4         | 4.04%   |
| HP Pavilion                   | 4         | 4.04%   |
| Acer Aspire                   | 3         | 3.03%   |
| Lenovo Legion                 | 2         | 2.02%   |
| Lenovo G50-45                 | 2         | 2.02%   |
| HP ZBook                      | 2         | 2.02%   |
| ASUS VivoBook                 | 2         | 2.02%   |
| ASUS ASUS                     | 2         | 2.02%   |
| win element MoreFine          | 1         | 1.01%   |
| Sony VGN-NS31M                | 1         | 1.01%   |
| Samsung 730QCJ                | 1         | 1.01%   |
| Samsung 305V4A                | 1         | 1.01%   |
| Razer Blade                   | 1         | 1.01%   |
| MSI Alpha                     | 1         | 1.01%   |
| Lenovo ZIWB2                  | 1         | 1.01%   |
| Lenovo G70-80                 | 1         | 1.01%   |
| Intel Client Systems LAPBC510 | 1         | 1.01%   |
| HUAWEI KLVL-WXXW              | 1         | 1.01%   |
| HUAWEI HLYL-WXX9              | 1         | 1.01%   |
| HP Stream                     | 1         | 1.01%   |
| HP Sona                       | 1         | 1.01%   |
| HP OMEN                       | 1         | 1.01%   |
| HP Notebook                   | 1         | 1.01%   |
| HP Laptop                     | 1         | 1.01%   |
| HP Compaq                     | 1         | 1.01%   |
| GPU Company GWNR71517         | 1         | 1.01%   |
| Google Nami                   | 1         | 1.01%   |
| Gigabyte AERO                 | 1         | 1.01%   |
| Getac S400G3                  | 1         | 1.01%   |
| Dell XPS                      | 1         | 1.01%   |
| Dell System                   | 1         | 1.01%   |
| Dell Precision                | 1         | 1.01%   |
| COM1 NBINF-X5-9G5             | 1         | 1.01%   |
| Clevo W35                     | 1         | 1.01%   |
| Avell High Performance Avell  | 1         | 1.01%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 13        | 13.13%  |
| 2021 | 9         | 9.09%   |
| 2014 | 8         | 8.08%   |
| 2012 | 8         | 8.08%   |
| 2011 | 8         | 8.08%   |
| 2019 | 7         | 7.07%   |
| 2016 | 7         | 7.07%   |
| 2015 | 7         | 7.07%   |
| 2008 | 7         | 7.07%   |
| 2018 | 6         | 6.06%   |
| 2022 | 4         | 4.04%   |
| 2017 | 4         | 4.04%   |
| 2009 | 4         | 4.04%   |
| 2010 | 3         | 3.03%   |
| 2013 | 2         | 2.02%   |
| 2007 | 2         | 2.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 99        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 88        | 88.89%  |
| Enabled  | 11        | 11.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 97.98%  |
| Yes  | 2         | 2.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 41        | 40.59%  |
| 8.01-16.0  | 20        | 19.8%   |
| 16.01-24.0 | 15        | 14.85%  |
| 3.01-4.0   | 10        | 9.9%    |
| 32.01-64.0 | 9         | 8.91%   |
| 24.01-32.0 | 3         | 2.97%   |
| 2.01-3.0   | 2         | 1.98%   |
| 1.01-2.0   | 1         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 33        | 32.35%  |
| 2.01-3.0  | 26        | 25.49%  |
| 3.01-4.0  | 20        | 19.61%  |
| 4.01-8.0  | 17        | 16.67%  |
| 8.01-16.0 | 5         | 4.9%    |
| 0.51-1.0  | 1         | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 71.29%  |
| 2      | 25        | 24.75%  |
| 0      | 2         | 1.98%   |
| 4      | 1         | 0.99%   |
| 3      | 1         | 0.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 65%     |
| Yes       | 35        | 35%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 83%     |
| No        | 17        | 17%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 98.99%  |
| No        | 1         | 1.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 79.8%   |
| No        | 20        | 20.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 21        | 21.21%  |
| France       | 13        | 13.13%  |
| Germany      | 9         | 9.09%   |
| Russia       | 6         | 6.06%   |
| Canada       | 5         | 5.05%   |
| UK           | 4         | 4.04%   |
| Spain        | 4         | 4.04%   |
| Italy        | 4         | 4.04%   |
| Brazil       | 3         | 3.03%   |
| Norway       | 2         | 2.02%   |
| Netherlands  | 2         | 2.02%   |
| Mexico       | 2         | 2.02%   |
| Ivory Coast  | 2         | 2.02%   |
| Hungary      | 2         | 2.02%   |
| Costa Rica   | 2         | 2.02%   |
| Yemen        | 1         | 1.01%   |
| Turkey       | 1         | 1.01%   |
| Taiwan       | 1         | 1.01%   |
| Switzerland  | 1         | 1.01%   |
| Sweden       | 1         | 1.01%   |
| South Africa | 1         | 1.01%   |
| Poland       | 1         | 1.01%   |
| Peru         | 1         | 1.01%   |
| Nigeria      | 1         | 1.01%   |
| Nicaragua    | 1         | 1.01%   |
| Ireland      | 1         | 1.01%   |
| Indonesia    | 1         | 1.01%   |
| Finland      | 1         | 1.01%   |
| Bulgaria     | 1         | 1.01%   |
| Belgium      | 1         | 1.01%   |
| Austria      | 1         | 1.01%   |
| Australia    | 1         | 1.01%   |
| Argentina    | 1         | 1.01%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Montreal             | 2         | 1.98%   |
| Madrid               | 2         | 1.98%   |
| Hamburg              | 2         | 1.98%   |
| Groningen            | 2         | 1.98%   |
| Denver               | 2         | 1.98%   |
| Budapest             | 2         | 1.98%   |
| Béziers             | 2         | 1.98%   |
| Abidjan              | 2         | 1.98%   |
| Zele                 | 1         | 0.99%   |
| Yonkers              | 1         | 0.99%   |
| Yekaterinburg        | 1         | 0.99%   |
| Wroclaw              | 1         | 0.99%   |
| Woonsocket           | 1         | 0.99%   |
| Woodland Park        | 1         | 0.99%   |
| Warner Robins        | 1         | 0.99%   |
| Vienna               | 1         | 0.99%   |
| Verdal               | 1         | 0.99%   |
| Velleron             | 1         | 0.99%   |
| Turin                | 1         | 0.99%   |
| Toulouse             | 1         | 0.99%   |
| Toronto              | 1         | 0.99%   |
| Tarragona            | 1         | 0.99%   |
| Taipei               | 1         | 0.99%   |
| Sunderland           | 1         | 0.99%   |
| Stuttgart            | 1         | 0.99%   |
| Stockholm            | 1         | 0.99%   |
| Stabekk              | 1         | 0.99%   |
| St Petersburg        | 1         | 0.99%   |
| Sofia                | 1         | 0.99%   |
| Sleman               | 1         | 0.99%   |
| Seropedica           | 1         | 0.99%   |
| Santo André         | 1         | 0.99%   |
| Sanaa                | 1         | 0.99%   |
| San Juan             | 1         | 0.99%   |
| San Francisco        | 1         | 0.99%   |
| San Clemente         | 1         | 0.99%   |
| Samara               | 1         | 0.99%   |
| Rüsselsheim am Main | 1         | 0.99%   |
| Rio de Janeiro       | 1         | 0.99%   |
| Ragusa               | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 20        | 20     | 16.39%  |
| WDC                         | 17        | 18     | 13.93%  |
| SK hynix                    | 9         | 10     | 7.38%   |
| Toshiba                     | 7         | 7      | 5.74%   |
| Seagate                     | 7         | 8      | 5.74%   |
| SanDisk                     | 7         | 7      | 5.74%   |
| Intel                       | 6         | 11     | 4.92%   |
| Unknown                     | 4         | 4      | 3.28%   |
| Kingston                    | 4         | 4      | 3.28%   |
| Hitachi                     | 4         | 4      | 3.28%   |
| Micron Technology           | 3         | 3      | 2.46%   |
| UMIS                        | 2         | 2      | 1.64%   |
| PNY                         | 2         | 2      | 1.64%   |
| Phison                      | 2         | 2      | 1.64%   |
| KIOXIA                      | 2         | 2      | 1.64%   |
| Crucial                     | 2         | 2      | 1.64%   |
| China                       | 2         | 2      | 1.64%   |
| XPG                         | 1         | 1      | 0.82%   |
| Wibtek                      | 1         | 1      | 0.82%   |
| Union Memory                | 1         | 1      | 0.82%   |
| Team                        | 1         | 1      | 0.82%   |
| SPCC                        | 1         | 1      | 0.82%   |
| Reeinno                     | 1         | 1      | 0.82%   |
| Realtek                     | 1         | 1      | 0.82%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.82%   |
| LITEON                      | 1         | 1      | 0.82%   |
| Lexar                       | 1         | 1      | 0.82%   |
| Kingston Technology Company | 1         | 2      | 0.82%   |
| KingSpec                    | 1         | 1      | 0.82%   |
| JMicron Technology          | 1         | 1      | 0.82%   |
| Inateck                     | 1         | 1      | 0.82%   |
| HGST                        | 1         | 1      | 0.82%   |
| Fujitsu                     | 1         | 1      | 0.82%   |
| External                    | 1         | 1      | 0.82%   |
| Dogfish                     | 1         | 1      | 0.82%   |
| BHT                         | 1         | 1      | 0.82%   |
| ASMT                        | 1         | 1      | 0.82%   |
| A-DATA Technology           | 1         | 2      | 0.82%   |
| Unknown                     | 1         | 1      | 0.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB                  | 2         | 1.59%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 1.59%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.59%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.59%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 1.59%   |
| Samsung SSD 870 EVO 1TB                   | 2         | 1.59%   |
| Samsung SSD 860 EVO 500GB                 | 2         | 1.59%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 1.59%   |
| Kingston SA400S37240G 240GB SSD           | 2         | 1.59%   |
| China SSD 1TB                             | 2         | 1.59%   |
| XPG GAMMIX S7 1TB                         | 1         | 0.79%   |
| Wibtek W800S 256GB SSD                    | 1         | 0.79%   |
| WDC WDS100T2G0A-00JH30 1TB SSD            | 1         | 0.79%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 0.79%   |
| WDC WDS100T2B0A-00SM50 1TB SSD            | 1         | 0.79%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.79%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.79%   |
| WDC WD5000BEKT-60KA9T0 500GB              | 1         | 0.79%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 0.79%   |
| WDC WD3200BEKT-75PVMT1 320GB              | 1         | 0.79%   |
| WDC WD3200BEKT-60V5T1 320GB               | 1         | 0.79%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 0.79%   |
| WDC WD10JPVT-75A1YT0 1TB                  | 1         | 0.79%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB      | 1         | 0.79%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 0.79%   |
| Unknown MMC Card  4GB                     | 1         | 0.79%   |
| Unknown MMC Card  16GB                    | 1         | 0.79%   |
| Unknown DA4128  128GB                     | 1         | 0.79%   |
| Unknown 032G34  32GB                      | 1         | 0.79%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB   | 1         | 0.79%   |
| UMIS RPJTJ256MEE1OWX 256GB                | 1         | 0.79%   |
| UMIS RPITJ512VME2OWD 512GB                | 1         | 0.79%   |
| Toshiba TR150 240GB SSD                   | 1         | 0.79%   |
| Toshiba MK1637GSX 160GB                   | 1         | 0.79%   |
| Toshiba HDWL110 1TB                       | 1         | 0.79%   |
| Team TM8FP4001T 1TB                       | 1         | 0.79%   |
| SPCC Solid State Disk 1TB                 | 1         | 0.79%   |
| SK hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 0.79%   |
| SK hynix SC401 SATA 256GB SSD             | 1         | 0.79%   |
| SK hynix SC308 SATA 256GB SSD             | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 30.3%   |
| Toshiba             | 6         | 6      | 18.18%  |
| Seagate             | 6         | 6      | 18.18%  |
| Hitachi             | 4         | 4      | 12.12%  |
| Samsung Electronics | 2         | 2      | 6.06%   |
| JMicron Technology  | 1         | 1      | 3.03%   |
| Inateck             | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| ASMT                | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 24.39%  |
| SanDisk             | 5         | 5      | 12.2%   |
| Kingston            | 3         | 3      | 7.32%   |
| WDC                 | 2         | 2      | 4.88%   |
| SK hynix            | 2         | 2      | 4.88%   |
| PNY                 | 2         | 2      | 4.88%   |
| Micron Technology   | 2         | 2      | 4.88%   |
| Crucial             | 2         | 2      | 4.88%   |
| China               | 2         | 2      | 4.88%   |
| Wibtek              | 1         | 1      | 2.44%   |
| Toshiba             | 1         | 1      | 2.44%   |
| SPCC                | 1         | 1      | 2.44%   |
| Reeinno             | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| Lexar               | 1         | 1      | 2.44%   |
| KingSpec            | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| External            | 1         | 1      | 2.44%   |
| Dogfish             | 1         | 1      | 2.44%   |
| BHT                 | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 36        | 50     | 32.73%  |
| SSD  | 36        | 41     | 32.73%  |
| HDD  | 32        | 34     | 29.09%  |
| MMC  | 6         | 7      | 5.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 62        | 70     | 56.36%  |
| NVMe | 36        | 49     | 32.73%  |
| SAS  | 6         | 6      | 5.45%   |
| MMC  | 6         | 7      | 5.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 54     | 70.83%  |
| 0.51-1.0   | 20        | 20     | 27.78%  |
| 1.01-2.0   | 1         | 1      | 1.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 30        | 29.13%  |
| 251-500    | 29        | 28.16%  |
| 501-1000   | 15        | 14.56%  |
| 1001-2000  | 9         | 8.74%   |
| 51-100     | 8         | 7.77%   |
| 21-50      | 7         | 6.8%    |
| 1-20       | 4         | 3.88%   |
| 2001-3000  | 1         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 37        | 36.27%  |
| 101-250   | 19        | 18.63%  |
| 21-50     | 17        | 16.67%  |
| 51-100    | 10        | 9.8%    |
| 251-500   | 9         | 8.82%   |
| 501-1000  | 8         | 7.84%   |
| 1001-2000 | 2         | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 5.26%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 5.26%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 5.26%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 5.26%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 5.26%   |
| UMIS RPITJ512VME2OWD 512GB                          | 1         | 1      | 5.26%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 5.26%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 5.26%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 5.26%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 5.26%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 5.26%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 5.26%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 5.26%   |
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 5.26%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 5.26%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 5.26%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 26.32%  |
| Seagate             | 4         | 4      | 21.05%  |
| Samsung Electronics | 3         | 3      | 15.79%  |
| Hitachi             | 2         | 2      | 10.53%  |
| UMIS                | 1         | 1      | 5.26%   |
| Toshiba             | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| KingSpec            | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 35.71%  |
| Seagate             | 4         | 4      | 28.57%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| Hitachi             | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 73.68%  |
| SSD  | 4         | 4      | 21.05%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Works    | 77        | 102    | 72.64%  |
| Malfunc  | 19        | 19     | 17.92%  |
| Detected | 10        | 11     | 9.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 69        | 56.56%  |
| AMD                          | 18        | 14.75%  |
| Samsung Electronics          | 8         | 6.56%   |
| SK hynix                     | 7         | 5.74%   |
| SanDisk                      | 5         | 4.1%    |
| Union Memory (Shenzhen)      | 3         | 2.46%   |
| Phison Electronics           | 3         | 2.46%   |
| Kingston Technology Company  | 2         | 1.64%   |
| Toshiba America Info Systems | 1         | 0.82%   |
| Seagate Technology           | 1         | 0.82%   |
| Realtek Semiconductor        | 1         | 0.82%   |
| Micron Technology            | 1         | 0.82%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.82%   |
| KIOXIA                       | 1         | 0.82%   |
| ADATA Technology             | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 12.31%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 6.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 4.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 4.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 3.08%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 2.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 2.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.31%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 1.54%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 1.54%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 1.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 1.54%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.54%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.54%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.54%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.54%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.77%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.77%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 1         | 0.77%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.77%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1         | 0.77%   |
| Seagate FireCuda 530 SSD                                                       | 1         | 0.77%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.77%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.77%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 1         | 0.77%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 71        | 57.72%  |
| NVMe | 36        | 29.27%  |
| RAID | 12        | 9.76%   |
| IDE  | 4         | 3.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 76.77%  |
| AMD    | 23        | 23.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics | 4         | 4.04%   |
| Intel Core i5-2450M CPU @ 2.50GHz      | 3         | 3.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 2.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 2.02%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz     | 2         | 2.02%   |
| Intel Core i7-5600U CPU @ 2.60GHz      | 2         | 2.02%   |
| Intel Core i7-2630QM CPU @ 2.00GHz     | 2         | 2.02%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 2         | 2.02%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 2         | 2.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 2         | 2.02%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 2         | 2.02%   |
| Intel Core i5-10300H CPU @ 2.50GHz     | 2         | 2.02%   |
| Intel Celeron N4000 CPU @ 1.10GHz      | 2         | 2.02%   |
| AMD Ryzen 7 5825U with Radeon Graphics | 2         | 2.02%   |
| AMD Ryzen 5 5500U with Radeon Graphics | 2         | 2.02%   |
| Intel Processor 5Y10 CPU @ 0.80GHz     | 1         | 1.01%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.01%   |
| Intel Genuine CPU U2300 @ 1.20GHz      | 1         | 1.01%   |
| Intel Core i9-8950HK CPU @ 2.90GHz     | 1         | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 1         | 1.01%   |
| Intel Core i7-8850H CPU @ 2.60GHz      | 1         | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 1         | 1.01%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.01%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz     | 1         | 1.01%   |
| Intel Core i7-4600U CPU @ 2.10GHz      | 1         | 1.01%   |
| Intel Core i7-3940XM CPU @ 3.00GHz     | 1         | 1.01%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 1.01%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 1         | 1.01%   |
| Intel Core i7-2635QM CPU @ 2.00GHz     | 1         | 1.01%   |
| Intel Core i7-10850H CPU @ 2.70GHz     | 1         | 1.01%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz      | 1         | 1.01%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.01%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.01%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.01%   |
| Intel Core i5-4310M CPU @ 2.70GHz      | 1         | 1.01%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 1         | 1.01%   |
| Intel Core i5-4210M CPU @ 2.60GHz      | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 28        | 28.28%  |
| Intel Core i5      | 24        | 24.24%  |
| Other              | 7         | 7.07%   |
| AMD Ryzen 7        | 7         | 7.07%   |
| AMD Ryzen 5        | 6         | 6.06%   |
| Intel Core i3      | 5         | 5.05%   |
| Intel Core 2 Duo   | 5         | 5.05%   |
| Intel Celeron      | 5         | 5.05%   |
| AMD E              | 2         | 2.02%   |
| Intel Pentium Dual | 1         | 1.01%   |
| Intel Genuine      | 1         | 1.01%   |
| Intel Core i9      | 1         | 1.01%   |
| AMD Ryzen 3 PRO    | 1         | 1.01%   |
| AMD Ryzen 3        | 1         | 1.01%   |
| AMD E2             | 1         | 1.01%   |
| AMD E1             | 1         | 1.01%   |
| AMD A8             | 1         | 1.01%   |
| AMD A6             | 1         | 1.01%   |
| AMD A4             | 1         | 1.01%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 47        | 47.47%  |
| 4      | 32        | 32.32%  |
| 6      | 12        | 12.12%  |
| 8      | 6         | 6.06%   |
| 12     | 1         | 1.01%   |
| 10     | 1         | 1.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 75        | 75.76%  |
| 1      | 24        | 24.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 23.76%  |
| 0x206a7    | 7         | 6.93%   |
| 0x306a9    | 6         | 5.94%   |
| 0x306d4    | 5         | 4.95%   |
| 0x08600104 | 5         | 4.95%   |
| 0x906ea    | 4         | 3.96%   |
| 0xa0652    | 3         | 2.97%   |
| 0x806ea    | 3         | 2.97%   |
| 0x706e5    | 3         | 2.97%   |
| 0x406e3    | 3         | 2.97%   |
| 0x40651    | 3         | 2.97%   |
| 0x0a50000c | 3         | 2.97%   |
| 0x906e9    | 2         | 1.98%   |
| 0x806c1    | 2         | 1.98%   |
| 0x6fd      | 2         | 1.98%   |
| 0x106e5    | 2         | 1.98%   |
| 0x08600106 | 2         | 1.98%   |
| 0x08108109 | 2         | 1.98%   |
| 0x07030105 | 2         | 1.98%   |
| 0x706a1    | 1         | 0.99%   |
| 0x6fb      | 1         | 0.99%   |
| 0x506e3    | 1         | 0.99%   |
| 0x506c9    | 1         | 0.99%   |
| 0x406c4    | 1         | 0.99%   |
| 0x40661    | 1         | 0.99%   |
| 0x306c3    | 1         | 0.99%   |
| 0x1067a    | 1         | 0.99%   |
| 0x10676    | 1         | 0.99%   |
| 0x08608103 | 1         | 0.99%   |
| 0x08608102 | 1         | 0.99%   |
| 0x08600103 | 1         | 0.99%   |
| 0x07030106 | 1         | 0.99%   |
| 0x07030104 | 1         | 0.99%   |
| 0x06006110 | 1         | 0.99%   |
| 0x0500010d | 1         | 0.99%   |
| 0x05000029 | 1         | 0.99%   |
| 0x03000027 | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 13.13%  |
| SandyBridge      | 9         | 9.09%   |
| Zen 2            | 8         | 8.08%   |
| Skylake          | 8         | 8.08%   |
| IvyBridge        | 7         | 7.07%   |
| Haswell          | 6         | 6.06%   |
| Broadwell        | 6         | 6.06%   |
| Puma             | 4         | 4.04%   |
| Penryn           | 4         | 4.04%   |
| Zen 3            | 3         | 3.03%   |
| TigerLake        | 3         | 3.03%   |
| Nehalem          | 3         | 3.03%   |
| IceLake          | 3         | 3.03%   |
| Core             | 3         | 3.03%   |
| CometLake        | 3         | 3.03%   |
| Zen+             | 2         | 2.02%   |
| Westmere         | 2         | 2.02%   |
| Goldmont plus    | 2         | 2.02%   |
| Bobcat           | 2         | 2.02%   |
| Alderlake Hybrid | 2         | 2.02%   |
| Unknown          | 2         | 2.02%   |
| Silvermont       | 1         | 1.01%   |
| K10 Llano        | 1         | 1.01%   |
| Goldmont         | 1         | 1.01%   |
| Excavator        | 1         | 1.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 68        | 53.97%  |
| Nvidia | 29        | 23.02%  |
| AMD    | 29        | 23.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 9         | 6.92%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 8         | 6.15%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 5.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 4.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 4.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 5         | 3.85%   |
| Intel HD Graphics 5500                                                    | 5         | 3.85%   |
| Intel UHD Graphics 620                                                    | 4         | 3.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 2.31%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.54%   |
| Nvidia GK208BM [GeForce 920M]                                             | 2         | 1.54%   |
| Nvidia GF108M [GeForce GT 525M]                                           | 2         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.54%   |
| Intel Iris Plus Graphics G7                                               | 2         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.54%   |
| AMD Wrestler [Radeon HD 6310]                                             | 2         | 1.54%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.54%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.54%   |
| AMD Lucienne                                                              | 2         | 1.54%   |
| AMD Barcelo                                                               | 2         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.77%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.77%   |
| Nvidia GT216M [GeForce GT 230M]                                           | 1         | 0.77%   |
| Nvidia GT216GLM [Quadro FX 880M]                                          | 1         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.77%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                              | 1         | 0.77%   |
| Nvidia GP104GLM [Quadro P5200 Mobile]                                     | 1         | 0.77%   |
| Nvidia GM107GLM [Quadro M2000M]                                           | 1         | 0.77%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.77%   |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 0.77%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.77%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 0.77%   |
| Nvidia GF119M [NVS 4200M]                                                 | 1         | 0.77%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 46.46%  |
| Intel + Nvidia | 20        | 20.2%   |
| 1 x AMD        | 19        | 19.19%  |
| AMD + Nvidia   | 5         | 5.05%   |
| 1 x Nvidia     | 4         | 4.04%   |
| 2 x AMD        | 3         | 3.03%   |
| Intel + AMD    | 2         | 2.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 91.92%  |
| Proprietary | 8         | 8.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 54.55%  |
| 0.01-0.5   | 14        | 14.14%  |
| 0.51-1.0   | 12        | 12.12%  |
| 1.01-2.0   | 8         | 8.08%   |
| 3.01-4.0   | 6         | 6.06%   |
| 5.01-6.0   | 4         | 4.04%   |
| 8.01-16.0  | 1         | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 19.13%  |
| LG Display              | 19        | 16.52%  |
| BOE                     | 17        | 14.78%  |
| Samsung Electronics     | 14        | 12.17%  |
| Chimei Innolux          | 13        | 11.3%   |
| Lenovo                  | 3         | 2.61%   |
| Hewlett-Packard         | 3         | 2.61%   |
| Dell                    | 3         | 2.61%   |
| Apple                   | 3         | 2.61%   |
| Sharp                   | 2         | 1.74%   |
| Goldstar                | 2         | 1.74%   |
| Chi Mei Optoelectronics | 2         | 1.74%   |
| Ancor Communications    | 2         | 1.74%   |
| Philips                 | 1         | 0.87%   |
| LG Philips              | 1         | 0.87%   |
| Iiyama                  | 1         | 0.87%   |
| HannStar                | 1         | 0.87%   |
| Hannspree               | 1         | 0.87%   |
| CPT                     | 1         | 0.87%   |
| BenQ                    | 1         | 0.87%   |
| ASUSTek Computer        | 1         | 0.87%   |
| Arnos Instruments       | 1         | 0.87%   |
| Acer                    | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.71%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 2         | 1.71%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.71%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.71%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.71%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.71%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 1.71%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO229E 1920x1080 309x174mm 14.0-inch        | 2         | 1.71%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4151 1366x768 344x194mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 1         | 0.85%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.85%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 0.85%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch              | 1         | 0.85%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 50.96%  |
| 1366x768 (WXGA)    | 30        | 28.85%  |
| 3840x2160 (4K)     | 5         | 4.81%   |
| 1600x900 (HD+)     | 5         | 4.81%   |
| 1280x800 (WXGA)    | 3         | 2.88%   |
| 1680x1050 (WSXGA+) | 2         | 1.92%   |
| 3440x1440          | 1         | 0.96%   |
| 2880x1800          | 1         | 0.96%   |
| 2560x1440 (QHD)    | 1         | 0.96%   |
| 2160x1440          | 1         | 0.96%   |
| 1920x1200 (WUXGA)  | 1         | 0.96%   |
| 1440x900 (WXGA+)   | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 56        | 48.7%   |
| 13     | 15        | 13.04%  |
| 17     | 8         | 6.96%   |
| 14     | 8         | 6.96%   |
| 24     | 6         | 5.22%   |
| 12     | 5         | 4.35%   |
| 27     | 3         | 2.61%   |
| 21     | 3         | 2.61%   |
| 23     | 2         | 1.74%   |
| 19     | 2         | 1.74%   |
| 18     | 2         | 1.74%   |
| 84     | 1         | 0.87%   |
| 40     | 1         | 0.87%   |
| 34     | 1         | 0.87%   |
| 20     | 1         | 0.87%   |
| 16     | 1         | 0.87%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 60.18%  |
| 201-300     | 13        | 11.5%   |
| 351-400     | 12        | 10.62%  |
| 501-600     | 9         | 7.96%   |
| 401-500     | 8         | 7.08%   |
| 801-900     | 1         | 0.88%   |
| 701-800     | 1         | 0.88%   |
| 1501-2000   | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 88        | 87.13%  |
| 16/10 | 11        | 10.89%  |
| 3/2   | 1         | 0.99%   |
| 21/9  | 1         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 50%     |
| 81-90          | 17        | 14.91%  |
| 121-130        | 7         | 6.14%   |
| 71-80          | 6         | 5.26%   |
| 201-250        | 6         | 5.26%   |
| 61-70          | 5         | 4.39%   |
| 151-200        | 4         | 3.51%   |
| 301-350        | 3         | 2.63%   |
| 251-300        | 3         | 2.63%   |
| 141-150        | 2         | 1.75%   |
| More than 1000 | 1         | 0.88%   |
| 351-500        | 1         | 0.88%   |
| 131-140        | 1         | 0.88%   |
| 501-1000       | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 44.64%  |
| 101-120       | 33        | 29.46%  |
| 51-100        | 18        | 16.07%  |
| 161-240       | 10        | 8.93%   |
| More than 240 | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 83        | 82.18%  |
| 2     | 16        | 15.84%  |
| 3     | 2         | 1.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 63        | 39.62%  |
| Realtek Semiconductor             | 54        | 33.96%  |
| Qualcomm Atheros                  | 15        | 9.43%   |
| Broadcom                          | 7         | 4.4%    |
| Ralink                            | 3         | 1.89%   |
| MediaTek                          | 3         | 1.89%   |
| ASIX Electronics                  | 3         | 1.89%   |
| Ericsson Business Mobile Networks | 2         | 1.26%   |
| Xiaomi                            | 1         | 0.63%   |
| Motorola PCS                      | 1         | 0.63%   |
| Marvell Technology Group          | 1         | 0.63%   |
| ICS Advent                        | 1         | 0.63%   |
| Huawei Technologies               | 1         | 0.63%   |
| Hewlett-Packard                   | 1         | 0.63%   |
| DisplayLink                       | 1         | 0.63%   |
| Dell                              | 1         | 0.63%   |
| Broadcom Limited                  | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 15.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 4.04%   |
| Intel Wireless 7265                                                    | 8         | 4.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 4.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.53%   |
| Intel Wireless 8260                                                    | 5         | 2.53%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 2.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 2.53%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.02%   |
| Intel Wireless 7260                                                    | 4         | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 1.52%   |
| Intel WiFi Link 5100                                                   | 3         | 1.52%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.52%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 1.01%   |
| Realtek 802.11ac NIC                                                   | 2         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 1.01%   |
| Intel Wireless 3160                                                    | 2         | 1.01%   |
| Intel Ethernet Connection I219-V                                       | 2         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 1.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.01%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module     | 2         | 1.01%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 2         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 1         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 61.62%  |
| Realtek Semiconductor | 16        | 16.16%  |
| Qualcomm Atheros      | 11        | 11.11%  |
| Broadcom              | 5         | 5.05%   |
| Ralink                | 3         | 3.03%   |
| MediaTek              | 2         | 2.02%   |
| Broadcom Limited      | 1         | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                              | 8         | 8%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 6         | 6%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 5         | 5%      |
| Intel Wireless 8260                                              | 5         | 5%      |
| Intel Wi-Fi 6 AX200                                              | 5         | 5%      |
| Intel Cannon Lake PCH CNVi WiFi                                  | 5         | 5%      |
| Intel Wireless 8265 / 8275                                       | 4         | 4%      |
| Intel Wireless 7260                                              | 4         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 3         | 3%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 3         | 3%      |
| Intel WiFi Link 5100                                             | 3         | 3%      |
| Intel Wi-Fi 6 AX201                                              | 3         | 3%      |
| Intel Centrino Ultimate-N 6300                                   | 3         | 3%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 2         | 2%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 2%      |
| Realtek 802.11ac NIC                                             | 2         | 2%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 2         | 2%      |
| Intel Wireless 3160                                              | 2         | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                   | 2         | 2%      |
| Intel Alder Lake-P PCH CNVi WiFi                                 | 2         | 2%      |
| Broadcom BCM4331 802.11a/b/g/n                                   | 2         | 2%      |
| Broadcom BCM43142 802.11b/g/n                                    | 2         | 2%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 1         | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 1         | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 1         | 1%      |
| Realtek RTL8191SEvB Wireless LAN Controller                      | 1         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 1%      |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                        | 1         | 1%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                        | 1         | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 1         | 1%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 1         | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 1         | 1%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 1         | 1%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter    | 1         | 1%      |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]          | 1         | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 1         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 1         | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                  | 1         | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 44        | 48.35%  |
| Intel                    | 28        | 30.77%  |
| Qualcomm Atheros         | 6         | 6.59%   |
| Broadcom                 | 4         | 4.4%    |
| ASIX Electronics         | 3         | 3.3%    |
| Xiaomi                   | 1         | 1.1%    |
| MediaTek                 | 1         | 1.1%    |
| Marvell Technology Group | 1         | 1.1%    |
| ICS Advent               | 1         | 1.1%    |
| Hewlett-Packard          | 1         | 1.1%    |
| DisplayLink              | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 31        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 8.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 8.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 5.38%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 3.23%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 2.15%   |
| Intel Ethernet Connection I219-V                                       | 2         | 2.15%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 2.15%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 2.15%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 2.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.08%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.08%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.08%   |
| MediaTek RMX3085                                                       | 1         | 1.08%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.08%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.08%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.08%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.08%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.08%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 1.08%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.08%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.08%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.08%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.08%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1         | 1.08%   |
| HP lt4120 Snapdragon X5 LTE                                            | 1         | 1.08%   |
| DisplayLink HP Port Replicator (Composite Device)                      | 1         | 1.08%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1         | 1.08%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 1.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 52.69%  |
| Ethernet | 83        | 44.62%  |
| Modem    | 4         | 2.15%   |
| Unknown  | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 78.7%   |
| Ethernet | 23        | 21.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 77        | 77.78%  |
| 1     | 20        | 20.2%   |
| 3     | 1         | 1.01%   |
| 0     | 1         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 70%     |
| Yes  | 30        | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 54.43%  |
| Realtek Semiconductor           | 7         | 8.86%   |
| Qualcomm Atheros Communications | 5         | 6.33%   |
| Broadcom                        | 5         | 6.33%   |
| Apple                           | 3         | 3.8%    |
| Realtek                         | 2         | 2.53%   |
| Ralink Technology               | 2         | 2.53%   |
| Lite-On Technology              | 2         | 2.53%   |
| IMC Networks                    | 2         | 2.53%   |
| Hewlett-Packard                 | 2         | 2.53%   |
| Dell                            | 2         | 2.53%   |
| Ralink                          | 1         | 1.27%   |
| MediaTek                        | 1         | 1.27%   |
| Foxconn International           | 1         | 1.27%   |
| ASUSTek Computer                | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 15        | 18.99%  |
| Intel Bluetooth Device                            | 7         | 8.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 6         | 7.59%   |
| Intel AX201 Bluetooth                             | 6         | 7.59%   |
| Realtek Bluetooth Radio                           | 5         | 6.33%   |
| Intel AX200 Bluetooth                             | 5         | 6.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 4         | 5.06%   |
| Realtek Bluetooth Radio                           | 2         | 2.53%   |
| Qualcomm Atheros  Bluetooth Device                | 2         | 2.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 2.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 2.53%   |
| Intel AX211 Bluetooth                             | 2         | 2.53%   |
| Apple Bluetooth Host Controller                   | 2         | 2.53%   |
| Realtek RTL8723B Bluetooth                        | 1         | 1.27%   |
| Realtek 802.11ac WLAN Adapter                     | 1         | 1.27%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 1.27%   |
| Ralink CSR BS8510                                 | 1         | 1.27%   |
| Ralink RT3290 Bluetooth                           | 1         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 1.27%   |
| MediaTek Wireless_Device                          | 1         | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 1         | 1.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 1.27%   |
| IMC Networks Wireless_Device                      | 1         | 1.27%   |
| IMC Networks Bluetooth Radio                      | 1         | 1.27%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 1.27%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 1.27%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 1.27%   |
| Dell Wireless 370 Bluetooth Mini-card             | 1         | 1.27%   |
| Dell DW375 Bluetooth Module                       | 1         | 1.27%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 1.27%   |
| ASUS BT-270 Bluetooth Adapter                     | 1         | 1.27%   |
| Apple Bluetooth USB Host Controller               | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 76        | 53.52%  |
| AMD                                  | 27        | 19.01%  |
| Nvidia                               | 24        | 16.9%   |
| Yealink Network Technology           | 1         | 0.7%    |
| Yamaha                               | 1         | 0.7%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.7%    |
| Realtek Semiconductor                | 1         | 0.7%    |
| QinHeng Electronics                  | 1         | 0.7%    |
| Mackie Designs                       | 1         | 0.7%    |
| Logitech                             | 1         | 0.7%    |
| Lenovo                               | 1         | 0.7%    |
| Focusrite-Novation                   | 1         | 0.7%    |
| Dell                                 | 1         | 0.7%    |
| C-Media Electronics                  | 1         | 0.7%    |
| BR25                                 | 1         | 0.7%    |
| Behringer.......                     | 1         | 0.7%    |
| BEHRINGER International              | 1         | 0.7%    |
| ASUSTek Computer                     | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 8.14%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 5.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 4.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 3.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 3.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.49%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 3.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.91%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 2.91%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.91%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.74%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.74%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.16%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.16%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.16%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.16%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.16%   |
| Yealink Network Technology VoIP Phone                                      | 1         | 0.58%   |
| Yamaha Steinberg UR242                                                     | 1         | 0.58%   |
| Thesycon Systemsoftware & Consulting Audio Interface                       | 1         | 0.58%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.58%   |
| QinHeng Electronics CH345 MIDI adapter                                     | 1         | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 31.67%  |
| SK hynix            | 33        | 27.5%   |
| Micron Technology   | 14        | 11.67%  |
| Kingston            | 13        | 10.83%  |
| Ramaxel Technology  | 4         | 3.33%   |
| Crucial             | 4         | 3.33%   |
| Unknown             | 3         | 2.5%    |
| Timetec             | 2         | 1.67%   |
| Nanya Technology    | 2         | 1.67%   |
| Transcend           | 1         | 0.83%   |
| Patriot             | 1         | 0.83%   |
| G.Skill             | 1         | 0.83%   |
| Elpida              | 1         | 0.83%   |
| Corsair             | 1         | 0.83%   |
| A-DATA Technology   | 1         | 0.83%   |
| Unknown             | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 3.1%    |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 4         | 3.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 2.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 2.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 3         | 2.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 2.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 2.33%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 2         | 1.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.55%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 1.55%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 1.55%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s     | 2         | 1.55%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.55%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 1.55%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.78%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.78%   |
| Timetec RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.78%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 0.78%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s              | 1         | 0.78%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s         | 1         | 0.78%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM 1334MT/s         | 1         | 0.78%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s       | 1         | 0.78%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 0.78%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.78%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s | 1         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 0.78%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2400MT/s       | 1         | 0.78%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB DDR4 2400MT/s              | 1         | 0.78%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 47        | 46.53%  |
| DDR4   | 42        | 41.58%  |
| DDR2   | 5         | 4.95%   |
| SDRAM  | 3         | 2.97%   |
| LPDDR4 | 2         | 1.98%   |
| LPDDR3 | 2         | 1.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 90        | 89.11%  |
| Row Of Chips | 8         | 7.92%   |
| Unknown      | 2         | 1.98%   |
| Chip         | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 39.32%  |
| 4096  | 40        | 34.19%  |
| 2048  | 13        | 11.11%  |
| 16384 | 12        | 10.26%  |
| 32768 | 3         | 2.56%   |
| 1024  | 3         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 37        | 34.26%  |
| 3200    | 19        | 17.59%  |
| 2667    | 15        | 13.89%  |
| 1334    | 10        | 9.26%   |
| 2400    | 7         | 6.48%   |
| 2133    | 5         | 4.63%   |
| 1333    | 4         | 3.7%    |
| 667     | 3         | 2.78%   |
| 4267    | 2         | 1.85%   |
| 4199    | 2         | 1.85%   |
| 1639    | 1         | 0.93%   |
| 1067    | 1         | 0.93%   |
| 800     | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

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


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1022 | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4200F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 24        | 26.67%  |
| IMC Networks                           | 9         | 10%     |
| Realtek Semiconductor                  | 7         | 7.78%   |
| Suyin                                  | 6         | 6.67%   |
| Sunplus Innovation Technology          | 5         | 5.56%   |
| Quanta                                 | 5         | 5.56%   |
| Bison Electronics                      | 5         | 5.56%   |
| Microdia                               | 4         | 4.44%   |
| Syntek                                 | 3         | 3.33%   |
| Lite-On Technology                     | 3         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.33%   |
| Sonix Technology                       | 2         | 2.22%   |
| Apple                                  | 2         | 2.22%   |
| ViewQuest Technologies                 | 1         | 1.11%   |
| Silicon Motion                         | 1         | 1.11%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.11%   |
| Ricoh                                  | 1         | 1.11%   |
| Razer USA                              | 1         | 1.11%   |
| Philips (or NXP)                       | 1         | 1.11%   |
| Luxvisions Innotech Limited            | 1         | 1.11%   |
| Logitech                               | 1         | 1.11%   |
| Importek                               | 1         | 1.11%   |
| HRY                                    | 1         | 1.11%   |
| Dell                                   | 1         | 1.11%   |
| Acer                                   | 1         | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                       | 6         | 6.59%   |
| IMC Networks Integrated Camera                  | 4         | 4.4%    |
| Syntek Integrated Camera                        | 3         | 3.3%    |
| Realtek Lenovo EasyCamera                       | 3         | 3.3%    |
| IMC Networks USB2.0 HD UVC WebCam               | 3         | 3.3%    |
| Chicony Integrated Camera [ThinkPad]            | 3         | 3.3%    |
| Chicony HD Webcam                               | 3         | 3.3%    |
| Chicony HD User Facing                          | 3         | 3.3%    |
| Suyin USB 2.0 Camera                            | 2         | 2.2%    |
| Suyin Asus Integrated Webcam                    | 2         | 2.2%    |
| Sunplus Integrated_Webcam_HD                    | 2         | 2.2%    |
| Sunplus HD WebCam                               | 2         | 2.2%    |
| Sonix USB2.0 HD UVC WebCam                      | 2         | 2.2%    |
| Microdia Integrated_Webcam_HD                   | 2         | 2.2%    |
| Chicony HP HD Camera                            | 2         | 2.2%    |
| Bison Integrated Camera                         | 2         | 2.2%    |
| Apple FaceTime HD Camera                        | 2         | 2.2%    |
| ViewQuest Ability GABB Webcam                   | 1         | 1.1%    |
| Suyin HP Webcam                                 | 1         | 1.1%    |
| Suyin HP TrueVision HD Integrated Webcam        | 1         | 1.1%    |
| Sunplus Dell HD Webcam                          | 1         | 1.1%    |
| Silicon Motion WebCam SCB-1100N                 | 1         | 1.1%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera | 1         | 1.1%    |
| Ricoh Sony Vaio Integrated Webcam               | 1         | 1.1%    |
| Realtek VGA WebCam                              | 1         | 1.1%    |
| Realtek Integrated_Webcam_HD                    | 1         | 1.1%    |
| Realtek HP Wide Vision HD Camera                | 1         | 1.1%    |
| Realtek HP "Truevision HD" laptop camera        | 1         | 1.1%    |
| Razer USA Gaming Webcam [Kiyo]                  | 1         | 1.1%    |
| Quanta ov9734_techfront_camera                  | 1         | 1.1%    |
| Quanta Laptop_Integrated_Webcam_2HDM            | 1         | 1.1%    |
| Quanta HP Webcam                                | 1         | 1.1%    |
| Quanta HP TrueVision HD Camera                  | 1         | 1.1%    |
| Quanta HP HD Camera                             | 1         | 1.1%    |
| Philips (or NXP) PCVC740K ToUcam Pro [pwc]      | 1         | 1.1%    |
| Microdia Sonix Integrated Webcam                | 1         | 1.1%    |
| Microdia Integrated Webcam HD                   | 1         | 1.1%    |
| Luxvisions Innotech Limited HP HD Camera        | 1         | 1.1%    |
| Logitech C922 Pro Stream Webcam                 | 1         | 1.1%    |
| Lite-On Integrated Camera                       | 1         | 1.1%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 47.37%  |
| Synaptics                  | 3         | 15.79%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| Samsung Electronics        | 1         | 5.26%   |
| LighTuning Technology      | 1         | 5.26%   |
| Focal-systems.Corp         | 1         | 5.26%   |
| AuthenTec                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 10.53%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 10.53%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 10.53%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 10.53%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 5.26%   |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 5.26%   |
| Validity Sensors Fingerprint scanner              | 1         | 5.26%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 5.26%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5.26%   |
| Focal-systems.Corp FT9201Fingerprint.             | 1         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Broadcom            | 5         | 41.67%  |
| Upek                | 3         | 25%     |
| Alcor Micro         | 2         | 16.67%  |
| Lenovo              | 1         | 8.33%   |
| Chicony Electronics | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 57        | 57.58%  |
| 1     | 36        | 36.36%  |
| 2     | 5         | 5.05%   |
| 3     | 1         | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 19        | 41.3%   |
| Chipcard              | 10        | 21.74%  |
| Graphics card         | 7         | 15.22%  |
| Net/wireless          | 3         | 6.52%   |
| Multimedia controller | 2         | 4.35%   |
| Camera                | 2         | 4.35%   |
| Storage               | 1         | 2.17%   |
| Card reader           | 1         | 2.17%   |
| Bluetooth             | 1         | 2.17%   |

