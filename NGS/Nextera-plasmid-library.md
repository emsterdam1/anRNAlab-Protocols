Nextera library preparation for whole-plasmid sequencing
================================================================================
Description: Using "tagmentation" workflow to fragment and index plasmids for next-gen sequencing.

Reagent volumes have been dramatically reduced from manufacturer's guidelines for cost-savings.

Materials:
--------------------------------------------------------------------------------
  * Diluted plasmid (0.2 ng/µL)
  * Illumina Nextera XT reagents
    * Tagment DNA Buffer
    * Amplicon tagment mix
    * Neutralization Buffer
    * Nextera PCR Master Mix
  * In-house index primer F (i7, 5 µM)
  * In-house index primer R (i5, 5 µM)
  * Magnetic SPRI beads

Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler
  * Magnetic Stand
  
___
Protocol:
--------------------------------------------------------------------------------

**1.** Set up tagmentation reactions for each plasmid:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Tagment DNA Duffer | 2X | **2.5**  µL | 
  | plasmid DNA | 0.2 ng/µL | **1.25**  µL |
  | Amplicon Tagment Mix || **1.25**  µL |
  || **Total** | **5** µL |
  
  <!-- : in the pipes specify justification -->
  <!-- **X** bolds the inside -->
  
 **2.** In a thermocycler, incubate reactions at 55 °C for 11 minutes, then cool to 10 °C.
   * *Note: Normal reaction time is 5 minutes, but plasmids are much longer than typical template* 

**3.** As soon as reactions reach 10 °C, add 1.25 Neutralization Buffer (NT) and incubate 5 min at RT.
  * *Neutralization buffer stops the reaction, so timing is important*
  
**4.** Assemble Nextera PCR reactions:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Tagmented DNA | | **6.25**  µL | 
  | i7 index primer | 5µM | **1.25**  µL |
  | i5 index primer | 5µM | **1.25**  µL |
  | Nextera PCR Master Mix |3.33X| **3.75**  µL |
  || **Total** | **12.5** µL |
  
**5.** Run Nextera PCR:

  | Cycles | Temp | Time | Step |
  | ---------: | :--------: | :---------: |:---------: |
  | **1** | **72 °C** | **3:00** | **enzyme denaturation?** |
  | **1** | **95 °C** | **0:30** | **inital denaturation** |
  
  || 95 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **-14X-** | **55 °C*** | **0:30** | **annealing** |
  || **72 °C** | **0:30** | **extension** |
 
  | 1 | 72 °C | 5:00 | final extension |
  | ---------: | :--------: | :---------: |:---------: |

*Note: Cycle number has been increased by 2 to offset the use of less reagent*

**6.** Clean up PCRs with columns or SPRI beads. Elute libraries in 15 µL of water.
  * For plasmids, we use Mag-Bind TotalPure NGS beads (Omega BioTek) at a 0.65X ratio and wash 2X with 80% ethanol.
  
**7.** Check samples on a Bioanalyzer/TapeStation and assess length distributions before sequencing.

  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>More Info</summary>
  
  <a href="https://support.illumina.com/content/dam/illumina-support/documents/documentation/chemistry_documentation/samplepreps_nextera/nextera-xt/nextera-xt-library-prep-reference-guide-15031942-05.pdf">
Detailed Nextera Information</a>

<br/>

  <a href="http://gc3fstorage.uoregon.edu/IMAGES/Evaluation_of_Omega_Mag-Bind_TotalPure_NGS_Beads_MWeitzman_April2018.pdf">
Determining Bead Cutoffs</a>  

</details>
