## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x4385c` | `0x43a5c` | **`+0x200`** |
| `__TEXT.__cstring` | `0x61ea` | `0x62b2` | **`+0xc8`** |
| `__TEXT.__os_log` | `0x535a` | `0x52f6` | **`-0x64`** |

### Other Changes

```diff

-162.14.0.0.0
+162.16.1.0.0

-  CStrings:  923
+  CStrings:  921
CStrings:
+ "\"IOGPU::systemPagingOff() timeout. %d threads still stuck. addCommandToTail_slow %u, waitForAllSubmitted %u, workQueuesDisabled %u, waitingOnResources %u, waitForStamp %u, wireMemory %u\\n\" @%s:%d"
+ "12111111212112222222222111122211122222111112111222222111122212222122222221"
+ "1211111212221212121111111212211121222221111112112211122111112122222222222222222222222222122212"
+ "IOGPU::systemPagingOff() timeout. %d threads still stuck. addCommandToTail_slow %u, waitForAllSubmitted %u, workQueuesDisabled %u, waitingOnResources %u, waitForStamp %u, wireMemory %u\n"
- "\"IOGPU::systemPagingOff() timeout. %d threads still stuck.\\n\" @%s:%d"
- "%s: promoting NoResources->NoMemory on workQueue %p: outstanding=%u throttled=%u prepareSeed=%u/%u\n"
- "121111112121122222222221111222111222221111121112222111122212222122222221"
- "121111121222121212111111121211121222221111112112211122111112122222222222222222222222222122212"
- "IOGPU::systemPagingOff() timeout. %d threads still stuck.\n"
- "void IOGPUScheduler::scheduleWorkqueue(IOGPUWorkQueue *)"
```
