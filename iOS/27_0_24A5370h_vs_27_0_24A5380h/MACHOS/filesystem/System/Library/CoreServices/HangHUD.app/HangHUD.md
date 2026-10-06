## HangHUD

> `/System/Library/CoreServices/HangHUD.app/HangHUD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f59c` | `0x2f624` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0xa716` | `0xa78d` | **`+0x77`** |
| `__DATA.__objc_const` | `0x6aa8` | `0x6ad8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x2d0` | `0x300` | **`+0x30`** |
| `__TEXT.__cstring` | `0x386c` | `0x3891` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0x52e0` | `0x5300` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3364` | `0x3374` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x2138` | `0x2140` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1aa8` | `0x1ab0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x61c` | `0x620` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
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

-  Functions: 1531
+  Functions: 1532

-  CStrings:  3094
+  CStrings:  3098
CStrings:
+ "ShouldMonitorCPURoleForAppExtensions"
+ "TB,R,V_shouldMonitorCPURoleForAppExtensions"
+ "_shouldMonitorCPURoleForAppExtensions"
+ "shouldMonitorCPURoleForAppExtensions"
```
