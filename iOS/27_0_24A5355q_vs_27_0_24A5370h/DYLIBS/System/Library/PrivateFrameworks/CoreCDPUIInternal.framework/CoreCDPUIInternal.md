## CoreCDPUIInternal

> `/System/Library/PrivateFrameworks/CoreCDPUIInternal.framework/CoreCDPUIInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b98` | `0x5e60` | **`+0x2c8`** |
| `__AUTH_CONST.__cfstring` | `0xbc0` | `0xcc0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x85b` | `0x8a5` | **`+0x4a`** |
| `__DATA_CONST.__objc_selrefs` | `0x778` | `0x7a8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x6b4` | `0x6cc` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x1f8` | **`+0x8`** |

### Other Changes

```diff

-440.1.0.0.0
+442.0.0.0.0

-  Functions: 138
-  Symbols:   364
-  CStrings:  116
+  Functions: 140
+  Symbols:   370
+  CStrings:  124
Symbols:
+ -[SettingsController _seedSwitchDefaultsFromPlist]
+ -[SettingsController _writeSwitchDefaultsFromPlist]
+ GCC_except_table58
+ GCC_except_table63
+ _CFRelease
+ _OBJC_CLASS_$_NSBundle
+ _objc_enumerationMutation
+ _objc_release_x28
- GCC_except_table56
- GCC_except_table61
CStrings:
+ "PSSwitchCell"
+ "_DidSeedSwitchDefaults"
+ "cell"
+ "default"
+ "defaults"
+ "items"
+ "key"
+ "plist"
```
