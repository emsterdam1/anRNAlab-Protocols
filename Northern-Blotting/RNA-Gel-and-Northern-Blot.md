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
  * 20 % SDS 
    
Equipment Required:
--------------------------------------------------------------------------------
  * Agarose Gel Rig
  * Fume Hood
  * [Northern Blotting Apparatus](https://www.cytivalifesciences.com/en/us/shop/protein-analysis/blotting-and-detection/blotting-equipment/turboblotter-kits-large-p-05563)

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
<br/><br/><br/><br/>


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
