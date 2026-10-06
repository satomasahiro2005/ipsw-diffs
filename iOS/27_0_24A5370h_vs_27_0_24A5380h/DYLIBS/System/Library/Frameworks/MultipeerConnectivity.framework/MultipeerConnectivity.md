## MultipeerConnectivity

> `/System/Library/Frameworks/MultipeerConnectivity.framework/MultipeerConnectivity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e6f0` | `0x2e72c` | **`+0x3c`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-179.600.3.0.0
+180.100.1.0.0
Functions:
~ _micro -> _TracePrintNodes : 68 -> 692
~ _TracePrintNodes -> _micro : 692 -> 68
~ _gckSessionUpdateRoutingTable : 900 -> 920
~ _gckSessionChangeStateCList : 3156 -> 3176
~ _GCKSessionSendTo : 1312 -> 1316
~ _gckSessionFindNextHop : 136 -> 140
~ _gckSessionProcessDD : 2060 -> 2072
~ _gckSessionProcessLSA : 2692 -> 2724
~ _gckSessionHandleDeletedNode : 356 -> 364
~ __Z18AGPSessionRecvFromP4CAGPjP15GCKSessionEventi : 3648 -> 3608
CStrings:
+ "04:41:32"
+ "04:41:39"
+ "Jun 23 2026"
- "19:17:20"
- "19:17:32"
- "Jun  9 2026"
```
