## JournalSettings

> `/System/Library/PreferenceBundles/JournalSettings.bundle/JournalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x772ec` | `0x74ee8` | **`-0x2404`** |
| `__DATA.__objc_data` | `0x6d28` | `0x6a28` | **`-0x300`** |
| `__TEXT.__objc_methname` | `0x2ae6` | `0x2c36` | **`+0x150`** |
| `__TEXT.__oslogstring` | `0x1175` | `0x10a5` | **`-0xd0`** |
| `__TEXT.__eh_frame` | `0x1a20` | `0x1ae8` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x2d60` | `0x2cb0` | **`-0xb0`** |
| `__TEXT.__cstring` | `0x2a34` | `0x2984` | **`-0xb0`** |
| `__DATA_CONST.__got` | `0xe10` | `0xeb8` | **`+0xa8`** |
| `__TEXT.__objc_methlist` | `0x9b4` | `0xa1c` | **`+0x68`** |
| `__TEXT.__objc_stubs` | `0x2420` | `0x2480` | **`+0x60`** |
| `__DATA.__objc_const` | `0x30b8` | `0x3110` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x540` | `0x4f0` | **`-0x50`** |
| `__DATA.__objc_selrefs` | `0xba0` | `0xbe8` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x3370` | `0x3330` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1530` | `0x1568` | **`+0x38`** |
| `__TEXT.__const` | `0x4654` | `0x4684` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x2f54` | `0x2f24` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x14ca` | `0x14fa` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x19c0` | `0x19a0` | **`-0x20`** |
| `__DATA.__common` | `0x448` | `0x460` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x1840` | `0x1858` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xbd0` | `0xbd8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1e4a` | `0x1e44` | **`-0x6`** |
| `__TEXT.__swift_as_cont` | `0xcc` | `0xd0` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x94` | `0x98` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-89.0.0.0.0
+94.0.0.0.0

-  Functions: 1821
-  Symbols:   349
-  CStrings:  967
+  Functions: 1826
+  Symbols:   347
+  CStrings:  968
Symbols:
- _swift_release_x12
- _swift_retain_x8
CStrings:
+ "EntryUndoManager.redo()"
+ "didShowMindfulMinuteHealthPermission"
+ "didShowStateOfMindHealthPermission"
+ "isRedoing"
+ "isUndoing"
+ "keyPathsForValuesAffectingDidShowMindfulMinuteHealthPermission"
+ "keyPathsForValuesAffectingDidShowStateOfMindHealthPermission"
+ "keyPathsForValuesAffectingHasSeenBothHealthTCCs"
+ "persistentStoreCoordinator"
+ "redo"
+ "setDidShowMindfulMinuteHealthPermission:"
+ "setDidShowStateOfMindHealthPermission:"
+ "setGroupsByEvent:"
+ "setPersistentStoreCoordinator:"
- "EntryViewModel undoable could not generate an action to undo snapshot for action %s"
- "Move Asset undo/redo button label"
- "No undo manager; just performing actions for %s"
- "Performing undoable %s \nBefore: %s\nAfter:  %s"
- "Registering reverse undo action %s"
- "attachmentIdsMissingFile"
- "beginUndoGroupIfNeeded()"
- "didShowMindfulMinuteHealthPermissionKey"
- "didShowStateOfMindHealthPermissionKey"
- "initWithData:"
- "setActionName:"
- "setHasSeenBothHealthTCCs:"
- "setParentContext:"
```
