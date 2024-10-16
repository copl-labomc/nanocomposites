Short naming system of nanocomposites to brainstorm! Something like comp3D-PS, nano3D-PS, poly3D-PS, PolyOrigin, NanoOrigin, CompOrigin, etc.

<!--- Published in:... Cite main paper here instead of at the end? --->

_**For ~10 cm long polystyrene preforms x 13 mm diameter**_ (AP: 12.7 mm for 1/2" ID of PMMA tubes.)

## Specific Safety Measures ##
- When modifiying the core of the protocol, never leave the polymerization completely unattended until the substance is significantly viscous in case of <a href="https://sciencing.com/runaway-polymerization-7556.html">runaway polymerization</a> requiring to immediately turn off heating.
- Check for slow bubbles in the bubbler when opening the inert gas valve. Excessive pressure could build up in the manifold in their absence. <!--- TODO : revise once we get the proper pressure regulator for the nitrogen line that should read between 3 and 5 psi --->
- Do not forget to open the valve on the gas evacuation pipe before turning on the oven, then and close it at the end of the manipulations.
- Never open the oven at high temperature to avoid a thermal shock that could break glass.

<!--- UNDER CONSTRUCTION, work with Stéphane & David là-dessus, a link to a COPL.ULaval sharepoint intranet would be most appropriate!
All general safety guidelines(?check proper word) from <a href="...">SIMDUT</a>, <a href="...">SSP</a>, <a href="...">COPL</a> and <a href="link the appropriate wikiOMC section">labOMC</a> continue to apply of course.
TODO : check and implement ULaval's rules for unattended experiments, develop section Lab safety for Jupyter Notebook, including this <a href="http://www.ilpi.com/safety/index.html">http://www.ilpi.com/safety/index.html</a> as a resource
--->

<!--- TODO : Add Cie provider names + grades of chemicals--->
## Chemicals & Furnitures ##
- 10 mL of purified styrene (AP: 8 mL, especially since 10 mL doesn't fit into the size of test tube specified below!) 
- Precipitated nanosemiconductors (NSCs) in the desired amount<sup>*</sup>
- 60 mg of benzoyl peroxide as polymerization initiator (Luperox A98) (AP: 120 mg per 15 mL styrene, OMT: initiator-free variant)
- Fume hood
- Vortex mixer
- Oven
- Ultrasonic bath with heating
- Venturi pump : filtering flask connected to a vacuum ejector on the water tap
- Light inert gas flow, but it can be hard to adjust directly on the nitrogen line in a fume hood, so a valved bubbler can be employed <!--- TODO : revise once we get the proper pressure regulator for the nitrogen line that should read between 3 and 5 psi --->
- Syringe needles
- 13 mm x 100 mm glass test tube with a fitting airtight septum
- Mineral oil bath with heat-resistant means to hold the tube
- Micropipettes and suitable tips
- Solvents

_N.B. The residual liquid with the NSC precipitate is volatile and may cause some bubbles in the plastic in the end. If this becomes a problem, the liquid can be left to evaporate as long as the NSCs are not dryed out completely and thus overly exposed to oxygen. A NSC powder could be obtained by evaporation under inert atmosphere in principle, but at this point, we haven't tested how detrimental this is to the photoluminescence (PL)._ 

<!--- <sup>*</sup> TODO : annotate include here the figure in our paper for optical density (?check OD def) + cQD concentration of increasingly orange samples <img src="/assets/original_nanocomposite.gif" alt="Optical density of nanocomposites with varying nanosemiconductor concentration"> N.B. if I put the assets folder high up, the asset link might need some dots --->

## Dispersion of Nanosemiconductors in the Monomer ## 
- Add a known volume of purified liquid monomer to the centrifuge tube of precipitated NSCs.
- Agitate with the vortex mixer and/or hold the tube in an ultrasonic bath briefly to improve NSC dispersion.
- Pour the mixture into the glass test tube.
- Repeat the previous 3 steps until the NSCs are rinsed out of the centrifuge tube.
- Complete pouring of the purified monomer directly in the glass test tube up to the selected volume.
- Add the initiator Luperox A98 to the tube and agitate with the vortex.
- Close the test tube with an airtight septum that can be pierced by syringe needles.

## Degassing & Purging ##
- Put the glass tube under light vacuum with the Venturi pump, with the needle above the liquid level.
- Turn on the heat on the ultrasonic bath and place the tube in it to enhance degassing for a few minutes. Note that the polymerization will already accelerate while heating.
- Bubble inert gas through the mixture for a few minutes, with the metal needle below the mixture level and adding a second one above the liquid as exhaust. 
- Repeat at least twice to minimize oxygen in the mixture. <!--- TODO : find out if it's better to finish under vacuum or under nitrogen considering light diffusion on dissolved gasses in fiber, potential glass tube breaking and dissolved gases that could lead to bubbles during fiber drawing, then adjust the last step here if needed. --->
- Clean the bubbling needle with toluene, and the vacuum one as well if it touched the mixture.

_N.B. This section aims to protect air-sensitive NSCs by displacing oxygen. It can be shortened for preliminary tests when light diffusion (? to check if it's really correlated to oxygen or just any gas like nitogen, then and put explanation at the beginning of sentence) and PL stability of the resulting nanocomposite are not an issue._

## Polymerization Reaction ##
- Keep the test tube under vacuum in the hot ultrasonic bath (∼60 °C) for ~7 h until the mixture has a syrup-like consistency. <!--- TODO merge with next TODO too(!): watch out for potential glass breaking & get a temperature data logger for the ultrasonic bath so we can state an average temperature. (If glass breaking prevents vacuuming all the time and/or we are concious about wasting water, add this step "- Degas one last time for at least 10 min with the tube still in the hot bath using the Venturi pump." and possibly a nitrogen purge if we find out if it's better to finish on this. TODO : If possible, test how long it's actually worth degassing, with a pressure jauge and/or idealy with something like a sensor of oxygen and/or air directly in the mixture, as it will likely tends asymptotically towards a pressure equilibrium and thus not worth pumping forever. That might also help pinpoint the conditions in which the small test tubes tend to break during polymerization :( --->
- Secure the tube in a mineral oil bath with wire or a heat-resistant holder.
- Open the valve on top of the pipe behind the oven to ensure proper evacuation.
- Place the glass tube assembly in the oven.
- Heat at 90°C for ~48 h until fully polymerized. (AP: 90°C for ~48 h, OMT: 140°C for days)
- Progressively cool the oven back down to room temperature before pulling out the nanocomposite and glassware. Note that the oven's timer can stop heating automatically :smiley:.
- Close the exhaust pipe valve.

_N.B. The first step with polymerization starting in the bath is required only for experiments on single NSCs, isolated without aggregates in the nanocomposite._ <!--- Adapt this according to our findings relative to overpressure vs underpressure in the glass tube : Do not skip the following step however, degassing helps to prevent bubbles in the plastic and overpressure from a potential runaway polymerization.--->

<!--- TO DISCUSS WITH AP, OMT, etc. & ADAPT PROTOCOL AS NEEDED : 
- Investigate glass beaking cause: implosion(vacuum underpressure) or explosion (nitrogen over pressure in relation with pkoi y'avait du liquide qui sortait du four avec Arthur, cheminée-exhaust avec aiguille touchait la mixture? pkoi la polymérisation d'Olivier-Michel s'emballait et débordait du tube? P-e la dernière étape en surpression d'azote vs sous vide et/ou il n'y avait pas de cheminée? 
- Investigate the cause of bubble formation at both the nanocomposite and fiber step (if that's really bubbles and not dirt we see in the pictures =p) : Quelle est la contribution de l'humidité adsorbée vs celle des gaz dissous? Est-ce que le recuit des préformes est mieux dans le four sous vide ou sous azote? L'azote est probablement mieux pour ralentir la diffusion d'oxygène, mais p-e plus à risque de laisser des bulles lors du processing des préformes? Ehsan & Frej font du moulage sous vide...
--->

<!--- UNDER CONSTRUCTION :
## Nanocomposite Stripping & Annealing ## 
ARTHUR :  Un recuit durant au moins 24 h à 70˚C est ensuite nécessaire afin de libérer les tensions résiduelles du polymère, de même que pour évacuer l’humidité dans le nanocomposite, susceptible de créer des bullesaux interfaces lors de l’étirage.
OMT : 
- Check with Ehsan for a better word than stripping
- consulter pour réduire les chances de se couper sur des tessons de verre
- four sous vide pour bulles, mais pas trop préparer d'avance pour préserver les NSCs
- Storing preforms: azote mais bulles vs done ones in drawer

### Main Observations ###
- The nanocomposite volume shrinks by ~...% relative to the initial monomer, thus NSC doping concentrations must be re-calculated accordingly. (TODO: evaluate by water dispoacement and check if it tracks with calculations from absorption curves of cQD cores b4 vs after.)
- The quantum yield of CdSe/CdS colloidal quantum dots drops by roughly 35%.
-...
Also list pros and cons of the nanocomposite properties that were characterized, referring & linking to the example sample and research notebook Airtable records.

**References**
- our paper, unless it's at the top, but check it for other refs that should be here
- Francesco Meinardi, Annalisa Colombo, Kirill A. Velizhanin, Roberto Simonutti, MonicaLorenzon, Luca Beverina, Ranjani Viswanatha, Victor I. Klimov, and Sergio Brovelli. _Large-area luminescent solar concentrators based on Stokes-shift-engineered nanocrys-tals in a mass-polymerized PMMA matrix._ Nature Photonics 8(5), p. 392–399 (2014). <a href="https://doi.org/10.1038/nphoton.2014.54">https://doi.org/10.1038/nphoton.2014.54</a>

**Selected resources on nanocomposites** 
- <a href="https://www.mdpi.com/2073-4360/4/1/275">https://www.mdpi.com/2073-4360/4/1/275</a>
--->





<!---------------------------------------------------------------------------------------
TODO : The following needs to be moved in WikiOMC turned into Jupyter Notebook, separated and better organized:
------------------------------------------------------------------------------------------->

<!---
TODO : format references properly
--->
# basic-techniques # (maybe split between basic and intermediate?)

Proper safety and disposal methods must be learned first, study attentively the wikiOMC page <!--- TODO : ...name & link.. + develop a page on cristal growth like the series starting from http://dx.doi.org/10.1002/chemv.201200103 with lamer models as well and more theory :) + a page on polarity vs polarisability 
--->

## Vacuum & cryogenics ##
...safety
TODO: Voir avec Mario pour nous trouver une bonne formation de l'AVS ou autre


## Using a Balance ##
<!---
TODO : add a short text including what is acceptably skipped from the video in our lab
--->
<a href="https://youtu.be/cG6QrqS4ruQ?si=rKG0k026AFvik7i0">https://youtu.be/cG6QrqS4ruQ?si=rKG0k026AFvik7i0</a>

## Using a Vortex Mixer ##
...

## Ultrasonication ##
...

## Using an Oil Bath ##
...Safety.
<a href="https://chem.libretexts.org/Bookshelves/Organic_Chemistry/Organic_Chemistry_Lab_Techniques_(Nichols)/01%3A_General_Techniques/1.04%3A_Heating_and_Cooling_Methods/1.4H%3A_Water_Sand_and_Oil_Baths">https://chem.libretexts.org/Bookshelves/Organic_Chemistry/Organic_Chemistry_Lab_Techniques_(Nichols)/01%3A_General_Techniques/1.04%3A_Heating_and_Cooling_Methods/1.4H%3A_Water_Sand_and_Oil_Baths</a>

## Centrifugation ##
...safety.

- <a href="https://handling-solutions.eppendorf.com/sample-handling/centrifugation/safe-use-of-centrifuges/centrifuge-safety/">https://handling-solutions.eppendorf.com/sample-handling/centrifugation/safe-use-of-centrifuges/centrifuge-safety/</a>
- <a href="https://handling-solutions.eppendorf.com/sample-handling/centrifugation/safe-use-of-centrifuges/basics-in-centrifugation/">https://handling-solutions.eppendorf.com/sample-handling/centrifugation/safe-use-of-centrifuges/basics-in-centrifugation/</a>
- <a href="https://handling-solutions.eppendorf.com/sample-handling/centrifugation/this-and-that/detailview/news/transferring-centrifugation-parameters-from-a-protocol-to-your-own-conditions/">https://handling-solutions.eppendorf.com/sample-handling/centrifugation/this-and-that/detailview/news/transferring-centrifugation-parameters-from-a-protocol-to-your-own-conditions/</a>

## Venturi Effect ##
...
<a href="https://web.uvic.ca/~berryde/techniques/degas.pdf">https://web.uvic.ca/~berryde/techniques/degas.pdf</a>
<!--- TODO : Since pumping and cryogenic techniques seem hard to find (unless I don't have the right keywords?), possibly make a whole wiki section for general degassing and vacuuming, from liguids to vacuum chambers --->

## Cleaning Glassware ##
- NSC synthesis flasks...Bain de bases : KOH + EtOH + 1 ou i-P??OH, I can't read the last one on the pails :(

## Using a Glovebox ##
... safety
<a href="http://www.ilpi.com/inorganic/glassware/glovebox.html">http://www.ilpi.com/inorganic/glassware/glovebox.html</a>


## Using a Schlenk Line ##
... safety. <a href="http://www.ilpi.com/inorganic/glassware/vacline.html">http://www.ilpi.com/inorganic/glassware/vacline.html</a>

Copy pasted from resources, to adapt : To maintain a positive pressure on a reaction that is simply stirring, the bubbler should bubble once every few seconds. A greater flow wastes nitrogen and can bubble away volatile solvents. A lesser flow increases the chances of air diffusing into your apparatus.
To prevent oil or mercury from splashing out of your bubbler, connect a piece of Tygon tubing to the outlet.

- <a href="https://schlenklinesurvivalguide.com/">https://schlenklinesurvivalguide.com/</a>
- <a href="http://www.ilpi.com/inorganic/glassware/index.html">http://www.ilpi.com/inorganic/glassware/index.html</a>

## General Resources ##
- <a href="https://chem.libretexts.org/Ancillary_Materials/Demos_Techniques_and_Experiments/General_Lab_Techniques">https://chem.libretexts.org/Ancillary_Materials/Demos_Techniques_and_Experiments/General_Lab_Techniques</a>
- <a href="https://www.chemistryviews.org/?s=tips+and+tricks&orderby=relevance">https://www.chemistryviews.org/?s=tips+and+tricks&orderby=relevance</a>
- <a href="https://edu.rsc.org/interactive-lab-primer-lab-techniques/115379.subject">https://edu.rsc.org/interactive-lab-primer-lab-techniques/115379.subject</a>



