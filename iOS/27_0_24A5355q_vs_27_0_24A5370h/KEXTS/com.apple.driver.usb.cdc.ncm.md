## com.apple.driver.usb.cdc.ncm

> `com.apple.driver.usb.cdc.ncm`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x20d8` | `0x2870` | **`+0x798`** |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x5b0` | **`+0x5b0`** |
| `__TEXT_EXEC.__text` | `0xd15c` | `0xd6c4` | **`+0x568`** |
| `__TEXT.__cstring` | `0x2331` | `0x2414` | **`+0xe3`** |
| `__DATA_CONST.__kalloc_type` | `0x140` | `0x180` | **`+0x40`** |
| `__DATA.__common` | `0xd8` | `0x100` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x2b8` | `0x2d8` | **`+0x20`** |
| `__TEXT.__const` | `0xba` | `0xca` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x80` | `0x88` | **`+0x8`** |

### Other Changes

```diff

-391.0.0.0.0
-  Functions: 338
+394.0.0.0.0
+  Functions: 357

-  CStrings:  234
+  CStrings:  239
CStrings:
+ "%06lu.%06u [0x%llx][%s] %s::%s: too many consecutive IO errors (%u), not re-enqueueing\n"
+ "12111112122212121111111112222111211211121"
+ "1211111212221212111111122121111111112112112111221111211112111121111211112111121111211112111121111211112111121111211112111121111211112111112111112111112111112111112111112111112111112111112111112111112111112111112111112111112112222211221111122222222112111211222222222"
+ "AppleUSBHostNCMRestrictedEthernetInterface"
+ "anri"
+ "site.AppleUSBHostNCMRestrictedEthernetInterface"
- "121111121222121211111112212111111111211211211122111121111211112111121111211112111121111211112111121111211112111121111211112111121111211111211111211111211111211111211111211111211111211111211111211111211111211111211111211111211222211221111122222222112111211222222222"
```
