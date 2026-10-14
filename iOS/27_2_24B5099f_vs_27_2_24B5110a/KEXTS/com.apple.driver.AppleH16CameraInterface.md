## com.apple.driver.AppleH16CameraInterface

> `com.apple.driver.AppleH16CameraInterface`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x9dc84` | `0x9dcf8` | **`+0x74`** |
| `__TEXT.__cstring` | `0x19f97` | `0x19ff7` | **`+0x60`** |
| `__TEXT.__os_log` | `0x15bb4` | `0x15c13` | **`+0x5f`** |

### Other Changes

```diff

-6.103.0.0.0
+6.104.0.0.0

-  CStrings:  2398
+  CStrings:  2399
Functions:
~ __ZN13AppleH16CamIn26processSharedMallocRequestEyyyPv : 1144 -> 1344
~ sub_fffffe0008e1d540 -> sub_fffffe0008e1f758 : 100 -> 104
~ sub_fffffe0008e1d5a4 -> sub_fffffe0008e1f7c0 : 100 -> 8
~ sub_fffffe0008e1d950 -> sub_fffffe0008e1fb10 : 136 -> 140
CStrings:
+ "1221211112112"
+ "AppleH16CamIn:%s - ERROR: ISP free request for address %#llx that it does not own - rejecting\n"
- "122121111211"
```
