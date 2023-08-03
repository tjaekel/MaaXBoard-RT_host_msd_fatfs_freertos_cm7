# MaaXBoard-RT_host_msd_fatfs_freertos_cm7
 MaaXBoard RT with USB memory stick

## USB Memory Stick on User USB
This project generates FW to test if an USB Memory Stick is connected
(on the User USB port, USB-A connector).

## ATTENTION
It displays on debug UART (LPUART1) what it is doing.
But it ERASES all content in USB stick!
(just two created directories remain on USB stick)

It confirms, that USB-A connector (used as Ehci1) works.

## Remarks
Debug UART is LPUART1 (not 6).
And for User USB (USB-A) it is Ehci1.

