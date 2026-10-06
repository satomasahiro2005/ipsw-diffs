## bookassetd

> `/System/Library/PrivateFrameworks/BookLibraryCore.framework/Support/bookassetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe0f80` | `0xe1014` | **`+0x94`** |
| `__DATA_CONST.__got` | `0x8b0` | `0x918` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0xc4f4` | `0xc522` | **`+0x2e`** |
| `__TEXT.__auth_stubs` | `0xd90` | `0xdb0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x19d0` | `0x19d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2305.0.0.0.0
+2306.0.0.0.0

-  Functions: 2405
-  Symbols:   587
-  CStrings:  4562
+  Functions: 2406
+  Symbols:   589
+  CStrings:  4563
Symbols:
+ _NSTemporaryDirectory
+ __set_user_dir_suffix
Functions:
~ sub_1000a3aac : 272 -> 304
+ sub_1000e2840
CStrings:
+ "_set_user_dir_suffix failed: %{darwin.errno}d"
```
