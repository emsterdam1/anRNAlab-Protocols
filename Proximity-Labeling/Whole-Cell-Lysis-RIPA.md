RIPA-based Whole Cell Lysis
================================================================================
Description: RIPA buffer contains detergents suited to, with the help of sonication, disrupt all cellular membranes and break up chromatin.
[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [Stable cell line generation by lentiviral infection](./Making-Stables.md)
* [MiniTurbo biotinylation](./miniTurbo-biotinylation.md)

Materials:
--------------------------------------------------------------------------------
  * Cell pellet
  
  * 1X Mass Spec RIPA lysis buffer pH 7.5
  
    * 50 mM HEPES pH 8 (HEPES is substituted instead of Tris for MS compatibility)
    * 150 mM NaCl
    * 2 mM EDTA (Metal chelator)
    * 0.1% SDS
    * 1% Nonidet-P40 (or IGEPAL CA-630)
    * 0.2% Sodium Deoxycholate (some formulations have up to 0.5%)
    * 10% Glycerol (for protein solubility and stability)
    
    *Note: Add detergents and glycerol last and leave room to pH to 7.5 w/HCl.*<br/>*Store buffer at 4 °C.*
  
  * Day of lysis additives
    
    * [100X protease inhibitor](https://www.thermofisher.com/order/catalog/product/78429#/78429)
    * [100X phosphatase inhibitor](https://www.thermofisher.com/order/catalog/product/78420#/78420)
    * [250 Units/µl Benzonase Nuclease](https://www.sigmaaldrich.com/catalog/product/sigma/e1014?lang=en&region=US&cm_sp=Insite-_-caSrpResults_srpRecs_srpModel_e1014-25ku-_-srpRecs3-1) (degrades all nucleic acids)
    * [100X = 1M N-ethylmaleimide](https://www.thermofisher.com/order/catalog/product/23030?us&en#/23030?us&en) (labels cysteines, optional, prepare fresh in ethanol)
     
Equipment Required:
--------------------------------------------------------------------------------
  * [Sonicator](https://www.fishersci.com/shop/products/fisher-scientific-model-120-sonic-dismembrator-4/p-3974654) (other models need optimization)

<br/><br/><br/><br/><br/><br/><br/><br/><br/>

<!-- Use <br/> to fill in first page -->
___
Protocol:
--------------------------------------------------------------------------------

**1.** Add protease inhibibitor (1/100), phosphatase inhibitor (1/100), and Benzonase (1/5000) to 1X in RIPA buffer to create final lysis buffer.
  *Note: NEM (1/100) can also be optionally added to disrupt reduced cysteines.*

**2.** Lyse cell pellets on ice in prepared lysis buffer.
  * For multi-well plate formats, use 25 µl/cm<sup>2</sup> of lysis buffer
  * For 10cm and 15 cm dishes, use 5 µl/cm<sup>2</sup> of lysis buffer
    
    * Examples: 250 µl for a 6-well, 750 µl for each 15 cm dish
    
**3.** Sonicate each sample on ice with 10X short (5 seconds on, 1 sec off) pulses at 30% amplitude.
  *Note: This value should be optimized for each sonicator*
  
**4.** In 1.7 mL eppendorf tubes, briefly vortex samples and clear lysates at 21,000 xg for 30-60 minutes at 4 °C. Retain supernatants and pool larger samples back into conical tubes if necessary.

  * Cleared lysates can be stored at -80 °C. BCA assay will be required to quantitate protein for next steps.

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="./BCA-Assay.md">
BCA protein quantification</a>

</p> <a href="./miniTurbo-Western-Validation.md">
Western Validation</a>

</p> <a href="./miniTurbo-Strep-IP.md">
Strep IP</a>

</p> <a href="./Affinity-MS-Sample-Prep.md">
MS Sample Prep</a>

</p> <a href="./Peptide-Quant.md">
Peptide Quantification</a>

</details>

<details>
  <summary>More Info</summary>
  
  <a href="https://www.website.com/just-copy-paste-your-target-website-here.html">
WEBSITE LINK NAME</a>  

</details>
