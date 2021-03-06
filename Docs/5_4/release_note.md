# mbed OS 5.4 Releases

## mbed OS 5.4.3 release
We are pleased to announce the [mbed OS 5.4.3 release](https://github.com/ARMmbed/mbed-os/releases/tag/mbed-os-5.4.3) is now available.
This release includes new target support for nRf52840 and UBLOX_C030. There are also a number of bug fixes to improve the stability of 
the code and improvements to the tools.

### Known issues

The following list of known issues apply to this release:

None

Here is a full list of all changes and fixes in this release.

### Ports for upcoming targets

[3841](https://github.com/ARMmbed/mbed-os/pull/3841): Add nRf52840 target

[3992](https://github.com/ARMmbed/mbed-os/pull/3992): Introducing UBLOX_C030 platform

### Fixes and changes

[3951](https://github.com/ARMmbed/mbed-os/pull/3951): [NUCLEO_F303ZE] Correct ARDUINO pin

[4021](https://github.com/ARMmbed/mbed-os/pull/4021): Fix a macro to detect when RTOS was in use for the NRF52840_DK

[3979](https://github.com/ARMmbed/mbed-os/pull/3979): [KW24D] Add missing SPI defines and Arduino connector definitions

[3990](https://github.com/ARMmbed/mbed-os/pull/3990): [UBLOX_C027] Construct a ticker-based wait, rather than calling wait_ms(), in the C027 board startup code

[4000](https://github.com/ARMmbed/mbed-os/pull/4000): Add some type checking of configs

[4003](https://github.com/ARMmbed/mbed-os/pull/4003): Fix OBOE in async serial tx for NRF52 target, fix #4002

[4012](https://github.com/ARMmbed/mbed-os/pull/4012): [STM32] Correct I2C master error handling

[4020](https://github.com/ARMmbed/mbed-os/pull/4020): [NUCLEO_L011K4] Remove unsupported toolchain files

[4046](https://github.com/ARMmbed/mbed-os/pull/4046): [USBHOST] Fix device disconnection from hub during hub port reset

[4049](https://github.com/ARMmbed/mbed-os/pull/4049): [Tools] Turn off page alignment of sections

[4065](https://github.com/ARMmbed/mbed-os/pull/4065): [K66F] Move bss section to m_data_2 Section

[4014](https://github.com/ARMmbed/mbed-os/pull/4014): [Issue 3763] Reduce heap allocation in the GCC linker file

[4030](https://github.com/ARMmbed/mbed-os/pull/4030): [STM32L0] Reduce IAR heap and stack size for small targets

[4060](https://github.com/ARMmbed/mbed-os/pull/4060): [lpc1768] Remove invalid use of IP_SOF_BROADCAST_RECV option

[4070](https://github.com/ARMmbed/mbed-os/pull/4070): Elide adding regions to profile when empty

[4072](https://github.com/ARMmbed/mbed-os/pull/4072): Remove superfluous space

[4085](https://github.com/ARMmbed/mbed-os/pull/4085): Fix mbed-cli issue #468 and add LPCTargetCode.lpc_patch to POST_BINARY_WHITELIST

[4101](https://github.com/ARMmbed/mbed-os/pull/4101): Modify semihost_disabledebug() to support more interface FW revs

[4109](https://github.com/ARMmbed/mbed-os/pull/4109): [NUCLEO_L476RG] Make minor serial pin update

[3911](https://github.com/ARMmbed/mbed-os/pull/3911): [IAR exporter] Extend debugger settings template with modifiable options needed for Nordic targets

[3982](https://github.com/ARMmbed/mbed-os/pull/3982): [Ticker] Fix kl25z bug for handling events in the past

[4112](https://github.com/ARMmbed/mbed-os/pull/4112): Only link in LPC17xx ethernet ISR as needed

[4098](https://github.com/ARMmbed/mbed-os/pull/4098): Raise error when mbed_app.json is bad

### Using the release

You can fetch the mbed OS 5.4.3 release from the [mbed-os GitHub](https://github.com/ARMmbed/mbed-os) repository,
using the tag "mbed-os-5.4.3".
Please feel free to ask any questions or provide feedback on this release [on the forum](https://forums.mbed.com/), or to contact us at [support@mbed.org](mailto:support@mbed.org).

## mbed OS 5.4.2 release
We are pleased to announce the [mbed OS 5.4.2 release](https://github.com/ARMmbed/mbed-os/releases/tag/mbed-os-5.4.2) is now available.

This release includes support for the new target EFM32PG12, some driver updates for NUC472/M453, an update for STM32 to Cube version v1.6.0 and TLS hw acceleration (AES ECB) for NUCLEO_F439ZI. There are also bug fixes and improvements to the tools and mbed-os core.

### Known Issues

The following list of known issues applies to this release:
None

Here is a full list of all changes and fixes in this release.

### Ports for Upcoming Targets

[3934](https://github.com/ARMmbed/mbed-os/pull/3934): [Silicon Labs] Update to HAL and devices

### Fixes and Changes

[3691](https://github.com/ARMmbed/mbed-os/pull/3691): [TLS/hw acceleration] AES ECB for NUCLEO_F439ZI

[3827](https://github.com/ARMmbed/mbed-os/pull/3827): Correct return values for `I2C::write(int, const char*, int, bool)`

[3862](https://github.com/ARMmbed/mbed-os/pull/3862): Trap earlier when a Thread instance is reused

[3869](https://github.com/ARMmbed/mbed-os/pull/3869): [NCS36510] Default range changed from 0 to 950mV - ADC 

[3893](https://github.com/ARMmbed/mbed-os/pull/3893): [STM32F7] Update STM32 Cube version v1.6.0

[3895](https://github.com/ARMmbed/mbed-os/pull/3895): Use PATH env variable when GCC found in PATH

[3917](https://github.com/ARMmbed/mbed-os/pull/3917): Fix mistake register setting in serial_format()

[3931](https://github.com/ARMmbed/mbed-os/pull/3931): ARM Pack Manager improvements

[3927](https://github.com/ARMmbed/mbed-os/pull/3927): [DELTA_DFBM_NQ620] Add RC calibration setting and revise mbed_overrides.c

[3747](https://github.com/ARMmbed/mbed-os/pull/3747): bd: Add randomness to block device test and more debug friendly output

[3918](https://github.com/ARMmbed/mbed-os/pull/3918): [NUC472/M453] Support unique locally administered MAC address and other driver updates

[3920](https://github.com/ARMmbed/mbed-os/pull/3920): Adjust heap size to work for both tls-client and mbed-client

[3924](https://github.com/ARMmbed/mbed-os/pull/3924): Don't set the build_dir to anything on export

[3933](https://github.com/ARMmbed/mbed-os/pull/3933): #3593 Add template entry to fix exported project build error

[3953](https://github.com/ARMmbed/mbed-os/pull/3953): OS2 tests minor updates for STM32

[3969](https://github.com/ARMmbed/mbed-os/pull/3969): [NUCLEO_F302R8] Add missing PB_8/PB_9 CAN pins

[3975](https://github.com/ARMmbed/mbed-os/pull/3975): [NSAPI/lwIP] Free held netbuf on close

[3976](https://github.com/ARMmbed/mbed-os/pull/3976): mbed-coap error fixes merge to mbed OS

[3968](https://github.com/ARMmbed/mbed-os/pull/3968): [Greentea] Fix test code mbed-os-tests-mbed_hal-flash

[3949](https://github.com/ARMmbed/mbed-os/pull/3949): Fix C declaration of dir functions and types

[3922](https://github.com/ARMmbed/mbed-os/pull/3922): Fix/improve error parsing from API messages

[3939](https://github.com/ARMmbed/mbed-os/pull/3939): Update mbed trace


### Using the release

You can fetch the mbed OS 5.4.2 release from the [mbed-os GitHub](https://github.com/ARMmbed/mbed-os) repository,
using the tag "mbed-os-5.4.2".

Please feel free to ask any questions or provide feedback on this release [on the forum](https://forums.mbed.com/), or to contact us at [support@mbed.org](mailto:support@mbed.org).


## mbed OS 5.4.1 release

We are pleased to announce the [mbed OS 5.4.1 release](https://github.com/ARMmbed/mbed-os/releases/tag/mbed-os-5.4.1) is now available.

This release includes an update of mbed TLS to version 2.4.2, bringing essential and critical security patches, including a fix for CVE-2017-2784. For core mbed OS, there are a number of bug fixes to improve the stability of the code and improvements to the tools. 

### Fixes and Changes

[3716](https://github.com/ARMmbed/mbed-os/pull/3716): fix for issue #3715: correction in startup files for ARM and IAR, alignment of system_stm32f429xx.c files

[3741](https://github.com/ARMmbed/mbed-os/pull/3741): STM32 remove warning in hal_tick_32b.c file

[3780](https://github.com/ARMmbed/mbed-os/pull/3780): STM32L4 : Fix GPIO G port compatibility

[3831](https://github.com/ARMmbed/mbed-os/pull/3831): NCS36510: SPISLAVE enabled (Conflict resolved)

[3832](https://github.com/ARMmbed/mbed-os/pull/3832): lwip: Increase timeout on network tests with python projects

[3836](https://github.com/ARMmbed/mbed-os/pull/3836): Allow to redefine nRF's PSTORAGE_NUM_OF_PAGES outside of the mbed-os

[3840](https://github.com/ARMmbed/mbed-os/pull/3840): STM32: gpio SPEED - always set High Speed by default

[3844](https://github.com/ARMmbed/mbed-os/pull/3844): STM32 GPIO: Typo correction. Update comment (GPIO_IP_WITHOUT_BRR)

[3846](https://github.com/ARMmbed/mbed-os/pull/3846): STORAGE: removal of unsupported tests having ported to sd-driver repository

[3850](https://github.com/ARMmbed/mbed-os/pull/3850): STM32: change spi error to debug warning

[3860](https://github.com/ARMmbed/mbed-os/pull/3860): Define GPIO_IP_WITHOUT_BRR for xDot platform

[3875](https://github.com/ARMmbed/mbed-os/pull/3875): Add post-build hook white-list to exporters

[3880](https://github.com/ARMmbed/mbed-os/pull/3880): DISCO_F469NI: allow the use of CAN2 instance when CAN1 is not activated

[3897](https://github.com/ARMmbed/mbed-os/pull/3897): Ignore FuzzyWuzzy warnings

[3898](https://github.com/ARMmbed/mbed-os/pull/3898): Prevent underflow in heap size calculation

[3913](https://github.com/ARMmbed/mbed-os/pull/3913): [NRF51822] Fix reference to sleep in hal_patch override

[3795](https://github.com/ARMmbed/mbed-os/pull/3795): Fix pwm period calc

[3828](https://github.com/ARMmbed/mbed-os/pull/3828): STM32 CAN API: correct format and type

[3842](https://github.com/ARMmbed/mbed-os/pull/3842): TARGET_NRF: corrected spi_init() to properly handle re-initialization

[3843](https://github.com/ARMmbed/mbed-os/pull/3843): STM32L476xG: set APB2 clock to 80MHz (instead of 40MHz)

[3852](https://github.com/ARMmbed/mbed-os/pull/3852): Ignore build directory from scan resources

[3866](https://github.com/ARMmbed/mbed-os/pull/3866): bd: Fix missing const attributes on functions

[3879](https://github.com/ARMmbed/mbed-os/pull/3879): NUCLEO_F446ZE: Add missing AnalogIn pins on PF_3, PF_5 and PF_10.

[3877](https://github.com/ARMmbed/mbed-os/pull/3877): Update mbed TLS feature to mbedtls-2.4.2

[3902](https://github.com/ARMmbed/mbed-os/pull/3902): Fix heap and stack size for NUCLEO_F746ZG

[3864](https://github.com/ARMmbed/mbed-os/pull/3864): Fix mbed 2 builds

[3829](https://github.com/ARMmbed/mbed-os/pull/3829): can_write(): return error code when no tx mailboxes are available 


### Using the release

You can fetch the mbed OS 5.4.1 release from the [mbed-os GitHub](https://github.com/ARMmbed/mbed-os) repository, using the tag "mbed-os-5.4.1".

Please feel free to ask any questions or provide feedback on this release [on the forum](https://forums.mbed.com/), or to contact us at [support@mbed.org](mailto:support@mbed.org).

## mbed OS 5.4.0 release
 
This is the release note for ARM mbed OS 5.4.0. It summarizes the major enhancements in this version. 

You can find the mbed OS 5.4.0 release on [GitHub](https://github.com/ARMmbed/mbed-os/tree/mbed-os-5.4).

## About this release

mbed OS 5.4.0 incorporates functionality you can use to prepare for the upcoming mbed Cloud device management services. This includes bootloader and filesystem infrastructure and the certified Thread 1.1 stack for developers. In addition, this release contains many minor fixes and enhancements and brings target platform support up to 74 targets.

The following sections provide more details about this release.

## Core

mbed OS 5.4 adds flexible filesystem support to address the needs of IoT applications requiring storage within the end node. This release already includes a FAT filesystem implementation for removable media, such as SD cards, and future releases will add embedded flash filesystems and encryption.

The filesystem is integrated with the C standard libraries of the ARM, IAR and GCC compilers. It is available for use across all mbed Enabled platforms.

The release also includes early access to the mbed OS bootloader, so partners can add support for their targets' flash controllers. This forms part of the support for the upcoming mbed Cloud Update service, which allows managing device firmware update campaigns.

To read the documentation, see [file system](https://docs.mbed.com/docs/mbed-os-api-reference/en/latest/APIs/storage/filesystem/) and [bootloader](https://docs.mbed.com/docs/mbed-os-handbook/en/latest/advanced/bootloader/).

## Connectivity

mbed OS 5.4 uses the recently certified mbed Thread 1.1 stack to provide solutions for building end nodes and border routers.

A Linux-based Access Point reference that uses the Thread border router is also available.

The mbed OS [LoRaWAN APIs](https://github.com/ARMmbed/mbed-os/tree/feature-lorawan/features/FEATURE_LORAWAN) are available for partner feedback and integration.

## Security

The mbed crypto libraries in mbed TLS include all the internal partner APIs and documentation for enabling hardware entropy and symmetric and asymmetric cryptographic acceleration. Partners are working on implementations for their target platforms, and a partner workshop will support them. We expect support for the first set of targets in 5.5.

## Upcoming

The feature branch work on our [CMSIS5 and CMSIS-RTOS2](https://github.com/ARMmbed/mbed-os/tree/feature_cmsis5/rtos) upgrade is nearing completion, so testing will begin soon after the release of 5.4. We are aiming for inclusion on mainline for 5.5.

Throughout the year, we also plan a program of upgrading supported compilers to ensure the latest features and fixes from the different ARM compilers are available to developers; this will mean supporting ARM GCC Embedded 6, ARM Compiler 6 and IAR Embedded Workbench 8.

If you would like to be involved in helping test any of these upgrades to help minimize the effect on developers, please contact us.

## Targets

Thanks to our partners’ hard work, mbed OS 5.4 now supports 74 [target platforms](https://developer.mbed.org/platforms/).

We will continue to add new targets in our biweekly releases as partners introduce support.

## Fixes and changes

Please see the mbed-os GitHub repository referenced below for a full list of changes introduced in this release. You can find a list of known issues [here](https://github.com/ARMmbed/mbed_os_release_notes/blob/master/Docs/5_4/known_issues.md).

##Using the release

You can fetch the mbed OS 5.4.0 release from the [mbed-os GitHub](https://github.com/ARMmbed/mbed-os) repository using the tag “mbed-os-5.4.0”.

Please feel free to ask any questions or provide feedback about this release on the forum, or to contact us at [support@mbed.org](mailto:support@mbed.org).
