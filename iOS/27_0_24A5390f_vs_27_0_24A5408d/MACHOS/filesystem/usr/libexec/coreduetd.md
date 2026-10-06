## coreduetd

> `/usr/libexec/coreduetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21224` | `0x21494` | **`+0x270`** |
| `__TEXT.__oslogstring` | `0x371d` | `0x377a` | **`+0x5d`** |
| `__TEXT.__objc_methname` | `0x65ae` | `0x6609` | **`+0x5b`** |
| `__TEXT.__objc_stubs` | `0x52a0` | `0x52e0` | **`+0x40`** |
| `__DATA.__objc_const` | `0x2508` | `0x2528` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1a18` | `0x1a38` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x17e0` | `0x17f0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x828` | `0x830` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a0` | `0x1a4` | **`+0x4`** |
| `__TEXT.__cstring` | `0x1c85` | `0x1c86` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-1967.0.0.0.0
+1971.0.0.0.0

-  Functions: 670
+  Functions: 674

-  CStrings:  1776
+  CStrings:  1780
CStrings:
+ "CDDCommunicator: nearby re-poll computed defaultPaired nearby count = %lu (from %lu devices)"
+ "_nearbyRepollTimer"
+ "b"
+ "nearbyPairedDeviceCountForDevices:"
+ "repollNearbyPairedDevices"
+ "startNearbyRepollTimer"
- "R"
- "isConnected"
```
