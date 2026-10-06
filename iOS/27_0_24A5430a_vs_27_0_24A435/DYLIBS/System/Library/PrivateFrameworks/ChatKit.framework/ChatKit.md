## ChatKit

> `/System/Library/PrivateFrameworks/ChatKit.framework/ChatKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc21e74` | `0xc22174` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0x55147` | `0x55197` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x9dd48` | `0x9dd80` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x3f190` | `0x3f1b8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x37520` | `0x37540` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x207dc` | `0x207fc` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x7330c` | `0x7332c` | **`+0x20`** |
| `__DATA.__bss` | `0x44c50` | `0x44c40` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6b60` | `0x6b68` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7d10` | `0x7d18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x31bd0` | `0x31bc8` | **`-0x8`** |

### Other Changes

```diff

-1491.100.1.2.23
+1491.100.1.2.25

-  Symbols:   73708
-  CStrings:  13244
+  Symbols:   73709
+  CStrings:  13245
Symbols:
+ _kPhotosAlwaysShareProvenancePreferenceKey
+ _objc_retain_x11
- _supportsFoundInSuggestions.sBehavior
CStrings:
+ "Photos prefs excludes provenance when sharing. Stripping provenance metadata."
```
