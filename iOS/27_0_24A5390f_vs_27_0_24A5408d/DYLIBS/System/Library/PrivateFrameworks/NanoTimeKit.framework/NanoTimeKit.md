## NanoTimeKit

> `/System/Library/PrivateFrameworks/NanoTimeKit.framework/NanoTimeKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fd464` | `0x2fd820` | **`+0x3bc`** |
| `__TEXT.__oslogstring` | `0x1542e` | `0x1548e` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x20ba0` | `0x20be0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1dc9e` | `0x1dcce` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x53a00` | `0x53a20` | **`+0x20`** |
| `__DATA.__bss` | `0x5b50` | `0x5b40` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x14d10` | `0x14d20` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2fff8` | `0x30008` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3290` | `0x3288` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x28e0` | `0x28e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd488` | `0xd490` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x39a8` | `0x39ac` | **`+0x4`** |

### Other Changes

```diff

-2483.512.0.0.0
+2483.523.0.4.0

-  Functions: 20308
-  Symbols:   34018
-  CStrings:  6396
+  Functions: 20314
+  Symbols:   34023
+  CStrings:  6399
Symbols:
+ +[NTKComplication(Defines) siriComplication]
+ -[NTKBundleComplicationManager prewarmCaches]
+ GCC_except_table139
+ GCC_except_table149
+ GCC_except_table87
+ _NTKDemoModeFProgramNumber
+ _NTKIsRunningInStoreDemoMode
+ _NTKIsRunningInStoreOrPressDemoMode
+ _OBJC_IVAR_$_NTKTritiumDefaults._npsManager
- -[NTKTritiumDefaults reload]
- GCC_except_table146
- _NTKCheckInApplicationBundleIdentifier_block_invoke.value
- _OBJC_CLASS_$_NSCollectionLayoutSpacing
CStrings:
+ "com.apple.SiriApp.watchapp"
+ "com.apple.SiriComplication"
+ "description=NanoTimeKit-2483.523.0.4"
+ "system app (%@) is in the always-present allowlist; treating as not restricted/removed"
- "description=NanoTimeKit-2483.512"
```
