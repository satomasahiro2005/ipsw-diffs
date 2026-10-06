## iWorkImport

> `/System/Library/PrivateFrameworks/iWorkImport.framework/iWorkImport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x564a8` | `0x55b2c` | **`-0x97c`** |
| `__TEXT.__auth_stubs` | `0x1670` | `0x1570` | **`-0x100`** |
| `__TEXT.__objc_stubs` | `0x8860` | `0x8900` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0xb28` | `0xab8` | **`-0x70`** |
| `__TEXT.__gcc_except_tab` | `0x8cc` | `0x874` | **`-0x58`** |
| `__TEXT.__objc_methname` | `0x95e4` | `0x963c` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x2720` | `0x2748` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1870` | `0x1848` | **`-0x28`** |
| `__TEXT.__const` | `0x450` | `0x438` | **`-0x18`** |
| `__AUTH_CONST.__weak_auth_got` | `0x28` | `0x18` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x740` | `0x748` | **`+0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-487.0.0.0.0
+488.0.0.0.0

+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/AppEditIn.framework/AppEditIn

+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSFeatureFlags.framework/TSFeatureFlags
+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSFundamentals.framework/TSFundamentals
+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSGeometry.framework/TSGeometry

-  Functions: 2121
-  Symbols:   528
-  CStrings:  3907
+  Functions: 2116
+  Symbols:   513
+  CStrings:  3912
Symbols:
+ _OBJC_CLASS_$_TSUBezierPath
- __ZN4Path19ConvertWithBackDataEf
- __ZN4Path4FillEP5Shapeibbb
- __ZN4Path5CloseEv
- __ZN4Path6LineToEff
- __ZN4Path6MoveToEff
- __ZN4Path7CubicToEffffff
- __ZN4PathC1Ev
- __ZN4PathD1Ev
- __ZN5Shape14ConvertToFormeEP4PathiPS1_
- __ZN5Shape14ConvertToShapeEPS_8fill_typb
- __ZN5Shape7BooleenEPS_S0_7bool_op
- __ZN5ShapeC1Ev
- __ZN5ShapeD1Ev
- __ZdaPvSt19__type_descriptor_t
- __ZnamSt19__type_descriptor_t
- _acos
CStrings:
+ "CGPath"
+ "arrayWithCapacity:"
+ "bezierPathWithCGPath:"
+ "intersectBezierPaths:"
+ "uniteBezierPaths:"
```
