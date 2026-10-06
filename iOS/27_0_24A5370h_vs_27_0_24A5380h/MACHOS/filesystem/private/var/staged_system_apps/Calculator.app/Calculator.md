## Calculator

> `/private/var/staged_system_apps/Calculator.app/Calculator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf1d90` | `0xf2124` | **`+0x394`** |
| `__TEXT.__objc_methname` | `0x27a5` | `0x2805` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x10e0` | `0x1120` | **`+0x40`** |
| `__DATA.__objc_const` | `0x3260` | `0x3280` | **`+0x20`** |
| `__TEXT.__const` | `0xa8e4` | `0xa904` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2d20` | `0x2d38` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x798` | `0x7a8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4e30` | `0x4e40` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2b81` | `0x2b91` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2324` | `0x2330` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x2720` | `0x2728` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1abbe` | `0x1abb6` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-131.0.0.0.0
+133.0.0.0.0

-  Functions: 4473
-  Symbols:   2257
-  CStrings:  932
+  Functions: 4479
+  Symbols:   2258
+  CStrings:  935
Symbols:
+ _$sSo15_UICornerInsetsV5UIKitE4zeroABvgZ
CStrings:
+ "_hasSafeAreaCorners"
+ "_interfaceOrientation"
+ "_safeAreaCornerInsetsForInterfaceOrientation:statusBarHidden:"
```
