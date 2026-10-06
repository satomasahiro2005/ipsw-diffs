## attributionkitd

> `/System/Library/Frameworks/AdAttributionKit.framework/Support/attributionkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b3758` | `0x1b3ef4` | **`+0x79c`** |
| `__TEXT.__oslogstring` | `0x48a7` | `0x4997` | **`+0xf0`** |
| `__TEXT.__objc_methname` | `0x3005` | `0x3055` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x2ac0` | `0x2ae0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1570` | `0x1580` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3a82` | `0x3a92` | **`+0x10`** |
| `__DATA.__objc_const` | `0xa2e8` | `0xa2f0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xc40` | `0xc48` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1adc` | `0x1ae4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7788` | `0x7790` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4.0.7.0.0
+4.1.1.0.0

-  Functions: 8853
-  Symbols:   1081
-  CStrings:  1679
+  Functions: 8855
+  Symbols:   1083
+  CStrings:  1685
Symbols:
+ _$s3XPC0A10_TYPE_DATAs13OpaquePointerVvg
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
+ _xpc_dictionary_get_value
- _$syXlN
- __CFXPCCreateCFObjectFromXPCObject
- _xpc_dictionary_get_dictionary
CStrings:
+ "Expecting data type for xpc user info"
+ "Failed to cast deserialized user info to dictionary"
+ "Failed to deserialize user info: %@"
+ "Failed to get data bytes from xpc user info"
+ "Failed to get xpc user info"
+ "com.apple.distnoted.matching.trusted"
+ "profileConnectionDidReceiveAllowCloudSyncChangedNotification:userInfo:"
+ "propertyListWithData:options:format:error:"
- "com.apple.distnoted.matching"
- "postNotificationName:object:"
```
