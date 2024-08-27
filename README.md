# zmon
Quick &amp; dirty HWMonitor-clone for Linux, written in Python and using GTK-bindings.

## Description
Far from finished, a work-in-progress.

## Requirements
- Requires Python and its standard libraries, as well as Python GTK3.0-bindings (which *may* be part of standard libraries, I don't know)
- `sensors -j` ([lm-sensors](https://en.wikipedia.org/wiki/Lm_sensors)) as a %PATH% executable
- Developed, tested and works-out-of-the-box on LMDE 6 'Faye' (X11/Cinnamon based on Debian 12 'Bookworm' with Python 3.11.2)
- *Should* work out-of-the-box just as well on other GTK-derived GNU/Linux distributions
- *Probably* requires tinkering to get to work with Qt/KDE-derived distributions (but so do all GTK-applets)
- If *all* dependencies are met, it should work with other systems as well (e.g. Windows)
- In Windows, you may need to call `python zmon` from a terminal/shell/shortcut instead of just executing the script

## Screenshots
![2024-08-27_zmon-1](https://github.com/user-attachments/assets/a01c8b55-916e-42d5-89e1-08d029a3c824)
![2024-08-27_zmon-2](https://github.com/user-attachments/assets/8ce9a297-faac-4f6c-a12d-89b830c48848)

*Note: These may or may not reflect the latest updates.*

## License
This work is presently unlicensed.
