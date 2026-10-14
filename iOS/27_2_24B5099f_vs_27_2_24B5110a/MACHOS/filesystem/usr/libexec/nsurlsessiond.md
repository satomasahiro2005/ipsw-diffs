## nsurlsessiond

> `/usr/libexec/nsurlsessiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84688` | `0x84730` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x3cc8` | `0x3d4d` | **`+0x85`** |
| `__DATA_CONST.__cfstring` | `0x1e00` | `0x1e60` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xf9a2` | `0xf9cf` | **`+0x2d`** |
| `__TEXT.__gcc_except_tab` | `0xe8e4` | `0xe8f0` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3896.200.52.0.0
+3896.200.61.0.0

-  CStrings:  3902
+  CStrings:  3906
CStrings:
+ "Rejecting pid %d pretending to be %{public}@"
+ "com.apple.MobileAsset.DownloadService"
+ "com.apple.MobileAsset.DownloadService.Backported"
+ "com.apple.MobileAsset.DownloadService.Builtin"
```
