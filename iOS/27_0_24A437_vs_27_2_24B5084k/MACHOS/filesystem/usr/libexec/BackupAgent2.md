## BackupAgent2

> `/usr/libexec/BackupAgent2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90d80` | `0x914fc` | **`+0x77c`** |
| `__TEXT.__gcc_except_tab` | `0x210c` | `0x2478` | **`+0x36c`** |
| `__TEXT.__cstring` | `0x1900c` | `0x191dc` | **`+0x1d0`** |
| `__TEXT.__oslogstring` | `0xdfd8` | `0xe1a8` | **`+0x1d0`** |
| `__DATA_CONST.__const` | `0x1438` | `0x1460` | **`+0x28`** |
| `__TEXT.__const` | `0x4c8` | `0x4b8` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1940` | `0x1948` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3039.2.2.0.0
+3039.40.8.0.0

-  Functions: 2458
+  Functions: 2459

-  CStrings:  5765
+  CStrings:  5772
CStrings:
+ "=diag= Aborting directory node enumeration, too many dirents under %{public}s"
+ "=diag= Aborting readdir_r, too many dirents under %{public}s"
+ "=diag= Failed to enumerate directory nodes under %{public}s"
+ "=diag= Failed to find the file using getattrlistbulk (%u)"
+ "=diag= getattrlistbulk found file entry (%u) for %@: %@"
+ "=drive-domain-delegate= Not creating safe harbour for %@ with invalid container type (%@)"
+ "=pc= open_dprotected_np could not open file at %s: %{errno}d"
```
