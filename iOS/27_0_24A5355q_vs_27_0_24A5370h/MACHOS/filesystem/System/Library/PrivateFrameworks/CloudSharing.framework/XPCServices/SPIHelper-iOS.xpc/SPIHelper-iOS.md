## SPIHelper-iOS

> `/System/Library/PrivateFrameworks/CloudSharing.framework/XPCServices/SPIHelper-iOS.xpc/SPIHelper-iOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3b5c` | `0xb5570` | **`+0x1a14`** |
| `__TEXT.__oslogstring` | `0x3cbb` | `0x3e3b` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x7aa0` | `0x7b48` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x26b6` | `0x2736` | **`+0x80`** |
| `__DATA.__data` | `0x1fb8` | `0x1ff8` | **`+0x40`** |
| `__DATA.__objc_const` | `0x1670` | `0x16b0` | **`+0x40`** |
| `__TEXT.__const` | `0x5058` | `0x5098` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x285d` | `0x289d` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x151c` | `0x155c` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x116c` | `0x1184` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x135c` | `0x136c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2748` | `0x2758` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x710` | `0x718` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x894` | `0x89c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x260` | `0x264` | **`+0x4`** |

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
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-232.0.0.0.0
+234.0.0.0.0

-  Functions: 2449
+  Functions: 2455

-  CStrings:  993
+  CStrings:  999
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
