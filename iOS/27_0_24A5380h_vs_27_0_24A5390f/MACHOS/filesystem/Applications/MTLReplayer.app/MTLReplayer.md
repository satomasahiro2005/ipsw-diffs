## MTLReplayer

> `/Applications/MTLReplayer.app/MTLReplayer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x968` | `0x940` | **`-0x28`** |
| `__TEXT.__cstring` | `0x182e` | `0x180b` | **`-0x23`** |
| `__TEXT.__text` | `0xa1c8` | `0xa1ac` | **`-0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.0.33.0.0
+2027.0.35.0.0

-  CStrings:  590
+  CStrings:  588
Functions:
~ sub_100001578 : 1796 -> 1772
~ sub_10000b160 -> sub_10000b148 : 212 -> 208
CStrings:
- "-collectRawCounters"
- "-testProfiling"
```
