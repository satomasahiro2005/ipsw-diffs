## BiometricKit

> `/System/Library/PrivateFrameworks/BiometricKit.framework/BiometricKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x9b0` | `0x690` | **`-0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x4b0` | `0x7d0` | **`+0x320`** |
| `__DATA.__bss` | `0x48` | `0x28` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__text` | `0x3c574` | `0x3c580` | **`+0xc`** |
| `__TEXT.__oslogstring` | `0x4f89` | `0x4f88` | **`-0x1`** |

### Other Changes

```diff

-573.0.0.0.0
+575.0.0.0.0
Functions:
~ +[BiometricKitXPCClient clientUUID] : 428 -> 436
~ _ComponentSetUpdate : 5144 -> 5148
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-575~83, %s file: %s, line: %d\n\n"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-573~902, %s file: %s, line: %d\n\n"
```
