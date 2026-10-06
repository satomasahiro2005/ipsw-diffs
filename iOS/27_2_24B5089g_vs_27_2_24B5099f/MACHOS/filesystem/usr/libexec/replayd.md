## replayd

> `/usr/libexec/replayd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbadf8` | `0xbae68` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x5d20` | `0x5d40` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xf320` | `0xf340` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x15f58` | `0x15f73` | **`+0x1b`** |
| `__TEXT.__cstring` | `0x17cf7` | `0x17d0c` | **`+0x15`** |
| `__DATA.__objc_const` | `0x11388` | `0x11398` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x74a0` | `0x74b0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4720` | `0x4728` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2370` | `0x2378` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-765.11.1.0.0
+765.14.1.0.0

-  Functions: 3682
+  Functions: 3683

-  CStrings:  7387
+  CStrings:  7389
CStrings:
+ "RPEnableEdgeLightDev"
+ "edgeLightDevOverrideActive"
```
