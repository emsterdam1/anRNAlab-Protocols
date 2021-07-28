Streptavidin Pull-down of MiniTurbo-labeled Proteins
================================================================================
Description: Proteins labeled with biotin by miniTurbo are captured on a streptavidin matrix.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [miniTurbo biotinylation](./miniTurbo-biotinylation.md)
* [RIPA cell lysis](./Whole-Cell-Lysis-RIPA.md)

Materials:
--------------------------------------------------------------------------------

### Solutions and Buffers ###

  * **1X Mass Spec RIPA lysis buffer**  
    ◦ 50 mM HEPES pH 7.5 (HEPES is substituted instead of Tris for MS compatibility)  
    ◦ 150 mM NaCl  
    ◦ 2 mM EDTA (Metal chelator)  
    ◦ 0.1% SDS  
    ◦ 1% Nonidet-P40 (or IGEPAL CA-630)  
    ◦ 0.2% Sodium Deoxycholate (some formulations have up to 0.5%)  
    ◦ 10% Glycerol (for protein solubility and stability)  

  * **Wash Buffer 1 (WB1)**  
    ◦ 2% SDS  
    
  * **Wash Buffer 2 (high salt, WB2)**
    ◦ 50 mM HEPES pH **7.5**  
    ◦ 500 mM NaCl  
    ◦ 1 mM EDTA  
    ◦ 1% Triton-X 100
    ◦ 0.1% Sodium Deoxycholate
 
   * **Wash Buffer 3 (high detergent, WB3)** 
    ◦ 50 mM HEPES pH **8.0**  
    ◦ 250 mM LiCl  
    ◦ 1 mM EDTA  
    ◦ 0.5% Nonidet-P40 (or IGEPAL CA-630)
    ◦ 0.5% Sodium Deoxycholate
    
   * **Wash Buffer 4 (low salt, WB4)** 
    ◦ 50 mM HEPES pH **7.5**  
    ◦ 50 mM NaCl  
    
  * 50 mM Ammonium bicarbonate (ABC, NH<sub>4<sub/>HCO<sub>3<sub/>)<br/>
  _Note: Make ABC in mass spec grade water and store in glass up to 2 months at room temperature_
  
<br/>

### Other materials and reagents ### 

  * cell lysate (10 mg total protein per replicate)
  * streptavidin-conjugated [sepharose beads](https://www.sigmaaldrich.com/US/en/product/sigma/ge17511301) 70% slurry
  * _optional: 26-gauge needles and 1 mL syringes_
  
Equipment Required:
--------------------------------------------------------------------------------
  
  * tube rotator

<br/><br/><br/><br/>
<!-- Use <br/> to fill in first page -->

___
Protocol:
--------------------------------------------------------------------------------
### Day 1

**1.** For each sample, aliquot 10 mg of total protein in 8 mL of RIPA lysis buffer on ice.<br/>
  _Note: Make 2 replicates per sample, ideally biological replicates_
    
**2.** Suspend streptavidin beads in 4 volumes of RIPA buffer and spin at 400 x g for 2 minutes at 4 °C.<br/>
  _Start with ~60 µl of bead slurry per pulldown._ 
  
**3.** Aspirate the supernatant, leaving a 0.5 cm layer of RIPA above the beads. Wash in RIPA 2 more times.<br/>
  _If you are worried about bead loss, a 26-gauge needle can optionally be used to aspirate._

**4.** Resuspend beads as a 50% slurry in RIPA (a total bead+RIPA volume of ~85 µl per pulldown).

**5.** Add 60 µl of the 50% slurry to each 8 mL sample. <br/>
  Capture biotinylated proteins with rotation overnight (16 hours) at 4 °C.

### Day 2

**6.** Re-capture beads at 400 x g for 2 minutes at 4 °C. Save the supernatant in a separate tube.

**7.** Resuspend beads in 500 µl of RIPA and move to a 1.7 mL eppendorf tube.<br/>
  Rinse the 15 mL once more with 500 µl of RIPA and add to 1.7 mL tube as well.

**8.** Re-capture beads at 400 x g for 2 minutes at 4 °C and discard supernatant.

**9.** Wash beads in 1 mL of wash buffer 1 (WB1), rotating 5 minutes and re-capturing at room temperature.

**10.** Repeat the wash step 1X with WB1, 1X with WB2, 1X with WB3, and 1X with WB4.
  
**11.** Wash beads 3 more times in 50 mM ABC, without rotations but capturing at 400 x g for 5 minutes.<br/>
  _Retain 10% of the last resuspension for analysis. Final pellet is ready for on-bead digestion._
    
  
 
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>More Info</summary>
  
  <a href="https://doi.org/10.1083/jcb.201112098">
Original BioID approach</a>  

</details>
  
<details>
  <summary>Next Steps</summary>

</p> <a href="../Mass-Spec-Prep/On-Bead-Digestion.md">
Rapigest reduction, alkylation, and Trypsin Digestion</a>

</p> <a href="../Mass-Spec-Prep/C18-Column-Cleanup.md">
C18 Column</a>
  
</p> <a href="../Mass-Spec-Prep/Ethyl-Acetate-Cleanup.md">
Ethyl Acetate Cleanup</a>  
  
</p> <a href="../Mass-Spec-Prep/Peptide-Quant.md">
Peptide Quantification</a>

</details>
