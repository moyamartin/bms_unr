<div align='center'>
<img src='assets/FCEIA-logo.png' width='200' align='left'>
<img src='assets/LOGO-UNR-NEGRO.png' width='100' align='right'>
</div>

# Battery Management System for Electrical Vehicles

This repo contains the final project of @lusho2206, @fededc88 and @moymartin
needed to finish the Bachelor degree in Electrical Engineering from the [Faculty
of Exact Sciences and Land Surveying](https://www.fceia.unr.edu.ar/) which
belongs to the [National University of Rosario](https://unr.edu.ar/)

## Introduction

Electrical Vehicles, based on Lithium Ion battery packs, are considered one of 
the most important technological breakthrough of the last years mainly due to 
their low emissions to the environment and the lack of dependency with fosil fuels.

Nevertheless, the energy source from these kind of vehicles are quite sensitive
and they need a control unit to operate properly. This control unit is known as
a Battery Management System. These kind of devices are in charge of monitoring
and protecting the battery packs implementing the following functionalities:

* Protect the battery pack in order to work in the safety operation area (SOA)
  taking into account the voltage, current and temperature of the pack
* Balance the individual cells of the battery pack.
* Estimate the state of charge (SoC) of the battery pack.
* Estimate the state of health (SoH) of the battery pack.
* Publish this information to a on-board computer of the vehicle

## Description

Taking into account the latter functionalities, the goal of this project is to
develop a BMS able to:

* Estimate the SoC
* Equalize the unbalanced cells
* Protect the battery pack
* Report the status of the battery through RS232 and CAN protocols.

This can be summarized in the following block diagram:

[BMS schematic](/assets/bms_sch.png)
