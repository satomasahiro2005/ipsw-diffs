## HearingSettings

> `/System/Library/PreferenceBundles/HearingSettings.bundle/HearingSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a968` | `0x3c39c` | **`+0x1a34`** |
| `__TEXT.__swift5_typeref` | `0xbf9` | `0xd5b` | **`+0x162`** |
| `__TEXT.__const` | `0x890` | `0x9d0` | **`+0x140`** |
| `__DATA.__bss` | `0x598` | `0x6b8` | **`+0x120`** |
| `__TEXT.__cstring` | `0x3307` | `0x3427` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x1070` | `0x1178` | **`+0x108`** |
| `__TEXT.__auth_stubs` | `0xf00` | `0xf80` | **`+0x80`** |
| `__DATA.__data` | `0xcd0` | `0xd38` | **`+0x68`** |
| `__DATA_CONST.__auth_got` | `0x790` | `0x7d0` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xa4` | `0xdc` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xe30` | `0xe68` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xd8` | `0x10c` | **`+0x34`** |
| `__TEXT.__objc_methname` | `0x95a7` | `0x95d7` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xd6` | `0x106` | **`+0x30`** |
| `__DATA.__objc_const` | `0x3e38` | `0x3e58` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x6e8` | `0x708` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1d8` | `0x1f4` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x228` | `0x240` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x24` | `0x2c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1c` | `0x20` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`

### Other Changes

```diff

-543.2.3.0.0
+543.2.5.0.0

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 1225
+  Functions: 1266

-  CStrings:  2359
+  CStrings:  2366
CStrings:
+ "AudioRouteNeverHandoffAlertCancel"
+ "AudioRouteNeverHandoffAlertConfirm"
+ "AudioRouteNeverHandoffAlertMessageCalls"
+ "AudioRouteNeverHandoffAlertMessageMedia"
+ "AudioRouteNeverHandoffAlertTitleCalls"
+ "AudioRouteNeverHandoffAlertTitleMedia"
+ "_pendingNeverRouteCategory"
```
