## com.apple.driver.usb.AppleSynopsysUSBXHCI

> `com.apple.driver.usb.AppleSynopsysUSBXHCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__kalloc_type` | `0x4c0` | `0x600` | **`+0x140`** |
| `__TEXT_EXEC.__text` | `0x41528` | `0x415a0` | **`+0x78`** |
| `__TEXT_EXEC.__auth_stubs` | `0x5e0` | `0x5d0` | **`-0x10`** |
| `__TEXT.__cstring` | `0x43c8` | `0x43d2` | **`+0xa`** |
| `__DATA_CONST.__auth_got` | `0x2f0` | `0x2e8` | **`-0x8`** |

### Other Changes

```diff

-717.0.0.502.1
+717.0.1.0.0

-  CStrings:  275
+  CStrings:  277
Functions:
~ sub_fffffff00a6ed3b4 -> sub_fffffff00a6dcd14 : 40 -> 64
~ sub_fffffff00a6ef658 -> sub_fffffff00a6defd0 : 40 -> 64
~ sub_fffffff00a708ee0 -> sub_fffffff00a6f8870 : 40 -> 64
~ sub_fffffff00a718f24 -> sub_fffffff00a7088cc : 40 -> 64
~ sub_fffffff00a728654 -> sub_fffffff00a718014 : 40 -> 64
CStrings:
+ "11"
+ "site.T"
```
