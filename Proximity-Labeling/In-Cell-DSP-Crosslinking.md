In-cell Protein-Protein Crosslinking with DSP _(Work in Progress)_
================================================================================
Description: DSP `(dithiobis[succinimidylpropionate])` crosslinks proximal free amines in cells.<br/>
Crosslinks are cleavable by reduction.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [Stable cell line generation by lentiviral infection](../Lentivirus-Stables/virus-production-HEK293T.md)

Materials:
--------------------------------------------------------------------------------
### Day 1-3
  * Cell line stably expressing bait protein or control
  * Cell culture reagents (per your chosen cell line)
    
### Day 3 or 4
  * 1X PBS pH 7.4 _Note: It may be worth testing higher pH PBS to improve DSP reactivity_
  * 25 mM [DSP](https://www.thermofisher.com/order/catalog/product/A35393#/A35393) in DMSO (made immediately before use)
  * **Quenching Solution**  
    ◦ 20 mM Tris pH 7.5  
    ◦ 5 mM L-Cysteine  
  * Liquid nitrogen for freezing large cell pellets

Equipment Required:
--------------------------------------------------------------------------------
### Day 1-4

  * Cell culture incubator (37 °C with 5% CO<sub>2</sub> usually)
  * Microcentrifuge (for tubes) or larger centrifuge (for conicals) 

<br/>

<!-- Use <br/> to fill in first page -->
___
Protocol:
--------------------------------------------------------------------------------
### Day 1
**1.** Plate cell lines at ~30,000 cells/cm<sup>2</sup> (about 150,000 cells/mL)  
  * If preparing for western validation, each test sample needs at least a 6-well.  
  * For Mass Spec preparation, each cell line needs at least 5 15-cm dishes (10 total for 2 replicates).

### Day 3 or 4

**2.** Wash cells twice in a half growth volume of PBS (for example 10 mL for a 15 cm dish).<br/>
Suspension cells will have to be pelleted.
  
**3.** Cover cells in 0.5 growth volumes PBS. Carefully mix in DSP to a final concentration of 0.5 mM.<br/>
Uncrosslinked samples treated with DMSO are appropriate when optimizing.<br/>
_1 mg of DSP in 100 µl of DMSO makes a 25 mM stock solution enough to treat 1 15 cm dish._

**4.** Incubate cells at 37 °C for 30 minutes.<br/>
_Note: other protocols use room temperature or ice for 2 hours. Worth testing._ 
  
**5.** Carefully aspirate media.<br/>
Quench excess DSP with 0.5 growth volume of Quenching Solution for 5 minutes at room temperature.<br/>
_Note: This may cause adherent cells to detach, requiring pelleting. May be an unnecessary step._

**6.** Carefully aspirate Quenching Solution and wash cells with 0.5X growth volume of PBS.<br/>
_Note: Cells are being harvested, no need to use cell culture grade PBS for washing steps._<br/>
_To process 15 cm dishes, don't aspirate, just dump media and washes into waste container._
  
**7.** Scrape cells with ice-cold PBS and combine like samples into single tube.  
  * For small plate wells, pipetting a 0.5X growth volume of PBS dislodges cells.<br/>
  Move to eppendorf tubes on ice.  
  * For 15 cm dishes, scrape with 3 mL of cold PBS and combine into a 50 mL conical tube on ice.<br/>
  Collect remaining cells with shared 10 mL wash of cold PBS for plates of one sample and combine.<br/>
  Example: Process 5 15 cm dishes of one sample with 3 mL scrapes + a final 10 mL shared wash. <br/>
    This would result in a half-full 50 mL conical for the sample.
  
**8.** Pellet cells at 500xg for 10 minutes. Discard supernatant and freeze cell pellets (or proceed to lysis).
  
  *Note:For cell pellets for Westerns in eppendorf tubes, pellets can be stored directly at -20 °C.*<br/>
  *For pellets less than 1 mL of bed volume in conical tubes, place directly into -80 °C.*<br/>
  *Pellets larger than 1 mL should be snap-frozen in liquid nitrogen before moving to -80 °C.* 
 
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>
  
</p> <a href="HaloTag-Mammalian-Lysis.md">
Whole Cell Lysis</a>

</p> <a href="../General/BCA-Assay.md">
BCA protein quantification</a>

</p> <a href="../General/Western-Blotting.md">
Western Validation</a>

</p> <a href="./HaloTag-Pulldown.md">
HaloTag Pulldown</a>

</p> <a href="../Mass-Spec-Prep/Bead-Reduction-Elution.md">
Rapigest reduction, alkylation, and Trypsin Digestion</a>

</p> <a href="../Mass-Spec-Prep/C18-Column-Cleanup.md">
C18 Column</a>
  
</p> <a href="../Mass-Spec-Prep/Ethyl-Acetate-Cleanup.md">
Ethyl Acetate Cleanup</a>  
  
</p> <a href="../Mass-Spec-Prep/Peptide-Quant.md">
Peptide Quantification</a>

</details>

<details>
  <summary>More Info</summary>
  
  <a href="https://assets.thermofisher.com/TFS-Assets/LSG/manuals/MAN0017093_2162635_Pierce_DSP_UG.pdf">
DSP Basic Protocol</a>  

</details>
