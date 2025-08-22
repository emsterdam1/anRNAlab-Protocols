Targeted cDNA enrichment with biotinylated TEQUILA probes
================================================================================
Description: enrich target genes for sequencing with biotinylated probes

Materials:
--------------------------------------------------------------------------------
  * 100 ng/µl of TS probes <br/> _For PCR amplified cDNA, probes can be sense or antisense._
  * 500 ng library cDNA
  * 1 µg/µl Cot-1 DNA
  * _Optional: blocking oligonucleotides 1 nmole per reaction_
  * **50X Denhardt's Solution**
    * 1 % Ficoll (400)
    * 1 % polyvinylpyrrolidone
    * 1 % bovine serum albumin <br/> _Note: Will need to heat this to get into solution._
  * **20X Saline-sodium citrate buffer (SSC) pH 7**
    * 3M NaCl
    * 0.3M sodium citrate
  * 50 % PEG-8000
  * 20 % SDS
  * **2X Bead Wash Buffer**
    * 20 mM Tris-HCl pH 7.5
    * 2M NaCl
    * 2 mM EDTA
  * [magnetic streptavidin beads](https://www.thermofisher.com/order/catalog/product/65001)
  
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler
  * Magnetic stand
  * Vortexer

<!-- Use <br/> to go to next page -->
<br/><br/><br/><br/>

Protocol:
--------------------------------------------------------------------------------
### Day 1: Probe annealing

**1.** Prepare 500 µL of 2X Hyb buffer. <br/> _Each sample only needs 7.5 µl_

  | Component | [Stock] | [Final] | Quantity | 
  | ---------: | :---------: | :---------: |:---------- |
  | nuclease-free water | | | **325**  µL | 
  | SSC buffer | 20X | 2X | **50**  µL |
  | Denhardt's | 50X | 2X | **20**  µL |
  | PEG-8000 | 50% | 20% | **200**  µL |
  | SDS | 20% | 0.2% | **5**  µL |
  | **Total** ||| **500** µL |
  
  _Pipette mix thoroughly, PEG is viscous and SDS is detergent._ <br/>
  
**2.** Anneal RC oligo to template pool in a thermocycler with the following program:  

  | Component | [Stock] | Quantity | 
  | ---------: | :---------: |:---------- |
  | cDNA | 500 ng | **X**  µL | 
  | Cot-1 DNA | 1 µg/µL | **0.5**  µL |
  | TS probes | 100 ng/µL| **1**  µL |
  | nuclease-free water || **6-X**  µL |
  | 2X Hyb | 2X | **7.5**  µL |
  | **Total** || **15** µL |

  | Temp | Time | Step |
  | :--------: | :---------: |:---------: |
  | **95 °C** | **2:00** | **inital denaturation** |
  | **down to 4 °C** | **0.1 °C/sec** | **gradual ramp down** |
  | **4 °C** || **hold until next step** |
  
  _Note: Should take 15 minutes to ramp down from 95 to 4,_ <br/> _set Proflex ramp rate to 0.3 °C/sec to achieve this._
<br/>

<br/><br/><br/><br/>

### Intial extension (~15 minutes)

**3.** To each sample, add the following components: <br/> _Tip: can spot 1 µL at tube tops and spin down to mix_

  | Component | [Stock] | Quantity | 
  | ---------: | :---------: |:---------- |
  | annealed mix || **46**  µL | 
  | DTT | 100 mM | **1**  µL |
  | T4 Gene 32 Protein | 10 mg/ml | **1**  µL |
  | Klenow Fragment| 5 U/µL | **1**  µL |
  | **Total** || **49** µL |
  <br/>

**4.** Incubate extension in a thermocycler for 10 minutes at 37 °C (set lid to 55 °C)

### Isothermal strand displacement amplification (up to 16 hours)

**5.** For each time point sample, add 1 µL of 10U/µL Nt.BspQI nickase. <br/> For the no nickase control, add 1 µL of water.

**6.** Incubate reactions at 37 °C for varying time points. <br/> A good starting point is 2, 4, 6, and 8 hours.

**7.** At the end of each time point, inactivate enzyme at 80 °C for 20 minutes. <br/> Move inactivated time points to 4 °C until ready to clean up all samples. <br/> _Note: the no nickase control should incubate as long as the longest time point._

<br/><br/><br/><br/><br/><br/><br/><br/>

### Day 2: Purification and analysis

### SPRI bead cleanup and Tape (~40 minutes)

**8.** Clean up reaction products with 1.8X SPRI beads and 2 75 % ethanol washes. <br/> Elute products in 30 µL of water.

**9.** Use a spec to measure concentrations and analyze products on an HS D1000 Tape. <br/> The no nickase control should only show initial extension products at correct size, <br/> longer time points should have more products (smears).

### qPCR follow-up

**10.** Make 1:1000 dilutions of each sample and measure increase in desired products by qPCR. <br/> Choose the time point where signal plateaus.
