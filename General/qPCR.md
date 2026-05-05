qPCR from Cellular RNA
================================================================================
Quantify level of RNA in cellular samples.

Materials:
--------------------------------------------------------------------------------
  **Reverse Transcription cDNA**  
  
  * Cellular mRNA (1 ug/sample)
  * iSCRIPT cDNA Synthesis Kit (Blue Label Reaction Mix Buffer, Yellow Label RT Enzyme)

 **qPCR Reaction**  
  
  * cDNA from RT reaction
  * SYBR Green (Thermo)
  * 384 well plate with plate cover

Equipment Required:
--------------------------------------------------------------------------------
  * Centrifuge
  * qPCR Thermocycler (BioRad CFX Opus)
  * Repeat Pipetter
<br/><br/><br/>





  
___
Protocol:
--------------------------------------------------------------------------------
**Part 1: Reverse Transcrption of RNA (~1 hr)**  

**1.** Assemble an RT reaction for each sample as follows:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Sample RNA | X ng/µL | **500ng/X**  µL | 
  | Buffer | 5X | **4**  µL |
  | RT Enzyme |  | **1**  µL |
  | RNase-free water |  | **To Total** |
  || **Total** | **20** µL |

**2.** Assemble a no RT control reaction for each sample as follows:
  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Sample RNA | X ng/µL | **250ng/X**  µL | 
  | Buffer | 5X | **2**  µL |
  | RNase-free water |  | **0.5**  µL |
  | RNase-free water |  | **To Total** |
  || **Total** | **10** µL |

_Note: The no RT can have fewer inputted RNA µg, but for simplicity the same input amount is used here._

**2.** Run the iSCRIPT cDNA protocol on the thermocycler:
* Priming at 25°C for 5 min
* RT at 46°C for 20 min
* RT inactivation at 95°C for 1 minute
* Hold at 4°C

**3** Add 100 µL to each reaction to dilute it. 

**Part 2: qPCR of cDNA (~30 min prep, 2 hr run)**

**1.** Create master mixes for each primer set in the following ratio per sample:
 | Component | Concentration | Quantity | Notes
  | ---------: | ---------: | :---------- | :---------- |
  | Fwd Primer| 10 µM | **0.5**  µL | |
  | Rev Primer | 10 µM | **0.5**  µL | |
  | RNase-free water |  |**2**  µL | |
  | SYBR Green |  |**5**  µL | Add **last**, only when ready to load plate|
  || **Total** | **8** µL | |

**2.** Aliquot 2 µL of the diluted cDNA in triplicate per primer set. 

**3.** Add 8 µL of the appropriate master mix.

**4.** Cover the plate with the adhesive cover. Take time to ensure each well is sealed, as is the entire perimeter of the plate. Keep in the dark.

**5.** Spin down in centrifugre. Use "Short" setting and allow the speed to get up to 1000 x g

**6.** Place plate in the Biorad CFX Opus, with the following cycles:
* 95C for 3 minutes
* Cycle 40X
  * Priming at 95C for 15 sec
  * Annealing at 65C for 30 sec
  * Elongation at 72C for 40 sec
* Melting 65C to 95C 0.5C increment for 5 sec


