## perfdiagsselfenabled

> `/usr/libexec/perfdiagsselfenabled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc5d8` | `0xc674` | **`+0x9c`** |
| `__TEXT.__objc_methname` | `0x3430` | `0x34a7` | **`+0x77`** |
| `__DATA.__objc_const` | `0x1ba0` | `0x1bd0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1491` | `0x14b6` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0x1680` | `0x16a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xad8` | `0xae4` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x780` | `0x788` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x6c8` | `0x6d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1c4` | `0x1c8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-415.0.0.0.0
+421.0.0.0.0

-  Functions: 320
+  Functions: 321

-  CStrings:  838
+  CStrings:  842
CStrings:
+ "ShouldMonitorCPURoleForAppExtensions"
+ "TB,R,V_shouldMonitorCPURoleForAppExtensions"
+ "_shouldMonitorCPURoleForAppExtensions"
+ "shouldMonitorCPURoleForAppExtensions"
```
