PCR amplification
================================================================================
Description: A high-fidelity DNA polymerase is used to create a variety of DNA amplicons.
This is a generalized protocol that can be augmented depending on many variables

[Go To Protocol](#protocol)

Materials:
--------------------------------------------------------------------------------
  * 10 mM dNTP mix (each at 10 mM) _Sometimes these are included in the Enzyme Master Mix_
  * 10 µM Forward Primer
  * 10 µM Reverse Primer
  * DNA template  
    ◦ 0.01 ng gBlock,  
    ◦ 1 ng plasmid, or  
    ◦ cDNA  
  * Buffer components (5X buffer, DMSO, Enzyme)
  
Equipment Required:
--------------------------------------------------------------------------------

  * Thermocycler
  
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
<!-- Use <br/> to go to next page -->
  
Protocol:
--------------------------------------------------------------------------------
**1.** Mix 1 µl of DNA template (per 25 µL reaction) with buffer components according to the polymerase chosen:

  * [Q5 Hot-start Master Mix](https://www.neb.com/protocols/2012/08/30/protocol-for-q5-hot-start-high-fidelity-2x-master-mix-m0494)
  * [Q5 Hot-start Polymerase](https://www.neb.com/protocols/2012/08/30/pcr-using-q5-hot-start-high-fidelity-dna-polymerase-m0493)
  * [Phusion Polymerase](https://www.neb.com/protocols/0001/01/01/pcr-protocol-m0530)
  
  _Note: All of these (and others) work, and sometimes certain polymerases work better for specific amplicons._<br/>_For difficult amplicons, adding DMSO to a final concentration of 3 % can help._
  
**2.** Incubate samples in thermocycler with the following settings:  

  | Cycles | Temp | Time | Step |
  | ---------: | :--------: | :---------: |:---------: |
  | **1** | **98 °C** | **0:30** | **inital denaturation** |
  
  **Optional Touchdown phase for lowly represented targets in cDNA**<br/>Annealing temp is reduced by 1 degree each cycle. Total cycles (this phase and next) should not exceed 40.
  || 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **variable** | **72->target °C*** | **0:30** | **annealing** |
  || **72 °C** | **30 s per kb** | **extension** |
  
  | | 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **30-35X** | **64 °C** | **0:30** | **annealing** |
  | | **72 °C** | **30 s per kb** | **extension** |
 
  | 1 | 72 °C | 2-5 minutes | final extension |
  | ---------: | :--------: | :---------: |:---------: |
  
  _Note: the extension times and annealing temps can be optimized for amplicon length and primer Tm's_
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="https://www.neb.com/protocols/2015/12/08/quick-protocol-for-monarch-pcr-dna-cleanup-kit-5-g-t1030">
Monarch PCR Cleanup (NEB) </a>

</p> <a href="./DNA-Agarose-Gel.md">
Gel Verification </a>

</p> <a href="../Gateway-Cloning/pDONR-BP-reaction.md">
pENTR Creation</a>

</details>

<details>
  <summary>More Info</summary>
  
  <a href="https://www.neb.com/protocols/0001/01/01/pcr-protocol-m0530">
NEB Phusion Website</a>  

</details>
