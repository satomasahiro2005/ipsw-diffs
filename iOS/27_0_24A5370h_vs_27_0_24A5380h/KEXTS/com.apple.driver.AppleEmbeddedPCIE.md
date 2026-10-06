## com.apple.driver.AppleEmbeddedPCIE

> `com.apple.driver.AppleEmbeddedPCIE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x33898` | `0x33e00` | **`+0x568`** |
| `__TEXT.__cstring` | `0x7152` | `0x7277` | **`+0x125`** |
| `__DATA_CONST.__kalloc_type` | `0x280` | `0x300` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x2c98` | `0x2cb8` | **`+0x20`** |

### Other Changes

```diff

-1042.0.0.0.0
-  Functions: 504
+1042.0.2.0.0
+  Functions: 507

-  CStrings:  672
+  CStrings:  681
CStrings:
+ "1121"
+ "AppleEmbeddedPCIEUserClient.cpp"
+ "IOReturn AppleEmbeddedPCIEUserClient::extLockPort(IOExternalMethodArguments *)"
+ "[%s()] duration argument must not exceed %u seconds\n"
+ "extLockPort"
+ "site.struct lockPortData"
+ "threadData != NULL"
+ "threadData->lock"
+ "thread_call_enter1(threadCall, threadData) != TRUE"
```
