## HealthActivityCache

> `/System/Library/Health/Plugins/HealthActivityCache.bundle/HealthActivityCache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20a78` | `0x211a8` | **`+0x730`** |
| `__TEXT.__objc_methtype` | `0x1907` | `0x1b5a` | **`+0x253`** |
| `__TEXT.__gcc_except_tab` | `0x2f8c` | `0x2ff4` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0xd40` | `0xda8` | **`+0x68`** |
| `__TEXT.__objc_stubs` | `0x3180` | `0x3140` | **`-0x40`** |
| `__DATA.__objc_const` | `0x24b8` | `0x24d8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x6a0` | `0x680` | **`-0x20`** |
| `__TEXT.__cstring` | `0xbc2` | `0xbb0` | **`-0x12`** |
| `__DATA.__objc_selrefs` | `0xf28` | `0xf18` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x4a0` | `0x4b0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x6b0` | `0x6c0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x370` | `0x378` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x41dc` | `0x41e3` | **`+0x7`** |
| `__DATA.__objc_ivar` | `0x250` | `0x254` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  Functions: 567
-  Symbols:   332
-  CStrings:  973
+  Functions: 577
+  Symbols:   335
+  CStrings:  971
Symbols:
+ _HDActivityCacheEntityEncodingOptionIncludeStatistics
+ ___kCFBooleanTrue
+ _memcmp
CStrings:
+ "_incrementalTotalsByTypeCode"
+ "setEncodingOption:forKey:"
+ "{map<_HKDataTypeCode, _HDActivityCacheIncrementalTotal, std::less<_HKDataTypeCode>, std::allocator<std::pair<const _HKDataTypeCode, _HDActivityCacheIncrementalTotal>>>=\"__tree_\"{__tree<std::__value_type<_HKDataTypeCode, _HDActivityCacheIncrementalTotal>, std::__map_value_compare<_HKDataTypeCode, std::pair<const _HKDataTypeCode, _HDActivityCacheIncrementalTotal>, std::less<_HKDataTypeCode>>, std::allocator<std::pair<const _HKDataTypeCode, _HDActivityCacheIncrementalTotal>>>=\"__begin_node_\"^v\"\"{?=\"__end_node_\"{__tree_end_node<std::__tree_node_base<void *> *>=\"__left_\"^v}}\"\"{?=\"__size_\"Q}}}"
+ "\x98\xc1"
- "distantFuture"
- "features"
- "qss.%@ IS NULL AND"
- "workoutSeriesAggregation"
- "\x98\x91"
- "\xf0\xd1"
```
