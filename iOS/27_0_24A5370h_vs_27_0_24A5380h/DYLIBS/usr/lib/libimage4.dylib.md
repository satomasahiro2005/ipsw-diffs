## libimage4.dylib

> `/usr/lib/libimage4.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bc40` | `0x2bc20` | **`-0x20`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ _decompressECPublicKey : 424 -> 416
~ _CTGetICDPFederationType : 316 -> 288
~ _X509ChainCheckPathWithOptions : 1580 -> 1584
CStrings:
+ "@(#)VERSION:Darwin Image4 Library Version 7.0.0: Fri Jun 26 22:05:08 PDT 2026; root:AppleImage4_libraries-374~2957/libimage4/RELEASE_ARM64E"
+ "Darwin Image4 Library Version 7.0.0: Fri Jun 26 22:05:08 PDT 2026; root:AppleImage4_libraries-374~2957/libimage4/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Image4 Library Version 7.0.0: Mon Jun 15 23:47:29 PDT 2026; root:AppleImage4_libraries-374~2133/libimage4/RELEASE_ARM64E"
- "Darwin Image4 Library Version 7.0.0: Mon Jun 15 23:47:29 PDT 2026; root:AppleImage4_libraries-374~2133/libimage4/RELEASE_ARM64E"
```
