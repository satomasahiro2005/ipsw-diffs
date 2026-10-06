## CoreUARP

> `/System/Library/PrivateFrameworks/CoreUARP.framework/CoreUARP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x89758` | `0x893dc` | **`-0x37c`** |
| `__AUTH_CONST.__objc_const` | `0x11410` | `0x112a0` | **`-0x170`** |
| `__AUTH_CONST.__cfstring` | `0x7180` | `0x7060` | **`-0x120`** |
| `__TEXT.__objc_methlist` | `0x8a38` | `0x8980` | **`-0xb8`** |
| `__TEXT.__cstring` | `0x7da1` | `0x7d16` | **`-0x8b`** |
| `__AUTH.__objc_data` | `0x20d0` | `0x2080` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1cc0` | `0x1c70` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x26d0` | `0x26b8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x718` | `0x708` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x628` | `0x618` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x618` | `0x608` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xbc4` | `0xbbc` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3260` | `0x3258` | **`-0x8`** |

### Other Changes

```diff

-1587.0.27.0.0
+1587.2.2.0.0

-  Functions: 3970
-  Symbols:   6534
-  CStrings:  2048
+  Functions: 3960
+  Symbols:   6508
+  CStrings:  2039
Symbols:
+ _UARPLayer2RequestAssetBuffer
+ _UARPLayer2ReturnAssetBuffer
- +[UARPSupportedAccessoryA2562 appleModelNumber]
- +[UARPSupportedAccessoryA2562 modelUUID]
- +[UARPSupportedAccessoryd5b67c73d2e5e518 appleModelNumber]
- +[UARPSupportedAccessoryd5b67c73d2e5e518 productGroup]
- +[UARPSupportedAccessoryd5b67c73d2e5e518 productID]
- +[UARPSupportedAccessoryd5b67c73d2e5e518 productNumber]
- +[UARPSupportedAccessoryd5b67c73d2e5e518 vendorID]
- -[UARPSupportedAccessoryA2562 .cxx_destruct]
- -[UARPSupportedAccessoryA2562 init]
- -[UARPSupportedAccessoryd5b67c73d2e5e518 .cxx_destruct]
- -[UARPSupportedAccessoryd5b67c73d2e5e518 description]
- -[UARPSupportedAccessoryd5b67c73d2e5e518 init]
- _OBJC_CLASS_$_UARPSupportedAccessoryA2562
- _OBJC_CLASS_$_UARPSupportedAccessoryd5b67c73d2e5e518
- _OBJC_IVAR_$_UARPSupportedAccessoryA2562.hwID
- _OBJC_IVAR_$_UARPSupportedAccessoryd5b67c73d2e5e518.hwID
- _OBJC_METACLASS_$_UARPSupportedAccessoryA2562
- _OBJC_METACLASS_$_UARPSupportedAccessoryd5b67c73d2e5e518
- __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryA2562
- __OBJC_$_CLASS_METHODS_UARPSupportedAccessoryd5b67c73d2e5e518
- __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryA2562
- __OBJC_$_INSTANCE_METHODS_UARPSupportedAccessoryd5b67c73d2e5e518
- __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryA2562
- __OBJC_$_INSTANCE_VARIABLES_UARPSupportedAccessoryd5b67c73d2e5e518
- __OBJC_CLASS_RO_$_UARPSupportedAccessoryA2562
- __OBJC_CLASS_RO_$_UARPSupportedAccessoryd5b67c73d2e5e518
- __OBJC_METACLASS_RO_$_UARPSupportedAccessoryA2562
- __OBJC_METACLASS_RO_$_UARPSupportedAccessoryd5b67c73d2e5e518
CStrings:
- "693FBEFE-C1E0-4125-96AC-10F8915DA1F3"
- "A2562"
- "HardwareID: %@"
- "PG/PN: %@%@, "
- "Sidekick"
- "Unity Remote"
- "Universal Electronics Inc."
- "d2e5e518"
- "d5b67c73"
```
