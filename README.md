[日本語マニュアル](https://github.com/vxcall/BetterValorant/blob/master/README_jp.md)
# BetterValorant
Stretched resolution in VALORANT

This is a forked version that you can now have keybind to on/off the true stretched res.

I keep this as forked version for now as the change is just a preference level imho.

### Original repository -> [l1m0n3/BetterValorant](https://github.com/l1m0n3/BetterValorant)

# Premise
According to my experience, this stretch method only be enabled in-match, meaning when u jump outta match and return to menu, the stretch get automatically canceled. **So u likely have to re-enable everytime the new game(match) starts.** It's such a drag so I made it easy to on and off the feature.
No clue what makes this happens but menu window tries to resist the true stretch ends up letterboxing.

# How to use
1. Valorant in-game setting set your "Display Mode" to "Windowed"
2. Valorant in-game setting, set your "Aspect Ratio Method" to "Fill"
3. Launch BetterValorant.exe
4. At initial launch setting prompt will show up to configure width and height. My recommendation is 1280 x 960.
   ![image](https://github.com/user-attachments/assets/556cf15b-252a-4226-a0d1-febc9ac976ed)
6. press `[` key to enable/disable true stretch and `]` key to quit the software.

So basically, everytime u hop into match, u press `[` to get true stretched res, and press `]` once u go back menu. If u have any suggestion for keybind, open an issue and tell me

# FAQ
Q: How can I use a different resolution? It automatically applies previous resolution setting.

A: Delete the config file at `%userprofile%/Documents/BetterValorant/config.txt` or you can edit the file directly.

Q: My Anti-Virus blocks BetterValorant.exe! This is a virus!

A: No, it's just a false-positive. But if you got the exe from somewhere else but here, it might be containing a virus. You can compile the code by yourself so you won't get any viruses.
