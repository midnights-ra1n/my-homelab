# Infrastrucure

## Diagram of my complete local network

![network](/infrastructure/network.png)

Regarding the network hardware, I use a **Zyxel GS1200-8 Gigabit ethernet switch** and a **TP-Link AX1500 Wi-Fi 6 router**.

## Hosts

Here, I show you all my physical/virtual machines and containers that run into my homelab, her roles and why I use it.

### Physical machines

|                  | "drizzy" Proxmox                                                                       | PI-NET                                                              |
|------------------|----------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| Motherboard      | Gigabyte B550 DS3H                                                                     | Raspberry Pi 4 Model B                                              |
| CPU              | AMD Ryzen 5 5500                                                                       | Broadcom BCM2711, Quad core Cortex-A72 (ARM v8) 64-bit SoC @ 1.8GHz |
| RAM              | 32 GB @ 3200 MHz                                                                       | 2 GB LPDDR4-3200 SDRAM                                              |
| OS Disk          | SSD NVMe Kingston 500 GB (System and VMs)                                              | SanDisk 64 GB SD Card                                               |
| Additional disks | SSD NVMe Kingston 256 GB (CTs) 2x HDD Seagate IronWolf 4 TB HDD Seagate Barracuda 1 TB |                                                                     |

### Virtual Machines

To be completed

### Linux Containers (Proxmox)

To be completed