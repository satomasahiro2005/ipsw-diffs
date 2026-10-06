## JournalWidgetsSecure

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalWidgetsSecure.appex/JournalWidgetsSecure`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbc7d4` | `0xb8de0` | **`-0x39f4`** |
| `__DATA.__objc_data` | `0x6b20` | `0x6820` | **`-0x300`** |
| `__DATA.__bss` | `0x88d8` | `0x86d8` | **`-0x200`** |
| `__TEXT.__const` | `0x7c64` | `0x7b14` | **`-0x150`** |
| `__DATA_CONST.__const` | `0x3a90` | `0x3950` | **`-0x140`** |
| `__TEXT.__cstring` | `0x2859` | `0x2789` | **`-0xd0`** |
| `__TEXT.__oslogstring` | `0x11ea` | `0x111a` | **`-0xd0`** |
| `__TEXT.__eh_frame` | `0x2cd4` | `0x2d9c` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x4350` | `0x42c0` | **`-0x90`** |
| `__DATA.__data` | `0x6b60` | `0x6b10` | **`-0x50`** |
| `__TEXT.__swift5_capture` | `0x540` | `0x4f0` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x3cc4` | `0x3c78` | **`-0x4c`** |
| `__DATA_CONST.__auth_got` | `0x21b0` | `0x2168` | **`-0x48`** |
| `__TEXT.__swift5_typeref` | `0x6c6a` | `0x6c2a` | **`-0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x15e8` | `0x15b0` | **`-0x38`** |
| `__DATA.__objc_selrefs` | `0xa28` | `0xa38` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x6ec` | `0x6fc` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x232c` | `0x231c` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x4a4` | `0x494` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1971` | `0x1961` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x14e0` | `0x14e8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2bc` | `0x2b8` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x1e4` | `0x1e8` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xb4` | `0xb8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-89.0.0.0.0
+94.0.0.0.0

-  Functions: 2913
-  Symbols:   440
-  CStrings:  902
+  Functions: 2890
+  Symbols:   439
+  CStrings:  896
Symbols:
- _swift_release_x12
CStrings:
+ "EntryUndoManager.redo()"
+ "isRedoing"
+ "isUndoing"
+ "redo"
+ "setGroupsByEvent:"
+ "setPersistentStoreCoordinator:"
- "An unknown exception occurred."
- "EntryViewModel undoable could not generate an action to undo snapshot for action %s"
- "Failed to parse image properties from the passed data / image source."
- "Move Asset undo/redo button label"
- "No undo manager; just performing actions for %s"
- "Performing undoable %s \nBefore: %s\nAfter:  %s"
- "Registering reverse undo action %s"
- "attachmentIdsMissingFile"
- "beginUndoGroupIfNeeded()"
- "initWithData:"
- "setActionName:"
- "setParentContext:"
```
