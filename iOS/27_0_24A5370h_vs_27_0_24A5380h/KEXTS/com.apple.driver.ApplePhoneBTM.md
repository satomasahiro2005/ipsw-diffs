## com.apple.driver.ApplePhoneBTM

> `com.apple.driver.ApplePhoneBTM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x425b` | `0x41b3` | **`-0xa8`** |
| `__TEXT.__os_log` | `0x6c4` | `0x6fb` | **`+0x37`** |
| `__TEXT_EXEC.__text` | `0x197d4` | `0x197c4` | **`-0x10`** |

### Other Changes

```diff

-222.0.0.0.0
-  Functions: 1117
+223.0.2.0.0
+  Functions: 1114

-  CStrings:  544
+  CStrings:  543
CStrings:
+ "%s: _pmuDriver is NULL"
+ "%s: _pmuSecondaryDriver is NULL"
- "\"AppleBTM: %s:%u \" \"%s: _pmuDriver is NULL\" @%s:%d"
- "\"AppleBTM: %s:%u \" \"%s: _pmuSecondaryDriver is NULL\" @%s:%d"
- "IOReturn AppleBTMAONPMUAgent::configSampling(SampleRate)"
```
