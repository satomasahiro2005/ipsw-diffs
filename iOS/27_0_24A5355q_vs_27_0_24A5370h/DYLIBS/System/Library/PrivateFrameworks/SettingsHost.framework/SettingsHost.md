## SettingsHost

> `/System/Library/PrivateFrameworks/SettingsHost.framework/SettingsHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ee58` | `0x7f5d0` | **`+0x778`** |
| `__TEXT.__eh_frame` | `0x21a8` | `0x2238` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0xf78` | `0xfa8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1750` | `0x1778` | **`+0x28`** |
| `__DATA.__data` | `0x860` | `0x870` | **`+0x10`** |
| `__TEXT.__const` | `0x5288` | `0x5298` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x148` | `0x154` | **`+0xc`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-27.0.20.0.0
+27.0.20.100.0

-  Functions: 2113
+  Functions: 2114
CStrings:
+ "Another process is already indexing '%{public}s', waiting until it finishes."
- "Another process is already indexing '%{public}s', yielding until it finishes."
```
