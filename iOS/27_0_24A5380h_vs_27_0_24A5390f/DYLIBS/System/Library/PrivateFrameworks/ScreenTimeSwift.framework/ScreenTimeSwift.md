## ScreenTimeSwift

> `/System/Library/PrivateFrameworks/ScreenTimeSwift.framework/ScreenTimeSwift`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83ad8` | `0x853c4` | **`+0x18ec`** |
| `__TEXT.__oslogstring` | `0x225f` | `0x239f` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x3180` | `0x3150` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x2c98` | `0x2c70` | **`-0x28`** |
| `__TEXT.__const` | `0x442c` | `0x440c` | **`-0x20`** |
| `__TEXT.__cstring` | `0xe37` | `0xe17` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x1748` | `0x1730` | **`-0x18`** |
| `__DATA.__data` | `0xf40` | `0xf30` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xdc8` | `0xdb8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x394` | `0x384` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1780` | `0x1790` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x13a0` | `0x13a8` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x1488` | `0x1490` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xc4` | `0xbc` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0xd8` | `0xd0` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x160` | `0x15c` | **`-0x4`** |

### Other Changes

```diff

-645.1.100.0.0
+649.0.0.0.0

-  Functions: 2148
-  Symbols:   881
-  CStrings:  218
+  Functions: 2157
+  Symbols:   879
+  CStrings:  220
Symbols:
+ ___swift_closure_destructor.11Tm
+ _symbolic SccySaySo14STFamilyDeviceCG______pG s5ErrorP
- ___swift_closure_destructor.20Tm
- ___swift_closure_destructor.82Tm
- _symbolic SaySo14STFamilyDeviceCG
- _symbolic ScCySaySo14STFamilyDeviceCG______pG s5ErrorP
CStrings:
+ "Skipping migrating App Store restrictions because the All Restrictons toggle is disabled."
+ "Skipping migrating Game Center restrictions because the All Restrictons toggle is disabled."
+ "Skipping migrating Game Center's screen recording policy because the All Restrictons toggle is disabled."
+ "Skipping migrating web content restrictions because the All Restrictons toggle is disabled."
+ "isEligibleForMigrationUI(_:)"
- "Restrictions blueprint is disabled. Not migrating any restrictions."
- "devices(for:forceRefresh:)"
- "isEligible(for:)"
```
