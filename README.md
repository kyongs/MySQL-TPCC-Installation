

## MySQL / TPC-C Installation
In this article, you will learn how to run the TPC-C benchmark on MySQL 5.7. Follow the guide below.

> **NOTE**: This guide is based on **Ubuntu 18.04**. If you are using a different environment, you may encounter some unexpected errors. You will need to resolve any errors that occur in a different environment yourself if you are not using Ubuntu version 18.04.

> **NOTE**: The easiest way to install Ubuntu 18.04 on your laptop is to use a virtual machine.

## Instructions
### Mount devices (Optional)
- If you have more than one storage device on your PC, read and try [this guide](1_mount_devices.md) to separate data and log devices.

### 1. Install MySQL 5.7
- Follow the [installation guide](2_mysql57-installation.md) to install MySQL 5.7 source code version.

### 2. Install mysql-tpcc
- Follow the [installation guide](3_tpcc-mysql-installation.md) to install tpcc-mysql.
- Refer to the [performance analysis guide](4_performance_analysis.md) to gather performance metrics while running the TPC-C benchmark on MySQL 5.7.

