## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcef94` | `0xce76c` | **`-0x828`** |
| `__AUTH_CONST.__objc_const` | `0xa480` | `0xa740` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x1855e` | `0x183ee` | **`-0x170`** |
| `__DATA.__data` | `0xe68` | `0xf38` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0xd4e0` | `0xd460` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x91f` | `0x8c1` | **`-0x5e`** |
| `__DATA_DIRTY.__objc_data` | `0x500` | `0x4b0` | **`-0x50`** |
| `__DATA_CONST.__const` | `0xfd8` | `0x1000` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x3090` | `0x30a8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x500` | `0x4f0` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x90` | `0xa0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x5ba4` | `0x5b94` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x230` | `0x228` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x19d0` | `0x19c8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x5c4` | `0x5c0` | **`-0x4`** |

### Other Changes

```diff

-1663.0.0.0.1
+1673.0.0.0.0

-  Functions: 2409
-  Symbols:   3830
-  CStrings:  2263
+  Functions: 2402
+  Symbols:   3825
+  CStrings:  2260
Symbols:
+ +[MIBundleContainer enumerateAppBundleContainersInDomain:forPersona:isTransient:usingBundleMetadataProviderBlock:]
+ -[MIGlobalConfiguration internalLibraryDirectory]
+ -[MIGlobalConfiguration internalMobileInstallationContentDirectory]
+ -[MIGlobalConfiguration internalSupersededAppAdditionsPlistURL]
+ -[MIStoreMetadata contentDescriptors]
+ -[MIStoreMetadata secondaryGenreID]
+ -[MIStoreMetadata setContentDescriptors:]
+ -[MIStoreMetadata setSecondaryGenreID:]
+ -[MIStoreMetadataContentDescriptor identifier]
+ -[MIStoreMetadataContentDescriptor initWithIdentifier:]
+ -[MIStoreMetadataContentDescriptor setIdentifier:]
+ GCC_except_table48
+ GCC_except_table54
+ GCC_except_table60
+ GCC_except_table66
+ _OBJC_IVAR_$_MIStoreMetadata._contentDescriptors
+ _OBJC_IVAR_$_MIStoreMetadata._secondaryGenreID
+ _OBJC_IVAR_$_MIStoreMetadataContentDescriptor._identifier
+ __OBJC_$_PROP_LIST_MIBundleMetadataProvider
+ __OBJC_$_PROTOCOL_CLASS_METHODS_MIBundleMetadataProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MIBundleMetadataProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_MIUserManagementDaemonContainerResolver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MIBundleMetadataProvider
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MIUserManagementDaemonContainerResolver
+ __OBJC_$_PROTOCOL_REFS_MIBundleMetadataProvider
+ __OBJC_CLASS_PROTOCOLS_$_MIBundleContainer
+ __OBJC_CLASS_PROTOCOLS_$_MIUserManagement
+ __OBJC_LABEL_PROTOCOL_$_MIBundleMetadataProvider
+ __OBJC_LABEL_PROTOCOL_$_MIUserManagementDaemonContainerResolver
+ __OBJC_PROTOCOL_$_MIBundleMetadataProvider
+ __OBJC_PROTOCOL_$_MIUserManagementDaemonContainerResolver
+ ___114+[MIBundleContainer enumerateAppBundleContainersInDomain:forPersona:isTransient:usingBundleMetadataProviderBlock:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e27_B16?0"MIBundleContainer"8ls32l8
+ _contentDescriptorID
+ _secondaryGenreID
- +[MIStoreMetadataContentLevel supportsSecureCoding]
- -[MIGlobalConfiguration internalFrameworksRootDirectory]
- -[MIStoreMetadata contentLevels]
- -[MIStoreMetadata setContentLevels:]
- -[MIStoreMetadataContentDescriptor initWithKindDescriptor:]
- -[MIStoreMetadataContentDescriptor kind]
- -[MIStoreMetadataContentDescriptor setKind:]
- -[MIStoreMetadataContentLevel .cxx_destruct]
- -[MIStoreMetadataContentLevel contentDescriptors]
- -[MIStoreMetadataContentLevel copyWithZone:]
- -[MIStoreMetadataContentLevel dictionaryRepresentation]
- -[MIStoreMetadataContentLevel encodeWithCoder:]
- -[MIStoreMetadataContentLevel hash]
- -[MIStoreMetadataContentLevel initWithCoder:]
- -[MIStoreMetadataContentLevel initWithKindDescriptor:contentDescriptors:]
- -[MIStoreMetadataContentLevel isEqual:]
- -[MIStoreMetadataContentLevel kind]
- -[MIStoreMetadataContentLevel setContentDescriptors:]
- -[MIStoreMetadataContentLevel setKind:]
- GCC_except_table46
- GCC_except_table52
- GCC_except_table56
- GCC_except_table61
- GCC_except_table78
- _OBJC_CLASS_$_MIStoreMetadataContentLevel
- _OBJC_IVAR_$_MIStoreMetadata._contentLevels
- _OBJC_IVAR_$_MIStoreMetadataContentDescriptor._kind
- _OBJC_IVAR_$_MIStoreMetadataContentLevel._contentDescriptors
- _OBJC_IVAR_$_MIStoreMetadataContentLevel._kind
- _OBJC_METACLASS_$_MIStoreMetadataContentLevel
- __OBJC_$_CLASS_METHODS_MIStoreMetadataContentLevel
- __OBJC_$_CLASS_PROP_LIST_MIStoreMetadataContentLevel
- __OBJC_$_INSTANCE_METHODS_MIStoreMetadataContentLevel
- __OBJC_$_INSTANCE_VARIABLES_MIStoreMetadataContentLevel
- __OBJC_$_PROP_LIST_MIStoreMetadataContentLevel
- __OBJC_CLASS_PROTOCOLS_$_MIStoreMetadataContentLevel
- __OBJC_CLASS_RO_$_MIStoreMetadataContentLevel
- __OBJC_METACLASS_RO_$_MIStoreMetadataContentLevel
- _contentLevels
- _kMISValidationOptionAllowLaunchWarning
CStrings:
+ "-[MIGlobalConfiguration internalSupersededAppAdditionsPlistURL]"
+ "B16@?0@\"MIBundleContainer\"8"
+ "CoreOS"
+ "Failed to create URL for internal superseded app additions plist."
+ "Failed to set up daemon container for persona %@: %@"
+ "InternalSupersededAppAdditions.plist"
+ "_ParseContentDescriptors"
+ "id"
+ "secondaryGenreID"
+ "secondaryGenreId"
- "%s: Got daemon container at %@ for data separated persona %@ that was not on persona mount %@"
- "Expected contentLevels element to be a dictionary."
- "Expected contentLevels element to have a string value for '%@'."
- "Expected contentLevels element to have array value for '%@'."
- "Failed to determine volume UUID for daemon container for persona %@ at %@ : %@"
- "Failed to determine volume UUID for persona volume mount %@ : %@"
- "Failed to get daemon container URL from %@"
- "Failed to get daemon container for persona %@: %@"
- "Failed to get sandbox extension for daemon container for persona %@ at %@"
- "Got daemon container at %@ for data separated persona %@ that was not on persona mount %@"
- "_ParseContentLevels"
- "contentLevels"
- "contentLevels element has no valid contentDescriptors; dropping."
```
