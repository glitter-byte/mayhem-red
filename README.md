This is a basic reskin of the defualt theme shipped with WifiPineapplePagers

Its a work in progres

To use, place in /root/themes/
You should be able to select it from the settings menu Settings > General > Theme > mayhem-red

Dashboard

<img width="759" height="537" alt="alerts" src="https://github.com/user-attachments/assets/1d976356-8069-463c-a9b8-e7ae7f426b5c" />

ALerts Screen

<img width="780" height="552" alt="alertsscreen" src="https://github.com/user-attachments/assets/da47be3f-98cc-4dc5-ae10-22cb66d418ad" />

Alerts Menu

<img width="756" height="537" alt="authcapture" src="https://github.com/user-attachments/assets/7b413974-be84-4f4e-95bc-77b18f2b3d77" />

Payloads

<img width="771" height="551" alt="payloads" src="https://github.com/user-attachments/assets/5fd0690e-8814-4f14-8500-99682747dca4" />

Launch Payload

<img width="767" height="540" alt="launch payload" src="https://github.com/user-attachments/assets/01369675-60e9-45eb-a302-4ef27e61253b" />

Recon

<img width="756" height="539" alt="recon" src="https://github.com/user-attachments/assets/40881da6-3279-4e40-afc3-0edc28c7ce1a" />

Settings

<img width="755" height="540" alt="settings" src="https://github.com/user-attachments/assets/89520547-b521-4cbf-8f2d-2b13ecb4a0b5" />

Option Select

<img width="760" height="545" alt="select menus" src="https://github.com/user-attachments/assets/82e4a73d-82d5-4498-84c1-1a19b205f5b8" />






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


