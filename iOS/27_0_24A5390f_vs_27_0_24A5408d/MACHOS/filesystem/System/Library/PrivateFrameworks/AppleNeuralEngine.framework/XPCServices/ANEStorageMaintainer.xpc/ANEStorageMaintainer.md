## ANEStorageMaintainer

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANEStorageMaintainer.xpc/ANEStorageMaintainer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7990` | `0x8440` | **`+0xab0`** |
| `__TEXT.__oslogstring` | `0xd7d` | `0x1009` | **`+0x28c`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x580` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0xfe6` | `0x1075` | **`+0x8f`** |
| `__TEXT.__objc_stubs` | `0xf20` | `0xfa0` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x278` | `0x2d0` | **`+0x58`** |
| `__DATA.__objc_selrefs` | `0x4f8` | `0x520` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x300` | `0x320` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3c4` | `0x3dc` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1e8` | `0x1ee` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-382.12.0.0.0
+382.15.1.0.0

-  Functions: 97
-  Symbols:   384
-  CStrings:  324
+  Functions: 110
+  Symbols:   402
+  CStrings:  341
Symbols:
+ +[_ANEStorageHelper relevantContainerForPath:]
+ +[_ANEStorageHelper sourcePathForModelInStoreAt:]
+ _OUTLINED_FUNCTION_9
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
+ _free
+ _objc_msgSend$dataWithBytesNoCopy:length:freeWhenDone:
+ _objc_msgSend$modelSourceContainerName
+ _objc_msgSend$sourcePathForModelInStoreAt:
+ _objc_msgSend$stringWithUTF8String:
- _objc_retain_x5
CStrings:
+ "%@/%@"
+ "%@: Error deserializing container: %s"
+ "%@: Error executing query: %llu"
+ "%@: Error querying current version of deserialized container: %s"
+ "%@: Full path: %{public}@ is member of container at path: %s. Relative component is: %s (error:%llu)"
+ "%@: Nil sourcePathname!"
+ "%@: Returning full path as: %@"
+ "%@: Returning path consisting of container path: %@ and relative path: %@. Resulting full path vended is: %@"
+ "%@: nil patchedURL for modelURL=%@ — cannot patch"
+ "%@: nil patchedURL for modelURL=%@ — skipping purge"
+ "%@: stringByDeletingPathExtension returned nil for filename=%{public}@ (length=%lu)"
+ "%@: substringToIndex:%lu returned nil for filename=%{public}@"
+ "dataWithBytesNoCopy:length:freeWhenDone:"
+ "modelSourceContainerName"
+ "relevantContainerForPath:"
+ "sourcePathForModelInStoreAt:"
+ "stringWithUTF8String:"
```
