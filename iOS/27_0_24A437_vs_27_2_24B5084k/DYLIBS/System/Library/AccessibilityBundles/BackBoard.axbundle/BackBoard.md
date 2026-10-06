## BackBoard

> `/System/Library/AccessibilityBundles/BackBoard.axbundle/BackBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x281ec` | `0x28850` | **`+0x664`** |
| `__TEXT.__oslogstring` | `0x1fc0` | `0x2233` | **`+0x273`** |
| `__AUTH_CONST.__objc_const` | `0x3098` | `0x3158` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x698` | `0x5e8` | **`-0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1da0` | `0x1e20` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0xfc0` | `0x1040` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2369` | `0x23d1` | **`+0x68`** |
| `__TEXT.__dlopen_cstrs` | `0x2d9` | `0x33b` | **`+0x62`** |
| `__AUTH.__objc_data` | `0x260` | `0x2b0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x232c` | `0x237c` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xc68` | `0xca0` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c08` | `0x1c38` | **`+0x30`** |
| `__DATA.__bss` | `0x510` | `0x538` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x8f8` | `0x910` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x208` | `0x218` | **`+0x10`** |
| `__TEXT.__const` | `0x500` | `0x510` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd10` | `0xd00` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x6a8` | `0x6b0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x158` | `0x160` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x160` | `0x164` | **`+0x4`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 1027
-  Symbols:   2106
-  CStrings:  492
+  Functions: 1037
+  Symbols:   2124
+  CStrings:  506
Symbols:
+ +[AXBChatterboxManager initializeMonitor]
+ -[AXBChatterboxManager setChatterboxEnabled:]
+ -[AXBChatterboxManager updateSettings]
+ -[AXBDisplayFilterManager _reconcileGrayscaleCacheWithColorFilters]
+ GCC_except_table163
+ GCC_except_table203
+ GCC_except_table238
+ GCC_except_table248
+ GCC_except_table267
+ GCC_except_table310
+ GCC_except_table354
+ GCC_except_table356
+ GCC_except_table406
+ GCC_except_table411
+ GCC_except_table427
+ GCC_except_table435
+ GCC_except_table471
+ GCC_except_table489
+ GCC_except_table540
+ GCC_except_table586
+ GCC_except_table615
+ GCC_except_table632
+ GCC_except_table645
+ GCC_except_table657
+ GCC_except_table690
+ GCC_except_table728
+ GCC_except_table742
+ GCC_except_table816
+ _AXBCaseAccommodationsEnabled.onceToken
+ _AXDeviceIsViridian
+ _AXDeviceSupportsChatterbox
+ _AXLogChatterbox
+ _CFPreferencesGetAppBooleanValue
+ _MADisplayFilterPrefGetType
+ _MADisplayFilterPrefSetCategoryEnabled
+ _MADisplayFilterPrefSetType
+ _OBJC_CLASS_$_AXBChatterboxManager
+ _OBJC_IVAR_$_AXBChatterboxManager._enabled
+ _OBJC_METACLASS_$_AXBChatterboxManager
+ __AXSUpdateGrayscaleEnabledCache
+ __OBJC_$_CLASS_METHODS_AXBChatterboxManager
+ __OBJC_$_INSTANCE_METHODS_AXBChatterboxManager
+ __OBJC_$_INSTANCE_VARIABLES_AXBChatterboxManager
+ __OBJC_CLASS_RO_$_AXBChatterboxManager
+ __OBJC_METACLASS_RO_$_AXBChatterboxManager
+ ___41+[AXBChatterboxManager initializeMonitor]_block_invoke
+ ___41+[AXBChatterboxManager initializeMonitor]_block_invoke_2
+ ___AXBCaseAccommodationsEnabled_block_invoke
+ ___AXBCaseAccommodationsEnabled_block_invoke_2
+ _sAXBCaseAccommodationsEnabled
- GCC_except_table196
- GCC_except_table229
- GCC_except_table23
- GCC_except_table231
- GCC_except_table237
- GCC_except_table245
- GCC_except_table247
- GCC_except_table256
- GCC_except_table257
- GCC_except_table300
- GCC_except_table33
- GCC_except_table344
- GCC_except_table346
- GCC_except_table35
- GCC_except_table36
- GCC_except_table37
- GCC_except_table396
- GCC_except_table401
- GCC_except_table417
- GCC_except_table425
- GCC_except_table461
- GCC_except_table479
- GCC_except_table530
- GCC_except_table576
- GCC_except_table605
- GCC_except_table622
- GCC_except_table635
- GCC_except_table647
- GCC_except_table680
- GCC_except_table718
- GCC_except_table732
- GCC_except_table806
CStrings:
+ "%@-colorfilter-toggle-testing"
+ "AXBChatterboxManager.m"
+ "Asked to enable/disable Chatterbox but feature flag is off, so no"
+ "Buddy running: %{BOOL}d (Buddy pid: %d, setup complete: %{BOOL}d)"
+ "Chatterbox monitor asked to enable: %ld"
+ "EdgeSwipeBandExpansionEnabled"
+ "Error toggling Chatterbox: %@"
+ "Home click controller init: setup complete: %{BOOL}d, triple click options: %@"
+ "Home click controller transition %d %d %d (was %d %d %d), triple click options: %@"
+ "Home click controller transition deferred, setup is not complete yet. Retrying in 2s"
+ "LiveSpeechServices not available"
+ "Removing Buddy triple click option left behind after setup completed"
+ "Updating Buddy VoiceOver status: requires Buddy triple click: %{BOOL}d, triple click options: %@, VoiceOver: %{BOOL}d"
+ "com.apple.backboardd"
+ "softlink:o:path:/System/Library/PrivateFrameworks/LiveSpeechServices.framework/LiveSpeechServices"
- "Home click controller transition %d %d %d"
```
