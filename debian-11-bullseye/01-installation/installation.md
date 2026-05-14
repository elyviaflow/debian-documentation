<div align="center">

<br/>

<p align="center">
  <img src="https://assets.celestiahub.web.id/img/elyvianame.png" width="500">
</p>


**Debian Server Administration — Installation**

<br/>

[![Debian 11](https://img.shields.io/badge/Debian-11-A81D33?style=flat-square&logo=debian)](#)
[![License](https://img.shields.io/badge/License-MIT-4A90D9?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-2ECC71?style=flat-square)]()
[![Documentation](https://img.shields.io/badge/Documentation-Stable-27AE60?style=flat-square)](#)
[![VirtualBox Ready](https://img.shields.io/badge/VirtualBox-Ready-183A61?style=flat-square&logo=virtualbox&logoColor=white)](#)
[![ElyviaFlow](https://img.shields.io/badge/ElyviaFlow-v1.0.0-6C5CE7?style=flat-square)](https://www.elyviaflow.com)
<br/>

*Step-by-step Debian 11 installation guide for VirtualBox environments.*
*Learn how to set up and deploy a Debian server from scratch.*

<br/>

</div>

---

## Step 01 - Create Virtual Machine
Create a new virtual machine, then rename it according to your preference. After that, select the downloaded Debian 11 ISO file and click **Finish.**
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-01.png" width="500">
</p>

---

## Step 02 - Start the Virtual Machine
After that, locate the virtual machine you created in the machine list, then click **Start** to boot it. Wait until the Debian installation menu appears.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-02.png" width="500">
</p>

---

## Step 03 - Select Install
Once the installation menu appears, select **Install** (not **Graphical Install**) to continue the installation process,
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-03.png" width="500">
</p>

then press **Enter.**

---

## Step 04 - Select a Language
Next, select the language option. Leave it as the default setting, <br/>
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-04.png" width="500">
</p>

```bash
English                         -   English
```
then press `Enter.`

---

## Step 05 - Select your location
Next, select your location based on the region where you are currently installing Debian. <br/><br/>
For example, since our location is in Indonesia, choose **Other** first. After the region menu appears, select **Asia** because Indonesia is part of the Asian region. Once the list of Asian countries appears, select **Indonesia**, then press Enter.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-05.png" width="500">
</p>

```bash
Other   ->  Asia    ->  Indonesian
```
then press `Enter.`

---

## Step 06 - Configure locales
Next, in the locale configuration menu, leave the default option as:<br/>
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-06.png" width="500">
</p>

```bash
United States                       -   en_US.UTF-8
```
then press `Enter.`

---

## Step 07 - Configure the Keyboard
Next, in the keyboard configuration menu, select the keyboard layout you are using. The most common global keyboard layout is American English.<br/>
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-07.png" width="500">
</p>

```bash
American English
```
After selecting it, press `Enter.`

---

## Step 08 - Initial Setup
Next, in the **Configure the Network** menu, you will be asked to enter a hostname for your server.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-08.1.png" width="500">
</p>

Example : `elyviaflow`<br/>
Then press **Enter.**

##

After entering the hostname, you will be asked to enter a domain name or DNS name.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-08.2.png" width="500">
</p>

Example : `elyviaflow.org`<br/>
Then press **Enter.**

##

Next, in the **Set Up Users and Passwords** menu, you will be asked to create a password for the root user, which will be used to log in to Debian.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-08.3.0.png" width="500">
</p>

Example : `12345`<br/>
Then press **Enter.**

##

After entering the root password, you will be asked to confirm it by entering the same password again.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-08.3.1.png" width="500">
</p>

Example : `12345`<br/>
Then press **Enter.**

##

After that, you will be asked to create a second user account by entering the user's full name. This account will also be used to log in to Debian.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-08.4.0.png" width="500">
</p>

Example : `elyvia`<br/>
Then press **Enter.**

##

Next, enter the username for the second user account.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-08.4.1.png" width="500">
</p>

Example : `elyvia`<br/>
Then press **Enter.**

##

After that, create a password for the second user account.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-08.4.2.png" width="500">
</p>

Example : `123`<br/>
Then press **Enter.**

##

Finally, confirm the password for the second user account by entering the same password again,
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-08.4.3.png" width="500">
</p>

Example : `123`<br/>
then press **Enter.**

---

## Step 09 - Configure the Clock
Next, in the **Configure the Clock** menu, select the time zone that matches your region.<br/>
> For example, since we are located in **Java**, select **Western**,
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-09.png" width="500">
</p>

```bash
Westren (Sumatra, Jakarta, Java, West and Central Kalimantan)
```
After selecting it, press `Enter.`

---

## Step 10 - Partision Disk
Next, you will enter the Partition Disks menu to configure the storage layout for Debian.<br/><br/>
First, select **Guided - use entire disk** to let Debian automatically create the required partitions,
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-10.1.0.png" width="500">
</p>

**Select :**
```bash
Guided  -  use entire disk
```
Then press **Enter.**

##

After that, choose the disk that will be used for the installation. Usually, only one virtual disk will appear in VirtualBox. Select the available disk,
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-10.1.1.png" width="500">
</p>

**Select :**
```bash
SCSI2 (0,0,0) (sda)   -   53.7 GB ATA VBOX HARDISK
```
Then press **Enter.**

##

Next, choose the partitioning scheme. For beginners, it is recommended to select **All files in one partition (recommended for new users)**,
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-10.1.2.png" width="500">
</p>

**Select :**
```bash
All files in one partition (recommended for new users)
```
Then press **Enter.**

##

After the partition layout preview appears, select **Finish partitioning and write changes to disk**, 
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-10.1.3.png" width="500">
</p>

**Select :**
```bash
Finish partitioning and write changes to disk
```
Then press **Enter.**

##

A confirmation message will appear asking whether you want to save the changes to the disk. Select **Yes**,
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/step-10.1.4.png" width="500">
</p>

**Select :**
```bash
Yes
```
Then press **Enter.** to begin the partitioning process.

---

<div align="center">

<br/>

Made with ❤️ by **ElyviaFlow**  
⭐ Star this repo if you find it helpful!
<br/>

</div>
