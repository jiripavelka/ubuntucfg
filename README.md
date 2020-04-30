# Ubuntu CFG

Simple way to backup complete Ubuntu config and restore only selected dirs. The script filters dump to dirs stated in `dirs` file (do not use trailing slashes).

## Dump all settings

   ```
   { ubuntucfg } » dconf dump / > settings.dconf
   ```

## Load all settings

   ```
   { ubuntucfg } » dconf load / < settings.dconf
   ```

## Load filtered settings

   ```
   { ubuntucfg } » ./filter dirs < settings.dconf | dconf load /
   ```
