## libBasebandManagerDAL.dylib

> `/usr/lib/libBasebandManagerDAL.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ed57c` | `0x1ed3ec` | **`-0x190`** |
| `__TEXT.__gcc_except_tab` | `0x2abf8` | `0x2abd4` | **`-0x24`** |
| `__TEXT.__oslogstring` | `0xaa9f` | `0xaa80` | **`-0x1f`** |
| `__TEXT.__cstring` | `0x5ec6` | `0x5ed7` | **`+0x11`** |

### Other Changes

```diff

-1580.0.0.0.0
+1585.0.0.0.0
Functions:
~ __GLOBAL__sub_I_ResetInfo.cpp : 2588 -> 2676
~ __ZN9SARModule22initializeHelpers_syncEv : 7900 -> 7412
CStrings:
+ ".*ATCS_TIMEOUT.*"
+ "AppleBasebandManager-AppleBasebandServices_Manager-1585"
+ "AppleBasebandServices_Manager-1585"
- "AppleBasebandManager-AppleBasebandServices_Manager-1580"
- "AppleBasebandServices_Manager-1580"
- "Failed to get Accessory State!"
```
