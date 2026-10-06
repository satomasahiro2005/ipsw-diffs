## FrontBoard

> `/System/Library/PrivateFrameworks/FrontBoard.framework/FrontBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83994` | `0x840ac` | **`+0x718`** |
| `__TEXT.__cstring` | `0xb2be` | `0xb4cf` | **`+0x211`** |
| `__AUTH_CONST.__cfstring` | `0x8de0` | `0x8ec0` | **`+0xe0`** |
| `__DATA_DIRTY.__objc_data` | `0xeb0` | `0xe60` | **`-0x50`** |
| `__AUTH_CONST.__objc_const` | `0xb698` | `0xb650` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0xdcc` | `0xd8c` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x2818` | `0x2848` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x3800` | `0x3828` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x5ac0` | `0x5a98` | **`-0x28`** |
| `__TEXT.__oslogstring` | `0x6187` | `0x6176` | **`-0x11`** |
| `__TEXT.__unwind_info` | `0x2000` | `0x2010` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x94c` | `0x954` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x910` | `0x908` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2b8` | `0x2b0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x228` | `0x220` | **`-0x8`** |

### Other Changes

```diff

-1150.0.0.0.0
+1153.0.0.0.0

-  Functions: 3160
-  Symbols:   4765
-  CStrings:  1765
+  Functions: 3170
+  Symbols:   4766
+  CStrings:  1774
Symbols:
+ -[FBProcess allowsTerminatingOnWatchdogViolations]
+ -[FBSystemService _beginFetchBTLPMTimeout]
+ -[FBSystemService _bluetoothLPMTimeoutWithFetchTimeout:]
+ -[FBWorkspaceDomain allowsTerminatingOnWatchdogViolations]
+ -[FBWorkspaceScene _workspaceQueue_createWatchdogForProcess:sceneAction:settings:transitionContext:]
+ GCC_except_table18
+ GCC_except_table21
+ GCC_except_table4
+ GCC_except_table45
+ GCC_except_table69
+ GCC_except_table72
+ GCC_except_table92
+ _NSStringFromFBSDefaultWatchdogBehavior
+ _OBJC_IVAR_$_FBSystemService._BTLPMTimeout
+ _OBJC_IVAR_$_FBSystemService._BTLPMTimeoutFetchGroup
+ _OBJC_IVAR_$_FBWorkspaceDomain._allowsTerminatingOnWatchdogViolations
+ _OBJC_IVAR_$_FBWorkspaceScene._isUISubclass
+ _OBJC_IVAR_$_FBWorkspaceScene._queue_allWatchdogs
+ _OBJC_IVAR_$_FBWorkspaceScene._queue_watchdogStack
+ ___100-[FBWorkspaceScene _workspaceQueue_createWatchdogForProcess:sceneAction:settings:transitionContext:]_block_invoke
+ ___100-[FBWorkspaceScene _workspaceQueue_createWatchdogForProcess:sceneAction:settings:transitionContext:]_block_invoke_2
+ ___42-[FBSystemService _beginFetchBTLPMTimeout]_block_invoke
+ ___46-[FBSystemService shutdownWithOptions:origin:]_block_invoke_6
+ ___46-[FBSystemService shutdownWithOptions:origin:]_block_invoke_7
+ ___block_descriptor_33_e56_v24?0"NSObject<OS_dispatch_queue>"8?<v?"NSError">16l
+ ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s_e34_v16?0"<FBProcessBootstrapping>"8ls32l8s40l8
+ ___block_descriptor_93_e8_32s40s48s56s64s72s80bs_e46_v16?0"<FBSWorkspaceServiceServerInterface>"8ls32l8s40l8s48l8s56l8s80l8s64l8s72l8
+ _getCBControllerClass
+ _getCBControllerLowPowerModeCompletionTimeoutSeconds
- -[FBUIApplicationWorkspaceScene .cxx_destruct]
- -[FBUIApplicationWorkspaceScene _workspaceQueue_cancelWatchdogTimer:]
- -[FBUIApplicationWorkspaceScene _workspaceQueue_createWatchdogForProcess:sceneAction:transitionContext:]
- -[FBUIApplicationWorkspaceScene _workspaceQueue_invalidate]
- -[FBUIApplicationWorkspaceScene initWithConnection:host:settings:clientSettings:fromRemnant:]
- -[FBWorkspaceScene _workspaceQueue_createWatchdogForProcess:sceneAction:transitionContext:]
- GCC_except_table10
- GCC_except_table15
- GCC_except_table34
- GCC_except_table55
- GCC_except_table67
- GCC_except_table70
- GCC_except_table91
- _OBJC_CLASS_$_FBUIApplicationWorkspaceScene
- _OBJC_IVAR_$_FBUIApplicationWorkspaceScene._allWatchdogs
- _OBJC_IVAR_$_FBUIApplicationWorkspaceScene._sentSceneCreate
- _OBJC_IVAR_$_FBUIApplicationWorkspaceScene._watchdogStack
- _OBJC_IVAR_$_FBWorkspaceScene._lock_sentSceneCreate
- _OBJC_METACLASS_$_FBUIApplicationWorkspaceScene
- __OBJC_$_INSTANCE_METHODS_FBUIApplicationWorkspaceScene
- __OBJC_$_INSTANCE_VARIABLES_FBUIApplicationWorkspaceScene
- __OBJC_CLASS_RO_$_FBUIApplicationWorkspaceScene
- __OBJC_METACLASS_RO_$_FBUIApplicationWorkspaceScene
- ___104-[FBUIApplicationWorkspaceScene _workspaceQueue_createWatchdogForProcess:sceneAction:transitionContext:]_block_invoke
- ___104-[FBUIApplicationWorkspaceScene _workspaceQueue_createWatchdogForProcess:sceneAction:transitionContext:]_block_invoke_2
- ___block_descriptor_48_e8_32s40s_e34_v16?0"<FBProcessBootstrapping>"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48r_e17_v16?0"NSError"8lr48l8s32l8s40l8
- ___block_descriptor_85_e8_32s40s48s56s64s72bs_e46_v16?0"<FBSWorkspaceServiceServerInterface>"8ls32l8s40l8s48l8s72l8s56l8s64l8
- _getkNISystemShutdownCompletionTimeoutSeconds
CStrings:
+ "AllowTerminatingOnWatchdogViolations"
+ "BOOL _shouldRunWatchdog(FBProcess *__strong, _FBSceneAction, FBSSceneSettings *__strong, BOOL, FBWatchdogTransitionContext *__strong)"
+ "CoreBluetooth error activating controller: %{public}@"
+ "Create Active"
+ "Create Inactive"
+ "Got BT LPM timeout %ds"
+ "already have a source registered for pid=%i: new=%@:%@ existing=%@:%@"
+ "attempting to add a process with a pid that is already tracked : new=<%p %@:%@> existing=<%p %@:%@>"
+ "attempting to add a process with a vpid that is already tracked : new=<%p %@:%@> existing=<%p %@:%@>"
+ "unknown sceneBehavior (%@) for action=%@ on %@"
+ "unknown transitionBehavior (%@) for action=%@ on %@"
+ "\x81"
- "CoreBluetooth error activating controller: %@"
- "CoreBluetooth query for LPM completion timeout."
- "already have a source registered for %@: %@"
```
