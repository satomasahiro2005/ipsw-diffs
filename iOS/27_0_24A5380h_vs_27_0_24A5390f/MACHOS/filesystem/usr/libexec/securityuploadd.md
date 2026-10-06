## securityuploadd

> `/usr/libexec/securityuploadd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12df8` | `0x12cf4` | **`-0x104`** |
| `__TEXT.__objc_stubs` | `0x1f00` | `0x1f80` | **`+0x80`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x60` | **`+0x60`** |
| `__DATA_CONST.__objc_intobj` | `0x30` | `0x90` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xe41` | `0xdf5` | **`-0x4c`** |
| `__TEXT.__objc_methname` | `0x234d` | `0x2391` | **`+0x44`** |
| `__DATA_CONST.__cfstring` | `0x14c0` | `0x1500` | **`+0x40`** |
| `__TEXT.__cstring` | `0xf9d` | `0xfd8` | **`+0x3b`** |
| `__DATA_CONST.__got` | `0x318` | `0x340` | **`+0x28`** |
| `__DATA_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0xa20` | `0xa40` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x294` | `0x27c` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0xf60` | `0xf50` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x8f8` | `0x8e8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x418` | `0x408` | **`-0x10`** |
| `__DATA.__objc_const` | `0xe40` | `0xe38` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x7c0` | `0x7b8` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-62460.0.38.0.1
+62460.0.55.0.1

-  Functions: 331
-  Symbols:   395
-  CStrings:  762
+  Functions: 328
+  Symbols:   400
+  CStrings:  768
Symbols:
+ _NSCocoaErrorDomain
+ _NSFileGroupOwnerAccountID
+ _NSFileOwnerAccountID
+ _NSFilePosixPermissions
+ _NSMultipleUnderlyingErrorsKey
+ _OBJC_CLASS_$_NSConstantDictionary
- _objc_retain_x10
CStrings:
+ "62460.0.55.0.1"
+ "ValidCacheFiles"
+ "domain"
+ "failed to fix trustd file permissions"
+ "failed to set attributes on %s: %s"
+ "firstObject"
+ "fixTrustdPermissions:"
+ "numberWithUnsignedShort:"
+ "protected trustd directory unavailable"
+ "setAttributes:ofItemAtPath:error:"
+ "unsignedShortValue"
+ "valid.sqlite3-journal"
+ "valid.sqlite3-shm"
+ "valid.sqlite3-wal"
- ".valid_replace"
- "62460.0.38.0.1"
- "Client (pid: %d) properly entitled for trustd file helper interface, let's go"
- "changeOwnerOfValidFile:error:"
- "com.apple.private.trustd.FileHelp"
- "failed to change owner of %s: %s"
- "fixValidPermissions:"
- "trustd/%@"
```
