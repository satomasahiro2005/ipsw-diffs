## com.apple.security.AKSAnalytics

> `com.apple.security.AKSAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x3c0` | **`+0x3c0`** |
| `__TEXT_EXEC.__text` | `0x4de8` | `0x4e68` | **`+0x80`** |
| `__TEXT.__cstring` | `0x8c30` | `0x8c8f` | **`+0x5f`** |
| `__DATA.__data` | `0x3270` | `0x32a0` | **`+0x30`** |

### Other Changes

```diff

-2369.0.0.0.7
+2383.0.6.0.1

-  CStrings:  1557
+  CStrings:  1561
Functions:
~ sub_fffffff0084f35e4 -> sub_fffffff0084fcbb4 : 444 -> 448
~ sub_fffffff0084f4d00 -> sub_fffffff0084fe2d4 : 156 -> 188
~ sub_fffffff0084f4f0c -> sub_fffffff0084fe500 : 712 -> 748
~ sub_fffffff0084f529c -> sub_fffffff0084fe8b4 : 168 -> 188
~ sub_fffffff0084f5384 -> sub_fffffff0084fe9b0 : 312 -> 308
~ sub_fffffff0084f5bd4 -> sub_fffffff0084ff1fc : 144 -> 140
~ sub_fffffff0084f5c64 -> sub_fffffff0084ff288 : 148 -> 180
~ sub_fffffff0084f5cf8 -> sub_fffffff0084ff33c : 332 -> 344
CStrings:
+ "19:45:32"
+ "Jun 18 2026"
+ "com.apple.acx_test_runner"
+ "com.apple.cameraispd"
+ "com.apple.usernotificationsd"
+ "com.apple.xctspawn"
- "22:59:26"
- "May 27 2026"
```
