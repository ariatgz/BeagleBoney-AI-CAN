# BeagleBoneY AI CAN1 (CSI0) Device Tree Overlay

Enable the **CAN1 (Controller Area Network)** interface on the BeagleBoneY AI using **Device Tree Source (DTS)** and **Device Tree Overlay (DTBO)** files.

This project configures CAN1 to be routed through the **CSI0 port**, allowing connection to external CAN hardware via a ribbon cable and compatible CAN transceiver.

---

## Overview

The BeagleBone AI does not expose CAN1 on standard headers by default. This repository provides the necessary device tree configuration to:

- Enable the **CAN1 peripheral**
- Configure **pin multiplexing (pinmux)**
- Route CAN signals through the **CSI0 interface**
- Use Linux **SocketCAN** for CAN communication
