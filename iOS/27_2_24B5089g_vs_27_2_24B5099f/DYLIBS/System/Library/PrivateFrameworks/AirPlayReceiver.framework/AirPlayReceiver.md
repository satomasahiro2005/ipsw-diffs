## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17c39c` | `0x17c4c8` | **`+0x12c`** |
| `__TEXT.__cstring` | `0x33201` | `0x332b3` | **`+0xb2`** |

### Other Changes

```diff

-1005.8.1.0.0
+1005.12.1.0.0

-  CStrings:  5200
+  CStrings:  5203
Functions:
~ _airplayReqProcessor_requestProcessCommand : 3796 -> 4096
CStrings:
+ "1005.12.1"
+ "[%{ptr}] Not the main session - Dropping now playing client\n"
+ "[%{ptr}] Not the main session - Dropping now playing info\n"
+ "[%{ptr}] Not the main session - Dropping playback state\n"
- "1005.8.1"
```
