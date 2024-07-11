Near IR Northern Blotting of RNA
================================================================================
Description: Detect RNA targets in a mixture with near IR probes.

Materials:
--------------------------------------------------------------------------------
  **Denaturing Agarose Gel**  
  * Concentrated RNA sample (at least 10 µg of total RNA)
  * Agarose
  * Formaldehyde (37 %)
  * Glycerol
  * [GelRed or GelGreen Nucleic Acid Gel Stain](https://biotium.com/technology/nucleic-acid-gel-stains/gelred-gelgreen-dna-gel-stains/)
  * **[10X MOPS RNA Running Buffer](https://www.thermofisher.com/order/catalog/product/AM8671) (pH to 7.0 with NaOH)**  
    ◦ 200 mM MOPS (3-(N-morpholino)propanesulfonic acid)  
    ◦ 50 mM NaOAc  
    ◦ 10 mM EDTA

  **ElectroBlotting**   
  * **[5X TBE Running Buffer (Tris-borate-EDTA)](https://www.thermofisher.com/order/catalog/product/LC6675) (pH to ~8.3)**  
    ◦ 450 mM Tris base  
    ◦ 450 mM Boric acid  
    ◦ 10 mM EDTA   
  * 3MM Chromatography Whatman paper (8 sheets and 1 longer wick)
  * paper/sponges for transfer stack
  * [nylon membrane](https://www.cytivalifesciences.com/en/us/shop/molecular-and-immunodiagnostics/genomic-consumables/nytran-supercharge-spc-blotting-membranes-p-04733)
  * **[20X SSC Buffer](https://www.takarabio.com/products/protein-research/sds-page-and-western-blotting/buffers-and-powders/ssc-powder) (pH to 7.0 with NaOH)**  
    ◦ 300 mM sodium citrate  
    ◦ 3 M NaCl  
    
  **Probe hybridization**  
  * Near IR Northern probes (1 µM)
  * [Hybridization buffer](https://www.thermofisher.com/order/catalog/product/AM8677)
  * 20 % SDS solution
  * 1X PBS pH 7.6
    
Equipment Required:
--------------------------------------------------------------------------------
  * Agarose Gel Rig
  * Fume Hood
  * Electrophoretic transfer apparatus
  * Hybridization oven with rotation
  * Gel/Blot fluorescent imager

<br/>

___
Protocol:
--------------------------------------------------------------------------------

**Part 1: Denaturing Agarose gel (~3 hours)**  

**1.** For a 100 ml volume gel, combine the following and melt:  
  
  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | agarose | | **1**  g | 
  | MOPS RNA Running Buffer | 10X | **10**  mL |
  | Water | | **74**  mL |
  || **Total** | **84** mL |
  
**2.** In a fume hood, add 16 mL of 37 % formaldehyde to the mixture and cast gel.<br/>
_Gel sets in ~30 minutes._

**3.** Prepare 5X Sample buffer (mix 500 µL of 10X MOPS with 500 µL of glycerol)

**4.** Assemble enough 2X RNA Loading Buffer per RNA sample as follows:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Sample Buffer | 5X | **4**  µl | 
  | Gel stain | 100X | **0.8**  µl |
  | Formaldehyde | 37 % | **3.35**  µl |
  | Water | | **1.85**  µl |
  || **Total** | **10** µl |

**5.** Mix 10 µl of RNA sample (at least 10 µg) with 10 µl of 2X Loading Buffer.<br/>
Denature RNAs at 70 °C for 5 minutes and cool at 0-4 °C for 2 minutes.

**6.** Load samples (and usually a ladder). Run gel at 110 V for 1.5 hours.<br/>

**7.** Rinse gel 3 times for 10 minutes in (MilliQ) water (Rinses are formaldehyde waste). <br/> Image gel to ensure even loading before assembling Northern transfer.

**8.** Soak gel in 5 volumes of 0.05 N NaOH for 20 minutes. <br/> _Note: This fragments RNA, allowing RNAs > 2000 nt to transfer better._

**9.** Discard NaOH solution.<br/> Equilibrate gel in 10 volumes of transfer buffer (0.5X TBE) for 20 minutes.



**Part 2: Electroblotting Transfer to nylon membrane (~45 minutes)** 

**9.** Assemble a transfer "sandwich" for electroblotting. <br/> anode (-) > 4 x wet whatman > nylon membrane > gel > 4 x wet whatman -> cathode (+) 

**10.** Transfer at 200 mA constant current for 30 minutes in 0.5X TBE running buffer.



**Part 3: Preparation for Northern blotting (~45 minutes)** 

**11.** Carefully disassemble the transer. <br/> _Note: you can save the gel for imaging to confirm transfer._ 

**12.** Gently wash blot in 2X SSC buffer for 5 minutes with RNA side up. <br/> _Note: the RNA is associated with the blot, but not attached._

**13.** Set the blot on whatman paper (RNA side up). <br/> Dry in the hyb oven for 30 minutes at 65 °C.

**14.** Expose blot twice to 120 mJ/cm<sup>2</sup> of 265 nm UV in the crosslinker. <br/> _Note: Now the RNA is irreversibly attached to the blot._ <br/> _The blot can be stored between sheets of whatman paper long term in a dessicator._

**Part 4: Northern blotting (~1 hour + overnight)** 

**15.** Warm 10 mL of Hyb buffer per 100 cm<sup>2</sup> blot for 15 minutes at 65 °C. <br/> Place blot inside a glass hyb tube with the RNA side facing inwards.

**16.** Add warm hyb buffer to blot and block for 30 minutes at 65 °C.

**17.** Directly to the hyb liquid (not the blot), add 1 µl of 1 µM probe per 10 mL buffer. <br/> Incubate overnight in the dark with rotation at 65 °C. <br/> _Note: if re-using probe, replace the prehybridization buffer with probe already in hyb buffer._

**Part 5: Washes and imaging (~1 hour)** 

**18.** Collect hyb buffer + probe from the tube (probe can be saved at -20 °C)

**19.** Wash blot twice in 2X SSC + 0.1 % SDS for 15 minutes at room temperature (leave chamber open). <br/> _Note: any volume that covers the inside of the tube is fine (25 mL is good)._

**20.** Wash once in 1X SSC + 0.1 % SDS for 15 minutes at up to 65 °C (close chamber again).

**21.** Before imaging, rinse the blot for 5 minutes in 1X PBS. <br/> _Note: Blots can be stored between whatman paper in a dessicator long term._
  
<!-- The text below creates dropdown lists for links to next steps or hyperlinks -->


<details>
  <summary>More Info</summary>
  
  <a href="https://doi.org/10.1261%2Frna.068213.118">
Original IR Northern Paper</a>

</details>
