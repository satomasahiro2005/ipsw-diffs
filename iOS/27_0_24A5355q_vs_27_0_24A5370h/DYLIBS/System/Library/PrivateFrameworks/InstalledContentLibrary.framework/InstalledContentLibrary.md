## InstalledContentLibrary

> `/System/Library/PrivateFrameworks/InstalledContentLibrary.framework/InstalledContentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcdc40` | `0xcee4c` | **`+0x120c`** |
| `__AUTH_CONST.__objc_const` | `0xa1e8` | `0xa480` | **`+0x298`** |
| `__TEXT.__cstring` | `0x183ce` | `0x185ce` | **`+0x200`** |
| `__TEXT.__objc_methlist` | `0x5a24` | `0x5b94` | **`+0x170`** |
| `__AUTH_CONST.__cfstring` | `0xd500` | `0xd640` | **`+0x140`** |
| `__AUTH.__objc_data` | `0xe60` | `0xf00` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0xd98` | `0xde0` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x3050` | `0x3088` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1998` | `0x19c8` | **`+0x30`** |
| `__DATA.__data` | `0xe58` | `0xe68` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5b4` | `0x5c4` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x4f0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x220` | `0x230` | **`+0x10`** |

### Other Changes

```diff

-1655.0.0.0.0
+1660.0.0.0.0

-  Functions: 2379
-  Symbols:   3770
-  CStrings:  2262
+  Functions: 2407
+  Symbols:   3825
+  CStrings:  2273
Symbols:
+ +[MIStoreMetadataContentDescriptor supportsSecureCoding]
+ +[MIStoreMetadataContentLevel supportsSecureCoding]
+ -[MIStoreMetadata contentLevels]
+ -[MIStoreMetadata setContentLevels:]
+ -[MIStoreMetadataContentDescriptor .cxx_destruct]
+ -[MIStoreMetadataContentDescriptor copyWithZone:]
+ -[MIStoreMetadataContentDescriptor dictionaryRepresentation]
+ -[MIStoreMetadataContentDescriptor encodeWithCoder:]
+ -[MIStoreMetadataContentDescriptor hash]
+ -[MIStoreMetadataContentDescriptor initWithCoder:]
+ -[MIStoreMetadataContentDescriptor initWithKindDescriptor:]
+ -[MIStoreMetadataContentDescriptor isEqual:]
+ -[MIStoreMetadataContentDescriptor kind]
+ -[MIStoreMetadataContentDescriptor setKind:]
+ -[MIStoreMetadataContentLevel .cxx_destruct]
+ -[MIStoreMetadataContentLevel contentDescriptors]
+ -[MIStoreMetadataContentLevel copyWithZone:]
+ -[MIStoreMetadataContentLevel dictionaryRepresentation]
+ -[MIStoreMetadataContentLevel encodeWithCoder:]
+ -[MIStoreMetadataContentLevel hash]
+ -[MIStoreMetadataContentLevel initWithCoder:]
+ -[MIStoreMetadataContentLevel initWithKindDescriptor:contentDescriptors:]
+ -[MIStoreMetadataContentLevel isEqual:]
+ -[MIStoreMetadataContentLevel kind]
+ -[MIStoreMetadataContentLevel setContentDescriptors:]
+ -[MIStoreMetadataContentLevel setKind:]
+ GCC_except_table15
+ GCC_except_table30
+ GCC_except_table78
+ _OBJC_CLASS_$_MIStoreMetadataContentDescriptor
+ _OBJC_CLASS_$_MIStoreMetadataContentLevel
+ _OBJC_IVAR_$_MIStoreMetadata._contentLevels
+ _OBJC_IVAR_$_MIStoreMetadataContentDescriptor._kind
+ _OBJC_IVAR_$_MIStoreMetadataContentLevel._contentDescriptors
+ _OBJC_IVAR_$_MIStoreMetadataContentLevel._kind
+ _OBJC_METACLASS_$_MIStoreMetadataContentDescriptor
+ _OBJC_METACLASS_$_MIStoreMetadataContentLevel
+ __OBJC_$_CLASS_METHODS_MIStoreMetadataContentDescriptor
+ __OBJC_$_CLASS_METHODS_MIStoreMetadataContentLevel
+ __OBJC_$_CLASS_PROP_LIST_MIStoreMetadataContentDescriptor
+ __OBJC_$_CLASS_PROP_LIST_MIStoreMetadataContentLevel
+ __OBJC_$_INSTANCE_METHODS_MIStoreMetadataContentDescriptor
+ __OBJC_$_INSTANCE_METHODS_MIStoreMetadataContentLevel
+ __OBJC_$_INSTANCE_VARIABLES_MIStoreMetadataContentDescriptor
+ __OBJC_$_INSTANCE_VARIABLES_MIStoreMetadataContentLevel
+ __OBJC_$_PROP_LIST_MIStoreMetadataContentDescriptor
+ __OBJC_$_PROP_LIST_MIStoreMetadataContentLevel
+ __OBJC_CLASS_PROTOCOLS_$_MIStoreMetadataContentDescriptor
+ __OBJC_CLASS_PROTOCOLS_$_MIStoreMetadataContentLevel
+ __OBJC_CLASS_RO_$_MIStoreMetadataContentDescriptor
+ __OBJC_CLASS_RO_$_MIStoreMetadataContentLevel
+ __OBJC_METACLASS_RO_$_MIStoreMetadataContentDescriptor
+ __OBJC_METACLASS_RO_$_MIStoreMetadataContentLevel
+ ___61-[ICLWorkspace enumerateBuiltInSystemContentWithBlock:error:]_block_invoke_2
+ ___61-[ICLWorkspace enumerateBuiltInSystemContentWithBlock:error:]_block_invoke_3
+ _contentDescriptors
+ _contentLevels
- GCC_except_table28
- GCC_except_table54
CStrings:
+ "-[ICLWorkspace enumerateBuiltInSystemContentWithBlock:error:]_block_invoke_3"
+ "Expected '%@' array element to be a dictionary."
+ "Expected '%@' element to have a string value for '%@'."
+ "Expected contentLevels element to be a dictionary."
+ "Expected contentLevels element to have a string value for '%@'."
+ "Expected contentLevels element to have array value for '%@'."
+ "Invalid type for metadata property '%@'."
+ "Unexpectedly received a nil rawContainer (MIMCMContainer)"
+ "_ParseContentLevels"
+ "contentDescriptors"
+ "contentLevels"
+ "contentLevels element has no valid contentDescriptors; dropping."
- "-[ICLWorkspace enumerateBuiltInSystemContentWithBlock:error:]_block_invoke"
```
