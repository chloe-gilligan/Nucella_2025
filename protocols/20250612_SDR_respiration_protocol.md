---
layout: post
title: SDR Respirometry Protocol
date: '2025-09-11'
categories: Protocols
tags: respirometry, Nucella, physiology
projects: Nucella
---

# SDR Respirometry Protocol

Original: 20201214 from Putnam lab
Revised by Chloé Gilligan for Nucella respiration

**Contents**
- [**Supplies**](#Supplies)
- [**PresensⓇ SDR™ V4.0.0**](#Presens_SDR_Software)
- [**LoligoⓇ MicroResp™ Software**](#Loligo_MicroResp_Software)
- [**Initial Setup**](#Initial_Setup)
- [**Water Preparation**](#Water Preparation)
- [**Sample Preparation**](#Sample_Preparation)
- [**Respiration**](#Respiration)
- [**Final Checks**](#Final_Checks)
- [**Data Analysis**](#Data_Analysis)
- [**Take-Down and Clean Up**](#Take-Down)


<a name="Supplies"></a> **Supplies**

- 2 PreSens SDR SensorDish® Reader Basic Set [(SDR Specs)](https://www.presens.de/products/detail/sdr-sensordish-reader-basic-set) [(SDR User Manual)](https://github.com/Putnam-Lab/Lab_Management/blob/master/Lab_Resources/Equipment_Protocols/Respirometry_Protocol/Images/SDR_UserManual.pdf) 
- 2 PreSens SDR QuickStart Guide [PreSens Getting Started](https://github.com/Putnam-Lab/Lab_Management/blob/master/Lab_Resources/Equipment_Protocols/Respirometry_Protocol/Images/SDR_GettingStarted_GS_SDR-16-01_dv2.pdf)    
- Loligo Glass 24 well microplate with Presens Oxygen spots [Loligo 80µl well size plate Cat #CH25000](https://loligosystems.com/products/microplate/accessories/24-well-glass-microplate-80-ul/)
OR 
- Plastic 24 well plate with Loligo glass vials 2ml (or other appropriate size)
- LoligoⓇ MicroResp™ Software [(Software Download)](https://www.loligosystems.com/downloads)
- [> 48 pieces of 12mm Microscope Cover Glass](https://www.amazon.com/gp/product/B00XZP7XMU/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)
- Windows Computer 
- [Digital Traceable Thermometer](https://www.traceable.com/4000-traceable-digital-thermometer.html)
- Kimwipes
- DI Water
- Squeeze Bottle
- Towels
- Isopropanol wipes
- Air-saturated filtered seawater (100% FSW)
- Zero percent oxygen calibration solution (FSW saturated with sodium sulfite)

## Software Options
<a name="Presens_SDR_Software"></a> **PresensⓇ SDR™ V4.0.0**

1. Download and install the PresensⓇ SDR™ V4.0.0 Software to a windows computer. Download found here: [(Presens Software Download)](https://www.presens.de/index.php?eID=dumpFile&t=f&f=1466&token=5a8621a95739d6b1afbfc48719edafeccb4e1b87). 
- [Windows XP/Vista/7/8 USB Serial Driver](https://www.presens.de/index.php?eID=dumpFile&t=f&f=1456&token=88b25aa3ec8e8e89942b5c586ba7f4076bae219a)
- [Windows XP/Vista USB Serial Driver](https://www.presens.de/index.php?eID=dumpFile&t=f&f=1469&token=27969a51372168cc3a583a1e40b24c5b8584c2c2)

or if LoligoⓇ MicroResp™ Software was purchased with Loligo Plate

<a name="Loligo_MicroResp_Software"></a> **LoligoⓇ MicroResp™ Software**
1. Download and install the LoligoⓇ MicroResp™ Software to a windows computer. Download found here: [(Loligo Software Download)](https://www.loligosystems.com/downloads). 

[Loligo Plate Calibration and Care](https://github.com/Putnam-Lab/Lab_Management/blob/master/Lab_Resources/Equipment_Protocols/Respirometry_Protocol/Images/Loligo_Plate_microresp_quickguide.pdf)

<a name="Initial_Setup"></a>**Initial Setup**

Setting up the SDR sensor plates and accompanying system for the first time in a new place:

1.  Assemble SDR reader following the [(SDR SensorDish Reader Installation Video)](https://www.youtube.com/watch?v=F0_b4Ws6Eow&feature=youtu.be). Connect the SDR plate readers to the USB port on the computer and open the LoligoⓇ MicroResp™ Software. Load the correct calibration file for the instrumentation used. For the Loligo 1624 Microplate the calibration files can be found here: [(Calibration Files)](https://www.loligosystems.com/microplate-data)


2. Assemble and run the equipment in a temperaure-controlled environment, such as an incubator. Fluctuations in room temperature and increases in temperature due to the use of LED lighting can influence measurements. Temperature control using an incubator will allow for respiration measurements in treatment conditions if desired.  


3. Run a one-point calibration with 100% oxygen saturated filtered seawater (FSW) for each plate before each run. To do this, bubble FSW for 15 minutes or vigoursly shake in a falcon tube to fully aerate the water. Load the plate with the 100% saturated FSW and place the plate in the incubator on the SDR. In the software, select oxygen levels be measured at % air saturation. Click "Calibration" and then "One-point adjustment". A box will pop up with the % air saturation values for each well. These should be between 90-120%. At the box at the bottom, enter "100" for % air saturation. Click OK. Repeat these steps for both plates.


4. After the calibration, click "Single Scan" in the upper left hand corner. This will run a single measurement scan on all of the wells to double check the calibration. The values should be around 98-105% air saturation. The plate is now calibrated! **It is strongly recommended to run the calibration before every plate/run, especially if different temperatures are being measured.** 

5. On the software in the top tool bar, input the salinity of the water being used in the vials or glass plate as well as the desired temperature. You will monitor the temperature with a thermometer that stays in the incubator for the entirety of the respiration run.
6. Set the parameter to oxygen
7. Set the batch number to PSt-2408-01
8. Set log interval, I reccomend 2 minutes to limit static
9. Select log measurement and save files to desired location
10. DO NOT let computer go to sleep, make sure screen will not turn off during run

<a name="Water_Preparation"></a> **Water Preparation**

1. Filter Sea Water to 10 mm with a sock filter. Run water through 2 times.

2. Calibrate refractometer with DI water around 20ºC and record the salinity each time you run the SDR program.


<a name="Sample_Preparation"></a> **Sample Preparation**


1. Set up SDR respirometry equipment (see [**Initial Setup**](#Initial_Setup) for details). Set oxygen concentration in units of µmol/L, indicate temperature and salinity.    
2. Use snails that have just emerged and are around the same age (appx. within 18 hours).
3. Using calipers record the length of at least one snail from each tea infuser.
3. Put each snail in a 2ml vial or if using the 250 ml glass plate, load samples into wells, loading desired wells with samples and at least 2 with 0.2 µm filtered sea water (FSW) as blanks. Randomize the location of blanks for each run to limit well-specific differences in blank samples. 
4. Fill all vials with their respective treatment water
	- For crab water fill a measure X bucket with crabs and use that water to fill vials
	- Heat accordingly in incubator 
     ##### Glass plate
         - Once all samples are loaded in the plate, including blanks, seal each well with a glass coverslip. See video example of sealing wells here: [(Sealing Wells Video)](https://github.com/urol-e5/protocols/blob/master/images/Well_Loading_Example_Resp.mov) 
         - If using a waterbath, cover with [(Microsealing film)](https://www.loligosystems.com/products/microplate/accessories/microplate-sealing-film-100-pcs/), [(Silicon pad)](https://www.loligosystems.com/products/microplate/accessories/silicone-pad/) and a [(Compression block)](https://www.loligosystems.com/products/microplate/accessories/compression-block-for-microplate/) and fill waterbath completely 

     ##### 2ml vials
         - To fill glass vials, fill a MeasureX container with filtered sea water and fully submerge vials with sample inside. Shake vial and rub fingers around lid of vial to ensure there are no bubbles present.

5. Make sure that the OxoDish or HydroDish are correctly aligned over the middle of the lasers on the SDR SensorDish Readers. 
6. The SensorDishes can easily be positioned on the SDR due to a groove in the housing of the SDR.
7. Please be sure that the SensorDishes rest in the groove properly, otherwise the measurement signal will not be sufficient, which results in a bad resolution or even the message “NO SENSOR”.
8. Be sure to put the SensorDish® aligned correctly onto the SDR (well numeration) to be able to associate the software values with your samples.
9. Create a platemap of the location of the EC full sample ID
10. Run [**Respiration**](#Respiration) trials.




<a name="Respiration"></a> **Respiration**
	
1. Turn off lights or block incubator windows with tinfoil/ trash bag. Collect data under darkness for a period of time in which a stable signal is recorded that is different than the blanks and sustained, recommended to run for 1-2 hours. Look for a decrease in oxygen that is different from the blanks. 
	- Oxygen measurements will appear “jumpy” under the light as the SDR plate readings are variable under light. For this reason, be sure to run respiration runs in dark and long enough to provide enough data for analysis to extract a representative slope.	
2.  Running 1 full plate will provide n=22 samples and n=2 blanks. Run as many plates to obtain desired sample size or run all treatment conditions. During run, watch for bubbles and breakages in well sealing and note these issues on metadata sheet. These wells will need to be excluded from analyses. It is therefore important to ensure a quality seal before the run begins and re-seal any wells that show bubbles prior to running. 
3.  Label the saved files with the following name format: “Date_RunID”. If more runs are needed, use Run2, Run3, etc. This file format is suggested - use file names that are informative and appropriate to the experiment. 
4. Export data files in .xlsx format and convert to .csv for data analysis. 



<a name="Final_Checks"></a> **Final Checks**

1. Ensure complete recording of sample information, well and plate numbers, and notes (bubbles, problems with seal) as well as  R run times in metadata sheets. See example repositories below for examples. 
2. Ensure data downloaded completely from each run. This should include oxygen concentrations for each well as well as simulataneous temperature measurements. Data output will vary depending on software system.  

<a name="Data_Analysis"></a> **Data Analysis**

1. Data are analyzed by formating and preparing data and extracting slopes using the LolinR package. There are variations of analysis applications depending on experimental use. 

Refer to these repositories and notebooks for data analysis and workflows for respirometry data: 

[Kevin Wong Notebook] (https://kevinhwong1.github.io/KevinHWong_Notebook/)  
[Sam Gurr Notebook] (https://samgurr.github.io/SamJGurr_Lab_Notebook/)   
[Ariana Huffmyer Notebook] (https://ahuffmyer.github.io/ASH_Putnam_Lab_Notebook/)  

[Ariana Huffmyer Git Repository: M. capitata and A. hyacinthus P and R] (https://github.com/AHuffmyer/EarlyLifeHistory_Energetics)    
[Kevin Wong Git] (https://github.com/kevinhwong1)    

<a name="Take-Down"></a> **Take-Down and Clean Up**

1. Confirm data are exported
3. Use isopropanol wipes on all of the cables and wipe dry with kimwipes. Notes: make sure to avoid the top of the SDR SensorDish Readers and ends of the wires. 
4. Disconnect and disassemble the SDR SensorDish Readers carefully and place components back into the SDR SensorDish Reader cases. 
5. Record and export all data to multiple backup locations (GoogleDrive, GitHub, Computer).
6. Check that all data files appear to have data in proper columns and consistency throughout. If you see any inconsistencies, make sure to redownload data from program or re-run trials before clean up.
7. Stop/Exit the Presens or MicroResp program. 
8. Remove snails from wells and either preserve for snail size/biomass measurements, or carefully place back into a beaker.
9. Over a sink, remove any access seawater from the wells. 
10. Use a squeeze bottle filled with DI water to rinse out each individual well with DI water and then <70% Ethanol and place on a towel to dry.
11. Rinse the top and bottom of each coverslip with DI water and then <70% Ethanol and place on a kimwipe to dry.
12. After all supplies have been dried, put them back in their respective cases. 
13. **keep the spots covered to reduce light effects**


### Future directions: Thermal performance curves

### Example protocol: Larval thermal performance curves 

This section details the protocol for performing thermal performance curves (TPCs). In *M. capitata* 2023 experiments, Ariana Huffmyer and Jill Ashey performed TPCs under 10, 15, 24, 28, 29, 32, 36, 39, and 40°C in the dark. This encompassed a range for temperatures relevant to the study species. 

See Ariana's [GitHub respository from this project](https://github.com/AHuffmyer/larval_symbiont_TPC) for example metadata and file formats and scripts.

1. Follow the steps outlined above for initial set-up. These measurements will be taken in the dark, so there is no need to set light levels. 
2. Set the incubator to the desired temperature for measurements. 
3. Perform a one-point calibration as detailed above. **Important**: perform a calibration at every temperature!!! This will ensure the plate is calibrated at the proper temperature for measurements. 
4. Gather the larvae and incubate them in the dark for 20-30 minutes. Load the larvae in the plates as detailed above. Make sure to have plate maps prepared beforehand with a sufficient number of replicates and blanks. After the larvae are loaded into the plates, incubate the plates in the dark for 5 minutes.
5. Load the plates onto the SDR in the incubators set to the desired temperatures. Start the run on the program and let the program run for 15-20 minutes. 
6. Stop the program and export the data. Record start and stop times in metadata. 
7. Remove the plates and clean them, making sure to remove all larvae. Turn the incubators to the next TPC temperature. 
8. Once the incubators have reached the next temperature, re-calibrate each plate at that temperature. **Important**: perform a calibration at every temperature!!! This will ensure the plate is calibrated at the proper temperature for measurements. 
9. Re-load the plate with fresh larvae, put the plate on the SDR and begin measurements. 
10. Repeat these steps for each temperature. 
11. Follow the steps outlined above for take down and clean up. 