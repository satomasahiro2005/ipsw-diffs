## SiriDataclassOwner

> `/System/Library/Accounts/DataclassOwners/SiriDataclassOwner.bundle/SiriDataclassOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7aa8` | `0x7c9c` | **`+0x1f4`** |
| `__TEXT.__oslogstring` | `0x39e` | `0x40f` | **`+0x71`** |
| `__TEXT.__cstring` | `0x223` | `0x1f3` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0x860` | `0x880` | **`+0x20`** |
| `__TEXT.__const` | `0x394` | `0x3b4` | **`+0x20`** |
| `__DATA.__data` | `0x1a0` | `0x1b0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x438` | `0x448` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x270` | `0x280` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x172` | `0x17e` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

-  Functions: 136
+  Functions: 140
Symbols:
+ _objc_retain_x28
- _objc_retain_x27
CStrings:
+ "Completed DataClass action %@"
+ "Ignoring unsupported action %@"
+ "Received unknown action: %@"
+ "SKIPPED - Siri needs voice profile locally for HS/JS to continue to function"
+ "User enabled iCloud syncing. Returning recommended action."
+ "User has no cloud eligible data. Returning recommended action."
+ "actionsForEnabling(_:on:isSignIn:)"
- "Could not create cancel action."
- "Could not create delete action."
- "Could not create keep action."
- "SKIPPED - Siri deletion task"
- "User enabled iCloud syncing. Returning only keep action."
- "actions(forAdding:forDataclass:)"
- "actionsForEnablingDataclass(on:forDataclass:)"
```
