https://askubuntu.com/questions/984205/how-to-save-gnome-settings-in-a-file


To dump the settings to an INI file, run this command:

``
dconf dump / > dconf-settings.ini
``

To restore/ load those settings

``
cat dconf-settings.ini | dconf load
``
