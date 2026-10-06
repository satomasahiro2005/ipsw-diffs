## com.apple.driver.corecapture

> `com.apple.driver.corecapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x27ecc` | `0x2809c` | **`+0x1d0`** |
| `__TEXT.__os_log` | `0x4680` | `0x47bc` | **`+0x13c`** |
| `__TEXT.__cstring` | `0x2082` | `0x2084` | **`+0x2`** |

### Other Changes

```diff

-1355.42.0.0.0
+1355.44.0.0.0

-  CStrings:  671
+  CStrings:  677
Functions:
~ __ZN9CCLogPipe13freeResourcesEv : 496 -> 288
~ __ZN9CCLogPipe25initWithOwnerNameCapacityEP9IOServicePKcS3_PK13CCPipeOptions : 1744 -> 1944
~ __ZN9CCLogPipe7mapPipeEy : 860 -> 968
~ __ZN9CCLogPipe19getMemoryDescriptorEy : 152 -> 516
CStrings:
+ "%s::%s() ring buffer allocation is deferred\n"
+ "%s::%s(): Log Size must be non-zero Owner:%s Pipe:%s\n"
+ "%s::%s(): Pipe size resolved to zero Owner:%s Pipe:%s\n"
+ "?"
+ "CCLogPipe::getMemoryDescriptor mapPipe(0) failed rv:0x%x map:%p owner:%s pipe:%s"
+ "CCLogPipe::getMemoryDescriptor mapPipe(1) failed rv:0x%x map:%p owner:%s pipe:%s"
```
