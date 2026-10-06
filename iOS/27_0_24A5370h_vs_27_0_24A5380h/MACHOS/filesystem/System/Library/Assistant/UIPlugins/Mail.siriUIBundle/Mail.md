## Mail

> `/System/Library/Assistant/UIPlugins/Mail.siriUIBundle/Mail`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6d0` | `0xa740` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x12dd` | `0x130a` | **`+0x2d`** |
| `__DATA.__objc_const` | `0x1298` | `0x12b8` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x309b` | `0x30b0` | **`+0x15`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa0` | `0xa4` | **`+0x4`** |
| `__TEXT.__cstring` | `0x55d` | `0x55e` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3893.100.7.0.0
+3895.100.17.2.1

-  Symbols:   289
-  CStrings:  737
+  Symbols:   290
+  CStrings:  738
Symbols:
+ OBJC_IVAR_$_MFEmailSnippetComposeView._searchCompletedLock
Functions:
~ sub_71c0 : 356 -> 396
~ sub_7acc -> sub_7af4 : 20 -> 92
CStrings:
+ "_searchCompletedLock"
+ "{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}"
+ "\xe1"
- "\r"
- "\xd1"
```
