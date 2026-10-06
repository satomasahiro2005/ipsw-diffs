## AppleAccountTransparency

> `/System/Library/PrivateFrameworks/AppleAccountTransparency.framework/AppleAccountTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x725dc` | `0x7399c` | **`+0x13c0`** |
| `__AUTH_CONST.__const` | `0x3698` | `0x3960` | **`+0x2c8`** |
| `__TEXT.__cstring` | `0x209d` | `0x233d` | **`+0x2a0`** |
| `__TEXT.__swift5_reflstr` | `0x12f5` | `0x14f5` | **`+0x200`** |
| `__TEXT.__const` | `0x43b0` | `0x4420` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x6130` | `0x61a0` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x1358` | `0x13b8` | **`+0x60`** |
| `__DATA.__data` | `0x878` | `0x898` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1cc0` | `0x1ce0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1961` | `0x197b` | **`+0x1a`** |
| `__AUTH_CONST.__auth_got` | `0xc68` | `0xc70` | **`+0x8`** |

### Other Changes

```diff

-448.125.5.2.0
+448.125.9.0.0

-  Functions: 1905
-  Symbols:   912
-  CStrings:  378
+  Functions: 1914
+  Symbols:   914
+  CStrings:  386
Symbols:
+ _symbolic Si______t 24AppleAccountTransparency8AATErrorO
+ _symbolic _____ySi_____G s18_DictionaryStorageC 24AppleAccountTransparency8AATErrorO
CStrings:
+ "Verification: events remained pending and returned eventNotYetTransparent"
+ "Verification: events returned eventMetadataMismatch and eventNotYetTransparent"
+ "Verification: events returned eventMetadataMismatch, remained pending, and returned eventNotYetTransparent"
+ "Verification: events returned eventNotTransparent and eventNotYetTransparent"
+ "Verification: events returned eventNotTransparent, eventMetadataMismatch, and eventNotYetTransparent"
+ "Verification: events returned eventNotTransparent, remained pending, and returned eventNotYetTransparent"
+ "Verification: events returned eventNotYetTransparent"
+ "eventNotYetTransparent"
```
