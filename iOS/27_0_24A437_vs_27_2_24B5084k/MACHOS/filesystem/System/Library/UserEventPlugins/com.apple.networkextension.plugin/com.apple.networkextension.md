## com.apple.networkextension

> `/System/Library/UserEventPlugins/com.apple.networkextension.plugin/com.apple.networkextension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21a8` | `0x221c` | **`+0x74`** |
| `__TEXT.__cstring` | `0x37e` | `0x3b7` | **`+0x39`** |

### Same-size Content Changes

- `__DATA.__cfstring`
- `__DATA.__const`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2340.0.0.0.4
+2365.40.1.0.0

-  CStrings:  96
+  CStrings:  97
Functions:
~ _init_networkextension : 728 -> 844
CStrings:
+ "com.apple.networkextension.preserve-existing-connections"
```
