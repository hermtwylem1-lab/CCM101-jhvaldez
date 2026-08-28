# Mission Overview

This laboratory activity, **Build the Cloud Infrastructure Blueprint**, focuses on understanding the basic infrastructure that supports modern cloud computing. Using the KillerCoda Linux Playground, I investigated a cloud-based Linux environment and identified its compute, storage, networking, and operating system resources.

The activity also involved researching AWS, Microsoft Azure, and Google Cloud Platform, comparing their core infrastructure services, and designing a simple cloud infrastructure diagram. The completed work was organized and documented in a GitHub Cloud Computing Portfolio.

## Objectives

* Explain the major components of modern cloud infrastructure.
* Investigate hardware and software resources in a Linux environment.
* Identify compute, storage, networking, and operating system resources.
* Understand how cloud infrastructure components work together.
* Compare equivalent services offered by AWS, Microsoft Azure, and Google Cloud Platform.
* Create a simple cloud infrastructure diagram.
* Practice technical documentation using Markdown.
* Continue developing a structured GitHub Cloud Computing Portfolio.

## Cloud Infrastructure Components

### Compute Resources

Compute resources provide the processing power required to run applications and services. The KillerCoda environment uses an **Intel Xeon E312xx CPU with one CPU core** to process commands and run applications.

### Storage Resources

Storage resources provide space for operating system files, applications, and data. The KillerCoda environment has a **19 GB root disk** along with several mounted file systems, including `/boot` and `/boot/efi`.

### Networking Resources

Networking resources allow cloud systems and users to communicate with each other. The KillerCoda environment uses IP addresses such as **`172.30.1.2`** and **`172.17.0.1`** for network communication.

### Operating System

The operating system manages the server's hardware and software resources. The KillerCoda environment runs **Ubuntu 24.04.4 LTS** with the **6.8.0-138-generic** Linux kernel.

## Tools Used

* KillerCoda Playground
* Ubuntu Linux Terminal
* GitHub
* Git
* Markdown
* Draw.io
* Modern Web Browser

## Linux Commands Executed

The following commands were used to investigate the Linux cloud environment:

```bash
cat /etc/os-release
uname -r
lscpu
nproc
free -h
lsblk
df -h
mount | column -t
hostname
hostname -I
ip addr
```

## Skills Learned

Through this laboratory activity, I learned how to investigate a cloud-based Linux environment and identify its main infrastructure resources. I gained a better understanding of how compute, storage, networking, and operating systems work together to support cloud services.

I also learned how to compare equivalent services between AWS, Microsoft Azure, and Google Cloud Platform. Additionally, I improved my Linux command-line skills, Markdown documentation, cloud infrastructure planning, diagram design, and GitHub portfolio management.

## Challenges Encountered

One challenge I encountered was understanding the information provided by different Linux commands and connecting each result to the correct cloud infrastructure component. Another challenge was comparing services from AWS, Microsoft Azure, and Google Cloud because each provider uses different names for similar services.

Creating the cloud infrastructure diagram and organizing all the laboratory documentation also required careful planning. These challenges helped me improve my understanding of cloud infrastructure and become more comfortable with Linux, cloud services, technical documentation, and GitHub.

