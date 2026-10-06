## SiriUIBridge

> `/System/Library/PrivateFrameworks/SiriUIBridge.framework/SiriUIBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d0c0` | `0x2d310` | **`+0x250`** |
| `__AUTH_CONST.__objc_const` | `0x51a8` | `0x5208` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0xc80` | `0xcc0` | **`+0x40`** |
| `__DATA.__data` | `0x640` | `0x680` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xb12` | `0xb50` | **`+0x3e`** |
| `__TEXT.__const` | `0x520` | `0x550` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1faa` | `0x1fda` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x24cc` | `0x24fc` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0xa38` | `0xa40` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x248` | `0x250` | **`+0x8`** |

### Other Changes

```diff

-3600.27.1.0.0
+3600.27.2.0.0

+  - /System/Library/Frameworks/IOSurface.framework/IOSurface

-  Functions: 1751
-  Symbols:   1812
-  CStrings:  239
+  Functions: 1755
+  Symbols:   1823
+  CStrings:  241
Symbols:
+ -[SUIBVisualCaptureContext setSurfaces:]
+ -[SUIBVisualCaptureContext surfaces]
+ -[SUIBVisualCaptureContextMutation setSurfaces:]
+ -[SUIBVisualCaptureContextMutation surfaces]
+ _NSClassFromString
+ _OBJC_CLASS_$_IOSurface
+ _OBJC_IVAR_$_SUIBVisualCaptureContext._surfaces
+ _OBJC_IVAR_$_SUIBVisualCaptureContextMutation._surfaces
+ ___NSDictionary0__struct
+ ___block_descriptor_48_e8_32s40s_e42_v16?0"SUIBVisualCaptureContextMutation"8ls32l8s40l8
+ _symbolic So12NSDictionaryCm
+ _symbolic So6NSDataCm
+ _symbolic So8NSStringCm
+ _symbolic So9IOSurfaceCm
- _OBJC_CLASS_$_NSKeyedArchiver
- _OBJC_CLASS_$_NSKeyedUnarchiver
- ___block_descriptor_40_e8_32s_e42_v16?0"SUIBVisualCaptureContextMutation"8ls32l8
CStrings:
+ "NSXPCCoder"
+ "SUIBVisualCaptureContext::surfaces"
```
