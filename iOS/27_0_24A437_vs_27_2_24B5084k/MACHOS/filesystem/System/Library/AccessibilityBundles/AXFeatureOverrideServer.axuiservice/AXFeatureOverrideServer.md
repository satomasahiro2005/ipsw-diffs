## AXFeatureOverrideServer

> `/System/Library/AccessibilityBundles/AXFeatureOverrideServer.axuiservice/AXFeatureOverrideServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3304` | `0x5314` | **`+0x2010`** |
| `__DATA.__objc_const` | `0x368` | `0x5a8` | **`+0x240`** |
| `__TEXT.__objc_stubs` | `0xc0` | `0x300` | **`+0x240`** |
| `__DATA_CONST.__const` | `0x218` | `0x418` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x723` | `0x923` | **`+0x200`** |
| `__DATA.__data` | `0x1b0` | `0x380` | **`+0x1d0`** |
| `__TEXT.__objc_methtype` | `0x315` | `0x4a5` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0x117` | `0x27a` | **`+0x163`** |
| `__TEXT.__auth_stubs` | `0x5f0` | `0x710` | **`+0x120`** |
| `__TEXT.__const` | `0x342` | `0x460` | **`+0x11e`** |
| `__DATA.__bss` | `0x2a0` | `0x3a0` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x172` | `0x256` | **`+0xe4`** |
| `__TEXT.__swift5_fieldmd` | `0xd8` | `0x1a4` | **`+0xcc`** |
| `__TEXT.__constg_swiftt` | `0x120` | `0x1c0` | **`+0xa0`** |
| `__TEXT.__objc_classname` | `0x2d` | `0xca` | **`+0x9d`** |
| `__DATA.__objc_selrefs` | `0x158` | `0x1f0` | **`+0x98`** |
| `__DATA_CONST.__auth_got` | `0x300` | `0x390` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x22c` | `0x298` | **`+0x6c`** |
| `__TEXT.__swift5_capture` | `0x10` | `0x78` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x140` | `0x1a8` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x1a5` | `0x205` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x70` | `0xa8` | **`+0x38`** |
| `__DATA.__objc_data` | `0x110` | `0x140` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x148` | `0x178` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x48` | `0x60` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x14` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x18` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 91
-  Symbols:   107
-  CStrings:  112
+  Functions: 142
+  Symbols:   128
+  CStrings:  154
Symbols:
+ _OBJC_CLASS_$_RBSProcessEndowmentInfo
+ _OBJC_CLASS_$_RBSProcessMonitor
+ _OBJC_CLASS_$_RBSProcessPredicate
+ _OBJC_CLASS_$_RBSProcessStateDescriptor
+ _OBJC_CLASS_$_RBSTarget
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ _RBSTaskStateIsRunning
+ _objc_release_x22
+ _objc_release_x26
+ _objc_retain_x22
+ _swift_deallocClassInstance
+ _swift_deletedMethodError
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_n
+ _swift_release_x19
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x8
+ _swift_retain_x19
+ _swift_retain_x21
+ _swift_retain_x22
+ _swift_retain_x23
+ _swift_retain_x24
+ _swift_unknownObjectRelease
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
- _CFNotificationCenterAddObserver
- _CFNotificationCenterGetDarwinNotifyCenter
- _objc_release_x25
- _objc_release_x27
- _objc_release_x9
- _objc_retain_x8
- _swift_release_x27
CStrings:
+ "@52@0:8@16q24@32i40^@44"
+ "No owner pid available; override lifecycle will rely on the session timer only"
+ "Owner backgrounded; suspending override session [%s]"
+ "Owner foregrounded; reinstating override session [%s]"
+ "Owner process terminated; tearing down override session [%s]"
+ "Owning client connection interrupted; tearing down override session"
+ "RBSProcessMonitorConfiguring"
+ "_TtC23AXFeatureOverrideServer23RBSOverrideOwnerMonitor"
+ "_TtC23AXFeatureOverrideServer26AXAccessQueueOverrideTimer"
+ "com.apple.frontboard.visibility"
+ "currentState"
+ "endowmentInfos"
+ "endowmentNamespace"
+ "endowmentNamespaces"
+ "featureProvider"
+ "invalidate"
+ "isSuspended"
+ "monitor"
+ "monitorWithConfiguration:"
+ "ownerClientIdentifier"
+ "ownerMonitor"
+ "ownerMonitorFactory"
+ "ownerPID"
+ "performAsynchronousWritingBlock:"
+ "predicateMatchingTarget:"
+ "setEndowmentNamespaces:"
+ "setEvents:"
+ "setPredicates:"
+ "setPreventLaunchUpdateHandle:"
+ "setServiceClass:"
+ "setStateDescriptor:"
+ "setUpdateHandler:"
+ "setValues:"
+ "state"
+ "targetWithPid:"
+ "taskState"
+ "timer"
+ "timerFactory"
+ "v16@?0@\"<RBSProcessMonitorConfiguring>\"8"
+ "v20@0:8I16"
+ "v24@0:8@\"NSArray\"16"
+ "v24@0:8@\"RBSProcessStateDescriptor\"16"
+ "v24@0:8@?16"
+ "v24@0:8@?<v@?@\"RBSProcessMonitor\"@\"NSSet\">16"
+ "v24@0:8@?<v@?@\"RBSProcessMonitor\"@\"RBSProcessHandle\"@\"RBSProcessStateUpdate\">16"
+ "v24@0:8Q16"
+ "v32@?0@\"RBSProcessMonitor\"8@\"RBSProcessHandle\"16@\"RBSProcessStateUpdate\"24"
- "Observed application state change"
- "Reverting to prior feature enablement and removing active overrides"
- "SBSubstantialTransitionNotification"
- "applicationStateChanged"
- "com.apple.mobile.SubstantialTransition"
```
