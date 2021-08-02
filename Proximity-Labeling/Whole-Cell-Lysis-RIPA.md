RIPA-based Whole Cell Lysis
================================================================================
Description: RIPA buffer contains detergents suited to, with the help of sonication, disrupt all cellular membranes and break up chromatin.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [Stable cell line generation by lentiviral infection](../Lentivirus-Stables/virus-production-HEK293T.md)
* [MiniTurbo biotinylation](./miniTurbo-biotinylation.md)

Materials:
--------------------------------------------------------------------------------
  * Cell pellet
  
  * 1X Mass Spec RIPA lysis buffer
  
    * 50 mM HEPES pH 7.5 (HEPES is substituted instead of Tris for MS compatibility)
    * 150 mM NaCl
    * 2 mM EDTA (Metal chelator)
    * 0.1% SDS
    * 1% Nonidet-P40 (or IGEPAL CA-630)
    * 0.2% Sodium Deoxycholate (some formulations have up to 0.5%)
    * 10% Glycerol (for protein solubility and stability)
    
    *Note: Add detergents and glycerol last and leave room to pH to 7.5 w/HCl.*<br/>*Store buffer at 4 °C.*
  
  * "Day of" lysis additives
    
    * [100X protease inhibitor](https://www.thermofisher.com/order/catalog/product/78429#/78429)
    * [100X phosphatase inhibitor](https://www.thermofisher.com/order/catalog/product/78420#/78420)
    * [250 Units/µl Benzonase Nuclease](https://www.sigmaaldrich.com/catalog/product/sigma/e1014?lang=en&region=US&cm_sp=Insite-_-caSrpResults_srpRecs_srpModel_e1014-25ku-_-srpRecs3-1) (degrades all nucleic acids)
    * [100X = 1M N-ethylmaleimide](https://www.thermofisher.com/order/catalog/product/23030?us&en#/23030?us&en) (labels cysteines, optional, prepare fresh in ethanol)
     
Equipment Required:
--------------------------------------------------------------------------------
  
  * [Sonicator](https://www.fishersci.com/shop/products/fisher-scientific-model-120-sonic-dismembrator-4/p-3974654) (other models need optimization)

<!-- Use <br/> to fill in first page -->

___
Protocol:
--------------------------------------------------------------------------------

**1.** Add protease inhibibitor (1/100), phosphatase inhibitor (1/100), and Benzonase (1/5000) to 1X in RIPA buffer to create lysis buffer. <br/>*Note: NEM (1/100) can also be optionally added to disrupt reduced cysteines.*

**2.** Lyse cell pellets on ice in prepared lysis buffer.
  * For multi-well plate formats, use 25 µl/cm<sup>2</sup> of lysis buffer
  * For 10cm and 15 cm dishes, use 5 µl/cm<sup>2</sup> of lysis buffer
    
    * Examples: 250 µl for a 6-well, 750 µl for each 15 cm dish
    
**3.** Sonicate each sample on ice with 10X short (5 seconds on, 1 sec off) pulses at 30% amplitude. <br/>*Note: This value should be optimized for each sonicator.*<br/>*The time it takes to sonicate multiple samples is usually enough for complete lysis (10-15 minutes).*
  
**4.** In 1.7 mL eppendorf tubes, briefly vortex samples and clear lysates at 21,000 xg for 30-60 minutes at 4 °C. Retain supernatants and pool larger samples back into conical tubes if necessary.

  * Cleared lysates can be stored at -80 °C. BCA assay will be required to quantitate protein for next steps.

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="../General/BCA-Assay.md">
BCA protein quantification</a>

</p> <a href="../General/Western-Blotting.md">
Western Validation</a>

</p> <a href="./miniTurbo-Strep-Pulldown.md">
Strep IP</a>

</p> <a href="../Mass-Spec-Prep/On-Bead-Digestion.md">
Rapigest reduction, alkylation, and Trypsin Digestion</a>

</p> <a href="../Mass-Spec-Prep/C18-Column-Cleanup.md">
C18 Column</a>
  
</p> <a href="../Mass-Spec-Prep/Ethyl-Acetate-Cleanup.md">
Ethyl Acetate Cleanup</a>  
  
</p> <a href="../Mass-Spec-Prep/Peptide-Quant.md">
Peptide Quantification</a>

</details>
