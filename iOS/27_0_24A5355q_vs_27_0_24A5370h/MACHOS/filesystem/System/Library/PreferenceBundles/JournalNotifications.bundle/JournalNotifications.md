## JournalNotifications

> `/System/Library/PreferenceBundles/JournalNotifications.bundle/JournalNotifications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa7f24` | `0xa8bbc` | **`+0xc98`** |
| `__TEXT.__cstring` | `0x21c4` | `0x2274` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x1a3f` | `0x1adf` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x3b90` | `0x3bf0` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x2aa0` | `0x2a40` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x3c08` | `0x3bb8` | **`-0x50`** |
| `__TEXT.__const` | `0x6c74` | `0x6cc4` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x2228` | `0x2270` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x1dd0` | `0x1e00` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1320` | `0x1350` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x11a9` | `0x11d9` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1f40` | `0x1f18` | **`-0x28`** |
| `__DATA.__data` | `0x58e0` | `0x5900` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x30d6` | `0x30b6` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x460` | `0x440` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0xf20` | `0xf38` | **`+0x18`** |
| `__DATA.__bss` | `0x84b0` | `0x84c0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x308e` | `0x3086` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0xc0` | `0xb8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x188` | `0x18c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
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

-  Functions: 2670
-  Symbols:   460
-  CStrings:  1020
+  Functions: 2667
+  Symbols:   462
+  CStrings:  1022
Symbols:
+ _NSAdaptiveImageGlyphAttributeName
+ _OBJC_CLASS_$_NSAdaptiveImageGlyph
+ _swift_release_x9
- _swift_continuation_resume
CStrings:
+ "Device is locked, skipping update"
+ "imageByPreparingForDisplay"
+ "settings-navigation://com.apple.Settings.AppleAccount?aaaction=upgradeSecurityLevel"
+ "settings-navigation://com.apple.Settings.PrivacyAndSecurity/LOCATION"
- "prepareForDisplayWithCompletionHandler:"
- "v16@?0@\"UIImage\"8"
```
