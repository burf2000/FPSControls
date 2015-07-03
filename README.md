FPSControls
--------------
--------------

![Screenshot](https://raw.github.com/nicklockwood/FPSControls/master/Screenshot.jpg)


Purpose
--------------

FPSControls is an experimental implementation of touch-friendly first-person shooter controls using SceneKit and Swift.

Unlike most shooters on the app store, this control system has no on-screen buttons with fixed locations, either for movement or firing, but still provides full freedom of movement and firing ability via gestures.

This has the following advantages over other control systems:

1. No controls obscuring the screen, and you can place your fingers wherever is most convenient
2. No fixed layout means that it works with any device size, from iPhone to iPad without uncomfortable stretching
3. No fixed button or joypad positions means your finger can't slip into a position where the control stops working
4. Movement, aiming, single fire and automatic fire mode are implemented unambiguously, without risk of accidentally discharging a weapon, or staring at the ceiling that are common in other gesture-based FPS control systems

This is obviously not a real game, and in practice, additional controls would probably be necessary to augment this basic setup (e.g. reload, switch weapon, open door, melee, jump, throw grenade, etc.)

However, by implementing the moving, aiming and firing mechanisms intuitively without fixed control positions, we can ensure that the player is less likely to die due to a control failure, thereby avoiding frustration.

It should be quite feasible to add other, lower-priority "hunt and peck" controls around the main display without interfering with these core interactions.


Supported iOS & SDK Versions
-----------------------------

Updated to Swift 1.2

NOTE: 'Supported' means that the library has been tested with this version. 'Compatible' means that the library should work on this iOS version (i.e. it doesn't rely on any unavailable SDK features) but is no longer being tested for compatibility and may require tweaking or bug fixes to run correctly.


Tips
-------

Due to software GPU emulation, the iOS simulator provides really horrible performance when running this demo, and it's difficult to get a sense of the controls when using a mouse anyway.

Run it on a real device instead. You should get 60fps on an iPhone 6, or comparable device. If you are seeing unplayably bad performance on any relatively modern hardware, please file a support ticket on github.


Release notes
---------------

Version 1.1

- First release
- Updated to Swift 1.2

Upcoming 
- Seems to have a couple of issues on device
- May move to swift 2