# Welcome to Pervasive Displays Inc. repository on GitHub

![](https://github.com/PervasiveDisplays/.github/blob/main/profile/ProductLine.png)

**Pervasive Displays Inc.** designs, manufactures and markets e-paper displays (EPD) for applications requiring high resolution, good readability and low power consumption. Pervasive Displays focuses on commercial and industrial applications and is the world leading vendor with most experience in E Ink e-paper technology. 

## EPD hardware drivers

The following drivers provide a quick example with built-in images for test. **PDLS Common** is required to use these drivers.

* [Pervasive_Wide_Small](https://github.com/PervasiveDisplays/Pervasive_Wide_Small) for small-sized, monochrome/BW, wide-temperature 1.52", 1.54", 2.06", 2.13", 2.66", 2.71", 2.9", 3.70", 4.2" and 4.37" screens
* [Pervasive_Wide_Medium](https://github.com/PervasiveDisplays/Pervasive_Wide_Medium) for medium-sized, monochrome/BW, wide-temperature 5.81" and 7.4" screens
* [Pervasive_Wide_Large](https://github.com/PervasiveDisplays/Pervasive_Wide_Large) for large, monochrome, wide-temperature screens, with built-in images for test
* [Pervasive_BWRY_Small](https://github.com/PervasiveDisplays/Pervasive_BWRY_Small) for small-sized 1.54", 2.13", 2.66", 4.2" Spectra 4/BWRY/four color type screens
* [Pervasive_Touch_Small](https://github.com/PervasiveDisplays/Pervasive_Touch_Small) Hardware driver for small, monochrome, touch-enabled screens
  
For BWR/Spectra models, you may either choose from the [**EPD_Driver_GU drivers**](#legacy-libraries) or [**PDLS_EXT3_Basic_Global**](https://github.com/PervasiveDisplays/PDLS_EXT3_Basic_Global)

## Pervasive Displays Library Suite 

The **Pervasive Displays Library Suite** is specifically designed for the [Pervasive Displays](https://www.pervasivedisplays.com) screens and boards. It provides the text and graphic primitives for all the screens and supports capacitive touch on touch-screens.

* [PDLS_Common](https://github.com/PervasiveDisplays/PDLS_Common) provides a light hardware abstraction layer with C-like syntax for C and C++ SDKs. It is required by the drivers and the PDLS library.
* [PDLS_Basic](https://github.com/PervasiveDisplays/PDLS_Basic) for Pervasive Displays with wide temperature and embedded fast update ([film `K`](https://pdls.pervasivedisplays.com/userguide/Volume2/Chapter1/Section6.html#film)) and four color ([film `Q`](https://pdls.pervasivedisplays.com/userguide/Volume2/Chapter1/Section6.html#film)) with EXT3.1 extension kit
* ![](https://img.shields.io/badge/-NEW-orange) [PDLS_EXT4_Basic_Matter](https://github.com/PervasiveDisplays/PDLS_EXT4_Basic_Matter) for Pervasive Displays E-Paper Development Kit for Matter (EPDK-Matter) and monochrome screens with wide temperature and embedded fast update ([film `K`](https://pdls.pervasivedisplays.com/userguide/Volume2/Chapter1/Section6.html#film))

## Legacy Libraries
This section refers to legacy versions of our libraries and will no longer be updated. Please proceed to the section above for the latest.

The **EPD hardware drivers** provide a quick example with built-in images for test. These four are all for **global/normal update ONLY**.

* [EPD_Driver_GU_small](https://github.com/PervasiveDisplays/EPD_Driver_GU_small) for BW/BWR small-sized 1.54", 2.13", 2.66", 2.71", 2.9", 3.70", 4.2" and 4.37" screens 
* [EPD_Driver_GU_mid](https://github.com/PervasiveDisplays/EPD_Driver_GU_mid) for BW/BWR mid-sized 5.81" and 7.4" screens
* [EPD_Driver_GU_large](https://github.com/PervasiveDisplays/EPD_Driver_GU_large) for BW/BWR large-sized 9.7" and 12" screens
* [EPD_Driver_BWRY](https://github.com/PervasiveDisplays/EPD_Driver_BWRY) for Spectra 4/BWRY type screens

The **Pervasive Displays Library Suite** is specifically designed for the [Pervasive Displays](https://www.pervasivedisplays.com) screens and boards. It provides the text and graphic primitives for all the screens and supports capacitive touch on touch-screens.

* [PDLS_EXT3_Basic_Global](https://github.com/PervasiveDisplays/PDLS_EXT3_Basic_Global) for Pervasive Displays iTC monochrome and colour Spectra (black-white-red) screens ([films `C` and `J`](https://pdls.pervasivedisplays.com/userguide/Volume2/Chapter1/Section6.html#film)) with EXT3.1 extension kit
* [PDLS_EXT3_Basic_Fast](https://github.com/PervasiveDisplays/PDLS_EXT3_Basic_Fast) for Pervasive Displays monochrome screens with embedded fast update ([film `P`](https://pdls.pervasivedisplays.com/userguide/Volume2/Chapter1/Section6.html#film)) with EXT3.1 extension kit
* ![](https://img.shields.io/badge/-NEW-orange) [PDLS_EXT4_Basic_Matter](https://github.com/PervasiveDisplays/PDLS_EXT4_Basic_Matter) for Pervasive Displays E-Paper Development Kit for Matter (EPDK-Matter) and monochrome screens with wide temperature and embedded fast update ([film `K`](https://pdls.pervasivedisplays.com/userguide/Volume2/Chapter1/Section6.html#film))

## Documentation

* [Documentation](https://github.com/PervasiveDisplays/PDLS_EXT3_Basic_Documentation)
* [Wiki](https://docs.pervasivedisplays.com/)

## Configuration

**Software**

* Arduino SDK and IDE
* SPI library
* I²C / Wire library for touch

**Hardware**

+ iTC [monochrome](https://www.pervasivedisplays.com/products/?_sft_product_colour=black-white) and [colour Spectra (black-white-red)](https://www.pervasivedisplays.com/products/?_sft_product_colour=black-white-red) screens with [EPD Extension Kit Gen 3 (EXT3 or EXT3-1)](https://www.pervasivedisplays.com/product/epd-extension-kit-gen-3-EXT3/) board
* iTC [monochrome touch-screens](https://www.pervasivedisplays.com/products/?_sft_etc_itc=tp) with [Touch Expansion Board for EXT3 (EXT3-Touch)](https://www.pervasivedisplays.com/product/touch-expansion-board-ext3-touch/) and [EPD Extension Kit Gen 3 (EXT3 or EXT3-1)](https://www.pervasivedisplays.com/product/epd-extension-kit-gen-3-EXT3/) boards
* iTC [colour Spectra 4 (black-white-red-yellow)](https://www.pervasivedisplays.com/products/?_sft_product_colour=black-white-red-yellow) screens
* [EPD Pico Kit (EPDK)](https://www.pervasivedisplays.com/product/epd-pico-kit-epdk/), including a Raspberry Pi Pico RP2040, an EXT3-1 extension board and a 2.66" monochrome panel
* ![](https://img.shields.io/badge/-NEW-orange) [Pervasive Displays E-Paper Development Kit for Matter (EPDK-Matter)](https://www.pervasivedisplays.com/product/epdk-matter/)
