## IdentityLookup

> `/System/Library/Frameworks/IdentityLookup.framework/IdentityLookup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x274ec` | `0x285b4` | **`+0x10c8`** |
| `__TEXT.__oslogstring` | `0xdbd` | `0xe7d` | **`+0xc0`** |
| `__TEXT.__cstring` | `0xab1` | `0xaf5` | **`+0x44`** |
| `__DATA_CONST.__objc_selrefs` | `0x860` | `0x878` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x270` | `0x278` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb10` | `0xb08` | **`-0x8`** |

### Other Changes

```diff

-1403.100.1.0.0
+1406.200.51.2.1

-  Symbols:   1109
-  CStrings:  155
+  Symbols:   1110
+  CStrings:  160
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
Functions:
~ sub_24996de64 -> sub_24d2f2e64 : 6896 -> 10500
~ sub_24997e938 -> sub_24d30474c : 44 -> 236
~ sub_24997e964 -> sub_24d304838 : 236 -> 96
~ sub_24997ea50 -> sub_24d304898 : 96 -> 76
~ sub_24997eab0 -> sub_24d3048e4 : 76 -> 44
~ sub_249981c34 -> sub_24d307a48 : 696 -> 740
~ sub_249981eec -> sub_24d307d2c : 484 -> 496
~ sub_2499821d4 -> sub_24d308020 : 1188 -> 1204
~ sub_249982774 -> sub_24d3085d0 : 2188 -> 2740
~ sub_249983000 -> sub_24d309084 : 276 -> 292
~ sub_249983114 -> sub_24d3091a8 : 352 -> 372
~ sub_2499839a4 -> sub_24d309a4c : 2380 -> 2412
CStrings:
+ "Extension %s, failed plist validation: %@ marking as uninstalled"
+ "NSPIRConfiguration"
+ "PrivacyPassIssuerURL"
+ "livecalleridProfileEnabled"
+ "not re-enabling extension %s, failed plist validation: %@"
+ "plist validated successfully for extension %s"
- "PIRConfiguration"
```
