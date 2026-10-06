## com.apple.dt.DTAIModelRunnerService

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/XPCServices/com.apple.dt.DTAIModelRunnerService.xpc/com.apple.dt.DTAIModelRunnerService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe128` | `0xea18` | **`+0x8f0`** |
| `__DATA.__bss` | `0xf80` | `0x1180` | **`+0x200`** |
| `__DATA_CONST.__const` | `0x588` | `0x6d0` | **`+0x148`** |
| `__TEXT.__const` | `0xa8c` | `0xbac` | **`+0x120`** |
| `__DATA.__objc_const` | `0x308` | `0x1f8` | **`-0x110`** |
| `__DATA.__objc_data` | `0x2f8` | `0x1e8` | **`-0x110`** |
| `__TEXT.__objc_methname` | `0x24b` | `0x197` | **`-0xb4`** |
| `__TEXT.__swift5_fieldmd` | `0x2ac` | `0x320` | **`+0x74`** |
| `__TEXT.__unwind_info` | `0x3d0` | `0x428` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x201` | `0x251` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0xe6` | `0x99` | **`-0x4d`** |
| `__DATA.__data` | `0x3a8` | `0x368` | **`-0x40`** |
| `__TEXT.__objc_classname` | `0xf7` | `0xb7` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x94` | `0x64` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x95a` | `0x98a` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xf0` | `0x118` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x160` | `0x140` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x21d` | `0x231` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x1e8` | `0x1f8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xdc0` | `0xdb0` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x304` | `0x2f4` | **`-0x10`** |
| `__TEXT.__cstring` | `0x5bb` | `0x5cb` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x7c` | `0x8c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x70` | `0x68` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x6e8` | `0x6e0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x18` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0x860` | `0x868` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x64` | `0x60` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-64578.145.1.0.0
+64578.160.1.0.0

-  Functions: 266
-  Symbols:   159
-  CStrings:  129
+  Functions: 299
+  Symbols:   151
+  CStrings:  128
Symbols:
- _objc_allocWithZone
- _objc_release
- _objc_retain_x2
- _objc_retain_x25
- _swift_retain_x20
- _swift_retain_x23
- _swift_retain_x24
- _swift_retain_x27
CStrings:
+ "@72@0:8q16q24q32q40q48@56q64"
+ "CoreAI: (XPC) received specializationConfig value: %ld"
+ "PerfRunner: %@ specializationConfig"
+ "initWithExperimentIterations:loadCount:predictionCount:maxPredictionTime:maxIterationTime:functionName:specializationConfigRawValue:"
+ "runWithModelLocation:completionHandler:"
+ "specializationConfig"
+ "v32@0:8@\"_TtC35com_apple_dt_DTAIModelRunnerService13ModelLocation\"16@?<v@?@\"NSString\">24"
- "@24@0:8@16"
- "@64@0:8q16q24q32q40q48@56"
- "_TtC35com_apple_dt_DTAIModelRunnerService13PerfRunConfig"
- "com_apple_dt_DTAIModelRunnerService.PerfRunConfig"
- "initWithConfig:"
- "initWithExperimentIterations:loadCount:predictionCount:maxPredictionTime:maxIterationTime:functionName:"
- "runWithModelLocation:perfRunConfig:completionHandler:"
- "v40@0:8@\"_TtC35com_apple_dt_DTAIModelRunnerService13ModelLocation\"16@\"_TtC35com_apple_dt_DTAIModelRunnerService13PerfRunConfig\"24@?<v@?@\"NSString\">32"
```
