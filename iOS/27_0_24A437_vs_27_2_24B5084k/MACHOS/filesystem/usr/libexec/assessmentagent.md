## assessmentagent

> `/usr/libexec/assessmentagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x37e9` | `0x38c9` | **`+0xe0`** |
| `__TEXT.__text` | `0x9cd3c` | `0x9ce08` | **`+0xcc`** |
| `__TEXT.__objc_stubs` | `0x2540` | `0x2580` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x3a4d` | `0x3a7d` | **`+0x30`** |
| `__DATA.__objc_const` | `0x5710` | `0x5728` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xac8` | `0xad8` | **`+0x10`** |
| `__TEXT.__const` | `0x83c0` | `0x83d0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x34ac` | `0x34b8` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0x47a0` | `0x47a8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xc90` | `0xc98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-56.2.1.0.0
+56.40.4.0.0

-  CStrings:  1107
+  CStrings:  1111
CStrings:
+ "TB,R,N,GisAirPlayRestrictionsEnabled"
+ "airPlayRestrictionsEnabled"
+ "allowsForceQuitKeyboardShortcuts"
+ "allowsLockdownMode"
+ "allowsOnlyParticipantsToRun"
+ "allowsPrivateRelay"
+ "allowsVirtualMachine"
+ "isAirPlayRestrictionsEnabled"
+ "requiresReleaseOS"
- "allowLockdownMode"
- "allowOnlyParticipantsToRun"
- "allowPrivateRelay"
- "allowVirtualMachine"
- "allowsForceQuit"
```
