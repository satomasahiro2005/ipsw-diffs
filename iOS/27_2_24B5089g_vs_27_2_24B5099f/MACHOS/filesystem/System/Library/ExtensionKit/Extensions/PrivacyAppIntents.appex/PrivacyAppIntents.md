## PrivacyAppIntents

> `/System/Library/ExtensionKit/Extensions/PrivacyAppIntents.appex/PrivacyAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7254` | `0x8920` | **`+0x16cc`** |
| `__DATA.__bss` | `0x1380` | `0x1600` | **`+0x280`** |
| `__TEXT.__auth_stubs` | `0x540` | `0x6f0` | **`+0x1b0`** |
| `__TEXT.__const` | `0xc14` | `0xda0` | **`+0x18c`** |
| `__TEXT.__cstring` | `0x259d` | `0x2702` | **`+0x165`** |
| `__DATA_CONST.__const` | `0x8a8` | `0x9d8` | **`+0x130`** |
| `__TEXT.__oslogstring` | `—` | `0x115` | **`+0x115`** |
| `__DATA_CONST.__auth_got` | `0x2a8` | `0x380` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0x3e6` | `0x43d` | **`+0x57`** |
| `__DATA.__data` | `0x1b0` | `0x200` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x118` | `0x160` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x2f4` | `0x338` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x2e0` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x363` | `0x39e` | **`+0x3b`** |
| `__TEXT.__swift5_assocty` | `0x130` | `0x160` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x478` | `0x490` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xb8` | `0xd0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x9c` | `0xb0` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x24` | `0x2c` | **`+0x8`** |
| `__DATA.__common` | `0x30` | `0x31` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.1.7.0.0
+2027.1.9.0.0

-  Functions: 201
-  Symbols:   68
-  CStrings:  162
+  Functions: 230
+  Symbols:   81
+  CStrings:  174
Symbols:
+ __os_log_impl
+ _objc_release_x23
+ _os_log_type_enabled
+ _swift_arrayDestroy
+ _swift_beginAccess
+ _swift_deallocObject
+ _swift_getForeignTypeMetadata
+ _swift_getObjectType
+ _swift_release_n
+ _swift_release_x22
+ _swift_release_x27
+ _swift_release_x8
+ _swift_retain_n
+ _swift_slowDealloc
+ _swift_unknownObjectRetain
- ___stack_chk_fail
- ___stack_chk_guard
CStrings:
+ "%{public}s answered %{public}s rather than ELIGIBLE."
+ "%{public}s query failed with status %{public}d. Treating as not eligible, so this domain contributes no transparency report."
+ "DARMSTADTIUM"
+ "GREYMATTER"
+ "NOT_YET_AVAILABLE"
+ "Presenting no transparency report."
+ "Presenting the %{public}s transparency report."
+ "Private Cloud Compute Report"
+ "The “Private Cloud Compute Report” setting is in the iOS Settings app under “Privacy & Security” pane. This setting allows users to view Private Cloud Compute reports."
+ "Transparency Report"
+ "com.apple.settings.PrivacyAndSecuritySettings"
+ "unrecognized answer "
```
