## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/FileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12e3f0` | `0x12e738` | **`+0x348`** |
| `__AUTH_CONST.__objc_const` | `0x25030` | `0x250f8` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x14f02` | `0x14f9f` | **`+0x9d`** |
| `__AUTH_CONST.__cfstring` | `0x11640` | `0x116c0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x6240` | `0x62a0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xea4c` | `0xeaa4` | **`+0x58`** |
| `__TEXT.__ustring` | `0x21e` | `0x25a` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x7128` | `0x7150` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1da8` | `0x1dc8` | **`+0x20`** |
| `__DATA.__bss` | `0xc50` | `0xc60` | **`+0x10`** |
| `__TEXT.__const` | `0x89a` | `0x88a` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x5998` | `0x59a8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb18` | `0xb20` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x10d0` | `0x10d4` | **`+0x4`** |

### Other Changes

```diff

-4838.40.92.502.1
+4838.40.130.0.2

-  Functions: 7478
-  Symbols:   11232
-  CStrings:  4065
+  Functions: 7488
+  Symbols:   11246
+  CStrings:  4071
Symbols:
+ +[FPProviderDomain migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]
+ -[FPAccessControlManager transferAccessToAllItemsFromBundle:toBundle:completionHandler:]
+ -[FPAccessControlManager withServicerProxy:]
+ -[NSFileProviderDomain migrationState]
+ -[NSFileProviderDomain setMigrationState:]
+ _GSSTORAGE_FP_PROVIDER_CONTENT_VERSION_XATTR_NAME
+ _OBJC_IVAR_$_NSFileProviderDomain._migrationState
+ ___44-[FPAccessControlManager withServicerProxy:]_block_invoke
+ ___88-[FPAccessControlManager transferAccessToAllItemsFromBundle:toBundle:completionHandler:]_block_invoke
+ ___99+[FPProviderDomain migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v16?0"<FPDAccessControlServicing>"8ls32l8
+ ___block_descriptor_56_e8_32s40s48bs_e37_v16?0"<FPDAccessControlServicing>"8ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48bs_e37_v16?0"<FPDAccessControlServicing>"8ls32l8s48l8s40l8
+ ___fpfs_supports_appDomainMigration_block_invoke
+ _fpfs_supports_appDomainMigration
+ _fpfs_supports_appDomainMigration.feature_enabled
+ _fpfs_supports_appDomainMigration.once_token
+ _kFileProviderSupersededAppReplacementEntitlement
- GCC_except_table99
- ___76-[FPAccessControlManager revokeAccessToAllItemsForBundle:completionHandler:]_block_invoke_3
- ___80-[FPAccessControlManager bundleIdentifiersWithAccessToAnyItemCompletionHandler:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48bs_e49_v24?0"<FPDAccessControlServicing>"8"NSError"16ls48l8s32l8s40l8
CStrings:
+ "(⏹  superseded app migration)"
+ ",migrating"
+ "4838.40.130.0.2"
+ "DISCONNECTION_REASON_SUPERSEDED_APP_MIGRATION"
+ "access control servicer"
+ "appDomainMigration"
+ "com.apple.private.fileprovider.superseded-app-replacement"
+ "v16@?0@\"<FPDAccessControlServicing>\"8"
- "4838.40.92.502.1"
- "com.apple.genstore.fp_provider_cver#C"
```
