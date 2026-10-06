## MechTouchId

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismPlugins/MechTouchId.bundle/MechTouchId`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d18` | `0x3e30` | **`+0x118`** |
| `__TEXT.__objc_stubs` | `0x1080` | `0x10e0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xfa3` | `0xff4` | **`+0x51`** |
| `__DATA_CONST.__const` | `0x260` | `0x2a0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x550` | `0x568` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x334` | `0x344` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x170` | `0x178` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.63.0.0
+2319.40.29.0.0

-  Functions: 56
-  Symbols:   112
-  CStrings:  267
+  Functions: 59
+  Symbols:   115
+  CStrings:  270
Symbols:
+ _LACLightweightUIModeFromOptions
+ _LACLightweightUIModeNone
+ _OBJC_CLASS_$_LACDevice
CStrings:
+ "_usesLightweightUI"
+ "featureFlagLightweightTouchIDEnabled"
+ "isDynamicIslandAvailable"
```
