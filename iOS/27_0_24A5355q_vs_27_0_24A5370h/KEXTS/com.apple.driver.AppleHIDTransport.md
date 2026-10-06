## com.apple.driver.AppleHIDTransport

> `com.apple.driver.AppleHIDTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x8e0` | **`+0x8e0`** |
| `__TEXT_EXEC.__text` | `0x7bef4` | `0x7c178` | **`+0x284`** |
| `__DATA_CONST.__const` | `0x91f8` | `0x9278` | **`+0x80`** |
| `__TEXT.__cstring` | `0xc8e9` | `0xc8ff` | **`+0x16`** |

### Other Changes

```diff

-10100.34.0.0.0
-  Functions: 2222
+10100.38.1.0.0
+  Functions: 2234
CStrings:
+ "beginDrainPollingFifo"
+ "drainPollingFifo"
+ "endDrainPollingFifo"
- "beginDrainFifo"
- "endDrainFifo"
- "pollData"
```
