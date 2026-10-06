## MFAAuthentication

> `/System/Library/PrivateFrameworks/MFAAuthentication.framework/MFAAuthentication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x424d4` | `0x4263c` | **`+0x168`** |
| `__AUTH_CONST.__cfstring` | `0x1b20` | `0x1b40` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1a90` | `0x1aa8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x5268` | `0x5278` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Functions: 849
-  Symbols:   1841
-  CStrings:  717
+  Functions: 850
+  Symbols:   1844
+  CStrings:  718
Symbols:
+ -[MFAACertificateManager createNoAuthICNonce:withChallenge:]
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _CTParseLeafSPKI
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
- -[MFAACertificateManager createVeridianNonce:withChallenge:]
CStrings:
+ "PretendWirelessCTAMatch"
+ "createNoAuthICNonce: %@ + %@ -> %@ -> %@"
- "createVeridianNonce: %@ + %@ -> %@ -> %@"
```
