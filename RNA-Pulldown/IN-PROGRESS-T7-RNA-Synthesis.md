Mid-scale synthesis of RNAs with T7 RNA polymerase
================================================================================
Description: Make RNAs for testing

Materials:
--------------------------------------------------------------------------------
  **In vitro transcription**  
  * T7 DNA template (50-250 ng/µl)
  * [T7 RNA polymerase 50 U/µl](https://www.neb.com/products/m0251-t7-rna-polymerase?gclid=Cj0KCQiAi8KfBhCuARIsADp-A57GNLut6Ljx0Vs8oFy-UTuFQ5o9echAGb_0VRMSuEzQ4IjYrTkXpFsaArplEALw_wcB#Product%20Information)
  * 20 mM Spermidine (3 µl of pure 6.37 M in 1 mL of water)
  * Mix of 10 mM each rATP, rCTP, rGTP, and rUTP
  * 100 mM DTT
  * 1 U/µl [Inorganic Pyrophosphotase (PPase)](https://www.neb.com/products/m0361-pyrophosphatase-inorganic-e-coli)
  * DMSO
  * 0.1 % Triton X-100
  * **10X T7 Buffer**  
    ◦ 400 mM Tris-HCl, pH 8.0  
    ◦ 250 mM NaCl  
    ◦ 80 mM MgCl<sub>2</sub>  
  
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

**Part 1: In vitro transcription (overnight reaction)**  

**1.** Assemble the transcription reactions as follows:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | DNA template | 50-250 ng/µl | **10**  µL | 
  | Spermidine | 20 mM | **5**  µL |
  | rNTP mix | 10 mM each| **5**  µL |
  | T7 Buffer | 10X | **5**  µL |
  | DMSO | | **5**  µL |
  | Triton X-100 | 0.1 % | **5**  µL |
  | DTT | 100 mM | **5**  µL |
  | PPase | 1 U/µl | **5**  µL |
  | T7 RNA Polymerase | 50 U/µL | **5**  µL |
  || **Total** | **50** µL |

**2.** Incubate reaction overnight (16 hours) at 37 °C.<br/>
_Note: thermocycler lid should be off or set to < 50 °C._

**Part 2: DNase Treatment (~20 minutes)** 

**3.** Add 5 µL of TURBO DNase and incubate for an additional 10 minutes at 37 °C.<br/>
*Note: There is 10 mM necessary CaCl<sub>2</sub> in the TURBO enzyme storage buffer.*

**4.** Purify RNA with [SPRI beads](../NGS/SPRI-beads.md) at a 1.8X ratio with two 70 % ethanol washes.

**Part 3: Gel Verification/Purification (3 hours + variable)** 

**5.** RNA probes can be visualized on a denaturing urea polyacrylamide gel.<br/>
  * Dilute RNA samples into 20 µL of 1X NEB RNA Loading Dye (target 10 pmoles total)
  * Dilute appropriate RNA ladder into 20 µL of 1X NEB RNA Loading Dye as well
  * Denature samples for 5 minutes at 70 °C
  * Load 18 µL of each sample
  * Gels can be stained for 30 minutes in 50 mL 3X GelRed solution (in water)<br/>
*Note: If there are significant truncation products, full length should be gel-purified.*<br/>
*Gel slices can be eluted passively in TBE or [electroeluted](https://doi.org/10.1016/j.ab.2013.02.021) and precipitated.*

**6.** Purify RNA with [SPRI beads](../NGS/SPRI-beads.md) again at a 1.8X ratio with two 70 % ethanol washes.

  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->
