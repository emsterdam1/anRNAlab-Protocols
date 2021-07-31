Peptide Quantification
================================================================================
Description: Peptide concentration is measured using an amine-reactive fluorescent detection reagent<br/>
that specifically labels the N-terminus of peptides. Labeled peptides are detected at Ex 390nm/Em 475nm.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [Trypsin digestion](./On-Bead-Digestion)
* [C18 cleanup](./C18-Column-Cleanup)
* [Ethyl acetate cleanup](./Ethyl-Acetate-Cleanup.md)

Materials:
--------------------------------------------------------------------------------
  * purified peptide samples
  * MS Loading Buffer in LC-MS grade water  
    ◦ 2% acetonitrile [(ACN)](https://www.fishersci.com/shop/products/pierce-acetonitrile-acn-lc-ms-grade-3/PI85188)  
    ◦ 0.1% formic acid [(FA)](https://www.fishersci.ca/shop/products/formic-acid-optima-lc-ms-grade-fisher-chemical-5/p-3795381)  
  _Example: 979 µl of water, 20 µl of ACN, and 1 µl FA. Store in glass._
  
  * Pierce Quantitative Fluorometric Peptide Assay [(Pierce 23290)](https://www.fishersci.com/shop/products/thermo-scientific-pierce-quantitative-fluorometric-peptide-assay-kit-1/PI23290)  
    ◦ Peptide Digest Assay Standards (0-1000 µg/ml) in MS loading buffer  
    ◦ Fluorometric Peptide Assay Buffer  
    ◦ Fluorometric Peptide Assay Reagent  
  
  
Equipment Required:
--------------------------------------------------------------------------------
  
  * Fluorometer or plate reader that measures fluorescence at or near at Ex 390nm/Em 475nm

<br/><br/><br/>

<!-- Use <br/> to fill in first page -->

___
Protocol:
--------------------------------------------------------------------------------

**1.** Equilibrate assay components to room temperature.

**2.** Make standards in MS loading buffer. A serial 1:1 dilution of 7 concentrations is sufficient.<br/>
Include a max concentration standard (1000 µg/mL) and a buffer background (0 µg/mL) 
  
**3.** Dilute 2-5 µl of samples into 10 µl total of MS loading buffer.

**4.** Load 10 µl of samples/standards into microplate wells and note positions.<br/>
Load replicates for each standard.

**5.** Using a repeater pipette, add 70 µl of Fluorometric Peptide Assay Buffer to each well.

**6.** Using a repeater pipette, add 20 µl of Fluorometric Peptide Assay Reagent to each well.

**7.** Incubate in the dark at room temperature for 5-30 minutes.

**5.** Measure fluorescence at or near at Ex 390nm/Em 475nm for all standards and samples.

**6.** Average measurements for each standard and subtract background absorbance (the 0 standard). Plot normalized averages against concentration.

  *A quadratic can be fitted to the curve to calculate sample concentrations, or concentration can be interpolated linearly between two standard points.* 

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>More Info</summary>
  
  <a href="https://assets.fishersci.com/TFS-Assets/LSG/manuals/23290_quantpeptide_fluor_UG.pdf">
Pierce Quantitative Fluorometric Peptide Assay</a>  

</details>
