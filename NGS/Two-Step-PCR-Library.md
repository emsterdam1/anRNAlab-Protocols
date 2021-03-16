2-step PCR amplification of amplicon sequencing libraries
================================================================================
Description: Normally used to amplify cDNA for Mutational profiling, but could be used to add adapters and indices onto any DNA target.

[Go To Protocol](#protocol)

Materials:
--------------------------------------------------------------------------------
  **Both Steps**
  * 10 mM dNTP mix (each at 10 mM) _Sometimes these are included in the Enzyme Master Mix_
  * Buffer components (5X buffer, DMSO, Enzyme)
  * SPRI beads
  
  **Step 1 PCR**
  * 10 µM each gene-specific forward and reverse MaP primers
  * cDNA template (1 ng/µL OR unpurified product)  
  
  **Step 2 PCR**
  * Purified Step 1 product (1 ng/µL)
  * [In-house index primers](../CWML-primers.csv)
    * In-house index primer F (i7, 5 µM)
    * In-house index primer R (i5, 5 µM)

  
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler
  * Magnetic stand


<br/><br/><br/><br/>
<!-- Use <br/> to go to next page -->
  
Protocol:
--------------------------------------------------------------------------------
**1.** Mix 1-3 µl of cDNA template and 1.25 µL of each primer (per 25 µL reaction) with buffer components according to the polymerase chosen:

  * [Q5 Hot-start Master Mix](https://www.neb.com/protocols/2012/08/30/protocol-for-q5-hot-start-high-fidelity-2x-master-mix-m0494)
  * [Q5 Hot-start Polymerase](https://www.neb.com/protocols/2012/08/30/pcr-using-q5-hot-start-high-fidelity-dna-polymerase-m0493)
  
  _Note: Sometimes other polymerases work better for specific amplicons._<br/>_For difficult amplicons, adding DMSO to a final concentration of 3 % can help._
  
  
**2.** Incubate samples in thermocycler with the following settings:  

  | Cycles | Temp | Time | Step |
  | ---------: | :--------: | :---------: |:---------: |
  | **1** | **98 °C** | **0:30** | **inital denaturation** |
  
  **Optional Touchdown phase for lowly represented targets in cDNA**<br/>Annealing temp is reduced by 1 degree each cycle. Total cycles (this phase and next) should not exceed 40.
  || 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **variable** | **72->target °C** | **0:30** | **annealing** |
  || **72 °C** | **0:30** | **extension** |
  
  **Standard amplification phase**
  || 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **15-20X** | **target °C** | **0:30** | **annealing** |
  | | **72 °C** | **0:30** | **extension** |
 
  | 1 | 72 °C | 2 minutes | final extension |
  | ---------: | :--------: | :---------: |:---------: |
  
  _Note: the extension times and annealing temps can be optimized for amplicon length and primer Tm's_
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

**3.** Clean up 1st step PCR with a 1X ratio of [SPRI beads](./SPRI-beads.md), 2x 80% Ethanol washes, and 15 µL elution.

**4.** Mix 2 ng of Step 1 product and 5 µL of each index primer (per 50 µL reaction) with PCR buffer components and cycle:

  | Cycles | Temp | Time | Step |
  | ---------: | :--------: | :---------: |:---------: |
  | **1** | **98 °C** | **0:30** | **inital denaturation** |
  
  || 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **10X** | **67 °C** | **0:30** | **annealing** |
  | | **72 °C** | **0:30** | **extension** |
 
  | 1 | 72 °C | 2 minutes | final extension |
  | ---------: | :--------: | :---------: |:---------: |

**5.** Clean up 2nd step PCR with a 0.8X ratio of [SPRI beads](./SPRI-beads.md), 2x 80% Ethanol washes, and 15 µL elution.
