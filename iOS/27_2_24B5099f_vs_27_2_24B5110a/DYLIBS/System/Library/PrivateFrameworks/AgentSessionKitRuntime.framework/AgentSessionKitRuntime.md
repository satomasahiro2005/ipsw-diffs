## AgentSessionKitRuntime

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/AgentSessionKitRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e0a10` | `0x2e3aa0` | **`+0x3090`** |
| `__TEXT.__oslogstring` | `0x9663` | `0x9923` | **`+0x2c0`** |
| `__AUTH_CONST.__const` | `0x9b08` | `0x9ce8` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `0x18c68` | `0x18d88` | **`+0x120`** |
| `__TEXT.__swift5_capture` | `0x28d4` | `0x29b4` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0xa7a5` | `0xa881` | **`+0xdc`** |
| `__TEXT.__const` | `0x2d2ec` | `0x2d38c` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xe2b0` | `0xe328` | **`+0x78`** |
| `__DATA.__data` | `0x56a8` | `0x56d8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xa7ba` | `0xa7ea` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x12b10` | `0x12b38` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1618` | `0x1640` | **`+0x28`** |
| `__TEXT.__cstring` | `0x22ce` | `0x22ee` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x860` | `0x878` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x830c` | `0x8324` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x738` | `0x74c` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x25c0` | `0x25d0` | **`+0x10`** |

### Other Changes

```diff

-297.12.0.1.2
+297.12.4.0.0

-  Functions: 22596
+  Functions: 22662

-  CStrings:  790
+  CStrings:  798
CStrings:
+ "client set observation transaction held=%{bool,public}d"
+ "compactSession: skip (%{public}ld unrepresentable atoms) session=%{public}s"
+ "dropping event update with no client proxy: %{public}s"
+ "dropping session update with no client proxy: %{public}s"
+ "failed to send event update to client: %{public}@"
+ "failed to send session update to client: %{public}@"
+ "persistSupersededTimestamps: cannot decode %{public}ld live atoms site=%{public}s clocks=%{public}ld...%{public}ld session=%{public}s"
+ "persistSupersededTimestamps: cleared %{public}ld unrepresentable atoms site=%{public}s clocks=%{public}ld...%{public}ld session=%{public}s"
+ "persistSupersededTimestamps: failed to fetch existing timestamps for dedup, may insert duplicates: %{public}@"
+ "prepareSessionRecord: inline replacement off (%{public}ld unrepresentable atoms) session=%{public}s"
+ "remoteUnrepresentable"
- "failed to send event update to client: %@"
- "failed to send session update to client: %@"
- "persistSupersededTimestamps: failed to fetch existing timestamps for dedup, may insert duplicates: %@"
```
