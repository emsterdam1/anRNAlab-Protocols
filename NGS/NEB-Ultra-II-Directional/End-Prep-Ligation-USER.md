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
    
Equipment Required:
--------------------------------------------------------------------------------
  * Fume hood
  * High-speed microcentrifuge
  * 50 °C heat block (ideally with rotation)

<br/><br/>
___
Protocol:
--------------------------------------------------------------------------------

**Part 1: End Prep and dA tailing**<br/>_Note: MaP products only require half-reactions for all steps._

**1.** Dilute second strand synthesis product in 50 µL of water.

**2.** Add 7 µL of End Prep Reaction Buffer and 3 µL of End Prep Enzyme Mix.<br/>Pipette mix each sample thoroughy and perform the following thermocycles:<br/>
_Note: set heated lid > 75 °C._

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


**4.** Carefully remove (top) aqueous phase and store in new tubes on ice until ready to precipitate.<br/>

  | Component | Quantity | 
  | ---------: | :---------- |
  | End Prepped DNA | **60**  µL | 
  | Diluted Adaptor | **2.5**  µL |
  | Ligation Enhancer | **1**  µL |
  | Ligation Master Mix | **30**  µL |
  | **Total** | **93.5** µL |
  
_Note: Initial aqueous phases can be stored on ice for 2-3 hours or long-term at -80 °C._<br/>
_This fraction contains uncrosslinked (unbound) RNA._

<br/>

**Part 2: Clean crosslinked RNP interface (40 minutes)**

**5.** Discard (bottom) organic phase (in appropriate waste container), retaining only the interface.<br/>
_Note 1: "Pierce" the interface from one side of the tube before withdrawing liquid from the bottom_<br/>
_Note 2: The discarded phenol organic phase could be saved as an unbound protein fraction._

**6.** Clean interface with two more 1 mL Trizol/ 200 µL chloroform separations, retaining interface.

**7.** To the final interface, add 9 volumes of 100% methanol (~900 µL). Vortex 15 seconds.

**8.** Pellet interface at 14,000 x g for 10 minutes at 10 °C.

**9.** Discard supernatant and <ins>repeat</ins> methanol wash once.<br/>
_Note: Discard methanol supernatant in proper waste container._

<br/>

**Part 3: Digest crosslinked proteins (2 hours)**

**10.** To cleaned interface, add 300 µL Proteinase K buffer + 0.5 mg/ml Proteinase K enzyme.<br/>
_Note: If enzyme not RNA-grade, pre-incubate with buffer at 50 °C for 15 minutes to remove RNase activity._

**11.** Incubate samples at 50 °C (shake at 400 rpm) for 1.5 - 2 hours to digest crosslinked proteins.

<br/><br/>

**Part 4: Prepare bound RNA fraction for precipitation (20 minutes)**

**12.** Add 300 µL PCA to each sample, vortex 15 seconds, and spin at 12,000 x g for 15 minutes at 10 °C.

**13.** Transfer (top) aqueous phase to a new tube and add 50 µL of 3M sodium acetate

<br/>

**Part 5: Isopropanol precipitation of bound and unbound RNAs (30 minutes)**

_You can retrieve the unbound RNAs from storage and precipitate together with the bound RNAs._<br/>
_Bound and unbound RNA fractions will be at ~350 and ~450 µL, respectively._

**14.** To each RNA fraction, add 600 µL isopropanol and vortex 15 seconds 

**15.** Incubate samples at room tempurature for 10 min.

**16.** Pellet RNA precipitate at 15,000 x g for 10 minutes. Discard supernatant.<br/>
_Note: You can spin at higher speeds, but do so at ~15 °C to mitigate heating._

**17.** Add 900 µL 100% ethanol, spin 5 minutes, and discard ethanol. 

**18.** Wash once more with 70% ethanol at 7,500 x g.

**19.** Remove final wash carefully and air dry pellet for 5 minutes.<br/>
_Note: Spin down residual ethanol and remove with a small volume pipette._

**20.** Resuspend in 44 µl of nuclease-free water in preparation for [DNase treatment](../General/TURBO-DNase.md).<br/>
_Note: DNase treatment is not necessary if RNA is not from a cell or tissue source._
  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>
  
</p> <a href="../Mutational-Profiling/MaP-RT-Marathon.md">
MaP with Marathon RT</a>

</p> <a href="../NGS/Second-Strand-Synthesis.md">
Second-Strand Synthesis</a>

</p> <a href="../NGS/Two-Step-PCR-Library.md">
2-step PCR library generation </a>

</details>

<details>
  <summary>More Info</summary>
  
  <a href="https://doi.org/10.1038/s41587-018-0001-2">
Original OOPS paper</a>  
<br/>
  <a href="https://doi.org/10.1038/s41596-020-0344-2">
Published OOPS protocol</a> 

</details>
