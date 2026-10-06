## AirDrop

> `/System/Library/PrivateFrameworks/Sharing.framework/PlugIns/AirDrop.appex/AirDrop`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f86c` | `0x1fe9c` | **`+0x630`** |
| `__DATA.__bss` | `0x90` | `0x210` | **`+0x180`** |
| `__TEXT.__cstring` | `0xa7a` | `0xbba` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0x19f` | `0x2a9` | **`+0x10a`** |
| `__TEXT.__const` | `0x534` | `0x5f4` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x988` | `0xa20` | **`+0x98`** |
| `__TEXT.__swift5_fieldmd` | `0x18c` | `0x220` | **`+0x94`** |
| `__DATA_CONST.__auth_ptr` | `0x120` | `0x170` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x1700` | `0x1740` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x718` | `0x740` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0xb90` | `0xbb0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x421c` | `0x423c` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x32e0` | `0x3300` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x284` | `0x2a0` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x458` | `0x468` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x108` | `0x118` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x42e` | `0x43c` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0x4` | `0x10` | **`+0xc`** |
| `__DATA.__data` | `0x9b8` | `0x9b0` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x1040` | `0x1048` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2131.10.1.2.11
+2131.20.65.2.1

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 463
-  Symbols:   370
-  CStrings:  913
+  Functions: 481
+  Symbols:   371
+  CStrings:  926
Symbols:
+ __swift_FORCE_LOAD_$_swiftIntents
+ _swift_release_x22
- _swift_release_x25
CStrings:
+ "AirDropTTR"
+ "DigitalEngraving"
+ "Headphone_PRX"
+ "HomePodUseAMS"
+ "HomePodUseAMSEarly"
+ "PINPairingDDUI"
+ "ShareSheetSnapshotCollection"
+ "ShareSheetTestability"
+ "Sharing"
+ "auto_unlock_ipad_as_realitydevice"
+ "headphones_prox_upsell_supported"
+ "marketing_upsell_use_sharing_config"
+ "setRightBarButtonItems:"
```
