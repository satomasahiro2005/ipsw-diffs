## DriverKit

> `/System/Library/Frameworks/DriverKit.framework/DriverKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37d34` | `0x37dc4` | **`+0x90`** |

### Other Changes

```text
Functions:
~ __Z21OSUnserializeXMLparsePv : 3952 -> 4072
~ _OSCreateObjectFromSerialization : 2196 -> 2200
~ __ZL29OSCollectionEntryGetStringPtrP15OSSerialization17OSCollectionEntry : 124 -> 128
~ __ZL31OSCollectionEntryGetUInt64ValueP15OSSerialization17OSCollectionEntry : 108 -> 112
~ ____ZL20OSDictionaryGetEntryP12OSDictionaryP8OSObjectPKcPm_block_invoke : 364 -> 368
~ __ZN16IOReporter_IVars19updateReportChannelEiRjRPhRm : 224 -> 228
~ __ZN25IOHistogramReporter_IVarsC2EP9IOService19IOReportChannelTypeyPK8OSStringtyiP24IOHistogramSegmentConfig : 904 -> 908
```
