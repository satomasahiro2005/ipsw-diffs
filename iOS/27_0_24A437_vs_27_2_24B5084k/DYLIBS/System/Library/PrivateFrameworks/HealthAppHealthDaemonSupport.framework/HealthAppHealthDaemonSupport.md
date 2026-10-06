## HealthAppHealthDaemonSupport

> `/System/Library/PrivateFrameworks/HealthAppHealthDaemonSupport.framework/HealthAppHealthDaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13e3c` | `0x19d64` | **`+0x5f28`** |
| `__TEXT.__eh_frame` | `0x798` | `0xa70` | **`+0x2d8`** |
| `__AUTH_CONST.__const` | `0x1df0` | `0x1f30` | **`+0x140`** |
| `__AUTH_CONST.__auth_got` | `0x598` | `0x678` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x6a8` | `0x768` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x351` | `0x3f1` | **`+0xa0`** |
| `__TEXT.__const` | `0x980` | `0x9e8` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x14a` | `0x1ab` | **`+0x61`** |
| `__TEXT.__swift5_fieldmd` | `0x268` | `0x2b4` | **`+0x4c`** |
| `__DATA.__data` | `0x550` | `0x590` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x453` | `0x48d` | **`+0x3a`** |
| `__TEXT.__constg_swiftt` | `0x3c8` | `0x3ec` | **`+0x24`** |
| `__TEXT.__swift5_capture` | `0x7ac` | `0x7c0` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x4c` | `0x60` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x38` | `0x4c` | **`+0x14`** |
| `__DATA_CONST.__const` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x34` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  - /System/Library/PrivateFrameworks/HealthOrchestration.framework/HealthOrchestration

+  - /usr/lib/swift/libswiftCoreAudio.dylib

+  - /usr/lib/swift/libswiftCoreImage.dylib

-  Functions: 741
-  Symbols:   352
-  CStrings:  29
+  Functions: 790
+  Symbols:   363
+  CStrings:  32
Symbols:
+ _OBJC_CLASS_$_HPFUserInteractionFetchRequestXPCTransport
+ ___swift_closure_destructor.15Tm
+ ___swift_memcpy72_8
+ __swiftEmptySetSingleton
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreAudio_$_HealthAppHealthDaemonSupport
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_HealthAppHealthDaemonSupport
+ _swift_dynamicCastClass
+ _swift_release_x10
+ _swift_release_x12
+ _swift_retain
+ _symbolic Say_____G 10Foundation4UUIDV
+ _symbolic So42HPFUserInteractionFetchRequestXPCTransportC
+ _symbolic _____ 09HealthAppA13DaemonSupport29CustomPinnedContentIdentifierO
- ___swift_closure_destructor.11Tm
- ___swift_closure_destructor.8Tm
- ___swift_memcpy32_8
- _symbolic _____ 10Foundation4UUIDV
CStrings:
+ "Expected an HAHDAwakeningInputSignalRegistrarServerInterface proxy, got "
+ "Expected an HAHDUserInteractionStoreServerInterface proxy, got "
+ "HKObjectType_CycleTrackingCustom"
+ "fetchInteractions(_:)"
+ "softDeleteInteractions(uuids:)"
- "fetchInteractions(featureIdentifier:itemIdentifier:)"
- "softDeleteInteraction(uuid:)"
```
