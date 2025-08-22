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

### Hyb Buffer Prep (~15 minutes)
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
  
### Hybridization (12+ hours overnight)
**2.** Assemble the hybridization reaction.  

  | Component | [Stock] | Quantity | 
  | ---------: | :---------: |:---------- |
  | cDNA | 500 ng | **X**  µL | 
  | Cot-1 DNA | 1 µg/µL | **0.5**  µL |
  | TS probes | 100 ng/µL| **1**  µL |
  | nuclease-free water || **6-X**  µL |
  | 2X Hyb | 2X | **7.5**  µL |
  | **Total** || **15** µL |

  _Note: to achieve 500 ng, can concentrate pre-pooled multiplexed samples._

**3.** In a thermocycler, incubate at 95 °C for 10 minutes, <br/> then put at 65 °C for 12+ hours overnight

### Day 2: Bead Capture and Washing

### Bead Equilibration and Capture (~15 minute prep + 45 min wait)

**4.** For each sample, capture streptavidin beads from 50 µL of slurry. <br/> Remove supernatant.

**5.** Wash beads 3 times in 100 µL (per initial 50) of 1X Bead Wash buffer + 0.1% Tween-20. <br/> Distribute last resuspension into separate tubes of 100 µL per sample before removing supernatant.

**6.** Immediately after removing last bead wash, add samples to each bead preparation. <br/> Incubate mixtures at 65 °C for 45 minutes. _Note: This would be a good time to prepare and preheat wash buffers._

### Wash buffer preparation (begin during bead capture incubation)

**7.** Prepare Wash buffers I, II, and III for each sample:

  | Wash Buffer | [SSC] | [SDS] | per sample | 
  | ---------: | :---------: | :---------: |:---------- |
  | Wash Buffer I | **1X** | **0.1%** | **200 µL** |
  | Wash Buffer II | **0.1X** | **0.1%** | **350 µL** |
  | Wash Buffer III | **0.1X** | **0%** | **150 µL** |

**8.** Preheat half of Wash Buffer I and II to 65 °C for at least 20 minutes. 

### Bead washes ()

**9.** Capture sample beads and remove supernatant. <br/> Add 50 µL of HOT Wash Buffer I, vortex quickly, spin down, and move suspensions to new tube.

**10.** Perform 2 washes of each sample with 100 µL of HOT Wash Buffer II at 65 °C for 5 min each.

<br/><br/><br/><br/><br/><br/><br/><br/>

### Day 2: Purification and analysis

### SPRI bead cleanup and Tape (~40 minutes)

**8.** Clean up reaction products with 1.8X SPRI beads and 2 75 % ethanol washes. <br/> Elute products in 30 µL of water.

**9.** Use a spec to measure concentrations and analyze products on an HS D1000 Tape. <br/> The no nickase control should only show initial extension products at correct size, <br/> longer time points should have more products (smears).

### qPCR follow-up

**10.** Make 1:1000 dilutions of each sample and measure increase in desired products by qPCR. <br/> Choose the time point where signal plateaus.
