## com.apple.driver.AppleHIDTransportMailbox

> `com.apple.driver.AppleHIDTransportMailbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x17c98` | `0x17698` | **`-0x600`** |
| `__TEXT.__cstring` | `0x3357` | `0x3130` | **`-0x227`** |
| `__TEXT_EXEC.__auth_stubs` | `0x420` | `0x410` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x210` | `0x208` | **`-0x8`** |

### Other Changes

```diff

-10100.39.0.0.0
+10100.41.0.0.0

-  CStrings:  307
+  CStrings:  296
Functions:
~ __ZN35AppleHIDTransportProtocolSCMMailbox24enableInputReportLoggingEhb -> sub_fffffff008f018dc : 956 -> 16
~ __ZN35AppleHIDTransportProtocolSCMMailbox29drainInputReportLoggingBufferEP18IOMemoryDescriptorPy -> sub_fffffff008f01a1c : 612 -> 16
CStrings:
- "[0x%llx][%llx][%s::%s]: ERROR!! drain failed with ret=0x%08X (%s)"
- "[0x%llx][%llx][%s::%s]: ERROR!! failed to allocate input report logging buffer (%u bytes)"
- "[0x%llx][%llx][%s::%s]: ERROR!! invalid interfaceID %u"
- "[0x%llx][%llx][%s::%s]: allocated input report logging buffer (%u bytes, watermark %u bytes)"
- "[0x%llx][%llx][%s::%s]: interface %u %s, mask=0x%08X"
- "[0x%llx][%llx][%s::%s]: released input report logging buffer"
- "[0x%llx][%llx][%s::%s]: wrote %llu bytes, %u bytes remaining"
- "disabled"
- "drainInputReportLoggingBuffer"
- "enableInputReportLogging"
- "enabled"
```
