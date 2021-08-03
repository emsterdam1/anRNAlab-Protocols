Mutational profiling (MaP) with Marathon RT
================================================================================
Description: Using modified manganese-containing buffer to encourage transcriptase read-through of modified nucleotides.<br/>
Mutations and deletions at sites of read-through can be mapped by sequencing. Marathon RT enables much longer reads.

Before starting:
--------------------------------------------------------------------------------
* [In-cell crosslinking with SDA](../Chemical-Probing/SDA-Xlinking.md) _(Note: not clear whether this procedure works with SDA crosslinking)_
* [OOPS RNP enrichment](../Chemical-Probing/OOPS-RNP.md)
* [In-cell SHAPE RNA profiling](../Chemical-Probing/In-cell-SHAPE.md)
* [Cell-free SHAPE RNA profiling](../Chemical-Probing/Cell-free-SHAPE.md)

Materials:
--------------------------------------------------------------------------------
  * **Modified RNA** _(and unmodified for control)_
    * 5 pMol of _in vitro_ RNA transcript,
    * 0.5-5 µg of cellular RNA (depending on representation of RNA of interest), **OR**
    * enriched target RNA
  * **2 µM of gene specific primer (_targeted_) or 70 µM (200 ng/µL) of [random nonamer](https://www.neb.com/products/s1254-random-primer-9#Product%20Information) (_for non-targeted_)**
  * **10 mM dNTPs**
  * **5X MRT buffer** _(make fresh and keep on ice)_  
    ◦ 250 mM Tris pH 7.5  
    ◦ 1 M KCl  
    ◦ 25 mM DTT _(Note: Don't use DTT that has been freeze-thawed more than once.)_  
  * **20 mM MnCl<sub>2</sub>**  
  * **20 U/µl** [**Marathon**](https://www.kerafast.com/productgroup/855/marathonrt-reverse-transcriptase) **Reverse Transcriptase**
  * [**G-50 microspin columns**](https://www.cytivalifesciences.com/en/us/shop/molecular-biology/purification/gel-filtration-columns/illustra-microspin-g-50-columns-p-00056)
 _(for lowly expressed targets and randomer-primed samples)_  
  
Equipment Required:
--------------------------------------------------------------------------------
  * Thermocycler

<br/>

___
Protocol:
--------------------------------------------------------------------------------

**1.** For each sample, combine 6 µl RNA, 1 µl primer, and 1 µl of dNTPs. <br/>Denature at 68-75 °C for 5 minutes, then anneal on ice for 2 minutes.

**2.** Assemble enough RT master mix for each sample, adding manganese only immediately before use:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | MRT buffer | 5X | **4**  µL | 
  | Glycerol | 80% | **5**  µL |
  | MnCl<sub>2</sub> | 20 mM | **1**  µL |
  || **Total** | **10** µL |
  
  **The color should change upon adding MnCl<sub>2</sub>. If it doesn't, you need new NTP minus buffer.**  
  _Note: You can lower the concentration of MnCl<sub>2</sub> to 0.5 µL to accomodate larger RNA volumes._
  
**3.** Mix 10 µL of master mix with 8 µL of each primer-RNA mix and incubate for 2 minutes at 25 °C. 

**4.** Add 2 µL of Marathon RT enzyme to each reaction and incubate at 42 °C for 3 hours:

**5.** cDNA product purification:  
  ◦ For abundant targets, product cDNA can go straight into PCR amplification.  
  ◦ For lowly expressed targets and randomly-primed reactions, buffer exchange with G50 columns.

**(6.)** Dilute randomly-primed cDNA to 34 µL (with water) in preparation for second-strand synthesis.
  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>Next Steps</summary>
  
</p> <a href="../NGS/Second-Strand-Synthesis.md">
Second-Strand Synthesis</a>

</p> <a href="../NGS/Two-Step-PCR-Library.md">
2-step PCR library generation </a>

</details>

<details>
  <summary>More Info</summary>
  
  <a href="https://doi.org/10.1016/j.jmb.2020.03.022">
Original Pyle Lab Marathon RT Protocol</a>  

</details>
