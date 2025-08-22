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
  * Strip tube Vortexer

Protocol:
--------------------------------------------------------------------------------
### Day 1: Probe annealing

### Hyb Buffer Prep (~15 minutes)
**1.** Prepare 100 µL of 2X Hyb buffer.

  | Component | [Stock] | [Final] | Quantity | 
  | ---------: | :---------: | :---------: |:---------- |
  | nuclease-free water | | | **45**  µL | 
  | SSC buffer | 20X | 2X | **10**  µL |
  | Denhardt's | 50X | 2X | **4**  µL |
  | PEG-8000 | 50% | 20% | **40**  µL |
  | SDS | 20% | 0.2% | **1**  µL |
  | **Total** ||| **100** µL |
  
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

**3.** In a thermocycler, incubate at 95 °C for 10 minutes, <br/> then put at 65 °C for 12+ hours overnight

### Day 2: Bead Capture and Washing

### Bead Equilibration and Capture (~15 minute prep + 45 min wait)

**4.** For each sample, capture streptavidin beads from 50 µL of slurry. Remove supernatant.

**5.** Wash beads 3 times in 100 µL (per initial 50) of 1X Bead Wash buffer + 0.1% Tween-20. <br/> Distribute into separate tubes of 100 µL per sample before removing last supernatant.

**6.** Immediately after removing last bead wash, add samples to each bead preparation. <br/> Incubate mixtures at 65 °C for 45 minutes.

### Wash buffer preparation (begin during bead capture incubation)

**7.** Prepare Wash buffers I, II, and III for each sample:

  | Wash Buffer | [SSC] | [SDS] | per sample | 
  | ---------: | :---------: | :---------: |:---------- |
  | Wash Buffer I | **1X** | **0.1%** | **200 µL** |
  | Wash Buffer II | **0.1X** | **0.1%** | **350 µL** |
  | Wash Buffer III | **0.1X** | **0%** | **150 µL** |

**8.** Preheat half of Wash Buffer I and II to 65 °C for at least 20 minutes. 

### Bead washes (30 minutes)

**9.** Capture sample beads and remove supernatant. <br/> Add 50 µL of HOT Wash Buffer I, vortex quickly, spin down, and move suspensions to new tube.

**10.** Perform 2 washes of each sample with 100 µL of HOT Wash Buffer II at 65 °C for 5 min each. _Note: Can incubate in a thermocycler or block, just tap mix periodically to keep from settling._

**11.** Wash once in 100 µL of room temp Wash Buffer I. <br/> Vortex for 2 minutes. Spin down, capture beads, and remove supernatant.

**12.** Wash once in 100 µL of room temp Wash Buffer II. <br/> Vortex for 1 minute. Spin down, capture beads, and remove supernatant.

**13.** Wash once in 100 µL of room temp Wash Buffer III. <br/> Vortex for 30 seconds. Spin down, capture beads, and remove supernatant.

**14.** Resuspend beads in 20 µL of nuclease-free water. Library PCR can be performed on-beads.
