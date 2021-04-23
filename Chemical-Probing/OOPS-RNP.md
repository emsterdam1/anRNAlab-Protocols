Orthogonal Organic Phase Separation (OOPS) of bound RNA
================================================================================
Description: Crosslinked ribonucleoprotein (RNP) complexes end up in the interphase of organic phase separation approaches.<br/>
This fact enables easy separation of protein-crosslinked and uncrosslinked RNA.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [In-cell crosslinking with SDA](./SDA-Xlinking.md)

Materials:
--------------------------------------------------------------------------------
  * Crosslinked cells
  * [Trizol](https://www.thermofisher.com/order/catalog/product/15596026#/15596026) lysis reagent
  * Chloroform
  * 100% and 70% ethanol
  * 100% methanol
  * **Proteinase K lysis buffer**
    * 10 mM Tris-HCl pH 8
    * 10 mM EDTA (Metal chelator)
  * 20 mg/ml [Proteinase K](https://www.thermofisher.com/order/catalog/product/25530049#/25530049)
  * [Acid PCA](https://www.thermofisher.com/order/catalog/product/AM9722#/AM9722) (phenol:chloroform:isoamyl alcohol 125:25:1)<br/>
  _Note: Acid phenol is better at separating RNA, but normal formulations of PCA and salts are acceptable._
  * [3M Sodium Acetate](https://www.fishersci.com/shop/products/sodium-acetate-3m-aq-soln-ph-4-5-autoclaved/AAJ61288EQE) pH 4.5
  * Optional for low concentrations: [glycogen](https://www.thermofisher.com/order/catalog/product/10814010#/10814010)
  
Equipment Required:
--------------------------------------------------------------------------------
  * Fume hood
  * High-speed microcentrifuge
  * 50 °C heat block (ideally with rotation)

___
Protocol:
--------------------------------------------------------------------------------

**Part 1: Extract unbound RNA fraction (40 minutes)**

**1.** Homogenize cells (**all steps assume 1 mL Trizol per sample**) and set 5 minutes at room temperature.

**2.** Add 200 µL of chloroform to each sample, vortex mix for 15 seconds.
  
**3.** Separate phases at 12,000 x g for 15 minutes at 4 °C.

**4.** Carefully remove the (top) aqueous phase and store in new tubes on ice until ready to precipitate.<br/>
_Note: Initial aqueous phases can be stored on ice for 2-3 hours or long-term at -80 °C._<br/>
_This fraction contains uncrosslinked (unbound) RNA._

<br/>

**Part 2: Clean crosslinked RNP interface (40 minutes)**

**5.** Discard (bottom) organic phase (in appropriate waste container), retaining only the interface.<br/>
_Note 1: "Pierce" the interface from one side of the tube before withdrawing liquid from the bottom_<br/>
_Note 2: The discarded phenol organic phase could be saved as an unbound protein fraction._

**6.** Clean up the interface first with two subsequent 1 mL Trizol separations, retaining interface each time.

**7.** To the final interface, add 9 volumes of 100% methanol (~900 µL). Vortex 15 seconds.

**8.** Pellet interface at 14,000 x g for 10 minutes (4 °C or room temp). 

**9.** Discard supernatant and <ins>repeat</ins> methanol wash once.

<br/>

**Part 3: Digest crosslinked proteins (2 hours)**

**10.** To cleaned interface, add 300 µL Proteinase K buffer + 0.5 mg/ml Proteinase K enzyme.<br/>
_Note: If enzyme not RNA-grade, pre-incubate with buffer at 50 °C for 15 minutes to remove RNase activity_

**11.** Incubate samples at 50 °C (shake at 400 rpm) for 1.5 - 2 hours to digest crosslinked proteins.

<br/>

**Part 4: Prepare bound RNA fraction for precipitation (20 minutes)**

**12.** Add 300 µL PCA to each sample, vortex 15 seconds, and spin at 12,000 x g for 15 minutes at 4 °C.

**13.** Transfer (top) aqueous phase to a new tube and add 50 µL of 3M sodium acetate

<br/>

**Part 5: Isopropanol precipitation of bound and unbound RNAs (30 minutes)**

_You can retrieve the unbound RNAs from storage and precipitate together with the bound RNAs._

**14.** To bound (~350 µL) and unbound (~450 µL) RNA fractions, add 600 µL isopropanol and vortex 15 seconds.

**15.** Pellet RNA precipitate at 15-20,000 x g for 10 minutes at 4 °C. Discard supernatant.

**16.** Add 900 µL 100% ethanol, spin 5 minutes, and discard ethanol. 

**17.** Repeat wash once with 70% ethanol and air dry pellet for 5 minutes.

**18.** Resuspend in 44 µl of nuclease-free water in preparation for [DNase treatment](../General/TURBO-DNase.md).<br/>
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
