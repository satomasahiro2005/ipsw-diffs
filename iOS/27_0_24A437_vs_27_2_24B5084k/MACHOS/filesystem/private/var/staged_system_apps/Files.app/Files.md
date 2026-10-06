## Files

> `/private/var/staged_system_apps/Files.app/Files`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71d34` | `0x7231c` | **`+0x5e8`** |
| `__TEXT.__objc_stubs` | `0x2160` | `0x2200` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x4c21` | `0x4c91` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x3615` | `0x3675` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x10b8` | `0x10e0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x5730` | `0x5758` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x640` | `0x650` | **`+0x10`** |
| `__TEXT.__const` | `0x18a4` | `0x18b4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xda0` | `0xda8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-401.0.0.0.0
+401.1.5.0.0

-  Functions: 1652
-  Symbols:   865
-  CStrings:  1255
+  Functions: 1655
+  Symbols:   867
+  CStrings:  1261
Symbols:
+ _DOCDocumentsAppBundleIdentifier
+ _OBJC_CLASS_$_DOCStateRestorationCrashGuard
CStrings:
+ "%s: Discarding the state restoration activity because %ld launches in a row crashed"
+ "beginLaunchAttemptForHostIdentifier:"
+ "finishLaunchAttempt"
+ "isRestorationSuppressed"
+ "maximumConsecutiveFailedLaunches"
+ "sharedGuard"
```
