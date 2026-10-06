## IdentityLookup

> `/System/Library/Frameworks/IdentityLookup.framework/IdentityLookup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28588` | `0x274e0` | **`-0x10a8`** |
| `__TEXT.__oslogstring` | `0xe7d` | `0xdbd` | **`-0xc0`** |
| `__TEXT.__cstring` | `0xad1` | `0xab1` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x878` | `0x860` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x278` | `0x270` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xb08` | `0xb10` | **`+0x8`** |

### Other Changes

```diff

-1395.100.1.0.0
+1397.100.1.0.0

-  Symbols:   1110
-  CStrings:  159
+  Symbols:   1109
+  CStrings:  155
Symbols:
- _OBJC_CLASS_$_NSUserDefaults
Functions:
~ sub_2484ffe64 -> sub_249651e64 : 10500 -> 6896
~ sub_24851174c -> sub_249662938 : 236 -> 44
~ sub_248511838 -> sub_249662964 : 96 -> 236
~ sub_248511898 -> sub_249662a50 : 76 -> 96
~ sub_2485118e4 -> sub_249662ab0 : 44 -> 76
~ sub_248514a48 -> sub_249665c34 : 740 -> 696
~ sub_248514d2c -> sub_249665eec : 496 -> 484
~ sub_248515020 -> sub_2496661d4 : 1204 -> 1188
~ sub_2485155d0 -> sub_249666774 : 2740 -> 2188
~ sub_248516084 -> sub_249667000 : 292 -> 276
~ sub_2485161a8 -> sub_249667114 : 372 -> 352
CStrings:
- "Extension %s, failed plist validation: %@ marking as uninstalled"
- "livecalleridProfileEnabled"
- "not re-enabling extension %s, failed plist validation: %@"
- "plist validated successfully for extension %s"
```
