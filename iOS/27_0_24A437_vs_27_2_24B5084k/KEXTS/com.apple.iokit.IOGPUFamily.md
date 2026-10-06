## com.apple.iokit.IOGPUFamily

> `com.apple.iokit.IOGPUFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__os_log` | `0x52f6` | `0x535a` | **`+0x64`** |
| `__TEXT.__cstring` | `0x61b3` | `0x61ea` | **`+0x37`** |
| `__TEXT_EXEC.__text` | `0x437c0` | `0x437d4` | **`+0x14`** |

### Other Changes

```diff

-162.11.0.0.0
-  Functions: 2002
+162.13.0.0.0
+  Functions: 2003

-  CStrings:  921
+  CStrings:  923
CStrings:
+ "%s: promoting NoResources->NoMemory on workQueue %p: outstanding=%u throttled=%u prepareSeed=%u/%u\n"
+ "121111112121122222222221111222111222221111121112222111122212222122222221"
+ "void IOGPUScheduler::scheduleWorkqueue(IOGPUWorkQueue *)"
- "12111111212112222222222111122211122222111112111222222111122212222122222221"
```
