## com.apple.driver.AppleHIDTransport

> `com.apple.driver.AppleHIDTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x7c178` | `0x7c4ac` | **`+0x334`** |
| `__TEXT.__cstring` | `0xc8ff` | `0xc982` | **`+0x83`** |
| `__DATA_CONST.__const` | `0x9278` | `0x9288` | **`+0x10`** |
| `__TEXT.__const` | `0x2e3` | `0x2f3` | **`+0x10`** |
| `__TEXT_EXEC.__auth_stubs` | `0x8e0` | `0x8f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x470` | `0x478` | **`+0x8`** |

### Other Changes

```diff

-10100.38.1.0.0
-  Functions: 2234
+10100.39.0.0.0
+  Functions: 2236

-  CStrings:  1522
+  CStrings:  1527
CStrings:
+ "121111121222121211111211122112111111"
+ "HIDContinuousRecorder"
+ "InputReportLogging"
+ "InputReportLoggingBufferMaxUsagePercent"
+ "InputReportLoggingDroppedFrames"
+ "_hcrEventLogger"
- "1211111212221212111112111221121111"
```
