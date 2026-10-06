## libRoseUpdater.dylib

> `/usr/lib/updaters/libRoseUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ed08` | `0x1ee50` | **`+0x148`** |
| `__TEXT.__gcc_except_tab` | `0x1410` | `0x1418` | **`+0x8`** |
| `__TEXT.__cstring` | `0x485d` | `0x4862` | **`+0x5`** |

### Other Changes

```diff

-  CStrings:  512
+  CStrings:  513
Functions:
~ __ZN16RoseCapabilities41supportedFDRDataClassesForCalibrationTypeENS_15CalibrationTypeE : 500 -> 608
~ ____ZN13RoseTargetMap13getRoseTargetEv_block_invoke : 1520 -> 1736
~ __ZNSt3__13mapIPK10__CFStringNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_4lessIS3_EENS7_INS_4pairIKS3_S9_EEEEEC2B9nqe220106ESt16initializer_listISE_ERKSB_ : 84 -> 88
CStrings:
+ "UwbB"
```
