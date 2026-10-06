## libusrtcp.dylib

> `/usr/lib/libusrtcp.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5aa20` | `0x5b420` | **`+0xa00`** |
| `__TEXT.__oslogstring` | `0xe618` | `0xe6be` | **`+0xa6`** |
| `__TEXT.__cstring` | `0x1a5e` | `0x1a8e` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x450` | `0x458` | **`+0x8`** |

### Other Changes

```diff

-6681.0.436.0.8
+6681.0.498.502.1

-  Functions: 329
-  Symbols:   653
-  CStrings:  1116
+  Functions: 333
+  Symbols:   657
+  CStrings:  1120
Symbols:
+ _rbbr_sender_utilizing_rwnd
+ _rbbr_update_win
+ _tcp_calc_rcv_window
+ _tcp_clear_recv_bg
+ _tcp_set_recv_bg
- _rbbr_apply_cruise_backoff
CStrings:
+ "%{public}s %{public}s recv_bg: cleared (was %{public}s)"
+ "%{public}s %{public}s recv_bg: reactive teardown (recv_bg_viable=%d algo_mismatch=%d active=%u desired=%d)"
+ "%{public}s %{public}s recv_bg: switching to %{public}s bg=%d recv_cc_algo=%u"
+ "%{public}s new CE count (%llu) can't be less than current CE count (%llu)OR newly ACKed (%llu) can't be less that current ACKed (%llu)"
+ "%{public}s new CE count (%llu) can't be less than current CE count (%llu)OR newly ACKed (%llu) can't be less that current ACKed (%llu), backtrace limit exceeded"
+ "%{public}s new CE count (%llu) can't be less than current CE count (%llu)OR newly ACKed (%llu) can't be less that current ACKed (%llu), dumping backtrace:%{public}s"
+ "%{public}s new CE count (%llu) can't be less than current CE count (%llu)OR newly ACKed (%llu) can't be less that current ACKed (%llu), no backtrace"
+ "tcp_clear_recv_bg"
+ "tcp_rbbr_init"
+ "tcp_rbbr_switch_to"
+ "tcp_set_recv_bg"
- "%{public}s %u packets were newly CE marked"
- "%{public}s already processed AccECN field/options for this ACK"
- "%{public}s new CE count (%u) can't be less than current CE count (%u)OR newly ACKed (%u) can't be less that current ACKed (%u)"
- "%{public}s new CE count (%u) can't be less than current CE count (%u)OR newly ACKed (%u) can't be less that current ACKed (%u), backtrace limit exceeded"
- "%{public}s new CE count (%u) can't be less than current CE count (%u)OR newly ACKed (%u) can't be less that current ACKed (%u), dumping backtrace:%{public}s"
- "%{public}s new CE count (%u) can't be less than current CE count (%u)OR newly ACKed (%u) can't be less that current ACKed (%u), no backtrace"
- "tcp_process_accecn"
```
