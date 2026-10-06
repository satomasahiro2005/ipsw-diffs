## AccessibilityRemoteUIServices

> `/System/Library/PrivateFrameworks/AccessibilityRemoteUIServices.framework/AccessibilityRemoteUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ff8` | `0x5148` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0xb14` | `0xb64` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xa00` | `0xa40` | **`+0x40`** |
| `__TEXT.__cstring` | `0x4ef` | `0x52b` | **`+0x3c`** |
| `__AUTH_CONST.__objc_const` | `0xff8` | `0x1028` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x6a0` | `0x6c0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x54` | `0x60` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x198` | `0x1a0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1f8` | `0x200` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 144
-  Symbols:   481
-  CStrings:  59
+  Functions: 148
+  Symbols:   491
+  CStrings:  60
Symbols:
+ +[AXRemoteViewServiceAdaptor stopHandlingHIDEventsForRemoteViewController:]
+ -[AXRConnectedDeviceViewController _stopHandlingHIDEvents]
+ -[AXRConnectedDeviceViewController _tearDownHIDEventHandling]
+ -[_AXRemoteNearbyDevicesViewController stopHandlingHIDEvents]
+ GCC_except_table37
+ GCC_except_table69
+ _AXRemoteViewServiceShouldStopHandlingHIDEventsNotification
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_IVAR_$_AXRConnectedDeviceViewController._hasTornDownHIDEventHandling
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_AXRemoteViewServiceInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AXRemoteViewServiceInterface
+ _objc_opt_respondsToSelector
- GCC_except_table35
- GCC_except_table67
CStrings:
+ "AXRemoteViewServiceShouldStopHandlingHIDEventsNotification"
```
