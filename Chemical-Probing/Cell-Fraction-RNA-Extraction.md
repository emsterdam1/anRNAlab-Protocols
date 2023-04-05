Cell Fractionation and RNA Recovery
================================================================================
Description: Extract RNA from Nucleus and Cytoplasm

  ### Solutions and Buffers ###
  
  ◦ 1X Phosphate-buffered saline pH 7.4  
  ◦ 25:24:1 Phenol Chloroform Isoamyl Alcohol ([PCA](https://www.thermofisher.com/order/catalog/product/15593031#/15593031), wear eye protection and PPE)   
  ◦ 100 mM DTT  
  ◦ Triton X-100  
  ◦ 20 % SDS  
  ◦ 5M NaCl  
  ◦ 500 mM EDTA  
   
* **10X Low Salt Buffer**   
  ◦ 200 mM Tris pH 8.0  
  ◦ 100 mM KCl  
  ◦ 15 mM MgCl<sub>2</sub>
  
* **5X Proteinase K Digestion Buffer**  
  ◦ 200 mM Tris pH 8.0  
  ◦ 1 M NaCl    
  ◦ 100 mM EDTA   
  
 ### Other materials and reagents ### 
  * Confluent cells (for HEK293T cells, plate 500K cells each in 2 10 cm dishes and grow up 2 days)
  * [RNase Inhibitor](https://www.promega.com/products/rna-analysis/rnase-inhibitor-rna-protection/rnasin-ribonuclease-inhibitor/?catNum=N2515#overview)
  * 20 mg/mL [Proteinase K](https://www.thermofisher.com/order/catalog/product/EO0491#/EO0491)
  * [20 mg/ml glycogen](https://www.thermofisher.com/order/catalog/product/R0561#/R0561)
  
     
Equipment Required:
--------------------------------------------------------------------------------
  * Cell culture incubator and hood
  * 37 °C water bath or heat block for 15 ml conical tubes
  * Centrifuge equipped with high-speed rotor for required tubes
  <br/>_Note: ensure your conical tubes can withstand necessary g-forces._
  * Fume hood for work with phenol

Protocol:
--------------------------------------------------------------------------------
### Part 1: Cell Lysis and Fractionation (20 minutes) ###

**1.** Prepare ice-cold Lysis Buffer with 1X Low Salt Buffer, 1 mM DTT and 0.1 % Triton.<br/>
_Note: 2.5 mL per 10 cm dish or 500 ul per 6-well plate well._<br/>
_Optional: 800 U/mL RNase Inhibitor_

**2.** Wash cells twice in 0.5 growth volumes of PBS. <br/>
_Note: Crosslinked or chemically treated cells can be lysed directly on plate after treatment._

**3.** Scrape cells into 2.5 mL of the prepared cold 1X Lysis Buffer. Incubate for 10 minutes at 4 °C.
    
**4.** Pellet nuclei at 1500 x g for 5 minutes at 4 °C. <br/>
While spinning, prepare Wash Buffer with 1X Low Salt Buffer and 1 mM DTT<br/>
_Note: Need volume equal to original lysis amounts._

**5.** Carefully remove the cytoplasmic lysate into a new tube on ice. <br/>

**6.** Wash nuclei with Wash Buffer and pellet again 1500 x g for 5 minutes at 4 °C.<br/>
While spinning, prepare PK Buffer with 1X Proteinase K Digestion buffer, 1.5 % SDS, and 0.5 mg/ml Proteinase K

### Part 2: Protein Digestion (2 hours) ###

**7.** Resuspend washed nuclear pellet in PK Buffer and set at room temperature.<br/>
_Note: 2.5 mL per 10 cm dish or 500 ul per 6-well plate well._

**8.** To the cytoplasmic lysate, adjust buffer with:  
  ◦ 0.04 volumes 5M NaCl _(100 µl for 2.5 mL)_  
  ◦ 0.08 volumes 20 % SDS _(200 µl for 2.5 mL)_  
  ◦ 0.05 volumes 500 mM EDTA _(125 µl for 2.5 mL)_  
  ◦ 0.03 volumes of 20 mg/mL Proteinase K _(75 µl for 2.5 mL)_

**9.** Incubate both lysates at 37 °C with shaking for 2 hours.

### Part 3: PCA Extraction (60 minutes, fume hood) ###

**10.** Extract RNA (aqueous layer) twice with 1 volume of PCA and twice with 1 volume chloroform.  
  For each extraction:
  1.  Shake mix vigorously
  2.  Spin at 15,000 x g for 10 minutes
  3.  Save (top) aqueous layer

### Part 4: Isopropanol precipitation of modified RNAs (30 minutes) **

**11.** Add 1/25 volume of 5M NaCl and 1/1000 volumes of 20 mg/ml glycogen to each sample and mix.

**12.** Add 1 volume isopropanol and vortex 15 seconds. Incubate at room temperature for 10 minutes.

**13** Pellet RNA precipitate at 15-20,000 x g for 10 minutes. Discard supernatant.

**14.** Wash with 75% ethanol, spin at 7,500 x g for 5 minutes, discard supernatant and air dry pellet for 5 minutes.
<br/>_Note: Pellets in ethanol can be stored long term at -20 °C, just remember to DNase treat._

**15.** Resuspend in 44/88 µl of nuclease-free water in preparation for [DNase treatment](../General/TURBO-DNase.md).<br/>

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="../General/TURBO-DNase.md">
DNase treatment</a>

</p> <a href="../Mutational-Profiling/MaP-RT-SSII.md">
MaP with Marathon RT</a>

</p> <a href="../NGS/Second-Strand-Synthesis.md">
Second-Strand Synthesis</a>

</p> <a href="../NGS/Two-Step-PCR-Library.md">
2-step PCR library generation </a>

</details>
