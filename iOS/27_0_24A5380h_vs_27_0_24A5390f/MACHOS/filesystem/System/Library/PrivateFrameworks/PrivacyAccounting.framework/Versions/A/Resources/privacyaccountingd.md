## privacyaccountingd

> `/System/Library/PrivateFrameworks/PrivacyAccounting.framework/Versions/A/Resources/privacyaccountingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc2b0` | `0xc59c` | **`+0x2ec`** |
| `__TEXT.__oslogstring` | `0x1106` | `0x1176` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x7f0` | `0x840` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x2c23` | `0x2c64` | **`+0x41`** |
| `__TEXT.__objc_stubs` | `0x2280` | `0x22c0` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x408` | `0x430` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x670` | `0x698` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x240` | `0x260` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xb30` | `0xb40` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x468` | `0x478` | **`+0x10`** |
| `__TEXT.__const` | `0xe0` | `0xe8` | **`+0x8`** |
| `__TEXT.__cstring` | `0xfc7` | `0xfcf` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-148.0.0.0.0
+149.0.0.0.0

-  Functions: 318
-  Symbols:   210
-  CStrings:  803
+  Functions: 322
+  Symbols:   217
+  CStrings:  807
Symbols:
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ __CFXPCCreateXPCObjectFromCFObject
+ __xpc_type_data
+ _xpc_copy
+ _xpc_data_get_bytes_ptr
+ _xpc_data_get_length
+ _xpc_dictionary_set_value
CStrings:
+ "Could not deserialize user info for XPC event: %{public}s error: %{public}@"
+ "No UserInfo data found in XPC event"
+ "com.apple.distnoted.matching.trusted"
+ "dataWithBytes:length:"
+ "propertyListWithData:options:format:error:"
- "com.apple.distnoted.matching"
```
