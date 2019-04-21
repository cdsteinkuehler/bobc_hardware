KiCad v5:
To make all components visible in 3D-viewer open footprint editor or pcb preferences-->configure paths then
create a new variable named:

MYKSYS3DMOD
pointing to
../KiCAD_Libraries/v5_kicad-packages-3D
Then you may have to restart kicad.

Freecad 0.18 (KiCad StepUp Wb)
in stepupwd preferences add ALT3DMOD
pointing to '/(your repo location)/bobc_hardware/KiCAD_Libraries/v5_kicad-packages-3D'

and import the pcb files ...
