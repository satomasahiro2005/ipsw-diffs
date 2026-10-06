## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/CoreRepairCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9a280` | `0x9acbc` | **`+0xa3c`** |
| `__TEXT.__oslogstring` | `0xa4a8` | `0xa541` | **`+0x99`** |
| `__TEXT.__gcc_except_tab` | `0x19e8` | `0x1a44` | **`+0x5c`** |
| `__AUTH_CONST.__cfstring` | `0x9520` | `0x9560` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x28f0` | `0x2908` | **`+0x18`** |
| `__TEXT.__cstring` | `0x7e70` | `0x7e81` | **`+0x11`** |
| `__DATA_CONST.__got` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__TEXT.__const` | `0x850` | `0x860` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4f64` | `0x4f6c` | **`+0x8`** |

### Other Changes

```diff

-1307.2.4.0.0
+1307.40.46.0.0

-  Functions: 2783
-  Symbols:   697
-  CStrings:  2629
+  Functions: 2788
+  Symbols:   699
+  CStrings:  2634
Symbols:
+ _NSCalendarIdentifierGregorian
+ _OBJC_CLASS_$_NSCalendar
CStrings:
+ "%s exit: challenge: %@, outSignature: %@, outDeviceNonce: %@, typeInfo: %@, outError: %@"
+ "(null)"
+ "(nullptr)"
+ "Set sensor power failed: %d"
+ "Set sensor power to %d successfully"
```
