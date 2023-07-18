Near IR Northern Blotting of RNA
================================================================================
Description: Detect RNA targets in a mixture with near IR probes.

Materials:
--------------------------------------------------------------------------------
  **Denaturing Agarose Gel**  
  * Concentrated RNA sample (at least 10 µg of total RNA)
  * Agarose
  * Formaldehyde (37 %)
  * Glycerol
  * [GelRed or GelGreen Nucleic Acid Gel Stain](https://biotium.com/technology/nucleic-acid-gel-stains/gelred-gelgreen-dna-gel-stains/)
  * **[10X MOPS RNA Running Buffer](https://www.thermofisher.com/order/catalog/product/AM8671) (pH to 7.0 with NaOH)**  
    ◦ 200 mM MOPS (3-(N-morpholino)propanesulfonic acid)  
    ◦ 50 mM NaOAc  
    ◦ 10 mM EDTA  

  **Northern Blotting**      
  * 3MM Chromatography Whatman paper (8 sheets and 1 longer wick)
  * paper/sponges for transfer stack
  * [nylon membrane](https://www.cytivalifesciences.com/en/us/shop/molecular-and-immunodiagnostics/genomic-consumables/nytran-supercharge-spc-blotting-membranes-p-04733)
  * **[20X SSC Buffer](https://www.takarabio.com/products/protein-research/sds-page-and-western-blotting/buffers-and-powders/ssc-powder) (pH to 7.0 with NaOH)**  
    ◦ 300 mM sodium citrate 
    ◦ 3 M NaCl  
    
  **Probe hybridization**  
  * Near IR Northern probes (1 µM)
  * [Hybridization buffer](https://www.thermofisher.com/order/catalog/product/AM8677)
  * 20 % SDS solution
    
Equipment Required:
--------------------------------------------------------------------------------
  * Agarose Gel Rig
  * Fume Hood
  * [Northern Blotting Apparatus](https://www.cytivalifesciences.com/en/us/shop/protein-analysis/blotting-and-detection/blotting-equipment/turboblotter-kits-large-p-05563)
  * Hybridization oven with rotation
  * Gel/Blot fluorescent imager

<br/>

___
Protocol:
--------------------------------------------------------------------------------

**Part 1: Denaturing Agarose gel (~3 hours)**  

**1.** For a 100 ml volume gel, combine the following and melt:  
  
  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | agarose | | **1**  g | 
  | MOPS RNA Running Buffer | 10X | **10**  mL |
  | Water | | **74**  mL |
  || **Total** | **84** mL |
  
**2.** In a fume hood, add 16 mL of 37 % formaldehyde to the mixture and cast gel.<br/>
_Gel sets in ~30 minutes._

**3.** Prepare 5X Sample buffer (mix 500 µL of 10X MOPS with 500 µL of glycerol)
_Note: thermocycler lid should be off or set to < 50 °C._

**4.** Assemble enough 2X RNA Loading Buffer per RNA sample as follows:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Sample Buffer | 5X | **4**  µl | 
  | Gel stain | 100X | **0.8**  µl |
  | Formaldehyde | 37 % | **3.35**  µl |
  | Water | | **1.85**  µl |
  || **Total** | **10** µl |

**5.** Mix 10 µl of RNA sample (at least 10 µg) with 10 µl of 2X Loading Buffer.<br/>
Denature RNAs at 70 °C for 5 minutes and cool at 0-4 °C for 2 minutes.

**6.** Load samples (and usually a ladder). Run gel at 110 V for 1.5 hours.<br/>
Image gel to ensure even loading before assembling Northern transfer.

**Part 2: DNase Treatment (~20 minutes)** 
**Part 3: Gel Verification/Purification (3 hours + variable)** 
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
