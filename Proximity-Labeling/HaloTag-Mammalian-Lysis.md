Whole Cell Lysis of HaloTag Samples
================================================================================
Description: Lysis buffer contains detergents suited to disrupt all cellular membranes with minimal impact on HaloTag activity.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [Stable cell line generation by lentiviral infection](../Lentivirus-Stables/virus-production-HEK293T.md)
* [In cell DSP crosslinking](./In-Cell-DSP-Crosslinking.md)

Materials:
--------------------------------------------------------------------------------
  * Cell pellet
  
  * **HaloTag Mammalian Lysis Buffer (HTMLB)**  
    ◦ 50 mM Tris-HCl pH 7.5  
    ◦ 150 mM NaCl  
    ◦ 1% Triton-X 100  
    ◦ 0.1% Sodium Deoxycholate  
    _Note: Add detergents last and store buffer at 4 °C._
  
  * "Day of" lysis additives  
    
    ◦ [50X protease inhibitor](https://www.promega.com/products/protein-purification/protein-purification-kits/protease-inhibitor-cocktail/?catNum=G6521)<br/>
    _Do not use protease inhibitor cocktails (like Halt) that include AEBSF, it inhibits HaloTag._<br/>
    _PMSF is not stable in water. Resuspend dry inhibitor stock in 100% ethanol and store at 4 °C._  
    ◦ [100X phosphatase inhibitor](https://www.thermofisher.com/order/catalog/product/78420#/78420)  
    ◦ [250 Units/µl Benzonase Nuclease](https://www.sigmaaldrich.com/catalog/product/sigma/e1014?lang=en&region=US&cm_sp=Insite-_-caSrpResults_srpRecs_srpModel_e1014-25ku-_-srpRecs3-1) (degrades all nucleic acids)  

  * **Protein Purification Buffer - NP40 (PPB-N)**  
    ◦ 50 mM HEPES pH 7.5  
    ◦ 150 mM NaCl  
    ◦ 0.005% NP-40 (or IGEPAL CA-630)  
    _Note: Add detergent last and store buffer at 4 °C._
     
Equipment Required:
--------------------------------------------------------------------------------
  
  * [Sonicator](https://www.fishersci.com/shop/products/fisher-scientific-model-120-sonic-dismembrator-4/p-3974654) (other models need optimization)

<!-- Use <br/> to fill in first page -->

___
Protocol:
--------------------------------------------------------------------------------

**1.** Add protease inhibibitor (1/50), phosphatase inhibitor (1/100), and Benzonase (1/5000) to 1X in HTMLB to create lysis buffer.

**2.** Lyse cell pellets on ice for 15 minutes in prepared lysis buffer.
  * For multi-well plate formats, use 25 µl/cm<sup>2</sup> of lysis buffer
  * For 10cm and 15 cm dishes, use 5 µl/cm<sup>2</sup> of lysis buffer
    
    * Examples: 250 µl for a 6-well, 750 µl for each 15 cm dish
    
**3.** Sonicate each sample on ice with 10X short (5 seconds on, 1 sec off) pulses at 30% amplitude. <br/>*Note: This value should be optimized for each sonicator.*<br/>*The time it takes to sonicate multiple samples is usually enough for complete lysis (10-15 minutes).*
  
**4.** In 1.7 mL eppendorf tubes, briefly vortex samples and clear lysates at 14,000 xg for 10 minutes at 4 °C.<br/>
Retain supernatants and pool larger samples back into conical tubes if necessary.

**5.** Dilute cleared lysates with 2 volumes of PPB-N to limit detergent interference with HaloTag activity.

  * Dilute lysates can be stored at -80 °C, but HaloTag pulldowns are best performed immediately.<br/>
  BCA assay will be required to quantitate protein for next steps.

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="../General/BCA-Assay.md">
BCA protein quantification</a>

</p> <a href="../General/Western-Blotting.md">
Western Validation</a>

</p> <a href="../Mass-Spec-Prep/Bead-Reduction-Elution.md">
Rapigest reduction, alkylation, and Trypsin Digestion</a>

</p> <a href="../Mass-Spec-Prep/C18-Column-Cleanup.md">
C18 Column</a>
  
</p> <a href="../Mass-Spec-Prep/Ethyl-Acetate-Cleanup.md">
Ethyl Acetate Cleanup</a>  
  
</p> <a href="../Mass-Spec-Prep/Peptide-Quant.md">
Peptide Quantification</a>

</details>
