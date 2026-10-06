## com.apple.driver.AppleSPU

> `com.apple.driver.AppleSPU`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x5dab` | `0x5dcf` | **`+0x24`** |
| `__TEXT_EXEC.__text` | `0x4a1c8` | `0x4a1e0` | **`+0x18`** |

### Other Changes

```diff

-1087.0.5.0.0
+1087.40.4.0.0

-  CStrings:  968
+  CStrings:  970
Functions:
~ __ZN17AppleSPUHIDDriver11handleStartEP9IOService : 4980 -> 5004
CStrings:
+ "TCCService"
+ "kTCCServiceMotionSensors"
```
