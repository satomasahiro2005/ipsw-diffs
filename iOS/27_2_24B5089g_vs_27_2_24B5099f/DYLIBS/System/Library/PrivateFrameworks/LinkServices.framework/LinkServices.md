## LinkServices

> `/System/Library/PrivateFrameworks/LinkServices.framework/LinkServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14b760` | `0x14f828` | **`+0x40c8`** |
| `__DATA.__data` | `0x28ac` | `0x296c` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x2e12` | `0x2ec6` | **`+0xb4`** |
| `__AUTH_CONST.__auth_got` | `0x1850` | `0x18b8` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x6540` | `0x64e0` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x9ff3` | `0xa049` | **`+0x56`** |
| `__TEXT.__const` | `0x7878` | `0x78c8` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x16f68` | `0x16fa8` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x54e0` | `0x5518` | **`+0x38`** |
| `__TEXT.__cstring` | `0xc821` | `0xc851` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xb340` | `0xb370` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x5c40` | `0x5c70` | **`+0x30`** |
| `__DATA.__bss` | `0x4818` | `0x4828` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x19d8` | `0x19e8` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x4cb0` | `0x4cc0` | **`+0x10`** |
| `__DATA.__common` | `0x70` | `0x78` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb14` | `0xb10` | **`-0x4`** |

### Other Changes

```diff

-301.1.10.2.101
+301.1.15.0.0

-  Functions: 8849
-  Symbols:   9256
-  CStrings:  2271
+  Functions: 8879
+  Symbols:   9275
+  CStrings:  2273
Symbols:
+ +[LNEmbeddedApplicationLauncher openApplicationService]
+ -[LNExportedContent ln_approximateArchivedSizeWithBudget:]
+ -[LNSchemaDialogWhen(LinkServices) propertyValueNamed:ofEntityValue:]
+ GCC_except_table1263
+ GCC_except_table1269
+ GCC_except_table3124
+ GCC_except_table3127
+ GCC_except_table3179
+ GCC_except_table3275
+ GCC_except_table3287
+ GCC_except_table3337
+ GCC_except_table3342
+ GCC_except_table3346
+ GCC_except_table3359
+ GCC_except_table3383
+ GCC_except_table3387
+ GCC_except_table3518
+ GCC_except_table3533
+ _LNApproximateArchivedSize
+ _OBJC_CLASS_$_NSTextCheckingResult
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_LNApproximateArchivedSizeProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LNApproximateArchivedSizeProviding
+ __OBJC_$_PROTOCOL_REFS_LNApproximateArchivedSizeProviding
+ __OBJC_LABEL_PROTOCOL_$_LNApproximateArchivedSizeProviding
+ __OBJC_PROTOCOL_$_LNApproximateArchivedSizeProviding
+ ___55+[LNEmbeddedApplicationLauncher openApplicationService]_block_invoke
+ ___69-[LNSchemaDialogWhen(LinkServices) propertyValueNamed:ofEntityValue:]_block_invoke
+ __os_log_default
+ __os_log_error_impl
+ _openApplicationService.onceToken
+ _openApplicationService.service
+ _symbolic ShySSG
+ _symbolic So23LNSchemaDialogStatementCSg
+ _symbolic So31LNStaticDeferredLocalizedStringCSg
+ _symbolic _____ySSShySSGG s17_NativeDictionaryV
+ _symbolic _____ySo23LNSchemaDialogStatementCSgG s23_ContiguousArrayStorageC
+ _symbolic _____ySo31LNStaticDeferredLocalizedStringCSgG s23_ContiguousArrayStorageC
- -[LNEmbeddedApplicationLauncher preflightManager]
- -[LNEmbeddedApplicationLauncher setPreflightManager:]
- GCC_except_table1265
- GCC_except_table1273
- GCC_except_table3123
- GCC_except_table3126
- GCC_except_table3176
- GCC_except_table3272
- GCC_except_table3284
- GCC_except_table3334
- GCC_except_table3339
- GCC_except_table3343
- GCC_except_table3356
- GCC_except_table3380
- GCC_except_table3384
- GCC_except_table3515
- GCC_except_table3530
- _OBJC_IVAR_$_LNEmbeddedApplicationLauncher._preflightManager
CStrings:
+ "Schema dialog When: entity property '%{public}@' not found; branching on absent value"
+ "\\$\\{([^.#}]+)(?:\\.([^#}]+))?#("
+ "\\$\\{([^.}]+)\\.([^#}]+)\\}"
+ "hydrateEntities(entityParameterInfos:connection:requestedProperties:)"
- "\\$\\{([^.}]+)\\.([^}]+)\\}"
- "hydrateEntities(entityParameterInfos:connection:)"
```
