## com.apple.driver.AppleSEPManager

> `com.apple.driver.AppleSEPManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1178f` | `0x117ff` | **`+0x70`** |
| `__TEXT_EXEC.__text` | `0x44ce4` | `0x44d00` | **`+0x1c`** |

### Other Changes

```diff

-928.40.4.0.0
+928.40.6.0.0

-  CStrings:  1493
+  CStrings:  1494
Functions:
~ __ZN12AppleSEPXART22_handle_sep_driven_msgEPNS_11XARTMessageE : 2240 -> 2268
CStrings:
+ "AppleSEP:WARNING: Received unsupported SEP secure storage analytics version (%d), skipping\n"
+ "in_msg_p->length == analytics_payload_len"
+ "in_msg_p->length >= sizeof(analytics.version)"
- "analytics.version == 1"
- "in_msg_p->length == sizeof(xart_analytics_t)"
```
