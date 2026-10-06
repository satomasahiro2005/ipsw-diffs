## com.apple.driver.usb.AppleUSBHub

> `com.apple.driver.usb.AppleUSBHub`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x3f0` | **`+0x3f0`** |
| `__TEXT_EXEC.__text` | `0x1b5cc` | `0x1b5b8` | **`-0x14`** |

### Other Changes

```diff

-1616.0.0.0.0
+1617.0.1.0.0
Functions:
~ sub_fffffff00a67c908 -> sub_fffffff00a710118 : 44 -> 40
~ sub_fffffff00a67d0b4 -> sub_fffffff00a7108c0 : 136 -> 140
~ sub_fffffff00a680b08 -> sub_fffffff00a714318 : 152 -> 164
~ ____ZN11AppleUSBHub21powerStateDidChangeToEmmP9IOService_block_invoke : 664 -> 668
~ ____ZN11AppleUSBHub32firstMatchNotificationThreadCallEP11thread_call_block_invoke : 3040 -> 3032
~ sub_fffffff00a6834d4 -> sub_fffffff00a716cec : 5004 -> 4996
~ __ZN11AppleUSBHub33allocateDownstreamBusCurrentGatedEP9IOServiceRjS2_ : 4532 -> 4500
~ __ZN11AppleUSBHub17interruptOccurredEPvij : 5408 -> 5400
~ sub_fffffff00a68813c -> sub_fffffff00a71b924 : 1552 -> 1556
~ sub_fffffff00a6888b8 -> sub_fffffff00a71c0a4 : 1340 -> 1344
~ __ZN17AppleUSB30HubPort12getPortSpeedEv : 1988 -> 2000
```
