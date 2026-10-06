## ActivityProgressUI

> `/Applications/ActivityProgressUI.app/ActivityProgressUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44e7c` | `0x4680c` | **`+0x1990`** |
| `__TEXT.__const` | `0x3fe4` | `0x40c4` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x2250` | `0x22f0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x14ec` | `0x158c` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xcf8` | `0xd88` | **`+0x90`** |
| `__DATA.__data` | `0x2698` | `0x2718` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x81c` | `0x89c` | **`+0x80`** |
| `__TEXT.__cstring` | `0x887` | `0x8e7` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xd32` | `0xd82` | **`+0x50`** |
| `__DATA.__objc_const` | `0x4a00` | `0x4a48` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x1834` | `0x1874` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x39a5` | `0x39e5` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x15c0` | `0x1600` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1b90` | `0x1bc0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x10a4` | `0x10d4` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xfb0` | `0xfe0` | **`+0x30`** |
| `__DATA.__bss` | `0x2bf0` | `0x2c10` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x20` | `0x40` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xb30` | `0xb48` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xdd0` | `0xde8` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xbfc` | `0xc14` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x24d2` | `0x24e8` | **`+0x16`** |
| `__DATA.__objc_data` | `0xf18` | `0xf28` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xa40` | `0xa50` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x5c` | `0x60` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x44` | `0x48` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-390.0.0.0.0
+391.0.0.0.0

-  Functions: 1605
-  Symbols:   906
-  CStrings:  812
+  Functions: 1632
+  Symbols:   909
+  CStrings:  821
Symbols:
+ _$ss11_SetStorageC4copy8originalAByxGs05__RawaB0C_tFZ
+ _$ss11_SetStorageC6resize8original8capacity4moveAByxGs05__RawaB0C_SiSbtFZ
+ _$ss50ELEMENT_TYPE_OF_SET_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
CStrings:
+ "BackgroundActivitySessionsController: No session found when unfailing activity for task ID %s"
+ "Marking task identifier %s as unfailed by client"
+ "PreserveSubtitleOnFailure"
+ "_preserveSubtitleOnFailure"
+ "com.apple.private.activityprogress.ui.preserve-failure-subtitle"
+ "connectionsAllowedToPreserveFailureSubtitle"
+ "initWithBool:"
+ "setUserInfoObject:forKey:"
+ "unfailActivityForIdentifier:"
```
