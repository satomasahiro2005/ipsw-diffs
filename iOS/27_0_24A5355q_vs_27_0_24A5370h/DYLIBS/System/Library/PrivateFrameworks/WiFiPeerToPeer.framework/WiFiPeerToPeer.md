## WiFiPeerToPeer

> `/System/Library/PrivateFrameworks/WiFiPeerToPeer.framework/WiFiPeerToPeer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x8661` | `0x869c` | **`+0x3b`** |
| `__AUTH_CONST.__cfstring` | `0x6a60` | `0x6a80` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xf38` | `0xf48` | **`+0x10`** |
| `__TEXT.__text` | `0x3d458` | `0x3d44c` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x320` | `0x328` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2228` | `0x2230` | **`+0x8`** |

### Other Changes

```diff

-885.62.0.0.0
+885.66.4.1.0

-  Symbols:   3391
-  CStrings:  1081
+  Symbols:   3392
+  CStrings:  1082
Symbols:
+ -[WiFiAwarePKBootstrappingRecords initWithExpiration:bootstrappingRecords:]
+ _NSCocoaErrorDomain
- -[WiFiAwarePKBootstrappingRecords initWithexpiration:bootstrappingRecords:]
CStrings:
+ "WiFiAwarePKBootstrappingRecords: Missing required field(s)"
```
