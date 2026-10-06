## revisiond

> `/System/Library/PrivateFrameworks/GenerationalStorage.framework/revisiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291d8` | `0x2923c` | **`+0x64`** |
| `__TEXT.__objc_methname` | `0x3add` | `0x3b2a` | **`+0x4d`** |
| `__TEXT.__auth_stubs` | `0xf40` | `0xf10` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0x3420` | `0x3440` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x7b0` | `0x798` | **`-0x18`** |
| `__TEXT.__cstring` | `0x5268` | `0x525e` | **`-0xa`** |
| `__DATA.__objc_selrefs` | `0x1030` | `0x1038` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x900` | `0x908` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-405.0.0.0.1
+411.0.0.0.0

-  Functions: 871
-  Symbols:   339
+  Functions: 872
+  Symbols:   336
Symbols:
- _objc_release_x3
- _snprintf
- _unlink
CStrings:
+ "\"%s\" is not owned by the caller"
+ "13:31:31"
+ "Sep  4 2026"
+ "T@\"NSNumber\",&,N,V_doArchiveWithOwnerUID"
+ "_doArchiveWithOwnerUID"
+ "doArchiveWithOwnerUID"
+ "gsarchive-XXXXXXXX"
+ "setDoArchiveWithOwnerUID:"
+ "unsignedIntValue"
- "%s_XXXXXX"
- "15:33:35"
- "Aug  8 2026"
- "TB,N,V_doArchive"
- "_doArchive"
- "doArchive"
- "setDoArchive:"
- "stat(%s) failed"
- "temporary path \"%s_XXXXXX\" too long"
```
