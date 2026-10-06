## iOSDiagnostics

> `/System/Library/PrivateFrameworks/iOSDiagnostics.framework/iOSDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55dc` | `0x58d8` | **`+0x2fc`** |
| `__AUTH_CONST.__objc_const` | `0x1bb8` | `0x1c08` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x380` | `0x3a8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x718` | `0x740` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xa1c` | `0xa44` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x208` | `0x228` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb8` | `0xd4` | **`+0x1c`** |
| `__TEXT.__cstring` | `0xb07` | `0xb11` | **`+0xa`** |
| `__DATA.__objc_ivar` | `0x78` | `0x80` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x140` | `0x148` | **`+0x8`** |

### Other Changes

```diff

-1374.0.27.0.0
+1374.2.1.0.0

-  Functions: 191
-  Symbols:   484
-  CStrings:  94
+  Functions: 195
+  Symbols:   494
+  CStrings:  95
Symbols:
+ -[DADiagnosticsLauncher clearDiagnosticsCheckupServiceIfEqualTo:]
+ -[DADiagnosticsLauncher diagnosticsCheckupService]
+ -[DADiagnosticsLauncher setDiagnosticsCheckupService:]
+ GCC_except_table16
+ GCC_except_table18
+ _OBJC_CLASS_$_NSLock
+ _OBJC_IVAR_$_DADiagnosticsLauncher._diagnosticsCheckupServiceLock
+ _OBJC_IVAR_$_DADiagnosticsLauncher._diagnosticsCheckupServiceStorage
+ ___51-[DADiagnosticsLauncher _establishDaemonConnection]_block_invoke
+ ___block_descriptor_48_e8_32w40w_e8_v16?0q8lw32l8w40l8
+ _objc_retain_x8
- GCC_except_table14
CStrings:
+ "v16@?0q8"
```
