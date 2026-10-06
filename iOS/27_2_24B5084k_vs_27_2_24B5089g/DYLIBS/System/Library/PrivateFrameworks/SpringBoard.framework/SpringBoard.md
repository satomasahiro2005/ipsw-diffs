## SpringBoard

> `/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xe5b0` | `0xd840` | **`-0xd70`** |
| `__DATA_DIRTY.__objc_data` | `0x26c00` | `0x27970` | **`+0xd70`** |
| `__TEXT.__text` | `0xb0fd48` | `0xb0fec4` | **`+0x17c`** |
| `__DATA.__bss` | `0xaa8` | `0x970` | **`-0x138`** |
| `__DATA_DIRTY.__bss` | `0x18c8` | `0x19f8` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0x10be8` | `0x10c48` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x6588f` | `0x658b2` | **`+0x23`** |
| `__AUTH_CONST.__objc_const` | `0x288db8` | `0x288dd8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x18630` | `0x1864c` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0xbe028` | `0xbe040` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4eb10` | `0x4eb20` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2e648` | `0x2e658` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xfca4` | `0xfca8` | **`+0x4`** |

### Other Changes

```diff

-4637.1.7.0.0
+4637.1.8.101.0

-  Functions: 73621
-  Symbols:   119469
-  CStrings:  23574
+  Functions: 73627
+  Symbols:   119477
+  CStrings:  23575
Symbols:
+ -[SpringBoard _resumeAppReplacementIfNecessary]
+ -[_SBSATimerAndDescriptionRecord dealloc]
+ GCC_except_table161
+ GCC_except_table203
+ GCC_except_table259
+ GCC_except_table263
+ GCC_except_table373
+ GCC_except_table405
+ GCC_except_table451
+ _OBJC_IVAR_$_SBBackgroundAngelKeepAliveHandler._handleLastGrantedBootstrap
+ ___47-[SpringBoard _resumeAppReplacementIfNecessary]_block_invoke
+ ___47-[SpringBoard _resumeAppReplacementIfNecessary]_block_invoke_2
+ ___47-[SpringBoard _resumeAppReplacementIfNecessary]_block_invoke_3
+ ___block_descriptor_56_e8_32s40s48w_e40_v16?0"<RBSProcessMonitorConfiguring>"8ls32l8s40l8w48l8
- GCC_except_table347
- GCC_except_table388
- GCC_except_table396
- GCC_except_table401
- GCC_except_table443
- ___block_descriptor_48_e8_32s40w_e40_v16?0"<RBSProcessMonitorConfiguring>"8ls32l8w40l8
CStrings:
+ "Error resuming app replacement: %@"
```
