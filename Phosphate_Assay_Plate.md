# Phosphate Assay 

Murphy and Riley (1962) A Modified Single Solution Method for the Determination of Phosphate in Natural Waters. Analytica Chimica Acta 27(1962)31-36. 

pandoc Phosphate_Assay_Plate.md -o Phosphate_Assay_Plate.pdf --pdf-engine=lualatex -V geometry:margin=1in

### Materials 
* 15 mL centrifuge tubes (10 for standard curve + # of samples) 
* Pipettes and tips
   * P200 (2x Std curve + # Samples)
   * P1000 (helpful for transfers)
* Cuvettes
   * Disposable plastic cuvettes (one per sample/standard) or
   * Reusable glass cuvette (rinsed thoroughly between reads)
* Tube racks (15 mL)
* Kimwipes
* DI Water Squirt Bottle
* Timer (for 30-minute incubation)
* Aluminum foil
* Ice bucket + ice
* Chemical waste container (Labeled: Phosphate Assay Waste)
* Instrument: Spectrophotometer capable of reading 880 nm
* 1x 1L amber glass schott bottle 
* 1x 100ml plastic bottle 
* 1x 100ml glass schott bottle 
* 1x 100ml amber glass schott bottle 
* 1x 250ml amber glass schott bottle

### Chemicals 
* 10N Sulfuric Acid (1000 mL)
   * CAS 7664-93-9
   * MW 98.08g/mol
   * Highly corrosive, store in acid cabinet
* Ammonium heptamolybdate tetrahydrate
   * CAS 12054-85-2
   * MW 1235.86g/mol
   * In chemicals shelf 
* Potassium Antimony Oxide Tartrate Trihydrate
   * CAS 28300-74-5
   * MW 667.87g/mol
   * In hazardous chemicals shelf
* Ascorbic Acid 
   * CAS 50-81-7
   * MW 176.12g/mol
   * Store in fridge at 4C
* Potassium Phosphate Dibasic
  * CAS 7758-11-4
  * MW 174.18g/mol
  * Store in chemical shelf 

### Reagent Preparation 
1. 9N Sulfuric Acid Reagent (1L)
   1. Place 1L amber glass bottle on ice
   2. Add 250 mL of sulfuric Acid to 750 mL of MQ water. 
   3. Once cooled, it can be stored in the acid cabinet
   4. This is very dangerous, do in the back of the hood, with most protective PPE
2. Ammonium heptamolybdate Reagent (100ml))
   1. Dissolve 9.5g of ammonium heptamolybdate in 100 mL of MQ in a plastic bottle
   2. Solution is good as long as it remains clear
   3. Store in chemical shelf
3. Potassium Antimony Tartrate Triydrate Solution (100ml)
   1. Dissolve 3.25g of potassium antimony tartrate in 100 mL of MQ water in glass schott bottle
   2. Store in hazardous chemical shelf 
4. Ascorbic Acid solution (100ml)
   1. Dissolve 7g of ascorbic acid in 100mL of MQ water in an amber bottle
   2. Store in fridge at 4C, solution is stable when it remains colorless
5. Mixed Reagent 
   1. Add 120ml of 9N sulfuric acid to amber bottle, and stir
   2. Add 45ml of the ammonium heptamolybdate solution
   3. Add 5ml of potassium antimony tartrate solution 
   4. Add 70ml MQ water
   5. Store room temp, solution is shelf stable for months
2. Potassium Phosphate (K2HPO4) Primary Stock
   1. Weigh ~0.5g of K2HPO4 into 50mL Centrifuge tube
   2. Add 50 mL water, vortex
   3. Calculate exact concentration
      1. ________g / ((174.18 g/mol) x 50mL) * 1x10^9 = uM
      2. E.g. If 0.5 g, = 57412 uM

### Materials Preparation
1. Remove samples from -80 freezer, place on ice to thaw
2. Make Working phosphate stock (1000uM)
   1. Make 50 mL of 1000 uM working stock from primary stock, C1V1 = C2V2
   3. Primary Stock Conc _________ uM x ____  mL = 1000uM x 50 mL
      1. E.g. X = (1000*50/57412) = 0.871mL = 871uL
   4. Add 871uL of primarily stock to 49.129mL MQ water
   5. Store in the fridge
3. Label 9x 50 mL centrifuge tubes as follows:
   1. 5uM
   2. 2.5uM
   3. 1.25uM
   4. 0.625uM
   5. 0.3125uM 
   6. 0.15625uM
   7. 0.078125uM
   8. 0.0390625uM
   9. 0uM
4. Add 25mL MQ water to each tube except the 5uM tube.
5. Add 50mL water to the 5uM tubes
6. Add 125uL of the 1000uM Working stock into the labeled 5uM centrifuge tube containing 50mL of water.
7. Vortex
8. Take 25mL from the 5uM tube and add to the “2.5uM” tube. 
9. Vortex
10. Continue, using serial dilutions by adding 25mL of each previous tube to the 25mL of water in the next.
11. Do not add anything to the 0uM standard.

### Primary Procedure 
1. Defrost samples
2. Test 1
   1. Add 200ul of sample/standard/MQ water to the appropriate wells of a clear 96 well plate
   2. Add 30ul of Mixed Reagent to each well
   3. Mix briefly by pipetting (use multichannel pipet)
   4. Add 30ul of Ascorbic Acid to each well
   5. Mix briefly by pipetting (use multichannel pipet)
   6. Be wary of bubbles
3. Test 2
   1. Add 80ul of sample/standard/MQ water to the appropriate wells of a clear 96 well plate
   2. Add 80ul of Mixed Reagent to each well
   3. Mix briefly by pipetting (use multichannel pipet)
   4. Add 80ul of Ascorbic Acid to each well
   5. Mix briefly by pipetting (use multichannel pipet)
   6. Be wary of bubbles 
4. Incubate in the dark at room temperature for 30min
5. Turn on plate reader prior for warm up time 
6. Read absorbance 880nm excitation

### Analysis 
1. Subtract the fluorescence values of the samples mixed with MQ water instead of the Mixed Reagent (sample blanks) from the corresponding reacted sample fluorescence’s (= corrected sample fluorescence)
2. Subtract the average fluorescence of the MQ water tubes (i.e., 0uM phosphate) mixed with borate buffer instead of Mixed Reagent (standard blanks) from the fluorescence values of all the standards
3. Plot corrected fluorescence (y) vs. concentration (x) for all standards to establish a standard curve with linear regression
4. Use the equation of the standard curve to calculate sample concentration from absorbance

### Waste Protocols 
1. All chemical waste can be disposed of in the same container



