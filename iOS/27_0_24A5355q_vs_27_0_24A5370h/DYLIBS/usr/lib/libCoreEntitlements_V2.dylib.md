## libCoreEntitlements_V2.dylib

> `/usr/lib/libCoreEntitlements_V2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65c0` | `0x6920` | **`+0x360`** |
| `__AUTH_CONST.__const` | `0x50` | `0xa0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x200` | `0x220` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x18` | `—` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__cstring` | `0xd1` | `0xcf` | **`-0x2`** |

### Other Changes

```diff

-93.0.0.0.0
+94.0.0.0.0

-  Functions: 139
+  Functions: 152

-  CStrings:  25
+  CStrings:  24
Symbols:
+ _CEDictionarySerialize
+ _allocateNSArrayWithIntegerAndValue
+ _allocateNSDictionaryAsArray
+ _arrayEncodeIterate
+ _arrayLengthIterate
+ _getNSBoolean
+ _getNSData
+ _getNSInteger
+ _getNSString
+ _getNSType
+ _iterateNSArray
+ _serializeNSEnv
- _OBJC_CLASS_$_NSConstantIntegerNumber
- _objc_release_x25
- _objc_release_x26
- _objc_release_x27
- _objc_release_x28
- _objc_release_x8
- _objc_retain_x1
- _objc_retain_x19
- _objc_retain_x20
- _objc_retain_x23
- _objc_retain_x24
- _objc_retain_x27
CStrings:
- "i"
```
