NEBNext Standard First Strand Synthesis
================================================================================
Description: Bulk RNA samples are fragmented and reverse-transcribed.

[Go To Protocol](#protocol)

Materials:
--------------------------------------------------------------------------------
  _Note: All NEB modules are included in the [NEBNext® Ultra™ II Directional RNA Library Prep Kit for Illumina®](https://www.neb.com/products/e7760-nebnext-ultra-ii-directional-rna-library-prep-kit-for-illumina#Product%20Information)_
  * Purified full-length RNA (Total, mRNA, affinity-purified RNA, etc.)
  * **[NEBNext® Ultra™ II RNA First Strand Synthesis Module](https://www.neb.com/products/e7771-nebnext-ultra-ii-rna-first-strand-synthesis-module#Product%20Information)**
    * First Strand Synthesis Reaction Buffer  
    * Random Primers  
    * First Strand Synthesis Enzyme Mix  
    * Strand Specificity Reagent
    
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler

<br/><br/><br/><br/><br/><br/><br/><br/>
___
Protocol:
--------------------------------------------------------------------------------

**Part 1: Fragmentation and primer annealing**

**1.** Combine the following components on ice and mix well.

  | Component | Quantity | 
  | ---------: | :---------- |
  | RNA | **5**  µL | 
  | FS Reaction Buffer | **4**  µL |
  | Random Primers | **1**  µL |
  | **Total** | **10** µL |

**2.** Fragment RNA at 94 °C for 10 minutes and then transfer to ice. <br/>
_Note: Timing can be optimized for varying starting RNA and desired fragment lengths_
  
**Part 2: First Strand Sythesis**
  
**3.** Combine the following components on ice.

  | Component | Quantity | 
  | ---------: | :---------- |
  | Fragmented and primed RNA | **10**  µL | 
  | Strand specificity reagent | **8**  µL |
  | FS Enzyme mix | **2**  µL |
  | **Total** | **20** µL |

**4.** Mix samples well and perform the following thermocycles:

  | Step | Temp | Time | Action |
  | ---------: | :--------: | :---------: |:---------: |
  | **i** | **25 °C** | **10:00** | **Complex Assembly** |
  | **ii** | **42 °C** | **15:00** | **Reverse Transcription** |
  | **iii** | **70 °C** | **15:00** | **Enzyme Denaturation** |
  | **iv** | **10 °C** | **hold** | **wait** |
  
The product can be used immediately in second strand synthesis.

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="./Directional-Second-Strand-Synthesis.md">
Directional Second Strand Synthesis </a>

</details>
