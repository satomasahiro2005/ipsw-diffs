## MTLAssetUpgraderD

> `/usr/libexec/MTLAssetUpgraderD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x183a4` | `0x18418` | **`+0x74`** |
| `__TEXT.__oslogstring` | `0xacf` | `0xb14` | **`+0x45`** |
| `__DATA_CONST.__cfstring` | `0x1c0` | `0x1e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x924` | `0x92f` | **`+0xb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-381.0.0.0.0
+382.4.0.0.0

-  Functions: 350
-  Symbols:   634
-  CStrings:  204
+  Functions: 348
+  Symbols:   633
+  CStrings:  206
Symbols:
- _OUTLINED_FUNCTION_10
CStrings:
+ "<no error>"
+ "addRecompilationWork: failed to get dynamic library type of '%s'"
+ "recompilation: serialization of dynamic library %@ failed: %@"
- "recompilation: serialization of dynamic library %@ failed"
```
