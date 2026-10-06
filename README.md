# Grey-filter
A portable Windows screen dimmer with adjustable gray overlays, multi-monitor support, and keyboard shortcuts.
# Filtre Gris PC

A portable Windows screen dimmer with adjustable gray overlays, multi-monitor support, and keyboard shortcuts.

## Requirements

- Windows 10 or 11 with **.NET Framework 4.8**.
- The current interface is in **French**; the guide below explains the controls.

## Quick start

1. Download **Filtre_Gris_PC.zip** and **extract all files**.
2. Open the extracted folder and run **FiltreGris.exe** or **LANCER.bat**. Keep the files together.
3. Move **“Opacité du filtre”** to adjust the overlay from **0% to 90%**. Higher opacity makes the display darker. The default is **35%**.
4. Under **“Couleur du filtre”**, choose black, anthracite gray, or dark gray. Under **“Appliquer sur”**, select one monitor or **“Tous les écrans”** (all monitors).

No installation, account, or administrator access is required. You can keep clicking and typing in your other apps while the filter is active.

## Everyday controls

- **Mettre en pause / Réactiver le filtre**: pause or resume the filter. Moving the opacity slider also resumes it.
- **Masquer la fenêtre**: hide the settings window while keeping the filter active. Click the tray icon near the Windows clock (check hidden icons if needed), or run `LANCER.bat` again, to reopen it.
- **Quitter** or the window’s **X**: close the app and remove the filter. You can also run `ARRETER.bat` to request shutdown.

Settings are saved automatically between sessions.

## Keyboard shortcuts

| Shortcut | Action |
| --- | --- |
| Ctrl + Alt + Up | Increase opacity by 5 percentage points |
| Ctrl + Alt + Down | Decrease opacity by 5 percentage points |
| Ctrl + Alt + F8 | Pause / resume |
| Ctrl + Alt + F9 | Open settings |
| Ctrl + Alt + F11 | Quit and remove the filter |

If another app reserves a shortcut, use the buttons or tray menu instead.

## Notes

- This is a visual overlay. It does not change the monitor’s hardware backlight or convert the image to grayscale.
- Some games in exclusive fullscreen mode may ignore the filter. Try **borderless windowed mode**. HDR results may vary.
- To reset preferences, close the app and delete `%LOCALAPPDATA%\FiltreGrisPC\reglages.ini`.

**Testing status:** compilation verified; Windows desktop testing is still pending.
