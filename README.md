# Ubuntu CFG

## Settings dconf

   ```
   { ~ } » dconf dump /org/gnome/settings-daemon/ > ubuntucfg/settings.dconf
   { ~ } » dconf load /org/gnome/settings-daemon/ < ubuntucfg/settings.dconf
   ```

