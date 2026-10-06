## libcryptex.dylib

> `/usr/lib/libcryptex.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2d0` | `0x280` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1e0` | `0x230` | **`+0x50`** |
| `__DATA.__bss` | `0x88` | `0x60` | **`-0x28`** |
| `__DATA_DIRTY.__bss` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__text` | `0x25c60` | `0x25c70` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1fec` | `0x1ff6` | **`+0xa`** |

### Other Changes

```diff

-757.0.0.0.0
+761.0.1.0.0
Functions:
~ _hdi_copy_mounted : 1816 -> 1832
CStrings:
+ "761.0.1"
+ "@(#)VERSION:Darwin Cryptex Interface Version 2.0.0: Fri Jun 26 22:05:14 PDT 2026; root:libcryptex-761.0.1~16/libcryptex/RELEASE_ARM64E"
+ "Darwin Cryptex Interface Version 2.0.0: Fri Jun 26 22:05:14 PDT 2026; root:libcryptex-761.0.1~16/libcryptex/RELEASE_ARM64E"
- "757"
- "@(#)VERSION:Darwin Cryptex Interface Version 2.0.0: Sat Jun 13 08:36:15 PDT 2026; root:libcryptex-757~412/libcryptex/RELEASE_ARM64E"
- "Darwin Cryptex Interface Version 2.0.0: Sat Jun 13 08:36:15 PDT 2026; root:libcryptex-757~412/libcryptex/RELEASE_ARM64E"
```
