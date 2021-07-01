# H<sub>2</sub>S production
Instructions for synthesizing H2S to be used for trapping RaSH.

**Warning:** The following chemistry should only be done under the protection of a fume hood! H2S is highly toxic even in small quantities.
## Reference Video 
This video explains how to make H<sub>2</sub>S and is what we followed in our procedure.
https://www.youtube.com/watch?v=cRtsexmFO4s



## Parts 

2x Ring Stand

1x Three Necked Flask https://www.sigmaaldrich.com/US/en/product/aldrich/synf431100?cm_sp=Insite-_-caContent_prodMerch_gruCrossEntropy-_-prodMerch10-1

1x Addition Funnel https://www.sigmaaldrich.com/US/en/product/aldrich/z548693

1x A Dozen Keck Clamps https://www.sigmaaldrich.com/US/en/product/aldrich/z150428

1x Glass Stopper https://www.sigmaaldrich.com/US/en/product/aldrich/cls757514

2x Synthware™ 90 degree vacuum adapter with glass stopcock https://www.sigmaaldrich.com/US/en/product/aldrich/syna751420?cm_sp=Insite-_-caContent_prodMerch_gruCrossEntropy-_-prodMerch10-3

1x 50 mL graduated cylinder

1x Long glass straw (anything that can get H2S to the bottom of the graduated cylinder.)

2x CF Valve

3/8 in tubing and 1/4 in tubing

![hydrogen-sulfide-glassware-setup](https://user-images.githubusercontent.com/59063892/124081631-a3ecea80-da00-11eb-8b3f-7feb92d45f9f.jpg)
## Chemicals

100 g Copper Sulfate Penta Hydride

30 mL 37% HCl

30 g Iron(II) Sulfide

## Procedure

1) Put one H<sub>2</sub>S detector in the fumehood, and a second outside of the fumehood.
2) Fill a graduated cylinder with 50 mL of DI water. Put 21 g of CuSO4 into the graduated cylinder. Stir the solution with the glass straw to dissolve until saturated.
3) Put 5 g of FeS into the three-neck flask.
4) Make sure that the addition funnel valve is closed, and replace the funnel with the addition funnel.
5) Add 10 mL of saturated HCl into the addition funnel. This amount of HCl is estimated to make 1-2 L of gaseous H<sub>2</sub>S.
6) Place the base of the three neck flask in an ice bath. We do this to cool the HCl during the reaction so that HCl vapor is produced in smaller quantities relative to H<sub>2</sub>S than without an ice bath.
7) Close the valve connecting the three-neck flask with the CF valves, and open the valve connecting the argon to the three-neck flask.
8) Disconnect the argon hose and turn the argon valve on the cylinder to provide a gentle argon flow. Test for flow through the hose. Reconnect the hose and run argon through the three-neck flask with no cap on the addition funnel for about a minute. After that, turn off the argon and put the cap onto the addition funnel without a keck clamp, this is important as the cap (without a clamp) can release any excess pressure. 
9) Make sure that the CF valves are open, and open the valve connecting the three-neck flask to the CF valves. Turn on argon until the system is entirely flushed.
10) Turn off argon, and close the valve connecting the three-neck flask to argon.
11) Open the addition funnel valve slowly to introduce HCl into the three-neck flask to react with FeS. You should see bubbles in the CuSO<sub>4</sub> solution, and after a ~minute black precipitate will form in the solution. Close the addition funnel valve, and when bubbles are no longer forming, close off the two CF valves simultaneously. Take the glass cap off of the addition funnel.
12) Undo the KF connections around the two CF valves.
13) Blow out residual H<sub>2</sub>S in the two CF to KF connectors with N<sub>2</sub>.  The CF valves now contain H<sub>2</sub>S between them and may be removed from the fumehood for use with UHV experiments.
14) Open all valves on the three-neck flask and leave the addition funnel valve closed. Remove the cap on the addition funnel and flush with N<sub>2</sub>.
15) Pour residual HCl from the addition funnel into the HCl waste bottle and dilute with water.
16) Add water through a funnel into the three-neck flask, and pour the solution into another waste bottle.
17) Pour the CuSO<sub>4</sub> solution (with precipitate) into a separate waste bottle.
18) Clean all glassware.


