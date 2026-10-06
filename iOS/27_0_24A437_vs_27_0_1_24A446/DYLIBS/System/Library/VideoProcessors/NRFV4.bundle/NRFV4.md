## NRFV4

> `/System/Library/VideoProcessors/NRFV4.bundle/NRFV4`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x36baa` | `0x36bfa` | **`+0x50`** |
| `__TEXT.__text` | `0x27c54c` | `0x27c598` | **`+0x4c`** |

### Other Changes

```diff

-764.22.13.0.0
+764.22.14.0.0

-  CStrings:  8999
+  CStrings:  9000
Functions:
~ _generatePDPGainsFromInputFrameMetadata : 4832 -> 4908
CStrings:
+ "( sensorSizeInBayerPixels.width > 0 ) && ( sensorSizeInBayerPixels.height > 0 )"
```
