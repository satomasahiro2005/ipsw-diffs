## watchpresenced

> `/usr/libexec/watchpresenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6448` | `0x673c` | **`+0x2f4`** |
| `__TEXT.__oslogstring` | `0x7e1` | `0x859` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x1b4` | `0x228` | **`+0x74`** |
| `__DATA_CONST.__const` | `0x438` | `0x410` | **`-0x28`** |
| `__TEXT.__objc_methname` | `0x192c` | `0x194c` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1300` | `0x1320` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x278` | `0x290` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xa14` | `0xa24` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x6c8` | `0x6d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-29.0.0.0.0
+30.0.0.0.0

-  Functions: 176
+  Functions: 181

-  CStrings:  490
+  CStrings:  493
Symbols:
+ _objc_release_x27
- _objc_release_x28
CStrings:
+ "Cannot run discovery mode: watch or CBCentralManager unavailable"
+ "Sharing was interrupted, re-arming on wrist detection..."
+ "Unsupported RSSI window size %d, falling back to 8"
+ "_wristMonitoringWasInterrupted:"
- "SFClient invalidation completed, releasing reference"
```
