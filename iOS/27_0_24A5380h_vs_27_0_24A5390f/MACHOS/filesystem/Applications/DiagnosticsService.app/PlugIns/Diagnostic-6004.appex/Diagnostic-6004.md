## Diagnostic-6004

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6004.appex/Diagnostic-6004`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14674` | `0x14888` | **`+0x214`** |
| `__TEXT.__oslogstring` | `0xfe` | `0x22e` | **`+0x130`** |
| `__TEXT.__objc_stubs` | `0xdc0` | `0xde0` | **`+0x20`** |
| `__TEXT.__const` | `0xb88` | `0xb98` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x500` | `0x508` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1374.0.5.0.0
+1374.0.27.0.0

-  CStrings:  376
+  CStrings:  385
Functions:
~ sub_100001c18 : 280 -> 400
~ sub_100002198 -> sub_100002210 : 756 -> 848
~ sub_10000248c -> sub_100002560 : 156 -> 228
~ sub_100002530 -> sub_10000264c : 472 -> 592
~ sub_100002708 -> sub_10000289c : 180 -> 308
CStrings:
+ "Device does not have Exclaves. Skipping stat capture."
+ "Display pipe stats captured"
+ "Exclaves is not supported, skipping status."
+ "Exclaves is supported."
+ "Platform has display pipe stats, preparing to capture"
+ "Retrieving display pipe stats..."
+ "Returning %lu stats for display pipe client"
+ "Starting display pipe stat capture"
+ "count"
```
