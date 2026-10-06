## DisplayFilterUIServer

> `/System/Library/AccessibilityBundles/DisplayFilterUIServer.axuiservice/DisplayFilterUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d24` | `0x20e4` | **`+0x3c0`** |
| `__TEXT.__objc_stubs` | `0x960` | `0xaa0` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0xe53` | `0xf60` | **`+0x10d`** |
| `__DATA.__objc_const` | `0x588` | `0x640` | **`+0xb8`** |
| `__TEXT.__objc_methtype` | `0x439` | `0x4b3` | **`+0x7a`** |
| `__TEXT.__auth_stubs` | `0x2c0` | `0x330` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x3e0` | `0x448` | **`+0x68`** |
| `__DATA.__data` | `0x120` | `0x180` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x43c` | `0x484` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x168` | `0x1a0` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x8d` | `0xaf` | **`+0x22`** |
| `__DATA_CONST.__got` | `0xb0` | `0xd0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xf8` | `0x110` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1c` | `0x24` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__cstring` | `0x15f` | `0x160` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 47
-  Symbols:   82
-  CStrings:  212
+  Functions: 51
+  Symbols:   93
+  CStrings:  231
Symbols:
+ _CGPathAddPath
+ _CGPathAddRect
+ _CGPathCreateMutable
+ _CGPathRelease
+ _CGRectIsEmpty
+ _CGRectUnion
+ _OBJC_CLASS_$_CAShapeLayer
+ _OBJC_CLASS_$_SBSSystemApertureLayoutMonitor
+ _OBJC_CLASS_$_UIBezierPath
+ _kCAFillRuleEvenOdd
+ _objc_retainAutorelease
CStrings:
+ "@\"SBSSystemApertureLayoutMonitor\""
+ "CGPath"
+ "CGRectValue"
+ "SBSSystemApertureLayoutMonitoring"
+ "_apertureFrame"
+ "_layoutMonitor"
+ "_updateMaskViewApertureExclusion"
+ "addObserver:"
+ "bezierPathWithRoundedRect:cornerRadius:"
+ "dealloc"
+ "objectAtIndexedSubscript:"
+ "removeObserver:"
+ "setFillRule:"
+ "setMask:"
+ "setPath:"
+ "systemApertureLayoutDidChange:"
+ "v24@0:8@\"NSArray\"16"
+ "viewDidLayoutSubviews"
+ "{CGRect=\"origin\"{CGPoint=\"x\"d\"y\"d}\"size\"{CGSize=\"width\"d\"height\"d}}"
```
