## CoreCaptureDaemon

> `/System/Library/PrivateFrameworks/CoreCaptureDaemon.framework/CoreCaptureDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b220` | `0x5aea4` | **`-0x37c`** |
| `__TEXT.__oslogstring` | `0xb554` | `0xb4fa` | **`-0x5a`** |
| `__DATA_CONST.__const` | `0x3d0` | `0x390` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x4ec` | `0x4d4` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x7d0` | `0x7c8` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x11` | `0x14` | **`+0x3`** |

### Other Changes

```diff

-1355.39.0.0.0
+1355.41.0.0.0

-  Functions: 613
-  Symbols:   1150
-  CStrings:  1232
+  Functions: 611
+  Symbols:   1147
+  CStrings:  1231
Symbols:
+ GCC_except_table605
+ GCC_except_table606
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__15dequeI14StackshotEntryNS_9allocatorIS1_EEED2B9fqe220106Ev
+ __ZNSt3__16vectorIP17_xpc_connection_sNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__19allocatorIP14StackshotEntryE17allocate_at_leastB9fqe220106Em
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- GCC_except_table596
- GCC_except_table607
- GCC_except_table608
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__15dequeI14StackshotEntryNS_9allocatorIS1_EEED2B9fqe220100Ev
- __ZNSt3__16vectorIP17_xpc_connection_sNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__19allocatorIP14StackshotEntryE17allocate_at_leastB9fqe220100Em
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ____ZN9CCLogFile9closeFileEv_block_invoke
- ____ZN9CCLogFile9closeFileEv_block_invoke_2
CStrings:
+ "owner=%s pipe=%s fileName=%s offset=%zu length=%zu fileDesc=%d"
- "owner=%s pipe=%s fileName=%s offset=%zu length=%zu fileDesc=%d phase=async"
- "owner=%s pipe=%s fileName=%s offset=%zu length=%zu fileDesc=%d phase=shutdown"
```
