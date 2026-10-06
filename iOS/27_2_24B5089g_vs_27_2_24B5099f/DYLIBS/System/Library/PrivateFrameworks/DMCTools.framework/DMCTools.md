## DMCTools

> `/System/Library/PrivateFrameworks/DMCTools.framework/DMCTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21388` | `0x22130` | **`+0xda8`** |
| `__TEXT.__oslogstring` | `0xe56` | `0xfe6` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x7c0` | `0x820` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x718` | `0x778` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x6f8` | `0x748` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x550` | `0x5a0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x6f0` | `0x738` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0xfb0` | `0xfe0` | **`+0x30`** |
| `__TEXT.__const` | `0xdd8` | `0xdf8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x810` | `0x820` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x114` | `0x124` | **`+0x10`** |
| `__DATA.__data` | `0x4a8` | `0x4b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x268` | `0x270` | **`+0x8`** |

### Other Changes

```diff

-113.40.17.0.0
+113.40.20.0.0

-  Functions: 648
-  Symbols:   352
-  CStrings:  85
+  Functions: 666
+  Symbols:   355
+  CStrings:  89
Symbols:
+ _OBJC_CLASS_$_BGRepeatingSystemTaskRequest
+ _objc_retain_x26
+ _swift_retain_x21
CStrings:
+ "DMCBackgroundTask failed to submit repeating task '%{public}s' with error: %{public}@"
+ "DMCBackgroundTask failed to update repeating task '%{public}s' with error: %{public}@. Falling back to submit."
+ "DMCBackgroundTask submitted repeating task '%{public}s' with interval %{public}f seconds"
+ "DMCBackgroundTask task with name %s exists, attempting to cancel before submitting"
+ "DMCBackgroundTask updated repeating task '%{public}s' with interval %{public}f seconds"
- "DMCBackgroundTask task with name %s exists, attempting to cancel before submitting again"
```
