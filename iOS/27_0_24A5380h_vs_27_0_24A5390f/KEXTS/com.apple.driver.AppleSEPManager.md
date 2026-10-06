## com.apple.driver.AppleSEPManager

> `com.apple.driver.AppleSEPManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x41f24` | `0x42e78` | **`+0xf54`** |
| `__TEXT.__cstring` | `0x11527` | `0x1178f` | **`+0x268`** |
| `__TEXT_EXEC.__auth_stubs` | `0xb00` | `0xb20` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x580` | `0x590` | **`+0x10`** |

### Other Changes

```diff

-928.0.0.0.0
-  Functions: 2519
+928.0.2.0.0
+  Functions: 2544

-  CStrings:  1473
+  CStrings:  1493
CStrings:
+ "%s: SEP CoreAnalytics: Failed to send CA event %d\n"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AppleSEPManager/AppleSEPCommon.h"
+ "AppleSEPCommon.h"
+ "KdbgScope::~KdbgScope()"
+ "analytics.version == 1"
+ "begin_code & TRACE_FUNCTION_BEGIN"
+ "code_begin & TRACE_FUNCTION_BEGIN"
+ "code_end & TRACE_FUNCTION_END"
+ "com.apple.applesepos.storage.stats"
+ "dictData[0]"
+ "dictKey[0]"
+ "eventName"
+ "eventPayload"
+ "in_msg_p->length == sizeof(xart_analytics_t)"
+ "pwn"
+ "top_ < kMaxDepth"
+ "top_ > 0"
+ "void AppleSEPManager::_report_sandcat_pwn(uint32_t)"
+ "void KdbgScope::pop(uint32_t)"
+ "void KdbgScope::push(uint32_t)"
```
