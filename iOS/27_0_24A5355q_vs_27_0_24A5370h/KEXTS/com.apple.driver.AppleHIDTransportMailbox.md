## com.apple.driver.AppleHIDTransportMailbox

> `com.apple.driver.AppleHIDTransportMailbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x16420` | `0x18058` | **`+0x1c38`** |
| `__TEXT.__cstring` | `0x2de9` | `0x33cc` | **`+0x5e3`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x440` | **`+0x440`** |
| `__DATA_CONST.__const` | `0x11d8` | `0x13d8` | **`+0x200`** |
| `__DATA_CONST.__auth_got` | `0x1c8` | `0x220` | **`+0x58`** |
| `__TEXT.__const` | `0xda` | `0x11d` | **`+0x43`** |
| `__DATA_CONST.__kalloc_type` | `0x80` | `0xc0` | **`+0x40`** |
| `__DATA.__common` | `0x60` | `0x88` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xc0` | `0xd0` | **`+0x10`** |

### Other Changes

```diff

-10100.34.0.0.0
-  Functions: 333
+10100.38.1.0.0
+  Functions: 366

-  CStrings:  285
+  CStrings:  308
CStrings:
+ "1211111212221212111111121121211111111211211211211211211211211211211211211211211211211211211211211211211211211211211211211211211211222122212221222122212221222122212221222122212221222122212221222122221111112111211222"
+ "12111112122212121111121112211211111111111112221"
+ "121112111112"
+ "NonPollingFifoDrainEventSource"
+ "[0x%llx][%llx][%s::%s]: Creating polling FIFO '%s' on the first drainPollingFifo call"
+ "[0x%llx][%llx][%s::%s]: Deferring creation of polling FIFO '%s' until the first drainPollingFifo call"
+ "[0x%llx][%llx][%s::%s]: ERROR!! beginDrainPollingFifo: Failed to block polling FIFO %d (%s), ret=0x%08X (%s)"
+ "[0x%llx][%llx][%s::%s]: ERROR!! beginDrainPollingFifo: drain already active"
+ "[0x%llx][%llx][%s::%s]: ERROR!! beginDrainPollingFifo: polling FIFO %s not found"
+ "[0x%llx][%llx][%s::%s]: ERROR!! drain failed with ret=0x%08X (%s)"
+ "[0x%llx][%llx][%s::%s]: ERROR!! drainPollingFifo failed with ret=0x%08X (%s)"
+ "[0x%llx][%llx][%s::%s]: ERROR!! drainPollingFifo: FIFO %s requires blocking dequeue but beginDrainPollingFifo was not called"
+ "[0x%llx][%llx][%s::%s]: ERROR!! dropped frame for interface %u (reportSize=%u, writable=%u, total dropped=%u)"
+ "[0x%llx][%llx][%s::%s]: ERROR!! endDrainPollingFifo: no drain in progress"
+ "[0x%llx][%llx][%s::%s]: ERROR!! endDrainPollingFifo: polling FIFO %s not found"
+ "[0x%llx][%llx][%s::%s]: ERROR!! failed to allocate input report logging buffer (%u bytes)"
+ "[0x%llx][%llx][%s::%s]: ERROR!! invalid interfaceID %u"
+ "[0x%llx][%llx][%s::%s]: ERROR!! slow path triggered: %u bytes buffered exceeds %llu bytes available in output buffer. Per-entry drain is suboptimal; increase user-client output buffer to >= logging buffer capacity (%u bytes)."
+ "[0x%llx][%llx][%s::%s]: allocated input report logging buffer (%u bytes, watermark %u bytes)"
+ "[0x%llx][%llx][%s::%s]: beginDrainPollingFifo: FIFO %s drain started"
+ "[0x%llx][%llx][%s::%s]: beginDrainPollingFifo: FIFO %s is empty, skipping drain"
+ "[0x%llx][%llx][%s::%s]: drainPollingFifo: draining FIFO %d (%s), type=%d, maxDataSize=%llu"
+ "[0x%llx][%llx][%s::%s]: drained %u bytes, %u bytes remaining (slow path)"
+ "[0x%llx][%llx][%s::%s]: drained %u bytes, 0 bytes remaining"
+ "[0x%llx][%llx][%s::%s]: endDrainPollingFifo: FIFO %s drain ended"
+ "[0x%llx][%llx][%s::%s]: interface %u %s, mask=0x%08X"
+ "[0x%llx][%llx][%s::%s]: interface %u, reportSize=%u, entrySize=%u, readable=%u/%u"
+ "[0x%llx][%llx][%s::%s]: released input report logging buffer"
+ "[0x%llx][%llx][%s::%s]: watermark reached (readable=%u, watermark=%u), notifying user clients"
+ "[0x%llx][%llx][%s::%s]: wrote %llu bytes, %u bytes remaining"
+ "_nonPollingFifoDrainEventSource"
+ "beginDrainPollingFifo"
+ "disabled"
+ "drainInputReportLoggingBuffer"
+ "drainInputReportLoggingBufferEntries"
+ "drainPollingFifo"
+ "enableInputReportLogging"
+ "enabled"
+ "endDrainPollingFifo"
+ "site.NonPollingFifoDrainEventSource"
+ "writeToInputReportLoggingBuffer"
- "121111121222121211111112112121111111121121121121121121121121121121121121121121121121121121121121121121121121121121121121121121121122212221222122212221222122212221222122212221222122212221222122212222111111211121"
- "1211111212221212111112111221121111111111111222"
- "[0x%llx][%llx][%s::%s]: Creating polling FIFO '%s' on the first pollData call"
- "[0x%llx][%llx][%s::%s]: Deferring creation of polling FIFO '%s' until the first pollData call"
- "[0x%llx][%llx][%s::%s]: ERROR!! beginDrainFifo: Failed to block polling FIFO %d (%s), ret=0x%08X (%s)"
- "[0x%llx][%llx][%s::%s]: ERROR!! beginDrainFifo: drain already active"
- "[0x%llx][%llx][%s::%s]: ERROR!! beginDrainFifo: polling FIFO %s not found"
- "[0x%llx][%llx][%s::%s]: ERROR!! endDrainFifo: no drain in progress"
- "[0x%llx][%llx][%s::%s]: ERROR!! endDrainFifo: polling FIFO %s not found"
- "[0x%llx][%llx][%s::%s]: ERROR!! pollData failed with ret=0x%08X (%s)"
- "[0x%llx][%llx][%s::%s]: ERROR!! pollData: FIFO %s requires blocking dequeue but beginDrainFifo was not called"
- "[0x%llx][%llx][%s::%s]: beginDrainFifo: FIFO %s drain started"
- "[0x%llx][%llx][%s::%s]: beginDrainFifo: FIFO %s is empty, skipping drain"
- "[0x%llx][%llx][%s::%s]: endDrainFifo: FIFO %s drain ended"
- "[0x%llx][%llx][%s::%s]: pollData: draining FIFO %d (%s), type=%d, maxDataSize=%llu"
- "beginDrainFifo"
- "endDrainFifo"
- "pollData"
```
