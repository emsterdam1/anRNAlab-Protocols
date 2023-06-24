Antisense oligo and RNase H depletion of rRNAs
================================================================================
Description: DNA oligos enable RNase H cleavage of mouse or human rRNAs from a sample

Materials:
--------------------------------------------------------------------------------
  **Probe annealing**
  * DNA-free total RNA
  * 50 µM [DNA depletion oligo mix](./HsMm-rRNA-RNaseH-pool.csv) (each at ~ 380 pM)
  
  **RNase H digestion**
  * 5 U/µl [Thermostable RNase H](https://www.neb.com/products/m0523-thermostable-rnase-h#Product%20Information)
  * **10X RNase H Buffer (pH 8.3 at RT, included with enzyme)**
    * 500 mM Tris-HCl
    * 750 mM KCl
    * 30 mM MgCl<sub/>2<sub>
    * 100 mM DTT
  
  **DNase removal of oligos**
  * 2 U/µl [TURBO DNase](https://www.thermofisher.com/order/catalog/product/AM2238)
  * **10X DNase I Buffer (pH 7.6 at RT, included with enzyme + stabilizer)**
    * 100 mM Tris-HCl
    * 25 mM MgCl<sub/>2<sub>
    * 5 mM CaCl<sub/>2<sub>
  
  **Cleanup**
  * [SPRI beads](./SPRI-beads.md)
  
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler
  * Magnetic stand

<!-- Use <br/> to go to next page -->
  
Protocol:
--------------------------------------------------------------------------------
### Probe annealing (~15 minutes)

**1.** In 15 µl of RNase-free water, mix 1 µl of depletion oligos for every 1 µg of total RNA.  

**2.** Anneal oligos to target rRNA in a thermocycler with the following program:  

  | Temp | Time | Step |
  | :--------: | :---------: |:---------: |
  | **98 °C** | **2:00** | **inital denaturation** |
  | **down to 22 °C** | **1 °C/sec** | **gradual ramp down** |
  | **22 °C** | **5:00** | **final annealing** |
  <br/>

### RNase H digestion (~40 minutes)

**3.** For each sample, mix the following components:

  | Component | Quantity | 
  | ---------: | :---------- |
  | Oligo-annealed RNA | **15**  µL | 
  | RNase-free water | **1**  µL |
  | 10X RNase H Buffer | **2**  µL |
  | 5U/µL thermostable RNase H| **2**  µL |
  | **Total** | **20** µL |

**4.** Digest rRNA in a thermocycler for 30 minutes at 50 °C (set lid to 55 °C):

  | Temp | Time | Step |
  | :--------: | :---------: |:---------: |
  | **98 °C** | **2:00** | **inital denaturation** |
  | **down to 22 °C** | **1 °C/sec** | **gradual ramp down** |
  | **22 °C** | **5:00** | **final annealing** |
  <br/>

### DNase removal of oligos (~40 minutes)

**5.** For each sample, mix the following components:

  | Component | Quantity | 
  | ---------: | :---------- |
  | RNase H-treated RNA | **20**  µL | 
  | RNase-free water | **24**  µL |
  | 10X DNase I Buffer | **5**  µL |
  | 2U/µL TURBO DNase| **1**  µL |
  | **Total** | **50** µL |

**6.** Digest DNA in a thermocycler for 30 minutes at 37 °C (set lid to 55 °C):
<br/>

### SPRI bead cleanup (~15 minutes)

**7.** Clean up rRNA-depleted RNA with columns or SPRI beads. Elute RNA in 16 µL of RNase-free water.
  * Use [SPRI beads](./SPRI-beads.md) to purify (1.8X ratio and 2X washes with 70% ethanol).

The product can be used for downstream library preparation.

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="./NEB-Ultra-II-Directional/First-strand-synthesis.md">
First Strand Synthesis </a>

</details>
