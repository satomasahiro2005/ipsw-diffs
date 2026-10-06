## com.apple.driver.ASIOKit

> `com.apple.driver.ASIOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x3d0ac` | `0x50b48` | **`+0x13a9c`** |
| `__TEXT.__const` | `0x8580` | `0x91d0` | **`+0xc50`** |
| `__DATA_CONST.__const` | `0x2be8` | `0x34c0` | **`+0x8d8`** |
| `__TEXT.__cstring` | `0x261` | `0xd2` | **`-0x18f`** |
| `__TEXT_EXEC.__auth_stubs` | `0x210` | `0x1f0` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x108` | `0xf8` | **`-0x10`** |

### Other Changes

```diff

-27.2.2.0.0
+27.2.6.0.0

-  CStrings:  18
+  CStrings:  11
CStrings:
+ "1211111212221212111"
- "1.2.840.113635.100.10.1"
- "1.2.840.113635.100.8.3"
- "1.2.840.113635.100.8.4"
- "1.2.840.113635.100.8.5"
- "1.2.840.113635.100.8.6"
- "1.2.840.113635.100.8.7"
- "121111121222121211"
- "{\"kMAOptionsBAAValidity\": 525600, \"kMAOptionsBAAOIDSToInclude\": [\"1.2.840.113635.100.10.1\", \"1.2.840.113635.100.8.3\", \"1.2.840.113635.100.8.4\", \"1.2.840.113635.100.8.5\", \"1.2.840.113635.100.8.6\", \"1.2.840.113635.100.8.7\"], \"kMAOptionsBAASCRTAttestation\": true}"
```
