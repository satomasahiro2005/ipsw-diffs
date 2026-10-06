## PermissionKit

> `/System/Library/Frameworks/PermissionKit.framework/PermissionKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ef1c` | `0x1f5a4` | **`+0x688`** |
| `__AUTH_CONST.__const` | `0xfb8` | `0x1158` | **`+0x1a0`** |
| `__TEXT.__const` | `0x2570` | `0x2698` | **`+0x128`** |
| `__DATA.__bss` | `0x3f80` | `0x4080` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x3f8` | `0x4b0` | **`+0xb8`** |
| `__AUTH.__data` | `0x128` | `0x1d8` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x878` | `0x91c` | **`+0xa4`** |
| `__TEXT.__cstring` | `0x62f` | `0x58f` | **`-0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x6d8` | `0x778` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x973` | `0xa01` | **`+0x8e`** |
| `__TEXT.__swift5_reflstr` | `0x35e` | `0x3e6` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x898` | `0x8f8` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0xac8` | `0xb08` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xa` | `0x43` | **`+0x39`** |
| `__DATA.__data` | `0x780` | `0x7a8` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `—` | `0x28` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x9f8` | `0xa08` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xc0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x210` | `0x218` | **`+0x8`** |

### Other Changes

```diff

-93.0.0.0.0
+96.0.0.0.0

-  Functions: 739
-  Symbols:   454
-  CStrings:  33
+  Functions: 772
+  Symbols:   473
+  CStrings:  32
Symbols:
+ __DATA__TtC13PermissionKit30SignificantChangeResultResumer
+ __IVARS__TtC13PermissionKit30SignificantChangeResultResumer
+ __METACLASS_DATA__TtC13PermissionKit30SignificantChangeResultResumer
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ ___swift_memcpy4_4
+ _associated conformance 13PermissionKit0A4FlowOSHAASQ
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _symbolic Sb8approved_t
+ _symbolic ScCy__________G 13PermissionKit0A6ResultO s5NeverO
+ _symbolic ScCy__________GSg 13PermissionKit0A6ResultO s5NeverO
+ _symbolic _____ 13PermissionKit0A4FlowO
+ _symbolic _____ 13PermissionKit0A6ResultO
+ _symbolic _____ 13PermissionKit30SignificantChangeResultResumerC
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic _____yScCy__________GSgG 2os21OSAllocatedUnfairLockV 13PermissionKit0E6ResultO s5NeverO
+ _symbolic _____yScCy__________GSg_____G s13ManagedBufferCsRi__rlE 13PermissionKit0C6ResultO s5NeverO So16os_unfair_lock_sV
+ _type_layout_string So16os_unfair_lock_sV
CStrings:
+ "%s Unhandled Handle.Kind"
+ "%s Unknown answer kind"
+ "init(askToAnswerChoiceKind:)"
+ "permissionChoice(from:)"
+ "topic(ofType:from:)"
- "Fatal error"
- "PermissionKit/AskToConversion.swift"
- "PermissionKit/CommunicationHandle.swift"
- "PermissionKit/PermissionChoice.swift"
- "init(_:) Unhandled Handle.Kind"
- "topic(ofType:from:) Unhandled Handle.Kind"
```
