## AvatarPosterExtension

> `/System/Library/ExtensionKit/Extensions/AvatarPosterExtension.appex/AvatarPosterExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x176b4` | `0x17a18` | **`+0x364`** |
| `__TEXT.__oslogstring` | `0xc84` | `0xcc4` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x570` | `0x578` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-402.100.1.0.0
+403.100.1.0.0

-  Functions: 387
+  Functions: 388

-  CStrings:  505
+  CStrings:  506
CStrings:
+ "Original sanitized rect was invalid zero; using fallback width"
```
