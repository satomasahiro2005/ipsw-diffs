## com.apple.driver.SecureRTBuddyProxy

> `com.apple.driver.SecureRTBuddyProxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x9a08` | `0x9cfc` | **`+0x2f4`** |
| `__DATA_CONST.__assert` | `—` | `0x168` | **`+0x168`** |
| `__TEXT.__cstring` | `0x11c7` | `0x128b` | **`+0xc4`** |
| `__DATA_CONST.__got` | `0x78` | `0x80` | **`+0x8`** |

### Other Changes

```diff

-778.40.9.0.0
-  Functions: 300
+778.40.11.0.0
+  Functions: 318

-  CStrings:  82
+  CStrings:  89
CStrings:
+ "NULL != tb_endpoint"
+ "SecureRTBuddyProxyEndpoint.cpp"
+ "TB_ERROR_SUCCESS == tberr"
+ "_pmAssertionCount == 0"
+ "_pmAssertionID != kIOPMUndefinedDriverAssertionID"
+ "endpointNumber < 64"
+ "tberr == TB_ERROR_SUCCESS"
```
