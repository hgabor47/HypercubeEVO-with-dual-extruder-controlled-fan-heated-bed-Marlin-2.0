# HypercubeEVO
3DPrinter-HypercubePM version:
https://www.youtube.com/watch?v=kAhyeJ2CmXs


# NEW:
# HypercubeEVO
RAMPS 1.4 (1.6) Marlin 2.0 config:
- Dual extruders (PIN D9,D10)
- 3D Touch (BLTouch) (PIN D11 Servo) 
- Two cooling fan (one fixed for dual extruders (12VPower), one controlled for hotends (PIN D8))
- Heated bed (fast modern heat with SSR controlled 110/230v silicon heater) (PIN D4 Servo)

![Image](https://github.com/hgabor47/HypercubeEVO-with-dual-extruder-controlled-fan-heated-bed-Marlin-2.0/blob/master/HypercubeEVO-Marlin2/RAMP%20Circuit.png?raw=true)

I use TMC2100 stepper drivers for XYZ and A4899 for extruders but this is up to you.
And no additional electric circuit needed (if you use SSR for bed heating like me)

# OLD:
# HypercubePM
Folyamatosan töltöm fel a kapcsolódó anyagokat.
Egyelőre a Blender állományt használhatjátok Blender 2.8 verzió letöltése szükséges. ( https://www.blender.org/2-8/ )
A Blend állományból STL exporttal kinyert fájlokat kell egy másik 3D nyomtatón kinyomtatni.

A Marlin 1.1.7 verziójú firmware config állománya is mellékelve.

Továbbiakban lesz még:
- Áramköri bekötési rajz
- További anyagok felsorolása (blend tartalmazza, de megnevezés típus is leírásra kerül)
