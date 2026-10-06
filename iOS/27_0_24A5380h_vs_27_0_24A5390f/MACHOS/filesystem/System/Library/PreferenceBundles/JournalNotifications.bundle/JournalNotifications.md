## JournalNotifications

> `/System/Library/PreferenceBundles/JournalNotifications.bundle/JournalNotifications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa9074` | `0xa6418` | **`-0x2c5c`** |
| `__DATA.__objc_data` | `0x6ee0` | `0x6be0` | **`-0x300`** |
| `__DATA_CONST.__const` | `0x3bb8` | `0x3920` | **`-0x298`** |
| `__DATA.__bss` | `0x84c0` | `0x8240` | **`-0x280`** |
| `__TEXT.__cstring` | `0x2274` | `0x2104` | **`-0x170`** |
| `__TEXT.__objc_methname` | `0x30c6` | `0x3236` | **`+0x170`** |
| `__TEXT.__const` | `0x6cd4` | `0x6bc4` | **`-0x110`** |
| `__TEXT.__oslogstring` | `0x1209` | `0x1139` | **`-0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x1aff` | `0x1a4f` | **`-0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x227c` | `0x21e8` | **`-0x94`** |
| `__TEXT.__objc_methlist` | `0x99c` | `0xa04` | **`+0x68`** |
| `__TEXT.__objc_stubs` | `0x2cc0` | `0x2d20` | **`+0x60`** |
| `__DATA.__objc_const` | `0x3358` | `0x33b0` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x2a40` | `0x2a98` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x584` | `0x534` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x3730` | `0x36e4` | **`-0x4c`** |
| `__DATA.__objc_selrefs` | `0xdb0` | `0xdf8` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1358` | `0x1390` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x3c10` | `0x3be0` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x307e` | `0x305c` | **`-0x22`** |
| `__DATA.__data` | `0x5900` | `0x58e0` | **`-0x20`** |
| `__DATA.__common` | `0x4a0` | `0x4b8` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1e10` | `0x1df8` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x808` | `0x7f0` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x1f18` | `0x1f00` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x48c` | `0x478` | **`-0x14`** |
| `__DATA_CONST.__auth_ptr` | `0xf30` | `0xf28` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x278` | `0x274` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x18c` | `0x190` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xac` | `0xb0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-89.0.0.0.0
+94.0.0.0.0

-  Functions: 2667
+  Functions: 2654

-  CStrings:  1023
+  CStrings:  1011
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
- "audioPicker"
- "automatic"
- "beginUndoGroupIfNeeded()"
- "cameraPicker"
- "didShowMindfulMinuteHealthPermissionKey"
- "didShowStateOfMindHealthPermissionKey"
- "drawingCanvas"
- "external"
- "imagePicker"
- "initWithData:"
- "intelligentToolbox"
- "locationPicker"
- "mediaPicker"
- "setActionName:"
- "setHasSeenBothHealthTCCs:"
- "setParentContext:"
- "shareSheet"
- "stateOfMindPicker"
- "suggestionSheet"
- "unknown"
```
