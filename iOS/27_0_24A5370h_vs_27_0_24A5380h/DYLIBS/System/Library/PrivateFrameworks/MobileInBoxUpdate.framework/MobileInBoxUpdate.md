## MobileInBoxUpdate

> `/System/Library/PrivateFrameworks/MobileInBoxUpdate.framework/MobileInBoxUpdate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x332e4` | `0x332bc` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1d40` | `0x1d60` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x4418` | `0x4420` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xf40` | `0xf38` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xae0` | `0xae8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-266.0.0.0.0
+274.0.0.0.0

-  Symbols:   1917
-  CStrings:  492
+  Symbols:   1918
+  CStrings:  493
Symbols:
+ _kMIBUClientPersonalizationLanguageKey
Functions:
~ -[MIBUNFCCommand _initWithAPDU:] : 1176 -> 1172
~ _decompressECPublicKey : 424 -> 416
~ _CTGetICDPFederationType : 316 -> 288
~ _X509ChainCheckPathWithOptions : 1580 -> 1584
~ -[MIBUDeserializer _deserializeNextTag:withData:] : 1132 -> 1128
CStrings:
+ "language"
+ "name"
- "PersonalizationName"
```
