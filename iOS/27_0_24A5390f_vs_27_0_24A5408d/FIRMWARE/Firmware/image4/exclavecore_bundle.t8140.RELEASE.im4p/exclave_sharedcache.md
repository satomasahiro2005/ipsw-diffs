## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xece2c8` | `0xeb49d4` | **`-0x198f4`** |
| `__DATA.__const` | `0x142370` | `0x13b978` | **`-0x69f8`** |
| `__TEXT.__swift5_capture` | `0x6a68` | `0x3738` | **`-0x3330`** |
| `__TEXT.__const` | `0x1e8834` | `0x1eb9d4` | **`+0x31a0`** |
| `__PDATA.__bss` | `0xc4b8` | `0xba48` | **`-0xa70`** |
| `__DATA.__bss` | `0x24890` | `0x24f70` | **`+0x6e0`** |
| `__TEXT.__swift5_fieldmd` | `0x795c4` | `0x79c5c` | **`+0x698`** |
| `__TEXT.__eh_frame` | `0x80958` | `0x80dec` | **`+0x494`** |
| `__TEXT.__swift5_reflstr` | `0x497e8` | `0x49b68` | **`+0x380`** |
| `__TEXT.__constg_swiftt` | `0x71ab8` | `0x71dc4` | **`+0x30c`** |
| `__TEXT.__swift5_typeref` | `0x30cb2` | `0x30f0a` | **`+0x258`** |
| `__TEXT.__swift5_assocty` | `0xf800` | `0xfa30` | **`+0x230`** |
| `__TEXT.__swift5_proto` | `0xbc38` | `0xbe10` | **`+0x1d8`** |
| `__DATA.__data` | `0x5b6a8` | `0x5b808` | **`+0x160`** |
| `__DATA.__ENDPOINTS` | `0x1b6ad` | `0x1b7b4` | **`+0x107`** |
| `__DATA.__auth_ptr` | `0x7bb8` | `0x7c70` | **`+0xb8`** |
| `__TEXT.__swift5_types` | `0x7740` | `0x77ec` | **`+0xac`** |
| `__TEXT.__oslogstring` | `0x6fa7` | `0x7025` | **`+0x7e`** |
| `__TEXT.__cstring` | `0xaeff1` | `0xaefb1` | **`-0x40`** |
| `__TEXT.__swift5_builtin` | `0x2b5c` | `0x2b84` | **`+0x28`** |
| `__TEXT.__swift5_mpenum` | `0xd90` | `0xda8` | **`+0x18`** |
| `__TEXT.__swift5_protos` | `0x148c` | `0x1494` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__PDATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1777.0.20.0.0
-  Functions: 52586
+1777.0.27.0.0
+  Functions: 52735

