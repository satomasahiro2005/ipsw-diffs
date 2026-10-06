## Diagnostic-8389

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8389.appex/Diagnostic-8389`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dc9c` | `0x1deb0` | **`+0x214`** |
| `__TEXT.__oslogstring` | `0x54` | `0x18f` | **`+0x13b`** |
| `__TEXT.__objc_stubs` | `0xb00` | `0xb20` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xf70` | `0xf80` | **`+0x10`** |
| `__TEXT.__const` | `0x36d0` | `0x36e0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4e8` | `0x4f0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x7c0` | `0x7c8` | **`+0x8`** |

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
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
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

-  Symbols:   196
-  CStrings:  438
+  Symbols:   197
+  CStrings:  447
Symbols:
+ __os_log_impl
Functions:
~ sub_100001920 : 280 -> 400
~ sub_100001ea0 -> sub_100001f18 : 756 -> 848
~ sub_100002194 -> sub_100002268 : 156 -> 228
~ sub_100002238 -> sub_100002354 : 472 -> 592
~ sub_100002410 -> sub_1000025a4 : 180 -> 308
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
