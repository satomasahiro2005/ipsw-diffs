## PosterKit

> `/System/Library/PrivateFrameworks/PosterKit.framework/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xb12f` | `0xafff` | **`-0x130`** |
| `__TEXT.__text` | `0x185ef0` | `0x185f98` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x4bd0` | `0x4b30` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x2840` | `0x28e0` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0xabe0` | `0xab80` | **`-0x60`** |
| `__AUTH.__data` | `0xcf8` | `0xd28` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x55428` | `0x55458` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1bd0` | `0x1be8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x2adc` | `0x2ac8` | **`-0x14`** |
| `__DATA.__bss` | `0x40f8` | `0x40e8` | **`-0x10`** |
| `__DATA.__data` | `0x5f18` | `0x5f28` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xc4c8` | `0xc4d8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x3f0` | `0x3e0` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__TEXT.__const` | `0x5f44` | `0x5f54` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1a114` | `0x1a124` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e88` | `0x1e90` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x62d8` | `0x62d0` | **`-0x8`** |
| `__DATA.__common` | `0x90` | `0x89` | **`-0x7`** |
| `__DATA.__objc_ivar` | `0x1ab0` | `0x1ab4` | **`+0x4`** |

### Other Changes

```diff

-344.0.101.0.0
+347.102.0.0.0

-  Functions: 10548
-  Symbols:   15615
-  CStrings:  2136
+  Functions: 10549
+  Symbols:   15619
+  CStrings:  2132
Symbols:
+ +[PRUpdatingService pr_raceTestService]
+ -[PREditor _updateComplicationsGalleryReticleAssertion]
+ -[PREditor complicationsGalleryReticleAssertion]
+ -[PREditor setComplicationsGalleryReticleAssertion:]
+ -[PRUpdatingService _markVendedTrashPurgable:]
+ -[PRUpdatingService pr_runUpdateActiveSessions]
+ -[PRUpdatingService pr_setTestPosterContainerTemporaryURL:]
+ -[PRUpdatingService pr_setTestTrashURL:]
+ GCC_except_table173
+ GCC_except_table191
+ GCC_except_table203
+ GCC_except_table55
+ GCC_except_table56
+ _OBJC_IVAR_$_PREditor._complicationsGalleryReticleAssertion
+ __UILerp
+ __UIMap
+ __UIUnlerp
- +[CSProminentLayoutController(PRUtilities) pr_complicationRowElements]
- -[CSProminentDisplayViewController(PRAdditions) pr_setCompactFont:]
- -[CSProminentDisplayViewController(PRAdditions) pr_setPermanentCompactTimeEnabled:animated:]
- -[PREditingFontAndContentStylePickerViewController _presentCompactTimeSecrecyAlertIfNeeded]
- -[PRUpdatingService _markVendedTrashPurgable]
- -[UIFont(PRTimeFont) pr_isNewYorkFont]
- GCC_except_table110
- GCC_except_table172
- GCC_except_table190
- GCC_except_table202
- GCC_except_table51
- GCC_except_table52
- _PRFontNameIsNewYorkFont
CStrings:
+ "ComplicationsGalleryReticles"
- "-[PREditingFontAndContentStylePickerViewController _presentCompactTimeSecrecyAlertIfNeeded]"
- ".NewYorkSoftNumeric"
- "Compact Time"
- "PRHideCompactTimeSecrecyAlert"
- "[Internal] Permanent compact time is an unreleased feature, and the sensitive UI toggle in Control Center must be enabled to see this change on Lock Screen. Do not use in a public place."
```
