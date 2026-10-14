## ave.videoencoder

> `/System/Library/VideoCodecs/ave.videoencoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x173c04` | `0x1751dc` | **`+0x15d8`** |
| `__TEXT.__cstring` | `0x4d200` | `0x4d6fa` | **`+0x4fa`** |
| `__AUTH_CONST.__const` | `0x58d0` | `0x5950` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x3060` | `0x3080` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa58` | `0xa60` | **`+0x8`** |

### Other Changes

```diff

-913.63.1.0.0
+913.64.1.0.0

-  Functions: 1541
-  Symbols:   2347
-  CStrings:  6395
+  Functions: 1547
+  Symbols:   2353
+  CStrings:  6417
Symbols:
+ GCC_except_table114
+ __Z36AVE_USL_Drv_SetInitialThreadPriorityPvi
+ __Z57AVE_Prop_AVC_GetMachThreadPriorityForThreadEmittingFramesPvS_PK13__CFAllocatorPK10__CFStringS_
+ __Z57AVE_Prop_AVC_SetMachThreadPriorityForThreadEmittingFramesPvS_PK10__CFStringPKv
+ __Z58AVE_Prop_HEVC_GetMachThreadPriorityForThreadEmittingFramesPvS_PK13__CFAllocatorPK10__CFStringS_
+ __Z58AVE_Prop_HEVC_SetMachThreadPriorityForThreadEmittingFramesPvS_PK10__CFStringPKv
+ __ZN7AVE_DAL24SetInitialThreadPriorityEi
- GCC_except_table112
CStrings:
+ "%lld %d AVE %s: %s:%d %s | H264VideoEncoder Error: AVE_USL_Drv_SetInitialThreadPriority, Null pointer for driver data."
+ "%lld %d AVE %s: %s:%d %s | H264VideoEncoder Error: AVE_USL_Drv_SetInitialThreadPriority, Null pointer for driver data.\n"
+ "%lld %d AVE %s: %s:%d %s | fail to set initial thread priority %p %lld %d %d"
+ "%lld %d AVE %s: %s:%d %s | fail to set initial thread priority %p %lld %d %d\n"
+ "%lld %d AVE %s: %s::%s Enter %p %lld %d"
+ "%lld %d AVE %s: %s::%s Enter %p %lld %d\n"
+ "%lld %d AVE %s: %s::%s Exit %p %lld %d %d"
+ "%lld %d AVE %s: %s::%s Exit %p %lld %d %d\n"
+ "%lld %d AVE %s: ENTER AVE_USL_Drv_SetInitialThreadPriority."
+ "%lld %d AVE %s: ENTER AVE_USL_Drv_SetInitialThreadPriority.\n"
+ "%lld %d AVE %s: EXIT AVE_USL_Drv_SetInitialThreadPriority %d."
+ "%lld %d AVE %s: EXIT AVE_USL_Drv_SetInitialThreadPriority %d.\n"
+ "01:11:56"
+ "913.64.1"
+ "AVE_Prop_AVC_GetMachThreadPriorityForThreadEmittingFrames"
+ "AVE_Prop_AVC_SetMachThreadPriorityForThreadEmittingFrames"
+ "AVE_Prop_HEVC_GetMachThreadPriorityForThreadEmittingFrames"
+ "AVE_Prop_HEVC_SetMachThreadPriorityForThreadEmittingFrames"
+ "AVE_USL_Drv_SetInitialThreadPriority"
+ "MachThreadPriorityForThreadEmittingFrames"
+ "MachThreadPriorityForThreadEmittingFrames = %d\n"
+ "Oct 10 2026"
+ "SetInitialThreadPriority"
+ "kVTCompressionPropertyKey_MachThreadPriorityForThreadEmittingFrames"
+ "priority >= 0"
- "20:36:17"
- "913.63.1"
- "Sep 27 2026"
```
