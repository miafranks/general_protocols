# Ammonium Assay Plate Reader
Holmes et al (1999) A simple and precise method for measuring ammonium in marine and freshwater ecosystems. Can J. Fish. Aquat. Sci. 56: 1801-1808

Ref from Zoey: https://www.protocols.io/view/measuring-ammonium-nh4-concentrations-in-water-sam-5qpvobb3zl4o/v1?step=6

pandoc Ammonium_Assay_Plate.md -o Ammonium_Assay_Plate.pdf --pdf-engine=lualatex -V geometry:margin=1in

### Materials 
* 10x 50ml Falcon Tubes
* 15ml Falcon tubes
* 200 and 1000 uL filter tips
* 200 and 1000 uL pipettes
* Microcentrifuge tubes
* Tube racks
* Culture Tubes
* Kim Wipes
* Stir bar
* 1x 1L glass schott bottle
* 1x 125ml glass schott bottle
* 1x 1L+ dark nalgene bottle
* Plate reader
* 96-well microplate with lid, black (preferable)

### Chemicals 
* Anhydrous Sodium Tetraborate
   * CAS 1330-43-4
   * MW 201.22g/mol
   * Store in hazardous chemical shelf
* Anhydrous Sodium Sulfite
   * CAS 7757-83-7
   * MW 126.04g/mol
   * Store in chemical shelf 
* OPA (Phthaldialdehyde)
   * CAS 643-79-8
   * MW 134.13g/mol
   * Store in fridge in secondary containment 
* Ammonium Chloride
   * CAS 12125-02-9
   * MW 53.49g/mol
   * Store in chemical shelf 
* Ethanol (200% Proof)
   * CAS 64-17-5
   * MW 46.07
   * Store in flammables cabinet
* Ammonium Standard for IC
   * 1000mg/l / 55mM 
   * Store in chemical shelf

### Reagent Preparation
1. Borate Buffer (Separately make 2x1L)
   1. In a schott bottle, add 40g of Sodium Tetraborate and 1L of MilliQ Water
   2. If not dissolving, mix on stir plate
2. Sodium Sulfite Solution
   1. In a schott bottle, combine 1g of sodium sulfite and 125 mL of MilliQ Water
   2. Shake to mix
   3. Stable for ~1 month, then discard
3. OPA Solution 
   1. Cover a 50ml falcon tube with aluminum foil
   2. Add 2g OPA to 50ml of ethanol, vortex
   3. Keep in dark until making working reagent
4. Working Reagent
   1. In a dark polyethylene/nalgene bottle, add all (1L) borate buffer solution
   2. Add 5mL of the sodium sulfite solution
   3. Add 50mL of OPA solution, invert to mix 
   4. Let it age for three days before use
   5. Store in the dark and/or fridge, date, and discard after 3 months
   6. Final concentrations:
      1. borate buffer (40 g·L–1, 21 mM)
      2. sodium sulfite (40 mg·L–1, 0.063 mM)
      3. and OPA in ethanol (50 mL·L–1)
5. Primary Working Stock for Ammonium Chloride (10mM) (IF OUT OF AMMONIUM STANDARD FOR IC)
   1. Take care to avoid contamination as much as possible
      1. Wash pipette tips 2x with MQ water 
   2. Rinse 50ml falcon tube 3x with MQ water
   3. Combine 50ml MQ water with 26.75mg of ammonium chloride (0.010mol/L* 53.49g/mol* 0.050L)
   4. Determine the actual final concentration
      1. Ammonium chloride added __________mg / (53.49g/mol * 50ml) *1000 = Final concentration _______ mM
   5. Filter to sterilize and store in fridge
6. Make Process Blank
   1. Rinse a 50ml falcon tube 3x with MQ water
   2. Fill it with MQ water to the freeze line
   3. Place in -80 freezer
   4. Treat as a sample for processing and use it to determine background fluorescence 

### Material Preparation 
1. Wash Pipette tips with MQ water
2. Secondary Working Stock for Ammonium (100uM) (USING STANDARD)
   1. Rinse 50ml falcon tube 3x with MQ water
   2. Fill with 50ml MQ water
   3. Add 90.9ul of Ammonium standard for IC (55mM) to tube
   4. Vortex
3. Secondary Working Stock for Ammonium (100uM) (USING PRIMARY WORKING STOCK)
   1. Calculate volume of primary stock needed
      1. Primary stock conc. __________ mM (X volume_______ml) = 0.1mM(50ml)
      2. Ex. If primary stock is 10mM, X = 0.5ml or 500ul
   2. Combine primary stock volume with up to 50ml of MQ water (Ex. 500ul primary stock + 9.5ml MQ)
4. Precondition tubes and pipette tips
   1. Wash 8x 50ml falcon tubes, 15ml falcon tubes (enough for all samples), the cuvette, and any potential pipette tips with Working Reagent
   2. Leave overnight
   3. Rinse with MQ water and leave to dry
   4. All times after first conditioning, WR rinse isn't required 
5. Standard Preparation
   1. Label 10x 50ml tubes from 1-10 with the below concentrations
   2. Label 9x50mL centrifuge tubes as follows:
     1. 10µM
     2. 5µM
     3. 2.5µM
     4. 1.25µM
     5. 0.625µM
     6. 0.3125µM 
     7. 0.15625µM
     8. 0.078125µM
     9. 0.0390625µM
     10. 0µM
   3. Fill tubes 2-10 with 25ml MQ water
   4. To make the first concentration, combine 5ml of the 100uM secondary working stock with 45ml MQ water
   5. Vortex
   6. Take 25ml from the 10uM tube and combine it with the 25ml MQ water in tube #2.
   7. Vortex
   8. Continue serial dilutions until tube 9. Do not add anyting to tube 10.
  
### Primary Procedure 
1. Defrost samples
2. Label microcentrifuge tubes for all standards and samples
3. Add 1ml of Working Reagent to each tube, working in dim light 
4. Add 250 uL of sample, standard, or MQ water to each corresponding tube
5. Mix (invert or vortex) and incubate in the dark at room temperature for 2-3 hours
6. Transfer 250uL of each reaction to triplicate wells of a 96-well microplate and measure fluorescence on plate reader
7. Turn on plate reader prior for warm up time 
8. Read plate at 350±9 nm excitation and 422±20 nm emission (fluorescence top mode, manual Z-position set to 24995 um, 25 flashes, manual gain of 100, 20 us integration time)

### Analysis 
1. Subtract the fluorescence values of the samples mixed with MQ water or borate buffer instead of the Working Reagent (sample blanks) from the corresponding reacted sample fluorescence’s (= corrected sample fluorescence)
2. Subtract the average fluorescence of the MQ water tubes (i.e., 0uM ammonium) mixed with borate buffer instead of Working Reagent (standard blanks) from the fluorescence values of all the standards
3. Plot corrected fluorescence (y) vs. concentration (x) for all standards to establish a standard curve with linear regression
4. Use the equation of the standard curve to calculate sample concentration from fluorescence

### Waste Protocols 
1. Make a waste container to dispose of all liquids 
