## DisplayFilterUIServer

> `/System/Library/AccessibilityBundles/DisplayFilterUIServer.axuiservice/DisplayFilterUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17e8` | `0x1d24` | **`+0x53c`** |
| `__TEXT.__objc_methname` | `0xdbf` | `0xe53` | **`+0x94`** |
| `__TEXT.__objc_stubs` | `0x900` | `0x960` | **`+0x60`** |
| `__TEXT.__cstring` | `0x101` | `0x15f` | **`+0x5e`** |
| `__DATA_CONST.__const` | `0xc0` | `0x110` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x140` | `0x180` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x280` | `0x2c0` | **`+0x40`** |
| `__DATA.__objc_const` | `0x558` | `0x588` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x40c` | `0x43c` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x148` | `0x168` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x3c8` | `0x3e0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x431` | `0x439` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 41
-  Symbols:   78
-  CStrings:  205
+  Functions: 47
+  Symbols:   82
+  CStrings:  212
Symbols:
+ _OBJC_CLASS_$_NSArray
+ ___NSDictionary0__struct
+ _objc_enumerationMutation
+ _objc_release_x26
+ _objc_retain_x19
+ _objc_retain_x20
- _OBJC_CLASS_$_NSDictionary
- _OBJC_CLASS_$_NSNumber
CStrings:
+ "Mask fully opaque"
+ "T@\"UIView\",&,N,V__maskView"
+ "__maskView"
+ "_fadeDisplayForSmartInvertStartWithMaskOpaqueCompletion:"
+ "_maskView"
+ "arrayWithObjects:count:"
+ "colorWithRed:green:blue:alpha:"
+ "com.apple.accessibility.physicalinteraction.client"
+ "countByEnumeratingWithState:objects:count:"
+ "fadeToBlackAndComeBack:fadedInCompletion:completion:"
+ "processing message asynchronously: %@ %d"
+ "set_maskView:"
+ "v24@0:8@?16"
+ "v40@0:8d16@?24@?32"
- "_fadeDisplayForSmartInvertStart"
- "animationDuration"
- "d16@0:8"
- "dictionaryWithObjects:forKeys:count:"
- "fadeToBlackAndComeBack:completion:"
- "numberWithDouble:"
- "v32@0:8d16@?24"
```
