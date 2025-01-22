# Hyperion mini

original Hyperion circuit by devi ever

## why 
I wanted to put a fuzz circuit between the potentiometers of my jaguar's rhythm circuit. The hyperion proved ideal. This kicad schematic can be used to produce PCBs suitable for this task. 

## bom per circuit

Components you might already have if you're converting an existing rhythm circuit:
- 2x rhythm circuit potentiometers with roller knobs (see section below on values)
- 1x rhythm circuit roller knob bracket

Through hole components:
- 1x 1k resistor 
    - this will be mounted on the RC's tone pot for the pregain control
- 2x NPN transistors (i used mpsa18)
- 1x PNP transistor (i used 2n5087)

SMD components (all 1206 sized, for ease of hand-soldering)
- 4x 100n capacitor 
        - consider c0g caps if microphonics are a concern. i used x7r and liked the results
- 2x 10k resistors
- 2x 2.2M resistors

## rhythm circuit potentiometer values

You probably won't be able to use 100k potentiometers on the rhythm circuit bracket. Fender's rhythm circuit pots have weirdly small sized shafts, so if you're using official parts your options are either 1M or 50k. I used 2 x 50k, and thought it was fine. If you'd like to use 100k pots to exactly match the schematic, you will probably need to acquire an aftermarket rhythm circuit bracket with roller wheels that can accommodate standard sized potentiometer shafts. If you need to choose to use the stock 1M and 50k potentiometer values, you might want to audition whether you prefer having the higher value as your pre-gain or volume control.