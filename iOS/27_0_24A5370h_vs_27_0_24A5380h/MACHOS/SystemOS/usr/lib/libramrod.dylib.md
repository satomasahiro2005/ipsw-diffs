## libramrod.dylib

> `/usr/lib/libramrod.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x94f98` | `0x79100` | **`-0x1be98`** |
| `__TEXT.__text` | `0xeeef4` | `0xeec34` | **`-0x2c0`** |
| `__TEXT.__cstring` | `0x2bbc9` | `0x2bb6f` | **`-0x5a`** |
| `__AUTH_CONST.__cfstring` | `0xc380` | `0xc3a0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xada` | `0xac8` | **`-0x12`** |
| `__TEXT.__unwind_info` | `0x1e80` | `0x1e88` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA.__objc_classrefs`
- `__DATA.__objc_superrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3695.0.0.0.0
+3696.0.3.0.1

-  Functions: 2863
+  Functions: 2860

-  CStrings:  6357
+  CStrings:  6356
Symbols:
+ _initializeIOServiceConnectionWithNameAndType
- _initializeIOServiceConnectionWithName
CStrings:
+ "-dy"
+ "-dyM"
+ "J126"
+ "libCyrusFDR unit_is_j126 = %{public}d"
+ "libCyrusFDR: unit_is_j126 %d%s"
+ "libCyrusFDR: unit_is_j126 returned %d%s"
- "-dyo"
- "-dyoM"
- "failed to get UniqueChipID"
- "failed to query UniqueChipID"
- "libCyrusFDR: entered libCyrusFDR unit_has_missealed_ocelot%s"
- "libCyrusFDR: found ecid in missealed ocelots %d%s"
- "libCyrusFDR: unit_has_missealed_ocelot returned %d%s"
```
