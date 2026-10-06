## DiagnosticExtensionsKit

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsKit.framework/DiagnosticExtensionsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f57c` | `0x3f3e8` | **`-0x194`** |
| `__AUTH_CONST.__const` | `0x3f40` | `0x3e78` | **`-0xc8`** |
| `__TEXT.__swift5_capture` | `0x188c` | `0x183c` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0xe76` | `0xe4a` | **`-0x2c`** |
| `__TEXT.__const` | `0x5e2` | `0x5d2` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0x5f0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x610` | `0x618` | **`+0x8`** |
| `__DATA.__data` | `0x4b0` | `0x4b8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-149.0.0.0.0
+150.0.0.0.0

-  Functions: 929
+  Functions: 928

-  CStrings:  120
+  CStrings:  119
CStrings:
+ "ExtensionKit discovery failed: %{public}s"
+ "On-demand discovery failed for [%{public}s]: [%{public}s]"
+ "extensionWithIdentifier(_:)"
- "ExtensionKit discovery failed: %s"
- "On-demand discovery error: %{public}s"
- "On-demand discovery failed for %{public}s: %{public}s"
- "findExtension(withIdentifier:)"
```
