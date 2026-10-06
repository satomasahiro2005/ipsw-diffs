## AmbientUIServices

> `/System/Library/PrivateFrameworks/AmbientUIServices.framework/AmbientUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71d4` | `0x8ce0` | **`+0x1b0c`** |
| `__TEXT.__oslogstring` | `—` | `0x234` | **`+0x234`** |
| `__AUTH_CONST.__objc_const` | `0x15c8` | `0x1700` | **`+0x138`** |
| `__AUTH.__objc_data` | `0x520` | `0x640` | **`+0x120`** |
| `__DATA.__data` | `0x350` | `0x410` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x648` | `0x6c8` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x400` | `0x478` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0x4c8` | `0x450` | **`-0x78`** |
| `__TEXT.__unwind_info` | `0x2d8` | `0x330` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x204` | `0x258` | **`+0x54`** |
| `__TEXT.__const` | `0x2a8` | `0x2f8` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0xb0` | `0x64` | **`-0x4c`** |
| `__AUTH.__data` | `0xc8` | `0xf8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x208` | `0x228` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x174` | `0x154` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xb8` | `0xd4` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x168` | `0x158` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x78` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c0` | `0x3b8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x18` | `0x1c` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x296` | `0x298` | **`+0x2`** |

### Other Changes

```diff

-104.0.0.0.0
+107.0.0.0.0

+  - /System/Library/PrivateFrameworks/SpringBoardFoundation.framework/SpringBoardFoundation

-  Functions: 259
-  Symbols:   396
-  CStrings:  20
+  Functions: 275
+  Symbols:   430
+  CStrings:  30
Symbols:
+ +[AMUIAmbientPosterScenePresentationTriggerSuspensionAction actionWithSuspending:]
+ -[AMUIAmbientPosterScenePresentationTriggerSuspensionAction suspending]
+ _OBJC_CLASS_$_AMUIAmbientPosterScenePresentationTriggerSuspensionAction
+ _OBJC_METACLASS_$_AMUIAmbientPosterScenePresentationTriggerSuspensionAction
+ _OBJC_METACLASS_$__TtC17AmbientUIServicesP33_E8672D477A7D25B25ACDDA034ABBC9D047AmbientPosterPresentationTriggerSuspensionToken
+ __DATA__TtC17AmbientUIServicesP33_E8672D477A7D25B25ACDDA034ABBC9D047AmbientPosterPresentationTriggerSuspensionToken
+ __INSTANCE_METHODS__TtC17AmbientUIServicesP33_E8672D477A7D25B25ACDDA034ABBC9D047AmbientPosterPresentationTriggerSuspensionToken
+ __IVARS__TtC17AmbientUIServicesP33_E8672D477A7D25B25ACDDA034ABBC9D047AmbientPosterPresentationTriggerSuspensionToken
+ __METACLASS_DATA__TtC17AmbientUIServicesP33_E8672D477A7D25B25ACDDA034ABBC9D047AmbientPosterPresentationTriggerSuspensionToken
+ __OBJC_$_CLASS_METHODS_AMUIAmbientPosterScenePresentationTriggerSuspensionAction
+ __OBJC_$_INSTANCE_METHODS_AMUIAmbientPosterScenePresentationTriggerSuspensionAction
+ __OBJC_$_PROP_LIST_AMUIAmbientPosterScenePresentationTriggerSuspensionAction
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BSInvalidatable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BSInvalidatable
+ __OBJC_$_PROTOCOL_REFS_BSInvalidatable
+ __OBJC_CLASS_RO_$_AMUIAmbientPosterScenePresentationTriggerSuspensionAction
+ __OBJC_LABEL_PROTOCOL_$_BSInvalidatable
+ __OBJC_METACLASS_RO_$_AMUIAmbientPosterScenePresentationTriggerSuspensionAction
+ __OBJC_PROTOCOL_$_BSInvalidatable
+ __PROTOCOLS__TtC17AmbientUIServicesP33_E8672D477A7D25B25ACDDA034ABBC9D047AmbientPosterPresentationTriggerSuspensionToken
+ ___swift_allocate_value_buffer
+ ___swift_project_value_buffer
+ __os_log_impl
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_stdlib_malloc_size
+ __swift_stdlib_reportUnimplementedInitializer
+ _malloc_size
+ _memcpy
+ _objc_release_x27
+ _objc_retain_x27
+ _os_log_type_enabled
+ _swift_once
+ _swift_release_x25
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _symbolic Si
+ _symbolic So8NSObjectC
+ _symbolic _____ 17AmbientUIServices0A40PosterPresentationTriggerSuspensionToken33_E8672D477A7D25B25ACDDA034ABBC9D0LLC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic yycSg
- _OBJC_CLASS_$_BSCompoundAssertion
- _keypath_get.13Tm
- _keypath_set.14Tm
- _objc_retain_x28
- _swift_release_x24
- _swift_retain_x19
- _symbolic So19BSCompoundAssertionCySo8NSObjectCGSg
CStrings:
+ "AmbientUIServices.AmbientPosterPresentationTriggerSuspensionToken"
+ "[client] acquirePresentationTriggerSuspensionAssertion — count: %ld"
+ "[client] invalidate — suspensionCount: %ld"
+ "[client] releasePresentationTriggerSuspension — count: %ld"
+ "[client] sendPresentationTriggerSuspensionAction(%s)"
+ "[client] sendPresentationTriggerSuspensionAction(%s) — clientScene nil, dropping"
+ "[host] begin suspension — count: %ld"
+ "[host] end suspension — already at 0, ignoring"
+ "[host] end suspension — count: %ld"
+ "[host] sceneWillDeactivate — suspensionCount: %ld"
+ "init()"
+ "presentationTrigger"
- "ambientPosterScenePresentationTriggerSuspension"
- "presentationTriggerSuspension"
```
