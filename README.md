# holoLens2AnchorSystem
Anchor system from scratch for DoubleMe's National Aquarium Exhibit

SETUP:
- use this as a template for a scene that needs to be anchored at a specific spot in real space, and put all the assets you want anchored in "MAIN SCENE"
- I recommend indicating standard locations (in the real world): one where the user stands and the other where the user lines up the calibration X

USAGE:
- using your hand, line the ray up with wherever you want the origin of your main scene to exist
- when the calibration confirmation button pops up, you can continue to place the X until you click the button (it often takes multiple tries to get the X where you want it)
- when the X is where you want it to be, *align your head rotation with where you want the positive z-axis of your main scene to face* and press the button to confirm

SYSTEM SPECS:
- HoloLens 2
- Unity 2021.3.8f1
- Visual Studio 2022
