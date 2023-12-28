![Untitled-2 copy](https://github.com/MrrZed0/HP_EliteDesk_800_G3_Hackintosh/assets/154046655/c5b0bd10-b4c1-43ff-a76f-78f6a73b26a3)

# HP_EliteDesk_800_G3_Hackintosh

## Hardware:

**Brand:** HP

**Model:** EliteDesk 800 G3 65W

**OS:** macOS Monterey 12.7.2

**CPU:** Intel i5-7500 3.40GHz

**RAM:** 12GB DDR4 2400MHz

**HDD#1:** 500GB Solid State Drive SATA

**HDD#2:** M.2 NVMe Slot Empty

**Graphics:** Intel HD Graphics 630 1536MB

**LAN:** Intel NIC

**Bluetooth:** Intel Bluetooth

## BIOS Settings:

## **Advanced → Boot Options**

Disable Fast Boot

Enable USB Storage Boot

UEFI Boot order, place your bootable macOS installation USB on the first row otherwise you will need to choose it when system restarts by pressing F10 → your USB.

Other settings remain default

## **Advanced → Secure Boot Configuration**

Select Legacy Support Disable and Secure Boot Disable

Other settings remain default

## **Advanced → System Options**

Enable Virtualization Technology (VTx)

Disable Virtualization Technology for Directed I/O (VTd)

Enable M.2 SSD if you're using a NVME SSD

Check M.2 WLAN/BT (Uncheck it if have interruption issues)

Check Allow PCIe/PCI SERR# Interrupt (Uncheck it if have interruption issues)

Other settings remain default

## **Advanced → Built-in Device Options**

Disable Wake on LAN

Set Video memory size to 64MB or larger

Disable LAN/WLAN Auto Switching

Disable Wake on Wake on USB
Other settings remain default
