## libMetalMetricsInterpose.dylib

> `/usr/lib/libMetalMetricsInterpose.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1409c` | `0x14148` | **`+0xac`** |
| `__DATA_CONST.__cfstring` | `0x1e0` | `0x260` | **`+0x80`** |
| `__TEXT.__cstring` | `0x5bd` | `0x634` | **`+0x77`** |
| `__TEXT.__auth_stubs` | `0x820` | `0x850` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xba8` | `0xbc8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x420` | `0x438` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x12b8` | `0x12a8` | **`-0x10`** |
| `__DATA.__bss` | `0xf0` | `0xf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__thread_vars`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5.0.22.0.0
+5.0.24.0.0

-  Functions: 381
-  Symbols:   970
-  CStrings:  216
+  Functions: 386
+  Symbols:   978
+  CStrings:  220
Symbols:
+ FPMTLMetricsCanUseIMPTrampolines
+ FPMTLMetricsIsExcluded
+ FPMTLMetricsIsExcluded.isBlastDoor
+ FPMTLMetricsIsExcluded.onceToken
+ FPMTLMetricsIsProcessTranslated.onceToken
+ GCC_except_table23
+ GCC_except_table55
+ GCC_except_table63
+ _CFBundleGetIdentifier
+ _CFBundleGetMainBundle
+ _CFStringCompare
+ _FPMTLMetricsCanUseIMPTrampolines
+ _FPMTLMetricsIsExcluded
+ _OUTLINED_FUNCTION_1
+ ___FPMTLMetricsIsExcluded_block_invoke
+ ___FPMTLMetricsIsProcessTranslated_block_invoke
- FPMTLMetricsInterposeEnableCompilerStats
- GCC_except_table18
- GCC_except_table54
- GCC_except_table56
- GCC_except_table74
- __ZZ40FPMTLMetricsInterposeEnableCompilerStatsE10isAppleGPU
- __ZZ40FPMTLMetricsInterposeEnableCompilerStatsE9onceToken
- ___FPMTLMetricsInterposeEnableCompilerStats_block_invoke
CStrings:
+ "com.apple.InCallService"
+ "com.apple.MessagesAirlockService"
+ "com.apple.MessagesBlastDoorService"
+ "com.apple.gputoolsserviced"
```
