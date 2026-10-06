## druid

> `/System/Library/PrivateFrameworks/DragUI.framework/Support/druid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e908` | `0x2ec0c` | **`+0x304`** |
| `__TEXT.__objc_methname` | `0xbfb5` | `0xc029` | **`+0x74`** |
| `__TEXT.__cstring` | `0x1509` | `0x1567` | **`+0x5e`** |
| `__TEXT.__objc_methtype` | `0x2cd9` | `0x2d29` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x7e60` | `0x7ea0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x38b4` | `0x38ec` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x2958` | `0x2978` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xe00` | `0xe20` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x2b71` | `0x2b8a` | **`+0x19`** |
| `__TEXT.__unwind_info` | `0xd18` | `0xd30` | **`+0x18`** |
| `__DATA.__objc_const` | `0x69c8` | `0x69b8` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x710` | `0x720` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__TEXT.__const` | `0x24a` | `0x242` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-9127.0.66.1.101
+9127.0.68.0.0

-  Functions: 1365
-  Symbols:   380
-  CStrings:  2734
+  Functions: 1368
+  Symbols:   382
+  CStrings:  2740
Symbols:
+ _BSInterfaceOrientationDescription
+ _BSOrientationRotationDirectionDescription
+ _OBJC_CLASS_$_FBSActiveInterfaceOrientationObserver
- _OBJC_CLASS_$_FBSOrientationObserver
CStrings:
+ "@\"FBSActiveInterfaceOrientationObserver\""
+ "Got orientation change for [%@]: orientation = %@, duration = %g, direction = %@"
+ "_activeStatesByDisplay"
+ "_pushActiveState:"
+ "_updateInterfaceOrientation:duration:direction:"
+ "activateWithStateUpdateHandler:"
+ "animationDuration"
+ "enumerateKeysAndObjectsUsingBlock:"
+ "interfaceOrientationForDisplay:"
+ "q24@0:8@16"
+ "touchDeliveryDidObserveOccurrence:"
+ "v16@?0@\"FBSActiveInterfaceOrientationStateUpdate\"8"
+ "v24@0:8@\"BKSTouchDeliveryOccurrence\"16"
+ "v32@0:8@\"DROrientationObserver\"16@\"FBSActiveInterfaceOrientationStateUpdate\"24"
+ "v32@?0@\"FBSDisplayIdentity\"8@\"FBSActiveInterfaceOrientationState\"16^B24"
+ "viewIsAppearing:"
- "@\"FBSOrientationObserver\""
- "Got orientation change to %ld duration %g direction %ld"
- "Tq,R,N,V_interfaceOrientation"
- "_interfaceOrientation"
- "activeInterfaceOrientation"
- "activeInterfaceOrientationWithCompletion:"
- "duration"
- "setHandler:"
- "v16@?0@\"FBSOrientationUpdate\"8"
- "v32@0:8@\"DROrientationObserver\"16@\"FBSOrientationUpdate\"24"
```
