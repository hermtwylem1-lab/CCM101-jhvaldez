# Cloud Infrastructure Components

## Checkpoint 3 – Identify Cloud Infrastructure Components

This activity identifies the main cloud infrastructure components found in the Linux environment provided by the KillerCoda Playground. The components include compute, storage, networking, and the operating system. Each component has an important role in providing a functional cloud environment.

## 1. Compute Resources

**Example:** CPU and CPU cores

**Purpose:**
Compute resources provide the processing power needed to run applications, commands, and services on the server.

**Importance in Cloud Computing:**
Compute resources are important because cloud applications need processing power to perform tasks. Cloud providers allow users to increase or decrease computing resources depending on their workload.

**Relation to the KillerCoda Linux Environment:**
The KillerCoda server provides a CPU and multiple CPU cores that allow Linux commands, applications, and other processes to run. The CPU information can be checked using commands such as `lscpu` and `nproc`.

## 2. Storage Resources

**Example:** Disk storage and mounted file systems

**Purpose:**
Storage resources are used to store the operating system, applications, configuration files, user files, and other data.

**Importance in Cloud Computing:**
Storage is important because cloud applications need a reliable place to save and access data. Cloud storage can also provide flexibility and scalability when more storage is required.

**Relation to the KillerCoda Linux Environment:**
The KillerCoda Linux server has disk storage that contains the operating system and other files. The available disk space can be checked using the `df -h` command, while mounted file systems can be viewed using the `mount` command.

## 3. Networking Resources

**Example:** IP address and network interface

**Purpose:**
Networking resources allow the Linux server to communicate with other computers, users, and cloud services.

**Importance in Cloud Computing:**
Networking is important because cloud servers need to communicate over networks to provide applications and services to users. It also allows different cloud resources to communicate with each other.

**Relation to the KillerCoda Linux Environment:**
The KillerCoda server has a network connection and an IP address that allows it to communicate through the cloud environment. The IP address can be checked using the `hostname -I` command.

## 4. Operating System

**Example:** Ubuntu 24.04.4 LTS

**Purpose:**
The operating system manages the server's hardware and software resources. It provides the environment where applications, commands, and services can run.

**Importance in Cloud Computing:**
The operating system is important because it allows cloud servers to run applications and manage resources. Linux is commonly used in cloud environments because it is reliable, flexible, and widely supported.

**Relation to the KillerCoda Linux Environment:**
The KillerCoda Playground provides an Ubuntu 24.04.4 LTS Linux environment. It allows users to practice Linux commands, inspect server resources, manage files, and perform cloud-related activities.
