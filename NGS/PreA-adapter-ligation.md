Ligation of 3' adapter with T4 RNA ligase I
================================================================================
Description: Ligation of 3' adapter to RNA for subsequent RT

Materials:
--------------------------------------------------------------------------------
  **Probe annealing**
  * DNA-free total RNA
  * 50 µM [DNA depletion oligo mix](./HsMm-rRNA-RNaseH-pool.csv) (each at ~ 380 nM)
  
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
### Day 1: Ligation with RNA Ligase I (~15 minute prep, overnight ligation)

**1.** Assemble the ligation reaction. <br/>The ratio of adapter to RNA should be around 2:1, and works with as little as 5 pmol of pure RNA ends.

  | Component | Stock Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | PEG-8000 | 50 % | **10**  µL | 
  | RNA || **1**  µL |
  | adapter || **1**  µL |
  | DMSO | 100 % | **2**  µL |
  | RNA Ligase Buffer | 10X | **2**  µL |
  | ddH<sub/>2<sub>O || **3**  µL |
  | T4 RNA Ligase I | 10 U/µL | **1**  µL |
  || **Total** | **20** µL |

  _Note: PEG-8000 is super viscous, be careful that you add the correct amount._ <br/> _Ensure all components are mixed thoroughly by tapping and spinning down._

**2.** Ligate the RNA in a thermocycler for 16 hours at 16 °C (turn off lid).

### Day 2: Purification of Reaction products

**3.** Chelate Magnesium in the buffer by quenching reaction with 20 µL (1 reaction volume) of 25 mM EDTA.

**4.** If your ligated products are expected to be > 200 nt, you can remove excess adapter with [SPRI beads](./SPRI-beads.md). <br/> For small RNA products, it is advisable to [gel purify](./PAGE-purification-of-RNA.md). <br/> In either case, it is useful to validate efficiency on a denaturing PAGE gel if performing for the first time.



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
