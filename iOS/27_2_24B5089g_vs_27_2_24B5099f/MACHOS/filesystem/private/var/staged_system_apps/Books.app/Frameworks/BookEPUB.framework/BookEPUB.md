## BookEPUB

> `/private/var/staged_system_apps/Books.app/Frameworks/BookEPUB.framework/BookEPUB`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2831b4` | `0x285164` | **`+0x1fb0`** |
| `__DATA.__bss` | `0xe010` | `0xe410` | **`+0x400`** |
| `__TEXT.__const` | `0x1e180` | `0x1e3f0` | **`+0x270`** |
| `__TEXT.__eh_frame` | `0x5394` | `0x551c` | **`+0x188`** |
| `__DATA_CONST.__const` | `0x15d50` | `0x15e80` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0xc9a3` | `0xcac3` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x7090` | `0x7138` | **`+0xa8`** |
| `__TEXT.__constg_swiftt` | `0x952c` | `0x95c8` | **`+0x9c`** |
| `__DATA.__data` | `0xce98` | `0xcf08` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x6a8d` | `0x6afd` | **`+0x70`** |
| `__DATA.__objc_data` | `0x5618` | `0x5680` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x5d74` | `0x5ddc` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x66ce` | `0x6736` | **`+0x68`** |
| `__DATA.__objc_const` | `0x10d68` | `0x10dc8` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x14648` | `0x146a8` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x2558` | `0x25b0` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x3e80` | `0x3ed0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x9231` | `0x9281` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x770` | `0x7a0` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1f58` | `0x1f80` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xe08` | `0xe30` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0xaac0` | `0xaaa0` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x7d8` | `0x7f8` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x258` | `0x274` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x230` | `0x244` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0x58a8` | `0x58b8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x42d8` | `0x42d0` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x4cc` | `0x4d4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x4504` | `0x4508` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-6715.0.0.0.0
+6722.11.0.0.0

-  Functions: 11429
-  Symbols:   1475
-  CStrings:  5851
+  Functions: 11474
+  Symbols:   1478
+  CStrings:  5858
Symbols:
+ _UIAccessibilitySwitchControlStatusDidChangeNotification
+ _UIAccessibilityVoiceOverStatusDidChangeNotification
+ _swift_willThrowTypedImpl
CStrings:
+ "AX: no loader for current location -- cannot refresh reading state after accessibility status change"
+ "AX: screen reader enabled after book open -- refreshing reading state for current page"
+ "Failed to get contentView as? WKWebView -- unable to force value `%s`"
+ "axScreenReaderRunning"
+ "axStatusObservationTasks"
+ "contentSnapshotKind"
+ "kREIIpadEnhancedLandscapePageLabelOffset"
+ "kREIIpadPageLabelOffset"
- "screen"
```
