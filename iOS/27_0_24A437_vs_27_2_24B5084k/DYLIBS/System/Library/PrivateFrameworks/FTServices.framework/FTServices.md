## FTServices

> `/System/Library/PrivateFrameworks/FTServices.framework/FTServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46d6c` | `0x470f0` | **`+0x384`** |
| `__TEXT.__oslogstring` | `0x6d91` | `0x6eb1` | **`+0x120`** |
| `__TEXT.__cstring` | `0x45ba` | `0x46aa` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x4100` | `0x4180` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x25ac` | `0x25f0` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0x10e8` | `0x10f0` | **`+0x8`** |

### Other Changes

```diff

-2003.100.1.2.1
+2003.200.33.2.5

-  CStrings:  964
+  CStrings:  969
Functions:
~ sub_1c130431c -> sub_1c267731c : 84 -> 404
~ sub_1c1304370 -> sub_1c26774b0 : 152 -> 464
~ sub_1c1307cb4 -> sub_1c267af2c : 664 -> 676
~ sub_1c130834c -> sub_1c267b5d0 : 620 -> 876
CStrings:
+ "Cancelling message in the queue: %@ (obj: %p)"
+ "FTMessageDelivery Sending SOS for APS failure that received response code: (HTTP Status Code: %d)"
+ "FTMessageDelivery Sending SOS for request to url: (%@) that received response code: (HTTP Status Code: %d)"
+ "Received network state changed but not in airplane mode message (obj: %p)"
+ "Timer is cleared with current message=%@ (obj: %p)"
+ "Timer is invalidated with current message=%@ (obj: %p)"
+ "We're out of airplane mode, and we have a pending retry (obj: %p)"
- "FTMessageDelivery Sending SOS for APS failure that recieved response code: (HTTP Status Code: %d)"
- "FTMessageDelivery Sending SOS for request to url: (%@) that recieved response code: (HTTP Status Code: %d)"
```
