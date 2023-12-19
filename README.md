# Revert *The Binding of Isaac: Repentance Online Beta* Save File

## How to Use

No cloud save path:
```
USERS\Documents\My Games\Binding of Isaac Repentance
```

Cloud save path:
```
Steam\userdata\your_steam_id\250900\remote
```

Find `rep_beta_persistentgamedata1.dat`, copy `isaac_revert_online.py` to this path, execute it:

```
python issac_revert_online.py
```

That's all.

## How it works

*Binding of Isaac: Repentance Online Beta* add 3 new secrets, the save data after secrets will not be loaded correctly when using non-beta game version. 

The script change game version and remove these 3 new secrets.
