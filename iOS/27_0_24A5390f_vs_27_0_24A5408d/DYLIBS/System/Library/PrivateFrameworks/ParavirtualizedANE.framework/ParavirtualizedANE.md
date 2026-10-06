## ParavirtualizedANE

> `/System/Library/PrivateFrameworks/ParavirtualizedANE.framework/ParavirtualizedANE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fb48` | `0x202a4` | **`+0x75c`** |
| `__TEXT.__oslogstring` | `0x64a6` | `0x6600` | **`+0x15a`** |
| `__TEXT.__gcc_except_tab` | `0x3b48` | `0x3c98` | **`+0x150`** |
| `__AUTH_CONST.__objc_const` | `0x540` | `0x570` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xa18` | `0xa48` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x7e4` | `0x814` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x6f0` | `0x708` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x320` | `0x328` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x48` | `0x4c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-382.12.0.0.0
+382.15.1.0.0

-  Functions: 539
-  Symbols:   554
-  CStrings:  559
+  Functions: 545
+  Symbols:   564
+  CStrings:  563
Symbols:
+ -[_ANEVirtualModel baseKeeperProgram]
+ -[_ANEVirtualModel setBaseKeeperProgram:]
+ -[_ANEVirtualPlatformClient ensureBaseKeeperClientForBaseModelIdentifier:]
+ -[_ANEVirtualPlatformClient teardownFailedInstanceForVirtualModel:programHandle:]
+ GCC_except_table104
+ GCC_except_table105
+ GCC_except_table110
+ GCC_except_table111
+ GCC_except_table126
+ GCC_except_table127
+ GCC_except_table143
+ GCC_except_table151
+ GCC_except_table152
+ GCC_except_table156
+ GCC_except_table44
+ GCC_except_table57
+ GCC_except_table58
+ GCC_except_table64
+ GCC_except_table67
+ GCC_except_table70
+ GCC_except_table71
+ GCC_except_table75
+ GCC_except_table80
+ GCC_except_table90
+ GCC_except_table96
+ _OBJC_CLASS_$__ANEProgramForEvaluation
+ _OBJC_IVAR_$__ANEVirtualModel._baseKeeperProgram
+ _objc_retain_x24
+ _vm_kernel_page_size
- GCC_except_table106
- GCC_except_table107
- GCC_except_table112
- GCC_except_table113
- GCC_except_table141
- GCC_except_table148
- GCC_except_table149
- GCC_except_table154
- GCC_except_table46
- GCC_except_table59
- GCC_except_table60
- GCC_except_table66
- GCC_except_table69
- GCC_except_table72
- GCC_except_table73
- GCC_except_table77
- GCC_except_table82
- GCC_except_table92
- GCC_except_table98
CStrings:
+ "%@: ERROR IOSurface size (%llu) not within page padding of IOBuffer size (%llu) for procedure=%@, error=%@!"
+ "%@: base model for identifier=%@ not found in cache; cannot keep base direct-path client alive"
+ "%@: failed to open persistent base direct-path client for base programHandle=%llu"
+ "%@: failed to unload orphaned instance for programHandle=%llu, error=%@"
+ "%@: keeping base direct-path client alive for base programHandle=%llu identifier=%@"
- "%@: ERROR IOSurface size (%llu) doesn't match IOBuffer size (%llu) for procedure=%@, error=%@!"
```
