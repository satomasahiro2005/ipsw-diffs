## GameControllerServer

> `/System/Library/PrivateFrameworks/GameControllerServer.framework/GameControllerServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xde94` | `0xde48` | **`-0x4c`** |

### Other Changes

```diff

-14.0.14.0.0
+14.0.17.0.0
Functions:
~ -[_GCHapticPlayer processSliceForLogicalDevice:startTime:endTime:] : 2200 -> 2196
~ -[_GCHapticPlayer handleCommand:] : 2948 -> 2932
~ -[_GCHapticClientProxy invalidate] : 544 -> 540
~ ___64-[_GCHapticClientProxy(HapticServer) teardownAndReleaseChannels]_block_invoke : 444 -> 440
~ ___53-[_GCHapticClientProxy(HapticServer) releaseChannels]_block_invoke : 432 -> 428
~ ___60-[_GCHapticClientProxy(HapticServer) requestChannels:reply:]_block_invoke : 1224 -> 1216
~ ___30-[_GCHapticServerManager init]_block_invoke_2 : 832 -> 828
~ ___68-[_GCHapticServerManager acceptNewConnection:fromHapticsEnabledApp:]_block_invoke_2 : 568 -> 564
~ ___55-[_GCHapticServerManager logicalDeviceWasUnregistered:]_block_invoke : 644 -> 640
~ ___55-[_GCHapticServerManager logicalDeviceWasUnregistered:]_block_invoke.23 : 400 -> 396
~ -[_GCHapticServerManager playersHaveImpendingCommandsForStartTime:endTime:] : 396 -> 392
~ -[_GCHapticServerManager processActiveEventsForStartTime:endTime:] : 2472 -> 2440
~ -[_GCHapticServerManager identifyCompletedClients] : 1100 -> 1088
~ ___38-[_GCHapticServerManager enterRunloop]_block_invoke_2 : 432 -> 428
~ -[_GCHapticParameterCurve initWithHapticCommand:] : 712 -> 732
~ -[_GCHapticEvent(Private) valueForNoteParam:inParameters:] : 392 -> 388
~ -[_GCHapticTokenAndParams initWithHapticCommand:] : 480 -> 496
```
