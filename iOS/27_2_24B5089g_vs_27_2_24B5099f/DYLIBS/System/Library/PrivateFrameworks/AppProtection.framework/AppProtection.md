## AppProtection

> `/System/Library/PrivateFrameworks/AppProtection.framework/AppProtection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__const` | `0x73a0` | `0x7468` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `0x2840` | `0x28d0` | **`+0x90`** |
| `__DATA.__data` | `0x2438` | `0x24a8` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x185c` | `0x18cc` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x4840` | `0x4880` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x2dca` | `0x2df6` | **`+0x2c`** |
| `__TEXT.__text` | `0xb3854` | `0xb387c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2358` | `0x2378` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x173c` | `0x1754` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x3f28` | `0x3f38` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x130` | `0x138` | **`+0x8`** |

### Other Changes

```diff

-55.1.2.100.0
+55.1.4.0.0

-  Functions: 3530
-  Symbols:   2098
+  Functions: 3547
+  Symbols:   2108
Symbols:
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_APAuthAssertionObserving
+ __OBJC_$_PROTOCOL_METHOD_TYPES_APAuthAssertionObserving
+ __OBJC_$_PROTOCOL_REFS_APAuthAssertionObserving
+ __OBJC_LABEL_PROTOCOL_$_APAuthAssertionObserving
+ __OBJC_PROTOCOL_$_APAuthAssertionObserving
+ ___swift_closure_destructor.3Tm
+ ___swift_closure_destructor.50Tm
+ ___swift_closure_destructor.6Tm
+ _flat unique So24APAuthAssertionObserving_p
+ _symbolic Say______pG So24APAuthAssertionObservingP
CStrings:
+ "auth assertion: %s was invalidated with error: %s"
+ "deallocating valid auth assertion %@; invalidating"
+ "invalidating already invalidated assertion with uuid: %@"
- "auth assertion: %s was invalidated with error: %@"
- "deallocating valid auth assertion %@!"
- "invalidating already invalidated assertion with uuid: %s"
```
