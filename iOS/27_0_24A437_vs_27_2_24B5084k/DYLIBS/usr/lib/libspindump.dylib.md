## libspindump.dylib

> `/usr/lib/libspindump.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3918` | `0x39e0` | **`+0xc8`** |
| `__AUTH_CONST.__auth_got` | `0x248` | `0x268` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x38` | `0x40` | **`+0x8`** |

### Other Changes

```diff

-448.0.0.0.0
+452.0.0.0.0

-  Functions: 87
-  Symbols:   174
+  Functions: 88
+  Symbols:   180
Symbols:
+ _OBJC_CLASS_$_NSNumber
+ _SPStringFromInfoDictionaryValue
+ _objc_autoreleaseReturnValue
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_retain
Functions:
~ ___SPSubmitHIDTelemetry_block_invoke : 732 -> 784
+ _SPStringFromInfoDictionaryValue
```
