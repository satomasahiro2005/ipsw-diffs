## ASDAccountNotificationPlugin

> `/System/Library/Accounts/Notification/ASDAccountNotificationPlugin.bundle/ASDAccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11f4` | `0x1d8c` | **`+0xb98`** |
| `__TEXT.__auth_stubs` | `0x210` | `0x360` | **`+0x150`** |
| `__DATA_CONST.__auth_got` | `0x108` | `0x1b8` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x128` | `0x1a0` | **`+0x78`** |
| `__TEXT.__objc_stubs` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xc8` | `0x108` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2f` | `0x6e` | **`+0x3f`** |
| `__TEXT.__swift5_fieldmd` | `0x2c` | `0x60` | **`+0x34`** |
| `__DATA_CONST.__const` | `0xf8` | `0x120` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x80` | `0xa4` | **`+0x24`** |
| `__TEXT.__const` | `0x172` | `0x18e` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x26c` | `0x283` | **`+0x17`** |
| `__TEXT.__swift5_reflstr` | `0x12` | `0x28` | **`+0x16`** |
| `__TEXT.__swift5_typeref` | `0x43` | `0x57` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0xf0` | `0x100` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x48` | `0x58` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x4b` | `0x5b` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x28` | `0x2c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x10` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-27.0.52.0.0
+27.0.60.0.0

-  Functions: 24
-  Symbols:   45
-  CStrings:  64
+  Functions: 36
+  Symbols:   63
+  CStrings:  68
Symbols:
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_msgSend
+ _objc_release_x23
+ _objc_release_x24
+ _objc_release_x25
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x19
+ _objc_retain_x20
+ _objc_retain_x22
+ _objc_retain_x23
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_release_x19
- _swift_release_x20
CStrings:
+ "account update triggered with type: %u for account type: %s"
+ "accountType"
+ "com.apple.account.AppleAccount"
+ "com.apple.account.iTunesStore"
+ "identifier"
- "account update triggered with type: %u"
```
