## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3476ec` | `0x34ad40` | **`+0x3654`** |
| `__TEXT.__oslogstring` | `0x2d24` | `0x2f94` | **`+0x270`** |
| `__TEXT.__constg_swiftt` | `0x83a0` | `0x85a4` | **`+0x204`** |
| `__AUTH.__objc_data` | `0x3070` | `0x3258` | **`+0x1e8`** |
| `__DATA_DIRTY.__data` | `0x10f0` | `0x12d0` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0xa960` | `0xab00` | **`+0x1a0`** |
| `__AUTH.__data` | `0x4258` | `0x40d0` | **`-0x188`** |
| `__TEXT.__swift5_reflstr` | `0x4e50` | `0x4fd0` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x178a8` | `0x179d0` | **`+0x128`** |
| `__TEXT.__eh_frame` | `0x17290` | `0x17380` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x6290` | `0x6360` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x849d` | `0x855d` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x7890` | `0x7934` | **`+0xa4`** |
| `__DATA.__bss` | `0x26bb8` | `0x26c58` | **`+0xa0`** |
| `__TEXT.__const` | `0x3faa9` | `0x3fb49` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xca48` | `0xcaa8` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x32c4` | `0x3310` | **`+0x4c`** |
| `__DATA.__data` | `0x3d18` | `0x3d48` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2ad0` | `0x2ae0` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x19a0` | `0x19b0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2970` | `0x2980` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1260` | `0x1268` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x7ac` | `0x7b0` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xdcc` | `0xdd0` | **`+0x4`** |

### Other Changes

```diff

-727.3.0.0.0
+727.3.1.0.0

-  Functions: 16051
+  Functions: 16102

-  CStrings:  1646
+  CStrings:  1655
CStrings:
+ "$ioCycleHeadroomMultiplier"
+ "$maxIOCycleHeadroom"
+ "AudioQueue diag [%ld refills, %.*fHz]: dispatchLatency avg=%.*fms max=%.*fms, maxWork=%.*fms, minInFlight=%ld, underflows=%ld, deadlineMisses=%ld, genSkips=%ld, poolReuse=%ld alloc=%ld sizeMiss=%ld freeDepth=%ld, ioCycle=%.*fms bufDur=%.*fms buffersPerIOCycle=%.*f"
+ "AudioQueue missed refill deadline #%ld: emitted silence with %ld buffer(s) pending — refill did not stage within a buffer duration. maxDispatchLatency=%.*fms, maxWork=%.*fms, staged=%ld, ioCycle=%.*fms, buffersPerIOCycle=%.*f stagedTarget=%ld adaptiveFloor=%ld"
+ "AudioQueue session timings (%{public}s): ioBufferDuration=%.*fms (requested %.*fms), outputLatency=%.*fms, headroom=%.*fms, otherAudioPlaying=%{bool}d, bufferDuration=%.*fms, buffersPerIOCycle=%.*f, stagedTarget=%ld, ioCycleFloor=%.*fms, effectivePriming=%.*fms, effectiveMaxBuffered=%.*fms"
+ "AudioQueue underflow #%ld: nothing pending, emitted silence. maxDispatchLatency=%.*fms, maxWork=%.*fms, refills=%ld"
+ "Callback-thread enqueue failed: %d"
+ "TTSSettingsIoCycleHeadroomMultiplier"
+ "TTSSettingsMaxIOCycleHeadroom"
+ "com.apple.Accessibility.TextToSpeech.AudioQueueSessionConfig"
+ "priming"
+ "queue build"
+ "queue start"
+ "route change"
- "$seamFadeDuration"
- "AudioQueue diag [%ld refills, %.*fHz]: dispatchLatency avg=%.*fms max=%.*fms, maxWork=%.*fms, minInFlight=%ld, underflows=%ld, genSkips=%ld, poolReuse=%ld alloc=%ld sizeMiss=%ld freeDepth=%ld"
- "AudioQueue underflow #%ld: injecting silence. maxDispatchLatency=%.*fms, maxWork=%.*fms, minInFlight=%ld, sizeMisses=%ld, refills=%ld"
- "Interleaved mono to %u channels using Accelerate"
- "TTSSettingsSeamFadeDuration"
```
