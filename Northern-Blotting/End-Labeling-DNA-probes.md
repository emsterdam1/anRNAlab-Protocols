Tailing DNA IR Northern probes with Terminal Transferase
================================================================================
Description: Make end-labeled fluorescent DNA probes for Northern blotting

Materials:
--------------------------------------------------------------------------------
  **Terminal Transfer**  
  * 10 µM DNA northern probe
  * [Terminal Transferase 20 U/µl](https://www.neb.com/products/m0315-terminal-transferase)
  * 2.5 mM CoCl<sub>2</sub>
  * 100 µM [5-Azidomethyl-2'-deoxyuridine (AmdU)](https://www.lumiprobe.com/p/amdu-azidomethyl-deoxyuridine)
  * **10X TdT Buffer**  
    ◦ 200 mM Tris-Acetate, pH 7.9  
    ◦ 500 mM KOAc (potassium acetate)  
    ◦ 100 mM MgOAc<sub>2</sub> (magnesium acetate)
  * SPRI beads
  
  **Dye Labeling**  
  * 6-10% denaturing urea polyacrylamide gels  
  * 10 mM [AZDye 680 DBCO Infrared Dye](https://clickchemistrytools.com/product/afdye-680-dbco/) (dissolve 1 mg in 92 µl DMSO)
  * 10X PBS pH 7.4  

    

Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler/heat block set to 37 °C
  * Microvolume spectrophotometer
  * Magnetic rack
  * Polyacrylamide gel rig
  
___
Protocol:
--------------------------------------------------------------------------------

**Part 1: Terminal Transfer of Azido-dUTP (~1.5 hours)**  

**1.** Assemble the transferase reactions as follows:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | DNA probe | 10 µM | **10**  µL | 
  | AmdU | 100 µM | **4**  µL |
  | TdT Buffer | 10X | **2**  µL |
  | CoCl<sub>2</sub> | 2.5 mM | **2**  µL |
  | RNase-free water |  | **1**  µL |  
  | Terminal Transferase | 10 U/µL | **1**  µL |
  || **Total** | **20** µL |

**2.** Incubate reaction at 37 °C for 1 hour.<br/>
_Note: thermocycler lid should be off or set to < 50 °C._ 

**3.** Purify products with [SPRI beads](../NGS/SPRI-beads.md).<br/>
_Note: For short DNA probes < 50 nt, add 5X beads and 7.2X isopropanol._ <br/>
_Bind 10 minutes. Wash 2x in 85 % Ethanol. Dry and elute in 16 µL of water._

**4.** Quantify ssDNA by microvolume spectrophotometer.<br/>
_Note: Calculate molarity assuming an average of 3 added AmdU._

**Part 2: Dye Labeling** 

**5.** In 20 µL 1X PBS, combine 20 molar equivalents of AZDye 680 DBCO with 5 µL of tailed ssDNA probe. <br/>
Incubate in the dark at room temperature for 6 hours.

**6.** Purify labeled DNA probes again with [SPRI beads](../NGS/SPRI-beads.md) at ratios relevant to probe size.<br/>
Elute products in 16 µL.

**Part 3: Gel Verification/Purification (3 hours + variable)** 

**7.** ssDNA probes can be visualized on a denaturing urea polyacrylamide gel (6-15 %).<br/>
_Note: In general, 1 µL of product (~1.25 picomoles) is enough to visualize on a gel._

  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->


<details>
  <summary>More Info</summary>
  
  <a href="https://doi.org/10.1261%2Frna.068213.118">
Original IR Northern Paper</a>

</details>
