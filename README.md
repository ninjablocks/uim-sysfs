uim-sysfs: Usermode Init Manager for TI Shared Transport
========================================================

The TI shared transport driver allows multiplexing of a shared UART transport for multiple chips on the WiLink family of devices. This userspace process maps across the TTY to the appropriate kernel service, most notably the Bluetooth HCI.