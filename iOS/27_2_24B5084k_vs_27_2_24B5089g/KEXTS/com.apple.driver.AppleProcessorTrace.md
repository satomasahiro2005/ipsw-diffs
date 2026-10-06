## com.apple.driver.AppleProcessorTrace

> `com.apple.driver.AppleProcessorTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x59a7` | `0x5988` | **`-0x1f`** |
| `__TEXT_EXEC.__text` | `0x3c5a0` | `0x3c58c` | **`-0x14`** |

### Other Changes

```diff

-130.40.6.0.0
+130.40.7.0.0

-  CStrings:  522
+  CStrings:  521
Functions:
~ __ZN26AppleProcessorTraceSession4initEN21apple_processor_trace16MethodConfigArgsE11OSSharedPtrI30AppleProcessorTraceEventSourceE : 2036 -> 2016
CStrings:
+ "absMaxThresh < chunks_size"
- "absMaxThresh < chunks.size()"
- "absMinThresh <= absMaxThresh"
```
