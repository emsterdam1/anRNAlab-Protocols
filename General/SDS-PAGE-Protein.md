SDS-PAGE for protein
================================================================================
Description: A polyacrylamide matrix and electric current is used to separate proteins within a mixture.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [Whole Cell lysis](../Proximity-Labeling/Whole-Cell-Lysis-RIPA.md)

Materials:
--------------------------------------------------------------------------------
  
  * Cell lysate
  
  * 4-12% gradient polyacrylamide gel (variety of sizes)  
    ◦ [10-well](https://www.thermofisher.com/order/catalog/product/NP0335BOX?SID=srch-srp-NP0335BOX#/NP0335BOX?SID=srch-srp-NP0335BOX), 1.5 mm, load volume 37 µl  
    ◦ [15-well](https://www.thermofisher.com/order/catalog/product/NP0336BOX?SID=srch-srp-NP0336BOX#/NP0336BOX?SID=srch-srp-NP0336BOX), 1.5 mm, load volume 25 µl  
    ◦ [18-well](https://www.bio-rad.com/en-us/sku/3450124-4-12-criterion-xt-bis-tris-protein-gel-18-well-30-ul?ID=3450124), load volume 30 µl  
    ◦ [26-well](https://www.bio-rad.com/en-us/sku/3450125-4-12-criterion-xt-bis-tris-protein-gel-26-well-15-ul?ID=3450125), load volume 15 µl  
  
  * 1 M DTT (20X) or 0.5 M [TCEP (10X)](https://www.thermofisher.com/order/catalog/product/77720#/77720)
  
  * SDS Loading buffer ([4X LDS](https://www.thermofisher.com/order/catalog/product/NP0007#/NP0007))
  
  * Molecular weight ladder ([Pageruler Plus](https://www.thermofisher.com/order/catalog/product/26619#/26619), [Precision Plus](https://www.bio-rad.com/en-us/sku/1610374-precision-plus-protein-dual-color-standards-500-ul?ID=1610374))<br/>_Note: ladders run [differently](https://assets.thermofisher.com/TFS-Assets/LSG/figures/BN0810112-LadderMarkers.jpg-650.jpg) depending on the gel buffer system._
  
  * **20X MOPS-SDS Running Buffer** [(Boston Bioproducts, pH 7.7)](https://bostonbioproducts.com/products/mops-sds-running-buffer-20x-bp-178)  
    ◦ 1 M MOPS  
    ◦ 1 M Tris-Base  
    ◦ 20 mM EDTA  
    ◦ 2% SDS  
  
Equipment Required:
--------------------------------------------------------------------------------

  * Heat block (70 °C)
  
  * Gel electrophoresis apparatus (varying manufacturer's and setups)
  
  * power supply

<!-- Use <br/> to fill in first page -->

___
Protocol:
--------------------------------------------------------------------------------

**1.** Prepare ~ 500 mL of 1X MOPS SDS Running buffer per rig (dilute in ddH<sub>2</sub>O).

_**optional**_ If samples are to be labeled (for example with [HaloTag ligand](./Labeling-HaloTag-Samples.md)), perform this labeling before denaturation.

**2.** Prepare each sample with reducing agent and SDS Loading Buffer. <br/>_(for example, 18 µl Sample + 3 µl 0.5 M TCEP + 7 µl 4X LDS)_

**3.** Denature proteins at 70 °C for 10 minutes. Also denature an aliquot (3 µl per gel) of ladder for at least 5 minutes.

**4.** **Prepare gels:** Remove wrapping, rinse in ddH<sub>2</sub>O, and remove comb and seal covering the gel bottom.<br/>Place gels into the electrophoresis apparatus, ensuring the wells are facing the chamber where current is applied.<br/>The electrophoresis chamber must be closed (use of a buffer dam is required when running 1 gel).
    
**5.** Fill the inner (for current) and outer (for heat transfer) chambers of the electrophoresis apparatus with 1X MOPS running buffer.<br/>
The inner chamber should not leak. Use a syringe needle or pipette to flush the wells of build-up.

**6.** Spin down samples at 15,000 x g to pellet any aggregate material.
  
**7.** Carefully load each sample into the wells, including a well with 2.5 µl of ladder. <br/>_Note: LDS can be added to empty wells to prevent too much well spreading. Spreading will also occur if sample buffers vary significantly._

**8.** Connect the gel apparatus to a power supply and run at 120V for about 2 hours (to run the dye off).<br/>_Note: More buffer for heatsink in the outer chamber enables higher tolerated current without melting the gel, but this must be tested for each apparatus._

**9.** **Disassemble gels:** Disconnect the power supply and remove the gels. <br/> Use a tool to break open the gels and cut off wells and other extrusions. <br/> The gel needs to be able to lay flat for direct imaging or western transfer.

<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->

<details>
  <summary>More Info</summary>
  
  <a href="https://en.wikipedia.org/wiki/SDS-PAGE">
Wikipedia</a>  

</details>

<details>
  <summary>Next Steps</summary>

</p> <a href="./Western-Blotting.md">
Western Blotting</a>

</details>
