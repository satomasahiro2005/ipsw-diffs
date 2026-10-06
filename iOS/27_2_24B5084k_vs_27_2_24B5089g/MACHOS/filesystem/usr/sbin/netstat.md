## netstat

> `/usr/sbin/netstat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xf8c1` | `0xf9da` | **`+0x119`** |
| `__TEXT.__text` | `0x1b728` | `0x1b7a8` | **`+0x80`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  2434
+  CStrings:  2442
Functions:
~ _print_droptap_stats : 4600 -> 4648
~ sub_100019e04 -> sub_100019e34 : 88 -> 104
~ _drop_description_str : 5440 -> 5488
~ sub_10001b76c -> sub_10001b7dc : 88 -> 104
CStrings:
+ "DROP_REASON_FSW_TX_FLOW_AOP_OFFLOAD"
+ "DROP_REASON_FSW_TX_FLOW_BAD_ID"
+ "DROP_REASON_FSW_TX_FLOW_TORN_DOWN"
+ "DROP_REASON_FSW_TX_FLOW_WRONG_PORT"
+ "Flowswitch Tx flow id mismatch"
+ "Flowswitch Tx flow torn down"
+ "Flowswitch Tx not allowed on offload flow"
+ "Flowswitch flow not owned by Tx nexus port"
```
