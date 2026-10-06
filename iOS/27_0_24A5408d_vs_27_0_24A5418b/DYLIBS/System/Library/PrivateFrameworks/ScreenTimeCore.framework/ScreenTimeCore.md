## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfb294` | `0xfc7b4` | **`+0x1520`** |
| `__TEXT.__eh_frame` | `0x4078` | `0x4220` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0xbfea` | `0xc07a` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x3f40` | `0x3fb0` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x9a80` | `0x9ae0` | **`+0x60`** |
| `__TEXT.__cstring` | `0xa84c` | `0xa8ac` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x35f8` | `0x3640` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x228` | `0x250` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1544` | `0x1560` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x194` | `0x1ac` | **`+0x18`** |
| `__DATA.__bss` | `0x3f80` | `0x3f90` | **`+0x10`** |
| `__DATA.__data` | `0x2200` | `0x2210` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x54c8` | `0x54d8` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x164` | `0x170` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x1d98` | `0x1da0` | **`+0x8`** |

### Other Changes

```diff

-655.0.101.0.0
+655.0.106.0.0

-  Functions: 5958
-  Symbols:   6815
-  CStrings:  2279
+  Functions: 5981
+  Symbols:   6824
+  CStrings:  2284
Symbols:
+ -[STRegulatoryIntelligenceSiriPolicy presentsOriginalSiriOnly]
+ -[STRegulatoryIntelligenceSiriPolicy setPresentsOriginalSiriOnly:]
+ _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._presentsOriginalSiriOnly
+ _STImagePlaygroundBundleIdentifiers
+ _STImagePlaygroundBundleIdentifiers.bundleIdentifiers
+ _STImagePlaygroundBundleIdentifiers.onceToken
+ _STIsDeviceChinaSKU.isChinaSKURegion
+ _STIsImagePlaygroundBundleIdentifier
+ _STShouldHideBundleIdentifierFromUI
+ _STUserDefaultsKeyForceChinaSKU
+ ___STImagePlaygroundBundleIdentifiers_block_invoke
+ ___swift_closure_destructor.18Tm
+ ___swift_project_boxed_opaque_existential_2Tm
+ _symbolic SccySo10CTCategoryC______pG s5ErrorP
- -[STRegulatoryIntelligenceSiriPolicy setSiriAIIsHidden:]
- -[STRegulatoryIntelligenceSiriPolicy siriAIIsHidden]
- _OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._siriAIIsHidden
- _STIsDeviceChinaSKU.isChinaSKU
- ___swift_project_boxed_opaque_existential_2
CStrings:
+ "Could not get category for bundleID %{private}s: %{public}@"
+ "Overriding China SKU answer to %{public}@ due to the %{public}@ internal user default."
+ "STForceChinaSKU"
+ "com.apple.GenerativePlaygroundApp"
+ "com.apple.Posters.ImagePlaygroundPosterApp"
```
