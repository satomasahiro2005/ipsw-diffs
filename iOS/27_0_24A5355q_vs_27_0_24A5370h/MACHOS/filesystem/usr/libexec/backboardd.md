## backboardd

> `/usr/libexec/backboardd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55cc4` | `0x56dd8` | **`+0x1114`** |
| `__DATA.__objc_const` | `0xaab8` | `0xac98` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0xd6dd` | `0xd851` | **`+0x174`** |
| `__TEXT.__oslogstring` | `0x6e15` | `0x6f39` | **`+0x124`** |
| `__TEXT.__objc_stubs` | `0x9b40` | `0x9c60` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x4844` | `0x48fc` | **`+0xb8`** |
| `__TEXT.__objc_methtype` | `0x2d5b` | `0x2dec` | **`+0x91`** |
| `__DATA.__data` | `0x1a68` | `0x1ac8` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x1313` | `0x1368` | **`+0x55`** |
| `__DATA.__objc_data` | `0x1f90` | `0x1fe0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x3228` | `0x3278` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x3000` | `0x3048` | **`+0x48`** |
| `__TEXT.__cstring` | `0x4b38` | `0x4b68` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1548` | `0x1570` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x7c0` | `0x7d4` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x1540` | `0x1550` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xab0` | `0xab8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x850` | `0x858` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x328` | `0x330` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x228` | `0x230` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x260` | `0x268` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x720` | `0x728` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`

### Other Changes

```diff

-860.0.1.0.0
+866.0.0.0.0

-  Functions: 1863
-  Symbols:   612
-  CStrings:  4010
+  Functions: 1879
+  Symbols:   614
+  CStrings:  4035
Symbols:
+ _IOHIDEventCreateNavigationSwipeEvent
+ _OBJC_CLASS_$_BKIOHIDService
CStrings:
+ "@\"BKHIDUISensorGroup\"16@0:8"
+ "@\"NSString\"24@0:8@\"BKSHIDEventAuthenticationMessage\"16"
+ "BKHIDEventAuthenticationMessageNamespaceResolving"
+ "BKHIDNavigationSwipeEventProcessor"
+ "DeviceSurfaceType"
+ "_applyUIMode:toWrappers:"
+ "_destinationsPerSenderID"
+ "_dispatcherPerSenderID"
+ "_lock_endTransactions"
+ "_lock_groupedValuesByKey"
+ "_lock_modified"
+ "_lock_propertyValueByKey"
+ "_lock_sensors"
+ "_pendingDeliveryManagerBlocks"
+ "_postEvent:sender:toDestination:usingDispatcher:"
+ "_postEvent:sender:toDestinations:usingDispatcher:"
+ "addAuthenticationMessageNamespaceResolver:"
+ "associatedDisplay"
+ "empty"
+ "hoistOnThread:"
+ "navswipe in %{public}@"
+ "navswipe send %{public}@ to %{public}@ (display:%{public}@)"
+ "navswipe: service disappeared for sender:%llX; sending synthetic cancel"
+ "navswipe: terminal phase 0x%X from sender:%llX with %{public}s destinations; re-querying"
+ "no recorded"
+ "nullDisplay"
+ "performWhenDeliveryManagerAvailable:"
+ "removeDisappearanceObserver:"
+ "senderDisplayUUIDForAuthenticationMessage:"
+ "touch suppression to be handled by system shell"
+ "v16@?0@\"BKHIDEventDeliveryManager\"8"
+ "v24@0:8@?<v@?>16"
+ "v24@0:8@?<v@?@\"BKHIDEventDeliveryManager\">16"
- "_endTransactions"
- "_groupedValuesByKey"
- "_lock_applyUIMode:toWrappers:"
- "_modified"
- "_propertyValueByKey"
- "_sensors"
- "_transactionNestCount"
- "kMGQDeviceSurfaceType"
```
