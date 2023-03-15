NEBNext Final Library Amplification
================================================================================
Description: Adaptor-including cDNA templates PCR library amplification

[Go To Protocol](#protocol)

Materials:
--------------------------------------------------------------------------------
  _Note: All NEB modules are included in the [NEBNext® Ultra™ II Directional RNA Library Prep Kit for Illumina®](https://www.neb.com/products/e7760-nebnext-ultra-ii-directional-rna-library-prep-kit-for-illumina#Product%20Information)_
  * Purified adaptor-ligated DNA
  * **[NEBNext® Ultra™ II Q5 Master Mix](https://www.neb.com/products/m0544-nebnext-ultra-ii-q5-master-mix#Product%20Information)**
    * First Strand Synthesis Reaction Buffer  
  * [In-house index primers](../../CWML-primers.csv)
    * In-house index primer F (i7, 5 µM)
    * In-house index primer R (i5, 5 µM)
    
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
___
Protocol:
--------------------------------------------------------------------------------

**1.** For each sample, combine the following components and mix well.

  | Component | Quantity | 
  | ---------: | :---------- |
  | Adaptor-ligated DNA | **15**  µL | 
  | Q5 Ultra II Master Mix | **25**  µL |  
  | 5 µM i7 F | **5**  µL |
  | 5 µM i5 R | **5**  µL |
  | **Total** | **50** µL |

**2.** Perform the following steps in a thermocycler: <br/>
_Note: The minimum number of cycles should be optimized to reduce PCR duplication artifacts,_<br/> 
  
  | Cycles | Temp | Time | Step |
  | ---------: | :--------: | :---------: |:---------: |
  | **1** | **98 °C** | **1:00** | **inital denaturation** |
  
  || 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **8-16X** | **67 °C** | **0:30** | **annealing** |
  | | **72 °C** | **0:30** | **extension** |
 
  | 1 | 72 °C | 2 minutes | final extension |
  | ---------: | :--------: | :---------: |:---------: |
  
  
**3.** Clean up PCR with a 1X ratio of [SPRI beads](../SPRI-beads.md), 2x 80% Ethanol washes, and 15 µL elution.<br/>
Assess library concentration and size distribution by fluorimeter and Bioanalyzer/TapeStation.

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="../Pool-Denature-Sequence.md">
Directional Second Strand Synthesis </a>

</details>
