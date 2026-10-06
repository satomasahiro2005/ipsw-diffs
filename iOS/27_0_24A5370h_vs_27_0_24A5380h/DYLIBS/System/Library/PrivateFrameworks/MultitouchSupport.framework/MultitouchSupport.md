## MultitouchSupport

> `/System/Library/PrivateFrameworks/MultitouchSupport.framework/MultitouchSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e660` | `0x1ca58` | **`-0x1c08`** |
| `__TEXT.__unwind_info` | `0x6c0` | `0x690` | **`-0x30`** |
| `__TEXT.__const` | `0x2028` | `0x2008` | **`-0x20`** |
| `__TEXT.__cstring` | `0x16b5` | `0x169d` | **`-0x18`** |

### Other Changes

```diff

-10100.39.0.0.0
+10100.40.0.0.0

-  Functions: 663
-  Symbols:   1005
-  CStrings:  346
+  Functions: 639
+  Symbols:   980
+  CStrings:  345
Symbols:
+ _MTParse_CompactV5BinaryPath
- _MTConvert_CompactHeaderToV2Header
- _MTConvert_CompactV10HeaderToV2Header
- _MTConvert_CompactV3HeaderToV2Header
- _MTConvert_CompactV9HeaderToV2Header
- _MTConvert_V3HeaderToV2Header
- _MTParse_CompactBinaryPath
- _MTParse_CompactV10BinaryPath
- _MTParse_CompactV3orV5BinaryPath
- _MTParse_CompactV9BinaryPath
- _MTParse_HostPathAndImage
- _MTParse_SensorImage
- _MTParse_V3BinaryPathOrImage
- _MTProcess_0xC5_Data
- _MTProcess_0xCC_Data
- __Z23MTCompactV3HeaderUnpackP28MTCompactBinaryFrameHeaderV3Phj
- __Z23MTCompactV9HeaderUnpackP28MTCompactBinaryFrameHeaderV9Phj
- __Z24MTCompactV10HeaderUnpackP29MTCompactBinaryFrameHeaderV10Phj
- __Z25MTParse_SensorImageHeaderPhiP28MTParsedMultitouchFrameRep_tP10__MTDevice
- __Z27MTParse_V3BinaryFrameHeaderPhiP28MTParsedMultitouchFrameRep_tP10__MTDevice
- __Z28MTCompactBinaryContactUnpackP22MTCompactBinaryContactPhj
- __Z30MTCompactV9BinaryContactUnpackP24MTCompactBinaryContactV9Phj
- __Z31MTCompactV10BinaryContactUnpackP25MTCompactBinaryContactV10Phj
- __Z32MTParse_CompactBinaryFrameHeaderPhiP28MTParsedMultitouchFrameRep_tP10__MTDevice
- __Z34MTParse_CompactV3BinaryFrameHeaderP28MTCompactBinaryFrameHeaderV3P28MTParsedMultitouchFrameRep_tP10__MTDevice
- __Z34MTParse_CompactV9BinaryFrameHeaderP28MTCompactBinaryFrameHeaderV9P28MTParsedMultitouchFrameRep_tP10__MTDevice
- __Z35MTParse_CompactV10BinaryFrameHeaderP29MTCompactBinaryFrameHeaderV10P28MTParsedMultitouchFrameRep_tP10__MTDevice
CStrings:
- "Unknown data format %x\n"
```
