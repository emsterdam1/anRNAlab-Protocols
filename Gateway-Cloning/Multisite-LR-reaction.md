Multisite gateway cloning reaction 
================================================================================
Description: LR Clonase stitches together multiple gene fragments into a single destination vector.

[Go To Protocol](#protocol)

Before starting:
--------------------------------------------------------------------------------
* [pENTR creation from fragment](./pDONR-BP-reaction.md)

Materials:
--------------------------------------------------------------------------------
### Day 1
  * Promoter pENTR (50 ng/µL)
  * Tag pENTR (50 ng/µL)
  * ORF pENTR (50 ng/µL)
  * pDEST destination vector (50 ng/µL)
  * L-R Clonase II Mix (Thermo)

### Day 2
  * Proteinase K (2µg/mL)
  * Ice
  * DH10B competent cells
  * SOC Media
  * LB + antibiotic plates

Equipment Required:
--------------------------------------------------------------------------------
### Day 2

  * 37 °C shaker
  * 42 °C water bath

<br/>

<br/>

<br/>

<!-- Use <br/> to go to next page -->
___
Protocol:
--------------------------------------------------------------------------------
### Day 1
1. Mix desired combinations of pENTR and pDEST vectors, adding LR clonase last:

  | Component | Concentration | Quantity | 
  | ---------: | ---------: | :---------- |
  | Promoter | 50 ng/µL | **1**  µL |
  | Tag | 50 ng/µL | **1**  µL |
  | ORF | 50 ng/µL | **1**  µL |
  | pDEST | 50 ng/µL | **2**  µL |
  | ddH2O || **3**  µL |
  | LR Clonase II|| **2**  µL |
  || **Total** | **10** µL |
              
 2. Incubate samples at Room Temperature overnight.

### Day 2

3. Add 1 µL of Proteinase K and incubate 15 min at 37 °C.

4. For each reaction, thaw 20 µL of DH10B cells on ice (less than 5 min).
 * _Note: If one construct in a group yields almost no colonies, using 2x cells (and reagents) can double the yield._

5. Add 2 µL of each reaction to 20 µL of thawed cells. Incubate on ice for 20 min.

6. Heat shock cells in 42 °C water bath for 45 sec. Immediately return to ice for 2 min.

7. Add 80 µL of SOC media to each batch of cells. Incubate for 1 hr shaking at 37 °C.

8. Plate cells onto LB plates with respective antibiotics and incubate overnight.
 * _Note: grow at 37 °C for bacterial and mammalian expression vectors, 30 °C for lentiviral vectors._<br/>_Multi-site cloning is inefficient, few colonies grow up. Be sure to test multiple clones._</br>_Linearizing the destination vector can improve efficiency of the LR reaction._
 
 * _Note: For restriction digest validation of product of pDEST663 and pENTR(259,235,221), cut with EcoRV, BstZ17I, and BsrGI._

<details>
  <summary>Next Steps</summary>
  
</p> <a href="../General/Note-On-Minipreps.md">
GeneJet Plasmid Miniprep</a>

</p> <a href="../General/Restriction-Digest.md">
Restriction Digest </a>

</p> <a href="https://www.sigmaaldrich.com/content/dam/sigma-aldrich/docs/Sigma/Bulletin/2/na0200bul.pdf">
GenElute HP MidiPrep</a>

</details>

<details>
  <summary>More Info</summary>
  
  <a href="https://www.thermofisher.com/us/en/home/life-science/cloning/gateway-cloning/multisite-gateway-technology.html">
Thermo Website</a>  

</details>
