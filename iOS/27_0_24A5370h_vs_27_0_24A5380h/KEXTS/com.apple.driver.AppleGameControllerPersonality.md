## com.apple.driver.AppleGameControllerPersonality

> `com.apple.driver.AppleGameControllerPersonality`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1a64` | `0x1d94` | **`+0x330`** |
| `__DATA_CONST.__const` | `0x1510` | `0x1388` | **`-0x188`** |
| `__TEXT.__os_log` | `0x76` | `0xc0` | **`+0x4a`** |
| `__TEXT.__cstring` | `0x22b` | `0x235` | **`+0xa`** |

### Other Changes

```diff

-14.0.17.0.0
-  Functions: 58
+14.0.19.0.0
+  Functions: 57

-  CStrings:  29
+  CStrings:  28
CStrings:
+ "AppleGCHIDUserEventDriver::handleStart(<IOHIDInterface %#010llx>)"
+ "AppleGCHIDUserEventDriver::probe(<IOHIDDevice %#010llx>)"
+ "AppleGCIOHIDEventDriverPropertyMerger"
+ "AppleGCIOHIDEventDriverPropertyMerger::probe(<IOHIDDevice %#010llx>)"
+ "Built-In"
+ "GameControllerCapabilities"
+ "GameControllerEligible"
+ "GameControllerSupport"
+ "GameControllerType"
+ "site.AppleGCIOHIDEventDriverPropertyMerger"
- "AppleGCHIDEventDummyService"
- "AppleGCHIDEventDummyService::probe()"
- "AppleGCHIDEventDummyService::probe() matched!"
- "AppleGCHIDUserEventDriver::probe()"
- "GameControllerSupportedHIDDevice"
- "GamepadHIDServiceSupport"
- "HIDRMOverride"
- "HIDServiceSupport"
- "Register"
- "com.apple."
- "site.AppleGCHIDEventDummyService"
```
