## applekeystored

> `/usr/libexec/applekeystored`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9d84c` | `0x9d990` | **`+0x144`** |
| `__TEXT.__const` | `0x9de9` | `0x9e49` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xea58` | `0xeaa8` | **`+0x50`** |
| `__TEXT.__cstring` | `0xfe5c` | `0xfeac` | **`+0x50`** |
| `__DATA.__data` | `0x7300` | `0x7328` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2383.2.1.0.0
+2383.40.14.0.0

-  Functions: 3304
+  Functions: 3303

-  CStrings:  2637
+  CStrings:  2640
CStrings:
+ "/private/var/mobile/Library/com.apple.safetyalerts"
+ "SafetyAlerts"
+ "com.apple.safetyalertsd"
```
