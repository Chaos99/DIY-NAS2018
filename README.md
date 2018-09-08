# DIY-NAS2018
Collection of guides and configurations to build a small home server / NAS 

## General description

I needed to replace my old QNAP NAS DS112 because it has become awefully slow and, well, full.
Instead of putting a bigger hard drive into the dated model, I decided to either buy or build a new NAS.
Based on my experiences with the old one, I decided on the following cryteria:

### Criteria
* x86-based, so I have a maximum of software to chose from
* Linux-based, so can follow available how-tos and documentation for manual software installations (even if targeted at desktop OSs)
* RAID for data protection (= at least 2 HDD slots)
* able to saturate my Gigabit-Ethernet home infrastructure
* maintain nearly full transfer speed even when handling additional load of wasteful protocols like smb and overhead of transport and disk encryption (= beefy CPU with HW accelerated crypto)
* be energy-efficent and stay below an avarage of 20W for 24/7 usage

This and my of course minimal budget lead me to either chose one of Synology DS218+ or QNAP TS-251+ 2-bay intel-based NASs or build my own along the lines of the one detailed in this article: [NAS Basic 2.0 on elefacts.de (german)](https://www.elefacts.de/test-59-nas_basic_2.0__effizientes_selbstbau_nas_mit_4x_sata_im_mini_itx_format) 

### Comparision
Comparing the solutions brought me to the insights that:
* Although comparable in performance, the Synology is based on the much more recent hardware and would be my choice between the two commercial ones
* If I replicate the hardware of the synology, I could only barely save 100EUR in price, but have a bulkier form faktor and still no out-of-the-box software solution
* If I keep the same price point, I can achieve about 4-5x more performance with a more recent chipset in a diy build (still with added sw effort of course)

### Hardware
So I ordered the following parts
* from mindfactory.de
* * Asrock J5005-ITX J5005 Gemini Lake SOD/U3/4S3 M-ITX retail
* * 2x 4GB Crucial CT4G4SFS824A DDR4-2400 SO-DIMM CL17
* * 2x 4TB WD Red WD40EFRX 
* from Amazon
* * Cooler Master Elite 130 Mini-ITX PC-Case 
* * PicoPSU-90 12V DC-DC ATX/mini-ITX power adapter
* * Salcar 72W power brick (12V 6A)
* * 1-to-4 SATA Y-power cable
* I still had lying around
* * 120GB Kingston SSD
* * 1 Sata cable

Including the original prices of the things I had around and including shipping, I paid 5% more than the cheapest offer for a Synology DS218+. (Because I made a last-minute upgrade on the chipsets. Could have gone for a J4105 to keep within the budget).
For this I got 2x the single, 3x the multi thread performance, added 6GB more RAM and got 119.5GB more space on the FLASH system partition.
