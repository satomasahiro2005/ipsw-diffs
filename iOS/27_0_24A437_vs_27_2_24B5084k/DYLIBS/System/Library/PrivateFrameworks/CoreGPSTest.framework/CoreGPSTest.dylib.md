## CoreGPSTest.dylib

> `/System/Library/PrivateFrameworks/CoreGPSTest.framework/CoreGPSTest.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66e6c` | `0x66dac` | **`-0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x3988` | `0x3974` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0xbb8` | `0xbb0` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0xaa72` | `0xaa6e` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-365.0.9.0.1
+367.0.1.0.0

-  Symbols:   4320
+  Symbols:   4318
Symbols:
+ __ZN11NmeaLogging13NmeaExtractor4feedEPKhm
- __ZN11NmeaLogging13NmeaExtractor4feedERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE
- __ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE4findEcm
- __ZNKSt3__114default_deleteIN11NmeaLogging13NmeaExtractorEEclB9fqe220106EPS2_
Functions:
~ __ZN21GnssIndicationHandler4sendERKN4gnss15MeasurementDataE : 996 -> 988
~ __ZN12VendorLoggerC2ERKNS_6ConfigE : 2196 -> 2112
~ __ZN12VendorLoggerD2Ev : 516 -> 500
~ __ZN12VendorLogger7restartEv : 68 -> 28
~ ____ZN12VendorLogger3logEONSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE_block_invoke : 164 -> 132
~ __ZN11NmeaLogging13NmeaExtractor4feedERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE -> __ZN11NmeaLogging13NmeaExtractor4feedEPKhm : 348 -> 320
~ __ZN4cCLP8LogEntry11PrivateData6cpbHalERKNS1_6SvInfoERKNSt3__16vectorIhNS5_9allocatorIhEEEERN4gnss6SvInfoE : 1120 -> 1128
~ __ZN4cCLP8LogEntry11PrivateData6cpbHalERKN4gnss6SvInfoERNS1_6SvInfoERNSt3__16vectorIhNS8_9allocatorIhEEEE : 228 -> 236
CStrings:
+ "#version,CoreGPS-367.0.1,machContSec,%{public}.3f,BuildTime,{Sep  9 2026,20:53:27}"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/include/google/protobuf/repeated_field.h"
+ "20:53:24"
+ "20:56:26"
+ "Sep  9 2026"
- "#version,CoreGPS-365.0.9.0.1,machContSec,%{public}.3f,BuildTime,{Aug 13 2026,21:42:35}"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/google/protobuf/repeated_field.h"
- "21:42:30"
- "21:46:23"
- "Aug 13 2026"
```
