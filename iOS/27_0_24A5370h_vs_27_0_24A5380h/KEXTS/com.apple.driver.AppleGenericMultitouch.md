## com.apple.driver.AppleGenericMultitouch

> `com.apple.driver.AppleGenericMultitouch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xa390` | `0xa61c` | **`+0x28c`** |
| `__TEXT.__os_log` | `0x2ae7` | `0x2b8c` | **`+0xa5`** |
| `__TEXT.__cstring` | `0x6ccc` | `0x6d1b` | **`+0x4f`** |
| `__TEXT_EXEC.__auth_stubs` | `0x370` | `0x380` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x1c0` | **`+0x8`** |

### Other Changes

```diff

-29.0.0.0.0
-  Functions: 244
+30.0.0.0.0
+  Functions: 247

-  CStrings:  323
+  CStrings:  326
CStrings:
+ "12111112122212121111112"
+ "IOReturn AppleGenericMultitouchDecider::helperStateChangedGated(AppleGenericMultitouchDeciderHelper *)"
+ "[Decider] Already launched, ignoring state change\n%s line %d"
+ "_commandGate"
+ "getWorkLoop()->addEventSource(_commandGate.get()) == 0"
- "121111121222121211111"
- "void AppleGenericMultitouchDecider::helperStateChanged(AppleGenericMultitouchDeciderHelper *)"
```
