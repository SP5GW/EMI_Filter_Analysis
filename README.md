# EMI Filter Analysis 

<p align="center">
<img src="./img/internals_complete.jpg" width="600" height="500"/>
</p>

## Introduction

I have started this project as part of efforts to reduce noise floor observed on VLF bands when experimenting with my miniwhip antenna [2].
I have to admit that results are mixed. I do not see major improvements from using EMC Filter on VLF band, but I can definitely appreciate/hear the  benefit of using noise free ground when using my cristal radio. It shall be noted that presented device is based on commercially available EMC filter made by polish company Filtercon (model: FB1M 5A/250V) [3]. Design has been enhanced by adding the option to replace power line ground with "noise free ground" in line with proposal made by Nico PA0NHC [1].

THIS PROJECT INVOLVES MODIFICATIONS TO THE GROUNDING AND RECONNECTION OF 220V POWERLINE CABLING. WORKING WITH HIGH-VOLTAGE ELECTRICAL SYSTEMS CAN BE HAZARDOUS AND REQUIRES EXPERTISE. ENSURE YOU HAVE THE NECESSARY KNOWLEDGE AND EXPERIENCE BEFORE PROCEEDING. ANY ACTIONS YOU TAKE ARE AT YOUR OWN RISK. THE AUTHOR ASSUMES NO RESPONSIBILITY FOR DAMAGES, INJURIES, OR CONSEQUENCES RESULTING FROM THE USE OF THIS INFORMATION. ALWAYS PRIORITIZE SAFETY AND CONSULT A QUALIFIED PROFESSIONAL IF IN DOUBT.

A noise-free ground must comply with all applicable safety regulations. Specifically, its resistance must not exceed the limits imposed by local standards. For example, in Poland, the resistance should be less than 7 ohms.

The main lessons learneded from this project are:

1) Before installing an EMC filter in your setup, try powering your radio from a battery. Compare the interference levels when the radio is battery-powered versus when it is connected to the AC powerline. If the interference levels remain unchanged, it is likely that the noise originates from another source.

2) Installation of the EMC filter in reverse configuration suggested in [1] did not lead to any improved interference surpression in my case - see measurements below. 

## Device Schematics


## Measurement results


## EMC Filter design

<p align="center">
<img src="./img/internals_interim.jpg" width="400" height="400"/>
<img src="./img/internals_complete.jpg" width="400" height="400"/>
<img src="./img/final_product.jpg" width="500" height="500"/>
</p>

## References

[1] How to get any Miniwhip optimally working. Yes, it costs effort ! - YouTube video - Nico Veth, PA0NHC

[2] Miniwhip project, https://github.com/SP5GW/MiniWhip_Antenna - Andrzej Mazur, SP5GW

[3] Filtercon EMC Filter application note, https://filtercon.com.pl/sieciowe-filtry-przeciwzakloceniowe-serii-fb1s-i-fb1m-z-elementem-przeciwprzepieciowym/
