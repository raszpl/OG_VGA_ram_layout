Quick and dirty investigation into original 1987 IBM Personal System/2 Display Adapter aka very first VGA card.
My original assumption was that IBM "simply" consolidated EGA CRT Controller (CRTC), Timing Sequencer (TS), Attribute Controller (ATC)
and two GDCs into one huge ass ~200 pin LSI and called it a day. This would mean virtual 4 banks of 64KB physically organized as one big 32bit pool.
EGA implementation is documented in IBMs original diagrams and Tube Times fantastic reversed pcb https://github.com/schlae/EGACard.
Original EGA used two LSI GDCs (Graphics Data Controllers) each controlling 4 ram chips and 16bit of data bus giving it combined 32bit data bus.

Initial examination of kindly provided PCB photos  makes me question initial assumptions.
