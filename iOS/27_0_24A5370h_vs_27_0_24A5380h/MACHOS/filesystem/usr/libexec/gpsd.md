## gpsd

> `/usr/libexec/gpsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16ee08` | `0x16ef08` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x10bd7` | `0x10c19` | **`+0x42`** |
| `__DATA_CONST.__cfstring` | `0x1220` | `0x1240` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x10008` | `0x10028` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x860` | `0x880` | **`+0x20`** |
| `__DATA.__bss` | `0x3b8` | `0x3d0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x8ad0` | `0x8ae8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x8238` | `0x8250` | **`+0x18`** |
| `__TEXT.__cstring` | `0xa640` | `0xa652` | **`+0x12`** |
| `__TEXT.__auth_stubs` | `0x20a0` | `0x20b0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x822` | `0x832` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1068` | `0x1070` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-365.0.5.0.0
+365.0.6.0.0

-  Functions: 9992
-  Symbols:   15381
-  CStrings:  2477
+  Functions: 9993
+  Symbols:   15383
+  CStrings:  2480
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreGPS/install/Symbols/BuiltProducts/libGPSDaemon.a(GpsdClientManager-5a0131e3adc059d69b87924e6e6341a8.o)
+ __ZNK15GpsdPreferences17acLongitudeOffsetEv
+ __ZThn304_N21GpsdGnssDeviceManager13handleRequestERKN5proto4gpsd7RequestE
+ __ZThn304_N21GpsdGnssDeviceManagerD0Ev
+ __ZThn304_N21GpsdGnssDeviceManagerD1Ev
+ ____ZNK15GpsdPreferences17acLongitudeOffsetEv_block_invoke
+ _objc_msgSend$floatValue
+ _objc_opt_isKindOfClass
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreGPS/install/Symbols/BuiltProducts/libGPSDaemon.a(GpsdClientManager-d70f5d96e9af4663fc198895c2234454.o)
- _$s9Tightbeam0A7EncoderVSgWOh
- __ZL9fDefaults
- __ZThn296_N21GpsdGnssDeviceManager13handleRequestERKN5proto4gpsd7RequestE
- __ZThn296_N21GpsdGnssDeviceManagerD0Ev
- __ZThn296_N21GpsdGnssDeviceManagerD1Ev
CStrings:
+ "#gdm,ACLongitudeOffset,applied,%{public}.6f,trackAge,%{public}.3f"
+ "#version,CoreGPS-365.0.6,machContSec,%{public}.3f,BuildTime,{Jun 30 2026,21:07:20}"
+ "21:10:40"
+ "ACLongitudeOffset"
+ "Jun 30 2026"
+ "floatValue"
- "#version,CoreGPS-365.0.5,machContSec,%{public}.3f,BuildTime,{Jun 18 2026,19:48:09}"
- "19:51:04"
- "Jun 18 2026"
```
