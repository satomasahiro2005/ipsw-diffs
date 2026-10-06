## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e784c` | `0x5eb0ec` | **`+0x38a0`** |
| `__PDATA.__bss` | `0xc4b8` | `0xba48` | **`-0xa70`** |
| `__TEXT.__const` | `0x1221a4` | `0x1228b4` | **`+0x710`** |
| `__DATA.__const` | `0x3d1f0` | `0x3d678` | **`+0x488`** |
| `__TEXT.__cstring` | `0x4f381` | `0x4f671` | **`+0x2f0`** |
| `__DATA.__bss` | `0xe3e0` | `0xe6c0` | **`+0x2e0`** |
| `__TEXT.__eh_frame` | `0x35038` | `0x35238` | **`+0x200`** |
| `__TEXT.__swift5_fieldmd` | `0x1c010` | `0x1c18c` | **`+0x17c`** |
| `__TEXT.__swift5_typeref` | `0x14022` | `0x14190` | **`+0x16e`** |
| `__TEXT.__swift5_reflstr` | `0x11f68` | `0x120a8` | **`+0x140`** |
| `__TEXT.__swift5_assocty` | `0x7a20` | `0x7b48` | **`+0x128`** |
| `__DATA.__ENDPOINTS` | `0x1a221` | `0x1a328` | **`+0x107`** |
| `__TEXT.__swift5_proto` | `0x3cb4` | `0x3d98` | **`+0xe4`** |
| `__TEXT.__constg_swiftt` | `0x27e80` | `0x27f0c` | **`+0x8c`** |
| `__DATA.__data` | `0x186e8` | `0x18770` | **`+0x88`** |
| `__TEXT.__oslogstring` | `0xb5` | `0xf3` | **`+0x3e`** |
| `__DATA.__auth_ptr` | `0x2338` | `0x2368` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x1590` | `0x15b8` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x2474` | `0x2490` | **`+0x1c`** |
| `__TEXT.__swift5_mpenum` | `0x39c` | `0x3b4` | **`+0x18`** |
| `__DATA.__common` | `0x71a` | `0x72a` | **`+0x10`** |
| `__TEXT.__chain_fixups` | `0xb0` | `0xb8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x970` | `0x978` | **`+0x8`** |

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
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1777.0.20.0.0
-  Functions: 22941
+1777.0.27.0.0
+  Functions: 22984

-  CStrings:  7292
+  CStrings:  7310
CStrings:
+ "\n    Background factors: last="
+ " -> calculated XYZ:"
+ " [nits]\n    Indicator factors: last="
+ " sample is invalid, using max sample (lux="
+ ", BackgroundColor="
+ ", IndicatorColor="
+ "Calculated XYZ and supplied XYZ for background color are too far from each other, original RGB:"
+ "Calculated XYZ and supplied XYZ for indicator color are too far from each other, original RGB:"
+ "Can't skip by a negative offset"
+ "Chill pill usage is "
+ "EXBrightComponent/EXBrightComponent_swift.swift"
+ "EXBrightComponent/Extensions.swift"
+ "EXBrightDefines/EXBrightDefines_swift.swift"
+ "EXBrightDisplayPipeClient/EXBrightDisplayPipeClient_swift.swift"
+ "EXBrightPILEICClient/EXBrightPILEICClient_swift.swift"
+ "Escaping Closure Propagated"
+ "Failed to calibrate sensor(s), setting dispatchUpcallOnSILEnabled=true"
+ "MMIO read: addr=%p value=0x%llx"
+ "MMIO read: addr=%p value=0x%x"
+ "MMIO write: addr=%p value=0x%x"
+ "Queue size must > 0"
+ "Swift/BorrowingSequence.swift"
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
+ "minItems must be >= 1"
+ "octopus_chill_pill_stability"
- "\n    Background RGB: last="
- " [nits]\n    Indicator RGB: last="
- ", BackgroundRGB="
- "Brightness health nil when expecting a value - setting to false"
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
```
