## com.apple.driver.AppleCS42L79Audio

> `com.apple.driver.AppleCS42L79Audio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x11598` | `0x115e0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x1f92` | `0x1fc5` | **`+0x33`** |
| `__TEXT.__os_log` | `0x292f` | `0x2951` | **`+0x22`** |

### Other Changes

```diff

-1000.45.0.0.0
-  Functions: 382
+1010.2.0.0.0
+  Functions: 381

-  CStrings:  467
+  CStrings:  468
CStrings:
+ "Failed to HallStreaming enable:%d client:%#x"
+ "Failed to HallStreaming enable:%d client:%#x\n"
+ "Hall InRequest %s:%d client=%#x Success"
+ "enableHallStreaming inEnable:%d client:%#x mask:%#x->%#x"
+ "enableHallStreaming invalid client:%#x"
+ "enableHallStreaming invalid client:%#x\n"
- "Failed to HallStreaming enable:%d"
- "Failed to HallStreaming enable:%d\n"
- "Hall InRequest %s:%d param1=%d Success"
- "HallStreaming state already set enable:%d"
- "enableHallStreaming inEnable:%d"
```
