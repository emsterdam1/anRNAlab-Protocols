Pulldown of target RNA with small number of biotinylated antisense DNA oligos
================================================================================
Description: A target RNA can be enriched from complex pools via antisense pulldown.
<br/>
The enriched RNA (or RNA complexes) are useful for a number of downstream applications.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [Trizol RNA Purification](../General/Trizol-RNA-Purification.md)

Materials:
--------------------------------------------------------------------------------
  * 100 mM DTT  
  * 20% SDS  
### Day 1
  * Input RNA  
  * 10 uM biotinylated DNA probes <br/>_(antisense for capture, sense for control)_


  * **Hybridization Buffer Stock (2X)**  
    ◦ 100 mM HEPES pH 7.5  
    ◦ 2 M NaCl  
    ◦ 4 M Urea  
    ◦ 12 mM EDTA  
    
### Day 2
  * [MyOne Streptavidin C1 Magnetic Beads](https://www.thermofisher.com/order/catalog/product/65001)
  * **Wash Buffer No Salt Stock (10X)**  
    ◦ 100 mM HEPES pH 7.4  
    ◦ 20 mM EDTA  
    ◦ 10 mM EGTA  
  * **Elution Buffer Stock (2X)**  
    ◦ 40 mM HEPES pH 8.0  
    ◦ 20 mM EDTA  
    ◦ 20 mM TCEP  
  
  
<!-- Using distinct bullet symbols with 2 spaces at end of each line makes a better formatted list -->
    

Equipment Required:
--------------------------------------------------------------------------------
### Day 2
* Overhead rotator 
* Magnetic rack for 1.5mL tubes
* Heat block/thermocycler


<br/><br/>
___
Protocol:
--------------------------------------------------------------------------------
### Day 1: 

**METHOD FORMATTING IN PROGRESS**

**1.** Dilute up to 4 ug of each RNA sample in 41.5 ul of nuclease-free water.

**2.** Add 5 ul of biotinylated probes to each RNA.<br/>
_Note: matched sense probes for each RNA sample are recommended as a control._
  
**2.** Create enough hybridization master mix for each RNA sample: 
  * 50 ul 2X hybrization stock
  * 2 ul of 100 mM DTT
  * 1.5 ul of 20% SDS

**3.** Combine 53.5 ul of master mix with each RNA sample (100 ul total).<br/>
Incubate hybridization reaction overnight (~16 hrs) at room temperature.

<details>
  <summary>Example**</summary>

** Expect roughly 75-80% loss from starting material. Modulate streptavidin bead amount if more RNA is used. For reference, in a pulldown from a MALAT1 T7 reaction, starting with ~6ug of RNA resulted in 800-900ng eluted MALAT1 RNA. 


* *Example:* 
 	1. *2uL of RNA in ddH20, 2ug RNA* 
  	2. *10uL 10mM biotinylated probe* 
  	3. *88uL 1x hybridisation buffer*
</details><br/>
3. Leave reaction benchtop and room temperature overnight. 
<br/>
### Day 2

#### Buffer prep and bead capture 

  1. Prepare 1x WB100, WB30, W10 with 2% SDS added freshly. Washes will be 500uL per wash. WB100 has 7x washes, WB30 has 1x wash, and WB10 has 2x washes. 
  2. Place WB10 and WB30 in a 42C heatbath at this time. 
  3. If input is required for control, remove 7-10uL from each reaction at this time and store at 4C. 
  4. Take the hybridisation reactions and add 25uL of MyOne T1 Streptavidin beads to each reaction. Vortex beads thoroughly before use. 
  6. Gently mix the beads + hybridisation reaction and leave on benchtop room temperature for **~2** hours.
<br/><br/>
#### Washing beads
  7. After incubation, place the tubes on a magrack. 
  8. **Remove and keep the supernatant. This is the flowthrough**
  9. Perform washes, 500µL each, room temp, with ~5 minutes of overhead rotation per wash: 
  		1. WB100 5x washes
  		2. **Transfer beads to new clean eppendorf tubes**
  		3. WB100 2x washes 
  		4. WB30 at 42C 1x wash
  		5. WB10 at 42C 1x wash; *during this time set the heatbath to 50C and place the remaining WB10 at 50C*
  		6. WB10 at 50C 1x wash. Remove ALL wash buffer with small pippette 
<br/><br/>
#### Eluting RNA

  10. Resuspend beads in 50uL of Elution Buffer and transfer to PCR strip tubes
  11. Run in a thermocycler
  		1. 3x cycles of ramping up to 95C and then down to 4C at a rate of 1C/second 
  		2. Hold at 4C
  12. Place PCR strips on magrack and transfer the supernatant to new clean 1.5mL eppendorfs
  13. Samples can be stored at 4C overnight or directly to bead clean up
<br/><br/>
#### Cleaning up elution

  14. Clean up using 1.8x SPRI beads; 90µL of well vortexed beads to 50µL of elution 
  15. Gently mix SPRI beads and elution and let sit room temp for 5-10 minutes
  16. Wash 3x with 500µL 70% EtOH, ~2 minutes each 
  17. After final wash, use a small pipette to remove all liquid 
  18. Let beads air dry for 5-10 minutes. Do not allow to over-dry
  19. Resuspend beads well in 30µL ultrapure ddH20
  20. Let sit room temperature for >10 minutes 
  21. Place beads back on magrack 
  22. Transfer supernatant to new clean eppendorf. This is your eluted RNA. 

<br/>


<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>
  
</p> <a href="./path-to-file/file1.ext">
Link to RT-qPCR protocol?</a>

</p> <a href="./path-to-other-file/file2.ext">
IDK?</a>

</details>

<details>
  <summary>Cited Protocols</summary>
  
  <a href="https://www.nature.com/articles/s41594-020-0390-z">
Enhanced nucleotide chemistry and toehold nanotechnology reveals lncRNA spreading on chromatin</a> Toehold techology, wash buffers, capture oligos. 

 <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7956044/">
Analysis of RNA-protein networks with RNP-MaP defines functional hubs on RNAn</a> Elution of RNA off beads (without use of elution oligos) 


</details>
