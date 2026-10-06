## deleted_helper

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9754` | `0x9cc0` | **`+0x56c`** |
| `__DATA_CONST.__cfstring` | `0x620` | `0x680` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1dd2` | `0x1e24` | **`+0x52`** |
| `__TEXT.__cstring` | `0x8bf` | `0x8fd` | **`+0x3e`** |
| `__TEXT.__objc_stubs` | `0x8e0` | `0x900` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x777` | `0x781` | **`+0xa`** |
| `__DATA.__objc_selrefs` | `0x280` | `0x288` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x190` | `0x198` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-904.0.0.0.0
+904.0.5.0.0

-  Functions: 82
-  Symbols:   375
-  CStrings:  331
+  Functions: 84
+  Symbols:   378
+  CStrings:  334
Symbols:
+ ___block_descriptor_92_e8_32s40s48s56s64s72r_e5_v8?0lr72l8s32l8s40l8s48l8s56l8s64l8
+ _adjustBundleSizesForClones
+ _buildPurgeResult
+ _objc_msgSend$allValues
- ___block_descriptor_84_e8_32s40s48s56s64r_e5_v8?0lr64l8s32l8s40l8s48l8s56l8
CStrings:
+ "CLONE_CORRECTION"
+ "allValues"
+ "buildPurgeResult: Applied clone correction. Raw total: %llu, adjusted total: %llu"
```
