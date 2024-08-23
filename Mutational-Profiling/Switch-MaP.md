Template-switching Mutational profiling (Switch-MaP)
================================================================================
Description: Using modified manganese-containing buffer to encourage transcriptase read-through of modified nucleotides.<br/>
Mutations and deletions at sites of read-through can be mapped by sequencing.<br/>
5' capping and addition of template-switching oligo enable 5' mapping.

Materials:
--------------------------------------------------------------------------------
  * **Modified RNA** _(and unmodified for control)_
    * 15+ pmoles of _in vitro_ RNA transcript,
    * 0.5-5 µg of cellular RNA (depending on representation of RNA of interest), **OR**
    * enriched target RNA
  * **[Vaccinia Capping System](https://www.neb.com/en-us/products/m2080-vaccinia-capping-system)**
    * 10 U/µl Vaccinia Capping Enzyme
    * 10 mM GTP
    * 10X capping buffer (50 mM Tris-HCl pH 8, 5 mM KCl, 1 mM MgCl<sub>2</sub>, 1mM DTT)
  * **2 µM of gene- or adapter-specific primer (_targeted_) or 70 µM (200 ng/µL) of [random nonamer](https://www.neb.com/products/s1254-random-primer-9#Product%20Information) (_for non-targeted_)**
  * **10 mM dNTPs**
  * **100 µM template-switching oligo (TSO, [ARL792](../ARL-primers.csv))
  * **10X NTP minus buffer** _(make fresh and keep on ice)_  
    ◦ 500 mM Tris pH 8.0  
    ◦ 750 mM KCl  
    ◦ 100 mM DTT _(Note: Don't use DTT that has been freeze-thawed more than once.)_  
  * [**5M Betaine**](https://www.fishersci.ca/shop/products/betaine-5m-solution-molecular-biology-grade-ultrapure-affymetrix-usb-3/aaj77507ucr)
  * **40 mM MnCl<sub>2</sub>**  
  * **200 U/µl** [**SuperScript II**](https://www.thermofisher.com/order/catalog/product/18064022#/18064022) **Reverse Transcriptase**
  * [**G-50 microspin columns**](https://www.cytivalifesciences.com/en/us/shop/molecular-biology/purification/gel-filtration-columns/illustra-microspin-g-50-columns-p-00056)
 _(for lowly expressed targets and randomer-primed samples)_  
  
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler

___
Protocol:
--------------------------------------------------------------------------------

**Optional: 5' G-Capping of 5' triphosphate RNAs (45 minutes)** <br/>
_Note: This is especially important to increase switching for RNAs that have a 5' U._

**i.** In 14 µl of water, denature RNA at 68-75 °C for 5 minutes, then anneal on ice for 2 minutes.

**ii.** Assemble the capping reaction as follows:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Denatured RNA | | **14**  µL | 
  | Capping buffer| 10X | **2**  µL |
  | GTP | 10 mM | **2**  µL |
  | Nuclease-free water | | **1**  µL |
  | Vaccinia capping enzyme | | **1**  µL |
  || **Total** | **20** µL |

**iii.** Incubate capping reaction for 30 minutes at 37 °C.

**iv.** Purify RNA by SPRI beads or column-based approach (elute in <= 20 µl).

**Switch-MaP (3 hours)**

**1.** For each sample, combine 6 µl RNA, 1 µl RT primer, and 2 µl of dNTPs. <br/>
Denature at 68-75 °C for 5 minutes, then anneal on ice for 2 minutes. <br/>
_Note: Use 6 µl of purified capping product or 5 pmoles RNA._

**2.** Assemble enough RT master mix for each sample, adding manganese only immediately before use:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | NTP minus buffer | 10X | **2**  µL | 
  | Betaine | 5M | **4**  µL |
  | TSO | 100 µM | **1**  µL |
  | MnCl<sub>2</sub> | 40 mM | **3**  µL |
  || **Total** | **10** µL |
  
  **The color should change upon adding MnCl<sub>2</sub>. If it doesn't, you need new NTP minus buffer.**  
  _Note: You can lower the concentration of MnCl<sub>2</sub> to 0.5 µL to accomodate larger RNA volumes._
  
**3.** Mix 10 µL of master mix with 9 µL of each primer-RNA mix and incubate for 2 minutes at 25 °C. 

**4.** Add 1 µL of SSII RT enzyme to each reaction and perform the following thermocycles:

  | Step | Temp | Time | Action |
  | ---------: | :--------: | :---------: |:---------: |
  | **i** | **25 °C** | **10:00** | **Equilibration** |
  | **ii** | **42 °C** | **90:00** | **Extension** |
  
  **Cycle 10 times**  
  | iiia | 50 °C | 2:00 ||
  | ---------: | :--------: | :---------: |:---------: |
  | **iiib** | **42 °C** | **2:00** | **Extension past difficult adducts** |
 
  **End Reaction** 
  | iv | 70 °C | 10:00 | Enzyme denaturation |
  | ---------: | :--------: | :---------: |:---------: |

**5.** For RNA targets longer than 100 nts:  
- remove excess TSO with 1.8X [SPRI beads](../NGS/SPRI-beads.md) <br/>
- use a column-based size-selection method to remove excess adapter
  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>

</p> <a href="../NGS/Two-Step-PCR-Library.md">
2-step PCR library generation </a>

</details>

<details>
  <summary>More Info</summary>
  
  <a href="https://doi.org/10.1038/nprot.2015.103">
Original SHAPE-MaP Protocol</a>  

</details>
