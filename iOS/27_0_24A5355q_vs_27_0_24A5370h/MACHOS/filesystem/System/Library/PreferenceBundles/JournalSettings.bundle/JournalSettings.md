## JournalSettings

> `/System/Library/PreferenceBundles/JournalSettings.bundle/JournalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76258` | `0x76ba4` | **`+0x94c`** |
| `__TEXT.__cstring` | `0x2984` | `0x2a34` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x141a` | `0x14aa` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x1a78` | `0x1a20` | **`-0x58`** |
| `__DATA_CONST.__const` | `0x2db0` | `0x2d60` | **`-0x50`** |
| `__DATA_CONST.__got` | `0xdd8` | `0xe08` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x32e0` | `0x3310` | **`+0x30`** |
| `__TEXT.__const` | `0x4614` | `0x4644` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x494` | `0x464` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1804` | `0x1834` | **`+0x30`** |
| `__DATA.__data` | `0x4758` | `0x4778` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1978` | `0x1990` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xbb8` | `0xbd0` | **`+0x18`** |
| `__DATA.__bss` | `0x5250` | `0x5260` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x2f34` | `0x2f44` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x2ae6` | `0x2ad6` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1540` | `0x1530` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x1e52` | `0x1e4a` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0xb0` | `0xa8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xc8` | `0xcc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-77.0.0.0.0
+84.0.0.0.0

-  Functions: 1823
-  Symbols:   348
-  CStrings:  965
+  Functions: 1819
+  Symbols:   349
+  CStrings:  966
Symbols:
+ _NSAdaptiveImageGlyphAttributeName
+ _OBJC_CLASS_$_NSAdaptiveImageGlyph
- _swift_continuation_resume
CStrings:
+ "imageByPreparingForDisplay"
+ "settings-navigation://com.apple.Settings.AppleAccount?aaaction=upgradeSecurityLevel"
+ "settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCATION"
- "prepareForDisplayWithCompletionHandler:"
- "v16@?0@\"UIImage\"8"
```
