## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x2bc220` | `0x3aede0` | **`+0xf2bc0`** |
| `__TEXT.__text` | `0x7c9c4` | `0x7c5e8` | **`-0x3dc`** |
| `__TEXT.__cstring` | `0x74e0` | `0x75df` | **`+0xff`** |
| `__DATA_CONST.__cfstring` | `0x29c0` | `0x2a60` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x1ef0` | `0x1ee0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1248` | `0x1238` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x18bc` | `0x18c8` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0xf88` | `0xf80` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xc78` | `0xc80` | **`+0x8`** |
| `__TEXT.__const` | `0x2c10` | `0x2c08` | **`-0x8`** |
| `__DATA.__bss` | `0x79` | `0x80` | **`+0x7`** |
| `__TEXT.__oslogstring` | `0x5ecc` | `0x5ecb` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-20.47.7.0.0
+20.50.6.0.0

-  CStrings:  1826
+  CStrings:  1829
Symbols:
+ _kFigCaptureStreamMetadata_AEMotionCompensationIntegrationTimeDelta
+ _kFigCaptureStreamMetadata_FlashAmbientLuxLevel
+ _kFigCaptureStreamMetadata_FlashAmbientLuxLevelHigh
+ _kFigCaptureStreamMetadata_FlashAmbientLuxLevelLow
+ _kFigCaptureStreamMetadata_ImageRegistrationInfo
+ _kFigCaptureStreamMetadata_InputSignals
+ _kFigCaptureStreamMetadata_Signals
- _kFigCaptureStreamMetadata_TimeSHActualFrameRate
- _kFigCaptureStreamMetadata_TimeSHDecimationLevel
- _kFigCaptureStreamMetadata_TimeSHDecimationTag
- _kFigCaptureStreamMetadata_TimeSHDesiredFrameRate
- _kFigCaptureStreamMetadata_TimeSHSequenceNumber
- _kFigCaptureStreamMetadata_TimeSHShouldSkipFrame
- _perror
CStrings:
+ "\tCouldn't read %s: %s"
+ "\tCouldn't write %s: %s"
+ "\tUnexpected local cache size (expected: %ld, found: %ld)"
+ "\tUnexpected written size (expected: %ld, written %ld)"
+ "(Bin) Loading ISPCPU firmware file: %s\n"
+ "/usr/local/share/firmware/isp/2426_02XX.dat"
+ "/usr/local/share/firmware/isp/4127_01XX.dat"
+ "/usr/local/share/firmware/isp/8227_01XX.dat"
+ "/usr/local/share/firmware/isp/9726_01XX.dat"
+ "20.50.6"
+ "ABDNet_NoiseAddback_Private"
+ "Bin ISPCPU firmwareFile does not exist %s\n\n"
+ "Filtered points outside radius %f IR px. %d remaining out of %d points.\n"
- "%s - fatpMode=%d\n"
- "(Bin) Using ISPCPU firmware override file\n"
- "20.47.7"
- "GMC_Interface.cpp"
- "Load firmware from %s\n\n"
- "Num of points after filter: %d\n"
- "Unknown or Invalid Projector type, skipping Params init!!!"
- "error loading ISPCPU firmware "
- "initParamsFromCalib"
- "runGmcOnGmsPoints"
```
