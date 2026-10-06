## GenericHID

> `/System/Library/ScreenReader/BrailleDrivers/GenericHID.brailledriver/GenericHID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e78` | `0x555c` | **`+0x6e4`** |
| `__TEXT.__objc_methname` | `0x101c` | `0x1183` | **`+0x167`** |
| `__TEXT.__objc_stubs` | `0xf20` | `0x1060` | **`+0x140`** |
| `__DATA_CONST.__cfstring` | `0x1c0` | `0x220` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x588` | `0x5e0` | **`+0x58`** |
| `__DATA.__objc_const` | `0x9d8` | `0xa20` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x6bc` | `0x6fc` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x571` | `0x5a8` | **`+0x37`** |
| `__DATA_CONST.__got` | `0xa0` | `0xc0` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x31b` | `0x335` | **`+0x1a`** |
| `__TEXT.__cstring` | `0x1ef` | `0x206` | **`+0x17`** |
| `__TEXT.__auth_stubs` | `0x4c0` | `0x4d0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x120` | `0x130` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x8c` | `0x94` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x268` | `0x270` | **`+0x8`** |
| `__TEXT.__const` | `0x48` | `0x50` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-467.3.1.0.0
+467.3.3.0.0

-  Functions: 91
-  Symbols:   106
-  CStrings:  335
+  Functions: 95
+  Symbols:   111
+  CStrings:  354
Symbols:
+ _OBJC_CLASS_$_NSComparisonPredicate
+ _OBJC_CLASS_$_NSExpression
+ _kSCROBrailleDriverBluetoothDeviceNameRegexPatterns
+ _kSCROBrailleDriverModels
+ _objc_allocWithZone
CStrings:
+ "-mobile"
+ "@\"NSString\""
+ "B32@0:8@16@24"
+ "Product"
+ "Resolved generic HID model: %{public}@ (vid %@ pid %@)"
+ "_modelIdentifierFromModels"
+ "_productName:matchesPatterns:"
+ "_resolvedModelIdentifier"
+ "_resolvedModelSearched"
+ "_sharedModelIdentifier"
+ "evaluateWithObject:"
+ "expressionForConstantValue:"
+ "expressionForEvaluatedObject"
+ "infoDictionary"
+ "initWithLeftExpression:rightExpression:modifier:type:options:"
+ "modelIdentifierForAnalytics"
+ "pathForResource:ofType:"
+ "plist"
+ "stringByAppendingString:"
```
