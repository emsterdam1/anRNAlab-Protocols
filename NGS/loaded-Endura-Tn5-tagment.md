Endura Tn5 library preparation for sequencing
================================================================================
Description: Using "tagmentation" workflow to fragment and index DNA libraries for next-gen sequencing.

Materials:
--------------------------------------------------------------------------------
  * Diluted dsDNA (0.3 ng/µL)
  * [Endura Tn5 reagents](https://www.zymoresearch.com/products/endura-tn5-transposase-loaded)
    * 10X Tagmentation Buffer
    * 10X Stop Buffer
    * Nextera adapter-loaded Endura Tn5 enzyme (1U/µl)
  * **Tn5 dilution buffer** (store at -20 °C)
    * 20 mM HEPES pH 7.5  
    * 100 mM NaCl  
    * 1 mM DTT
    * 0.1 % Triton X-100
    * 50 % Glycerol
  * [PCR cleanup kit](https://www.neb.com/en-us/products/t1130-monarch-spin-pcr-and-dna-cleanup-kit-5-ug)
  * [In-house index primers](../ARL-primers.csv)
    * In-house index primer F (i7, 5 µM)
    * In-house index primer R (i5, 5 µM)
  * [Q5® Hot Start High-Fidelity 2X Master Mix](https://www.neb.com/en-us/products/m0494-q5-hot-start-high-fidelity-2x-master-mix)
  * Magnetic SPRI beads [(Omega BioTek)](https://www.omegabiotek.com/product/mag-bind-totalpure-ngs)

Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler
  * Magnetic Stand

<br/><br/><br/><br/>
___
Protocol:
--------------------------------------------------------------------------------

**1.** Dilute Tn5 transposase to 0.005 U/µl in Tn5 dilution buffer. <br/>
       Aliquot into 50 µl portions and store long-term at -20 °C.

**2.** Set up tagmentation reactions for each dsDNA sample:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Tagmentation Buffer | 10X | **1**  µL | 
  |  dsDNA | 0.3 ng/µL | **7**  µL |
  | dilute Endura Tn5 | 0.005 U/µL | **2**  µL |
  || **Total** | **10** µL |
  
**3.** In a thermocycler, incubate reactions at 55 °C for 10 minutes.

**4.** Immediately add 1 µL 10X Stop Buffer and incubate 5 min at 75 °C.
  * *This stops the reaction, so timing is important*

**5.** Purify reaction product (for example with PCR cleanup kit)<br/>
       Elute product in 15 µL of water.

**6.** Assemble PCR reactions:
  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Tagmented DNA | | **15**  µL | 
  | i7 index primer | 5µM | **5**  µL |
  | i5 index primer | 5µM | **5**  µL |
  | Q5 Master Mix | 2X | **25**  µL |
  || **Total** | **50** µL |

<br/><br/><br/><br/><br/>
**7.** Run tagment-specific PCR:

  | Cycles | Temp | Time | Step |
  | ---------: | :--------: | :---------: |:---------: |
  | **1** | **72 °C** | **5:00** | **adapter overhang extension** |
  | **1** | **98 °C** | **1:00** | **inital denaturation** |
  
  || 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **-11X-** | **67 °C*** | **0:30** | **annealing** |
  || **72 °C** | **0:30** | **extension** |
 
  | 1 | 72 °C | 2:00 | final extension |
  | ---------: | :--------: | :---------: |:---------: |
  

**8.** Clean up PCRs with [SPRI beads](./SPRI-beads.md). Elute libraries in 16 µL of water.<br/>
       (0.65X ratio and 2X washes with 80% ethanol)
  
**9.** Check samples on a Bioanalyzer/TapeStation and assess length distributions before sequencing.<br/>
       Target is ~400 nt average, which can be shifted by moving [Tn5] between 0.00375-0.0075 U/µL
