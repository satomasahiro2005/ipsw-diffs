## FaceTime

> `/private/var/staged_system_apps/FaceTime.app/FaceTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc5da4` | `0xc625c` | **`+0x4b8`** |
| `__TEXT.__oslogstring` | `0x5316` | `0x5386` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x4138` | `0x4178` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x10d3d` | `0x10d7d` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x4a40` | `0x4a68` | **`+0x28`** |
| `__DATA.__objc_const` | `0x94b0` | `0x94d0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xad40` | `0xad60` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xfa2` | `0xfc2` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2e68` | `0x2e80` | **`+0x18`** |
| `__DATA.__data` | `0x3380` | `0x3370` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xf60` | `0xf6c` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x1bc8` | `0x1bd4` | **`+0xc`** |
| `__DATA.__objc_data` | `0x2870` | `0x2878` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x3da8` | `0x3db0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x8a8` | `0x8b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xf10` | `0xf18` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3077.200.64.2.3
+3077.200.88.0.0

+  - /System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation

-  Functions: 3692
-  Symbols:   1500
-  CStrings:  3777
+  Functions: 3698
+  Symbols:   1502
+  CStrings:  3781
Symbols:
+ _$s15ConversationKit26ButtonsStackViewControllerCMn
+ _OBJC_CLASS_$_IDSServerBag
CStrings:
+ "PhoneSceneDelegate: Initialized FaceTime IDSServerBag: %@"
+ "PhoneSceneDelegate: Initialized Messages IDSServerBag: %@"
+ "makeButtonViewController"
+ "sharedInstanceForBagType:"
```
