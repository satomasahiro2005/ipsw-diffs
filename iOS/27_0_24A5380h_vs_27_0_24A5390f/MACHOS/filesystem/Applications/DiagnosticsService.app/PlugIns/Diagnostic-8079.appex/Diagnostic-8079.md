## Diagnostic-8079

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8079.appex/Diagnostic-8079`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8944` | `0x8b58` | **`+0x214`** |
| `__TEXT.__oslogstring` | `0xabc` | `0xbf7` | **`+0x13b`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1374.0.5.0.0
+1374.0.27.0.0

-  CStrings:  692
+  CStrings:  700
Functions:
~ sub_1000085ac : 280 -> 400
~ sub_100008b2c -> sub_100008ba4 : 756 -> 848
~ sub_100008e20 -> sub_100008ef4 : 156 -> 228
~ sub_100008ec4 -> sub_100008fe0 : 472 -> 592
~ sub_10000909c -> sub_100009230 : 180 -> 308
CStrings:
+ "Device does not have Exclaves. Skipping stat capture."
+ "Display pipe stats captured"
+ "Exclaves is not supported, skipping status."
+ "Exclaves is supported."
+ "Platform has display pipe stats, preparing to capture"
+ "Retrieving display pipe stats..."
+ "Returning %lu stats for display pipe client"
+ "Starting display pipe stat capture"
```
