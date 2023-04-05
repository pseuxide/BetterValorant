# BetterValorant
Stretched resolution in VALORANT

This is a fork version that i slightly fixed the usage difficulties that I personally had.

Original repository -> [l1m0n3/BetterValorant](https://github.com/l1m0n3/BetterValorant)

# premise
According to my experience, this stretch method only be enabled in-match, meaning when u jump outta match and return to menu, the stretch get automatically canceled. **So u likely have to re-enable everytime the new game(match) starts.** It kinda drags out so I made it easy to on and off the feature.
No clue what makes this happens but menu window tries to resist the true stretch ends up letterboxing.

# How to use
1. Valorant in-game setting set your "Display Mode" to "Windowed"
2. Valorant in-game setting, set your "Aspect Ratio Method" to "Fill"
3. Launch BetterValorant.exe
4. (initial setting prompt will show up at first launch)
5. press `~` key to enable true stretch, and `\` key to disable. and `=` key to quit the software. Note that this key settings is only taking my keyboard into account so you might feel it odd.

So basically, everytime u hop into match, u press \` to get true stretched res, and press `=` once u go back menu.

# FAQ
Q: How can I use a different resolution? It automatically applies previous resolution setting.

A: Delete the config file at `%userprofile%/Documents/BetterValorant/config.txt` or you can edit the file directly.

Q: My Anti-Virus blocks BetterValorant.exe! This is a virus!

A: No, it's just a false-positive. But if you got the exe from somewhere else but here, it might be containing a virus. You can compile the code by yourself so you won't get any viruses.
