## ChronoServices

> `/System/Library/PrivateFrameworks/ChronoServices.framework/ChronoServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x100f60` | `0x1015d0` | **`+0x670`** |
| `__TEXT.__gcc_except_tab` | `0xab18` | `0xac38` | **`+0x120`** |
| `__TEXT.__cstring` | `0x5a35` | `0x5ac5` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x5200` | `0x5260` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x8244` | `0x829c` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x20210` | `0x20250` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3160` | `0x3198` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x6bb0` | `0x6be8` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x748` | `0x74c` | **`+0x4`** |

### Other Changes

```diff

-734.0.0.0.0
+740.0.0.0.0

-  Functions: 7329
-  Symbols:   6540
-  CStrings:  1326
+  Functions: 7337
+  Symbols:   6551
+  CStrings:  1329
Symbols:
+ -[CHSChronoServicesConnection containersPendingDescriptorResolution]
+ -[CHSWidgetExtensionProvider _shouldKeepHostedItem:]
+ -[CHSWidgetExtensionProvider shouldDeleteControl:]
+ -[CHSWidgetExtensionProvider shouldDeleteWidget:]
+ -[CHSWidgetExtensionsBox containersPendingDescriptorResolution]
+ -[CHSWidgetExtensionsBox initWithExtensions:generatedFrom:containersPendingDescriptorResolution:]
+ -[CHSWidgetExtensionsBox setContainersPendingDescriptorResolution:]
+ GCC_except_table120
+ GCC_except_table124
+ GCC_except_table126
+ GCC_except_table131
+ GCC_except_table135
+ GCC_except_table138
+ GCC_except_table144
+ GCC_except_table147
+ GCC_except_table72
+ GCC_except_table81
+ GCC_except_table83
+ GCC_except_table97
+ _CHSNonDefaultTestFamily
+ _OBJC_IVAR_$_CHSWidgetExtensionsBox._containersPendingDescriptorResolution
- GCC_except_table109
- GCC_except_table116
- GCC_except_table123
- GCC_except_table128
- GCC_except_table133
- GCC_except_table136
- GCC_except_table139
- GCC_except_table73
- GCC_except_table84
- GCC_except_table98
CStrings:
+ "containersPendingDescriptorResolution"
+ "shouldDeleteControl: requires a controls-scoped provider"
+ "shouldDeleteWidget: requires a widgets-scoped provider"
```
