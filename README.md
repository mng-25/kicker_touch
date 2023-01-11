# kicker_touch
<h2>A fork of the KDE Plasma 5 Kicker plasmoid with automatic switching to dash mode</h2>
Note for those without convertible laptops:

Swapping comments on as noted by the comment: <i>// Disable for non-touch enabled machines, turns config checkbox into dash mode toggle</i> in main.qml and CompactRepresentation.qml will turn the checkbox for enabling dash switching into a hard toggle.

Issues: Disabling tablet mode (flipping back to conventional laptop mode) causes plasmashell to crash. With the above hack, disabling the config option and applying will cause the crash.
