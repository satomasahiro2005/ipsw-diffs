## com.apple.driver.AppleOLYHAL

> `com.apple.driver.AppleOLYHAL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1c8b4` | `0x1d0b0` | **`+0x7fc`** |
| `__TEXT.__cstring` | `0x4860` | `0x4967` | **`+0x107`** |
| `__DATA_CONST.__const` | `0x1380` | `0x13a8` | **`+0x28`** |
| `__TEXT_EXEC.__auth_stubs` | `0x700` | `0x710` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x380` | `0x388` | **`+0x8`** |

### Other Changes

```diff

-530.5.0.0.0
-  Functions: 569
+530.7.0.0.0
+  Functions: 576

-  CStrings:  508
+  CStrings:  516
CStrings:
+ "\"%s:%u:\" \"completionTimeoutRecoveryInProgress\" @%s:%d"
+ "%s::%s: PCIe device is gone.\n"
+ "%s::%s: Spurious dext respawn timer expiration"
+ "%s::%s: WiFi dext launched in unallowable state\n"
+ "%s::%s: completion timeout recovery in progress: reset cannot finish until termination is complete\n"
+ "%s::%s: waiting for reset progress... current progress: %u\n"
+ "121111121222121211111111221211211122111121112212221111111"
+ "1211112211111222211112211112211"
+ "APB0_S"
+ "APB1_S"
+ "OLYHAL panic: %s[%x] = 0x%08x\n"
+ "mapbar0"
- "\"AppleBCMWLAN Dext didn't respawn within %u milliseconds\\n\" @%s:%d"
- "%s::%s: Still waiting for reset progress... current progress: %u\n"
- "1211111212221212111111112212112111221121112212221111111"
- "121111221111122221111221111221"
```
