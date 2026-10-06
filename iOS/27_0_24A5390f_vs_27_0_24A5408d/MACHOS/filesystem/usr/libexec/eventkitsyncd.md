## eventkitsyncd

> `/usr/libexec/eventkitsyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75ec0` | `0x761dc` | **`+0x31c`** |
| `__TEXT.__objc_stubs` | `0xcbc0` | `0xcc20` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xbc30` | `0xbc8e` | **`+0x5e`** |
| `__TEXT.__objc_methname` | `0xfc6c` | `0xfcc5` | **`+0x59`** |
| `__DATA_CONST.__cfstring` | `0x5080` | `0x50c0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x3f60` | `0x3f78` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x4d8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5b50` | `0x5b5a` | **`+0xa`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-430.0.0.0.0
+431.0.0.0.0

-  Symbols:   369
-  CStrings:  4634
+  Symbols:   371
+  CStrings:  4641
Symbols:
+ _NSFileProtectionCompleteUntilFirstUserAuthentication
+ _NSFileProtectionKey
Functions:
~ sub_100007ad8 : 176 -> 972
CStrings:
+ "-shm"
+ "-wal"
+ "== Started EventKitSync-431"
+ "Failed to set protection level of file %@ with error: %@"
+ "Updating protection level of file %@"
+ "attributesOfItemAtPath:error:"
+ "setAttributes:ofItemAtPath:error:"
+ "stringByAppendingString:"
- "== Started EventKitSync-430"
```
