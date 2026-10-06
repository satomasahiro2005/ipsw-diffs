## com.apple.driver.AppleM68Buttons

> `com.apple.driver.AppleM68Buttons`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1d0d0` | `0x1d1b0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x4eb6` | `0x4eff` | **`+0x49`** |

### Other Changes

```diff

-  CStrings:  629
+  CStrings:  632
Functions:
~ _DeserializeCredential : 1440 -> 1444
~ _LibSer_SEPControl_Deserialize : 356 -> 496
~ _LibSer_SEPControlResponse_Deserialize : 208 -> 288
CStrings:
+ "remaining >= cmdSize"
+ "remaining >= respSize"
+ "remaining >= sizeof(uint32_t)"
```
