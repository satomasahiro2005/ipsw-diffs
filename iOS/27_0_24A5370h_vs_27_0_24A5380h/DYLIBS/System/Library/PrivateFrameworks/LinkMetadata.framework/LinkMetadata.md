## LinkMetadata

> `/System/Library/PrivateFrameworks/LinkMetadata.framework/LinkMetadata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x139520` | `0x13a0fc` | **`+0xbdc`** |
| `__AUTH_CONST.__objc_const` | `0x104b0` | `0x10588` | **`+0xd8`** |
| `__AUTH.__data` | `0xc90` | `0xd38` | **`+0xa8`** |
| `__AUTH_CONST.__const` | `0xc5e0` | `0xc670` | **`+0x90`** |
| `__TEXT.__const` | `0x130a4` | `0x13134` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x310c` | `0x3164` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x5d50` | `0x5da8` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0xf26` | `0xf7b` | **`+0x55`** |
| `__TEXT.__swift5_typeref` | `0x5064` | `0x50b8` | **`+0x54`** |
| `__AUTH.__objc_data` | `0x1168` | `0x11b8` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x2538` | `0x24e8` | **`-0x50`** |
| `__TEXT.__cstring` | `0xbae2` | `0xbb2c` | **`+0x4a`** |
| `__TEXT.__eh_frame` | `0x622c` | `0x6274` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x4448` | `0x4480` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x13d0` | `0x13f8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d68` | `0x2d90` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x6980` | `0x69a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x8a1c` | `0x8a3c` | **`+0x20`** |
| `__DATA.__data` | `0x4250` | `0x4260` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2358` | `0x2348` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1e7d` | `0x1e89` | **`+0xc`** |
| `__DATA_CONST.__const` | `0xe40` | `0xe48` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe28` | `0xe20` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x538` | `0x540` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4ec` | `0x4f4` | **`+0x8`** |

### Other Changes

```diff

-301.0.42.7.0
+301.0.43.6.0

-  Functions: 9988
-  Symbols:   9097
-  CStrings:  1568
+  Functions: 10012
+  Symbols:   9108
+  CStrings:  1572
Symbols:
+ +[NSBundle(StaticExtraction) ln_uniqueBundleWithCachingForPath:]
+ +[NSBundle(StaticExtraction) ln_uniqueBundleWithCachingForURL:]
+ -[LNStaticDeferredLocalizedString localizedStringForLocaleIdentifier:uniqueBundle:]
+ GCC_except_table1597
+ GCC_except_table1611
+ GCC_except_table1934
+ GCC_except_table1939
+ GCC_except_table1945
+ GCC_except_table1949
+ GCC_except_table1951
+ GCC_except_table1954
+ GCC_except_table1956
+ GCC_except_table2407
+ GCC_except_table2408
+ GCC_except_table2785
+ GCC_except_table2817
+ _LNActionConfigurationContextWidgetFamilySystemExtraLargePortrait
+ _OUTLINED_FUNCTION_1353
+ __DATA__TtC12LinkMetadata17UniqueBundleCache
+ __IVARS__TtC12LinkMetadata17UniqueBundleCache
+ __METACLASS_DATA__TtC12LinkMetadata17UniqueBundleCache
+ _symbolic SDy_____So8NSBundleCG 10Foundation3URLV
+ _symbolic _____ 12LinkMetadata0aB7VersionO
+ _symbolic _____ 12LinkMetadata17UniqueBundleCacheC
+ _symbolic _____ySDy_____So8NSBundleCGG 15Synchronization5MutexVAARi_zrlE 10Foundation3URLV
+ _symbolic _____y_____So8NSBundleCG s17_NativeDictionaryV 10Foundation3URLV
- GCC_except_table1596
- GCC_except_table1610
- GCC_except_table1933
- GCC_except_table1938
- GCC_except_table1944
- GCC_except_table1948
- GCC_except_table1950
- GCC_except_table1953
- GCC_except_table1955
- GCC_except_table2404
- GCC_except_table2405
- GCC_except_table2782
- GCC_except_table2814
- _get_type_metadata 15Synchronization5MutexVy12LinkMetadata16EntitlementCacheV5State33_319CBF348F19F2181A789093F567D54CLLVG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "Allocating UniqueBundleCache: %s"
+ "Deallocating UniqueBundleCache: %s"
+ "LinkProgrammaticInterface-301.0.43.6"
+ "systemExtraLargePortrait"
```
