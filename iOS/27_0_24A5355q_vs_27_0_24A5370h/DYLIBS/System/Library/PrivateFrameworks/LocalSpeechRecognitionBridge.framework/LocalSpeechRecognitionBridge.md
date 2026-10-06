## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/LocalSpeechRecognitionBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b618` | `0x1bfb8` | **`+0x9a0`** |
| `__TEXT.__oslogstring` | `0x2617` | `0x297f` | **`+0x368`** |
| `__TEXT.__cstring` | `0x4515` | `0x46e6` | **`+0x1d1`** |
| `__TEXT.__objc_methlist` | `0x23fc` | `0x2494` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x3c40` | `0x3cb8` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x1278` | `0x12e0` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x6d8` | `0x728` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x1940` | `0x1980` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x6a0` | `0x6b0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Other Changes

```diff

-3600.64.114.1.5
+3600.70.8.0.0

-  Functions: 708
-  Symbols:   1437
-  CStrings:  565
+  Functions: 718
+  Symbols:   1454
+  CStrings:  582
Symbols:
+ -[LBAudioStreamConsumer didDetectUserSpeakingEndForRequestId:secondsFromEnd:lastPacketIndex:]
+ -[LBAudioStreamProvider _anchorHostTimeForPacketIndex:]
+ -[LBAudioStreamProvider _recordOutgoingPacketHostTime:]
+ -[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:]
+ -[LBAudioStreamProvider packetHostTimesBaseIndex]
+ -[LBAudioStreamProvider packetHostTimes]
+ -[LBAudioStreamProvider setPacketHostTimes:]
+ -[LBAudioStreamProvider setPacketHostTimesBaseIndex:]
+ GCC_except_table316
+ GCC_except_table437
+ GCC_except_table441
+ GCC_except_table448
+ GCC_except_table527
+ GCC_except_table641
+ GCC_except_table681
+ GCC_except_table686
+ _CSMachAbsoluteTimeSubtractTimeInterval
+ _NSStringFromSelector
+ _OBJC_IVAR_$_LBAudioStreamProvider._packetHostTimes
+ _OBJC_IVAR_$_LBAudioStreamProvider._packetHostTimesBaseIndex
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_LBAudioStreamConsumerServiceDelegate
+ ___82-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:]_block_invoke
+ ___93-[LBAudioStreamConsumer didDetectUserSpeakingEndForRequestId:secondsFromEnd:lastPacketIndex:]_block_invoke
+ ___block_descriptor_56_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_64_e8_32s40w_e5_v8?0lw40l8s32l8
- GCC_except_table308
- GCC_except_table427
- GCC_except_table431
- GCC_except_table438
- GCC_except_table517
- GCC_except_table631
- GCC_except_table666
- GCC_except_table671
CStrings:
+ "%s #stream LBAudioStreamConsumer DROP delegate does not respond to %@ — selector mapping likely missing on delegate %@"
+ "%s #stream LBAudioStreamConsumer DROP weakSelf=nil"
+ "%s #stream LBAudioStreamConsumer XPC RECEIVED requestId=%@ secondsFromEnd=%f lastPacketIndex=%llu"
+ "%s #stream LBAudioStreamProvider DROP invalid secondsFromEnd=%f"
+ "%s #stream LBAudioStreamProvider DROP no packet hostTimes tracked (stream may not have produced packets yet)"
+ "%s #stream LBAudioStreamProvider DROP not-streaming state=%@"
+ "%s #stream LBAudioStreamProvider DROP weakSelf=nil"
+ "%s #stream LBAudioStreamProvider ENTRY secondsFromEnd=%f lastPacketIndex=%llu"
+ "%s #stream LBAudioStreamProvider XPC SEND useHostTime=%llu (anchorHostTime=%llu, secondsFromEnd=%f)"
+ "%s #stream LBAudioStreamProvider peer lastPacketIndex=%llu (%@) outside window (baseIndex=%llu count=%lu); using most recent hostTime=%llu"
+ "-[LBAudioStreamConsumer didDetectUserSpeakingEndForRequestId:secondsFromEnd:lastPacketIndex:]"
+ "-[LBAudioStreamConsumer didDetectUserSpeakingEndForRequestId:secondsFromEnd:lastPacketIndex:]_block_invoke"
+ "-[LBAudioStreamProvider _anchorHostTimeForPacketIndex:]"
+ "-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:]"
+ "-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:]_block_invoke"
+ "ejected"
+ "newer-than-produced"
```
