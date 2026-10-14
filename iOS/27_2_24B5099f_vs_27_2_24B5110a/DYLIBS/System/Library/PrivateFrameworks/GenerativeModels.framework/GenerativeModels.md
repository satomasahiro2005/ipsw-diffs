## GenerativeModels

> `/System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd50f8` | `0xd57bc` | **`+0x6c4`** |
| `__TEXT.__oslogstring` | `0x3443` | `0x35a3` | **`+0x160`** |
| `__AUTH_CONST.__auth_got` | `0x1708` | `0x1710` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x51f4` | `0x51ec` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x3410` | `0x3408` | **`-0x8`** |

### Other Changes

```diff

-297.12.0.1.2
+297.12.4.0.0

-  Functions: 6152
-  Symbols:   258
-  CStrings:  501
+  Functions: 6150
+  Symbols:   259
+  CStrings:  504
Symbols:
+ _MobileGestalt_get_deviceClassNumber
CStrings:
+ "isUseCaseAccessNotGrantedSecure: returning granted (false); device is exempt from Velvet Rope (rdar://181760475)"
+ "joinWaitlist: returning .accepted; device is exempt from Velvet Rope (rdar://181760475) for %{public}s"
+ "waitlistStatus: returning .accepted; device is exempt from Velvet Rope (rdar://181760475) for %{public}s"
```
