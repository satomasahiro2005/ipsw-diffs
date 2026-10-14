## gpsd

> `/usr/libexec/gpsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x178010` | `0x17807c` | **`+0x6c`** |
| `__TEXT.__oslogstring` | `0x1214f` | `0x12162` | **`+0x13`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-367.0.1.0.0
+367.0.2.0.0

-  CStrings:  2571
+  CStrings:  2572
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreGPS/install/Symbols/BuiltProducts/libGPSDaemon.a(GpsdClientManager-381bc0d6d1d9cb2ddfd738b76d01572f.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreGPS/install/Symbols/BuiltProducts/libGPSDaemon.a(GpsdClientManager-08a6ba2f97614e390e5951ea6af36173.o)
Functions:
~ __ZN7GnssHal12GpioEmbedded12setResetHighEv : 104 -> 212
CStrings:
+ "#gpio,setResetHigh"
+ "#version,CoreGPS-367.0.2,machContSec,%{public}.3f,BuildTime,{Oct 10 2026,01:18:38}"
+ "01:18:35"
+ "01:21:19"
+ "Oct 10 2026"
- "#version,CoreGPS-367.0.1,machContSec,%{public}.3f,BuildTime,{Sep 27 2026,23:16:15}"
- "23:16:12"
- "23:19:36"
- "Sep 27 2026"
```
