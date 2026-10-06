## SpringBoardServices

> `/System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a5ec` | `0x7b5fc` | **`+0x1010`** |
| `__AUTH.__objc_data` | `0x33e0` | `0x3ac0` | **`+0x6e0`** |
| `__DATA_DIRTY.__objc_data` | `0xff0` | `0x960` | **`-0x690`** |
| `__AUTH_CONST.__objc_const` | `0x25b70` | `0x260a8` | **`+0x538`** |
| `__TEXT.__cstring` | `0xdc48` | `0xde60` | **`+0x218`** |
| `__AUTH_CONST.__cfstring` | `0xace0` | `0xaea0` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x4787` | `0x490e` | **`+0x187`** |
| `__TEXT.__objc_methlist` | `0x8a68` | `0x8b58` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3448` | `0x3490` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x29c0` | `0x29f8` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0xc94` | `0xcbc` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3928` | `0x3908` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x864` | `0x874` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8b8` | `0x8c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x6c8` | `0x6d0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x480` | `0x488` | **`+0x8`** |

### Other Changes

```diff

-4621.0.0.0.0
+4626.103.0.0.0

-  Functions: 4274
-  Symbols:   7887
-  CStrings:  2104
+  Functions: 4302
+  Symbols:   7921
+  CStrings:  2126
Symbols:
+ +[SBSAppResizingServiceStatus supportsBSXPCSecureCoding]
+ -[SBSAppResizingService _resetForBrokenConnection]
+ -[SBSAppResizingService addObserver:]
+ -[SBSAppResizingService removeObserver:]
+ -[SBSAppResizingService serverDidUpdateStatus:]
+ -[SBSAppResizingService status]
+ -[SBSAppResizingServiceStatus .cxx_destruct]
+ -[SBSAppResizingServiceStatus description]
+ -[SBSAppResizingServiceStatus encodeWithBSXPCCoder:]
+ -[SBSAppResizingServiceStatus hash]
+ -[SBSAppResizingServiceStatus initWithBSXPCCoder:]
+ -[SBSAppResizingServiceStatus initWithUnavailabilityReasons:resizableApplication:]
+ -[SBSAppResizingServiceStatus isEqual:]
+ -[SBSAppResizingServiceStatus isResizingPossible]
+ -[SBSAppResizingServiceStatus resizableApplication]
+ -[SBSAppResizingServiceStatus unavailabilityReasons]
+ -[SBSLockScreenService simulateCaptureLaunchFromSource:bundleIdentifier:completion:]
+ -[SBSLockScreenServiceConnection simulateCaptureLaunchFromSource:bundleIdentifier:completion:]
+ _OBJC_CLASS_$_SBSAppResizingServiceStatus
+ _OBJC_IVAR_$_SBSAppResizingService._lock_observers
+ _OBJC_IVAR_$_SBSAppResizingService._lock_status
+ _OBJC_IVAR_$_SBSAppResizingServiceStatus._resizableApplication
+ _OBJC_IVAR_$_SBSAppResizingServiceStatus._unavailabilityReasons
+ _OBJC_METACLASS_$_SBSAppResizingServiceStatus
+ _OUTLINED_FUNCTION_9
+ _SBSAppResizingUnavailabilityReasonsDescription
+ _SBSCaptureLaunchSimulationErrorDomain
+ __OBJC_$_CLASS_METHODS_SBSAppResizingServiceStatus
+ __OBJC_$_INSTANCE_METHODS_SBSAppResizingServiceStatus
+ __OBJC_$_INSTANCE_VARIABLES_SBSAppResizingServiceStatus
+ __OBJC_$_PROP_LIST_SBSAppResizingServiceStatus
+ __OBJC_CLASS_PROTOCOLS_$_SBSAppResizingServiceStatus
+ __OBJC_CLASS_RO_$_SBSAppResizingServiceStatus
+ __OBJC_METACLASS_RO_$_SBSAppResizingServiceStatus
+ ___94-[SBSLockScreenServiceConnection simulateCaptureLaunchFromSource:bundleIdentifier:completion:]_block_invoke
- ___block_descriptor_48_e8_32s40w_e29_v16?0"BSServiceConnection"8lw40l8s32l8
CStrings:
+ "<%@: %p; resizingPossible: %d; unavailabilityReasons: %@; resizableApplication: %@>"
+ "DeviceUnsupported"
+ "Initializing"
+ "Landscape"
+ "LegacyApplication"
+ "NSString * _Nullable SBSAppResizingUnavailabilityReasonNameForReason(SBSAppResizingUnavailabilityReasons)"
+ "NoApplication"
+ "Other"
+ "SBSAppResizingService: %{public}@"
+ "SBSAppResizingService: committed resolvedSize: %{public}@"
+ "SBSAppResizingService: interrupted"
+ "SBSAppResizingService: minSize: %{public}@; maxSize: %{public}@"
+ "SBSAppResizingService: server ended resizing"
+ "SBSAppResizingServiceStatus.m"
+ "SBSCaptureLaunchSimulationErrorDomain"
+ "SBSLockScreenService: error from request to simulate capture launch : %@"
+ "SBSLockScreenService: failed request to simulate capture launch (no remoteTarget)"
+ "UnderLock"
+ "called simulateCaptureLaunchFromSource:bundleIdentifier:completion: after invalidation"
+ "kResizableApplicationKey"
+ "kUnavailabilityReasonsKey"
+ "unhandled SBSAppResizingUnavailabilityReasons: %ld"
```
