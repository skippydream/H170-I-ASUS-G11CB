# <a href="https://github.com/acidanthera/OpenCorePkg/releases">Opencore 0.7.9</a> EFI <img align="right" width="100" height="100" src="https://www.macos86.it/uploads/monthly_2020_08/OpenCore_avatar.png.c375ed1196132fefe5bd41fcefb31cbe.png">
\
\
\
<img src="https://user-images.githubusercontent.com/36988839/157909168-be6d4799-52fb-41f9-8819-1968d878861f.jpeg">
<img align="right" width="300" height="300" src="https://www.tomshw.it/data/thumbs/6/6/2/3/desktop-asus-pc-gaming-g11cb-it007t-2bf00cc2ffa62d150170d7441188a02dc.jpg">

  ## Specs
- Processor \
-- Processor manufacturer **Intel** \
-- Processor generation **6th gen Intel® Core™ i7** \
-- Processor model **i7-6700** \
-- Processor cores **4** \
-- Processor frequency **3.4 GHz** \
-- Processor socket **LGA 1151**

- Graphics \
-- On-board graphics card model **Intel® HD Graphics 530**

# Install guide

## BIOS setup
That is the hardest part.
## Create your own SSDT (.aml files) to insert in ACPI folder.
#### Download <a href="https://github.com/corpnewt/SSDTTime">SSDTTime</a> 

> Follow this guide
> https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-easy.html#running-ssdttime

## Setup your own SMBios
#### Download <a href="https://github.com/corpnewt/GenSMBIOS">GenSMBios</a> 
How to use it:

	- Run GenSMBios
	- "2. Select config.plist" -> Drag and drop config.plist from /EFI/OC/
	- "1. Install/Update MacSerial"
	- "3. Generate SMBIOS" -> Enter iMac17,1 1
## Finish up

#### Download <a href="https://github.com/corpnewt/ProperTree">ProperTree</a> 
Then:

	- Run ProperTree
	- Open (CTRL + O) /EFI/OC/config.plist
	- Snapshot (CTRL + R)
  - Save (CTRL + S)
