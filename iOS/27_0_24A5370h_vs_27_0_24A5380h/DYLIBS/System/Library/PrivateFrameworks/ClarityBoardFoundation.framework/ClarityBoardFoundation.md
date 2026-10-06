## ClarityBoardFoundation

> `/System/Library/PrivateFrameworks/ClarityBoardFoundation.framework/ClarityBoardFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc858` | `0xe27c` | **`+0x1a24`** |
| `__TEXT.__const` | `0x610` | `0x780` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x24c` | `0x37c` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x5e0` | `0x6f8` | **`+0x118`** |
| `__DATA.__bss` | `0x300` | `0x410` | **`+0x110`** |
| `__AUTH_CONST.__const` | `0x230` | `0x338` | **`+0x108`** |
| `__TEXT.__cstring` | `0x8e9` | `0x9ee` | **`+0x105`** |
| `__TEXT.__swift5_reflstr` | `0x16a` | `0x202` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x2d8` | `0x36c` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x470` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x160` | `0x1d0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x204` | `0x274` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x1db` | `0x23c` | **`+0x61`** |
| `__DATA.__data` | `0x2e0` | `0x340` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x6b0` | `0x6f0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f8` | `0x238` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x130` | `0x170` | **`+0x40`** |
| `__TEXT.__swift5_builtin` | `—` | `0x3c` | **`+0x3c`** |
| `__AUTH.__data` | `0x400` | `0x428` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x7e0` | `0x800` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x160` | `0x180` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x18` | `0x28` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x14` | `0x1c` | **`+0x8`** |

### Other Changes

```diff

-161.0.0.0.0
+163.0.0.0.0

-  Functions: 329
-  Symbols:   435
-  CStrings:  93
+  Functions: 400
+  Symbols:   461
+  CStrings:  104
Symbols:
+ +[CLFLog(ClarityBoardAdditions) orientationLog]
+ GCC_except_table10
+ GCC_except_table21
+ GCC_except_table23
+ GCC_except_table3
+ GCC_except_table30
+ _BSDeviceOrientationDescription
+ _BSInterfaceOrientationDescription
+ _BSInterfaceOrientationMaskDescription
+ _OBJC_CLASS_$_CLBApplicationInterfaceOrientationSettings
+ _OBJC_CLASS_$_UIView
+ _OBJC_METACLASS_$_CLBApplicationInterfaceOrientationSettings
+ __DATA_CLBApplicationInterfaceOrientationSettings
+ __INSTANCE_METHODS_CLBApplicationInterfaceOrientationSettings
+ __IVARS_CLBApplicationInterfaceOrientationSettings
+ __METACLASS_DATA_CLBApplicationInterfaceOrientationSettings
+ __PROPERTIES_CLBApplicationInterfaceOrientationSettings
+ ___47+[CLFLog(ClarityBoardAdditions) orientationLog]_block_invoke
+ ___swift_memcpy32_8
+ _orientationLog.LogObject
+ _orientationLog.OnceToken
+ _swift_getForeignTypeMetadata
+ _symbolic $sSY
+ _symbolic Si
+ _symbolic So42CLBApplicationInterfaceOrientationSettingsC
+ _symbolic _____ 22ClarityBoardFoundation28InterfaceOrientationResolverV
+ _symbolic _____ So19UIDeviceOrientationV
+ _symbolic _____ So22BSInterfaceOrientationV
+ _symbolic _____ So22UIInterfaceOrientationV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So22UIInterfaceOrientationV
+ _type_layout_string 22ClarityBoardFoundation28InterfaceOrientationResolverV
- GCC_except_table11
- GCC_except_table22
- GCC_except_table24
- GCC_except_table31
- GCC_except_table4
CStrings:
+ "Attempt to create UIInterfaceOrientationMask from invalid orientation."
+ "ClarityBoardFoundation/Orientation.swift"
+ "Computing interface orientation. %s, last: %s, deviceBased: %s, device: %s"
+ "Device is flat (%s). Using last interface orientation: %s"
+ "Falling back to first supported orientation: %s"
+ "Fatal error"
+ "Should not have called first() on an empty UIInterfaceOrientationMask"
+ "Unhandled orientation: "
+ "Using device based orientation: %s"
+ "Using supported orientation from client settings: %s"
+ "orientation"
```
