## ReportMemoryException

> `/usr/libexec/ReportMemoryException`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93c4` | `0x93ac` | **`-0x18`** |

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

-356.0.0.0.0
+358.0.0.0.0
Functions:
~ _mergePrefsFromInput : 2176 -> 2168
~ _RMEGetTimeOrderedLogPathsMatchingPrefs : 1124 -> 1116
~ _mergePrefsFromInputProcessList : 444 -> 440
~ _deleteOldGcoreFiles : 856 -> 852
```
