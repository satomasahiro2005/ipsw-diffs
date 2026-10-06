## com.apple.mobilenotes.EditorExtension

> `/private/var/staged_system_apps/MobileNotes.app/PlugIns/com.apple.mobilenotes.EditorExtension.appex/com.apple.mobilenotes.EditorExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x244` | `0x1e4` | **`-0x60`** |
| `__TEXT.__text` | `0x9944` | `0x9900` | **`-0x44`** |
| `__TEXT.__auth_stubs` | `0xa60` | `0xa40` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x538` | `0x528` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1d0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3001.2.2.0.0
+3001.40.8.100.1

-  Symbols:   185
-  CStrings:  247
+  Symbols:   182
+  CStrings:  246
Symbols:
- _ICInternalSettingsIsAppleAccountBrandingEnabled
- _ICInternalSettingsIsTextKit2Enabled
- _OBJC_CLASS_$_ICNoteEditorViewController
Functions:
~ sub_1000029b0 : 3180 -> 3156
~ sub_10000766c -> sub_100007654 : 1160 -> 1116
CStrings:
- "To use Quick Notes, an upgraded iCloud account or On My iPhone account is required."
```
