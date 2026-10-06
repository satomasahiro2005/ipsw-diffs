## QuickLookSupport

> `/System/Library/PrivateFrameworks/QuickLookSupport.framework/QuickLookSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x4a8` | `0x480` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0x330` | `0x318` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x1338` | `0x1348` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x708` | `0x6f8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xeb0` | `0xeb8` | **`+0x8`** |
| `__TEXT.__text` | `0x15794` | `0x1579c` | **`+0x8`** |

### Other Changes

```diff

-217.0.0.0.0
+218.0.0.0.0

-  Symbols:   1322
+  Symbols:   1321
Symbols:
+ +[QLUTIManager _searchAndStoreValueInTypeKeyedDictionary:forType:withDescription:validationBlock:]
+ ___98+[QLUTIManager _searchAndStoreValueInTypeKeyedDictionary:forType:withDescription:validationBlock:]_block_invoke
+ ___block_descriptor_80_e8_32s40s48s56bs64r_e5_v8?0lr64l8s32l8s40l8s48l8s56l8
- GCC_except_table1
- ___105+[QLUTIManager findAndStoreValueInTypeKeyedDictionary:forType:withDescription:withQueue:validationBlock:]_block_invoke_2
- ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
- ___block_descriptor_72_e8_32s40s48s56bs64r_e5_v8?0lr64l8s32l8s40l8s48l8s56l8
Functions:
~ +[QLUTIManager findAndStoreValueInTypeKeyedDictionary:forType:withDescription:withQueue:validationBlock:] : 556 -> 456
~ ___105+[QLUTIManager findAndStoreValueInTypeKeyedDictionary:forType:withDescription:withQueue:validationBlock:]_block_invoke : 220 -> 84
~ ___105+[QLUTIManager findAndStoreValueInTypeKeyedDictionary:forType:withDescription:withQueue:validationBlock:]_block_invoke_2 -> +[QLUTIManager _searchAndStoreValueInTypeKeyedDictionary:forType:withDescription:validationBlock:] : 440 -> 256
~ _QLSLogHandle -> ___98+[QLUTIManager _searchAndStoreValueInTypeKeyedDictionary:forType:withDescription:validationBlock:]_block_invoke : 72 -> 444
~ ___105+[QLUTIManager findAndStoreValueInTypeKeyedDictionary:forType:withDescription:withQueue:validationBlock:]_block_invoke.3 -> _QLSLogHandle : 16 -> 72
```
