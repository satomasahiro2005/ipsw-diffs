## HealthPrivacyService

> `/Applications/HealthPrivacyService.app/HealthPrivacyService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ae4` | `0x5bc4` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x1bdf` | `0x1c55` | **`+0x76`** |
| `__TEXT.__objc_stubs` | `0x14e0` | `0x1540` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x6d8` | `0x6f8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x410` | `0x420` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x6fc` | `0x70c` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x218` | `0x220` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x160` | `0x168` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 174
-  Symbols:   120
-  CStrings:  385
+  Functions: 175
+  Symbols:   122
+  CStrings:  389
Symbols:
+ _OBJC_CLASS_$_UITraitUserInterfaceStyle
+ _objc_unsafeClaimAutoreleasedReturnValue
CStrings:
+ "_userInterfaceStyleDidChange:previousTraitCollection:"
+ "layoutIfNeeded"
+ "registerForTraitChanges:withAction:"
+ "setNeedsLayout"
+ "timeBoundedAuthorization"
- "authorizationUICodeRefresh"
```
