## com.apple.driver.AppleSMCWirelessCharger

> `com.apple.driver.AppleSMCWirelessCharger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x113c4` | `0x11330` | **`-0x94`** |
| `__TEXT.__cstring` | `0x3848` | `0x380a` | **`-0x3e`** |
| `__TEXT.__const` | `0x60` | `0x8c` | **`+0x2c`** |

### Other Changes

```diff

-155.0.10.0.0
+155.2.2.0.0

-  CStrings:  468
+  CStrings:  467
Functions:
~ sub_fffffff00968d920 -> sub_fffffff0095f2760 : 68 -> 76
~ sub_fffffff00968d964 -> sub_fffffff0095f27ac : 68 -> 76
~ sub_fffffff00968dabc -> sub_fffffff0095f290c : 104 -> 112
~ sub_fffffff00968db24 -> sub_fffffff0095f297c : 5760 -> 5664
~ sub_fffffff0096941f0 -> sub_fffffff0095f8fe8 : 640 -> 644
~ sub_fffffff0096972c0 -> sub_fffffff0095fc0bc : 4236 -> 4360
~ sub_fffffff00969d854 -> sub_fffffff0096026cc : 2332 -> 2132
~ sub_fffffff00969e170 -> sub_fffffff009602f20 : 116 -> 112
CStrings:
+ "1211111212221212122122111222122111112121211122222111111111111111111111111111112222222222222222222222222222112211111211121111111111111111121"
+ "extended-otp-cal"
- "%s: Failed to set WAEQ to %d (ret=%d)\n"
- "121111121222121212212211122212211111212121112222211111111111111111111111111111222222222222222222222222222112211111211121111111111111111121"
- "chg-disable-inductive-fw-reload-on-crash"
```
