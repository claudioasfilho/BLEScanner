# BLE Scanner

How it works:

This is a Simple BLE Scanner that prints out all the advertisers around it.

Tools and SDKs:

This was tested with:

Silicon Labs Bluetooth Stack 2.10.0.0

Gecko SDK Suite v2.4.0

GNU GCC Compiler: Apple LLVM version 9.0.0 (clang-900.0.39.2)
Target: x86_64-apple-darwin16.7.0
Thread model: posix


Development Board: Silicon Labs WSTK with BRD4159A (EFR32MG13P632F512GM48)

Usage:

In order to avoid modifying the Make File, please clone this to the following folder on the Bluetooth SDK structure.

/Applications/Simplicity Studio.app/Contents/Eclipse/developer/sdks/gecko_sdk_suite/v2.4/app/bluetooth/examples_ncp_host/

It should compile as is.

In order to execute it, please use the following command:

./exe/BLEScanner /dev/tty.(Serial Port) 115200

If you desire to use this with a different Host, you will need to modify the Makefile in order to accommodate the cross compiler.

Target Device Images:

Both the NCP and Stand Alone Bootloader images can be found on the File Structure.

Stand Alone Bootloader - StandAlonebootloader-bgapi-MG13-combined.s37
Bluetooth NCP Image - ncp-MG13P.s37
