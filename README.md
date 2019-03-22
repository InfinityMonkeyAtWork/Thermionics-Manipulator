# Thermionics-Manipulator
Control a 4-axis (X,Y,Z,rotation) manipulator with Schneider MDrive stepper motors via LabVIEW:
- Move two horizontal axis (X,Y), vertical axis (Z) and rotation by a certain amount and speed, both user defined. 
- Move in horizontal direction according to the current angle of rotation (in-plain) or perpendicular to it.
- Continously raster scan patterns with user defined speed and line spacing. Pause/ Resume at any time.
- Move vertically (Z) with or without tilt compensation in the horizontal plain in case of imperfect alignment of vertical manipulator axis with respect to what ideally would be defined as the vertical axis.
- Save and go to waypoints.
