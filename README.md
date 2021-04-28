# ACMQ-EDFILW
The EdFil editor can be used to generate the input netlist file for the ASIZ program, other circuit simulators developed by the author, as SENSI, IFFT, MNAE, MNAV, etc., and also for other programs, even SPICE.

The EdFil editor can be used to generate the input netlist file for the ASIZ program, other circuit simulators
developed by the author, as SENSI, IFFT, MNAE, MNAV, etc., and also for other programs, even SPICE. It
was written (by 1983) after the conclusion that it is virtually impossible to write a textual netlist for a
nontrivial circuit without errors. This program is rather different from other schematic capture programs, but it
is very easy to use.
The circuit is drawn on the screen using the mouse and some keyboard keys, which cause the insertion of a
corresponding component between the two nodes closest to the mouse position. The orientation of the
component can be changed by pressing Space or Backspace. Names and parameters for the elements are given
by moving the cursor to the component and touching the Return key or the left mouse button, or by pressing
Ctrl-X, what causes the program to ask parameters for all visible elements. The best method is usually to firstly
draw all the circuit and later give the parameters. There are default names and parameters for all elements,
corresponding to usual values in the author’s simulators. The editor accepts any text in the parameters, to be
given accordingly to what the simulator to be used requires, that are reproduced in the netlist exactly as given,
in uppercase, unless for formulas, that must be enclosed between parenthesis, that are evaluated. The
parameters can be visualized by pressing Esc with the mouse cursor over an element.

