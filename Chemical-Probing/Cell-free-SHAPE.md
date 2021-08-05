Cell-free RNA structure probing with SHAPE
================================================================================
Description: SHAPE reagents label 2'OH of flexible unbound RNA nucleotides.

--------------------------------------------------------------------------------
  ### Solutions and Buffers ###
  
  * 1X Phosphate-buffered saline pH 7.4
  * 25:24:1 Phenol Chloroform Isoamyl Alcohol ([PCA](https://www.thermofisher.com/order/catalog/product/15593031#/15593031), wear eye protection and PPE)
  
  * **2X Cell-Free Lysis Buffer** 
    ◦ 80 mM Tris pH 8.0    
    ◦ 50 mM NaCl    
    ◦ 12 mM MgCl<sub>2</sub>  
    ◦ 2 mM CaCl<sub>2</sub>    
    ◦ 500 mM Sucrose    
    ◦ 1 % Triton X-100    
  
  * **2X Proteinase K Digestion Buffer** _Note: Keep 2X at room temperature._   
    ◦ 80 mM Tris pH 8.0  
    ◦ 400 mM NaCl    
    ◦ 40 mM EDTA  
    ◦ 3 % SDS
    
  * **1.11X Folding Buffer**  
    ◦ 111 mM HEPES pH 8.0    
    ◦ 111 mM NaCl      
    ◦ 5.55 mM MgCl<sub>2</sub>    
  
 ### Other materials and reagents ### 
  * Confluent cells (for HEK293T cells, plate 500K cells each in 2 10 cm dishes and grow up 2 days)
  * 10X stock of SHAPE reagent. _Note: Store reagents dry and dilute in DMSO immediately before use._  
    ◦ For a 10X stock of [5NIA](https://www.sigmaaldrich.com/catalog/product/aldrich/s428396) in DMSO, 5.2 mg/100 µl yields 250 mM  
    ◦ a 10X stock of [1M7](https://www.sigmaaldrich.com/US/en/product/aldrich/908401) is 100 mM, [NAI](https://www.sigmaaldrich.com/catalog/product/mm/03310) and [NAI-N3](https://www.sigmaaldrich.com/catalog/product/aldrich/913812) is 1 M 
  * [RNase Inhibitor](https://www.promega.com/products/rna-analysis/rnase-inhibitor-rna-protection/rnasin-ribonuclease-inhibitor/?catNum=N2515#overview)
  * [High concentration DNase I](https://www.sigmaaldrich.com/US/en/product/roche/04716728001?context=product)
  * 20 mg/mL [Proteinase K](https://www.thermofisher.com/order/catalog/product/EO0491#/EO0491)
  * [PD-10](https://www.sigmaaldrich.com/US/en/product/sigma/ge17085101) G-25 Sephadex desalting columns
  * [20 mg/ml glycogen](https://www.thermofisher.com/order/catalog/product/R0561#/R0561)
  
     
Equipment Required:
--------------------------------------------------------------------------------
  * Cell culture incubator and hood
  * 37 °C water bath or heat block for 15 ml conical tubes
  * Centrifuge equipped with high-speed rotor for 15 ml and 50 ml conical tubes
  <br/>_Note: ensure your conical tubes can withstand necessary g-forces._
  * Fume hood for work with phenol

Protocol:
--------------------------------------------------------------------------------
### Part 1: Cell Lysis and Fractionation (20 minutes) ###

**1.** Prepare ice-cold 1X Cell-Free lysis buffer with 800 U/mL RNase Inhibitor and 450 U/mL of DNase I.

**2.** Wash cells (in 10 cm dishes) twice in 5 mL PBS. _Note: Suspension cells will have to be pelleted._

**3.** Scrape cells into 2.5 mL of the prepared cold 1X Cell-Free lysis buffer. Incubate for 5 minutes at 4 °C.
    
**4.** Pellet nuclei at 2250 x g for 3 minutes at 4 °C. Carefully separate the cytoplasmic lysate and nuclear pellet.

### Part 2: Protein Digestion (60 minutes, fume hood) ###

**5.** To the cytoplasmic lysate, adjust buffer with:  
  ◦ 0.04 volumes 5M NaCl _(100 µl for 2.5 mL)_  
  ◦ 0.08 volumes 20 % SDS _(200 µl for 2.5 mL)_  
  ◦ 0.05 volumes 500 mM EDTA _(125 µl for 2.5 mL)_  
  ◦ 0.03 volumes of 20 mg/mL Proteinase K _(75 µl for 2.5 mL)_

**6.** Resuspend the nuclear pellet in 2.5 mL 1X Proteinase K Digestion buffer + 0.5 mg/ml Proteinase K.

**7.** Incubate both lysates at room temperate with shaking for 45 minutes.<br/>_Note: Start equlibrating the PCA (step 8) and PD-10 columns (step 10) during this incubation._

### Part 3: PCA Extraction (60 minutes) ###

**8.** Equilibrate PCA with a total of 8 volumes of 1.1X folding buffer.

**9.** Extract RNA (aqueous layer) twice with 1 volume of equlibrated PCA and twice with 1 volume chloroform.  
  For each extraction:
  1.  Shake mix vigorously
  2.  Spin at 15,000 x g for 10 minutes
  3.  Save (top) aqueous layer

### Part 4: Buffer Exchange (30 minutes) ###

**10.** Exchange the final extractions into 1.1x folding buffer over desalting columns.
  <br/>Each column accepts up to 2.5 mL of input material with the following gravity flow [procedure](https://cdn.cytivalifesciences.com/dmm3bwsv3/AssetStream.aspx?mediaformatid=10061&destinationid=10016&assetid=11531):
  1.  Equilibrate columns 5 times with 5 mL of 1.1X folding buffer
  2.  Add sample and allow full entry into column, discard flowthrough
  3.  Place a tube under columns for collection and elute with 3.5 mL of 1.1X folding buffer
  4.  Combine like RNA samples together

### Part 5: RNA Refolding (20 minutes) ###

**11.** Encourage native refolding of RNAs through incubation for 20 minutes at 37 °C.

### Part 6: SHAPE modification (15-45 minutes) ###

**12.** Split RNA samples into two halves:<br/> add one half to 1/9 volume of 10X SHAPE reagent (treated) and the other half to 1/9 volume of DMSO (untreated). <br/> _Note: It is important to add the larger volume of RNA to the smaller volume of reagent for proper mixing._

**13.** Incubate RNA for at 37 °C for multiple reagent half-lives (for example 10 minutes with 5NIA).<br/>_Note: Reagents with long half-lifes should be quenched with DTT (or similar reagent) after 30 minutes._

### Part 7: Isopropanol precipitation of modified RNAs (30 minutes) **

**14.** Add 1/25 volume of 5M NaCl and 1/1000 volumes of 20 mg/ml glycogen to each sample and mix.

**15.** Add 1 volume isopropanol and vortex 15 seconds. Incubate at room temperature for 10 minutes.

**16** Pellet RNA precipitate at 15-20,000 x g for 10 minutes. Discard supernatant.

**17.** Wash once with 75% ethanol, spin at 7,500 x g for 5 minutes, discard supernatant and air dry pellet for 5 minutes.
<br/>_Note: Pellets in ethanol can be stored long term at -20 °C, just remember to DNase treat._

**18.** Resuspend in 44 µl of nuclease-free water in preparation for [DNase treatment](../General/TURBO-DNase.md).<br/>

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