-  CStrings:  16312
+  CStrings:  16317
CStrings:
+ "\n    Background factors: last="
+ " -> calculated XYZ:"
+ " [nits]\n    Indicator factors: last="
+ " sample is invalid, using max sample (lux="
+ " transitioning disabled -> ready"
+ " transitioning executing -> ready"
+ "%llx %llx %llx"
+ ", BackgroundColor="
+ ", IndicatorColor="
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Mon Aug  3 22:27:24 PDT 2026; root:AppleImage4_exclavecore-374~17057/ExclaveImage4/RELEASE_ARM64E"
+ "ANEExclave version: ANEExclave_exclavecore-13.18.1"
+ "Build Date: Mon Aug  3 22:03:24 PDT 2026"
+ "Calculated XYZ and supplied XYZ for background color are too far from each other, original RGB:"
+ "Calculated XYZ and supplied XYZ for indicator color are too far from each other, original RGB:"
+ "Can't skip by a negative offset"
+ "Chill pill usage is "
+ "CryptoKit/Ed448Keys_cc.swift"
+ "CryptoKit/X25519Keys_cc.swift"
+ "CryptoKit/X448Keys_cc.swift"
+ "Directory not present (probe): "
+ "EXBrightComponent/EXBrightComponent_swift.swift"
+ "EXBrightComponent/Extensions.swift"
+ "EXBrightDefines/EXBrightDefines_swift.swift"
+ "EXBrightDisplayPipeClient/EXBrightDisplayPipeClient_swift.swift"
+ "EXBrightPILEICClient/EXBrightPILEICClient_swift.swift"
+ "Escaping Closure Propagated"
+ "ExclaveOS Image4 Framework Version 7.0.0: Mon Aug  3 22:27:24 PDT 2026; root:AppleImage4_exclavecore-374~17057/ExclaveImage4/RELEASE_ARM64E"
+ "ExclaveSISP-6.18"
+ "Failed to calibrate sensor(s), setting dispatchUpcallOnSILEnabled=true"
+ "MMIO read: addr=%p value=0x%llx"
+ "MMIO read: addr=%p value=0x%x"
+ "MMIO write: addr=%p value=0x%x"
+ "MNISTPersistentPower"
+ "No Resource Available"
+ "Queue size must > 0"
+ "SCA: applying lower thresholds"
+ "SCA: restoring normal thresholds (lower thresholds window ended)"
+ "Swift/BorrowingSequence.swift"
+ "Tue Aug  4 06:17:40 PDT 2026"
+ "[EIC] MMIO read: addr=%p value=0x%llx\n"
+ "[EIC] MMIO read: addr=%p value=0x%x\n"
+ "[EIC] MMIO write: addr=%p value=0x%x\n"
+ "] Brightness health nil when expecting a value - setting to false"
+ "] Cannot estimate ramp duration, invalid target brightness value: "
+ "] Contrast Health "
+ "] Contrast failure session began"
+ "] Contrast failure session continuing, passing since "
+ "] Contrast failure session ending"
+ "] Contrast failure session longer than grace period for applying soft boundary, reporting failure"
+ "] Contrast failure session still in grace period ("
+ "] Contrast health for frame #"
+ "] ContrastCheckResult="
+ "] Failed to create BrightnessUtil, health checks will not be available!"
+ "] Hibernation count has changed, reporting bad health"
+ "] Indicator Brightness Health "
+ "] Indicator brightness health for frame #"
+ "] No MIB before first sample, ignoring .failureNoMIB"
+ "] Overflow when substracting timestamps, frame ts: "
+ "] Received MIB with SIL off"
+ "] SCA factor is 0, requesting soft boundary"
+ "] SIL not enabled when requesting soft boundary"
+ "] Setting UI Brightness "
+ "] Soft boundary minimum ontime not met"
+ "] Switched to MIB ramp up mode during brightness ramp down, ignoring this frame."
+ "] Underflow in contrast failure session recovery check, "
+ "] Underflow in soft boundary SIL session start grace period evaluation - "
+ "] Underflow when checking minimum ontime for soft boundary"
+ "] Waking up from hibernation with soft boundary state as enabled!"
+ "] We have received empty array of frames for health check!"
+ "][EXDisplayPipe Utilization] Health Check took "
+ "][evaluateContrastHealth] Contrast is progressing, returning success"
+ "][healthCheckMode] .rampUp -> .steady. Ctx: adjustedIBNitsFiltered="
+ "init(distributedTrigger) completed: registered "
+ "init(gst) completed: registered "
+ "minItems must be >= 1"
+ "octopus_chill_pill_stability"
- "\n    Background RGB: last="
- " [nits]\n    Indicator RGB: last="
- " transitioning to ready state"
- ", BackgroundRGB="
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Wed Jul 15 23:43:44 PDT 2026; root:AppleImage4_exclavecore-374~12685/ExclaveImage4/RELEASE_ARM64E"
- "ANEExclave version: ANEExclave_exclavecore-13.17.1"
- "Brightness health nil when expecting a value - setting to false"
- "Build Date: Wed Jul 15 22:52:19 PDT 2026"
- "Cannot estimate ramp duration, invalid target brightness value: "
- "Contrast Health "
- "Contrast failure session began"
- "Contrast failure session continuing, passing since "
- "Contrast failure session ending"
- "Contrast failure session longer than grace period for applying soft boundary, reporting failure"
- "Contrast failure session still in grace period ("
- "Contrast health for frame #"
- "ContrastCheckResult="
- "EXBrightComponent/EXBrightComponent_Swift.swift"
- "EXBrightDisplayPipeClient/EXBrightDisplayPipeClient_Swift.swift"
- "EXBrightPILEICClient/EXBrightPILEICClient_Swift.swift"
- "ExclaveOS Image4 Framework Version 7.0.0: Wed Jul 15 23:43:44 PDT 2026; root:AppleImage4_exclavecore-374~12685/ExclaveImage4/RELEASE_ARM64E"
- "ExclaveSISP-6.14.1"
- "Failed to create BrightnessUtil, health checks will not be available!"
- "Hibernation count has changed, reporting bad health"
- "Indicator Brightness Health "
- "Indicator brightness health for frame #"
- "MMIO Write: addr=%p value=0x%x"
- "No MIB before first sample, ignoring .failureNoMIB"
- "Overflow when substracting timestamps, frame ts: "
- "Received MIB with SIL off"
- "SCA factor is 0, requesting soft boundary"
- "SIL not enabled when requesting soft boundary"
- "Setting UI Brightness "
- "Soft boundary minimum ontime not met"
- "Switched to MIB ramp up mode during brightness ramp down, ignoring this frame."
- "Thu Jul 16 00:30:13 PDT 2026"
- "Underflow in contrast failure session recovery check, "
- "Underflow in soft boundary SIL session start grace period evaluation - "
- "Underflow when checking minimum ontime for soft boundary"
- "Unexpected size!"
- "Waking up from hibernation with soft boundary state as enabled!"
- "We have received empty array of frames for health check!"
- "[EIC] MMIO Write: addr=%p value=0x%x\n"
- "[EXDisplayPipe Utilization] Health Check took "
- "[evaluateContrastHealth] Contrast is progressing, returning success"
- "[healthCheckMode] .rampUp -> .steady. Ctx: adjustedIBNitsFiltered="
- "acquireReaderResource(readerId:frameId:)"
- "beginExecution(modeId:)"
- "buildController(_:clientId:executor:defaultMode:)"
- "cId:%u gId:%u fId:%llu qos:%u"
- "completeExecution(modeId:)"
- "connectGlobalDependency(triggerSender:graph:)"
- "connectOutputs(descriptions:)"
- "connectSessionDependency(triggerSender:graph:)"
- "connectSessionInputs(dependencyId:graph:connectedModes:)"
- "consumeRunnableReceivers()"
- "handleModeChangeRequest(_:)"
- "handleTrigger(_:)"
- "init completed: registered "
- "init(clientId:distributedTriggerService:auxiliaryExecutionContext:pbsClientManager:graphTriggerConfigs:writerTriggerConfigs:preallocationConfig:)"
- "init(clientId:graphDescription:executor:)"
- "init(clientId:graphs:writers:readers:gstService:pbsService:powerManager:writersInfo:readersInfo:lifeCycleCallback:)"
- "init(clientId:gstService:pbsService:powerManager:writers:readers:resourceConfigs:graphTriggerConfigs:writerTriggerConfigs:preallocationConfig:)"
- "init(graphs:writers:readers:sessionManager:)"
- "init(taskRegistry:)"
- "processControlSignals(controlSignals:)"
- "releaseAssertion(for:)"
- "relinquishWriterResource(writerId:index:frameId:)"
- "settleAndDisableGraph()"
- "takeAssertion(for:)"
- "updateGraphs(added:removed:)"
```
