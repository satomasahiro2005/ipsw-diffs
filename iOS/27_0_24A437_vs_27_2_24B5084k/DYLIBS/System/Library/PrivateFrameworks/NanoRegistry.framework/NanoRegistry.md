## NanoRegistry

> `/System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5483c` | `0x54ca8` | **`+0x46c`** |
| `__TEXT.__cstring` | `0x4159` | `0x41ed` | **`+0x94`** |
| `__AUTH_CONST.__cfstring` | `0x4ae0` | `0x4b40` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x6d70` | `0x6dd0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x4a64` | `0x4a8c` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e08` | `0x1e18` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x36c` | `0x374` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1978` | `0x1980` | **`+0x8`** |

### Other Changes

```diff

-1075.1.4.0.0
+1075.11.0.0.0

-  Functions: 2085
-  Symbols:   3621
-  CStrings:  825
+  Functions: 2088
+  Symbols:   3626
+  CStrings:  828
Symbols:
+ -[NRWatchPairingExtendedMetadata setSupportsSecurePairing:]
+ -[NRWatchPairingExtendedMetadata supportsSecurePairing]
+ -[WatchSetupExtendedMetadata initWithPairingVersion:productVersionMajor:productVersionMinor:postFailSafeObliteration:encodedSystemVersion:supportsSecurePairing:]
+ -[WatchSetupExtendedMetadata supportsSecurePairing]
+ _OBJC_IVAR_$_NRWatchPairingExtendedMetadata._supportsSecurePairing
+ _OBJC_IVAR_$_WatchSetupExtendedMetadata._supportsSecurePairing
- -[WatchSetupExtendedMetadata initWithPairingVersion:productVersionMajor:productVersionMinor:postFailSafeObliteration:encodedSystemVersion:]
CStrings:
+ "F47B90E6-F2D5-49D0-A8F2-C880AA3FED19"
+ "com.apple.nanoregistry.F47B90E6-F2D5-49D0-A8F2-C880AA3FED19"
+ "supportsSecurePairing"
+ "{ chipID = %ld pairingVersion = %ld productType = \"%@\" postFailsafeObliteration = \"%s\" isCellularEnabled = \"%s\" encodedSystemVersion = \"%ld\" supportsSecurePairing = \"%s\" }"
- "{ chipID = %ld pairingVersion = %ld productType = \"%@\" postFailsafeObliteration = \"%s\" isCellularEnabled = \"%s\" encodedSystemVersion = \"%ld\" }"
```
