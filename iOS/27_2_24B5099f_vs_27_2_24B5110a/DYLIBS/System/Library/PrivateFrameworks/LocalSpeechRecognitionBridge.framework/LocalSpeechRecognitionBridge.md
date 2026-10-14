## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/LocalSpeechRecognitionBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dab0` | `0x1e068` | **`+0x5b8`** |
| `__TEXT.__oslogstring` | `0x2d3e` | `0x2eb9` | **`+0x17b`** |
| `__TEXT.__cstring` | `0x4b12` | `0x4c65` | **`+0x153`** |
| `__AUTH_CONST.__objc_const` | `0x3d88` | `0x3e28` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x2524` | `0x25a4` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1368` | `0x13b0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1b80` | `0x1bc0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x2d0` | `0x2dc` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x728` | `0x730` | **`+0x8`** |

### Other Changes

```diff

-3605.31.3.0.0
+3605.32.1.0.0

-  Functions: 745
-  Symbols:   1487
-  CStrings:  617
+  Functions: 754
+  Symbols:   1499
+  CStrings:  626
Symbols:
+ -[LBAudioStreamProvider _anchorHostTimeForPacketIndex:inHostTimes:baseIndex:]
+ -[LBAudioStreamProvider _forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]
+ -[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]
+ -[LBAudioStreamProvider previousPacketHostTimesBaseIndex]
+ -[LBAudioStreamProvider previousPacketHostTimes]
+ -[LBAudioStreamProvider previousStreamId]
+ -[LBAudioStreamProvider setPreviousPacketHostTimes:]
+ -[LBAudioStreamProvider setPreviousPacketHostTimesBaseIndex:]
+ -[LBAudioStreamProvider setPreviousStreamId:]
+ GCC_except_table318
+ GCC_except_table335
+ GCC_except_table458
+ GCC_except_table462
+ GCC_except_table468
+ GCC_except_table475
+ GCC_except_table557
+ GCC_except_table677
+ GCC_except_table712
+ GCC_except_table717
+ GCC_except_table722
+ _OBJC_IVAR_$_LBAudioStreamProvider._previousPacketHostTimes
+ _OBJC_IVAR_$_LBAudioStreamProvider._previousPacketHostTimesBaseIndex
+ _OBJC_IVAR_$_LBAudioStreamProvider._previousStreamId
+ ___94-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]_block_invoke
- -[LBAudioStreamProvider _anchorHostTimeForPacketIndex:]
- GCC_except_table312
- GCC_except_table326
- GCC_except_table449
- GCC_except_table453
- GCC_except_table459
- GCC_except_table466
- GCC_except_table548
- GCC_except_table668
- GCC_except_table703
- GCC_except_table708
- GCC_except_table713
CStrings:
+ "%s #stream LBAudioStreamProvider DROP legacy USE, no live stream to attribute it to"
+ "%s #stream LBAudioStreamProvider DROP nil streamId"
+ "%s #stream LBAudioStreamProvider DROP no packet hostTimes tracked for streamId=%@ (stream may not have produced packets yet)"
+ "%s #stream LBAudioStreamProvider DROP unknown streamId=%@ (current=%@, previous=%@)"
+ "%s #stream LBAudioStreamProvider ENTRY (legacy, no streamId) secondsFromEnd=%f lastPacketIndex=%llu"
+ "%s #stream LBAudioStreamProvider ENTRY secondsFromEnd=%f lastPacketIndex=%llu streamId=%@"
+ "%s #stream LBAudioStreamProvider XPC SEND useHostTime=%llu (anchorHostTime=%llu, secondsFromEnd=%f, streamId=%@, stream=%{public}@)"
+ "-[LBAudioStreamProvider _anchorHostTimeForPacketIndex:inHostTimes:baseIndex:]"
+ "-[LBAudioStreamProvider _forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]"
+ "-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]"
+ "-[LBAudioStreamProvider forwardUserSpeakingEndWithSecondsFromEnd:lastPacketIndex:forStreamId:]_block_invoke"
+ "current"
+ "previous"
- "%s #stream LBAudioStreamProvider DROP no packet hostTimes tracked (stream may not have produced packets yet)"
- "%s #stream LBAudioStreamProvider ENTRY secondsFromEnd=%f lastPacketIndex=%llu"
- "%s #stream LBAudioStreamProvider XPC SEND useHostTime=%llu (anchorHostTime=%llu, secondsFromEnd=%f)"
- "-[LBAudioStreamProvider _anchorHostTimeForPacketIndex:]"
```
