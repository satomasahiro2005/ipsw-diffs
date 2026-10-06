## GeneralSettingsUI

> `/System/Library/PrivateFrameworks/Settings/GeneralSettingsUI.framework/GeneralSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44174` | `0x434a8` | **`-0xccc`** |
| `__AUTH_CONST.__objc_const` | `0x1ed8` | `0x1d30` | **`-0x1a8`** |
| `__TEXT.__gcc_except_tab` | `0x2e0` | `0x174` | **`-0x16c`** |
| `__TEXT.__objc_methlist` | `0xa64` | `0x944` | **`-0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0xb68` | `0xa78` | **`-0xf0`** |
| `__TEXT.__cstring` | `0x2951` | `0x2881` | **`-0xd0`** |
| `__TEXT.__unwind_info` | `0x11a0` | `0x1110` | **`-0x90`** |
| `__DATA.__data` | `0x4f0` | `0x480` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x680` | `0x620` | **`-0x60`** |
| `__TEXT.__const` | `0x2694` | `0x2634` | **`-0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x680` | `0x630` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0x1618` | `0x15d8` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x650` | `0x628` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x10b8` | `0x1098` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x1470` | `0x1460` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0xc25` | `0xc15` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x6c` | `0x64` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xe8` | `0xe0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x58` | `0x50` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x28` | `0x20` | **`-0x8`** |

### Other Changes

```diff

-2027.0.2.0.0
+2027.0.4.0.0

-  Functions: 1173
-  Symbols:   1100
-  CStrings:  333
+  Functions: 1152
+  Symbols:   1045
+  CStrings:  327
Symbols:
- +[PSGMousePointerController sharedInstance]
- -[PSGMousePointerController .cxx_destruct]
- -[PSGMousePointerController globalDevicePreferences]
- -[PSGMousePointerController hasMagicMouse]
- -[PSGMousePointerController hasMouse]
- -[PSGMousePointerController hasTrackpad]
- -[PSGMousePointerController init]
- -[PSGMousePointerController mousePointerDevicesDidConnect:]
- -[PSGMousePointerController mousePointerDevicesDidDisconnect:]
- -[PSGMousePointerController observerToken]
- -[PSGMousePointerController pointerDevices]
- -[PSGMousePointerController setGlobalDevicePreferences:]
- -[PSGMousePointerController setObserverToken:]
- -[PSGMousePointerController setPointerDevices:]
- -[PSGMousePointerController setTrackingSpeedIndex:]
- -[PSGMousePointerController trackingSpeedIndex]
- -[PSGMousePointerController trackpadSupportsSilentClick]
- -[PSGMousePointerController trackpadSupportsSystemHaptics]
- GCC_except_table12
- GCC_except_table13
- GCC_except_table14
- GCC_except_table15
- GCC_except_table3
- GCC_except_table5
- _OBJC_CLASS_$_BKSMousePointerDevicePreferences
- _OBJC_CLASS_$_BKSMousePointerService
- _OBJC_CLASS_$_NSMutableSet
- _OBJC_CLASS_$_NSPredicate
- _OBJC_CLASS_$_PSGMousePointerController
- _OBJC_IVAR_$_PSGMousePointerController._observerToken
- _OBJC_IVAR_$_PSGMousePointerController._pointerDevices
- _OBJC_METACLASS_$_PSGMousePointerController
- _PSGPointerDevicesDidChangeNotification
- _PSGTrackingSpeedFactors
- __OBJC_$_CLASS_METHODS_PSGMousePointerController
- __OBJC_$_INSTANCE_METHODS_PSGMousePointerController
- __OBJC_$_INSTANCE_VARIABLES_PSGMousePointerController
- __OBJC_$_PROP_LIST_PSGMousePointerController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_BKSMousePointerDeviceObserver
- __OBJC_$_PROTOCOL_METHOD_TYPES_BKSMousePointerDeviceObserver
- __OBJC_$_PROTOCOL_REFS_BKSMousePointerDeviceObserver
- __OBJC_CLASS_PROTOCOLS_$_PSGMousePointerController
- __OBJC_CLASS_RO_$_PSGMousePointerController
- __OBJC_LABEL_PROTOCOL_$_BKSMousePointerDeviceObserver
- __OBJC_METACLASS_RO_$_PSGMousePointerController
- __OBJC_PROTOCOL_$_BKSMousePointerDeviceObserver
- ___43+[PSGMousePointerController sharedInstance]_block_invoke
- ___59-[PSGMousePointerController mousePointerDevicesDidConnect:]_block_invoke
- ___62-[PSGMousePointerController mousePointerDevicesDidDisconnect:]_block_invoke
- _objc_getProperty
- _objc_setProperty_atomic
- _objc_sync_enter
- _objc_sync_exit
- _sharedInstance.onceToken
- _sharedInstance.sharedInstance
CStrings:
- "%s: %@"
- "-[PSGMousePointerController mousePointerDevicesDidConnect:]"
- "-[PSGMousePointerController mousePointerDevicesDidDisconnect:]"
- "NOT (productName CONTAINS[c] %@)"
- "PSGPointerDevicesDidChangeNotification"
- "UC Automouse"
```
