## demod_helper

> `/usr/libexec/demod_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x6877` | `0x68b4` | **`+0x3d`** |
| `__DATA_CONST.__cfstring` | `0x5280` | `0x52a0` | **`+0x20`** |
| `__TEXT.__text` | `0x2ec34` | `0x2ec40` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1871.40.45.0.0
+1871.40.52.0.0

-  CStrings:  2194
+  CStrings:  2195
Functions:
~ sub_1000171c4 : 1372 -> 1384
CStrings:
+ "/var/mobile/Library/Preferences/com.apple.voicetrigger.plist"
```
