## AccessibilityReaderShareExtension

> `/Applications/AccessibilityReader_iOS.app/PlugIns/AccessibilityReaderShareExtension.appex/AccessibilityReaderShareExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d4` | `0x9a8` | **`+0x2d4`** |
| `__TEXT.__auth_stubs` | `0x1c0` | `0x260` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0xe8` | `0x138` | **`+0x50`** |
| `__TEXT.__oslogstring` | `—` | `0x4d` | **`+0x4d`** |
| `__TEXT.__cstring` | `—` | `0x2c` | **`+0x2c`** |
| `__DATA.__bss` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x13c` | `0x14c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x88` | `0x98` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x1c0` | `0x1ce` | **`+0xe`** |
| `__DATA.__objc_selrefs` | `0xd0` | `0xd8` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0xdd` | `0xe5` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 14
-  Symbols:   54
-  CStrings:  50
+  Functions: 18
+  Symbols:   60
+  CStrings:  54
Symbols:
+ __os_log_impl
+ _os_log_type_enabled
+ _swift_once
+ _swift_release_x8
+ _swift_slowAlloc
+ _swift_slowDealloc
CStrings:
+ ".cxx_destruct"
+ "AXSpringBoardServer unavailable; skipping Reader launch from share extension"
+ "com.apple.accessibility.AccessibilityReader"
+ "v16@0:8"
```
