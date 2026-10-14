## AVFCore

> `/System/Library/PrivateFrameworks/AVFCore.framework/AVFCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ca4ec` | `0x1ca874` | **`+0x388`** |
| `__TEXT.__oslogstring` | `0x50ad` | `0x5128` | **`+0x7b`** |
| `__DATA_CONST.__const` | `0x5bb8` | `0x5be0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xa02c` | `0xa044` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xb6b0` | `0xb6b8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1c2f4` | `0x1c2fc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa578` | `0xa580` | **`+0x8`** |

### Other Changes

```diff

-2475.12.1.0.0
+2475.13.1.1.0

-  Functions: 12121
-  Symbols:   23982
-  CStrings:  4303
+  Functions: 12122
+  Symbols:   23984
+  CStrings:  4304
Symbols:
+ -[AVPlayerItemIntegratedTimelinePeriodicObserver _doesTimeResideInPrimarySegment:atTime:timeMappingOut:]
+ ___block_descriptor_57_e8_32o40r48r_e5_v8?0ls32l8r40l8r48l8
Functions:
~ -[AVSampleBufferVideoRenderer _setRequiresFlushToResumeDecoding:] : 708 -> 1104
~ ___65-[AVSampleBufferVideoRenderer _setRequiresFlushToResumeDecoding:]_block_invoke : 44 -> 112
~ -[AVPlayerItemIntegratedTimelinePeriodicObserver rescheduleObserverWithSnapshot:itemToSchedule:] : 1984 -> 2120
+ -[AVPlayerItemIntegratedTimelinePeriodicObserver _doesTimeResideInPrimarySegment:atTime:timeMappingOut:]
CStrings:
+ "<<<< AVSampleBufferVideoRenderer >>>> %s: <%{public}@|%p> Waking a suspended Swift enqueue because a flush is now required"
```
