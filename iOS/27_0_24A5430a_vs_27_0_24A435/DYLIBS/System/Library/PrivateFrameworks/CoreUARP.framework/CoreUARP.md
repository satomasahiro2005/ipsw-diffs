## CoreUARP

> `/System/Library/PrivateFrameworks/CoreUARP.framework/CoreUARP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x893dc` | `0x8a184` | **`+0xda8`** |
| `__AUTH_CONST.__objc_const` | `0x112a0` | `0x11918` | **`+0x678`** |
| `__DATA_DIRTY.__objc_data` | `0x1c70` | `0x1f40` | **`+0x2d0`** |
| `__TEXT.__objc_methlist` | `0x8980` | `0x8c00` | **`+0x280`** |
| `__AUTH_CONST.__cfstring` | `0x7060` | `0x71c0` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x26b8` | `0x2708` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x708` | `0x750` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x618` | `0x660` | **`+0x48`** |
| `__DATA_CONST.__objc_superrefs` | `0x608` | `0x650` | **`+0x48`** |
| `__TEXT.__cstring` | `0x7d16` | `0x7d5d` | **`+0x47`** |
| `__DATA.__objc_ivar` | `0xbbc` | `0xbe0` | **`+0x24`** |

### Other Changes

```diff

-  Functions: 3960
-  Symbols:   6508
-  CStrings:  2039
+  Functions: 3999
+  Symbols:   6620
+  CStrings:  2050
Symbols:
+ +[UARPSupportedAccessoryA3440 alternativeAppleModelNumbers]
+ +[UARPSupportedAccessoryA3440 appleModelNumber]
+ +[UARPSupportedAccessoryA3440 productID]
+ +[UARPSupportedAccessoryA3441 appleModelNumber]
+ +[UARPSupportedAccessoryA3441 mobileAssetAppleModelNumber]
+ +[UARPSupportedAccessoryA3441 productID]
+ +[UARPSupportedAccessoryA3529 appleModelNumber]
+ +[UARPSupportedAccessoryA3529 productID]
+ +[UARPSupportedAccessoryA3529USB appleModelNumber]
+ +[UARPSupportedAccessoryA3529USB productID]
+ +[UARPSupportedAccessoryA3530USB appleModelNumber]
+ +[UARPSupportedAccessoryA3530USB productID]
+ +[UARPSupportedAccessoryA3532 alternativeAppleModelNumbers]
+ +[UARPSupportedAccessoryA3532 appleModelNumber]
+ +[UARPSupportedAccessoryA3532 productID]
+ +[UARPSupportedAccessoryA3533 appleModelNumber]
+ +[UARPSupportedAccessoryA3533 mobileAssetAppleModelNumber]
+ +[UARPSupportedAccessoryA3533 productID]
+ +[UARPSupportedAccessoryA3577 appleModelNumber]
+ +[UARPSupportedAccessoryA3577 productID]
+ +[UARPSupportedAccessoryA3577USB appleModelNumber]
+ +[UARPSupportedAccessoryA3577USB productID]
+ -[UARPSupportedAccessoryA3440 .cxx_destruct]
+ -[UARPSupportedAccessoryA3440 init]
+ -[UARPSupportedAccessoryA3441 .cxx_destruct]
+ -[UARPSupportedAccessoryA3441 init]
+ -[UARPSupportedAccessoryA3529 .cxx_destruct]
+ -[UARPSupportedAccessoryA3529 init]
+ -[UARPSupportedAccessoryA3529USB .cxx_destruct]
+ -[UARPSupportedAccessoryA3529USB init]
+ -[UARPSupportedAccessoryA3530USB .cxx_destruct]
+ -[UARPSupportedAccessoryA3530USB init]
+ -[UARPSupportedAccessoryA3532 .cxx_destruct]
+ -[UARPSupportedAccessoryA3532 init]
+ -[UARPSupportedAccessoryA3533 .cxx_destruct]
+ -[UARPSupportedAccessoryA3533 init]
+ -[UARPSupportedAccessoryA3577 .cxx_destruct]
+ -[UARPSupportedAccessoryA3577 init]
+ -[UARPSupportedAccessoryA3577USB .cxx_destruct]
+ -[UARPSupportedAccessoryA3577USB init]
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3440
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3441
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3529
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3529USB
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3530USB
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3532
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3533
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3577
+ _OBJC_CLASS_$_UARPSupportedAccessoryA3577USB
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3440.hwID
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3441.hwID
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3529.hwID
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3529USB.hwID
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3530USB.hwID
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3532.hwID
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3533.hwID
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3577.hwID
+ _OBJC_IVAR_$_UARPSupportedAccessoryA3577USB.hwID
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3440
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3441
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3529
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3529USB
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3530USB
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3532
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3533
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3577
+ _OBJC_METACLASS_$_UARPSupportedAccessoryA3577USB
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3440
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3441
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3529
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3529USB
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3530USB
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3532
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3533
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3577
+ __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA3577USB
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3440
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3441
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3529
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3529USB
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3530USB
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3532
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3533
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3577
+ __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA3577USB
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3440
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3441
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3529
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3529USB
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3530USB
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3532
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3533
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3577
+ __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA3577USB
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3440
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3441
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3529
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3529USB
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3530USB
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3532
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3533
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3577
+ __OBJC_CLASS_RO_$_UARPSupportedAccessoryA3577USB
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3440
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3441
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3529
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3529USB
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3530USB
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3532
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3533
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3577
+ __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA3577USB
CStrings:
+ "A3439"
+ "A3440"
+ "A3441"
+ "A3529"
+ "A3530"
+ "A3531"
+ "A3532"
+ "A3533"
+ "A3577"
+ "AirPods"
+ "AirPods Case"
+ "Rave"
- "RaveSeed"
```
