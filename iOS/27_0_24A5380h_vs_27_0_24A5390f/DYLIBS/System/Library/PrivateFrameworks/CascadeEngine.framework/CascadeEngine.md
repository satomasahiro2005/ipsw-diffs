## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/CascadeEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xf00` | `0xe88` | **`-0x78`** |
| `__TEXT.__text` | `0x639f4` | `0x6399c` | **`-0x58`** |
| `__TEXT.__cstring` | `0x2a84` | `0x2a64` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1e8c` | `0x1eac` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x19f0` | `0x1a08` | **`+0x18`** |
| `__TEXT.__const` | `0x1248` | `0x1258` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xed8` | `0xee0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x670` | `0x678` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x6bc` | `0x6c0` | **`+0x4`** |

### Other Changes

```diff

-243.0.0.0.0
+247.0.1.0.0

-  Functions: 2263
-  Symbols:   2054
-  CStrings:  823
+  Functions: 2264
+  Symbols:   2056
+  CStrings:  822
Symbols:
+ -[CCRapportManager dealloc]
+ -[CCRapportManager registrationOptions]
+ -[CCRapportManager registrationStatusFlags]
+ GCC_except_table29
+ GCC_except_table36
+ GCC_except_table43
+ GCC_except_table8
+ _RPOptionStatusFlags
+ ___block_descriptor_80_e8_32s40s48r56r64r_e5_B8?0lr48l8r56l8r64l8s32l8s40l8
+ _clock_gettime_nsec_np
- GCC_except_table33
- GCC_except_table40
- ___55-[CCSetStoreAdminConnection _shouldDeferActivityBlock:]_block_invoke_3
- ___55-[CCSetStoreAdminConnection _shouldDeferActivityBlock:]_block_invoke_4
- ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
- ___block_descriptor_64_e8_32r40r48r56r_e5_v8?0lr32l8r40l8r48l8r56l8
- ___block_descriptor_80_e8_32r40r48r56r64r72r_e5_v8?0lr32l8r40l8r48l8r56l8r64l8r72l8
- ___block_descriptor_88_e8_32s40s48s56r64r72r_e5_B8?0ls32l8r56l8r64l8r72l8s40l8s48l8
CStrings:
- "com.apple.cascade.shouldDefer.state"
```
