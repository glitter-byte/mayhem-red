

<img width="975" height="894" alt="virtualpager" src="https://github.com/user-attachments/assets/32dc34d8-51ea-4f87-af1e-222fe9e0f6e4" />


<img width="780" height="552" alt="alerts" src="https://github.com/user-attachments/assets/8566aab2-fc26-4560-8a07-4a3b1fb946db" />


<img width="767" height="540" alt="launch payload" src="https://github.com/user-attachments/assets/a773d53c-b9a0-461e-af6d-6c6a6a5864fa" />



Editing these files within /lib/pager/themes/ will have no effect. Do not place new themes there.

If you would like to modify the theme, create a new one by copying the wargames theme to /root/themes with a new directory name

cp -r /lib/pager/themes/wargames /root/themes/mycooltheme

Find more information at docs.hak5.org


TIPS FOR QUICK AND DIRTY RESKIN
-------------------------------
colors are defined in theme.json
view color_palette_preview.html in your browser for reference

you can use find and replace text to change colors in a json or in a whole directory at once
use quotations around colors to avoid file names and bluetooth: "blue" to "gray"
the wargames theme uses blue for most text and yellow for text highlighted when selected

edit assets in a raster img editor
assets are .png with transparency

to quickly reload the UI from the virtual pager, enable dev mode by pressing the green button 6 times in the About menu in Settings.
once enabled, press the green button again to open the dev menu, scroll down and select restart server
you will have to reload your virtual pager screen and log in again

- some of the filenames and colors got a little screwy, this was my first attempt - forgive for my transgrssions as i forgive my tansgressors -
