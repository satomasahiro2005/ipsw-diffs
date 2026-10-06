## TrustedClockingServices

> `/System/Library/PrivateFrameworks/TrustedClockingServices.framework/TrustedClockingServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11688` | `0x11aa0` | **`+0x418`** |
| `__TEXT.__cstring` | `0x1cac` | `0x1dac` | **`+0x100`** |
| `__TEXT.__gcc_except_tab` | `0x4c8` | `0x570` | **`+0xa8`** |
| `__AUTH_CONST.__objc_const` | `0x1bf0` | `0x1c90` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x76c` | `0x7dc` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x360` | `0x3c0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f8` | `0x348` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x768` | `0x7a8` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x6a0` | `0x6b8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x64` | `0x74` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x150` | `0x160` | **`+0x10`** |

### Other Changes

```diff

-95.0.0.0.0
+95.202.0.0.0

-  Functions: 610
-  Symbols:   780
-  CStrings:  134
+  Functions: 618
+  Symbols:   801
+  CStrings:  137
Symbols:
+ -[TrustedClockingManager beginQoSOverrideWithClass:forUseCaseID:]
+ -[TrustedClockingManager endQoSOverrideForUseCaseID:]
+ -[TrustedClockingManager setThreadsByUseCase:]
+ -[TrustedClockingManager threadsByUseCase]
+ -[TrustedClockingThread beginQoSOverrideWithClass:]
+ -[TrustedClockingThread endActiveQoSOverride]
+ -[TrustedClockingThread endQoSOverride]
+ GCC_except_table17
+ GCC_except_table19
+ GCC_except_table24
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_IVAR_$_TrustedClockingManager._threadsByUseCase
+ _OBJC_IVAR_$_TrustedClockingThread._activeOverride
+ _OBJC_IVAR_$_TrustedClockingThread._overrideMutex
+ _OBJC_IVAR_$_TrustedClockingThread._threadHandle
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TrustedClockingThreadProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TrustedClockingThreadProtocol
+ __ZNK5caulk6thread13native_handleEv
+ _objc_opt_new
+ _objc_retain_x26
+ _objc_retain_x28
+ _pthread_override_qos_class_end_np
+ _pthread_override_qos_class_start_np
+ _pthread_self
- GCC_except_table20
- _objc_release_x26
- _objc_retain_x22
- _objc_retain_x25
CStrings:
+ "TrustedClockingManager: No thread registered for useCaseID %u, cannot begin QoS override"
+ "TrustedClockingManager: No thread registered for useCaseID %u, ignoring endQoSOverride"
+ "TrustedClockingThread::beginQoSOverrideWithClass: Failed to start override for qosClass %u"
+ "\x97"
- "\x96"
```
