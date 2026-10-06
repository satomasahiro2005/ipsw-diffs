## LinkMetadata

> `/System/Library/PrivateFrameworks/LinkMetadata.framework/LinkMetadata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13a0fc` | `0x13d514` | **`+0x3418`** |
| `__DATA.__bss` | `0x1f190` | `0x1dc90` | **`-0x1500`** |
| `__DATA_DIRTY.__bss` | `0x6438` | `0x7930` | **`+0x14f8`** |
| `__DATA_DIRTY.__data` | `0x2348` | `0x27e8` | **`+0x4a0`** |
| `__AUTH.__objc_data` | `0x11b8` | `0xf30` | **`-0x288`** |
| `__DATA_DIRTY.__objc_data` | `0x24e8` | `0x2770` | **`+0x288`** |
| `__AUTH.__data` | `0xd38` | `0xb50` | **`-0x1e8`** |
| `__AUTH_CONST.__objc_const` | `0x10588` | `0x106c8` | **`+0x140`** |
| `__DATA.__data` | `0x4260` | `0x4120` | **`-0x140`** |
| `__TEXT.__eh_frame` | `0x6274` | `0x619c` | **`-0xd8`** |
| `__TEXT.__cstring` | `0xbb2c` | `0xbbf6` | **`+0xca`** |
| `__AUTH_CONST.__cfstring` | `0x69a0` | `0x6a60` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x8a3c` | `0x8ae4` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0xf7b` | `0x100a` | **`+0x8f`** |
| `__AUTH_CONST.__auth_got` | `0x13f8` | `0x1478` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x4480` | `0x44e0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x5da8` | `0x5e00` | **`+0x58`** |
| `__DATA_CONST.__const` | `0xe48` | `0xe98` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d90` | `0x2dd8` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x50b8` | `0x50fc` | **`+0x44`** |
| `__TEXT.__const` | `0x13134` | `0x13154` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1e89` | `0x1ea9` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x570` | `0x584` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x870` | `0x880` | **`+0x10`** |
| `__DATA.__common` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe20` | `0xe28` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0x90` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x38` | `0x40` | **`+0x8`** |

### Other Changes

```diff

-301.0.43.6.0
+301.0.45.4.101

