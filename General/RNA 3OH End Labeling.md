RNA End Labeling
================================================================================
Description: Couples diol oxidation and hydrazide labeling to add molecules to RNA 3' Ends

[Go To Protocol](#protocol)

Materials:
--------------------------------------------------------------------------------
  * Target RNA (with 3' hydoxyls, 100 µM)
  * 1 M NaOAc pH 4.5
  * 1 M NaOAc pH 6 (add 128 µl of 6.25 N NaOH to 3 ml of 1M NaOAc pH 5.2)
  * 40 % glycerol
  * 1 M Tris pH 8.5
  * 250 mM NaIO<sub>4</sub>
    * *Dissolve 0.053 g of solid [NaIO<sub>4</sub>](https://www.fishersci.com/shop/products/sodium-periodate-99-8-acs-reagent-thermo-scientific/AC419610050) per mL of water.*<br/>
      *This solution can be stored long-term in the dark in aliquots at -80 °C.*<br/>
      *Note: This is a reactive compound, wear a mask when weighing solid*
  * 10 mM hydrazide-containing label
    * *For example, dissolve 1 mg of [Cy3-hydrazide](https://www.lumiprobe.com/p/cy3-hydrazide) in 184 µL of DMSO.*<br/>
      *This solution can be stored long-term in the dark in aliquots at -80 °C.*
  * SPRI beads

Equipment Required:
--------------------------------------------------------------------------------
  * Magnetic rack
  * Fume Hood

<br/><br/><br/><br/><br/><br/><br/><br/>

<!-- Use <br/> to fill in first page -->
  
  
___
Protocol:
--------------------------------------------------------------------------------
**1.** Mix following components in the fume hood:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | RNA | 100 µM | **20**  µL | 
  | NaOAc pH 4.5 | 1 M | **1**  µL |
  | NaIO<sub>4</sub> | 250 mM | **1**  µL |
  || **Total** | **22** µL |
  
  <!-- : in the pipes specify justification -->
  <!-- **X** bolds the inside -->
  
**2.** Incubate samples at room temperature for 90 minutes in the dark.<br/>
Periodate will break the bond between terminal 2'-3' ribose diol and leave behind aldehydes. 

**3.** Add 1 µL of 40 % Glycerol to quench periodate.

**4.** Add 7 µL of Tris pH 8.5 to raise pH to more neutral level.
 
**5.** Remove reaction buffer through purification with [SPRI beads](../NGS/SPRI-beads.md).<br/>
Elute in 20 µL of nuclease-free water. <br/>
*Note: If your RNA is small, be sure to use correct bead amount and isopropanol additive.*<br/>
*Note: Reaction products will be ~ 500 µM formaldehyde, dispose in appropriate liquid waste*

**6.** Mix following components in the fume hood:<br/>
*Note: hydrazide at this concentration (< 1 % solution) is not considered hazardous.*

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Oxidated RNA product| ~ 100 µM | **20**  µL | 
  | NaOAc pH 6 | 1 M | **2.5**  µL |
  | hydrazide-label | 10 mM | **2.5**  µL |
  || **Total** | **25** µL |
  
**7.** Incubate samples at room temperature for 2 hours (in the dark if fluorescent label).<br/>
Hydrazide reacts with the proximal aldehydes generated in the first reaction.

**8.** Remove reaction buffer through purification with [SPRI beads](../NGS/SPRI-beads.md).<br/>
Elute in 20 µL of nuclease-free water (and store in amber tubes if fluorescent). <br/>
*Note: If your RNA is small, be sure to use correct bead amount and isopropanol additive.*<br/>
