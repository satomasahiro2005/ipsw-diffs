## libramrod.dylib

> `/usr/lib/libramrod.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf0a70` | `0xf0530` | **`-0x540`** |
| `__TEXT.__cstring` | `0x2be81` | `0x2beef` | **`+0x6e`** |
| `__AUTH_CONST.__cfstring` | `0xc480` | `0xc4c0` | **`+0x40`** |
| `__TEXT.__const` | `0x79110` | `0x79130` | **`+0x20`** |
| `__DATA.__bss` | `0x948` | `0x960` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x2b40` | `0x2b50` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x15a8` | `0x15b0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1eb0` | `0x1eb8` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA.__objc_classrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3696.0.12.0.3
+3696.40.10.0.0

-  Functions: 2871
-  Symbols:   1892
-  CStrings:  6386
+  Functions: 2874
+  Symbols:   1896
+  CStrings:  6388
Symbols:
+ _kImg4TagStr_srvc
+ _ramrod_manifest_tag_is_valid
+ _ramrod_manifest_tag_is_valid_string
+ _strnlen
CStrings:
+ "%s: %s: FUD image at index %ld is not a well-formed firmware tag"
+ "%s: %s: unable to determine the preboot path"
```
