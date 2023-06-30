Synthesis of long RNAs with MegaScript
================================================================================
Description: Make long RNAs for testing

Materials:
--------------------------------------------------------------------------------
  **In vitro transcription**  
  * T7 DNA template (50-250 ng/µl)
  * [T7 RNA polymerase Enzyme Mix](https://www.thermofisher.com/order/catalog/product/AM1333)
  * Mix of 25 mM each rATP, rCTP, rGTP, and rUTP
  * 10X T7 Reaction Buffer

  **DNase Treatment**      
  * TURBO DNase (2U/µl)
  * SPRI beads
  
  **Gel Validation and Purification**  
  * 6-10% denaturing urea polyacrylamide gels
  * 2X NEB RNA Loading Dye
  * 10,000X GelRed Nucleic Acid Stain  

Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler/heat block set to 37 °C
  * Polyacrylamide gel rig
  * Magnetic rack
  
___
Protocol:
--------------------------------------------------------------------------------

**Part 1: In vitro transcription (~4.5 hours)**  

**1.** Assemble the transcription reactions as follows:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | DNA template | 50-250 ng/µl | **4**  µL | 
  | rNTP mix | 25 mM each | **5**  µL |
  | T7 Buffer | 10X | **2**  µL |
  | RNase-free water | | **7**  µL |
  | T7 Enzyme Mix | | **2**  µL |
  || **Total** | **20** µL |

**2.** Incubate reaction for 4 hours at 37 °C.<br/>
_Note: thermocycler lid should be off or set to < 50 °C._

**Part 2: DNase Treatment (~25 minutes)** 

**3.** Add 1 µL of TURBO DNase and incubate for an additional 15 minutes at 37 °C.<br/>
*Note: There is 10 mM necessary CaCl<sub>2</sub> in the TURBO enzyme storage buffer.*

**4.** Purify RNA with [SPRI beads](../NGS/SPRI-beads.md) at a 1.8X ratio with two 70 % ethanol washes.

**Part 3: Gel Verification/Purification (3 hours + variable)** 

**5.** RNA can be visualized on a denaturing urea polyacrylamide gel.<br/>
  * Dilute RNA samples into 20 µL of 1X NEB RNA Loading Dye (target 10 pmoles total)
  * Dilute appropriate RNA ladder into 20 µL of 1X NEB RNA Loading Dye as well
  * Denature samples for 5 minutes at 70 °C
  * Load 18 µL of each sample
  * Gels can be stained for 30 minutes in 50 mL 3X GelRed solution (in water)<br/>
*Note: If there are significant truncation products, full length should be gel-purified.*<br/>
*Gel slices can be eluted passively in TBE or [electroeluted](https://doi.org/10.1016/j.ab.2013.02.021) and precipitated.*

**6.** Purify RNA with [SPRI beads](../NGS/SPRI-beads.md) again at a 1.8X ratio with two 70 % ethanol washes.

  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->
