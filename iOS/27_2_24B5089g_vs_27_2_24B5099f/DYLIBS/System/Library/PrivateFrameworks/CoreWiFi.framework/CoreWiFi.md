## CoreWiFi

> `/System/Library/PrivateFrameworks/CoreWiFi.framework/CoreWiFi`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x200cb0` | `0x200ce0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x259e6` | `0x25a0a` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x1d200` | `0x1d220` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x3e40` | `0x3e58` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1070` | `0x1068` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x2080` | `0x2088` | **`+0x8`** |

### Other Changes

```diff

-1032.7.0.0.0
+1032.8.0.0.0

-  Symbols:   1187
-  CStrings:  6380
+  Symbols:   1186
+  CStrings:  6381
Symbols:
- _swift_release_x24
Functions:
~ sub_2462dab0c -> sub_24568cb0c : 7256 -> 7280
~ sub_2464a2c7c -> sub_245854c94 : 896 -> 900
~ sub_2464a2ffc -> sub_245855018 : 352 -> 356
~ sub_2464a3bc8 -> sub_245855be8 : 328 -> 332
~ sub_2464b0fd0 -> sub_245862ff4 : 260 -> 272
CStrings:
+ "NETWORK WARNING FLAGS CHANGED EVENT"
```
