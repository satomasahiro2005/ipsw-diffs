## libDetachedCertificates.dylib

> `/usr/lib/libDetachedCertificates.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7244` | `0x7264` | **`+0x20`** |
| `__TEXT.__cstring` | `0x8db` | `0x8e4` | **`+0x9`** |

### Other Changes

```diff

-1166.0.0.0.0
+1171.0.3.0.0

-  Symbols:   170
+  Symbols:   169
Symbols:
- _objc_retain
Functions:
~ -[DetachedCertificatesFile rebuildSKIDMaps] : 908 -> 896
~ +[DetachedCertificatesFile parseFromData:error:] : 2160 -> 2176
~ +[DetachedCertificatesFile parseCertificateEntry:certificate:error:] : 1128 -> 1184
~ -[DetachedCertificatesFile addCertificateChainsWithLeaves:parents:error:] : 2036 -> 2032
~ -[DetachedCertificatesFile mergeWithFile:error:] : 1012 -> 1000
~ -[DetachedCertificatesFile derEncodedSize] : 804 -> 792
CStrings:
+ "Error draining certificate entry fields"
- "Expected OCTET STRING for akid"
```