-  Functions: 10012
-  Symbols:   9108
-  CStrings:  1572
+  Functions: 10062
+  Symbols:   9146
+  CStrings:  1583
Symbols:
+ +[LNPackageMetadata(Testing) _test_urlForLibraryName:loaderPath:executablePath:rpaths:]
+ -[LNActionMetadataBuilder setSourceBundleIdentifier:]
+ -[LNActionMetadataBuilder sourceBundleIdentifier]
+ -[LNEntityMetadataBuilder setSourceBundleIdentifier:]
+ -[LNEntityMetadataBuilder sourceBundleIdentifier]
+ -[LNEnumMetadataBuilder setSourceBundleIdentifier:]
+ -[LNEnumMetadataBuilder sourceBundleIdentifier]
+ -[LNParameter copyWithZone:]
+ -[LNProperty copyWithZone:]
+ -[LNProperty deferredProperty]
+ -[LNProperty isDeferred]
+ -[LNValue ln_approximateArchivedSizeWithBudget:]
+ -[LSBundleRecord(LNAdditions) ln_attributionBundleIdentifier]
+ GCC_except_table1051
+ GCC_except_table1054
+ GCC_except_table1055
+ GCC_except_table1080
+ GCC_except_table1224
+ GCC_except_table1234
+ GCC_except_table1236
+ GCC_except_table1238
+ GCC_except_table1243
+ GCC_except_table1245
+ GCC_except_table1247
+ GCC_except_table1249
+ GCC_except_table1252
+ GCC_except_table1605
+ GCC_except_table1619
+ GCC_except_table1947
+ GCC_except_table1952
+ GCC_except_table1958
+ GCC_except_table1962
+ GCC_except_table1964
+ GCC_except_table1967
+ GCC_except_table1969
+ GCC_except_table2420
+ GCC_except_table2421
+ GCC_except_table2462
+ GCC_except_table2803
+ GCC_except_table2835
+ _LNApproxSize_AttributedString
+ _LNApproximateArchivedSize
+ _LNApproximateArchivedSizeImpl
+ _LNPerValueArchivedSizeLimit
+ _NSInvalidArchiveOperationException
+ _OBJC_IVAR_$_LNActionMetadataBuilder._sourceBundleIdentifier
+ _OBJC_IVAR_$_LNEntityMetadataBuilder._sourceBundleIdentifier
+ _OBJC_IVAR_$_LNEnumMetadataBuilder._sourceBundleIdentifier
+ _OBJC_IVAR_$_LNProperty._deferred
+ _OUTLINED_FUNCTION_258
+ _OUTLINED_FUNCTION_673
+ __OBJC_$_CLASS_METHODS_LNPackageMetadata(LinkMetadata|LinkMetadata1|Testing)
+ __OBJC_$_INSTANCE_METHODS_LNPackageMetadata(LinkMetadata|LinkMetadata1|Testing)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_LNApproximateArchivedSizeProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LNApproximateArchivedSizeProviding
+ __OBJC_$_PROTOCOL_REFS_LNApproximateArchivedSizeProviding
+ __OBJC_LABEL_PROTOCOL_$_LNApproximateArchivedSizeProviding
+ __OBJC_PROTOCOL_$_LNApproximateArchivedSizeProviding
+ __OBJC_PROTOCOL_REFERENCE_$_LNApproximateArchivedSizeProviding
+ ___LNApproxSize_AttributedString_block_invoke
+ ___block_descriptor_56_e8_32r40r_e41_v40?0"NSDictionary"8{_NSRange=QQ}16^B32lr32l8r40l8
+ ___block_descriptor_64_e8_32r_e17_v32?0r*8r*16^B24lr32l8
+ _macho_for_each_exported_symbol
+ _malloc_type_calloc
+ _swift_release_x10
+ _symbolic SS4name______3urlt 10Foundation3URLV
+ _symbolic SS4name______3urltSg 10Foundation3URLV
+ _symbolic _____ySS4name______3urltG s23_ContiguousArrayStorageC 10Foundation3URLV
- GCC_except_table1045
- GCC_except_table1048
- GCC_except_table1049
- GCC_except_table1073
- GCC_except_table1216
- GCC_except_table1218
- GCC_except_table1228
- GCC_except_table1230
- GCC_except_table1235
- GCC_except_table1237
- GCC_except_table1239
- GCC_except_table1241
- GCC_except_table1244
- GCC_except_table1597
- GCC_except_table1611
- GCC_except_table1934
- GCC_except_table1939
- GCC_except_table1945
- GCC_except_table1949
- GCC_except_table1951
- GCC_except_table1954
- GCC_except_table1956
- GCC_except_table2407
- GCC_except_table2408
- GCC_except_table2785
- GCC_except_table2817
- _OUTLINED_FUNCTION_255
- _OUTLINED_FUNCTION_665
- __OBJC_$_CLASS_METHODS_LNPackageMetadata
- __OBJC_$_INSTANCE_METHODS_LNPackageMetadata(LinkMetadata|LinkMetadata1)
CStrings:
+ "%s -> %s defined in current image"
+ "(nil)"
+ "(unknown)"
+ "<%@: %p, identifier: %@, value: %@, deferred: %@>"
+ "Contents/Resources"
+ "LNValue payload exceeds %lld-byte cap. valueType=%{public}@ valueClass=%{public}@ ctx=%{public}s"
+ "LNValue payload exceeds the %lld-byte per-value cap. valueType=%@ valueClass=%@"
+ "LinkProgrammaticInterface-301.0.45.4.101"
+ "NSXPCEncoder"
+ "deferred"
+ "metadata `%s' did not match any imported or exported symbol."
+ "non-xpc"
+ "v32@?0r*8r*16^B24"
+ "xpc"
- "<%@: %p, identifier: %@, value: %@>"
- "LinkProgrammaticInterface-301.0.43.6"
- "metadata `%s' did not match any imported symbol."
```
