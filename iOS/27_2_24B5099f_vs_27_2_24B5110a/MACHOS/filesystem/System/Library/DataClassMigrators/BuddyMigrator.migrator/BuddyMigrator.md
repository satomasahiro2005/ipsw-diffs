## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d6b0` | `0x2dbfc` | **`+0x54c`** |
| `__TEXT.__objc_stubs` | `0x3080` | `0x31e0` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x4ced` | `0x4dcd` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x2e89` | `0x2f69` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0x1110` | `0x1158` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x1c40` | `0x1c70` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0xaa0` | `0xac0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x4a0` | `0x4b0` | **`+0x10`** |
| `__TEXT.__const` | `0xf80` | `0xf90` | **`+0x10`** |
| `__TEXT.__cstring` | `0x10a2` | `0x10b2` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xcf0` | `0xd00` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x12d0` | `0x12d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5411.2.2.0.0
+5411.2.4.0.0

-  Functions: 1007
-  Symbols:   421
-  CStrings:  1290
+  Functions: 1012
+  Symbols:   424
+  CStrings:  1304
Symbols:
+ _BuddyRestoreStateDebugFileKey
+ _OBJC_CLASS_$_NSFileManager
+ _OBJC_CLASS_$_NSURL
CStrings:
+ "DebugRestoreStateFile"
+ "Failed to write restore state to %{public}@: %{public}@"
+ "Ignoring invalid restore state file %{public}@: %{public}@ (%{public}@)"
+ "Persisting restore state from %{public}@: %{public}@"
+ "Wrote restore state to %{public}@: %{public}@"
+ "_debugRestoreStateFileURL"
+ "_loadDebugRestoreStateFileIfNeededIntoPreferences:"
+ "dictionaryWithContentsOfURL:error:"
+ "fileExistsAtPath:"
+ "fileURLWithPath:"
+ "length"
+ "path"
+ "writeToDebugRestoreStateFileIfNeeded"
+ "writeToURL:error:"
```
