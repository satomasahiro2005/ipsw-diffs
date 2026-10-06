## PowerUI

> `/System/Library/PrivateFrameworks/PowerUI.framework/PowerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9de4` | `0xd9e98` | **`+0xb4`** |
| `__AUTH_CONST.__cfstring` | `0xdc20` | `0xdca0` | **`+0x80`** |
| `__TEXT.__cstring` | `0xf7f9` | `0xf815` | **`+0x1c`** |
| `__TEXT.__const` | `0x6d0` | `0x6e0` | **`+0x10`** |

### Other Changes

```diff

-  CStrings:  3209
+  CStrings:  3213
Functions:
~ +[PowerUISmartChargeUtilities isUltraWatch] : 196 -> 236
~ -[PowerUIBluetoothHandler isAccessorySupported:] : 64 -> 80
~ -[PowerUIAudioAccessorySmartChargeManager nameForProductID:] : 272 -> 396
CStrings:
+ "B868CHE"
+ "B868CHM"
+ "B868E"
+ "B868M"
```
