## com.apple.driver.usb.AppleSynopsysUSB40XHCI

> `com.apple.driver.usb.AppleSynopsysUSB40XHCI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__kalloc_type` | `0x340` | `0x480` | **`+0x140`** |
| `__TEXT_EXEC.__text` | `0x63bc4` | `0x63c3c` | **`+0x78`** |
| `__TEXT.__cstring` | `0x2df7` | `0x2e01` | **`+0xa`** |

### Other Changes

```diff

-717.0.0.502.1
+717.0.1.0.0

-  CStrings:  178
+  CStrings:  180
Functions:
~ sub_fffffff00a698200 -> sub_fffffff00a687af0 : 40 -> 64
~ sub_fffffff00a6adfe4 -> sub_fffffff00a69d8ec : 40 -> 64
~ sub_fffffff00a6c1d00 -> sub_fffffff00a6b1620 : 40 -> 64
~ sub_fffffff00a6d6f48 -> sub_fffffff00a6c6880 : 40 -> 64
~ sub_fffffff00a6e6b78 -> sub_fffffff00a6d64c8 : 40 -> 64
CStrings:
+ "11"
+ "site.T"
```
