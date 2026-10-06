## JournalShareExtension

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalShareExtension.appex/JournalShareExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf6c04` | `0xf9564` | **`+0x2960`** |
| `__DATA.__bss` | `0x6510` | `0x6810` | **`+0x300`** |
| `__DATA_CONST.__const` | `0x4ce0` | `0x4f80` | **`+0x2a0`** |
| `__TEXT.__const` | `0x6224` | `0x6474` | **`+0x250`** |
| `__TEXT.__eh_frame` | `0x4b40` | `0x4ca8` | **`+0x168`** |
| `__TEXT.__swift5_typeref` | `0x2bf4` | `0x2d34` | **`+0x140`** |
| `__TEXT.__objc_methtype` | `0x1b67` | `0x1c97` | **`+0x130`** |
| `__TEXT.__objc_methname` | `0x6a8d` | `0x6b8d` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0xe94` | `0xf7c` | **`+0xe8`** |
| `__TEXT.__objc_stubs` | `0x4e20` | `0x4ee0` | **`+0xc0`** |
| `__DATA.__data` | `0x5d68` | `0x5de8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x2798` | `0x2808` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x22dd` | `0x233d` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x3d28` | `0x3d68` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1ae0` | `0x1b18` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x40b0` | `0x40e0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x680` | `0x6b0` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x26c` | `0x294` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1e70` | `0x1e8c` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x2060` | `0x2078` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x14bc` | `0x14d4` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x3b0` | `0x3c8` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xe08` | `0xe18` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1300` | `0x1310` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x368` | `0x374` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x258` | `0x260` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x170` | `0x178` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1f0` | `0x1f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-94.0.0.0.0
+99.2.1.0.0

-  Functions: 3137
-  Symbols:   505
-  CStrings:  1714
+  Functions: 3195
+  Symbols:   506
+  CStrings:  1724
Symbols:
+ _NSIntersectionRange
CStrings:
+ "Context stats from %{public}s for [%{public}s] context\ninsertedObjects.count: %ld\ndeletedObjects.count: %ld\nupdatedObjects.count: %ld"
+ "EntryViewModel added %{public}s asset in %s with id %{public}s to entry id %{public}s. Undoable: %{bool}d. Time: %f seconds"
+ "EntryViewModel.finishEditingAndSave - assets.count: %ld entry id: %{public}s"
+ "Error saving EntryViewModel editing context %@: %@"
+ "JournalEntryAssetFileAttachmentMO is missing filePath, likely not downloaded yet. ID: %{public}s"
+ "_disabledComponentsForTextFormattingOptions"
+ "componentKey"
+ "components"
+ "enumerateSubstringsInRange:options:usingBlock:"
+ "groups"
+ "setAttributes:"
+ "v16@?0@\"NSAttributedString\"8"
+ "v56@?0@\"NSString\"8{_NSRange=QQ}16{_NSRange=QQ}32^B48"
+ "v80@0:8@\"UIWritingToolsCoordinator\"16{_NSRange=QQ}24@\"UIWritingToolsCoordinatorContext\"40@\"NSAttributedString\"48q56@\"UIWritingToolsCoordinatorAnimationParameters\"64@?<v@?@\"NSAttributedString\">72"
+ "writingToolsCoordinator:replaceRange:inContext:proposedText:reason:animationParameters:completion:"
- "%s for [%s] context\ninsertedObjects.count: %ld\ndeletedObjects.count: %ld\nupdatedObjects.count: %ld"
- "(finishEditingAndSave) Error saving editing context %@: %@"
- "(finishEditingAndSave) assets.count: %ld entry id: %{public}s"
- "EntryViewModel added %{public}s asset in %s with id %{public}s to entry id %{public}s %f seconds"
- "JournalEntryAssetFileAttachmentMO is missing filePath. ID: %{public}s"
```
