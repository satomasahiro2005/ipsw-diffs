## CryptoTokenKit

> `/System/Library/Frameworks/CryptoTokenKit.framework/CryptoTokenKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a048` | `0x4a19c` | **`+0x154`** |
| `__TEXT.__oslogstring` | `0x389d` | `0x38e4` | **`+0x47`** |
| `__AUTH_CONST.__cfstring` | `0x3240` | `0x3260` | **`+0x20`** |
| `__TEXT.__const` | `0x2d0` | `0x2e8` | **`+0x18`** |
| `__DATA.__bss` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x18a8` | `0x18b0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-878.40.4.0.0
+878.40.5.0.0

-  Functions: 2071
-  Symbols:   3695
-  CStrings:  866
+  Functions: 2074
+  Symbols:   3697
+  CStrings:  868
Symbols:
+ __block_invoke.gsmakDataBytes
+ _gsmakData
CStrings:
+ "gsmak"
+ "gsmak not supported, attempt to read its public key failed, error %08x"
```
