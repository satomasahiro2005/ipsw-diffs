## ManagedConfiguration

> `/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf79f8` | `0xf7b38` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x19760` | `0x197e0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x187d2` | `0x1882f` | **`+0x5d`** |
| `__AUTH_CONST.__const` | `0x2110` | `0x2130` | **`+0x20`** |
| `__DATA.__bss` | `0xc89` | `0xc99` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x4e00` | `0x4e10` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e48` | `0x5e50` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb35c` | `0xb364` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 5824
-  Symbols:   9740
-  CStrings:  4637
+  Functions: 5828
+  Symbols:   9745
+  CStrings:  4641
Symbols:
+ -[MCProfileConnection(Misc) isPairingWithHomeDevicesAllowed]
+ GCC_except_table291
+ GCC_except_table374
+ _MCFeaturePairingWithHomeDevicesAllowed
+ _MCGestaltIsHomeAccessory
+ _MCGestaltIsHomeAccessory.isHomeAccessory
+ _MCGestaltIsHomeAccessory.onceToken
+ ___MCGestaltIsHomeAccessory_block_invoke
- GCC_except_table290
- GCC_except_table373
- GCC_except_table43
CStrings:
+ "FEATURE_PAIRING_WITH_HOME_DEVICES"
+ "HomeAccessory"
+ "Localizable-J490"
+ "allowPairingWithHomeDevices"
```
