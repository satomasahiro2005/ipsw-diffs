## libATCommandStudioDynamic.dylib

> `/usr/lib/libATCommandStudioDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2525` | `0x259d` | **`+0x78`** |
| `__TEXT.__const` | `0x1b00` | `0x1b20` | **`+0x20`** |

### Other Changes

```diff

-1576.0.0.0.0
+1580.0.0.0.0
CStrings:
+ "Client: [%{public}s], invalid fTransport at time of initialization"
+ "Client: [%{public}s], invalid fTransport when handling indication"
+ "Client: [%{public}s], invalid fTransport when handling response"
+ "Client: [%{public}s], invalid fTransport when sending disconnect message"
+ "Client: [%{public}s], invalid fTransport when sending internal error response for remote id"
+ "Client: [%{public}s], invalid fTransport when setting connected state"
+ "Client: [%{public}s], invalid fTransport when shutting down"
+ "Client: [%{public}s], invalid fTransport when triggering exit low power state"
+ "Client: [%{public}s], invalid fTransport when triggering low power state"
+ "[%{public}s]: Client created of type 0x%x"
+ "[%{public}s]: Client disconnect from modem; temp failure=%d; old state=%s"
+ "[%{public}s]: Client id received successfully: svc=0x%x id=%d; starting client"
+ "[%{public}s]: ERROR: Triggered enter-low-power but we are in state %s already!"
+ "[%{public}s]: Received client id (svc=0x%x id=%d), but client was manually released; releasing id now."
+ "[%{public}s]: handleStatus_sync(%s), current fQMuxState=%s"
- "Client: [%s], invalid fTransport at time of initialization"
- "Client: [%s], invalid fTransport when handling indication"
- "Client: [%s], invalid fTransport when handling response"
- "Client: [%s], invalid fTransport when sending disconnect message"
- "Client: [%s], invalid fTransport when sending internal error response for remote id"
- "Client: [%s], invalid fTransport when setting connected state"
- "Client: [%s], invalid fTransport when shutting down"
- "Client: [%s], invalid fTransport when triggering exit low power state"
- "Client: [%s], invalid fTransport when triggering low power state"
- "[%s]: Client created of type 0x%x"
- "[%s]: Client disconnect from modem; temp failure=%d; old state=%s"
- "[%s]: Client id received successfully: svc=0x%x id=%d; starting client"
- "[%s]: ERROR: Triggered enter-low-power but we are in state %s already!"
- "[%s]: Received client id (svc=0x%x id=%d), but client was manually released; releasing id now."
- "[%s]: handleStatus_sync(%s), current fQMuxState=%s"
```
