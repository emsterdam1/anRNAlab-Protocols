RNA pulldown with biotinylated DNA oligos
================================================================================

Materials:
--------------------------------------------------------------------------------
  ◦ Input RNA  
  ◦ 10 uM biotinylated DNA probes _(antisense for capture, sense for control)_  
  ◦ 100 mM DTT  
  ◦ 500 mM TCEP  
  ◦ 20% SDS  
  ◦ 100 mM NaCl  
  ◦ [MyOne Streptavidin C1 Magnetic Beads](https://www.thermofisher.com/order/catalog/product/65001)  
  * **Bead Treatment Solution (make day of use)**  
    ◦ 100 mM NaOH  
    ◦ 50 mM NaCl 
  * **Hybridization Buffer Stock (2X)**  
    ◦ 100 mM HEPES pH 7.5  
    ◦ 2 M NaCl  
    ◦ 4 M Urea  
    ◦ 12 mM EDTA  

  * **Wash Buffer No Salt Stock (10X)**  
    ◦ 100 mM HEPES pH 7.4  
    ◦ 20 mM EDTA  
    ◦ 10 mM EGTA  
  * **Elution Buffer Stock (10X)**  
    ◦ 200 mM Tris pH 8.0  
    ◦ 100 mM EDTA  
<br/><br/><br/>  
Equipment Required:
--------------------------------------------------------------------------------
◦ End-over-end rotator  
◦ Magnetic racks for 1.5mL tubes and for 96-well plates  
◦ Heated Water Bath  
◦ Heat block with shaking  
◦ Thermocycler  



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

**3.** Treat and Equilibrate (5 x #RNA samples) µL of Streptavidin beads on a magnetic rack.<br/>      
  &ensp;&ensp;**i.** Wash beads twice for 2 minutes in Bead Treatment solution (inactivate RNases)  
  &ensp;&ensp;**ii.** Combine (10 x #RNA samples) µL of hyb master mix with (8.7 x #RNA samples) µL of water    
  &ensp;&ensp;**iii.** Resuspend beads in (5 x #RNA samples) µL of the new 1X hyb buffer    
  &ensp;&ensp;**iv.** Capture beads, discard buffer, resuspend in (5 x #RNA samples) µL of 1X hyb buffer  
  
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

**4.** Capture and treat (26 x #RNA samples) µL of Streptavidin beads in a 1.5 mL tube by magnetic rack.<br/>  
  &ensp;&ensp;**i.** Wash beads twice for 2 minutes in 1 original volume of Bead Treatment solution (inactivate RNases)  
  &ensp;&ensp;**ii.** Wash beads once for 2 minutes in 1 volume 100 mM NaCl, and resuspend in 0.25 volumes 100 mM NaCl  
  
**5.** To each RNA hybridization, add 5 µL of treated streptavidin beads.<br/>
Incubate capture mixtures with end-over-end rotation at room temperature for 2 hours.

**Washing beads**

  **6.** Separate capture mixtures on a magnetic rack  
  **7.** **Retain the buffer fraction as "flow-through" for downstream analysis.**  
  **8.** Perform bead washes, 500 µL each, 2-5 minutes, with shaking or rotation:  
  		&ensp;&ensp;**i.** 5 x room temperature washes with WB100  
  		&ensp;&ensp;**ii.** **Transfer beads to new clean eppendorf tubes**  
  		&ensp;&ensp;**iii.** 2 x more washes with WB100  
  		&ensp;&ensp;**iv.** 1 x wash with WB30 **at 42 °C**  
    &ensp;&ensp;**v.** 1 x wash with WB10 **at 42 °C**  
    &ensp;&ensp;**vi.** 1 x wash with WB10 **at 50 °C**  

**Eluting RNA**

**9.** Make 50 µL of 1X elution buffer per RNA sample:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Elution stock | 10X | **5**  µL | 
  | TCEP | 500 mM | **2**  µL |
  | ddH<sub>2</sub>O || **43**  µL |
  || **Total** | **50** µL |
  
  **10.** Capture beads, discard wash buffer, and resuspend beads in 30uL of 1X Elution Buffer.<br/>
  Transfer samples to PCR strip tubes
  
  **11.** In a thermocycler, perform 3 cycles of:
  &ensp;&ensp;**i.** Rapidly heat samples to 95 °C, and  
  &ensp;&ensp;**ii.** cool to 4 °C at a rate of 1 °C/second.<br/>
  _After the third cool down, samples can be kept at 4-10 °C_
  
  **12.** Separate beads on magnetic rack and transfer the eluate to new clean 1.5 mL eppendorfs.
  
  **13.** Resuspend the beads in 20 µL of 1X elution buffer and repeat elution. <br/>
  Combine the original 30 µL elution and second 20 µL elutions together.<br/>
  _Samples can be stored at 4C overnight or go directly to bead clean up_
  
  **14.** Clean up captured RNA with a 1.8X ratio of [SPRI beads](../NGS/SPRI-beads.md), 3x 70% Ethanol washes, and 15 µL elution.

<details>
  <summary>Next Steps</summary>
  
</p> <a href="../Mutational-Profiling/MaP-RT-SSII.md">
MaP with SuperScript II RT</a>

</p> <a href="../NGS/Second-Strand-Synthesis.md">
Second-Strand Synthesis</a>

</p> <a href="../NGS/Basic-Nextera-XT.md">
Nextera XT library prep</a>

</details>

<details>
  <summary>Cited Protocols</summary>
  
  <a href="https://www.nature.com/articles/s41594-020-0390-z">
Enhanced nucleotide chemistry and toehold nanotechnology reveals lncRNA spreading on chromatin</a> <br/>Toehold techology, wash buffers, capture oligos. 
<br/>
 <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7956044/">
Analysis of RNA-protein networks with RNP-MaP defines functional hubs on RNAn</a> <br/>Elution of RNA off beads (without use of elution oligos) 


</details>
