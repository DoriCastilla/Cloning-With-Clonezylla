# Cloning a Hard Disk with Clonezilla
## Task: 
Update the storage capacity of my laptop with a bigger hard disk.
## Components:
- OS: Windows 11 
- D1: NVMe 250GB
- D2: External HD 1TB
- D3: NVMe 1TB
## Webography and videography:
- Download: https://clonezilla.org/downloads/download.php?branch=alternative
- Install Rufus: https://rufus.ie/en/
- Disk to disk: https://clonezilla.org/show-live-doc-content.php?topic=clonezilla-live/doc/03_Disk_to_disk_clone https://www.youtube.com/watch?v=6hXKpnitzrw&ab_channel=TechIN
## Steps:
### Step 1: Prepare the USB flash drive
a. Download the amd64 (x86-64) version of Clonezilla Live ISO file. 

![Cloning1](https://github.com/user-attachments/assets/893ed4b9-b1b7-400d-b849-f8f5b7b45cdd)

b.	Download and install Rufus on your Windows computer, if you do not have it already. I did choose the non-portable.

![Cloning2](https://github.com/user-attachments/assets/94828655-9f48-4531-b503-6d735c12f57b)

c.	Install Rufus on your computer, following these instructions if you have not done it before.
d.	Turn off your laptop and connect the pen drive and the external disk to your computer.
### Step 2: 3.	Clone the disk with Clonezilla
a.	Turn on the PC and open the BIOS/UEFI (remember the key is not the same for every PC, but usually are Escape, Enter, F1, F2, F9 or F10) and boot the computer from the USB flash drive, were you have installed Rufus with the Clonezilla live ISO. Clonezilla will appear.

![Cloning3](https://github.com/user-attachments/assets/b6c4b6f5-ee0c-498c-a9e1-498b28e2f906)

b.	Follow [these instructions](https://clonezilla.org/show-live-doc-content.php?topic=clonezilla-live/doc/03_Disk_to_disk_clone) step by step. 
You have to be sure to identify which of the two detected hard disks is the source (the D1 inside your laptop) that will show up and which one is the destination of the cloning  (in my case, the external HD). 

### Step 2: Change the hard disk of the computer
a.	Remove the old SSD (D1: NVMe 250GB) from your laptop. If you don’t know it, look on its brand website or on a trustworthy, helpful website. Remember to turn off the power before opening it.
b.	Install the new one (D3: NVMe 1TB) and close the laptop.
c.	Connect again the USB flash drive with Rufus and power on the laptop. Don’t connect the cloned external hard disk yet, if the computer detects two local hard disks, there will be a conflict, and it can provoque a bad performance.
d.	When the laptop is booted, you can connect the external disk again.

### Step 3: Clone the new disk with Clonezilla 
a.	Repeat the previous step, booting the computer from Clonezilla in the USB flash drive. 
b.	Follow the same instructions, but this time, be very careful, because the disk source is the external one, and the destination will be the new one you set inside the laptop. 
c.	When the cloning is done, power off the laptop, unplug all peripherals, and start it normally. If all was good, it will start as it was before, but your capacity of storage is increased.

![225be5b42cd3b82c3f93c5c274a028df (2)](https://github.com/user-attachments/assets/f5251788-005f-474f-a36c-2708b63c4e3a)
