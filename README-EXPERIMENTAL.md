Experimental Build Deviations from Official Stunnel:
- Base Font changed from <b>Courier</b> raster font to <b>MS Shell Dlg</b>. This improves the look on newer Windows versions. On Windowx XP this should show the log in Tahoma 8pt and on Windows Vista/7/10/11 or later to Segoe UI 9pt.
- Implements Log Coloring according to the LOG line debug level. This requires RICHEDIT control to be available, which should be in the default supported OS installations.
- When closed or terminated, Stunnel saves window location and sizes to the current user regsitry and restores them when started again.
- Save peer certificate function now allows user to select the save location and to open the folder where the file was saved in Windows Explorer.
- Save Log function now defaults the filename to stunnel-YYYYMMDD-HHMMSS.log, lets you choose the save location foldfer and optionally open it in Windows Explorer. A keyboard accelerator (Ctrl+S) has been also added.
- Added <b>Copy to Clipbaord</b> and <b>Select All (Ctrl+C)</b> to the Log Window
- Add Ctrl+R keybaord accelerator to Reload Configuration
