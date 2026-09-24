# Entry 3: Finalizing Layout, Stabilizers, and Prepping for Routing

 What i did
Stabilizer Validation:Verified and locked in the placement of all four 2u stabilizer footprints (Backspace, Enter, Left Shift) and the Spacebar stabilizer layout. All footprints are centered with their switches.
 Component Grid: Completely finalized the physical grid layout for all 67-68 keys, diodes, and the top-right rotary encoder. Everything is cleared of structural boundaries.

 Key Design Decisions and Breakthroughs
* The Screen Problem: I spent time experimenting with a portrait 0.91" OLED screen on an extended right-side board. After looking at it in the 3D Viewer and looking at the layout, I realized it created highly congested space next to the knob and left too much awkward dead space on the PCB. 
  Switching up: To make sure I had a clean reliable daily driver that prints easily within standard 3D printing limits, I made the call to delete the screen from this board. 
 Next
Net Classes Configured: Opened File > Board Setup > Net Classes and successfully bumped my default Track Width up from `0.2 mm` to `0.3 mm` for safe manufacturing tolerances.
Routing Strategy: Ready to begin layout routing. I will be running horizontal Row traces on the F.Cu Top Layer - Red and vertical Column traces on the B.Cu Bottom Layer - Green to keep the matrix clean and free of shorts.
