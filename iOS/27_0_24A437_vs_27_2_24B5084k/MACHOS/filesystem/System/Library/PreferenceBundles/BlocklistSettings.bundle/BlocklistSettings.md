## BlocklistSettings

> `/System/Library/PreferenceBundles/BlocklistSettings.bundle/BlocklistSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc3cc` | `0xca98` | **`+0x6cc`** |
| `__DATA_CONST.__got` | `0x228` | `0x250` | **`+0x28`** |
| `__DATA.__data` | `0x2a8` | `0x2c8` | **`+0x20`** |
| `__TEXT.__const` | `0x1e8` | `0x208` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xc30` | `0xc40` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x187` | `0x195` | **`+0xe`** |
| `__DATA_CONST.__auth_got` | `0x628` | `0x630` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xb8` | `0xc0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x488` | `0x490` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3072.100.1.2.5
+3077.200.51.2.1

+  - /System/Library/PrivateFrameworks/CommunicationsFilter.framework/CommunicationsFilter

+  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Functions: 191
-  Symbols:   221
+  Functions: 193
+  Symbols:   224
Symbols:
+ _CMFSyncAgentBlockListUpdated
+ _OBJC_CLASS_$_NSDistributedNotificationCenter
+ __swiftEmptySetSingleton
+ __swift_FORCE_LOAD_$_swiftAppleArchive
+ _swift_setDeallocating
- _swift_release_x22
- _swift_retain_x22
```
