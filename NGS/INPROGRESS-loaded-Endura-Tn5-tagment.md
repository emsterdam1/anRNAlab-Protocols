Endura Tn5 library preparation for sequencing
================================================================================
Description: Using "tagmentation" workflow to fragment and index DNA libraries for next-gen sequencing.

Materials:
--------------------------------------------------------------------------------
  * Diluted dsDNA (0.3 ng/µL)
  * [Endura Tn5 reagents](https://www.zymoresearch.com/products/endura-tn5-transposase-loaded)
    * 10X Tagmentation Buffer
    * 10X Stop Buffer
    * Neutralization Buffer
    * Nextera adapter-loaded Endura Tn5 enzyme (1U/µl)
  * **Tn5 dilution buffer** (store at -20 °C)
    * 20 mM HEPES pH 7.5  
    * 100 mM NaCl  
    * 1 mM DTT
    * 0.1 % Triton X-100
    * 50 % Glycerol 
  * [In-house index primers](../../ARL-primers.csv)
    * In-house index primer F (i7, 5 µM)
    * In-house index primer R (i5, 5 µM)
  * Magnetic SPRI beads [(Omega BioTek)](https://www.omegabiotek.com/product/mag-bind-totalpure-ngs)

Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler
  * Magnetic Stand

<br/><br/><br/><br/><br/><br/>
___
Protocol:
--------------------------------------------------------------------------------

**1.** Dilute Tn5 transposase to 0.0075 U/µl in Tn5 dilution buffer. <br/>
       Aliquot into 50 µl portions and store long-term at -20 °C.

**2.** Set up tagmentation reactions for each dsDNA sample:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Tagmentation Buffer | 10X | **1**  µL | 
  |  dsDNA | 0.3 ng/µL | **7**  µL |
  | dilute Endura Tn5 | 0.0075 U/µL | **5**  µL |
  || **Total** | **10** µL |
  
 **3.** In a thermocycler, incubate reactions at 55 °C for 5 minutes, then cool to 10 °C.

**4.** As soon as reactions reach 10 °C, add 5 µL Neutralization Buffer (NT) and incubate 5 min at RT.
  * *Neutralization buffer stops the reaction, so timing is important*
  
**5.** Assemble Nextera PCR reactions:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Tagmented DNA | | **25**  µL | 
  | i7 index primer | 5µM | **5**  µL |
  | i5 index primer | 5µM | **5**  µL |
  | Nextera PCR Master Mix |3.33X| **15**  µL |
  || **Total** | **50** µL |

<br/><br/><br/><br/><br/>
**6.** Run Nextera PCR:

  | Cycles | Temp | Time | Step |
  | ---------: | :--------: | :---------: |:---------: |
  | **1** | **72 °C** | **3:00** | **enzyme denaturation?** |
  | **1** | **95 °C** | **0:30** | **inital denaturation** |
  
  || 95 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **-12X-** | **55 °C*** | **0:30** | **annealing** |
  || **72 °C** | **0:30** | **extension** |
 
  | 1 | 72 °C | 5:00 | final extension |
  | ---------: | :--------: | :---------: |:---------: |
  

**7.** Clean up PCRs with columns or SPRI beads. Elute libraries in 30 µL of water.
  * Use [SPRI beads](./SPRI-beads.md) to purify (0.65X ratio and 2X washes with 80% ethanol).
  * Alternatively, purify with [column-based kit](https://www.neb.com/-/media/nebus/files/protocols/t1030_quick_protocol_card_monarch_pcrdna_cleanup.pdf?rev=df342b32fb1144af88257b50773a0c7a&hash=662C2FB4EA8277B53B4FE89E3D5887A8)
  
**8.** Check samples on a Bioanalyzer/TapeStation and assess length distributions before sequencing.
