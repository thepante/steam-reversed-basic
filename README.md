![screenshot](https://i.imgur.com/51yNr5j.png)  

## Steam window buttons on the left
Under Linux (and Windows), default Steam client UI has fixed window control buttons to the right. But in Linux the user can have the controls button on the left too, just like they are in macOS. And since Steam client doesn't adapt it automatically neither has an option about it, here is this skin with only basic changes to move the buttons to the left.

### Changes made  
 - Location of window control buttons to the left
 - Typical macOS buttons - or alternative one with lowered brightness colors
 - Removed fullscreen (Big Picture) dedicated button (use keybinds or menu instead)

## Get it
You can install it directly from the terminal:  
```bash
cd /tmp && wget https://github.com/thepante/steam-reversed-basic/archive/master.zip && unzip master.zip && mv steam-reversed-basic-master ~/.steam/steam/skins/"Buttons to Left" & rm master.zip && cd ~
```

Then in Steam open `Settings` → `Interface`, and select the new skin `Buttons to Left`

#### Or install it manually
You can clone this repository, then copy its content and paste it under `~/.steam/steam/skins/` naming the folder as you want. Then in the interface Steam settings you have to select the skin listed as that new folder name.

#### Alternative button colors
You can select an alternative version of the buttons but with lower brightness. Inside this skin path are a folder called `graphics` and second one `graphics-b`. You can swap them to change one version to another.

```bash
cd ~/.steam/steam/skins/Buttons\ to\ Left
```
And then swap those folders:
```
mv graphics graphics-o && mv graphics-b graphics && mv graphics-o graphics-b
```

Restart the Steam client to see the changes. If you want to revert it: just repeat the swap. 

The skin will always use the folder named `graphics`

---
Tested only on Linux, shouldn't have errors under Windows (not guaranteed).
