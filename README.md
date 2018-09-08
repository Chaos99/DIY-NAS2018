# DIY-NAS2018
Collection of guides and configurations to build a small home server / NAS 

##General description

I needed to replace my old QNAP NAS DS112 because it has become awefully slow and, well, full.
Instead of putting a bigger hard drive into the dated model, I decided to either buy or build a new NAS.
Based on my experiences with the old one, I decided on the following cryteria:

* x86-based, so I have a maximum of software to chose from
* Linux-based, so can follow available how-tos and documentation for manual software installations (even if targeted at desktop OSs)
* RAID for data protection (= at least 2 HDD slots)
* able to saturate my Gigabit-Ethernet home infrastructure
* maintain nearly full transfer speed even when handling additional load of wasteful protocols like smb and overhead of transport and disk encryption (= beefy CPU with HW accelerated crypto)
* be energy-efficent and stay below an avarage of 20W for 24/7 usage

This and my of course minimal budget lead me to either chose one of Synology DS218+ or QNAP TS-251+ 2-bay intel-based NASs or build my own along the lines of the one detailed in this article: [NAS Basic 2.0 on elefacts.de (german)](https://www.elefacts.de/test-59-nas_basic_2.0__effizientes_selbstbau_nas_mit_4x_sata_im_mini_itx_format) 
