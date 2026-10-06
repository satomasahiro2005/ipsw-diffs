## Pasteboard

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Pasteboard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27eac` | `0x28490` | **`+0x5e4`** |
| `__TEXT.__oslogstring` | `0x1670` | `0x171d` | **`+0xad`** |
| `__AUTH_CONST.__objc_const` | `0x30f8` | `0x3128` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x22c0` | `0x22f0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x15a0` | `0x15c8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1568` | `0x1588` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1ba8` | `0x1bbd` | **`+0x15`** |
| `__TEXT.__unwind_info` | `0xe78` | `0xe88` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x830` | `0x83c` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x1b0` | `0x1b4` | **`+0x4`** |

### Other Changes

```diff

-9127.0.84.1.102
+9127.1.3.0.0

-  Functions: 1075
-  Symbols:   1819
-  CStrings:  314
+  Functions: 1081
+  Symbols:   1833
+  CStrings:  324
Symbols:
+ -[PBItemCollection itemQueue_originatorPid]
+ -[PBItemCollection originatorPid]
+ -[PBItemCollection setItemQueue_originatorPid:]
+ -[PBItemCollection setOriginatorPid:]
+ GCC_except_table106
+ GCC_except_table118
+ GCC_except_table124
+ GCC_except_table82
+ GCC_except_table93
+ _OBJC_IVAR_$_PBItemCollection._itemQueue_originatorPid
+ ___33-[PBItemCollection originatorPid]_block_invoke
+ ___37-[PBItemCollection setOriginatorPid:]_block_invoke
+ ___block_descriptor_44_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_60_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_72_e8_32s40s48bs_e70_v40?0"NSData"8"PBSecurityScopedURLWrapper"16"NSError"24"NSUUID"32ls32l8s48l8s40l8
+ ___block_descriptor_88_e8_32s40s48s56bs64r_e68_v40?0"NSData"8"PBSecurityScopedURLWrapper"16"NSError"24?<v?>32ls32l8s40l8r64l8s48l8s56l8
+ __os_signpost_emit_with_name_impl
+ _os_signpost_enabled
+ _os_signpost_id_generate
+ _pthread_getname_np
+ _pthread_self
+ _pthread_setname_np
+ _snprintf
- GCC_except_table102
- GCC_except_table114
- GCC_except_table120
- GCC_except_table78
- GCC_except_table89
- ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_64_e8_32s40s48bs_e70_v40?0"NSData"8"PBSecurityScopedURLWrapper"16"NSError"24"NSUUID"32ls32l8s48l8s40l8
- ___block_descriptor_80_e8_32s40s48s56bs64r_e68_v40?0"NSData"8"PBSecurityScopedURLWrapper"16"NSError"24?<v?>32ls32l8s40l8r64l8s48l8s56l8
- _objc_retain_x28
CStrings:
+ "?"
+ "PromisedDataFault"
+ "PromisedDataLoad"
+ "failed peer=%d"
+ "index out of range"
+ "index=%lu type=%{public}@"
+ "no representation"
+ "pb-fault pid %d %s"
+ "peer=%d sync=%d index=%lu type=%{public}@"
+ "replied bytes=%lu"
+ "\xf0Q"
- "\xf0A"
```
