# SBC-7109S-Linux4.4.12-Qt4.8.5-BSP

## BSP development package documentation

* This document if for the [Aplex](http://www.aplextec.com/cn/home.php) SBC-7109S motherboard;
* Kernel version: Linux v4.4.12;
* GUI library version: Qt4.8.5;

## BSP development package document brief

When you get the motherboard and the BSP package provided by our sales, please refer to [《SBC-7109S-Linux4.4.12-Qt4.8.5 Quick Start Guide》](Quick_Start_Guide.md) and you will get the following information:
* The main interface on the motherboard;
* How to use the compilation tool and burn the software image we have compiled;

If you would like to further develop on our motherboard, please refer to [《SBC-7109S-Linux4.4.12-Qt4.8.5 User's Guide》](User's_Guide.md), from which you will get the following information:
* How to build a development environment;
* How to compile U-Boot, Linux Kernel source code;
* How to use we provided example-applications;
* How to use we have created for development environment of the VMware virtual machine, include U-Boot, Linux Kernel, Qt library source code, can be used for secondary development.

For the configuration and modification of the Qt desktop system, please refer to [《SBC-7109S-Linux4.4.12-Qt4.8.5 Desktop Display System》](Desktop_Display_System.md), you will get the following information:
* Desktop system configuration file location
* Reference for how the desktop system configuration and configuration

## BSP development package document directory description

About how to get the BSP package, please contact our service staff.

```
    .
    ├── board-support                   // Board support software package
    │   ├── prebuilt-images             // Compiled image and dtb.
    │   │   ├── u-boot.img              // Compiled u-boot.img
    │   │   ├── zImage                  // Compiled zImage
    |   |   ├── MLO                     // Compiled MLO
    |   |   ├── uEnv.txt                // SD card configure
    |   |   ├── uEnv_emmc.txt           // Emmc configure
    |   │   └── am335x-sbc7109.dtb      // Compiled device tree
    │   │        
    │   ├── linux-kernel-source-code    // Linux Kernel source
    │   ├── u-boot-source-code          // U-boot source
    │   ├── qt-source-code              // Qt GUI library source
    │   └── VMware-Workstation          // Pre-setupped VMWARE virtual machine
    ├── docs                            // User guide and development document
    │   └── README.txt                  // Specified for GitHub BSP documents
    ├── example-applications            // Application examples
    │   └── board-demo-examples         // IO Demo for mainboard
    ├── filesystem                      // Root file system
    │   └── rootfs.tar                  // Comparessed root file system
    └── linux-devkit                    // Development tools
        ├── compiler                    // Compiler
        └── tools                       // Tools

```

## BSP development package usage and reference documents list

* [SBC-7109S-Linux4.4.12-Qt4.8.5 Quick Start Guide.md](Quick_Start_Guide.md)；
* [SBC-7109S-Linux4.4.12-Qt4.8.5 User's Guide](User's_Guide.md)；
* [SBC-7109S-Linux4.4.12-Qt4.8.5 Desktop Display System](Desktop_Display_System.md)；

##  copyright notice

All of the above interpretation is belong to [aplex](http://www.aplextec.com/cn/home.php)
