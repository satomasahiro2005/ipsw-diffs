## mc_mobile_tunnel

> `/usr/libexec/mc_mobile_tunnel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7098` | `0x7060` | **`-0x38`** |
| `__DATA_CONST.__got` | `0x360` | `0x340` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-113.0.2.0.0
+113.2.5.0.0

-  Symbols:   232
+  Symbols:   228
Symbols:
- _kMDMPRequestTypeAvailableOSUpdates
- _kMDMPRequestTypeOSUpdateStatus
- _kMDMPRequestTypeScheduleOSUpdate
- _kMDMPRequestTypeScheduleOSUpdateScan
Functions:
~ sub_100002ec8 : 904 -> 848
```
