## MusicSettingsAppIntents

> `/System/Library/ExtensionKit/Extensions/MusicSettingsAppIntents.appex/MusicSettingsAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5398` | `0x557c` | **`+0x1e4`** |
| `__TEXT.__eh_frame` | `0x1e0` | `0x238` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x5c0` | `0x610` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x16d` | `0x19e` | **`+0x31`** |
| `__DATA_CONST.__auth_got` | `0x2e8` | `0x310` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x240` | `0x260` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc8` | `0xd8` | **`+0x10`** |
| `__TEXT.__const` | `0xad0` | `0xae0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x260` | `0x270` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x90` | `0x98` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x4a0` | `0x4a8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2c` | `0x30` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-4026.100.73.0.0
+4026.100.79.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 194
-  Symbols:   89
-  CStrings:  62
+  Functions: 197
+  Symbols:   94
+  CStrings:  63
Symbols:
+ _OBJC_CLASS_$_LSApplicationRecord
+ _objc_release
+ _objc_release_x23
+ _objc_release_x24
+ _objc_retain_x22
CStrings:
+ "initWithBundleIdentifier:allowPlaceholder:error:"
```
