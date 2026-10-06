## MobileSMS

> `/private/var/staged_system_apps/MobileSMS.app/MobileSMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c408` | `0x1c6ac` | **`+0x2a4`** |
| `__TEXT.__oslogstring` | `0xd42` | `0xe06` | **`+0xc4`** |
| `__TEXT.__objc_stubs` | `0x3ee0` | `0x3f60` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x4e94` | `0x4eec` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x474` | `0x4c0` | **`+0x4c`** |
| `__DATA.__objc_selrefs` | `0x1528` | `0x1548` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x780` | `0x798` | **`+0x18`** |
| `__TEXT.__cstring` | `0x237c` | `0x238e` | **`+0x12`** |
| `__TEXT.__const` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x538` | `0x540` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xf4c` | `0xf54` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 515
+  Functions: 517

-  CStrings:  1310
+  CStrings:  1319
Functions:
~ sub_100012a98 : 228 -> 348
+ sub_100012bfc
+ sub_10001d7d0
CStrings:
+ "Autocomplete test"
+ "Contact store is missing analyzeDatabaseWithError:. Store: %@"
+ "Performed pre-test contacts DB analysis: %{BOOL}d"
+ "Pre-test ANALYZE completed in %.3fs"
+ "Pre-test ANALYZE failed after %.3fs: %{public}@"
+ "_runFTSAnalyzeBeforeAutocompleteTest"
+ "analyzeDatabaseWithError:"
+ "now"
+ "timeIntervalSinceNow"
```
