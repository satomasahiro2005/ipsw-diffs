## seserviced

> `/usr/libexec/seserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a2fc0` | `0x4a3764` | **`+0x7a4`** |
| `__TEXT.__eh_frame` | `0x16abc` | `0x16bdc` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0xaff8` | `0xb030` | **`+0x38`** |
| `__TEXT.__const` | `0x16310` | `0x16330` | **`+0x20`** |
| `__TEXT.__cstring` | `0x23076` | `0x23096` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x197fd` | `0x197dd` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x5d3c` | `0x5d52` | **`+0x16`** |
| `__DATA.__data` | `0xe904` | `0xe8f4` | **`-0x10`** |
| `__DATA.__common` | `0x840` | `0x838` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-71.8.0.0.0
+71.9.0.0.0

-  Functions: 13504
+  Functions: 13513

-  CStrings:  11722
+  CStrings:  11721
CStrings:
+ "Setting scanning to %{bool}d with low power mode %{bool}d, Uwb available %{bool}d, biolockout backoff %{bool}d, express reader group identifiers %s, adaptive connection rssi threshold %hhd, device stationary %{bool}d, biolock %{bool}d, and geofence entry state %{bool}d"
+ "iOS (27.2) - SecureElementService-71.9"
- "Setting scanning to %{bool}d with low power mode %{bool}d, Uwb suspended %{bool}d, biolockout backoff %{bool}d, express reader group identifiers %s, adaptive connection rssi threshold %hhd, device stationary %{bool}d, biolock %{bool}d, and geofence entry state %{bool}d"
- "iOS (27.2) - SecureElementService-71.8"
- "isAvailable"
```
