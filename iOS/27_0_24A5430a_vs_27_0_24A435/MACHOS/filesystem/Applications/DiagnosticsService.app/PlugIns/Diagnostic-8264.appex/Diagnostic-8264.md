## Diagnostic-8264

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8264.appex/Diagnostic-8264`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c18` | `0x4eac` | **`+0x294`** |
| `__TEXT.__objc_stubs` | `0xfc0` | `0x10a0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x896` | `0x92e` | **`+0x98`** |
| `__TEXT.__objc_methname` | `0xf0d` | `0xf71` | **`+0x64`** |
| `__DATA.__objc_selrefs` | `0x500` | `0x530` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x940` | `0x960` | **`+0x20`** |
| `__TEXT.__cstring` | `0x877` | `0x884` | **`+0xd`** |
| `__TEXT.__const` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 68
+  Functions: 70

-  CStrings:  379
+  CStrings:  389
CStrings:
+ "BatteryIndex"
+ "Failed to retrieve native battery index, or no battery index populated by T200."
+ "Per-pack error[%d]: %ld, Domain: %@, Description: %@"
+ "Raw T200 error: %@"
+ "domain"
+ "getFailedBatterySPCs"
+ "integerValue"
+ "localizedDescription"
+ "populateInternalError:error:"
+ "userInfo"
```
