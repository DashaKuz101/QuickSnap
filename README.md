# Quick Snap!
A two player version of the classic Snap card game... hit when the rank of the top cards match.


# Common Issues FAQ

## Game won't run
```
Running Debug Version from /bin/Debug
Error from sg_Audio_LoadSoundEffectNamed - Error opening audio device: DirectSoundCreate: No audio device found

Unhandled Exception: SwinGameSDK.SwinGameException: Error from sg_Audio_LoadSoundEffectNamed - Error opening audio device: DirectSoundCreate: No audio device found
   at SwinGameSDK.sgLibrary.sg_Audio_LoadSoundEffectNamed(String name, String filename)
   at SwinGameSDK.SwinGame.LoadSoundEffectNamed(String name, String filename)
   at CardGames.SnapGame.LoadResources() in c:\Users\101127311\QuickSnap\src\SnapGame.cs:line 15
   at CardGames.SnapGame.Main() in c:\Users\101127311\QuickSnap\src\SnapGame.cs:line 93
```

The fix is to connect your headphones to the computer's audio output.