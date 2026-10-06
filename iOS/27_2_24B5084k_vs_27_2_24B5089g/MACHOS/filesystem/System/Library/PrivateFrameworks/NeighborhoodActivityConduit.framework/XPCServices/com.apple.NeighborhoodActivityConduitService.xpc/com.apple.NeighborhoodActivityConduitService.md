## com.apple.NeighborhoodActivityConduitService

> `/System/Library/PrivateFrameworks/NeighborhoodActivityConduit.framework/XPCServices/com.apple.NeighborhoodActivityConduitService.xpc/com.apple.NeighborhoodActivityConduitService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x141c64` | `0x1423c0` | **`+0x75c`** |
| `__DATA_CONST.__const` | `0x6378` | `0x6410` | **`+0x98`** |
| `__TEXT.__objc_stubs` | `0x2e40` | `0x2ec0` | **`+0x80`** |
| `__TEXT.__const` | `0x46a8` | `0x4708` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x6b27` | `0x6b77` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x1c64` | `0x1cb4` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x1304` | `0x1350` | **`+0x4c`** |
| `__DATA.__objc_const` | `0x4150` | `0x4190` | **`+0x40`** |
| `__DATA.__data` | `0x3620` | `0x35f0` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x1b44` | `0x1b6c` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1698` | `0x16b8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1ed6` | `0x1ef6` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x140` | `0x154` | **`+0x14`** |
| `__DATA.__objc_data` | `0xfe8` | `0xff0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3fc8` | `0x3fd0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x32aa` | `0x32b0` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x114` | `0x118` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1626.200.53.0.0
+1626.200.65.0.0

-  Functions: 3840
+  Functions: 3851

-  CStrings:  1600
+  CStrings:  1606
Symbols:
+ _OBJC_CLASS_$_NSError
- _OBJC_CLASS_$_IMContactStore
CStrings:
+ "TUCompanionDeviceName"
+ "code"
+ "domain"
+ "identifierKey"
+ "initWithDomain:code:userInfo:"
+ "operatingSystemVersion"
+ "setIncludeSharedPhotoContacts:"
+ "userInfo"
- "contactForDestinationId:keysToFetch:"
- "keysForNicknameHandling"
```
