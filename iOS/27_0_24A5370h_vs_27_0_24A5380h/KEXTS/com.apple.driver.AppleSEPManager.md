## com.apple.driver.AppleSEPManager

> `com.apple.driver.AppleSEPManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x41bf8` | `0x41f24` | **`+0x32c`** |
| `__TEXT.__cstring` | `0x11437` | `0x11527` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x9f40` | `0x9fc0` | **`+0x80`** |

### Other Changes

```diff

-927.0.0.0.0
-  Functions: 2515
+928.0.0.0.0
+  Functions: 2519

-  CStrings:  1470
+  CStrings:  1473
CStrings:
+ "12111112122212121111111111111"
+ "PE_i_can_has_debugger(NULL)"
+ "decode_info != nullptr"
+ "static IOReturn AppleSEPUserClient::DispatchGetTraceRecordState(AppleSEPUserClient *, void *, IOExternalMethodArguments *)"
+ "target->_asep->cpu_trace_memory != nullptr"
+ "virtual IOReturn AppleSEPUserClient::clientMemoryForType(uint32_t, IOOptionBits *, IOMemoryDescriptor **)"
- "1211111212221212111111111111"
- "IOReturn AppleSEPControl::cmsgCPU_TRACE_GET_STREAM_FILL(uint32_t *)"
- "nullptr != fill"
```
