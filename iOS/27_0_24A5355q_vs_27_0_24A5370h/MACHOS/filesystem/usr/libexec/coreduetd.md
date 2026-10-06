## coreduetd

> `/usr/libexec/coreduetd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21160` | `0x21224` | **`+0xc4`** |
| `__TEXT.__objc_methname` | `0x6580` | `0x65ae` | **`+0x2e`** |
| `__TEXT.__objc_stubs` | `0x5280` | `0x52a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x808` | `0x828` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x17d8` | `0x17e0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4b8` | `0x4c0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1c83` | `0x1c85` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1956.0.1.0.0
+1959.0.1.0.0

-  Functions: 668
-  Symbols:   321
+  Functions: 670
+  Symbols:   322
Symbols:
+ _OBJC_CLASS_$_NSXPCConnection
CStrings:
+ "_addOrUpdateInteractionsQueue"
+ "_handoffCurrentReplyToQueue:block:"
- "_appExtensionQueue"
- "com.apple.appExtensionQueue"
```
