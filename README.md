# Deej Volume OSD (Windows 11 Style)
Displays a modern, anti-aliased Windows 11 volume OSD flyout (matching the native `Fn + F2` overlay) whenever you adjust a physical hardware slider powered by the [**deej**](https://github.com/omriharel/deej) project .
![](https://github.com/michalkichal2436/deej-osd/blob/main/win11Stlye.gif)

(Windows 11 Style Compact 1-Line)
## Key Features
- **Automatic `config.yaml` Synchronization**: Point the mod to your `config.yaml` file (or leave the path empty to automatically detect a running `deej.exe` instance). The mod parses `slider_mapping` (`master`, `mic`, `system`, `deej.unmapped`, `deej.current`, single process names, and process groups) and hot-reloads whenever the file is saved.
- **4 Built-in Window Presets**:
  1. **Compact 1-Line with App Icon** *(App Icon + Bar + Number)*
  2. **Windows 11 Style Compact 1-Line** *(Application Icon + Bar + Circular Thumb, no number)*
  3. **2-Line Detailed** *(App Icon & Name on top + Speaker + Bar + Number below)*
  4. **Custom** *(Full control over header visibility, text position, alignment, bar thumb, and elements)*
- **Hardware Noise & Wake Threshold**: Configure how many percent a slider must move from rest before waking the OSD, preventing accidental potentiometer jitter from triggering the popup.
- **Full GDI+ Anti-Aliasing**: Sub-pixel smoothed pill-shaped progress bars, high-resolution (`64x64` 32-bit ARGB) bicubic-scaled application icons, and Windows 11 system accent color integration.
