## com.apple.fskit.exfat

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.exfat.appex/com.apple.fskit.exfat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x120a4` | `0x12454` | **`+0x3b0`** |
| `__TEXT.__objc_stubs` | `0x760` | `0x800` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x32c` | `0x374` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0x6fc` | `0x741` | **`+0x45`** |
| `__TEXT.__auth_stubs` | `0x980` | `0x9c0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x581` | `0x5bc` | **`+0x3b`** |
| `__DATA.__objc_selrefs` | `0x2b0` | `0x2d8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x4d0` | `0x4f0` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x3c0` | `0x3e0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2e0` | `0x2f8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xb8` | `0xc8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3e51` | `0x3e5c` | **`+0xb`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-560.0.0.0.0
+561.0.0.0.0

-  Functions: 276
-  Symbols:   408
-  CStrings:  570
+  Functions: 277
+  Symbols:   414
+  CStrings:  577
Symbols:
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_EHTYPE_$_NSException
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_release_x28
+ _objc_retainAutoreleasedReturnValue
CStrings:
+ "%s: got an exception from fsck_exfat_check_fs, error = %ld"
+ "error"
+ "fsck error: %d: %s"
+ "integerValue"
+ "numberWithInt:"
+ "objectForKeyedSubscript:"
+ "reason"
+ "userInfo"
- "fsck error %d"
```
