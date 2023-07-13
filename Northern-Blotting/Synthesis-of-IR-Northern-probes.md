Synthesis of near IR Northern probes
================================================================================
Description: Make body-labeled fluorescent RNA probes for Northern blotting

Materials:
--------------------------------------------------------------------------------
  **In vitro transcription**  
  * T7 DNA template (50-250 ng/µl)
  * [T7 RNA polymerase 50 U/µl](https://www.neb.com/products/m0251-t7-rna-polymerase?gclid=Cj0KCQiAi8KfBhCuARIsADp-A57GNLut6Ljx0Vs8oFy-UTuFQ5o9echAGb_0VRMSuEzQ4IjYrTkXpFsaArplEALw_wcB#Product%20Information)
  * 20 mM Spermidine (3 µl of pure 6.37 M in 1 mL of water)
  * Separate stocks of 10 mM rATP, rCTP, rGTP, and rUTP
  * 10 mM 5-Azido-C<sub>3</sub>-rUTP
  * 100 mM DTT
  * **10X T7 Buffer**  
    ◦ 400 mM Tris-HCl, pH 8.0  
    ◦ 250 mM NaCl  
    ◦ 80 mM MgCl<sub>2</sub>  
  
  **DNase Treatment**      
  * TURBO DNase (2U/µl)
  
  **Dye Labeling**  
  * 6-10% denaturing urea polyacrylamide gels  
  * [10 mM 800CW-DBCO Infrared Dye](https://www.fishersci.com/shop/products/800cw-dbco-1/NC0902760) (dissolve 0.5 mg in 37.5 µl DMSO)
  * 10X PBS pH 7.4  
  * SPRI beads
    

Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler/heat block set to 37 °C
  * Polyacrylamide gel rig
  * Magnetic rack

<br/>

___
Protocol:
--------------------------------------------------------------------------------

**Part 1: In vitro transcription (overnight reaction)**  

**1.** For each transcription:<br/>
Make 4 µL of a 3:1 mixture of rUTP and 5-Azido-C<sub>3</sub>-rUTP (10 mM total).

**2.** Assemble the transcription reactions as follows:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | DNA template | 50-250 ng/µl | **2**  µL | 
  | Spermidine | 20 mM | **1**  µL |
  | rATP | 10 mM | **1**  µL |
  | rCTP | 10 mM | **1**  µL |
  | rGTP | 10 mM | **1**  µL |
  | rUTP mix | 10 mM | **1**  µL |
  | Buffer | 10X | **1**  µL |
  | DTT | 100 mM | **1**  µL |
  | T7 RNA Polymerase | 50 U/µL | **1**  µL |
  || **Total** | **10** µL |

**3.** Incubate reaction overnight (16 hours) at 37 °C.<br/>
_Note: thermocycler lid should be off or set to < 50 °C._

**Part 2: DNase Treatment (~20 minutes)** 

**4.** Add 1 µL of TURBO DNase and incubate for an additional 10 minutes at 37 °C.<br/>
*Note: There is 10 mM necessary CaCl<sub>2</sub> in the TURBO enzyme storage buffer.*

**5.** Purify products with [SPRI beads](../NGS/SPRI-beads.md).<br/>
_Note: For RNA probes ~ 100 nt, add 3X beads and 1.8X isopropanol._ <br/>
_Bind 10 minutes. Wash 2x in 85 % Ethanol. Dry and elute in 16 µL of water._


<br/><br/>
**Part 3: Gel Verification/Purification (3 hours + variable)** 

**6.** RNA probes can be visualized on a denaturing urea polyacrylamide gel.<br/>
*Note: If there are significant truncation products, full length should be gel-purified.*<br/>
*Gel slices can be eluted passively in TBE or [electroeluted](https://doi.org/10.1016/j.ab.2013.02.021) and precipitated.*

**Part 4: Dye Labeling** 

**7.** In 20 µL 1X PBS, combine 20 molar equivalents of 800CW DBCO with 5 µL RNA probe. <br/>
Incubate in the dark at room temperature for 6 hours.

**8.** Purify labeled RNA probes again with [SPRI beads](../NGS/SPRI-beads.md) at ratios relevant to probe size.<br/>
Elute products in 16 µL.

**9.** RNA labeling can be confirmed by fluorescence on a denaturing urea polyacrylamide gel.<br/>
_Note: In general, 1 µL of product is enough to visualize on a gel._

  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->


<details>
  <summary>More Info</summary>
  
  <a href="https://doi.org/10.1261%2Frna.068213.118">
Original IR Northern Paper</a>

</details>
