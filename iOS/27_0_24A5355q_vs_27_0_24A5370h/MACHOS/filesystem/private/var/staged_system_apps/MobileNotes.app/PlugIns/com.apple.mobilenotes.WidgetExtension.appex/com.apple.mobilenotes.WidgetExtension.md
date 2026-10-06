## com.apple.mobilenotes.WidgetExtension

> `/private/var/staged_system_apps/MobileNotes.app/PlugIns/com.apple.mobilenotes.WidgetExtension.appex/com.apple.mobilenotes.WidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x605ec` | `0x61914` | **`+0x1328`** |
| `__TEXT.__oslogstring` | `0xe8d` | `0xf81` | **`+0xf4`** |
| `__TEXT.__auth_stubs` | `0x1d30` | `0x1e10` | **`+0xe0`** |
| `__DATA_CONST.__auth_got` | `0xea8` | `0xf18` | **`+0x70`** |
| `__DATA.__data` | `0x3118` | `0x3148` | **`+0x30`** |
| `__TEXT.__cstring` | `0x14fd` | `0x152d` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x750` | `0x760` | **`+0x10`** |
| `__TEXT.__const` | `0x8664` | `0x8674` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1c40` | `0x1c50` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb5c` | `0xb68` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2985.0.0.202.2
+2991.0.0.0.0

-  Functions: 2125
-  Symbols:   277
-  CStrings:  625
+  Functions: 2130
+  Symbols:   276
+  CStrings:  630
Symbols:
+ __os_signpost_emit_with_name_impl
- _swift_release_x28
- _swift_retain_x8
CStrings:
+ "GetTimeline"
+ "[Error] Interval already ended"
+ "[QNDBG] QuickNote getTimeline enter {family: %s}"
+ "[QNDBG] QuickNote getTimeline returning {noteId: %s, hasThumbnail: %{bool}d}"
+ "[QNDBG] widgetThumbnail reports back unknown family: %s. Defaulting to .extraLargeQuickNoteWidget"
```
