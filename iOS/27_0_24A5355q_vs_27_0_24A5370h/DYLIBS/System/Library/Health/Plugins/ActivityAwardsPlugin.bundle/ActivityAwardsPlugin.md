## ActivityAwardsPlugin

> `/System/Library/Health/Plugins/ActivityAwardsPlugin.bundle/ActivityAwardsPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1600` | `0x16f4` | **`+0xf4`** |
| `__TEXT.__oslogstring` | `0x197` | `0x1e1` | **`+0x4a`** |
| `__DATA_CONST.__objc_selrefs` | `0x390` | `0x3a0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x108` | `0xf8` | **`-0x10`** |

### Other Changes

```diff

-2027.0.18.0.0
+2027.0.20.0.0

-  CStrings:  12
+  CStrings:  13
Functions:
~ sub_24780a094 -> sub_248db9094 : 124 -> 16
~ sub_24780a110 -> sub_248db90a4 : 16 -> 124
~ sub_24780b00c -> sub_248dba00c : 128 -> 252
~ sub_24780b130 -> sub_248dba1ac : 96 -> 156
~ sub_24780b190 -> sub_248dba248 : 96 -> 156
CStrings:
+ "Sample added but there is an active workout session, not notifying daemon"
```
