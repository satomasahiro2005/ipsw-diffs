## AudioServerApplication

> `/System/Library/PrivateFrameworks/AudioServerApplication.framework/AudioServerApplication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12848` | `0x1280c` | **`-0x3c`** |

### Other Changes

```diff

-1200.28.0.0.0
+1200.30.0.0.0

-  Symbols:   655
+  Symbols:   656
Symbols:
+ _objc_retain_x28
Functions:
~ -[ASAPlaythrough initWithDevices:usingMainDevice:andClockDevice:withName:isPrivate:usingChannelMapping:] : 1748 -> 1740
~ -[ASAPlaythrough initWithDevices:usingMainDevice:andClockDeviceUID:withName:isPrivate:usingChannelMapping:] : 504 -> 500
~ -[ASAPlaythrough start] : 652 -> 644
~ _InputOutputProc : 948 -> 936
~ -[ASAPlaythrough _createIOContext] : 2640 -> 2696
~ -[ASAPlaythrough _freeIOContext:] : 384 -> 364
~ _CheckAudioBufferList : 112 -> 116
~ -[ASAAudioDevice relatedDeviceObjectIDs] : 284 -> 288
~ -[ASAAudioDevice nominalSampleRates] : 300 -> 304
~ -[ASAAudioDevice nominalSampleRateRanges] : 288 -> 292
~ -[ASAAudioDevice inputStreamObjectIDs] : 276 -> 280
~ -[ASAAudioDevice inputStreams] : 364 -> 360
~ -[ASAAudioDevice outputStreamObjectIDs] : 276 -> 280
~ -[ASAAudioDevice outputStreams] : 364 -> 360
~ -[ASAAudioDevice controlObjectIDs] : 276 -> 280
~ -[ASAAudioDevice controls] : 540 -> 536
~ -[ASAAudioDevice diagnosticDescriptionWithIndent:walkTree:] : 3776 -> 3752
~ -[ASAAudioDevice inputStreamUsageForAudioProc:] : 332 -> 328
~ -[ASAAudioDevice outputStreamUsageForAudioProc:] : 332 -> 328
~ -[ASAStereoPanControl getPanChannel:] : 216 -> 212
~ -[ASAObject ownedObjectIDs] : 284 -> 288
~ -[ASAObject diagnosticDescriptionWithIndent:walkTree:] : 700 -> 696
~ -[ASAPlugin boxObjectIDs] : 276 -> 280
~ -[ASAPlugin boxes] : 364 -> 360
~ -[ASAPlugin audioDeviceObjectIDs] : 280 -> 284
~ -[ASAPlugin audioDevices] : 364 -> 360
~ -[ASAPlugin clockDeviceObjectIDs] : 280 -> 284
~ -[ASAPlugin clockDevices] : 364 -> 360
~ -[ASAPlugin diagnosticDescriptionWithIndent:walkTree:] : 1368 -> 1356
~ -[ASABox audioDeviceObjectIDs] : 284 -> 288
~ -[ASABox audioDevices] : 364 -> 360
~ -[ASABox clockDeviceObjectIDs] : 284 -> 288
~ -[ASABox clockDevices] : 364 -> 360
~ -[ASABox diagnosticDescriptionWithIndent:walkTree:] : 1720 -> 1712
~ -[ASACoreAudio pluginObjectIDs] : 276 -> 280
~ -[ASACoreAudio plugins] : 364 -> 360
~ -[ASACoreAudio boxObjectIDs] : 276 -> 280
~ -[ASACoreAudio boxes] : 364 -> 360
~ -[ASACoreAudio audioDeviceObjectIDs] : 276 -> 280
~ -[ASACoreAudio audioDevices] : 364 -> 360
~ -[ASACoreAudio clockDeviceObjectIDs] : 276 -> 280
~ -[ASACoreAudio clockDevices] : 364 -> 360
~ -[ASACoreAudio diagnosticDescriptionWithIndent:walkTree:] : 1700 -> 1684
~ -[ASAAggregateDevice initWithDevices:usingMainDevice:andClockDevice:withName:withUID:isPrivate:withIsolatedUseCaseID:] : 2084 -> 2076
~ -[ASAAggregateDevice initWithDevices:usingMainDevice:andClockDeviceUID:withName:withUID:isPrivate:withIsolatedUseCaseID:] : 864 -> 860
~ -[ASAClockDevice nominalSampleRates] : 296 -> 300
~ -[ASAClockDevice nominalSampleRateRanges] : 288 -> 292
~ -[ASAClockDevice controlObjectIDs] : 276 -> 280
~ -[ASAClockDevice controls] : 540 -> 536
~ -[ASAClockDevice diagnosticDescriptionWithIndent:walkTree:] : 2096 -> 2088
~ -[ASASelectorControl currentItems] : 352 -> 356
~ -[ASASelectorControl availableItems] : 352 -> 356
~ -[ASASelectorControl diagnosticDescriptionWithIndent:walkTree:] : 1040 -> 1032
~ -[ASAStream availableVirtualFormats] : 304 -> 312
~ -[ASAStream availablePhysicalFormats] : 304 -> 312
~ -[ASAStream controlObjectIDs] : 300 -> 304
~ -[ASAStream controls] : 540 -> 536
~ -[ASAStream diagnosticDescriptionWithIndent:walkTree:] : 4020 -> 4008
```
