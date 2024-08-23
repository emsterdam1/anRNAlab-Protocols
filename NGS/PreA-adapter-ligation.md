Ligation of 3' adapter with T4 RNA ligase I
================================================================================
Description: Ligation of 3' adapter to RNA for subsequent RT

Materials:
--------------------------------------------------------------------------------
  * At least 5 uM of purified RNA target
  * 100 uM 5' preadenylated (App) and 3' blocked adapter ([ARL793](../ARL-primers.csv)) 
  * 50 % PEG-8000
  * 100 % DMSO
  * **10X T4 RNA Ligase Reaction Buffer**
    * 500 mM Tris-HCl pH 7.5
    * 100 mM MgCl<sub>2</sub>
    * 10 mM DTT
  * 10 U/ul T4 RNA Ligase I
  * 25 mM EDTA
  
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler

<!-- Use <br/> to go to next page -->
  
Protocol:
--------------------------------------------------------------------------------
### Day 1: Ligation with RNA Ligase I (~15 minute prep, overnight ligation)

**1.** Assemble the ligation reaction. <br/>The ratio of adapter to RNA should be around 2:1, and works with as little as 5 pmol of pure RNA ends.

  | Component | Stock Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | PEG-8000 | 50 % | **10**  µL | 
  | RNA || **1**  µL |
  | diluted adapter || **1**  µL |
  | DMSO | 100 % | **2**  µL |
  | RNA Ligase Buffer | 10X | **2**  µL |
  | ddH<sub/>2</sub>O || **3**  µL |
  | T4 RNA Ligase I | 10 U/µL | **1**  µL |
  || **Total** | **20** µL |

  _Note: PEG-8000 is super viscous, be careful that you add the correct amount._ <br/> _Ensure all components are mixed thoroughly by tapping and spinning down._

**2.** Ligate the RNA in a thermocycler for 16 hours at 16 °C (turn off lid).

### Day 2: Purification of Reaction products

**3.** Chelate Magnesium in the buffer by quenching reaction with 20 µL (1 reaction volume) of 25 mM EDTA.

**4.** If ligated products are > 200 nt, dilute with water to 100 µL and either: <br/>
- remove excess adapter with 1.8X [SPRI beads](./SPRI-beads.md) <br/>
- use a column-based size selection method to remove excess adapter

For smaller RNA products, the correct size should be [gel purified](./PAGE-purification-of-RNA.md).

<details>
  <summary>Next Steps</summary>

</p> <a href="./PAGE-purification-of-RNA.md">
PAGE purification of small RNA products </a>

</details>
