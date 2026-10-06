## DriverKit

> `/System/Library/Frameworks/DriverKit.framework/DriverKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37dc4` | `0x37f74` | **`+0x1b0`** |

### Other Changes

```diff

-509.40.8.0.0
+509.40.10.0.0
Functions:
~ __ZN25IODataQueueDispatchSource4initEv : 172 -> 196
~ __ZThn24_N25IODataQueueDispatchSource4initEv : 32 -> 8
~ __ZN25IODataQueueDispatchSource17SendDataAvailableEv : 120 -> 324
~ __ZN25IODataQueueDispatchSource16SendDataServicedEv : 136 -> 324
~ __ZN25IODataQueueDispatchSource4freeEv : 228 -> 268
```
