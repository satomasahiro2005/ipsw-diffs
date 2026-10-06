## ReportMemoryException

> `/usr/libexec/ReportMemoryException`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92c0` | `0x9264` | **`-0x5c`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-365.0.0.0.0
+369.0.0.0.0
Functions:
~ ___RMEIsAutoSubmitEnabled_block_invoke : 60 -> 56
~ _RMEGetDefaultLargeExemptedProcesses : 148 -> 100
~ _RMEPopulateDefaultPrefs : 1616 -> 1576
```
