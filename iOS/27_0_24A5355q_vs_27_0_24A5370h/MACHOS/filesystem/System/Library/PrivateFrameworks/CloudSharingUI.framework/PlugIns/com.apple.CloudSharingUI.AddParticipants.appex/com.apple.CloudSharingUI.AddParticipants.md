## com.apple.CloudSharingUI.AddParticipants

> `/System/Library/PrivateFrameworks/CloudSharingUI.framework/PlugIns/com.apple.CloudSharingUI.AddParticipants.appex/com.apple.CloudSharingUI.AddParticipants`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9ddec` | `0x9f858` | **`+0x1a6c`** |
| `__TEXT.__oslogstring` | `0x38f6` | `0x3a76` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x3f78` | `0x4030` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x25e0` | `0x2660` | **`+0x80`** |
| `__DATA.__data` | `0x1cd8` | `0x1d20` | **`+0x48`** |
| `__DATA.__objc_const` | `0x1400` | `0x1440` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x1195` | `0x11d5` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x2f3d` | `0x2f6d` | **`+0x30`** |
| `__TEXT.__const` | `0x4332` | `0x4352` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x18e0` | `0x1900` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xf3c` | `0xf54` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x1ce0` | `0x1cf0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x6a8` | `0x6b0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x470` | `0x478` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x160` | `0x164` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-232.0.0.0.0
+234.0.0.0.0

-  Functions: 2362
+  Functions: 2368

-  CStrings:  895
+  CStrings:  901
CStrings:
+ "_ckShareIsAvailable"
+ "changeReadWritePermission : Error adding migrated participant %@"
+ "changeReadWritePermission : Missing lookupInfo for migrated participant, they will not be readded"
+ "changeReadWritePermission : Missing lookupInfo for participant, default CK behavior will be applied"
+ "ckShare.allowsAnonymousPublicAccess[doc]: %{bool}d"
+ "ckShare.allowsAnonymousPublicAccess[photos]: %{bool}d"
+ "initialSharingType"
- "ckShare.allowsAnonymousPublicAccess: %{bool}d"
```
