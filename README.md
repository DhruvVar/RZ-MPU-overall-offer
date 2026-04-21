# Renesas MPU Overall Offer

Welcome to the public GitHub entry point for **Renesas MPU software**.

This page provides a structured overview of the public software resources available for the Renesas **RZ MPU family**, including:

- **RZ Flexible Software Package (FSP)**
- **RZ FSP example and application projects**
- **RZ Linux solutions**
- **Linux BSP / VLP / SDK entry points**
- **Documentation**
- **Releases**
- **Boards and kits**
- **Support resources**

This page is intended to help developers quickly find the right starting point depending on their **RZ device family**, **software stack**, and **development workflow**.

---

## Quick Links

### Official RZ / MPU Entry Points
- [RZ 32 & 64-Bit MPUs](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus)
- [RZ Flexible Software Package (FSP)](https://www.renesas.com/en/software-tool/rz-flexible-software-package-fsp)
- [RZ FSP Documentation](https://renesas.github.io/rz-fsp/)
- [RZ MPU Software Package / Linux Solutions](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzg-series/verified-linux-package)

### Core Public GitHub Repositories
- [renesas/rz-fsp](https://github.com/renesas/rz-fsp)
- [renesas/rz-fsp-examples](https://github.com/renesas/rz-fsp-examples)
- [renesas-rz organization](https://github.com/renesas-rz)

### Releases
- [RZ FSP Releases](https://github.com/renesas/rz-fsp/releases)
- [RZ FSP Example Releases](https://github.com/renesas/rz-fsp-examples/releases)

### Linux / BSP / SDK Entry Points
- [Renesas RZ Linux Solutions](https://renesas-rz.github.io/rz_solution/)
- [Renesas RZ Linux Solutions – News & Updates](https://renesas-rz.github.io/rz_solution/history/)
- [Renesas RZ Linux Solutions – Knowledge Base](https://renesas-rz.github.io/rz_solution/knowledge_base/)

### Support and Tools
- [Renesas Support](https://www.renesas.com/support)
- https://www.renesas.com/e2studio

---

## Overview

The public Renesas MPU offer is represented by the **RZ family**. The official RZ family page states that the RZ family includes **RZ/V**, **RZ/A**, **RZ/G**, **RZ/T**, and **RZ/N** series and that the portfolio supports use cases such as **edge AI**, **vision AI**, **high-resolution HMI**, and **industrial automation**. [1](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus)

The public software offer for RZ MPUs is organized around **two major development paths**:

### 1. RZ Flexible Software Package (FSP)
The official RZ FSP page describes the **Renesas RZ Flexible Software Package (FSP)** as an enhanced software package for embedded designs using the Renesas RZ family of Arm microprocessors. It states that RZ FSP provides a way to build secure, connected devices using production-ready drivers, **FreeRTOS**, **Azure RTOS**, and other middleware stacks. om/en/software-tool/rz-flexible-software-package-fsp)[4](https://github.com/renesas/rz-fsp)

### 2. RZ Linux Solutions
The official RZ MPU Software Package / Linux solutions page states that for RZ MPUs, Renesas provides Linux software solutions including **Linux BSP Plus**, **Verified Linux Package (VLP)**, **Ubuntu/Debian**, **SDK**, and **AOSP** packages depending on the target device and use case. It also points users to the Renesas RZ Linux Solutions GitHub-based entry page. [3](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzg-series/verified-linux-package)[5](https://renesas-rz.github.io/rz_solution/)

---

## Start Here by Goal

## I want to start MPU development on RZ
Recommended flow:

1. Review the [RZ 32 & 64-Bit MPUs page](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus)
2. Decide whether your project is better aligned to **FSP / RTOS / bare metal** or **Linux-based** development
3. If using RTOS / FSP, go to [RZ Flexible Software Package (FSP)](https://www.renesas.com/en/software-tool/rz-flexible-software-package-fsp)
4. If using Linux, go to [Renesas RZ Linux Solutions](https://renesas-rz.github.io/rz_solution/)

---

## I want the main RTOS / FSP-based MPU software package
Start with:

- [RZ Flexible Software Package (FSP)](https://www.renesas.com/en/software-tool/rz-flexible-software-package-fsp)
- [renesas/rz-fsp](https://github.com/renesas/rz-fsp)
- [RZ FSP Documentation](https://renesas.github.io/rz-fsp/)
- [RZ FSP Releases](https://github.com/renesas/rz-fsp/releases)

The official RZ FSP page states that **RZ FSP v4.0.0** integrates the existing **RZ/A FSP**, **RZ/G FSP**, **RZ/N FSP**, **RZ/T FSP**, and **RZ/V FSP** into a **single package**. It also states that the legacy family-specific FSPs will continue to be supported until the end of **January 2027**, but that new features and bug fixes will only be provided in the successor RZ FSP. [2](https://www.renesas.com/en/software-tool/rz-flexible-software-package-fsp)[4](https://github.com/renesas/rz-fsp)[6](https://github.com/renesas/rza-fsp)[7](https://github.com/renesas/rzg-fsp)[8](https://github.com/renesas/rzv-fsp)

---

## I want examples and application projects for RZ MPUs
Start with:

- [renesas/rz-fsp-examples](https://github.com/renesas/rz-fsp-examples)
- [RZ FSP Example Releases](https://github.com/renesas/rz-fsp-examples/releases)

The public `rz-fsp-examples` repository states that it provides **Example Projects** and **Application Projects** for the Renesas RZ MPU family. It also states that example projects demonstrate the basic usage of FSP in user applications and that application projects illustrate solutions in various core technologies. nesas/rz-fsp-examples)

---

## I want Linux-based software for RZ MPUs
Start with:

- [Renesas RZ Linux Solutions](https://renesas-rz.github.io/rz_solution/)
- [RZ MPU Software Package](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzg-series/verified-linux-package)
- [renesas-rz organization](https://github.com/renesas-rz)

The RZ Linux Solutions page states that it covers **RZ/G**, **RZ/V**, **RZ/T**, and **RZ/N** and provides multiple Linux solution categories including **Linux BSP Plus**, **VLP**, **Ubuntu/Debian**, and **SDK**. [5](https://renesas-rz.github.io/rz_solution/)

The `renesas-rz` GitHub organization describes itself as the public GitHub presence for **Renesas RZ Software** and explicitly states that it provides links to repositories used for building BSP images, including **kernel**, **u-boot**, **Yocto**, and **graphics libraries**. [10](https://github.com/renesas-rz)

---

## I want Linux BSP / Yocto / Verified Linux Package details
Start with:

- [RZ MPU Software Package / Linux Solutions](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzg-series/verified-linux-package)
- [Renesas RZ Linux Solutions](https://renesas-rz.github.io/rz_solution/)
- [Renesas RZ Linux Solutions – News & Updates](https://renesas-rz.github.io/rz_solution/history/)

The official RZ MPU Software Package page explains the public Linux software choices for RZ MPUs:
- **Linux BSP Plus** for users who want to start development with the latest LTS kernel,
- **VLP** for users who require super long-term Linux kernel maintenance,
- and **SDK** for Linux beginners who want to start application software development quickly. [3](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzg-series/verified-linux-package)

---

## I want RZ family-specific context
Start with the relevant public family pages:

- [RZ/A MPU](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rza-mpu)
- [RZ/T Series MPU](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzt-series-mpu)
- [RZ/G3E](https://www.renesas.com/en/products/rz-g3e)
- [RZ/A3M](https://www.renesas.com/en/products/rz-a3m)
- [RZ/T2H](https://www.renesas.com/en/products/rz-t2h)

These public product pages describe the positioning of each device / family and help users choose the correct software path depending on whether they are targeting **HMI**, **AI/vision**, **real-time control**, or **Linux-capable general-purpose MPU** use cases. [11](https://www.renesas.com/en/products/rz-g3e)[12](https://www.renesas.com/en/products/rz-a3m)[13](https://www.renesas.com/en/products/rz-t2h)[14](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rza-mpu)[15](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzt-series-mpu)

---

## Repository Map

## Unified RZ FSP Path
- [renesas/rz-fsp](https://github.com/renesas/rz-fsp)
- [renesas/rz-fsp-examples](https://github.com/renesas/rz-fsp-examples)
- [RZ FSP Documentation](https://renesas.github.io/rz-fsp/)
- [RZ FSP Releases](https://github.com/renesas/rz-fsp/releases)

## RZ Linux / BSP / SDK Path
- [renesas-rz organization](https://github.com/renesas-rz)
- [Renesas RZ Linux Solutions](https://renesas-rz.github.io/rz_solution/)
- [Renesas RZ Linux Solutions – News & Updates](https://renesas-rz.github.io/rz_solution/history/)
- [Renesas RZ Linux Solutions – Knowledge Base](https://renesas-rz.github.io/rz_solution/knowledge_base/)

---

## Featured Public Paths

### Main MPU Product and Software Pages
- [RZ 32 & 64-Bit MPUs](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus)
- [RZ Flexible Software Package (FSP)](https://www.renesas.com/en/software-tool/rz-flexible-software-package-fsp)
- [RZ MPU Software Package / Linux Solutions](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzg-series/verified-linux-package)

### Main GitHub Repositories
- [renesas/rz-fsp](https://github.com/renesas/rz-fsp)
- [renesas/rz-fsp-examples](https://github.com/renesas/rz-fsp-examples)
- [renesas-rz organization](https://github.com/renesas-rz)

### Documentation and Releases
- [RZ FSP Documentation](https://renesas.github.io/rz-fsp/)
- [RZ FSP Releases](https://github.com/renesas/rz-fsp/releases)
- [RZ FSP Example Releases](https://github.com/renesas/rz-fsp-examples/releases)

### Linux Solutions
- [Renesas RZ Linux Solutions](https://renesas-rz.github.io/rz_solution/)
- [News & Updates](https://renesas-rz.github.io/rz_solution/history/)
- [Knowledge Base](https://renesas-rz.github.io/rz_solution/knowledge_base/)

---

## Legacy Family-Specific FSP Repositories

Before the unified **RZ FSP v4.0.0**, Renesas provided separate public FSP repositories for some RZ subfamilies. The unified RZ FSP page and repository both explicitly state that these legacy family-specific FSPs have been integrated into the single **RZ FSP** package. [2](https://www.renesas.com/en/software-tool/rz-flexible-software-package-fsp)[4](https://github.com/renesas/rz-fsp)

Public legacy repositories include:

- [renesas/rza-fsp](https://github.com/renesas/rza-fsp)
- [renesas/rzg-fsp](https://github.com/renesas/rzg-fsp)
- [renesas/rzv-fsp](https://github.com/renesas/rzv-fsp)

The public READMEs for these repos state that they are **deprecated** and recommend migration to **RZ FSP v4.0.0**. [6](https://github.com/renesas/rza-fsp)[7](https://github.com/renesas/rzg-fsp)[8](https://github.com/renesas/rzv-fsp)

---

## Related Official Resources

### Product and Software
- [RZ 32 & 64-Bit MPUs](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus)
- [RZ Flexible Software Package (FSP)](https://www.renesas.com/en/software-tool/rz-flexible-software-package-fsp)
- [RZ MPU Software Package / Linux Solutions](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzg-series/verified-linux-package)

### Documentation and Downloads
- [RZ FSP Documentation](https://renesas.github.io/rz-fsp/)
- [RZ FSP Releases](https://github.com/renesas/rz-fsp/releases)
- [RZ FSP Example Releases](https://github.com/renesas/rz-fsp-examples/releases)

### Linux Solutions
- [Renesas RZ Linux Solutions](https://renesas-rz.github.io/rz_solution/)
- [News & Updates](https://renesas-rz.github.io/rz_solution/history/)
- [Knowledge Base](https://renesas-rz.github.io/rz_solution/knowledge_base/)

### Support and Tools
- [Renesas Support](https://www.renesas.com/support)
- https://www.renesas.com/e2studio

---

## Notes

- This page is intended to improve discoverability across public **Renesas MPU** GitHub resources.
- In current public Renesas product positioning, the MPU portfolio is represented by the **RZ family**. [1](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus)
- The public software offer includes both a **unified RZ FSP path** and a **Linux solutions path**. [2](https://www.renesas.com/en/software-tool/rz-flexible-software-package-fsp)[3](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzg-series/verified-linux-package)
- The public `renesas-rz` organization is especially relevant for Linux-based RZ development because it links to repositories used for BSP images and Linux-related deliverables. [10](https://github.com/renesas-rz)

---

## Renesas GitHub Organizations

To browse public Renesas software related to MPUs, visit:

- [Renesas GitHub Organization](https://github.com/renesas)
- [Renesas RZ Software GitHub Organization](https://github.com/renesas-rz)

---
