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
  * 100 mM NaCl
  * **Bead Treatment Solution (make day of use)**  
    ◦ 100 mM NaOH  
    ◦ 50 mM NaCl 

### Day 1
  * Input RNA  
  * 10 uM biotinylated DNA probes <br/>_(antisense for capture, sense for control)_


  * **Hybridization Buffer Stock (2X)**  
    ◦ 100 mM HEPES pH 7.5  
    ◦ 2 M NaCl  
    ◦ 4 M Urea  
    ◦ 12 mM EDTA  
    
### Day 2
  * 500 mM TCEP
  * [MyOne Streptavidin C1 Magnetic Beads](https://www.thermofisher.com/order/catalog/product/65001)
  * **Wash Buffer No Salt Stock (10X)**  
    ◦ 100 mM HEPES pH 7.4  
    ◦ 20 mM EDTA  
    ◦ 10 mM EGTA  
  * **Elution Buffer Stock (10X)**  
    ◦ 200 mM Tris pH 8.0  
    ◦ 100 mM EDTA  
  
  
<!-- Using distinct bullet symbols with 2 spaces at end of each line makes a better formatted list -->
    

Equipment Required:
--------------------------------------------------------------------------------
* Overhead rotator 
* Magnetic rack for 1.5mL tubes
* Heated Water Bath
* Heat block with shaking
* Thermocycler


<br/><br/>
___
Protocol:
--------------------------------------------------------------------------------
### Day 0: Prepare Buffer Stocks (See Materials)<br/>
_Buffer stocks can be stored long term at room temperature without reducing agent or SDS._

### Day 1: RNA-oligo hybridization

**Sample Preparation**

**1.** Dilute up to 4 ug of each RNA sample in 46.5 µL of nuclease-free water.<br/>
_Note: Be sure to include samples for capture with control sense probes._
  
**2.** Create enough hybridization master mix to accomodate 1.2X the number of RNA samples: 

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | hybridization stock | 2X | **50**  µL | 
  | DTT | 100 mM | **2**  µL |
  | SDS | 20 % | **1.5**  µL |
  || **Total** | **53.5** µL |

**Bead Equilibration**

**3.** Separate (5 x #RNA samples) µL of Streptavidin beads on a magnetic rack.  
  ◦ Wash beads twice for 2 minutes in Bead Treatment solution (inactivate RNases)
  ◦ Combine (10 x #RNA samples) µL of hyb master mix with (8.7 x #RNA samples) µL of water  
  ◦ Resuspend beads in (5 x #RNA samples) µL of the new 1X hyb buffer  
  ◦ Capture beads, discard buffer, resuspend in (5 x #RNA samples) µL of 1X hyb buffer
  
**Sample Pre-clearance**

**4.** Combine 53.5 ul of hyb master mix with each RNA sample (100 ul total).<br/>
_Final concentrations: 50 mM HEPES pH 7.5, 1 M NaCl, 2 M Urea, 6 mM EDTA, 0.3 % SDS, 2 mM DTT_

**5.** Pre-clear RNA samples with 5 ul of pre-equilibrated Streptavidin beads. <br/>
Mix samples with overhead rotation for 30 minutes at room temperature.

**6.** Capture beads and recover 95 ul of each RNA sample into new tubes.

**7.** Add 5 ul of biotinylated probes to each RNA sample.<br/>
Incubate hybridization reaction overnight (~16 hrs) at room temperature.

### Day 2: Bead Capture, Washing, and Elution

**Buffer prep and bead capture** 

**1.** Prepare enough fresh wash buffer for each RNA sample. Per sample:

  | for WB100 | [ ] | Quantity || for WB30 | [ ] | Quantity || for WB10 | [ ] | Quantity |
  | ---------: | :--------: | :---------- | ---------: | ---------: | :--------: | :---------- | ---------: | ---------: | :--------: | :---------- |
  | WB stock | 10X | **400**  µL || WB stock | 10X | **100**  µL || WB stock | 10X | **150**  µL |
  | NaCl | 5 M | **80**  µL || NaCl | 5 M | **6**  µL || NaCl | 5 M | **3**  µL |
  | SDS | 20 % | **400**  µL || SDS | 20 % | **100**  µL || SDS | 20 % | **150**  µL |
  | ddH<sub>2</sub>O || **3120**  µL || ddH<sub>2</sub>O || **794**  µL || ddH<sub>2</sub>O || **1197**  µL | 
  || **Total** | **4** mL ||| **Total** | **1** mL ||| **Total** | **1.5** mL |
  
**2.** Set aside WB30 and WB10 in a 42 °C water bath or heat block at this time. 

**3.** Remove 10 % (~10 µL) of input RNA samples and store at 4C for downstream validation. 

**4.** Capture (26 x #RNA samples) µL of Streptavidin beads in a 1.5 mL tube by magnetic rack.  
  ◦ Wash beads twice for 2 minutes in 1 original volume of Bead Treatment solution (inactivate RNases)  
  ◦ Wash beads once for 2 minutes in 1 volume 100 mM NaCl, and resuspend in 0.25 volumes 100 mM NaCl  
  
**5.** To each RNA hybridization, add 5 µL of treated streptavidin beads.<br/>
Incubate capture mixtures with end-over-end rotation at room temperature for 2 hours.

<br/><br/>
**Washing beads**

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
