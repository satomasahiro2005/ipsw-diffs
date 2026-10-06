## com.apple.driver.AppleInterruptControllerV3

> `com.apple.driver.AppleInterruptControllerV3`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x270` | **`+0x270`** |
| `__TEXT_EXEC.__text` | `0x4470` | `0x4478` | **`+0x8`** |

### Other Changes

```text
Functions:
~ _panic : 200 -> 224
~ __ZN26AppleInterruptControllerV317getAICBaseAddressEv : 372 -> 392
~ __ZN26AppleInterruptControllerV35startEP9IOService : 2912 -> 2896
~ __ZN26AppleInterruptControllerV326_aicPlatformQuiesceActionsEv : 808 -> 812
~ __ZN26AppleInterruptControllerV325_aicPlatformActiveActionsEv : 752 -> 740
~ __ZN26AppleInterruptControllerV326startInterruptTimestampingEj : 496 -> 492
~ __ZN26AppleInterruptControllerV325stopInterruptTimestampingEj : 308 -> 304
~ __ZN29AICInterruptTimestampFunction12getTimestampEv : 380 -> 376
```