# RaSH<sup>+</sup> production
Instructions for making RaSH<sup>+</sup> by leaking H<sub>2</sub>S gas into the vacuum chamber.

## Parts

3x CF valves

1x 1.33 in CF "T"

1x 1.33 in CF blank

1x CF 1.33 to KF16 converter

1x slow leak valve

1x Turbo Pump

KF16 tubing

CF 1.33 in tubing

![vacuum_setup](https://user-images.githubusercontent.com/59063892/124167948-5781c900-da59-11eb-8e74-a0573aa6c747.png)

## Procedure
1) By following the previous procedure, we were able to securely store ~50 cm<sup>3</sup> of H<sub>2</sub>S gas between two closed CF valves (blue square in the image above). With the valves still closed, remove the CF to KF converters on either end of the CF valves from the H<sub>2</sub>S production procedure. 
2) On one end of the CF valves, bolt on a 1.33 in CF blank. On the other end, bolt on a 1.33 in CF 'T' piece. 
3) Working on the 'T' piece, attach one open end of the 'T' to a CF valve, and the other end of the 'T' to a CF tube connected to the slow leak valve on the ion trap vacuum system. Then, using a CF to KF converter, attach KF16 tubing to the new CF valve, and connect the other end of the tube to a turbo pump. 
4) With the leak valve closed, and the H<sub>2</sub>S CF valves closed, open the CF valve that connects to the turbo pump. Turn on the turbo pump, and pump down the system until pressure is around 1x10<sup>-4</sup> mbar. 
5) Close the CF valve to the turbo pump, and turn off the turbo. 
6) Open the CF valve that connects the CF 'T' and the precision leak valve. There should now be a throughline for the  H<sub>2</sub>S to get to the leak valve on the trap.  The H<sub>2</sub>S pressure will depend on the length of the CF tube used, but should be at least a factor of 5 less than 1 atm. 
7) Trap Ra ions. Then, by slowly opening the precision leak valve, introduce  H<sub>2</sub>S into the trapping volume. Look for gas collisions on the imaging CCD and wait for a dark ion to be produced. Use OMS to confirm RaSH<sup>+</sup> is the dark ion. 

## Confirming RaSH<sup>+</sup> production

We use Optical Mass Spectrometry (OMS), which can realize sub-dalton resolution, to identify dark ions in our trap. https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.023002
<img width="945" alt="OMS_github" src="https://user-images.githubusercontent.com/59063892/124172376-98c8a780-da5e-11eb-87de-84c6e35ea9ee.png">

Figure: An illustration of OMS on an arbitrary dark ion trapped between 2 "bright" Ra<sup>+</sup> ions.
 
We begin with a chain of 2 or 3 Ra<sup>+</sup> ions. Then, we leak in H<sub>2</sub>S gas (using the procedure above) and wait for one of the ions to go dark (depicted as a black box with a question mark in the figure above). We detune our 1079 nm Ra<sup>+</sup> repumping laser, which causes "local heating" and "gloabl cooling", which causes our ion chain to oscillate axially in the trap at a secular frequency of the trapped ions. 

When an ion goes dark, we immediately perform OMS and record an FFT of the axial oscillation frequency. We continue to do this periodically, (about every 5 minutes), in order to check if there has been any drift of the axial frequency. We monitor the dark ion until it dissociates, and as soon as the dark ion dissociates, we perform OMS on the the chain of bright ions. We use the data from the post-dissociation OMS FFT to calibrate the final dark ion OMS FFT, and end up with the following plot:
![RaSH_github](https://user-images.githubusercontent.com/59063892/124175841-f4952f80-da62-11eb-85fb-e6cd5a95b95e.png)

**With this plot, we can see that the dark ion has a mass of roughly 259 amu, equal to 226+33 (SH = 33 amu). This confirms RaSH<sup>+</sup> synthesis!**

