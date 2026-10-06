## SmartStackUIServices

> `/System/Library/PrivateFrameworks/SmartStackUIServices.framework/SmartStackUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1248` | `0x2248` | **`+0x1000`** |
| `__AUTH_CONST.__auth_got` | `0xf0` | `0x1d8` | **`+0xe8`** |
| `__AUTH_CONST.__const` | `0x778` | `0x828` | **`+0xb0`** |
| `__TEXT.__const` | `0x222` | `0x2c0` | **`+0x9e`** |
| `__DATA.__bss` | `0x180` | `0x200` | **`+0x80`** |
| `__TEXT.__oslogstring` | `—` | `0x52` | **`+0x52`** |
| `__TEXT.__swift5_reflstr` | `0x273` | `0x2c3` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x108` | `0x148` | **`+0x40`** |
| `__TEXT.__cstring` | `—` | `0x39` | **`+0x39`** |
| `__TEXT.__unwind_info` | `0xc8` | `0x100` | **`+0x38`** |
| `__DATA.__data` | `0x48` | `0x70` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x94` | `0xb0` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x83` | `0x9f` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x10` | `0x14` | **`+0x4`** |

### Other Changes

```diff

-306.1.0.0.0
+315.0.0.0.0

+  - /System/Library/Frameworks/RelevanceKit.framework/RelevanceKit

-  Functions: 51
-  Symbols:   90
-  CStrings:  0
+  Functions: 94
+  Symbols:   112
+  CStrings:  3
Symbols:
+ ___chkstk_darwin
+ ___swift_allocate_value_buffer
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_memcpy17_8
+ ___swift_project_value_buffer
+ __os_log_impl
+ __swiftEmptyArrayStorage
+ __swift_stdlib_malloc_size
+ _malloc_size
+ _memcpy
+ _os_log_type_enabled
+ _swift_bridgeObjectRetain
+ _swift_getObjectType
+ _swift_release
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_unknownObjectRetain
+ _symbolic Sb
+ _symbolic Si
+ _symbolic _____ 20SmartStackUIServices19CardGlassDefinitionV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _type_layout_string 20SmartStackUIServices19CardGlassDefinitionV
CStrings:
+ "Selected glass subvariant '%{public}s' (suppressForeground=%{bool}d, layerId=%ld)"
+ "com.apple.NanoHomeScreen"
+ "watchSmartStackAnimatedContent"
```
