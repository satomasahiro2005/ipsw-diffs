## ANELargeModelCompilerService

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANELargeModelCompilerService.xpc/ANELargeModelCompilerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18b64` | `0x19a28` | **`+0xec4`** |
| `__TEXT.__oslogstring` | `0x224c` | `0x2571` | **`+0x325`** |
| `__TEXT.__objc_methname` | `0x24e1` | `0x25f1` | **`+0x110`** |
| `__TEXT.__objc_stubs` | `0x21c0` | `0x2280` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x7f0` | `0x890` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1277` | `0x12e6` | **`+0x6f`** |
| `__TEXT.__objc_methtype` | `0x615` | `0x67b` | **`+0x66`** |
| `__DATA_CONST.__cfstring` | `0x18c0` | `0x1920` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x410` | `0x460` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x96c` | `0x9ac` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xa58` | `0xa90` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x1248` | `0x1274` | **`+0x2c`** |
| `__DATA.__objc_const` | `0xd20` | `0xd48` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x320` | `0x348` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x430` | `0x440` | **`+0x10`** |
| `__DATA.__data` | `0x3f8` | `0x400` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__const` | `0x118` | `0x120` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-382.12.0.0.0
+382.15.1.0.0

-  Functions: 295
-  Symbols:   940
-  CStrings:  853
+  Functions: 311
+  Symbols:   965
+  CStrings:  879
Symbols:
+ +[_ANECompiler applyBondedFlavor:toCompilerOptions:]
+ +[_ANEStorageHelper relevantContainerForPath:]
+ +[_ANEStorageHelper sourcePathForModelInStoreAt:]
+ -[_ANECompilerService moveCachedModelFromSource:toDestination:withReply:]
+ -[_ANECompilerService updateSourcePathAt:to:withContainerAt:withContainer:withReply:]
+ -[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:appGroups:expunge:]
+ -[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:appGroups:expunge:allowProcessModelShare:]
+ GCC_except_table15
+ GCC_except_table4
+ GCC_except_table7
+ ___103-[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:appGroups:expunge:allowProcessModelShare:]_block_invoke
+ ___73-[_ANECompilerService moveCachedModelFromSource:toDestination:withReply:]_block_invoke
+ ___85-[_ANECompilerService updateSourcePathAt:to:withContainerAt:withContainer:withReply:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s64l8s48l8s56l8
+ ___kCFBooleanTrue
+ _container_copy_from_path
+ _container_error_copy_unlocalized_description
+ _container_free_object
+ _container_get_path
+ _container_query_create_from_container
+ _container_query_free
+ _container_query_get_last_error
+ _container_query_get_single_result
+ _container_query_operation_set_flags
+ _container_serialize_copy_deserialized_reference
+ _container_serialize_copy_serialized_reference
+ _kANEFDisableBondedNetworksKey
+ _objc_msgSend$applyBondedFlavor:toCompilerOptions:
+ _objc_msgSend$description
+ _objc_msgSend$modelSourceContainerName
+ _objc_msgSend$moveItemAtURL:toURL:error:
+ _objc_msgSend$scanAllPartitionsForModel:csIdentity:appGroups:expunge:allowProcessModelShare:
+ _objc_msgSend$sourcePathForModelInStoreAt:
+ _objc_msgSend$writeToFile:options:error:
- -[_ANECompilerService updateSourcePathAt:to:withReply:]
- -[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:expunge:]
- -[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:expunge:allowProcessModelShare:]
- GCC_except_table13
- GCC_except_table5
- ___55-[_ANECompilerService updateSourcePathAt:to:withReply:]_block_invoke
- ___93-[_ANEModelCacheManager scanAllPartitionsForModel:csIdentity:expunge:allowProcessModelShare:]_block_invoke
- ___block_descriptor_64_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- _objc_msgSend$scanAllPartitionsForModel:csIdentity:expunge:allowProcessModelShare:
- _objc_retain_x5
CStrings:
+ "%@/%@"
+ "%@: Error deserializing container: %s"
+ "%@: Error executing query: %llu"
+ "%@: Error querying current version of deserialized container: %s"
+ "%@: FAILED storing containerInfo=%@ to %@ : err=%@"
+ "%@: Full path: %{public}@ is member of container at path: %s. Relative component is: %s (error:%llu)"
+ "%@: Nil sourcePathname!"
+ "%@: Returning full path as: %@"
+ "%@: Returning path consisting of container path: %@ and relative path: %@. Resulting full path vended is: %@"
+ "%@: nil patchedURL for modelURL=%@ — cannot patch"
+ "%@: nil patchedURL for modelURL=%@ — skipping purge"
+ "%@: stringByDeletingPathExtension returned nil for filename=%{public}@ (length=%lu)"
+ "%@: substringToIndex:%lu returned nil for filename=%{public}@"
+ "%s: DisableBondedNetworks set from ANEF flag (bonded flavor will be disabled if supported on this HW)"
+ "+[_ANECompiler applyBondedFlavor:toCompilerOptions:]"
+ "B44@0:8@16@24@32B40"
+ "B48@0:8@16@24@32B40B44"
+ "DisableBondedNetworks"
+ "applyBondedFlavor:toCompilerOptions:"
+ "kANEFDisableBondedNetworksKey"
+ "modelSourceContainerName"
+ "moveCachedModelFromSource:toDestination:withReply:"
+ "moveItemAtURL:toURL:error:"
+ "relevantContainerForPath:"
+ "scanAllPartitionsForModel:csIdentity:appGroups:expunge:"
+ "scanAllPartitionsForModel:csIdentity:appGroups:expunge:allowProcessModelShare:"
+ "sourcePathForModelInStoreAt:"
+ "updateSourcePathAt:to:withContainerAt:withContainer:withReply:"
+ "v40@0:8@\"NSURL\"16@\"NSURL\"24@?<v@?B@\"NSError\">32"
+ "v56@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSData\"40@?<v@?B@\"NSError\">48"
+ "v56@0:8@16@24@32@40@?48"
+ "writeToFile:options:error:"
- "B36@0:8@16@24B32"
- "B40@0:8@16@24B32B36"
- "scanAllPartitionsForModel:csIdentity:expunge:"
- "scanAllPartitionsForModel:csIdentity:expunge:allowProcessModelShare:"
- "updateSourcePathAt:to:withReply:"
- "v40@0:8@\"NSString\"16@\"NSString\"24@?<v@?B@\"NSError\">32"
```
