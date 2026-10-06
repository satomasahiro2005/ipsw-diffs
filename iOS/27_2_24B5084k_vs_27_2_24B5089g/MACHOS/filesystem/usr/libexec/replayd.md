## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbac1c` | `0xbadf8` | **`+0x1dc`** |
| `__TEXT.__oslogstring` | `0x166f4` | `0x167e9` | **`+0xf5`** |
| `__TEXT.__cstring` | `0x17c86` | `0x17cf7` | **`+0x71`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-765.9.1.0.0
+765.11.1.0.0

-  Functions: 3680
+  Functions: 3682

-  CStrings:  7382
+  CStrings:  7387
CStrings:
+ " [ERROR] %{public}s:%d pickerDidCancel rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [ERROR] %{public}s:%d pickerDidDismiss rejected: caller lacks ScreenCaptureKit private entitlement"
+ " [INFO] %{public}s:%d skipping invalid pid=%@"
+ "-[RPConnectionManager pickerDidCancel:forStream:]"
+ "-[RPConnectionManager pickerDidDismiss:forStream:isCancelled:]"
```
