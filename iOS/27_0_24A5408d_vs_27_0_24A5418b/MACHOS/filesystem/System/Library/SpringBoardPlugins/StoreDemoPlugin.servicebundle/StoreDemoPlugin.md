## StoreDemoPlugin

> `/System/Library/SpringBoardPlugins/StoreDemoPlugin.servicebundle/StoreDemoPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb968` | `0xb988` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1446` | `0x1464` | **`+0x1e`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1871.0.51.0.0
+1871.2.1.0.0
Functions:
~ sub_7efc : 808 -> 840
CStrings:
+ "StoreDemo plugin: launching screen saver! isPad=%{bool}d hasSD=%{bool}d"
- "StoreDemo plugin: launching screen saver."
```
