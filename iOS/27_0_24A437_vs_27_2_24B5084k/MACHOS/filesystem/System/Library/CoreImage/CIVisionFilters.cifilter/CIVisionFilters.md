## CIVisionFilters

> `/System/Library/CoreImage/CIVisionFilters.cifilter/CIVisionFilters`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fcc` | `0x2068` | **`+0x9c`** |
| `__DATA_CONST.__const` | `0x68` | `0xc8` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x460` | `0x420` | **`-0x40`** |
| `__TEXT.__auth_stubs` | `0x450` | `0x470` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x431` | `0x417` | **`-0x1a`** |
| `__DATA.__bss` | `0x10` | `0x29` | **`+0x19`** |
| `__DATA.__objc_selrefs` | `0x178` | `0x168` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x238` | `0x248` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1c0` | `0x1b0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x100` | `0x108` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1667.22.1.0.0
+1667.40.3.0.0

+  - /System/Library/Frameworks/Metal.framework/Metal

-  Functions: 37
-  Symbols:   113
-  CStrings:  88
+  Functions: 41
+  Symbols:   115
+  CStrings:  86
Symbols:
+ _MTLCreateSystemDefaultDevice
+ _objc_release
CStrings:
- "device"
- "metalCommandBuffer"
```
