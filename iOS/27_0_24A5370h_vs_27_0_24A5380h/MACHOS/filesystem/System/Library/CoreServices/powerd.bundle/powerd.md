## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77620` | `0x77744` | **`+0x124`** |
| `__DATA.__common` | `0x11d0` | `0x1270` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x6e59` | `0x6ec2` | **`+0x69`** |
| `__DATA_CONST.__cfstring` | `0x7680` | `0x76e0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x388` | `0x3c0` | **`+0x38`** |
| `__DATA.__bss` | `0xdb8` | `0xdc0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1660` | `0x1668` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2041.0.0.502.1
+2043.0.13.502.1

-  CStrings:  4064
+  CStrings:  4066
CStrings:
+ "PreventSystemSleepSecurityIndicator"
+ "com.apple.private.iokit.preventSystemSleepSecurityIndicator"
```
