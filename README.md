Quick and dirty investigation into original 1987 IBM Personal System/2 Display Adapter aka very first VGA card https://www.minuszerodegrees.net/video/IBM%20Announcement%20Letter%20187-054.txt https://upload.wikimedia.org/wikipedia/commons/3/3f/IBM_VGA_graphics_card.jpg

My original assumption was that IBM "simply" consolidated EGA CRT Controller (CRTC), Timing Sequencer (TS), Attribute Controller (ATC)
and two GDCs into one huge ass ~200 pin LSI and called it a day. This would mean virtual 4 banks of 64KB physically organized as one big 32bit pool.
EGA implementation is documented in IBMs original diagrams and Tube Times fantastic reversed pcb https://github.com/schlae/EGACard.
Original EGA used two LSI GDCs (Graphics Data Controllers) each controlling 4 ram chips and 16bit of data bus giving it combined 32bit data bus.

Tracing visible tracks confirms it. Original IBM VGA implementations didnt differ logically from EGA.
