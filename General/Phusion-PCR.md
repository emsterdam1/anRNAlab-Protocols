PCR amplification with Phusion
================================================================================
Description: The high-fidelity DNA polymerase Phusion is used to create DNA amplicons.
This is a generalized protocol that can be augmented depending on many variables

[Go To Protocol](#protocol)

Materials:
--------------------------------------------------------------------------------
  * 10 mM dNTP mix (each at 10 mM)
  * 10 µM Forward Primer
  * 10 µM Reverse Primer
  * DNA template
    * 0.01 ng gBlock,
    * 1 ng plasmid, or
    * cDNA
  * Phusion components (5X buffer, DMSO, Enzyme)
  
Equipment Required:
--------------------------------------------------------------------------------

  * Thermocycler
  
<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>

<br/>
<!-- Use <br/> to go to next page -->
  
Protocol:
--------------------------------------------------------------------------------
1. Mix desired components like this:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | HF or GC Buffer | 5X | **10**  µL | 
  | dNTPs | 10 mM | **1**  µL |
  | F primer | 10 µM | **2.5**  µL |
  | R primer | 10 µM | **2.5**  µL |
  | DNA template | variable | **2**  µL |
  | ddH2O || **31.5**  µL |
  | Phusion Polymerase | 2 U/µL | **2.5**  µL |
  || **Total** | **50** µL |
  
  <!-- : in the pipes specify justification -->
  <!-- **X** bolds the inside -->
  
  _Note: for difficult amplicons, can use DMSO to a final concentration of 3 % (1.5 µL)_
  
2. Incubate samples in thermocycler with the following settings:  

  | Cycles | Temp | Time | Step |
  | ---------: | :--------: | :---------: |:---------: |
  | **1** | **98 °C** | **0:30** | **inital denaturation** |
  
  || 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **8X** | **72->64 °C*** | **0:30** | **annealing** |
  || **72 °C** | **2:00** | **extension** |
  
  | | 98 °C | 0:10 | denaturation |
  | ---------: | :--------: | :---------: |:---------: |
  | **22X** | **64 °C** | **0:30** | **annealing** |
  | | **72 °C** | **2:00** | **extension** |
 
  | 1 | 72 °C | 5:00 | final extension |
  | ---------: | :--------: | :---------: |:---------: |
  
  _Note: the extension times and annealing temps can be optimized for amplicon length and primer Tm's_
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="https://www.neb.com/protocols/2015/12/08/quick-protocol-for-monarch-pcr-dna-cleanup-kit-5-g-t1030">
Monarch PCR Cleanup (NEB) </a>

</p> <a href="./DNA-Gel.md">
Gel Verification </a>

</p> <a href="../Gateway-Cloning/pDONR-BP-reaction.md">
pENTR Creation</a>

</details>

<details>
  <summary>More Info</summary>
  
  <a href="https://www.neb.com/protocols/0001/01/01/pcr-protocol-m0530">
NEB Phusion Website</a>  

</details>
