## RemoteManagementStore

> `/System/Library/PrivateFrameworks/RemoteManagementStore.framework/RemoteManagementStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3aef0` | `0x3b9b0` | **`+0xac0`** |
| `__TEXT.__objc_methlist` | `0x2420` | `0x2468` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x36b8` | `0x36f0` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x3407` | `0x3437` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1598` | `0x15c0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xea0` | `0xec8` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x164` | `0x184` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x400` | `0x410` | **`+0x10`** |
| `__TEXT.__const` | `0x53c` | `0x54c` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xd0` | `0xdc` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x1b0` | `0x1b4` | **`+0x4`** |

### Other Changes

```diff

-624.0.10.0.0
+624.2.3.0.0

-  Functions: 1351
-  Symbols:   1748
+  Functions: 1362
+  Symbols:   1760
Symbols:
+ +[RMAssetResolverController _fetchDeclarationWithAssetIdentifier:storeIdentifier:scope:completionHandler:]
+ +[RMAssetResolverController _resolveDataAsset:assetIdentifier:store:completionHandler:]
+ +[RMAssetResolverController resolveDataAssetWithAssetIdentifier:storeIdentifier:scope:completionHandler:]
+ -[RMStoreResolvedAsset serverReportedContentType]
+ -[RMStoreResolvedAsset setServerReportedContentType:]
+ _OBJC_CLASS_$_RMModelSecurityCertificateDeclaration
+ _OBJC_IVAR_$_RMStoreResolvedAsset._serverReportedContentType
+ _RMConfigurationTypeExtensibleSSO
+ ___105+[RMAssetResolverController resolveDataAssetWithAssetIdentifier:storeIdentifier:scope:completionHandler:]_block_invoke
+ ___106+[RMAssetResolverController _fetchDeclarationWithAssetIdentifier:storeIdentifier:scope:completionHandler:]_block_invoke
+ ___106+[RMAssetResolverController _fetchDeclarationWithAssetIdentifier:storeIdentifier:scope:completionHandler:]_block_invoke_2
+ ___87+[RMAssetResolverController _resolveDataAsset:assetIdentifier:store:completionHandler:]_block_invoke
+ ___87+[RMAssetResolverController _resolveDataAsset:assetIdentifier:store:completionHandler:]_block_invoke_2
+ ___block_descriptor_56_e8_32s40bs_e66_v32?0"RMModelDeclarationBase"8"RMSubscriberStore"16"NSError"24ls40l8s32l8
+ ___block_descriptor_64_e8_32s40s48bs_e66_v32?0"RMModelDeclarationBase"8"RMSubscriberStore"16"NSError"24ls48l8s32l8s40l8
- ___117+[RMAssetResolverController resolveDataAssetWithAssetIdentifier:downloadURL:storeIdentifier:scope:completionHandler:]_block_invoke_2
- ___block_descriptor_64_e8_32s40s48bs_e39_v24?0"RMSubscriberStore"8"NSError"16ls48l8s32l8s40l8
- ___block_descriptor_72_e8_32s40s48s56bs_e44_v24?0"RMModelDeclarationBase"8"NSError"16ls56l8s32l8s40l8s48l8
CStrings:
+ "Activation does not reference configuration %s: %s"
+ "Missing app configuration"
+ "Missing extensible SSO configuration or legacy profile"
- "Activation does not reference configuration: %s"
- "Missing configuration"
- "No app configuration found"
```
