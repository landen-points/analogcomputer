# analogcomputer
This project involves designing and building a simple analog computer capable of solving calculus-based
operations such as integration, differentiation, and summation using op-amp-based circuits to a proof-of-
concept level accuracy. The core components will include TL082 dual op-amps, a variety of passive
components (resistors, capacitors), and voltage regulators.

Instead of using a traditional PCB, the final prototype will be made using paper circuits. Paper circuits are
more DIY friendly, and will be open source. I am also interested in incorporating non-traditional
fabrication techniques as a proof of concept for analog computing. This approach aims to provide a low-
cost, flexible, and rapidly prototyped alternative to standard PCBs, as there is no lead time for PCB
ordering.

I gained inspiration from reading the Art of Electronics Second Edition (Horowitz and Hill) chapter on
op-amp designs for calculus functions (chapter 4), and further research into devices such as the Comdyna
GP-6.

The circuits used in the analog computer are separated by module, so a build can incorporate how ever many of each are desired.

To build a computer of your own:
  1. Print the paper circuit modules located in ./papercircuits to US letter size (8.5x11in) paper
  2. Cut the modules accordingly
  3. Poke holes through lead locations and place components in. Suggested component values are printed on the paper circuit PDFs
  4. Solder them together, using legs or jumpers. Be creative with it
  5. To mount to a panel, I use M3 screws driven directly through the paper circuit and into a wood panel. Leave them as bare paper circuits if desired
  6. Connect a ±12V supply
