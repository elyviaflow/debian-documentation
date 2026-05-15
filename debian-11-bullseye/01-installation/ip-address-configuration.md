<div align="center">

<br/>

<p align="center">
  <img src="https://assets.celestiahub.web.id/img/elyvianame.png" width="500">
</p>


**Debian Server Administration — IP Address Configuration**

<br/>

[![Debian 11](https://img.shields.io/badge/Debian-11-A81D33?style=flat-square&logo=debian)](#)
[![License](https://img.shields.io/badge/License-MIT-4A90D9?style=flat-square)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-2ECC71?style=flat-square)]()
[![Documentation](https://img.shields.io/badge/Documentation-Stable-27AE60?style=flat-square)](#)
[![VirtualBox Ready](https://img.shields.io/badge/VirtualBox-Ready-183A61?style=flat-square&logo=virtualbox&logoColor=white)](#)
[![ElyviaFlow](https://img.shields.io/badge/ElyviaFlow-v1.0.0-6C5CE7?style=flat-square)](https://www.elyviaflow.com)
<br/>

*To configure the IP address, you need to enable Adapter 2 on the virtual machine that was previously installed.*

<br/>

</div>

---

## Step 01 - Poweroff the machine
Before doing this, make sure the virtual machine is powered off. If the machine is still running, shut it down first by entering the following command in the Debian console, then press **Enter**:
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.0.png" width="500">
</p>

**command:**
```bash
poweroff
```

---

## Step 02 - Settings a Network
After the virtual machine has been powered off, open the **Settings** menu of the installed machine.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.1.png" width="500">
</p>

Next, go to the **Network** section, then select **Adapter 2** and check Enable Network Adapter to activate it.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.2.png" width="500">
</p>

> In the **Attached To** option, select **Host-Only Adapter**. After that, make sure the **Name** option is set to **VirtualBox Host-Only Ethernet Adapter**.

> Finally, change the **Promiscuous Mode** setting to **Allow-All.**

Then click `OK`

---

## Step 03 - Start the Machine
After completing the network configuration, power on the virtual machine again and log in as the **root** user as usual.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.3.0.png" width="500">
</p>

Next, run the following command to check whether **Adapter 2** is active:

**command:**
```bash
ip a
```
then press `Enter.`
> If the configuration was successful, the interface **enp0s8** should appear in the network interface list.
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.3.1.png" width="500">
</p>

## Step 04 - Change network Interface
If the configuration is correct and the **enp0s8** interface appears, the next step is to edit the network interface configuration by running the following command, then press **Enter**:
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.4.0.png" width="500">
</p>

Follow the configuration shown in the image provided. For simplicity, we will use the **/24** subnet format. Otherwise, you would need to manually add a **netmask** entry in the configuration.

> To save the configuration in Nano, press **Ctrl + O**, then press **Enter**, and use **Ctrl + X** to exit the editor.

> Alternatively, you can simply press **Ctrl + X**, then press **Y**, and finally press **Enter** to save and exit.

**command:**
```bash
nano /etc/network/interfaces
```

After finishing the network interface configuration, restart the networking service to apply the new configuration by running the following command, then press **Enter**:
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.4.1.png" width="500">
</p>

**command:**
```bash
systemctl restart networking
```
After restarting the networking service, reboot the system to ensure all configurations are applied properly by running the following command, then press **Enter**:
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.4.2.png" width="500">
</p>

**command:**
```bash
reboot
```

---

## Step 05 - Check new configuration
After the reboot process is completed, log in again as the **root** user as usual.

Next, check whether the network configuration has been applied correctly by running the following command:

**command:**
```bash
ip a
```
<p align="center">
  <img src="https://assets.celestiahub.web.id/debian-11/ip-address/step-01.1.5.png" width="500">
</p>
If the configuration was successful, the network interface and IP address configuration should appear as shown in the image provided. The setup process is now complete.

---

<div align="center">

<br/>

Made with ❤️ by **ElyviaFlow**  
⭐ Star this repo if you find it helpful!
<br/>

</div>
