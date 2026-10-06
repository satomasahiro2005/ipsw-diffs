## SupportFlow

> `/Applications/SupportFlow.app/SupportFlow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x138528` | `0x139228` | **`+0xd00`** |
| `__TEXT.__eh_frame` | `0x7334` | `0x73e4` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0xe2b8` | `0xe358` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x138d2` | `0x1386e` | **`-0x64`** |
| `__TEXT.__cstring` | `0xa5aa` | `0xa60a` | **`+0x60`** |
| `__TEXT.__const` | `0x15a24` | `0x159d4` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x16e2` | `0x1732` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x1224` | `0x1264` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x6668` | `0x66a0` | **`+0x38`** |
| `__DATA.__data` | `0xdb60` | `0xdb90` | **`+0x30`** |
| `__DATA.__objc_const` | `0x3018` | `0x3038` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1b60` | `0x1b40` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x72dc` | `0x72f0` | **`+0x14`** |
| `__TEXT.__objc_methname` | `0x32e7` | `0x32f7` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x513c` | `0x5130` | **`-0xc`** |
| `__DATA.__objc_selrefs` | `0xa90` | `0xa88` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1c40` | `0x1c48` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x648` | `0x644` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x270` | `0x274` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-37.0.24.0.0
+37.0.26.0.0

-  Functions: 9774
+  Functions: 9785

-  CStrings:  1825
+  CStrings:  1827
Symbols:
+ _$s7SwiftUI4ViewPAAE18accessibilityLabelyAA15ModifiedContentVyxAA31AccessibilityAttachmentModifierVGAA4TextVF
- _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
CStrings:
+ "Accessibility label for the close button."
+ "CLOSE_BUTTON_ACCESSIBILITY_LABEL"
+ "Failed to observe iCloud backup enabled state notification: %{public}@"
+ "backupStateObservationTask"
+ "com.apple.private.restrict-post.MobileBackup.EnabledState"
- "BACKUP_TURN_ON_AFTER_ACCOUNT"
- "com.apple.SupportFlow"
- "syncBackupEnabled"
```
