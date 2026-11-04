# Hail-to-the-Rainbow VR
VR Mod for Hail to the Rainbow

broken not tested fully 

HAIL TO THE RAINBOW VR  -  VR mod (Unity 2019.4, Mono x64, BepInEx 5)
=====================================================================
Version 0.1.9 (test build)



CONTROLS (the controllers are a gamepad for the game - the game shows gamepad prompts)
-
  Left stick ............ move
  
  Right stick ........... left / right = turn (snap\smooth)   up = jump   down = crouch
  
  Right trigger ......... attack / shoot
  
  Left trigger ........ block / aim
  
  A ..................... use / interact (menus: select)
  
  B ..................... heal (menus: back)
  
  Y ..................... reload
  
  X ..................... inventory - tap  to open, tap again to close (InventoryToggle = false: hold X)
  
  Right grip (hold) ..... LASER
  
  Left stick click ...... run
  
  Right stick click ... flashlight

  Right stick up ... jump (car break)

  Right stick down ... crouch
  
  Left grip (tap) ....... LB (menus: tab left)
  
  Left grip + Y ......... pause (Start)
  
  Left grip + B ....... photo mode (Select)
  
  **Left grip + left stick  d-pad**
  
  **Left grip + right stick the game's normal right stick (look / turn items) - no turning / jumping meanwhile**
  
  Left grip + L3 ........ the **MOD'S FLASHLIGHT** on / off (bright; hand / brightness / reach / beam in the VR menu)
  
  Left grip + X ......... live ADJUSTMENT of BOTH hands: the hands stay put in the air, move each controller to
                          where you want to hold them (right stick up / down = bigger / smaller), left grip + X again
                          keeps it. Each item in your hands (gun, uzi, tool, detector, book...) keeps its own, left
                          hand included.
                          
  Both stick clicks ..... re-centre the view 
  
  Both stick hold 1.2 s = VR settings menu)
  
  Menus: the right controller's laser is the mouse (right trigger = click), A / B / grips work like a gamepad.

6DOF
  * The first-person hands (with the gun / tool) follow your right controller; shots and tool hits go where it points.
  * The left hand is bent onto your left controller (LeftHandOffset / LeftHandRotation in the cfg).
  * Both arms bend: the shoulders stay at your body (RightArmBends / LeftHandOnLeftController).
  * The flashlight shines from your left controller (FlashlightHand = Left / Right / Head / Game; its height /
    angle in the VR menu or FlashlightPosition / FlashlightRotation).
  * Interaction prompts float by your right controller, health and flashlight battery by your left.
  * The right hand is fixed on the controller - what you hold doesn't sway with the game's animation.
  * Items the game holds in the left hand are shown in your right hand (AllItemsInRightHand).
  * What you can use / pick up is picked from where your right controller points (A = use).
  * The game looks where you look (you walk where you look).
  * First run: the hands may sit too far forward - use left grip + X once for each item to put them in your hand.

Issues
-
* all item not place correct and may adjust in correctly when swap live adjust work to fix (LG+X)
* drone move with left stick and turn with LG + right stick
