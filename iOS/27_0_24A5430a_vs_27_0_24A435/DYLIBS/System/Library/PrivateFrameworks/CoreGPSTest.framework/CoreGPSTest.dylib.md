## CoreGPSTest.dylib

> `/System/Library/PrivateFrameworks/CoreGPSTest.framework/CoreGPSTest.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66ca0` | `0x66e6c` | **`+0x1cc`** |
| `__TEXT.__const` | `0x64c0` | `0x6570` | **`+0xb0`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__oslogstring`

### Other Changes

```diff
Functions:
~ __ZN12MessageQueueIN6cproto4gpsd10IndicationELm16EE4pushERKS2_b : 420 -> 424
~ __ZN17GnssDevicePayload16flushIndicationsEv : 280 -> 284
~ __ZN14GnssByteBufferILm65536EE4tickEy : 292 -> 296
~ __ZN12MessageQueueIN6cproto4gpsd10IndicationELm16EE4tickEy : 180 -> 184
~ __ZN14GnssByteBufferILm65536EE4pushEPKhm : 636 -> 640
~ __ZNSt3__16vectorIN7GnssHal7NvStore4ItemENS_9allocatorIS3_EEE6resizeEm : 352 -> 364
~ __ZNSt3__16vectorIdNS_9allocatorIdEEE6resizeEm : 284 -> 288
~ __ZNSt3__16vectorIP18GpsdSessionHandlerNS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRS2_EEEPS2_DpOT_ : 184 -> 176
~ __ZNSt3__16vectorIN6cproto4gnss9Emergency12GpsEphemerisENS_9allocatorIS4_EEE6resizeEm : 404 -> 408
~ __ZN24GpsdPlatformInfoHardware14detectHardwareEv : 2664 -> 3080
~ __ZN4cCLP8LogEntry11PrivateData6cpbHalERKNS1_20MeasurementExtensionERKNSt3__16vectorIhNS5_9allocatorIhEEEERN4gnss20MeasurementExtensionE : 744 -> 756
CStrings:
+ "#version,CoreGPS-365.0.9.0.1,machContSec,%{public}.3f,BuildTime,{Aug 13 2026,21:42:35}"
+ "21:42:30"
+ "21:46:23"
- "#version,CoreGPS-365.0.9.0.1,machContSec,%{public}.3f,BuildTime,{Aug 13 2026,22:26:38}"
- "22:26:33"
- "22:31:07"
```
