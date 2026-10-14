## BackBoard

> `/System/Library/AccessibilityBundles/BackBoard.axbundle/BackBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29304` | `0x28ca0` | **`-0x664`** |
| `__TEXT.__oslogstring` | `0x23ac` | `0x246d` | **`+0xc1`** |
| `__AUTH_CONST.__objc_const` | `0x3170` | `0x30b8` | **`-0xb8`** |
| `__TEXT.__dlopen_cstrs` | `0x33b` | `0x2d9` | **`-0x62`** |
| `__AUTH.__objc_data` | `0x2b0` | `0x260` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0x1040` | `0x1000` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x239c` | `0x2364` | **`-0x38`** |
| `__TEXT.__gcc_except_tab` | `0x5e4` | `0x5b8` | **`-0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x1e40` | `0x1e20` | **`-0x20`** |
| `__DATA.__bss` | `0x538` | `0x518` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c38` | `0x1c18` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xd18` | `0xcf8` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x910` | `0x8f8` | **`-0x18`** |
| `__TEXT.__cstring` | `0x23f1` | `0x23da` | **`-0x17`** |
| `__AUTH_CONST.__auth_got` | `0xcc0` | `0xcb0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x6b0` | `0x6a8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x160` | `0x158` | **`-0x8`** |
| `__TEXT.__const` | `0x518` | `0x520` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x164` | `0x160` | **`-0x4`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 1046
-  Symbols:   2128
-  CStrings:  510
+  Functions: 1039
+  Symbols:   2112
+  CStrings:  508
Symbols:
+ GCC_except_table196
+ GCC_except_table231
+ GCC_except_table241
+ GCC_except_table260
+ GCC_except_table303
+ GCC_except_table347
+ GCC_except_table349
+ GCC_except_table399
+ GCC_except_table404
+ GCC_except_table420
+ GCC_except_table428
+ GCC_except_table464
+ GCC_except_table482
+ GCC_except_table533
+ GCC_except_table579
+ GCC_except_table608
+ GCC_except_table628
+ GCC_except_table641
+ GCC_except_table653
+ GCC_except_table686
+ GCC_except_table724
+ GCC_except_table738
+ GCC_except_table812
- +[AXBChatterboxManager initializeMonitor]
- -[AXBChatterboxManager setChatterboxEnabled:]
- -[AXBChatterboxManager updateSettings]
- GCC_except_table163
- GCC_except_table203
- GCC_except_table238
- GCC_except_table248
- GCC_except_table267
- GCC_except_table310
- GCC_except_table354
- GCC_except_table356
- GCC_except_table406
- GCC_except_table411
- GCC_except_table427
- GCC_except_table435
- GCC_except_table471
- GCC_except_table489
- GCC_except_table540
- GCC_except_table586
- GCC_except_table615
- GCC_except_table635
- GCC_except_table648
- GCC_except_table660
- GCC_except_table693
- GCC_except_table731
- GCC_except_table745
- GCC_except_table819
- _AXDeviceSupportsChatterbox
- _AXLogChatterbox
- _OBJC_CLASS_$_AXBChatterboxManager
- _OBJC_IVAR_$_AXBChatterboxManager._enabled
- _OBJC_METACLASS_$_AXBChatterboxManager
- __OBJC_$_CLASS_METHODS_AXBChatterboxManager
- __OBJC_$_INSTANCE_METHODS_AXBChatterboxManager
- __OBJC_$_INSTANCE_VARIABLES_AXBChatterboxManager
- __OBJC_CLASS_RO_$_AXBChatterboxManager
- __OBJC_METACLASS_RO_$_AXBChatterboxManager
- ___41+[AXBChatterboxManager initializeMonitor]_block_invoke
- ___41+[AXBChatterboxManager initializeMonitor]_block_invoke_2
CStrings:
+ "_appTransition entry: buddy=%{BOOL}d setupComplete=%{BOOL}d loginUI=%{BOOL}d setupAdj=%{BOOL}d checkerBoardScenario=%{BOOL}d voEnabled=%{BOOL}d"
+ "_startVoiceOverSequence: VO already enabled, toggling"
+ "_startVoiceOverSequence: voEnabled=%{BOOL}d checkerBoardScenario=%{BOOL}d buddy=%{BOOL}d"
+ "_toggleVoiceOver entry: voEnabled(before)=%{BOOL}d usageConfirmed=%{BOOL}d"
- "AXBChatterboxManager.m"
- "Asked to enable/disable Chatterbox but feature flag is off, so no"
- "Chatterbox monitor asked to enable: %ld"
- "Error toggling Chatterbox: %@"
- "LiveSpeechServices not available"
- "softlink:o:path:/System/Library/PrivateFrameworks/LiveSpeechServices.framework/LiveSpeechServices"
```
