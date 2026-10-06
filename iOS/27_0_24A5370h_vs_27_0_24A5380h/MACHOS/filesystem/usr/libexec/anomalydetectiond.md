## anomalydetectiond

> `/usr/libexec/anomalydetectiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36b4ac` | `0x36d0e4` | **`+0x1c38`** |
| `__DATA_CONST.__const` | `0x27450` | `0x27530` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x11809` | `0x118e6` | **`+0xdd`** |
| `__TEXT.__cstring` | `0x1c836` | `0x1c8dd` | **`+0xa7`** |
| `__TEXT.__auth_stubs` | `0x18c0` | `0x1840` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0xc730` | `0xc7a8` | **`+0x78`** |
| `__DATA_CONST.__got` | `0x608` | `0x678` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0xc78` | `0xc38` | **`-0x40`** |
| `__TEXT.__const` | `0xfaae` | `0xfaee` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x10438` | `0x10470` | **`+0x38`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-164.0.0.0.0
+166.0.0.0.0

-  Functions: 17112
-  Symbols:   616
-  CStrings:  9325
+  Functions: 17147
+  Symbols:   608
+  CStrings:  9341
Symbols:
- __ZN6motion19AnomalyFMEmbeddings7predictERKNSt3__13mapINS1_12basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEENS_2fm9ArrayDataENS1_4lessIS8_EENS6_INS1_4pairIKS8_SA_EEEEEENS1_8functionIFvNS1_10shared_ptrIKNS9_16PredictionResultEEEEEE
- __ZN6motion19AnomalyFMEmbeddingsC1EPU28objcproto17OS_dispatch_queue8NSObject
- __ZNSt3__118condition_variable10notify_oneEv
- __ZNSt3__118condition_variable4waitERNS_11unique_lockINS_5mutexEEE
- __ZNSt3__118condition_variableD1Ev
- __ZNSt3__15mutex4lockEv
- __ZNSt3__15mutex6unlockEv
- __ZNSt3__15mutexD1Ev
CStrings:
+ "AnomalyFM_adaptor"
+ "[%s] Error encountered when running adaptor: %s"
+ "[%s] adaptor timed out"
+ "[%s] base model timed out"
+ "[%s] dump adaptor input: [%s]"
+ "[%s] dump base model input: [%s]"
+ "[%s] response_arrays size: %zu"
+ "accelBias0"
+ "accelBias1"
+ "buttonPress"
+ "ch < kColsInBaseModel"
+ "com.apple.fm.coremotion.anomalyfm.sideload.adapter"
+ "com.apple.fm.coremotion.anomalyfm.sideload.base"
+ "deltaPositionAltimeterZ"
+ "down"
+ "dumpBaseModelRow"
+ "invalid channel"
+ "usage"
+ "usagePage"
+ "yOffset"
+ "{\"msg%{public}.0s\":\"invalid channel\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
- "[%s] Error encountered when running transit model %s"
- "[%s] dump adapter input': [%s]"
- "[%s] result_arrays size: %zu"
- "com.apple.fm.coremotion.anomalyfm"
- "com.apple.fm.coremotion.anomalyfm.adaptor"
```
