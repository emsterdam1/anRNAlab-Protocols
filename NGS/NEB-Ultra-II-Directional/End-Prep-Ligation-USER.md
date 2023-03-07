End Prep, Adaptor Ligation, and USER Treatment
================================================================================
Description: cDNA fragment libraries are treated to enable hairpin adaptor ligation,<br/>and U bases are excised to create directional DNA library templates.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [Directional Second Strand Synthesis](./Directional-Second-Strand-Synthesis.md)

Materials:
--------------------------------------------------------------------------------
  _Note: All NEB modules are included in the [NEBNext® Ultra™ II Directional RNA Library Prep Kit for Illumina®](https://www.neb.com/products/e7760-nebnext-ultra-ii-directional-rna-library-prep-kit-for-illumina#Product%20Information)_
  * Purified cDNA fragments
  * **[NEBNext® Ultra™ II End Repair/dA-Tailing Module](https://www.neb.com/products/e7546-nebnext-ultra-ii-end-repair-da-tailing-module#Protocols,%20Manuals%20&%20Usage)**
    * End Prep Reaction Buffer
    * End Prep Enzyme Mix
  * 15 µM NEBNext Nextera Adapter ([ARL400](../../ARL-primers.csv))
  * [NEBNext® Adaptor Dilution Buffer](https://www.neb.com/products/b1430-nebnext-adaptor-dilution-buffer#Product%20Information)
  * **[NEBNext® Ultra™ II Ligation Module](https://www.neb.com/products/e7595-nebnext-ultra-ii-ligation-module#Protocols,%20Manuals%20&%20Usage)**
    * Ligation Enhancer
    * Ligation Master Mix
  * **[USER® Enzyme](https://www.neb.com/products/m5505-user-enzyme#Product%20Information)**
    
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler

<br/><br/><br/><br/>
___
Protocol:
--------------------------------------------------------------------------------

**Part 1: End Prep and dA tailing**<br/>_Note: MaP products only require half-reactions for all steps._

**1.** Dilute second strand synthesis product in 50 µL of water.

**2.** Add 7 µL of End Prep Reaction Buffer and 3 µL of End Prep Enzyme Mix.<br/>Mix each sample thoroughy and perform the following thermocycles:<br/>

  | Step | Temp | Time | Action |
  | ---------: | :--------: | :---------: |:---------: |
  | **i** | **20 °C** | **30:00** | **End Repair** |
  | **ii** | **65 °C** | **30:00** | **dA-Tailing** |
  | **iii** | **10 °C** | **hold** | **wait** |
  
**Part 2: Adaptor Ligation**
  
**3.** Dilute Adaptor on ice in Adaptor Dilution Buffer according to input RNA amount.<br/>_Note: Treat MaP input as 10-fold less starting material_<br/>

  | Total RNA Input | Dilution Factor |
  | ---------: | :--------: |
  | **1,000 ng - 250 ng** | **1/5 dilution** |
  | **249 ng - 100 ng** | **1/25 dilution** |
  | **99 ng - 10 ng** | **1/100 dilution** |


**4.** Combine the following reagents on ice:

  | Component | Quantity | 
  | ---------: | :---------- |
  | End Prepped DNA | **60**  µL | 
  | Diluted Adaptor | **2.5**  µL |
  | Ligation Enhancer | **1**  µL |
  | Ligation Master Mix | **30**  µL |
  | **Total** | **93.5** µL |
  
**5.** Mix well and incubate for 15 minutes at 20 °C. 

**Part 3: USER removal of U-containing DNA**

**6.** Add 3 µL USER enzyme to the mixture and incubate for 15 minutes at 37 °C.

**7.** Purify and size select desired cDNA with [SPRI beads](../SPRI-beads.md).<br/>
_Note: cDNA is single-stranded after USER treatment (half-size, 0.9X for everything)_<br/>
_The product can be amplified in a gene-specific manner or immediately barcoded (contains i7 and i5 sequences)_

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="../NGS/Two-Step-PCR-Library.md">
2-step PCR library generation </a>

</details>
