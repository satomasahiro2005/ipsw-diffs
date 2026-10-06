## hangtracerd

> `/usr/libexec/hangtracerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35c00` | `0x35cd4` | **`+0xd4`** |
| `__TEXT.__objc_methname` | `0x9b06` | `0x9b7d` | **`+0x77`** |
| `__DATA_CONST.__got` | `0x448` | `0x490` | **`+0x48`** |
| `__DATA.__objc_const` | `0x59c8` | `0x59f8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x4d64` | `0x4d89` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0x64e0` | `0x6500` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x281c` | `0x282c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1ec8` | `0x1ed0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x2100` | `0x2108` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x514` | `0x518` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-415.0.0.0.0
+421.0.0.0.0

-  Functions: 1362
+  Functions: 1363

-  CStrings:  3140
+  CStrings:  3144
CStrings:
+ "ShouldMonitorCPURoleForAppExtensions"
+ "TB,R,V_shouldMonitorCPURoleForAppExtensions"
+ "_shouldMonitorCPURoleForAppExtensions"
+ "shouldMonitorCPURoleForAppExtensions"
```
