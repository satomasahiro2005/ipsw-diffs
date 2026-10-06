## remoteappintentsd

> `/usr/libexec/remoteappintentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73a58` | `0x744f4` | **`+0xa9c`** |
| `__TEXT.__oslogstring` | `0x1bca` | `0x1d8a` | **`+0x1c0`** |
| `__DATA.__data` | `0x2278` | `0x2258` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x7c8` | `0x7d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-41.0.45.0.0
+41.0.50.0.0

-  Functions: 2654
-  Symbols:   1100
-  CStrings:  562
+  Functions: 2663
+  Symbols:   1101
+  CStrings:  566
Symbols:
+ _$s18AppIntentsServices0bC0O10DeviceTypeO7unknownyA2EmFWC
CStrings:
+ "%sAllowing request: peer device type is unknown (model: %{public}s) but no MDM restrictions are active."
+ "%sDenying request: peer device type is unknown (model: %{public}s) and home device pairing is disabled by MDM."
+ "%sDenying request: peer device type is unknown (model: %{public}s) and paired watch connection is disabled by MDM."
+ "%sResolved peer device type %{public}s from Networking device model \"%{public}s\"."
```
