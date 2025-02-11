Ubuntu MATE 20.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

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

Total: 415

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Packard Be... | EasyNote TE11HC             | [8dab3905db](https://linux-hardware.org/?probe=8dab3905db) | Jan 01, 2024 |
| Acer          | Aspire 5050                 | [92930dd0d4](https://linux-hardware.org/?probe=92930dd0d4) | Nov 13, 2023 |
| Acer          | Aspire A515-45              | [b367027f2a](https://linux-hardware.org/?probe=b367027f2a) | Oct 30, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1deb55b03b](https://linux-hardware.org/?probe=1deb55b03b) | Sep 25, 2023 |
| Dell          | Inspiron 3593               | [1562efcaf2](https://linux-hardware.org/?probe=1562efcaf2) | Aug 27, 2023 |
| HP            | 250 G8 Notebook PC          | [60809c13e6](https://linux-hardware.org/?probe=60809c13e6) | Jul 15, 2023 |
| Dell          | G5 5590                     | [c956c1fd2e](https://linux-hardware.org/?probe=c956c1fd2e) | Jul 03, 2023 |
| Dell          | Studio 1558                 | [66e76ea87d](https://linux-hardware.org/?probe=66e76ea87d) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Lenovo        | IdeaPad S410p 20296         | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| Avell High... | A72 HYB                     | [c6f131b8b1](https://linux-hardware.org/?probe=c6f131b8b1) | May 24, 2023 |
| Avell High... | A72 HYB                     | [d54fb61d87](https://linux-hardware.org/?probe=d54fb61d87) | May 24, 2023 |
| HP            | Compaq Presario CQ60        | [5b51a121e2](https://linux-hardware.org/?probe=5b51a121e2) | May 18, 2023 |
| HP            | Laptop 15-ef2xxx            | [83f752ffd8](https://linux-hardware.org/?probe=83f752ffd8) | Apr 17, 2023 |
| ASUSTek       | U6Sg                        | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| Dell          | Latitude E6320              | [a6a0d01947](https://linux-hardware.org/?probe=a6a0d01947) | Mar 31, 2023 |
| Packard Be... | EasyNote TE11HC             | [ce6f515364](https://linux-hardware.org/?probe=ce6f515364) | Mar 19, 2023 |
| Packard Be... | EasyNote TE11HC             | [0bb94771bc](https://linux-hardware.org/?probe=0bb94771bc) | Mar 18, 2023 |
| Packard Be... | EasyNote TE11HC             | [4a54741fec](https://linux-hardware.org/?probe=4a54741fec) | Mar 12, 2023 |
| Packard Be... | EasyNote TE11HC             | [fb3c4afbaa](https://linux-hardware.org/?probe=fb3c4afbaa) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| Lenovo        | G500 20236                  | [d92542c9e8](https://linux-hardware.org/?probe=d92542c9e8) | Jan 14, 2023 |
| Acer          | AO756                       | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| Dell          | G5 5590                     | [c0bba3f9fd](https://linux-hardware.org/?probe=c0bba3f9fd) | Jan 04, 2023 |
| Dell          | G5 5590                     | [cb89cf0f00](https://linux-hardware.org/?probe=cb89cf0f00) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-C            | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Dell          | Latitude E5430 non-vPro     | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| ASUSTek       | T100TA                      | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| Dell          | Studio 1558                 | [ef9a6b217c](https://linux-hardware.org/?probe=ef9a6b217c) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| Sony          | VGN-CR120E                  | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Dell          | Studio 1558                 | [8b5cb100a8](https://linux-hardware.org/?probe=8b5cb100a8) | Nov 05, 2022 |
| HP            | Pavilion g6                 | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| HP            | Compaq Presario CQ71        | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Samsung       | 760XBE                      | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Samsung       | 760XBE                      | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | B51-30 80LK                 | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| HP            | EliteBook 840 G3            | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| HP            | 15                          | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Dell          | Precision 7520              | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| ASUSTek       | T100TA                      | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| HP            | Pavilion dv5                | [dd2f0b859b](https://linux-hardware.org/?probe=dd2f0b859b) | Aug 24, 2022 |
| HP            | ProBook 455 G7              | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| Google        | Swanky                      | [f54bdd7887](https://linux-hardware.org/?probe=f54bdd7887) | Aug 04, 2022 |
| Google        | Swanky                      | [daac706167](https://linux-hardware.org/?probe=daac706167) | Aug 02, 2022 |
| HP            | Pavilion g6                 | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Acer          | Aspire 5050                 | [59d8bb1e10](https://linux-hardware.org/?probe=59d8bb1e10) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | [a8bcc56e78](https://linux-hardware.org/?probe=a8bcc56e78) | Jul 26, 2022 |
| HP            | EliteBook 8570p             | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Dell          | Latitude XT                 | [9d9deeace5](https://linux-hardware.org/?probe=9d9deeace5) | Jul 10, 2022 |
| Dell          | Latitude XT                 | [b0a096fb7d](https://linux-hardware.org/?probe=b0a096fb7d) | Jul 10, 2022 |
| MicroByte     | ezbook                      | [0f08faf963](https://linux-hardware.org/?probe=0f08faf963) | Jul 08, 2022 |
| Dell          | XPS 17 9710                 | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| Dell          | XPS 13 9360                 | [73746e5672](https://linux-hardware.org/?probe=73746e5672) | Jun 03, 2022 |
| Fujitsu       | LIFEBOOK E5511              | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| HP            | Pavilion Power Laptop 15... | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| HP            | ProBook 650 G1              | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Medion        | Akoya E6415                 | [32545030d4](https://linux-hardware.org/?probe=32545030d4) | May 16, 2022 |
| Avell High... | A70 MOB                     | [c8900ed973](https://linux-hardware.org/?probe=c8900ed973) | May 15, 2022 |
| Avell High... | A62 LIV                     | [8b912c2c4f](https://linux-hardware.org/?probe=8b912c2c4f) | May 15, 2022 |
| HP            | Laptop 17-by3xxx            | [86c82d9ca0](https://linux-hardware.org/?probe=86c82d9ca0) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | [a55c5c5c9f](https://linux-hardware.org/?probe=a55c5c5c9f) | May 03, 2022 |
| Toshiba       | Satellite C660              | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| Dell          | Precision 3561              | [26fa0f202c](https://linux-hardware.org/?probe=26fa0f202c) | Apr 20, 2022 |
| Clevo         | W54xEU                      | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Clevo         | W54xEU                      | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| Dell          | XPS 13 9380                 | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| Samsung       | R505                        | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| Dell          | Latitude E5400              | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Lenovo        | G700 20251                  | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| HP            | Pavilion dv7                | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| Samsung       | R530/R730/R540              | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| Dell          | Studio 1558                 | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Dell          | Vostro 3350                 | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| ASUSTek       | X541UV                      | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| HP            | Pavilion dv7                | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| Dell          | Vostro 3401                 | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| Toshiba       | Satellite P755              | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| ASUSTek       | 1011PX                      | [776d052837](https://linux-hardware.org/?probe=776d052837) | Mar 09, 2022 |
| ASUSTek       | UX305FA                     | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| Fujitsu       | LIFEBOOK S752               | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| Acer          | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| Lenovo        | ThinkPad T460p 20FW000VU... | [9cbb915f78](https://linux-hardware.org/?probe=9cbb915f78) | Feb 18, 2022 |
| ASUSTek       | X553MA                      | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| Acer          | Aspire 7735                 | [38d97cd9da](https://linux-hardware.org/?probe=38d97cd9da) | Feb 06, 2022 |
| Dell          | XPS 15 9570                 | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Dell          | Latitude 3410               | [8f2181125e](https://linux-hardware.org/?probe=8f2181125e) | Jan 27, 2022 |
| ASUSTek       | X553MA                      | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| Dell          | XPS 12 9Q23                 | [3c8e26636b](https://linux-hardware.org/?probe=3c8e26636b) | Jan 15, 2022 |
| Dell          | Latitude E5400              | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| ASUSTek       | X541SA                      | [4103077e59](https://linux-hardware.org/?probe=4103077e59) | Jan 08, 2022 |
| Lenovo        | Flex 2-14 20404             | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| Acer          | Aspire A515-43              | [82163f143b](https://linux-hardware.org/?probe=82163f143b) | Dec 29, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| Lenovo        | G580 2189                   | [843f8c04fe](https://linux-hardware.org/?probe=843f8c04fe) | Dec 21, 2021 |
| HP            | ENVY Notebook               | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| Acer          | Aspire ES1-523              | [66a8186276](https://linux-hardware.org/?probe=66a8186276) | Dec 15, 2021 |
| Unknown       | Unknown                     | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| HP            | EliteBook Folio 9480m       | [2cd39490da](https://linux-hardware.org/?probe=2cd39490da) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Dell          | Latitude E6400              | [170f397883](https://linux-hardware.org/?probe=170f397883) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | [3b06bfa748](https://linux-hardware.org/?probe=3b06bfa748) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Polaroid      | MP1464PR001                 | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| HP            | EliteBook Folio 9480m       | [8b5c3b008f](https://linux-hardware.org/?probe=8b5c3b008f) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | [bf8ac4dc12](https://linux-hardware.org/?probe=bf8ac4dc12) | Nov 24, 2021 |
| Dell          | Precision 5560              | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| Acer          | TravelMate 5720             | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| HP            | ZBook Fury 17.3 inch G8 ... | [63f392ea8b](https://linux-hardware.org/?probe=63f392ea8b) | Nov 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [162531d482](https://linux-hardware.org/?probe=162531d482) | Nov 16, 2021 |
| Dell          | Vostro 5568                 | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | [e881f41269](https://linux-hardware.org/?probe=e881f41269) | Nov 14, 2021 |
| AMI           | Unknown                     | [d1cd5b09e1](https://linux-hardware.org/?probe=d1cd5b09e1) | Nov 12, 2021 |
| Toshiba       | Satellite C665              | [a136cdd51d](https://linux-hardware.org/?probe=a136cdd51d) | Nov 11, 2021 |
| HP            | ZBook 15                    | [835fb0e921](https://linux-hardware.org/?probe=835fb0e921) | Nov 10, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| GPD           | P2 MAX                      | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Dell          | Precision 7520              | [83df635945](https://linux-hardware.org/?probe=83df635945) | Oct 26, 2021 |
| HP            | Pavilion Notebook           | [cd2454732b](https://linux-hardware.org/?probe=cd2454732b) | Oct 25, 2021 |
| Lenovo        | ThinkPad L512 2598A59       | [0bc832bd49](https://linux-hardware.org/?probe=0bc832bd49) | Oct 19, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | [2bc2b5c1d6](https://linux-hardware.org/?probe=2bc2b5c1d6) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [b566b7f862](https://linux-hardware.org/?probe=b566b7f862) | Oct 13, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [26453872b1](https://linux-hardware.org/?probe=26453872b1) | Oct 12, 2021 |
| ASUSTek       | N43SL                       | [c5adc8860e](https://linux-hardware.org/?probe=c5adc8860e) | Oct 09, 2021 |
| Lenovo        | Z51-70 80K6                 | [219e5cd0d5](https://linux-hardware.org/?probe=219e5cd0d5) | Oct 04, 2021 |
| HP            | ProBook 455 G7              | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Dell          | Vostro 3350                 | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| Acer          | Aspire A515-43              | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| Teclast       | F15S                        | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| Packard Be... | EasyNote SL65               | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| Acer          | Extensa 5630                | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| ASUSTek       | X556UAK                     | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Acer          | Aspire E1-571               | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Dell          | Studio 1558                 | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| HP            | EliteBook 2170p             | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | Pavilion dv7                | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| Dell          | Latitude E6400              | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| Dell          | Latitude E6510              | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| ASUSTek       | K73SJ                       | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | Pavilion                    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| Dell          | Precision M4800             | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Dell          | G7 7588                     | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| Cube          | i18-L                       | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| HP            | Pavilion                    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| ONE-NETBOO... | A1                          | [86c38b0aca](https://linux-hardware.org/?probe=86c38b0aca) | Apr 23, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| Dell          | Inspiron 3480               | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fb0db0afbd](https://linux-hardware.org/?probe=fb0db0afbd) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [236be7c7e7](https://linux-hardware.org/?probe=236be7c7e7) | Apr 12, 2021 |
| HP            | Pavilion dv6                | [bf634bb665](https://linux-hardware.org/?probe=bf634bb665) | Apr 09, 2021 |
| HP            | 15                          | [acc9ccddfa](https://linux-hardware.org/?probe=acc9ccddfa) | Apr 08, 2021 |
| HP            | ProBook 4530s               | [12a7784eb4](https://linux-hardware.org/?probe=12a7784eb4) | Apr 06, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fa8acecaa2](https://linux-hardware.org/?probe=fa8acecaa2) | Apr 01, 2021 |
| Dell          | Latitude E7250              | [d88e8eb416](https://linux-hardware.org/?probe=d88e8eb416) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| Dell          | Latitude 7310               | [9f4c2f64a5](https://linux-hardware.org/?probe=9f4c2f64a5) | Mar 30, 2021 |
| Dell          | Latitude E7250              | [d1716d96f2](https://linux-hardware.org/?probe=d1716d96f2) | Mar 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [dc5e67af5a](https://linux-hardware.org/?probe=dc5e67af5a) | Mar 27, 2021 |
| Acer          | Aspire 4740                 | [3551944dd9](https://linux-hardware.org/?probe=3551944dd9) | Mar 25, 2021 |
| Samsung       | 760XBE                      | [3cacabef7b](https://linux-hardware.org/?probe=3cacabef7b) | Mar 23, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [92bcacad15](https://linux-hardware.org/?probe=92bcacad15) | Mar 22, 2021 |
| Samsung       | 760XBE                      | [26e28d0645](https://linux-hardware.org/?probe=26e28d0645) | Mar 21, 2021 |
| ASUSTek       | K50IE                       | [cc01498ee9](https://linux-hardware.org/?probe=cc01498ee9) | Mar 18, 2021 |
| MSI           | GF63 Thin 9SCSR             | [f58ddcc3f4](https://linux-hardware.org/?probe=f58ddcc3f4) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | [1919b6a57f](https://linux-hardware.org/?probe=1919b6a57f) | Mar 17, 2021 |
| HP            | Pavilion g7                 | [cc361e0dbf](https://linux-hardware.org/?probe=cc361e0dbf) | Mar 04, 2021 |
| Toshiba       | Satellite L350D             | [0286dc8c95](https://linux-hardware.org/?probe=0286dc8c95) | Mar 02, 2021 |
| HP            | Pavilion g7                 | [41d55a3dd7](https://linux-hardware.org/?probe=41d55a3dd7) | Feb 26, 2021 |
| Dell          | Precision M4800             | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5bd6c548d2](https://linux-hardware.org/?probe=5bd6c548d2) | Feb 15, 2021 |
| Positivo      | N8X0EK1                     | [c6ac8d6eca](https://linux-hardware.org/?probe=c6ac8d6eca) | Feb 15, 2021 |
| Dell          | Latitude E6500              | [75d199bcfd](https://linux-hardware.org/?probe=75d199bcfd) | Feb 12, 2021 |
| Dell          | Studio 1747                 | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | [952ca96633](https://linux-hardware.org/?probe=952ca96633) | Feb 09, 2021 |
| Notebook      | W310CZ/CZ-T                 | [2b60fc9e91](https://linux-hardware.org/?probe=2b60fc9e91) | Feb 09, 2021 |
| Acer          | Aspire ES1-521              | [73b3295031](https://linux-hardware.org/?probe=73b3295031) | Jan 29, 2021 |
| Dell          | G7 7588                     | [ae6d47978a](https://linux-hardware.org/?probe=ae6d47978a) | Jan 28, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| HP            | 250 G5 Notebook PC          | [f2e3b573f5](https://linux-hardware.org/?probe=f2e3b573f5) | Jan 16, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [e8b3cf2cbd](https://linux-hardware.org/?probe=e8b3cf2cbd) | Jan 14, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [8117aff9b0](https://linux-hardware.org/?probe=8117aff9b0) | Jan 14, 2021 |
| Medion        | X682X                       | [bf7dbceaa3](https://linux-hardware.org/?probe=bf7dbceaa3) | Jan 13, 2021 |
| Dell          | XPS 13 9370                 | [1b3b03be98](https://linux-hardware.org/?probe=1b3b03be98) | Jan 07, 2021 |
| HP            | 255 G7 Notebook PC          | [4f385a65db](https://linux-hardware.org/?probe=4f385a65db) | Jan 03, 2021 |
| Samsung       | SR58P                       | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1483935c23](https://linux-hardware.org/?probe=1483935c23) | Jan 02, 2021 |
| Acer          | Aspire E1-532P              | [a1f1287741](https://linux-hardware.org/?probe=a1f1287741) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [30041ef295](https://linux-hardware.org/?probe=30041ef295) | Jan 01, 2021 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HP            | Notebook                    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | [cfa92bb7f3](https://linux-hardware.org/?probe=cfa92bb7f3) | Dec 28, 2020 |
| ASUSTek       | X302LA                      | [f5dde37fb9](https://linux-hardware.org/?probe=f5dde37fb9) | Dec 26, 2020 |
| ASUSTek       | X302LA                      | [a35e9f4b28](https://linux-hardware.org/?probe=a35e9f4b28) | Dec 25, 2020 |
| Star Labs     | LabTop                      | [b8c8467e92](https://linux-hardware.org/?probe=b8c8467e92) | Dec 20, 2020 |
| Toshiba       | Satellite Pro L500          | [d01d9e0d34](https://linux-hardware.org/?probe=d01d9e0d34) | Dec 08, 2020 |
| Dell          | Inspiron 3520               | [be6f5d9f85](https://linux-hardware.org/?probe=be6f5d9f85) | Dec 07, 2020 |
| Dell          | Latitude D630               | [475177f3da](https://linux-hardware.org/?probe=475177f3da) | Dec 07, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [5862508036](https://linux-hardware.org/?probe=5862508036) | Dec 06, 2020 |
| HP            | Pavilion 17                 | [2f04deaf4e](https://linux-hardware.org/?probe=2f04deaf4e) | Dec 03, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [ee0aa7b52f](https://linux-hardware.org/?probe=ee0aa7b52f) | Dec 02, 2020 |
| Dell          | Precision 7710              | [f017e7a0d2](https://linux-hardware.org/?probe=f017e7a0d2) | Nov 30, 2020 |
| Acer          | Aspire E5-523               | [cfd9403111](https://linux-hardware.org/?probe=cfd9403111) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Dell          | Latitude E6400              | [a39e2e7fa3](https://linux-hardware.org/?probe=a39e2e7fa3) | Nov 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [833a22d4ee](https://linux-hardware.org/?probe=833a22d4ee) | Nov 20, 2020 |
| HP            | EliteBook 830 G6            | [c47a2f5f86](https://linux-hardware.org/?probe=c47a2f5f86) | Nov 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | [08c8440950](https://linux-hardware.org/?probe=08c8440950) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [968f302807](https://linux-hardware.org/?probe=968f302807) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [2a9231cde8](https://linux-hardware.org/?probe=2a9231cde8) | Nov 17, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [b8e7eedfed](https://linux-hardware.org/?probe=b8e7eedfed) | Nov 17, 2020 |
| Dell          | Latitude E6420              | [3452613a4c](https://linux-hardware.org/?probe=3452613a4c) | Nov 16, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | EliteBook Folio 9470m       | [659c1c8745](https://linux-hardware.org/?probe=659c1c8745) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | [248ce84271](https://linux-hardware.org/?probe=248ce84271) | Nov 05, 2020 |
| Dell          | Latitude E6420              | [6cdd815251](https://linux-hardware.org/?probe=6cdd815251) | Nov 04, 2020 |
| Dell          | Latitude E6420              | [10d44f2853](https://linux-hardware.org/?probe=10d44f2853) | Nov 04, 2020 |
| Acer          | Aspire A314-32              | [686d0b8c4f](https://linux-hardware.org/?probe=686d0b8c4f) | Nov 03, 2020 |
| Dell          | Latitude E6430              | [39ba29b6a3](https://linux-hardware.org/?probe=39ba29b6a3) | Nov 02, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [d9a9dae79a](https://linux-hardware.org/?probe=d9a9dae79a) | Oct 31, 2020 |
| Lenovo        | ThinkPad E520 1143B5G       | [146fc730d7](https://linux-hardware.org/?probe=146fc730d7) | Oct 29, 2020 |
| MSI           | GE72 7RE                    | [f75b251f96](https://linux-hardware.org/?probe=f75b251f96) | Oct 29, 2020 |
| Acer          | Aspire 5715Z                | [a2fca6b9da](https://linux-hardware.org/?probe=a2fca6b9da) | Oct 26, 2020 |
| Lenovo        | V570 HuronRiver Platform    | [62082c183e](https://linux-hardware.org/?probe=62082c183e) | Oct 26, 2020 |
| ASUSTek       | X751LK                      | [0dad6a22c5](https://linux-hardware.org/?probe=0dad6a22c5) | Oct 26, 2020 |
| HP            | Pavilion dv7                | [59e2fce913](https://linux-hardware.org/?probe=59e2fce913) | Oct 26, 2020 |
| Dell          | Precision M4800             | [2f91204b5e](https://linux-hardware.org/?probe=2f91204b5e) | Oct 26, 2020 |
| HP            | 255 G7 Notebook PC          | [fd598f0888](https://linux-hardware.org/?probe=fd598f0888) | Oct 25, 2020 |
| Dell          | G3 3590                     | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| Dell          | Latitude E6430              | [67b44ea2b4](https://linux-hardware.org/?probe=67b44ea2b4) | Oct 20, 2020 |
| HP            | Compaq 6730s                | [b8d5fd5eea](https://linux-hardware.org/?probe=b8d5fd5eea) | Oct 19, 2020 |
| HP            | Notebook                    | [669e2e8ce6](https://linux-hardware.org/?probe=669e2e8ce6) | Oct 19, 2020 |
| Lenovo        | G50-80 80R0                 | [51ec4152a2](https://linux-hardware.org/?probe=51ec4152a2) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c45c0eb7e4](https://linux-hardware.org/?probe=c45c0eb7e4) | Oct 16, 2020 |
| HP            | ProBook 4430s               | [c816b204bf](https://linux-hardware.org/?probe=c816b204bf) | Oct 15, 2020 |
| Lenovo        | ThinkPad X270 20HN0013MX    | [3dbb81e06d](https://linux-hardware.org/?probe=3dbb81e06d) | Oct 14, 2020 |
| Dell          | Latitude E6420              | [1e2a1974f2](https://linux-hardware.org/?probe=1e2a1974f2) | Oct 08, 2020 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [01948526e2](https://linux-hardware.org/?probe=01948526e2) | Oct 08, 2020 |
| Acer          | Aspire 5715Z                | [e112fe04f3](https://linux-hardware.org/?probe=e112fe04f3) | Oct 08, 2020 |
| Medion        | E15302                      | [957a41b1b5](https://linux-hardware.org/?probe=957a41b1b5) | Oct 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [28bab55cdf](https://linux-hardware.org/?probe=28bab55cdf) | Oct 02, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | [e2a36190d7](https://linux-hardware.org/?probe=e2a36190d7) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| System76      | Serval WS                   | [7add8e6511](https://linux-hardware.org/?probe=7add8e6511) | Sep 25, 2020 |
| Dell          | Precision M6700             | [1b20609aaa](https://linux-hardware.org/?probe=1b20609aaa) | Sep 25, 2020 |
| HP            | ProBook 440 G5              | [3140b90a75](https://linux-hardware.org/?probe=3140b90a75) | Sep 24, 2020 |
| Apple         | MacBook4,1                  | [91c2f7bfb9](https://linux-hardware.org/?probe=91c2f7bfb9) | Sep 20, 2020 |
| Dell          | Latitude E6410              | [6fa6138bb4](https://linux-hardware.org/?probe=6fa6138bb4) | Sep 18, 2020 |
| Dell          | Latitude E6410              | [8a3b88673f](https://linux-hardware.org/?probe=8a3b88673f) | Sep 17, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Dell          | Latitude E6410              | [8930b7e16f](https://linux-hardware.org/?probe=8930b7e16f) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [299b899172](https://linux-hardware.org/?probe=299b899172) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [b45cb0028d](https://linux-hardware.org/?probe=b45cb0028d) | Sep 16, 2020 |
| HP            | Compaq 8710w (GC124EA#AK... | [dc5006e254](https://linux-hardware.org/?probe=dc5006e254) | Sep 15, 2020 |
| Apple         | MacBook4,1                  | [092f9a6491](https://linux-hardware.org/?probe=092f9a6491) | Sep 15, 2020 |
| HP            | G42                         | [9cb42d6f5f](https://linux-hardware.org/?probe=9cb42d6f5f) | Sep 15, 2020 |
| HP            | G42                         | [72d647e1b9](https://linux-hardware.org/?probe=72d647e1b9) | Sep 15, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| Acer          | Aspire A315-42G             | [ab24b14a42](https://linux-hardware.org/?probe=ab24b14a42) | Sep 09, 2020 |
| Samsung       | 530U4E/540U4E               | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| Dell          | Latitude E6420              | [e3bc793dc3](https://linux-hardware.org/?probe=e3bc793dc3) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [676828b4d4](https://linux-hardware.org/?probe=676828b4d4) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [6057658605](https://linux-hardware.org/?probe=6057658605) | Sep 01, 2020 |
| Dell          | Latitude E6420              | [9b1f1928c7](https://linux-hardware.org/?probe=9b1f1928c7) | Sep 01, 2020 |
| Positivo      | Mobile                      | [2249764f28](https://linux-hardware.org/?probe=2249764f28) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [cae373d70b](https://linux-hardware.org/?probe=cae373d70b) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [c77cf6f3fa](https://linux-hardware.org/?probe=c77cf6f3fa) | Aug 30, 2020 |
| Toshiba       | Satellite M500              | [42449081bb](https://linux-hardware.org/?probe=42449081bb) | Aug 29, 2020 |
| HP            | 250 G4 Notebook PC          | [97eeff2c12](https://linux-hardware.org/?probe=97eeff2c12) | Aug 22, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| MSI           | GP72MVR 7RFX                | [39da2f58b5](https://linux-hardware.org/?probe=39da2f58b5) | Aug 16, 2020 |
| Dell          | Inspiron 7559               | [021ed0aac6](https://linux-hardware.org/?probe=021ed0aac6) | Aug 16, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0e5e076914](https://linux-hardware.org/?probe=0e5e076914) | Aug 15, 2020 |
| GPD           | MicroPC                     | [bb39ae1b31](https://linux-hardware.org/?probe=bb39ae1b31) | Aug 15, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3e086d75b0](https://linux-hardware.org/?probe=3e086d75b0) | Aug 12, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ab576b0cd8](https://linux-hardware.org/?probe=ab576b0cd8) | Aug 12, 2020 |
| ASUSTek       | X71SL                       | [f2da7fe3f0](https://linux-hardware.org/?probe=f2da7fe3f0) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| HP            | Pavilion dm1                | [ccb974921b](https://linux-hardware.org/?probe=ccb974921b) | Aug 05, 2020 |
| ASUSTek       | X71SL                       | [7bfd99a9bd](https://linux-hardware.org/?probe=7bfd99a9bd) | Aug 05, 2020 |
| Dell          | System XPS L702X            | [86885b0835](https://linux-hardware.org/?probe=86885b0835) | Aug 04, 2020 |
| MSI           | GV62 8RD                    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| Dell          | Inspiron 3421               | [09aac7d871](https://linux-hardware.org/?probe=09aac7d871) | Aug 01, 2020 |
| Dell          | Precision M4800             | [defc3ac914](https://linux-hardware.org/?probe=defc3ac914) | Aug 01, 2020 |
| Lenovo        | Flex 2-14D 20376            | [efd445830e](https://linux-hardware.org/?probe=efd445830e) | Jul 27, 2020 |
| Dell          | Inspiron 7520               | [a1ea369f96](https://linux-hardware.org/?probe=a1ea369f96) | Jul 27, 2020 |
| Dell          | Inspiron 3421               | [12424c5a76](https://linux-hardware.org/?probe=12424c5a76) | Jul 25, 2020 |
| HP            | Pavilion g4                 | [a10cfaa6e2](https://linux-hardware.org/?probe=a10cfaa6e2) | Jul 24, 2020 |
| HP            | EliteBook 2570p             | [baa26535f9](https://linux-hardware.org/?probe=baa26535f9) | Jul 23, 2020 |
| Dell          | Vostro 3560                 | [c83b65951c](https://linux-hardware.org/?probe=c83b65951c) | Jul 20, 2020 |
| HP            | ZBook 17 G2                 | [61d82db95d](https://linux-hardware.org/?probe=61d82db95d) | Jul 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8e5e5de5c3](https://linux-hardware.org/?probe=8e5e5de5c3) | Jul 20, 2020 |
| HP            | 250 G5 Notebook PC          | [9577cafcf7](https://linux-hardware.org/?probe=9577cafcf7) | Jul 19, 2020 |
| Lenovo        | ThinkPad T490 20N3CTO1WW    | [b6f9682f0b](https://linux-hardware.org/?probe=b6f9682f0b) | Jul 15, 2020 |
| ASUSTek       | X555LJ                      | [5657a6a512](https://linux-hardware.org/?probe=5657a6a512) | Jul 14, 2020 |
| Dell          | G7 7588                     | [8c4a8875bd](https://linux-hardware.org/?probe=8c4a8875bd) | Jul 14, 2020 |
| Dell          | G7 7588                     | [aee8398552](https://linux-hardware.org/?probe=aee8398552) | Jul 12, 2020 |
| Sony          | VPCF1290X                   | [f7c7a3ca92](https://linux-hardware.org/?probe=f7c7a3ca92) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [f4dd6bbdec](https://linux-hardware.org/?probe=f4dd6bbdec) | Jul 06, 2020 |
| Lenovo        | ThinkPad 11e 20D9CTO1WW     | [11c17aa062](https://linux-hardware.org/?probe=11c17aa062) | Jul 05, 2020 |
| Acer          | Aspire 7750G                | [f6a31e475d](https://linux-hardware.org/?probe=f6a31e475d) | Jul 05, 2020 |
| HP            | 250 G4                      | [ca40ef5473](https://linux-hardware.org/?probe=ca40ef5473) | Jul 02, 2020 |
| HP            | Pavilion g6                 | [0175164903](https://linux-hardware.org/?probe=0175164903) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| HP            | Pavilion g6                 | [efc97f097b](https://linux-hardware.org/?probe=efc97f097b) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [944b66e3ba](https://linux-hardware.org/?probe=944b66e3ba) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [3f58959650](https://linux-hardware.org/?probe=3f58959650) | Jun 24, 2020 |
| Lenovo        | ThinkPad T520 4243RS6       | [881175c7ec](https://linux-hardware.org/?probe=881175c7ec) | Jun 23, 2020 |
| HP            | ProBook 450 G5              | [143bbac73c](https://linux-hardware.org/?probe=143bbac73c) | Jun 23, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [c5a7e2708f](https://linux-hardware.org/?probe=c5a7e2708f) | Jun 22, 2020 |
| Lenovo        | ThinkPad X240 qqqq          | [04328e30ac](https://linux-hardware.org/?probe=04328e30ac) | Jun 15, 2020 |
| Sony          | VPCF1290X                   | [55652dadf6](https://linux-hardware.org/?probe=55652dadf6) | Jun 15, 2020 |
| Lenovo        | ThinkPad T430 2349H86       | [5ef2ab445e](https://linux-hardware.org/?probe=5ef2ab445e) | Jun 13, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [5467542c77](https://linux-hardware.org/?probe=5467542c77) | Jun 12, 2020 |
| HP            | Pavilion g6                 | [78f5ccb141](https://linux-hardware.org/?probe=78f5ccb141) | Jun 11, 2020 |
| Acer          | Nitro AN515-54              | [4c810c7859](https://linux-hardware.org/?probe=4c810c7859) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [35995e9a53](https://linux-hardware.org/?probe=35995e9a53) | Jun 06, 2020 |
| ASUSTek       | X541SA                      | [508fc56922](https://linux-hardware.org/?probe=508fc56922) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [d6bcbe862e](https://linux-hardware.org/?probe=d6bcbe862e) | Jun 05, 2020 |
| HP            | 250 G7 Notebook PC          | [56c24dddd4](https://linux-hardware.org/?probe=56c24dddd4) | May 31, 2020 |
| Packard Be... | EasyNote ME69BMP            | [7023dc94da](https://linux-hardware.org/?probe=7023dc94da) | May 28, 2020 |
| Dell          | Precision M6800             | [fac8dbf769](https://linux-hardware.org/?probe=fac8dbf769) | May 28, 2020 |
| Packard Be... | EasyNote ME69BMP            | [17cb4d2a9a](https://linux-hardware.org/?probe=17cb4d2a9a) | May 28, 2020 |
| Dell          | Precision M4800             | [4f404379b5](https://linux-hardware.org/?probe=4f404379b5) | May 27, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Toshiba       | Satellite M500              | [89bc529650](https://linux-hardware.org/?probe=89bc529650) | May 23, 2020 |
| Sony          | VPCF1290X                   | [6d41a82565](https://linux-hardware.org/?probe=6d41a82565) | May 22, 2020 |
| Sony          | VPCF1290X                   | [e260c25549](https://linux-hardware.org/?probe=e260c25549) | May 20, 2020 |
| ASUSTek       | X541SA                      | [af59d45f16](https://linux-hardware.org/?probe=af59d45f16) | May 19, 2020 |
| Dell          | Latitude E6400              | [5575a3dc87](https://linux-hardware.org/?probe=5575a3dc87) | May 17, 2020 |
| Dell          | Latitude E6400              | [4ad76f6e55](https://linux-hardware.org/?probe=4ad76f6e55) | May 16, 2020 |
| Dell          | Latitude E6400              | [9c8f7c7f2c](https://linux-hardware.org/?probe=9c8f7c7f2c) | May 16, 2020 |
| Dell          | Latitude E6400              | [0e2b5d699e](https://linux-hardware.org/?probe=0e2b5d699e) | May 16, 2020 |
| HP            | 250 G1                      | [bc48855d22](https://linux-hardware.org/?probe=bc48855d22) | May 16, 2020 |
| Lenovo        | ThinkPad X240 20AMS08816    | [5581eee295](https://linux-hardware.org/?probe=5581eee295) | May 10, 2020 |
| Dell          | System XPS L502X            | [f095fb06d8](https://linux-hardware.org/?probe=f095fb06d8) | May 09, 2020 |
| HP            | EliteBook 840 G2            | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Samsung       | 550P5C/550P7C               | [4262f676d3](https://linux-hardware.org/?probe=4262f676d3) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [015ef81b51](https://linux-hardware.org/?probe=015ef81b51) | May 02, 2020 |
| ASUSTek       | G73Sw                       | [d4abec1a93](https://linux-hardware.org/?probe=d4abec1a93) | May 02, 2020 |
| HP            | 250 G5 Notebook PC          | [f986b480ad](https://linux-hardware.org/?probe=f986b480ad) | May 01, 2020 |
| Dell          | Inspiron 3576               | [4dc9474ba1](https://linux-hardware.org/?probe=4dc9474ba1) | Apr 29, 2020 |
| Sony          | VPCS12X9E                   | [3631a4d89d](https://linux-hardware.org/?probe=3631a4d89d) | Apr 24, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| HP            | EliteBook 755 G5            | [db0ea12ab8](https://linux-hardware.org/?probe=db0ea12ab8) | Apr 16, 2020 |
| Dell          | XPS 13 9360                 | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [154b970640](https://linux-hardware.org/?probe=154b970640) | Mar 25, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [ad9b0ebdf6](https://linux-hardware.org/?probe=ad9b0ebdf6) | Feb 25, 2020 |
| Acer          | Aspire V3-574G              | [471f9aa9b0](https://linux-hardware.org/?probe=471f9aa9b0) | Jan 02, 2020 |
| MSI           | GP72 6QF                    | [98dc37dc79](https://linux-hardware.org/?probe=98dc37dc79) | Oct 21, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 24        | 7.12%   |
| 5.4.0-52-generic  | 17        | 5.04%   |
| 5.4.0-47-generic  | 10        | 2.97%   |
| 5.4.0-40-generic  | 10        | 2.97%   |
| 5.4.0-58-generic  | 9         | 2.67%   |
| 5.8.0-50-generic  | 8         | 2.37%   |
| 5.4.0-48-generic  | 8         | 2.37%   |
| 5.4.0-31-generic  | 8         | 2.37%   |
| 5.4.0-26-generic  | 8         | 2.37%   |
| 5.4.0-65-generic  | 7         | 2.08%   |
| 5.11.0-40-generic | 7         | 2.08%   |
| 5.4.0-56-generic  | 6         | 1.78%   |
| 5.4.0-54-generic  | 6         | 1.78%   |
| 5.4.0-45-generic  | 6         | 1.78%   |
| 5.11.0-38-generic | 6         | 1.78%   |
| 5.8.0-59-generic  | 5         | 1.48%   |
| 5.8.0-48-generic  | 5         | 1.48%   |
| 5.8.0-43-generic  | 5         | 1.48%   |
| 5.4.0-81-generic  | 5         | 1.48%   |
| 5.4.0-37-generic  | 5         | 1.48%   |
| 5.4.0-29-generic  | 5         | 1.48%   |
| 5.13.0-41-generic | 5         | 1.48%   |
| 5.13.0-30-generic | 5         | 1.48%   |
| 5.11.0-37-generic | 5         | 1.48%   |
| 5.8.0-53-generic  | 4         | 1.19%   |
| 5.4.0-91-generic  | 4         | 1.19%   |
| 5.4.0-89-generic  | 4         | 1.19%   |
| 5.4.0-51-generic  | 4         | 1.19%   |
| 5.13.0-39-generic | 4         | 1.19%   |
| 5.4.0-90-generic  | 3         | 0.89%   |
| 5.4.0-74-generic  | 3         | 0.89%   |
| 5.4.0-73-generic  | 3         | 0.89%   |
| 5.4.0-39-generic  | 3         | 0.89%   |
| 5.4.0-33-generic  | 3         | 0.89%   |
| 5.4.0-28-generic  | 3         | 0.89%   |
| 5.15.0-41-generic | 3         | 0.89%   |
| 5.11.0-43-generic | 3         | 0.89%   |
| 5.11.0-41-generic | 3         | 0.89%   |
| 5.11.0-27-generic | 3         | 0.89%   |
| 5.8.0-63-generic  | 2         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 183       | 59.22%  |
| 5.8.0   | 33        | 10.68%  |
| 5.11.0  | 31        | 10.03%  |
| 5.13.0  | 27        | 8.74%   |
| 5.15.0  | 24        | 7.77%   |
| 5.14.0  | 4         | 1.29%   |
| 5.3.0   | 2         | 0.65%   |
| 5.9.3   | 1         | 0.32%   |
| 5.8.17  | 1         | 0.32%   |
| 5.15.6  | 1         | 0.32%   |
| 5.15.34 | 1         | 0.32%   |
| 5.15.27 | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 183       | 59.22%  |
| 5.8     | 34        | 11%     |
| 5.11    | 31        | 10.03%  |
| 5.15    | 27        | 8.74%   |
| 5.13    | 27        | 8.74%   |
| 5.14    | 4         | 1.29%   |
| 5.3     | 2         | 0.65%   |
| 5.9     | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 304       | 99.67%  |
| aarch64 | 1         | 0.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 297       | 97.38%  |
| Cinnamon   | 3         | 0.98%   |
| GNOME      | 2         | 0.66%   |
| X-Cinnamon | 1         | 0.33%   |
| KDE5       | 1         | 0.33%   |
| i3         | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 299       | 98.03%  |
| Wayland | 3         | 0.98%   |
| Tty     | 3         | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 116       | 37.3%   |
| TDM     | 99        | 31.83%  |
| Unknown | 76        | 24.44%  |
| GDM     | 16        | 5.14%   |
| GDM3    | 3         | 0.96%   |
| SDDM    | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 112       | 36.6%   |
| fr_FR | 33        | 10.78%  |
| pt_BR | 30        | 9.8%    |
| en_GB | 18        | 5.88%   |
| de_DE | 16        | 5.23%   |
| es_ES | 15        | 4.9%    |
| it_IT | 12        | 3.92%   |
| ru_RU | 8         | 2.61%   |
| C     | 7         | 2.29%   |
| ru_UA | 6         | 1.96%   |
| pl_PL | 5         | 1.63%   |
| es_AR | 4         | 1.31%   |
| nl_NL | 3         | 0.98%   |
| en_PH | 3         | 0.98%   |
| en_IN | 3         | 0.98%   |
| de_CH | 3         | 0.98%   |
| en_CA | 2         | 0.65%   |
| en_AU | 2         | 0.65%   |
| ca_ES | 2         | 0.65%   |
| zh_TW | 1         | 0.33%   |
| zh_CN | 1         | 0.33%   |
| uk_UA | 1         | 0.33%   |
| sv_SE | 1         | 0.33%   |
| sk_SK | 1         | 0.33%   |
| nl_BE | 1         | 0.33%   |
| hu_HU | 1         | 0.33%   |
| fr_CH | 1         | 0.33%   |
| fr_CA | 1         | 0.33%   |
| fr_BE | 1         | 0.33%   |
| fi_FI | 1         | 0.33%   |
| et_EE | 1         | 0.33%   |
| es_UY | 1         | 0.33%   |
| es_PR | 1         | 0.33%   |
| es_PE | 1         | 0.33%   |
| es_MX | 1         | 0.33%   |
| en_NZ | 1         | 0.33%   |
| en_IL | 1         | 0.33%   |
| en_IE | 1         | 0.33%   |
| da_DK | 1         | 0.33%   |
| cs_CZ | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 159       | 52.13%  |
| BIOS | 146       | 47.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 285       | 92.83%  |
| Overlay | 11        | 3.58%   |
| Btrfs   | 3         | 0.98%   |
| Zfs     | 2         | 0.65%   |
| Xfs     | 2         | 0.65%   |
| Tmpfs   | 2         | 0.65%   |
| Ext3    | 2         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 124       | 40.39%  |
| Unknown | 97        | 31.6%   |
| MBR     | 86        | 28.01%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 274       | 87.82%  |
| Yes       | 38        | 12.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 68.73%  |
| Yes       | 96        | 31.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 66        | 21.64%  |
| Hewlett-Packard        | 63        | 20.66%  |
| Dell                   | 62        | 20.33%  |
| ASUSTek Computer       | 26        | 8.52%   |
| Acer                   | 23        | 7.54%   |
| Toshiba                | 10        | 3.28%   |
| Samsung Electronics    | 8         | 2.62%   |
| MSI                    | 7         | 2.3%    |
| Sony                   | 4         | 1.31%   |
| Packard Bell           | 3         | 0.98%   |
| Medion                 | 3         | 0.98%   |
| Avell High Performance | 3         | 0.98%   |
| Positivo               | 2         | 0.66%   |
| Notebook               | 2         | 0.66%   |
| GPD                    | 2         | 0.66%   |
| Fujitsu                | 2         | 0.66%   |
| Apple                  | 2         | 0.66%   |
| Unknown                | 2         | 0.66%   |
| Wortmann AG            | 1         | 0.33%   |
| TUXEDO                 | 1         | 0.33%   |
| Teclast                | 1         | 0.33%   |
| System76               | 1         | 0.33%   |
| Star Labs              | 1         | 0.33%   |
| Polaroid               | 1         | 0.33%   |
| Pine Microsystems      | 1         | 0.33%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.33%   |
| MicroByte              | 1         | 0.33%   |
| Intel                  | 1         | 0.33%   |
| Google                 | 1         | 0.33%   |
| Cube                   | 1         | 0.33%   |
| Clevo                  | 1         | 0.33%   |
| Chuwi                  | 1         | 0.33%   |
| AMI                    | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Dell Latitude E6420             | 5         | 1.64%   |
| HP Pavilion dv7                 | 4         | 1.31%   |
| HP Pavilion g6                  | 3         | 0.98%   |
| HP Notebook                     | 3         | 0.98%   |
| Dell Precision M4800            | 3         | 0.98%   |
| Dell Latitude E6410             | 3         | 0.98%   |
| Unknown                         | 3         | 0.98%   |
| Toshiba Satellite C660          | 2         | 0.66%   |
| HP EliteBook 8470p              | 2         | 0.66%   |
| HP 15                           | 2         | 0.66%   |
| Dell XPS 13 9360                | 2         | 0.66%   |
| Dell Vostro 3350                | 2         | 0.66%   |
| Dell Precision 7520             | 2         | 0.66%   |
| Dell Latitude E6430             | 2         | 0.66%   |
| Dell Inspiron 3421              | 2         | 0.66%   |
| ASUS ZenBook UX431DA_UM431DA    | 2         | 0.66%   |
| ASUS X553MA                     | 2         | 0.66%   |
| ASUS X541SA                     | 2         | 0.66%   |
| Acer Aspire 5050                | 2         | 0.66%   |
| Wortmann AG TERRA_MOBILE_1749   | 1         | 0.33%   |
| TUXEDO InfinityBook Pro 14 Gen6 | 1         | 0.33%   |
| Toshiba Satellite Pro L500      | 1         | 0.33%   |
| Toshiba Satellite Pro C660      | 1         | 0.33%   |
| Toshiba Satellite P755          | 1         | 0.33%   |
| Toshiba Satellite M500          | 1         | 0.33%   |
| Toshiba Satellite L350D         | 1         | 0.33%   |
| Toshiba Satellite C675          | 1         | 0.33%   |
| Toshiba Satellite C665          | 1         | 0.33%   |
| Toshiba Satellite C50D-C        | 1         | 0.33%   |
| Teclast F15S                    | 1         | 0.33%   |
| System76 Serval WS              | 1         | 0.33%   |
| Star Labs LabTop                | 1         | 0.33%   |
| Sony VPCS12X9E                  | 1         | 0.33%   |
| Sony VPCF1290X                  | 1         | 0.33%   |
| Sony VPCEH1S1E                  | 1         | 0.33%   |
| Sony VGN-CR120E                 | 1         | 0.33%   |
| Samsung SR58P                   | 1         | 0.33%   |
| Samsung R530/R730/R540          | 1         | 0.33%   |
| Samsung R505                    | 1         | 0.33%   |
| Samsung 760XBE                  | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 41        | 13.44%  |
| Dell Latitude         | 23        | 7.54%   |
| HP Pavilion           | 20        | 6.56%   |
| Acer Aspire           | 18        | 5.9%    |
| HP EliteBook          | 11        | 3.61%   |
| Toshiba Satellite     | 10        | 3.28%   |
| Lenovo IdeaPad        | 10        | 3.28%   |
| Dell Precision        | 10        | 3.28%   |
| Dell Inspiron         | 9         | 2.95%   |
| Dell XPS              | 7         | 2.3%    |
| HP 250                | 6         | 1.97%   |
| Dell Vostro           | 6         | 1.97%   |
| HP ProBook            | 5         | 1.64%   |
| HP ZBook              | 4         | 1.31%   |
| HP Laptop             | 4         | 1.31%   |
| HP Compaq             | 4         | 1.31%   |
| ASUS VivoBook         | 4         | 1.31%   |
| Packard Bell EasyNote | 3         | 0.98%   |
| HP Notebook           | 3         | 0.98%   |
| Unknown               | 3         | 0.98%   |
| Lenovo ThinkBook      | 2         | 0.66%   |
| Lenovo Legion         | 2         | 0.66%   |
| Lenovo Flex           | 2         | 0.66%   |
| HP 15                 | 2         | 0.66%   |
| Fujitsu LIFEBOOK      | 2         | 0.66%   |
| Dell System           | 2         | 0.66%   |
| Dell Studio           | 2         | 0.66%   |
| ASUS ZenBook          | 2         | 0.66%   |
| ASUS X553MA           | 2         | 0.66%   |
| ASUS X541SA           | 2         | 0.66%   |
| Acer TravelMate       | 2         | 0.66%   |
| Wortmann AG TERRA     | 1         | 0.33%   |
| TUXEDO InfinityBook   | 1         | 0.33%   |
| Teclast F15S          | 1         | 0.33%   |
| System76 Serval       | 1         | 0.33%   |
| Star Labs LabTop      | 1         | 0.33%   |
| Sony VPCS12X9E        | 1         | 0.33%   |
| Sony VPCF1290X        | 1         | 0.33%   |
| Sony VPCEH1S1E        | 1         | 0.33%   |
| Sony VGN-CR120E       | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 37        | 12.13%  |
| 2012    | 32        | 10.49%  |
| 2019    | 30        | 9.84%   |
| 2013    | 25        | 8.2%    |
| 2020    | 24        | 7.87%   |
| 2018    | 21        | 6.89%   |
| 2015    | 20        | 6.56%   |
| 2014    | 19        | 6.23%   |
| 2016    | 18        | 5.9%    |
| 2008    | 18        | 5.9%    |
| 2010    | 17        | 5.57%   |
| 2017    | 16        | 5.25%   |
| 2021    | 13        | 4.26%   |
| 2009    | 7         | 2.3%    |
| 2007    | 4         | 1.31%   |
| 2006    | 2         | 0.66%   |
| 2022    | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 305       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 275       | 89.87%  |
| Enabled  | 31        | 10.13%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 304       | 99.67%  |
| Yes  | 1         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 89        | 28.8%   |
| 4.01-8.0    | 82        | 26.54%  |
| 8.01-16.0   | 48        | 15.53%  |
| 16.01-24.0  | 43        | 13.92%  |
| 32.01-64.0  | 18        | 5.83%   |
| 64.01-256.0 | 9         | 2.91%   |
| 1.01-2.0    | 9         | 2.91%   |
| 2.01-3.0    | 7         | 2.27%   |
| 24.01-32.0  | 4         | 1.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 129       | 39.57%  |
| 2.01-3.0   | 83        | 25.46%  |
| 3.01-4.0   | 41        | 12.58%  |
| 4.01-8.0   | 40        | 12.27%  |
| 0.51-1.0   | 24        | 7.36%   |
| 8.01-16.0  | 8         | 2.45%   |
| 24.01-32.0 | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 227       | 72.52%  |
| 2      | 75        | 23.96%  |
| 3      | 9         | 2.88%   |
| 4      | 1         | 0.32%   |
| 0      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 54.9%   |
| Yes       | 138       | 45.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 264       | 86.56%  |
| No        | 41        | 13.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 300       | 97.72%  |
| No        | 7         | 2.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 75%     |
| No        | 77        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| Brazil          | 41        | 13.4%   |
| USA             | 36        | 11.76%  |
| France          | 35        | 11.44%  |
| Germany         | 28        | 9.15%   |
| Spain           | 18        | 5.88%   |
| UK              | 16        | 5.23%   |
| Italy           | 15        | 4.9%    |
| Russia          | 12        | 3.92%   |
| Ukraine         | 9         | 2.94%   |
| Switzerland     | 7         | 2.29%   |
| Netherlands     | 7         | 2.29%   |
| Indonesia       | 6         | 1.96%   |
| Argentina       | 6         | 1.96%   |
| Poland          | 4         | 1.31%   |
| Canada          | 4         | 1.31%   |
| Turkey          | 3         | 0.98%   |
| Sweden          | 3         | 0.98%   |
| Norway          | 3         | 0.98%   |
| India           | 3         | 0.98%   |
| Greece          | 3         | 0.98%   |
| Finland         | 3         | 0.98%   |
| Denmark         | 3         | 0.98%   |
| Vietnam         | 2         | 0.65%   |
| Thailand        | 2         | 0.65%   |
| Portugal        | 2         | 0.65%   |
| Philippines     | 2         | 0.65%   |
| Mexico          | 2         | 0.65%   |
| Ireland         | 2         | 0.65%   |
| Chile           | 2         | 0.65%   |
| Belgium         | 2         | 0.65%   |
| Australia       | 2         | 0.65%   |
| Venezuela       | 1         | 0.33%   |
| Uruguay         | 1         | 0.33%   |
| The Netherlands | 1         | 0.33%   |
| Taiwan          | 1         | 0.33%   |
| Slovakia        | 1         | 0.33%   |
| Réunion        | 1         | 0.33%   |
| Puerto Rico     | 1         | 0.33%   |
| Peru            | 1         | 0.33%   |
| New Zealand     | 1         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 21        | 6.58%   |
| Paris             | 7         | 2.19%   |
| Moscow            | 6         | 1.88%   |
| Kyiv              | 5         | 1.57%   |
| Barcelona         | 5         | 1.57%   |
| Rome              | 3         | 0.94%   |
| Rio de Janeiro    | 3         | 0.94%   |
| Berlin            | 3         | 0.94%   |
| Seville           | 2         | 0.63%   |
| Samara            | 2         | 0.63%   |
| Saint-Cloud       | 2         | 0.63%   |
| Porto Alegre      | 2         | 0.63%   |
| Oslo              | 2         | 0.63%   |
| Marseille         | 2         | 0.63%   |
| Manchester        | 2         | 0.63%   |
| Jakarta           | 2         | 0.63%   |
| Huissen           | 2         | 0.63%   |
| Ho Chi Minh City  | 2         | 0.63%   |
| Gigean            | 2         | 0.63%   |
| Getxo             | 2         | 0.63%   |
| Genoa             | 2         | 0.63%   |
| Frankfurt am Main | 2         | 0.63%   |
| Evansville        | 2         | 0.63%   |
| Essen             | 2         | 0.63%   |
| Durham            | 2         | 0.63%   |
| Dresden           | 2         | 0.63%   |
| Draper            | 2         | 0.63%   |
| Clichy-sous-Bois  | 2         | 0.63%   |
| Brooklyn          | 2         | 0.63%   |
| Bristol           | 2         | 0.63%   |
| Balikpapan        | 2         | 0.63%   |
| Athens            | 2         | 0.63%   |
| Ankara            | 2         | 0.63%   |
| Amsterdam         | 2         | 0.63%   |
| Albuquerque       | 2         | 0.63%   |
| Akron             | 2         | 0.63%   |
| Zurich            | 1         | 0.31%   |
| Zagreb            | 1         | 0.31%   |
| Yogyakarta        | 1         | 0.31%   |
| Xining            | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 51        | 58     | 13.25%  |
| Seagate               | 51        | 56     | 13.25%  |
| Samsung Electronics   | 48        | 55     | 12.47%  |
| Toshiba               | 37        | 43     | 9.61%   |
| Kingston              | 29        | 34     | 7.53%   |
| Unknown               | 23        | 26     | 5.97%   |
| SanDisk               | 21        | 28     | 5.45%   |
| SK hynix              | 15        | 20     | 3.9%    |
| Hitachi               | 15        | 17     | 3.9%    |
| Intel                 | 11        | 15     | 2.86%   |
| Crucial               | 11        | 16     | 2.86%   |
| A-DATA Technology     | 10        | 12     | 2.6%    |
| Micron Technology     | 5         | 6      | 1.3%    |
| KIOXIA                | 5         | 6      | 1.3%    |
| HGST                  | 5         | 5      | 1.3%    |
| China                 | 5         | 6      | 1.3%    |
| Phison                | 4         | 4      | 1.04%   |
| PNY                   | 3         | 3      | 0.78%   |
| Fujitsu               | 3         | 3      | 0.78%   |
| Transcend             | 2         | 3      | 0.52%   |
| Silicon Motion        | 2         | 2      | 0.52%   |
| SAGE                  | 2         | 2      | 0.52%   |
| Patriot               | 2         | 2      | 0.52%   |
| LITEONIT              | 2         | 3      | 0.52%   |
| LITEON                | 2         | 2      | 0.52%   |
| KingSpec              | 2         | 2      | 0.52%   |
| Intenso               | 2         | 2      | 0.52%   |
| Apacer                | 2         | 3      | 0.52%   |
| XPG                   | 1         | 1      | 0.26%   |
| Vaseky                | 1         | 1      | 0.26%   |
| Smart                 | 1         | 1      | 0.26%   |
| SABRENT               | 1         | 1      | 0.26%   |
| Realtek Semiconductor | 1         | 1      | 0.26%   |
| Ramos Technology      | 1         | 1      | 0.26%   |
| Plextor               | 1         | 1      | 0.26%   |
| OCZ                   | 1         | 1      | 0.26%   |
| Netac                 | 1         | 1      | 0.26%   |
| Mass                  | 1         | 1      | 0.26%   |
| LaCie                 | 1         | 1      | 0.26%   |
| HS-SSD-E100           | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD         | 8         | 2.03%   |
| Toshiba MQ01ABF050 500GB                | 7         | 1.77%   |
| Kingston SA400S37120G 120GB SSD         | 7         | 1.77%   |
| Seagate ST320LT007-9ZV142 320GB         | 6         | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 1.27%   |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 1.01%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.01%   |
| Seagate ST500LT012-1DG142 500GB         | 4         | 1.01%   |
| Hitachi HTS545050B9A300 500GB           | 4         | 1.01%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.76%   |
| Unknown MMC Card  16GB                  | 3         | 0.76%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 3         | 0.76%   |
| Seagate ST9500420AS 500GB               | 3         | 0.76%   |
| Seagate ST500LT012-9WS142 500GB         | 3         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.76%   |
| Seagate ST1000LM014-1EJ164 1TB          | 3         | 0.76%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.76%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.76%   |
| Intel SSDPEKNW512G8 512GB               | 3         | 0.76%   |
| Hitachi HTS547564A9E384 640GB           | 3         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.51%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 0.51%   |
| WDC WD5000BPKT-75PK4T0 500GB            | 2         | 0.51%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 2         | 0.51%   |
| WDC WD10SPZX-08Z10 1TB                  | 2         | 0.51%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB      | 2         | 0.51%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 2         | 0.51%   |
| Unknown DA4064  64GB                    | 2         | 0.51%   |
| Transcend TS512GMTS430S 512GB SSD       | 2         | 0.51%   |
| Toshiba MQ01ACF032 320GB                | 2         | 0.51%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.51%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.51%   |
| Toshiba MK7559GSXP 752GB                | 2         | 0.51%   |
| Seagate ST9500325AS 500GB               | 2         | 0.51%   |
| Seagate ST9250410AS 250GB               | 2         | 0.51%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 0.51%   |
| Seagate ST500LM000-SSHD-8GB             | 2         | 0.51%   |
| Seagate ST2000LM015-2E8174 2TB          | 2         | 0.51%   |
| SanDisk SD6SB2M-512G-1006 512GB SSD     | 2         | 0.51%   |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 55     | 35.66%  |
| WDC                 | 34        | 39     | 23.78%  |
| Toshiba             | 29        | 34     | 20.28%  |
| Hitachi             | 15        | 17     | 10.49%  |
| HGST                | 5         | 5      | 3.5%    |
| Fujitsu             | 3         | 3      | 2.1%    |
| Samsung Electronics | 2         | 2      | 1.4%    |
| SAGE                | 2         | 2      | 1.4%    |
| SABRENT             | 1         | 1      | 0.7%    |
| LaCie               | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 37     | 23.53%  |
| Kingston            | 27        | 32     | 19.85%  |
| SanDisk             | 15        | 21     | 11.03%  |
| Crucial             | 9         | 14     | 6.62%   |
| WDC                 | 6         | 6      | 4.41%   |
| A-DATA Technology   | 6         | 8      | 4.41%   |
| China               | 5         | 6      | 3.68%   |
| Intel               | 4         | 7      | 2.94%   |
| Toshiba             | 3         | 3      | 2.21%   |
| PNY                 | 3         | 3      | 2.21%   |
| Transcend           | 2         | 3      | 1.47%   |
| SK hynix            | 2         | 4      | 1.47%   |
| Micron Technology   | 2         | 3      | 1.47%   |
| LITEONIT            | 2         | 3      | 1.47%   |
| KingSpec            | 2         | 2      | 1.47%   |
| Intenso             | 2         | 2      | 1.47%   |
| Apacer              | 2         | 3      | 1.47%   |
| Vaseky              | 1         | 1      | 0.74%   |
| Smart               | 1         | 1      | 0.74%   |
| Seagate             | 1         | 1      | 0.74%   |
| Ramos Technology    | 1         | 1      | 0.74%   |
| Plextor             | 1         | 1      | 0.74%   |
| Patriot             | 1         | 1      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| Netac               | 1         | 1      | 0.74%   |
| LITEON              | 1         | 1      | 0.74%   |
| HS-SSD-E100         | 1         | 1      | 0.74%   |
| FORESEE             | 1         | 1      | 0.74%   |
| Dogfish             | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 136       | 159    | 37.78%  |
| SSD     | 124       | 169    | 34.44%  |
| NVMe    | 77        | 91     | 21.39%  |
| MMC     | 21        | 28     | 5.83%   |
| Unknown | 2         | 2      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 235       | 318    | 68.12%  |
| NVMe | 77        | 91     | 22.32%  |
| MMC  | 21        | 28     | 6.09%   |
| SAS  | 12        | 12     | 3.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 182       | 233    | 68.68%  |
| 0.51-1.0   | 69        | 78     | 26.04%  |
| 1.01-2.0   | 12        | 15     | 4.53%   |
| 3.01-4.0   | 2         | 2      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 95        | 30.25%  |
| 101-250        | 91        | 28.98%  |
| 501-1000       | 48        | 15.29%  |
| 1-20           | 19        | 6.05%   |
| 51-100         | 19        | 6.05%   |
| 1001-2000      | 17        | 5.41%   |
| 21-50          | 11        | 3.5%    |
| More than 3000 | 7         | 2.23%   |
| 2001-3000      | 7         | 2.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 110       | 33.85%  |
| 51-100         | 55        | 16.92%  |
| 101-250        | 54        | 16.62%  |
| 21-50          | 51        | 15.69%  |
| 251-500        | 31        | 9.54%   |
| 501-1000       | 16        | 4.92%   |
| 1001-2000      | 5         | 1.54%   |
| More than 3000 | 2         | 0.62%   |
| 2001-3000      | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT007-9ZV142 320GB   | 4         | 4      | 10.53%  |
| WDC WD3200BEVT-60ZCT1 320GB       | 2         | 2      | 5.26%   |
| Toshiba MK7559GSXP 752GB          | 2         | 2      | 5.26%   |
| WDC WD7500BPVT-75HXZT1 752GB      | 1         | 1      | 2.63%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1         | 1      | 2.63%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 2.63%   |
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 2      | 2.63%   |
| WDC WD3200BEKT-60V5T1 320GB       | 1         | 1      | 2.63%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 2.63%   |
| Vaseky V820/1TB SSD               | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 2.63%   |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 2.63%   |
| Toshiba MK2565GSXN 250GB          | 1         | 1      | 2.63%   |
| Toshiba MK2555GSX 250GB           | 1         | 1      | 2.63%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.63%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 2.63%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 2.63%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 2.63%   |
| Seagate ST320LT012-9WS14C 320GB   | 1         | 1      | 2.63%   |
| SanDisk SD7SN3Q256G1002 256GB SSD | 1         | 1      | 2.63%   |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 2.63%   |
| OCZ VERTEX450 128GB SSD           | 1         | 1      | 2.63%   |
| Intel SSDSC2KF256H6L 256GB        | 1         | 1      | 2.63%   |
| Hitachi HTS722016K9A300 160GB     | 1         | 1      | 2.63%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 2.63%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.63%   |
| Hitachi HTS541616J9SA00 160GB     | 1         | 1      | 2.63%   |
| Fujitsu MHZ2320BH G1 320GB        | 1         | 1      | 2.63%   |
| China SSD 120GB                   | 1         | 1      | 2.63%   |
| A-DATA Technology SU650 120GB SSD | 1         | 3      | 2.63%   |
| A-DATA Technology SP900 64GB SSD  | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 28.95%  |
| WDC                 | 8         | 9      | 21.05%  |
| Toshiba             | 6         | 6      | 15.79%  |
| Hitachi             | 4         | 4      | 10.53%  |
| A-DATA Technology   | 2         | 4      | 5.26%   |
| Vaseky              | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| Samsung Electronics | 1         | 1      | 2.63%   |
| OCZ                 | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| Fujitsu             | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 35.48%  |
| WDC                 | 8         | 9      | 25.81%  |
| Toshiba             | 6         | 6      | 19.35%  |
| Hitachi             | 4         | 4      | 12.9%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 32     | 81.58%  |
| SSD  | 7         | 9      | 18.42%  |

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
| Works    | 173       | 231    | 52.58%  |
| Detected | 119       | 177    | 36.17%  |
| Malfunc  | 37        | 41     | 11.25%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 229       | 67.16%  |
| AMD                              | 33        | 9.68%   |
| SanDisk                          | 16        | 4.69%   |
| Samsung Electronics              | 15        | 4.4%    |
| SK hynix                         | 12        | 3.52%   |
| Toshiba America Info Systems     | 7         | 2.05%   |
| ADATA Technology                 | 5         | 1.47%   |
| Phison Electronics               | 4         | 1.17%   |
| KIOXIA                           | 4         | 1.17%   |
| Silicon Motion                   | 3         | 0.88%   |
| Micron Technology                | 3         | 0.88%   |
| Silicon Integrated Systems [SiS] | 2         | 0.59%   |
| Micron/Crucial Technology        | 2         | 0.59%   |
| Kingston Technology Company      | 2         | 0.59%   |
| Solid State Storage Technology   | 1         | 0.29%   |
| Realtek Semiconductor            | 1         | 0.29%   |
| Nvidia                           | 1         | 0.29%   |
| Lite-On Technology               | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 35        | 9.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 8.13%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 24        | 6.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 19        | 5.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 4.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 15        | 4.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 3.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 3.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 2.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.63%   |
| SK hynix BC511 NVMe SSD                                                          | 5         | 1.36%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 5         | 1.36%   |
| Intel SSD 660P Series                                                            | 5         | 1.36%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 5         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.36%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 4         | 1.08%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 4         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 3         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 0.81%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.81%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.81%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.81%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 229       | 65.62%  |
| NVMe | 76        | 21.78%  |
| RAID | 23        | 6.59%   |
| IDE  | 21        | 6.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 265       | 86.89%  |
| AMD    | 39        | 12.79%  |
| ARM    | 1         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 1.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 1.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.31%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.31%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 1.31%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.31%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.31%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.31%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.31%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.31%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 3         | 0.98%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 0.98%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.98%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.98%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.98%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.98%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.98%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.98%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 3         | 0.98%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.98%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.66%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.66%   |
| Intel Genuine CPU T1600 @ 1.66GHz             | 2         | 0.66%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.66%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 2         | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.66%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 2         | 0.66%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 2         | 0.66%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.66%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.66%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 2         | 0.66%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 86        | 28.2%   |
| Intel Core i7                  | 76        | 24.92%  |
| Intel Core i3                  | 26        | 8.52%   |
| Intel Core 2 Duo               | 15        | 4.92%   |
| Intel Celeron                  | 15        | 4.92%   |
| Other                          | 13        | 4.26%   |
| Intel Pentium                  | 13        | 4.26%   |
| AMD Ryzen 5                    | 7         | 2.3%    |
| AMD Ryzen 7                    | 6         | 1.97%   |
| Intel Atom                     | 5         | 1.64%   |
| Intel Pentium Dual-Core        | 4         | 1.31%   |
| AMD A6                         | 4         | 1.31%   |
| Intel Core m3                  | 3         | 0.98%   |
| AMD A4                         | 3         | 0.98%   |
| Intel Xeon                     | 2         | 0.66%   |
| Intel Genuine                  | 2         | 0.66%   |
| Intel Core M                   | 2         | 0.66%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.66%   |
| AMD Ryzen 9                    | 2         | 0.66%   |
| AMD Ryzen 3                    | 2         | 0.66%   |
| AMD A8                         | 2         | 0.66%   |
| Intel Pentium Silver           | 1         | 0.33%   |
| Intel Pentium Dual             | 1         | 0.33%   |
| Intel Core i9                  | 1         | 0.33%   |
| Intel Core 2 Extreme           | 1         | 0.33%   |
| Intel Celeron Dual-Core        | 1         | 0.33%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.33%   |
| AMD Turion 64 Mobile           | 1         | 0.33%   |
| AMD Ryzen 7 PRO                | 1         | 0.33%   |
| AMD Ryzen 5 PRO                | 1         | 0.33%   |
| AMD Phenom II                  | 1         | 0.33%   |
| AMD E2                         | 1         | 0.33%   |
| AMD E1                         | 1         | 0.33%   |
| AMD E                          | 1         | 0.33%   |
| AMD Athlon X2                  | 1         | 0.33%   |
| AMD Athlon                     | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 175       | 57.19%  |
| 4      | 103       | 33.66%  |
| 6      | 13        | 4.25%   |
| 8      | 10        | 3.27%   |
| 1      | 3         | 0.98%   |
| 14     | 1         | 0.33%   |
| 3      | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 304       | 99.67%  |
| 2      | 1         | 0.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 221       | 72.46%  |
| 1      | 84        | 27.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 305       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 12.62%  |
| 0x206a7    | 35        | 11.33%  |
| 0x306a9    | 31        | 10.03%  |
| 0x306d4    | 13        | 4.21%   |
| 0x1067a    | 12        | 3.88%   |
| 0x806e9    | 11        | 3.56%   |
| 0x806ec    | 10        | 3.24%   |
| 0x40651    | 10        | 3.24%   |
| 0x406e3    | 9         | 2.91%   |
| 0x306c3    | 9         | 2.91%   |
| 0x706e5    | 8         | 2.59%   |
| 0x6fd      | 8         | 2.59%   |
| 0x806ea    | 7         | 2.27%   |
| 0x20655    | 7         | 2.27%   |
| 0x906ea    | 6         | 1.94%   |
| 0x806c1    | 6         | 1.94%   |
| 0x20652    | 6         | 1.94%   |
| 0x08108102 | 6         | 1.94%   |
| 0x906e9    | 5         | 1.62%   |
| 0x406c4    | 5         | 1.62%   |
| 0x30678    | 5         | 1.62%   |
| 0x706a1    | 4         | 1.29%   |
| 0x506e3    | 4         | 1.29%   |
| 0x06006705 | 4         | 1.29%   |
| 0x806d1    | 3         | 0.97%   |
| 0x406c3    | 3         | 0.97%   |
| 0x30673    | 3         | 0.97%   |
| 0x08600106 | 3         | 0.97%   |
| 0x07030105 | 3         | 0.97%   |
| 0x02000032 | 3         | 0.97%   |
| 0xa0652    | 2         | 0.65%   |
| 0x906ed    | 2         | 0.65%   |
| 0x806eb    | 2         | 0.65%   |
| 0x6fa      | 2         | 0.65%   |
| 0x506c9    | 2         | 0.65%   |
| 0x106e5    | 2         | 0.65%   |
| 0x10676    | 2         | 0.65%   |
| 0x08108109 | 2         | 0.65%   |
| 0x08101016 | 2         | 0.65%   |
| 0xa0660    | 1         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 16.72%  |
| SandyBridge      | 39        | 12.79%  |
| IvyBridge        | 34        | 11.15%  |
| Haswell          | 24        | 7.87%   |
| Skylake          | 16        | 5.25%   |
| Silvermont       | 16        | 5.25%   |
| Broadwell        | 16        | 5.25%   |
| Penryn           | 14        | 4.59%   |
| Westmere         | 13        | 4.26%   |
| IceLake          | 12        | 3.93%   |
| Core             | 10        | 3.28%   |
| Zen+             | 8         | 2.62%   |
| TigerLake        | 6         | 1.97%   |
| Puma             | 5         | 1.64%   |
| Excavator        | 5         | 1.64%   |
| Zen 2            | 4         | 1.31%   |
| Goldmont plus    | 4         | 1.31%   |
| Zen 3            | 3         | 0.98%   |
| Zen              | 3         | 0.98%   |
| K8 & K10 hybrid  | 3         | 0.98%   |
| Goldmont         | 3         | 0.98%   |
| CometLake        | 3         | 0.98%   |
| Unknown          | 3         | 0.98%   |
| Nehalem          | 2         | 0.66%   |
| K8 Hammer        | 2         | 0.66%   |
| Bobcat           | 2         | 0.66%   |
| Piledriver       | 1         | 0.33%   |
| K10              | 1         | 0.33%   |
| Bonnell          | 1         | 0.33%   |
| Alderlake Hybrid | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 243       | 63.95%  |
| Nvidia                           | 74        | 19.47%  |
| AMD                              | 62        | 16.32%  |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 8.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 8.48%   |
| Intel HD Graphics 5500                                                                   | 14        | 3.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.57%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.29%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.29%   |
| Intel HD Graphics 620                                                                    | 5         | 1.29%   |
| Intel HD Graphics 530                                                                    | 5         | 1.29%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.29%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.03%   |
| Intel HD Graphics 630                                                                    | 4         | 1.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.03%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 1.03%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.77%   |
| Intel HD Graphics 500                                                                    | 3         | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.77%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.77%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.51%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 2         | 0.51%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 170       | 55.74%  |
| Intel + Nvidia | 57        | 18.69%  |
| 1 x AMD        | 39        | 12.79%  |
| Intel + AMD    | 16        | 5.25%   |
| 1 x Nvidia     | 15        | 4.92%   |
| 2 x AMD        | 4         | 1.31%   |
| AMD + Nvidia   | 2         | 0.66%   |
| Other          | 1         | 0.33%   |
| 1 x SiS        | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 254       | 82.74%  |
| Proprietary | 42        | 13.68%  |
| Unknown     | 11        | 3.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 215       | 70.03%  |
| 0.01-0.5   | 27        | 8.79%   |
| 1.01-2.0   | 25        | 8.14%   |
| 0.51-1.0   | 18        | 5.86%   |
| 3.01-4.0   | 14        | 4.56%   |
| 5.01-6.0   | 4         | 1.3%    |
| 2.01-3.0   | 3         | 0.98%   |
| 7.01-8.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 66        | 19.47%  |
| LG Display              | 60        | 17.7%   |
| Samsung Electronics     | 46        | 13.57%  |
| Chimei Innolux          | 43        | 12.68%  |
| BOE                     | 32        | 9.44%   |
| Dell                    | 13        | 3.83%   |
| Chi Mei Optoelectronics | 13        | 3.83%   |
| PANDA                   | 8         | 2.36%   |
| Sharp                   | 6         | 1.77%   |
| LG Philips              | 5         | 1.47%   |
| Hewlett-Packard         | 5         | 1.47%   |
| Philips                 | 4         | 1.18%   |
| Lenovo                  | 4         | 1.18%   |
| Goldstar                | 4         | 1.18%   |
| InnoLux Display         | 3         | 0.88%   |
| Apple                   | 3         | 0.88%   |
| Sony                    | 2         | 0.59%   |
| Iiyama                  | 2         | 0.59%   |
| CSO                     | 2         | 0.59%   |
| AOC                     | 2         | 0.59%   |
| Ancor Communications    | 2         | 0.59%   |
| Acer                    | 2         | 0.59%   |
| ___                     | 1         | 0.29%   |
| Vizio                   | 1         | 0.29%   |
| Unknown                 | 1         | 0.29%   |
| Seiko/Epson             | 1         | 0.29%   |
| Optoma                  | 1         | 0.29%   |
| NEC Computers           | 1         | 0.29%   |
| MS_ Nvidia              | 1         | 0.29%   |
| Medion                  | 1         | 0.29%   |
| LGD                     | 1         | 0.29%   |
| InfoVision              | 1         | 0.29%   |
| HannStar                | 1         | 0.29%   |
| CPT                     | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 1.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 1.74%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 1.16%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.87%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 3         | 0.87%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.87%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 0.58%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch        | 2         | 0.58%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.58%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 2         | 0.58%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.58%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.58%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 2         | 0.58%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                        | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 310x170mm 13.9-inch          | 2         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 2         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.58%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.58%   |
| ___ LCDTV16 ___9000 1360x768                                             | 1         | 0.29%   |
| Vizio D24f-F1 VIZ1027 1920x1080 530x300mm 24.0-inch                      | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 118       | 36.99%  |
| 1920x1080 (FHD)    | 112       | 35.11%  |
| 1600x900 (HD+)     | 29        | 9.09%   |
| 1280x800 (WXGA)    | 15        | 4.7%    |
| 2560x1440 (QHD)    | 8         | 2.51%   |
| 1440x900 (WXGA+)   | 7         | 2.19%   |
| 1680x1050 (WSXGA+) | 6         | 1.88%   |
| 3840x2160 (4K)     | 5         | 1.57%   |
| 1920x1200 (WUXGA)  | 5         | 1.57%   |
| 3440x1440          | 2         | 0.63%   |
| 3200x1800 (QHD+)   | 2         | 0.63%   |
| 2560x1600          | 2         | 0.63%   |
| 1360x768           | 2         | 0.63%   |
| 2880x1800          | 1         | 0.31%   |
| 2160x1440          | 1         | 0.31%   |
| 1680x945           | 1         | 0.31%   |
| 1600x1200          | 1         | 0.31%   |
| 1400x1050          | 1         | 0.31%   |
| 1024x600           | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 138       | 40.59%  |
| 14      | 44        | 12.94%  |
| 13      | 43        | 12.65%  |
| 17      | 30        | 8.82%   |
| 12      | 14        | 4.12%   |
| 21      | 9         | 2.65%   |
| 24      | 8         | 2.35%   |
| 23      | 8         | 2.35%   |
| 11      | 8         | 2.35%   |
| 27      | 6         | 1.76%   |
| Unknown | 6         | 1.76%   |
| 18      | 5         | 1.47%   |
| 22      | 4         | 1.18%   |
| 34      | 2         | 0.59%   |
| 31      | 2         | 0.59%   |
| 20      | 2         | 0.59%   |
| 19      | 2         | 0.59%   |
| 10      | 2         | 0.59%   |
| 72      | 1         | 0.29%   |
| 65      | 1         | 0.29%   |
| 49      | 1         | 0.29%   |
| 46      | 1         | 0.29%   |
| 29      | 1         | 0.29%   |
| 16      | 1         | 0.29%   |
| 8       | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 200       | 59%     |
| 201-300     | 44        | 12.98%  |
| 351-400     | 36        | 10.62%  |
| 401-500     | 22        | 6.49%   |
| 501-600     | 21        | 6.19%   |
| Unknown     | 6         | 1.77%   |
| 601-700     | 3         | 0.88%   |
| 1001-1500   | 3         | 0.88%   |
| 701-800     | 2         | 0.59%   |
| 1501-2000   | 1         | 0.29%   |
| 101-200     | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 266       | 86.36%  |
| 16/10   | 31        | 10.06%  |
| 3/2     | 4         | 1.3%    |
| Unknown | 3         | 0.97%   |
| 21/9    | 2         | 0.65%   |
| 4/3     | 1         | 0.32%   |
| 0.62    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 136       | 40.12%  |
| 81-90          | 68        | 20.06%  |
| 201-250        | 24        | 7.08%   |
| 121-130        | 23        | 6.78%   |
| 71-80          | 19        | 5.6%    |
| 61-70          | 14        | 4.13%   |
| 51-60          | 8         | 2.36%   |
| 131-140        | 7         | 2.06%   |
| 301-350        | 6         | 1.77%   |
| 151-200        | 6         | 1.77%   |
| Unknown        | 6         | 1.77%   |
| 351-500        | 4         | 1.18%   |
| 251-300        | 4         | 1.18%   |
| 141-150        | 4         | 1.18%   |
| More than 1000 | 3         | 0.88%   |
| 41-50          | 2         | 0.59%   |
| 111-120        | 2         | 0.59%   |
| 1-40           | 1         | 0.29%   |
| 501-1000       | 1         | 0.29%   |
| 91-100         | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 127       | 37.91%  |
| 121-160       | 113       | 33.73%  |
| 51-100        | 55        | 16.42%  |
| 161-240       | 22        | 6.57%   |
| More than 240 | 8         | 2.39%   |
| Unknown       | 6         | 1.79%   |
| 1-50          | 4         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 253       | 81.88%  |
| 2     | 44        | 14.24%  |
| 3     | 6         | 1.94%   |
| 0     | 6         | 1.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 159       | 32.78%  |
| Realtek Semiconductor             | 155       | 31.96%  |
| Qualcomm Atheros                  | 81        | 16.7%   |
| Broadcom                          | 35        | 7.22%   |
| Broadcom Limited                  | 13        | 2.68%   |
| Ralink                            | 7         | 1.44%   |
| Marvell Technology Group          | 6         | 1.24%   |
| Ralink Technology                 | 5         | 1.03%   |
| Sierra Wireless                   | 4         | 0.82%   |
| Xiaomi                            | 2         | 0.41%   |
| TP-Link                           | 2         | 0.41%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.41%   |
| Ericsson Business Mobile Networks | 2         | 0.41%   |
| Tenda                             | 1         | 0.21%   |
| Samsung Electronics               | 1         | 0.21%   |
| Qualcomm Atheros Communications   | 1         | 0.21%   |
| Qualcomm                          | 1         | 0.21%   |
| NetGear                           | 1         | 0.21%   |
| Lenovo                            | 1         | 0.21%   |
| Hewlett-Packard                   | 1         | 0.21%   |
| Fibocom                           | 1         | 0.21%   |
| Dell                              | 1         | 0.21%   |
| Attansic Technology               | 1         | 0.21%   |
| ASUSTek Computer                  | 1         | 0.21%   |
| ASIX Electronics                  | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 92        | 15.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 40        | 6.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 23        | 3.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 2.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2.36%   |
| Intel Wireless 7265                                                     | 14        | 2.36%   |
| Intel Wireless 7260                                                     | 14        | 2.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.52%   |
| Intel Wireless 8265 / 8275                                              | 9         | 1.52%   |
| Intel Wireless 3165                                                     | 9         | 1.52%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.35%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.18%   |
| Intel Wireless 8260                                                     | 6         | 1.01%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.01%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.84%   |
| Intel Ethernet Connection I218-LM                                       | 5         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.67%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 0.67%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.67%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 150       | 46.88%  |
| Qualcomm Atheros                | 70        | 21.88%  |
| Realtek Semiconductor           | 38        | 11.88%  |
| Broadcom                        | 24        | 7.5%    |
| Broadcom Limited                | 12        | 3.75%   |
| Ralink                          | 7         | 2.19%   |
| Ralink Technology               | 5         | 1.56%   |
| Sierra Wireless                 | 4         | 1.25%   |
| TP-Link                         | 2         | 0.63%   |
| Tenda                           | 1         | 0.31%   |
| Qualcomm Atheros Communications | 1         | 0.31%   |
| Qualcomm                        | 1         | 0.31%   |
| NetGear                         | 1         | 0.31%   |
| Hewlett-Packard                 | 1         | 0.31%   |
| Fibocom                         | 1         | 0.31%   |
| Dell                            | 1         | 0.31%   |
| ASUSTek Computer                | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 4.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 4.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 4.38%   |
| Intel Wireless 7265                                                     | 14        | 4.38%   |
| Intel Wireless 7260                                                     | 14        | 4.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 4.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 3.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.81%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.81%   |
| Intel Wireless 3165                                                     | 9         | 2.81%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 2.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 2.19%   |
| Intel Wireless 8260                                                     | 6         | 1.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.88%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.56%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.25%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.25%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.94%   |
| Intel Wireless 3160                                                     | 3         | 0.94%   |
| Intel WiFi Link 5100                                                    | 3         | 0.94%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.94%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter    | 3         | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.94%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.63%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.63%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 146       | 54.48%  |
| Intel                            | 74        | 27.61%  |
| Qualcomm Atheros                 | 18        | 6.72%   |
| Broadcom                         | 14        | 5.22%   |
| Marvell Technology Group         | 6         | 2.24%   |
| Xiaomi                           | 2         | 0.75%   |
| Silicon Integrated Systems [SiS] | 2         | 0.75%   |
| Broadcom Limited                 | 2         | 0.75%   |
| Samsung Electronics              | 1         | 0.37%   |
| Lenovo                           | 1         | 0.37%   |
| Attansic Technology              | 1         | 0.37%   |
| ASIX Electronics                 | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 92        | 33.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 14.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 8.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 4.04%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.94%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.84%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.84%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.47%   |
| Intel Ethernet Connection I219-V                                  | 4         | 1.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.1%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.1%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.74%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.74%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.74%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.74%   |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.74%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.37%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 300       | 53.1%   |
| Ethernet | 263       | 46.55%  |
| Modem    | 2         | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 243       | 75.7%   |
| Ethernet | 78        | 24.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 246       | 80.13%  |
| 1     | 57        | 18.57%  |
| 0     | 3         | 0.98%   |
| 3     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 257       | 83.44%  |
| Yes  | 51        | 16.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 112       | 47.86%  |
| Qualcomm Atheros Communications | 29        | 12.39%  |
| Realtek Semiconductor           | 23        | 9.83%   |
| Broadcom                        | 20        | 8.55%   |
| Dell                            | 13        | 5.56%   |
| Lite-On Technology              | 9         | 3.85%   |
| IMC Networks                    | 9         | 3.85%   |
| Foxconn / Hon Hai               | 4         | 1.71%   |
| Cambridge Silicon Radio         | 4         | 1.71%   |
| Ralink                          | 3         | 1.28%   |
| ASUSTek Computer                | 3         | 1.28%   |
| Ralink Technology               | 2         | 0.85%   |
| Toshiba                         | 1         | 0.43%   |
| Foxconn International           | 1         | 0.43%   |
| Apple                           | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 58        | 24.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 7.69%   |
| Intel Bluetooth Device                              | 14        | 5.98%   |
| Realtek Bluetooth Radio                             | 12        | 5.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 3.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 3.85%   |
| Intel AX200 Bluetooth                               | 8         | 3.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 2.99%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 2.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 2.99%   |
| IMC Networks Bluetooth Device                       | 7         | 2.99%   |
| Dell DW375 Bluetooth Module                         | 7         | 2.99%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 1.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.71%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.71%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 1.71%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.28%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.28%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.28%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.85%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.85%   |
| Lite-On Bluetooth Device                            | 2         | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.85%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 2         | 0.85%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.85%   |
| Toshiba Bluetooth Radio                             | 1         | 0.43%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.43%   |
| Ralink CSR BS8510                                   | 1         | 0.43%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.43%   |
| IMC Networks BCM20702A0                             | 1         | 0.43%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.43%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.43%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 257       | 68.35%  |
| AMD                                            | 48        | 12.77%  |
| Nvidia                                         | 46        | 12.23%  |
| Realtek Semiconductor                          | 4         | 1.06%   |
| Lenovo                                         | 3         | 0.8%    |
| Silicon Integrated Systems [SiS]               | 2         | 0.53%   |
| Sony                                           | 1         | 0.27%   |
| Siemens Information and Communication Products | 1         | 0.27%   |
| Project DAC DS                                 | 1         | 0.27%   |
| Plantronics                                    | 1         | 0.27%   |
| No brand                                       | 1         | 0.27%   |
| Meizu                                          | 1         | 0.27%   |
| Logitech                                       | 1         | 0.27%   |
| Kingston Technology                            | 1         | 0.27%   |
| Hewlett-Packard                                | 1         | 0.27%   |
| GN Netcom                                      | 1         | 0.27%   |
| Generalplus Technology                         | 1         | 0.27%   |
| FiiO Electronics Technology                    | 1         | 0.27%   |
| Elite Silicon                                  | 1         | 0.27%   |
| Corsair                                        | 1         | 0.27%   |
| Conexant Systems                               | 1         | 0.27%   |
| C-Media Electronics                            | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 39        | 8.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 34        | 7.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 6.44%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 4.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 3.56%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 3.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 2.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.67%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.78%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.56%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.33%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.11%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.11%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.89%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 68        | 24.55%  |
| SK hynix                                         | 52        | 18.77%  |
| Micron Technology                                | 33        | 11.91%  |
| Kingston                                         | 24        | 8.66%   |
| Unknown                                          | 23        | 8.3%    |
| Crucial                                          | 16        | 5.78%   |
| Ramaxel Technology                               | 10        | 3.61%   |
| Nanya Technology                                 | 9         | 3.25%   |
| Elpida                                           | 8         | 2.89%   |
| A-DATA Technology                                | 7         | 2.53%   |
| Smart                                            | 6         | 2.17%   |
| Unknown (ABCD)                                   | 3         | 1.08%   |
| Teikon                                           | 2         | 0.72%   |
| Patriot                                          | 2         | 0.72%   |
| Netlist                                          | 2         | 0.72%   |
| Goodram                                          | 2         | 0.72%   |
| Corsair                                          | 2         | 0.72%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.36%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.36%   |
| Toshiba                                          | 1         | 0.36%   |
| Team                                             | 1         | 0.36%   |
| Qimonda                                          | 1         | 0.36%   |
| G.Skill                                          | 1         | 0.36%   |
| ASint Technology                                 | 1         | 0.36%   |
| Apacer                                           | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 2.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 2.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.71%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 1.71%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 4         | 1.37%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 4         | 1.37%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.02%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.02%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 1.02%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 1.02%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 1.02%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 1.02%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.68%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.68%   |
| Unknown RAM Module 2048MB SODIMM DRAM                            | 2         | 0.68%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.68%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 2         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 2         | 0.68%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.68%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 2         | 0.68%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.68%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 2         | 0.68%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 2         | 0.68%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s            | 2         | 0.68%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 2         | 0.68%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.68%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 2         | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 110       | 47.41%  |
| DDR4    | 75        | 32.33%  |
| DDR2    | 15        | 6.47%   |
| LPDDR3  | 11        | 4.74%   |
| SDRAM   | 8         | 3.45%   |
| LPDDR4  | 8         | 3.45%   |
| DRAM    | 2         | 0.86%   |
| DDR5    | 1         | 0.43%   |
| DDR     | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 210       | 91.3%   |
| Row Of Chips | 16        | 6.96%   |
| Chip         | 3         | 1.3%    |
| DIMM         | 1         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 93        | 36.33%  |
| 8192  | 78        | 30.47%  |
| 2048  | 44        | 17.19%  |
| 16384 | 24        | 9.38%   |
| 32768 | 9         | 3.52%   |
| 1024  | 7         | 2.73%   |
| 1536  | 1         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 76        | 29.92%  |
| 2667    | 42        | 16.54%  |
| 3200    | 26        | 10.24%  |
| 1334    | 24        | 9.45%   |
| 2133    | 15        | 5.91%   |
| 2400    | 12        | 4.72%   |
| 1333    | 12        | 4.72%   |
| Unknown | 9         | 3.54%   |
| 4199    | 6         | 2.36%   |
| 3266    | 6         | 2.36%   |
| 667     | 6         | 2.36%   |
| 1066    | 5         | 1.97%   |
| 800     | 4         | 1.57%   |
| 1067    | 3         | 1.18%   |
| 2048    | 2         | 0.79%   |
| 975     | 2         | 0.79%   |
| 4800    | 1         | 0.39%   |
| 4267    | 1         | 0.39%   |
| 1867    | 1         | 0.39%   |
| 533     | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| QinHeng CH340S                   | 1         | 33.33%  |
| Canon PIXMA MG2500 Series        | 1         | 33.33%  |
| Brother DCP-7055 scanner/printer | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Canon       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 33.33%  |
| Seiko Epson ES-D400 [GT-S80]                     | 1         | 33.33%  |
| Canon CanoScan LiDE 90                           | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 86        | 31.16%  |
| Microdia                               | 30        | 10.87%  |
| Sunplus Innovation Technology          | 18        | 6.52%   |
| Bison Electronics                      | 18        | 6.52%   |
| IMC Networks                           | 14        | 5.07%   |
| Realtek Semiconductor                  | 13        | 4.71%   |
| Quanta                                 | 11        | 3.99%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.99%   |
| Ricoh                                  | 9         | 3.26%   |
| Acer                                   | 9         | 3.26%   |
| Suyin                                  | 7         | 2.54%   |
| Syntek                                 | 6         | 2.17%   |
| Silicon Motion                         | 6         | 2.17%   |
| Lite-On Technology                     | 5         | 1.81%   |
| Luxvisions Innotech Limited            | 4         | 1.45%   |
| Logitech                               | 4         | 1.45%   |
| Apple                                  | 4         | 1.45%   |
| Samsung Electronics                    | 2         | 0.72%   |
| LG Electronics                         | 2         | 0.72%   |
| Importek                               | 2         | 0.72%   |
| Alcor Micro                            | 2         | 0.72%   |
| Z-Star Microelectronics                | 1         | 0.36%   |
| Y Media                                | 1         | 0.36%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.36%   |
| Ruision                                | 1         | 0.36%   |
| Primax Electronics                     | 1         | 0.36%   |
| Microsoft                              | 1         | 0.36%   |
| Lenovo                                 | 1         | 0.36%   |
| Google                                 | 1         | 0.36%   |
| Generalplus Technology                 | 1         | 0.36%   |
| DigiTech                               | 1         | 0.36%   |
| Cubeternet                             | 1         | 0.36%   |
| Aveo Technology                        | 1         | 0.36%   |
| Unknown                                | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 20        | 7.22%   |
| Microdia Integrated_Webcam_HD                       | 10        | 3.61%   |
| Sunplus Integrated_Webcam_HD                        | 8         | 2.89%   |
| Chicony USB2.0 VGA UVC WebCam                       | 7         | 2.53%   |
| Chicony HD WebCam                                   | 6         | 2.17%   |
| Bison Integrated Camera                             | 6         | 2.17%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 1.81%   |
| Acer BisonCam, NB Pro                               | 5         | 1.81%   |
| Ricoh HD Webcam                                     | 4         | 1.44%   |
| Quanta HD User Facing                               | 4         | 1.44%   |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 4         | 1.44%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 1.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 3         | 1.08%   |
| Realtek USB camera                                  | 3         | 1.08%   |
| Realtek Integrated_Webcam_HD                        | 3         | 1.08%   |
| Microdia Integrated Webcam                          | 3         | 1.08%   |
| Lite-On HP HD Camera                                | 3         | 1.08%   |
| Chicony Integrated IR Camera                        | 3         | 1.08%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 1.08%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.08%   |
| Chicony HP Webcam-101                               | 3         | 1.08%   |
| Chicony HP HD Webcam                                | 3         | 1.08%   |
| Chicony CNF9055 Toshiba Webcam                      | 3         | 1.08%   |
| Bison Lenovo Integrated Webcam                      | 3         | 1.08%   |
| Syntek Lenovo EasyCamera                            | 2         | 0.72%   |
| Syntek EasyCamera                                   | 2         | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.72%   |
| Sunplus Dell Integrated Webcam                      | 2         | 0.72%   |
| Silicon Motion WebCam SC-13HDL11939N                | 2         | 0.72%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.72%   |
| Ricoh Sony Visual Communication Camera              | 2         | 0.72%   |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 2         | 0.72%   |
| Realtek Lenovo EasyCamera                           | 2         | 0.72%   |
| Quanta VGA WebCam                                   | 2         | 0.72%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 2         | 0.72%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 0.72%   |
| Microdia Dell Integrated HD Webcam                  | 2         | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 50%     |
| Synaptics                  | 11        | 21.15%  |
| Shenzhen Goodix Technology | 4         | 7.69%   |
| Upek                       | 3         | 5.77%   |
| Elan Microelectronics      | 3         | 5.77%   |
| STMicroelectronics         | 1         | 1.92%   |
| Samsung Electronics        | 1         | 1.92%   |
| LighTuning Technology      | 1         | 1.92%   |
| Focal-systems.Corp         | 1         | 1.92%   |
| AuthenTec                  | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader              | 5         | 9.62%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 5         | 9.62%   |
| Validity Sensors VFS491                                  | 4         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 4         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 5.77%   |
| Validity Sensors Synaptics WBDI                          | 3         | 5.77%   |
| Shenzhen Goodix Fingerprint Reader                       | 3         | 5.77%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 2         | 3.85%   |
| Validity Sensors Fingerprint scanner                     | 2         | 3.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 3.85%   |
| Synaptics Fingerprint reader [HP G6]                     | 2         | 3.85%   |
| Elan ELAN:Fingerprint                                    | 2         | 3.85%   |
| Validity Sensors VFS471 Fingerprint Reader               | 1         | 1.92%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 1.92%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 1.92%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 1.92%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.92%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 1.92%   |
| Shenzhen Goodix FingerPrint                              | 1         | 1.92%   |
| Samsung Fingerprint Device                               | 1         | 1.92%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 1.92%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 1.92%   |
| Elan ELAN:ARM-M4                                         | 1         | 1.92%   |
| AuthenTec AES2810                                        | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 23        | 58.97%  |
| Alcor Micro           | 8         | 20.51%  |
| Upek                  | 2         | 5.13%   |
| O2 Micro              | 2         | 5.13%   |
| Lenovo                | 2         | 5.13%   |
| Gemalto (was Gemplus) | 1         | 2.56%   |
| Advanced Card Systems | 1         | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 25.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 20.51%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 20.51%  |
| Broadcom 5880                                                                | 3         | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.13%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.13%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.13%   |
| Broadcom 58200                                                               | 2         | 5.13%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.56%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 183       | 58.84%  |
| 1     | 102       | 32.8%   |
| 2     | 21        | 6.75%   |
| 3     | 3         | 0.96%   |
| 8     | 2         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 52        | 31.71%  |
| Chipcard                 | 37        | 22.56%  |
| Graphics card            | 34        | 20.73%  |
| Net/wireless             | 11        | 6.71%   |
| Storage                  | 8         | 4.88%   |
| Bluetooth                | 5         | 3.05%   |
| Camera                   | 4         | 2.44%   |
| Multimedia controller    | 3         | 1.83%   |
| Sound                    | 2         | 1.22%   |
| Flash memory             | 2         | 1.22%   |
| Communication controller | 2         | 1.22%   |
| Card reader              | 2         | 1.22%   |
| Network                  | 1         | 0.61%   |
| Firewire controller      | 1         | 0.61%   |

