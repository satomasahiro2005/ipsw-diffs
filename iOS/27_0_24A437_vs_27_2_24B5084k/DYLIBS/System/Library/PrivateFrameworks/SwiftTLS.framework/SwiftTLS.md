## SwiftTLS

> `/System/Library/PrivateFrameworks/SwiftTLS.framework/SwiftTLS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdfb7c` | `0xdfd68` | **`+0x1ec`** |
| `__TEXT.__cstring` | `0x1161` | `0x1221` | **`+0xc0`** |
| `__TEXT.__const` | `0x7284` | `0x72a4` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x27c3` | `0x27e3` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2d34` | `0x2d40` | **`+0xc`** |

### Other Changes

```diff

-171.0.15.0.0
+171.40.7.0.0

-  Functions: 2303
+  Functions: 2305

-  CStrings:  386
+  CStrings:  389
CStrings:
+ "Unexpectedly parsed ciphertext when expecting plaintext"
+ "Unexpectedly parsed plaintext when expecting ciphertext"
+ "can't check key usage limit without ciphersuite set"
```
