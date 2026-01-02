# Author pluginu
- https://www.nexusmods.com/mywintercar/mods/197
- https://github.com/potatosalad775/MWC_Localization_Core
- Některé překlady vycházejí ze staré češtiny z MSC: https://www.nexusmods.com/mysummercar/mods/1384

# Requirements
Plugin využívá `BepInEx` verze `>5.x`, bez kterého to nebude fungovat!

## Instalace
### 1. Instalace `BepInEx`
**Pokud jsi již MWC módoval je vysoce pravděpodobné, že je pro to vyžíván tento plugin, takže už ho máš a může krok skipnout.** Návod pracuje s verzi v5.4.23.4 a může již být novejší verze.

1. Stáhni `BepInEx` z: https://github.com/BepInEx/BepInEx/releases/download/v5.4.23.4/BepInEx_win_x64_5.4.23.4.zip

2. Rozbal `BepInEx_win_x64_5.4.23.4.zip` do složky s instalací MWC.
Například: `G:\SteamLibrary\steamapps\common\My Winter Car`

Nějak takto by měla vypadat tvoje struktura:
![alt text](doc/image.png)
** Hra v momentální chvili nebude fungovat.** Je to způsobeno configem BepInEx v `MWC instalace/BepInEx/config/BepInEx.cfg` obsahuje defaultně nastavený `Type = Application`, ale správná hodnota pro MWC je `Type = MonoBehaviour` (tento konfig obsahuje čeština se správnou hodnotou)

### 2. Instalace `češtiny`
1. Stáhni nejnovejší verzi z: https://github.com/MrZajic/MWC_cs-CZ/releases (MWC_cz-x.x.x-x.zip)
2. Rozbal zip do složky s instalací MWC. 
Například: `G:\SteamLibrary\steamapps\common\My Winter Car`
