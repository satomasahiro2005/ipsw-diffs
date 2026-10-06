## pasted

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Support/pasted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d1e4` | `0x1d324` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x5351` | `0x5375` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x1940` | `0x1960` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4680` | `0x46a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1e09` | `0x1e1e` | **`+0x15`** |
| `__DATA.__objc_selrefs` | `0x13c0` | `0x13c8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1408` | `0x1410` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-9127.1.3.0.0
+9127.1.12.0.0

-  Functions: 514
+  Functions: 515

-  CStrings:  1389
+  CStrings:  1391
CStrings:
+ "authoredBootSession"
+ "persistedBootSession"
+ "removeServerPrivateMetadata"
+ "setAuthoredBootSession:"
- "saveBootSession"
- "setSaveBootSession:"
```
