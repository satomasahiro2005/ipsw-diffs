## Diagnostic-4009

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-4009.appex/Diagnostic-4009`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75ec` | `0x77c8` | **`+0x1dc`** |
| `__TEXT.__oslogstring` | `0x331` | `0x46c` | **`+0x13b`** |
| `__TEXT.__cstring` | `0xb18` | `0xac1` | **`-0x57`** |
| `__DATA.__data` | `0x308` | `0x2e0` | **`-0x28`** |
| `__TEXT.__objc_methname` | `0x1adf` | `0x1abf` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x1840` | `0x1820` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x760` | `0x750` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0xd64` | `0xd5c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1374.0.5.0.0
+1374.0.27.0.0

-  Functions: 246
+  Functions: 245

-  CStrings:  567
+  CStrings:  569
CStrings:
+ "Device does not have Exclaves. Skipping stat capture."
+ "Display pipe stats captured"
+ "Exclaves is not supported, skipping status."
+ "Exclaves is supported."
+ "Platform has display pipe stats, preparing to capture"
+ "Retrieving display pipe stats..."
+ "Returning %lu stats for display pipe client"
+ "Starting display pipe stat capture"
- "/usr/local/bin/h10isp"
- "/usr/local/bin/h13isp"
- "/usr/local/bin/h16isp"
- "/usr/local/bin/h9isp"
- "ispBinary"
- "stringWithUTF8String:"
```
