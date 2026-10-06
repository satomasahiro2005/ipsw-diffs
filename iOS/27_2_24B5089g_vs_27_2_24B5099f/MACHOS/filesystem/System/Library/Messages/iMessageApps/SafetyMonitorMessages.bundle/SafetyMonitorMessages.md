## SafetyMonitorMessages

> `/System/Library/Messages/iMessageApps/SafetyMonitorMessages.bundle/SafetyMonitorMessages`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16c9c` | `0x16d94` | **`+0xf8`** |
| `__DATA_CONST.__const` | `0x3a8` | `0x3f8` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0xa87` | `0xa57` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x1a0` | `0x1c8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x62c` | `0x64c` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xb00` | `0xae0` | **`-0x20`** |
| `__DATA.__objc_data` | `0x200` | `0x1f0` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x11c0` | `0x11d0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x198` | `0x188` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x2bc` | `0x2c8` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x350` | `0x348` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x8e8` | `0x8f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1123.0.0.0.0
+1123.0.3.0.0

-  Functions: 200
-  Symbols:   164
-  CStrings:  219
+  Functions: 202
+  Symbols:   165
+  CStrings:  218
Symbols:
+ _swift_release_x24
CStrings:
+ "endSessionButtonHandler(presenter:)"
+ "safeResponseToTriggerPrompt(presenter:)"
- "dismissViewControllerAnimated:completion:"
- "endSessionButtonHandler()"
- "safeResponseToTriggerPrompt()"
```
