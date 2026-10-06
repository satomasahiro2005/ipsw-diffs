## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b034` | `0x2db04` | **`+0x2ad0`** |
| `__TEXT.__auth_stubs` | `0x1180` | `0x1230` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x4cf3` | `0x4d93` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x2df1` | `0x2e89` | **`+0x98`** |
| `__DATA_CONST.__auth_got` | `0x8d0` | `0x928` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x12a0` | `0x12f0` | **`+0x50`** |
| `__TEXT.__const` | `0xf38` | `0xf80` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0xd75` | `0xdbd` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x1014` | `0x104c` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xcc0` | `0xcf8` | **`+0x38`** |
| `__TEXT.__objc_stubs` | `0x30e0` | `0x3100` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xb9c` | `0xbbc` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1118` | `0x1130` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1c30` | `0x1c48` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x4b4` | `0x4c4` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5411.0.0.0.0
+5411.101.0.0.0

-  Functions: 989
-  Symbols:   421
-  CStrings:  1289
+  Functions: 1010
+  Symbols:   423
+  CStrings:  1297
Symbols:
+ _memcmp
+ _swift_release_x3
CStrings:
+ "@\"NSString\"16@?0@\"NSString\"8"
+ "AppState changed (%{private}s): %{public}s"
+ "AppState changed (%{public}s): %{public}s"
+ "B40@0:8@16@24@?32"
+ "Failed to determine bundleID: %{public}s"
+ "appStatesFrom:"
+ "bundleIdentifierForIdentityString:error:"
+ "containsSuspiciousChangesWithOriginalAppStates:currentAppStates:bundleIdentifierResolver:"
```
