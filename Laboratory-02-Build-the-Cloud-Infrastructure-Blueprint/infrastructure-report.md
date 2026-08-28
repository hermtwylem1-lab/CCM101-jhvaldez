# Infrastructure Report

## Checkpoint 2 – Investigate the Cloud Server

### Overview

This report documents the investigation of the Linux cloud server provided through the KillerCoda Playground. Linux commands were used to identify the operating system, kernel version, CPU, memory, disk capacity, mounted file systems, hostname, and IP address.

## 1. Operating System

**Command used:**

```bash
cat /etc/os-release
```

**Finding:**

The cloud server is running **Ubuntu 24.04.4 LTS (Noble Numbat)**.

## 2. Kernel Version

**Command used:**

```bash
uname -r
```

**Finding:**

The kernel version is:

```text
6.8.0-138-generic
```

## 3. CPU Model

**Command used:**

```bash
lscpu | grep "Model name"
```

**Finding:**

The CPU model is:

**Intel Xeon E312xx (Sandy Bridge, IBRS update)**

## 4. Number of CPU Cores

**Command used:**

```bash
nproc
```

**Finding:**

The server has **1 CPU core**.

## 5. Total RAM

**Command used:**

```bash
free -h
```

**Finding:**

The server has approximately **1.9 GiB of total RAM**.

The memory information displayed was:

* Total: **1.9 GiB**
* Used: **421 MiB**
* Free: **852 MiB**
* Available: **1.4 GiB**
* Swap: **1.0 GiB**

## 6. Disk Capacity

**Command used:**

```bash
df -h
```

**Finding:**

The main disk partition `/dev/vda1` has a capacity of **19 GB**.

| File System  | Size | Used | Available | Use | Mounted On  |
| ------------ | ---: | ---: | --------: | --: | ----------- |
| `/dev/vda1`  |  19G | 5.4G |       13G | 30% | `/`         |
| `/dev/vda16` | 881M | 117M |      703M | 15% | `/boot`     |
| `/dev/vda15` | 105M | 6.2M |       99M |  6% | `/boot/efi` |

## 7. Mounted File Systems

**Command used:**

```bash
mount | column -t
```

**Finding:**

The Linux server has several mounted file systems, including:

* `/dev/vda1` mounted on `/`
* `/dev/vda16` mounted on `/boot`
* `/dev/vda15` mounted on `/boot/efi`
* `tmpfs` mounted on `/run`
* `tmpfs` mounted on `/dev/shm`
* `tmpfs` mounted on `/run/lock`
* `proc` mounted on `/proc`
* `sysfs` mounted on `/sys`
* `devtmpfs` mounted on `/dev`
* `cgroup2` mounted on `/sys/fs/cgroup`

These file systems help Linux manage the operating system, devices, processes, and temporary system data.

## 8. Hostname

**Command used:**

```bash
hostname
```

**Finding:**

The hostname of the server is:

```text
ubuntu
```

## 9. IP Address

**Command used:**

```bash
hostname -I
```

**Finding:**

The server has the following IP addresses:

```text
172.30.1.2
172.17.0.1
```

The IP addresses are used for communication within the cloud/server environment.

## Summary

The KillerCoda cloud server is running **Ubuntu 24.04.4 LTS** with kernel version **6.8.0-138-generic**. It uses an **Intel Xeon E312xx CPU with 1 CPU core**, approximately **1.9 GiB of RAM**, and a **19 GB main disk**. The hostname is `ubuntu`, and the server has the IP addresses `172.30.1.2` and `172.17.0.1`.

The investigation shows that the cloud server has the basic infrastructure resources needed to run Linux applications and services, including compute, memory, storage, and networking resources.

## Evidence

Screenshots of the Linux commands and their results are included in the `screenshots` folder as evidence of the completed investigation.

### Screenshot 1

The first screenshot shows the operating system, kernel version, CPU model, number of CPU cores, RAM, disk capacity, and initial mounted file system information.

### Screenshot 2

The second screenshot shows additional mounted file systems, the hostname, and the IP addresses of the cloud server.

