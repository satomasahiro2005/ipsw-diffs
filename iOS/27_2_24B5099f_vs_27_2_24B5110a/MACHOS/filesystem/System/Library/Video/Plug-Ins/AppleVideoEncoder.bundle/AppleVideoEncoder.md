## AppleVideoEncoder

> `/System/Library/Video/Plug-Ins/AppleVideoEncoder.bundle/AppleVideoEncoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f1bd8` | `0x1f3a58` | **`+0x1e80`** |
| `__TEXT.__cstring` | `0x5bde2` | `0x5c359` | **`+0x577`** |
| `__DATA_CONST.__const` | `0xdd10` | `0xddd0` | **`+0xc0`** |
| `__DATA_CONST.__cfstring` | `0x3640` | `0x3660` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa18` | `0xa20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-913.63.1.0.0
+913.64.1.0.0

-  Functions: 1986
+  Functions: 1994

-  CStrings:  7587
+  CStrings:  7612
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
+ "01:15:18"
+ "01:15:21"
+ "01:15:22"
+ "01:15:23"
+ "913.64.1"
+ "AVE_Prop_AV1_GetMachThreadPriorityForThreadEmittingFrames"
+ "AVE_Prop_AV1_SetMachThreadPriorityForThreadEmittingFrames"
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
- "20:40:45"
- "20:40:48"
- "20:40:50"
- "913.63.1"
- "Sep 27 2026"
```
