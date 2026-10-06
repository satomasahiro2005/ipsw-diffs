## libSavageUpdater_iOS.dylib

> `/usr/lib/updaters/libSavageUpdater_iOS.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dddc` | `0x1ddec` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4d0` | `0x4d8` | **`+0x8`** |

### Other Changes

```diff
Symbols:
+ _initializeIOServiceConnectionWithNameAndType
- _initializeIOServiceConnectionWithName
Functions:
~ _initializeIOServiceConnectionWithName -> _initializeIOServiceConnectionWithNameAndType : 184 -> 196
~ _initialize : 108 -> 112
```
